# How Money Is Created

> **STATUS: TIER 1 on the mechanics. TIER 2 on the consequences.** The
> mechanics are double-entry bookkeeping published by the institutions that
> perform it. This is the highest myth-density file in the notebook: the gap
> between what is documented and what is believed is larger here than anywhere
> else in economics.

> Written from general knowledge without source verification.

---

## The textbook story, and why it is wrong

**What most people were taught (the money multiplier):**

> A customer deposits £100. The bank must hold 10% in reserve, so it lends
> £90. That £90 is deposited elsewhere, that bank lends £81, and so on. Total
> deposits converge to £1,000 — the deposit multiplied by 1/reserve ratio.
> Banks "lend out" the savings entrusted to them.

**What actually happens:**

> A bank approves a loan. It writes the loan as an asset and simultaneously
> credits the borrower's account, creating a new deposit as a liability. Both
> sides of the balance sheet expand at once. **No pre-existing deposit was
> moved. The money did not exist a moment earlier.** The bank then arranges
> reserves and funding afterwards, if it needs them.

This is not a heterodox position. The Bank of England's *Quarterly Bulletin*
2014 Q1 carried "Money creation in the modern economy" (McLeay, Radia and
Thomas), which says in terms that whenever a bank makes a loan it
simultaneously creates a matching deposit, thereby creating new money, and
that this differs from the description found in some economics textbooks. The
Deutsche Bundesbank's *Monthly Report* of April 2017 says the same thing.
**Two of the most conservative central banks in the world published papers
correcting the textbooks.**

**The decisive evidence:** several major economies have had *no reserve
requirement at all* for decades — the UK, Canada, Australia, New Zealand,
Sweden. The United States cut its reserve requirement to zero in March 2020.
A multiplier of 1/0 is not a number. The framework does not merely mislead; in
these jurisdictions it does not have a denominator.

**Where the error came from:** the multiplier was a reasonable stylisation of
a system with binding reserve requirements and a central bank targeting
quantities. Central banks now target an *interest rate*, which means they
supply whatever quantity of reserves the system demands at that rate.
Causality runs the other way from the textbook: **loans create deposits;
deposits create the demand for reserves; the central bank supplies them.**

---

## The two-circuit system

The single most useful diagram in monetary economics.

| | **Reserves (central bank money)** | **Broad money (bank deposits)** |
|---|---|---|
| Who can hold it | Banks, government, some clearing entities | Households, firms, everyone |
| Who creates it | The central bank | Commercial banks, by lending |
| What it's used for | Interbank settlement | The real economy |
| Can it "leave" its circuit | No — reserves cannot be lent to the public | No |
| Bridge between circuits | **Physical cash**, issued on demand when depositors withdraw | |

**Reserves cannot be spent into the economy.** When a bank "lends out
reserves" in a popular explanation, the explanation is describing something
that cannot happen. A bank pays another bank in reserves; it pays *you* by
crediting a deposit.

This single distinction resolves most confusion about QE.

---

## What constrains bank lending

Not reserves. In order of practical bite:

| Constraint | Mechanism |
|---|---|
| **Creditworthy demand** | You cannot force people to borrow. This binds hardest in downturns |
| **Capital requirements** | Basel III: risk-weighted assets against equity. This is the binding regulatory constraint |
| **Profitability** | The spread must cover expected losses, funding and capital cost |
| **Liquidity and settlement risk** | Loans lead to outflows to other banks; the bank must fund those |
| **The policy rate** | Sets the cost of funding at the margin and therefore the price of credit |
| **Competition and risk appetite** | Underrated; procyclical; the core of the Minsky story |

**Practical implication:** in a slump, "the banks aren't lending" is usually
about demand and capital, not about a shortage of anything the central bank
can print. This is why QE did far less for lending than its advocates hoped
and far less damage than its critics feared.

---

## What QE actually does

Quantitative easing: the central bank buys assets — usually government bonds —
and pays by creating reserves.

**If it buys from a bank:** the bank swaps a bond for reserves. Broad money is
unchanged. Nothing has reached the public.

**If it buys from a pension fund via a bank:** the fund's bank credits the
fund's deposit and receives reserves. **Broad money rises** — but the fund has
swapped a bond for a deposit; it is not richer, it is differently positioned.

So QE is best understood as **a large asset swap that shortens the duration of
assets held by the private sector.** Its proposed channels:

