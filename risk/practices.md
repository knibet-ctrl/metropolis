# Practices — What To Actually Do

> **Status: mixed and marked per item.** Ranked by evidence strength, not by
> how good they sound. Several widely promoted practices here are **TIER 3**
> and I say so rather than smuggling them in beside the solid ones.

> **The honest summary before you start: three things carry most of the value —
> ask for the base rate, name the absorbing barrier, and write forecasts down
> with dates. Everything else is a rounding error by comparison.**

---

## Ranked by evidence strength

| Rank | Practice | Tier | Effort | Why it's ranked here |
|---|---|---|---|---|
| 1 | **Ask for the base rate before anything else** | **1** | Minutes | Largest documented accuracy gain per unit effort in the whole field |
| 2 | **Name the absorbing barrier** | **1** (mathematically) | Minutes | The only error class with no recovery path |
| 3 | **Use a simple model or checklist for repeated judgements** | **1** | Hours once | Meehl 1954; Grove 2000. Experts lose in ~94% of comparisons |
| 4 | **Size the bet; cap any single exposure** | **1** | Minutes | Sizing dominates edge arithmetically. See decisions.md |
| 5 | **Record forecasts with probabilities and dates** | **1** for the components | Minutes each | Without a record, hindsight bias makes learning impossible |
| 6 | **Convert probabilities to natural frequencies** | **1** | Seconds | Format effects are large, free, and immediate |
| 7 | **Find the hidden common factor in your "diversified" exposures** | **1** | An hour | Career and portfolio both. Most people hold one bet several times |
| 8 | **Classify reversible vs irreversible, then set the process** | **2** | Minutes | Robust to your probability estimates being wrong — which is why it works |
| 9 | **Update in small increments, frequently** | **2** | Ongoing | Observed superforecaster behaviour; approximately Bayesian |
| 10 | **Premortem before irreversible commitments** | **3** | 30 minutes | Weak direct evidence; near-zero cost; legitimises dissent, which is the real mechanism |
| 11 | **Keep a decision journal** | **3** | 10 min/decision | No controlled trial exists. Components are sound. Do not oversell it |
| 12 | **Read the strongest opposing case before committing** | **3** | Hours | Sensible, hard to evidence, and easy to do performatively |

---

## The 2×2 — use this before any consequential decision

| | **Knowable** (a reference class exists) | **Unknowable** (no reference class) |
|---|---|---|
| **Reversible** | **DECIDE FAST.** ~70% of the information you wish you had. Optimise cycle time. Measure and iterate. *Failure mode: over-deliberating* | **RUN A CHEAP EXPERIMENT.** Small stake, real feedback, pre-committed kill criteria. *Failure mode: letting the experiment quietly become the commitment* |
| **Irreversible** | **DO THE WORK PROPERLY.** Reference-class forecast, premortem, external reviewer with no stake, explicit margin of safety. *Failure mode: inside-view analysis mistaken for rigour* | **BUY OPTIONALITY OR DON'T ACT.** Stage it, delay, buy information, or take a robust suboptimal choice. **Never optimise here.** *Failure mode: proceeding because a model produced a number* |

**Two rules for using it:**

1. **Classify before you analyse, not after.** The classification is much harder
   to game in advance.
2. **The best move in the bottom-right cell is usually to move the decision into
   a different cell** — make it smaller, make it staged, or buy a reversal
   mechanism. **Converting an irreversible decision into a reversible one is
   worth more than any amount of analysis of the irreversible version.**

---

## Decision journal template

Copy this. Fill it in **before** the outcome is known. That is the whole point.

