# Inflation

> **STATUS: TIER 1 that it exists and is broadly measurable. TIER 2 on
> measurement precision. TIER 2 on causes in normal times. TIER 1-2 on the
> structural causes of hyperinflation. TIER 3 on forecasting it.**

> Written from general knowledge without source verification. Peak
> hyperinflation figures in particular are estimates that vary by source and
> methodology; treat them as orders of magnitude.

---

## What it is

A sustained rise in the general price level — equivalently, a fall in the
purchasing power of the unit of account. Two things it is **not**:

- **Not a relative price change.** Eggs getting expensive because of avian flu
  is not inflation; it is information. Inflation is when the measuring rod
  shrinks.
- **Not a price level.** "Inflation is falling" means prices are rising more
  slowly. It does not mean prices are falling. **This confusion caused
  enormous political friction in 2023-24**, when central banks celebrated
  disinflation to publics whose grocery bills were permanently 25% higher. The
  central banks were technically right and rhetorically deaf: the public was
  responding to the price *level*, which does not come back down.

---

## Measurement: harder than it looks

A price index must answer: what does it cost today to buy what you bought
before? Every word in that sentence is a problem.

| Problem | What it is | Direction of bias |
|---|---|---|
| **Substitution** | When beef rises, people buy chicken. A fixed basket (Laspeyres) overstates the cost of living | Overstates |
| **Quality change** | A 2026 car is not a 1990 car. Hedonic regression adjusts for measured attributes | Contested — hedonics is where most public suspicion lands |
| **New goods** | Products enter the basket long after adoption; the early price collapse is missed | Overstates |
| **Outlet substitution** | Shifting to discounters isn't fully captured | Overstates |
| **Owner-occupied housing** | ~1/3 of US CPI is Owners' Equivalent Rent — an *imputed* number, not a transaction price | Uncertain, and it lags actual rents by a year or more |
| **Heterogeneity** | The "average household" doesn't exist. Low-income baskets are weighted toward food, energy and rent | Understates inflation for the poor in energy shocks |

The **Boskin Commission** (1996) concluded that US CPI overstated the cost of
living by roughly 1.1 percentage points a year. Methodology changed
substantially afterwards. Note what that number implies: **an error of 1pp per
year compounds to ~35% over 30 years, which is enough to flip the sign on
"have real wages stagnated since 1973?"** That famous debate is substantially
a debate about which deflator you use. This is a TIER 2 measurement issue
routinely treated as a TIER 1 fact by both sides.

**Index families worth knowing:** headline CPI; core (ex food and energy — not
because those don't matter but because they're noisy); PCE deflator
(chain-weighted, broader, the Fed's preferred measure, typically ~0.3pp below
CPI); trimmed-mean and median CPI (drop the tails, better signal of the
underlying trend); GDP deflator (domestic production, excludes imports).

**The honest summary: inflation is measured to about ±1pp of "true" cost of
living, and there is no objectively correct answer, because comparing a 1990
telephone to a 2026 telephone is not a well-posed question.**

---

## Five competing explanations

Each is a real mechanism. The dispute is about weights, not existence.

### 1. Monetary / quantity theory

The **equation of exchange**, $MV = PY$, is an **identity** — velocity $V$ is
defined as whatever makes it balance. It becomes a *theory* only when you add:
$V$ is stable, and $Y$ is determined by real factors independent of $M$. Then
$M \uparrow \Rightarrow P \uparrow$.

Friedman: *"Inflation is always and everywhere a monetary phenomenon."*

| Where it works | Where it fails |
|---|---|
| High inflations. Above ~40%/yr the money-price correlation is close to 1 | Low-inflation advanced economies at short horizons |
| Long horizons, cross-country comparisons | 2008-2019: enormous base money growth, sub-target inflation |
| Explaining every hyperinflation's proximate mechanism | Velocity became unstable after ~1980, which is why the Fed abandoned monetary targeting in 1982 after only three years |

**Fair scoring:** monetarism won the 1970s argument decisively and then its
own operating rule broke on contact with financial deregulation. The
long-run/high-inflation version is close to TIER 1. The short-run version is
not.