| Channel | Claim | Evidence |
|---|---|---|
| Portfolio rebalancing | Holders pushed into riskier assets, raising prices and lowering yields | Reasonable event-study support, mostly at announcement |
| Signalling | Commits the central bank to low rates for longer | Probably the largest channel |
| Market functioning | Restores liquidity in dislocated markets | Strongest in March 2020; near-consensus |
| Bank lending | More reserves → more lending | **Weak to absent.** The multiplier isn't there |
| Wealth effects and distribution | Asset prices rise, benefiting asset holders | Real, and the most politically consequential effect |

**What QE is not:** it is not "printing money" in the sense of financing
government spending. The government still issues bonds; the central bank buys
existing ones in the secondary market. Consolidated across government and
central bank, QE looks like swapping long-dated debt for overnight
reserve-rate debt — a debt management operation. That consolidated view is
itself contested, but it is the clearest way to see why QE did not behave the
way "printing money" intuitions predicted.

**The record:** the Fed's balance sheet went from roughly $900bn in mid-2008
to about $4.5tn by 2014, and around $9tn by 2022. Core inflation ran *below*
target for most of 2009-2019. On 15 November 2010 an open letter to Ben
Bernanke, signed by more than twenty economists and commentators, appeared in
the *Wall Street Journal* warning of currency debasement and inflation. It was
a clean, dated, public prediction, and it failed. **This is the strongest
single piece of evidence against the naive quantity theory, and it should be
weighed against the fact that 2021 inflation arrived anyway — by a different
mechanism.**

---

## Why 2020-21 was different

The distinction matters and is usually missed.

| | **2009-2014 QE** | **2020-21 pandemic response** |
|---|---|---|
| Who received the new money | Financial institutions swapping assets | **Households and firms, directly** |
| Instrument | Asset purchases | Fiscal transfers, cheques, furlough, PPP loans |
| Effect on broad money | Small | US M2 grew roughly 25% in 2020 — the largest single-year increase in the series |
| Effect on spending | Muted; the money stayed in portfolios | Direct; and spending was channelled into goods because services were closed |
| Supply side | Intact | Severely disrupted |

**"They printed money in 2009 and nothing happened, then they printed money in
2020 and we got inflation" is not a contradiction. They were different
operations.** One was an asset swap in the financial circuit; the other put
purchasing power into deposit accounts against a constrained supply of goods.

---

## The sectoral balances identity

This is **an accounting identity.** It is true by construction. It contains no
causal claim whatsoever.

From the national accounts:

$$(S - I) + (T - G) + (M - X) = 0$$

Or, more legibly:

> **Private sector balance + Government balance + Foreign sector balance = 0**

If the domestic private sector wants to save more than it invests, and the
rest of the world is running a surplus against you, **the government's deficit
is the arithmetic residual.** Not a policy choice — an identity. Wynne
Godley's stock-flow-consistent modelling built on this, and it is why some
Levy Institute economists warned about US private-sector deficits before both
2001 and 2008.

**What it does tell you:** all three balances cannot be in surplus at once.
Every country cannot run a trade surplus. "Everyone should save more" is
arithmetically impossible in aggregate at unchanged output — the paradox of
thrift restated as bookkeeping.

**What it does not tell you:**
- whether any particular deficit is desirable
- whether a deficit is sustainable
- what the interest cost will be
- what the inflation consequence is
- which balance is causally driving which

**Both sides abuse this.** Deficit hawks ignore it entirely and reason as
though a government were a household. Deficit doves invoke it and slide from
"the deficit is the residual" to "therefore the deficit is fine," which does
not follow from an identity. **If someone derives a policy conclusion from an
accounting identity without adding an empirical premise, they have made an
error, and it is the same error regardless of their politics.**

---

## Government spending mechanics

The operational description is not contested; the interpretation is.

1. The Treasury holds an account at the central bank.
2. Spending debits that account and credits a commercial bank's reserve
   account, which credits the recipient's deposit. **Reserves and broad money
   both rise.**
3. Taxation reverses it: deposits and reserves both fall.
4. Bond issuance drains the reserves created by deficit spending, swapping
   them for interest-bearing securities.

Operationally, in a system where the central bank must supply reserves to hold
its rate target, spending is not "funded by" prior taxation in a mechanical
sense. **But institutional rules impose real constraints anyway:** most
central banks are legally barred from directly financing the treasury (in the
EU, Article 123 TFEU), debt ceilings and no-overdraft rules exist, and bond
markets price sovereign risk. Whether these constraints are "real" or
"self-imposed" is exactly the MMT argument, and it is partly semantic and
partly not.

