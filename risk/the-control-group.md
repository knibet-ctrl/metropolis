# The Control Group — Forecasting and Risk Management Failures

> **Status: TIER 1** on the facts of each case. **TIER 2** on the mechanism
> attributions — these are reconstructions, and investigation reports are
> written by people with incentives.

> **Why this file exists.** A notebook that only studies successful forecasting
> is a survivorship machine. The failures are more informative than the
> successes because they are better documented — catastrophes get commissions,
> and commissions get subpoena power.

> **The finding that runs through every case below: in almost all of them,
> somebody inside the organisation knew and was overruled.** The failures are
> organisational far more often than epistemic. See the "unknown knowns" cell in
> the-questions.md.

---

## Summary table — the mechanism in each case

| Case | Year | Core mechanism | Was it foreseen internally? |
|---|---|---|---|
| LTCM | 1998 | Thin-tailed model on fat-tailed data; leverage; correlation assumed independent | Partly — Merrill's risk disclosures, Buffett's warnings |
| Gaussian copula / CDOs | 2005–08 | Correlation parameter calibrated on data containing no downturn | Yes — including by Li himself |
| Challenger | 1986 | Selection on the dependent variable; management override of engineering | **Explicitly, the night before** |
| Columbia | 2003 | Normalization of deviance; imaging requests cancelled | **Yes, three times** |
| Fukushima | 2011 | Design basis set below known hazard; common-cause redundancy failure | **Yes — TEPCO's own 2008 study** |
| Iraq WMD | 2002 | Confirmation search; dissent suppressed to footnotes; vague verbal probability | **Yes — INR, DOE, BND** |
| COVID (varied) | 2020 | Failure to update on exponential data; overconfident point models | Partly |
| Tetlock's experts | 1984–2003 | Hedgehog overconfidence; no scoring; no feedback | No — nobody was measuring |

---

## Long-Term Capital Management, 1998

**The purest case in the file, because the people involved were as good as it
gets and it made no difference.**

**The setup.** Founded 1994 by John Meriwether, formerly head of bond arbitrage
at Salomon Brothers. Partners included **Robert Merton and Myron Scholes**, who
shared the **1997 Nobel Memorial Prize** in economics for the options pricing
framework. David Mullins, former Vice Chairman of the Federal Reserve.

**The returns, net of fees:** ~21% (1994, partial year), ~43% (1995), ~41%
(1996), ~17% (1997). By early 1998, roughly **$4.7bn of equity supporting about
$125bn of balance sheet — leverage on the order of 25:1** — and a **derivatives
notional of roughly $1.25 trillion.**

**The strategy** was convergence arbitrage: identify pairs of near-identical
securities trading at small spreads, bet the spread narrows, and use enormous
leverage to make small edges material.

**What happened.** Russia defaulted on domestic debt and devalued on **17 August
1998**. A global flight to quality followed. **Every convergence trade LTCM held
moved the wrong way simultaneously**, because they were all, at bottom, the same
trade: short liquidity, long risk premium. The fund lost roughly **$4.6bn in
under four months.** Equity fell from ~$4.7bn to ~$400m.

On **23 September 1998** the New York Fed organised a **$3.625bn**
recapitalisation by fourteen institutions. Bear Stearns refused to participate.

**The mechanisms, in order of importance:**

| Mechanism | Detail |
|---|---|
| **Thin-tailed model on fat-tailed data** | Risk models calibrated on ~5 years of data. The August 1998 loss was described internally as a 10-sigma event. Under a Gaussian, a 10-sigma daily event has probability around $10^{-23}$ |
| **Correlation assumed where none was established** | The positions were treated as diversified. They shared a single hidden factor: liquidity. **The "diversification" was 100 expressions of one bet** |
| **Leverage converts a drawdown into ruin** | At 25:1, a 4% adverse move on the balance sheet wipes out the equity. There is no path back from that |
| **Endogenous risk** | LTCM was large enough that its own liquidation moved prices against it. **The model treated prices as exogenous.** They weren't |
| **Absence of an absorbing barrier in the model** | The models computed distributions of returns. They did not model the state "we are forced to liquidate," which is the only state that matters |

**Warnings that existed.** Merrill Lynch's own risk disclosures described
mathematical models producing a false sense of security. Buffett had made
similar points publicly. Several banks reduced exposure in 1998. **None of this
is hindsight; it was in the record beforehand.**

