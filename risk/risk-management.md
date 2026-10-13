# Risk Management — Building Things That Don't Fall Over

> **Status: TIER 1** on correlation breakdown, margin of safety, and the
> mathematics of redundancy. **TIER 2** on normal accident theory vs High
> Reliability Organisation theory — a genuine, live, unresolved dispute.
> **TIER 3** on antifragility as a distinct category.

> **The organising claim: you cannot manage risk you cannot forecast, so the
> objective is not accurate prediction but tolerable failure.** Every technique
> below is a way of buying survivability at the cost of efficiency. There is no
> version where it is free, and the whole discipline consists of deciding how
> much to pay.

---

## The efficiency–robustness trade-off

**This is the master trade-off, and it is genuinely a trade-off, not a
false one.**

| | Optimised for efficiency | Optimised for robustness |
|---|---|---|
| Inventory | Just-in-time, near-zero buffers | Safety stock, multiple suppliers |
| Staffing | Lean, no slack, high utilisation | Cross-trained, deliberate spare capacity |
| Capital | High leverage, minimal cash | Low leverage, large cash reserve |
| Supply chain | Single lowest-cost source | Dual-sourced, geographically split |
| Behaviour in normal times | **Wins.** Visibly cheaper, measurably better | **Loses.** Looks wasteful every quarter |
| Behaviour in the tail | **Fails, sometimes terminally** | Survives |

**The structural problem: efficiency's benefits are continuous and measurable;
robustness's benefits are discrete, rare and counterfactual.** Whoever cut the
buffer gets promoted for years. Whoever kept it gets vindicated once, possibly
after leaving.

**This is not a management failure. It is a measurement failure**, and it is
the same shape as the prevention paradox (see the-control-group.md). Any
organisation that measures quarterly and rewards visible efficiency will drift
toward fragility by construction, regardless of the quality of its people.

**Queueing theory adds a hard constraint people don't expect.** As utilisation
$\rho$ approaches 1, expected wait time scales roughly as $\rho/(1-\rho)$:

| Utilisation | Relative wait |
|---|---|
| 50% | 1.0 |
| 80% | 4.0 |
| 90% | 9.0 |
| 95% | **19.0** |
| 99% | **99.0** |

**Going from 90% to 95% utilisation — a 5.6% efficiency gain — roughly doubles
delay.** Systems run near capacity have no ability to absorb variance. This is
why hospitals at 95% bed occupancy collapse under a modest surge.

---

## Redundancy, and how it fails

**Naive redundancy arithmetic.** Two independent components each with failure
probability 0.01:

$$P(\text{both fail}) = 0.01 \times 0.01 = 0.0001$$

**A 100-fold improvement. This is where the entire safety-engineering
literature's optimism comes from, and it depends entirely on independence.**

Now add a **common-cause failure** with probability 0.005 that takes out both:

$$P(\text{system fails}) = 0.0001 + 0.005 = 0.0051$$

**The improvement collapses from 100x to about 2x.** The common-cause term
completely dominates the independent term. **In real systems, the common-cause
probability is almost always larger than the product of the independent
probabilities, which means redundancy calculations are nearly always dominated
by the term that is hardest to estimate.**

### Ariane 5, Flight 501, 4 June 1996

The clearest demonstration on record.

- The Inertial Reference System software was **reused from Ariane 4** without
  re-verification against Ariane 5's flight profile.
- A 64-bit floating-point value (horizontal bias) was converted to a 16-bit
  signed integer. Ariane 5's higher horizontal velocity **overflowed the
  conversion.**
- **The backup unit ran identical software on identical inputs.** It failed
  approximately 0.05 seconds before the primary — not after.
- The rocket self-destructed 37 seconds after launch. Loss around **$370
  million**, plus the payload.

**Two identical units running identical software provide redundancy against
hardware failure and no redundancy whatsoever against software failure.** The
system had two of something and one failure mode.

**The general lesson: redundancy protects only against the failure modes that
are actually independent.** Ask of every redundant pair: *what single event
takes out both?* Shared power, shared code, shared location, shared supplier,
shared assumption, shared designer.

### The Fukushima version

Multiple emergency diesel generators — **located in the basements of the turbine
buildings.** Redundant against generator failure. Not redundant against water.
The tsunami took out all of them at once.

---

## Margin of safety

**Benjamin Graham**, *The Intelligent Investor* (1949), chapter 20: buy at a
price sufficiently below intrinsic value that you can be substantially wrong
about intrinsic value and still not lose money.

