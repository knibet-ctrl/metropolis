# Institutions of Knowledge — The Incentive Structures

> **Status: Tier 1 that metrics distort behaviour; Tier 1 that publication bias
> is severe; Tier 2 on nearly every proposed fix, because almost none have been
> tested at scale.** This is the file where the notebook's organising principle
> does most of its work: **knowledge production tracks the incentive structure,
> not the intentions of the people inside it.**

---

## The core mechanism: Goodhart, everywhere

**Goodhart (1975), on monetary policy:** "Any observed statistical regularity
will tend to collapse once pressure is placed upon it for control purposes."

**Strathern's (1997) compression, which is the version everyone quotes:** "When
a measure becomes a target, it ceases to be a good measure."

**Campbell's law (Donald Campbell, 1979) is the more precise social-science
statement and deserves to be better known:** the more any quantitative social
indicator is used for social decision-making, the more it will be subject to
corruption pressures and the more apt it will be to distort and corrupt the
processes it was intended to monitor.

**Applied to science:**

| Metric | Intended proxy for | What it actually selects for |
|---|---|---|
| **Publication count** | Productivity | Salami-slicing, least-publishable-units, gift authorship, paper mills |
| **Citation count** | Influence | Self-citation, citation cartels, review articles, controversy. Retracted papers keep accruing citations |
| **h-index** (Hirsch, 2005, PNAS) | Sustained impact | Rewards a mid-career profile shape; punishes one enormous contribution; strongly field- and age-dependent. **Hirsch himself published a paper in 2020 arguing it can fail badly and had unintended consequences** |
| **Journal impact factor** (Garfield) | Article quality | Was built for librarians choosing subscriptions. **Garfield explicitly warned against using it to evaluate individuals.** Distributions are so skewed that the median paper in a high-IF journal gets far fewer citations than the IF |
| **Grant income** | Research capacity | Rewards expensive research over cheap research, regardless of value per pound |
| **Novelty** | Discovery | Punishes replication, null results, and confirmation of others' work |

**DORA** (the San Francisco Declaration on Research Assessment, 2012) asked
institutions to stop using impact factor for individual assessment. Thousands of
signatories. **Behaviour has changed slowly and unevenly** — because the
underlying problem is that hiring committees need a cheap comparable number, and
DORA does not supply one.

---

## Publication bias, quantified

The best single demonstration, worth memorising:

**Turner et al. (2008), *NEJM*.** Antidepressant trials registered with the FDA
— so the *complete* set is known, including the unpublished ones.

| FDA verdict | Published? | How framed |
|---|---|---|
| Positive (38 trials) | **37 published** | As positive |
| Negative or questionable (36 trials) | **22 never published**; 11 published | The 11 published were framed as positive |

**Result: the published literature showed an effect size roughly a third larger
than the complete evidence base.** No individual fabricated anything.

**Supporting evidence:**
- **Fanelli (2010)** found that ~85-90% of published papers reported positive results, rising over time, and varying substantially by country and discipline.
- **ClinicalTrials.gov reporting compliance** remains poor — a large fraction of registered trials never post results despite legal requirements (FDAAA), and enforcement has been minimal.
- **AllTrials** (Ben Goldacre and colleagues, 2013) campaigned for retrospective as well as prospective registration. Partial success.
- **Registered Reports** produce positive-result rates around 44% against ~96% in the standard literature (Scheel et al., 2021). **That gap is the size of the bias.**

---

## The funding system

**How it works:** researchers write applications; panels of peers score them;
money flows to the top few percent.

**What the evidence says about whether it identifies good science:**

| Finding | Source |
|---|---|
| **Panel scores show essentially no agreement.** 43 experienced reviewers scoring the same 25 NIH R01 applications in simulated study sections produced no better-than-chance concordance on merit | Pier et al. (2018), PNAS |
| **Scores don't predict output above the funding line.** NIH percentile rankings among funded grants did not predict subsequent publications or citations | Fang, Bowen & Casadevall (2016), eLife |
| **The application burden is enormous.** Australian NHMRC applicants were estimated to have spent roughly 550 working years of researcher time preparing one funding round's applications | Herbert et al. (2013), BMJ Open |
| **Success rates around 20% or lower** mean most of that effort produces nothing | NIH, ERC, national councils |

