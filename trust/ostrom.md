# Ostrom

The empirical refutation of the tragedy of the commons, and the design principles that replaced it.

> **Status: TIER 1.** That long-enduring, self-governed common-pool resource institutions exist and share identifiable features is about as well established as anything in institutional social science. The design principles are TIER 1/2 — broadly supported by meta-analysis, with acknowledged formulation problems. The claim that they scale to global commons is TIER 3.

> Written from general knowledge on 2026-09-01 without live source verification.

---

## Why this deserves its own file

Elinor Ostrom won the Nobel Memorial Prize in Economic Sciences in 2009, shared with Oliver Williamson — the first woman to do so, and a political scientist rather than an economist. Her central work, *Governing the Commons* (1990), did something rare: it took a formal result that everyone believed, went and looked at the world, and found the result was empirically false as a general claim.

She remains under-known outside economics and environmental governance. Her findings are directly applicable to open-source projects, shared engineering infrastructure, team-owned codebases, condominium associations, professional standards bodies, fisheries, groundwater, and any resource where individual incentive and collective interest diverge.

---

## What Hardin actually claimed, and what was wrong with it

Garrett Hardin's "The Tragedy of the Commons" (*Science*, 1968) presented a pasture open to all. Each herder gains the full benefit of adding one more animal and bears only a fraction of the cost of overgrazing. Rational herders therefore add animals until the pasture is destroyed. "Freedom in a commons brings ruin to all." Hardin's conclusion: the only escapes are **privatisation** or **coercive state control** — "mutual coercion, mutually agreed upon".

The paper was enormously influential. It shaped forty years of environmental policy toward exactly two instruments: sell it, or nationalise it.

**The error is in the setup, and it is a definitional one.** Hardin's pasture has no boundary, no membership, no communication, no monitoring and no rules. That is not a **commons**; it is an **open-access resource**. A historical commons — English open fields, Swiss alpine pasture, Japanese village forest — was a *governed* institution with defined members, stinting rules limiting how many animals each household could put out, appointed officers, and sanctions. Hardin modelled the absence of the institution and concluded the institution could not work.

Hardin later partly conceded this, saying he should have written "the tragedy of the *unmanaged* commons". The correction never caught up with the original.

Two further points that ought to be stated plainly:

- **The English enclosure evidence does not support Hardin either.** Historians of the open-field system (Carl Dahlman among others) documented that the medieval commons was rule-bound and functional; enclosure was driven by distributional and political forces, not by ecological collapse.
- **Hardin's own politics were not incidental to the paper.** The 1968 article was substantially about population control, and he went on to write "Lifeboat Ethics" and to associate with restrictionist immigration organisations. This does not make the model wrong, and it should not be used as a substitute for arguing about the model. But readers who encounter the paper only as a neutral piece of ecology are missing its context.

**What Hardin's model does correctly describe:** genuinely open-access resources with no governance. High-seas fisheries beyond national jurisdiction. Atmospheric carbon. Antibiotic effectiveness. Groundwater in unregulated basins. Attention and bandwidth in unmoderated online spaces. In these cases the tragedy is real, observed and severe. The correct statement is: **open access without governance produces the tragedy; a commons is precisely the institution that prevents it.**

---

## The cases

Ostrom and her colleagues assembled and coded hundreds of case studies. The headline long-enduring systems:

| System | Resource | Duration | Notable feature |
|---|---|---|---|
| **Törbel, Valais, Switzerland** | Alpine summer pasture, forest, irrigation | Association records reaching back to the thirteenth century; written statutes from 1483 | Stinting rule: a household may send up to the number of cows it can feed through the winter — self-enforcing, cheap to verify |
| **Japanese village commons (*iriai*)** — Hirano, Nagaike, Yamanoka | Mountain forest and meadow for thatch, fodder, fuel | Several centuries, documented through the Tokugawa period | Rotating detectives patrolling in pairs; graduated fines; opening dates for harvest set collectively |
| **Spanish *huerta* irrigation** — Valencia, Murcia, Orihuela, Alicante | Irrigation water | Valencia's *Tribunal de las Aguas* claims roots over a thousand years and still sits weekly at the cathedral | Oral, public, same-day dispute resolution at essentially zero cost; judgments unwritten and unappealable |
| **Philippine *zanjera*** — Ilocos Norte | Irrigation | Nineteenth century onward | Members hold bundled shares that tie water rights to labour obligations — benefit and cost proportional by construction |
| **California groundwater basins** — Raymond, West, Central | Aquifers threatened by saltwater intrusion | Negotiated from the 1940s–60s | Ostrom's own doctoral work (1965) on the West Basin; users litigated and negotiated their way to a polycentric governance settlement rather than waiting for the state |

