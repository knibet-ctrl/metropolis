# Institutions

What they are, what they do, and why they resist transplantation.

> **Status: TIER 2 — contested but tractable.** That institutions matter for economic outcomes is close to consensus. *Which* institutions, *how much*, and *identified how* are all live disputes, and the methodological objections to the persistence literature are more serious than most summaries admit.

> Written from general knowledge on 2026-09-01 without live source verification.

---

## Definition

Douglass North (*Institutions, Institutional Change and Economic Performance*, 1990; Nobel 1993 with Robert Fogel):

> Institutions are the rules of the game in a society, or more formally, the humanly devised constraints that shape human interaction.

Two distinctions from North that do a lot of work:

**Institutions are not organisations.** Institutions are the rules; organisations are the players. A parliament is an organisation; parliamentary sovereignty is an institution. A firm is an organisation; limited liability is an institution. Conflating them is the source of a great deal of confused reform: you cannot fix the rules by replacing the players, which is what most reform programmes actually attempt.

**Formal and informal constraints are both institutions.** Written law, and also norms, conventions and self-imposed codes of conduct. North's later view was that **informal constraints dominate and change slowly**, which is precisely why importing a formal rulebook rarely produces the behaviour the rulebook was written to produce.

North's functional claim: institutions matter because they determine **transaction costs** — the cost of measuring what is being exchanged and enforcing agreements. Where measurement and enforcement are cheap, complex impersonal exchange is possible and specialisation can be deep. Where they are expensive, exchange stays personal, local and shallow. See [rules-and-enforcement.md](rules-and-enforcement.md).

**Underrated companion work:** North, Wallis and Weingast, *Violence and Social Orders* (2009). Their frame: most societies through history have been **limited access orders** — elites create rents by restricting access to organisations and trade, and those rents are what stop the elites fighting each other. Violence is contained by *making peace profitable for the armed*. **Open access orders** — impersonal, entry-permitting, with impersonal control of the military — are recent and rare. The critical implication for reform: in a limited access order, "open up competition" is not an improvement to be adopted but a threat to the settlement that prevents civil war. This explains a great deal of otherwise baffling elite resistance to obviously beneficial reforms.

---

## Extractive and inclusive institutions, at strength

Daron Acemoglu, Simon Johnson and James Robinson. Nobel 2024. The argument, presented properly:

**Inclusive economic institutions** secure property rights, enforce contracts impartially, permit entry and competition, and provide public goods including education. They generate investment, technology adoption and growth. **Extractive institutions** are structured to transfer resources from the many to a narrow elite; they suppress entry because entry threatens incumbent rents, and they under-invest in human capital because an educated population is a political risk.

Economic institutions are sustained by **political institutions**. Inclusive political institutions are pluralistic (power broadly distributed) *and* centralised (the state can actually enforce). Both are required: pluralism without centralisation is Somalia; centralisation without pluralism is an extractive autocracy. The mechanism that blocks growth under extraction is fear of **creative destruction** — new technology reallocates economic power, which threatens political power, so incumbents block it.

**The empirical backbone:**

| Paper | Design | Result |
|---|---|---|
| AJR (2001), *AER*, "The Colonial Origins of Comparative Development" | Instrument current institutional quality with **European settler mortality** in the colonial period. Where Europeans died (malaria, yellow fever) they built extractive states; where they survived they built settler colonies with European-style institutions | Large causal effect of institutions on income; effect survives controlling for geography |
| AJR (2002), *QJE*, "Reversal of Fortune" | Compare pre-colonial prosperity (proxied by urbanisation and population density around 1500) to today, within the set of colonised countries | Reversal: places rich in 1500 are poor now. Kills the simple "geography determines prosperity" story, since geography did not reverse |
| Dell (2010) | Regression discontinuity at the boundary of the Peruvian/Bolivian **mita** forced-labour zone | Households just inside the historic mita boundary are measurably poorer today, with less road infrastructure and more subsistence farming |

The reversal-of-fortune design is genuinely clever and is the strongest part of the case, because it is difficult for a geography story to explain a reversal.

---

## The serious critiques

These are not quibbles. Present them at full strength.