**The implication is uncomfortable and I think it is correct: for applications
above a competence threshold, the funding process is close to a lottery with a
very expensive ticket-purchasing procedure attached.**

**Which raises the obvious proposal — run an actual lottery** above a quality
bar. The New Zealand Health Research Council and the Volkswagen Foundation have
run partial randomisation schemes. **Tier 3: promising, small, unevaluated at
scale.** The objections are mostly about legitimacy rather than efficiency,
which tells you something.

**The second-order effect is worse than the first.** A ~20% success rate with
noisy selection means researchers optimise for *fundability*: incremental
proposals, work already substantially done before the grant is written,
fashionable topics, and senior-name-attached applications. **The system selects
against the risky work it claims to want.**

---

## Why nobody replicates

| Fact | Source |
|---|---|
| Replications were **~1.07% of psychology publications** from 1900 to 2012, and most were conducted by the original authors | Makel, Plucker & Hegarty (2012) |
| Dedicated replication funding is almost nonexistent; the Dutch NWO Replication Studies programme (from 2016) is the notable exception | |
| Journals for negative results largely failed commercially. *Journal of Negative Results in BioMedicine* closed in 2017 | |
| Preclinical cancer replication was blocked by unavailable protocols: **not one of 193 experiments in the Reproducibility Project could be repeated from the published methods alone**, and roughly a third of original authors were unhelpful or unresponsive | RP:CB (2021), eLife |

**The negative-results-journal failure is the cleanest natural experiment in the
file.** The venue existed. Nobody submitted. **The constraint is not
publication opportunity; it is that no career is advanced by filling it.**

---

## The natural selection of bad science

**Smaldino & McElreath (2016), *Royal Society Open Science*.** The best formal
account of the whole problem.

Model laboratories as reproducing entities: a lab's "fitness" is its publication
output; students inherit their advisor's methods; labs with lower methodological
standards (lower power, more flexible analysis) publish more; those methods
spread through the population.

**The result: methodological rigour declines over time under selection for
publication volume, with no dishonesty and no bad actors anywhere in the
model.** The paper pairs this with the empirical observation that statistical
power in the social and behavioural sciences **did not improve from 1960 to
2011** despite continuous published warnings.

**This is the theoretical core of the entire notebook.** It explains the
fifty-year gap between Sterling's 1959 warning and the 2011 reforms without
appealing to anyone's character.

---

## Universities

**The Humboldt model** (Berlin, 1810) fused teaching and research and made the
professor a researcher rather than a transmitter. It is the single most
consequential institutional design in the history of knowledge, and every
university on earth is a variation on it.

**What has changed, and the direction is consistent:**
- **Massification.** Vastly more PhDs than permanent research positions. A structural oversupply produces a tournament, and tournaments are won on measurable output.
- **Administrative growth and audit culture.** REF in the UK, tenure metrics in the US, national ranking systems. Campbell's law applies directly.
- **Casualisation.** Postdocs and adjuncts on short contracts cannot take multi-year risks. **The people best placed to do original work have the least security to do it.**
- **The publish-or-perish tournament creates exactly the selection pressure Smaldino and McElreath modelled.**

**The steelman**, and it is substantial: this system has produced more knowledge,
faster, than any previous arrangement, and its outputs — from mRNA vaccines to
transformer architectures to the CRISPR toolkit — are real. **Criticism of the
incentives should not be read as a claim that the enterprise fails.** It
doesn't. It underperforms, and the underperformance is measurable.

---

## Patents and the ownership of knowledge

