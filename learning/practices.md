# Practices — What To Actually Do

> **Status: mixed and marked per item.** Ranked by evidence strength, not by
> how good they sound. Several widely promoted practices here are **TIER 3**
> and I say so rather than smuggling them in beside the solid ones.

> **The honest summary before you start: three things carry most of the value —
> retrieve instead of review, space the retrievals, and manufacture feedback in
> a domain that doesn't give it. Everything else is a rounding error by
> comparison.**

> **Standing caveat: written from general knowledge without source
> verification.**

---

## Ranked by evidence strength

| Rank | Practice | Tier | Effort | Why it's ranked here |
|---|---|---|---|---|
| 1 | **Replace review with retrieval** | **1** | None (it's a substitution) | g ≈ 0.5-0.6 over restudy, growing with delay. Largest free gain available |
| 2 | **Space the retrievals** | **1** | Planning only | 254-study meta-analysis. Costs nothing but a calendar |
| 3 | **Distrust the feeling of fluency** | **1** | Continuous | Prerequisite for 1 and 2 surviving contact with your preferences |
| 4 | **Check whether your domain permits valid intuition** | **1** | 5 minutes, once | Kahneman-Klein. Determines whether to trust yourself at all in this domain |
| 5 | **Manufacture feedback where none exists** | **2** | Substantial setup | Converts a no-expertise domain into a possible-expertise one. The highest-ceiling item here |
| 6 | **Worked examples first, then fade them** | **1** for novices | Low | Sweller & Cooper. **Reverses once you have schemas** — stop when it starts feeling redundant |
| 7 | **Interleave once basics are stable** | **1** for the effect, **2** for timing | Low, unpleasant | Large effects; the crossover point is unmapped, so use judgement |
| 8 | **Train the actual capability, not a proxy** | **1** | Varies | Transfer is rare. Everything else follows from this |
| 9 | **Self-explain while studying worked examples** | **2** | Low | Chi et al. Moderate effect, requires prior knowledge |
| 10 | **Pretest before instruction (guess, then learn)** | **2** | Minutes | Generation and pretesting effects. Counterintuitive, replicated, almost never used |
| 11 | **Get task-directed, not self-directed, feedback** | **1** for the danger, **2** for the fix | Depends on others | Over a third of feedback interventions harm. This is the mitigation |
| 12 | **Write down what you predicted before you find out** | **2** | Minutes | The only way to get calibration feedback. See risk/forecasting.md |
| 13 | **Teach it to someone** | **3** | High | The protégé effect. Mechanism (retrieval + generation) is sound; isolation is poor |
| 14 | **Sleep adequately near learning** | **2** direction, **3** magnitude | Free | Direction supported; popular claims outrun evidence |
| 15 | **Keep a learning log** | **3** | 10 min/session | No controlled trial. Components are sound. Do not oversell it |

---

## The protocol for learning something hard

A concrete sequence. It assumes months to years, not a weekend.

### Phase 0 — Diagnose the domain (do this first, it changes everything)

| Question | If yes | If no |
|---|---|---|
| **Is the environment regular?** Do stable cues exist to be learned? | Intuition is achievable. Volume of varied practice will pay | Do not aim for intuition. Aim for explicit rules, checklists and models. See risk/decisions.md |
| **Does the domain give fast, unambiguous feedback?** | Practise directly | **You must build the feedback loop before accumulating hours.** Otherwise you will get confident, not good |
| **Is there an established pedagogy — known-good models, a teaching tradition?** | Find it. Do not reinvent it | Expect a much slower rate and a much higher failure rate. Budget accordingly |
| **Do you have access to someone better than you?** | Use them for diagnosis, not encouragement | See "when no coach exists" below |

**If the answers are no, no, no, no — you are in a domain where twenty years
of experience produces one year of skill repeated twenty times.** Management,
investing, writing, and most of professional life sit here. The fix is
structural, not motivational.

### Phase 1 — Build the map (weeks)

1. **Get a syllabus, not a book.** Find how the domain is actually sequenced by
   people who teach it. Skipping this costs months.
2. **Study worked examples heavily.** Resist solving problems yourself at this
   stage — for novices, unguided problem-solving is among the least efficient
   uses of time (Sweller & Cooper, 1985; Kirschner, Sweller & Clark, 2006).
3. **Do not interleave yet.** Block until each element can be executed at all.
4. **Build a factual base deliberately.** You cannot reason with elements you
   cannot retrieve. This is the least fashionable instruction in the file and
   it follows directly from working memory limits.

### Phase 2 — Acquire (months)

1. **Convert everything into retrieval.** After reading a section, close it and
   write what you remember. Then check. **The checking is not the learning; the
   attempt is.**
2. **Space it.** See the schedule below.
3. **Start interleaving** once you can execute each element. Mix problem types
   within a session. It will feel worse and you will perform worse in the
   session. That is the expected signature.
4. **Attack the specific weak component.** Not the whole piece. Isolate the bar,
   the sub-step, the class of problem you get wrong, and drill that.
5. **Vary the surface context deliberately.** Same principle, different
   clothing. This is the only reliable route to transfer.

### Phase 3 — Refine (years)

1. **Work at the edge.** If you succeed comfortably, the task is too easy; if
   you fail entirely, too hard. Aim for effortful success.
2. **Increase the feedback resolution.** Record yourself, get the diff, compare
   against a known-good model line by line.
3. **Study your own errors as a dataset.** Categorise them. Most people have
   three or four recurring error types and never name them.
4. **Expect plateaus and treat them as diagnostic.** A plateau usually means
   the task has automatised at its current level, which means the difficulty
   must increase or the target must change.

---

## Spacing schedules

**The rule (Cepeda et al., 2008): the optimal gap is roughly 10-20% of the
interval you want to retain over.** The function is broad near the optimum, so
approximation is fine. Massing is what actually costs you.

### Manual schedule — for a body of material learned once

| Review | Timing after first learning |
|---|---|
| 1 | Same day, a few hours later |
| 2 | Next day |
| 3 | ~3 days |
| 4 | ~1 week |
| 5 | ~2-3 weeks |
| 6 | ~2 months |
| 7 | ~6 months |
| Then | Annually |

**Each review must be a retrieval attempt, not a reread.** A reread on this
schedule captures a fraction of the benefit.

### Algorithmic — for large volumes of discrete facts

Anki, or any SM-2 descendant. Notes on using it well:

| Rule | Reason |
|---|---|
| **Make your own cards** | The making is elaborative encoding. Shared decks lose most of the value |
| **One fact per card** | Multi-part cards produce partial retrieval, which the algorithm cannot score |
| **Cloze deletions over recognition** | Free recall beats recognition; multiple choice is the weakest format |
| **Cards must be answerable in <10 seconds** | Longer cards are essays and belong in a different practice |
| **Do the reviews daily or the schedule is meaningless** | The algorithm is a schedule, not a study method |
| **Cards are for facts, not for skill** | Vocabulary, anatomy, formulae, dates. Not for judgement, not for procedure |

**Honest limitation:** the specific parameters of SM-2 and its successors are
fitted heuristics, not derived from the spacing literature. **The spacing effect
is TIER 1; the particular algorithm is not.** Most of the benefit comes from
reviewing at increasing intervals at all.

---

## How to self-test properly

Most self-testing is recognition in disguise. Recognition is the weakest format
and produces the largest illusion of knowing.

| Bad | Good | Why |
|---|---|---|
| Reread and think "yes, I know this" | Close the book. Write the answer from blank | Recognition ≠ recall. The illusion is the failure mode |
| Multiple choice | Free recall, then check | Retrieval strength scales with retrieval difficulty |
| Test immediately after reading | Test after a delay | Immediate testing draws on working memory, not on the memory you care about |
| Test on the material's own organisation | Test on questions you generate, in a different order | Order-bound recall is a cue artefact |
| Test only what you're confident about | Test what you avoid | Avoidance is the diagnostic signal |
| Stop when you get it right once | Continue to spaced retrieval after success | Karpicke & Roediger (2008): dropping items after one success is what destroys retention |

**The blank-page test** is the cheapest high-value technique available: after a
study session, take a blank page and write everything you can recall about the
topic, unaided, in any order. Then compare against the source. The gap is your
actual state of knowledge. It takes ten minutes and it is uncomfortable, which
is why almost nobody does it.

---

## How to get feedback when no coach exists

**The hardest problem in self-directed learning, and the one that determines
whether hours convert into skill.** Ranked by quality.

| Method | Quality | Notes |
|---|---|---|
| **Objective ground truth** | Best | Tests that pass or fail. A chess engine. A closed-form answer. Take it wherever it exists |
| **Known-good model comparison** | Very good | Do the task, then compare against an expert's version of the same task line by line. Requires published exemplars, which most domains have and most learners ignore |
| **Delayed self-review** | Good | Do the work; wait long enough to lose authorial fluency; review as a stranger. The delay is doing the work |
| **Recording yourself** | Good | Removes the performer's perspective. Standard in music and sport; nearly unused in speaking, writing and teaching, where it would help most |
| **Prediction logs** | Good for judgement | Write the prediction and the reasoning before the outcome. The only way to get feedback in slow domains. See risk/forecasting.md |
| **Reverse-engineering** | Good | Take a finished expert product, reconstruct it from a summary, compare. Franklin's method with the *Spectator* essays is the canonical example |
| **Peer review from a non-expert** | Mixed | Good at detecting confusion, bad at diagnosing cause. Use it to locate problems, not to fix them |
| **Public exposure** | Mixed and slow | Real consequences, but noisy signal and long lag |
| **Praise from friends** | Worthless or negative | Self-directed feedback, which Kluger & DeNisi identify as the harmful category |

**The general principle: feedback quality is determined by how quickly and
unambiguously you learn you were wrong.** Everything else is secondary. If you
cannot construct a fast disconfirmation loop, you are not practising, you are
performing.

**Cross-reference: this is exactly leaders/ mechanism #1 (direct contact with
reality) at the level of an individual skill.** Ohno's circle, Borlaug in the
fields, and Yunus leaving the lecture theatre are the same move — arranging to
be corrected by something that does not care what you believe. The mechanism is
identical; only the scale differs.

