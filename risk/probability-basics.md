# Probability — What the Number Actually Means

> **Status: TIER 1 on the mathematics, TIER 2 on the interpretation.** The
> algebra is not in dispute. What a probability *refers to* has been argued
> since the 1650s and is not resolved.

> **The practical claim of this file:** most probability errors in real life are
> not errors of calculation. They are errors of *conditioning* — people compute
> P(evidence | hypothesis) and report it as P(hypothesis | evidence). That one
> swap has sent innocent people to prison.

---

## Three things "70% chance" can mean

| Interpretation | Claim | Works well for | Breaks on |
|---|---|---|---|
| **Frequentist** | In the long run, 70% of cases like this turn out that way | Dice, insurance, manufacturing, weather | One-off events. "70% chance Iran signs a deal" has no long run |
| **Bayesian / subjective** | My degree of belief, coherent with my other beliefs, updatable by evidence | Unique events, forecasting, decision-making | Where does the prior come from? Two rational people can differ |
| **Propensity** | A physical disposition of the system itself | Radioactive decay, quantum events | Doesn't apply to elections or wars |

**Frequentism cannot price a one-off, and Bayesianism cannot tell you where to
start.** Both objections are real. Working forecasters are unapologetic
Bayesians who use frequencies as priors wherever a reference class exists,
which is the pragmatic settlement and not a philosophical resolution.

**A test that clarifies the difference:** ask a frequentist "what's the
probability the 1,000,000th digit of π is 7?" The digit is determinate; there's
no repeatable trial. A Bayesian says 0.1 without blinking, because it's a state
of knowledge, not a state of the world. **Probability is in the map, not the
territory** — that's the Bayesian thesis, and it's why it's the right frame for
forecasting.

---

## Bayes' theorem, fully worked

$$P(H \mid E) = \frac{P(E \mid H)\,P(H)}{P(E)}$$

Thomas Bayes, published posthumously 1763; independently and more usefully
developed by Pierre-Simon Laplace from 1774.

### The mammography example — do the arithmetic

Setup (the standard teaching numbers; real-world figures vary by age and
technology):

- Prevalence of breast cancer in women aged 40–50: **1%**
- Sensitivity — P(positive | cancer): **80%**
- False positive rate — P(positive | no cancer): **9.6%**

**A woman tests positive. What is the probability she has cancer?**

The intuitive answer most people give — including most doctors — is around
70–80%. Work it out with 10,000 women:

| Group | Count | Test positive | Test negative |
|---|---|---|---|
| Has cancer (1%) | 100 | 100 × 0.80 = **80** | 20 |
| No cancer (99%) | 9,900 | 9,900 × 0.096 = **950** | 8,950 |
| **Total** | 10,000 | **1,030** | 8,970 |

$$P(\text{cancer} \mid +) = \frac{80}{80 + 950} = \frac{80}{1030} = 0.0777$$

**7.8%.** Not 80%. **More than nine out of ten positive results are false
positives**, and the entire reason is the base rate — 99% of the women tested
did not have the disease, so even a small false-positive rate on a large group
swamps the true positives from a small one.

Gerd Gigerenzer and Ulrich Hoffrage (1995) gave this problem to physicians. In
the probability format, a small minority got it right — figures around 15% are
commonly cited. **Presented as natural frequencies — "80 out of 100 women with
cancer will test positive; 950 out of 9,900 without will also test positive" —
correct answers rose to roughly half.** *(Exact percentages vary across studies;
the direction and magnitude of the improvement is robust and has replicated.)*

**This is one of the most useful facts in the notebook, and it is not a fact
about bias. It is a fact about representation.** The same information in a
different format produces different reasoning. See biases.md.

### The same thing in odds form (faster)

Prior odds × likelihood ratio = posterior odds.

- Prior odds of cancer: 1 : 99
- Likelihood ratio: 0.80 / 0.096 = **8.33**
- Posterior odds: 8.33 : 99 → probability = 8.33 / 107.33 = **7.8%** ✓

