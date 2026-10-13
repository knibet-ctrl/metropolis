# Nature and Nurture — Why The Dichotomy Is Wrong

> **Status: TIER 1** on the core quantitative findings and on the caveats.
> **TIER 2** on the interpretation of twin-study assumptions. **TIER 3** on most
> popular epigenetics.

> **Written from general knowledge with no live source verification.** Sample
> sizes and effect sizes are indicative.

> **This file carries the notebook's misuse warning.** The findings below have
> been used to justify sterilisation, segregated schooling, immigration
> restriction and worse. The abuse is not a reason to suppress the findings; it
> is a reason to state them precisely, including what they cannot support. The
> section headed **"The one error that does the damage"** is the point of the
> file.

---

## The dichotomy is not a fifty-fifty split of a single quantity

Asking whether a trait is due to genes or environment is like asking whether the
area of a rectangle is due to its length or its width. For any *individual*, the
answer is meaningless — 100% both. The question only becomes coherent for
*variation across a population*, and then only relative to the specific
environments that population happens to contain.

Three mechanisms make the partition leaky in practice:

| Mechanism | What it means | Example |
|---|---|---|
| **Passive rGE** (gene-environment correlation) | Parents provide both genes and environment, correlated | Bookish parents pass on both genes associated with reading ability and a house full of books. The "book effect" is confounded by design |
| **Evocative rGE** | The child's genetically influenced behaviour elicits environments | An irritable infant draws different handling than a placid one. Measured "harsh parenting" is partly a *consequence* of child temperament |
| **Active rGE / niche-picking** | People select environments matching their propensities | Scarr & McCartney (1983). Explains why heritability *rises* with age as people gain autonomy over their surroundings |

**Consequence, and it is severe:** the entire observational parenting literature
— thousands of papers correlating what parents do with how children turn out —
is confounded by passive and evocative rGE. Those correlations are upper bounds
on causal effects, and where genetically informative designs have been applied,
the effects usually shrink substantially or vanish. **TIER 1** as a
methodological point; routinely ignored in practice.

**Gene-environment interaction (GxE)** is the fourth complication: genetic
effects differ by environment. The famous candidate-gene GxE findings —
Caspi et al. (2002, MAOA and maltreatment; 2003, 5-HTTLPR and depression) — were
enormously influential and have **failed to replicate** in large samples (Culverhouse
et al. 2018; Border et al. 2019, who found essentially no support for any of the
18 most-studied candidate genes in depression). Treat single-gene GxE claims as
**TIER 3 at best.** Broad GxE — heritability differing by socioeconomic level —
is better supported. See what-shapes-a-person.md.

---

## What twin and adoption studies actually do

| Design | Logic | Main vulnerability |
|---|---|---|
| **Classical twin study** | MZ twins share ~100% of segregating genes, DZ ~50%. Both share the family environment. Excess MZ similarity is attributed to genes | The equal environments assumption (below) |
| **Twins reared apart** | Any similarity is not from shared rearing | Rare; selective placement; often not separated at birth; contact between twins; small N. The Minnesota study (Bouchard, from 1979) had ~137 pairs |
| **Adoption study** | Adoptive relatives share environment, not genes; biological relatives the reverse | Selective placement into above-average homes; restricted environmental range; prenatal environment is shared with the biological mother |
| **Adoptive siblings** | Two genetically unrelated children raised together. Their adult correlation is a near-direct estimate of shared-environment effect | Same restriction-of-range problem |
| **Children-of-twins / within-family** | Compares siblings differing in exposure, holding family constant | Siblings differ non-randomly; low power |
| **GCTA / SNP heritability** | Estimates heritability from measured common variants in unrelated people | Only captures common additive variants; underestimates total |
| **Within-family polygenic prediction** | Compares siblings' polygenic scores — random Mendelian assignment | The cleanest design available. Predictive power roughly **halves** relative to population estimates |

**The headline dataset.** Polderman et al. (2015, *Nature Genetics*) meta-analysed
**2,748 twin publications, 14.5 million twin pairs, 17,804 traits, 1958-2012**.
Mean heritability across all traits: **~49%**. For roughly two-thirds of traits,
the data were consistent with a simple additive genetic model with no shared
environment at all. This is the most comprehensive single result in the field.