**The key insight, and it generalises far beyond investing: the margin is
protection against being wrong about your own model, not against bad luck.**

Engineering equivalents:

| Application | Typical safety factor | Reason |
|---|---|---|
| Structural steel, well-characterised loads | ~1.5–2.0 | Material variance, load estimation error |
| Pressure vessels | ~3.5–4.0 | Consequences of failure |
| Elevator cables | ~**11x** | Human life, unmonitored degradation, near-zero tolerance |
| Aircraft structures | ~1.5 (with strict inspection) | Weight is a hard constraint; compensated by monitoring |

**Note the elevator number.** Where consequences are catastrophic, unmonitored,
and irreversible, engineering does not use a 20% contingency. **It uses an
order of magnitude.** Compare with the "add 20% contingency" convention in
project management (base-rates.md), applied to a distribution whose median
overrun is 45% and whose tail is unbounded.

**The general rule: size the margin against the uncertainty in your model, not
against the variance in the outcome you modelled.** These are different
quantities and the first is almost always larger.

---

## Robust, resilient, antifragile

Taleb's triad (*Antifragile*, 2012), with honest tier marks.

| | **Fragile** | **Robust** | **Resilient** | **Antifragile** |
|---|---|---|---|---|
| Response to shock | Breaks | Unaffected | Breaks, recovers | **Improves** |
| Response to volatility | Concave (harmed) | Flat | Flat-ish, lagged | **Convex (benefits)** |
| Example | Over-leveraged firm; single-supplier chain; porcelain | Bank vault; low-leverage balance sheet | Power grid with black-start capability; forest after fire | Muscle under load; immune system; evolution; an option position |
| Tier | 1 | 1 | 1 | **3 as a distinct category** |

**Robust and resilient are distinct and both well established.** Robust means
"does not break." Resilient means "breaks and comes back." **They demand
different investments** — robustness buys strength; resilience buys recovery
capacity, spare parts, drills and restart procedures. Most organisations claim
robustness and have neither.

**Antifragility is the contested one.** The precise, defensible version is
**convexity: a payoff function whose second derivative with respect to
volatility is positive.** That is standard options mathematics (positive gamma)
and was well understood before 2012. The looser usage — "things that get
stronger from stress" — is real in biology (hormesis, muscle hypertrophy,
adaptive immunity) but is doing more rhetorical than analytical work when
applied to organisations.

**Steelman for Taleb:** having a *word* for it changed what people looked for,
and the observation that most institutions are unknowingly *short volatility*
— collecting small steady gains while carrying an unhedged tail — is correct,
important, and was under-appreciated.

**Steelman against:** you cannot make an organisation antifragile by declaring
it so. The operational content reduces to "hold optionality, limit downside,"
which is the barbell, which is robustness plus options.

---

## Correlated risk — the killer

**The single most reliable way to be destroyed is to hold many positions that
you believe are independent and that share a hidden common factor.**

| Domain | The apparent diversification | The hidden common factor |
|---|---|---|
| 2008 mortgage securities | Loans across many states and borrower types | **National house prices.** The calibration data contained no national downturn |
| Equity portfolios | Many sectors, many geographies | Global liquidity and risk appetite |
| Supply chains | Dozens of suppliers | A handful of upstream fabs, ports, or one strait |
| Careers | Salary, employer stock, employer pension, house near the office | **One employer.** All four fail together |
| Insurance | Thousands of policies | One hurricane path |
| Cloud infrastructure | Multiple services, multiple AZs | One control plane, one region, one DNS provider |

### The numbers

Equity correlations in calm markets typically sit around **0.2–0.3**. In a
panic, cross-asset correlations commonly exceed **0.8**.

**Consequence for portfolio variance.** For $n$ equally weighted assets each
with variance $\sigma^2$ and pairwise correlation $\rho$, portfolio variance is:

$$\sigma_p^2 = \frac{\sigma^2}{n} + \frac{n-1}{n}\rho\sigma^2$$

As $n \to \infty$, this converges to $\rho\sigma^2$. **The diversification
benefit is bounded by the correlation and nothing else.**

With $\sigma = 20\%$:
- $\rho = 0.2$: floor is $\sqrt{0.2} \times 20\% = 8.9\%$ — **diversification cuts risk by 55%**
- $\rho = 0.8$: floor is $\sqrt{0.8} \times 20\% = 17.9\%$ — **diversification cuts risk by 11%**