**Learn the odds form.** It makes the key insight visible: a test with a
likelihood ratio of 8 moves you 8-fold, and 8-fold from 1% is still under 10%.
**Strong evidence applied to a weak prior yields a weak conclusion.**

---

## The prosecutor's fallacy — the same error, with a body count

**P(evidence | innocent) is not P(innocent | evidence).** Swapping them is the
prosecutor's fallacy.

### Worked example

A DNA profile matches. Random match probability: **1 in 1,000,000**. The
prosecutor says: "The chance the defendant is innocent is one in a million."

That is wrong. Suppose the suspect pool is a city of 5,000,000 adults.

- Expected innocent matches: 5,000,000 × (1/1,000,000) = **5**
- Guilty matches: **1**
- P(guilty | match) = 1 / 6 = **17%**

**17%, not 99.9999%.** The difference is entirely the prior — how many people
could plausibly have done it. *(Real cases involve other evidence which
sharpens the prior enormously; the point is that the match statistic alone does
not do the work claimed for it.)*

### Sally Clark

Convicted in 1999 of murdering two of her infant sons. Paediatrician **Sir Roy
Meadow** testified that the probability of two cot deaths in a family like hers
was **1 in 73 million** — obtained by squaring roughly 1 in 8,543.

Two independent errors:

1. **Independence assumed without justification.** Cot deaths within a family
   are plausibly correlated — shared genetics, environment, sleeping practices.
   Squaring is only valid under independence. The true figure for a second cot
   death is far higher.
2. **The prosecutor's fallacy.** The relevant comparison is not "how unlikely is
   double SIDS" but "how unlikely is double SIDS *versus* double infanticide."
   Double infanticide is also extremely rare. When the ratio is computed, the
   evidence points weakly toward natural causes, not away.

The **Royal Statistical Society** issued a public statement on the misuse of
statistics in the case (October 2001). Clark's conviction was quashed in 2003.
She died in 2007. **Two other women were convicted on similar reasoning.**

**This is not an abstract error. It is the base rate fallacy with a prison
sentence attached.**

---

## Conditional probability and where independence dies

$$P(A \cap B) = P(A) \cdot P(B) \quad \textbf{only if independent}$$

**Independence is an assumption, never an observation.** It is the most
frequently violated assumption in applied probability, and it always fails in
the same direction: things you assumed were independent turn out to be
correlated *in the bad state*.

### Worked example: why AAA tranches weren't AAA

100 mortgages, each with a 5% default probability. You hold a tranche that only
loses money if more than 20 default.

**Assuming independence:**
- Expected defaults: 100 × 0.05 = **5**
- Standard deviation: $\sqrt{100 \times 0.05 \times 0.95} = \sqrt{4.75} = 2.18$
- 20 defaults is $(20 - 5) / 2.18 = \textbf{6.9 standard deviations}$ out
- Probability: roughly **1 in 10 billion**. Comfortably AAA.

**With default correlation of ~0.3** (i.e. a common factor — a national housing
downturn — drives all of them):
- The distribution is no longer bell-shaped. It becomes heavily skewed with a
  fat right tail: most of the time almost nothing defaults, and occasionally
  30–40 default together.
- P(>20 defaults) rises from ~10⁻¹⁰ to the **low single-digit percent** range.
- That is a **downgrade of roughly eight orders of magnitude from a single
  parameter you cannot observe directly.**

**The entire 2008 structured-credit disaster is contained in that one
parameter.** See the-control-group.md on David X. Li's Gaussian copula.

**The general rule:** the correlation you estimate from calm data is not the
correlation that applies in a crisis. Correlations in equity markets that sit
around 0.2–0.3 in normal conditions rise above 0.8 in a panic. **Diversification
evaporates exactly when it is needed.**

---

## A 1-in-100 event vs a 1-in-100-year event

These are constantly confused and they are not the same claim.

- **A 1-in-100 event** = probability 1% *per trial*. Trials might be daily.
- **A 1-in-100-year event** = probability 1% *per year*. This is a *rate*, not a
  statement that it happens once a century.

**Arithmetic on the 1-in-100-year flood, assuming independence between years:**

