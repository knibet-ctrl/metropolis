# Practices — What To Actually Do

> **Status: Tier 2 overall.** The procedures below are ordered by strength of
> evidence, not by how clever they sound. The top items are supported by
> controlled comparisons; the bottom items are heuristics I find useful and
> cannot defend with data. **The ordering is the content of this file.** Most
> "how to think critically" advice inverts it, leading with the clever and
> burying the effective.

---

## The one-minute version

For a claim in front of you right now, in order:

1. **How likely was this before I saw the evidence?** (Prior.)
2. **Is it preregistered, or could it have been analysed many ways?**
3. **How big is the effect, and how big is the sample?**
4. **Has anyone independent got the same result?**
5. **Who benefits if I believe it?**

**If you only ever do (1) and (4), you will outperform most people with
graduate training.**

---

## TIER A — Structural moves with controlled evidence behind them

These work. They are not clever and they are not fun.

### 1. Start from the base rate

The prior does more work than the evidence in most real cases. **Before
evaluating a study, ask what fraction of claims of this type turn out true.**

- New drug entering Phase II: roughly 30-40% reach approval. So a promising Phase II result is not strong evidence of an approved drug.
- Novel social-psychology effect published in a high-prestige journal: **base rate of replication around 40-60%.** Adjust accordingly and stop being surprised.
- Nutritional epidemiology single-study finding: **treat as close to no information.** Schoenfeld & Ioannidis (2013) took 50 common cookbook ingredients, found studies for 40, and most had published claims of cancer association or protection — frequently both.
- Preclinical cancer finding: RP:CB and Amgen suggest a very low prior for exact replication.

**The failure mode this prevents:** treating a surprising result as informative
because it is surprising. **In a low-prior field, surprise is the signature of
error, not of discovery.**

### 2. Ask whether the analysis could have gone many ways

Not "did they cheat" — **"how many defensible analyses existed?"**

Silberzahn's 29 teams got effect estimates from 0.89 to 2.93 on identical data.
Botvinik-Nezer's 70 fMRI teams used 70 different pipelines. **If the analysis
space is large and the reported analysis is one point in it, the p-value means
much less than it says.**

