# What We Actually Know — The Confidence Ledger

> **The key file.** Everything in this notebook, sorted by how much weight it
> can bear. Read this before acting on anything else here, including this
> sentence.

**The tiers:**

- **TIER 1 — Established.** Multiple independent lines of evidence, or it is a
  theorem. Overturning it would require extraordinary evidence.
- **TIER 2 — Contested but tractable.** Serious people disagree; evidence is
  relevant; progress is possible.
- **TIER 3 — Speculative.** Coherent, unfalsified, weakly evidenced. Hold
  loosely.
- **TIER 4 — Unanswerable in principle, or malformed.** No procedure could
  settle it.

**Standing caveat: none of this was verified against sources. Figures are from
general knowledge. Directions of effect are more reliable than magnitudes, and
magnitudes are more reliable than the specific decimal places.**

---

## TIER 1 — Established

### Mathematics (these are theorems, not findings)

| Claim | Notes |
|---|---|
| **Expected value ≠ time-average growth for multiplicative processes** | The coin-flip example: +5% ensemble average, −5.13% time average. Both correct. This is arithmetic |
| **Any repeated positive probability of ruin gives ruin probability → 1** | $(1-p)^n \to 0$. 2% annual gives 54.5% thirty-year survival |
| **Kelly bet sizing maximises long-run growth; over-betting has a catastrophic asymmetry** | 60/40 edge: 20% is optimal (+2.01%/bet), 40% is approximately zero, 100% is −∞ |
| **Portfolio variance floors at $\rho\sigma^2$** | Diversification benefit is bounded by correlation. More positions cannot help once $\rho$ rises |
| **Bayes' theorem; posterior depends on the base rate** | 1% prevalence, 80% sensitivity, 9.6% false positive → 7.8% PPV |
| **P(A ∩ B) ≤ P(A). Always** | Yet the conjunction fallacy is reliably observed |
| **A "1-in-100-year" event has ~26% chance of occurring at least once in 30 years** | $1 - 0.99^{30}$ |
| **Brier is a proper scoring rule** | Honest reporting maximises expected score. Cannot be gamed |
| **Common-cause failure dominates redundancy calculations** | Two 1% components: $10^{-4}$ independent, but a 0.5% common cause makes the system 0.51% |
| **Queueing delay explodes near full utilisation** | 90%→95% utilisation roughly doubles wait |

### Empirical

| Claim | Evidence |
|---|---|
| **Expert political/economic forecasting is poor and decays to noise past ~3–5 years** | Tetlock, 284 experts, ~20 years |
| **Fame among forecasters correlates *negatively* with accuracy** | Same dataset. Robust and uncomfortable |
| **Measurable, persistent individual forecasting skill exists** | GJP: ~70% of superforecasters stayed in the top 2% year-over-year. Luck does not persist |
| **Brief probabilistic-reasoning training improves accuracy** | ~10% improvement from ~1 hour, persisting through a season |
| **Simple mechanical models beat expert judgement** | Meehl 1954; Grove et al. 2000 meta-analysis of 136 studies: experts better in ~6% of cases |
| **Even unit-weighted models beat experts** | Dawes 1979. Experts pick the variables well and combine them badly |
| **Human judgement is enormously noisy** | Underwriters differ from each other by ~55% median on identical cases. Judges likewise |
| **~9 in 10 large infrastructure projects run over budget, and this has not improved in 70 years** | Flyvbjerg 2002, 258 projects, 20 countries |
| **Rail overruns average ~45%; bridges/tunnels ~34%; roads ~20%** | Same dataset |
| **~0.5% of large projects come in on budget, on time and on benefits** | Flyvbjerg, 16,000+ projects |
| **Financial returns are not Gaussian; tails are far fatter** | 1987's −22.6% is a ~20σ event under Gaussian assumptions. Known since Mandelbrot 1963 |
| **Correlations rise sharply in crises** | ~0.2–0.3 calm, >0.8 in panic. Every calm-calibrated model understates crisis risk by construction |
| **Overconfidence in interval estimates is large and robust** | Alpert & Raiffa: 98% intervals contained the truth ~60% of the time |
| **Scope insensitivity** | $80/$78/$88 to save 2,000/20,000/200,000 birds |
| **Hindsight bias** | Fischhoff 1975. You cannot recover your prior uncertainty after learning the outcome |
| **Presentation format substantially changes reasoning quality** | Natural frequencies roughly triple physicians' correct diagnostic inferences |
| **A large fraction of pre-2015 social psychology has failed to replicate** | OSC 2015: ~36% of 100 studies. Camerer 2018: 13/21 |
| **Ego depletion does not replicate** | 23 labs, n≈2,141, d ≈ 0.04 |
| **Published nudge effects are ~6x larger than field-deployed effects** | 8.7pp vs 1.4pp across ~23 million people |
| **In nearly every documented disaster, someone inside warned** | Challenger, Columbia, Fukushima, Iraq. See the-control-group.md |

