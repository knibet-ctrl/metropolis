# Decisions — Deciding Without Knowing

> **Status: TIER 1** on the mathematics (expected utility, Kelly, ruin).
> **TIER 2** on the practical heuristics (premortems, decision journals,
> reversibility framing) — sensible, weakly evidenced, low cost.

> **The organising claim: decision quality and outcome quality are different
> things, and confusing them destroys learning.** In any noisy domain, good
> decisions lose regularly. Annie Duke calls the confusion *resulting*. It is
> the most expensive habit in this notebook.

---

## Expected value, and where it stops working

$$EV = \sum_i p_i \times v_i$$

**Where EV is the correct objective:**
- Outcomes are additive, not multiplicative
- The bet is repeatable many times
- No single outcome can remove you from the game
- Stakes are small relative to your total position

**Where EV is the wrong objective:**
- Multiplicative processes (wealth, compounding, business survival)
- One-shot decisions
- **Any possibility of ruin** — see fat-tails.md
- Fat-tailed payoffs where the mean does not converge

### The St Petersburg paradox — the original counterexample

Nicolaus Bernoulli, 1713; solved by Daniel Bernoulli, 1738.

A fair coin is flipped until it comes up heads. If it takes $n$ flips, you win
$2^n$ ducats.

$$EV = \tfrac{1}{2}(2) + \tfrac{1}{4}(4) + \tfrac{1}{8}(8) + \cdots = 1 + 1 + 1 + \cdots = \infty$$

**Infinite expected value. Nobody will pay more than about $20 to play.**

Two answers, and it matters which you take:

| Answer | Claim |
|---|---|
| **Bernoulli (1738)** | Utility of money is logarithmic. $E[\log(\text{wealth})]$ converges. Risk aversion is a property of preferences |
| **Ergodicity (Peters)** | The process is multiplicative and non-ergodic. The time-average growth rate is finite. Risk aversion is a property of *time*, not preferences |

**They give the same number in this case. They are not the same claim.** The
first fits a curve to behaviour; the second derives a result from the structure
of the process. See fat-tails.md.

**Practical translation: when the process compounds, optimise the geometric
mean, not the arithmetic mean.**

---

## Reversible vs irreversible — the highest-leverage frame

**Jeff Bezos**, Amazon shareholder letter, **1997** (introduced), restated in
**2015** as one-way and two-way doors. Cross-reference `leaders/playbook.md`.

| | **Type 2 — two-way door** | **Type 1 — one-way door** |
|---|---|---|
| Reversible? | Yes, cheaply | No, or at prohibitive cost |
| Right process | **Fast, decentralised, by individuals or small teams** | **Slow, deliberate, consultative, senior** |
| Right information threshold | ~**70%** of the information you wish you had | Much higher |
| Cost of error | Low — you walk back through | High — permanent |
| Dominant failure mode | Over-deliberating. **This is what large organisations do** | Under-deliberating. **This is what startups and individuals do** |

**Bezos's specific claim: as organisations scale, they apply the Type 1 process
to Type 2 decisions by default, producing slowness, risk aversion and
diminished invention.** That is a claim about organisational drift and it is
plausible rather than established — but the *asymmetry* itself is
mathematically well-founded.

### Why the asymmetry is real and not just a slogan

For a reversible decision, your loss is bounded by the cost of reversal. For an
irreversible one it is unbounded. **Under any fat-tailed uncertainty about
outcomes, the expected cost of an irreversible mistake dominates the expected
cost of a reversible one by an amount that does not depend on your probability
estimates being right.** That robustness is what makes it usable — you don't
need good probabilities to apply it.

### The 2×2 that generalises it

| | **Knowable (good base rate exists)** | **Unknowable (no reference class)** |
|---|---|---|
| **Reversible** | **Just decide fast and measure.** Optimise for cycle time. A/B test | **Experiment cheaply.** Small bets, real feedback, kill fast |
| **Irreversible** | **Do the analysis properly.** Reference class forecast, premortem, external review | **Buy optionality or don't act.** Delay, stage it, buy information, or accept a robust suboptimal choice |