Concrete checks:
- Was it **preregistered**? Is the registration linked and does it match the paper? *(Claesen et al. 2021: of 27 preregistered psychology papers, one had no undisclosed deviations. Check the registration, don't just note its existence.)*
- Is it a **Registered Report**? Strongest single signal available.
- How many outcome variables are reported, and were they specified in advance?
- Are there subgroup findings? **Subgroup results in a null trial are hypothesis generation, never conclusions.**
- Is the sample size a round number, or does it look like optional stopping?

### 3. Look at effect size and interval, never significance alone

"Statistically significant" answers a question you did not ask. The questions
you asked are **how big** and **how precisely measured**.

- A confidence interval spanning trivial-to-enormous is an underpowered study, whatever the p-value.
- **Winner's curse:** in a low-powered field, the studies that reach significance systematically overestimate the effect (Ioannidis, 2008). **The first published estimate of an effect is usually the largest one you will ever see.**
- Convert to something concrete: absolute risk, natural frequencies, number needed to treat. "Doubles your risk" means nothing without the base.

### 4. Convert everything to natural frequencies

**The best-evidenced debiasing intervention in the notebook**, and it takes
seconds. Gigerenzer & Hoffrage (1995) roughly tripled correct answers on
diagnostic reasoning problems purely by restating percentages as counts.

"5% false positive rate, 0.1% prevalence" → "Of 1,000 people, 1 has it and 50
test positive falsely." **The second sentence makes the answer obvious. The
first defeats doctors.**

### 5. Ask for the track record, not the argument

Scored predictions beat reputation, credentials and eloquence. Weather
forecasters are well calibrated because they are scored daily; pundits are not
calibrated because they are never scored.

**Applied to yourself:** write down predictions with probabilities and dates.
Score them. This is the only reliable individual-level improvement in the whole
notebook, and it works because it manufactures the feedback that the
Kahneman-Klein conditions require.

### 6. Seek disconfirmation from a source that wants you to be wrong

Not "consider other views" in the abstract. **Read the best-argued opposition,
by name.** "Consider the opposite" as an explicit instruction has measurable
effect where generic "be objective" instructions have none (Lord, Lepper &
Preston, 1984).

The operational test: **can you state the strongest opposing case in a form its
best advocate would accept?** If not, you don't understand the question yet.
This is the discipline every file in this notebook is trying to enforce on
itself.

---

## TIER B — Reliable heuristics, weaker evidence

### Evaluating a study

| Check | What you're looking for |
|---|---|
| **Design** | RCT > prospective cohort > case-control > cross-sectional > case series > anecdote. **But design quality beats design type**: a well-designed natural experiment beats a badly-run RCT |
| **Sample** | n, and who they were. WEIRD undergraduates are a specific population, not humanity |
| **Preregistration** | As above. Highest-value single check |
| **Primary outcome** | Named in advance, or discovered? If the abstract's headline is a secondary outcome, be suspicious |
| **Controls** | Compared to what? Placebo, treatment-as-usual, nothing, or waitlist? These give very different numbers |
| **Attrition** | Who dropped out and were they analysed? Intention-to-treat versus per-protocol changes conclusions routinely |
| **Funding and COI** | Not disqualifying. Note that disclosure does not neutralise bias and can license more of it (Cain, Loewenstein & Moore, 2005) |
| **Replication** | Independent group, different lab, similar result? This is the only check that matters unconditionally |

### Evaluating a source

| Signal | Direction |
|---|---|
| Links to the primary study | **Good.** Most reporting doesn't |
| Reports effect size and absolute risk | **Good** |
| Reports the confidence interval or acknowledges uncertainty | **Good** |
| Quotes a scientist not involved in the study | **Good** — the single best marker in science journalism |
| "Scientists say", "studies show", no citation | **Bad** |
| Relative risk only | **Bad** |
| A mouse study reported as a human finding | **Bad**, and extremely common |
| Press release language reproduced verbatim | **Bad.** Sumner et al. (2014, BMJ) found most exaggeration in health news originates in **university press releases**, not journalists |
| Confident causal language about observational data | **Bad** |
| Single study framed as overturning a field | **Bad.** Almost nothing does |

### Evaluating an expert

Run the four questions from expertise-and-authority.md in order: competence,
**domain match**, **does the domain support expertise**, incentives. **Two and
three do most of the work and are almost always skipped.**

### Evaluating a consensus

**Ask how it formed.**

| Convergence-consensus (trust more) | Inheritance-consensus (trust less) |
|---|---|
| Independent methods agree | Everyone cites the same three papers |
| Different fields agree | One field, one paradigm |
| Predictions were made in advance and held | Post-hoc explanation only |
| Dissent exists and is engaged on the merits | Dissent is characterised rather than answered |
| Someone tried hard to falsify it and failed | Nobody has checked because it's obviously true |

**Plate tectonics, common descent and greenhouse physics are the first column.
Dietary fat, candidate genes and ego depletion were the second — and from
outside, at the time, they looked identical.** That is the hard part and I have
no method for it.

---

## TIER C — Things I find useful and cannot defend with evidence

Marked honestly. Take or leave.

- **Read the methods section before the abstract.** The abstract is marketing written by people with a stake.
- **Look for the sentence the authors didn't want to write.** Good papers contain one. Its absence is informative.
- **Prefer the position that explains why the alternative is tempting.** A theory that accounts for its rival's appeal is doing more work than one that just contradicts it. *(Borrowed from existence/epistemics.md.)*
- **Notice when a claim is doing emotional or tribal work for you.** Not disqualifying — but a belief that would be costly to abandon gets less scrutiny, always, and deserves more.
- **Distinguish "I don't know" from "nobody knows" from "unknowable."** Three completely different situations: a reading list, a research programme, a stopping point.
- **Prefer old results that survived to new results that surprise.** Time is a filter, and it is free.
- **When two authorities disagree, find out what evidence would separate them.** If none exists, the disagreement is not empirical and no amount of reading will settle it.

---

## What NOT to do

**Ranked by how much damage it does.**

1. **Do not use "do your own research" as a method.** In practice it means searching until you find agreement, with no control over source quality and no exposure to the strongest counter-argument. **The skill you actually need is choosing whom to trust, which is different and learnable.** *(This is the item most likely to annoy readers and I would defend it hardest.)*
2. **Do not treat a single study as evidence of anything.** Whatever it found, whoever published it. The base rate of individual-study reversal is far too high.
3. **Do not update to 0% or 100%.** Almost all real evidence moves you a little. People who flip completely on one paper flip back on the next.
4. **Do not use "they laughed at Galileo."** No evidential content. The base rate for rejected-and-right is low and the denominator is unrecorded.
5. **Do not cite a bias to dismiss an argument.** "That's just confirmation bias" is not a rebuttal, several of the famous biases failed replication, and the move is itself motivated reasoning wearing a lab coat.
6. **Do not confuse the absence of a demarcation criterion with equivalence.** No definition of science exists; astrology is still worthless. Both are true.
7. **Do not treat peer review as verification.** Two people, once, without the data. See peer-review.md.
8. **Do not trust your certainty.** Confidence is generated by brain states and is uncorrelated with accuracy above a low threshold. The intensity of a conviction says nothing about its truth.
9. **Do not accept relative risk without the base rate.** "50% increase" on a 2-in-100,000 risk is 3-in-100,000.
10. **Do not read only correctives.** A diet of "everything you know is wrong" content produces a person who is confidently wrong in a more sophisticated register. **This notebook is corrective-shaped and you should apply the warning to it.**
11. **Do not attempt to debias by willpower.** Nothing in the record suggests it works. Change the format, the structure, or the incentive.
12. **Do not demand certainty before acting.** Decisions run on expected value under uncertainty. "The evidence isn't conclusive" is true of nearly everything and is used almost exclusively by people defending a status quo.

---

## The institutional version — if you produce research

Ordered by evidence of effect.

1. **Preregister.** Then follow it, and report deviations explicitly. The 57%→8% shift is the size of the prize.
2. **Submit Registered Reports where the design permits.** Review of the protocol before results exist fixes the deepest problem in the system.
3. **Power your studies properly**, and if you can't, say so and frame the work as exploratory rather than confirmatory. Exploratory work is legitimate; exploratory work labelled confirmatory is the whole crisis.
4. **Publish the nulls.** Preprint them if nothing else will take them.
5. **Post data, code and full protocols.** RP:CB could not repeat a single one of 193 experiments from published methods. That is a solved problem and it costs an afternoon.
6. **Report effect sizes with intervals, and label exploratory analyses as such.**
7. **Try adversarial collaboration** on any question where you and a colleague predict different results. Rare, career-inefficient, and the highest-quality evidence a contested literature can produce.
8. **Run the automated checks on your own manuscript** before a stranger does: statcheck, GRIM, image duplication.

---

## Where the popular story is wrong

| Popular advice | Problem |
|---|---|
| "Learn the list of cognitive biases" | No evidence that bias education improves judgement. Format changes and structural commitments do. **This is where almost all critical-thinking curricula spend their time** |
| "Check the source" | Necessary, wildly insufficient. Prestigious sources published the candidate-gene literature, Surgisphere, and Schön |
| "Follow the evidence wherever it leads" | You will follow it toward the conclusion you prefer unless the structure prevents you. Sincerity is not a method |
| "Trust the experts" / "Question everything" | Both are refusals to do the work. The question is *which* experts, about *what*, in a domain where expertise is *possible* |
| "Read both sides" | Only useful if both sides are argued well. Reading a good case against a bad case is worse than reading one good case |
| "Be sceptical" | Selective scepticism applied to unwelcome conclusions is the default human state and feels identical from inside. **The test is whether you apply the same standard to evidence you like** |
| "Peer-reviewed sources only" | A filter with known low sensitivity and unknown specificity |

---

## Open questions

- [ ] Does prediction scoring transfer? Superforecasters improve on tournament questions; **whether that generalises to everyday judgement is untested.**
- [ ] Is there any teachable procedure for distinguishing convergence-consensus from inheritance-consensus? The table above is heuristics, not a method. **The most practically important gap in the notebook.**
- [ ] Do the Tier C items in this file survive contact with evidence, or are they the sort of plausible advice this notebook exists to be suspicious of? Assume the latter until tested.
- [ ] Is "don't do your own research" defensible for high-stakes personal decisions where no expert knows your situation? **I think it is not, and I have not worked out the boundary.**
- [ ] What is the minimum viable version of this file — the three checks that capture most of the value? My guess: prior, preregistration, independent replication. Untested.
