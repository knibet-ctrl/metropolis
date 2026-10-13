# Power and Technology — Who Captures the Value

> **Status: TIER 1** that standards confer durable advantage, that network
> effects produce concentration, and that surveillance capability outlives the
> intent it was built for. **TIER 2** on the magnitude of network effects
> (Metcalfe's n² is probably wrong). **TIER 2 and genuinely unresolved** on
> whether patents promote or retard innovation, which varies enormously by
> industry.

**Written from general knowledge without live source verification.**

---

## The central asymmetry

**The person who invents a technology, and the person who uses it, are almost
never the person who captures its value.**

| Inventor | What they got | Who captured it |
|---|---|---|
| Gutenberg | Bankruptcy; lost the press to his financier Fust in 1455 | Venetian printers, the Stationers' Company, later publishers |
| Keith Tantlinger (twist-lock) | A royalty-free release, at McLean's direction | Shippers, retailers, exporting economies, consumers |
| Malcom McLean | Two fortunes made, both largely lost; United States Lines bankrupt 1986 | Same as above |
| Xerox PARC (GUI, Ethernet, laser printer, WYSIWYG) | Xerox monetised the laser printer well and the rest badly | Apple, Microsoft, and eventually everyone |
| Tim Berners-Lee | Released the web without patent or royalty, deliberately | Effectively the entire consumer internet industry |
| Steven Sasson (digital camera, Kodak, 1975) | A patent that expired around 2007 | Camera and later phone manufacturers |
| Douglas Engelbart (the mouse, NLS) | The patent expired before the mouse became ubiquitous | Apple, Logitech, Microsoft |

**Why: value accrues to whatever remains scarce after the invention makes
something abundant.** Invention makes a capability abundant. Scarcity moves to
the complements — distribution, standards, installed base, brand, data,
regulatory position, or a physical bottleneck.

**The operational question is therefore never "who invented it" but "what
became scarce, and who owns that."**

---

## Standards and protocol control

**Whoever sets the protocol captures value for as long as the protocol lasts,
and protocols last far longer than firms.**

### Qin Shi Huang, 221 BCE — the deepest example available

Cross-ref `leaders/`. On unifying China, the Qin state standardised:

| Standardised | Consequence |
|---|---|
| **The script** (small seal script, under Li Si) | A single written language over a continent of mutually unintelligible spoken languages. **A literate bureaucracy became possible at imperial scale, and China's political unity 2,200 years later still partly rests on this** |
| Weights and measures | Taxation and grain administration became comparable across regions |
| Coinage (the round *banliang* with a square hole) | Fiscal integration |
| **Axle widths** | Cart ruts in the loess roads were effectively a gauge. Standardising axles made the road network interoperable — and made military logistics work |
| Law | Uniform Legalist code |

**The Qin dynasty lasted about fifteen years. Its standards lasted two
millennia.** This is the single strongest illustration in the notebook of the
gap between the lifespan of an institution and the lifespan of the protocol it
imposes.

### The modern pattern

| Standards contest | Winner | Why |
|---|---|---|
| **Railway gauge** | Stephenson's 4ft 8½in over Brunel's superior 7ft broad gauge | Installed mileage. The Gauge Act 1846 ratified an accomplished fact. **The better engineering lost to the larger network** |
| **Container dimensions** | ISO 20ft/40ft with corner castings | McLean released the twist-lock patent royalty-free. **Giving away the interface to own the business** |
| **Networking** | **TCP/IP over OSI** | The IETF's "rough consensus and running code" beat the ITU/ISO committee stack. Implementations existed and were free; OSI had superior documents |
| **AC vs DC** | Westinghouse/Tesla AC | Transmission distance. Physics, for once, decided |
| **Mains voltage/frequency** | Permanently split: 110–120V/60Hz vs 220–240V/50Hz | Pure path dependence. Nobody will ever change it. **This is a far better lock-in example than QWERTY** |
| **Mobile** | GSM in most of the world | EU coordination and mandated spectrum. **A regulatory standard beat a market contest** |
| Video | VHS over Betamax | See the-control-group.md — and note the "worse technology won" reading is wrong |

**The strategic lesson, stated cynically because that is how it is used:**
control the interface, give away the specification, own a complement. Every
platform strategy since 1990 is a variation on this.

---

## Network effects and winner-take-most

**The mechanism:** the value of joining a network increases with the number of
existing members, so early leads compound and the market tips.

**Metcalfe's law — value ∝ n² — is almost certainly wrong.** Briscoe, Odlyzko &
Tilly (2006) argue **n log n** is more defensible, on the grounds that
connections are not of equal value and follow something like a Zipf
distribution. **The n² figure was used to justify dot-com valuations and is
still repeated. Do not use it.**

Distinguish carefully:

| Type | Mechanism | Tips the market? |
|---|---|---|
| **Direct network effects** | Users value other users (telephone, messaging) | Strongly |
| **Indirect / two-sided** | Users value complements which follow users (consoles and games; Rochet & Tirole's platform work) | Strongly |
| **Data feedback** | More users → better product → more users | **Weaker than claimed.** Returns to data diminish, often quickly |
| **Economies of scale** | Fixed costs spread | Concentrates but doesn't tip |
| **Switching costs / lock-in** | Sunk investment in learning, data, integration | Preserves position rather than creating it |

**The important qualification, which cuts against the fatalism:** network
effects are frequently **local rather than global**. Facebook won globally;
messaging apps did not (WhatsApp, WeChat, LINE, KakaoTalk, iMessage and
Telegram all dominate different countries). Ride-hailing and food delivery
turned out to have thin, city-level network effects and correspondingly brutal
economics. **"Network effects therefore natural monopoly" is a claim requiring
evidence about the *scope* of the effect, and it is often asserted by people
raising money.**

---

## Patents — genuinely unresolved

**This section deliberately does not reach a conclusion, because the evidence
does not support one.**

### The case that patents promote innovation

- Disclosure: the bargain is publication in exchange for a temporary monopoly.
  Without it, trade secrecy, and knowledge does not accumulate.
- Pharmaceutical development involves very high fixed costs and near-zero
  imitation costs. Without exclusivity, the investment case collapses. **This
  is the strongest single argument and it is close to decisive in that one
  industry.**
- **B. Zorina Khan's** work argues the cheap, examination-based US patent
  system was genuinely *democratising* — it let people without capital or
  social standing hold and license property in ideas, in contrast to European
  systems with high fees and privilege-based grants.
- Patents enable specialised invention: you can invent without manufacturing.

### The case that patents retard innovation

- **Petra Moser's** research using 19th-century World's Fair exhibition
  catalogues found most innovations were **not patented**, and that countries
  *without* patent laws — the **Netherlands abolished patents 1869–1912;
  Switzerland had none until 1888** — innovated at comparable rates, though
  they **specialised differently**, concentrating in areas where secrecy
  worked. That last finding is the subtle and important one: **patents change
  the direction of innovation more reliably than the amount.**
- **Boldrin & Levine, *Against Intellectual Monopoly* (2008)**, argue the Watt
  patent (1769, extended by Act of Parliament to 1800) **suppressed** steam
  development for thirty years, with a burst of improvement after expiry.
  **Contested — Selgin & Turner (2011) pushed back hard on the specifics and
  the counterfactual.** Do not cite the Watt claim as settled.
- **Patent thickets and anticommons.** Heller & Eisenberg (1998): too many
  overlapping rights block use. The sewing machine wars ended in the **1856
  Sewing Machine Combination**, the first patent pool. The **1917 aircraft
  patent pool** had to be forced by the US government because the Wright-Curtiss
  litigation had stalled American aviation to the point of a national security
  problem.
- Patent trolls, defensive portfolios and litigation arms races consume real
  resources and produce nothing.

### The finding that is actually solid

**Appropriability mechanisms vary enormously by industry, and patents are the
primary mechanism in very few of them.** The **Levin et al. (1987) Yale survey**
and the **Cohen, Nelson & Walsh (2000) Carnegie Mellon survey** both found that
across most manufacturing industries firms rely on **lead time, complementary
manufacturing and sales capability, and secrecy** — with patents ranked
important mainly in pharmaceuticals and chemicals. **Tier 1.**

**Therefore: "do patents work" is a malformed question.** The answerable version
is "in which industries, at which term lengths, with which examination
standards" — and the answer is different for each.

---

## Infrastructure as durable political choice

**Infrastructure is politics with a 50-to-200-year commitment period, decided
by people who will not be alive to be held accountable.**

| Case | The durable choice |
|---|---|
| **US interstate highways** (1956) | Routed through and often destroying Black urban neighbourhoods; subsidised suburbanisation; locked in car dependence for a century. Combined with redlining (HOLC maps from the 1930s), the spatial structure of American inequality was largely set in about thirty years and is essentially unrepealable |
| **Haussmann's Paris** (1853–1870) | Wide boulevards, displacement of the poor from the centre. The "boulevards were built to stop barricades" claim is **commonly repeated and disputed by historians** as a primary motive — circulation, sanitation and property speculation were all major drivers. Note this is the same evidential problem as the Moses bridges |
| **Rail gauges** | Russia's 1520mm gauge is often attributed to invasion-proofing; the evidence is mixed. The *effect* on interoperability is real regardless of the motive |
| **Suburban zoning and minimum parking** | Not usually called technology, but it is the operating system of the built environment, and it determines what transport technologies can succeed |
| **Undersea cables** | Physical chokepoints; a small number of routes carry most intercontinental traffic. Strategic vulnerability disguised as plumbing |
| **The mechanical tomato harvester** (UC Davis) | Publicly funded, required a new bred-for-machines tomato, and preceded a collapse in the number of California tomato growers from thousands to hundreds. **Langdon Winner's better example, and much better documented than the Moses bridges** |

**The general point: infrastructure choices are made once, under conditions of
poor information, by a small number of actors, and then constrain everyone for
generations. They are the highest-leverage and least-scrutinised decisions any
society makes.**

---

## Surveillance as a technology of governance

### The rule: capability outlives intent

**Every dataset built by a government you trust will eventually be operated by
a government you did not choose.** This is not speculation. It is the best
attested regularity in the file.

**The Dutch population registers.** The Netherlands had unusually complete,
well-maintained civil registers, built for ordinary administrative purposes,
recording religious affiliation. Under occupation, they were used. **Jewish
death rates in the occupied Netherlands were among the highest in Western
Europe — commonly cited around 73–75%, against roughly 25% in France, where
records were more fragmented and civil registration less comprehensive.**
Seltzer & Anderson's work on population statistics and human rights documents
the general pattern.

**Caveat, because this is important and often overclaimed:** many factors
differed between the Netherlands and France — geography, the absence of an
unoccupied zone, the character of the local administration, the timing of
deportations. **The registry is a contributing cause, not a demonstrated
sufficient one.** Edwin Black's *IBM and the Holocaust* (2001) makes stronger
causal claims about Hollerith tabulation than most historians accept. **The
weaker claim is enough: the data was collected for benign purposes decades
earlier by people who could not have imagined its use.**

### The modern shape

| Capability | Note |
|---|---|
| **Telecoms metadata** | Snowden (2013). The legal architecture was built for one threat model and applied to another |
| **Facial recognition** | Deployed faster than any legal framework, in most jurisdictions with no enabling statute at all |
| **Payment rails** | Increasingly the most effective control point — deplatforming from payments is more consequential than deplatforming from speech, and far less regulated |
| **Commercial ad-tech** | **The dominant surveillance mode by volume is commercial, not state** — and states buy from it, which routes around warrant requirements |
| **China's "social credit"** | **Widely misdescribed in Western coverage.** There is no unified national citizen score. There are multiple fragmented systems — corporate compliance blacklists, court judgement-defaulter lists, some municipal pilots. Jeremy Daum's work is the standard corrective. **The reality is bad enough without the invented version, and using the invented version discredits the criticism** |

### The steelman for surveillance capability

**Give it, because the case is not zero.** Modern states genuinely require legibility to
function: taxation, epidemiology, welfare delivery, conscription, disaster
response and criminal investigation all depend on knowing who and where people
are. **James C. Scott's *Seeing Like a State* (1998)** describes legibility as a
prerequisite for both mass welfare and mass atrocity, using the same
apparatus. **You cannot have the National Health Service without a register of
people.** The question is never "surveillance yes/no" but which data, retained
how long, accessible to whom, under what review, and — the question almost
nobody asks — **how is it destroyed when the purpose ends?**

---

## Where the popular story is wrong

| Popular story | Correction |
|---|---|
| **"The inventor gets rich"** | Almost never. Value accrues to whatever became scarce afterward |
| **"The best technology wins"** | Broad gauge lost. OSI had better documents. See the-control-group.md |
| **"Network effects mean natural monopoly"** | Depends entirely on the *scope* of the effect. Messaging is fragmented by country; delivery apps have thin city-level effects |
| **"Metcalfe's law: value ∝ n²"** | Probably n log n. The n² claim helped inflate the dot-com bubble |
| **"Patents drive innovation"** | True in pharma and chemicals. Weak-to-negative elsewhere, where lead time and secrecy dominate. The honest answer is industry-specific |
| **"Patents are a scam"** | Also wrong. The pharma case is strong and the disclosure bargain is real |
| **"Data is the new oil"** | Returns to data diminish fast in most applications. The metaphor is used to justify accumulation, not to describe economics |
| **"China has a social credit score"** | Largely a Western misconception. Multiple fragmented systems, no unified score |
| **"If you have nothing to hide"** | The relevant risk is not what the current government does with the data. It is what the next one, or the occupying one, does. The Dutch registers were built by liberal democrats |

---

## Open questions

- [ ] Is there a systematic study of value capture by role — inventor, first
      mover, standard-setter, distributor, complement-owner — across many
      technologies? This seems tractable and I am not aware of one.
- [ ] What determines whether network effects are global or local? A predictive
      answer would be worth an enormous amount and I do not think one exists.
- [ ] Optimal patent term is presumably industry-specific and time-varying.
      Has anyone estimated it empirically per industry rather than by
      assumption?
- [ ] Is there any documented case of a state voluntarily destroying a
      surveillance capability after the justifying emergency ended?
- [ ] Do standards bodies produce systematically different outcomes than market
      standards contests — better interoperability, worse innovation, or
      neither? GSM vs the US mobile market is one natural comparison.
- [ ] How much of the durability of infrastructure choices is physical (sunk
      concrete) versus institutional (organisations that defend the choice)?
      The second is in principle reversible and the first is not.
