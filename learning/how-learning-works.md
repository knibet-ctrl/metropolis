# How Learning Works — Mechanism

> **Status: TIER 1 on the architecture, TIER 2 on most of the mechanistic
> detail.** The three-stage framing (encoding, consolidation, retrieval) is
> not seriously disputed. The cellular and systems-level accounts of each
> stage are live research.

> **Standing caveat: written from general knowledge without source
> verification. Numbers marked † are the ones to check first.**

---

## The architecture

| Stage | What happens | Time scale | What you can control |
|---|---|---|---|
| **Encoding** | Experience is transformed into a trace. Depth and elaboration at this moment determine what is available later | Seconds | A great deal. Attention, elaboration, generation, prior schema |
| **Consolidation** | The trace is stabilised, reorganised, integrated with existing knowledge. Hippocampal-to-neocortical transfer over days to years | Hours to years | Indirectly. Sleep, spacing, no interference |
| **Retrieval** | The trace is reconstructed. **Retrieval is not read-out; it modifies the trace** | Seconds | A great deal. This is where the leverage is |

**The single most consequential fact:** retrieval is not a neutral measurement.
Every act of retrieval alters the memory — strengthening it, and sometimes
altering its content. This is why testing is a learning event and why
eyewitness testimony degrades under repeated questioning. The same mechanism
produces both.

---

## Memory is reconstruction, not playback

**TIER 1.** Frederic Bartlett's *Remembering* (1932) is the origin. English
participants repeatedly recalled the Native American folk tale "The War of the
Ghosts"; over successive retellings the story systematically drifted toward
English cultural expectations — supernatural elements rationalised, unfamiliar
details dropped or normalised. Memory reconstructed the story to fit a schema.

Modern confirmations:

| Finding | Source | Detail |
|---|---|---|
| **Misinformation effect** | Loftus & Palmer (1974) | "Smashed" vs "hit" in the question changed speed estimates and produced false memories of broken glass that was never present |
| **False memories can be implanted** | Loftus & Pickrell (1995) | The "lost in the mall" paradigm: roughly **25%** of participants came to report a fabricated childhood event† |
| **DRM paradigm** | Deese (1959), Roediger & McDermott (1995) | Study a list of associated words (bed, rest, tired…); false recall of the non-presented lure ("sleep") occurs at rates comparable to real items |
| **Flashbulb memories are confident and wrong** | Neisser & Harsch (1992) on Challenger; Talarico & Rubin (2003) on 9/11 | Confidence stays high; accuracy decays like ordinary memory. **Confidence and accuracy decouple** |

**Practical consequence for learning:** because retrieval reconstructs, the
*cues* present at retrieval matter enormously. Encoding specificity (Tulving &
Thomson, 1973) — you remember best in the conditions you encoded in. Godden &
Baddeley (1975): divers who learned word lists underwater recalled them better
underwater. **This is one reason skills fail to transfer: the retrieval cues
are missing in the new context.**

---

## The forgetting curve — Ebbinghaus, 1885, and after

Hermann Ebbinghaus, working alone on himself, invented experimental memory
research. *Über das Gedächtnis*, 1885. He used **nonsense syllables** (CVC
trigrams) precisely to strip out prior meaning, memorised lists to a criterion,
and measured **savings** — the reduction in relearning time — at intervals.

The classic figures, approximate and from a single subject:

| Delay | Savings |
|---|---|
| 20 minutes | ~58% |
| 1 hour | ~44% |
| 9 hours | ~36% |
| 1 day | ~34% |
| 6 days | ~25% |
| 31 days | ~21% |

**What is solid:** the shape. Forgetting is steep, then flattens — roughly
logarithmic in time. Wixted & Ebbesen (1991) argued a power function fits
better than an exponential across many datasets; the practical difference is
that a power function has a long, slowly decaying tail.

**What was overstated:** the curve is for meaningless material learned by a
single highly practised subject with no elaboration, no context, and no
retrieval practice. **Meaningful, well-integrated, retrieval-practised material
decays far more slowly.** Bahrick's "permastore" work (1984) on Spanish learned
in school found that after an initial steep drop over 3-6 years, retention was
essentially flat for the next **25 to 30 years**.† Bahrick & Phelps (1987)
found the same for spaced-learned vocabulary at eight years.

**Replication:** Murre & Dros (2015, PLoS ONE) directly replicated Ebbinghaus's
procedure and obtained a close fit. It stands. This is unusual for a 140-year-
old psychology result and worth noting.