### 2. Demand-pull

Spending exceeds the economy's capacity to produce. The **Phillips curve**:
A.W. Phillips (1958) found an inverse relation between wage inflation and
unemployment in UK data, 1861-1957. Samuelson and Solow read it as a policy
menu. Friedman (1968) and Phelps independently said no: only *unexpected*
inflation buys employment; expectations adjust; there is no long-run trade-off
and attempting to exploit one produces accelerating inflation. **The 1970s
vindicated them — one of the cleanest successful predictions in macro
history.**

Then it flattened. From the 1990s the estimated slope became small enough that
Blanchard described the curve as alive but dozing. Whether it flattened because
of anchored expectations, globalisation, or measurement is unresolved. It
steepened again in 2021-22, which the anchored-expectations story predicts (a
non-linear curve, flat at low pressure and steep at high) and which the
"it's dead" story does not.

### 3. Cost-push / supply shocks

OPEC 1973 (roughly a fourfold oil price rise) and 1979. Pandemic supply chain
disruption. The 2022 European gas shock following Russia's invasion of
Ukraine. Shocks raise the price level and reduce output simultaneously —
stagflation — which is why they are the hardest case for a central bank: the
two halves of its mandate point in opposite directions.

### 4. Expectations

If everyone expects 5%, wage bargains and price-setting deliver 5%. Inflation
becomes self-fulfilling. Hence "anchoring," central bank independence,
inflation targeting (New Zealand first, 1990), and the enormous weight placed
on credibility. **The Lucas critique (1976)** is the sharp version: policy
regimes change behaviour, so historical relationships break exactly when you
try to exploit them.

**Caveat rarely stated:** expectations are measured badly. Household inflation
expectations are noisy, heavily influenced by petrol prices, and often
implausible. Market-implied breakevens confound expectations with risk premia.
A concept doing this much theoretical work should be measured better.

### 5. Profit / sellers' inflation

Isabella Weber's argument (from 2021) that in a shortage environment, firms
can raise prices beyond cost increases because a general shock provides
coordination cover — "sellers' inflation." ECB and other analyses found unit
profits contributed materially to euro area inflation in 2022.

**Handle with care.** The decomposition — deflator = unit labour costs + unit
profits + unit taxes — is **an accounting identity**. Finding that unit profits
"contributed" is not evidence of causation; in any demand-driven inflation
prices rise before wages, so profits mechanically rise first. That is exactly
what a *demand* story predicts too. The identity cannot distinguish them.

**Steelman for:** in concentrated sectors with observable common shocks, the
coordination story is plausible and has microeconomic precedent; margins in
some sectors rose more than input costs and stayed up.
**Steelman against:** margins are procyclical everywhere and always; "greed"
is a constant and cannot explain a change; and margins compressed again in
2023-24 without any change in corporate character.

**Status: genuinely open, frequently argued in bad faith from both directions,
and the identity/causation confusion is doing most of the damage.**

---

## Hyperinflations: what actually caused them

Conventionally, hyperinflation is inflation above 50% *per month*
(Cagan, 1956).

