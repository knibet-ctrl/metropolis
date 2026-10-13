# Organisational Trust

Inside firms and teams: psychological safety, agency problems, and why monitoring backfires.

> **Status: TIER 2 — contested but tractable.** The psychological safety literature is real but weaker than its popularity implies, is largely cross-sectional, and rests partly on self-report measures with an obvious common-method problem. The motivation crowding-out literature is real in some forms and over-generalised in others. Flagging replication issues throughout is not optional here — it is the main thing that separates this file from a management book.

> Written from general knowledge on 2026-09-01 without live source verification.

Cross-reference: **[../leaders/](../leaders/) mechanism #13 (error correction)**. The claim below is that psychological safety and the andon cord are the same mechanism at different scales.

---

## The origin story, which is better than the theory

Amy Edmondson's key paper is "Psychological Safety and Learning Behavior in Work Teams" (*Administrative Science Quarterly*, 1999). The origin is worth telling because it contains the whole insight.

She was working on a study of medication errors in hospital nursing units, expecting better-led units to make fewer errors. The data showed the opposite: units with better-rated leadership and climate reported **more** errors. The resolution was that they were not making more errors; they were **reporting** more. Units where nurses feared blame recorded fewer errors and made at least as many, invisibly.

**The measured variable was not error rate. It was the willingness to make errors visible.**

Edmondson defined psychological safety as a shared belief that the team is safe for interpersonal risk-taking — that you will not be humiliated, punished or downgraded for speaking up with a question, a concern, a mistake or a dissenting view. The construct predates her: Edgar Schein and Warren Bennis used the term in the 1960s.

**The distinction she has to keep repeating, because it keeps getting lost:** psychological safety is *not* comfort, niceness, lowered standards or consensus. Her own 2×2 crosses psychological safety with accountability: low safety and low accountability produces apathy; low safety and high accountability produces anxiety; high safety and low accountability produces a comfort zone; high safety and high accountability is the learning zone. Most corporate adoptions of the term collapse it into the comfort zone quadrant, which is the failure mode.

---

## Project Aristotle, and how much weight it can bear

Google ran an internal study (roughly 2012–2015, led by Julia Rozovsky, popularised by a *New York Times Magazine* piece by Charles Duhigg in 2016) analysing what distinguished effective teams. They initially expected team composition to matter — mix of skills, seniority, personality types — and found it largely did not. Five factors emerged, with **psychological safety by far the most important**, followed by dependability, structure and clarity, meaning, and impact.

**What it is worth:** a large-N observational study inside a serious organisation, conducted by people with no prior commitment to the construct, that converged on the same variable an independent academic literature had identified. That convergence is meaningful.

**What it is not worth:**

- Not peer reviewed and not fully published. Effect sizes, model specifications and the "effectiveness" operationalisation were never released for scrutiny.
- Conducted inside a single, extremely unusual company — high-selection knowledge workers, abundant resources, low job insecurity. The external validity to a factory, a hospital or a small firm is assumed, not shown.
- Largely cross-sectional and self-reported on both sides, which is the classic common-method-variance setup: people who feel good about their team rate both its safety and its effectiveness highly.

**Treat Project Aristotle as corroborating evidence, not as the foundation.** It is cited as the foundation roughly a thousand times more often than the underlying academic work, which is the wrong way round.

The academic meta-analytic picture (Frazier and colleagues, around 2017) shows psychological safety correlating positively with learning behaviour, information sharing, engagement and performance, at magnitudes that are real but moderate, in a literature that is predominantly cross-sectional. There are few good longitudinal or experimental designs. **The direction of causation is not well established: high-performing teams may simply feel safer.**

---

## The andon cord: the same mechanism, made physical

In the Toyota Production System, any line worker can pull the andon cord to signal a problem. The line stops (or, in the refined version, stops at the end of the fixed-position cycle if the problem is not resolved), a team leader comes, and the problem is fixed at source rather than passed downstream. It is one half of *jidoka* — automation with a human touch, machines that stop themselves when something is wrong — associated with Taiichi Ohno and Toyota's development of the system through the postwar decades.

The design achievement is not the cord. It is that **pulling it is normal, expected and status-neutral**. In a conventional plant, stopping the line is an act of insubordination that costs you socially and possibly professionally. Toyota engineered the cost of surfacing a problem down toward zero, and then engineered the cost of *not* surfacing one upward.

**NUMMI is the demonstration.** In 1984 GM and Toyota opened a joint venture in Fremont, California, in a plant GM had closed. GM's Fremont plant had been among its worst — absenteeism reportedly around 20%, chronic quality problems, sabotage, a hostile union relationship. NUMMI rehired most of the same workforce, including the union leadership. Within a couple of years it was producing at or near Toyota-level quality.

**Same people. Different system. This is the strongest single case in this library for the proposition that structure beats exhortation**, and it is why the "we need better people" diagnosis should always be the last hypothesis rather than the first. (Caveat: the comparison is not a controlled experiment — product mix, capital equipment and market conditions differed, and GM's later failure to propagate NUMMI's methods across its own plants is itself an important, separate story about why organisational learning does not transfer.)