---

## How to know if you're improving

**The problem: your subjective sense is unreliable and sometimes inverted.**

| Bad signal | Better signal |
|---|---|
| "It feels easier" | Could mean improvement, could mean automatisation at the same level, could mean you dropped the difficulty. Ambiguous |
| "I understood the lecture" | Comprehension during instruction is not retention after it |
| Recent performance | Highly variable. Single sessions are noise |
| "I've put in the hours" | Hours without feedback do not accumulate into skill |
| Confidence | Anti-diagnostic in low-validity domains |

| Good signal | Why |
|---|---|
| **Performance on a delayed unaided test** | The only direct measure of what you actually retained |
| **You can now solve problems you previously couldn't classify** | Movement from surface to deep representation (Chi et al. 1981). The clearest sign of real progress |
| **Your errors have changed category** | Beginners make different errors from intermediates. Same error rate, more advanced errors, is progress |
| **You notice things you previously didn't see** | Perceptual chunking. In chess, music, radiology and code review this is the primary observable |
| **Reduced time to the same standard** | Hard to fake, easy to measure |
| **Your predictions about your own performance get more accurate** | Calibration improving is itself a strong indicator, and it is what the risk/ notebook measures directly |

**Set a benchmark task early, before you know anything, and repeat it
periodically.** It should be too hard at the start. Without a fixed reference
you are comparing against a memory that has been rewritten — memory is
reconstructive, so your recollection of how bad you were is not reliable.

