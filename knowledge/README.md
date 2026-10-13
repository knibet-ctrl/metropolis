# KNOWLEDGE — Research Notebook
# Topic: How knowledge is actually made — and how wrong ideas die
# Started: 2026-09-01

===============================================================================
WHAT THIS IS
===============================================================================
An honest account of how humans come to know things, written with the same
discipline as the leaders/ and existence/ notebooks: positions stated fairly,
disagreements flagged as disagreements, confidence marked, and a standing
refusal to pretend something is settled when it isn't.

The questions:

  What separates science from everything else? Is there a rule?
  How does a wrong idea actually die — evidence, or funerals?
  How much of the published literature is false?
  What does peer review do? What does it not do?
  When should you trust an expert, and about what?
  Which institutions produce knowledge, and which distort it?
  What should *you* do with a claim in front of you right now?

**No live sources were used.** Every date, number, author and study name below
was written from general knowledge without verification against the literature.
Treat this as a structured map, not as scholarship. The specific claims most
likely to be slightly wrong are flagged in the honest part, below, and in
sources-and-caveats sections throughout.

===============================================================================
THE ONE IDEA THAT ORGANISES EVERYTHING
===============================================================================
**Knowledge is not produced by a method. It is produced by an error-correcting
social system, and that system has an incentive structure.**

Almost every confusion in this domain comes from believing one of two myths:

  MYTH A — "The Scientific Method." A procedure exists; follow it and truth
           comes out. Falsified by every close study of what scientists do.
  MYTH B — "It's all social construction." Because no clean method exists,
           knowledge is just power and consensus. Falsified by aeroplanes.

Both are wrong in the same way: **they mistake the absence of an algorithm for
the absence of a mechanism.** The mechanism is distributed error correction —
many people, with different priors, career interests and instruments, checking
each other over time, under conditions where being wrong eventually costs
something.

The corollary runs the whole notebook: **wherever being wrong stops costing
anything, knowledge production degrades — regardless of the credentials of the
people involved.** That single principle explains the replication crisis,
Lysenkoism, nutrition epidemiology, forensic science, and most of what is on
the failure list below.

===============================================================================
FILE MAP
===============================================================================
knowledge/README.md                 <- you are here. Index, findings, log.
knowledge/the-questions.md          <- START HERE. Splits "how do we know?" into
                                       separately-answerable parts, with tiers.
knowledge/what-is-science.md        <- Demarcation. Popper, Kuhn, Lakatos,
                                       Feyerabend, and why no criterion works.
knowledge/how-theories-die.md       <- Anomalies, auxiliary hypotheses,
                                       Duhem-Quine, Planck's principle tested.
                                       Wegener, Semmelweis, Marshall, phlogiston.
knowledge/the-replication-crisis.md <- What happened, in which fields, the
                                       casualties, and which reforms worked.
knowledge/peer-review.md            <- What it does and doesn't do. Its short
                                       history. Fraud it missed.
knowledge/expertise-and-authority.md<- Tetlock. Where expertise transfers and
                                       where it evaporates. Nobel disease.
knowledge/bias-and-reasoning.md     <- Motivated reasoning, myside bias, why
                                       intelligence doesn't protect you.
knowledge/institutions-of-knowledge.md <- Universities, journals, funders,
                                       patents. Goodhart all the way down.
                                       Contains the extended CONTROL GROUP:
                                       thalidomide, dietary fat, eugenics,
                                       the lobotomy Nobel.
knowledge/what-we-know.md           <- CONFIDENCE LEDGER. THE KEY FILE.
knowledge/practices.md              <- What to actually do with a claim.
knowledge/reading.md                <- Primary sources, plus correctives.

Read order if you have an hour:
  the-questions.md -> what-we-know.md -> practices.md

Cross-references: existence/epistemics.md covers reasoning failure in domains
with NO feedback. This notebook covers domains WITH feedback, and how that
feedback gets corrupted. leaders/failure-modes.md and leaders/sources-and-
caveats.md share the survivorship-bias discipline used here.
leaders/profiles/ignaz-semmelweis.md and .../robert-fitzroy.md are the two
existing profiles that bear directly on this topic.

