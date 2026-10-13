# Education — What Schooling Does and Doesn't Do

> **Status: TIER 1** that schooling causally raises measured cognitive ability.
> **TIER 1** that education-research effect sizes are systematically inflated.
> **TIER 2** on early-childhood programme effects. **TIER 2-3** on most named
> pedagogical interventions.

> **Written from general knowledge with no live source verification.** Effect
> sizes are indicative; the ones most worth checking are marked †.

> **Cross-reference:** the fade-out problem in this file and the transfer
> problem in `learning/` are the same problem. A skill that does not transfer
> across contexts will not persist across years either. Also see
> knowledge/what-is-science.md on why fields with weak measurement and strong
> policy demand produce inflated literatures.

---

## The one large, clean finding

**Schooling raises measured intelligence.** Ritchie & Tucker-Drob (2018)
meta-analysed three quasi-experimental designs — compulsory schooling-age
changes, school-entry age discontinuities, and control for prior IQ in
longitudinal data — across 42 datasets and over 600,000 participants. Estimate:
**roughly 1 to 5 IQ points per additional year of education, best estimate around
3.4 points†, and the gains persisted rather than fading.**

This matters because it is one of very few environmental effects on cognitive
ability with strong causal identification, and because it sits directly against
the "high heritability means nothing works" reading. Note what it is *not*: it
is an effect on measured ability, and the extent to which it reflects broad
capacity versus test-relevant skills is genuinely open.

---

## Why education effect sizes are systematically inflated

**This section should be read before any number in the rest of the file.**

| Inflation source | Magnitude | Reference |
|---|---|---|
| **Researcher-made outcome measures** vs standardised tests | roughly d = 0.40 vs 0.23† | Cheung & Slavin (2016) |
| **Small samples** | Small studies show much larger effects; a publication-bias signature | Cheung & Slavin (2016); Slavin & Smith (2009) |
| **Quasi-experiments** vs RCTs | Quasi-experimental estimates run substantially higher | Multiple reviews |
| **Published** vs unpublished | roughly d = 0.35 vs 0.19† | Cheung & Slavin |
| **Narrow, proximal outcomes** | Teaching to the measure inflates without transfer | The transfer problem again |
| **Restricted-range samples** | Simpson (2017): effect size is not comparable across designs with different variance |

**Kraft's (2020) recalibration** for standardised achievement outcomes in
well-designed causal studies of scaled interventions:

| Effect size (SD) | Kraft's label |
|---|---|
| < 0.05 | Small |
| 0.05 - 0.20 | Medium |
| > 0.20 | Large |

**Compare this with Hattie's *Visible Learning* (2009, 2012)**, which set a
"hinge point" at d = 0.40 and ranked ~250 influences above and below it. The
book is enormously influential in schools and its methodology has been
seriously criticised:
- Averaging effect sizes across incommensurable outcomes, ages, designs and
  measures.
- The "common language effect" conversions contained arithmetic errors
  (Bergeron & Rivard, 2017, whose paper is titled *How to Engage in Pseudoscience
  With Real Data*).
- Meta-meta-analysis inherits every bias in the source meta-analyses and adds
  its own.
- Snook et al. (2009) and Simpson (2017) on non-comparability.

**Treat the Hattie rankings as not reliable for ordering interventions.** The
underlying observation — that almost everything schools do produces a positive
effect size, so "does it work?" is the wrong question — is fair and useful.

**One more scaling fact.** Bloom, Hill, Black & Lipsey (2008): average annual
growth on standardised reading tests is around **1.0 SD in kindergarten-to-grade-1,
falling to roughly 0.2 SD by high school**. An effect of d = 0.20 therefore means
"about a year of learning" in high school and "about seven weeks" in first grade.
**Effect sizes are uninterpretable without the grade-level benchmark**, and are
almost always reported without it.

---

## Class size

| Study | Design | Result |
|---|---|---|
| **Project STAR** (Tennessee, 1985-89) | Randomised, ~11,600 students, K-3, classes of 13-17 vs 22-25 | Achievement gains around **0.15-0.20 SD**†, larger for Black and low-income students |
| **Chetty et al. (2011)** | Linked STAR participants to tax records | Kindergarten *classroom quality* predicted adult earnings; small classes raised college attendance. Test-score effects faded, life outcomes did not — **the pattern that recurs throughout this file** |
| **California CSR (1996)** | Statewide reduction, ~$1bn/year | Little measurable benefit. Plausible cause: the policy forced mass hiring, and teacher qualifications fell, especially in poor districts |
| **Hoxby (2000)** | Natural population variation in Connecticut | No significant class-size effect |

