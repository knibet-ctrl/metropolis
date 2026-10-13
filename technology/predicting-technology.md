# Predicting Technology — Why Forecasts Fail

> **Status: TIER 1** that technology forecasts have a poor track record and
> that diffusion follows S-curves. **TIER 1–2** on Wright's law (cost falls
> with cumulative production) as the most reliable available regularity.
> **TIER 2** on the Amara pattern, which is a well-observed regularity without
> a rigorous test. **TIER 3** on any specific forecast, including every one
> currently being made about AI.

**Written from general knowledge without live source verification.** Several
famous quotations below are of disputed provenance and I flag each one. This is
a file about false confidence, so it would be embarrassing to repeat apocrypha.

**Read alongside `risk/forecasting.md`.** Everything Tetlock found about
political forecasting applies here, plus additional failure modes specific to
technology.

---

## Amara's law

**Roy Amara (Institute for the Future):**

> **"We tend to overestimate the effect of a technology in the short run and
> underestimate the effect in the long run."**

Both halves matter and people usually quote only the half that suits them.

| Technology | Short-run overestimate | Long-run underestimate |
|---|---|---|
| Electricity | Immediate factory productivity gains | Reorganised manufacturing, urban form, domestic labour, the working day |
| Railways | The 1840s British railway mania and crash | National markets, standard time, mass tourism, modern logistics |
| The internet | 1999–2000 valuations; "everything by 2001" | Retail, media, advertising, dating, the collapse of local news, remote work |
| Mobile phones | 1990s expectations of a business-executive product | The primary computing device for most of humanity |
| Self-driving cars | "By 2020" — Musk said this repeatedly from 2015 | Commercial driverless robotaxi services now operate in several cities. **Directionally right, calendrically wrong by a decade or more. Textbook Amara** |
| Paperless office | Predicted from the 1970s; paper use **rose** after email | Office paper consumption did eventually peak (around the late 2000s in the US) and fall. **The prediction was right and roughly forty years early** |

**The mechanism behind both halves is the same: complementary innovation.**
Short run, the complements don't exist yet, so the technology underperforms.
Long run, the complements arrive and compound in ways nobody enumerated.

---

## The dynamo — the single most useful analogy in the notebook

**Paul David, "The Dynamo and the Computer" (*AER*, 1990).**

Electric motors were commercially available to factories from the 1880s.
Manufacturing productivity did not jump until the **1910s–1920s**. Why?

Because the gain did not come from swapping a steam engine for an electric one
driving the same **line shaft**. It came from abandoning the shaft entirely:

| Steam-era factory | Electrified factory |
|---|---|
| One prime mover, central | **Unit drive** — a motor per machine |
| Power distributed by belts from an overhead line shaft | Power distributed as wires |
| Machines placed by proximity to the shaft | **Machines placed by workflow** |
| Multi-storey, to keep shaft runs short | **Single-storey, sprawling, with overhead cranes** |
| Everything runs when the shaft runs | Machines run independently |
| Lighting poor (shafts and belts everywhere) | Natural light and overhead lighting possible |

**The reorganisation was the innovation.** It required new factory buildings,
new plant layouts, new management practice, and — critically — **a generational
turnover of factory managers who could not imagine the new layout.**

**Roughly forty years.** Hold this number when reading the AI section of
case-computing-and-ai.md.

---

## Famous wrong predictions — dismissals

**Handle with care. Several of the most-quoted are apocryphal or stripped of
context, and repeating them uncritically is exactly the epistemic failure this
notebook is about.**