**Adding more assets does not help once correlation rises.** You cannot
diversify your way out of a common factor with any number of positions.

**Restated as a rule: diversification is a bet that correlations stay low, and
correlations rise precisely in the states where you needed the diversification.
Any risk model calibrated on calm-period correlations understates crisis risk by
construction — not by error, by construction.**

**The career version is the one most readers should act on.** Salary, equity
compensation, pension, professional network, and mortgage on a house near the
office are five exposures to one firm. In the state where the firm fails, all
five fail together.

---

## Normal Accidents vs High Reliability — the live dispute

### Perrow

**Charles Perrow**, *Normal Accidents: Living with High-Risk Technologies*
(1984), written after Three Mile Island (28 March 1979).

Two dimensions:

| | **Linear interactions** | **Complex interactions** |
|---|---|---|
| **Loose coupling** | Post office, most manufacturing. *Failures are absorbed* | Universities, R&D. *Failures are absorbed, slowly* |
| **Tight coupling** | Dams, rail, power grids. *Fast but predictable failure paths* | **Nuclear plants, chemical plants, aircraft, spaceflight, modern financial systems.** *Accidents are structural* |

- **Interactive complexity** — unfamiliar, unplanned, unexpected interactions
  between components, not visible or immediately comprehensible to operators.
- **Tight coupling** — no slack, no buffer, invariant sequences, no time to
  improvise.

**Perrow's claim: in the bottom-right cell, serious accidents are not
aberrations. They are a normal, expected output of the system's structure.** The
policy implication is radical: some technologies should not be built, because
they cannot be made safe by any amount of effort.

**The uncomfortable corollary: adding safety systems adds components and
interactions, which increases interactive complexity.** Three Mile Island's
operator confusion arose partly from the safety instrumentation itself — a
pressure-operated relief valve stuck open while its indicator showed the
*command signal*, not the valve position. Operators reasonably concluded it was
shut. **The instrument told the truth about what it measured and lied about what
mattered.**

### The counter — High Reliability Organisations

Berkeley school: **Todd LaPorte, Karlene Roberts, Gene Rochlin**; later **Karl
Weick and Kathleen Sutcliffe**, *Managing the Unexpected* (2001).

**Their evidence: aircraft carrier flight decks, air traffic control and
commercial aviation are complex and tightly coupled, and achieve accident rates
orders of magnitude below what Perrow's theory implies.** So it is possible.

Five characteristics they identify:

| Practice | Content |
|---|---|
| **Preoccupation with failure** | Near-misses treated as system information, not as successes. Reported without penalty |
| **Reluctance to simplify** | Resist tidy explanations that discard anomalies |
| **Sensitivity to operations** | Continuous attention to the front line, not to the dashboard |
| **Commitment to resilience** | Train to recover, not only to prevent |
| **Deference to expertise** | **Authority migrates to the person who knows, regardless of rank** |

**That last one is the crux and it maps directly onto the control group.** Every
case in the-control-group.md is a failure of exactly that practice: the person
who knew was outranked.

### Adjudicating

**Genuinely unresolved.** Honest summary:

- **Perrow is right that structure creates a floor** on accident probability
  that no amount of good management removes.
- **HRO theorists are right that the floor is far lower than Perrow assumed**,
  and that the gap between organisations at the same structural position is
  enormous.
- **Aviation is the strongest evidence for HRO** — commercial aviation fatality
  rates fell by orders of magnitude over decades in a complex, tightly coupled
  system, via mandatory anonymous incident reporting, crew resource management,
  and no-blame investigation.
- **Finance is the strongest evidence for Perrow** — it has become steadily more
  complex and more tightly coupled, and the reforms after each crisis add
  components.

**Best synthesis available: structure sets the odds, culture sets your position
within them, and the range within a structure is wide enough that the culture
argument is where the actionable content is.**

---

## Defence in depth, and how it fails

**James Reason**, *Human Error* (1990) — the **Swiss cheese model**. Multiple
imperfect barriers; an accident requires the holes to line up.

**Reason's key distinction:**

| | **Active failures** | **Latent conditions** |
|---|---|---|
| Who | Front-line operator | Designers, managers, regulators, procurement |
| When | Immediate | Present for years, dormant |
| Visibility | Obvious in the investigation | Invisible until combined with a trigger |
| Blame attracted | **Almost all of it** | Almost none |

**The model's real content is that the holes are not random.** They are created
by design decisions, production pressure and resource allocation, and they
**drift** — they get larger and they migrate into alignment over time under
normal economic pressure.

