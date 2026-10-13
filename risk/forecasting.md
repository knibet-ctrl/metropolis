# Forecasting — What Works, Measured

> **Status: TIER 1** that expert political forecasting is poor and that
> measurable skill differences exist. **TIER 2** on how far superforecaster
> methods transfer outside tournament conditions. **TIER 3** on prediction
> market superiority.

> **The organising fact:** forecasting was an unmeasured profession until
> roughly 1984. Once someone started scoring it, the results were humiliating,
> and the improvements were mostly procedural rather than intellectual.

---

## Tetlock's Expert Political Judgment

Philip Tetlock began collecting forecasts in **1984** and published *Expert
Political Judgment: How Good Is It? How Can We Know?* in **2005**.

**The design, which is what makes it good:**
- **284 experts** — academics, government analysts, journalists, think-tankers.
  Median ~12 years' experience in their domain.
- Roughly **28,000 discrete predictions** over ~20 years. *(Counts up to 82,000+
  appear in the literature depending on how question-instances are
  individuated. The order of magnitude is what matters.)*
- **Questions with resolution criteria and deadlines.** Three-way forced choice:
  status quo persists / more of something / less of something.
- **Numeric probabilities required**, so scoring is possible.

**The results:**

| Finding | Detail |
|---|---|
| Average accuracy | Barely better than chance on three-way questions; **worse than simple extrapolation algorithms** on most |
| The famous line | Average expert did about as well as "a dart-throwing chimpanzee." Tetlock has said repeatedly this is overquoted and understates the nuance |
| Calibration | Badly overconfident. Events assigned ~80% happened well under 80% of the time |
| Horizon | **Skill decayed to noise beyond roughly 3–5 years** |
| Fame | **Negatively correlated with accuracy.** The most media-visible experts were the least accurate |
| Domain expertise | Beyond a low threshold, added almost nothing |

**That last pair is the finding people should sit with. More credentials did not
help. More airtime went with worse performance.** The plausible mechanism:
media rewards confident, simple, dramatic, ideologically coherent claims —
exactly the profile that forecasts badly.

### Foxes and hedgehogs

Tetlock's one large, reliable individual difference, borrowed from **Isaiah
Berlin's 1953 essay** *The Hedgehog and the Fox*, itself quoting Archilochus:
"The fox knows many things, but the hedgehog knows one big thing."

| | Hedgehog | Fox |
|---|---|---|
| Cognitive style | One organising theory, applied everywhere | Many partial models, no master theory |
| Language | "Moreover," "furthermore" — accumulating evidence for a thesis | "However," "on the other hand" — aggregating tensions |
| Confidence | High, stable | Moderate, moves with evidence |
| Updating | Reluctant; explains away misses | Frequent, incremental |
| Accuracy | **Worse**, and worse the more famous | **Better**, consistently |
| Media appeal | **High.** Clear, quotable, decisive | Low. Hedged, boring, unbookable |

**The mechanism is not that hedgehogs are stupid.** It is that a strong prior
theory is a machine for explaining away disconfirming evidence, and it makes
extreme forecasts. Extreme forecasts are heavily punished by proper scoring
rules when wrong.

---

## Brier scores — the arithmetic

**Glenn W. Brier, 1950**, *Monthly Weather Review*. A **proper scoring rule**:
your expected score is optimised by reporting your true belief. You cannot game
it by hedging or by exaggerating.

$$BS = \frac{1}{N}\sum_{i=1}^{N}(f_i - o_i)^2$$

where $f_i$ is the forecast probability and $o_i$ is 1 if the event happened,
0 if not. **Lower is better. 0 is perfect, 0.25 is "always said 50%", 1.0 is
confidently wrong every time.**

### Single-forecast intuition

| Forecast | Outcome | Score | Reading |
|---|---|---|---|
| 0.90 | Happened | 0.01 | Confident and right — excellent |
| 0.50 | Either | 0.25 | The no-information baseline |
| 0.90 | Didn't happen | **0.81** | Confident and wrong — catastrophic |
| 0.10 | Happened | 0.81 | Same |
| 0.99 | Didn't happen | **0.98** | Near-maximum penalty |

**Note the asymmetry that makes the rule work.** Moving from 0.5 to 0.9 gains
you 0.24 when right and costs you 0.56 when wrong. **Confidence is expensive.
This is precisely why hedgehogs score badly.**

### Full worked example

Five forecasts from one person:

| # | Forecast | Outcome | $(f-o)^2$ |
|---|---|---|---|
| 1 | 0.90 | 1 | 0.0100 |
| 2 | 0.75 | 1 | 0.0625 |
| 3 | 0.60 | 0 | 0.3600 |
| 4 | 0.30 | 0 | 0.0900 |
| 5 | 0.05 | 0 | 0.0025 |
| | | **Sum** | **0.5250** |

$$BS = 0.5250 / 5 = \mathbf{0.105}$$

**Is that good? A raw Brier score means nothing without a baseline.** Two
baselines:

