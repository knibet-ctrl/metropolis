# The Evidence Hierarchy — Why Most Health Findings Are Wrong

> **Status: TIER 1** on the mechanisms of error described here. **TIER 2** on
> how much each contributes in any given case. This file is methodology, and
> methodology is the most robust content in the notebook.

> **Not medical advice.** This file teaches you to evaluate claims, including
> the claims in the rest of this notebook. It does not tell you what to do.

> **The most important file here. Every other file depends on it.** If you read
> one thing, read this. The single distinction that does the most work in the
> entire field is **observational correlation versus randomised trial**, and
> almost all popular health coverage collapses it.

---

## The hierarchy, ranked

| Rank | Design | What it can establish | Failure modes |
|---|---|---|---|
| 1 | **Large RCT, hard outcome (death, MI, stroke, fracture), pre-registered, blinded, intention-to-treat** | Causation, in the population studied | Generalisability; trial populations are healthier and better-monitored than real patients |
| 2 | **Meta-analysis of such trials** | Causation with tighter intervals | Garbage in, garbage out. Heterogeneity. Publication bias in the inputs |
| 3 | **RCT with surrogate outcome** (LDL, HbA1c, bone density, PVC suppression) | That the drug does what it does | **The single most dangerous rank.** See CAST, torcetrapib, rosiglitazone in the-control-group.md |
| 4 | **Mendelian randomisation** | Causation, for lifelong exposure to a genetically-proxied variable | Pleiotropy; canalisation; answers a lifelong-exposure question, not a "start at 50" question |
| 5 | **Prospective cohort, objective exposure measurement** | Association; hypothesis generation | Confounding, healthy-user bias, reverse causation |
| 6 | **Prospective cohort, self-reported exposure (most nutrition)** | Very little | All of the above plus measurement error that can exceed the effect |
| 7 | **Case-control** | Association, with recall bias baked in | Sick people remember exposures differently |
| 8 | **Cross-sectional / ecological** | Almost nothing causal | Ecological fallacy. Correlation of country-level averages |
| 9 | **Mechanistic / animal / in vitro** | That a pathway exists | **Mice are not small humans.** Most oncology and ageing findings die here |
| 10 | **Expert opinion, case series, testimonial** | Nothing | Selection on the outcome |

**Note the gap between rank 4 and rank 5.** That gap is where most of the health
industry lives.

---

## The five mechanisms that kill observational health research

### 1. Confounding

The exposure travels with something else that does the causal work.

**Canonical case:** for decades, moderate wine drinkers had lower cardiovascular
mortality. They also had higher incomes, more education, better housing, better
access to care, lower smoking rates, and different social networks. Statistical
adjustment removes *measured* confounders imperfectly and *unmeasured* ones not
at all. **Residual confounding is unbounded — you cannot put an error bar on
what you didn't measure.**

### 2. Healthy-user bias — the most under-appreciated

**People who do one recommended thing do all the recommended things.** The kind
of person who takes a daily supplement is also the kind who wears a seatbelt,
attends screenings, and fills prescriptions.

**The demonstration that ends the argument:** the **Coronary Drug Project**
(1980), a placebo-controlled trial of clofibrate. Among patients *in the placebo
arm*, those who took their placebo reliably had **five-year mortality around 15%
versus around 28% for poor adherers.†** Adjusted for forty baseline covariates,
the gap persisted.

**Taking a sugar pill as directed nearly halved mortality.** There is no
pharmacology here. Adherence is a marker for something enormous and unmeasured.
Every observational study of a health behaviour is contaminated by this effect,
and it is roughly the size of the effects being reported.

### 3. Reverse causation

The disease causes the exposure, not the other way round.

| Observed | Likely reverse story |
|---|---|
| Low vitamin D predicts almost every disease | Illness reduces outdoor activity, mobility, and adiposity-adjusted D levels. VITAL (n=25,871) supplemented and found nothing |
| Low cholesterol predicts cancer mortality | Undiagnosed cancer lowers cholesterol for years before diagnosis |
| Long sleep predicts mortality | Illness causes long sleep |
| Being underweight predicts mortality | Cachexia from undiagnosed disease |
| Non-drinkers have worse outcomes | **The "sick quitter": abstainer categories in old cohorts contained former heavy drinkers who stopped because they were ill** |

Standard fix: exclude the first few years of follow-up and early events. It
helps and does not solve it, because the pre-clinical phase of many diseases is
a decade or more.

### 4. Measurement error — the food frequency questionnaire problem

Most nutritional epidemiology rests on the **FFQ**: a person recalls, on one
occasion, their average consumption frequency of ~100+ foods over the past year.

| Problem | Consequence |
|---|---|
| People cannot recall this | Correlations with weighed intake records are often in the 0.4–0.6 range† — for the *good* nutrients |
| Systematic under-reporting | Under-reporting scales with body weight and with social desirability. **Obese participants under-report energy intake more, which builds a spurious inverse relationship between reported calories and weight into the data** |
| Implausible totals | Archer et al.'s NHANES analyses concluded a large fraction of reported energy intakes were physiologically incompatible with survival† |
| Portion sizes are guessed | Grams are inferred from a picture |
| The instrument is the exposure | There is no independent gold standard for most nutrients |