And critically, **the failures**, which Ostrom also studied and which give the comparison its force:

| Failed / fragile system | What went wrong |
|---|---|
| **Bodrum, Turkey (inshore fishery)** | No agreed boundaries, mixed user groups with incompatible technologies, no monitoring — depletion and conflict. Nearby **Alanya** solved essentially the same problem with a rotational allocation system the fishers designed themselves |
| **Gal Oya, Sri Lanka** | Large state-built irrigation scheme; head-enders had no reason to release water to tail-enders; partial recovery only after organisers rebuilt farmer organisations from the field channel upward |
| **Various Nepalese irrigation systems** | Farmer-built systems often outperformed engineer-built concrete systems, because the concrete removed the head-enders' need for tail-enders' labour and destroyed the bargain that sustained cooperation |

That last one is worth pausing on. **Improving the physical infrastructure destroyed the institution**, because the institution was held together by mutual dependence that the improvement removed. This is one of the most useful lessons in the entire folder.

---

## The eight design principles

Ostrom derived these inductively from the long-enduring cases. They are not a recipe; they are the features that robust systems tend to share.

| # | Principle | What it means | Example | Failure mode when absent |
|---|---|---|---|---|
| **1** | **Clearly defined boundaries** | Both the resource's physical limits and who counts as a member are known | Törbel membership by citizenship in the village | Anyone can enter; no reason to invest in restraint |
| **2** | **Congruence between rules and local conditions; and between benefits and costs** | Appropriation rules fit the actual ecology; those who benefit more contribute more | *Zanjera* share-plus-labour bundling | Rules that ignore local hydrology are ignored; free-riding on contribution |
| **3** | **Collective-choice arrangements** | Most people affected by the rules can participate in changing them | Village assemblies setting the opening date for harvest | Rules imposed from outside are not owned, not enforced, and are gamed |
| **4** | **Monitoring** | Monitors actively audit conditions and behaviour, and are **either the appropriators themselves or accountable to them** | Japanese rotating patrols; Swiss appointed officers | Monitoring by a distant principal is expensive, evadable and captured |
| **5** | **Graduated sanctions** | First offences draw trivial penalties; repeat or severe offences escalate | Small fines rising with repetition | Draconian first penalties are not enforced because enforcement is socially unbearable; no penalty means no deterrence |
| **6** | **Conflict-resolution mechanisms** | Rapid, local, cheap arenas for disputes | Valencia's Thursday water court | Disputes fester or go to a formal system too slow and costly to use |
| **7** | **Minimal recognition of the right to organise** | External government does not override locally-made rules | Swiss cantonal recognition | Central government voids local arrangements; nobody bothers to make them |
| **8** | **Nested enterprises (polycentricity)** | For larger systems, governance layered in tiers, each doing what it can do | Irrigation federations of federations | A single scale must handle problems at every scale, and fails at most of them |

**The best available check on these:** Cox, Arnold and Villamayor-Tomás (2010) reviewed 91 empirical studies and found the principles broadly supported. Their main criticism was that principles 1, 2 and 4 each bundle two distinct things and should be split — boundaries of *resource* vs boundaries of *users*; congruence with *local conditions* vs proportionality of *benefit and cost*; monitoring of *resource conditions* vs monitoring of *user behaviour*. That refinement is worth adopting.

---

## Polycentricity, and why it matters beyond commons