| Window | P(at least one occurrence) | Calculation |
|---|---|---|
| 1 year | 1.0% | — |
| 10 years | **9.6%** | $1 - 0.99^{10}$ |
| 30 years (a mortgage) | **26.0%** | $1 - 0.99^{30} = 1 - 0.740$ |
| 50 years | **39.5%** | $1 - 0.99^{50}$ |
| 100 years | **63.4%** | $1 - 0.99^{100} = 1 - 0.366$ |

**Over the life of a 30-year mortgage there is roughly a one-in-four chance of
at least one "100-year flood."** Homeowners routinely hear "100-year flood" and
infer "won't happen to me."

Three further problems, all making it worse:

1. **The estimate itself is uncertain.** A "100-year" level derived from 40
   years of gauge data has enormous error bars. It might be a 30-year event.
2. **Non-stationarity.** The historical record assumes the underlying
   distribution is fixed. Under changing climate and changing land use
   (impervious surfaces, upstream development), it isn't.
3. **Spatial correlation.** "A 1-in-100-year flood" in each of twenty towns is
   not twenty independent events if one storm system causes all of them. This
   is what destroys insurers.

**A useful reframing for any recurring low-probability risk:** don't ask for the
annual probability. Ask **"what's the chance of at least one over my exposure
window?"** The number is usually much larger and much more decision-relevant.

---

## Where the popular story is wrong

| Popular claim | What's actually the case |
|---|---|
| "A positive test means you probably have it" | Only if the base rate is high relative to the false positive rate. For rare diseases, most positives are false. This is arithmetic, not a subtlety |
| "1-in-100-year event" means "once a century" | It's a 1% annual rate. ~26% over 30 years. And the estimate is itself uncertain and probably non-stationary |
| "The chance of that happening by coincidence is one in a million, so he's guilty" | Prosecutor's fallacy. Depends entirely on the size of the suspect pool. Sally Clark |
| "Probabilities of independent events multiply" | True, and *independence is almost never established*. Meadow's 1-in-73-million came from squaring a number he had no right to square |
| "Bayes' theorem is hard" | The odds form is one multiplication. What's hard is remembering to ask for the base rate |
| "Doctors are bad at statistics" | Partly. But Gigerenzer showed the *format* is doing most of the damage. Same doctors, natural frequencies, much better performance. Blame the representation first |
| "A 90% confidence interval means 90% chance the value is in there" | Only under the Bayesian (credible interval) reading. The frequentist confidence interval means something more awkward: 90% of intervals constructed this way contain the truth. Nearly everyone, including scientists, uses the Bayesian reading |
| "P(A and B) can be higher than P(A)" | Never. It is a theorem. Yet the conjunction fallacy shows people routinely rank it so — see biases.md |
| "Small probabilities are safe to ignore" | Only if the payoff is bounded. 0.1% of a survivable loss is noise; 0.1% of ruin, repeated, is certain death. See fat-tails.md |

---

## Open questions

- [ ] Is the Bayesian/frequentist dispute a real disagreement or a difference of application domain? Most working statisticians behave as pragmatists; the philosophers say the pragmatists are dodging.
- [ ] Where do priors come from for genuinely novel events? "Use a reference class" is the answer and it presupposes the thing that's missing.
- [ ] How much of documented base-rate neglect survives natural-frequency framing? Gigerenzer says most of it dissolves; Kahneman's side says a robust residue remains. This is unresolved and it matters for whether "debiasing" means training people or redesigning forms.
- [ ] Can default/loss correlation ever be estimated reliably ex ante, or is the crisis correlation structurally unobservable until the crisis? The honest answer may be the second, which would mean structured credit is unpriceable in principle.
- [ ] Should regulators require exposure-window probabilities ("26% over 30 years") instead of annual return periods for flood and seismic risk? The communication evidence says yes; nobody has done it at scale.
- [ ] Is there a good way to communicate a probability distribution to a non-technical decision-maker without it collapsing to a point estimate in their head? No known solution. Hurricane cone-of-uncertainty graphics are the best-studied case and they are still widely misread.
