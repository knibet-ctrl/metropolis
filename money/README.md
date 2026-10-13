# MONEY — Research Notebook
# Topic: Money, value, and how economies actually work
# Started: 2026-09-01

===============================================================================
WHAT THIS IS
===============================================================================
An attempt to say plainly what money is, where it comes from, who makes it,
what makes anything worth anything, and which parts of economics are actually
known versus argued about by serious people who read the same data.

**No live sources were used. Nothing here was verified against a primary
document, a database, or the web.** This is compiled from general knowledge.
Figures, dates and attributions are given precisely because vague numbers are
useless — but precision is not accuracy. Check anything load-bearing. Several
numbers below are almost certainly slightly wrong. See what-we-know.md for
which claims can bear weight.

**On politics.** Economics is the most ideologically loaded topic in this
notebook set. The discipline here is: every school gets its strongest form,
disagreements get explained rather than adjudicated, and where a dispute is
about values rather than facts, that is said out loud. If you can tell what
the author's politics are from these files, the files have failed.

===============================================================================
THE ONE IDEA THAT ORGANISES EVERYTHING
===============================================================================
**Nearly all public confusion about economics comes from conflating three
kinds of statement that look identical on the page.**

  1. ACCOUNTING IDENTITY — true by definition, tells you nothing about causes.
     "One sector's deficit is another sector's surplus." "MV = PY."
     "Savings equals investment." You cannot argue with these. You also cannot
     derive a policy from one. They constrain stories; they don't tell them.

  2. EMPIRICAL CLAIM — could be false, testable, has a confidence level.
     "Countries that left the gold standard earlier recovered earlier."
     "Most active funds underperform their index net of fees."

  3. THEORETICAL CLAIM — a causal mechanism inside a model. Only as good as
     the model's assumptions, and the assumptions are where the fight is.
     "Deficits crowd out private investment." "Minimum wages reduce employment."

The single most common rhetorical move in economic argument is to state an
identity, nod gravely, and let the listener supply a causal story it does not
contain. **Both left and right do this constantly.** MMT advocates do it with
sectoral balances. Monetarists do it with the equation of exchange. Hard-money
advocates do it with "money printing." Learn to spot it and half the noise in
the topic disappears.

Second organising idea: **money is not a thing, it is a record.** Almost every
puzzle about money gets easier once you stop looking for the substance and
start looking for the ledger and for who is trusted to keep it.

===============================================================================
FILE MAP
===============================================================================
money/README.md                 <- you are here. Index, findings, running log.
money/the-questions.md          <- START HERE. Splits "what is money?" into the
                                   five separable questions it actually is.
money/what-is-money.md          <- Functions, commodity vs credit theory, and
                                   the barter myth, which is a genuine textbook
                                   error repeated for 250 years.
money/how-money-is-created.md   <- THE HIGH-MYTH FILE. Banks create deposits by
                                   lending. The money multiplier is not how it
                                   works, per the BoE and Bundesbank themselves.
money/inflation.md              <- Measurement, five competing explanations,
                                   four hyperinflations dissected, and the
                                   2021-23 episode that embarrassed everyone.
money/banking-and-crises.md     <- Maturity transformation, runs, 1929, 1987,
                                   LTCM, 2008, SVB 2023, Minsky, and the
                                   Reinhart-Rogoff spreadsheet as epistemics.
money/value.md                  <- Why anything is worth anything. Labour theory
                                   vs the 1870s marginal revolution. Hayek 1945.
                                   Where markets fail and what they price badly.
money/schools.md                <- Nine schools, steelmanned. Core claim,
                                   best point, best objection, hits, misses.
money/inequality-and-growth.md  <- Why some countries are rich. Piketty and the
                                   serious critiques. Measurement problems.
money/the-control-group.md      <- FAILURES. Soviet calculation, gold standard
                                   1929-33, the euro's design, structural
                                   adjustment, Japan, and confident wrongness.
money/what-we-know.md           <- CONFIDENCE LEDGER. Four tiers. THE KEY FILE.
money/practices.md              <- What follows for one person. Non-prescriptive.
money/reading.md                <- Sources by subtopic, with correctives.

Read order if you have an hour:
  the-questions.md -> how-money-is-created.md -> what-we-know.md