**1. The settler mortality instrument is fragile.** David Albouy (published version around 2012, *AER*) reconstructed the mortality data and found: mortality figures were available from the country itself for fewer than half the sample, with the rest imputed from other countries in the region; the rates mixed **campaign mortality** (soldiers on military expeditions, catastrophically high) with **barracks mortality** (garrison troops in peacetime); and results were not robust to reasonable alternative codings or to clustering by the source of the imputation. AJR responded and defended the data. **My read: the point estimate should be treated as much less precisely identified than the original paper implies, without concluding the underlying claim is false.**

**2. The exclusion restriction is doubtful.** For the instrument to work, settler mortality must affect income today *only* through institutions. But settler mortality is essentially a measure of the historical **disease environment**, and disease burden plausibly affects productivity, human capital accumulation and fertility decisions directly today. Sachs and others pressed this hard. It is a hard objection to answer.

**3. Human capital, not institutions.** Glaeser, La Porta, López-de-Silanes and Shleifer (2004), "Do Institutions Cause Growth?", argued that what Europeans brought was **human capital and know-how**, not rules; that the standard institutional measures (expropriation risk, constraint on the executive) are **outcomes** rather than durable constraints — they change year to year and are coded partly from observed performance; and that historically, growth often preceded institutional improvement rather than following it. The counter is that human capital and institutions co-evolve and are not separable, which is true but weakens the original strong claim.

**4. Spatial autocorrelation, and this is the big one.** Morgan Kelly's work on "the standard errors of persistence" (roughly 2019–2020) argues that a large share of published historical-persistence results — "event in year X predicts outcome in year Y, hundreds of years later" — do not survive proper treatment of spatial correlation. Both the historical variable and the modern outcome are spatially smooth, so conventional standard errors are badly wrong. Kelly showed that **simulated spatially-correlated noise** reproduces correlations of similar magnitude to celebrated published results. This is a general threat to the persistence genre, including Putnam's medieval-communes argument, several colonial-legacy papers, and the Voigtländer–Voth result linking 1349 pogroms to 1920s Nazi voting. Some results survive; many were never tested against this. **Anyone reading this literature should ask, first, whether the spatial correlation was handled.**

**5. The East Asian problem.** South Korea, Taiwan, Singapore and post-1978 China grew at historically unprecedented rates under political institutions that were not remotely inclusive. AJR's answer is that this is "growth under extractive institutions", which is possible when the elite wants growth, but is not sustainable because it cannot support creative destruction indefinitely. This may be correct. It is also **unfalsifiable on any relevant timescale** — every year of continued Chinese growth is absorbed as "not yet". Flag it as such.

**6. Ha-Joon Chang's historical objection.** *Kicking Away the Ladder* (2002): the currently-rich countries did not develop under the institutions they now prescribe. Britain and the US used tariffs, patent infringement, state direction and restricted franchises during their industrialisation. Demanding that today's poor countries adopt mature-economy institutional forms before they industrialise inverts the historical sequence. **This is a strong argument about sequencing that the inclusive-institutions literature has not fully answered.**

---

## Path dependence

The claim: small early events can lock in an arrangement that persists even after better alternatives exist, because of increasing returns, network effects and switching costs. Paul David's QWERTY paper (1985) and Brian Arthur's work on increasing returns are the canonical statements.

**Caveat that is usually omitted: the QWERTY story is probably wrong.** Liebowitz and Margolis (1990) traced the evidence for Dvorak's superiority largely to studies conducted by Dvorak himself or under his supervision, and found the independent evidence weak. The most famous example of path dependence is a poor example of it. Path dependence in general is real — network effects and switching costs exist — but the canonical illustration should be retired.

Institutional path dependence is better argued from cases where the mechanism is visible: legal precedent systems, land tenure arrangements that survive the regimes that created them, colonial administrative boundaries that continue to structure ethnic politics, and the Habsburg-boundary result in [high-trust-and-low-trust.md](high-trust-and-low-trust.md).

---

## Why transplantation fails

The single most reproducible finding in institutional practice: **you can copy the form and not get the function.**