| Point | Status |
|---|---|
| **The economic case for patents** — temporary monopoly buys disclosure and funds fixed R&D costs — is strongest in pharmaceuticals, where development costs are enormous and imitation is trivial | **Tier 2, decent evidence in pharma** |
| **The case is much weaker in software and business methods**, where fixed costs are lower and patent thickets impose real costs | **Tier 2** |
| **Anticommons.** Heller & Eisenberg (1998, *Science*) argued that fragmented upstream patents on research inputs can block downstream innovation | **Tier 2, mechanism plausible, magnitude disputed** |
| **Gene patents.** Myriad Genetics held BRCA1/BRCA2 patents and used them to block competing diagnostic tests. Invalidated by the US Supreme Court in *AMP v. Myriad* (2013) | **Tier 1 on the facts** |
| **Bayh-Dole (1980)** let US universities patent federally funded research. Credited with technology transfer; criticised for pushing universities toward commercialisable work and secrecy | **Genuinely contested. Both effects are real** |
| **The strong sceptical case** — Boldrin & Levine, *Against Intellectual Monopoly* (2008) — argues patents have no demonstrable net positive effect on innovation | **Tier 2/3. A minority position held by serious economists** |

**The honest answer is that the empirical literature on patents and innovation
is genuinely mixed and heavily dependent on industry and on the specification
chosen.** Anyone confident in either direction is overreaching.

---

## Is science slowing down?

Two findings that point the same way, and both have caveats.

**Bloom, Jones, Van Reenen & Webb (2020), *American Economic Review*, "Are Ideas
Getting Harder to Find?"** Research productivity — output per researcher — is
falling sharply across many domains. Sustaining Moore's law requires roughly 18
times the researchers it did in the early 1970s. Similar patterns in
agricultural yields and medical research. **Reasonably robust; the
interpretation (low-hanging fruit exhausted, versus institutional decay) is
not.**

**Park, Leahey & Funk (2023), *Nature*, "Papers and patents are becoming less
disruptive over time."** The CD index — whether a paper's citers go on to cite
its predecessors, or replace them — declined steeply across all fields from
1945 to 2010. *(Contested. Subsequent critiques argue the CD index is sensitive
to changes in citation practice and reference-list length, and that the decline
is partly an artefact. Treat as unresolved.)*

**Supporting circumstantial evidence:** Nobel-winning work is being done at
progressively older ages (Jones & Weinberg); the burden of knowledge before you
can contribute keeps growing; team sizes keep growing while per-author
contribution shrinks.

**Steelman for "nothing is wrong":** absolute output of important results is
higher than ever; the productivity denominator is inflated by counting anyone
with a research job; and mRNA vaccines, CRISPR, LIGO, AlphaFold and the
transformer all arrived in fifteen years. **Both stories fit the data.**

---

## The Matthew and Matilda effects

- **Matthew effect** (Merton, 1968): recognition accrues to the already-recognised. The same result gets more credit with a famous name on it. Merton later credited Harriet Zuckerman as effectively a co-author of the work, a small correction of the very phenomenon he described.
- **Matilda effect** (Margaret Rossiter, 1993): women's contributions systematically attributed to male colleagues. Lise Meitner and the 1944 chemistry Nobel; Jocelyn Bell Burnell and the 1974 physics Nobel for pulsars.
- **Rosalind Franklin is the standard example and the popular version is wrong.** Cobb and Comfort (*Nature*, 2023) argued from archival evidence that Franklin was an equal contributor working in known collaboration rather than a victim of simple theft, and that she knew her data were being used. **The correction is more interesting than the myth, and this notebook has an obligation to prefer it.**

**Why this belongs in an institutions file rather than a fairness file:**
misallocated credit is an *information* failure. If credit doesn't track
contribution, the signal that funders, hiring committees and students use to
allocate effort is corrupted.

---

## The control group — when the institutions produced harm

Four cases where the full apparatus worked as designed: funding, peer review,
professional societies, prizes, regulation. **The output was wrong, and in three
of the four the wrongness was lethal.**

### Thalidomide (1957-1961)

Chemie Grünenthal marketed thalidomide as a sedative and anti-emetic, including
for morning sickness. **Roughly 10,000 infants were born with phocomelia and
related malformations**; survival was around 50%. Widukind Lenz in Germany and
William McBride in Australia independently identified the association in 1961;
the drug was withdrawn that year. Frances Oldham Kelsey at the FDA had refused
US approval on grounds of inadequate safety data and was later given a
presidential award.

