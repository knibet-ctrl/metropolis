# What Shapes A Person — The Three-Way Partition

> **Status: TIER 1** on the variance decomposition results themselves.
> **TIER 2** on what they mean. **TIER 3** on the mechanisms proposed for the
> non-shared residual.

> **Written from general knowledge with no live source verification.** Variance
> components are indicative and vary substantially by sample, age and measure.

> **Read the-questions.md first.** Everything in this file is an answer to
> Question 1 — what makes people differ from each other — and is routinely
> misreported as an answer to Questions 2, 3 and 5.

---

## The partition

Behavioural genetics decomposes observed variance into three components:

| Component | Symbol | What it is | What people assume it is |
|---|---|---|---|
| **Additive genetic** | A | Variance tracking genetic differences | "Innate", "fixed" — neither is implied |
| **Shared environment** | C | Everything that makes siblings raised together *more alike*: household, neighbourhood, parental style, income, religion, school | "Parenting" — but it is much broader, and it is only the *shared* part |
| **Non-shared environment** | E | Everything that makes siblings raised together *different*, **plus all measurement error** | "Peers" or "unique experiences" — but it is a residual, not a discovery |

**The single most important structural point in this file: E is a residual
term.** It is what is left over. It includes measurement error, test-retest
unreliability, developmental noise, illness, accident, differential prenatal
environment, and any real systematic cause nobody measured. Calling it
"non-shared environment" gives a leftover the grammar of a mechanism.

---

## The numbers, by trait and age

Approximate, Western samples, adult outcomes unless stated. Ranges are wide
across studies; treat these as orders of magnitude.

| Trait | A | C | E (incl. error) | Notes |
|---|---|---|---|---|
| Height | ~0.80 | ~0.05 | ~0.15 | C rises sharply where nutrition varies |
| Adult IQ | 0.60-0.80 | ~0.00-0.10 | 0.20-0.30 | C is substantial (~0.25) in childhood and falls to ~0 by adulthood |
| Child IQ (age 5-7) | 0.20-0.40 | 0.25-0.35 | ~0.35 | The Wilson effect in action |
| Big Five personality | 0.35-0.50 | ~0.00-0.05 | 0.50-0.60 | Self-report reliability caps this; **the flagship "C ≈ 0" result** |
| Schizophrenia | 0.65-0.80 | small | remainder | Hilker et al. (2018), Danish twins: ~79% |
| Autism | 0.60-0.90 | small | remainder | Tick et al. (2016) meta-analysis; Sandin et al. (2017) Swedish cohort ~83% |
| Major depression | ~0.35-0.40 | small | large | Lower than most psychiatric conditions |
| Educational attainment | 0.40 | **0.15-0.35** | remainder | **C is clearly non-zero here** |
| Income / wealth | 0.30-0.50 | **large** | remainder | Wealth transmission is overwhelmingly environmental |
| Religiosity (adult affiliation) | small | **large** | remainder | Denomination is almost entirely C |
| Political orientation | 0.30-0.40 | **0.20-0.30** | remainder | Contested but consistently non-zero C |
| Smoking / drinking **initiation** | small | **large** | remainder | C large for starting, A large for progressing to dependence |
| Delinquency in adolescence | moderate | **substantial** | remainder | C falls away in adulthood |
| Attachment security in infancy | **~0.00** | **~0.50** | ~0.50 | Bokhorst et al. (2003); Roisman & Fraley (2008). **A genuine counterexample to "everything is heritable"** |

**Read the bold entries.** The claim "shared environment doesn't matter" is
sustainable only for personality inventories and adult IQ. For religion,
politics, education, money, substance initiation and infant attachment, the
family environment is a major term. The popular version of this literature
generalised a result from two outcome families to all of human development.

---

## The surprising finding, stated precisely

**In typical Western samples, growing up in the same household does not make
two people meaningfully more similar in adult personality or adult cognitive
ability than two people picked at random.**

The cleanest evidence is adoptive siblings — genetically unrelated children
raised in the same home:

| Correlation | Childhood | Adulthood |
|---|---|---|
| Adoptive siblings, IQ | ~0.25-0.30 | **~0.00** |
| Adoptive siblings, personality | ~0.05 | ~0.05 |
| Biological siblings reared apart, IQ | — | ~0.24 |
| MZ twins reared apart, IQ | — | ~0.70-0.75 |

This is not an artefact of one design. It appears in twin studies, adoption
studies, and family studies, and the direction is confirmed by molecular
methods. **TIER 1 for the finding.** The interpretation is where it gets hard.

**Three cautions that are not optional:**

