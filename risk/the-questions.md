# The Questions — Disaggregated

> **Status: TIER 1 on the distinctions, TIER 2 on where any given question
> falls.** The taxonomy below is not controversial. Sorting real questions into
> it is where the arguing happens.

> **Start here.** Most questions about the future are unanswerable *as asked*
> and become tractable, or become obviously hopeless, once split. Both outcomes
> are wins.

The diagnostic that runs through this whole notebook:

**Do I know the outcome space, and do I know the probabilities over it?** Those
are two separate questions and they generate four situations that require
different tools. Using the wrong tool is the single most common failure in the
whole domain.

---

## The Knightian split

Frank Knight, *Risk, Uncertainty and Profit* (1921, University of Chicago).
John Maynard Keynes, *A Treatise on Probability* (1921). **Same year,
independently, same distinction.** That convergence is itself a signal.

Knight's point was economic: if all business risk were measurable, insurance
would price it away and profit would vanish. **Profit exists because genuine
uncertainty exists.** The epistemology was a by-product.

| | Outcomes known | Outcomes unknown |
|---|---|---|
| **Probabilities known** | **RISK.** Roulette, actuarial mortality, dice. Expected value works. Insurance works | — (incoherent) |
| **Probabilities unknown** | **UNCERTAINTY (Knightian).** Will this startup succeed? Election in 5 years. Judgement, base rates, ranges | **IGNORANCE.** Unknown unknowns. Not in your hypothesis space at all |

Add the third row that most treatments skip:

| **Outcomes and probabilities both unknowable in principle** | **RADICAL/DEEP UNCERTAINTY.** Novel systems with no reference class. Not a gap to be closed |

**The practical consequence:** the tools are not interchangeable.

| Situation | Right tool | Wrong tool (and the failure) |
|---|---|---|
| Risk | Expected value, actuarial pricing, Kelly sizing | Storytelling; "this time is different" |
| Uncertainty | Base rates, wide intervals, scenario sets, optionality | Point estimates; Value-at-Risk with a calibrated normal |
| Ignorance | Redundancy, margin of safety, limiting exposure, reversibility | **Any** probability model. LTCM applied risk tools to ignorance |
| Deep uncertainty | Robustness across scenarios, avoid irreversibility, keep options | Precise cost-benefit analysis with a discount rate |

---

## Rumsfeld's grid, and the cell he left out

Donald Rumsfeld, DoD briefing, 12 February 2002. He was mocked; the taxonomy is
sound and predates him (the Johari window, Luft and Ingham, 1955).

| | Known | Unknown |
|---|---|---|
| **Known** | Known knowns — facts | Known unknowns — identified gaps, quantifiable |
| **Unknown** | **Unknown knowns** | Unknown unknowns — surprises |

**The interesting cell is the one nobody names: unknown knowns.** Slavoj Žižek's
addition — things the organisation knows but does not acknowledge knowing.

This is not a philosophical curiosity. **It is the dominant cell in the failure
record.** Every case in the-control-group.md except arguably Fukushima's
magnitude turns out to be an unknown known: the information was inside the
building.

| Disaster | Who knew | What happened to the knowledge |
|---|---|---|
| Challenger 1986 | Roger Boisjoly, Morton Thiokol engineers | Overruled the night before launch |
| Columbia 2003 | Debris Assessment Team | Imaging requests cancelled by management |
| Fukushima 2011 | TEPCO's own 2008 internal study (15.7m tsunami) | Not acted on |
| Iraq WMD 2002 | State Dept INR, DOE on the aluminium tubes | Dissent relegated to footnotes |
| 2008 crisis | Multiple analysts, short-sellers, some regulators | Incentives ran the other way |

**If your failure mode is "unknown known," better forecasting will not help
you.** You need a different organisation. See risk-management.md.

---

## Which questions are forecastable at all

This is the table the rest of the notebook hangs on.