**The generalisable lesson:** two Nobel laureates in the specific field of
financial risk, with the best available models and the best available data,
produced a fund that destroyed itself in four months. **The failure was not
insufficient sophistication. Sophistication was the mechanism** — it justified
the leverage.

---

## The Gaussian copula and 2008

**David X. Li**, "On Default Correlation: A Copula Function Approach," *Journal
of Fixed Income*, **2000**. A tractable way to model the joint default
probability of a pool of loans using a single correlation parameter, with
correlation estimated from **credit default swap spreads** rather than from
historical joint defaults.

**Why it was adopted so fast:** it made previously unpriceable instruments
priceable. Rating agencies used it. It turned pools of subprime mortgages into
tranches that could be rated AAA. **Felix Salmon, *Wired*, February 2009:
"Recipe for Disaster: The Formula That Killed Wall Street."**

**The failures, precisely:**

1. **Correlation was treated as a constant.** It is a regime-dependent
   parameter that rises sharply in stress. See risk-management.md.
2. **It was estimated from CDS spreads over a short window (~2001–2005) that
   contained no national house-price decline.** The model was calibrated
   entirely on data from which the relevant event was absent. **This is the LTCM
   error, repeated exactly, eight years later, with more money.**
3. **The Gaussian copula has zero tail dependence.** The specific mathematical
   property that matters — the probability that two assets default *together in
   the extreme* — is assigned essentially zero by construction. It is a feature
   of the functional form, not of the data.
4. **The arithmetic sensitivity is brutal.** See the worked example in
   probability-basics.md: for a pool of 100 loans at 5% default probability,
   P(>20 defaults) moves from roughly $10^{-10}$ under independence to
   percentage-level under modest correlation. **Eight orders of magnitude from
   one unobservable parameter.**

**Steelman the counter-argument, because "one formula caused the crisis" is too
neat.** Donald MacKenzie and others argue the dominant causes were incentive
structures: originators bore no default risk, rating agencies were paid by
issuers, and traders were compensated on annual mark-to-model profits.
**Nobody was rewarded for questioning the correlation parameter, and many were
rewarded for not questioning it.** Li himself reportedly cautioned that few
understood the model's limits.

**Fair verdict: the formula was the instrument, not the cause.** A model that
produces the answer the buyer wants will be adopted regardless of whether the
buyer understands it. **The mechanism to watch for is not "wrong model." It is
"model whose output is commercially convenient and whose key parameter is
unobservable."**

---

## Challenger, 28 January 1986

**The best-documented case of a correct forecast being overruled.**

**The physical fact.** The solid rocket booster field joints were sealed by
rubber O-rings. Rubber resilience falls sharply at low temperature. Ambient
temperature at launch was around **36°F (2°C)**. The coldest previous shuttle
launch had been **53°F**.

**The night before.** On the evening of **27 January 1986**, Morton Thiokol
engineers — **Roger Boisjoly** and **Arnie Thompson** prominent among them —
recommended in a teleconference with NASA that the launch be postponed until
temperatures rose above 53°F. Boisjoly had been documenting O-ring erosion for
months and had written internally in July 1985 warning of loss of vehicle and
crew.

NASA pushed back. Thiokol management called an offline caucus. **Senior VP Jerry
Mason told VP of Engineering Bob Lund to "take off your engineering hat and put
on your management hat."** Thiokol reversed its recommendation. **Allan
McDonald, Thiokol's on-site director, refused to sign the launch
recommendation.**

**The analytical error.** The chart used to argue that temperature was not a
factor plotted only the **flights that had experienced O-ring damage**, against
temperature. Within that subset there was no clear trend. **Adding the flights
with zero damage — which clustered at warm temperatures — reveals a strong
relationship.**

**This is selection on the dependent variable, and it is one of the most common
and most lethal analytical errors there is.** You cannot learn what causes
failure by looking only at failures. *(Edward Tufte made this case famous; some
of his specific graphical claims have been criticised, but the exclusion of the
no-damage flights is documented in the Rogers Commission record and is not in
dispute.)*

**The probability estimates.** Richard Feynman's Appendix F to the Rogers
Commission report:

| Source | Estimated probability of loss of vehicle per flight |
|---|---|
| NASA management | ~**1 in 100,000** |
| NASA working engineers | ~**1 in 100** |
| **Actual shuttle record** | **2 losses in 135 flights = 1 in 67.5** |

**The engineers were right to within a factor of about 1.5. Management was wrong
by three orders of magnitude.** Feynman: "For a successful technology, reality
must take precedence over public relations, for nature cannot be fooled."

**Mechanism: this was not a forecasting failure. The forecast was made,
correctly, by the right people, in writing, the night before. It was an
authority failure.**

---

## Columbia, 1 February 2003

**The same organisation, seventeen years later, same mechanism.**

Foam from the external tank struck the leading edge of the left wing during
launch on **16 January 2003**, breaching the reinforced carbon-carbon panel.
On re-entry, superheated gas entered the wing structure. Seven crew died.

**What happened in between.** The **Debris Assessment Team** identified the
strike from launch footage and **requested on-orbit imaging of the wing from
national assets on three separate occasions. All three requests were cancelled
by shuttle programme management.** The engineers were told the analysis showed
no safety-of-flight issue — using a model (Crater) being applied well outside
its validated range, to a debris volume hundreds of times larger than anything
it had been calibrated against.

**Normalization of deviance.** Foam shedding had occurred on the majority of
prior flights. It was originally a violation of design requirements. Because it
had never caused loss of vehicle, it was progressively reclassified as an
in-family maintenance issue — **"accepted risk"** — and eventually stopped being
treated as an anomaly requiring resolution. **Diane Vaughan** had described
exactly this process in *The Challenger Launch Decision* (1996), seven years
before Columbia.

**The Columbia Accident Investigation Board (August 2003)** concluded that the
organisational causes were rooted in the programme's history and culture, and
explicitly stated that NASA had not fixed what Challenger revealed.

**Mechanism: an organisation that had produced a landmark investigation into its
own culture repeated the failure. Knowing about a failure mode does not
constitute protection against it.**

---

## Fukushima Daiichi, 11 March 2011

**The best "control group within the control group" in the whole file, because
the counterfactual actually exists.**

**The event.** The Tōhoku earthquake, magnitude 9.0. Reactors scrammed
successfully; the earthquake itself was survived. The tsunami arrived ~50
minutes later.

| Parameter | Value |
|---|---|
| Design basis tsunami height | **5.7 m** (later revised to ~6.1 m) |
| Actual run-up at the site | **~13–15 m** |
| **TEPCO's own 2008 internal study** | Projected wave heights **up to 15.7 m** |
| Action taken on that study | **None** |

**The cascade.** The tsunami flooded the site. **The emergency diesel generators
and switchgear were located in the basements of the turbine buildings.** All but
one were disabled simultaneously. Station blackout → loss of core cooling →
three core meltdowns and hydrogen explosions.

**Mechanisms:**

| Mechanism | Detail |
|---|---|
| **Design basis set from an inadequate historical record** | Based on relatively recent recorded tsunamis. The Jōgan event of **869 CE** was known to geologists and had produced comparable inundation |
| **Common-cause failure of redundancy** | Multiple generators, one location, one flooding event. See risk-management.md |
| **Known hazard, unactioned** | The 2008 internal study is the decisive fact. This is an "unknown known" |
| **Regulatory capture** | The NAIIC (Kurokawa) report, 2012, described the disaster as **"profoundly manmade"** and identified collusion between regulator and operator |

### The counterfactual — Onagawa

**Onagawa nuclear plant was closer to the epicentre than Fukushima Daiichi.** It
was built on higher ground with a seawall of roughly **14.8 m**, largely because
**Yanosuke Hirai**, a Tohoku Electric executive, insisted during the 1960s
design phase on accounting for historical tsunami records — over objections that
it was excessive and expensive.

**Onagawa survived, shut down safely, and served as an evacuation shelter for
local residents.** Fukushima Daini also survived, with difficulty.

**Same earthquake. Same tsunami. Same technology. Same country. Different
assumption about the tail. Completely different outcome.** This is as close to a
controlled experiment in risk management as the historical record provides, and
the variable that differed was **one person's willingness to design against a
thousand-year-old record rather than a fifty-year one.**

---

## The Iraq WMD assessment, 2002

