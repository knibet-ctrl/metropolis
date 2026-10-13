# Banking and Crises

> **STATUS: TIER 1 on the mechanism of bank fragility. TIER 1 on the
> historical pattern. TIER 2 on causes of any specific crisis. TIER 2-3 on
> prevention.** Note the shape: we understand *why* banks are fragile far
> better than we understand how to stop them failing.

> Written from general knowledge without source verification.

---

## What a bank does

Four things, of which the first is the dangerous one:

| Function | Description | Risk created |
|---|---|---|
| **Maturity transformation** | Borrow short (deposits, redeemable now), lend long (mortgages, 25 years) | **Structural insolvency-on-demand.** No bank can pay all depositors at once. This is not a flaw in the design; it *is* the design |
| **Liquidity transformation** | Turn illiquid loans into liquid claims | Runs |
| **Credit assessment** | Specialised information about borrowers | Destroyed when a bank fails — Bernanke's key 1983 point |
| **Payments** | Operate the settlement system | Systemic: a failing bank breaks other people's transactions |

**Diamond and Dybvig (1983)** formalised it: a bank offering demandable
deposits has *two* equilibria. In one, nobody runs and everything is fine. In
the other, everyone runs and everything is not — and running is individually
rational once you expect others to. **The run is self-fulfilling and requires
no bad news about the bank's assets.** Diamond, Dybvig and Bernanke shared the
2022 Nobel for this line of work.

The implications are stark: a solvent bank can fail; the fundamentals do not
have to be bad; and the only escapes are a credible promise (deposit
insurance) or a credible lender (the central bank).

---

## The two escapes

**Deposit insurance.** The FDIC was created by the Banking Act of 1933 after
roughly 9,000 US bank failures in 1930-33. It works — bank runs by retail
depositors essentially stopped in the US for fifty years. The cost is moral
hazard: insured depositors have no reason to monitor, so supervision and
capital requirements must substitute for market discipline. **The trade-off is
real and unavoidable; there is no design that gets stability without either
moral hazard or fragility.**

**Lender of last resort.** Walter Bagehot, *Lombard Street* (1873): in a
panic, lend freely, at a penalty rate, against good collateral. Note two
things usually omitted: Henry Thornton got there in 1802, and Bagehot was
*describing* what the Bank of England already did while urging it to admit it.
The penalty rate is the part most often quietly dropped in practice.

---

## The pattern

**Reinhart and Rogoff, *This Time Is Different* (2009)** — eight centuries,
66 countries. The finding is that financial crises are not exotic. They rhyme.

| Stage | Marker |
|---|---|
| Capital inflow surge | Cheap external funding |
| Credit boom | Private debt/GDP rises sharply |
| Asset price boom | Usually property, sometimes equities |
| A story about why it's different this time | Financial innovation, a new economy, better risk management |
| Trigger | Often minor and unrelated |
| Bust | Deeper and longer than a normal recession; recovery slower |
| Sovereign stress | Bank losses migrate onto the public balance sheet |

**The single most reliable predictor is the rate of change of private credit
to GDP.** Schularick and Taylor's "Credit Booms Gone Bust" (2012) and the BIS
work of Claudio Borio and William White support this. It is about as close to
a robust empirical regularity as macro-finance offers — and it is still not
good enough to time anything.

---

## The Reinhart-Rogoff episode — an epistemics case study

**Separate the book from the paper. This is now itself a common error.**

*This Time Is Different* (2009) is a careful piece of economic history whose
main findings largely stand.

"Growth in a Time of Debt" (*AER Papers & Proceedings*, 2010) is a different
object: a short conference paper claiming average growth falls sharply — to
roughly -0.1% — once gross government debt exceeds 90% of GDP.

It was cited immediately and heavily. Olli Rehn used it at the European
Commission; Paul Ryan cited it in the US budget debate; it became a load-
bearing number in the case for austerity across Europe.