---

## TIER 2 — Contested but tractable

| Question | State of play |
|---|---|
| **Do superforecaster methods transfer outside tournaments?** | The methods are procedural and look general. But tournament questions have resolution dates and criteria, and most real decisions don't. **Untested where it matters most** |
| **Did superforecasters beat intelligence analysts by ~30%?** | Reported by Tetlock, repeated universally, **unverifiable** — the comparison data is classified |
| **Is project overrun bias or strategic misrepresentation?** | Flyvbjerg argues incentives. The 70-year flat line and the asymmetry support him. Probably both; the mix determines whether you train people or change contracts |
| **How much base-rate neglect survives natural-frequency framing?** | Gigerenzer says most dissolves; Kahneman's camp says a robust residue remains. No clean adjudication |
| **Loss aversion: universal, or a bounded phenomenon?** | Gal & Rucker 2018 challenged it seriously. List 2003 showed experienced traders show no endowment effect. Real in risky choice; contested in riskless |
| **Normal accidents vs High Reliability Organisations** | Perrow: structure sets a floor. HRO: aviation shows the floor is far lower than claimed. **Both have strong evidence and the dispute is unresolved** |
| **Risk compensation / Peltzman effect** | Strong version unsupported. Moderate version has domain-specific support. Magnitude disputed |
| **Do prediction markets beat expert aggregation?** | Comparable at short horizons; better than polls; structurally limited by liquidity and law. The strong efficiency claim is oversold |
| **Is antifragility a distinct category or a restatement of convexity?** | The precise version is options gamma. Whether the broader concept adds analytical content is genuinely arguable |
| **Does the ergodicity programme replace expected utility or just re-derive it?** | Numerically coincident with log utility in the standard cases. Peters says the derivation matters; mainstream economists say show me a novel prediction |
| **Does general debiasing training work?** | Weak evidence for general transfer; better evidence for domain-specific training and for changing the environment instead |
| **Are decision journals effective?** | No controlled trial. The components are evidenced. The whole is not |
| **How much of climate is forecastable?** | "Boundary conditions not initial conditions" is roughly right and is doing a lot of work. Aggregate warming is far better constrained than regional impacts |
| **Is Perrow's high-complexity/tight-coupling cell expanding?** | Software has put both properties into systems that had neither. Plausible and unmeasured |

---

## TIER 3 — Speculative

Hold loosely. Reasonable people hold these; nobody should be confident.

| Claim | Note |
|---|---|
| **Premortems increase generated causes by ~30%** | Traces to a single 1989 study, universally repeated, no modern replication I know of |
| **Barbell strategies are optimal under fat tails** | Theoretically appealing; requires correctly identifying a genuinely safe leg, which 2008 and 2022 both complicated |
| **The ~70% information threshold for reversible decisions** | Bezos's rule of thumb. Sensible, memorable, entirely unvalidated as a number |
| **Organisations drift toward Type 1 process for Type 2 decisions as they scale** | Plausible, widely observed anecdotally, not measured |
| **"Skin in the game" selects for forecasting accuracy over time** | Theoretically strong; the empirical record for prediction markets is mixed and thin |
| **Choice overload** | Meta-analytic mean near zero with high heterogeneity. Sometimes real, conditions unknown |
| **Implicit bias tests predict individual behaviour** | Low test-retest reliability; weak individual prediction |
| **Growth mindset interventions** | Real but tiny at scale (~0.03–0.05 GPA points) |
| **Any specific "black swan" probability estimate** | If it's outside the model, you cannot price it. Estimates of tail probabilities in fat-tailed domains are not stable |
| **AI improves forecasting on non-stationary questions** | Genuine gains where data is abundant and stationary. For one-off geopolitical events the constraint is reference-class absence, which models don't manufacture |