- **Always say 50%:** every score is 0.25, so BS = **0.25**.
- **Climatology** — always predict the observed base rate. Here 2 of 5 events
  happened, so always forecast 0.40:
  - Events that happened (2): $(0.40-1)^2 = 0.36$ each → 0.72
  - Events that didn't (3): $(0.40-0)^2 = 0.16$ each → 0.48
  - Total 1.20, BS = **0.24**

**Brier Skill Score** relative to climatology:

$$BSS = 1 - \frac{0.105}{0.24} = \mathbf{0.5625}$$

**56% better than knowing nothing but the base rate.** That is a strong
forecaster. **Always report the skill score, never the raw Brier.** A Brier of
0.05 on questions where the answer is "no" 97% of the time is worse than
useless — climatology would score 0.029.

### Murphy's decomposition (1973)

$$BS = \underbrace{\text{Reliability}}_{\text{calibration}} - \underbrace{\text{Resolution}}_{\text{discrimination}} + \underbrace{\text{Uncertainty}}_{\text{difficulty}}$$

**This separates two independent virtues:**
- **Calibration** — when you say 70%, does it happen 70% of the time? *Easy to
  achieve: just say the base rate every time.*
- **Resolution** — do you say different numbers for different questions, and are
  the different numbers right? *This is where actual skill lives.*

**A perfectly calibrated forecaster with zero resolution is worthless.** Anyone
selling you calibration alone is selling you half the product.

---

## The Good Judgment Project

**IARPA's ACE tournament, 2011–2015.** US intelligence community funded five
research teams to compete on ~500 geopolitical questions with a control group.
Tetlock and Barbara Mellers ran the Good Judgment Project.

| Result | Detail |
|---|---|
| GJP won every year | By margins large enough that IARPA dropped other teams |
| Superforecasters | Top ~2% of ~5,000 volunteers, identified after year one |
| Persistence | ~70% of superforecasters stayed in the top 2% the following year — **this is the finding that establishes skill rather than luck** |
| Teaming | Putting superforecasters on teams improved accuracy further, roughly 10–20% |
| Training | A one-hour probabilistic-reasoning tutorial improved accuracy by ~10%, persisting through the season |
| Aggregation | Extremised weighted averages of the crowd beat almost all individuals |
| vs. intelligence analysts | Tetlock reports superforecasters beat IC analysts with classified access by ~30%. **This is the single most-cited claim in the field and it is unverifiable — the comparison data is classified. Treat as reported, not established** |

### What superforecasters actually do differently

Behaviourally observed, not self-reported. **All of it is procedural. None of it
is genius.**

| Practice | Detail | Why it works |
|---|---|---|
| **Granular probabilities** | They use 23%, not "likely." Rounding superforecasters' answers to the nearest 10% measurably degraded accuracy; rounding to thirds degraded it a lot | Real information exists at that resolution |
| **Start with the base rate** | Explicit outside view first, then adjust | See base-rates.md |
| **Decompose** | Fermi-style breakdown into estimable sub-quantities | Errors partially cancel; assumptions become visible |
| **Update frequently and in small steps** | Many small revisions on news, not one big flip | Under-updating and over-updating are both punished; small frequent moves approximate Bayes |
| **Balance inside and outside views** | Neither pure | — |
| **No ideological commitment** | Foxes. They do not have a thesis to protect | Removes the main source of motivated reasoning |
| **Actively seek disconfirmation** | Read the other side's best case | Counteracts confirmation search |
| **Treat beliefs as testable hypotheses** | "Perpetual beta" — Tetlock's phrase | Errors become information rather than threats |
| **Comfortable with being wrong** | Growth-oriented, non-defensive | Necessary for the previous row |

**Tetlock's summary of the strongest single predictor: not intelligence, not
subject knowledge, but "perpetual beta" — the degree to which someone treats
their own beliefs as provisional.** *(Effect sizes here are correlational within
a self-selected volunteer sample; the causal claim is weaker than the popular
account suggests.)*

---

## Meehl's finding — simple models beat experts

**The most important result in this file and the least known.**

**Paul Meehl**, *Clinical versus Statistical Prediction* (1954). Compared expert
clinical judgement to simple actuarial formulas across ~20 studies. Formulas won
or tied nearly everywhere. Meehl called the subsequent reaction the most
uniformly confirmed and most resisted finding in psychology.

**Grove et al. (2000)** meta-analysed **136 studies** across medicine, psychology,
education, criminal justice and finance:

| Outcome | Approximate share of studies |
|---|---|
| Mechanical prediction clearly better | ~47% |
| Roughly equal | ~47% |
| **Clinical (expert) judgement better** | **~6%** |

**Robyn Dawes (1979)**, *"The Robust Beauty of Improper Linear Models"*: models
with **arbitrary unit weights** — just add up the standardised predictors, no
fitted coefficients — beat expert judgement too. **The experts' contribution is
identifying which variables matter. Their contribution to weighting and
integrating them is negative.**