In 2013, Thomas Herndon, a graduate student at UMass Amherst, obtained the
spreadsheet as a class assignment and found three problems (published with
Michael Ash and Robert Pollin):

1. **An Excel formula error** that omitted five countries from an average row.
2. **An unusual weighting scheme** — each country counted equally regardless
   of how many years it contributed, so a single bad year for New Zealand
   carried the same weight as nineteen years of UK data.
3. **Selective data exclusion** of some early post-war country-years.

Corrected, the cliff at 90% disappears. A mild negative association remains.

**The lessons, and they are not the ones usually drawn:**

- The paper was policy-relevant for three years before anyone replicated it.
  **Nobody had checked.** That is the scandal, more than the error.
- Even with correct arithmetic, **the causal direction is unresolved**: does
  high debt slow growth, or does slow growth raise debt ratios? Almost
  certainly both. The corrected correlation does not settle it either way.
- Austerity was not caused by a spreadsheet. It was a political programme
  looking for a citation, and it would have found another. **Attributing
  European austerity to an Excel error is a comforting story that lets
  everyone off.**
- Reinhart and Rogoff acknowledged the coding error and disputed the rest.
  Treating them as frauds is unfair; treating the 90% threshold as a finding
  is worse.

---

## Five crises

### 1929-33 — the one that made macroeconomics

Margin lending fuelled the run-up; the Fed tightened in 1928-29 to curb
speculation. The crash (24 and 29 October 1929) was not the disaster. **The
disaster was the four waves of banking panics from 1930 to 1933** — roughly
9,000 bank failures, and a fall of about one third in the US money stock.

- **Friedman and Schwartz, *A Monetary History of the United States* (1963):**
  the Fed had the tools and did not use them. A monetary policy failure.
- **Bernanke (1983):** add a non-monetary channel — bank failures destroyed
  irreplaceable information about borrowers, so credit intermediation
  collapsed independently of the money stock.
- **Eichengreen, *Golden Fetters* (1992):** the gold standard transmitted
  deflation internationally and prevented any national response. See
  the-control-group.md.

These are complements, not rivals, and together they are close to TIER 1.

### 1987 — the crash that didn't matter

19 October 1987: the Dow fell 22.6% in one day, still the largest single-day
percentage fall. Portfolio insurance — automated selling as prices fell —
mechanically amplified it. The real economy barely noticed.

**The lesson is the contrast:** a 22.6% one-day equity fall with no credit
event did almost nothing. A far smaller shock *inside the credit system* in
2007-08 nearly ended the financial system. **Asset prices are not the
transmission mechanism. Leverage and funding are.**

### 1998 — LTCM

Long-Term Capital Management: John Meriwether's fund, with Robert Merton and
Myron Scholes (Nobel laureates, 1997) on the board. Convergence trades —
small spreads, enormous leverage, roughly 25:1 on balance sheet and far higher
in notional terms.

Russia's default in August 1998 triggered a flight to quality. Spreads that
the models treated as mean-reverting and weakly correlated all widened
together. **The correlation structure estimated on normal periods failed
exactly in the abnormal period, which is the only period that matters.**

The New York Fed convened fourteen banks to recapitalise the fund with about
$3.6bn. No public money — but public coordination. **Second lesson, and the
uncomfortable one: the rescue arguably taught the market that this is what
happens, which is a moral hazard cost you cannot measure.**

### 2008 — in detail

**The chain:**

| Link | What happened |
|---|---|
| Housing | US house prices peaked around 2006 after a long boom |
| Origination | Subprime lending with weak documentation, teaser rates, and originators who did not retain the risk |
| Securitisation | Mortgages → MBS → CDO → CDO-squared. Each layer obscured the underlying credit |
| Ratings | Issuer-pays model; structurally conflicted; correlation assumptions in the models were badly wrong |
| Funding | Short-term repo and asset-backed commercial paper funding long-dated assets — **maturity transformation outside the regulated banking system.** Gorton and Metrick called it a run on repo |
| Leverage | Investment bank leverage in the 30:1 range |

