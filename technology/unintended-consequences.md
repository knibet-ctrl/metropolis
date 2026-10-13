# Unintended Consequences — The Core Pattern

> **Status: TIER 1** that rebound effects, induced demand and task-level
> displacement are real. **TIER 2** on their magnitudes, on risk compensation
> generally, and on the net employment effect of automation. **TIER 2–3** on
> the lead–crime hypothesis, which is presented here as contested and is not
> endorsed. **TIER 1** on the ozone case, which is the notebook's one clean
> success story.

**Written from general knowledge without live source verification.** The
elasticities, coefficients and effect sizes below are from memory. Directions
are more reliable than magnitudes.

---

## Why unintended consequences are the normal case, not an anomaly

The intended effect of a technology is the one everybody modelled, priced and
competed over. **It is therefore the effect most likely to be already reflected
in decisions, and least likely to generate surplus or damage.**

Three structural reasons the second-order effects dominate:

| Mechanism | Description | Example |
|---|---|---|
| **Behavioural response** | People re-optimise once the constraint moves. The engineering calculation assumes behaviour is fixed. It isn't | Rebound, induced demand, risk compensation |
| **General equilibrium** | The direct effect changes prices, which changes everything downstream | Cheap freight → offshoring → deindustrial politics |
| **Complementary adaptation** | Institutions and physical stock reorganise around the technology over decades, and the reorganisation is the actual change | Factory layout after unit-drive motors; sealed architecture after AC |

**Robert Merton, "The Unanticipated Consequences of Purposive Social Action"
(1936)** is the canonical statement, and his causes still hold up: ignorance,
error, immediate-interest override, basic-values override, and
**self-defeating prediction** (the forecast changes the behaviour it forecasts).

---

## 1. The Jevons paradox

**William Stanley Jevons, *The Coal Question* (1865).** Watt's engine made coal
use dramatically more efficient. Jevons observed that British coal consumption
had risen sharply, not fallen, and argued this was *because* of the efficiency
gain: cheaper effective power expanded the range of profitable applications.

**The modern term is the rebound effect.** Decompose it:

| Type | Mechanism | Typical estimate |
|---|---|---|
| **Direct rebound** | The service gets cheaper, so you consume more of it (drive more in an efficient car) | Roughly **10–30%** for household energy services in developed economies (Sorrell / UKERC review, 2007) |
| **Indirect rebound** | Money saved is spent on other energy-consuming things | Adds meaningfully; estimates vary widely |
| **Economy-wide rebound** | Cheaper energy services change the structure of production and growth | **Contested.** Plausibly large over long horizons |
| **Backfire (>100%)** | Consumption rises above the pre-efficiency level | **Rare in narrow modern cases; well attested for general-purpose technologies over long horizons** |

**The canonical backfire is lighting.** Nordhaus (1996) reconstructed the price
of light over centuries and found it fell by something like four orders of
magnitude. Fouquet & Pearson's UK work shows consumption of light rose by a
vastly larger factor than the efficiency gain. **We did not save energy on
lighting. We lit everything, all night, forever.**

**Tiering, precisely:**
- Rebound exists and is non-zero: **Tier 1.**
- Direct rebound of 10–30% for household energy: **Tier 1–2.**
- Economy-wide backfire as a general rule: **Tier 3. Do not assert it.**

**Policy implication, which is the honest version and annoys both sides:**
efficiency mandates deliver less than engineering estimates promise, but they
do not usually deliver *nothing*. If you want less consumption of X, price X.
Efficiency is a complement to pricing, not a substitute.

---

## 2. Induced demand in roads

The cleanest empirical case in the file.

**Duranton & Turner, "The Fundamental Law of Road Congestion" (*American
Economic Review*, 2011).** Using US metropolitan data with instruments for road
placement (1947 interstate plan, 1898 railroads, exploration routes), they
estimated the **elasticity of vehicle-kilometres travelled with respect to
lane-kilometres of interstate at approximately 1.0.**

**A 10% increase in road capacity produces roughly a 10% increase in driving.
Congestion returns to roughly where it started.**

Anthony Downs (1962) had described the mechanism as **triple convergence**:
after a road is widened, drivers converge from other routes, from other times
of day, and from other modes.

Where the induced traffic comes from:

| Source | Note |
|---|---|
| Route switching | Immediate |
| Time-of-day switching | Immediate — peak spreading reverses |
| Mode switching | Months. Transit ridership falls |
| Trip generation | Years. People make trips they previously skipped |
| **Land use** | **Decades. Development relocates to the new capacity, and this is the irreversible one** |