1. **Range restriction.** Adoptive parents are screened. Twin registries recruit
   volunteers. Severely abusive, chaotic and deprived homes are systematically
   under-represented. The result is about *differences among adequate homes*.
2. **Outcome restriction.** See the table above.
3. **Measurement ceiling.** If a personality scale has test-retest reliability of
   0.75, roughly a quarter of "non-shared environment" is noise before any
   substantive interpretation begins.

---

## Judith Rich Harris, steelmanned

Harris published *Where Is the Child's Environment? A Group Socialization Theory
of Development* in *Psychological Review* (1995) and *The Nurture Assumption*
(1998), from outside academia, having been dismissed from a Harvard PhD
programme decades earlier.

**Her argument, at full strength:**

| Step | Claim | Support |
|---|---|---|
| 1 | The observational parenting literature is confounded by genetic transmission | Correct, and this was under-appreciated at the time. **TIER 1** |
| 2 | It is also confounded by reverse causation — children shape parents | Bell (1968) made the point; Harris pressed it. Well supported. **TIER 1** |
| 3 | Genetically informative designs show near-zero shared-environment effects on adult personality | Correct as stated. **TIER 1** |
| 4 | Therefore the family is not where socialisation happens | **Inference, not finding.** TIER 2 |
| 5 | Children are socialised in peer groups, by group-contrast and within-group assimilation | Her positive theory. **TIER 3** |
| 6 | Learned behaviour is context-specific and does not automatically transfer from home to peer group | Well supported and underrated — this is the same problem as transfer in learning/ |
| 7 | The immigrant-language observation: children of immigrants acquire the peer group's language and accent, not the parents' | Striking, robust, and genuinely hard for family-socialisation accounts. **TIER 1** as an observation |

**The immigrant-accent case is her strongest card and deserves respect.** No
amount of parental input produces the parents' accent in a child surrounded by a
different peer group. Whatever mechanism does that is not the parent-child
relationship.

---

## The case against Harris, also steelmanned

| Objection | Force |
|---|---|
| **The residual is not evidence for peers** | Turkheimer & Waldron's (2000) meta-analysis found that *measured* non-shared environmental variables — differential parental treatment, differential peer experience, differential life events — typically account for only a few percent of variance each. The E term is large; nothing anyone has measured fills it. Attributing it to peers is an assertion. **Strong objection** |
| **Range restriction** | Her argument covers the environments in the studies. Severe maltreatment lies outside them and has demonstrable lasting effects. **Strong** |
| **Outcome restriction** | C is substantial for education, income, religion, politics, substance initiation, criminal onset. Harris's thesis is much weaker outside personality and IQ. **Strong** |
| **Parents select the peer group** | If peers do the socialising, and parents choose the neighbourhood, school and social circle, parents retain a large indirect causal lever. Harris accepted this; the popular reception did not notice. **Strong, and it is the practical upshot** |
| **Variance is not causation** | Zero shared-environment variance means parents in this sample did not differ in ways that mattered — not that parenting cannot matter. **Decisive as a logical point** |
| **The relationship itself** | Harris's framework has nothing to say about whether a childhood was happy. She did not claim it did. Reviewers acted as though she had. **Category objection, and correct** |

**Where this lands.** Harris was right about the confound, right that the field
had assumed its conclusion, and probably wrong — or at least unevidenced — about
the positive peer-group theory. Her book is best read as a demolition, not a
replacement. **TIER 1 for the critique; TIER 3 for group socialisation theory.**

---

## The scarcity caveat — Turkheimer's interaction

Turkheimer, Haley, Waldron, D'Onofrio & Gottesman (2003) analysed **320 twin
pairs at age 7** from the National Collaborative Perinatal Project, a sample
heavily weighted towards poor families.

| Family SES | Heritability of IQ | Shared environment |
|---|---|---|
| Impoverished | **~0.10** | **~0.60** |
| Affluent | **~0.72** | ~0.15 |

**The standard result inverts under deprivation.** In poverty, environmental
differences dominate; in affluence, genetic differences dominate. This is
exactly what the greenhouse analogy predicts, and it reframes every heritability
number in this notebook as *conditional on a decent environment*.

**Caveats, and they are real:**
- N=320 at a single age. Later work is mixed.
- **Tucker-Drob & Bates (2016)** meta-analysed the interaction and found it
  reliably in **US samples** but **not in Western Europe or Australia**. The
  plausible explanation — that stronger welfare states compress environmental
  variance so there is less poverty-driven variance to find — is intuitive and
  **not directly tested**. **TIER 2.**
- The effect is clearer for cognitive ability than for other traits.