**The identity claim:** psychological safety and the andon cord are the same mechanism — *reducing the personal cost of surfacing bad news* — implemented at different scales and in different media. One is a norm, one is a physical affordance. The physical affordance is more robust, because it does not depend on the current manager's disposition. **Where you can convert a norm into an affordance, do it.**

| Instance | Domain | Mechanism |
|---|---|---|
| Andon cord | Manufacturing | Physical, status-neutral stop signal |
| Aviation ASRS reporting | Aviation safety | Reports go to **NASA**, not the FAA, with limited immunity from enforcement — the payer/punisher is deliberately separated from the recipient |
| Crew Resource Management | Cockpit | Explicit protocols for a junior officer to challenge a captain |
| Blameless post-mortem | Software | Ritualised separation of causal analysis from blame allocation |
| Surgical checklist / pre-op briefing | Medicine | Named introductions and an explicit invitation to raise concerns |
| Psychological safety | Teams generally | Norm-level version of all of the above |

The ASRS design detail is the crucial generalisable one: **the body receiving the reports must not be the body that punishes.** Every organisation that routes its confidential reporting line back through the management chain it is meant to check has built theatre.

---

## Principal–agent problems

Jensen and Meckling (1976) formalised agency costs: whenever a principal delegates to an agent with different interests and better information, the principal bears monitoring costs, the agent bears bonding costs, and there is a residual loss that neither can eliminate.

**Holmström's informativeness principle** (1979): a contract should condition on any signal that carries information about the agent's action, however noisy. Useful, and often misapplied — it justifies including relative performance measures, not adding metrics indiscriminately.

**Holmström and Milgrom (1991) on multitasking** is the more important result and is badly under-known outside economics. When an agent allocates effort across multiple tasks and only some are measurable, **strengthening incentives on the measurable tasks reallocates effort away from the unmeasurable ones**. The optimal response is often *weaker* incentives across the board, or no explicit incentives at all, because a low-powered incentive scheme distorts less. Bengt Holmström and Oliver Hart shared the Nobel in 2016.

This result explains an enormous number of organisational disasters:

| Case | Measured and rewarded | Unmeasured and destroyed |
|---|---|---|
| Wells Fargo cross-selling | Products per household ("Eight is Great") | Whether the customer wanted or knew about the account. Roughly 3.5 million unauthorised accounts; $185M CFPB settlement in 2016; a $3B settlement with DOJ/SEC in 2020; the CEO barred from banking |
| Sales-only commission | Bookings | Deliverability, customer retention, honest scoping |
| Hospital wait-time targets | Time to first contact | Actual treatment, gaming via reclassification, ambulances held outside |
| School accountability testing | Test scores | Curriculum breadth, teaching to the test, outright cheating (Atlanta, 2009–2015) |
| Ratings agencies | Volume of issuer business | Accuracy of ratings. Same structural flaw as Arthur Andersen: the monitored party pays the monitor |

**Wells Fargo is not primarily a story about dishonest employees.** Roughly five thousand people were fired for the conduct, which is a strong hint that the causal variable was not individual character. It is a multitasking failure with an aggressive quota system and a closed error-reporting channel — employees who raised concerns reported retaliation. Every element of Edmondson's model failing simultaneously.

---

## Motivation crowding-out

The claim: extrinsic incentives can *reduce* total motivation by displacing intrinsic motivation, so that adding a reward or penalty produces less of the behaviour than adding nothing.

**The evidence, honestly ranked:**

| Study | Finding | How much weight it bears |
|---|---|---|
| Deci (1971); Deci, Koestner & Ryan (1999) meta-analysis | Tangible, expected, performance-contingent rewards reduce intrinsic motivation for tasks that are already interesting. Verbal praise and unexpected rewards do not | Substantial, but contested — Eisenberger and Cameron (1996) argued the effect is limited and over-generalised, and the exchange between the camps was sharp. The narrow version survives; "rewards destroy motivation" does not |
| Titmuss (1970) on blood donation | Paying for blood reduced supply and quality relative to voluntary systems | Influential; the original empirical support was weaker than the argument's fame |
| Mellström & Johannesson (2008) | Payment for blood donation reduced female donation; the effect vanished when the payment could be donated to charity | Clean, small, and the charity manipulation is genuinely informative — it isolates the signalling/self-image channel |
| Frey & Oberholzer-Gee (1997) | In a Swiss community surveyed about hosting a nuclear waste repository, stated willingness to accept **fell** from roughly half to around a quarter when financial compensation was offered | The standout field-adjacent result. It is a stated-preference survey, not revealed behaviour, which limits it |
| Falk & Kosfeld (2006), "The Hidden Costs of Control" | Principals who imposed a minimum-effort constraint received *lower* effort than those who did not | Laboratory, but a clean design directly on the monitoring question |
| **Gneezy & Rustichini (2000), "A Fine is a Price"** | Ten Haifa daycare centres; a small fine (about 10 shekels) for late pickup **increased** lateness, and lateness stayed high after the fine was withdrawn | See caveats below |

