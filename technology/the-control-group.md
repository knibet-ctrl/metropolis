# The Control Group — Failures, and Predictions That Were Wrong in Both Directions

> **Status: TIER 1** on the facts of the failures below. **TIER 1** on the
> Liebowitz–Margolis critique of the QWERTY story, which is the most important
> item in the file. **TIER 2** on the general model of what separates adoption
> from quality. This is the file that undermines the rest of the notebook,
> which is why it is here.

**Written from general knowledge without live source verification.** Unit sales
figures and market share numbers are the weakest claims in this file.

---

## The problem this file exists to fix

**We study technologies that were adopted, tell stories about why they were
adopted, and then generalise about "how technology changes society."**

The stories are almost always retrospective rationalisations. Once you know VHS
won, VHS's advantages become obvious. Once you know the Segway lost, its flaws
become obvious. **Neither was obvious at the time to well-informed people with
money at stake.**

The control group is the set of technologies that:

1. Worked, and lost anyway.
2. Were worse, and won anyway.
3. Were confidently predicted and never arrived.

**Any theory of technological change that cannot explain these cases is a
theory of survivorship.**

---

## Failures: good technologies that lost

### Betamax — and why the standard story is wrong

| Claim | Reality |
|---|---|
| Betamax had better picture quality | **Marginally**, and the difference was largely invisible on 1970s televisions |
| Betamax was better, so "worse technology won" | **VHS was better on the attribute buyers were actually choosing** |
| — | **Recording length.** Betamax launched at ~1 hour; VHS at ~2 hours. **Two hours holds a film or a football match. One hour does not.** Sony had optimised the wrong variable |
| — | **Licensing.** JVC licensed VHS broadly and cheaply to many manufacturers; Sony licensed Betamax restrictively. More makers → lower prices → larger installed base |
| — | **The rental market.** Once VHS had the installed base, video rental stores stocked VHS, which drove further adoption |

**Correct lesson: not "the worse technology won" but "the technology that was
better on the dimension the customer was optimising won, and quality on the
dimension the engineer was optimising did not matter."** This is a general
result and it recurs everywhere in this file.

### Concorde

- First flight 1969; commercial service 1976–2003. Twenty aircraft built,
  fourteen in service.
- **It worked.** It was a technical triumph. Three and a half hours to New York.
- **It was killed by economics and regulation, not by engineering, and not
  primarily by the July 2000 Paris crash** — which was the proximate trigger
  for retirement, not the cause of the programme's failure.
- The binding constraints: enormous fuel consumption per seat; roughly 100
  seats; and above all **the sonic boom, which led the US to ban overland
  supersonic civil flight in 1973.** That single regulatory decision removed
  the transcontinental market and confined Concorde to ocean routes.
- BA and Air France acquired their aircraft on terms that reflected the
  manufacturers' write-off of the programme.

**Lesson: a technology can be excellent, work exactly as designed, and be
economically non-viable because of a physical externality that generates a
regulatory response. Nothing in the engineering predicted the ban.**

### The Segway

- Launched 2001 with extraordinary prior hype — investors and prominent
  technologists were quoted predicting it would be bigger than the PC and that
  cities would be redesigned around it.
- **Sold on the order of 140,000 units over about two decades**, against an
  ambition of 10,000 per week.

Why it failed:

| Problem | Detail |
|---|---|
| **No problem to solve** | For distances under a mile, walking. Over a mile, a bicycle or a car. It occupied a gap that did not exist |
| **Price** | Around $5,000. Roughly a car payment for a walking replacement |
| **No legal category** | Sidewalk or road? Neither regulator wanted it. Legality varied by city and country |
| **Social signal** | It made the rider look ridiculous, and this is not a trivial objection |

**But note the sequel, which is the interesting part: the form factor returned
and succeeded as e-scooters and e-bikes about fifteen years later, at roughly a
tenth of the price, with a rental model that removed the purchase decision, and
after cities had built the legal category.** The concept was not wrong. **The
price, the ownership model and the regulatory environment were wrong.** Failure
is frequently a timing and packaging result, not a concept result.

### Google Glass

