# The Questions — Disaggregating "What Does a Technology Do?"

> **Status: TIER 1** that the question needs disaggregating and that the
> sub-questions have different answer-types. **TIER 2** on the specific
> taxonomy below — it is mine, assembled from standard economic-history and
> STS categories, not a canonical framework you can cite.

**Written from general knowledge without live source verification.**

---

## The problem

"What effect did the internet have on society?" is not a question. It is at
least six questions wearing one coat, and they have different evidence
standards, different disciplines, different time constants and wildly different
tiers of confidence. Asking them together guarantees a bad answer, because the
easy sub-question (what does it do?) gets answered confidently and the hard
sub-question (how does power redistribute?) gets answered with the same
confidence.

**Sort the question before answering it.** This is the same move as `risk/`
sorting risk from uncertainty from ignorance, and it has the same payoff.

---

## The six questions

| # | Question | What it really asks | Discipline | Time constant | Tier |
|---|---|---|---|---|---|
| 1 | **What does it do?** | Technical capability. What physical or informational operation is now possible? | Engineering, physics | Immediate | **TIER 1** |
| 2 | **What does it make cheap?** | Which cost curve collapsed, and by how many orders of magnitude? | Economics, price history | 1–20 years | **TIER 1–2** |
| 3 | **What does it displace?** | Which existing activity, skill, asset or institution becomes uneconomic? | Labour and business economics | 5–30 years | **TIER 2** |
| 4 | **What does it enable?** | What new activities become possible once the cheap thing is cheap — including activities requiring complementary inventions that don't exist yet | Economic history, design | 20–60 years | **TIER 2–3** |
| 5 | **How does power redistribute around it?** | Who captures the surplus, who gains coercive capability, whose bargaining position collapses | Political economy | 10–100 years | **TIER 2–3** |
| 6 | **What atrophies because it is no longer needed?** | Which skills, redundancies, institutions and forms of local knowledge quietly disappear | History, anthropology | 30–100+ years | **TIER 3** |

And a seventh, which is malformed:

| 7 | **Was it good?** | Aggregation across incommensurable people, across generations, against unobservable counterfactuals | — | — | **TIER 4 as usually posed** |

---

## Question 1 — What does it do?

The only one that is reliably answerable in advance, and the only one anybody
puts on the box. It is also the one that carries the least information about
consequences.

Steam engines convert heat into rotary motion. Transistors switch current.
Containers are steel boxes of standard dimensions with corner castings. None of
those sentences predicts anything that follows.

**Warning:** technical capability is frequently *over*-specified and socially
*under*-specified in forecasts. The AT&T Picturephone worked. Concorde worked
beautifully. The Segway worked exactly as designed. Working is not the hard
part.

---

## Question 2 — What does it make cheap?

**This is the highest-return question in the file and the one most often
skipped.** It is close to a general-purpose forecasting tool.

The procedure: identify the cost curve that collapsed, express it in orders of
magnitude, then ask what was previously rationed by that cost and is now
un-rationed.

| Technology | What got cheap | Rough magnitude | What became un-rationed |
|---|---|---|---|
| Printing | Copying text | ~100–300× per copy in the first century | Identical copies, therefore standardisation, cross-referencing, errata, mass polemic |
| Steam + coal | Concentrated mechanical power, anywhere | Removed the water/wind/muscle siting constraint entirely | Factory location; scale; night work |
| Container | Loading and unloading cargo | Reportedly >30× per ton (Levinson — **verify**) | Distance itself; therefore supply-chain fragmentation |
| Contraceptive pill | Reliable, female-controlled fertility timing | Discrete, not continuous — a step change in reliability | Long-horizon career investment by women |
| Air conditioning | Habitable indoor temperature in hot climates | Made previously marginal regions economically normal | Sun Belt settlement, sealed-glass architecture |
| Computing | Copying, transmitting, searching, coordinating | 10⁶–10⁹ over decades | Global coordination, zero-marginal-cost distribution, ubiquitous measurement |
| LLMs | Producing plausible text and code | Contested; large for first drafts | Unclear, and that is the honest answer |

**The corollary is the useful part: when something becomes free, the scarce
complement becomes valuable.** Cheap copies made attention scarce (cross-ref
`existence/attention.md`). Cheap shipping made regulatory arbitrage and labour
cost differentials valuable. Cheap information made trust and verification
valuable — cross-ref `knowledge/`.

---

## Question 3 — What does it displace?

**More predictable than what it enables, and systematically less discussed,
because the losers are identifiable and inconvenient.**

Displacement is asymmetric in a way that dominates the politics:

| Property | Gains | Losses |
|---|---|---|
| Distribution | Diffuse, spread over millions of consumers | Concentrated in specific trades, towns, cohorts |
| Timing | Slow, cumulative, decades | Fast, within a few years |
| Visibility | Invisible (things are slightly cheaper) | Highly visible (a mill closed) |
| Political organisation | Impossible to organise | Easy to organise |
| Compensation | Never paid | Rarely paid |

**This asymmetry, not stupidity or fear, explains essentially all technology
resistance in history.** The croppers of Yorkshire, the New York longshoremen,
the London black-cab drivers and the illustrators of the 2020s are making the
same structurally correct observation: *the aggregate gain is real and none of
it is coming to me.*