**The catch nobody mentions:** the forgetting curve is routinely reproduced in
commercial spaced-repetition marketing with a second "curve" showing review
flattening the decay. That second curve is a schematic illustration, not
Ebbinghaus's data. The underlying spacing effect is real (see
what-actually-works.md); the specific picture is decoration.

---

## Working memory and cognitive load

**TIER 1 that capacity is sharply limited. TIER 2 on the number and on
cognitive load theory's instructional prescriptions.**

- **Miller (1956)**, "The Magical Number Seven, Plus or Minus Two." Often
  misquoted as a memory capacity claim; Miller was noting a recurring limit
  across several tasks and was explicitly playful about it.
- **Cowan (2001)** revised the number down to about **4 ± 1 chunks** when
  rehearsal and chunking are controlled. Cowan's estimate is the modern
  consensus figure.
- **Baddeley & Hitch (1974)**: working memory as a multi-component system —
  phonological loop, visuospatial sketchpad, central executive; episodic
  buffer added in 2000. The model is dated but remains the standard vocabulary.

**The unit is the chunk, and chunk size is unbounded.** "F-B-I-C-I-A-N-A-S-A"
is ten items or three. This is the entire hinge of expertise: experts do not
have larger working memory, they have larger chunks. See expertise.md.

### Cognitive Load Theory (John Sweller, from 1988)

Three load types:

| Type | Definition | What to do |
|---|---|---|
| **Intrinsic** | Inherent complexity — the number of interacting elements you must hold simultaneously | Cannot be reduced without changing the task. Sequence and segment |
| **Extraneous** | Load imposed by how the material is presented | **Eliminate.** Split attention, redundant text, poor diagrams |
| **Germane** | Effort going into schema construction | Protect it. This is the load you want |

The germane/extraneous distinction has been criticised as unfalsifiable in
practice — you cannot measure germane load independently of the outcome it is
invoked to explain. **Sweller himself revised the framework (around 2010),
folding germane load into intrinsic.** Treat the three-type version as a
teaching heuristic, not a measured decomposition.

**The effects CLT generated are more durable than the theory:**

| Effect | Claim | Status |
|---|---|---|
| **Worked example effect** | Studying worked solutions beats solving problems, for novices | Robust. Sweller & Cooper (1985) and many replications |
| **Split-attention effect** | Physically integrating text with diagram beats separating them | Robust |
| **Modality effect** | Narration + diagram beats on-screen text + diagram | Robust in lab; smaller in the wild |
| **Redundancy effect** | Adding narration that duplicates on-screen text **hurts** | Robust, and routinely violated by every slide deck ever made |
| **Expertise reversal effect** | Kalyuga, Ayres, Chandler & Sweller (2003): the above effects **reverse** as expertise grows. Guidance that helps a novice impairs an expert | Robust and badly under-applied |

**Expertise reversal is the most important item in this table.** It means there
is no such thing as a good instructional method — only a good match between
method and current expertise. Most educational arguments are two people
generalising from different points on this curve.

---

## Schemas and chunking — where expertise lives

A schema is an organised knowledge structure that lets many elements be handled
as one. Building schemas is what long-term learning *is*.

**The critical asymmetry: working memory is severely limited when dealing with
novel information and effectively unlimited when dealing with information
organised in long-term memory.** Sweller calls this the borrowing-and-
reorganising principle. It is why "you don't need to memorise, you can look it
up" is a category error: knowledge in long-term memory does not merely store
facts, it **expands the effective size of working memory** for that domain. You
cannot look up a chunk.

This is also the reason for the strongest single argument against content-free
skills teaching. See transfer.md.

---

## Understanding and remembering are different problems

**TIER 1, and constantly ignored in both directions.**

| | Remembering without understanding | Understanding without remembering |
|---|---|---|
| **Looks like** | Recites definitions, fails novel problems | Follows the lesson perfectly, cannot reproduce it a week later |
| **Cause** | Rote encoding, no schema integration | Fluent instruction, no retrieval practice, no spacing |
| **Fix** | Elaborative interrogation, self-explanation, varied examples, worked examples with sub-goal labelling | Spaced retrieval practice |
| **The failure mode of people who fear it** | Traditionalists over-drill and produce inert knowledge | Progressives banish memorisation and produce students who cannot retrieve anything to reason with |

