# The Replication Crisis

> **Status: Tier 1 that it happened and Tier 1 on the mechanisms. Tier 2 on
> scope, severity, and whether the reforms are working.** The replication rates
> below are real measurements from real projects. What they *mean* — how many
> failures are false originals versus flawed replications — is genuinely
> disputed and this file says so where it applies.

---

## The single most important fact

**It was not a discovery. It was a re-discovery, roughly fifty years late.**

| Year | Warning | Effect |
|---|---|---|
| 1959 | **Sterling**: 97% of papers in four psychology journals reported significant results. Statistically impossible under honest practice | None |
| 1962 | **Cohen**: median statistical power in abnormal/social psychology was ~0.48 for medium effects | None |
| 1967, 1978 | **Meehl**: "Theoretical risks and tabular asterisks." Argued that in soft psychology, null-hypothesis testing plus the "crud factor" (everything correlates with everything a bit) means significance tests carry almost no information | None |
| 1979 | **Rosenthal**: names the file-drawer problem, proposes the fail-safe N | Cited constantly, changed nothing |
| 1995 | **Sterling, Rosenbaum & Weinkam**: re-ran the 1959 analysis. Nothing had changed in 35 years | None |
| 2005 | **Ioannidis**: "Why Most Published Research Findings Are False" | Enormous attention, no immediate reform |
| 2011 | **Simmons, Nelson & Simonsohn**: "False-Positive Psychology" | **This one landed** |

**Conclusion: the failure was structural, not informational.** Everyone who
needed to know, knew. The behaviour changed only when the reputational cost of
publishing unreplicable work exceeded the career cost of doing rigorous work.

---

## Ioannidis 2005 — what the argument actually is

*PLoS Medicine*. Widely cited, widely misunderstood. **It is a modelling
argument, not a measurement.** The claim: the probability that a
statistically significant finding is true (its positive predictive value)
depends on three things:

1. **The pre-study odds** that the hypothesis is true,
2. **Statistical power** (probability of detecting a real effect),
3. **Bias** (analytic flexibility, selective reporting).

Work an example. Suppose 10% of tested hypotheses in a field are true, power is
0.3 *(realistic for social psychology)*, and α = 0.05. Test 1,000 hypotheses:
100 true, of which 30 are detected; 900 false, of which 45 are declared
significant. **Of 75 "significant" findings, 45 are false — 60%.** Add any
p-hacking and it gets worse. Nobody needs to cheat for this to happen.

