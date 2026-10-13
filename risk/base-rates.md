# Base Rates — The Outside View

> **Status: TIER 1.** This is the strongest, most replicated, most immediately
> useful finding in the entire notebook. It is also the most ignored.

> **The claim, stated flatly:** for almost any prediction about a project, a
> person, a company or a plan, **the average outcome of similar past cases is a
> better forecast than a detailed analysis of this case.** Not a supplement to
> it. Better than it.

---

## Inside view vs outside view

Kahneman and Tversky's distinction (developed through the 1970s; the canonical
statement is "Intuitive Prediction: Biases and Corrective Procedures," 1979).

| | Inside view | Outside view |
|---|---|---|
| **Method** | Model this case from its specifics. Break the plan into steps, estimate each | Find the reference class. Ask what happened to similar cases |
| **Feels** | Informative, rigorous, engaged, *responsible* | Crude, lazy, insulting, "you don't understand our situation" |
| **Actually is** | Systematically optimistic. Ignores unknown unknowns by construction | Boring and much more accurate |
| **Failure mode** | Cannot see what isn't in the plan | Wrong reference class; genuine novelty |

**Why the inside view fails is structural, not psychological.** A plan is a list
of things you thought of. Delays come overwhelmingly from things you did not
think of. **The inside view is a sum over the known unknowns and is blind to the
unknown unknowns by definition.** The base rate contains both, because it is
measured from outcomes rather than assembled from steps.

### Kahneman's own case — the best illustration and it's self-incriminating

Mid-1970s, Israel. Kahneman assembled a team to write a school textbook on
judgement and decision-making. After about a year, he asked everyone to
privately estimate the completion date. Estimates clustered at **18 to 30
months**.

He then asked Seymour Fox, Dean of the Hebrew University School of Education,
who was on the team, about comparable projects. Fox's answer:

- Of teams he knew of, roughly **40% never finished at all.**
- Of those that did, none took less than **seven years**; typical was **seven to
  ten.**

Asked whether this team was better than average, Fox said it was below average
on resources.

**The team continued anyway.** It took **eight years**. The curriculum was never
used.

**Note what happened: they received an accurate outside-view forecast, from an
expert, in the room, and ignored it.** The base rate does not fail because it is
unavailable. It fails because it is unwelcome. That is the whole problem.

---

## Flyvbjerg's data — the strongest empirical case

Bent Flyvbjerg (Aalborg, later Oxford). *"Underestimating Costs in Public Works
Projects: Error or Lie?"* (Journal of the American Planning Association, 2002).
258 transport infrastructure projects, 20 countries, spanning roughly 1927–1998.

| Project type | Average cost overrun | Notes |
|---|---|---|
| **Rail** | **+44.7%** | Standard deviation ~38%. Passenger forecasts also overstated, typically by more than half |
| **Bridges and tunnels** | **+33.8%** | Standard deviation ~62% — the fattest tail of the three |
| **Roads** | **+20.4%** | Standard deviation ~30% |

Two findings that matter more than the averages:

1. **Roughly 9 out of 10 projects came in over budget.** This is not a symmetric
   estimation error. Symmetric error would give ~50%.
2. **There was no improvement over seventy years.** Not with better software,
   better project management, better data. **A seventy-year flat line is not a
   learning problem. It is an incentive problem.**

Flyvbjerg's later database (reported in *How Big Things Get Done*, 2023, with
Dan Gardner), 16,000+ projects across dozens of types:

| Criterion | Share of projects meeting it |
|---|---|
| On budget | **~48%** |
| On budget **and** on time | **~8.5%** |
| On budget, on time, **and** delivering promised benefits | **~0.5%** |

**One in two hundred.** *(These figures are from memory and are load-bearing —
check them before citing.)*

Worst tails by category: **nuclear power plants, Olympic Games, nuclear waste
storage, and large IT.** Best: **solar, wind, roads, pipelines, transmission** —
the modular, repeatable ones. **Modularity is the strongest single predictor of
delivering to plan**, which is a genuinely actionable finding.

### Named cases