---

## MMT, steelmanned and then challenged

**What MMT actually claims** (Mosler, Wray, Kelton, Mitchell; roots in Knapp,
Lerner's "functional finance" 1943, Godley and Minsky):

- A government issuing debt in its own free-floating currency cannot be forced
  into *involuntary nominal* default. It can always meet a payment denominated
  in a unit it creates.
- Therefore "how will we pay for it?" is the wrong question. The right one is
  "are the real resources — labour, materials, capacity — available?"
- The binding constraint is **inflation**, not financing.
- Taxes serve to create currency demand, to withdraw purchasing power, and to
  shape distribution — not to fund spending mechanically.
- A job guarantee acts as an automatic stabiliser and a nominal anchor.

**The strongest objections:**

- **The inflation constraint binds much earlier and less legibly than MMT's
  framing implies.** Identifying spare capacity in real time is exactly what
  central banks are bad at — see inflation.md.
- **Withdrawing stimulus requires raising taxes, and legislatures do not do
  this promptly.** MMT's stabilisation mechanism assumes a fiscal authority
  behaving in a way no fiscal authority has ever behaved.
- **Exchange rates and imported inflation** are underweighted. Small open
  economies with import dependence face a constraint that the US does not.
  MMT's core case is strongest precisely for the country least in need of it.
- **Most of MMT's operational description is uncontroversial** — central
  bankers agree about balance sheet mechanics. The dispute is whether the
  policy conclusions follow, and largely they do not follow *from the
  mechanics alone*; they require additional empirical premises about the
  inflation-capacity relationship that are TIER 2 at best.

**Fair scoring:** MMT was right that QE would not cause inflation and right
that the deficit-crisis warnings of 2010-2019 were overblown. Its critics were
right that the 2021 fiscal expansion had a larger inflationary effect than MMT
proponents generally allowed. Neither side gets to claim the decade.

---

## Where the popular story is wrong

| Belief | Reality |
|---|---|
| "Banks lend out your deposits" | Lending creates deposits. Both balance sheet sides expand simultaneously |
| "The money multiplier" | Not how it works; several countries have zero reserve requirement |
| "The government prints money to fund itself" | It issues bonds; the central bank buys existing ones on the secondary market. Direct monetary financing is usually illegal |
| "QE is printing money" | It is an asset swap. Broad money rises only when purchases are from non-banks, and the seller is no richer |
| "QE caused the 2021 inflation" | The mechanism most economists point to is the *fiscal transfers* plus supply disruption. QE from 2009-2019 produced no such inflation |
| "There's a fixed amount of money and the rich have it" | The stock is endogenous and expands with credit. This changes the argument about distribution without weakening it |
| "Reserves are money sitting idle that banks should lend out" | Reserves cannot leave the interbank circuit |
| "A government is like a household" | A household cannot issue the unit its debts are denominated in. But a government also faces inflation and exchange rate limits a household does not. **Both halves of this get ignored, by opposite camps** |
| "Money printing always causes inflation" | 2009-2019 in the US, Europe and Japan is a large counterexample. The relationship is conditional on capacity, expectations and where the money lands |
| "Deficits are always paid for by future taxes" | A theoretical claim (Ricardian equivalence), not an identity, and empirically it holds only weakly |
| "Fractional reserve banking is a fraud" | It is maturity transformation, which is genuinely fragile — see banking-and-crises.md — but the fraud framing depends on the multiplier story, which is wrong |

---

## Open questions

- [ ] If reserves don't constrain lending, what is the actual transmission
      mechanism from the policy rate to credit volume? Price effects clearly
      operate, but the empirical decomposition is weak.
- [ ] Does the consolidated government-plus-central-bank view of QE hold when
      the central bank is legally independent and pays interest on reserves?
- [ ] Was the 2021-23 inflation mostly the *composition* of the stimulus
      (direct to households) or its *size*? The counterfactual is unavailable.
- [ ] Would full-reserve banking (Fisher's 1936 *100% Money*; the Chicago Plan;
      Switzerland's Vollgeld referendum, rejected roughly 75-25 in June 2018)
      eliminate instability or just relocate it into unregulated shadow credit?
      The historical prior favours relocation.
- [ ] What does a retail CBDC do to bank funding in a crisis? A frictionless
      run into central bank money is a plausible and largely untested risk.
- [ ] Why has the correct description of money creation, published by central
      banks over a decade ago, still not reached the textbooks or the press?