**Reading:** class size has a real effect in the early grades at substantial
reduction, and it does not scale, because scaling it dilutes teacher quality.
**TIER 2.** It is a good example of an intervention that is true in the trial and
false in the policy.

---

## Teacher quality

Chetty, Friedman & Rockoff (2014) linked ~1 million children to tax records:
a 1 SD improvement in teacher value-added in a single year raised earnings at
age 28 by about **1.3%**†, and replacing a bottom-5% teacher was valued at
roughly **$250,000 in lifetime earnings per classroom**†.

**Caveats that are usually dropped:**
- Rothstein (2010, 2017) argued the design does not fully rule out non-random
  student sorting; the dispute is technical and unresolved.
- Value-added estimates are noisy year to year — correlations across years
  around 0.3-0.5 — so individual teacher ratings are unreliable even if the
  aggregate signal is real.
- The effect on *earnings* is small in percentage terms. It is large in
  aggregate because it is multiplied across many students and many years.

**TIER 2.** Teacher effects are real, aggregate to something substantial, and
are far too noisy to use for individual employment decisions — which is exactly
what they were used for.

---

## Early childhood programmes

### Perry Preschool (Ypsilanti, Michigan, 1962-67)

**N = 123** (58 treatment, 65 control). Two years of high-quality preschool plus
weekly home visits, for low-income Black children with low measured IQ.
Followed to age 40 and beyond.

| Outcome at 40 (Schweinhart et al. 2005) | Treatment | Control |
|---|---|---|
| High school graduation | ~65% | ~45%† |
| Arrested 5+ times | ~36% | ~55%† |
| Earning above $20k | ~60% | ~40%† |
| **IQ gains** | **Faded to nothing by about age 10** | — |

Heckman's benefit-cost analyses estimate annual social returns of roughly
**7-12%**, which is why this study is the most cited evidence in early-childhood
policy worldwide.

**The caveats are severe and they are not usually stated:**
- **N = 123.** Sixty-odd people per arm carrying a global policy consensus.
- Randomisation was imperfect: some children were reassigned between groups on
  the basis of maternal employment and other factors.
- Many outcomes tested; multiplicity was not controlled in the original reports.
- **The 1962 counterfactual was no preschool at all.** Today's counterfactual is
  other childcare. Same programme, different question.
- Heckman & Karapakula (2019) re-analysed using randomisation-inference methods
  robust to the design flaws. **The main effects survived** but with much wider
  uncertainty intervals. They also found spillover benefits to siblings and to
  participants' own children — interesting and even less certain.

### Abecedarian (Chapel Hill, from 1972)

**N = 111.** Full-day, year-round centre-based care from a few months old to
age 5 — far more intensive than Perry.

- IQ advantage of roughly **4.5 points persisting to age 21**† — unusual, since
  IQ effects normally fade.
- College attendance ~23% vs ~6%†.
- Campbell et al. (2014, *Science*): **reduced cardiovascular and metabolic risk
  in the mid-thirties, particularly in men.** A health effect from a preschool
  programme, which is either a remarkable finding or a small-sample artefact.

### Head Start

- **Head Start Impact Study** (randomised, ~5,000 children, reports 2010 and
  2012): modest cognitive gains at the end of the programme year, roughly
  0.1-0.3 SD, **essentially gone by first grade and absent by third**.
- **But** long-run designs find real effects: Deming (2009) using sibling
  comparisons in the NLSY found gains on a summary young-adult index; Ludwig &
  Miller (2007) used the funding discontinuity and found effects on schooling and
  child mortality; Bailey, Sun & Timpe (2021) used large administrative data on
  1960s-80s cohorts and found gains in educational attainment and earnings.

### Tennessee Voluntary Pre-K — the negative result that should be better known

Lipsey, Farran & Hofer (2018), randomised via oversubscription lotteries,
~3,000 children. End-of-programme gains, then reversal: **by third grade the
treatment children scored *below* controls on achievement and had more
disciplinary infractions and special-education placements.**

This is a well-designed randomised study of a **scaled, state-run** programme
finding **harm**. It has had a small fraction of the attention given to Perry
Preschool, which had 123 children.

---

## The fade-out problem

Test-score gains from early interventions reliably shrink and usually vanish
within two to four years. Candidate explanations:

| Explanation | Assessment |
|---|---|
| **Control-group catch-up** | Controls learn the same content later. This is convergence, not loss. Well supported |
| **Non-sustaining environments** | Gains require a school environment that builds on them; ordinary schools don't. Well supported |
| **Skill decay** | Unpractised skills decay. Trivially true, hard to isolate |
| **Measurement ceiling** | Early tests measure content coverage, which converges by construction |
| **The active ingredient was never cognitive** | The strongest reading. Perry's IQ gains faded while crime, employment and education effects persisted. Something non-cognitive — self-regulation, expectations, school engagement, parental behaviour — carried the long-run effect |