**The famous example — the Katy Freeway (I-10, Houston), widened to around 26
lanes at its widest by 2008, with travel times reportedly worse within a few
years — is real but the magnitudes are disputed** and it is cited far more
often than it is checked.

**Caveats, in fairness:** Duranton & Turner's elasticity applies to US
metropolitan interstates over roughly two decades. It should not be assumed
identical for rural roads, for developing-country networks with large latent
demand, or for a specific bypass. Cervero and others have argued the effect
varies substantially by context and horizon. **The direction is Tier 1; the
universal unit elasticity is not.**

**The general form, which transfers everywhere: adding capacity to a
congestible system that is rationed by queueing does not reduce the queue. It
increases throughput until the queue re-forms at the same tolerable length.**
This applies to hospital beds, bandwidth, email, and — plausibly — to
productivity tools.

---

## 3. Risk compensation and the Peltzman effect

**Present both sides. This is genuinely contested and it is frequently
overclaimed by people who like the counterintuitive story.**

### The claim

**Sam Peltzman (*JPE*, 1975)** analysed US automobile safety regulation (seat
belts, collapsible steering columns, dual braking) and argued that drivers
**offset** the safety gain by driving more aggressively, so that occupant
deaths fell but pedestrian and cyclist deaths rose and total deaths were
roughly unchanged. The general principle: **people have a target level of risk,
and a safety improvement is partly spent on more risk-taking rather than
banked as fewer deaths.**

### The case for

- The mechanism is theoretically sound: safety is an input to a utility
  calculation, not an exogenous good.
- **Aschenbrenner & Biehl's Munich taxi study**: taxis fitted with ABS were
  driven measurably more aggressively than the non-ABS control fleet, over
  three years of monitored driving. Direct behavioural evidence.
- Observed in narrow settings: helmeted skiers and cyclists sometimes ride
  faster; ABS and stability control shift accident patterns; safer climbing
  gear enabled harder routes.
- Related and better-established: **Sam Peltzman's insight generalises to
  moral hazard**, which is uncontroversial in insurance economics.

### The case against

- **Robertson (1977)** identified errors in Peltzman's specification, and
  subsequent work (**Crandall & Graham, 1984**) found the regulations *did*
  reduce fatalities, with at most **partial** offset.
- The long-run US and European data are unambiguous: **road deaths per
  vehicle-mile fell enormously across the era of safety regulation.** If full
  offset were real, that should not have happened.
- **Ian Walker's 2006–07 study** on drivers overtaking a helmeted vs
  un-helmeted cyclist is the most-cited compensation result in cycling, and it
  is weak: **n = 1 rider**, and a **2013 re-analysis by Olivier & Walter found
  the effect not practically significant.**
- Ski helmet studies are mixed and mostly find no meaningful speed compensation.

### The defensible conclusion

**Risk compensation is real, generally partial, and rarely complete.** Treat
"the safety device made things worse" as a claim requiring strong evidence in
each specific case, not as a general law.

**Where it is most likely to bite:** when the safety improvement is *salient*
to the person who controls the risk, when the benefit accrues to that same
person, and when there is an appetite for more of the risky activity. ABS is a
strong candidate. Seat belts are weaker. **Airbags and structural crash safety,
which the driver cannot feel, are the weakest candidates of all** — and this
distinction is the most useful thing in this section.

---

## 4. Automation displaces tasks, not jobs — and polarises

**The single most important correction in modern technology-and-labour
discussion.**

### The task framework

**Autor, Levy & Murnane (2003)** — the "ALM" paper. A job is a bundle of tasks.
Technology substitutes for some tasks and complements others. What matters is
not whether a *job* is "automatable" but the **task composition** of the job
and whether the non-automated tasks become more valuable.

The key distinction is **not skill level but routineness**:

| Task type | Example | Effect of computerisation |
|---|---|---|
| **Routine manual** | Assembly, machine operation, sorting | **Substituted.** Codifiable, repetitive |
| **Routine cognitive** | Bookkeeping, filing, basic clerical, bank telling | **Substituted.** Often middle-paying jobs |
| **Non-routine manual** | Cleaning, care work, food service, construction trades | **Hard to automate.** Requires dexterity and situational judgement — Moravec's paradox |
| **Non-routine cognitive** | Analysis, management, design, persuasion | **Complemented.** Made more valuable |

### The consequence: polarisation, not simple displacement

Because the substituted tasks clustered in the **middle** of the wage
distribution, the observable outcome was **job polarisation** — employment
growth at the top and the bottom, hollowing in the middle.

Documented for the UK by **Goos & Manning (2007)**, "Lousy and Lovely Jobs,"
and for the US by **Autor & Dorn (2013)**. Broadly replicated across Western
Europe. **This is Tier 1 as a description of 1980–2010.**