**The sequence:** BNP Paribas froze three funds (August 2007) — the first
clear signal. Northern Rock, the first UK bank run since 1866 (September
2007). Bear Stearns absorbed by JPMorgan with Fed support (March 2008). Fannie
Mae and Freddie Mac into conservatorship (7 September 2008). **Lehman Brothers
filed for bankruptcy on 15 September 2008** — the largest in US history, over
$600bn in assets. AIG rescued the next day with an $85bn facility, because its
credit default swap book had no reserves behind it. The Reserve Primary Fund
broke the buck on 16 September, triggering a run on money market funds. TARP —
$700bn — passed 3 October after an initial rejection.

**On causes, the honest position is that they are contested.** Candidates:
loose Fed policy after 2001 (John Taylor); the global savings glut (Bernanke);
regulatory failure and the shadow banking gap; agency problems throughout the
securitisation chain; the ratings agencies; and simple leverage. **The
Financial Crisis Inquiry Commission's 2011 report split 6-4 with two separate
dissents. The official inquiry could not agree on what caused it.** Anyone
telling you the cause with confidence is selecting.

**Whether letting Lehman fail was a mistake is still argued.** Officials said
they lacked legal authority to rescue it; critics say they chose to make an
example and were shocked by the result. Both may be true.

### 2023 — SVB, and the speed problem

Silicon Valley Bank was **not** a credit failure. Its assets were Treasuries
and agency MBS — the safest paper there is, in credit terms. It was a
**duration** failure: it had bought long-dated securities at 2020-21 yields,
and the 2022 rate rises produced large unrealised losses, parked in a
held-to-maturity book where they were not marked.

Two amplifiers:
- **Concentration.** Deposits came overwhelmingly from VC-backed tech
  companies — a single, tightly networked community.
- **Uninsured deposits.** Roughly 94% of deposits exceeded the FDIC limit, so
  nearly every depositor had a rational reason to run.

On 8 March 2023 SVB announced a securities loss and an equity raise. On 9
March, depositors attempted to withdraw roughly $42bn **in a single day** —
coordinated over group chats and Twitter, executed by mobile app. The bank
failed on 10 March. Signature Bank followed; Credit Suisse was absorbed by UBS
on 19 March. Regulators invoked the systemic risk exception to cover *all*
deposits, creating de facto unlimited insurance without legislation.

**The genuinely new lesson: run speed has changed by an order of magnitude.**
Deposit insurance, liquidity ratios and resolution regimes were designed
around queues outside branches. Bagehot's framework assumed a bank had days.
It now has hours. Almost none of the regulatory architecture reflects this.

---

## Minsky

Hyman Minsky's **financial instability hypothesis**: stability is
destabilising. A long period without losses makes conservative finance look
irrational and aggressive finance look smart. Balance sheets migrate through
three stages:

| Stage | Can service | Fragility |
|---|---|---|
| **Hedge finance** | Interest and principal from cash flow | Robust |
| **Speculative finance** | Interest only; must roll principal | Vulnerable to funding conditions |
| **Ponzi finance** | Neither; depends on asset appreciation | Fails on any price decline |

The system drifts from hedge toward Ponzi *during good times*, endogenously.
No external shock is required. Paul McCulley coined "Minsky moment" in 1998.

**Caveat, and it is a real one:** Minsky's framework is descriptively
compelling, resists formalisation, and makes almost no point predictions. It
has been retrofitted to every crisis since. A theory that explains everything
after the fact and times nothing beforehand should be held as a lens, not a
model. Kindleberger's *Manias, Panics, and Crashes* (1978) is the historical
elaboration — displacement, boom, euphoria, distress, revulsion — and has the
same virtue and the same weakness.

---

## Regulation, and what's unresolved