**Ioannidis's 2018 *JAMA* editorial** on nutritional epidemiology is the
canonical statement of the problem. The counter-argument from the field is
serious: non-differential measurement error usually biases toward the null, so a
detected signal may be an underestimate. **The counter-counter-argument is that
the error is not non-differential** — it correlates with body weight, health
consciousness and social class, which is exactly the worst case.

### 5. Multiple comparisons and researcher degrees of freedom

A single cohort with 130 food items and 40 outcomes offers 5,200 primary
comparisons before you consider covariate sets, subgroups, and modelling
choices. **At p<0.05 you expect 260 significant findings from pure noise.**

- **Vibration of effects** (Patel, Burford & Ioannidis, 2015): re-analysing the
  same association under all plausible covariate combinations produces hazard
  ratios spanning both sides of 1 for many exposures. **The analyst's covariate
  choice determines the sign.**
- Schoenfeld & Ioannidis (2013) picked 50 ingredients from random cookbook
  recipes; **40 had published studies linking them to cancer risk**, in both
  directions, mostly with wide intervals.
- Almost nothing in nutritional epidemiology is pre-registered.

---

## Randomised trials and their limits

RCTs are the top of the hierarchy. They are not oracles.

| Limit | Detail |
|---|---|
| **Duration** | Diet and lifestyle act over decades; trials run 2–5 years. A null result may mean "no effect" or "not yet" |
| **Adherence** | Long diet trials have severe drift. By year 4, arms converge and the trial becomes a comparison of intentions |
| **Intention-to-treat dilutes** | Correct for validity, but it estimates the effect of *offering* the intervention, not of receiving it |
| **Blinding is often impossible** | You know if you're exercising, eating differently, or in therapy. Expectancy effects are unblinded into the outcome |
| **Populations are selected** | Trial participants are healthier, more adherent and better monitored. Effect sizes shrink in the real world |
| **Composite endpoints** | "Major adverse cardiovascular events" can be driven entirely by the softest component (revascularisation, often decided by an unblinded clinician) |
| **Early stopping inflates effects** | Trials stopped early for benefit systematically overestimate it |
| **Industry funding shifts results** | Well documented across drugs and nutrition. Not fraud usually — design choices, comparator selection, dose selection, and which trials get finished |
| **Sham controls are rare in surgery** | And when they are run, procedures frequently fail. See ORBITA, Moseley, FIDELITY, vertebroplasty in the-control-group.md |

---

## Mendelian randomisation — the useful middle

**The idea:** genetic variants are allocated at conception, roughly at random
with respect to lifestyle and social class. If a variant that raises LDL also
raises heart disease, and does so in proportion, that supports causation without
a trial.

| MR verdict | Exposure | Status |
|---|---|---|
| **Supported** | LDL cholesterol → cardiovascular disease | Concordant with statin, ezetimibe and PCSK9 trials. **The strongest triangulation in cardiology** |
| **Supported** | Body mass index → many outcomes | Broadly consistent with the observational picture |
| **Supported** | Blood pressure → stroke and CVD | Concordant with trials |
| **Refuted** | HDL cholesterol → protection | MR found no causal effect. Then CETP inhibitors — torcetrapib, dalcetrapib, evacetrapib — raised HDL substantially and failed or harmed. **"Good cholesterol" was a correlation** |
| **Refuted** | Moderate alcohol → cardioprotection | ALDH2 variant studies in East Asian populations find lower alcohol exposure associated with *better* cardiovascular outcomes |
| **Refuted / null** | Vitamin D → most outcomes | Consistent with VITAL and D-Health nulls |
| **Complicated** | Longer telomeres | Lower risk for some CVD, **higher risk for several cancers** (Haycock et al., 2017). See ageing.md |

**Limits:** pleiotropy (the variant does other things), lifelong exposure ≠
mid-life intervention, and mostly European-ancestry samples.

---

## Relative versus absolute risk — worked in full

**This is the most reliably exploited gap in health communication.**

In 2015 the IARC classified processed meat as a **Group 1 carcinogen** — the
same *hazard* category as tobacco. Headlines followed. The underlying figure was
approximately an **18% increase in colorectal cancer risk per 50 g/day
consumed.**

Work it:

$$\text{Baseline lifetime colorectal cancer risk} \approx 5\% \quad (5 \text{ in } 100)$$

$$\text{Relative risk} = 1.18$$

$$\text{New risk} = 5\% \times 1.18 = 5.9\%$$

$$\text{Absolute risk increase} = 0.9 \text{ percentage points} \approx 1 \text{ extra case per } 111 \text{ people}$$

**"18% increase" and "one extra case per ~111 lifetime bacon-eaters" are the
same number.** One sells papers.

**And the Group 1 classification does not mean what readers think.** IARC
categorises **hazard** — whether a thing can cause cancer at *some* dose — not
**risk** — how much it does at realistic doses. Tobacco and processed meat share
a category and differ in magnitude by more than an order of magnitude.

### The general rule

