# What Actually Works — Techniques Ranked By Evidence

> **Status: TIER 1 for the top two techniques, TIER 2 for most of the rest.**
> This is the core file of the notebook. If you read one file, read this one and
> then the-control-group.md.

> **Standing caveat: written from general knowledge without source
> verification. Effect sizes marked † are the ones I would check first.
> Remember the field-level warning from the README: education effect sizes are
> systematically inflated by small samples, unblinded assessors, and
> researcher-designed outcome measures. A 0.20 SD effect in a well-run trial is
> large (Kraft, 2020).**

---

## The reference study

**Dunlosky, Rawson, Marsh, Nathan & Willingham (2013), "Improving Students'
Learning With Effective Learning Techniques," *Psychological Science in the
Public Interest*, 14(1), 4-58.** Ten techniques, rated for utility across
materials, learners, conditions and criterion tasks.

| Rating | Techniques |
|---|---|
| **HIGH utility** | Practice testing, Distributed practice |
| **MODERATE utility** | Elaborative interrogation, Self-explanation, Interleaved practice |
| **LOW utility** | Summarisation, Highlighting/underlining, Keyword mnemonic, Imagery use for text, **Rereading** |

**The finding that matters: the two techniques students overwhelmingly report
using — rereading and highlighting — are both in the LOW group.** Karpicke,
Butler & Roediger (2009) surveyed students: roughly **84% listed rereading** as
a study strategy and about **55% listed it first**; only around **11%**
mentioned self-testing, and those who did described it as *checking* whether
they had learned, not as a way of learning.†

---

## The techniques with strong evidence

### 1. Retrieval practice / the testing effect — **TIER 1**

**The claim: attempting to recall information from memory produces more durable
learning than restudying the same information for the same amount of time.**

| Study | Design | Result |
|---|---|---|
| **Roediger & Karpicke (2006)**, *Psych Science* 17(3) | Prose passages. Study-study-study-study vs study-study-study-test vs study-test-test-test | **5 minutes later:** repeated study wins (~83% vs ~71%). **One week later:** repeated testing wins decisively (~61% vs ~40%).† **The ranking inverts with delay** |
| **Karpicke & Roediger (2008)**, *Science* 319 | Swahili-English pairs. Manipulated whether learned items were dropped from restudy vs dropped from retrieval | Dropping items from **restudy** had no cost. Dropping them from **retrieval** was devastating: ~80% vs ~35% at one week.† Retrieval, not exposure, does the work |
| **Karpicke & Blunt (2011)**, *Science* 331 | Retrieval practice vs elaborative concept mapping on science texts | Retrieval practice beat concept mapping, **including on inference questions** — and students predicted the opposite |
| **McDaniel, Agarwal, Huelser, McDermott & Roediger (2011)** | Real middle-school science classrooms, low-stakes quizzing | Substantial gains on unit exams for quizzed material. Effects hold outside the lab, smaller than in it |

**Effect size:** meta-analyses (Rowland 2014; Adesope, Trevisan & Sundararajan
2017) report roughly **g = 0.50 to 0.61** for testing over restudy.† Large by
any standard in this field. Rowland found the effect grows with retention
interval and is stronger with feedback.

**Where it fails or weakens:**
- **Without feedback**, errors can persist. Feedback substantially improves the
  effect and prevents the (small) risk of consolidating a wrong answer.
- **Recognition formats (multiple choice) are weaker than free recall.**
  Multiple choice can also introduce false knowledge from plausible
  distractors, though corrective feedback largely fixes this (Butler & Roediger).
- **If initial retrieval fails completely**, you get little. There is a floor:
  you need enough encoding to have something to retrieve. Butler's rule of
  thumb — retrieval should be *effortful but successful*.
- **Anxiety.** High-stakes testing is not the same intervention as low-stakes
  retrieval practice, and the literature supporting the latter is routinely
  cited to justify the former. That is a misuse.