- Explorer edition 2013, around $1,500; consumer programme cancelled 2015.
- **Killed by a social norm violation, not by capability.** A camera on a face
  in a bar was intolerable to the people nearby. The word "Glasshole" did more
  damage than any technical review.
- Survived for years as an enterprise product (Glass Enterprise Edition, in
  warehousing and manufacturing, where the wearer's colleagues are also
  wearing them and consent is not at issue), discontinued 2023.

**Lesson: social licence is a hard constraint, it is not derivable from the
specification sheet, and it is not predictable in advance.** Nothing in Glass's
engineering contains "people will hate you for wearing this."

### Nuclear power — the largest and most consequential case

| Fact | Detail |
|---|---|
| Global share | Roughly **10% of world electricity**, down from a peak around **17–18% in 1996** |
| Proof of feasibility | **France's Messmer Plan (1974)**: 50+ reactors ordered within about fifteen years, standardised designs, reaching roughly 70–75% of national electricity. **It was demonstrably achievable at national scale, quickly** |
| Safety record | On deaths per unit of energy produced, nuclear is comparable to wind and solar and **orders of magnitude better than coal**, including Chernobyl and Fukushima. This comparison is robust across methodologies |
| What stopped it | Three Mile Island (1979), Chernobyl (1986), Fukushima (2011); cost escalation; financing costs; bespoke one-off designs; regulatory ratcheting |
| **Negative learning** | **Lovering, Yip & Nordhaus (2016)**: US construction costs **rose** with cumulative experience — the opposite of Wright's law. France's rose more slowly; **South Korea's actually fell.** The difference tracks design standardisation and regulatory stability, not physics |

**Steelman the other side, because "irrational public fear killed nuclear" is
too easy:**

- Cost overruns are real, enormous and repeated (Flamanville, Olkiluoto,
  Hinkley Point C, Vogtle). **Cross-ref `risk/base-rates.md`: the base rate for
  nuclear construction schedules is terrible, and that is information.**
- High capital cost with long build times is punishing at any positive interest
  rate.
- Waste and proliferation are genuine externalities, not phantoms.
- Cheap shale gas after 2008 undercut nuclear economics independently of any
  public opinion.

**Honest conclusion: nuclear's stall is a joint product of real cost problems
and a regulatory/political response disproportionate to the measured risk.
Neither the "irrational fear" story nor the "it was just too expensive" story
is sufficient. The South Korean cost trajectory is the strongest evidence that
the cost problem was partly institutional rather than inherent.**

### Others worth knowing

| Case | Lesson |
|---|---|
| **Iridium** (1998) | $5bn satellite phone network, bankrupt within about a year. Terrestrial mobile expanded faster than the multi-year satellite build. **Losing a race against a technology that was improving while you built** |
| **AT&T Picturephone** (1970) | Correct concept, wrong price, wrong decade, chicken-and-egg network problem |
| **Kodak** | **The standard story is wrong.** Kodak invented the digital camera (Steven Sasson, 1975) and *did* invest heavily in digital, leading the US digital camera market at points. It died anyway because **digital imaging had structurally worse economics than film's razor-and-blades model** — there is no consumable to sell. **"Incumbents are stupid" is a much less useful lesson than "some transitions destroy the business model regardless of competent management"** |
| **Xerox PARC** | Also usually told wrong. Xerox *did* commercialise, with the Star (1981) at around $16,000 per workstation. It priced itself out. **Failure of pricing and channel, not of vision** |
| **Apple Newton** (1993) | Right concept, immature handwriting recognition, and mockery. The Palm Pilot succeeded three years later by doing less |
| **3D television** (c. 2010) | Every major manufacturer, simultaneously, and no consumer demand at all. **An entire industry can be wrong at once** |

---

## The other direction: worse technologies that won

### QWERTY — the double lesson, and the most important item in this file

**The standard story**, canonised by **Paul David's "Clio and the Economics of
QWERTY" (1985)**, the founding text of path-dependence economics:

> QWERTY was designed in the 1870s to *slow typists down* and prevent
> typebar jams. It is inefficient. Dvorak's 1936 layout is far faster. But
> the installed base of trained typists locked us into the inferior standard
> forever. Markets can get stuck on bad equilibria.

**Liebowitz & Margolis, "The Fable of the Keys" (1990), took this apart:**