===============================================================================
HEADLINE FINDINGS (compressed; each is expanded and caveated in its own file)
===============================================================================
 1. **The barter origin story is fiction.** Every introductory textbook since
    Smith (1776) opens with barter giving way to money. Anthropology has never
    found such an economy. Caroline Humphrey, 1985: no example of a pure barter
    economy has ever been described. Credit and accounting predate coinage by
    roughly two and a half millennia. TIER 1 on the negative claim; TIER 2 on
    what replaces it.

 2. **Banks do not lend out deposits; lending creates deposits.** The money
    multiplier taught in textbooks is a poor description of modern banking.
    This is not a heterodox position — the Bank of England (Quarterly Bulletin,
    2014 Q1) and the Bundesbank (Monthly Report, April 2017) state it plainly.
    Several major economies have had zero reserve requirements for decades.

 3. **"Printing money" is a phrase that obscures more than it reveals.**
    Physical cash is a small and passively-supplied share of the money stock.
    Central bank reserves and bank deposits circulate in largely separate
    circuits. QE swaps one asset for another; it is not helicopter money. The
    2008-2019 record is a clean falsification of the naive version.

 4. **Hyperinflation is a state-failure disease, not a printing disease.**
    Weimar, Hungary 1946, Zimbabwe 2008, Venezuela 2018 share a structure:
    collapse of real output and the tax base, a government that can neither cut
    nor borrow, foreign-currency obligations, then monetisation and a velocity
    spiral. Printing is the mechanism, not the cause.

 5. **The 1870s marginal revolution is the most important idea most people
    have never heard of.** Jevons, Menger and Walras independently established
    that value is not a property of objects but a relation between an agent and
    the marginal unit available. It dissolved the diamond-water paradox and
    made "intrinsic value" a category error.

 6. **Hayek's 1945 paper is the strongest thing anyone has written about
    prices** — and it is narrower and better than the laissez-faire slogan it
    gets reduced to. The claim is epistemic: the relevant knowledge exists only
    in dispersed, tacit, local form. Central planning fails on information, not
    on arithmetic. The same argument identifies exactly where markets fail.

 7. **Macroeconomics has a poor forecasting record and unusual policy power.**
    It missed 2008. It predicted inflation after QE that did not arrive. It
    called 2021 inflation transitory. It then predicted a recession to cure
    that inflation which also did not arrive. Two opposite failures inside a
    decade. Treat confident macro forecasts as roughly worthless.

 8. **Growth's causes are genuinely unsettled.** Institutions, geography,
    culture, human capital and energy are all live and all endogenous to each
    other. Solow's residual — the part we cannot explain — accounts for most
    measured growth. "Why are some countries rich?" may be the largest open
    question in social science.

 9. **Piketty's data and Piketty's theory should be scored separately.** The
    top-income-share series built from tax records is a major, largely accepted
    empirical contribution. The r > g mechanism has serious critiques, the
    sharpest being Rognlie's (2015) finding that the rise in capital's share is
    almost entirely housing.

10. **Where economists disagree, it is usually for one of three reasons:**
    different models (which mechanism is omitted), different values (what the
    objective function is), or different readings of the same data (sample,
    window, identification). Almost none of it is one side simply lying. Ask
    which of the three is operating before assigning bad faith.

===============================================================================
HONEST CAVEATS
===============================================================================
* **No verification.** Every number should be treated as approximately right at
  best. Dates of publication, peak inflation rates and balance sheet figures
  are the highest-risk items.
* **Anglophone bias.** The literature cited is overwhelmingly US/UK, which is
  itself a distortion of the field and of the world.
* **Macro is soft.** Large parts of this notebook sit at TIER 2. That is
  unusual for a field whose outputs move interest rates for eight billion
  people, and it is stated repeatedly rather than smoothed over.
* **Identification is the recurring weakness.** Most macro claims rest on a
  small number of non-independent country-decades. There is no control group
  for a national economy. the-control-group.md is the closest available
  substitute and it is not a real one.
* **The author has no live market data and no access to current conditions.**
  Nothing here is investment advice. See the disclaimer in practices.md.

===============================================================================
RUNNING LOG
===============================================================================
**2026-09-01** — Notebook created. All 13 files written in one pass from
general knowledge, no source access. Structure mirrors existence/ and leaders/.

Decisions made in this pass:
  * Kept the identity / empirical / theoretical distinction as the spine. It
    is doing more work here than the tier system alone can.
  * Gave MMT and Austrian economics the same steelman treatment as Keynesian
    and monetarist positions, including their strongest objections. Both are
    routinely caricatured, in opposite directions, by opposite audiences.
  * Flagged Graeber's *Debt* as directionally right on barter and unreliable
    in specifics. Not treating "the anthropology is right" and "this book is
    right" as the same claim.
  * Separated Reinhart & Rogoff's 2009 book (largely sound) from their 2010
    austerity paper (spreadsheet error). Conflating them is now itself a myth.
  * Put the 2021-23 inflation episode in as a live epistemics case study,
    scoring both camps as wrong, because that is what happened.

Known gaps for a future pass:
  - [ ] Nothing substantive on China's financial system, which is now large
        enough that omitting it distorts the whole picture.
  - [ ] Trade and exchange rates get only glancing treatment; they deserve a
        file (Balassa-Samuelson, the dollar system, Triffin, capital controls).
  - [ ] Crypto and CBDCs treated only as test cases, not on their own terms.
  - [ ] Ecological and feminist economics get a row in schools.md and no more.
  - [ ] Public finance and tax incidence are almost entirely absent.
