# Election Methods Guide (Principles)

*A companion to the [Elections & Role Governance Policy](elections-and-role-governance-policy.md) and the [Proposal & Voting Framework](proposal-and-voting-framework.md). This guide is **not** part of the governance framework and has no legal force — if anything here seems to differ from a policy, the policy (and above it, the Charter and Operating Agreement) wins. Its only job is to set out the considerations that bear on choosing between the DAO's two election mechanisms. Nothing here is a requirement, a test, or a condition on anyone's discretion.*

*The binding rules are in the Proposal & Voting Framework §4.5, §6.2.4 and §6.2.5, the Elections & Role Governance Policy §7 and §7A, and the [DAO Parameters Registry](../parameters/dao-parameters-registry.md) §6B. For the framework as a whole, see the [Policy Library Reading Guide](../policy-library-reading-guide.md).*

---

## Why there is a choice at all

The DAO runs elections under one of two mechanisms, and neither is the default. The RAC selects one when it creates an election, and the selection is named on the Temperature Check ballot so voters approve a candidate list knowing how that list will be voted on.

Both mechanisms are legitimate and both are fully specified. Neither is a placeholder for the other. But they ask the electorate different questions, and from the same field of candidates they will not always return the same people. That is not a defect — it is the reason having two is worth anything. It is also why the choice deserves a reason, and why that reason is worth writing down.

---

## What the two mechanisms have in common

Most of an election is the same either way. The choice is narrower than it first appears.

| | Both mechanisms |
|---|---|
| Who may stand | Same eligibility and nomination rules (Policy §5–§6) |
| Getting to a ballot | Same Nomination & Discussion Window, same Temperature Check approving the candidate list |
| Who may vote, with how much weight | Same eligible voting power, same snapshot rule — each vote takes its own snapshot when it opens, and only a rerun reuses the snapshot of the round it re-runs (Framework §6.1) |
| Turnout requirement | Same quorum — Minimum Participation for Elections, 7% |
| If turnout is short | One rerun over a doubled voting period. Two-stage lowers the quorum and raises the approval threshold to compensate; Majority Judgment holds both constant (see principle 4) |
| If seats go unfilled | Same referral to vacancy handling (Policy §11; founding elections §17.1) |
| Candidates who cleared the bar but missed a seat | Same 90-day reserve list (Policy §7.5) |
| Who declares the result | The RAC, under the same publication duty and the same 48-hour veto window |

*Why this is here:* if you are weighing the two mechanisms, weigh only what actually differs. Nothing in the list above should enter the decision.

---

## The one-line difference

> **Majority Judgment** asks *how good is each of these candidates?* — and seats the ones the electorate broadly rates well.
>
> **Two-stage** asks *who is worth considering?*, then *do you affirmatively back this particular person?* — and seats the ones who clear both.

Underneath that sits the substantive difference. Majority Judgment measures **breadth of acceptability**: a candidate's median grade is high only if a majority of voting power rates them at least that well, so a candidate with passionate backing from a third of the electorate and hostility from the rest will not do well. The two-stage mechanism measures something closer to **intensity of endorsement**: Stage 1 ranks candidates by how much voting power actively approves them, and Stage 2 then asks each shortlisted candidate to clear an individual 60% gate.

Neither measurement is the correct one in the abstract. Which one you want depends on the seat.

---

## How the median actually behaves

Read this before principle 4. The median is not an average, and the two disagree in ways that decide elections.

**It is not the average.** For a candidate graded 51% Excellent and 49% Poor, the average grade is around Good. The **median is Excellent**. Accumulate voting power from the top: Excellent alone reaches 51%, which crosses half, and the calculation stops there — it never reaches the Poor grades at all.

**It is not the most common grade either.** Take a candidate graded 25% Excellent, 10% Very Good, 20% Good, 15% Acceptable, 30% Poor:

| Grade | Share | Running total | Crossed half? |
|---|---|---|---|
| Excellent | 25% | 25% | no |
| Very Good | 10% | 35% | no |
| Good | 20% | **55%** | **yes — median is Good** |
| Acceptable | 15% | 70% | *(never reached)* |
| Poor | 30% | 100% | *(never reached)* |

Poor is the largest single block at 30% — and it is **irrelevant**. Those voters sit entirely below the halfway point, so the calculation never gets to them. "Most voters said Poor, so the candidate is rated Poor" is the natural reading and it is wrong.

**What actually decides the outcome is the grade sitting at the halfway mark.** In the table above, shifting just 10 points from Good to Acceptable drops the median to Acceptable and puts the candidate below the electability floor — unseated. The hostile 30% never mattered in either case.