**Turkheimer's three laws of behaviour genetics (2000):**
1. All human behavioural traits are heritable.
2. The effect of being raised in the same family is smaller than the effect of genes.
3. A substantial portion of variation is explained by neither.

Chabris et al. (2015) added a fourth: any behavioural trait is associated with
very many genetic variants, each of tiny effect. This killed the candidate-gene
era.

---

## The equal environments assumption, taken seriously

The classical twin design assumes MZ and DZ twins experience equally similar
*trait-relevant* environments. If MZ twins are treated more alike — and they
demonstrably are, in dress, activities and time spent together — then genetic
effects are inflated.

**The defence, which is better than critics allow:**
- **Misclassified zygosity.** Some twins are wrong about whether they are
  identical. Scarr & Carter-Saltzman (1979) and successors found that *actual*
  zygosity predicts similarity far better than *believed* zygosity. If treatment
  drove similarity, belief should dominate. It doesn't.
- **Convergent estimates from designs with different assumptions.** Adoption
  studies, twins reared apart, and SNP-based estimates from unrelated individuals
  do not share the EEA and give qualitatively similar answers.
- **Direction of causation.** MZ twins may be treated more alike *because* they
  behave more alike — evocative rGE, which is a genetic effect.

**The critique, steelmanned** (Jay Joseph; Ken Richardson; Richardson & Norgate):
- The tests above check gross treatment, not trait-relevant environments.
- MZ twins share a more similar prenatal environment; ~two-thirds are
  monochorionic, sharing a placenta. Chorionicity affects birthweight and possibly
  cognition, and most studies do not record it.
- MZ twins report far more time together, more shared friends, more identity
  fusion. For traits like personality and attitudes this could plausibly matter.
- Twin estimates assume no assortative mating and no gene-environment
  correlation; both are violated, and both push estimates around.
- SNP heritability comes in **well below** twin heritability — for cognitive
  ability, roughly 20-30% versus 60-80%. This "missing heritability" gap is real,
  and one honest reading is that twin estimates are too high.

**Where this lands: TIER 2.** The EEA is probably approximately right for
gross-level conclusions and probably inflates specific numbers. **Directional
conclusions — "genes matter substantially, shared environment less than expected"
— survive. Precise percentages should not be quoted as though they were
measured constants.**

---

## Heritability: what it is, and the seven things it is not

**Definition.** Heritability ($h^2$) is the proportion of *phenotypic variance*
in a *specific population* at a *specific time* in a *specific range of
environments* that is statistically associated with genetic variance.

$$h^2 = \frac{V_G}{V_P} = \frac{V_G}{V_G + V_E + V_{GxE} + V_{error}}$$

It is a **ratio of variances**. This has consequences that are not optional
caveats — they follow from the definition.

| It does NOT mean | Why |
|---|---|
| **1. That the trait is fixed in an individual** | $h^2$ is a population statistic. It has no individual-level interpretation at all. There is no such thing as "70% of your height came from your genes" |
| **2. That the trait cannot be changed** | Height heritability is ~0.8; Dutch mean height rose ~20cm in 150 years. PKU is 100% genetic and fully managed by diet. Myopia is highly heritable; glasses cost £30 |
| **3. That an individual has a genetic ceiling** | No study measures ceilings. Heritability is about observed variance, not about unobserved potential |
| **4. That between-group differences are genetic** | **The critical one. See below.** Within-group heritability places no constraint on between-group causes |
| **5. That environment is unimportant** | Heritability rises as environments become more equal and better. High $h^2$ can indicate environmental *success* |
| **6. That it is a constant** | It changes with age, cohort, country and social conditions. IQ heritability roughly doubles from childhood to adulthood |
| **7. That "genetic" means "innate" or "present at birth"** | Genetic influences unfold over decades and act through environments — including environments the person selects because of their genotype |

---

## The one error that does the damage

**Lewontin's 1970 argument, which settles the between-group question.**

Take a bag of genetically variable seed. Split it in two. Plant half in
excellent soil, half in depleted soil. Within each pot, all height variation is
genetic — heritability is 1.0. **The entire difference between the two pots is
environmental.**

