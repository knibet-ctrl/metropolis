# The Questions — Disaggregating "How Do I Be Healthy?"

> **Status: TIER 1** that the question needs splitting. **TIER 2** on where
> exactly the lines fall and how much the sub-questions conflict.

> **Not medical advice.** This file is about how to formulate a question, not
> about what to do. Personal decisions belong with a clinician who knows your
> history.

> **The finding: "how do I be healthy?" is at least five questions with
> different evidence bases, different measurement problems, and — critically —
> *different answers that sometimes point in opposite directions*. Most health
> advice fails by answering one of them while the reader was asking another.**

---

## The five questions

| # | Question | Outcome measured | Evidence quality | Who studies it |
|---|---|---|---|---|
| 1 | **Lifespan** — how long until I die? | All-cause mortality | **Best available.** Death is unambiguous, universally recorded, and cannot be gamed | Epidemiology, large RCTs |
| 2 | **Healthspan** — how long until I stop functioning well? | Disability-free years, frailty indices, HALE | **Poor.** No agreed definition, no standard instrument, almost no trial endpoints | Gerontology, health economics |
| 3 | **Day-to-day function** — how do I feel and perform today? | Energy, cognition, pain, mood, capacity | **Mixed.** Measurable but subjective, huge placebo component, short trials | Sports science, sleep medicine |
| 4 | **Disease risk** — what is my probability of X? | Incidence of specific disease | **Good for common diseases, terrible for rare ones** | Clinical epidemiology |
| 5 | **Subjective wellbeing** — is my life going well? | Life satisfaction, affect, meaning | **Reasonable psychometrics, weak causal evidence** | Psychology, economics |

---

## Why the split matters: the conflicts are real

**These are not five labels on one thing. They come apart.**

| Conflict | What it looks like |
|---|---|
| **Lifespan vs day-to-day function** | Aggressive blood pressure or lipid control may extend life while producing side effects that make today worse. This is a genuine trade-off, not a failure of medicine, and different patients rationally choose differently |
| **Lifespan vs healthspan** | Successfully treating fatal disease can convert a quick death into a long decline. **Medicine's greatest successes have partly produced dementia as a mass condition** — by keeping people alive long enough to get it |
| **Disease risk vs subjective wellbeing** | Screening reduces some disease-specific mortality and reliably produces anxiety, false positives, and overtreatment. The person who is told they might have cancer and doesn't has paid a real cost for someone else's benefit |
| **Function vs longevity** | Very high training loads improve performance now and have no demonstrated mortality benefit over moderate loads — possibly a small cost in some cohorts. **Athletic optimisation and longevity optimisation are different projects** |
| **Wellbeing vs everything** | Alcohol, most obviously. Also: the person for whom a restrictive diet destroys their social life may have bought disease-risk reduction with wellbeing. Nobody prices this in the guidelines |
| **Individual vs population** | A screening programme with a positive net effect across a million people still harms a substantial number of them. "Good policy" and "good for you" are different claims |

---

## Evidence quality by sub-question, in detail

### 1. Lifespan — the gold standard, and why

All-cause mortality is the only outcome in this notebook that is essentially
immune to the usual corruptions:

- **It cannot be redefined.** Diagnostic thresholds for hypertension,
  pre-diabetes, and osteoporosis have all been moved. Death has not.
- **It cannot be substituted.** No surrogate. See the-control-group.md on CAST,
  where a drug that fixed the surrogate killed the patients.
- **It captures harms as well as benefits.** A treatment that prevents one
  disease and causes another looks good on disease-specific mortality and bad on
  all-cause. **Disease-specific mortality is the single most misleading endpoint
  in common use.**
- **It is recorded whether or not the researcher wants it to be.**

**The cost:** all-cause mortality trials need enormous samples and long
follow-up, so almost nothing is powered for it. This is why most of what you
read uses something weaker.

### 2. Healthspan — the most important question, the worst evidence

**There is no agreed operational definition of healthspan.** Candidates include
disability-free life expectancy, years free of major chronic disease, frailty
index thresholds, and WHO's HALE. They give different answers and are not
interchangeable.

The **compression of morbidity** hypothesis (James Fries, *NEJM*, 1980) proposed
that as lifespan extends, the period of disability compresses toward the end.
**Whether this has actually happened is contested and appears to vary by country
and cohort.** Some data suggest expansion of morbidity instead — more years
alive, more of them impaired. This is arguably the most consequential open
question in the whole notebook and it is not settled.

**Practical consequence:** almost every longevity intervention marketed on
healthspan is being sold against an endpoint that nobody can measure.

### 3. Day-to-day function — high value, weak signal

This is what most people actually want and it has the worst signal-to-noise:

- Outcomes are self-reported and highly susceptible to expectancy.
- Trials are short, small, and unblinded — you know whether you did the workout.
- Regression to the mean dominates. **People try interventions when they feel
  worst, and feeling worst is followed by feeling better regardless.**
