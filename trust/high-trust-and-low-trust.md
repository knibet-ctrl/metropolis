# High-Trust and Low-Trust Societies

Measured differences, what they correlate with, and which way the causal arrow points.

> **Status: TIER 2 — contested but tractable.** The correlations are robust and replicated. The causal direction is genuinely contested, and the strongest claim in this file (institutions first) is a reading of the balance of evidence, not a settled result. The measurement critique in [the-questions.md](the-questions.md) threatens the whole literature.

> Written from general knowledge on 2026-09-01 without live source verification. Percentages below are recalled approximations and should be checked before use.

---

## The raw pattern

The World Values Survey and European Social Survey ask a version of: *"Generally speaking, would you say that most people can be trusted, or that you need to be very careful in dealing with people?"* Approximate shares answering "most people can be trusted", from memory and rounded generously:

| Band | Countries | Rough range |
|---|---|---|
| Very high | Norway, Sweden, Denmark, Finland, Netherlands | 60–75% |
| High | Switzerland, New Zealand, Australia, China (see caveat), Canada | 45–60% |
| Middle | Germany, UK, Japan, Ireland, Spain, US (declining) | 30–45% |
| Low | Italy, Greece, Poland, France, Portugal, Russia, most of Latin America | 15–30% |
| Very low | Brazil, Colombia, Philippines, Turkey, much of sub-Saharan Africa | 5–15% |

**Treat this table as indicative only.** China's high scores are the standard illustration of the radius problem — if respondents read "most people" as "people like me", the number measures particularised, not generalised, trust. Delhey, Newton and Welzel argued exactly this, and adjusting for radius substantially reorders the table.

Within the US, the General Social Survey series shows a decline from roughly half in the early 1970s to around a third or below. The decomposition matters: this looks substantially like **cohort replacement** — successive birth cohorts entering with lower trust and older, higher-trust cohorts dying out — rather than individuals becoming less trusting over their lives.

---

## What it correlates with

| Correlate | Direction | Strength | Notes |
|---|---|---|---|
| GDP per capita | Positive | Strong | Bidirectional almost certainly |
| Growth rate | Positive | Moderate | Knack & Keefer (1997); Zak & Knack (2001). Sensitive to sample and controls |
| Corruption (CPI, control of corruption) | Negative | Strong | Among the tightest bivariate relationships in comparative politics |
| Rule of law / judicial impartiality | Positive | Strong | Rothstein and colleagues argue this is the *causal* channel |
| Income inequality | Negative | Moderate–strong | Rothstein & Uslaner; contested magnitude |
| Universalistic welfare provision | Positive | Moderate | Contested; means-tested systems associated with lower trust than universal ones |
| Ethnic/linguistic fractionalisation | Negative | Weak once income and institutions controlled | Highly politically charged; see [the-questions.md](the-questions.md) |
| Firm size / large private organisations | Positive | Weak–moderate | Fukuyama's specific claim |
| Protestant historical share | Positive | Moderate | Almost certainly proxying for something else |

The correlation set is not in dispute. Everything interesting is about what generates it.

---

## Fukuyama's thesis, at strength

Francis Fukuyama's *Trust: The Social Virtues and the Creation of Prosperity* (1995) argued that societies differ in **spontaneous sociability**: the propensity to form voluntary associations with non-kin. High-trust societies — he named Japan, Germany and the United States — could build large professionally-managed firms that were neither family businesses nor state enterprises. Low-trust, *familistic* societies — he named China, southern Italy, France and Korea, with different mechanisms in each — struggled to move beyond family firms or required the state to build large organisations directly.

The intellectual lineage runs back to Edward Banfield's *The Moral Basis of a Backward Society* (1958), based on fieldwork in a southern Italian village he called Montegrano. Banfield described **amoral familism**: "maximise the material short-run advantage of the nuclear family; assume all others will do likewise". And forward to Robert Putnam's *Making Democracy Work* (1993), which compared Italian regional governments created in 1970 and found northern regions performing far better, tracing the difference to civic traditions distinguishable as far back as the medieval communes versus the Norman kingdom in the south.

**The steelman of the culturalist position is stronger than its critics usually allow:**

