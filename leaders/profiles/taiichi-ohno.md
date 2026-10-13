# Taiichi Ohno (1912–1990)

*Architect of the Toyota Production System. The notebook's case for pushing authority to where the information actually is.*

---

## What he inherited

Poverty at national scale, and an explicit productivity gap.

He joined Toyoda Automatic Loom Works in 1932 and moved to Toyota Motor in 1943.
Post-war Japan had no capital, no raw materials, a destroyed industrial base,
and a domestic market too small and too varied to support long production runs
of a single model.

**Toyoda Kiichiro** reportedly told his engineers that Japanese productivity was
roughly a ninth of America's, and that they had three years to catch up. That
gap was the design brief.

Ohno's constraint set was therefore the opposite of Ford's: **no money to hold
inventory, no space to store it, and a requirement to build many variants in
small volumes.** Everything in the Toyota Production System follows from
inverting Ford's assumptions under scarcity.

---

## Stories worth knowing

**The supermarket.** The origin of just-in-time. Visiting the United States,
Ohno was reportedly less impressed by the car factories than by **American
supermarkets** — where customers took what they wanted, when they wanted it, and
shelves were replenished only to replace what had been taken.

That is a **pull system**. Nothing is produced until downstream demand consumes
something. He applied it to manufacturing: each process withdraws parts from the
preceding one only as needed, and the preceding process makes only what has been
withdrawn.

The signalling device was the **kanban** — a card attached to a bin of parts.
When the bin is emptied, the card goes back upstream and authorises replacement.
A physical, unfakeable, self-regulating information system requiring no computer
and no manager.

**Genchi genbutsu — "go and see for yourself."** The core cultural instruction.
Managers were expected to go to the *gemba* — the actual place where the work
happens — and observe, rather than rely on reports.

The training exercise associated with him is the **"Ohno circle"**: he would
chalk a circle on the factory floor and instruct a new engineer to stand in it
and watch, for hours, sometimes most of a day, until they could see the waste
they had walked past every day for years.

**This is mechanism #1 turned into a mandatory management practice.** The
notebook's playbook says get direct contact with reality weekly; Ohno made it
the job description.

**The andon cord.** Any worker who saw a defect could pull a cord to signal a
problem — and if it was not resolved within the cycle, **the line stopped**.

Western manufacturers considered this insane. Line stoppage was the cardinal
sin; that is why inspection was placed at the end.

The logic was that a defect passed downstream becomes exponentially more
expensive to fix, and — more importantly — that a stopped line **forces the
organisation to find the root cause immediately**, while the evidence is present
and fresh.

*Precision note: the cord signals and typically halts the line at a fixed
position in the cycle, not instantaneously across the plant. The popular
"any worker stops the whole factory" version is simplified.*

**The deeper point is about authority.** The person best placed to detect a
defect is the person doing the work. Toyota gave that person the power to halt
the most expensive asset in the building. **Almost no organisation does the
equivalent, and almost every organisation's quality problems trace to that
refusal.**

**The Five Whys.** Ask "why" repeatedly to move from symptom to root cause. His
own worked example runs roughly: the machine stopped → the fuse blew → the
bearing seized → it wasn't lubricated → the pump was worn → **there was no
filter on the pump**.

Stopping at any earlier level produces a fix that fails again. Only the last
answer is actionable and permanent.

Most organisations stop at "why one" — replace the fuse — and then treat the
recurrence as bad luck.

**Muda, muri, mura.** He classified waste (*muda*) into seven categories:
overproduction, waiting, transport, over-processing, inventory, motion, and
defects. He regarded **overproduction as the worst**, because it conceals every
other kind of waste — you cannot see a bottleneck when there is a buffer of
inventory in front of it.

He paired it with *muri* (overburden of people or machines) and *mura*
(unevenness), arguing that attacking waste without smoothing flow just moves the
problem.

**SMED — single-minute exchange of die.** Developed with **Shigeo Shingo**.
Changing the dies on a large press traditionally took hours, which forced long
production runs to amortise the changeover.

They reduced changeover times dramatically — from hours to minutes — by
separating work that could be done while the machine was still running from work
that required it stopped, and then converting as much as possible into the
former.

**This is a beautiful example of attacking the real constraint.** Everyone
assumed long runs were necessary because changeovers were slow. Ohno treated
changeover time as a variable rather than a fact, and the entire economics of
small-batch production changed.