**Voting power decides where halfway falls.** Power is what positions the crossing, so a large holder can control the result outright. But past the crossing, extra power does nothing: a holder with 51% and a holder with 80% produce the identical median. Majority Judgment is *monotonic* in voting power, not *proportional* to it — unlike Stage 1 Approval Voting, where every unit of power keeps moving the ranking.

*Why the median at all, given all this:* grades are ranks, not quantities — there is no basis for saying Excellent-to-Very-Good is the same distance as Acceptable-to-Poor, so averaging them assumes a scale the ballot doesn't provide. And an average is trivially gamed: everyone grades their favourite Excellent and every rival Poor, and the election becomes a raw power contest. The median blunts that. It is a real trade, not a mistake — but it is the trade that produces principle 4.

---

## Principles

These pull in a direction. None of them decides a case on its own, and each has a counter-case worth taking seriously.

### 1. Match the ballot to the question the seat actually asks

Some seats need a person the whole electorate can live with — a mediator, an interpreter of rules, a holder of a swing position on a small body. Breadth of acceptability is the right property, and Majority Judgment measures it directly.

Other seats need someone with a real mandate to act, sometimes against opposition. The two-stage mechanism's per-candidate 60% gate produces exactly that: nobody is seated without a majority of decisive votes affirmatively saying yes to *them*.

*The counter-case:* a seat can need both, and then this principle gives you nothing. Move on to the ones that do discriminate.

### 2. Field size is a real constraint, not a preference

A Majority Judgment ballot is only valid if the voter grades **every** candidate. That is what makes the medians comparable, and it is a genuine cost: with five nominees it is a few minutes' work, with twenty-five it is a research project, and voters who will not do it simply do not vote. Turnout is not free, and quorum is 7%.

Stage 1 shortlisting exists precisely to solve this. Approval Voting over a large field is cheap for the voter — tick the ones you know — and it cuts the field to twice the number of seats before anyone is asked for a considered per-candidate judgement.

*The rough shape of it:* the larger and less familiar the field, the stronger the case for shortlisting first. A field small enough that an engaged voter could form a view on everyone is a field Majority Judgment can handle.

### 3. Two mechanisms, two very different clocks

Majority Judgment is one voting round, plus a rerun only if turnout falls short. Two-stage is Stage 1, then Stage 2, then possible per-candidate reruns, then fallback advancement of the next Stage 1 candidate — each of which is another vote, and the framework requires reruns to wait until all concurrent Stage 2 votes have closed.

Against the 21-day Replacement Completion Time for a vacancy, that difference is not academic.

*The counter-case:* for a founding election or a high-stakes body, the gap between rounds is where the community actually scrutinises a shortlist that has been narrowed to a serious few. Slowness is sometimes the product.

### 4. The 50% cliff — the most important thing on this page

**Below half the voting power cast, Majority Judgment is very hard to capture. At exactly half, it hands over everything.** Both halves of that sentence follow from the same property, and you cannot have one without the other.

*Exactly half, not half plus one.* The median is the highest grade at which the running total **reaches or exceeds** half (Framework §6.2.4), so a bloc holding precisely half of the voting power cast already fixes the grade — it does not need one more token. A candidate graded Excellent by half the electorate and Poor by the other half has a median of **Excellent**.

A median is fixed by the ballot standing at the halfway point and is completely blind to how extreme the grades on either side of it are. So:

| The electorate | Median grade | Stage 2 outcome |
|---|---|---|
| 51% grade Excellent, 49% grade Poor | **Excellent** — top grade, seated | 51% YES → **fails** the 60% gate |
| 30% grade Poor, rest spread above | Poor is ignored entirely | 70% YES → confirmed |

In the first row, a candidate half the DAO rates worst-possible receives the *highest available grade*. Those 49% Poor grades change nothing — they would produce the same result if they were Acceptable, or Good, or Very Good.

**Raising the Minimum Median Grade does not help.** The floor changes *which grade* a majority must confer; it never changes *what fraction* must agree. Set it to Very Good and a 51% block grades Very Good instead. There is no setting at which Majority Judgment becomes a supermajority instrument — it is a 50% instrument by construction.

Two-stage's 60% per-candidate gate *is* a share-of-turnout test, and it is the only place in the whole framework where a large minority can block. The Temperature Check won't do it (≥50% YES) and the veto won't (legality only — §8.2 excludes disagreement with substance).

**What this costs in practice.** Control belongs to whoever holds half of *turnout*, not half of the DAO — and exactly half is enough. At the 7% election quorum that is roughly **3.5% of eligible voting power** — enough to set every candidate's grade, and because one ballot grades every candidate, to sweep an entire body in a single action. Under two-stage the same block must win the Stage 1 ranking *and* clear 60% on each candidate separately.