| Prediction | Status |
|---|---|
| "This 'telephone' has too many shortcomings to be seriously considered as a means of communication" — attributed to a Western Union internal memo, 1876 | **Provenance doubtful.** No original document is reliably produced. Treat as apocryphal |
| "I think there is a world market for maybe five computers" — Thomas Watson, IBM, 1943 | **Almost certainly apocryphal.** No source |
| "There is no reason for any individual to have a computer in his home" — **Ken Olsen, DEC, 1977** | **Real quotation, routinely misused.** Olsen was talking about computers controlling household functions, not personal computers, and objected to the interpretation for the rest of his life. **Note that DEC nevertheless died of the PC, so the irony survives even though the quotation doesn't** |
| **Lord Kelvin**: heavier-than-air flying machines are impossible (1895); X-rays will prove to be a hoax | Real, and instructive — a first-rank physicist, wrong on both, within his own field |
| **Clifford Stoll**, "The Internet? Bah!", *Newsweek* 1995 | **Real, and worth reading.** He predicted no online commerce, no digital newspapers, no virtual communities of substance. **His reasoning was good and his conclusion was wrong**, which is far more interesting than a stupid prediction |
| **Robert Metcalfe**, 1995: the internet would collapse catastrophically in 1996 | Real. He publicly ate a printed copy of the column in 1997. **Ethernet's inventor, wrong about network scaling** |
| **Paul Krugman**, 1998: the internet's economic effect would be "no greater than the fax machine's" | Real; written for a magazine that solicited provocation, which he has pointed out. Still a Nobel laureate being badly wrong about a general-purpose technology |
| **Steve Ballmer**, 2007: the iPhone has "no chance" of significant market share | Real. Notable because his *reasoning* — no keyboard, expensive, no enterprise email story — was correct about the product as it then existed |

**The pattern in the good ones (Stoll, Ballmer): they evaluated the technology
as it was, not as the fifth version would be, and they underweighted price
declines and complementary ecosystems. That is a specific, correctable error.**

---

## Famous wrong predictions — enthusiasms

**The under-collected half. Failure to remember these is why every hype cycle
feels novel.**

| Prediction | What happened |
|---|---|
| **"Too cheap to meter"** — Lewis Strauss, AEC chairman, 1954 | **Frequently misquoted.** He was addressing science writers about atomic power generally, plausibly with fusion in mind, not promising cheap fission electricity. **The misquotation has done more damage to nuclear power's credibility than any accident** |
| **Nuclear-powered everything** | The **Aircraft Nuclear Propulsion** programme ran for over a decade before cancellation in 1961; the **Ford Nucleon** (1958) was a styling model for a nuclear car; **Project Plowshare** proposed excavating harbours with nuclear devices (Operation Chariot, Alaska); atomic gardening was a real hobby |
| **The paperless office** | Paper consumption **rose** after office computerisation — Sellen & Harper, *The Myth of the Paperless Office* (2002), documented increases following email introduction. Then it peaked and declined about forty years after the prediction |
| **Flying cars** | Molt Taylor's **Aerocar (1949) actually flew and was FAA-certified.** Almost nobody bought one. **The constraint was never engineering — it is that a flying car must be a bad car and a bad aeroplane, and requires a pilot's licence and an airfield** |
| **Videophones** | AT&T's **Picturephone** debuted at the 1964 World's Fair, launched commercially in 1970, and reportedly reached a few hundred subscribers against projections of millions. Killed by price and the chicken-and-egg problem. **Video calling arrived forty years later when it was free and bundled with something else** |
| **The Segway** (2001) | Prior hype included investor claims that it would be bigger than the internet and that cities would be redesigned around it. Sold on the order of **140,000 units over about two decades** against a stated ambition of 10,000 per week |
| **MOOCs will replace universities** (2012) | Completion rates in the single-digit percentages; Udacity pivoted to corporate training. Online learning is real and large; it did not replace the credential |
| **"The internet makes geography irrelevant"** | **The opposite happened.** Agglomeration intensified; superstar cities pulled further ahead; talent and capital concentrated. One of the most confidently made and most cleanly falsified predictions of the era |
| **3D printing will end mass manufacturing** (c. 2012) | Genuinely transformative for prototyping, tooling, dentistry, aerospace parts and hearing aids. Did not touch mass production economics |
| **Blockchain will replace institutions** (2017–2022) | Enormous investment. The surviving use cases are narrow. **The trust problem was social, and a technical fix for a social problem does not fit** |