### The robot evidence, which is genuinely contested

| Study | Finding |
|---|---|
| **Acemoglu & Restrepo (2020, JPE)** | US commuting zones, 1990–2007. One additional robot per thousand workers reduced the employment-to-population ratio by roughly 0.2 percentage points and wages by roughly 0.4%. Aggregate estimate on the order of 400,000–670,000 jobs |
| **Graetz & Michaels (2018)** | 17 countries, 1993–2007. Robots raised labour productivity and value added; **no significant negative effect on aggregate hours**, though some effect on low-skill share |

**Both are respectable. They differ on data, geography and identification.
Anyone telling you the automation-employment question is settled is not
familiar with the literature.** Tier 2.

### The displacement/reinstatement frame

**Acemoglu & Restrepo's broader framework:** technology *displaces* labour from
tasks and *reinstates* labour by creating new tasks. Historically, reinstatement
kept up — the jobs that exist today mostly did not exist in 1900. Their concern
is that recent technology has been displacement-heavy and reinstatement-light,
partly because of tax and policy incentives favouring capital.

**Whether reinstatement continues is Tier 3.** It has always worked before, and
"it has always worked before" is exactly the reasoning that fails at regime
changes. **Both the "this time is different" and the "it never is" positions
are unfalsifiable in advance.** Cross-ref `risk/base-rates.md`: the base rate
strongly favours reinstatement, and base rates fail precisely when the
generating process changes.

---

## 5. Leaded petrol and the crime hypothesis

**Presented as Tier 2–3 and explicitly not endorsed. This section exists partly
to demonstrate how to handle a seductive hypothesis honestly.**

### The uncontested part — Tier 1

- **Thomas Midgley Jr.** developed tetraethyl lead as an anti-knock additive in
  **1921** (General Motors, then the Ethyl Corporation with DuPont and Standard
  Oil). Workers at the production plants died of acute lead poisoning in the
  1920s; the plants were nicknamed accordingly. **The dangers were known
  immediately and were suppressed commercially for decades**, largely through
  Robert Kehoe's industry-funded research programme.
- **Clair Patterson**, working on the age of the Earth via lead isotopes,
  established in the 1960s that atmospheric and environmental lead was
  overwhelmingly industrial in origin. He was punished professionally for it.
- **Lead is a potent neurotoxin with no safe threshold.** It reduces IQ,
  impairs executive function and increases impulsivity and aggression in
  children. **Herbert Needleman's** work established the dose-response
  relationship. **This is Tier 1 and not disputed by anyone serious.**
- US phase-out ran roughly 1973–1996. **Global elimination completed in 2021**
  (Algeria last). Removing lead from petrol is one of the largest public health
  wins in history on its own terms, independent of any crime claim.

### The contested part — Tier 2–3

**Rick Nevin (2000, 2007)** and **Jessica Wolpaw Reyes (2007)** argued that the
rise and fall of atmospheric lead, lagged by about 20 years, tracks the rise
and fall of violent crime — across multiple countries — and that lead explains
a large share of the late-20th-century crime decline.

**Why it is seductive:** the lag is mechanistically motivated (exposure in
early childhood, offending in late adolescence), the correlation is
international, and there is a plausible biological pathway.

**Why to hold it loosely:**

| Problem | Detail |
|---|---|
| **Ecological correlation** | Aggregate time series with a fitted lag will match many pairs of rising-then-falling curves. Degrees of freedom in choosing the lag are a serious issue |
| **Publication bias** | **Higney, Hanley & Moro (2022)** meta-analysed the lead–crime literature and found strong evidence of publication bias; the corrected effect is **much smaller** than the headline claims |
| **Competing explanations** | The crime decline has many candidates: policing changes, incarceration, demographics, the crack epidemic's end, improved emergency medicine converting homicides into assaults, economic conditions. **Steven Levitt's abortion hypothesis is a cautionary parallel** — high-profile, and substantially damaged by the Foote & Goetz coding-error critique |
| **Overdetermination** | If lead explains most of it, and abortion explains most of it, and incarceration explains most of it, at least two are wrong |

**Position: lead poisoning is a Tier 1 catastrophe on IQ and health grounds
alone. The strong crime claim is Tier 2 at best and probably Tier 3 at the
magnitudes usually quoted. You do not need the crime claim to condemn leaded
petrol, and reaching for it weakens the case.**

**The real lesson from Midgley is different and larger: the same man invented
tetraethyl lead and, in 1928, chlorofluorocarbons.** Both were *safety
improvements* on their alternatives — CFCs replaced ammonia and sulphur dioxide
refrigerants that were killing people in domestic accidents. **He solved two
real problems and created two of the largest environmental harms of the
century.** That is the pattern, not a villain story.