**Diane Vaughan's normalization of deviance** (*The Challenger Launch Decision*,
1996) is the mechanism for the drift: each time an out-of-spec condition occurs
without consequence, it is reclassified as acceptable, and the acceptable range
expands. **Nobody makes a decision to accept unacceptable risk. The definition
of acceptable moves.**

### Why safety systems create new failure modes

| Mechanism | Example |
|---|---|
| **Added complexity** | Every safety system is more components, more interactions, more ways to be misread. Three Mile Island's valve indicator |
| **Risk compensation** | People behave more dangerously when protected. *(Peltzman, 1975. The strong version — that seatbelts don't save lives — is not supported. The moderate version has support in some domains, e.g. the Munich taxi ABS study. Tier 2/3, contested)* |
| **False assurance** | The existence of a safety system is taken as evidence of safety, reducing vigilance. Titanic's watertight compartments |
| **Alarm fatigue** | Too many alerts, most false, and the real one is ignored. Well documented in clinical settings |
| **Automation-induced skill decay** | Operators lose the manual competence needed when automation hands back control |
| **Mode confusion** | Operator's mental model of the automation's state diverges from its actual state. A recurring theme in aviation accidents |
| **Moral hazard** | Insured or bailed-out actors take more risk. Structural, well-evidenced in finance |

**The general form: safety systems reallocate risk from frequent small failures
to rare large ones.** That is usually the right trade. **But it means the
accident record gets quieter and the tail gets fatter, and a quiet record is
read as safety.**

---

## Where the popular story is wrong

| Popular claim | What's actually the case |
|---|---|
| "Redundancy makes systems safe" | Only against independent failures. Common-cause terms dominate the arithmetic and are the hardest to estimate. Ariane 5 had two computers and one failure mode |
| "Diversification eliminates risk" | It reduces idiosyncratic risk and cannot touch the common factor. Portfolio variance floors at $\rho\sigma^2$ regardless of how many positions you hold |
| "We had a robust safety culture" | Said after most disasters. The testable version is whether a junior person could stop the operation without career cost. Usually the answer, demonstrably, was no |
| "The operator made a mistake" | Reason's point: front-line error is usually the last hole in the cheese, and the other holes were made in the boardroom years earlier. Blaming the operator terminates the investigation exactly where it should start |
| "It was a one-in-a-million event" | Usually means the model said one-in-a-million. That is a claim about the model |
| "More safety systems means more safety" | Adds complexity, which adds interaction failures, and can add risk compensation and alarm fatigue. Net effect is usually positive; it is not automatic |
| "Just-in-time was a mistake" | It is enormously efficient and was correct for decades. The error was applying it to *irreplaceable* inputs with long requalification times. The trade-off should be made input by input, not as a philosophy |
| "Antifragile things get stronger from any stress" | Only within a dose range. Hormesis has an upper bound; past it the thing simply breaks. This is frequently dropped when the concept is applied to organisations |
| "High reliability proves Perrow wrong" | It proves the floor is lower than he claimed. It doesn't show there's no floor. Aviation achieved its record with a regulatory and reporting apparatus finance has never had |
| "We stress-tested for that" | Stress tests use scenarios someone imagined. They are a test of the imagination of the committee, and they were passed by every major bank shortly before 2008 |

---

## Open questions

- [ ] How do you estimate common-cause failure probability without waiting for the common cause? Every technique I know of is expert judgement dressed as analysis.
- [ ] Is there a measurable indicator of normalization of deviance that fires *before* the accident? Rate of out-of-spec acceptances over time is the obvious candidate; I don't know of an organisation tracking it as a leading metric.
- [ ] Can the aviation safety model — mandatory anonymous reporting, no-blame investigation, an independent investigator with statutory power — be transplanted to medicine or finance? Medicine has tried and liability regimes appear to be the binding constraint.
- [ ] What is the correct amount to pay for robustness, given that the benefit is counterfactual and unmeasurable? This is genuinely hard and is the reason organisations under-invest. It may not have a clean answer.
- [ ] Does risk compensation apply meaningfully to financial regulation? If capital buffers induce more risk-taking elsewhere, the buffer is partly self-defeating. Evidence is thin and the question is important.
- [ ] Is Perrow's bottom-right cell expanding? Software has put interactive complexity and tight coupling into systems that had neither — logistics, elections, grids, medical devices. If so, the base rate of normal accidents should be rising.