**What it changed:** the 1962 Kefauver-Harris Amendments in the US, requiring
proof of *efficacy* as well as safety and informed consent in trials; the
modern regulatory apparatus of pharmacovigilance descends directly from this.
**The system was reformed by a catastrophe, not by argument.**

**Two details usually omitted.** Thalidomide was not a rogue product of a
fringe operation; it passed the standards of its time, which simply did not
require teratogenicity testing. And **William McBride, one of the men who
identified it, was later struck off the medical register for falsifying data in
an unrelated drug study.** Being right once does not certify anyone.

### Dietary fat, sugar, and how the revisionist story is also wrong

**The mainstream account (roughly 1960-2000):** saturated fat raises serum
cholesterol, which causes heart disease; reduce fat, replace with
carbohydrate. Institutionalised in US dietary guidelines from 1980. Fat intake
fell; obesity and type 2 diabetes rose sharply.

**The documented industry capture is real.** Kearns, Schmidt & Glantz (2016,
*JAMA Internal Medicine*) recovered correspondence showing the Sugar Research
Foundation paid Harvard researchers — Hegsted, McGandy and Stare — to produce a
1967 *NEJM* review that minimised sugar's role and emphasised fat. **The funding
was not disclosed, which was permitted at the time.**

**The re-analyses are also real.** Ramsden et al. recovered unpublished data
from the Minnesota Coronary Experiment (*BMJ*, 2016) and the Sydney Diet Heart
Study (2013). Replacing saturated fat with linoleic acid lowered serum
cholesterol as predicted **and did not reduce mortality** — in the Minnesota
data, mortality was higher in the intervention group among older participants.
**The unpublished data had sat in a basement for forty years.** This is the
file-drawer problem with a body count.

**And now the correction to the correction, which is the part popular
retellings drop.** The revisionist account (Taubes, Teicholz) is itself
overstated:
- The widely repeated claim that Ancel Keys **cherry-picked 7 of 22 countries** conflates two different things: a 1953 illustrative graph, and the Seven Countries Study, a prospective cohort designed around those countries for logistic and collaborative reasons. **Keys was not a fraud, and repeating that he was is the same error in the other direction.**
- Trans fats — a *consequence* of the shift away from saturated fat — turned out to be genuinely harmful, which is a real indictment. But the specific claim that dietary guidelines caused the obesity epidemic is an ecological inference, not a demonstrated one.
- **The current state is genuinely unresolved.** *(Contested: replacing saturated fat with polyunsaturated fat has reasonable trial support; replacing it with refined carbohydrate does not. Nutritional epidemiology remains the least reliable major field in this notebook.)*

**The institutional lesson:** guidelines were issued for a population of
hundreds of millions on evidence that could not bear the weight, by committees
under political pressure to say something actionable, with industry funding
undisclosed and negative trials unpublished. **Every mechanism in this file,
operating at once.**

### Eugenics — the pure case

Galton coined the term in 1883. By 1910 it had the Eugenics Record Office at
Cold Spring Harbor under Charles Davenport, funding from the Carnegie
Institution and the Rockefeller Foundation, university chairs, dedicated
journals, and the support of leading statisticians — **Karl Pearson and R. A.
Fisher, who between them built much of modern statistics.** *Buck v. Bell*
(1927) upheld compulsory sterilisation 8-1, Oliver Wendell Holmes writing
"three generations of imbeciles are enough." Roughly 60,000 forced
sterilisations followed in the US; Sweden performed around 63,000 between 1935
and 1975.

**This was not fringe science captured by politics. It was mainstream science
supplying the politics.** Peer review, professional societies, elite
universities and philanthropic funding all functioned normally. **Nothing in
the institutional machinery of science detects a moral catastrophe, because
the machinery does not evaluate ends.**

### The lobotomy Nobel

António Egas Moniz received the 1949 Nobel Prize in Physiology or Medicine for
"the therapeutic value of leucotomy in certain psychoses." Walter Freeman
industrialised the transorbital version in the US; on the order of 40,000-50,000
procedures were performed there, including on Rosemary Kennedy in 1941.