$$\text{Absolute risk change} = \text{Baseline risk} \times (\text{RR} - 1)$$

**A 50% increase on a 0.2% baseline:**

$$0.2\% \times 0.5 = 0.1 \text{ percentage points} = 1 \text{ extra case per } 1{,}000$$

A 50% increase sounds like half of everything. It is one in a thousand. **Any
report of a relative risk without a baseline is uninterpretable, and the
omission is almost never accidental.**

---

## Number needed to treat

$$\text{NNT} = \frac{1}{\text{Absolute Risk Reduction}}$$

| Intervention | Approximate NNT | Note |
|---|---|---|
| Statin, secondary prevention, ~5 years, major vascular event | ~30–40† | Genuinely good |
| Statin, primary prevention, low baseline risk, ~5 years | 100–250+† | Depends almost entirely on baseline risk |
| Antibiotics for sore throat, to prevent one complication | Thousands† | Which is why prescribing has changed |
| Mammography screening, 10 years, one breast cancer death avoided | ~1,000+ women screened† | With substantial overdiagnosis alongside |

**NNT is not a property of a drug. It is a property of a drug in a population.**
The same statin has an NNT of 30 in a post-MI patient and 250 in a healthy
40-year-old, because baseline risk is doing the work. **This is why "statins
don't work" and "statins are lifesaving" are both defensible sentences about
different populations, and why arguing about the drug is the wrong argument.**

Its mirror, **NNH** (number needed to harm), is reported far less often. A
complete picture requires both.

---

## How to read a health headline — the checklist

1. **Randomised or observational?** If observational, apply a heavy discount and
   read on mostly for the hypothesis.
2. **What was actually measured?** Death and events, or a biomarker? If a
   biomarker, the finding is a hypothesis about a hypothesis.
3. **What is the absolute risk?** If not stated, find it before forming a view.
4. **Compared to what?** Placebo, standard care, or nothing? Comparator choice
   is where industry trials do most of their work.
5. **How many people, and for how long?** n=20 for two weeks and n=25,000 for
   five years are different objects.
6. **Was it pre-registered?** If not, assume the analysis was chosen after
   seeing the data, because usually it was.
7. **Is the outcome a composite?** If so, which component moved?
8. **Who funded it, and does the study exist because someone can sell the
   answer?**
9. **Does it agree with the RCTs?** For nutrition, check whether a trial exists
   at all before treating the cohort finding as a fact.
10. **Would you have heard about the null version?** Almost certainly not. **The
    findings you see are a biased sample of the findings that exist.**

---

## Where the popular story is wrong

| Popular belief | Reality |
|---|---|
| "Studies show" is meaningful | Meaningless without the design. A study showed hormone replacement prevented heart disease. A trial showed the opposite |
| Big studies are reliable studies | A 500,000-person cohort with a food questionnaire is a very precise estimate of a biased quantity. **Size fixes noise, not bias** |
| Meta-analysis settles arguments | It averages the literature, including its publication bias. A meta-analysis of biased studies is a precise bias |
| Correlation "suggests" causation | It constrains it slightly. Young & Karr found 52 observational claims tested in RCTs and **none confirmed** |
| Adjusting for confounders handles confounding | Only for measured confounders, only if measured well, only if modelled correctly. Residual confounding routinely exceeds the effect being reported |
| "Linked to cancer" means dangerous | IARC classifies hazard, not risk. Processed meat and plutonium share a category |
| p < 0.05 means real | It means "unlikely under the null, given this one analysis." With 5,200 comparisons and flexible covariates, it means very little |
| A biomarker improvement is a health improvement | CAST suppressed the arrhythmia and killed people. Torcetrapib raised HDL and killed people. **Surrogates have a body count** |
| Personal anecdote is weak evidence | It is not weak evidence. For most questions it is **no** evidence — n=1, unblinded, uncontrolled, with regression to the mean and natural history unaccounted |
| Scientists disagree, so nobody knows | Sometimes true (salt). Frequently false (smoking, blood pressure, vaccination), where "disagreement" is manufactured or is one contrarian against a field |

---

## Open questions

- [ ] **Is nutritional epidemiology salvageable, or should the field be rebuilt around trials and metabolomic biomarkers?** Ioannidis says rebuild; the field says the tools are improving. **The strongest live methodological argument in health research.**
- [ ] Does non-differential measurement error really bias to the null in FFQ data, or is the error differential in the ways that matter? This is the crux and it is not resolved.
- [ ] How large is residual confounding, quantitatively? The negative-control-outcome literature is the best attempt and remains rare.
- [ ] Can Mendelian randomisation answer intervention questions, or only lifelong-exposure ones? The LDL case suggests some transfer; nobody knows the general conditions.
- [ ] Why has adoption of absolute-risk reporting failed after thirty years of advocacy? Gigerenzer's format work shows it helps. **Nobody does it.** The incentives explain more than the ignorance does.
- [ ] What fraction of current TIER 1 health claims will reverse? Prasad's 40% figure is for practices that got tested. **The untested majority has no error bar at all.**
- [ ] Would mandatory pre-registration of observational analyses work, or would it just move the flexibility upstream into data collection?