**Practical reading:** high heritability is a symptom of environmental adequacy
and equality of provision. In an unequal society, environment does more of the
work. This is close to the opposite of the political conclusion usually drawn
from heritability findings.

---

## What is actually in the non-shared residual

Candidate contents, with honest assessment:

| Candidate | Evidence | Tier |
|---|---|---|
| **Measurement error** | Certain. Reliability ceilings guarantee a large share | 1 |
| **Developmental chance / stochasticity** | Freund et al. (2013, *Science*): genetically identical mice in a shared enriched environment diverged markedly in exploratory behaviour and adult neurogenesis. Isogenic *C. elegans* in controlled conditions vary in lifespan and behaviour. **Randomness is a real developmental cause** | 1-2 |
| **Prenatal and perinatal differences** | Birthweight discordance in MZ twins predicts later differences. Real but small | 2 |
| **Illness, injury, accident** | Obviously real; hard to quantify | 2 |
| **Differential parental treatment** | Measured, and small — a few percent (Turkheimer & Waldron 2000) | 2 |
| **Peer groups** | Harris's proposal. Selection effects are large and hard to separate from influence | 3 |
| **Idiosyncratic events with large consequences** | A teacher, an injury, a book, a first job. Plausible, essentially unmeasurable | 3 |

**The stochasticity finding deserves more attention than it gets.** Some of what
makes a person who they are is noise in a developing system, not a cause anyone
could have controlled or should feel responsible for. That is a substantive
finding, not a shrug.

---

## What environment demonstrably does move

Against the "environment doesn't matter" reading, here are effects with good
causal support:

| Effect | Magnitude | Design |
|---|---|---|
| Additional year of schooling on IQ | ~1-5 points, durable | Ritchie & Tucker-Drob (2018) meta-analysis of natural experiments |
| Moving to lower-poverty neighbourhood before 13 | ~+31% adult earnings | Chetty, Hendren & Katz (2016), MTO randomised programme |
| Removing severe institutional deprivation early | Large; see attachment-and-early-years.md | ERA study; BEIP randomised trial |
| Lead exposure reduction | Several IQ points; population-level | Multiple natural experiments |
| Iodine supplementation where deficient | ~10-13 IQ points | Meta-analyses of deficient populations |
| Flynn effect | ~3 points per decade across the twentieth century | Entirely environmental by construction |
| Genetic nurture | Non-transmitted parental alleles predict child's education at ~30% of transmitted effect | Kong et al. (2018) |

**These are not small.** The Flynn effect alone dwarfs every within-family
parenting variable ever measured. The correct summary is not "environment
doesn't matter" but **"the environmental variables that matter most are not the
ones parenting literature measures."**

---

## Where the popular story is wrong

| Popular story | Reality |
|---|---|
| "Science proved parents don't matter" | It found that *differences among adequate Western parenting styles* explain little variance in *two outcome families*. Every clause is doing work |
| "Non-shared environment means peers" | It means "unexplained". Measured peer variables fill very little of it. Some of it is certainly measurement error and some is developmental randomness |
| "Heritability is a fixed property of a trait" | It flips under deprivation. Turkheimer 2003 |
| "Birth order shapes personality" | Well-powered studies find essentially nothing. Rohrer et al. (2015), N~20,000 across three panels: null for all Big Five; ~1.5 IQ points for firstborns. See the-control-group.md |
| "Rich families pass on advantages genetically" | Wealth transmission is overwhelmingly environmental and institutional. Shared-environment effects on income are large, unlike for personality |
| "If it's in the genes, intervention is pointless" | Schooling, lead, iodine, nutrition, glasses, PKU diet. The list of effective interventions on heritable traits is long |
| "Everything is heritable, so attachment must be too" | Infant attachment security shows near-zero heritability and substantial shared environment. It is one of the cleanest counterexamples in the field |

---

## Open questions

- [ ] What fraction of the E term is measurement error? Nobody has produced a
      convincing decomposition, and the answer changes the interpretation of the
      whole literature.
- [ ] Does the Turkheimer interaction hold outside the US, and if not, is the
      welfare-state compression explanation correct or is it a post-hoc story?
- [ ] Is Harris's group socialisation theory testable? Thirty years on, it has
      produced remarkably little confirmatory research either way.
- [ ] How much developmental variance is irreducible stochasticity? The isogenic
      animal work suggests a real floor. Nobody has estimated it for humans.
- [ ] Do the near-zero shared-environment estimates hold in samples that
      adequately represent maltreating and chaotic families? Currently untested,
      because those families are hardest to recruit.
- [ ] Why is shared environment substantial for attachment but near-zero for
      personality? If both are "relational", the divergence needs explaining.