- **Transfer beyond the tested material is real but limited.** Testing what you
  test helps most; there is modest evidence of transfer to related untested
  material (Chan's retrieval-induced facilitation), and also of
  **retrieval-induced forgetting** of related non-retrieved items (Anderson,
  Bjork & Bjork, 1994). Both effects exist; the net is usually positive.

### 2. Distributed (spaced) practice — **TIER 1**

**The claim: the same total study time produces more durable learning when
distributed across sessions than when massed.**

- **Cepeda, Pashler, Vul, Wixted & Rohrer (2006)**: meta-analysis of **254
  studies, over 14,000 participants**.† Spacing advantage is robust and large.
- **Cepeda et al. (2008)**, *Psychological Science*: manipulated gap and
  retention interval factorially with over 1,300 participants. The **optimal
  gap scales with the retention interval, at roughly 10-20%.**

| Want to remember for | Optimal gap between reviews (approximate) |
|---|---|
| 1 week | ~1 day |
| 1 month | ~1 week |
| 6 months | ~3 weeks |
| 5 years | ~6-12 months |

**These are approximate and the function is broad and flat near the optimum.**
That is good news: getting the gap roughly right captures most of the benefit.
Getting it badly wrong — massing — loses most of it.

**Where it fails:** if the gap is so long that retrieval fails entirely, you are
relearning, not spacing. And spacing costs nothing but requires planning,
which is why it loses to cramming under time pressure. **Cramming is not
irrational for an exam next week. It is irrational for anything you want to
keep.**

**Applied form:** the Leitner box (1972) and computerised algorithms — Piotr
Woźniak's SuperMemo SM-2 (1987) and its descendants, Anki (2006). The
algorithms are heuristics fitted to the spacing literature, not derived from
it. They work; their specific parameters are not evidence-based in detail.

### 3. Interleaving — **TIER 1 for the effect, TIER 2 for scope**

**The claim: mixing problem types (ABCBCACAB) beats practising them in blocks
(AAABBBCCC), for retention and especially for the ability to select the right
method.**

| Study | Result |
|---|---|
| **Rohrer & Taylor (2007)** | Maths volume formulae. Blocked practice produced better performance *during practice*; interleaved produced far better performance one week later |
| **Rohrer, Dedrick & Stershic (2015)** | 7th-grade maths, interleaved homework. Delayed test: **~72% vs ~38%**.† One of the largest effects in the applied literature and it needs checking |
| **Kornell & Bjork (2008)** | Learning painters' styles. Interleaved exposure produced better generalisation to new paintings — **and about 78% of participants believed blocking had worked better**.† The metacognitive illusion is the finding |
| **Batting practice (Hall, Domingues & Cavazos, 1994)** | Random pitch order beat blocked for transfer to game-like conditions |

**Mechanism (disputed):** two candidates. (a) *Discriminative contrast* — mixing
lets you notice what distinguishes categories, which is why it helps most when
the problem types are confusable. (b) *Retrieval/reloading* — each switch forces
you to reload the method from memory, making each trial a retrieval event.
Evidence favours (a) for category learning and (b) for procedural material.
Probably both.

**Where it fails:** interleaving before you can do any of the individual things
is harmful. **Block until you have the basic procedure, then interleave.** The
literature is not precise about where the crossover sits, and this is the
weakest point in the practical advice.

### 4. Elaboration and self-explanation — **TIER 2, moderate**

- **Elaborative interrogation** (Pressley et al., 1987): asking and answering
  "why is this true?" Effects are decent for factual material; require existing
  domain knowledge to work at all.
- **Self-explanation** (Chi, Bassok, Lewis, Reimann & Glaser, 1989; Chi et al.,
  1994): explaining each step to yourself while studying worked examples. Chi's
  original finding was correlational — good learners spontaneously
  self-explained more — but the trained version also works.

Dunlosky rated both MODERATE. The honest reading: real, smaller than retrieval
and spacing, and heavily dependent on prior knowledge.

### 5. Worked examples — **TIER 1 for novices, and it reverses**

Sweller & Cooper (1985): studying worked solutions produces better learning per
unit time than solving equivalent problems, for novices. Confirmed many times.
The best form is the **completion problem** — partially worked, with the
learner finishing it — and **faded worked examples**, where support is
withdrawn step by step.

**Expertise reversal (Kalyuga et al., 2003): once learners have schemas, worked
examples become redundant and impair learning relative to problem solving.**
Any claim of the form "X is the best way to teach" that ignores this is wrong
by construction.

**Sub-goal labelling** (Catrambone, 1998): labelling the functional steps of a
worked example improves transfer to structurally different problems. Small
literature, consistent results, underused.

### 6. The generation effect — **TIER 1, modest**

Slamecka & Graf (1978): information you generate yourself is remembered better
than information you read. Extends to **pretesting** — Richland, Kornell & Kao
(2009) and others show that *guessing before being taught*, even when the guess
is wrong, improves later retention of the correct answer. Counterintuitive,
replicated, and almost never used.

### 7. Dual coding / multimedia design — **TIER 2**

Richard Mayer's multimedia principles (summarised in *Multimedia Learning*,
2009). Coherence, signalling, redundancy, spatial and temporal contiguity,
segmenting, modality. The individual effects are modest and mostly measured in
short computer-based lessons, but they are consistent and cheap.

**Do not confuse this with learning styles.** Dual coding says *everyone*
benefits from well-integrated verbal plus visual material. Learning styles says
*some* people should get only one. The first is supported; the second is not.
See the-control-group.md.

---

## The popular-but-weak