- Algan and Cahuc (2010) used the **inherited trust of US immigrant descendants** as an instrument. If the trust levels that second- and third-generation descendants of, say, Swedish or Sicilian immigrants carry — measured in the US, under identical institutions — predict the growth of their ancestral countries, then something is travelling with people rather than with institutions. Their results supported a causal effect of inherited trust on growth. This is the best-identified evidence on the culturalist side and it is not easy to dismiss.
- Nunn and Wantchekon (2011) showed that within Africa, individuals whose ancestors were more heavily raided during the slave trade report lower trust today — including lower trust in relatives and neighbours. The shock is centuries old and its effect persists.
- Tabellini (2010) found that historical literacy and political institutions in European regions predict current cultural attitudes, which in turn predict current economic performance.

---

## The institutions-first case

Against this, a substantial body of work argues the arrow mostly runs the other way, and I read the balance as favouring it.

**The core argument (Rothstein, Stolle, Uslaner and colleagues):** generalised trust is a *rational inference* from experience of public institutions. If the police take bribes, if courts are purchasable, if the queue at the licensing office is decided by connections, then "you can't be too careful" is simply **true**, and reporting it is accurate perception rather than cultural defect. Their specific finding is that the institutions that predict generalised trust best are the **impartial implementing institutions** — courts, police, tax administration, street-level bureaucracy — rather than the *representative* institutions (parliaments, parties, elections). Democracy per se predicts trust weakly; impartial administration predicts it strongly.

Supporting evidence:

- **Becker, Boeckh, Hainz and Woessmann (2016)** compared localities in Eastern Europe on either side of the long-defunct Habsburg empire boundary. Areas once under Habsburg administration show higher trust in courts and police today, and less bribery. The institutional history sits in the same places, generations after the institution itself disappeared — the mechanism is transmitted, but its *origin* is institutional.
- **Fisman and Miguel (2007)**, diplomatic parking violations in New York. Diplomats had immunity, so unpaid tickets measure willingness to exploit impunity. Violation rates tracked home-country corruption indices — a cultural finding. But when the city gained the power to revoke diplomatic licence plates in 2002, **violations dropped sharply across the board**. Culture set the level; enforcement moved everyone. This is the single best illustration that both channels are real and that the enforcement channel is fast while the cultural channel is slow.
- **The Nordic case does not support a deep-culture story well.** Nineteenth-century Sweden was poor, emigration-driven, and by contemporary accounts had serious problems with alcohol, corruption and clientelism. The transformation into a high-trust society ran alongside — arguably behind — a specific sequence of bureaucratic reforms.
- **Nunn and Wantchekon's own result** is best read as institutional in origin: the slave trade was a violent extractive institution, and its persistent effect on trust is a legacy of that institution, not evidence of a primordial cultural trait.
- **The migrant evidence cuts both ways.** Descendants of immigrants converge substantially toward host-country trust levels over generations. Inherited trust has explanatory power *and* decays under new institutions.

**Honest statement of where this leaves us:** both channels exist. Institutional quality appears to be the faster-moving and more manipulable one, and appears to explain more of the cross-national variance. But this is a reading of a contested literature, and Algan–Cahuc is a serious result on the other side. Anyone who tells you the question is closed has not read both halves.

---

## Corruption as an equilibrium, not a moral failing

This is the most practically important idea in the file.

Model corruption as a coordination game. If nearly everyone pays bribes, then:

- An official who refuses bribes is poorer than colleagues, isolated, possibly in danger, and the system is unchanged.
- A citizen who refuses to pay simply does not get the permit.
- Reporting is useless because the reporting channel is also corrupt.

If nearly nobody pays bribes, the same actions are cheap and effective. **Both states are stable.** The system has multiple equilibria, and which one a society sits in is history, not virtue. Andvig and Moene formalised versions of this around 1990.

Persson, Rothstein and Teorell (2013) drew the operational conclusion in "Why Anticorruption Reforms Fail": the standard toolkit treats corruption as a **principal–agent problem** — install an honest principal, add monitoring and incentives, and agents will comply. But in systemically corrupt societies there is no honest principal; everyone including the would-be reformer is inside the equilibrium. It is a **collective action problem**. Monitoring more, training more and exhorting more does not move a coordination equilibrium.

What sometimes does:

