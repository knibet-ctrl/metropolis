# The Questions — Five Different Ones, Constantly Confused

> **Status: TIER 1** on the claim that these are distinct questions with
> distinct methods and distinct answers. **TIER 2** on the specific answers,
> which are the rest of the notebook.

> **Written from general knowledge with no live source verification.** Figures
> are indicative and should be checked before use.

> **This is the most important file in the notebook.** Almost every public
> argument about children — nature versus nurture, whether parenting matters,
> whether school makes a difference, whether a bad childhood determines a life —
> is an argument in which the two sides are answering different questions and
> neither has noticed.

---

## The five questions

| # | Question | Method that answers it | Typical answer | Who asks it |
|---|---|---|---|---|
| 1 | **What makes people differ from each other?** | Twin, adoption, sibling and genomic designs. Variance decomposition | Genes substantial; family environment small for personality and adult IQ; a large unsystematic residual | Behavioural geneticists |
| 2 | **What do all humans need?** | Deprivation studies, cross-cultural work, natural experiments, animal models | Far more than Q1 suggests — but invisible to Q1 because nearly everyone in the sample has it | Paediatricians, anthropologists |
| 3 | **What can a parent actually change?** | RCTs of interventions, natural experiments, within-family designs | Some things reliably; personality and adult IQ, barely; safety, language exposure, environment selection, and the relationship itself, yes | Intervention researchers |
| 4 | **What predicts how a life goes?** | Cohort studies, administrative data, economics | Structural variables dominate: place, money, schooling, cohort, health, luck | Economists, sociologists |
| 5 | **What makes a childhood good in itself?** | None. It is not an empirical question | Not derivable from any of the above | Parents, ethicists, everyone |

**The central confusion.** Question 1 is about *variance*. Question 2 is about
*levels*. A variance study cannot see anything that everybody has.

---

## The variance/level distinction, worked

Take a wheat field. Seed is scattered uniformly; soil quality varies. Almost
all the variation in plant height is caused by soil — heritability near zero.

Now take the same seed, plant it in a greenhouse with identical, excellent soil
throughout. Now almost all remaining variation comes from genetic differences
between seeds — heritability near one.

**The plants in the greenhouse are taller.** Heritability went up because the
environment got *better and more uniform*, not because environment stopped
mattering. This is Lewontin's 1970 argument and it is the single most useful
thing in the field.

| Statement | True? | Why |
|---|---|---|
| "Heritability of adult IQ is ~70% in Western samples" | Broadly yes | Converging twin, adoption and sibling estimates |
| "So education can't raise IQ" | **No** | Heritability measures variance in *existing* environments. Schooling raises IQ ~1-5 points per year (Ritchie & Tucker-Drob 2018) |
| "So this child's ceiling is fixed" | **No** | Heritability is a population statistic. It applies to no individual |
| "So the gap between group A and group B is genetic" | **No, and this is the historically dangerous error** | Within-group heritability places no constraint whatever on between-group causes. See nature-and-nurture.md |
| "Iodine deficiency doesn't matter, IQ is heritable" | **No** | In an iodine-sufficient population, iodine explains zero variance. Supplementation in deficient populations raises IQ by roughly 10-13 points |

**The iodine case is the cleanest demonstration available.** A cause with a
massive effect on the level can have literally zero variance share in a
population where the deficiency has been fixed. Absence from a variance
decomposition is not evidence of unimportance.

---

## Question 3 versus Question 1: the compatibility argument

This is the one people get most wrong, in both directions.

**Claim A:** "Shared family environment explains little variance in adult
personality." — Well replicated. **TIER 1.**

**Claim B:** "How you treat your child matters." — Also true.

They are compatible for at least six reasons:

| # | Reason | Detail |
|---|---|---|
| 1 | **Range restriction** | Twin registries contain few abusive, chaotic or severely deprived families. The variance studied is variance among broadly adequate homes. The finding is "differences among adequate parenting styles are small", not "parenting is irrelevant" |
| 2 | **Level effects are invisible** | If all parents in the sample feed, shelter and talk to their children, feeding, shelter and talk contribute zero variance |
| 3 | **Outcome selection** | The finding is strongest for personality inventories and adult IQ. It is much weaker or absent for religiosity, political attitudes, education, income, substance-use initiation, language, criminal onset, and health behaviours |
| 4 | **Measurement ceiling** | Personality questionnaires have test-retest reliabilities around 0.7-0.8. Everything unmeasured lands in the residual and gets labelled "non-shared environment" |
| 5 | **The residual is not a mechanism** | "Non-shared environment" is a leftover term containing chance, error, illness, accident, prenatal differences and developmental noise. It is not a discovered cause |
| 6 | **Variance ≠ malleability** | Eyeglasses. Myopia is highly heritable; the intervention is trivially effective. Heritability tells you nothing about whether an effective intervention exists |

**The sharpest way to put it:** behavioural genetics tells you how much of the
*spread* between people in this population, in these environments, tracks
genetic differences. It does not tell you what would happen if you changed an
environment nobody in the sample has yet tried.