The Bloomington School — Elinor and Vincent Ostrom and colleagues — developed **polycentric governance**: many overlapping decision centres with partial autonomy, rather than one hierarchical authority. Their empirical entry point was unglamorous: a long series of studies of metropolitan police services from the 1970s, which found that small and medium departments often outperformed large consolidated ones on citizen-assessed outcomes, contradicting the prevailing consolidation orthodoxy.

The general claim is that **monocentric systems fail because a single centre cannot hold the local knowledge required**, and polycentric systems have redundancy, competition, experimentation and multiple error-correction channels. Compare [../leaders/](../leaders/) on error correction and [../civilisations/mechanisms.md](../civilisations/mechanisms.md) on brittleness through centralisation.

---

## Steelman: the case against Ostrom

Take these seriously.

- **Selection on the dependent variable.** She set out to study systems that had endured for centuries and then reported what they had in common. This method cannot tell you how many systems with all eight features collapsed anyway, nor how often a system lacking several features survived. Her later comparative work and the large coded databases partially address this; the original book does not.
- **Scale limits are real and possibly fatal for the biggest problems.** The cases are almost all small: hundreds to low thousands of users, with a bounded physical resource, dense repeated interaction and shared identity. Global carbon has none of these features — no boundaries, no exclusion, essentially no monitoring of individual actors, no graduated sanction that any body can impose on a sovereign state. Ostrom argued in her later work for **polycentric approaches to climate** — action at city, firm and regional level rather than waiting for a global treaty — and this is a reasonable argument, but it is a hope grounded in analogy, not a demonstrated result. **TIER 3.**
- **Distributional silence.** A long-enduring institution can be long-enduring and unjust. Many historical commons were governed by, and for, a restricted membership defined by lineage, gender or landholding. "Enduring" is not "good". Ostrom's framework is largely silent on who gets to be inside the boundary — which, given principle 1, is the whole political question.
- **The state is doing more work than it appears.** Critics note that most successful cases sit inside a functioning wider legal order that supplies principle 7 and a backstop for serious violence. Self-governance in the shadow of the state is a different phenomenon from self-governance without one.

---

## Where the popular story is wrong

- **"The tragedy of the commons is a proven fact about human nature."** It is a prediction from a model with no communication, no monitoring and no rules. Add any of the three and the prediction fails. Ostrom's contribution was empirical, not theoretical: she went and counted.
- **"The only options are privatise or nationalise."** This false binary was Hardin's policy conclusion and dominated environmental policy for decades. There is a third family — self-governed common property — with documented multi-century performance. Note also that privatisation and nationalisation both have *their own* failure records; see [the-control-group.md](the-control-group.md).
- **"Ostrom showed communities can always self-organise."** She showed no such thing and explicitly documented failures. Her claim is that self-organisation is **possible** and that its success depends on identifiable conditions — which mostly do not obtain by default.
- **"The design principles are a checklist you can install."** They are diagnostic, not constructive. Principle 3 in particular means the rules cannot be handed down; a set of rules externally imposed to satisfy the checklist violates the checklist. See [the-control-group.md](the-control-group.md) on isomorphic mimicry.
- **"Better infrastructure helps."** Sometimes it destroys the interdependence that held the institution together. The Nepalese irrigation finding should be the first thing anyone reads before funding a capital improvement to a shared system.

---

## Open questions

- [ ] What is the actual base rate? Of all common-pool resource systems that have existed, what fraction endured, and do the eight principles discriminate survivors from failures out of sample?
- [ ] Where exactly does scale break the mechanism? Is the binding constraint group size, heterogeneity, or the observability of individual appropriation?
- [ ] Can principle 4 (accountable monitoring) be substituted by technology — remote sensing, telemetry, on-chain records — or does the accountability of the *monitor* to the *users* do the essential work?
- [ ] Is polycentricity genuinely superior, or is the police-services evidence a period- and country-specific finding?
- [ ] Does the framework apply to non-rival shared goods — open-source maintenance, shared codebases, standards bodies — where the resource is not depleted by use but maintenance is undersupplied?
- [ ] How much do the successful cases depend on an outer state that guarantees principle 7 and monopolises violence?
- [ ] What happens to these institutions under rapid membership turnover, which is the normal condition in modern organisations?