**The bottom-right cell is where careers and companies end. The correct move
there is usually to convert the decision into a different cell** — stage it,
buy an option, add a reversal mechanism, or make it smaller.

---

## Optionality

An **option** is the right without the obligation. Its value comes from
**asymmetry**: bounded downside, unbounded upside. Under uncertainty, the value
of an option **increases** with volatility, which is why uncertainty is not
uniformly bad.

| Real-world form | Bounded downside | Unbounded upside |
|---|---|---|
| Prototype before committing | Cost of the prototype | Discovering a product |
| Hiring on contract first | Contract length | A great long-term hire |
| Staged investment tranches | The tranche | The whole outcome |
| Learning a skill | Time | Compounding, unforeseeable use |
| Publishing work publicly | Embarrassment | Opportunities you couldn't have named |

**Taleb's barbell:** put ~85–90% in maximally safe assets and ~10–15% in
maximally aggressive, convex bets. **Avoid the middle** — medium-risk positions
carry tail risk you can't see while capping upside you could have had.

**Steelman the objection:** the barbell requires you to correctly identify the
"safe" leg, and 2008 and 2022 both demonstrated that supposedly safe assets can
lose substantially. The strategy relocates the problem rather than eliminating
it.

---

## The Kelly criterion — bet sizing beats edge

**John L. Kelly Jr., Bell Labs, 1956.** The bet fraction that maximises the
long-run **geometric** growth rate of a bankroll.

$$f^* = \frac{bp - q}{b}$$

where $b$ = net odds received, $p$ = probability of winning, $q = 1-p$.

### Worked example — do the arithmetic

**A 60/40 edge at even money.** $b=1$, $p=0.6$, $q=0.4$.

$$f^* = \frac{(1)(0.6) - 0.4}{1} = \mathbf{0.20}$$

**Bet 20% of bankroll.** Now compute the long-run growth rate at different bet
sizes. Growth per bet is $g(f) = p\ln(1+bf) + q\ln(1-f)$:

| Bet fraction | Calculation | Growth per bet |
|---|---|---|
| $f = 0.05$ (quarter Kelly) | $0.6\ln(1.05) + 0.4\ln(0.95)$ = $0.6(0.04879) + 0.4(-0.05129)$ | **+0.88%** |
| $f = 0.10$ (half Kelly) | $0.6(0.09531) + 0.4(-0.10536)$ = $0.05719 - 0.04214$ | **+1.50%** |
| $f = 0.20$ (**full Kelly**) | $0.6(0.18232) + 0.4(-0.22314)$ = $0.10939 - 0.08926$ | **+2.01%** ← maximum |
| $f = 0.40$ (double Kelly) | $0.6(0.33647) + 0.4(-0.51083)$ = $0.20188 - 0.20433$ | **−0.02%** |
| $f = 0.60$ | $0.6(0.47000) + 0.4(-0.91629)$ = $0.28200 - 0.36652$ | **−8.45%** |
| $f = 1.00$ (all in) | $0.4 \times \ln(0)$ | **−∞. Certain ruin** |

**Four things fall out of that table and they are the whole point.**

1. **Half Kelly gives 1.50% vs full Kelly's 2.01% — about 75% of the growth for
   roughly half the volatility.** Most professionals bet fractional Kelly for
   exactly this reason, plus the fact that $p$ is estimated, not known.
2. **Double Kelly gives approximately zero growth.** You have doubled your risk
   and eliminated your entire edge. **There is no warning sign; the curve is
   smooth right up to it.**
3. **Betting your whole bankroll on a 60% favourite has a growth rate of
   negative infinity**, even though its expected value is +20% per bet.
4. **The penalty is asymmetric.** Under-betting costs you a little. Over-betting
   costs you everything.