See case-industrial.md on the Luddites and unintended-consequences.md on task
displacement.

---

## Question 4 — What does it enable?

The interesting one, and largely unforecastable, for a structural reason rather
than a failure of imagination:

**Enabled uses depend on complementary innovations that have not been invented
yet, and on organisational forms that nobody has tried.**

Paul David's dynamo case is the canonical demonstration. Electric motors were
available in factories from the 1880s. Manufacturing productivity did not jump
until the 1910s–1920s, because the gain did not come from replacing the steam
engine with an electric one — it came from abandoning the central line-shaft
entirely and giving every machine its own motor, which let you lay out the
factory by workflow instead of by proximity to the driveshaft, and let you
build single-storey plants. **That reorganisation was the innovation. It took
roughly forty years and a generational turnover of factory managers.**

You cannot forecast that from the motor's specification sheet. Nobody could
have. This is the strongest available prior for how to think about AI in
case-computing-and-ai.md.

---

## Question 5 — How does power redistribute?

**The most consequential question and the least-often asked.** Three distinct
mechanisms, frequently conflated:

| Mechanism | Question | Example |
|---|---|---|
| **Value capture** | Who ends up with the surplus? | Not the inventors. Not usually the users. Usually whoever controls the standard, the distribution channel or the complementary scarce asset |
| **Coercive capability** | What can the state (or a firm) now do to people that it could not before? | Registries, cameras, telecoms metadata, payment rails |
| **Bargaining position** | Whose outside option improved or collapsed? | Dockworkers after containerisation; skilled croppers after the shearing frame; possibly some white-collar workers now |

Two robust regularities, both Tier 2 leaning Tier 1:

- **The inventor almost never captures the value.** Tim Berners-Lee gave away
  the web. Tantlinger's twist-lock was released royalty-free. Xerox PARC
  invented the GUI and Apple and Microsoft monetised it. Value accrues to
  complementary scarce assets, not to the idea.
- **Capability outlives intent.** A surveillance system built by a government
  you trust is inherited by the next one. See power-and-technology.md.

---

## Question 6 — What atrophies?

The slowest and quietest question. It gets asked, if at all, a generation late.

| Technology | What quietly went away | Noticed? |
|---|---|---|
| Air conditioning | Climate-adapted vernacular architecture: courtyards, thick walls, high ceilings, cross-ventilation, verandas | Only after the buildings were gone |
| GPS | Route knowledge, map reading, and — genuinely — the redundancy of being able to navigate when the system is down | Partially |
| Digital classifieds | Local newspaper revenue, therefore local political accountability journalism | Late, and the causal chain is still under-appreciated |
| Printing | Trained memory arts; manuscript culture's tolerance for variation | Yates, *The Art of Memory* |
| Mechanised agriculture | Local seed varieties, dispersed agronomic knowledge, rural social density | Contested, romanticised, but partly real |

**Caveat, and it matters:** this section is where technology writing turns into
nostalgia. Most things that atrophied deserved to. The honest form of the
question is not "what did we lose" but "**which lost capability was a
redundancy we will need when the primary system fails?**" That reframing makes
it a `risk/` question rather than an aesthetic one.

---

## Where the popular story is wrong

| Popular framing | What's wrong with it |
|---|---|
| **"Technology X changed everything"** | Collapses six questions into one and answers the hard ones with the confidence appropriate to the easy one |
| **"The effects were unintended"** — said as if that were unusual | The unintended effects are the *normal* case, and they are where nearly all the surplus and damage live. Intended effects are competed away because everybody modelled them |
| **"We couldn't have known"** | Sometimes true (Q4, Q6). Often false: displacement (Q3) is usually visible in advance to the people about to be displaced, and is ignored because they lack power, not because the information was missing |
| **"It's a tool; it's neutral; it depends how you use it"** | Trivially true and analytically useless. Tools change the *cost* of actions, and changing relative costs is not neutral. A cheap gun and an expensive gun produce different societies |
| **"The technology decided"** | Determinism. Wrong in the way this whole notebook is about |
| **"It's all just social; the tech is incidental"** | The opposite error, equally wrong. Thermodynamics does not negotiate |

---

## Open questions

- [ ] Is the "what does it make cheap" heuristic actually predictive out of
      sample, or does it only look good retrospectively because we pick the
      cost curve that explains the outcome we already know?
- [ ] Is the ~40-year complementary-innovation lag (David's dynamo) a real
      regularity with a mechanism, or two or three cases fitted to a line?
- [ ] Can displacement (Q3) be forecast well enough to compensate people
      *before* it happens, rather than after? Has this ever been done?
- [ ] Is there any historical case where the power-redistribution consequences
      (Q5) were correctly forecast in advance by anyone other than the losers?
- [ ] What would a serious "atrophy audit" look like — identifying which lost
      capabilities are load-bearing redundancies rather than nostalgia?
- [ ] Does the disaggregation above miss a category? Candidate omissions:
      effects on *preference formation* (what people come to want), and
      effects on the *time horizon* of decision-making.
