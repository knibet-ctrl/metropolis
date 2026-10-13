# Peer Review — What It Does and Doesn't Do

> **Status: Tier 1 on the negatives, Tier 2 on the positives.** That peer review
> does not detect fraud and detects deliberate errors poorly is established by
> controlled studies. That it *improves* papers is plausible, weakly evidenced,
> and hard to measure. Its near-sacred status in public discourse is entirely
> unearned by the evidence.

---

## It is much younger than you think

The single most useful fact about peer review is its **date**.

| Date | Event |
|---|---|
| 1665 | *Philosophical Transactions of the Royal Society* founded by Henry Oldenburg, who selected papers largely himself and sometimes consulted others |
| 1752 | The Royal Society establishes a Committee on Papers — internal review by council members, not external referees |
| 1831 | William Whewell proposes written referee reports for the Royal Society |
| 1905 | Einstein publishes four papers in *Annalen der Physik* — the *annus mirabilis*, including special relativity — **with no external peer review.** Planck, as editor, decided |
| 1936 | Einstein submits a paper to *Physical Review* denying gravitational waves. It is sent to a referee (Howard Percy Robertson), who finds an error. Einstein is furious at the "unauthorised" review and withdraws it. **The referee was right; Einstein quietly corrected the paper and published it elsewhere** |
| 1973 | ***Nature* introduces systematic external peer review** |
| 1976 | *The Lancet* does the same |

**Read that again: the journal that published Watson and Crick's 1953 double
helix paper did not have formal peer review.** Most of twentieth-century
physics, the structure of DNA, and the foundations of modern chemistry were
published without it.

The modern system is a **post-war administrative response to volume and to
government funding accountability**, not an ancient guarantor of truth. Anyone
who says "this hasn't been peer reviewed" as though invoking a timeless
standard is invoking something younger than the pocket calculator.

---

## What it actually does

**Honestly: three things, none of which is verification.**

1. **Triage.** Reduces editorial load by filtering obvious unsuitability. This is real and valuable.
2. **Improves presentation and reporting.** Reviewers catch missing methods detail, unstated limitations, overreaching abstracts. *(Best evidenced of the three, and still modest.)*
3. **Confers institutional legitimacy.** Which is a sociological function, not an epistemic one — but it is the function that actually drives the system, because careers, grants and tenure hang on it.

**What it does not do:**
- It does not check the data. Reviewers almost never see raw data.
- It does not re-run the analysis. Where journals have tried, error rates found are high.
- It does not detect fabrication. It is not designed to and cannot be.
- It does not certify correctness. **A peer-reviewed paper is a paper two or three busy people thought was probably worth publishing.**

---

## The evidence on error detection

Small studies, consistent direction.

| Study | Design | Result |
|---|---|---|
| **Godlee, Gale & Martyn (1998), JAMA** | Inserted 8 deliberate errors into a manuscript sent to 420 reviewers | Median errors found: **2 of 8** |
| **Baxt et al. (1998), *Annals of Emergency Medicine*** | Fabricated paper with 10 major and 13 minor errors sent to 203 reviewers | Mean major errors detected: **~3 of 10.** Only 68% recommended rejection of a paper describing a fictitious drug trial with fatal flaws |
| **Schroter et al. (2008), *Journal of the Royal Society of Medicine*** | 9 deliberate errors; also tested whether training helps | Reviewers found ~3 of 9. **Training produced small, short-lived improvement** |
| **Nuijten et al. (2016), "statcheck"** | Automated recomputation of reported statistics in 30,000+ psychology papers | Roughly **half of papers contained at least one inconsistent p-value**; ~13% had an error affecting the significance conclusion |

*(All of the error-insertion studies are small and in biomedicine. The
consistency of direction is more convincing than any one of them.)*

---

## Reviewer agreement is barely above chance

| Study | Finding |
|---|---|
| **Rothwell & Martyn (2000), *Brain*** | Agreement between reviewers on submissions to two neuroscience journals was **close to what chance would produce** |
| **Cicchetti (1991), *Behavioral and Brain Sciences*** | Review of the literature: inter-reviewer reliability typically κ ≈ 0.2-0.3. **Agreement on rejection is higher than agreement on acceptance** |
| **Peters & Ceci (1982)** | Took 12 papers already published in prestigious psychology journals, changed the author names and affiliations to fictitious low-prestige institutions, and resubmitted to the same journals. **3 were detected as resubmissions. Of the remaining 9, 8 were rejected** — mostly on "serious methodological flaws" |
| **NIH grant review — Pier et al. (2018), PNAS** | 43 experienced reviewers in simulated study sections scored the same 25 R01 applications. **No agreement beyond chance** on which were meritorious |
| **Fang, Bowen & Casadevall (2016), eLife** | NIH percentile scores did not predict subsequent productivity or citation impact among funded grants | 

