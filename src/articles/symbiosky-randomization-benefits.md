# The Case for Randomized Jury Selection in Symbiosky

Date: 17-02-2026

## Why Conviction Should Earn Your Ticket, Not Guarantee Your Seat

---

The current Symbiosky model is built on a clean and powerful premise: conviction
voting routes funding toward the most credible contributors. Lock tokens, signal
confidence, let the mechanism sort truth from noise. It works because skin in
the game is a better filter than passive opinion. But conviction alone has a
structural ceiling — and crossing that ceiling may require borrowing one of the
oldest and most resilient ideas in democratic governance.

The future milestone is this: **even participants who demonstrate strong
conviction should face a randomized probability of being selected as a juror**
— roughly a one-in-three or one-in-five chance. Conviction earns you a seat in
the lottery. The lottery decides who actually judges.

---

## The Conviction Reset Loophole

The contract's conviction lifecycle has a natural rhythm: create a conviction,
lock tokens for a duration scaled by level, vote during the allowed window,
then release the stake once the lock expires and begin again. This cycle is
rational and well-designed. It demands real commitment at every stage.

But it also creates an optimization game. A sophisticated participant learns
to time their releases and re-stakes carefully — always maintaining active
conviction during high-stakes proposal windows, releasing during quiet
periods to free liquidity, re-entering before the next important vote. Nothing
in this behavior violates any rule. It is simply playing well.

The problem is that playing well requires resources, attention, and
experience. Participants who have been in the system longer understand the
cycle better. Those with more tokens can afford to maintain larger conviction
positions continuously without worrying about the liquidity cost of locking.
Over time, the gap between sophisticated and unsophisticated participants
widens — not because the system is rigged, but because it is predictable, and
predictable systems reward the people who study them most closely.

Randomization disrupts this without punishing sophistication. The expert
player who times their conviction perfectly still qualifies for the jury pool.
They are simply no longer guaranteed to sit on every jury their tokens make
them eligible for. Their advantage becomes probabilistic rather than
deterministic. They may sit on one jury in three, or one in five. Across
many decisions and many participants, the outcomes reflect the eligible
community rather than its most optimized subset.

---

## Conviction Was Already Pointing in This Direction

Based upon the contract's design choices, it becomes clear that the
we were already thinking about concentration risk — they just stopped
one layer short of randomization.

The minimum vote count requirement, hardcoded at launch to require at least
four distinct participants, exists precisely because a single high-conviction
actor should not be able to unilaterally validate a proposal. The logic is
sound: distributed judgment is more trustworthy than concentrated judgment,
even if the concentrated actor is genuinely credible. The threshold is a
structural guarantee that at least four voices contribute to every score.

The minimum total conviction threshold works alongside this, requiring that
the aggregate weight of participation crosses a meaningful baseline before a
score counts. Again, the instinct is correct: a handful of tiny, low-stakes
votes should not determine the fate of a proposal any more than a single
enormous one.

Both of these mechanisms are anti-concentration measures. They say, in effect,
that the system does not trust any single participant or small cluster of
participants to produce a valid outcome alone. Randomized jury selection is
simply the logical completion of that reasoning. It does not add a new
principle — it enforces the existing one at the selection stage rather than
only at the aggregation stage.

---

## Weight Calculation and Why It Creates a Rich-Get-Richer Dynamic

The voting weight in this system is determined by multiplying conviction level
by staked amount. A participant who stakes more and declares a higher level
casts a proportionally heavier vote. This is intentional and fair as a signal
of commitment — someone willing to lock more tokens at a higher level for
longer is demonstrating stronger belief, and their signal should reflect that.

But consider the compounding effect across many proposals. A participant with
a level-ten conviction and a large stake does not just cast a heavy vote on
one proposal — they cast a heavy vote on every proposal within their vote
budget. Their influence across the entire proposal landscape is proportional
to their resources, not their judgment. A participant with a level-three
conviction and a modest stake might have equally sound judgment about a
specific proposal but will be systematically outweighed regardless.

