# Bias and Reasoning — Why Being Smart Doesn't Save You

> **Status: Tier 1 that humans reason toward preferred conclusions; Tier 2 on
> most of the specific named biases, several of which have failed replication;
> Tier 2 leaning strongly on the claim that intelligence does not protect
> against myside bias.** **This file must be read alongside
> the-replication-crisis.md**, because the heuristics-and-biases literature is
> itself one of the fields worst hit by it. Anyone citing bias research without
> that caveat is demonstrating the phenomenon.

---

## The core finding, stated carefully

**Reasoning is largely a process of constructing justifications for conclusions
arrived at by other means.** This is the one claim in the file I would defend
hard, because it is supported by several independent lines of evidence rather
than by any single paradigm.

| Line of evidence | Source |
|---|---|
| Motivated reasoning as a general framework | Kunda (1990), *Psychological Bulletin*: people search memory for beliefs and rules that support the desired conclusion, constrained by the need to construct a *plausible* justification. **The constraint matters — motivated reasoning is not wishful thinking; it requires an argument** |
| Social intuitionism | Haidt (2001), "The Emotional Dog and Its Rational Tail"; *The Righteous Mind* (2012). Moral judgement is intuitive and immediate; reasoning follows as post-hoc advocacy. **The elephant and rider metaphor** (from *The Happiness Hypothesis*, 2006): the rider is not the driver, the rider is the press secretary |
| Argumentative theory | Mercier & Sperber (2011), *The Enduring Puzzle of Reason* / *The Enigma of Reason* (2017): reasoning evolved for producing and evaluating arguments in groups, not for individual accuracy. **This explains the pattern of biases as design features rather than bugs** — you are good at finding flaws in *others'* arguments and bad at finding them in your own, which is exactly what you'd expect |
| Split-brain confabulation | Gazzaniga's interpreter module: the left hemisphere generates confident explanations for behaviour it did not cause and has no access to |
| Choice blindness | Johansson et al. (2005): participants given the opposite of their chosen option often fail to notice and then explain why they chose it |

**Mercier and Sperber's framing is the most useful**, because it makes a
prediction the others don't: **individual reasoning is poor, group reasoning
among people with different priors is good.** That is consistent with the
laboratory record and with the whole argument of this notebook — knowledge is
made by distributed error correction, not by individual rigour.

---

## Why intelligence doesn't help

**The most important and most counterintuitive result in the file.**

- **Perkins (1985)** asked participants of varying education to reason about open social issues. More education produced **more arguments on their own side** — not more arguments on the other side. Capability was spent on advocacy.
- **Kahan et al. (2012), *Nature Climate Change***: higher scientific literacy and numeracy were associated with **greater polarisation** on climate risk, not convergence. Capability amplified the prior.
- **Kahan (2017), "Motivated Numeracy"**: participants interpreted a 2×2 table of data. When it was labelled as a skin-cream trial, high-numeracy participants got it right more often, as expected. When the identical numbers were labelled as a gun-control study, **high-numeracy participants got it wrong more often than low-numeracy ones when the correct answer cut against their politics.** Numeracy was deployed to defeat the data. *(Contested: the motivated-numeracy effect has had mixed replication — see Connor et al. (2020) and Persson and colleagues. Treat the direction as supported and the magnitude as uncertain.)*
- **Stanovich, *The Bias That Divides Us* (2021)**: across a large body of work, most reasoning biases correlate at least modestly with cognitive ability — smarter people do better. **Myside bias is the exception. It is close to uncorrelated with intelligence, education, and open-mindedness measures.** It correlates instead with how strongly the belief is held and how central it is to identity.

**The synthesis: intelligence is a tool, and the elephant decides what it gets
used for.** A better reasoner produces better arguments for what they already
believe, and better rebuttals of what they don't. **This is why credentialled
disagreement persists at high levels indefinitely, and why "just teach critical
thinking" has such a poor track record as an intervention.**

---

## The bias catalogue, audited

Because the field has a replication problem, this table separates what survived
from what didn't. **This is the part of the file most likely to be out of date.**