**The Peters & Ceci result is the one to remember**, and its interpretation is
contested: it may show prestige bias, or it may show that review is so noisy
that any given paper's acceptance is close to a coin flip. **Both readings are
bad.**

---

## The fraud record

**Every major fraud in modern science was caught by someone other than a
referee.** This is not a selective sample; I cannot think of a counterexample.

| Case | What | Who caught it |
|---|---|---|
| **Jan Hendrik Schön** (Bell Labs, 2000-2002) | Fabricated data on organic semiconductors and molecular transistors; at his peak, a paper every eight days in *Science*, *Nature*, *PRL* | Outside physicists (Lydia Sohn, Paul McEuen) noticed **identical noise traces** in graphs from supposedly different experiments. The Beasley Committee found misconduct in 16 of 24 allegations; 28+ retractions |
| **Diederik Stapel** (Tilburg, exposed 2011) | Fabricated entire datasets across social psychology; 58 retractions | **Junior researchers in his own group**, who risked their careers. The Levelt Committee report noted "a general culture of careless, selective and uncritical handling of research and data" — indicting the field, not just the man |
| **Hwang Woo-suk** (Seoul, 2005) | Fabricated human embryonic stem cell lines; *Science* papers 2004-05 | Anonymous tips and image analysis by Korean researchers online |
| **Anil Potti** (Duke, 2006-2015) | Genomic predictors of chemotherapy response — **patients were enrolled in trials on the basis of fabricated signatures** | Keith Baggerly and Kevin Coombes, biostatisticians at MD Anderson, doing forensic reanalysis. They published concerns in 2009. **It took years to be acted on** |
| **Brian Wansink** (Cornell, 2018) | Food psychology; 18 retractions. His own blog post described instructing a student to keep slicing data until something emerged; emails later showed explicit p-hacking direction | Bloggers and Data Colada, starting from the blog post |
| **Sylvain Lesné** (Minnesota; 2006 *Nature* paper on Aβ*56) | Image manipulation in an influential Alzheimer's paper; retracted 2024 | Matthew Schrag, a neuroscientist doing image forensics, reported by Charles Piller in *Science* (2022). **Note: the popular claim that "16 years of Alzheimer's research rested on fraud" is false.** The amyloid hypothesis long predates and does not depend on that paper |
| **Francesca Gino** (Harvard, 2023) | Alleged data fabrication in honesty research — *itself* about dishonesty | Data Colada (Simonsohn, Simmons, Nelson). She sued them; **the litigation risk of post-publication criticism is a real and underrated chilling force** |
| **Dan Ariely** | The 2012 "sign at the top" insurance-honesty paper contained fabricated data (documented via Excel font analysis of the original file) | Data Colada. Responsibility for the fabrication remains disputed |

**Pattern:** image forensics, statistical forensics, duplicated noise, impossible
distributions, and whistleblowing juniors. **Not referees.** Referees see a
narrative; fraud lives in the data they never receive.

---

## Retraction Watch and the numbers

Founded 2010 by Ivan Oransky and Adam Marcus. The Retraction Watch Database was
acquired by Crossref in 2023 and made open — a genuinely important
infrastructure event.

- Historical retraction rate: roughly **0.02-0.1% of papers**, rising.
- **2023 saw over 10,000 retractions**, a record — dominated by ~8,000 from Hindawi special issues, i.e. **paper-mill contamination, not a surge in ordinary error**.
- **Fang, Steen & Casadevall (2012), PNAS**: of 2,047 retracted biomedical papers, **67.4% were attributable to misconduct** (fraud or suspected fraud 43.4%, duplicate publication 14.2%, plagiarism 9.8%), and only 21.3% to honest error. **The prior assumption that most retractions are honest error is wrong.**
- **Paper mills** now produce industrial volumes of fabricated manuscripts. Cabanac, Labbé and Magazinov (2021) detected them via "tortured phrases" — paraphrasing software turning "breast cancer" into "bosom peril," "artificial intelligence" into "counterfeit consciousness."
- **Retracted papers keep being cited**, often positively, for years afterward. The correction does not propagate.

---

## The economics

**The business model is extraordinary and worth stating plainly.** Public
funding pays for the research. Academics write the papers for free. Academics
review them for free. Academics edit for free. **Publishers then sell the result
back to the institutions that produced it**, or charge article processing
charges of $2,000-$11,000.

- Elsevier's operating margins have run around 35-40% — higher than most of the technology sector.
- Kovanis et al. (2016) estimated the peer review effort at roughly **63 million hours per year**, with the top 5% of reviewers doing about 19 million of them. **Unpaid.**
- The 2012 "Cost of Knowledge" boycott (initiated by Tim Gowers) gathered thousands of signatures and did not change much.
- The University of California cancelled its Elsevier subscription in 2019 and settled in 2021.
- **Sci-Hub** (Alexandra Elbakyan, 2011) is illegal, is used heavily by researchers at institutions that hold subscriptions, and is best read as a symptom.