| Project | Estimate | Actual | Overrun |
|---|---|---|---|
| Sydney Opera House | A$7m, open 1963 | A$102m, opened 1973 | **~1,400%**, ten years late |
| Scottish Parliament | £10–40m (1997) | £414m (2004) | **~10x** |
| Boston Big Dig | ~$2.8bn (1982 $) | ~$14.8bn; ~$24bn with interest | **~5x** |
| Berlin Brandenburg Airport | Open 2011, ~€2bn | Opened Oct 2020, ~€7bn | 9 years late |
| Montreal Olympics 1976 | — | Debt cleared 2006 | ~720% real overrun |

The Oxford Olympics Study found **every Games since 1960 for which data exists
ran over budget** — a 100% overrun rate, average roughly 170% in real terms.
**A base rate of 100% is as clean a signal as this field produces, and cities
keep bidding.**

---

## Reference class forecasting — the actual procedure

Flyvbjerg turned the finding into a method. The UK Treasury adopted it: the
**Green Book** now mandates "optimism bias" uplifts, following a 2002–03 review
by Mott MacDonald of UK government projects.

**The procedure:**

1. **Identify a reference class** of past, completed, comparable projects. Wide
   enough for statistics, narrow enough for relevance. This is the hard step.
2. **Establish the distribution** of the outcome — not the mean, the *whole
   distribution*, including the tail.
3. **Place your case in the distribution.** Default: assume you are typical.
   Deviate only with specific, evidenced, *quantified* reasons.

Indicative Green Book-style uplifts applied to initial estimates (illustrative
magnitudes):

| Project type | Upper-bound optimism uplift |
|---|---|
| Standard buildings | ~4–24% |
| Non-standard buildings | ~50%+ |
| Standard civil engineering | ~20% |
| Non-standard civil engineering | ~66% |
| Equipment / development | up to ~200% |

**The uplifts look absurd until you look at the outcome data, at which point
they look conservative.**

### Worked example — do the arithmetic

A software team estimates a migration at **6 months**.

**Inside view:** decompose into 8 workstreams, sum the estimates, add a 20%
contingency → 7.2 months. Feels rigorous.

**Outside view:** the last 12 comparable migrations at this organisation took:
7, 9, 11, 8, 14, 9, 22, 10, 8, 13, 9, 18 months against original estimates of
4, 6, 6, 5, 8, 6, 9, 6, 5, 8, 6, 9.

Ratios of actual to estimate: 1.75, 1.50, 1.83, 1.60, 1.75, 1.50, 2.44, 1.67,
1.60, 1.63, 1.50, 2.00.

- Sum = 20.77; **mean ratio = 1.73**
- Sorted: 1.50, 1.50, 1.50, 1.60, 1.60, 1.63, 1.67, 1.75, 1.75, 1.83, 2.00,
  2.44 → **median = 1.65**
- **Minimum ratio = 1.50. Not one project came in under estimate.**
- 90th percentile ≈ 2.1

**Forecast:** 6 × 1.73 = **10.4 months** central; 90th percentile 6 × 2.1 =
**12.6 months**; and the floor is 6 × 1.5 = **9 months**, because that is the
best this organisation has ever done.

**The inside view said 7.2. The outside view says the fastest plausible outcome
is 9.** The 20% contingency was not conservative; it was below the historical
minimum. **That is the typical result.**

---

## The planning fallacy

Kahneman and Tversky, 1979. **The prediction that a task will take less time
than it does, held simultaneously with knowledge that similar past tasks took
longer.** The second clause is what makes it interesting — it is not ignorance.

| Study | Finding |
|---|---|
| Buehler, Griffin & Ross (1994) | Students predicting thesis completion: mean prediction 33.9 days, mean actual 55.5 days. Asked for a "worst case if everything went as badly as possible" estimate of 48.6 days — **the actual average exceeded their own worst case** |
| Same programme | Asking people to recall similar past tasks reduced the bias; asking them to plan in more detail did not |

**The debiasing result is the useful one: more planning does not help; more
recall does.** *(Effect sizes in the individual-task literature are moderate and
the standard replication caveats apply — see biases.md. The organisational and
infrastructure evidence, which is outcome data rather than lab data, is much
stronger.)*

### Is it bias or is it lying?

Flyvbjerg's own title asks it: *Error or Lie?* His answer is **strategic
misrepresentation** — in competitive funding environments, the project that
gets built is the one with the lowest bid and highest benefit forecast.
Optimistic estimates are *selected for*.