**Why:** humans are inconsistent. Given the identical case twice, clinicians
give different answers. A formula has zero noise. **Most of the model's
advantage over the expert is not superior insight; it is the absence of
randomness.**

This connects directly to **Kahneman, Sibony and Sunstein, *Noise* (2021)**:
insurance underwriters shown the same case differed from each other by a median
of ~55% — management had guessed 10%. **Noise is measurable without any
psychological theory, which is why it is holding up better than most of the bias
literature.**

**The practical implication almost nobody acts on: if you make the same kind of
judgement repeatedly, write down a checklist with weights and follow it. It will
beat you.**

---

## Prediction markets

**The theory:** money aggregates dispersed information and punishes noise.

| Evidence for | Evidence against |
|---|---|
| **Iowa Electronic Markets** (running since 1988) beat contemporaneous polls in a large majority of week-ahead comparisons | Thin markets are easy to move. The 2012 Intrade "Romney whale" spent millions distorting prices |
| Markets aggregate faster than polls and update continuously | Legal restrictions (CFTC) kept US markets tiny and unrepresentative. Intrade shut down in 2013 |
| Corporate internal markets (HP, Google, Ford) beat internal official forecasts in published studies | Longshot bias: low-probability contracts are systematically overpriced |
| Metaculus and Polymarket have produced credible track records on many question classes | No good mechanism for long-horizon questions — capital is tied up, so time value dominates |
| Skin in the game selects for accuracy over time | Markets can be confidently wrong. Brexit traded ~25% Leave on the day; 2016 US election ~15–20% Trump |

**On the last row — be careful.** A 20% event happening is not a market failure;
20% events happen one time in five. **The correct test is calibration over many
events, not the outcome of one.** People who cite Brexit as proof markets fail
are committing exactly the error this notebook is about.

**Fair summary: prediction markets are roughly comparable to good forecaster
aggregation, better than polls at short horizons, and structurally limited by
liquidity and law rather than by theory.** They are not magic and the strong
efficient-markets framing oversells them.

---

## Where the popular story is wrong

| Popular claim | What's actually the case |
|---|---|
| "Experts are no better than a dart-throwing chimp" | Tetlock's own line, and he has spent twenty years saying it's overquoted. Experts beat chance on short horizons and beat novices; they lose to *simple algorithms* and to *their own overconfidence*, and they collapse past ~3 years |
| "Superforecasters are geniuses" | Intelligence was a weak predictor. Numeracy mattered somewhat. **Method and disposition mattered most, and the training effect (~10% from one hour) shows it's teachable** |
| "It's all luck" | 70% year-over-year persistence in the top 2% rules this out. Luck doesn't persist |
| "Being well calibrated is the goal" | Half the goal. Resolution is the other half, and a base-rate parrot is perfectly calibrated and useless. Murphy's decomposition, 1973 |
| "A Brier score of 0.15 is good" | Meaningless without the climatology baseline. On easy questions it's terrible |
| "Prediction markets were wrong about Brexit/Trump" | They said ~20%. Twenty percent events happen. Judging a probabilistic forecast by one outcome is *resulting* |
| "Nate Silver got 2016 wrong" | FiveThirtyEight gave Trump ~29% on election day, well above other models. That was arguably the *best* published forecast, and it was pilloried for it |
| "More information improves forecasts" | Beyond a modest threshold it mainly increases confidence. This has been shown repeatedly since Oskamp (1965) — clinicians given more case material got no more accurate and much more certain |
| "AI/big data has solved forecasting" | For stationary high-frequency problems with abundant labelled data, genuine gains. For geopolitical and one-off events the constraint is the absence of a reference class, and no model manufactures one |
| "Forecasting tournaments prove we can predict the future" | They prove we can predict *tournament questions* — resolvable in 1–12 months, well-specified, drawn from a known distribution. This is precisely Taleb's objection and it is a fair one |

---

## Open questions

- [ ] Does superforecaster skill transfer to questions with no clean resolution date or criteria — which is most real decisions? Untested, and the honest answer is probably "less than advertised."
- [ ] Is the ~30% superiority over intelligence analysts real? Unverifiable; the underlying data is classified. It is repeated everywhere as fact.
- [ ] Can the tournament methods handle tail risk, or are they structurally confined to the body of the distribution? Taleb's critique of Tetlock rests entirely on this and has never been properly adjudicated.
- [ ] Why has Meehl's finding been ignored for seventy years? Best hypothesis is professional identity plus liability, but that's a story, not evidence.
- [ ] What is the right aggregation rule for a crowd of forecasters? Extremised weighted averages beat simple means in GJP; the optimal extremisation parameter appears to be dataset-dependent, which is worrying.
- [ ] Do prediction markets fail at long horizons for fundamental reasons (cost of capital) or fixable ones (instrument design)? If fundamental, the most decision-relevant questions are the ones markets can't price.
- [ ] Should governments run public, scored forecasting tournaments on policy questions? The obvious objection — political incentive to avoid a record — is also the strongest argument for it.
