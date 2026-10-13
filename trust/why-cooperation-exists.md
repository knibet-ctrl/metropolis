# Why Cooperation Exists

The evolutionary and game-theoretic foundations, and where the popular account of them is wrong.

> **Status: TIER 1 for the formal results — the mathematics of the prisoner's dilemma, the folk theorem and Hamilton's rule are settled. TIER 2 for which mechanisms actually explain human cooperation. TIER 3 for the grand syntheses (cultural group selection, big gods).**

> Written from general knowledge on 2026-09-01 without live source verification.

Cross-reference: [../existence/society.md](../existence/society.md) for scale and the social contract; [ostrom.md](ostrom.md) for the empirical institutions built on top of these mechanisms.

---

## The problem in one game

The prisoner's dilemma was formalised at RAND in 1950 by Merrill Flood and Melvin Dresher; Albert Tucker supplied the prisoner story that gave it the name. Payoffs where $T > R > P > S$ and $2R > T + S$:

|  | Cooperate | Defect |
|---|---|---|
| **Cooperate** | R, R | S, T |
| **Defect** | T, S | P, P |

Defection strictly dominates. Whatever the other player does, you do better by defecting. Both defect; both get $P$ when both could have had $R$. **This is not a puzzle about selfishness. It is a structural result: individually rational play produces a collectively worse outcome, and no amount of intelligence or good will inside the one-shot game fixes it.**

Every mechanism below is a way of changing the game so that the dilemma no longer has that structure.

---

## The mechanisms, ranked by how well established they are

| Mechanism | Core idea | Formal statement | Evidence in humans | Tier |
|---|---|---|---|---|
| **Kin selection** | Help copies of your genes | Hamilton (1964): $rb > c$ | Strong for nepotism gradients; cannot explain cooperation with strangers | TIER 1 |
| **Direct reciprocity** | I help you because you will help me | Trivers (1971); requires repeated interaction, $w > c/b$ | Strong; vampire bat blood-sharing (Wilkinson 1984) is the cleanest animal case | TIER 1 |
| **Indirect reciprocity / reputation** | I help you because *others* will then help me | Nowak & Sigmund (1998) image scoring; needs $q > c/b$ where $q$ is reputation reliability | Strong in humans; the distinctively human mechanism | TIER 1/2 |
| **Costly signalling** | Cooperation advertises unfakeable quality | Zahavi's handicap principle, formalised by Grafen (1990) | Plausible; hard to distinguish from reciprocity in field data | TIER 2 |
| **Altruistic / third-party punishment** | Defectors are punished at cost to the punisher | Fehr & Gächter (2002) | Real in lab; **much messier than usually presented** — see below | TIER 2 |
| **Network / spatial structure** | Cooperators clustering with cooperators | Nowak & May (1992) spatial games | Elegant; human field evidence thinner | TIER 2 |
| **Group selection (multi-level)** | Groups of cooperators outcompete groups of defectors | Price equation decomposition | Genetically contested; **culturally** more defensible | TIER 2/3 |
| **Institutions** | The game is deliberately restructured | Ostrom; mechanism design | Best-evidenced human answer at scale | TIER 1 |

---

## Axelrod, and the correction the popular version omits

Robert Axelrod ran two computer tournaments around 1979–1980 and wrote *The Evolution of Cooperation* (1984). Anatol Rapoport submitted TIT FOR TAT — cooperate first, then copy the opponent's last move. It had the highest aggregate score in both tournaments. Axelrod extracted four properties of successful strategies: **nice** (never defect first), **retaliatory** (punish defection), **forgiving** (return to cooperation immediately), and **clear** (legible enough that opponents can learn to cooperate with it).

That is where the popular account stops. It should not.

**Correction 1 — TFT never wins a pairwise contest.** It cannot. TFT can only ever match or trail its opponent's score in a head-to-head, because it never defects first. It won on *aggregate* score across a round-robin. This is a completely different property from dominance, and the two are routinely conflated.

**Correction 2 — the result is a property of the submitted pool, not of the game.** Axelrod's tournament outcome depends on which strategies people happened to send in. Change the mix — add more exploitative strategies, or fewer nice ones — and TFT's ranking moves. The tournament is an empirical finding about a specific ecology, not a theorem.