**Kaizen and respect for people.** Continuous improvement generated by the
people doing the work, in large volumes of small changes. Toyota's suggestion
systems have historically processed very large numbers of employee proposals
with high implementation rates.

The pairing that is usually omitted: the system depended on **employment
security**. Workers will not automate away their own tasks if doing so gets them
fired. Toyota's post-1950 commitment to long-term employment was not
sentimentality; it was a precondition for the improvement engine to function.

**He was disliked.** Ohno was reportedly abrasive, demanding, and unpopular on
the shop floor for years. Toyota did not promote him to the very top. The system
took roughly **thirty years to mature**, and for much of that time it looked
like an eccentric internal project.

---

## How he differed from his contemporaries

Compare with **Ford's Highland Park and River Rouge** — mass production of
identical units, large inventory buffers, inspection at the end, and authority
concentrated in engineers and managers. Ford's system was superb for one product
at enormous volume, and Ohno's constraints made it unusable.

**Constraint drove the innovation.** Toyota could not afford inventory, so it
invented a system that did not need it — and that system turned out to be
better in general, not merely better under poverty. This is a recurring notebook
pattern: **the binding constraint, taken seriously, produces the innovation.**

Compare with **W. Edwards Deming**, whose statistical quality teaching in Japan
from 1950 was hugely influential and who is often credited alongside Ohno.
Deming supplied the statistical and philosophical framework; Ohno supplied the
physical shop-floor mechanisms.

Compare with **Western manufacturers in the 1980s**, who studied Toyota and
copied the visible artefacts — kanban cards, andon boards, quality circles —
without the underlying commitments to employment security, worker authority, and
management presence on the floor. **Most of those transplants failed**, which is
the notebook's cargo-cult warning made concrete.

**NUMMI**, the GM–Toyota joint venture in Fremont from 1984, is the decisive
evidence. GM's worst-performing plant, reopened with substantially **the same
workforce** under the Toyota system, became one of its best. The variable was
the system, not the people.

---

## Mechanisms

| # | Mechanism | Evidence |
|---|---|---|
| 1 | Direct contact with reality | *Genchi genbutsu*; the Ohno circle |
| 10 | The real constraint | Overproduction as the master waste; SMED attacking changeover time |
| 7 | Institution-building | A system that outlived him and was copied globally |
| 2 | Time horizon | Roughly thirty years to maturity |
| **—** | **Error correction — THE CENTRAL FEATURE** | The andon cord is a structural bad-news channel with teeth |

---

## The price

His own: unpopularity, obstruction, and decades of slow work without recognition
until late in life.

Others': the system is demanding. Critics have documented intensity of work
pace, stress, and the pressure that continuous improvement places on individual
workers — the phrase "management by stress" comes from that critique. Just-in-time
also pushes inventory risk onto suppliers, and the fragility of lean supply
chains was exposed by the 2011 Tōhoku earthquake and again by the pandemic.

---

## Where the popular story is wrong

- **"Any worker can stop the whole factory instantly."** Simplified. The cord signals; the line halts at a fixed point if unresolved.
- **"Ohno invented lean."** "Lean" is a term coined by MIT researchers (Krafcik, and Womack/Jones/Roos) to describe what Toyota did. Ohno never used it.
- **"He invented it alone."** **Shigeo Shingo**, **Eiji Toyoda**, and the *jidoka* concept from **Sakichi Toyoda's** self-stopping looms are all foundational. Ohno synthesised.
- **"JIT means zero inventory."** It means inventory sized to actual flow. Toyota holds strategic buffers where the risk warrants it — a lesson it re-learned after 2011.
- **"It's a manufacturing technique."** It is a management philosophy about authority and information. The tools without the authority shift do not work, which is why so many copies failed.

---

## The pattern

**Ohno is the notebook's most practically important builder, and the least
famous person in the collection.**

His contribution is the resolution of a problem every organisation has: **the
person who knows about the problem is not the person with the authority to act
on it.** Information sits at the bottom; power sits at the top; and the gap
between them is where defects, waste and failure accumulate.

His answer was not to improve reporting. It was to **move the authority down to
where the information already was**, and to make stopping the line the expected
behaviour rather than the punishable one.

Set against `failure-modes.md`, this is the single clearest instance of the
notebook's most reliable finding: **an error-correction channel with real teeth
separates the success sample from the failure sample more consistently than
talent does.** Mao had no andon cord. Ford destroyed his own. Toyota built one
and hung it above every workstation.