---

## Question 4 is answered by different variables entirely

If you want to predict a life going well, the strongest predictors are not
parenting-style variables.

| Predictor | Strength | Notes |
|---|---|---|
| Parental income and wealth | Large | Intergenerational income elasticity ~0.3-0.5 in the US and UK; lower in Denmark and Canada. **TIER 1** |
| Neighbourhood, entered young | Substantial and causally supported | Chetty, Hendren & Katz (2016): +31% adult earnings for MTO movers before age 13; nothing for teen movers. **TIER 2** |
| Years of education completed | Large | Partly causal, partly selection. **TIER 1-2** |
| Childhood health and nutrition | Large where deficiency exists | **TIER 1** |
| Cognitive ability measured in childhood | Moderate | Confounded with all of the above |
| Self-regulation / conscientiousness | Moderate | Moffitt et al. (2011) Dunedin: childhood self-control predicted adult health, wealth and criminal outcomes, **TIER 2**, and the marshmallow-test version of this is much weaker than advertised — see the-control-group.md |
| Country and birth cohort | Enormous, usually ignored | A child born in 1990 in Seoul and one born in 1990 in Malawi face outcome distributions that dwarf every within-family variable in this notebook |
| Parenting style within the normal range | Small on these outcomes | **TIER 2** |

**The uncomfortable implication:** the variables with the biggest effect on
Question 4 are mostly not available to the individual parent, and the variables
most discussed in parenting literature are mostly not the ones with the biggest
effects. This is one reason the discourse is so anxious — it optimises the
controllable rather than the important.

---

## Question 5 is not an empirical question and cannot be made into one

"What makes a childhood good?" is a question about value. No study design
answers it. It matters anyway, and arguably more than the other four.

A childhood spent frightened but which produced a high-earning adult was still
a childhood spent frightened. Sixteen years is not a means of production for
year seventeen onwards. If someone tells you that a practice is pointless
because it doesn't move adult outcome variance, they have answered Question 1
and told you they answered Question 5.

**TIER 4** as an empirical matter — not because it is unimportant, but because
no procedure could settle it. See existence/ethics.md for the general form.

---

## Where the popular story is wrong

| Popular story | What is actually the case |
|---|---|
| "Nature versus nurture — which wins?" | Malformed. Neither is a channel that operates without the other. Gene-environment correlation means the "environment" is partly a genetic outcome, and gene-environment interaction means genetic effects differ by environment. There is no clean partition to win |
| "Behavioural genetics proved parents don't matter" | It proved that among broadly adequate Western homes, differences in parenting explain little *variance* in adult personality and IQ. Harris herself did not claim parents are irrelevant to children's lives |
| "High heritability means low malleability" | Independent quantities. Myopia, PKU, iodine, education. Repeat: independent quantities |
| "Studies show X causes Y in children" | Most developmental research is observational, and parents' genes are correlated with both the parenting and the child outcome. Passive gene-environment correlation confounds essentially the entire observational parenting literature |
| "Children are shaped by their childhood" | True but nearly contentless as stated. The operative questions are which parts, how much, how reversibly, and compared to what |
| "The science settled it" | Developmental psychology has a severe replication problem. Several confident consensus positions in this field were reversed within a generation. See the-control-group.md before trusting the current one |

---

## The question-sorting checklist

Before reading any developmental claim, ask:

1. **Variance or level?** Does this study measure spread between people, or the
   effect of having versus not having something?
2. **What was the range of environments sampled?** If no deprived families were
   included, no conclusion about deprivation follows.
3. **Which outcome?** Personality inventory at 30, or arrest by 25, or the
   child's actual experience on a Tuesday?
4. **What is the counterfactual?** Perry Preschool's counterfactual was *no
   preschool at all in 1962*. Modern pre-K's counterfactual is other childcare.
   Same intervention, different question.
5. **Is genetic confounding controlled?** If parents and children share genes
   and the design does not separate them, the reported parenting effect is an
   upper bound and probably a large overestimate.
6. **Who is being blamed?** If the answer is mothers, raise the prior for error
   sharply. The field's track record on that specific move is dismal.

---

## Open questions

- [ ] Is the "non-shared environment" residual mostly measurement error, mostly
      developmental chance, or mostly systematic-but-unmeasured causes? Three
      very different worlds, and the field has not settled it.
- [ ] Can Question 3 be answered properly at all without large, long, expensive
      RCTs of ordinary parenting practices — which are largely unethical and
      unfundable?
- [ ] How much of the range-restriction objection survives? Nobody has run a
      twin study with adequate representation of severely adverse homes, because
      such families are hardest to recruit and retain.
- [ ] Does the variance/level distinction actually change anyone's behaviour once
      understood, or is it a debating move? Untested.
- [ ] What would a serious empirical programme on Question 5 even look like?
      Child-reported wellbeing measures exist and are barely used in
      developmental research relative to adult outcome measures.