| Case | Approach | Outcome |
|---|---|---|
| **Hong Kong ICAC (1974)** | Independent commission outside the police, with investigation, prevention and public-education arms; a partial amnesty for pre-1977 offences to prevent the police from mutinying outright — which they nearly did | Broadly successful; among the few genuine transitions |
| **Singapore CPIB under Lee Kuan Yew** | Simultaneous change: high civil-service pay, small elite service, prosecution reaching senior figures, simplified regulation reducing bribe opportunities | Successful. See [../leaders/](../leaders/) — the striking feature is that the approach was *structural*, not moralistic. Reduce the number of discretionary decision points; make the honest path affordable; make prosecution credible at the top |
| **Georgia, 2004** | Under Saakashvili, the entire traffic police — on the order of tens of thousands of officers — dismissed effectively at once and a new force recruited | Petty bribery collapsed measurably. **Caveat: the wider record is mixed**, with later concerns about prosecutorial abuse, prison conditions and democratic backsliding. A successful mechanism is not a successful government |
| **Most national anti-corruption commissions** | Copied institutional form, added to an unchanged system | Little to no effect. See [the-control-group.md](the-control-group.md) |

The pattern: **simultaneous, visible, credible change that flips expectations** beats incremental improvement, because the thing being changed is a shared expectation and expectations do not move incrementally. This is uncomfortable, because "big bang" reform requires concentrated power, which is dangerous for other reasons. That trade-off is real and unresolved.

---

## Where this becomes a values disagreement rather than a factual one

The evidence base here is used to argue for opposite programmes, and it is important to be precise about where the disagreement actually sits.

| Position | Uses the evidence to argue | Where it is factually strong | Where it is a value commitment |
|---|---|---|---|
| Market-liberal | Secure property rights and constrained executives produce prosperity; aid without institutional reform is wasted | Property rights and constraint on expropriation do predict investment | That the resulting distribution is acceptable; that markets are the natural default |
| Social-democratic | Universal, impartial, non-means-tested public administration produces trust; inequality corrodes it | Impartiality of administration does predict trust; the universalism finding is real if smaller | That reducing inequality is worth its efficiency costs |
| Post-colonial / structuralist | Persistent underdevelopment is a legacy of extractive colonial institutions | The persistence findings are real, and the slave-trade and mita results are well identified | How much responsibility follows from causation; what remedy is owed |
| Culturalist / conservative | Civic virtue, family structure and religion sustain cooperation | Norms clearly do transmit and matter | That these norms should be promoted as policy |

**None of these positions is refuted by the evidence.** They select different parts of a partly-consistent picture and then differ about values. The honest move is to say so rather than to claim your politics falls out of the regression.

---

## Where the popular story is wrong

- **"Some cultures are just low-trust."** Trust levels have changed dramatically within countries within a century — the Nordic transformation being the clearest case. Treating them as fixed traits is contradicted by the time series.
- **"Corruption is caused by bad people."** In a corrupt equilibrium, honest individuals behave corruptly and corrupt individuals in a clean equilibrium behave honestly. Fisman and Miguel's diplomats are the demonstration: same people, changed enforcement, changed behaviour within months.
- **"Trust causes prosperity."** The correlation is strong; the direction is contested; the honest position is that impartial institutions plausibly cause both. Anyone quoting Knack and Keefer as if it settled causality is misreading it.
- **"Putnam showed civic culture from the Middle Ages determines governance today."** The *Making Democracy Work* argument has been criticised heavily for its historical coding and for the possibility that medieval civic traditions and modern performance are both downstream of geography, wealth or state penetration. The finding is suggestive, not decisive — and see [institutions.md](institutions.md) on spatial autocorrelation, which threatens results of exactly this shape.
- **"More transparency reduces corruption."** Transparency without a functioning enforcement channel can increase cynicism, because it publicises corruption that nobody is punished for. Transparency is necessary and radically insufficient.
- **"High trust is unambiguously good."** High-trust societies are more efficient and more vulnerable to fraud, affinity scams and elite capture, because verification is skipped. Optimum trust matches actual trustworthiness; it is not maximised.

---

## Open questions

- [ ] How much of the cross-national trust gradient survives correction for the radius-of-trust interpretation problem?
- [ ] Can the Algan–Cahuc inherited-trust result and the Rothstein institutional-impartiality result be reconciled quantitatively rather than rhetorically?
- [ ] Why did the Nordic transformation happen? Specific sequence, not "culture".
- [ ] Is the universal-vs-means-tested welfare finding causal, or does it reflect prior social homogeneity?
- [ ] Does big-bang anti-corruption require authoritarian capacity, or is there a democratic version with a track record?
- [ ] What is the half-life of inherited trust among migrant populations, and does it differ by origin and destination?
- [ ] Is there a behavioural, non-survey national trustworthiness measure that can be run repeatedly and cheaply?