**Now the finding that matters most.** Consider a much stronger edge — 70/30 —
but bet 60% of bankroll:

$$0.7\ln(1.6) + 0.3\ln(0.4) = 0.7(0.47000) + 0.3(-0.91629) = 0.32900 - 0.27489 = +0.054$$

Growth **+5.4%**. Now take the *weaker* 60/40 edge, correctly sized at 20%:
growth **+2.01%**. Now take the *stronger* 70/30 edge and bet 90%:

$$0.7\ln(1.9) + 0.3\ln(0.1) = 0.7(0.64185) + 0.3(-2.30259) = 0.44930 - 0.69078 = \mathbf{-0.241}$$

**−24% per bet. A 70% edge, sized wrongly, loses money faster than almost
anything.**

> **The superior edge, badly sized, is destroyed by the inferior edge, well
> sized. Bet sizing dominates edge.** This is the single most actionable piece
> of arithmetic in the notebook.

**Caveats, and they are serious.** Kelly assumes you *know* $p$. You don't — you
estimate it, and overestimating $p$ pushes you toward the over-betting side
where the penalty is severe. Kelly also assumes infinite divisibility, no
correlation between simultaneous bets, and indefinite repetition. **Fractional
Kelly (a half or a quarter) is the standard practical response to estimation
error, and it is a correct response, not a timid one.**

---

## Ruin

**Define the absorbing barrier explicitly for every consequential decision: what
state, if reached, ends the game?** Bankruptcy, death, disqualification, loss of
reputation, loss of licence, loss of the relationship.

**The rule:**

> **Never optimise expected value when ruin is possible. Optimise survival
> first, then growth within the survival constraint.**

### The arithmetic that makes it non-negotiable

Any per-period ruin probability $p > 0$, repeated: $P(\text{survive }n) =
(1-p)^n \to 0$.

| Annual ruin probability | 10 years | 30 years | 50 years |
|---|---|---|---|
| 0.5% | 95.1% | 86.0% | 77.8% |
| 1% | 90.4% | 73.9% | 60.5% |
| 2% | 81.7% | **54.5%** | **36.4%** |
| 5% | 59.9% | **21.5%** | **7.7%** |
| 10% | 34.9% | 4.2% | 0.5% |

**A 2% annual chance of blowing up gives you a coin-flip over a career.** And
every year the expected-value calculation says the bet is good.

**Three corollaries:**
1. **Returns don't multiply against zero.** No annual return rescues a path that
   hits the barrier.
2. **The relevant probability is cumulative over your exposure window, never
   per-period.** People quote per-period. See probability-basics.md.
3. **Correlated bets stack ruin probabilities.** Ten "independent" 1% risks that
   share a common factor are not a 9.6% cumulative risk; they are close to a
   single 10% risk that fires all at once.

---

## Premortems

**Gary Klein**, *Harvard Business Review*, September 2007. Klein's background is
naturalistic decision-making — studying firefighters and nurses making good
decisions under time pressure, a tradition largely opposed to Kahneman's.
(The two co-authored a notable joint paper in 2009, "Conditions for Intuitive
Expertise: A Failure to Disagree.")

**The procedure:**

1. The team is at the point of committing to a plan.
2. The facilitator says: **"It is eighteen months from now. This project has
   failed — catastrophically and publicly. Take two minutes and write down why."**
3. Everyone writes independently. **Independence before discussion is
   essential** — it prevents anchoring on the first speaker and gives cover to
   junior objectors.
4. Round-robin: each person reads one item.
5. Revise the plan against the list.

**Why it works, mechanistically:** it converts a *prospective* judgement (which
triggers optimism and social pressure to be supportive) into a *retrospective
explanation* task, which people are fluent at. **Klein cites research suggesting
prospective hindsight increases the number of causes generated by roughly 30%.**
*(This figure traces to Mitchell, Russo & Pennington, 1989. Treat as
suggestive; I am not aware of a large modern replication.)*

**Its real value may be political rather than cognitive.** It legitimises
dissent. In every case in the-control-group.md, someone knew. The premortem is
a licence to say so before the fact rather than to a commission afterwards.

---

## Decision journals

**The problem they solve:** hindsight bias (Fischhoff, 1975) makes it impossible
to reconstruct what you actually believed before the outcome. Without a record,
**you cannot learn from experience** — you can only learn a flattering story
about experience.

**Minimum viable entry, written *before* the outcome:**

1. The decision and the date
2. **The situation and what's driving it** (emotional state included — tired,
   angry, and rushed are all predictive)