**This matters enormously for the fix.** If it's cognitive bias, train people.
If it's incentives, change the contract. Flyvbjerg's evidence — the flat
seventy-year line, the asymmetry (overruns not underruns), the fact that private
projects with the estimator's own money at risk behave better — points hard at
incentives. **Probably both, with incentives dominant in public projects and
bias dominant in personal ones.**

**Anyone can lie, but "we ran the numbers and got 6 months" is much easier to
say than "6 months," which is why the inside view is also politically useful.
Do not assume good faith and do not assume bad faith. Assume the base rate.**

---

## Where base rates fail

Steelman the objection, because it is not empty.

| Objection | Force |
|---|---|
| **Reference class selection is unfalsifiable** | Real and serious. Is SpaceX in "aerospace programmes" or "startups" or "vertically integrated manufacturers"? The answer swings the forecast by orders of magnitude. Two honest analysts can get very different numbers |
| **Genuine novelty exists** | The first nuclear reactor had no reference class. Neither did the first mRNA vaccine at scale. Base rates are silent on step changes |
| **Base rates are backward-looking in changing systems** | The base rate of pandemic deaths in 2019 understated 2020 because of connectivity changes. Non-stationarity is real |
| **They kill ambition** | Weak as stated, but there's something in it: if everyone used base rates, no one would build a Channel Tunnel. Flyvbjerg's own answer — some overrunning projects were still worth doing — concedes this |
| **Outside view can be gamed too** | "Comparable" is a choice. Consultants select the reference class that produces the requested answer |
| **Regression to the mean cuts both ways** | Base rates predict the middle. For a genuinely exceptional operator they will be too pessimistic, and there is no way to know in advance which you are |

**The honest position: the outside view should be your prior, not your
conclusion.** Start there, then update on specific, evidenced, quantified
differences. The failure mode is skipping step one, which is what essentially
everyone does.

---

## Where the popular story is wrong

| Popular claim | What's actually the case |
|---|---|
| "Projects run late because of bad management" | Sometimes. But the overrun rate is stable across seventy years, twenty countries, and every management methodology invented in that period. That points at structure, not competence |
| "The planning fallacy is about optimism" | Partly. In public infrastructure the evidence points at *strategic misrepresentation* — deliberate underbidding under competitive selection. Calling it a cognitive bias lets the incentive off the hook |
| "Add a 20% contingency" | Almost always far too little. The historical distributions have medians well above that and long right tails. Contingency should come from the distribution, not from convention |
| "Our project is different" | It is. So was every project in the reference class. This objection has never once been evidence |
| "Break the plan down in more detail to estimate better" | The Buehler evidence says decomposition doesn't fix it and can make it worse by increasing confidence. Recall of similar past cases does help |
| "Base rate neglect is just innumeracy" | Gigerenzer's work shows format matters enormously (see probability-basics.md), and the deeper problem is motivational: people who know the base rate still ignore it. Kahneman's own team did |
| "Reference class forecasting is a Flyvbjerg invention" | The method is his; the outside-view concept is Kahneman and Tversky's from the 1970s. Flyvbjerg's contribution was the empirical distributions and getting it into government policy |
| "Big projects are getting better" | The 2023 dataset says no. What *has* improved is modular, repeatable construction — solar and wind farms deliver close to plan because they are many small identical things, not one big bespoke thing |

---

## Open questions

- [ ] Is there a defensible, non-gameable procedure for selecting a reference class? Everything I know of reduces to expert judgement, which reintroduces the problem.
- [ ] What fraction of infrastructure overrun is bias vs strategic misrepresentation? Flyvbjerg leans hard on the second; the evidence is suggestive rather than decisive.
- [ ] Does the modularity finding generalise beyond construction? It should apply to software and organisational change; I know of no comparable dataset.
- [ ] Should reference-class forecasting be *mandatory and audited* for public projects, given that the UK adopted it and overruns continued? The Green Book uplifts appear to be routinely negotiated away in practice.
- [ ] How do you use base rates on genuinely exceptional operators without giving every operator licence to claim exceptionality? No good answer exists.
- [ ] Is there a base rate for base-rate failure — i.e. how often does the outside view lose to a well-informed inside view? Nobody has assembled it, and it is the single most useful missing dataset in this file.
