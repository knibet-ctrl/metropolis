# Expertise and Authority — When to Trust, and About What

> **Status: Tier 1 that expertise is domain-specific and conditional; Tier 1
> that experts are systematically overconfident in prediction; Tier 2 on how to
> tell good expert judgement from bad in advance.** The Kahneman-Klein
> conditions are the most useful result in this file and they are widely
> ignored, including by experts.

---

## The four questions, again

From the-questions.md, because everything below hangs on keeping them apart:

1. Is this person competent in their domain?
2. **Is the claim inside that domain?**
3. **Does the domain support expertise at all?**
4. Are their incentives aligned with telling you the truth?

**Most trust failures are (2) and (3), not (1).** People argue about credentials
when the credential is usually the least interesting variable.

---

## Kahneman and Klein: the conditions for real expertise

"Conditions for Intuitive Expertise: A Failure to Disagree" (*American
Psychologist*, 2009). **Two researchers with opposite priors — Klein studied
naturalistic expert intuition and admired it; Kahneman studied heuristics and
biases and distrusted it — sat down to find where they disagreed and largely
couldn't.** That process makes the conclusion unusually credible.

**Expertise develops only when both conditions hold:**
- **A high-validity environment** — stable, learnable regularities exist in the cues.
- **Adequate practice with rapid, unambiguous feedback** — you find out you were wrong, soon, clearly.