===============================================================================
HEADLINE FINDINGS (compressed; each one contestable)
===============================================================================
 1. **There is no demarcation criterion.** Falsificationism fails, and every
    replacement fails. The mainstream philosophical position since Laudan
    (1983) is that "science" is a family-resemblance cluster, not a definition.
    This is not a scandal. It is the correct answer.

 2. **The replication crisis was a re-discovery, not a discovery.** Sterling
    documented 97% positive results in psychology journals in 1959. Meehl
    predicted the whole thing in 1967 and 1978. Rosenthal named the file-drawer
    problem in 1979. **The field was told, repeatedly, for fifty years, and
    nothing changed until 2011-2015.** That fact is more important than the
    crisis itself, because it tells you the failure was structural, not
    informational.

 3. **Preregistration works, and the size of the effect is shocking.** Kaplan
    and Irvin (2015) found large NHLBI cardiovascular trials reported a
    significant benefit 57% of the time before mandatory registration in 2000,
    and 8% of the time after. Registered Reports in psychology produce positive
    results roughly 40-50% of the time versus ~90%+ in the standard literature.
    **Nothing about the science changed. Only the ability to hide changed.**

 4. **"Science advances one funeral at a time" is roughly half true, and not
    for the reason people think.** Hull, Tessner and Diamond (1978) found age
    was a weak predictor of accepting Darwinism. But Azoulay, Fons-Rosen and
    Graff Zivin (2019) found that after a star life scientist dies prematurely,
    outsiders enter the subfield and their work is disproportionately cited.
    **The mechanism is gatekeeping and resource control, not stubborn belief.**

 5. **Peer review does not detect fraud and detects errors poorly.** In
    controlled tests where major errors were deliberately inserted, reviewers
    found roughly a quarter to a third of them. *(Baxt 1998, Schroter 2008 —
    small studies; the direction is robust, the exact fraction is not.)* Every
    large fraud case in the notebook was caught by outsiders doing forensic
    reanalysis, not by referees.

 6. **Expertise is real but narrow, and it transfers far less than the expert
    believes.** Kahneman and Klein (2009) agreed on the condition: expertise
    develops only where there are valid cues and fast, unambiguous feedback.
    Anaesthesiology, chess, weather forecasting — yes. Long-run political
    prediction, clinical prediction of violence, stock picking — no. The Nobel
    disease is the pure case: Pauling on vitamin C, Mullis on HIV, Montagnier
    on homeopathy.

 7. **Intelligence does not protect you; it arms you.** Kahan's numeracy work
    and Stanovich's myside-bias research point the same way: the more capable
    reasoner produces better arguments *for the conclusion they already hold*.
    Myside bias is close to uncorrelated with IQ, unlike almost every other
    bias. *(The strongest single finding in bias-and-reasoning.md.)*

 8. **The most important number in the notebook is the prior.** Ioannidis's
    2005 argument is not about p-values. It is that the truth of a "significant"
    finding depends mostly on how likely the hypothesis was before you tested
    it. A field that tests many implausible hypotheses with low power will
    publish mostly false positives no matter how honest everyone is.

 9. **Fields fix themselves when the cost of being wrong becomes visible.**
    Human genetics did it: the entire candidate-gene literature on depression
    was false positives, and genome-wide significance thresholds plus enormous
    samples killed it. Clinical trials did it via registration and CONSORT.
    **This is the strongest evidence that the system works — and it took
    external forcing every time.**

10. **The popular narrative of heroic outsiders is mostly survivorship bias.**
    We remember Wegener, Semmelweis and Marshall. We do not keep a list of the
    thousands of confident outsiders who were simply wrong, because there is no
    reason to write them down. **The base rate for "rejected maverick is right"
    is very low.** See the control group below.

===============================================================================
THE CONTROL GROUP — where the knowledge system failed
===============================================================================
Without failures you are pattern-matching on survivors. Two kinds of failure,
and they are not symmetrical.