*The other side, and it is real:* Approval Voting rewards coordination in its own way. A disciplined block that approves exactly its own slate concentrates all its power on those names while unorganised voters spread theirs thin, so a *minority* can dominate a Stage 1 ranking. Stage 2's gate then checks it — but only over the candidates Stage 1 chose to show the electorate.

*And the softer objection to the median:* the same insensitivity that ignores a hostile minority also favours the inoffensive. Majority Judgment can seat the candidate nobody objects to over the candidate half the DAO actively wants.

**The practical upshot:** the more concentrated the token distribution, and the more the seat matters, the stronger the case for two-stage.

### 5. Think about the record the election leaves behind

A Majority Judgment result is a full grade distribution for every candidate — including the ones who lost, and including the incumbents. That is a genuinely useful artefact: comparable across elections, informative at renewal, and hard to spin. A candidate who was seated on a median of Good with a long tail of Poor grades is visibly in a different position from one seated on a solid Very Good.

A two-stage result gives you a Stage 1 power ranking and a Stage 2 yes/no ratio. Enough to know who won; much less to know what the electorate thought.

*Where this matters most:* roles subject to auto-renewal (Policy §9.1). If a term renews unless challenged, the record from the last election is much of what a participant has to go on when deciding whether to challenge.

### 6. Seat count pulls in the opposite direction to field size

Majority Judgment handles multi-seat elections natively: the median-grade ranking *is* the seating order, so filling five seats is the same operation as filling one, and the awkward case the two-stage mechanism has to handle — more candidates confirmed than there are seats — simply does not arise.

But many seats usually means many nominees, and principle 2 then pulls the other way. Three seats from six nominees is comfortable for Majority Judgment. Three seats from thirty is where the shortlist multiplier earns its keep.

### 7. Weigh the cost of seating the wrong person

The two-stage mechanism puts an explicit, individual veto point on every candidate: a 60% approval gate, per person, with no Abstain to soften it. That is an expensive extra round, and for some seats it is cheap insurance — Treasury Signers holding multisig keys, or any role where removing the wrong occupant is slow and damaging.

Majority Judgment's equivalent protection is the Minimum Median Grade. It is a real bar, but a *different kind* of bar: it asks whether a majority grades the candidate at or above a level, not whether a supermajority affirmatively endorses them. Following principle 4, that means it cannot be tuned into a supermajority requirement.

*The trade:* a per-candidate confirmation gate costs a round and buys the framework's only minority-blocking mechanism in an election. That is a larger thing than it first sounds — it is not merely a stronger individual mandate, it is the difference between a seat that a bare majority of turnout can fill and one it cannot.

### 8. Consistency beats cleverness

Switching mechanisms between consecutive elections for the same role has costs that are easy to miss. Results stop being comparable, so the record from principle 5 loses much of its value. Candidates cannot know what kind of campaign to run. And the switch itself invites the reading — fairly or not — that the mechanism was chosen for the outcome it would produce.

*In practice:* treat the mechanism used last time for a role as the starting point. Departing from it is entirely legitimate; departing from it **without saying why** is what generates suspicion.

### 9. *When* the choice was made matters as much as what was chosen

The two mechanisms favour different candidates from the same field. It follows that a choice made **before** the nominee field is known is defensible in a way that a choice made after it is known is not — however honest the reasoning behind the later choice, and however good the outcome.

This is not a rule, and the framework does not impose a deadline. It is simply an observation about credibility, and it is cheapest to act on early: name the mechanism when the Nomination & Discussion Window opens, publish the reasons alongside it, and the question never arises. The Temperature Check then gives the community a real say — it is a live vote at 3% quorum, and a failed Temperature Check ends that election outright.

*This applies with most force where the body running the election has an interest in its outcome* — an election for the RAC's own successors, or a founding election run by a Transition RAC that the elected body will replace. There, an early and reasoned choice is worth a great deal, and a late one is worth very little.

### 10. Under Majority Judgment, the Minimum Median Grade is the real decision

Once you have chosen Majority Judgment, the mechanism is largely fixed. The dial that actually shapes the outcome is the floor a candidate must reach to be seated at all — **Good** as standard, and unchanged on a rerun.

Raising the floor is a statement that an empty seat is safer than a mediocre occupant. That is often true — and it is worth being clear-eyed that "empty" means the seat goes to vacancy handling under Policy §11, which is its own process with its own delay. A high floor is not a free stringency.