**Both failure modes are real and each camp is well calibrated about the other's
and blind about its own.** The genuine finding is that they are not opposed:
understanding aids retention (meaningful material is far more durable —
Bartlett, Bahrick), and retention enables understanding (you cannot reason
about elements you cannot hold). Willingham's formulation: *memory is the
residue of thought.* You remember what you thought about — which is why
highlighting fails (you thought about which sentence looked important, not
about the content).

---

## Consolidation and sleep

**TIER 2, and the popular literature here is unreliable.**

- Systems consolidation: hippocampus-dependent memories gradually become
  neocortex-dependent over days to years. Evidence from HM (Scoville & Milner,
  1957), from retrograde amnesia gradients, and from rodent work.
- Synaptic consolidation: protein-synthesis-dependent stabilisation over
  minutes to hours (Kandel's *Aplysia* work; Nobel 2000).
- **Reconsolidation**: reactivating a memory returns it to a labile state
  (Nader, Schafe & LeDoux, 2000). Genuinely important, still being worked out
  in humans.
- Sleep-dependent consolidation: slow-wave sleep implicated in declarative
  memory, REM in procedural. Stickgold and Walker are the main names.

**Flag.** Matthew Walker's *Why We Sleep* (2017) is the most widely read source
here and contains documented factual errors and overstatements (catalogued at
length by Alexey Guzey in 2019, with responses). Cordi & Rasch's review (around
2021) is substantially more cautious than the popular account: the direction of
the sleep-memory effect is supported, the effect sizes and the mechanistic
specificity are less secure than usually claimed. **Sleep well anyway; the cost
is zero and the general case is good. Do not cite the specific numbers.**

---

## Where the popular story is wrong

| Popular story | Reality |
|---|---|
| **Memory is a recording; forgetting is loss of the file** | Memory is reconstruction. Retrieval alters the trace. Much forgetting is retrieval failure, not storage loss — hence savings and sudden recovery with the right cue |
| **The forgetting curve proves you forget 70% in 24 hours** | That figure is from nonsense syllables, one subject, no meaning, no retrieval, 1885. Meaningful practised material behaves completely differently — Bahrick found ~30 years of near-flat retention for school Spanish |
| **We use 10% of our brain / working memory can be trained** | The first is fiction. The second is the brain-training claim and it fails: capacity training produces near transfer only. See the-control-group.md |
| **"Seven plus or minus two" is the capacity of working memory** | Miller's paper was not a capacity claim in the way it is cited. Cowan's ~4 chunks is the better modern figure, and the *chunk*, not the item, is the unit |
| **Memorisation is obsolete because of search engines** | Knowledge in long-term memory expands effective working memory in that domain. You cannot Google a chunk. This is the load-bearing argument and it is rarely engaged with by the other side |
| **Cognitive load theory says make everything easy** | It says eliminate *extraneous* load. Intrinsic load is the material and desirable difficulties deliberately add effort. CLT and desirable difficulties are often presented as opposed; they mostly are not, because they target different load types — though the boundary is genuinely contested |
| **Good instruction is good instruction** | Expertise reversal: the same method helps novices and harms experts. There is no method-level answer, only a match |

---

## Steelmanning the opposition

**Against cognitive load theory:** the construct is hard to measure
independently (most studies use subjective effort ratings or secondary-task
performance, both noisy), germane load was unfalsifiable enough that its author
withdrew it, and the theory's instructional recommendations have been derived
largely from short lab tasks with novices. Critics — including some
constructivists and some in the learning-sciences tradition — argue it
systematically underweights motivation, transfer and long-horizon engagement,
which are exactly the things short lab tasks cannot measure. **This critique is
partly right and rarely conceded.**

**Against the reconstruction view being practically important:** for most
academic content, memory distortion is a minor problem compared with total
absence of recall. The reconstruction literature dominates public discussion
because of its forensic implications, not its educational ones.

---

## Open questions

- [ ] Is the germane/extraneous distinction recoverable with a measurable definition, or should cognitive load theory be stated purely in terms of its empirical effects?
- [ ] How far does encoding specificity explain transfer failure, as against genuine absence of an abstract representation? These predict different remedies.
- [ ] What is the actual shape of forgetting for skills as opposed to facts, beyond five years? Bahrick's designs are hard to run and rare.
- [ ] Does reconsolidation offer a practical learning intervention, or only a clinical one for fear memories?
- [ ] How much of the sleep-and-memory literature survives a preregistered replication programme? Nobody has run one at scale.
- [ ] Is "savings" measurable cheaply enough to be used as a routine educational outcome? If so it would change what we conclude about most curricula.