**Heritability within groups says nothing whatsoever about the causes of
differences between groups.** This is not a caution or a nuance; it is a
mathematical fact about what the statistic measures. Every hereditarian argument
about race and intelligence from the 1969 Jensen article onward has required
this inference, and the inference is invalid.

Additional facts that bear on the same claim and are usually omitted:

- **"Race" as used in these arguments is a social classification** that maps
  poorly onto genetic population structure. The great majority of human genetic
  variation is within, not between, continental groupings, and the boundaries
  are drawn socially and differ by country and era.
- **Polygenic scores do not transport across ancestries.** Martin et al. (2019)
  found scores derived in European-ancestry samples lose roughly half to
  four-fifths of their predictive accuracy in African-ancestry samples. Scores
  cannot currently be used for cross-population comparison at all — the tool
  required for the argument does not exist.
- **Environments differ non-randomly and massively** along exactly the lines
  in question: wealth, schooling, neighbourhood, lead exposure, healthcare,
  discrimination, incarceration, stereotype effects, and test-measurement
  differences. These are not residual noise; they are the largest measured
  variables in the entire notebook.
- **Group gaps have narrowed within cohorts**, which no fixed-genetic account
  predicts, and the Flynn effect — roughly 3 IQ points per decade across the
  twentieth century in many countries — was far larger than any measured group
  gap and was entirely environmental.

**No group is inherently superior or inferior on anything in this notebook. The
evidence does not support the claim, the statistic invoked cannot support the
claim, and the historical record of the claim is sterilisation programmes and
segregated schooling.**

---

## The Wilson effect

Named for Ronald S. Wilson (Louisville Twin Study). **The heritability of
cognitive ability increases with age**, from roughly 20-40% in early childhood
to roughly 60-80% by adulthood, plateauing in middle age. Documented across
multiple cohorts and reviewed by Bouchard (2013).

The mirror-image finding is starker: **shared-environment effects on IQ decline
towards zero by late adolescence.** Adoptive siblings correlate around 0.25-0.30
on IQ in childhood and approximately **0.00 as adults** (McGue et al. 1993;
Loehlin, Horn & Willerman).

**Why?** The leading explanation is active gene-environment correlation: as
people gain control over their environments, they select ones that amplify
existing propensities. A modest early genetic nudge towards reading produces
years of extra reading. Genes act as an *engine of environment selection*, not
as a fixed endowment. **TIER 1** for the phenomenon; **TIER 2** for the
explanation.

**Uncomfortable corollary for interventions:** anything that works by supplying
an environment which is withdrawn at the end of the programme should be expected
to fade. See education.md.

---

## Genetic nurture — the finding that complicates everything

Kong et al. (2018, *Science*) analysed Icelandic data and found that
**parental alleles that were NOT transmitted to the child still predicted the
child's educational attainment**, at roughly 30% of the effect size of the
transmitted alleles.

Non-transmitted alleles cannot act on the child biologically. They act by
shaping the parent, who shapes the environment. **This is an environmental
effect measured with a genetic instrument.** It means:

- Population polygenic scores partly measure parental environments, not the
  child's biology.
- Within-family (sibling-difference) designs are the only clean estimate of
  direct genetic effects, and they roughly halve the apparent predictive power
  of education polygenic scores — from ~12-16% of variance (Okbay et al. 2022,
  N~3 million) down to roughly half that within families.
- Parents demonstrably transmit environmental advantage, and here it is,
  measured.

**TIER 1** for the finding. It should have made bigger waves than it did.

---

## Epigenetics: the real thing and the popular version

**What it actually is.** Chemical modifications — DNA methylation, histone
modification, non-coding RNA — that regulate gene expression without changing
sequence. This is uncontroversially real, ubiquitous, and how a liver cell and a
neuron with identical DNA end up different. **TIER 1.**

**What the popular version claims.** That your grandmother's famine, trauma or
smoking rewrote your genome, and that childhood experience leaves heritable
molecular scars. **TIER 3, and much of it TIER 4 as usually stated.**

The obstacle is mechanical: in mammals there are **two genome-wide
reprogramming waves** — shortly after fertilisation, and in primordial germ
cells — that erase the great majority of methylation marks. A small number of
imprinted loci escape. Transgenerational epigenetic inheritance is
well-demonstrated in plants, *C. elegans* and some rodent paradigms. **In humans
it is not established.**

