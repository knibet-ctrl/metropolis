# The Questions — Five Things Called "Learning"

> **Status: TIER 1 that the distinctions matter; TIER 2 on where exactly the
> boundaries fall.** This file contains almost no findings. It exists because
> the single most common error in this domain is answering one question with
> evidence from another.

> **Standing caveat: written from general knowledge without source
> verification.**

---

## The conflation problem

Someone says "she learned Spanish." This could mean any of five things with
almost non-overlapping evidence bases:

1. She can now perform an act she could not perform before (**acquisition**).
2. She will still be able to perform it in a year (**retention**).
3. She can use it in a situation unlike the one she trained in (**transfer**).
4. She performs at a level that took years of structured effort (**expertise**).
5. She holds a document asserting some of the above (**credentialing**).

These come apart constantly, and in predictable directions. **Massed practice
maximises 1 and damages 2. Blocked practice maximises 1 and damages 3. Credential
systems select on 5 and measure 1.** An intervention that looks excellent on
one is routinely mediocre or harmful on another, and studies with short
post-tests systematically favour the wrong techniques.

---

## The mapping table

| # | Question | What it actually asks | Best evidence base | Typical measurement | Characteristic error |
|---|---|---|---|---|---|
| **1** | **Acquisition** | Can you do it now, having just been taught? | Very strong. Lab studies, thousands of experiments | Immediate post-test | Mistaking performance during training for learning. Bjork's core point |
| **2** | **Retention** | Can you still do it after weeks, months, years? | Strong for verbal material, weak beyond ~1 year | Delayed test, no restudy | Almost never measured in real education. Nearly all schooling is optimised for 1 and evaluated on 1 |
| **3** | **Transfer** | Can you do it in a context unlike training? | Strong *negative* evidence. See transfer.md | Structurally dissimilar task | Assuming transfer without testing it. This is the load-bearing assumption of general education |
| **4** | **Expertise** | Are you among the best, after years? | Observational, correlational, small-n, retrospective | Tournament rating, peer nomination, objective output | Survivorship. We study the people who stayed |
| **5** | **Credentialing** | Does an institution certify you? | Strong economics literature; weak learning literature | Degree, licence, certificate | Confusing the signal with the thing signalled. See knowledge/expertise-and-authority.md |

---

## Why each needs different evidence

### 1. Acquisition — the well-lit area

Nearly all the rigorous experimental work is here, because it is cheap: teach
something in twenty minutes, test immediately, publish. **This is also why the
literature systematically misleads.** An immediate post-test rewards fluency,
massing and blocking — precisely the conditions that damage retention and
transfer.

The single most important methodological fact in the field: **performance
during training is a poor and sometimes inverted proxy for learning.** Robert
and Elizabeth Bjork have made this point since the 1970s, and it is the reason
the popular study advice is wrong. If you evaluate a technique by how well
students do while using it, you will select the worst techniques.

### 2. Retention — the neglected question

Ebbinghaus (1885) established that forgetting is steep and early. Everything
since has refined the shape without overturning it. But almost no educational
system measures retention. **A student who scores 90% in June and 40% in
September is recorded as having scored 90%.**

The interesting sub-question: retention of *what*? Retention of facts, of
procedures, and of the ability to relearn quickly are three different curves.
The third — **savings**, Ebbinghaus's own measure — is the most forgiving and
the least studied in applied settings. You may have "forgotten" calculus and
still relearn it in a tenth of the original time. That is a real residue and
standard tests do not detect it.

### 3. Transfer — the question the whole edifice rests on

Almost every justification for general education is a transfer claim. Latin
trains the mind. Maths teaches logical thinking. The humanities teach critical
thinking. Coding teaches problem-solving. **Every one of these is an empirical
claim about far transfer, and the evidence for far transfer is bad.**

Barnett & Ceci (2002) gave a taxonomy: transfer varies along knowledge domain,
physical context, temporal context, functional context, social context, and
modality. "Near" and "far" are a crude two-point summary of a six-dimensional
space, and much of the apparent disagreement in the literature is people
occupying different points in that space and using the same word.

### 4. Expertise — where the methodology is weakest

You cannot randomise people into becoming a grandmaster. Everything here is
observational, and the observations are made on survivors. **The population of
elite performers is the population that did not quit, did not get injured, was
not misidentified early, and had the resources to continue.** Any correlation
between practice and attainment measured within that group has been
conditioned on selection at every stage.

This is the methodological hole under the whole deliberate-practice literature,
and it cuts both ways: it inflates practice effects (the untalented quit before
accumulating hours) and deflates them (range restriction among elite performers
suppresses correlations).

### 5. Credentialing — a different subject entirely

The economics of education is largely about whether schooling raises
productivity (human capital) or identifies pre-existing productivity
(signalling). Spence (1973) formalised the signalling account. Caplan's *The
Case Against Education* (2018) argues the signalling share is large — his
estimate is roughly 80%, which is far above the mainstream view and should be
treated as an advocate's upper bound.†