**The steelman for publishers**, which is not nothing: they run submission
infrastructure at scale, maintain the version of record, handle indexing,
archiving and DOI persistence, and coordinate an enormous distributed process.
Those services have real costs. **They do not have 40%-margin costs.**

---

## Preprints

arXiv (Paul Ginsparg, 1991) has been the default in physics and mathematics for
thirty years. bioRxiv (2013) and medRxiv (2019) extended it.

**The evidence from physics is the most useful thing here:** a field has run
without pre-publication gatekeeping as its primary distribution channel for
three decades and **has not collapsed into noise.** Quality control moved to
post-publication reputation and community filtering, and it works — in a field
with strong theory, a small number of people who can evaluate any given claim,
and severe reputational costs for being wrong.

**COVID was the stress test and produced both results at once.** Preprints
enabled genomic sequences, variant surveillance and vaccine data to circulate in
days. They also enabled the hydroxychloroquine and ivermectin literature,
including fabricated studies (the Elgazzar ivermectin preprint, withdrawn after
a medical student found duplicated patient records) that shaped policy in
several countries before withdrawal. **And traditional peer review failed
symmetrically:** the Surgisphere affair (May 2020) put a fabricated
multinational database into *The Lancet* and *NEJM*, halting WHO trial arms,
before retraction within a month.

**Conclusion: the failure mode is not "preprints versus peer review." It is
speed under political pressure with no verification layer in either channel.**

---

## Steelmanning the defenders of peer review

The strongest case, stated properly:

- **The counterfactual is not "perfect verification." It is "nothing."** Journals without review fill with promotional material and error. The comparison class matters.
- **Reviewers do improve papers**, and authors know it. Surveys consistently find authors saying review made their manuscript better, which is weak evidence but is evidence.
- **Fields with pre-publication review have not obviously produced worse literature than physics.** Correlation with field norms confounds everything.
- **Bohannon's 2013 *Science* sting** — 157 of 304 open-access journals accepted a fatally flawed cancer paper — is usually cited against review. **It had no control arm of subscription journals**, a flaw this notebook is obliged to name given how often it makes the same complaint about the Sokal and grievance-studies hoaxes. It shows predatory publishing is real; it shows nothing comparative.
- **The reforms are working where tried.** Registered Reports move review to *before* the results exist, which fixes the deepest problem — reviewers evaluating conclusions rather than design.

---

## Where the popular story is wrong

| Popular belief | Reality |
|---|---|
| "Peer reviewed means verified" | It means two or three unpaid people read a narrative once, without the data. It is a filter, not a proof |
| "Peer review is how science has always worked" | *Nature* adopted it in 1973. Einstein's 1905 papers were not peer reviewed |
| "Peer review catches fraud" | It catches essentially none. Every major case was caught by outsiders doing forensics |
| "Preprints are dangerous, journals are safe" | The Surgisphere papers passed *Lancet* and *NEJM* review. The worst COVID misinformation came from both channels |
| "Reviewers are experts on the paper" | Often they are experts on the general area, given a paper using methods they cannot evaluate, on a deadline, for free |
| "Retractions mean the system works" | Retractions are ~0.1% of papers and mostly misconduct. Erroneous papers usually just sit there and keep getting cited |
| "Predatory journals are the problem" | They are a symptom. The problem is that publication count is the currency, so a market for publications exists |
| "Double-blind review removes bias" | It reduces some, and in specialised fields authors are often identifiable from the citations and methods anyway. Evidence of effect is mixed |

---

## Open questions

- [ ] Does peer review improve papers enough to justify ~63 million hours a year? **Nobody has attempted the cost-benefit calculation seriously.**
- [ ] Would open (signed) review improve or degrade candour? *BMJ* has used it for years; the evidence on quality is mixed and on reviewer willingness is negative.
- [ ] Can automated checks (statcheck, image forensics, GRIM/SPRITE tests) do at scale what referees cannot? Early evidence is very promising and adoption is slow.
- [ ] What is the undetected fraud rate? Unknowable by construction. Anonymous surveys suggest ~2% admit to fabrication and ~34% to questionable practices (Fanelli, 2009 meta-analysis) — **self-report on a question with career-ending consequences, so treat as a floor.**
- [ ] Does the physics preprint model transfer to fields with weaker theory and larger communities, or does it depend on conditions that don't generalise?
- [ ] How much does the litigation risk demonstrated by the Gino case suppress post-publication criticism? **This may be the most consequential recent development in the file and it is too new to assess.**