**What the floor cannot do** is stop a narrow majority. Following principle 4, a block that sets the median chooses the grade, so raising the floor costs it nothing while burdening a genuine broad electorate. That is exactly why the floor is *not* raised on a rerun, and why the rerun's quorum is *not* lowered: swapping a lower turnout bar for a higher grade bar looks like a fair trade and isn't one. If you want protection against a narrow majority, the floor is the wrong instrument and two-stage is the right mechanism.

*A related point worth internalising:* a Majority Judgment round that meets quorum but seats nobody has **not** failed. The electorate answered, and the answer was that none of these candidates should hold the seat. That is a real result, and it does not trigger a rerun.

---

## Side by side

| | Majority Judgment | Two-Stage Approval → Confirmation |
|---|---|---|
| **The ballot** | Grade every candidate: Excellent / Very Good / Good / Acceptable / Poor. Partial ballots invalid | Stage 1: approve any number of nominees. Stage 2: yes/no on each shortlisted candidate |
| **Rounds** | One, plus a rerun only if turnout is short | Two, plus possible per-candidate reruns and fallback advancement |
| **What wins** | Highest median grade, subject to the Minimum Median Grade floor | Top by approval power into the shortlist, then ≥60% yes individually |
| **Seating order** | The median-grade ranking is the seating order | Stage 2 confirms eligibility; Stage 1 power ranking orders the seating |
| **Measures** | Breadth of acceptability | Intensity of endorsement, per candidate |
| **Main weakness** | No supermajority protection — just over half of turnout (~3.5% of eligible) controls every grade and can sweep a whole body in one ballot | Stage 1 rewards block coordination; more rounds, more elapsed time |
| **If turnout falls short** | One rerun at the same quorum and floor, doubled period; or the RAC restarts under two-stage | Per-candidate rerun at reduced quorum and raised threshold |
| **Can candidates be fewer than seats?** | Yes — the floor supplies the possibility of losing | Yes — unfilled seats go to vacancy handling |
| **Voter effort** | High and fixed — every candidate, every ballot | Low at Stage 1, moderate at Stage 2 over a shortlist |
| **Record it leaves** | Full grade distribution per candidate | Approval ranking plus a yes/no ratio |
| **Suits** | Small to moderate fields; seats needing broad acceptability; multi-seat bodies; elections you want an evidence trail from | Large or unfamiliar fields; seats needing an individual mandate; roles where seating the wrong person is expensive |

---

## A starting point, not a rule

If you want somewhere to begin rather than a blank page:

| Seat | Suggested starting point | Because |
|---|---|---|
| Permanent RAC | **Two-stage** | The body that publishes results, adjudicates ties, and issues binding interpretations. Principle 4 — its members should not be seatable by a bare majority of a thin turnout |
| Treasury Signers | **Two-stage** | Multisig keys. The per-candidate 60% gate is worth its extra round |
| Working Group Stewards | **Majority Judgment** | Smaller fields, lower stakes, and the grade record is genuinely useful at renewal |
| Strategic Coordination WG | **Majority Judgment** | As above |
| Filling a single vacancy | **Majority Judgment** | One round inside the 21-day Replacement Completion Time; the floor still gates quality |
| A field of 20+ nominees | **Two-stage** | Grading everyone is a research project, and turnout is what pays for it |

This inverts the obvious intuition, which is worth saying out loud: the newer and more informative mechanism is *not* the one for the highest-stakes seats. It is better at telling you what the electorate thinks and worse at stopping a narrow majority from having its way.

---

## Where the binding rules actually are

| Question | Look here |
|---|---|
| The election pipeline, and both mechanisms in outline | [Proposal & Voting Framework](proposal-and-voting-framework.md) §4.5 |
| The Temperature Check as candidate-list approval | Proposal & Voting Framework §3.2 |
| Majority Judgment mechanics — grades, medians, ties, reruns | Proposal & Voting Framework §6.2.4 |
| Two-stage mechanics | Proposal & Voting Framework §6.2.2, §6.2.5, §6.2.7 |
| Voting power and the snapshot | Proposal & Voting Framework §6.1 |
| Participation and denominators for graded ballots | Proposal & Voting Framework §6.3 |
| How the RAC determines and publishes a result | Proposal & Voting Framework §6.5 |
| Election process, both mechanisms | [Elections & Role Governance Policy](elections-and-role-governance-policy.md) §7 (two-stage: §7.1–§7.3; Majority Judgment: §7A) |
| Reserve list | Elections & Role Governance Policy §7.5 |
| Unfilled seats and vacancies | Elections & Role Governance Policy §11; founding elections §17.1 |
| Term renewal and challenges | Elections & Role Governance Policy §9 |
| Every number named above | [DAO Parameters Registry](../parameters/dao-parameters-registry.md) §3.5, §6B |
| Why elections sit outside the continuity fallback | DAO Parameters Registry §9A |