| Famous claim | What the study found | The problems |
|---|---|---|
| **Dutch Hunger Winter** (Heijmans et al. 2008, PNAS) | Individuals prenatally exposed to the 1944-45 famine had ~5% lower methylation at the IGF2 DMR six decades later, versus unexposed same-sex siblings | ~60 sibling pairs; one locus; a small difference of unknown functional significance; **no demonstrated causal link to any phenotype**; the health outcomes of the cohort are real but do not require an epigenetic explanation — prenatal malnutrition has ordinary developmental effects |
| **Överkalix** (Bygren, Kaati, Pembrey) | Paternal grandfather's food availability during his "slow growth period" associated with grandson's mortality and diabetes risk | Tens of individuals; many comparisons; sex-specific effects that flip direction across analyses; historical records of variable quality; **no molecular mechanism measured at all**; not independently replicated |
| **Rat maternal licking/grooming** (Weaver et al. 2004) | Low maternal care associated with methylation of the glucocorticoid receptor promoter and altered stress response; cross-fostering reversed it | Genuinely important work, but **in rats, within one generation** — this is developmental programming, not inheritance. Human extrapolations are speculative, and some replications have been difficult |
| **Holocaust descendant methylation** (Yehuda et al. 2016) | Methylation differences at FKBP5 in Holocaust survivors' offspring | N=32 survivors, 22 offspring. Widely criticised on statistical grounds; confounded by postnatal environment; not replicated at scale |
| **"Epigenetic clocks"** (Horvath 2013) | Methylation predicts chronological age accurately | Real and useful — but it is a **biomarker of ageing**, not evidence of inherited experience. Frequently conflated in popular writing |

**Why this matters for this notebook specifically.** Overstated epigenetics is
the newest vehicle for the oldest error in the field: telling parents that their
stress, diet or unhappiness has permanently written itself into their child's
biology. That claim is not supported, and it is the kind of claim that produces
guilt without producing a single actionable step. Say what is known: severe
prenatal malnutrition, alcohol and tobacco exposure have real effects through
ordinary developmental biology, and those effects are worth avoiding for
ordinary reasons.

---

## Where the popular story is wrong

| Popular story | Reality |
|---|---|
| "It's 50/50 nature and nurture" | There is no fixed split. The ratio is a property of a population and environment, and changes when either changes |
| "Twin studies have been debunked" | The EEA critique is legitimate and probably inflates specific estimates. It does not overturn the directional findings, which replicate in designs that do not use the EEA |
| "Genes for intelligence / for anything" | No. Thousands of variants of minute individual effect. Chabris's fourth law. The candidate-gene era produced a graveyard of non-replications |
| "Epigenetics means your grandmother's trauma is in your DNA" | Not established in humans, and blocked by two rounds of germline reprogramming. Epigenetics as *developmental regulation* is real and important; epigenetics as *inherited memory of experience* is not |
| "Heritability means you can't change it" | Independent quantities. PKU, myopia, iodine, education, height |
| "The gap between groups must be partly genetic" | The statistic invoked cannot support that inference — Lewontin's seed argument. This error has the worst history in the whole of social science |
| "Polygenic scores can predict a child's future" | Within families, current education scores explain single-digit percentages of variance. They are useless for individual prediction and do not transport across ancestries |

---

## Open questions

- [ ] Why is SNP heritability so much lower than twin heritability? Rare
      variants, non-additive effects, or inflated twin estimates? This is the
      single most consequential unresolved technical question in the field.
- [ ] How much of the twin-study heritability estimate is assortative mating,
      which has increased in recent cohorts for education?
- [ ] Is there any well-powered human case of transgenerational epigenetic
      inheritance of an experience-driven mark? Currently: no.
- [ ] Does the Wilson effect reflect niche-picking, gene expression changes over
      development, or measurement properties of adult IQ tests? All three are
      live.
- [ ] Can within-family polygenic designs at population scale produce a usable
      estimate of direct genetic effects, and will those estimates survive the
      portability problem across ancestries? Currently they do not.
- [ ] What is the appropriate governance regime for polygenic embryo screening,
      which is being sold commercially on predictive claims the science does not
      support?