| Standard claim | The critique |
|---|---|
| QWERTY was designed to slow typists | More plausibly designed to separate **frequently-adjacent letter pairs** so typebars would not clash — that is, to enable *faster* effective typing on that mechanism, not slower |
| Dvorak is dramatically faster | **The key supporting studies were conducted or supervised by Dvorak himself**, with serious methodological problems |
| Independent confirmation exists | A **1956 US General Services Administration study (Earle Strong)** found **no advantage** to retraining typists on Dvorak. Later ergonomic work finds small differences at best |
| Lock-in trapped us | Retraining costs are modest; individuals who wanted Dvorak could switch; software has supported alternative layouts for decades. **Few switch, which is evidence the gain is small** |

**The double lesson, and this is why the case is in the notebook:**

1. **The flagship example of path dependence is largely a myth**, repeated for
   forty years by people who never checked it. Same structural failure as the
   Moses bridges and the stirrup. **Check your favourite example.**
2. **But path dependence and lock-in are nevertheless real.** The QWERTY story
   being weak does not make lock-in false. **Better examples exist:**

| Genuine lock-in | Why it is stronger than QWERTY |
|---|---|
| **Mains voltage and frequency** (110/60 vs 230/50) | Permanent global split with real ongoing costs; switching is genuinely infeasible |
| **Railway gauge** | Brunel's 7ft broad gauge was **demonstrably better engineering** and lost to installed mileage. Break-of-gauge costs were real and persisted for decades |
| **US customary units** | The Mars Climate Orbiter was lost in 1999 to a unit mismatch. The costs are documented and recurring |
| **Driving side** | Sweden's 1967 switch (Dagen H) shows it is *possible* and shows exactly how expensive |
| **IPv4 → IPv6** | Technically superior successor, specified in 1998, still not fully adopted nearly thirty years later |

**And be fair about the critics too: Liebowitz & Margolis had a policy agenda** —
they were arguing against antitrust intervention justified by lock-in claims,
particularly against Microsoft. Their critique of QWERTY is nonetheless
well-evidenced and has largely held up. **Both things can be true.**

### Other cases where the "worse" technology won

| Case | What actually happened |
|---|---|
| **VHS over Betamax** | Won on the attribute that mattered. Not really a "worse won" case at all |
| **TCP/IP over OSI** | OSI had better documents and formal standing. TCP/IP had **free, running implementations**. Shipping beat specifying |
| **x86 over cleaner architectures** | Backward compatibility and volume overwhelmed elegance for decades |
| **JavaScript** | Designed in about ten days in 1995, has become the most widely deployed programming language in history, because it was in the browser |
| **Fax machines in Japan** | Persisted for decades after email, because of *hanko* seals, handwriting norms and an installed base in business practice. **A social explanation, not a technical one** |

**The unifying observation: "worse" is almost always measured on a dimension
that the adopters were not optimising.** Before declaring that a bad technology
won, identify which attribute the buyer was actually choosing on. Usually the
answer dissolves the puzzle — and where it does not (railway gauge), you have
found a genuine lock-in case.

---

## Predictions that were wrong in both directions

**The both-directions requirement is the point. Any list containing only failed
dismissals is propaganda for optimism; any list containing only failed hype is
propaganda for cynicism.**

| Predicted and never arrived | Dismissed and arrived anyway |
|---|---|
| Flying cars (the Aerocar flew and was certified in 1949; nobody bought one) | Personal computers |
| Paperless office (paper use rose for decades; then fell, ~40 years late) | The commercial internet (Stoll, *Newsweek* 1995) |
| Videophones as imagined (Picturephone, 1970) | Video calling, eventually — free and bundled |
| "Too cheap to meter" electricity | Smartphones as the primary computing device (Ballmer, 2007) |
| Nuclear-powered aircraft, cars, excavation | Mass adoption of the mobile phone outside business |
| MOOCs replacing universities (2012) | E-commerce at scale |
| Blockchain replacing institutions (2017–2022) | Solar PV at current costs — **essentially every official energy agency forecast for two decades underestimated solar deployment, repeatedly and in the same direction** |
| 3D printing replacing manufacturing | Wikipedia working at all |
| "The internet makes geography irrelevant" | Cheap air travel for ordinary people |
| Self-driving cars "by 2020" | Self-driving cars, in a few cities, later |