**Correction 3 — noise breaks it.** If moves are misimplemented or misperceived with any probability, two TFT players enter an **echo cycle**: one accidental defection propagates into alternating retaliation indefinitely. Under noise, TFT is not merely suboptimal but badly so. Better performers include **generous tit-for-tat** (forgive defections with some probability), **contrite TFT** (recognise your own error and don't punish the retaliation it caused), and **Pavlov / win-stay–lose-shift** (Nowak & Sigmund, 1993), which self-corrects and can exploit unconditional cooperators.

**Correction 4 — the rules of the tournament are decisive.** In the 2004 twentieth-anniversary tournament, a team from Southampton entered a large bloc of colluding programs that recognised each other through an opening handshake, then had "slave" entries throw games to a designated "master". They took the top position. The lesson is not that collusion beats reciprocity; it is that **the result of any such tournament is an artefact of its entry rules**, which is exactly the point about Axelrod's original.

**Correction 5 — extortionate strategies exist.** Press and Dyson (2012) identified "zero-determinant" strategies that can unilaterally set a linear relationship between the two players' scores, allowing extortion of any opponent that adapts by learning. Subsequent work (Adami and Hintze; Stewart and Plotkin) showed extortionate ZD strategies are not evolutionarily stable in populations — they invade, then get displaced, and generous ZD strategies are the robust ones. The net effect on the popular story: reciprocity's robustness is real but is a *population-level, long-run* property, not a guarantee in any given encounter.

**What survives all of this:** the four properties (nice, retaliatory, forgiving, clear) remain a good practical heuristic, with the amendment that **forgiveness should be more generous than strict tit-for-tat whenever the environment is noisy** — that is, essentially always outside a computer.

---

## The folk theorem, and why it explains less than it seems to

In an infinitely repeated game (or one with sufficiently high continuation probability), if players are patient enough, **any** feasible payoff profile that gives each player at least their minmax value can be sustained as an equilibrium. Cooperation is an equilibrium. So is mutual defection. So is an asymmetric arrangement where one player is exploited forever but slightly less than minmax.

This is usually reported as "repetition solves the prisoner's dilemma". It does not. **It is an indeterminacy result.** It says cooperation is *possible*, not that it is predicted. The folk theorem tells you the set of things that can be stable is enormous; it gives you no help selecting among them. Everything interesting — which equilibrium a society lands in, how it got there, how it moves — lies in the selection problem that the folk theorem leaves entirely open. Institutions, norms and focal points are the answer to the selection problem, not the folk theorem.

Two practical corollaries that *do* follow:

- **The shadow of the future is the key parameter.** Anything that raises the probability of future interaction — long tenure, stable membership, visible succession, repeated tendering — moves the game toward the cooperative region. Anything that shortens it — a final period, a known exit date, an executive on a two-year horizon — moves it away. Backward induction from a known last period unravels cooperation entirely. This is why terminal-period behaviour is reliably worse, and why "his last year in office" is a real risk category.

---

## Punishment: the mechanism that is messier than advertised

Fehr and Gächter (2002) showed that in public goods games, contributions collapse over rounds *without* punishment and are sustained *with* costly punishment, even though punishing is individually irrational. This became one of the most cited results in behavioural economics. Three important qualifications:

1. **Antisocial punishment.** Herrmann, Thöni and Gächter (2008, *Science*) ran the same design in sixteen societies. In several — notably in parts of the Middle East, southern and eastern Europe, and Greece — subjects punished *high* contributors, not just free-riders. Where antisocial punishment was common, punishment failed to raise cooperation at all. The mechanism is **not universal**; it depends on prevailing norms of civic cooperation and rule of law.
2. **Net welfare.** Dreber, Rand, Fudenberg and Nowak (2008), "Winners don't punish", found that in a repeated game with costly punishment available, the highest-scoring individuals used punishment least. Punishment sustains cooperation while destroying much of the surplus it protects.
3. **Escalation.** Peer punishment invites counter-punishment. Centralised, institutionalised sanctioning generally outperforms decentralised peer punishment once groups can choose — which is a direct argument for why the third-party sanctioning institution (a court, a state, an Ostromian graduated-sanctions system with accountable monitors) is not just a scale convenience but a welfare improvement.

---

## The human specifics

**Cross-cultural variation is large and structured.** Henrich and collaborators ran ultimatum, dictator and public goods games across fifteen small-scale societies (published around 2001 and expanded around 2005). Offers ranged from near-zero to above 50% of the pie, with hyper-fair offers and rejection of overly generous offers among the Au and Gnau of Papua New Guinea. Two variables predicted fairness offers: **market integration** and **participation in a world religion**. The Machiguenga made low offers that were rarely rejected; the Lamalera whale hunters, who require large-scale coordination, made high offers.

This matters because the standard behavioural results were mostly generated on WEIRD subjects — Western, Educated, Industrialised, Rich, Democratic — as Henrich, Heine and Norenzayan argued in 2010. WEIRD samples are unrepresentative outliers on several of these measures, and undergraduates specifically are outliers within them.

**The "big gods" story is contested.** Norenzayan and others argued that moralising, punitive, omniscient gods expanded the effective scale of cooperation by supplying a supernatural monitor where reputation could not reach. Whitehouse and colleagues published a 2019 *Nature* paper using the Seshat historical databank arguing that moralising gods *followed* rather than preceded social complexity — which would invert the causal story. That paper was subsequently retracted after a dispute about the coding of missing data. **The state of this question is genuinely unresolved and anyone telling you otherwise is selling something.** Treat as TIER 3.

**Cultural group selection** (Boyd, Richerson, Henrich) is the most defensible version of group selection: groups with better norms outcompete or are imitated by groups with worse norms, and cultural variation between groups can be maintained by conformist transmission in a way genetic variation cannot. Genetic group selection remains bitterly contested — Nowak, Tarnita and Wilson's 2010 attack on inclusive fitness theory drew a rebuttal signed by well over a hundred biologists.

---

## Steelman: the case that this whole framework is over-applied

The strongest opposing position is not that game theory is wrong but that it is **radically under-determining and post hoc**. Given any observed behaviour, a game can be constructed in which it is the equilibrium. The folk theorem makes this formal. Critics — including some within economics — argue that:

- Payoff matrices in real settings are unobserved and are inferred from the behaviour they are meant to explain. This is circular.
- Laboratory games measure behaviour in a highly artificial frame; subjects import norms from outside the lab that the experimenter cannot see, so "cooperation in a public goods game" may measure willingness to play along with an experimenter.
- Anthropologists (Graeber among others) argue the exchange-and-reciprocity frame misdescribes most human sociality, which runs on obligation, kinship and "everyday communism" rather than calculated reciprocation.

**This is a serious objection and it lands.** The defence is that the framework earns its keep by making *comparative* predictions — cooperation should fall in the last period, rise with observability, rise with the probability of future interaction, fall with anonymity — and those comparative predictions hold up unusually well. Use game theory to predict how behaviour changes when structure changes, not to explain why any particular behaviour occurred.

---

## Where the popular story is wrong

- **"Tit-for-tat is the winning strategy."** It never wins a head-to-head match, its tournament victory is pool-dependent, and it fails under noise. The robust family is *generous* reciprocity.
- **"Repeated interaction solves cooperation."** The folk theorem says repeated interaction makes cooperation *possible alongside everything else*. Repetition creates the possibility; institutions do the selection.
- **"Humans are naturally cooperative" / "humans are naturally selfish."** Both are malformed. The reliable finding is that humans are **conditional cooperators**: most contribute if they expect others to, and withdraw when they observe free-riding. This makes cooperation bistable — expectations are self-fulfilling in both directions.
- **"Punishing free-riders makes groups better off."** Often it does not: the punishment costs can exceed the cooperation gains, and in some societies punishment is aimed at cooperators.
- **"Evolution explains altruism to strangers via group selection."** The mechanism that most cleanly explains large-scale cooperation with strangers is reputation plus institutions, not genetic group selection.
- **"The tragedy of the commons is a game-theoretic fact."** It is a prediction from a specific model that assumes no communication, no monitoring and no rule-making. Relax any of those and the prediction changes. See [ostrom.md](ostrom.md).

---

## Open questions

- [ ] What actually selects among the many equilibria the folk theorem permits? Is there a general theory of equilibrium selection or only case-by-case history?
- [ ] How much of laboratory cooperation is experimenter demand and imported norms rather than the modelled mechanism?
- [ ] Is antisocial punishment a stable cultural trait, a response to weak rule of law, or an artefact of subject-pool differences?
- [ ] Did moralising religions precede or follow large-scale cooperation? The Seshat dispute leaves this open.
- [ ] Does cultural group selection make any risky prediction that distinguishes it from within-group mechanisms plus diffusion?
- [ ] How much human cooperation is best modelled as reciprocity at all, versus obligation, identity or sheer habit?
- [ ] Can generous reciprocity be operationalised as a stated policy — "we forgive the first apparent defection" — without being exploited once announced?