**The recurring pattern across STAR, Perry and Head Start: test scores fade,
life outcomes persist.** If that is right, then evaluating early-childhood
programmes on test scores measures the wrong thing, and the field has spent
decades doing exactly that. **TIER 2** — it is a pattern across several studies,
not a demonstrated mechanism, and the Tennessee result shows it does not always
hold.

---

## Popular pedagogy, checked

| Intervention | Claim | Evidence |
|---|---|---|
| **Growth mindset** | Believing ability is malleable raises achievement | Sisk et al. (2018) meta-analysis: mean d ≈ 0.08 on achievement, near zero for most groups. Yeager et al. (2019, *Nature*), N = 12,490 US ninth-graders: ~0.10 GPA points for lower-achieving students. Real but tiny; large UK EEF trials null. **TIER 2, effect much smaller than the popular claim** |
| **Learning styles** | Match teaching to visual/auditory/kinaesthetic preference | Pashler et al. (2008): the required interaction has essentially never been demonstrated. **TIER 1 that it does not work.** Believed by a large majority of teachers |
| **Deliberate practice / "10,000 hours"** | Practice explains expertise | Macnamara, Hambrick & Oswald (2014) meta-analysis: practice explains ~26% of variance in games, 21% in music, 18% in sports, **4% in education, <1% in professions**. **TIER 1 that the strong version is false** |
| **Spacing and retrieval practice** | Distributed practice and testing beat restudying | Among the best-supported findings in all of education. **TIER 1** |
| **Phonics for early reading** | Systematic phonics instruction beats whole-language | Large converging evidence: US National Reading Panel (2000), UK Rose Review (2006), Ehri's meta-analyses, and the "science of reading" reversal in US districts from 2019 onward. **TIER 1** — and a case where the profession held a confident contrary position for thirty years |
| **Homework, primary school** | Raises achievement | Near-zero at primary level; modest at secondary (Cooper's reviews). **TIER 2** |
| **Grade retention** | Repeating a year helps strugglers | Generally negative on later outcomes and strongly predicts dropout. **TIER 2 that it harms** |
| **Small-group tutoring** | Intensive tutoring raises achievement | Among the largest reliable effects available, roughly 0.2-0.4 SD in good trials. Expensive; scaling degrades it. **TIER 1-2** |

---

## Where the popular story is wrong

| Popular story | Reality |
|---|---|
| "Hattie showed which interventions work best" | The rankings are built on incommensurable meta-analyses with known arithmetic errors. Use Kraft's benchmarks instead |
| "d = 0.4 is a decent effect in education" | For scaled interventions on standardised tests, d = 0.10 is a good result. The 0.4 convention comes from literatures inflated by researcher-made measures and small samples |
| "Perry Preschool proves universal pre-K works" | Perry was 123 children, in 1962, against a no-preschool counterfactual, with an unusually intensive programme. The best-designed test of a *scaled state programme* — Tennessee — found third-grade harm |
| "Early intervention gains fade, so it's pointless" | Test-score gains fade; several long-run designs find persisting effects on education, earnings, crime and health. Fade-out of the measure is not fade-out of the effect |
| "Class size reduction is a proven policy" | Proven in a randomised trial; failed when scaled in California, because scaling changed who was teaching |
| "Learning styles / brain-based learning" | No support. Widely believed by teachers, which is itself worth studying |
| "Schooling doesn't affect intelligence" | It does — roughly 1-5 IQ points per year, durably. One of the cleanest environmental effects in the notebook |
| "Growth mindset transforms outcomes" | d ≈ 0.08 on achievement in meta-analysis. It is a small effect that was marketed as a large one |

---

## Open questions

- [ ] Is the "fade-out of scores, persistence of outcomes" pattern real, or is it
      selective reporting across a small number of famous studies?
- [ ] What is the active ingredient in Perry and Abecedarian? Nobody knows, which
      is why nobody can reliably reproduce it at scale.
- [ ] Why did Tennessee VPK produce negative third-grade effects? Programme
      quality, counterfactual quality, or something about scaled provision?
- [ ] Does the schooling-to-IQ effect reflect general ability gains or
      test-relevant skill? The distinction matters enormously and is unresolved.
- [ ] Can tutoring effects survive scaling, or will they follow class-size
      reduction into dilution?
- [ ] How much of the education literature survives the researcher-made-measure
      correction? Nobody has re-run the canon with standardised outcomes only.
- [ ] What non-cognitive measure would actually capture what Perry changed? Until
      one exists, the mechanism claim is untestable.