| Effect | Status |
|---|---|
| **Confirmation bias / positive test strategy** | **Holds.** Wason's 2-4-6 task (1960) and selection task (1966). Robust across paradigms and cultures. Note the mechanism is usually *positive testing* rather than deliberate evidence-avoidance |
| **Anchoring** | **Holds well.** Replicated strongly in Many Labs 1 — one of the most robust effects in the literature |
| **Framing (Asian disease problem)** | **Holds.** Replicates reliably |
| **Base rate neglect** | **Holds.** Casscells, Schoenberger & Grayboys (1978): Harvard Medical School staff and students given a 1/1000 prevalence, 5% false-positive-rate diagnostic problem; **only about 18% gave the correct answer of roughly 2%.** Most said 95% |
| **Availability** | **Holds** as a general phenomenon; some specific demonstrations are shaky |
| **Sunk cost** | **Holds** |
| **Overconfidence / miscalibration** | **Holds strongly**, and is the practically important one |
| **Hindsight bias** | **Holds** |
| **Ego depletion** | **Failed.** See the-replication-crisis.md |
| **Behavioural priming (elderly, money, professor, Lady Macbeth)** | **Largely failed.** Kahneman himself conceded the literature was built on underpowered studies |
| **Facial feedback** | **Failed in a 17-lab RRR** (Wagenmakers et al., 2016). *(Later meta-analytic work is mixed; treat as unresolved rather than dead.)* |
| **Physical-warmth-to-social-warmth** | **Failed** in large-sample replication (Chabris et al., 2019) |
| **Implicit Association Test as behaviour predictor** | **Weak to null.** r ≈ 0.1; changing implicit scores does not change behaviour (Forscher et al., 2019) |
| **Dunning-Kruger** | **Contested.** The pattern in the original 1999 graphs can be substantially reproduced with *random data* because of regression to the mean plus better-than-average effects (Nuhfer et al., 2016-17; Gignac & Zajenkowski, 2020). **The underlying observation — unskilled people are poor at assessing their own skill — is plausible; the specific effect as drawn is not established** |
| **Stereotype threat** | **Contested.** Small-study literature with evidence of publication bias; large replications inconsistent |

**The meta-lesson: "cognitive bias" has become a rhetorical weapon detached from
its evidence base.** People cite the biases that suit them, which is itself the
finding.

---

## Bayes: what it gives you and what it doesn't

$$P(H \mid E) = \frac{P(E \mid H)\,P(H)}{P(E)}$$

**What it gives you, and it is genuinely valuable:**

1. **The prior is not optional.** Any evidence must be weighed against how likely the claim was beforehand. Ioannidis's whole argument is this, applied to journals.
2. **Evidence strength is a *ratio*, not a fact about the evidence.** The likelihood ratio $P(E|H)/P(E|\neg H)$ is what moves you. A finding that is equally likely under both hypotheses is worthless however dramatic it is.
3. **Updates should be proportional.** Most disagreement failures are people updating either 0% or 100%.
4. **It shows exactly why extraordinary claims need extraordinary evidence** — and simultaneously why that rule is *conservative* and delayed continental drift.

**The worked example everyone should be able to do.** Disease prevalence
1/1000. Test sensitivity ~100%, false positive rate 5%. You test positive.
In 1,000 people: 1 true positive, ~50 false positives. **P(disease) ≈ 2%.** Most
doctors say 95%. Gigerenzer and Hoffrage (1995) showed that **stating it in
natural frequencies rather than percentages raises correct answers dramatically
— from roughly 15-20% to roughly 50%+ with no training at all.**

**That is the single best debiasing result in this file, and it is a
representation change, not a willpower change.** The general lesson generalises
far beyond Bayes: **fix the format, not the person.**

**What Bayes does not give you:**
- **Priors you don't have.** "Be Bayesian" without numbers is a mood.
- **Protection from motivated reasoning.** You can choose priors and likelihoods to reach any posterior. Kahan's numerate participants were doing something structurally Bayesian and getting it wrong on purpose.
- **A resolution to Duhem-Quine.** You still choose which belief in the web to update.

---

## Steelmanning the defence of motivated reasoning

Rarely stated, and it is not stupid.