```
DECISION RECORD
================================================================
Date:                      2026-09-01
Decision:                  [one sentence]
Type:                      [1 = irreversible / 2 = reversible]
Deadline for the decision: [date]

STATE
  Physical/emotional state: [tired? rushed? angry? hungry? under pressure?]
  Time pressure:            [real deadline / manufactured urgency?]
  Who benefits if I say yes: [including me]

THE SITUATION
  What is actually being decided:
  What is NOT being decided (scope boundary):

THE OUTSIDE VIEW
  Reference class:          [what similar cases am I drawing on?]
  n =                       [how many?]
  Base rate of success:     [%]
  Typical time/cost ratio:  [actual ÷ estimated, from the reference class]
  Where I claim to differ, and the EVIDENCE for it:

ALTERNATIVES CONSIDERED
  Option A:                 [chosen]  Why:
  Option B:                            Why rejected:
  Option C:                            Why rejected:
  Option "do nothing":                 Why rejected:

THE FORECAST  (this is the load-bearing section)
  I expect: ____________________________ with probability ____%
  By date:  ____________
  Secondary: ___________________________ with probability ____%

RUIN CHECK
  Absorbing barrier — what state ends the game:
  Maximum plausible loss (not expected — maximum):
  Can I survive that? [yes / no]
  If no, what changes to make the answer yes:
  Exposure size as % of total relevant capital:

CORRELATION CHECK
  What else do I hold that fails in the same state?

FALSIFICATION
  What would make me conclude I was wrong:
  By when would I expect to see that:
  Pre-committed exit trigger:

PREMORTEM (top 3 from the exercise)
  1.
  2.
  3.
  Mitigation for each:

REVIEW DATE: ____________
================================================================

--- FILLED IN AT REVIEW, NOT BEFORE ---
What happened:
Was the DECISION good, independent of the outcome? [yes/no + why]
Was the FORECAST calibrated? [Brier contribution]
What did I learn that generalises:
```

**Two rules that make it work rather than become a ritual:**

- **Never edit a past entry.** The value is entirely in the un-retouched record.
- **Review on a schedule, in batches, not when something goes wrong.** Reviewing
  only after bad outcomes trains you to be risk-averse rather than calibrated.

---

## How to make a calibrated forecast

Seven steps. This is the superforecaster procedure, compressed.

**1. Make the question resolvable.** A forecast without resolution criteria and
a date is an opinion. Rewrite until a neutral third party could score it.

> Bad: "Will the project succeed?"
> Good: "Will the migration be running in production for all customers by 31 March 2027?"

**2. Start with the outside view.** Find the reference class. State $n$. State
the base rate. **Write the base rate down before you think about this case.**
Anchoring works in your favour here.

**3. Decompose.** Break into sub-questions you can estimate.

> "Will we ship by Q1?" → P(design signed off by Nov) × P(build in 3 months | design done) × P(no reprioritisation)
> $0.7 \times 0.5 \times 0.8 = \mathbf{0.28}$

**Note what decomposition does: three individually optimistic-sounding numbers
produce 28%.** People asked directly say "60%." The multiplication is where the
honesty is.

**4. Adjust from the base rate, with reasons, in writing.** Each adjustment must
name the evidence and the direction. **Adjustments without stated evidence are
the inside view wearing a disguise.**

**5. Use granular numbers.** 27%, not "unlikely." Rounding superforecasters'
estimates to the nearest 10% measurably degraded their accuracy — the
information at that resolution is real.

**6. Check the extremes.** Would you take a bet at those odds, both ways? If you
said 90% but would not accept 9:1, your real number is lower.

**7. Set an update trigger.** What specific news would move you, and by how
much? **Deciding this in advance prevents both under-updating and dramatic
over-correction.**

### Translating words to numbers

Vague words are the Sherman Kent problem — his readers interpreted "serious
possibility" as anywhere from 20% to 80%. **Adopt a fixed table and publish it.**

| Word | Use it to mean |
|---|---|
| Almost certain | 93–99% |
| Very likely | 80–92% |
| Likely / probable | 60–79% |
| Roughly even | 45–55% |
| Unlikely | 20–39% |
| Very unlikely | 5–19% |
| Almost no chance | 1–5% |

**Never write "possible."** It is compatible with everything from 1% to 99% and
therefore carries zero information.

---

## Calibration self-test — run this now

**Part A — Interval calibration.** For each, give a **90% confidence interval**:
a low and a high value such that you are 90% confident the truth lies between
them. **Write both numbers down before scrolling.** You are allowed to be very
wide. Being wide is the point.

1. Length of the Nile, in kilometres
2. Year Mozart was born
3. Number of bones in an adult human body
4. Height of Mount Everest, in metres
5. Average Earth–Moon distance, in kilometres
6. Population of Australia in 2024, in millions
7. Year of the Chernobyl disaster
8. Speed of light in a vacuum, in km/s
9. Number of UN member states
10. Gestation period of an African elephant, in days