**Both lists together are the point.** Anyone who is reliably contrarian is
reliably wrong half the time. **The failure mode is not optimism or pessimism.
It is confidence.**

---

## S-curves and why diffusion is slow

**Everett Rogers, *Diffusion of Innovations* (1962)** — innovators, early
adopters, early majority, late majority, laggards. Adoption follows a logistic
S-curve. The Bass model (1969) formalised it.

**Griliches (1957) on hybrid corn** is the foundational empirical study and its
finding is the useful one: **the differences between US states in adoption
ceiling and adoption rate tracked profitability, not information.** Farmers who
didn't adopt weren't ignorant; it wasn't worth it for them. **Most apparent
"resistance to technology" is an unmodelled cost-benefit calculation on someone
else's balance sheet.**

### Diffusion rates are not converging on "fast"

| Domain | Speed | Note |
|---|---|---|
| Consumer information goods | **Fast and accelerating.** Smartphones went from launch to majority in most rich countries within about a decade | Low capital cost, no infrastructure change, individual purchase decision |
| Household appliances | Decades | Requires electrification, distribution, income |
| **Physical infrastructure** | **50–100 years.** Electrification, rail, sewers, telephone wireline | Enormous sunk capital, long asset lives |
| **Energy systems** | **Historically 50–100 years.** Vaclav Smil, *Energy Transitions*, is the definitive statement | Scale is the constraint: energy systems are physically enormous |

**Live dispute worth flagging: Smil's "energy transitions are always slow" prior
has been partly wrong recently.** Solar PV and lithium battery cost declines and
deployment rates have run faster than Smil-style extrapolations. **He remains
right that the absolute scale required is staggering and that the incumbent
system does not shrink just because the new one grows. Both halves are true and
the argument is live. Tier 2.**

---

## What actually predicts well: Wright's law

**The one genuine success in technology forecasting, and it deserves more
attention than Moore's law.**

**T.P. Wright (1936)** observed that the labour cost of building aircraft fell
by a consistent percentage with each **doubling of cumulative units produced** —
not with time, and not with R&D spend.

| Formulation | Independent variable | Reliability |
|---|---|---|
| **Wright's law** | **Cumulative production** | **Better** |
| Moore's law | Time | Worse; and Moore's law was partly self-fulfilling |

**Farmer & Lafond (2016)** compared forecasting methods across 50+ technologies
with long cost histories and found **Wright's-law-style forecasts outperformed
time-based extrapolation.** This is a real, usable, out-of-sample-tested result.

**The best-known instance:** solar PV module costs have fallen roughly 20% per
doubling of cumulative installed capacity, sustained over decades — "Swanson's
law." Lithium batteries follow a similar pattern.

**Why it matters conceptually: cost falls because of production, and production
happens because of demand.** So **deployment subsidies are learning
investments**, not just consumption subsidies. Germany's expensive early solar
feed-in tariff bought down the cost curve for everyone, including for countries
that free-rode. That is a substantive policy conclusion derived from a
forecasting regularity, which is rare.

**Caveats:** it fails where physical limits bind (there is no experience curve
for the Carnot limit); it fails when input commodity prices dominate; and it
tells you about *cost*, not about *adoption*, which is the harder question.

### And note what Moore's law actually did

**Dennard scaling — the property that shrinking transistors let you raise clock
speed at constant power — broke around 2005–2006.** Clock speeds stopped rising.
The industry responded with multiple cores, then with specialised parallel
hardware (GPUs), which was the substrate that made large neural networks
trainable. **The end of one scaling law caused the architecture that produced
the current AI moment.** Nobody predicted that chain, and it is a good
illustration of why capability forecasting is hard even when the underlying
trend is quantified.