3. **The alternatives considered and rejected, with reasons**
4. **The forecast: what you expect, as a probability, by a date**
5. **What would make you conclude you were wrong**
6. Whether this is Type 1 or Type 2

Full template in practices.md.

**Honest status: TIER 3.** There is no controlled trial showing decision
journals improve decision quality. The *components* are better evidenced —
calibration training works, and hindsight bias is robust. **The journal is
cheap, plausible, and unproven. Say so.**

---

## Where the popular story is wrong

| Popular claim | What's actually the case |
|---|---|
| "Maximise expected value" | Correct only for additive, repeatable, ruin-free bets. Wrong for the majority of consequential decisions, and the error is not small — see the coin-flip in fat-tails.md |
| "Bad outcome means bad decision" | *Resulting.* In noisy domains good decisions lose constantly. Judging by outcome selects for luck and destroys the feedback loop |
| "Get more information before deciding" | For Type 2 decisions this is usually wrong. Bezos's ~70% threshold is roughly right, and beyond a modest point extra information raises confidence more than accuracy (Oskamp, 1965) |
| "Finding an edge is the hard part" | Sizing the bet matters more. A 70% edge at 90% of bankroll loses **24% per bet**; a 60% edge at 20% gains 2%. Arithmetic above |
| "Diversify to reduce risk" | Only across genuinely uncorrelated exposures. Correlation goes to ~1 in a crisis. Most "diversified" portfolios hold one bet in twenty costumes |
| "Trust your gut" | Klein's own condition, agreed with Kahneman in 2009: intuition is trustworthy only where the environment is **regular** and there is **rapid, unambiguous feedback**. Firefighting and chess qualify. Stock picking and hiring do not |
| "Kelly is aggressive" | Full Kelly is the *growth-maximising* size and it is already volatile enough that most professionals bet a fraction of it. The aggression people mean is *over*-Kelly, which has negative growth |
| "Sunk costs should never matter" | True in principle; in practice reputational and relational costs of abandonment are real forward-looking costs and are frequently misfiled as sunk cost fallacy |
| "Decision journals are proven" | They aren't. They are cheap and theoretically sound. Do not oversell them |
| "The 70% rule means decide with 70% confidence" | It means decide with 70% of the *information you wish you had* — a statement about how long to wait, not about your probability |

---

## Open questions

- [ ] Is there evidence that decision journals improve decisions, or only that they improve *self-assessment*? Nobody has run the trial and it would be straightforward to run.
- [ ] What is the right Kelly fraction under realistic estimation error in $p$? Half Kelly is folklore with good theoretical support; the optimal fraction as a function of estimator variance is derivable and rarely derived in practice.
- [ ] Does the premortem's 30% figure hold under modern preregistered replication? It traces to a single 1989 study. It is repeated everywhere.
- [ ] How do you identify absorbing barriers you haven't thought of? This is the unknown-unknowns problem restated, and it is the binding constraint on the whole ruin framework.
- [ ] Where exactly does the Klein/Kahneman boundary on intuition fall in ambiguous domains — medicine, management, investing? The 2009 joint paper set the criteria; applying them case by case is unresolved.
- [ ] Can organisations be structured so that Type 1 / Type 2 classification is made *before* the decision rather than argued about afterwards? Every failure I know of involved a Type 1 decision being processed as Type 2 by someone who wanted it that way.