**The corollaries people skip:**
- **Small effects plus small samples is the lethal combination**, not either alone.
- **More teams working on the same question makes it worse**, not better, if only positive results publish.
- **Hot fields are more corrupted**, not less.
- **"Underpowered" and "biased" are not separate problems.** Low power inflates the effect sizes of the studies that do reach significance (Ioannidis 2008, the winner's curse).

**The irony, which belongs in the file:** Ioannidis co-authored the Santa Clara
County COVID seroprevalence study (Bendavid et al., 2020), which was heavily
criticised for test-specificity assumptions and recruitment bias, and in March
2020 published a widely-quoted piece suggesting US deaths might be on the order
of 10,000. **The man who wrote the definitive paper on how findings go wrong
produced contested findings under the same pressures.** That is not a gotcha; it
is the strongest available evidence that the problem is structural rather than
about individual virtue.

---

## The mechanisms

| Mechanism | What it is | Evidence |
|---|---|---|
| **P-hacking** | Trying analyses until p < 0.05: dropping outliers, adding covariates, stopping data collection when significant, choosing among DVs | Simmons, Nelson & Simonsohn (2011) showed that four ordinary researcher degrees of freedom push the false-positive rate above 60%. They "demonstrated" that listening to *When I'm Sixty-Four* made participants 18 months younger |
| **HARKing** | Hypothesizing After the Results are Known — writing the paper as if the discovered pattern was predicted | Kerr (1998) named it. Surveys find a majority of researchers admit to some form |
| **Publication bias** | Null results don't get submitted or accepted | **Turner et al. (2008), NEJM** — the best single demonstration. Of FDA-registered antidepressant trials: 37 of 38 positive trials were published; of 36 negative or questionable trials, 22 were never published and 11 were published framed as positive |
| **The file drawer** | The unpublished nulls sitting in labs | Rosenthal (1979). Structurally unmeasurable, which is the point |
| **Low power** | Button et al. (2013): median power in neuroscience ~21% | Means most true effects are missed *and* most detected effects are inflated |
| **Analytic flexibility** | The "garden of forking paths" (Gelman & Loken) — no dishonesty required | **Silberzahn et al. (2018)**: 29 teams analysed the same football dataset asking whether referees give more red cards to darker-skinned players. Effect estimates ranged from 0.89 to 2.93; 20 of 29 found a significant effect, 9 did not. **Same data. Same question.** Botvinik-Nezer et al. (2020) found the same in fMRI with 70 teams |
| **Statistical software assumptions** | Eklund, Nichols & Knutsson (2016, PNAS): common fMRI cluster-inference methods had false positive rates up to 70% under some parameters. *(The authors walked back the widely-quoted "40,000 papers invalidated" framing.)* | |
| **Non-independent analysis** | Vul et al. (2009), "voodoo correlations": selecting voxels by correlation, then reporting that correlation | Inflated a chunk of the social-neuroscience literature |

**The natural-selection framing.** Smaldino & McElreath (2016), "The Natural
Selection of Bad Science": model labs as reproducing based on publication
output. Labs with lower methodological standards produce more papers, get more
students, and their methods spread. **No individual has to be dishonest for
rigour to decline.** They also showed statistical power in the social and
behavioural sciences did not improve between 1960 and 2011 despite continuous
warnings. This is the best single theoretical account of what happened.

---

## The measurements, by field

| Project | Field | Result |
|---|---|---|
| **Open Science Collaboration (2015), *Science*** | Psychology | 100 studies from three top journals; 97 originals were significant, **36% of replications were significant**; mean effect size roughly halved |
| **Many Labs 2 (Klein et al., 2018)** | Psychology | 28 classic findings, 60+ labs, ~15,000 participants; **14 of 28 replicated**. Notably, effects that replicated did so across cultures and settings — variation in effects was *not* explained by sample or setting |
| **Camerer et al. (2016), *Science*** | Experimental economics | **11 of 18 (61%)** |
| **Camerer et al. (2018), *Nature Human Behaviour*** | Social science papers in *Nature*/*Science*, 2010-2015 | **13 of 21 (62%)**, effect sizes ~50% of original. Prediction markets among researchers forecast which would fail with high accuracy — **the field knew** |
| **Reproducibility Project: Cancer Biology (2021), *eLife*** | Preclinical cancer | Attempted 53 papers, completed 23 (protocols often unobtainable; **not one of 193 experiments had a complete enough protocol to repeat without asking the authors, and roughly a third of authors were unhelpful or unresponsive**). Effect sizes ~85% smaller on average |
| **Begley & Ellis (2012), *Nature*** | Preclinical cancer (Amgen) | **6 of 53 "landmark" studies confirmed (11%).** *(Amgen never published the study identities or data. Widely cited; strictly unverifiable. Flagged as such.)* |
| **Prinz et al. (2011), Bayer** | Preclinical drug targets | ~20-25% reproducible |
| **Nature survey (2016)** | All fields, 1,576 researchers | 70% had failed to reproduce another scientist's experiment; over 50% had failed to reproduce their own; 52% said there was a "significant crisis" |

**Notice what is missing:** no comparable audit of physics, chemistry, geology
or most of engineering. **Whether they would fare better is a reasonable
assumption, not a measured fact.**

---

## Specific casualties

| Finding | Original | What happened |
|---|---|---|
| **Ego depletion** | Baumeister et al. (1998): self-control is a depletable resource | Carter & McCullough (2014) found severe publication bias in the meta-analysis. Hagger et al. (2016) Registered Replication Report: 23 labs, ~2,100 participants, **effect indistinguishable from zero.** The glucose-restoration version fared worse |
| **Power posing** | Carney, Cuddy & Yap (2010): expansive postures raise testosterone, lower cortisol, increase risk-taking | Ranehill et al. (2015, n≈200) found no hormonal or behavioural effects. **Dana Carney, the first author, publicly disavowed the effect in 2016** — an act of scientific integrity that deserves recording. Cuddy maintains a weaker "felt power" claim which has partial meta-analytic support and is contested by Simonsohn and Simmons |
| **Behavioural priming** | Bargh, Chen & Burrows (1996): priming "elderly" stereotype slowed walking speed | Doyen et al. (2012) failed to replicate and showed the effect appeared only when experimenters knew the condition — **experimenter expectancy, not priming.** Kahneman's 2012 open letter warned of a "train wreck looming." In 2017 he conceded he had placed too much faith in underpowered studies; **the priming chapter of *Thinking, Fast and Slow* should not be relied on, and its author said so** |
| **Stanford Prison Experiment** | Zimbardo (1971) | Not a controlled experiment; initially published largely outside peer review. Archives (Le Texier, 2019, *American Psychologist*; Blum's reporting) show guards were coached toward toughness; participant Douglas Korpi later said he faked his breakdown; only about a third of guards behaved cruelly; recruitment advertised for a study of "prison life," which self-selected (Carnahan & McFarland, 2007). The BBC Prison Study (Reicher & Haslam, 2006) got the opposite result. **Should not be cited as evidence of anything** |
| **Milgram obedience** | Milgram (1961-63) | **The behaviour is real and replicates** (Burger, 2009, ~70% to 150V). What collapsed is the interpretation. Gina Perry's archival work (*Behind the Shock Machine*, 2012) shows experimenters improvised far beyond the four scripted prods; many participants doubted the setup; the debriefing claims were misleading; and the famous 65% is one condition of 24, with obedience ranging from 0% to 92.5% across variations. Haslam & Reicher's "engaged followership" account — participants complying because they identified with a scientific project, not blindly obeying — fits the data better than "banality of evil" |
| **Facial feedback** | Strack et al. (1988): holding a pen in your teeth makes cartoons funnier | Wagenmakers et al. (2016), 17 labs: failed. *(Contested — Noah et al. argued the presence of a camera altered the effect, and later meta-analyses are mixed.)* |
| **Candidate gene studies** | ~1996-2015: 5-HTTLPR and depression, COMT and cognition, DRD4 and everything | **Border et al. (2019), *American Journal of Psychiatry***: tested the 18 most-studied candidate genes for depression in large samples. **Essentially no support for any of them.** Roughly two decades and thousands of papers, almost all false positives. **The most complete demolition of a literature in the file** |
| **Implicit Association Test** | Greenwald & Banaji (1998) | The measure exists; the claims made for it do not hold. Meta-analyses (Oswald et al. 2013; Forscher et al. 2019) find weak prediction of behaviour (r ≈ 0.1) and no evidence that shifting implicit measures shifts behaviour. Greenwald and Banaji have conceded it is unsuitable for individual diagnosis |
| **Growth mindset** | Dweck | Real but small. The National Study of Learning Mindsets (Yeager et al., 2019, *Nature*, n = 12,542) found effects around 0.1 GPA points, concentrated in lower-achieving students. Sisk et al. (2018) meta-analysis: small. **Not zero — and nowhere near the popularised claims** |

---

## Steelmanning the sceptics of the crisis

The strongest counter-case, and it is not weak:

**Gilbert, King, Pettigrew & Wilson (2016), *Science*.** They argued the Open
Science Collaboration's 36% dramatically understates reproducibility:
replications were often underpowered for the true (smaller) effect; many were
infidelities — different populations, different stimuli, one replication of a
US race-attitudes study run in Italy; and the OSC's own "protocol endorsed by
original author" subset replicated at a much higher rate. Anderson et al.
replied defending the design. *(My read: Gilbert et al. identified real
problems and their overall conclusion is not supported, because independent
projects using different designs converged on similar numbers. But the
criticism is legitimate and is usually ignored rather than answered.)*

**Two further points the sceptics have right:**
- **A failed replication is evidence, not proof.** Replications can be incompetent, underpowered, or performed on populations where the effect genuinely differs. Treating one failure as refutation repeats the original sin in reverse.
- **"Most published research is false" is not equivalent to "science doesn't work."** The findings that get built on — the ones with clinical or engineering consequences — face a second filter that the literature doesn't provide.

---

## What reforms have worked

**Preregistration. The evidence here is the strongest positive finding in the
notebook.**

| Reform | Evidence |
|---|---|
| **Trial registration (ClinicalTrials.gov, mandatory from 2000)** | **Kaplan & Irvin (2015), PLoS ONE**: large NHLBI cardiovascular trials reported significant benefit in 17 of 30 (57%) before 2000, and 2 of 25 (8%) after. **Nothing about the biology changed** |
| **Registered Reports** (peer review of the protocol before results exist; introduced at *Cortex* in 2013 by Chris Chambers) | Scheel, Schijen & Lakens (2021): positive-result rates around 44% in Registered Reports versus ~96% in the comparison literature. **This is what an unbiased literature looks like** |
| **Multi-lab replication consortia** | Many Labs, RRRs. Changed what counts as evidence for a contested effect |
| **Data and code sharing mandates** | Modest but real. Enabled the forensic work (Data Colada, Baggerly & Coombes) that catches fraud |
| **Larger samples / genome-wide thresholds** | The genetics fix. Human genetics went from a candidate-gene disaster to one of the more reliable empirical enterprises by adopting p < 5×10⁻⁸, consortium-scale samples, and mandatory replication cohorts. **The best existence proof that a field can repair itself** |
| **CONSORT, PRISMA, STROBE reporting standards** | Improved reporting quality measurably. Did not improve study quality much — reporting and doing are different |

**What has not worked, or not yet:**
- **Preregistration compliance is poor.** Claesen et al. (2021) examined 27 preregistered studies in *Psychological Science* and found only one with no undisclosed deviations. **Preregistration prevents hiding only if someone checks.**
- **Statistical education.** Fifty years of telling people about power did nothing (Smaldino & McElreath). Structural change worked; exhortation didn't.
- **Post-publication peer review.** PubPeer is valuable and tiny relative to output.
- **Replication funding.** Essentially nonexistent outside a few programmes (the Dutch NWO Replication Studies scheme). Makel, Plucker & Hegarty (2012) found replications made up ~1.07% of psychology publications since 1900, and most were by the original authors.
- **Journals dedicated to null results.** Almost all failed commercially. The *Journal of Negative Results in BioMedicine* closed in 2017. **A clean natural experiment: the problem is not the absence of a venue. It is that nobody's career benefits from filling it.**
- **The p-value wars.** Benjamin et al. (2018) proposed p < 0.005; Lakens et al. replied "justify your alpha"; Amrhein, Greenland & McShane (2019, *Nature*) called for retiring statistical significance entirely, with 800+ signatories. **Unresolved, and arguably a distraction from power and preregistration, which are the load-bearing issues.**

---

## Where the popular story is wrong

| Popular belief | Reality |
|---|---|
| "The replication crisis was discovered in 2011" | It was documented in 1959 and re-documented every decade since. What changed in 2011 was the incentive to care |
| "It's a psychology problem" | Preclinical cancer biology is worse. Nutrition epidemiology is worse. Psychology is the field that *measured* itself, which is why it looks bad |
| "Failed replication means the original was fraud" | Almost never. Low power plus flexible analysis plus selective publication produces false positives with everyone acting in good faith |
| "P-hacking is cheating" | Most of it is invisible from the inside. The garden of forking paths requires no forking decision to be conscious |
| "Bigger samples fix it" | Necessary, not sufficient. A large study of an implausible hypothesis with flexible analysis still fails. Priors and preregistration do more work |
| "Science is broken" | Fields with tight theory, precise instruments and cheap replication are largely fine. The crisis is concentrated where effects are small, measurement is noisy, and analysis is flexible. **That is a diagnosis, and it identifies the fix** |
| "Peer review should have caught this" | Reviewers see a narrative, not the data or the analysis history. Peer review cannot detect what is not in the manuscript |
| "The Stanford Prison Experiment shows situations override character" | It shows what happens when an experimenter tells participants what he wants and self-selected volunteers oblige |

---

## Open questions

- [ ] What is the replication rate in chemistry, materials science, and experimental physics? **Nobody has run the audit.** This is the single largest gap.
- [ ] Do the reforms transfer? Registered Reports work where the design is fixable in advance. What replaces them for exploratory and observational work?
- [ ] How much of the effect-size shrinkage in replications is regression to the mean versus genuine falsity? Bayesian analyses disagree.
- [ ] Is Gilbert et al.'s critique of the OSC more right than the field concedes? I lean no, but the argument was answered by assertion more than by data.
- [ ] Has the crisis produced net benefit, or merely a new set of gameable rituals? Preregistration is already being performed rather than practised in places.
- [ ] Machine-learning research has almost none of these safeguards, enormous analytic flexibility, and benchmark-chasing incentives. **Nobody has audited it. The prediction is obvious and the test has not been run.**