| Question class | Example | Forecastable? | Why / why not |
|---|---|---|---|
| Deterministic physical, known dynamics | Solar eclipse of 3 Sept 2081 | **Yes, to seconds** | Newtonian, no feedback, no agents |
| Chaotic physical, short horizon | Weather tomorrow | **Yes, well calibrated** | Physics + enormous sample + daily feedback |
| Chaotic physical, medium horizon | Weather in 3 weeks | **No** | Lyapunov horizon ~10–14 days. Hard limit, not a data problem |
| Chaotic physical, statistical aggregate | Climate in 2075 | **Partly** | Boundary conditions ≠ initial conditions. Different problem from weather |
| Large-population actuarial | US road deaths next year | **Yes, tightly** | Law of large numbers. ~±3% routinely |
| Individual within that population | Whether *you* crash next year | **No** | The aggregate is stable; the instance isn't |
| Engineered project cost/schedule | Will this rail line overrun? | **Yes, directionally** | Strong reference class. Base rate ~90% overrun |
| Technology diffusion, existing tech | Solar cost in 2030 | **Moderately** | Learning curves are among the more stable regularities |
| Technology *invention* timing | Fusion, AGI | **Very poorly** | No reference class. Forecast errors historically enormous in both directions |
| Reflexive markets | Stock price next month | **Weakly at best** | The forecast changes the thing. Soros's reflexivity |
| Elections, near-term, polled | US election 3 months out | **Partly** | Real but modest skill; correlated state errors are the killer |
| Political events, 1–12 months, well-specified | Tetlock/GJP tournament questions | **Yes, measurably** | This is exactly what superforecasters do |
| Political events, 3–5+ years | "Will regime X survive the decade" | **No** | Tetlock: accuracy decays to chance |
| Onset of a specific war | Any named conflict | **Poorly** | n=1 events, reflexive, deliberate deception |
| Rare high-impact tail | Next financial crisis, exact form | **No** | The mechanism is novel each time by construction |
| Identity of the next pandemic pathogen | — | **No** | Not in the hypothesis space. That a pandemic will occur *is* forecastable |
| Human unique life outcomes | Will this marriage last | **Weakly, but non-zero** | Gottman-type models beat chance; individual prediction stays noisy |

**Three structural rules fall out of the table.**

1. **Aggregates are forecastable; instances are not.** Insurance works because
   of this. Almost every "prediction is impossible" argument confuses the two.
2. **Skill decays with horizon, fast, and with reflexivity, faster.** A system
   that reads your forecast is a different system.
3. **The absence of a reference class is the single best predictor of
   forecasting failure.** If you cannot name twenty comparable prior cases, you
   are not forecasting, you are narrating.

---

## The questions that are malformed

Some questions cannot be answered because they are not well-posed, and dressing
them in a probability makes them worse.

| Question as usually asked | Why it's malformed | The tractable version |
|---|---|---|
| "What's the probability of another 2008?" | "Another 2008" is not a defined event | "P(S&P drawdown >30% in any 12 months)" — has a base rate |
| "Is this risky?" | Risk of what, to whom, over what horizon | "What's my maximum loss, and can I survive it?" |
| "Will AI be dangerous?" | Compound of a dozen claims | Split into capability, deployment, and mitigation claims, each datable |
| "What are the chances this works?" | No resolution criteria, no deadline | "By 30 June, will metric X exceed Y?" |
| "Was that a good decision?" | Conflates decision quality with outcome | "Given what was knowable then, was the process sound?" |

**The last one is the most expensive error in the whole notebook.** Judging
decisions by outcomes is called *resulting* (Annie Duke's term) and it destroys
learning, because in any noisy domain good decisions frequently lose. A
resolution criterion and a date turn an argument into a forecast. Almost
nothing else does.

---

## Where the popular story is wrong

| Popular claim | What's actually the case |
|---|---|
| "Risk and uncertainty are the same thing" | Knight's whole point in 1921 was that they aren't, and that treating uncertainty as risk is what blows up institutions. This distinction was *lost* by mainstream economics for fifty years, not never made |
| "You can't predict anything" | False and lazy. Weather, mortality, project overruns, aggregate behaviour and 1–12 month geopolitical questions are all measurably forecastable. The claim is usually made to excuse not measuring |
| "Experts can predict things" | Also false, for the specific class most people care about — long-horizon political and economic events. Tetlock's data is the best evidence in the field |
| "Black swan" means "a bad thing that happened" | Taleb's definition requires that it was outside your model *and* rationalised afterwards. 2008 was largely a grey swan: foreseen by many, ignored. Calling it a black swan is usually an excuse |
| "More data means better forecasts" | Only for stationary, high-frequency problems. For rare events, more data from the calm period makes you *more* confident and *more* wrong. This is exactly the LTCM mechanism |
| "Rumsfeld invented unknown unknowns" | The taxonomy dates to at least 1955; it was standard in engineering risk analysis before 2002 |
| "Scenario planning is forecasting" | It's the opposite — it's a technique for the questions where forecasting fails. Shell's 1970s use is famous precisely because they didn't assign probabilities |

---

## Open questions

- [ ] Is there a principled test that tells you, in advance, whether a question is in the forecastable class? Reference-class availability is the best proxy I know of and it's crude.
- [ ] How much of Knightian uncertainty is irreducible versus merely unmeasured? Bayesians say all uncertainty is subjective probability and the distinction dissolves. That argument has not been settled in 100 years.
- [ ] Does the forecastability of technology *invention* differ in kind from other long-horizon questions, or only in degree? Learning curves (Wright, Moore) suggest cost is far more forecastable than timing.
- [ ] Is the "unknown knowns" cell dominant in the failure record, or does it only look that way because post-hoc investigations are designed to find someone who warned? Serious survivorship concern; unresolved.
- [ ] Can reflexivity be modelled well enough to forecast through it, or is it a hard limit? Market microstructure says partly; macro says no.
- [ ] Where exactly does climate sit? "Boundary condition problem, not initial condition problem" is the standard defence and is roughly right, but it is doing a lot of work.