---

## Timeframes and the long-horizon problem

**Cross-reference: leaders/ mechanism #2 (long time horizon).**

The ten-year rule (Simon & Chase 1973; Hayes 1989 on composers) is not a
motivational slogan. It is an observed lower bound on elapsed time to
elite-level performance in domains with large chunk stores. It has two
practical implications:

1. **Your planning horizon must exceed your feedback horizon.** If a skill takes
   years to develop and gives feedback in months, any evaluation window shorter
   than years will mislead you into abandoning something that is working, or
   continuing something that is not.
2. **The rule is compressible by pedagogy, not by effort.** Chess mastery is
   reached faster now than in 1970 because databases, engines and accumulated
   teaching compressed the acquisition. **The highest-leverage investment is
   therefore usually in better instruction, not in more hours.** See
   expertise.md.

**And the failure mode, from leaders/failure-modes.md: long horizons enable
sunk-cost entrapment.** Set explicit review points with pre-committed criteria,
in advance, while you can still think clearly about them.

---

## Things not to do

| Don't | Because |
|---|---|
| **Reread and highlight** | Rated LOW by Dunlosky et al. Substitute retrieval at the same cost |
| **Cram, unless the horizon is genuinely short** | Optimal for tomorrow, near-worthless for next year. Choose it knowingly or not at all |
| **Buy a brain-training subscription** | No far transfer. Owen et al., n = 11,430. Spend the time on the domain |
| **Identify your learning style** | The construct does not predict outcomes |
| **Practise what you're already good at** | Comfortable, pleasant, and produces nothing |
| **Accumulate hours in a domain with no feedback and expect skill** | You will accumulate confidence instead, which is worse than nothing |
| **Take on a "general skills" course as a substitute for domain knowledge** | Transfer is rare. Learn the thing |
| **Trust your judgement of your own progress** | It is unreliable and sometimes inverted. Use a benchmark task |

---

## Cross-references

| Go to | For |
|---|---|
| **risk/forecasting.md** | Brier scores and calibration — the machinery for scoring your own predictions, which is the feedback mechanism for judgement domains |
| **risk/base-rates.md** | The outside view. What to use when your domain gives no feedback and you must decide anyway |
| **risk/practices.md** | Decision journals and the reversible/irreversible 2×2. Same TIER 3 honesty about journalling |
| **leaders/mechanism-matrix.md** | Mechanism #1 (direct contact with reality) and #2 (long time horizon) are the organisational forms of the feedback condition and the ten-year rule |
| **leaders/failure-modes.md** | The failure mode of a long horizon is sunk-cost entrapment. Set review points in advance |
| **knowledge/the-replication-crisis.md** | Why to discount the effect sizes cited throughout this notebook |
| **existence/attention.md** | The attention conditions that deliberate practice presupposes |

---

## Open questions

- [ ] What is the right retrieval-to-study time ratio? The literature says heavily retrieval-weighted; the function is unmapped.
- [ ] Does the blank-page test outperform structured self-quizzing? Both are retrieval; nobody has compared them directly at length.
- [ ] Can prediction logging measurably improve skill acquisition in a slow-feedback domain, or does it only improve calibration?
- [ ] How long should a benchmark task interval be before the retest is informative rather than a practice effect?
- [ ] Is there any evidence at all for the protégé effect isolated from retrieval practice? I suspect not.
- [ ] Do the spacing schedules above hold for procedural skill, or only for declarative material? The applied literature is thin.