**The solar entry deserves emphasis.** It is not a story about a lone visionary
being dismissed. It is a story about **institutional forecasts being wrong in
the same direction for twenty years**, published annually, with no correction
to the method. **Systematically biased official forecasts are more informative
than individual bad predictions, because they reveal a structural error rather
than a personal one.** Cross-ref `risk/forecasting.md`.

---

## What actually separates adoption from quality

A working model, offered as **Tier 2** — this is a synthesis, not a
literature finding:

| Factor | Question | Failure it explains |
|---|---|---|
| **1. Complementary infrastructure** | Does the stuff it needs already exist? | Iridium; electric cars before charging networks; Picturephone |
| **2. Legal and social category** | Does anyone know what it *is*, legally? | Segway; drones; early e-scooters |
| **3. Incentive alignment** | Does the value accrue to whoever has to change behaviour? | Enterprise software; medical records systems; most B2B failures |
| **4. The attribute actually being optimised** | Better on *which* dimension — and is it the buyer's? | Betamax; Concorde; Dvorak |
| **5. Social licence** | Will bystanders tolerate it? | Google Glass; nuclear power; GM crops in Europe |
| **6. Installed base and switching cost** | What must be abandoned to adopt? | VHS; QWERTY; IPv6; x86 |
| **7. Incumbent distribution** | Can an incumbent copy it and reach more customers faster? | Most consumer software features |
| **8. Cost trajectory of the alternative** | Is the thing you are racing improving faster than you? | Iridium vs terrestrial mobile; Concorde vs cheap subsonic mass air travel |
| **9. Price relative to the problem** | Is it priced like a solution to the problem it solves? | Segway ($5,000 walking replacement); Xerox Star ($16,000) |

**Notice what is not on this list: technical merit.** It enters only through
factor 4, and only on the dimension the buyer cares about.

---

## Where the popular story is wrong

| Popular story | Correction |
|---|---|
| **"QWERTY proves markets get locked into bad standards"** | The flagship example is largely myth. Lock-in is real; use mains voltage or railway gauge instead |
| **"Betamax was better and lost"** | It was worse on recording length and licensing, which were the deciding attributes |
| **"Kodak ignored digital"** | Kodak invented it and invested in it. The business model, not the management, was the problem |
| **"Xerox failed to commercialise PARC"** | Xerox commercialised badly and expensively. Different failure, different lesson |
| **"Concorde was killed by the crash"** | Killed by fuel economics and the 1973 US overland supersonic ban. The crash was the trigger, not the cause |
| **"Public fear killed nuclear power"** | Partly. Cost escalation and negative learning curves are real and were mostly self-inflicted through non-standardisation |
| **"Good technology wins eventually"** | The Aerocar was certified in 1949. Dvorak has been available for ninety years. Concorde flew for 27 years and stopped |
| **"Failures were obviously going to fail"** | Hindsight. Sony, Xerox, AT&T, Google and Kleiner Perkins are not staffed by fools, and they all backed things on this list |

---

## Open questions

- [ ] Is there a systematic, non-anecdotal dataset of technology failures?
      Everything here is a curated anecdote list and that is exactly the
      survivorship problem the file was written to address. **This is the
      biggest weakness in the notebook.**
- [ ] Does the nine-factor model above have any out-of-sample predictive value,
      or does it just accommodate any outcome after the fact?
- [ ] The Segway/e-scooter pattern — same concept, right price and legal
      environment fifteen years later — how common is it? Is there a
      systematic "too early" category with a characteristic lag?
- [ ] Why did US nuclear costs rise with experience while South Korean costs
      fell? If this is design standardisation, it is one of the most valuable
      policy findings available and it should be much better known.
- [ ] Have official energy forecasting agencies corrected the method that made
      them underestimate solar for two decades, or only the numbers?
- [ ] Is there a case where a genuinely better technology lost, stayed lost, and
      the loss was demonstrably costly — that is, a clean lock-in case with a
      measured welfare loss? Railway gauge is the best candidate. Has anyone
      priced it?