---

## 6. CFCs and ozone — the one that worked

The single clean success in this notebook, and it deserves close attention
because it is the template everybody wants and cannot generalise.

| Year | Event |
|---|---|
| 1928 | Midgley develops CFCs as a non-toxic, non-flammable refrigerant. A genuine safety advance |
| 1974 | **Molina & Rowland** publish in *Nature*: CFCs are inert enough to reach the stratosphere, where UV frees chlorine, which catalytically destroys ozone. **One chlorine atom destroys many thousands of ozone molecules** |
| 1985 | **Farman, Gardiner & Shanklin** (British Antarctic Survey) report the Antarctic ozone hole — from ground-based instruments. **Satellite data had recorded it but automated quality control was discarding the readings as implausible errors.** A permanent lesson about outlier rejection |
| 1987 | **Montreal Protocol.** Eventually ratified by every UN member state — the only treaty with that status |
| 1990–92 | London and Copenhagen amendments accelerate the phase-out |
| Ongoing | Ozone layer projected to recover to 1980 levels around mid-century globally and around the 2060s over Antarctica |
| 2016 | **Kigali Amendment** — because the HFC replacements turned out to be potent greenhouse gases |

### Why it worked — and why it does not generalise

| Factor | Ozone | Climate |
|---|---|---|
| Number of producers | Small handful of chemical firms | Effectively every economic actor |
| Substitutes | Available, and patentable — **DuPont had a commercial interest in the transition** | Partial, and cheap fossil incumbents |
| Cost of action | Modest, concentrated | Enormous, diffuse |
| Public image | **"A hole."** Visceral, spatial, immediately comprehensible | Diffuse, statistical, slow |
| Self-interest of rich countries | Direct: skin cancer in fair-skinned populations | Diffuse and delayed |
| Attribution | Clean chemistry, single mechanism | Multi-causal, contested |

**The honest reading: Montreal succeeded because it was easy, not because
humanity is capable of collective action on hard problems. Citing it as
precedent for climate is a category error.**

**And note the ending: the fix required a fix.** CFCs replaced dangerous
refrigerants; HFCs replaced CFCs and turned out to be greenhouse gases 1,000+
times more potent than CO₂ per molecule; Kigali replaces the HFCs. **Three
generations of solution, each creating the next problem. Ellul's
self-augmentation, demonstrated in a case where the system nonetheless
worked.**

---

## Where the popular story is wrong

| Popular story | Correction |
|---|---|
| **"Efficiency reduces consumption"** | Frequently the opposite, and reliably less than the engineering estimate. Price the thing you want less of |
| **"Building roads reduces congestion"** | Elasticity near 1.0 at metropolitan scale. This is one of the best-identified results in urban economics and is ignored in essentially every road-widening business case |
| **"Safety regulation is defeated by risk compensation"** | Offset is usually partial. Road deaths per mile fell enormously. Peltzman's strong version did not survive |
| **"Risk compensation is a myth"** | Also wrong. The ABS evidence is real. It depends on salience and who bears the risk |
| **"Robots are taking the jobs"** | Tasks, not jobs — and the observable historical effect was polarisation, not net destruction. Whether that continues is genuinely unknown |
| **"Lead explains the crime decline"** | Overclaimed. Meta-analysis finds substantial publication bias. Lead is a catastrophe for other, better-established reasons |
| **"Montreal proves we can solve climate"** | Montreal proves we can solve problems with few producers, cheap substitutes, a vivid image and rich-country self-interest. Climate has none of those |
| **"Unintended consequences mean we shouldn't act"** | No. It means model the behavioural response, build in reversal capacity, and monitor. Inaction has second-order effects too |

---

## Open questions

- [ ] Is economy-wide rebound for information technology large or small? Nobody
      has a credible estimate and it bears directly on AI energy projections.
- [ ] Does the Duranton–Turner unit elasticity hold outside US metropolitan
      interstates, and over what horizon does the land-use channel dominate?
- [ ] Is there a general predictor of *when* risk compensation will be large —
      salience? controllability? — that would let it be forecast rather than
      discovered?
- [ ] Has reinstatement of new tasks slowed measurably since 1980, or does the
      appearance of slowing reflect measurement lag in identifying new
      occupations?
- [ ] What is the post-publication-bias-correction effect size for lead on
      crime? If it is small but non-zero, what does that imply for current
      lead exposure in low-income countries?
- [ ] Are there other Montreal-shaped problems currently unsolved — few
      producers, cheap substitutes, vivid harm — that nobody has organised
      around? This seems like a searchable question with real payoff.
