# Case: Computing and AI — The One We Are Inside

> **Status: TIER 1** on what computing demonstrably made cheap and on the
> Solow paradox's history. **TIER 2** on whether the paradox resolved, on the
> causes of the post-2005 productivity slowdown, and on smartphones and
> adolescent mental health. **TIER 3 on essentially every forward-looking AI
> claim, including the confident dismissals.**

**Written from general knowledge without live source verification, and written
from inside the event it describes.** This is the least reliable file in the
notebook and it would be dishonest not to say so at the top. Every AI figure
below should be checked; several will be stale.

---

## What computing demonstrably made cheap

Only four things, and everything else follows from them:

| What got cheap | Order of magnitude | Consequences |
|---|---|---|
| **Copying** | Marginal cost of a perfect copy → ~0 | Destroyed the business model of every industry whose economics rested on controlling copies: recorded music, newspapers, film distribution, software, textbooks |
| **Transmitting** | Distance cost → ~0 | Remote work, offshored services, global teams, real-time global finance |
| **Searching and matching** | Retrieval cost collapsed | Search, marketplaces, dating, recommendation, price discovery, logistics optimisation |
| **Coordinating and measuring** | Transaction and monitoring cost collapsed | Global supply chains (**with the container** — neither works alone), gig platforms, algorithmic management, ubiquitous metrics |

**The scarce complement that appeared: attention.** Herbert Simon said it in
1971 — "a wealth of information creates a poverty of attention." When copies
are free, the constraint moves to the only input that cannot be manufactured.
Cross-ref `existence/attention.md`.

---

## The productivity paradox

### Solow, 1987

**Robert Solow**, reviewing Cohen & Zysman in the *New York Review of Books*:

> **"You can see the computer age everywhere but in the productivity
> statistics."**

By the late 1980s American business had spent enormously on IT and measured
productivity growth was worse than in the 1960s.

### It resolved — and then unresolved. This is the part people leave out.

| Period | US labour productivity growth | Interpretation |
|---|---|---|
| 1948–1973 | ~2.5–3% | Postwar boom |
| **1973–1995** | **~1.4–1.5%** | The slowdown. Solow's paradox |
| **1995–2004** | **~2.5–3%** | **The paradox resolved.** Attributed substantially to IT by Jorgenson, Oliner & Sichel |
| **2005–present** | **~1–1.5%** | **It came back, and nobody has a fully satisfying explanation** |

**Two robust findings from the resolution period:**

- **Brynjolfsson & Hitt**: firm-level returns to IT depended overwhelmingly on
  **complementary organisational investment** — process redesign,
  decentralisation, skill upgrading. Firms that bought computers and kept the
  old processes got approximately nothing. **This is David's dynamo, measured
  at firm level.**