- No commercial incentive to run a proper trial on something unpatentable.

Exceptions where evidence is genuinely decent: sleep deprivation and cognitive
performance, caffeine, and exercise capacity. See sleep.md and exercise.md.

### 4. Disease risk — good methods, terrible communication

The methods here are the most mature in the file. **The failure is almost
entirely in translation.** Relative risks are reported without base rates; risk
factors are described as diseases; and the difference between "raises risk" and
"causes" is systematically collapsed. See evidence-hierarchy.md for the
arithmetic.

**A specific structural problem:** most risk factors are studied one at a time,
but bodies experience all of them at once, and the effects are not additive.
There is no adequate model of the joint distribution.

### 5. Subjective wellbeing — real, measurable, causally opaque

Life-satisfaction scales are more reliable than sceptics assume — they correlate
with informant reports, physiological measures, and behaviour. The problem is
causal identification. Almost everything associated with wellbeing (health,
income, marriage, friendship) is bidirectionally caused.

**The one finding that keeps surviving:** social connection. Holt-Lunstad et al.
(2010) meta-analysed 148 studies and found roughly **50% greater odds of
survival** for people with stronger social relationships — an effect comparable
to smoking cessation in magnitude. **It is observational, and the reverse-causal
story (sick and unhappy people lose friends) is entirely plausible.** It is on
my TIER 1 list anyway, with the caveat attached, because the effect is large,
consistent across designs, and the intervention is harmless. See
existence/society.md.

---

## The questions people think they are asking, and what they are actually asking

| What they say | What they usually mean | Which question |
|---|---|---|
| "Is coffee good for me?" | Will this kill me sooner? | 1, weakly |
| "What's the best diet?" | How do I lose weight without being miserable? | Mostly 3 and 5, framed as 4 |
| "Should I take vitamin D?" | Is there a cheap thing I'm missing? | 4, answered by RCTs: mostly no |
| "How do I get more energy?" | Why do I feel bad? | 3 — and often the answer is sleep, or a treatable condition |
| "Will this make me live longer?" | Will I be *fine* for longer? | They mean 2; the evidence only speaks to 1 |
| "Is X bad for me?" | Should I feel guilty? | Frequently not an evidence question at all |

**The last row is not a joke.** A meaningful fraction of health questions are
requests for permission or absolution. They cannot be answered with data and
data given in response tends to be ignored.

---

## The question this notebook cannot answer

**"What should I, specifically, do?"** Every file here reports population-level
evidence. Applying it to one person requires: their baseline risk, their
competing risks, their comorbidities, their medications and interactions, their
values about the trade-offs above, and their tolerance for side effects.

**That is a clinical judgement and it needs a clinician.** A notebook that
pretends otherwise is worse than no notebook.

---

## Where the popular story is wrong

| Popular belief | Reality |
|---|---|
| "Healthy" is one thing | It is at least five things that trade off against each other |
| Living longer and staying well are the same goal | They diverge, and medicine has historically been much better at the first |
| More health information leads to better decisions | Beyond a small core, added information mostly adds anxiety and false positives. See medicine-and-screening.md |
| Personalised advice is available now | Precision medicine works in a few oncology and pharmacogenomic niches. Consumer "personalisation" is almost entirely marketing — DIETFITS specifically tested genotype-matched diets and found nothing |
| If a study measured *something*, it measured health | Most measure a surrogate: cholesterol, blood glucose, bone density, a biomarker. Surrogates have an appalling track record. See the-control-group.md |
| Feeling better means it's working | Regression to the mean plus expectancy plus natural history explain most perceived improvement in most conditions |
| The question is which intervention to add | For most people the highest-value moves are subtractions and the removal of a single risk factor, not additions |

---

## Open questions

- [ ] **Has morbidity actually compressed or expanded?** Fries (1980) versus the expansion hypothesis. Country-dependent, cohort-dependent, and not resolved. **The most consequential unanswered question in the notebook.**
- [ ] Can healthspan be operationalised well enough to serve as a trial endpoint? Without this, no longevity drug can be evaluated except on mortality, which requires decades.
- [ ] How much of the lifespan–healthspan gap is medicine's doing? Keeping people alive through cardiovascular disease plausibly increased dementia prevalence. Nobody has cleanly attributed this.
- [ ] Do people's stated trade-off preferences match their revealed ones? The screening literature suggests strongly not — people say they want the information and are harmed by it.
- [ ] Is subjective wellbeing causally upstream of physical health, downstream, or both? The instruments exist; the identification strategy does not.
- [ ] **What would a good measure of "function today" look like?** Grip strength, gait speed and VO2max are the best proxies, are all physical, and miss cognition and mood entirely.
- [ ] How much do the five questions correlate at the individual level rather than the population level? Nearly all the data is population-level and the assumption of transfer is untested.