Randomized selection addresses this asymmetry at the composition level rather
than the weight level. Rather than limiting how heavy any single vote can be
— which would require rewriting the core incentive mechanism — it limits
how reliably any participant can *show up* to cast that heavy vote. The
weight system remains intact. The high-conviction participant still votes with
full weight when selected. But whether they are selected for any particular
jury is a matter of chance, not accumulation. Their resources buy more lottery
tickets. They do not buy a permanent seat.

---


## Coordinated Blocs and the Limits of Anti-Double-Vote Protection

The contract prevents any single conviction from voting on the same proposal
twice, and it caps the total number of proposals any single conviction can
touch across its lifetime. These are important protections against the most
obvious forms of vote manipulation.

What they do not protect against is coordinated participation by multiple
independent convictions controlled by aligned interests. A group of
participants who share goals but hold separate convictions can each vote
independently, each within their personal vote budgets, each triggering no
anti-double-vote checks — and collectively dominate the scoring of proposals
that matter to them while ignoring proposals that do not.

This is not a flaw in the anti-double-vote logic. That logic is correctly
designed to prevent individual manipulation. The coordination attack operates
at a level above the individual — it is a social exploit rather than a
contract exploit. And it is the type of attack that grows more feasible, not
less, as the system matures and high-stakes participants have more to gain
from coordinating.

Randomization is the most effective defense against coordination attacks in
governance systems, and it does not require identifying or penalizing the
coordinators. If a coordinated bloc cannot guarantee which of its members
will be selected for any given jury, coordinating in advance becomes
dramatically harder. The bloc might control thirty percent of the eligible
pool and still find that their members collectively hold a minority on any
particular jury. Across many proposals, their aggregate influence remains
proportional to their participation — but they cannot concentrate it on the
decisions that matter most to them.

---

## What Randomization Preserves

It is worth being equally clear about what randomization does not change,
because the conviction mechanism's strengths are real and should not be
dissolved in the name of fairness.

The cost of entry remains real. Locking tokens at a declared level for a
scaled duration is still the price of eligibility. Casual or speculative
participants who are unwilling to make that commitment remain excluded. The
system continues to filter for genuine stakeholders.

The signal quality of individual votes is unchanged. A level-eight conviction
holder casting a vote on a proposal still contributes a weighted signal
proportional to their stake and level. Randomization determines whether they
vote, not how much their vote counts when they do.

The decay mechanism continues to enforce ongoing engagement. Participants who
go inactive still face erosion of their unprotected balance. The protection
afforded to active participants who maintain conviction stakes still applies.
Randomization does not exempt anyone from these dynamics.

And critically, higher conviction still produces more lottery entries over
time. A level-ten participant with a long lock duration remains eligible across
more proposal cycles than a level-two participant. The probability advantage
of deeper commitment is real — it is simply no longer absolute.

---

## Conviction as Qualification, Selection as Democracy

The most precise way to understand the proposal is as a separation of two
functions that the current system handles with a single mechanism.

Conviction voting currently handles both *qualification* — determining who is
serious enough to participate — and *selection* — determining who actually
does participate in any given decision. These are different tasks with
different optimal solutions. Conviction is the right tool for qualification:
it requires real commitment, punishes insincerity, and scales with genuine
belief. Randomness is the right tool for selection: it is immune to resource
advantages, resistant to coordination, and naturally representative of the
eligible pool.

Splitting these functions does not make either one weaker. It makes each one
do the job it is actually suited for. Conviction earns the right to be in the
draw. The draw decides who sits in judgment. What emerges is a system that is
simultaneously meritocratic at the entry stage and democratic at the selection
stage — rigorous and open, exclusive and fair.


---

*This article proposes a future governance milestone for Symbiosky. The
conviction voting system described is the current operational foundation.
Randomized jury selection is a proposed evolution subject to community
deliberation and protocol development.*