| Failure pattern | Mechanism | Example |
|---|---|---|
| **Isomorphic mimicry** | Adopting the visible form of a successful institution to gain legitimacy and funding, without the underlying capability | Anti-corruption commissions in over a hundred countries; almost no success outside Hong Kong and Singapore |
| **Premature load bearing** | Assigning a new institution responsibilities beyond its actual capability, causing visible failure that destroys its legitimacy | New civil services asked to run national programmes in their first year |
| **Transplant effect** | *How* law is received matters more than *which* law. Berkowitz, Pistor and Richard (2003) found countries that adapted transplanted law to local conditions, or already had familiarity with it, developed effective legal orders; countries handed an unadapted foreign code did not | Legal-origins comparisons |
| **Institutional monocropping** | Peter Evans's term: applying one idealised blueprint everywhere regardless of context | Structural adjustment; see [the-control-group.md](the-control-group.md) |
| **Missing complementary institutions** | An institution depends on others that were not copied | Privatisation without competition law, bankruptcy courts or securities regulation → asset stripping |
| **Ignoring the violence settlement** | Reform destroys the rents that were containing violence | De-Ba'athification; see [the-control-group.md](the-control-group.md) |

The constructive response, associated with Matt Andrews, Lant Pritchett and Michael Woolcock (*Building State Capability*, 2017), is **Problem Driven Iterative Adaptation**: start from a locally-felt problem rather than an imported solution; work in short experimental loops with real feedback; and build authorising environments broad enough to survive failure. It is less a technique than an admission that the transplant model does not work. Evidence for PDIA itself is still thin — it is a promising response, not a proven one.

---

## Steelman: institutions are overrated

The strongest opposing position:

- **Institutional measures are outcomes.** Most cross-country institutional indices are perception-based (expert surveys, risk ratings) and are known to be influenced by recent economic performance. Regressing income on them partly regresses income on itself.
- **Geography has not gone away.** Malaria burden, distance from markets, agricultural productivity and coastline access explain a great deal, and the reversal-of-fortune design does not rule out geography interacting with technology (temperate zones being better suited to the specific technologies of industrialisation).
- **The unit of analysis is wrong.** "Country institutions" is a very coarse object. Within-country variation in effective institutions is often larger than between-country variation.
- **Reverse causality is pervasive.** Rich countries can afford good courts, professional bureaucracies and low-corruption administration. The causal claim is not identified by the correlation, and the instruments used to identify it are the ones under attack.

**This is a real position held by serious economists.** The honest summary is: institutions almost certainly matter a lot; the specific magnitude estimates in the famous papers should be treated as uncertain by a factor that is embarrassing to state.

---

## Where the popular story is wrong

- **"Institutions are laws."** They are constraints, of which written law is a minority by volume. North's informal constraints do most of the work and change on a generational timescale.
- **"Why Nations Fail proved that institutions cause development."** It made a strong case with real identification problems. The 2001 instrument is contested, the exclusion restriction is doubtful, and the persistence genre has an unresolved statistical problem. The book is worth reading and should not be read as settled.
- **"QWERTY shows we get locked into inferior standards."** The specific example does not survive scrutiny. Use network effects in payment systems or operating systems instead.
- **"Reform means passing better laws."** Passing laws is the cheapest and least effective part. The binding constraints are enforcement capability, incentive compatibility for those who must implement, and the violence settlement the old arrangement was maintaining.
- **"Extractive institutions are a colonial phenomenon."** Limited access orders are the historical norm everywhere, including in Europe. Colonialism intensified and exported specific extractive forms; it did not invent extraction.
- **"Best practice can be adopted."** "Best practice" imported without the enforcement and incentive substrate reliably yields form without function, and often does harm by consuming the reform budget and burning the legitimacy of the next attempt.

---

## Open questions

- [ ] How much of the persistence literature survives Kelly's spatial-correlation critique? Which specific results have been re-tested?
- [ ] Is there an institutional measure that is a genuine constraint rather than a perception of recent outcomes?
- [ ] Can the East Asian growth record be reconciled with the inclusive-institutions thesis in a way that makes a falsifiable prediction with a date attached?
- [ ] What is the right sequencing — capability before load, or load forcing capability? The evidence pulls both ways.
- [ ] Does PDIA work? Are there controlled evaluations rather than case narratives?
- [ ] How do limited access orders transition to open access without civil war? North, Wallis and Weingast identify "doorstep conditions" but the transition mechanism is underspecified.
- [ ] Is within-country institutional variation a better research design than cross-country comparison, and what would a serious programme on it look like?