---

## TIER 4 — Unanswerable in principle, or malformed

| Question | Why it can't be settled |
|---|---|
| **"What's the probability of an unknown unknown?"** | If it's in your probability space it isn't unknown. The question is self-defeating |
| **"Was Y2K remediation worth it?"** | The counterfactual is unobservable and cross-country comparisons are confounded by legacy exposure. **Genuinely undecidable** |
| **"Was that a good decision?" judged from outcome alone** | Malformed. Decision quality and outcome quality are different variables in any noisy domain |
| **"How risky is this?"** with no specified loss, horizon, or holder | Not a question yet. Needs three parameters before it means anything |
| **"What's the probability of another 2008?"** | "Another 2008" is not a defined event with resolution criteria |
| **"When will AGI/fusion arrive?"** | No reference class. Forecast errors historically enormous in both directions. Not merely hard — the question lacks the structure that makes forecasting possible |
| **The true tail probability of a fat-tailed process from finite data** | The estimator does not converge. This is a mathematical limit, not a data limit |
| **Whether a specific unrealised risk was correctly managed** | Prevention paradox. Success and overreaction are observationally identical |

---

## The things people most commonly get wrong

Sorted roughly by how often the error appears and how much it costs.

| Belief | Reality |
|---|---|
| **"Maximise expected value"** | Correct only for additive, repeatable, ruin-free bets. Wrong for most consequential decisions. **The single most expensive error in the notebook** |
| **"Bad outcome = bad decision"** | *Resulting.* In noisy domains good decisions lose constantly. This destroys organisational learning faster than anything else |
| **"That was a black swan"** | Almost always a grey swan. The term requires that it was outside the model *and* rationalised afterwards. Used as an excuse, it enacts the thing it names |
| **"Our project is different"** | So was every project in the reference class. This has never once been evidence |
| **"Add a 20% contingency"** | Historical medians are far above that with long right tails. Elevator cables get 11x. Projects get 1.2x |
| **"1-in-100-year flood won't happen to me"** | ~26% over a 30-year mortgage, and the estimate is uncertain and probably non-stationary |
| **"A positive test means you probably have it"** | For rare conditions, most positives are false. 7.8% in the worked example |
| **"Diversification eliminates risk"** | Bounded by correlation, and correlation rises exactly when you need it. Most "diversified" portfolios are one bet in twenty costumes |
| **"Redundancy makes it safe"** | Only against independent failures. Ariane 5 had two computers and one bug. Fukushima had many generators and one basement |
| **"Thinking, Fast and Slow is settled science"** | Kahneman himself disavowed the priming chapter. Ego depletion, power posing, facial feedback, marshmallow test — all substantially or entirely down |
| **"Get more information before deciding"** | Past a modest threshold it raises confidence more than accuracy (Oskamp 1965). For reversible decisions it is usually the wrong move |
| **"Finding the edge is the hard part"** | A 70% edge sized at 90% of bankroll loses 24% per bet. A 60% edge sized at 20% gains 2%. **Sizing dominates edge** |
| **"Experts can't predict anything"** | Lazy. Weather, mortality, project overruns, aggregate behaviour and 1–12 month geopolitical questions are all measurably forecastable |
| **"Experts can predict things"** | Also wrong for long-horizon political and economic questions, which is what people usually mean |
| **"We stress-tested for that"** | Stress tests examine scenarios a committee imagined. Every major bank passed one shortly before 2008 |
| **"The operator made a mistake"** | Usually the last hole in the cheese. The other holes were cut in the boardroom years earlier |
| **"Nate Silver got 2016 wrong"** | He gave Trump ~29%, higher than anyone else. That was arguably the best published forecast and it was attacked for being right |
| **"Six sigma event"** | Means the model was wrong. Multi-sigma "events" occur every few years, which is the tell |
| **"Nobody saw it coming"** | In every case in the-control-group.md, somebody did, in writing, internally. The constraint was authority, not knowledge |

