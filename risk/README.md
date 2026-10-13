# RISK — Research Notebook
# Topic: Risk, uncertainty, and forecasting — deciding and predicting under uncertainty
# Started: 2026-09-01

===============================================================================
WHAT THIS IS
===============================================================================
An honest map of what is actually known about predicting the future and
deciding without knowing it.

  What can be forecast at all? What does a probability mean?
  Why do experts do so badly? Why do some people do better?
  How should you size a bet? Why do safety systems cause accidents?
  What is the difference between being wrong and being ruined?

Written in the same discipline as leaders/ and existence/: positions given
fairly, disputes flagged as disputes, confidence marked, arithmetic shown, and
a standing refusal to pretend something is settled when it isn't.

**No live sources were used. This was written from general knowledge with no
verification against primary documents.** Names, dates and figures are given
because vague claims are unfalsifiable and therefore useless — but every
specific number here should be checked before you cite it. Several are from
memory and may be off. Where a figure is load-bearing, I say so.

**Second warning, and this one is structural.** A large fraction of the popular
literature in this domain rests on behavioural-economics experiments that have
failed to replicate. This notebook does not treat the heuristics-and-biases
canon as settled. See biases.md, which opens with the caveat rather than
burying it.

===============================================================================
THE ONE IDEA THAT ORGANISES EVERYTHING
===============================================================================
**Almost all of the value in this domain comes from three moves, and none of
them is "predict better."**

  1. SORT THE QUESTION. Risk (known odds) / uncertainty (unknown odds) /
     ignorance (unknown outcomes) require completely different tools. Applying
     risk tools to ignorance is how LTCM died. -> the-questions.md

  2. USE THE BASE RATE. The single highest-return cognitive move available.
     Ask "what usually happens to things like this" before asking "what will
     happen to this." -> base-rates.md

  3. SURVIVE. Expected value is the wrong objective whenever ruin is on the
     table, because you only get one path through time, not the average of all
     of them. This is the ergodicity point and it is the deepest idea in the
     notebook. -> fat-tails.md, decisions.md

Forecasting skill is real, measurable, and worth maybe 20% of the total. Bet
sizing and survivability are worth more than accuracy. **You can be right more
often than anyone and still go to zero.**

===============================================================================
FILE MAP
===============================================================================
risk/README.md              <- you are here. Index, headlines, running log.
risk/the-questions.md       <- START HERE. Knight's risk/uncertainty/ignorance
                               split. Which questions are forecastable at all.
risk/probability-basics.md  <- What a probability means. Bayes worked in full.
                               Base rate fallacy with real numbers. 1-in-100
                               vs 1-in-100-year.
risk/base-rates.md          <- The highest-value tool in the notebook. Outside
                               view, reference class forecasting, Flyvbjerg's
                               overrun data, the planning fallacy.
risk/forecasting.md         <- Tetlock, foxes and hedgehogs, superforecasters,
                               Brier scores with arithmetic, prediction markets,
                               and Meehl's finding that simple models beat
                               experts.
risk/fat-tails.md           <- Taleb. Mediocristan vs Extremistan, power laws,
                               why the normal distribution is a lie in finance,
                               and ERGODICITY — the coin-flip example. Read this
                               one twice.
risk/biases.md              <- Heuristics and biases WITH the replication
                               caveat at the top. What survives, what didn't,
                               and Gigerenzer's serious critique.
risk/decisions.md           <- Decision theory you can use. EV vs utility,
                               reversibility, Kelly criterion, ruin, premortems.
risk/risk-management.md     <- Redundancy, margin of safety, robust vs resilient
                               vs antifragile, correlated risk, Perrow's normal
                               accidents, why safety systems fail.
risk/the-control-group.md   <- THE FAILURES. LTCM, 2008, Challenger, Columbia,
                               Fukushima, Iraq WMD, COVID. Each one: which
                               mechanism failed.
risk/what-we-know.md        <- CONFIDENCE LEDGER. Four tiers. What people most
                               commonly get wrong. THE KEY FILE.
risk/practices.md           <- What to actually do. Decision journal template,
                               calibration self-test you can run today.
risk/reading.md             <- Primary sources, with caveats attached.

Read order if you have an hour:
  the-questions.md -> what-we-know.md -> practices.md

Read order if you have three:
  add fat-tails.md (ergodicity) and the-control-group.md

Cross-notebook links:
  leaders/failure-modes.md   — overconfidence and survivorship in leadership
  leaders/playbook.md        — Bezos Type 1 / Type 2 decisions
  existence/epistemics.md    — how to think without fooling yourself
  existence/what-we-know.md  — the same tier system applied to metaphysics