| Regime | Aim | Problem revealed |
|---|---|---|
| Glass-Steagall (1933) | Separate commercial and investment banking | Repealed 1999; whether repeal caused 2008 is disputed — most of the failures were institutions Glass-Steagall would not have separated |
| Basel I (1988) | Minimum capital, crude risk weights | Gameable; drove regulatory arbitrage into off-balance-sheet vehicles |
| Basel II (2004) | Risk-sensitive, internal models, credit ratings | **Procyclical and dependent on exactly the ratings and models that failed** |
| Basel III (2010+) | Higher capital, leverage ratio, liquidity ratios (LCR, NSFR) | Complex; SVB was partly exempt through tailoring; the interest-rate risk gap was not closed |
| Dodd-Frank (2010) | Resolution regimes, stress tests, derivatives clearing | Concentrates risk in central counterparties — which are now themselves too big to fail |

**Live disputes:**
- *Does higher capital reduce lending?* Admati and Hellwig (*The Bankers' New
  Clothes*, 2013) argue no — equity is funding, not idle reserves, and the
  claim otherwise is a Modigliani-Miller error the industry has an interest in
  repeating. The industry disagrees. The empirical literature leans toward
  Admati and Hellwig on the long run and finds transition costs in the short.
- *Are stress tests informative?* They have become known-in-advance compliance
  exercises. SVB was not subject to the tightest ones.
- *Has risk simply moved?* Non-bank financial intermediation is now roughly
  half of global financial assets. **The next crisis has no obvious reason to
  originate in a regulated bank.**

---

## Where the popular story is wrong

| Belief | Reality |
|---|---|
| "Banks failed in 2008 because of bad mortgages" | Losses on subprime were large but not large enough to explain it. **The mechanism was a run on short-term wholesale funding.** Leverage and liquidity, not credit losses, did the damage |
| "The 1929 crash caused the Depression" | The crash was survivable. The 1930-33 banking panics and the one-third contraction of the money stock were not |
| "Deregulation caused 2008" | Partly, but the biggest failures — Bear, Lehman, AIG, the GSEs — were in areas Glass-Steagall never covered. The bigger gap was the *unregulated* shadow system |
| "Bailouts made bankers rich at taxpayer expense" | TARP was largely repaid with a profit to the Treasury; the AIG and GSE interventions returned money. **The real cost was distributional and moral-hazard-shaped, not fiscal** — households lost homes while institutions were made whole. That's a legitimate grievance stated in the wrong currency |
| "Nobody saw it coming" | Rajan's 2005 Jackson Hole paper (dismissed at the time), Shiller, Borio and White at the BIS, Baker, Roubini. **The problem was not absence of warning but absence of consequence for ignoring it** |
| "SVB failed because of risky investments" | It failed holding US Treasuries. Duration risk, deposit concentration and uninsured deposits |
| "Deposit insurance means my money is safe in any amount" | Only up to the cap. In 2023 the cap was overridden by discretion, which is not the same as a guarantee |
| "Reinhart-Rogoff was debunked, so debt doesn't matter" | The 90% cliff was debunked. A milder association survives and the causation runs both ways |
| "Bank runs take days" | They now take hours. This is genuinely new |

---

## Open questions

- [ ] Can maturity transformation be made safe, or is fragility the price of
      the service? Narrow banking eliminates it in regulated banks and
      probably recreates it outside them.
- [ ] What is the correct deposit insurance limit when a run can execute in an
      afternoon? Is any cap credible if it is overridden in every crisis?
- [ ] Is the credit-growth indicator good enough to act on ex ante, given that
      acting means deliberately slowing a booming economy on a signal that has
      false positives?
- [ ] Have central counterparties concentrated systemic risk rather than
      dispersing it?
- [ ] Would a resolution regime actually be used on a G-SIB in real time, or
      would the systemic risk exception be invoked again?
- [ ] Does Minsky's hypothesis have any testable implication that
      distinguishes it from "credit booms precede busts"?