---

## Why social consequences are structurally harder than technical capability

**This is the central argument of the file. It is not that forecasters lack
imagination. It is that the problem has a different structure.**

| Reason | Explanation |
|---|---|
| **Complementary innovations don't exist yet** | You are forecasting the effect of a system whose components have not been invented. The dynamo case |
| **Organisational adaptation requires generational turnover** | People who built careers on the old layout will not adopt the new one. You are waiting for retirement, not for engineering |
| **Cost curves are convex and small errors compound** | Being 20% wrong about a cost decline rate over 20 years is being an order of magnitude wrong about the price, which puts the technology in a completely different set of applications |
| **The binding constraint moves** | Solve the technical constraint and the binding one becomes regulatory, or social, or an input commodity. You have to forecast which constraint binds next |
| **Reflexivity** | Widely believed forecasts change investment, which changes the outcome. Moore's law worked partly *because* the ITRS roadmap coordinated the industry around it |
| **Interaction effects** | The container mattered because of computers, which mattered because of containers. The unit of analysis is the system, and systems have combinatorial futures |
| **Social licence is unforecastable from specifications** | Google Glass failed on a norm violation. Nothing in the spec sheet contains that |
| **Winner-selection is not quality-selection** | See the-control-group.md. Even a correct capability forecast doesn't tell you who wins |

**The honest conclusion: technical capability forecasting is hard but tractable
— Wright's law works, engineering roadmaps have signal. Social consequence
forecasting is close to intractable at horizons beyond a decade, and the
appropriate response is not better forecasts but robustness.** Cross-ref
`risk/risk-management.md`: build systems that survive being wrong rather than
systems that depend on being right.

---

## Where the popular story is wrong

| Popular story | Correction |
|---|---|
| **"Experts always dismiss new technology"** | Selection bias. Experts also overhyped nuclear, videophones, MOOCs and blockchain. Both lists are long |
| **"Change is accelerating"** | **True for consumer information goods, false for energy, infrastructure and construction**, where diffusion is as slow as it was a century ago and construction productivity has arguably fallen. "Acceleration" generalises from the fastest-moving sector |
| **"They said the telephone would never work"** | Probably apocryphal. The genuinely instructive failures are Stoll and Ballmer, whose reasoning was sound |
| **"Too cheap to meter"** | Misquoted, misattributed as a promise about fission plants, and used for seventy years to discredit an entire technology |
| **"Moore's law is a law of nature"** | It was a roadmap target the industry coordinated around. **Dennard scaling, the part that actually gave you speed, ended around 2005** |
| **"Nobody could have predicted X"** | Often somebody did, in a pile of failed predictions. Prediction is cheap; **calibrated** prediction is what's rare. Cross-ref `risk/forecasting.md` |
| **"The internet killed distance"** | Agglomeration got stronger. This was predicted confidently and falsified cleanly |
| **"We just need better forecasting"** | For social consequences at 20+ year horizons, no. Build for robustness instead |

---

## Open questions

- [ ] Is Amara's law testable? It requires a defensible measure of "expected
      effect" at time t, which nobody has constructed. It may be a
      well-observed pattern that cannot be turned into a claim.
- [ ] Is the ~40-year complementary-adaptation lag a real constant with a
      mechanism (generational turnover of management?), or a coincidence of a
      handful of cases?
- [ ] Are technology forecasters ever scored? Tetlock-style tournaments exist
      for geopolitics. Is there an equivalent with resolved technology
      questions and public track records?
- [ ] Does Wright's law hold for software and for AI capability, or does it
      require a physical unit of production to be meaningful?
- [ ] Is Smil right that energy transitions cannot be fast, or has solar
      falsified the strong version? What would settle this by 2035?
- [ ] Why is construction the one major sector where measured productivity has
      not risen — and in some series has fallen — over seventy years? If we
      cannot explain that, our general theories of technological progress are
      missing something large.