| Domain | Valid cues? | Fast clear feedback? | Real expertise? |
|---|---|---|---|
| Chess | Yes | Yes | **Yes** |
| Anaesthesiology | Yes | Yes (minutes) | **Yes** |
| Firefighting (structure) | Yes | Yes | **Yes** |
| Weather forecasting | Yes | Yes (24h, scored) | **Yes — and forecasters are among the best-calibrated professionals measured** |
| Bridge, poker | Partly | Yes, over volume | **Yes** |
| Radiology | Yes | **Often delayed or absent** | Partial. Intra-rater disagreement on re-reading the same films is substantial |
| Psychiatry (prognosis) | Weak | Slow, confounded | **Weak** |
| Clinical prediction of violence | Weak | Slow, censored (you don't observe the counterfactual) | **No** |
| Stock picking | Very weak | Noisy | **No** |
| Long-run political forecasting | Weak | Very slow | **No** |
| Wine judging | Contested | Poor | **Contested — judges show low test-retest reliability in blind trials (Hodgson, 2008)** |

**The awkward implication: the prestige of a field is uncorrelated with whether
it supports expertise.** Political commentary and macroeconomic forecasting are
high status and low validity. Weather forecasting is the reverse.

---

## Tetlock

### *Expert Political Judgment* (2005)

Twenty years, 284 experts (academics, government analysts, journalists),
roughly 28,000 probabilistic forecasts about political and economic events,
scored properly.

**Results:**
- **Average expert accuracy was barely better than chance** on the questions posed, and worse than simple extrapolation algorithms.
- Experts were **badly overconfident**: events they said had no chance happened ~15% of the time; events they said were certain failed to happen roughly as often.
- **Fame was inversely correlated with accuracy.** The more media appearances, the worse the forecasts.
- **Foxes beat hedgehogs.** Hedgehogs know One Big Thing and extend it everywhere; foxes hold many partial models and stitch. Fox performance was better and their confidence better calibrated. Hedgehogs made better television.
- Experts and non-experts converged: **domain knowledge helped up to a point and then stopped helping.**

*(Caveat worth stating: the questions were chosen for difficulty and short
horizons. Tetlock has been criticised for a question set biased against expert
advantage. The overconfidence finding is robust regardless of that.)*

### *Superforecasting* (2015, with Dan Gardner)

The IARPA Aggregative Contingent Estimation tournament (2011-2015). The Good
Judgment Project won by wide margins. The top ~2% — "superforecasters" —
substantially outperformed everyone else and improved year over year rather
than regressing to the mean, which is the key evidence that it is skill.

**What superforecasters do — and it is all learnable:**
- Start from base rates ("outside view") before considering specifics.
- Break questions into estimable components (Fermi decomposition).
- Update **frequently and in small increments** on new evidence.
- Use fine-grained probabilities (63%, not "likely").
- Actively seek disconfirming information and opposing arguments.
- Keep score and review errors.

**Training was effective.** A one-hour probabilistic-reasoning tutorial improved
accuracy measurably and persistently. **Teaming improved it further.**

*(The widely repeated claim that superforecasters beat intelligence analysts
with classified access by ~30% comes from Tetlock's account and press reporting
of a classified comparison. **Flag as needing verification** — it is one of the
most-quoted numbers in the genre and the underlying data are not public.)*

---

## Clinical versus statistical prediction

The oldest and most robust result in this file, and the most consistently
ignored.

- **Meehl (1954), *Clinical versus Statistical Prediction***: reviewed ~20 studies comparing expert clinical judgement with simple actuarial formulas. The formulas won or tied nearly every time. Meehl described the reaction from clinicians as ranging from indifference to outrage.
- **Grove et al. (2000)**, meta-analysis of 136 studies across medicine, psychology and education: mechanical prediction equalled or exceeded clinical prediction in about **94%** of comparisons.
- **Dawes (1979), "The robust beauty of improper linear models"**: even *randomly weighted* linear models beat expert judgement, because the experts' inconsistency costs more than the weights' imprecision. **The expert's main deficit is noise, not bias.**
- Kahneman, Sibony & Sunstein's *Noise* (2021) generalises this: the same judge, the same radiologist, the same underwriter gives different answers to the same case on different days.

**Why this hasn't changed practice:** professional identity, liability, the
"broken leg" objection (the clinician knows something the formula doesn't —
occasionally true, and empirically the clinician's overrides make things worse
on average), and the fact that formulas are humiliating to work under.

**The synthesis that actually works:** use the algorithm for the base estimate,
use the expert to identify inputs the algorithm can't see, and **do not let the
expert override the output on intuition.**

---

## Where expertise doesn't transfer: the Nobel disease

The purest natural experiment available. Take people whose competence in a
domain is beyond dispute, observe what happens when they speak outside it.

| Laureate | Field | Claim outside it |
|---|---|---|
| **Linus Pauling** (Chemistry 1954, Peace 1962) | Structural chemistry — arguably the greatest chemist of the century | Megadose vitamin C for colds and cancer. Trials were negative; he attacked the trialists. Did lasting damage to nutritional supplement discourse |
| **Kary Mullis** (Chemistry 1993, PCR) | Invented the polymerase chain reaction | HIV does not cause AIDS; astrology; climate denial; an account of meeting a glowing raccoon |
| **Luc Montagnier** (Medicine 2008, HIV) | Co-discovered HIV | DNA teleportation via electromagnetic signals in water; homeopathy; anti-vaccine claims |
| **William Shockley** (Physics 1956, transistor) | Semiconductor physics | Racial intelligence and voluntary sterilisation proposals |
| **Brian Josephson** (Physics 1973) | Josephson effect, at 22 | Telepathy, water memory |
| **James Watson** (Medicine 1962) | Structure of DNA | Repeated claims about race and intelligence; stripped of honorary titles in 2019 |

**This is not a list of stupid people.** It is evidence that **domain expertise
provides no protection outside the domain, and that the confidence it produces
travels even when the competence does not.** *(Selection caveat: there are
~1,000 laureates and this is a list of the memorable failures. The rate is
unknown and probably not high. The point is that the rate is not zero, which
is all it needs to be.)*

---

## Steelmanning deference to experts

The anti-expert position is currently fashionable and is mostly wrong. The
strongest case for deference:

- **You cannot check everything.** Division of cognitive labour is not a weakness; it is how a technological civilisation works. The alternative to trusting expertise is trusting something worse — usually a stranger with a strong opinion and no accountability.
- **The track record of expert consensus is very good in high-validity domains.** Structural engineering, aviation safety, vaccine efficacy, antibiotic pharmacology, satellite navigation. Millions of load-bearing predictions that come true daily and generate no anecdotes.
- **"Do your own research" is, empirically, worse.** The literature on lay information-seeking finds it typically means searching until you find agreement. *(Contested in size; the direction is consistent.)*
- **The reasoning-from-scratch alternative is a fantasy.** You are not going to derive vaccine safety from first principles. The realistic choice is *which* expertise to trust, not whether.
- **Expert consensus formed by independent routes is the strongest signal available to a non-expert.** When epidemiology, immunology, virology and clinical trials converge, that is much stronger than any one of them.

---

## When to discount an expert

Ranked, roughly, by how much diagnostic value each carries.

1. **The claim is outside the domain.** Highest-yield check by a wide margin. A virologist on viruses; a virologist on school closures, economics, or psychology of compliance — three different and much weaker claims.
2. **The domain fails the Kahneman-Klein conditions.** No fast feedback means no expertise, however senior the person.
3. **The expert is unfalsifiable.** Cannot state what would change their mind, or what their previous predictions were.
4. **There is no track record and no scoring.** Forecasting pundits are almost never scored. Weather forecasters always are. This difference explains their relative calibration entirely.
5. **Incentive misalignment.** Funding source, consulting income, institutional position, ideological identity. Not disqualifying — but the disclosure literature suggests disclosure doesn't fix it and can make it worse (Cain, Loewenstein & Moore, 2005: disclosure licensed advisors to give *more* biased advice).
6. **Extreme confidence on a hard question.** Calibrated experts hedge on hard questions. Certainty is a signal about the person, not about the world.
7. **They are famous for this opinion.** Tetlock's inverse relationship. Fame selects for memorable, unhedged, hedgehog-style claims.

---

## The consensus question, handled honestly

**"97% of scientists agree on climate change"** is the most-cited consensus
figure in public discourse and it is worth doing carefully, because it
illustrates the general problem.

- Cook et al. (2013) classified ~12,000 abstracts. About two-thirds expressed no position on attribution; of the third that did, ~97% endorsed human causation. **The 97% is a percentage of the position-taking minority**, which critics correctly note is not the same as 97% of scientists.
- Doran & Zimmerman (2009) surveyed earth scientists: ~97% of actively publishing climate scientists agreed.
- Anderegg et al. (2010) used publication and citation records and found similar.
- **The convergence across three quite different methods is the actual evidence.** The specific number is contested and it doesn't matter much; the underlying claim is well supported by the physical evidence independently of any survey.

**The general lesson: a consensus figure is a proxy for evidence, not evidence.
Ask how the consensus formed.** A consensus that formed because independent
methods converged (plate tectonics, common descent, greenhouse physics) is
worth a great deal. A consensus that formed because everyone read the same
three papers and nobody had an incentive to check (candidate genes, dietary
fat, ego depletion) is worth very little — and from outside, **the two look
identical.**

---

## The COVID control group

Necessary here because it is recent, contested, and shows all four failure
modes at once. **Tier labels applied deliberately.**

| Episode | What happened | Status |
|---|---|---|
| **Early mask guidance** | WHO and the US Surgeon General advised against public masking in February-March 2020, partly to preserve supply for healthcare workers | **Tier 1 on the facts.** Messaging traded honesty for behaviour management and spent credibility it could not get back. The failure is in (4): incentives |
| **Aerosol transmission** | Droplet/aerosol was governed by a 5-micron threshold traceable to a misreading of mid-century work (Wells, Langmuir). 239 scientists signed an open letter in July 2020; WHO's position shifted slowly | **Tier 1 that the threshold was wrong; Tier 2 on how much delay it caused.** A failure of an inherited convention nobody had re-derived |
| **Lab leak** | The February 2020 *Lancet* letter, organised by Peter Daszak with an undisclosed conflict of interest, characterised lab-origin hypotheses as conspiracy theory. Position later shifted to "plausible, unresolved" | **Origin remains Tier 2 / unresolved.** The *process* failure — a live hypothesis stigmatised via an undisclosed COI — is much better established than any origin claim |
| **Ioannidis's own forecasts** | March 2020 estimate that US deaths might be ~10,000; Santa Clara seroprevalence study criticised on specificity and recruitment | **Tier 1.** See the-replication-crisis.md. Being the world expert on how findings go wrong provided no protection |

**None of this supports "don't trust experts."** It supports: **check which of
the four questions is doing the work, and notice when a public health body is
optimising for behaviour rather than accuracy — because then it is not
reporting its beliefs.**

---

## Where the popular story is wrong

| Popular belief | Reality |
|---|---|
| "Experts are usually right" | In high-validity domains with feedback, yes, overwhelmingly. In prediction of complex social outcomes, barely better than chance (Tetlock) |
| "Credentials are what matter" | Credentials establish (1) of four. The other three do more work |
| "Follow the science" | Science yields conditional descriptions. Policy requires weighing values. The phrase launders the second as the first |
| "Do your own research" | Usually means searching until you find agreement. The realistic skill is choosing whom to trust, which is a different and learnable skill |
| "The smartest person in the room should decide" | Dawes: an inconsistent expert loses to a crude consistent formula. Noise, not stupidity, is the main enemy |
| "Consensus means it's settled" | Sometimes. Ask *how the consensus formed*: independent convergence versus shared inheritance |
| "Intelligence agencies / insiders know more" | Access to secret information helped less than probabilistic discipline in the ACE tournament, per Tetlock's account. **Verify this claim before repeating it** |
| "Peer disagreement means nobody knows" | Sometimes the disagreement is 97-3 and the 3 are getting equal airtime. False balance is a media production choice, not an epistemic state |

---

## Open questions

- [ ] Does the superforecaster-versus-analyst comparison hold up? It is repeated everywhere and the data are classified. **Do not repeat it without checking.**
- [ ] Do the Good Judgment training effects persist at 5-10 years, or decay like the reviewer-training effects in peer-review.md?
- [ ] Is there a reliable way for a non-expert to distinguish "consensus by convergence" from "consensus by inheritance"? I have offered heuristics, not a method. **This is the most practically important open question in the notebook.**
- [ ] Why has the clinical-versus-statistical result, robust since 1954, changed so little practice? Liability, identity, or something structural nobody has named?
- [ ] Does the Nobel disease have an elevated base rate versus matched non-laureate eminent scientists? Nobody has done the comparison, which is exactly the control-group failure this notebook keeps flagging.
- [ ] Are large language models a new form of the deference problem — fluent, confident, uncalibrated, and impossible to interrogate for track record? **Almost certainly yes, and this file has no answer for it.**