**Part B — Probability calibration.** For each statement, answer TRUE or FALSE
and give your confidence as a number **between 50% and 100%**. (Below 50% just
means you should flip your answer.)

1. The Great Wall of China is visible to the naked eye from the Moon.
2. Nassim Taleb co-authored a January 2020 note warning about the coronavirus.
3. Charles Perrow wrote *Normal Accidents* following Three Mile Island.
4. Bayes' theorem was published during Thomas Bayes's lifetime.
5. Amos Tversky shared the 2002 Nobel Memorial Prize with Kahneman.
6. Long-Term Capital Management had two Nobel laureates among its partners.
7. The Brier score is a proper scoring rule.
8. Knight and Keynes published their major works on uncertainty in the same year.
9. Ego depletion replicated successfully in a 23-lab preregistered study.
10. Onagawa nuclear plant was further from the 2011 epicentre than Fukushima Daiichi.

---

### Answers

**Part A:** 1. ~6,650 km · 2. 1756 · 3. 206 · 4. 8,849 m *(2020 joint
China–Nepal revision; 8,848 m previously — accept either)* · 5. ~384,400 km ·
6. ~27 million · 7. 1986 · 8. ~299,792 km/s · 9. 193 · 10. ~645 days (~22
months)

**Part B:** 1. **FALSE** · 2. **TRUE** · 3. **TRUE** · 4. **FALSE** (published
posthumously, 1763) · 5. **FALSE** (Tversky died in 1996; the prize is not
awarded posthumously) · 6. **TRUE** (Merton and Scholes) · 7. **TRUE** ·
8. **TRUE** (both 1921) · 9. **FALSE** (d ≈ 0.04, interval spanning zero) ·
10. **FALSE** (Onagawa was *closer*)

### Scoring Part A

**Count how many of your 10 intervals contained the true value.**

| Hits | Verdict |
|---|---|
| 9–10 | Well calibrated. Rare |
| 7–8 | Mildly overconfident. Better than most professionals |
| 5–6 | **Typical result.** Substantially overconfident |
| 0–4 | Severely overconfident. This is also common |

**The expected result if you were calibrated is 9.** Alpert and Raiffa's
subjects, asked for **98%** intervals, hit about **60%**. **The
overconfidence finding is not a laboratory curiosity — you have just
demonstrated it on yourself.**

**The fix is embarrassingly simple and it works: widen your intervals until they
feel absurd, then widen them again.** People asked to state their interval and
then *explicitly consider how it could be wrong* narrow the gap measurably.

### Scoring Part B — compute your Brier score

For each item: $f$ = your confidence expressed as a probability **for the answer
you gave**; $o = 1$ if you were right, $0$ if wrong. Score $= (f - o)^2$.

Worked example for one item — you answered TRUE at 80% confidence and were
**wrong**: $(0.80 - 0)^2 = \mathbf{0.64}$. Answered at 80% and were right:
$(0.80 - 1)^2 = \mathbf{0.04}$.

$$BS = \frac{1}{10}\sum (f_i - o_i)^2$$

| Brier | Reading |
|---|---|
| < 0.10 | Excellent — accurate *and* appropriately confident |
| 0.10–0.18 | Good |
| 0.18–0.25 | Adding little over guessing |
| **= 0.25** | **Exactly the score for answering 50% on everything** |
| > 0.25 | **You are confidently wrong. Worse than knowing nothing** |

**The diagnostic that matters:** if your accuracy was 70% but your average
confidence was 85%, you are overconfident by 15 points. **Subtract that
difference from every future estimate and re-test.** This crude correction is
most of what calibration training does, and it is why one hour of it produced
~10% accuracy gains in the Good Judgment Project.

---

## The premortem, as a 30-minute meeting

1. **(2 min)** Facilitator: *"It is [18 months from now]. This has failed —
   catastrophically, publicly, expensively. Write down why."*
2. **(5 min)** **Everyone writes silently and independently.** Non-negotiable.
   Discussion first destroys the exercise by anchoring on the senior voice.