| Episode | Peak (estimates vary) | What actually happened |
|---|---|---|
| **Weimar Germany, 1921-23** | ~29,500%/month, Oct-Nov 1923; prices roughly doubling every 3-4 days | Reparations (London Schedule, 1921: 132bn gold marks) denominated in **gold and foreign currency** — unpayable by printing. French-Belgian occupation of the Ruhr, January 1923, met with government-funded passive resistance: **the state paid millions of striking workers while output collapsed.** The Reichsbank under Havenstein kept discounting commercial bills, believing it was accommodating trade. Ended November 1923 with the Rentenmark — nominally land-backed, actually credible because spending was cut, the Reichsbank stopped discounting, and the Dawes Plan (1924) restructured reparations |
| **Hungary, 1945-46** | The worst ever recorded; prices doubling roughly every 15 hours | ~40% of the capital stock destroyed in the war; Soviet occupation and reparations extracting a large share of remaining output; near-total loss of fiscal administration. Ended August 1946 with the forint, after currency reform and a stabilised fiscal position |
| **Zimbabwe, 2007-09** | ~7.96 × 10^10 percent per month, November 2008 (Hanke and Kwok estimate) | Land seizures from 2000 collapsed commercial agriculture — **the export base and the tax base at once**. Quasi-fiscal deficits run through the Reserve Bank under Gideon Gono, financing subsidies and patronage off-budget. International isolation. Ended in 2009 by abandoning the currency entirely — dollarisation |
| **Venezuela, 2016-19** | ~1.7 million percent, 2018 (IMF estimate; official statistics ceased, so all figures are contested) | Oil ~95% of export earnings; PDVSA output collapsed from ~3.2m barrels/day to well under 1m through underinvestment, purges of technical staff and expropriations. Price controls destroyed domestic supply. Large foreign-currency debt. US sanctions from 2017-19 sharply worsened an already-collapsing situation — **how much is disputed and is a live political argument, not a settled finding** |

### The common structure

```
  1. REAL OUTPUT AND THE TAX BASE COLLAPSE   (war, land seizure, oil, occupation)
  2. THE STATE CANNOT CUT SPENDING            (legitimacy, war, patronage, subsidies)
  3. IT CANNOT BORROW                         (no credit, or debt is in foreign currency)
  4. THEREFORE IT MONETISES                   <- the "printing" everyone points at
  5. HOLDERS FLEE THE CURRENCY                velocity spirals; the tax base shrinks
     further in real terms (the Olivera-Tanzi effect), requiring more printing
  6. SELF-REINFORCING COLLAPSE
```

**The printing is step 4 of 6.** It is the proximate mechanism and it is
never the root cause. This matters practically: countries have expanded base
money enormously without hyperinflating (Japan, the US, the euro area,
2009-2019) because steps 1-3 did not apply.

**What ends them:** every one of these ended within months once the *fiscal*
position was credibly fixed — usually with a new unit, an external anchor and
a visible institutional break. Not gradually. **Hyperinflation ends fast when
the fiscal story changes, which is the strongest evidence that the fiscal
story is the cause.** (Sargent, "The Ends of Four Big Inflations," 1982.)

---

## 2021-23: the episode that embarrassed everyone

**What happened:** US CPI peaked at 9.1% (June 2022); euro area HICP at 10.6%
(October 2022); UK CPI at 11.1% (October 2022) — the highest in four decades.

**The competing post-mortems:**

| Camp | Claim | Score |
|---|---|---|
| **Excess demand** | The $1.9tn American Rescue Plan (March 2021) was far larger than the output gap. Larry Summers said so publicly in February 2021 and was widely dismissed | **Directionally right on inflation.** Wrong on the cost of unwinding it — he suggested very high unemployment would be needed |
| **Team Transitory** | Supply chains, semiconductor shortages, container rates, a goods-vs-services composition shift. Would resolve itself | **Wrong on duration, more right on mechanism than they got credit for.** Much of it did resolve itself |
| **Energy and food shocks** | Russia's invasion (February 2022), European gas prices, grain | Clearly a large part of the European episode specifically |
| **Labour market tightness** | Vacancies-to-unemployed reached record levels; the Beveridge curve shifted out. Blanchard, Domash and Summers vs Figura and Waller on whether it could shift back without unemployment rising | **Figura and Waller's position looks better ex post** — vacancies fell without a large unemployment rise |
| **Profits** | See above | Contested; identity/causation problem |

**Bernanke and Blanchard's 2023 decomposition** found that shocks to prices
given wages — supply and commodity shocks — dominated the initial surge, with
labour market tightness mattering more later. Broadly: mostly supply, then
some demand.

**The most important fact about this episode:** inflation fell from ~9% to
near target **without a recession and without a large rise in unemployment.**
Almost nobody predicted that. It falsifies the strong form of the sacrifice
ratio argument. The best available explanation is that a large part of the
inflation was supply-side and unwound itself, while expectations stayed
anchored — which means the credibility investment of the previous thirty years
paid off. That reading is plausible and not proven.