===============================================================================
HEADLINE FINDINGS (compressed; each contestable; tier marked)
===============================================================================
 1. **Most expert prediction is worthless beyond about three years.** TIER 1.
    Tetlock ran the study for two decades. Average expert accuracy on political
    and economic events was barely distinguishable from chance, and the most
    famous experts were the *worst*. Fame correlates negatively with accuracy.

 2. **Forecasting skill exists, is measurable, and is mostly technique.** TIER 1
    for existence, TIER 2 for transferability. Superforecasters beat the field
    persistently. What they do differently is teachable: granular probabilities,
    reference classes, frequent small updates, no ideological commitment.

 3. **The base rate beats the story, essentially always.** TIER 1. Flyvbjerg's
    data: 9 in 10 large infrastructure projects run over budget, and the rate
    has not improved in 70 years. The inside view feels more informative and
    is systematically worse.

 4. **Simple models beat expert judgement.** TIER 1, and the most ignored
    finding here. Meehl 1954, replicated for 70 years. Even unit-weighted
    linear models with no fitted coefficients beat the clinicians whose
    judgement generated the variables.

 5. **Ruin is not a bad outcome; it is a different category of outcome.** TIER 1
    mathematically. Expected value averages across parallel worlds. You live in
    one. A bet with positive expected value can have a negative growth rate for
    every individual who takes it. See the coin-flip arithmetic in fat-tails.md.

 6. **The normal distribution is wrong for most social and financial
    variables, and wrong in the direction that kills you.** TIER 1. The 1987
    crash was a ~20-sigma event under Gaussian assumptions — a probability so
    small the universe is not old enough. It happened on a Monday.

 7. **Much of the popular bias literature has not replicated.** TIER 1 that
    there is a problem; TIER 2 on which specific findings survive. Ego
    depletion: dead. Social priming: mostly dead. Power posing: hormonal claims
    retracted by an original author. Anchoring, overconfidence, scope
    insensitivity and base-rate neglect hold up better.

 8. **Diversification fails precisely when you need it.** TIER 1. Correlations
    that sit near 0.2 in calm markets go above 0.8 in a crisis. Every risk
    model calibrated on calm data understates crisis risk by construction.

 9. **Safety systems create new failure modes.** TIER 2, well argued. Perrow:
    in systems with high interactive complexity and tight coupling, accidents
    are structural, not aberrant, and added safety devices add complexity.
    High Reliability Organisation theory is the serious counter-argument.

10. **Almost every famous disaster was foreseen by someone inside the
    organisation who was overruled.** TIER 1 as a pattern. Boisjoly on
    Challenger. The Debris Assessment Team on Columbia. TEPCO's own 2008
    tsunami study. INR and DOE dissenting on Iraq's aluminium tubes. **The
    binding constraint is usually organisational, not epistemic.**

===============================================================================
HONEST CAVEATS
===============================================================================
- **No sources were checked.** Figures reconstructed from memory. Treat every
  number as approximately right and verify before use.
- **Survivorship runs through everything.** We hear about LTCM because it blew
  up. We do not have the reference class of near-identical funds that didn't.
- **The control group problem is severe here.** Successful risk management is
  invisible. Y2K either worked or was hype and the outcome cannot distinguish
  them. This is the prevention paradox and it is not solvable from outcomes.
- **This notebook is biased toward the tail-risk school.** Taleb's framing is
  load-bearing in several files. His critics have real points and are given
  space, but a reader should know the lean exists.
- **Behavioural economics is in an unfinished correction.** Anything here
  described as "holds up better" means "as of the last time I looked," and the
  field is moving.
- **Finance and engineering dominate the examples** because they keep records.
  Medicine, war and politics are worse-instrumented and probably worse-behaved.

===============================================================================
RUNNING LOG
===============================================================================
2026-09-01  Notebook created. 13 files. Structure follows existence/ and
            leaders/: disaggregation file first, confidence ledger as the key
            file, explicit control group of failures, practices file last.

2026-09-01  Decision: put the replication caveat at the TOP of biases.md rather
            than in a footnote. The popular version of this topic is largely
            downstream of Thinking, Fast and Slow, and a meaningful fraction of
            that book's cited studies are now in doubt. Burying that would
            reproduce the error the notebook is about.

2026-09-01  Decision: ergodicity gets full treatment with arithmetic in
            fat-tails.md. It is the least-known and highest-value idea in the
            domain, and every summary I have seen states it without showing the
            numbers, which is why nobody believes it.

2026-09-01  Open tension noted, unresolved: Taleb's position (do not forecast,
            build robustness) and Tetlock's position (forecasting is a
            measurable skill, train it) are usually presented as opposed. They
            are mostly about different question classes — Tetlock's questions
            are resolvable in 1–12 months and drawn from a known distribution;
            Taleb's are tail events outside it. But the two camps genuinely do
            disagree about how much of life is which. Flagged in
            what-we-know.md rather than papered over.