**The reference case for institutional forecasting failure with no physical
system involved.**

The **October 2002 National Intelligence Estimate**, *Iraq's Continuing Programs
for Weapons of Mass Destruction*, judged with **"high confidence"** that Iraq
had continued its WMD programmes and had chemical and biological weapons.

**The Silberman-Robb WMD Commission (March 2005) concluded the intelligence
community was "dead wrong in almost all of its pre-war judgments."**

**Mechanisms:**

| Mechanism | Detail |
|---|---|
| **Prior treated as evidence** | Iraq *had* had programmes and *had* used chemical weapons in the 1980s. Absence of evidence of destruction was read as evidence of concealment. **Under that logic no evidence could have disconfirmed the hypothesis** |
| **Dissent relegated to footnotes** | On the aluminium tubes, **State Department INR and the Department of Energy** — the actual centrifuge experts — dissented, arguing the tubes were for conventional rockets. The dissent appeared as annotation while the key judgments read as consensus |
| **Single-source reliance** | **"Curveball"** (Rafid Ahmed Alwan al-Janabi), the source for mobile biological weapons labs, was never interviewed by US intelligence. German BND handlers had flagged reliability concerns |
| **Vague verbal probability** | "High confidence" is not a number. **Sherman Kent** had argued for numeric probabilities in the 1950s and 60s and lost that argument. His 1964 essay "Words of Estimative Probability" documents a 1951 NIE saying Soviet attack on Yugoslavia was a "serious possibility" — Kent found readers interpreted that phrase as anywhere from **20% to 80%** |
| **No red team** | No institutional mechanism required someone to argue the null hypothesis |
| **Demand-side pressure** | The customer wanted a specific answer. *(How much this drove the analysis is politically contested; the structural point that customer expectation shapes intelligence production is not)* |

**Mechanism summary: the failure was not that analysts lacked information. It was
that the analytical process had no way to represent, aggregate or transmit
uncertainty, and no mechanism that rewarded dissent.**

---

## COVID-19 — failures and successes

**The most instructive case because both columns are full.**

### Failures

| Failure | Detail |
|---|---|
| **Failure to update on exponential data** | Through most of February 2020, case counts outside China were doubling every ~3 days and public and expert commentary largely continued to treat it as a regional event. **The data was public and unambiguous. The failure was one of updating, not of information** |
| **IHME model** | Its early-2020 US projections were repeatedly and substantially wrong, and — the worse fault — its uncertainty intervals were far too narrow, so actuals fell outside them frequently. **A model that is wrong is a problem; a model that is wrong and confident is a hazard** |
| **CFR/IFR conflation** | WHO's widely reported "3.4%" figure (3 March 2020) was a case fatality rate computed from confirmed cases, when the denominator was known to be severely undercounted. Infection fatality rate estimates settled far lower and were strongly age-dependent |
| **Mask guidance** | Early Western public guidance advised against general masking, in part driven by supply protection for healthcare workers. Whatever the merits, the guidance was later reversed, and the reversal cost credibility that was needed later |
| **Asymmetric caution** | Institutions applied high evidentiary standards to actions and low standards to inaction, which is not symmetric under uncertainty |

### Successes

| Success | Detail |
|---|---|
| **Vaccine development** | Moderna's candidate sequence was designed within days of the genome publication in mid-January 2020; Phase 1 dosing began **16 March 2020**; efficacy readouts came in **November 2020**. Against every historical base rate for vaccine timelines, this was extraordinary |
| **Genomic surveillance** | Sequencing and global sharing at a speed with no precedent |
| **Some forecasting aggregators** | Metaculus and superforecaster groups tracked several case and vaccine-timing questions creditably. Not uniformly |
| **Taiwan, South Korea, and others** | Institutional memory from SARS 2003 produced fast, effective early responses. **Reference class availability mattered more than model quality** |

### Steelman on the Imperial College model

**Report 9 (16 March 2020)** projected around 510,000 UK deaths in an unmitigated
scenario. It is routinely cited as a forecasting failure. **It was not a
forecast. It was a conditional scenario** — explicitly, "if no mitigation is
undertaken." Mitigation was undertaken, partly because of the report. **Judging
a conditional scenario against an outcome that its own publication helped
prevent is a category error**, and it is the prevention paradox again.