**The steelman, which is necessary:** the alternative for a patient with severe
psychosis in 1945 was indefinite institutional confinement, and chlorpromazine
did not arrive until 1952. Physicians were not choosing between lobotomy and
something better; they were choosing between lobotomy and nothing.

**What is not defensible is the evidence base.** Freeman's follow-up assessments
were conducted by Freeman, on his own patients, with outcome criteria he
selected, and "improvement" frequently meant "more manageable on the ward."
**There was no control group, no blinding, and no independent assessment — and
the Nobel Committee awarded the prize anyway.** It has never been rescinded,
and the Nobel Foundation's position is that prizes are not revoked.

**The common thread across all four:** in each case the *procedural* markers of
good science were present and the *structural* check — an independent party
with an incentive to find the error — was absent.

---

## Steelmanning the current system

The strongest defence, which critics of science-as-institution rarely state:

- **It works.** Compare any measurable output of institutional science to any alternative knowledge system on any dimension where both make checkable claims. This is not close.
- **The metrics exist because the alternative is worse.** Before bibliometrics, allocation ran on patronage, personal networks and institutional prestige — which was more biased, less transparent and unappealable. **Goodhart's law is a real cost of a real improvement.**
- **The critics use the system's own products.** Every number in this file comes from institutional science measuring itself and publishing the result. **A system that funds, publishes and promotes its own critics is doing something right**, and no comparably self-critical alternative exists.
- **Reform is happening.** Registered Reports, data mandates, DORA, open access, retraction infrastructure, replication consortia — all within about fifteen years.
- **The counterfactual for open science is not utopia.** Weakening gatekeeping produces paper mills; strengthening it produces conservatism. **There is no configuration without a failure mode**, and the reasonable goal is choosing which failure mode you prefer.

---

## Where the popular story is wrong

| Popular belief | Reality |
|---|---|
| "90% of papers are never cited" | **A myth.** Uncited rates vary enormously by field; in medicine roughly 10-15% are uncited after five years. The real finding is skew — a small fraction of papers gets most citations (Seglen) |
| "Impact factor measures paper quality" | It is a journal-level mean of a wildly skewed distribution, designed for librarians, and its creator warned against this use |
| "Scientists are motivated by truth" | Mostly, and also by rent, tenure, students, grants and status — like everyone. **Systems that assume virtue fail; systems that price incentives work** |
| "Open access fixes the problem" | It moved the payment from reader to author, which created an incentive to accept more papers. Paper mills are a direct consequence |
| "Predatory journals are the disease" | They are the symptom of publication-count currency |
| "More funding produces more discovery" | Bloom et al. suggests sharply diminishing returns per researcher. The relationship is not linear |
| "Peer review of grants finds the best science" | Panels don't agree with each other and their scores don't predict output above the line |
| "Universities are ivory towers detached from money" | Bayh-Dole, patent offices, industry sponsorship and the tuition market make them intensely commercial. Whether that is good is contested; that it is true is not |
| "Rosalind Franklin's data were stolen" | The archival record is more complicated and the correction is well documented |

---

## Open questions

- [ ] Would funding lotteries above a quality bar outperform panels? Two small programmes exist. **This is the highest-value untested reform in the notebook.**
- [ ] Is the disruptiveness decline real or a citation-practice artefact? Load-bearing for the "science is slowing" claim and currently unresolved.
- [ ] Can a metric be designed that resists Goodhart? The pessimistic answer — that any metric under pressure becomes a target — may simply be right, in which case the fix is periodic metric replacement rather than a better metric.
- [ ] What fraction of published output is now paper-mill product? Estimates of 2%+ of submissions circulate; the true figure is unknown and rising.
- [ ] Does casualisation measurably reduce risk-taking in research? Widely asserted, plausible, poorly measured.
- [ ] What is the counterfactual value of the ~63 million annual hours of unpaid peer review if spent on replication instead? Nobody has modelled it.
- [ ] Would mandatory publication of all registered trial results, actually enforced, change clinical practice measurably? The Turner et al. result implies yes, substantially. **It has not been enforced, which is itself the finding.**