| Technique | Verdict | Why it persists |
|---|---|---|
| **Rereading** | LOW (Dunlosky). Second and third readings add little, especially when massed. Some benefit from spaced rereading — but it is dominated by retrieval practice at the same cost | It is easy, it feels productive, and increasing fluency is misread as increasing knowledge |
| **Highlighting / underlining** | LOW. Repeatedly null. Some studies find it **harmful**, plausibly by drawing attention to isolated sentences and away from connections | It produces a visible artefact. The page looks studied |
| **Summarising** | LOW *as usually done*. Works if the learner is trained to summarise well, which most are not | Feels like processing. Often is transcription |
| **Massed practice / cramming** | Works for tomorrow, fails for next month. Not useless — correctly chosen for a throwaway exam | The incentive structure of schooling rewards it |
| **Mnemonics (keyword method)** | LOW general utility, though genuinely excellent for arbitrary paired associates (vocabulary, anatomy, ordered lists) | Overgeneralised from the narrow cases where it is very good |
| **Note-taking by hand vs laptop** | **Contested and probably overstated.** Mueller & Oppenheimer (2014) reported a handwriting advantage; **Morehead, Dunlosky & Rawson (2019) failed to replicate it.** Treat "always handwrite" as unsupported | A tidy story that fits an anti-technology prior |
| **Minimal-guidance discovery learning for novices** | Negative. Kirschner, Sweller & Clark (2006) is the canonical attack; the strongest empirical datum is Project Follow Through (1968-77, ~700,000 US children, ~$1bn), where Direct Instruction outperformed the alternatives on basic skills, cognitive skills **and** affective measures — and was largely ignored† | It aligns with a strong ideological commitment about the nature of the learner |

**On the last row, steelman the other side:** Kirschner et al. attack *minimal*
guidance, and their opponents mostly do not advocate minimal guidance —
problem-based and inquiry learning as practised include substantial
scaffolding. Hmelo-Silver, Duncan & Chinn (2007) made this reply and it lands.
The disagreement is narrower than the polemics suggest, and probably reduces to
expertise reversal: guidance for novices, autonomy later.

---

## The metacognitive problem — why any of this needs saying

**TIER 1 and it is the reason good techniques lose.**

| Finding | Source |
|---|---|
| Learners rate massed and blocked practice as more effective, while performing worse | Kornell & Bjork (2008); Simon & Bjork (2001) |
| Fluent-seeming lecturers are rated as far more effective with **no difference in actual learning** | Carpenter, Wilford, Kornell & Mullaney (2013) |
| Font legibility changes predicted memorability without changing actual memory | Rhodes & Castel (2008) |
| **Students in active-learning physics classes learned more and rated their learning as lower** | Deslauriers, McCarty, Miller, Callaghan & Kestin (2019), *PNAS*. The cleanest demonstration available |

**The consequence:** any system that selects teaching methods by student
satisfaction, or study methods by how they feel, is running a selection process
that is anti-correlated with learning over part of its range. Student
evaluations of teaching, in particular, partly measure fluency.

---

## Where the popular story is wrong

| Popular story | Reality |
|---|---|
| **Tests measure learning** | Tests *cause* learning, and typically more of it than the studying they replace. Retrieval is the mechanism, not the assessment |
| **You should study until it feels easy** | Ease is the signal to stop getting benefit. Desirable difficulty: if it feels effortful but you are succeeding, it is working |
| **Practise one thing until you've got it, then move on** | Blocking maximises performance today and damages retention and discrimination. Block briefly, then interleave |
| **Cramming doesn't work** | Cramming works *for tomorrow*, which is what it is used for. It fails for retention. Attack the incentive, not the student |
| **Learning by doing is the best way to learn** | For novices, unguided doing is among the worst uses of time. Worked examples first, then fade the guidance. This reverses with expertise |
| **The best study technique is whichever suits you** | The between-technique differences (retrieval and spacing vs rereading) dwarf any measured between-person differences in what works. The individualisation claim has been tested directly and failed |
| **Effect sizes in education are comparable to other fields** | They are not, and they are inflated. Cheung & Slavin (2016): researcher-made outcome measures produce roughly double the effect of standardised ones (~0.30 vs ~0.16)† |
| **Hattie's *Visible Learning* settles what works** | Treat it with heavy scepticism. The "common language effect size" transformation has been shown to be mathematically incoherent (Bergeron & Rivard, 2017), and averaging across incommensurable meta-analyses obscures more than it reveals (Slavin; Wecker et al.; Simpson, 2017) |

---

## Open questions

- [ ] Where exactly is the block-to-interleave crossover? The practical advice is currently hand-waving.
- [ ] Do the lab effect sizes for retrieval practice survive at classroom scale over a full year? McDaniel et al. suggest yes but smaller. How much smaller?
- [ ] Is the Rohrer, Dedrick & Stershic 72%-vs-38% figure right? It is the largest applied effect I cite and I am least confident in it.
- [ ] Does retrieval-induced forgetting ever outweigh retrieval-induced facilitation in realistic curricula?
- [ ] Is the note-taking-by-hand effect dead, or conditional? The replication failure is clear; the boundary conditions are not.
- [ ] What is the optimal ratio of study time to retrieval time? Roediger's work suggests heavily weighted toward retrieval, but the exact function is unmapped.
- [ ] How much of the spacing effect in commercial SRS comes from the algorithm as against merely from reviewing at all?