- The gains concentrated in IT-producing and IT-*using* sectors, with retail
  (Walmart's logistics) a standout — an under-appreciated fact, because the
  celebrated productivity story of the internet era is substantially about
  distribution centres and barcode scanners, not about the web.

### Robert Gordon's challenge

***The Rise and Fall of American Growth* (2016).** The claim: the inventions of
**1870–1970** — electricity, internal combustion, indoor plumbing and sanitation,
chemicals and pharmaceuticals, telecommunications — were **more transformative
than anything since**, and each could only happen once. Indoor plumbing changed
daily life more than the smartphone did.

Counters, with an assessment of each:

| Counter | Assessment |
|---|---|
| GDP mismeasures free digital goods | **Chad Syverson (2017) largely refuted this**: mismeasurement is too small to explain a slowdown of that size, and the slowdown occurred across countries with very different digital sector sizes. **Strong result, under-cited** |
| Intangible capital is unmeasured; the J-curve | **Brynjolfsson, Rock & Syverson**: during a GPT's build-out, firms invest in intangibles that are expensed not capitalised, so productivity is *understated* early and overstated later. **Plausible, partially testable, currently the best pro-optimist argument** |
| Diffusion lags | The dynamo argument again. Consistent with the data, unfalsifiable in the short run |
| Measured hours and quality adjustment are unreliable | True, and it cuts both ways |

**Honest position: the post-2005 slowdown is real, large and unexplained.
Anyone confident about why is overreaching.** Tier 2.

---

## Documented social effects of computing and the internet

Sorted by evidential strength, which is not the same as by how much they are
discussed.

### Strong evidence

| Effect | Detail |
|---|---|
| **Destruction of local journalism** | US newspaper advertising revenue fell from roughly $49bn (2005) to under $10bn — **classified advertising in particular went to Craigslist and Google essentially for free.** Newsroom employment roughly halved or worse. Thousands of US counties now have no daily local paper ("news deserts" — Penelope Muse Abernathy's work) |
| **Documented downstream effects of that** | Gao, Lee & Murphy (2020): **municipal borrowing costs rise measurably after a local newspaper closes** — a market-priced estimate of the value of local accountability journalism. Also lower split-ticket voting, lower turnout in local races, fewer candidates |
| **Retail restructuring** | Not just "shops closed." Inventory, logistics and the geography of warehousing were rebuilt |
| **Financial market structure** | Electronic then algorithmic trading; decimalisation (2001); Reg NMS (2005); the Flash Crash (6 May 2010). Spreads collapsed — a large, real consumer gain — while new instabilities appeared |
| **Measurement of everything** | Algorithmic management, performance metrics, and the extension of piece-rate logic to knowledge work |

**The local news case deserves emphasis: a technology that made classified
advertising free destroyed the funding model for local political accountability
as a side effect. Nobody intended it, nobody voted on it, and the mechanism ran
through the least glamorous product in the newspaper.** It is the best modern
illustration of everything in the-questions.md.

### Weaker evidence than the discourse assumes

**Filter bubbles and polarisation.** The popular story is that algorithmic
feeds trap people in echo chambers and this caused political polarisation.
**The evidence is substantially against the strong version:**

| Study | Finding |
|---|---|
| **Boxell, Gentzkow & Shapiro (2017)** | US polarisation **rose fastest among the demographic groups least likely to use the internet and social media** — notably the over-65s. **This is very hard to reconcile with an internet-driven story** |
| **Bakshy, Messing & Adamic (2015, *Science*)** | On Facebook, individual choice reduced cross-cutting exposure more than the algorithm did |
| **Flaxman, Goel & Rao (2016)** | Search and social media increase ideological distance **and simultaneously increase exposure to opposing views** — most people's media diets are more moderate than assumed |
| **The 2023 Meta election studies** (*Science* / *Nature*, Guess et al. and colleagues) | Large-scale experiments changing feed algorithms for three months found **approximately no effect on polarisation or political attitudes** |

**Position: echo chambers exist, are a minority phenomenon, and their causal
contribution to political polarisation is much smaller than the public
conversation assumes.** Cable television, party sorting and elite behaviour are
better-supported explanations. **This is one of the clearest "the popular story
is wrong" findings in the notebook.** Tier 2 leaning Tier 1.

### Genuinely unresolved: smartphones and adolescent mental health

**Do not resolve this. Both camps are overconfident.**

| For a causal effect | Against |
|---|---|
| **Jonathan Haidt, *The Anxious Generation* (2024)**: adolescent depression, self-harm and anxiety rose sharply from around 2012 across the US, UK and Nordic countries, disproportionately in girls, coinciding with smartphone and social media saturation | **Amy Orben & Andrew Przybylski (2019)** specification-curve analyses found associations of trivial size — comparable to eating potatoes or wearing glasses |
| The timing coincidence is genuinely striking and international, which argues against purely local explanations | **Candice Odgers** (*Nature* review, 2024) and Chris Ferguson: the causal evidence is weak, correlational, and the effect sizes in better-identified studies are small |
| Some experimental evidence: **Allcott, Braghieri, Eichmeyer & Gentzkow (2020)** — four weeks of Facebook deactivation improved subjective wellbeing, but by a **modest** amount (~0.09 SD) | Alternative explanations: diagnostic and measurement changes, post-2008 economic effects, parenting and unsupervised-play changes, opioid crisis family effects |

**Honest position: Tier 2 at best, and the strong causal version is Tier 3.**
The correlational signal and the timing are real and unexplained; the causal
evidence does not currently support the confidence of either side. **The
policy asymmetry argument — that precaution is cheap here — is a legitimate
argument but it is not evidence, and it should not be presented as evidence.**

---

## AI — handled carefully

### The rule for this section

**Confident boosters and confident dismissers are both making Tier 3 claims.**

- "AGI within a few years, transformation of all economic activity" — an
  extrapolation from a short capability trend with no established mechanism for
  the extrapolation. **Tier 3.**
- "It's just autocomplete, nothing will change, it's all hype" — a claim about
  the long-run economic effect of a general-purpose technology at a point where
  no general-purpose technology's effects have ever been visible early.
  **Also Tier 3.**

**Neither position has the evidence its confidence implies.** The asymmetry in
how they are received is social, not epistemic.

### What current systems demonstrably do — Tier 1

Stated narrowly, as capabilities rather than as promises:

- Generate fluent, contextually appropriate text across domains and languages.
- Translate at a quality that displaced a large fraction of routine
  professional translation work.
- Write, complete, explain and debug substantial quantities of code.
- Score highly on many professional and academic examinations — **with the
  standing caveat that benchmark contamination from training data is a real and
  incompletely solved problem, so exam scores are weak evidence of the
  underlying capability.**
- Summarise, extract and reformat unstructured text reliably enough for
  production deployment.

And demonstrably fail at: reliable factual accuracy without retrieval; reliable
arithmetic and long multi-step reasoning without tools; knowing what they do not
know; consistency across restatements of the same problem.

### What controlled studies have measured — Tier 1–2 on the studies, Tier 3 on extrapolation

| Study | Finding |
|---|---|
| **Noy & Zhang (2023, *Science*)** | Mid-level professional writing tasks: roughly **40% time reduction, ~18% quality improvement** |
| **Peng et al. (2023)** | GitHub Copilot on a defined programming task: **~55% faster.** Note: a synthetic task, not production engineering |
| **Brynjolfsson, Li & Raymond (2023)** | Customer support agents: **~14% productivity gain**, concentrated overwhelmingly in the **least experienced** workers |
| **Dell'Acqua et al. (2023)** | BCG consultants: substantial improvement on tasks inside the "jagged frontier" of capability, and **degraded performance on tasks outside it**, because users could not tell which was which |

**The most robust finding across studies is the compression effect: gains
concentrate among less-experienced workers, narrowing the performance gap.**
This replicates and it has large implications — for wage structure, for career
ladders, and for whether expertise remains worth acquiring. It also cuts against
the simple "AI replaces the juniors" story: measured effects go the other way.

**Caveats that apply to all of these:** short horizons, task-level not job-level,
selected tasks, novelty effects, and no measurement of quality degradation at
the tail. **Task-level RCT gains do not aggregate straightforwardly to firm
productivity, and firm productivity does not aggregate straightforwardly to
national statistics.**

### What is not demonstrable — Tier 3

- **Aggregate productivity effects.** As of writing there is no clear AI signal
  in national productivity statistics. **Daron Acemoglu (2024)** estimated total
  factor productivity effects on the order of **0.5–0.7% over ten years** —
  small. Others project transformative effects. **Both are extrapolations from
  assumptions, not measurements.**
- The shape of the capability curve. Whether current scaling continues, plateaus
  or requires architectural change is genuinely unknown to everyone, including
  the people building the systems.
- Net employment effects. See unintended-consequences.md — the historical base
  rate favours reinstatement of new tasks, and base rates fail exactly when the
  generating process changes.
- Anything about "AGI," a term with no agreed operational definition, which
  makes most claims involving it **Tier 4 as posed** rather than Tier 3.

### The best available prior

**The dynamo.** A general-purpose technology's productivity effects showed up
roughly forty years after commercial availability, and only after
organisations were rebuilt around it. If that prior applies, then:

- **Current absence of macro effects is uninformative** — it is what the dynamo
  case predicts.
- **Current claims of imminent transformation are also uninformative** — the
  dynamo case predicts a long lag, not a short one.
- **The rate-limiting step is organisational redesign, not model capability.**

**This prior could be wrong.** Software diffuses faster than factory buildings,
requires no capital equipment on the user side, and can be deployed
incrementally. The counter-argument — that this is the fastest-diffusing
technology in history and the lag will be compressed — is reasonable and
untested. **Both are Tier 3.**

### Second-order effects already visible

Worth listing because they are the kind of thing this notebook says gets missed:

| Effect | Note |
|---|---|
| **Energy and capital intensity** | Datacentre electricity demand is now a material factor in grid planning in several jurisdictions. A software technology has become an **energy** and **land-use** story |
| **Verification cost** | Cheap plausible text raises the cost of establishing that something is true. Cross-ref `knowledge/`. **When production is cheap and verification is not, the ratio is the problem** |
| **Compression of the skill gradient** | See the studies above. Possibly the largest labour-market effect and rarely the headline |
| **Concentration** | Frontier training requires capital at a scale that only a handful of organisations command. Compare it to any prior software wave, where the barrier was near zero |
| **Training-data enclosure** | The value of the open web as a commons is being converted into private model weights, with the predictable response of paywalling and litigation. **A commons is being enclosed, again** |

---

## Where the popular story is wrong

| Popular story | Correction |
|---|---|
| **"The Solow paradox was resolved"** | Resolved 1995–2004, then productivity growth fell back and has stayed low for two decades. Nobody has a good explanation |
| **"GDP just doesn't capture free digital goods"** | Syverson showed mismeasurement is far too small to explain the slowdown |
| **"Social media caused political polarisation"** | Polarisation rose fastest among the least-online demographics; large field experiments found ~no effect. The strong version is in serious trouble |
| **"Algorithms trap people in filter bubbles"** | Personal choice does more than the algorithm, and online media diets are more diverse than offline ones for most people |
| **"Smartphones are destroying teenagers"** | Genuinely unresolved. Timing coincidence real; causal evidence weak; effect sizes in the best studies small. Both camps overclaim |
| **"AI will replace X% of jobs by year Y"** | No such forecast has a defensible method. Task-level RCT gains do not aggregate to job elimination |
| **"AI is just autocomplete / all hype"** | Equally unsupported. The measured task-level effects are real and non-trivial |
| **"AI will help the top performers most"** | The measured effect is the opposite: gains concentrate in the least experienced |
| **"The internet destroyed newspapers"** | More precisely: **Craigslist and search advertising destroyed the classified-ad cross-subsidy that funded reporting.** The mechanism matters, because it tells you what a fix would need to replace |

---

## Open questions

- [ ] Why did US productivity growth fall after 2005 and stay down? This is the
      most important unanswered question in modern economics and it directly
      determines how to read AI.
- [ ] Does the Brynjolfsson–Rock–Syverson J-curve make any near-term
      falsifiable prediction, or does it explain any observation?
- [ ] Is benchmark contamination large enough to invalidate professional-exam
      results as capability evidence? What would an uncontaminated evaluation
      even look like?
- [ ] Does the compression effect (AI helps novices most) persist beyond the
      first year of exposure, or does it reverse as experts learn to use the
      tools well? This is testable now and the answer matters enormously.
- [ ] Is there a mechanism by which the ~40-year GPT adaptation lag could be
      compressed, or is organisational and generational turnover irreducible?
- [ ] What replaces the classified-advertising cross-subsidy for local
      accountability journalism? Nothing has, and the municipal borrowing cost
      result suggests it is worth paying for directly.
- [ ] If AI capability plateaued tomorrow, how much of the current economic
      projection would survive? Nobody publishes this scenario and it is the
      most useful one to have written down.