- **Priors *should* resist evidence.** A well-supported theory ought to survive one contrary study. Someone who abandons a robust belief on one paper is not rational, they are noisy. **Much of what looks like bias is correct conservatism applied without calibration.**
- **Reasoning that produces group truth via individual advocacy is a real design.** Adversarial systems — courts, peer review, the two-sided literature on any live question — work *because* participants argue their side hard. Mercier and Sperber's point.
- **Identity-protective cognition can be individually rational.** Kahan's argument: for an ordinary person, being wrong about climate physics costs nothing; being out of step with their community costs a lot. **The individual incentive and the collective epistemic interest genuinely diverge.** This is uncomfortable and I think it is correct.
- **The debiasing literature is weak.** If biases are so damaging, the interventions should work better than they do. That they mostly don't is evidence that the "bias" framing may be carving the phenomenon badly.

---

## What actually reduces error

Ranked by evidence, not by cleverness. *(This is the operational core; see
practices.md for the extended version.)*

1. **Change the representation.** Natural frequencies over percentages. Absolute risk over relative risk. Graphs over tables where the comparison is spatial. **Strongest evidence of anything here.**
2. **Change the structure, not the person.** Preregistration, blinding, pre-committed analysis plans, mechanical aggregation. Every reliable improvement in the notebook is structural.
3. **Make predictions in advance and score them.** The whole difference between weather forecasters and pundits.
4. **Consider the opposite, explicitly.** Lord, Lepper & Preston (1984) found that instructing people to consider the opposite reduced biased assimilation where general "be unbiased" instructions did nothing. *(Modest effect, replicated adequately.)*
5. **Use adversarial collaboration.** Two researchers with opposing predictions design one study together and pre-commit to interpretations. Kahneman advocated it for decades; the Kahneman-Klein paper is the model. Rare because it is career-inefficient.
6. **Aggregate independent judgements.** Crowds beat individuals when errors are uncorrelated. They fail badly when they aren't — which is why "the consensus" is only as good as the independence behind it.
7. **Ask for the track record.** Not the argument, the record.

**What does not work, and this is where most effort goes:** teaching people
lists of biases, exhortation to be objective, more information for people who
already disagree, and self-assessment of one's own bias (the bias blind spot —
Pronin, Lin & Ross, 2002 — means you see it in others and not in yourself, and
this is one of the more robust findings here).

---

## Where the popular story is wrong

| Popular belief | Reality |
|---|---|
| "Educating people fixes disagreement" | Kahan: more scientific literacy produced *more* polarisation on identity-loaded questions. Information is not the binding constraint |
| "Smart people are less biased" | True for most biases, false for the one that matters most. Myside bias is roughly independent of ability (Stanovich) |
| "Cognitive biases are well-established science" | Some are. Several famous ones failed replication. The catalogue is a mixture of durable results and casualties, and popular writing does not distinguish them |
| "*Thinking, Fast and Slow* is a reliable summary" | Kahneman publicly conceded the priming chapter was built on underpowered studies. The dual-system framing is also disputed as an oversimplification by Kahneman himself in later work. **Read it as an important book with known bad sections** |
| "The Dunning-Kruger effect proves incompetent people are confident" | The specific graphical effect is substantially reproducible from random data. Contested |
| "Implicit bias tests reveal hidden prejudice that drives behaviour" | The tests are unreliable at the individual level and predict behaviour weakly. Their own creators say they should not be used diagnostically |
| "Confirmation bias means people ignore evidence" | Usually people *engage* the evidence and reinterpret it. That is more dangerous, because it feels like thinking |
| "Just be objective" | Not an instruction anyone can follow. Every effective intervention in this file changes the environment, the format, or the incentives, not the intention |

---

## Open questions

- [ ] Is myside bias genuinely independent of intelligence, or is Stanovich's measurement capturing something narrower than the concept?
- [ ] Does adversarial collaboration scale, or does it only work when both parties are unusually honest? **The sample of successful cases is tiny and self-selected.**
- [ ] How much of the heuristics-and-biases catalogue survives a full audit? Nobody has done the systematic version; the field is being revised effect by effect.
- [ ] Are LLMs as reasoning aids a debiasing tool or an amplifier? They are extremely good at producing plausible arguments for a specified conclusion, which is the exact affordance motivated reasoning wants. **I expect net harm on identity-loaded questions and net benefit on technical ones, and I have no evidence for that.**
- [ ] Does Mercier and Sperber's argumentative theory make any prediction that distinguishes it from motivated-reasoning accounts empirically?
- [ ] Kahan's claim that identity-protective cognition is individually rational implies that fixing public reasoning requires changing the *social* cost of being wrong. Nobody has proposed a workable mechanism for that.