**The Gneezy–Rustichini caveats, stated plainly because this study is quoted as if it were a law:**

- Ten centres, a handful in the treatment group. The unit of randomisation is the centre, so the effective sample is tiny.
- One country, one sector, one time period, one specific fine level. The fine was small; the finding may be about *price level* rather than about crowding-out at all — a large fine might well have worked.
- The most striking claim — that behaviour did not revert after the fine was removed — rests on the smallest and weakest part of the data.
- **I am not aware of a large, well-powered, direct replication.** The result is widely believed, frequently taught, and thinly evidenced. Treat the *direction* as a live hypothesis and the *magnitude* as unverified.

**The general replication problem, which applies to this entire file:**

- Camerer and colleagues (2016, *Science*) attempted replications of eighteen experimental economics papers from top journals; around eleven replicated, with effect sizes roughly two-thirds of the originals.
- The Social Sciences Replication Project (Camerer et al., 2018) replicated twenty-one social science studies from *Nature* and *Science*; around thirteen replicated, with effect sizes roughly half.
- **The oxytocin–trust literature is a cautionary tale specific to this domain.** Kosfeld and colleagues (2005, *Nature*) reported that intranasal oxytocin increased transfers in the trust game. This spawned a large popular literature about a "moral molecule". Subsequent reviews (Nave, Camerer and McCullough, around 2015) found the evidence weak, the replications inconsistent, and the pharmacological premise — that intranasal administration meaningfully reaches the brain at those doses — questionable. **A headline trust finding, in a top journal, that largely did not survive.**
- Ego depletion, social priming and power posing all failed at scale. Several are adjacent to constructs used in the trust literature.

**What to do with this:** downgrade every single striking experiment by a large factor, and upgrade findings that show up across methods — laboratory, field, observational and historical. Crowding-out passes that test in weak form (monitoring and payment sometimes reduce voluntary contribution, especially where the behaviour signals something about the person) and fails it in strong form ("incentives backfire").

---

## Trust between people inside organisations

- Macaulay's classic 1963 study, "Non-Contractual Relations in Business", found that businesspeople in Wisconsin routinely made significant deals with minimal contractual detail and were reluctant to invoke contracts even when they had them — invoking the contract was understood as ending the relationship. The contract is a fallback, not the operating system.
- Coase (1937) and Williamson: firms exist because market transactions have costs — searching, negotiating, enforcing — and hierarchy economises on them, especially where assets are relationship-specific and hold-up is possible. Trust is, in this frame, a cheaper substitute for both contracts and hierarchy.
- Meta-analytic work on team trust (De Jong, Dirks and Gillespie, around 2016) finds a positive trust–performance association of moderate size, **strongly moderated by task interdependence**: trust matters much more where members actually depend on each other's work. This is an underused practical result. In genuinely parallel work, low trust costs little.

---

## Where the popular story is wrong

- **"Psychological safety means being nice."** It means the cost of dissent is low, not that dissent is rare. Edmondson's high-safety/low-accountability quadrant is a failure state, and it is what most corporate programmes actually produce.
- **"Project Aristotle proved psychological safety drives performance."** It is unpublished, single-company, cross-sectional and self-reported on both sides. It corroborates; it does not prove.
- **"Fines backfire."** Sometimes, in some settings, at some magnitudes, for behaviours that carry moral signalling value. The evidence base for the strong claim is one small field experiment plus a laboratory literature with known replication problems.
- **"Align incentives and behaviour follows."** It does — including the behaviour you did not intend. The multitasking result means the first question about any new metric should be "what unmeasured thing will now be sacrificed to it?"
- **"Bad outcomes come from bad people."** NUMMI, Wells Fargo's five thousand terminated employees, and Edmondson's nursing units all point the other way. Character is real; structure is bigger and more manipulable.
- **"More monitoring is safer."** Monitoring that replaces judgement produces compliance theatre and closes the error-reporting channel. The Boeing and Enron cases in [the-control-group.md](the-control-group.md) both had extensive formal monitoring.
- **"Trust is soft."** It is a transaction-cost variable. Where task interdependence is high, it is measurable in cycle time and rework.

---

## Open questions

- [ ] Is psychological safety causally upstream of performance, or a by-product of it? A longitudinal or experimental design is badly needed and mostly absent.
- [ ] Has "A Fine is a Price" ever been replicated at scale? If not, why is it in every textbook?
- [ ] Does crowding-out require the behaviour to be self-signalling, as the Mellström–Johannesson charity manipulation suggests? That would be a clean boundary condition.
- [ ] Can psychological safety be created by structural affordances alone, independent of the manager — the andon-cord conversion — and is there evidence for it?
- [ ] What is the actual effect size of blameless post-mortems and near-miss reporting on subsequent incident rates?
- [ ] How does psychological safety behave in remote and asynchronous teams, where the status cost of speaking may be lower but the channel is thinner?
- [ ] Is there any organisation-level intervention with credible randomised evidence, or is this entire field observational?