**Steelman for high human-capital share:** returns to education persist in
within-twin designs, appear in compulsory-schooling natural experiments, and
Ritchie & Tucker-Drob's (2018) meta-analysis found roughly **1 to 5 IQ points
per additional year of schooling** across three quasi-experimental designs —
that is a real cognitive effect, not a signal.

**Steelman for high signalling share:** the sheepskin effect (a large wage jump
for the final year that grants the certificate, not for the equivalent learning
without it), the near-total absence of measured far transfer from curricular
content, and the fact that graduates cannot pass their own exams a few years
later.

**This notebook does not resolve it.** Note only that questions 1-4 are about
learning and question 5 is about labour markets, and that they are argued
about in the same sentences constantly.

---

## The interventions-by-question grid

Which techniques help which question. Signs indicate direction, not size.

| Intervention | 1 Acquisition | 2 Retention | 3 Transfer | 4 Expertise |
|---|---|---|---|---|
| **Massed practice (cramming)** | **+ +** | **− −** | − | irrelevant |
| **Spaced practice** | − (feels worse) | **+ +** | + | + |
| **Blocked practice (one topic at a time)** | **+ +** | ~ | **− −** | − |
| **Interleaved practice** | **− −** (feels much worse) | + | **+ +** | + |
| **Retrieval practice / self-testing** | ~ | **+ +** | + | + |
| **Rereading** | + (feels good) | ~ 0 | 0 | 0 |
| **Worked examples (novices)** | **+ +** | + | + | + |
| **Worked examples (experts)** | **−** (expertise reversal) | − | ~ | − |
| **Minimal-guidance discovery (novices)** | **−** | − | ~ | − |
| **Immediate feedback** | **+ +** | ~ / − | ~ | + early |
| **Delayed feedback** | − | + | + | + later |

**Read the first two columns together.** Every technique with a strong positive
in column 1 and a negative in column 2 is a technique that will be popular,
because everyone involved — student, teacher, and administrator — is
measuring column 1.

---

## The three questions that are malformed

**TIER 4.** These get asked constantly and cannot be answered as posed.

| Question | Why it is malformed |
|---|---|
| **"How long does it take to learn X?"** | Underspecified on all five dimensions above. To what standard, retained how long, transferring to what? The 10,000-hour and 20-hour formulations are both answers to an unasked question |
| **"Is he a natural or did he work for it?"** | Presupposes a partition that does not exist. Genetic influence operates partly *through* the propensity and opportunity to practise (gene-environment correlation). See talent-and-limits.md |
| **"What percentage of ability is genes?"** | Heritability is a population-level variance decomposition under specific conditions. It is not a percentage of any individual's ability. Answering the question as posed is the primary error in the whole area |

---

## Where the popular story is wrong

| Popular story | What the evidence says |
|---|---|
| **"Learning" is one thing you get better or worse at** | Five distinct questions with different, sometimes opposed answers. Techniques that help one harm another |
| **If you can do it at the end of the lesson, you learned it** | Performance during and immediately after training is a **known-bad** proxy for durable learning, and is sometimes inversely related to it |
| **Struggling means the teaching failed** | Some struggle is diagnostic of bad instruction; some is the mechanism. Distinguishing them is the actual skill of teaching, and there is no simple rule |
| **A good course is one students rate highly** | Deslauriers et al. (2019) measured exactly this: more learning, lower self-rated learning. Student evaluations partially measure fluency, which is anti-correlated with durable learning |
| **Education generally trains the mind** | A far-transfer claim, tested repeatedly for over a century, and mostly not supported. Schooling does raise measured IQ (Ritchie & Tucker-Drob 2018), which is the strongest counterweight and deserves more attention than it gets |
| **The debate is talent vs practice** | Both sides accept both matter. The dispute is about variance shares within specific populations, and about whether the studies measured "practice" competently |

---

## Open questions

- [ ] What fraction of published education interventions ever measure retention beyond three months? My guess is under 10%; I have not checked.
- [ ] Is "savings" (fast relearning) a better outcome measure than recall for anything taught in school? Nobody seems to use it.
- [ ] Does the acquisition/retention inversion hold for motor skills as strongly as for verbal? The motor learning literature says broadly yes (Schmidt & Bjork 1992) but I have not verified the modern state.
- [ ] Can the survivorship problem in expertise research be addressed with prospective cohorts? A few exist in sport. What did they find?
- [ ] Where does the human-capital / signalling split actually sit? Caplan's 80% is an advocate's number; what does a fair reading give?
- [ ] Are there domains where blocked practice genuinely beats interleaving for transfer? Very early acquisition seems likely. Where is the crossover?

---

**Next:** how-learning-works.md for the mechanism, or jump straight to
what-actually-works.md if you want the operational answer.