**The fair criticisms are different and are real:** the model's code quality and
reproducibility were poor; the parameter uncertainty was under-communicated; and
the range of scenarios presented was narrower than the underlying uncertainty
warranted.

---

## The prevention paradox — why this file is structurally incomplete

**Successful risk management is invisible and indistinguishable from
overreaction.**

| Case | If it worked, you see | If it was hype, you see |
|---|---|---|
| **Y2K** | Nothing happened | Nothing happened |
| Ozone / Montreal Protocol 1987 | No ozone catastrophe | No ozone catastrophe |
| Netherlands Delta Works | No flood | No flood |
| Pandemic preparedness pre-2020 | Fewer deaths | — |

**Y2K is the cleanest case and it is genuinely undecidable from outcome.** The
US alone spent on the order of $100bn on remediation. Countries that spent far
less also had few problems, which is the strongest argument that it was
overstated — but they also had less legacy mainframe exposure, so the comparison
is confounded.

**The Delta Works is the strongest positive case, and it required 1,836 deaths
in the North Sea flood of 1953 to authorise.** The Randstad defences were built
to a **1-in-10,000-year** standard — a level that would be laughed out of any
cost-benefit meeting absent the memory of bodies.

**The structural consequence for this notebook: the control group is biased
toward failures because failures are legible. There is no comparable archive of
"the buffer we kept that we never needed and that was therefore correct."** Any
reader drawing conclusions from disaster case studies should hold that firmly.

---

## Where the popular story is wrong

| Popular claim | What's actually the case |
|---|---|
| "LTCM failed because of an unpredictable event" | Russia defaulting was not unforeseeable; several institutions had reduced exposure. LTCM failed because 25:1 leverage converts a foreseeable drawdown into ruin |
| "Nobody saw 2008 coming" | Many did, in writing, publicly. Some made large amounts of money on it. What was absent was not foresight but *incentive to act on it* |
| "One formula caused the financial crisis" | The Salmon article is excellent journalism and an incomplete causal account. Incentives, ratings agency business models, and originate-to-distribute mattered at least as much |
| "Challenger was an engineering failure" | The engineering was understood and correctly characterised in writing beforehand. It was a management failure with an unusually clear timestamp |
| "NASA learned from Challenger" | The CAIB explicitly found it had not. Columbia's organisational causes were the same causes |
| "Fukushima was an unforeseeable natural disaster" | TEPCO's own 2008 study projected 15.7 m. Onagawa, closer to the epicentre, survived because someone had insisted on a 14.8 m seawall in the 1960s |
| "Intelligence failed on Iraq because of bad information" | The correct information was in the building — INR and DOE dissented in the document itself. It was structurally demoted |
| "The Imperial model predicted 510,000 deaths and was wrong" | It was a conditional unmitigated scenario, not a forecast. The real criticisms are about code quality and communicated uncertainty |
| "The experts got COVID wrong" | Some did, badly. Others were right and early. **The distinguishing variable was not expertise but whether the person updated on exponential data in February 2020** |
| "Y2K was a hoax" | Undecidable from the outcome. That is precisely the prevention paradox, and treating absence of catastrophe as proof of overreaction is the reasoning that defunds preparedness |

---

## Open questions

- [ ] Is there any documented case of a large organisation *successfully* acting on an internal minority warning about a tail risk, at real cost, before the event? Onagawa is the best I know of. The scarcity of examples is itself the finding.
- [ ] Do post-hoc investigations systematically over-find warnings, because they go looking for them? Serious survivorship concern that would weaken the "somebody always knew" thesis. I don't know of work that quantifies it.
- [ ] Would numeric probabilities in intelligence estimates have changed the Iraq outcome, or would "85%" simply have been asserted with the same false confidence? Kent's reform has still not been fully implemented, sixty years on.
- [ ] Why did the CAIB's findings not prevent the next case, given that it explicitly diagnosed the failure to learn? Recursive and unresolved.
- [ ] How should the prevention paradox be handled institutionally — is there any accounting treatment for a counterfactual catastrophe avoided? Without one, prevention budgets will always be cut in calm periods.
- [ ] Was Y2K remediation cost-effective? Genuinely unknown and probably unknowable. The confounders (legacy exposure differences across countries) are not separable.