FALSE ACCEPTED — the system endorsed something wrong, sometimes lethally:
  Lysenkoism (USSR, 1930s-1964)        genetics banned; Vavilov died in prison
  Lobotomy                             Moniz, Nobel Prize 1949, never rescinded
  Eugenics                             mainstream ~1900-1940; Buck v. Bell 1927
  Thalidomide                          marketed 1957, withdrawn 1961
  N-rays                               Blondlot 1903; ~300 papers, zero rays
  Cold fusion                          Fleischmann & Pons, March 1989
  Piltdown Man                         1912 forgery, exposed 1953
  Dietary fat orthodoxy                see the-replication-crisis.md — and note
                                       the revisionist story is ALSO overstated
  Candidate gene studies               ~two decades of psychiatric genetics,
                                       essentially all false positives
  Schön (Bell Labs), Stapel (Tilburg)  fabrication that passed Science/Nature

TRUE REJECTED — the system suppressed something right:
  Wegener / continental drift          1912-1915 proposed, ~1965 accepted
  Semmelweis / handwashing             1847 demonstrated, died 1865 in an asylum
  Marshall & Warren / H. pylori        1982-84 evidence, ~1994 consensus
  Bizzozero, Lykoudis                  earlier, and entirely forgotten
  Barbara McClintock / transposons     1940s-50s, Nobel 1983

**The asymmetry matters.** The false-accepted list is longer, better funded and
did more damage than the true-rejected list. The romantic story is about the
second list. The dangerous failure mode is the first.

===============================================================================
THE HONEST PART
===============================================================================
- **No sources were checked.** Dates, sample sizes and percentages below are
  from memory. The ones most worth verifying before you repeat them:
  the Kaplan & Irvin 57%->8% figures; the Open Science Collaboration's 36%; the
  Amgen 6-of-53 figure (Amgen never released the study identities — treat as
  unverifiable); the Registered Report positive-rate comparison; the Azoulay
  effect sizes; the Turner et al. antidepressant publication numbers.
- **This notebook is itself subject to everything it describes.** It selects
  vivid cases, which is exactly the bias it warns about. The dull, correct,
  uneventful 95% of science does not generate anecdotes.
- **Survivorship bias is unfixable here.** Failed research programmes are
  systematically under-recorded. The famous frauds are the ones that were
  caught; the base rate of undetected fraud is unknown and probably
  unknowable. Anyone quoting a confident figure for it is estimating.
- **The author has a view**, and it leans toward "the system is badly broken in
  specific measurable ways and still the best thing we have." Positions
  arguing the opposite are steelmanned in each file; check whether the
  steelmanning is genuine or performed.
- **Fields differ enormously.** Statements about "science" are almost always
  false. Particle physics, clinical medicine, social psychology, nutrition
  epidemiology and macroeconomics have almost nothing in common
  methodologically. Where a claim is field-specific, it is labelled.

===============================================================================
RUNNING LOG
===============================================================================
2026-09-01  Notebook opened. 12 files drafted in one sitting from general
            knowledge, no live verification. Tier system inherited from
            existence/what-we-know.md.
2026-09-01  Decided the organising principle is incentive structure rather than
            method. This reframes the demarcation problem as secondary — a
            deliberate departure from how philosophy-of-science texts open.
2026-09-01  Added the two-column control group (false-accepted vs true-rejected)
            after noticing the draft was drifting toward heroic-outsider
            narrative. The asymmetry between the columns became finding #10.
2026-09-01  Flagged Planck's principle for follow-up: the popular version and
            the empirical version disagree, and the empirical version is more
            interesting. See how-theories-die.md.
2026-09-01  Expanded the four institutional-failure cases into full treatments
            in institutions-of-knowledge.md. The dietary fat entry needed a
            correction-to-the-correction: the revisionist story about Ancel
            Keys is itself overstated, and repeating it uncritically is the
            same error running the other way.
2026-09-01  OPEN: no file yet on knowledge outside institutional science —
            craft knowledge, tacit knowledge, indigenous knowledge systems,
            markets as information processors. Polanyi and Hayek are cited in
            passing and deserve their own treatment.
