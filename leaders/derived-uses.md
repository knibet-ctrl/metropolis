# Derived Uses — What Can Actually Be Built From This Data

Analysis of the notebook as a *dataset* rather than as reading material.
What it can support, what it can't, and what's worth doing.

---

## What this data is, structurally

Strip the prose and there are three things:

1. **A tagged case library** — ~40 figures, each mapped to a subset of the 12
   mechanisms, with outcome labels (success / failure / disputed).
2. **A mechanism taxonomy** — 12 items, each with a definition, a pathological
   twin, and a self-test question.
3. **An epistemic layer** — confidence ratings and a control group.

That shape is what determines the possibilities. It is effectively a small
**labelled dataset with a scoring rubric attached**. Most options below are
just different ways of querying it.

---

## Tier 1 — Personal instruments (highest value, lowest effort)

**Self-audit scorecard.** The 12 self-tests are already written as questions.
Score 0–3 on each, twice a year. The output isn't a number — it's *which
mechanism is weakest*, because that's where marginal effort should go. Most
people score high on effort-type mechanisms and near-zero on #7
(institution-building) and #12 (successors).

**Decision log.** Mechanism #4 is the most immediately operational item in the
notebook. Record every non-trivial decision with: reversible or not, confidence
at the time, review date. After six months you can measure your own
calibration — nothing else here lets you do that.

**Prediction journal.** Comes straight from the hardest question in
`failure-modes.md`: Churchill and FitzRoy felt identical from the inside.
Written, dated, falsifiable predictions with pre-committed disconfirming
evidence is the only known defence. Converts the notebook's biggest open
problem into a practice.

**Annual "what price am I not paying" review.** Point 4 of the meta-pattern is
the sharpest finding in the notebook and is answerable in one sitting.

---

## Tier 2 — Team and organisational diagnostics

**Error-correction audit.** The clearest result from the failure sample: a
working bad-news channel separates winners from losers more reliably than
talent does. Short diagnostic — when did someone last tell you you were wrong,
what happened to them, and is there a structural cord anyone can pull?
Genuinely useful, and almost nobody does it.

**Constraint-finding protocol.** Mechanism #10 as a recurring meeting format:
*"if this project succeeds perfectly, does the outcome change?"* Kills
non-constraint work.

**Selection rubric.** Mechanism #6 says selection dominates management. Build an
interview scorecard weighted toward the mechanisms that predict: long-horizon
persistence on one problem, direct contact with reality, evidence of building
systems rather than personal heroics.

**Pre-mortem checklist from the pathology table.** Before committing to a
strategy, walk the 12 evil twins and ask which one you're actually doing.
Conviction or stubbornness? Focus or avoidance?

---

## Tier 3 — Product possibilities

The content is already structured for this — each mechanism has a definition,
a test, an action, and a failure mode. That's a complete data model.

- **Assessment app** — 12 mechanisms × self-tests → profile → targeted playbook items.
- **Decision-classifier tool** — reversible/irreversible split plus review dates.
- **Case-study browser** — filter figures by mechanism, era, or outcome.
- **Prediction tracker** — with forced disconfirming-evidence fields and scheduled review.

**Honest read:** the assessment tool and the decision tool are the only two with
real utility. The case browser is a content project pretending to be a product.

---

## Tier 4 — Research and content

**Convert to a schema.** `figure | era | domain | mechanisms[] | outcome |
confidence | price_paid`. Once tabular, claims become weakly testable — e.g.
does #7 correlate with durability of influence? The notebook asserts it; the
data could check it.

**Testable hypotheses already in the file:**
- Median age at first real leverage is later than people assume (open question, currently unanswered).
- New-medium capture recurs every technology cycle (#5 sub-pattern) — strong enough to bet on.
- Mechanism #3 appears equally in winners and losers — already half-demonstrated, worth formalising.

**Writing.** The counter-intuitive findings are the publishable ones: charisma
is a correlate not a cause; #1 is the only load-bearing mechanism; Theranos ran
the visible playbook correctly.

---

## What this data CANNOT support

Being blunt, because this is where people over-claim:

- **Any success rate or probability.** No denominator. The invisible failure sample makes every effectiveness estimate meaningless.
- **Causal claims.** ~40 hand-picked cases with confirmation bias in selection. Illustration, not evidence.
- **Prediction about individuals.** Nothing here forecasts whether a given person will succeed.
- **Anything depending on the unverified facts.** Per the flagged-claims table in `sources-and-caveats.md`, this can't be published or presented until source-checking is done.

---

## If only three are pursued

1. **Decision log** — mechanism #4, immediately actionable, self-verifying over months.
2. **Error-correction audit** — the finding best supported by *both* samples.
3. **Prediction journal** — addresses the notebook's own hardest unsolved problem.

Everything else is either content, or a product idea that needs the
fact-verification done first.