**The honest scoring: the profession was wrong in 2021 (transitory), wrong
in 2022 (recession required), and had been wrong in the opposite direction in
2010 (QE inflation). Three public failures in thirteen years. This is a field
with weak forecasting ability and enormous policy influence, and that
combination should be stated plainly rather than managed.**

---

## Deflation, briefly

Worse than mild inflation, for a specific reason. Irving Fisher's
**debt-deflation** (1933): falling prices raise the *real* value of nominal
debt, forcing distress selling, which lowers prices further. Fisher, who had
lost a fortune in 1929 after publicly declaring stocks had reached a
permanently high plateau, understood the mechanism personally.

Japan from ~1998 is the modern case. This asymmetry — deflation is dangerous,
mild inflation is not — is why inflation targets are set at 2% rather than 0%.
The choice of 2% specifically has **no strong theoretical basis**; it appears
to derive from an offhand remark by New Zealand's finance minister in 1989 and
became a global standard by imitation. That is worth knowing.

---

## Why people hate inflation more than models say they should

Standard models put the welfare cost of moderate inflation surprisingly low —
menu costs, shoe-leather costs, relative price noise, unindexed tax brackets.
Publics loathe it far out of proportion. Stefanie Stantcheva's survey work
(2024) suggests why: **people experience inflation as a fall in their standard
of living caused by someone else, not as a joint movement of wages and
prices.** They attribute their wage rises to their own merit and price rises
to corporate or government action. Whether this is a bias or a correct
perception of distributional reality depends on whose wages you look at — and
during 2021-22, real wages did fall for most workers before recovering.

**The model may be underweighting a real cost: inflation destroys the
information content of prices and forces everyone to do arithmetic they
previously didn't have to do.** That is a cognitive tax that doesn't appear in
the welfare calculation.

---

## Where the popular story is wrong

| Belief | Reality |
|---|---|
| "Printing money causes inflation" | Only conditional on capacity, expectations, and where the money lands. 2009-2019 is a decade-long counterexample |
| "Hyperinflation is caused by printing" | Printing is step 4 of 6. Every case starts with output and fiscal collapse |
| "Weimar was caused by reckless money-printing" | Reparations in gold/foreign currency, the Ruhr occupation, and paying strikers while output stopped |
| "Inflation is falling means prices are falling" | It means they're rising more slowly. The level does not return |
| "The CPI is manipulated to hide real inflation" | The methodological changes are documented, debated in public, and go in both directions. But the ±1pp measurement uncertainty is real and understated |
| "Shrinkflation isn't in the numbers" | It is — indices are unit-price based. This one is a genuine misconception |
| "Wage rises cause inflation" | Wage-price spirals require validation by monetary policy and unanchored expectations. 2021-23 real wages *fell*; wages were chasing, not leading |
| "Corporate greed caused it" / "It was purely demand" | Both rest on the same accounting decomposition, which cannot distinguish them |
| "Inflation targeting at 2% is scientifically derived" | It is essentially a convention that spread by imitation from New Zealand, 1989-90 |
| "Central banks control inflation" | They influence it with long and variable lags through a transmission mechanism they do not fully understand. Supply shocks are outside their reach entirely |

---

## Open questions

- [ ] Is the Phillips curve genuinely non-linear (flat at low pressure, steep
      at high), or did 2021-22 just look that way because of supply shocks?
- [ ] How much of the 2023-24 disinflation was policy and how much was
      supply-side normalisation that would have happened anyway? **No
      counterfactual exists and this will never be settled cleanly.**
- [ ] Can inflation expectations be measured well enough to bear the
      theoretical weight placed on them?
- [ ] What is the right price index for a world of rapid quality change? The
      hedonic problem gets worse, not better, with software and AI.
- [ ] Does the sellers'-inflation hypothesis have a testable implication that
      distinguishes it from ordinary demand-driven margin expansion?
- [ ] Why 2%? Is there any evidence-based case for a different target, and
      would changing it now destroy the anchoring that took decades to build?