3. **(10 min)** Round-robin, one item each, no debate, no defending. Junior
   people first.
4. **(10 min)** Cluster and rank by (probability × severity ÷ detectability).
5. **(3 min)** For the top three: assign an owner, a mitigation, and a **leading
   indicator** — the thing you would see *first* if this were starting to
   happen.

**Two failure modes to guard against:**
- **The theatre version.** Run, minuted, plan unchanged. If nothing in the plan
  changes, it was a ritual.
- **The seniority collapse.** If the most senior person speaks first, you have
  run an anchoring exercise. **The silent independent write is the entire
  mechanism.**

---

## The weekly and quarterly loop

| Cadence | Do this |
|---|---|
| **Per decision** | Journal entry. Base rate. Ruin check. Forecast with a date |
| **Weekly, 10 min** | Review open forecasts. Update any where new evidence arrived. Small increments |
| **Quarterly, 60 min** | Score everything that resolved. Compute Brier. Compare to climatology. **Look for systematic direction of error, not individual misses** |
| **Annually** | Read your entries from 12 months ago cold. Ask what you were *systematically* wrong about — timelines, magnitudes, other people's behaviour, or your own persistence |

**What to look for in the quarterly review — the direction of error, not the
size:**

| Pattern | Diagnosis | Fix |
|---|---|---|
| High-confidence forecasts wrong more often than low | Overconfidence | Shrink all estimates toward the base rate |
| Consistently late on timelines | Planning fallacy | Multiply by your own historical ratio, not by 1.2 |
| Right on direction, wrong on magnitude | Fine on discrimination, poor on scaling | Widen intervals; forecast ranges not points |
| All estimates cluster at 50% | No resolution — you are a base-rate parrot | Force yourself to differentiate. Calibration without resolution is worthless |
| Good on your domain, terrible outside it | Normal and healthy | Restrict your confident claims to the domain |

---

## Where the popular story is wrong

| Popular claim | What's actually the case |
|---|---|
| "Trust your gut" | Klein and Kahneman agreed the conditions in 2009: intuition is trustworthy only where the environment is **regular** and feedback is **fast and unambiguous**. Firefighting and chess qualify. Hiring, stock picking and strategy do not |
| "Think positive / visualise success" | Visualising outcomes is associated with *worse* results in several studies (Oettingen's work); visualising the *process* and the *obstacles* does better. The premortem is the applied version |
| "Gather all the facts before deciding" | Beyond a modest threshold this raises confidence more than accuracy (Oskamp 1965), and for reversible decisions it is straightforwardly the wrong move |
| "Keep a journal to feel more mindful about decisions" | The value is the un-retouched record versus hindsight bias. If you edit past entries you have destroyed the only mechanism it has |
| "Calibration training is a nice-to-have" | It is one of very few debiasing interventions with a measured effect (~10% from one hour, persisting through a season) |
| "Say 'possible' to be appropriately humble" | It carries zero information — compatible with 1% and 99%. Use a number and publish your word-to-number table |
| "Contingency of 20%" | Below the historical *minimum* in most project reference classes. Take contingency from the distribution, not from convention |
| "Review decisions when they go wrong" | Reviewing only after bad outcomes is *resulting* institutionalised, and it trains risk aversion rather than calibration. Review on a schedule |
| "Premortems are a brainstorm" | The independent silent write is the mechanism. A discussion-first premortem is an anchoring exercise with extra steps |

---

## Open questions

- [ ] Does keeping a decision journal actually improve decision quality, or only self-knowledge? Nobody has run the trial and it would be cheap to run.
- [ ] How long does calibration training last without refreshers? GJP showed persistence through one season. Beyond that, unknown.
- [ ] Does calibration on trivia questions (Part A above) transfer to calibration on domain judgements? Partially, at best. The transfer question is under-studied and it matters for whether this test is useful or merely humbling.
- [ ] What is the right review cadence? Weekly/quarterly here is convention, not evidence.
- [ ] Can the 2×2 be applied honestly by the person who wants the decision to go a particular way? Probably not. It may need an external classifier, which most people don't have.
- [ ] Is there a version of the premortem that survives a hostile or hierarchical culture? Anonymous written submission is the obvious candidate and I know of no evidence on it.