---

## Where the strongest convergences are

Independent methods reaching the same conclusion is the best available signal in
a soft domain. There are four here.

**1. Simple beats complex under uncertainty.** Meehl (clinical psychology,
1954), Dawes (improper linear models, 1979), Gigerenzer (fast-and-frugal
heuristics, 1990s), DeMiguel et al. (1/N portfolios beating 14 optimisation
models, 2009), and the general bias-variance decomposition in statistics.
**Five independent literatures, one conclusion: in low-signal environments,
complex models fit noise and simple rules win.**

**2. The outside view beats the inside view.** Kahneman/Tversky (cognitive,
1970s), Flyvbjerg (infrastructure outcome data, 2002–2023), Tetlock
(forecasting tournaments, 1984–2015), and the superforecaster behavioural
record. **Four independent routes.**

**3. Ruin is categorically different from loss.** Kelly (information theory,
1956), Peters (ergodicity economics, 2010s), Taleb (fat tails), classical
gambler's ruin, and the entire practice of insurance. **The mathematics and the
practice agree and mainstream expected-value reasoning is the outlier.**

**4. Warnings existed and were organisationally suppressed.** Challenger,
Columbia, Fukushima, Iraq WMD, 2008. **Different industries, different
countries, different decades, same failure shape.** *(Caveat: post-hoc
investigations are designed to find warnings, so survivorship is a real concern
here. But the specificity of the warnings — Boisjoly's July 1985 memo, TEPCO's
15.7 m study, INR's tube dissent — is hard to explain away.)*

---

## The one genuine unresolved conflict in this notebook

**Tetlock says forecasting is a trainable skill and you should measure it.
Taleb says forecasting is largely futile and you should build robustness
instead.** They are usually presented as opposed and they mostly talk past each
other.

| | Tetlock | Taleb |
|---|---|---|
| Question class | Resolvable in 1–12 months, well-specified, drawn from a known distribution | Tail events outside the model |
| Claim | Skill exists, is measurable, is trainable | Tail probabilities are not estimable from finite data |
| Both are right about | Their own question class | Their own question class |
| The real disagreement | **What fraction of consequential outcomes is in each class** | Same |

**They are not contradictory. They are complementary, and the practical
synthesis is: forecast the body, engineer for the tail.** Use Tetlock's methods
for the 90% of decisions with a reference class. Use Taleb's for the 10% that
can end you. **The hard part is classification, and nobody has a good procedure
for it.**

---

## Where to spend attention

Ranked by (evidence strength × practical leverage ÷ effort).

| Rank | Action | Why |
|---|---|---|
| 1 | **Always ask for the base rate first** | TIER 1 evidence, near-zero cost, largest single accuracy gain available |
| 2 | **Identify the absorbing barrier before every consequential decision** | Prevents the only error class you cannot recover from |
| 3 | **Size positions properly; cap any single exposure** | Sizing dominates edge, arithmetically |
| 4 | **Write down forecasts with dates and probabilities** | Without a record you cannot learn. Hindsight bias guarantees it |
| 5 | **Look for the hidden common factor across your "diversified" exposures** | Career, portfolio, supply chain. Usually one factor in several costumes |
| 6 | **Use a checklist or a simple model for repeated judgements** | Meehl. Seventy years of evidence and near-universal non-adoption |
| 7 | **Run a premortem before irreversible commitments** | Weak evidence, near-zero cost, high option value. Mostly it legitimises dissent |
| 8 | **Convert probability questions into natural frequencies** | Format effects are large and free |
| 9 | **Distinguish reversible from irreversible and change the process accordingly** | Robust to being wrong about probabilities, which is why it's usable |
| 10 | **Update in small increments on new evidence, frequently** | The observed superforecaster behaviour, and it's approximately Bayes |
