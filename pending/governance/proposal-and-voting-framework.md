# Proposal & Voting Framework

---

## 1. Scope

This document defines:

* How proposals are created, discussed, and approved
* Voting mechanisms and thresholds
* Proposal categories and requirements
* Safeguards such as veto and resubmission rules

**Binding effect and the Advisory Governance Period.** This framework describes the DAO's governance mechanics. The point at which a passed DAO Proposal becomes a **legally binding decision of the Company** is governed by the Operating Agreement: during the **Advisory Governance Period** (formation to the Activation Date) governance outcomes are **advisory** (OA §§5.8–5.9), save for the three binding community acts in Charter §4A.2 (framework ratification, the Permanent RAC election, and the Activation Vote); from the **Activation Date** they are binding decisions of the Company (OA §5.7). References to a "binding" proposal in this document mean binding within the DAO's governance process and take legal effect on this timeline. The Activation Vote itself runs on the parameters in DAO Parameters §3A.2.

---

## 2.5 Proposal Eligibility

Any Governance Participant may submit a proposal. No minimum holding, prior registration, or approval from any DAO body is required to submit. This right flows directly from Governance Participant sovereignty as established in the Charter §4.1 and the governance participation rights in Operating Agreement Article V (§5.4).

---

## 3. Proposal Lifecycle

All proposals follow a three-stage pipeline:

### 3.1 Stage 1 — Draft Discussion

* Idea introduced publicly on the RAC-designated discussion platform
* Open community discussion and feedback
* Minimum duration defined in DAO Parameters §3.1

---

### 3.2 Stage 2 — Temperature Check (TC)

* Mandatory YES / NO poll submitted to the governance platform after Draft Discussion concludes
* Assesses community support before a binding vote is opened
* Vote type: Temperature Check Vote (§6.2.6) — YES / NO only, no Abstain
* Quorum: 3% of eligible voting power (DAO Parameters §3.2)
* Passes on simple majority (≥50% YES of votes cast)
* A failed TC resets the standard 7-day cooldown (DAO Parameters §3.4) before a new TC may be submitted for the same proposal
* Duration defined in DAO Parameters §3.1

**The Temperature Check in an Election proposal.** For Election proposals (§4.5) the Temperature Check carries an additional function: it is the community's approval of the candidate list. The Temperature Check and the election vote are created in a single operation on the governance platform, over one candidate list that is immutable from creation, so the list put to the Temperature Check is provably the list put to the election vote. The Temperature Check ballot states the election mechanism selected for that election (§4.5). A failed Temperature Check is terminal for that election: no election vote opens, no seats are filled, and the standard 7-day cooldown (DAO Parameters §3.4) runs before a new Temperature Check may be submitted for the same role.

The Temperature Check is a **list-level** gate — it asks whether this set of candidates is an acceptable field to hold an election over. Objection to an individual candidate is expressed at the election vote itself, through the Minimum Median Grade under Majority Judgment (§6.2.4) or the Stage 2 approval threshold under the two-stage process (§6.2.7). A voter should not reject an entire field over one candidate they would decline.

**Temperature Checks used outside this pipeline.** A Temperature Check is also used as a standalone instrument in two places, neither of which is a Stage 2 pipeline TC and neither of which elevates to a Governance Proposal on passing: the Community Accountability Hearing request (RAC Mandate §11B) and the Steward Consultation Temperature Check (Working Group Framework §7.2). Where a Steward Consultation TC is declined, the matter may proceed only as a full Treasury & Budget proposal after the standard cooldown in DAO Parameters §3.4 — that proposal runs the complete pipeline, including its own Stage 2 Temperature Check under this section.

---

### 3.3 Stage 3 — DAO Proposal

* Formal binding proposal elevated by the Governance Operator from a passed TC via the Owner Badge
* The Governance Operator must elevate an eligible passed TC within the TC Elevation Window (DAO Parameters §3.1), or record documented grounds for the delay with the RAC. An eligible TC left unelevated beyond that window triggers the elevation backstop (Governance Continuity Framework §4.2A)
* Must include all required fields (see §5)
* Category determines vote type, quorum, and approval threshold (§4; DAO Parameters §3.2–3.3)
* Passed → moves to execution; Failed → standard cooldown applies

---

## 4. Proposal Categories

### 4.1 Constitutional Proposals

Changes to:

* Charter
* Core governance structure

Charter changes are classified as Major Changes under the Governance Maintenance & Upgrade Framework and require this proposal type. The Governance Maintenance & Upgrade Framework governs versioning, consistency requirements, and amendment procedures for all Charter amendments.

---

### 4.2 Governance Process Proposals

Changes to:

* Governance rules
* Process documents

Proposals that introduce or modify governance documents — policies, process documents, and structural rules (excluding the Charter, which requires a Constitutional proposal per §4.1) — must follow the Governance Maintenance & Upgrade Framework.

This framework defines:

* classification of changes (patch, minor, major)
* required approval thresholds
* consistency and versioning requirements

All governance changes must clearly specify their classification and comply with the defined upgrade process.

---

### 4.3 Treasury & Budget Proposals

* Funding requests
* Budget allocations

Treasury & Budget proposals use the Standard vote type (§6.2.1). Where funds are distributed across multiple recipients, the proposal must state the split — the amount or percentage each recipient receives — and voters accept or reject that split as a package.

---

### 4.4 Executable Proposals

* Technical or operational changes
* On-chain or system execution

**Multi-option Approval Voting polls** are a sub-type of Executable proposals for cases where the community must choose between several defined options rather than a binary question. They use Approval Voting (§6.2.2) rather than the Standard vote type. A shortened 1-day Temperature Check applies (DAO Parameters §3.1). The result is advisory unless the proposal text mandates execution of the winning option.

Any Executable proposal that requires compensated work — including fixed-rate service delivery — must include a Treasury & Budget component specifying the cost arrangement and receiving party. Such combined proposals are evaluated against Treasury & Budget quorum and approval thresholds (the more stringent of the two proposal types). Executable proposals with zero cost proceed under Executable thresholds.

---

### 4.5 Election Proposals

Selection of candidates for DAO roles: RAC members, Working Group Stewards, Strategic Coordination WG members, and Treasury Signers.

Election proposals use a modified version of the standard pipeline (§3): the Draft Discussion and Nomination Period are merged into a single combined Nomination & Discussion Window (DAO Parameters §3.1 and §6B), and the Temperature Check is compressed to a minimum of 1 day (DAO Parameters §3.1). The Temperature Check for an Election proposal also serves as the community's approval of the candidate list (§3.2).

**Election mechanisms**

Two election mechanisms are operative, and an election runs under one of them:

* **Majority Judgment** (§6.2.4) — a single graded round in which voters grade every candidate. Pipeline: Nomination & Discussion Window → Temperature Check → Majority Judgment election vote → (single reduced-quorum rerun if the first round misses quorum).
* **Two-Stage Approval Voting → Confirmation** (§6.2.5) — Approval Voting shortlisting followed by a per-candidate confirmation vote. Pipeline: Nomination & Discussion Window → Temperature Check → Stage 1 Shortlisting → Stage 2 Confirmation.

Neither mechanism is subordinate to the other and neither requires activation. The RAC selects the mechanism for an election when it creates that election on the governance platform, and the selected mechanism is stated on the Temperature Check ballot (§3.2) so that the community approves the candidate list knowing how that list will be voted on. The Election Methods Guide is a companion aid describing the considerations that bear on this choice; it is not part of this framework and imposes no requirement.

Both mechanisms use the same eligible voting power and the same snapshot (§6.1), are preceded by the same Nomination & Discussion Window and Temperature Check, are published by the RAC under the same result determination procedure (§6.5), and refer unfilled seats to the same vacancy handling process (Elections & Role Governance Policy §11; founding election: §17.1).

**Majority Judgment Election Process**

The candidate list approved at the Temperature Check is put to a single graded vote (§6.2.4). Voters assign a grade to every candidate from the scale in DAO Parameters §3.5; a ballot that omits any candidate is invalid. Candidates are ranked by median grade, and a candidate is electable only if their median grade meets the MJ Minimum Median Grade (DAO Parameters §6B).

Seats are filled by electable candidates in descending median-grade order — the median-grade ranking is itself the seating order. Where a candidate ranked within the open seats is not electable, that seat passes to the next-ranked electable candidate. Electable candidates who are not seated are placed on the reserve list for the role (Elections & Role Governance Policy §7.5). If electable candidates are exhausted before the seats are, the election stands for the seats it filled and each remaining seat is referred to vacancy handling.

If the round closes below the Minimum Participation for Elections (DAO Parameters §6B), the RAC either re-runs the election once over the extended MJ Rerun Voting Period — at the same quorum and the same Minimum Median Grade, the remedy being time rather than a lower bar (§6.2.4) — or restarts the election under the two-stage mechanism (§6.2.5), which requires a new Temperature Check. The RAC publishes which route it has taken and its reasons. That choice arises only once a round has closed below quorum; a live election vote may not be halted. At most one rerun is permitted (Max MJ Reruns, DAO Parameters §6B). If the rerun also closes below quorum, no candidate is elected and all seats are referred to vacancy handling.

**Two-Stage Election Process**

**Stage 1 — Shortlisting (Approval Voting)**
An Approval Voting poll (§6.2.2) is published listing all eligible nominees. Voters may select any number of nominees they approve. The top candidates by total voting power — up to the shortlist size defined in DAO Parameters §6B — advance to Stage 2. The Stage 1 result is procedurally binding. Stage 1 has no separate quorum requirement; the Temperature Check result is sufficient. The minimum winner threshold (DAO Parameters §3.5) does not apply; candidates are ranked by total voting power only. If two or more candidates are tied in voting power for the last available shortlist slot, all tied candidates are included in the shortlist; the shortlist size is expanded by the number of additional tied candidates.

**Stage 2 — Confirmation (Confirmation Vote)**
Each shortlisted candidate is put to a separate Confirmation Vote (YES/NO) proposal (§6.2.7). There is no Abstain option at Stage 2: a voter with no view on a candidate expresses that at Stage 1 by not selecting them (§6.2.7). A candidate is confirmed if they meet the quorum and approval threshold defined by the DAO parameters "Election Stage 2 Quorum" and "Election Stage 2 Approval Threshold" in DAO Parameters §6B. Stage 2 proposals may run concurrently.

**Seating of confirmed candidates**
Because the shortlist is larger than the number of open seats (DAO Parameters §6B — Election Shortlist Multiplier), more candidates may be confirmed at Stage 2 than there are seats. Where that occurs, seats are filled by confirmed candidates in descending order of total voting power received in Stage 1: Stage 2 confirmation establishes eligibility to be seated, and the Stage 1 ranking determines the order of seating. If two or more confirmed candidates are tied in Stage 1 total voting power for the last available seat, the tie is resolved in favour of the candidate with the higher YES share of votes cast in their Stage 2 confirmation vote (Stage 2 has no Abstain option, so this is YES ÷ (YES + NO); §6.2.7); if the tie persists, the RAC conducts a single runoff Approval Voting poll between the tied candidates using the short Temperature Check period (DAO Parameters §3.1). The Stage 1 tie-expansion rule above does not apply at the seat boundary, where the number of seats is fixed. A confirmed candidate who is not seated is not elected, but is placed on the reserve list for the role and may be seated to fill a later same-role vacancy without a further election (Elections & Role Governance Policy §7.5).

**Fallback and rerun**
When a Stage 2 confirmation vote closes, each candidate is classified as **confirmed** (reaches the Election Stage 2 Quorum and meets the Approval Threshold), **rejected** (YES share below the Approval Threshold, whether or not quorum was met — a quorum shortfall never rescues a candidate the voters declined), or **quorum-held-over** (meets the Approval Threshold but misses quorum). A quorum-held-over candidate is re-run once at the reduced Election Stage 2 Rerun Quorum and the raised Election Stage 2 Rerun Approval Threshold, over the extended Rerun Voting Period (DAO Parameters §6B); if the rerun meets both they are confirmed, otherwise they are not elected. Where a candidate is rejected or fails their rerun and seats remain open, the next-highest un-voted candidate from the full Stage 1 result is advanced to a confirmation vote at the standard Stage 2 quorum and threshold, and is entitled to the same single rerun. This continues until all seats are filled or no un-voted Stage 1 candidate remains; if seats remain with no un-voted candidate and no outstanding rerun, remaining vacancies follow the vacancy handling process in the Elections & Role Governance Policy §11 (founding election: §17.1). Where Stage 2 confirmation votes run concurrently, the RAC opens any rerun or fallback confirmation vote only after all concurrent Stage 2 votes for that election have closed.

---

## 5. Proposal Requirements

All proposals must include:

* Title and description
* Category
* Rationale
* Expected outcomes
* Risks and trade-offs
* Budget (if applicable)
* Execution plan (if applicable)
* **Executor commitment declaration** *(required for all Executable and combined Executable + Treasury proposals)* — Named executor(s) must be identified by name and wallet address, and must have confirmed in writing (forum post or signed statement) that they accept the execution responsibility before the TC voting period opens. Where the proposer is also the executor, this must be declared as a conflict of interest.
* **Cumulative recipient disclosure** (Treasury & Budget proposals only): total disbursements to the same recipient, entity, or affiliated group over the trailing 90 days. The RAC verifies this field before opening the veto window. A missing or materially incorrect disclosure is valid grounds for a veto filing (Charter / rule violation: failure to meet required proposal content).

---

## 6. Voting Mechanics

### 6.1 Voting Power

* Voting power is determined at a fixed snapshot
* The snapshot is fixed at proposal creation — the operation that creates the Temperature Check on the governance platform and, for an Election proposal, creates the election and its Temperature Check together (§3.2). It is not taken when voting opens
* The snapshot is set by the system as a consequence of creation, not chosen by the RAC or the proposer
* One snapshot governs every stage of a proposal: the Temperature Check, the proposal or election vote, and any rerun of that vote. Stage 2 confirmation votes and a Majority Judgment rerun therefore resolve voting power against the same snapshot as the Temperature Check that preceded them
* Measured in XRD-equivalent units; eligible holdings include:
  * Eligible holdings are defined in two tiers (DAO Parameters §8A):
    * **Tier 1 — Constitutional floor (always eligible):** Liquid XRD held directly; LSU converted to XRD-equivalent via the LSU redemption rate at snapshot
    * **Tier 2 — RAC-governed supplementary sources:** LSULP and DEX pool positions as listed in the RAC-maintained register (DAO Parameters §8A)
  * Changes to Tier 2 sources follow the RAC process defined in DAO Parameters §8A

---

### 6.2 Vote Types

The vote type determines how voters express preferences and how results are determined. Each proposal category maps to a designated vote type. All types use one token = one vote as the base unit of voting power.

---

#### 6.2.1 Standard (YES / NO / ABSTAIN)

* Applies to: Constitutional, Governance Process, Treasury & Budget, and Executable proposals. This includes Treasury & Budget proposals that distribute funds across multiple recipients: the proposal states the split, and voters accept or reject it as a package. Multi-option Executable proposals use Approval Voting (§6.2.2) instead
* Voters cast one of three options: Yes, No, or Abstain
* Abstain counts toward Participation (and therefore toward quorum) but is excluded from Decisive Votes (and therefore from the approval threshold). Both terms are defined in §6.3
* Result: proposal passes if it meets quorum (§6.3), the YES share of Decisive Votes meets the approval threshold for the proposal type (DAO Parameters §3.3), **and** YES voting power meets the Minimum Affirmative Support floor for the proposal type (DAO Parameters §3.3A)

---

#### 6.2.2 Approval Voting

* Applies to: Election shortlisting (§4.5) and multi-option Executable proposals (§4.4)
* Voters may select any number of options from a defined list. For multi-option Executable proposals, the ballot is capped at 8 options (DAO Parameters §3.5). For election shortlisting, the ballot lists all eligible nominees and selections are unrestricted (DAO Parameters §6B).
* Each selected option receives the voter's full voting power
* Result: the option with the highest total voting power wins. For multi-option Executable proposals, the winner must meet the minimum winner threshold (DAO Parameters §3.5); if no option meets the threshold, the proposal fails and the proposer may resubmit after the standard cooldown. For election Stage 1 shortlisting, the minimum winner threshold does not apply — the top candidates by total voting power advance to Stage 2 (§4.5).

---

#### 6.2.3 [Retired — Weighted Allocation]

Weighted Allocation — a points-distribution ballot for Treasury proposals splitting funds across multiple recipients — was removed from this framework before ratification. It was never operative: it required platform tooling that was never specified, and its stated approval threshold could not be computed from the ballot it defined.

Treasury & Budget proposals distributing funds across multiple recipients use the Standard vote type (§6.2.1): the proposal states the split and voters accept or reject it as a package.

This section number is retained, rather than renumbered, so that references to §6.2.4–§6.2.7 remain stable.

---

#### 6.2.4 Majority Judgment

**Applies to:** Election Proposals (§4.5), as one of the two operative election mechanisms. Majority Judgment requires no activation vote, activation notice, or feature toggle.

**Definitions.**

**Grade** means one of the five ordered values in the grade scale (DAO Parameters §3.5), from Excellent (highest) to Poor (lowest). The order of the scale is normative: every comparison in this section is a comparison of rank on that scale.

**Median grade** means, for a candidate, the highest grade at which the voting power that graded the candidate at or above that grade reaches or exceeds half the voting power cast for that candidate. It is computed by accumulating voting power from the highest grade downward and taking the first grade at which the running total reaches half. (Where the literature on this method refers to a candidate's "majority grade," it means the same quantity.)

**Minimum Median Grade** means the lowest median grade at which a candidate may be seated (DAO Parameters §6B). It is the Majority Judgment analogue of the approval threshold: a ranking alone does not seat a candidate the electorate broadly grades below the floor.

**Electable** means a candidate whose median grade is at or above the Minimum Median Grade in force for the round.

**Ballot.**

* Voters assign exactly one grade to every candidate in the election. A ballot that leaves any candidate ungraded is invalid and is not counted
* Each voter's full voting power is applied to each grade that voter assigns
* Because every valid ballot grades every candidate, the voting power measured is the same for every candidate in the round. Median grades are therefore directly comparable, and a candidate cannot be advantaged by being graded on fewer ballots than a rival

**Result.**

* Each candidate's median grade is computed as defined above, and candidates are ranked by median grade in descending order, ties broken as below
* A candidate is seated only if electable. The median-grade ranking is itself the seating order, so the oversubscribed-confirmation question addressed for the two-stage process in §4.5 and Elections & Role Governance Policy §7.2.1 — where confirmation establishes eligibility and a separate ranking determines seating — does not arise under Majority Judgment
* Where a candidate ranked within the open seats is not electable, that seat passes to the next-ranked electable candidate. Where electable candidates are exhausted before the seats are, the election stands for the seats it filled and each remaining seat is referred to vacancy handling (Elections & Role Governance Policy §11; founding election: §17.1)
* Electable candidates who are not seated are placed on the reserve list for the role, ranked by median grade and by the tie-break order below (Elections & Role Governance Policy §7.5)

**Tie-break.** Where two or more candidates share a median grade and the tie affects the outcome, the tie is resolved by the **majority gauge**. For each tied candidate, let **p** be the share of voting power that graded the candidate *above* their median grade, and **q** the share that graded them *below* it. Both are shares of the voting power cast in the round, measured on the same basis as the median itself; because every valid ballot grades every candidate, that denominator is identical for every candidate in the round.

* A candidate with p > q ranks above a candidate with p = q, who ranks above a candidate with p < q
* Among candidates with p > q, the higher p ranks first
* Among candidates with p < q, the lower q ranks first

The majority gauge is the operative tie-resolution rule, and the iterative middlemost-grade formulation of Majority Judgment is not applied. The two orderings agree, so this is a choice of method rather than of outcome: the gauge is used because it is computed in a single pass over the recorded tallies, alters no vote data, and can be verified by any member from the published result (§6.5). Given the same votes and voting powers it must produce the same outcome.

A tie is broken only so far as the outcome requires: a tie that does not straddle the seat boundary or the electable boundary needs no resolution.

The majority gauge does not separate two candidates who share a median grade where both have p > q and the same p, where both have p < q and the same q, or where both have p = q. In the last case the size of p does not distinguish them: a candidate whose p equals their q sits exactly at their median grade on the gauge, and two candidates who both do so are equally placed however much voting power lies either side of it. Where a tie the gauge does not separate affects the outcome, the RAC adjudicates it and records its determination as part of the published result (§6.5), guided by the principle in Elections & Role Governance Policy §7A.4. This adjudication is a defined step of this mechanism, not a discretionary power exercised outside it.

**Quorum and low-turnout handling.** Election proposals are excluded from the Governance Continuity Fallback (DAO Parameters §9A), so Majority Judgment carries its own low-turnout handling. It does **not** follow the two-stage pattern of a reduced rerun quorum, for the reason given below.

* The round is valid if participation meets the Minimum Participation for Elections (DAO Parameters §6B)
* Where a round closes below quorum, the RAC either re-runs the election under this section or restarts it under the two-stage mechanism (§6.2.5), as provided below
* A rerun under this section runs at the **same** quorum and the **same** Minimum Median Grade as the round it follows, over the extended MJ Rerun Voting Period (DAO Parameters §6B). The remedy the rerun offers is time: the same electorate, the same snapshot (§6.1), the same candidate list and seat count, and the same thresholds, with twice as long to participate
* The RAC publishes a rerun notice when the rerun opens; the extended voting period runs from that notice
* At most one rerun is permitted (Max MJ Reruns, DAO Parameters §6B). If the rerun also closes below quorum, no candidate is elected and all seats are referred to vacancy handling (Elections & Role Governance Policy §11; founding election: §17.1)

*Why the quorum is not reduced.* The two-stage rerun can safely lower its quorum because it raises its approval threshold at the same time, and a share-of-votes threshold genuinely constrains a voting block — it must bring a larger fraction of those who voted with it. Majority Judgment has no share threshold to raise. A block holding more than half the voting power cast determines the median grade and may name any grade it chooses, so raising the Minimum Median Grade does not constrain it. Reducing the quorum would therefore lower the voting power needed to control the result with nothing offsetting it, and would make the rerun cheaper to control than the round it exists to rescue — an incentive to suppress turnout in the first round. The quorum and the electability floor accordingly hold constant across both rounds.

**Restarting under the two-stage mechanism.** Where a Majority Judgment round closes below quorum, the RAC may instead restart the election under the two-stage mechanism (§6.2.5) rather than re-run under this section. A restart is a new election: it requires a new Temperature Check approving the candidate list (§3.2), and the Stage 1 and Stage 2 thresholds apply unmodified. It carries nothing over from the Majority Judgment election — not the grades, the medians, or the ranking — and the earlier election is not converted, amended, or continued. The RAC publishes which route it has taken and its reasons.

Neither route is automatic. A round that closes below quorum ends there: the rerun does not open, and the restart does not occur, unless the RAC acts. A governance platform must not schedule, date, or open a rerun of its own motion, because doing so would resolve the choice this section reserves to the RAC before the RAC has made it.

This choice arises **only** after a round has closed below quorum. A Majority Judgment round that is open, or that has closed with quorum met, is not subject to it — there is no power to halt a live election vote or to set aside a result that met quorum.

**Number of candidates.** Majority Judgment places no requirement on the number of candidates relative to the number of seats, and in particular does not require that a candidate be capable of losing on rank. The Minimum Median Grade supplies that possibility independently of the ranking: where the candidates are no more numerous than the seats, the election is a quality test in which any candidate the electorate grades below the floor is not seated and the seat is referred to vacancy handling. An election with as many candidates as seats, or fewer, is therefore a valid Majority Judgment election.

**Denominators.** Majority Judgment produces graded results rather than a Yes/No tally. Participation and the treatment of Decisive Votes for this vote type are defined in §6.3.

---

#### 6.2.5 Two-Stage Elections

* Applies to: Election Proposals (§4.5), as one of the two operative election mechanisms, alongside Majority Judgment (§6.2.4)
* Stage 1 uses Approval Voting (§6.2.2) for shortlisting — voters may select any number of nominees
* Stage 2 uses the Confirmation Vote (§6.2.7) for confirmation of each shortlisted candidate
* Full procedure defined in §4.5 and Elections & Role Governance Policy §7

---

#### 6.2.6 Temperature Check Vote (YES / NO)

* Applies to: The Temperature Check stage (§3.2) for all proposal types
* Voters cast one of two options: Yes or No. There is no Abstain option.
* Quorum is measured by total voting power cast (YES + NO only)
* Result: TC passes if the YES share of votes cast meets the TC approval threshold (≥50% YES; see DAO Parameters §3.3)

---

#### 6.2.7 Confirmation Vote (YES / NO)

* Applies to: Stage 2 candidate confirmation in Two-Stage Elections (§6.2.5, §4.5)
* Voters cast one of two options: Yes or No. **There is no Abstain option.**
* Quorum is measured by total voting power cast (YES + NO only), against the Election Stage 2 Quorum (DAO Parameters §6B)
* Result: the candidate is confirmed if the YES share of votes cast meets the Election Stage 2 Approval Threshold (DAO Parameters §6B)

**Why no Abstain.** Stage 1 (§6.2.2) already gives voters a costless, non-punitive way to express "no view" on a nominee — declining to select them. Stage 2 is a confirmation gate on candidates who have already cleared that filter, and the question at that gate is binary. An Abstain option would therefore duplicate a channel Stage 1 already provides while allowing voting power to be contributed to a candidate's quorum without expressing support for that candidate. Because Stage 2 ballots run concurrently across all shortlisted candidates, that would let a single holder supply the quorum for an entire slate in one action, leaving the outcome to be decided by a small affirmative bloc. The Minimum Affirmative Support floor (DAO Parameters §3.3A) is unnecessary here for the same reason: with no Abstain, the quorum and approval thresholds together guarantee a minimum level of affirmative support by construction.

---

### 6.3 Quorum

**Participation** means the total voting power cast on a proposal, including Abstain. Participation is the measure for all quorum tests and for the absolute participation floor in DAO Parameters §3.2.

**Decisive Votes** means Yes + No, excluding Abstain. Decisive Votes is the denominator for every approval threshold, vote share, ratio, and margin calculation in this framework and in DAO Parameters, unless a provision expressly states otherwise. Where a vote type provides no Abstain option (§6.2.2, §6.2.6, §6.2.7), Participation and Decisive Votes are equal.

**Graded ballots.** Majority Judgment (§6.2.4) is a graded vote type: a voter assigns each candidate a grade, which is neither a Yes nor a No. Two consequences follow, and this section is the provision that expressly states them.

* **Participation** for a Majority Judgment round means the total voting power of all valid ballots cast in that round. Because a valid ballot grades every candidate, participation is a single figure for the round and is the same for every candidate in it. It is measured against the quorum for the round in the ordinary way (DAO Parameters §6B)
* **Decisive Votes is not used for Majority Judgment.** There is no Yes share to compute and no ratio or margin measured against Decisive Votes. The function that an approval threshold performs for a Yes/No vote type is performed for Majority Judgment by the Minimum Median Grade (§6.2.4), which is a threshold on rank rather than on share. The RAC must apply that test, not the §6.4 default

This is the same construction used in DAO Parameters §3A.4, where a single provision expressly displaces the default denominator and the RAC is directed to apply the stated one.

An Abstain option exists only in the Standard vote type (§6.2.1) — Constitutional, Governance Process, Treasury & Budget, and Executable proposals. No other vote type offers it, and in particular Stage 2 election confirmations do not (§6.2.7). Majority Judgment has no Abstain grade either: a voter who does not wish to support a candidate grades them low, and the grade scale itself carries that expression.

A proposal is valid only if quorum is met. Quorum is measured as Participation expressed as a percentage of eligible voting power — Yes, No, and Abstain votes all count toward it. Abstain therefore counts toward quorum but not toward the approval calculation (§6.2.1).

Meeting quorum is necessary but not sufficient. A Standard vote must additionally meet the Minimum Affirmative Support floor (DAO Parameters §3.3A), which is expressed as YES voting power against eligible voting power and is unaffected by Abstain volume. The floor exists so that a proposal carried over quorum largely by Abstain votes cannot pass on a negligible base of affirmative support. It applies only to the Standard vote type; vote types without an Abstain option do not need it, because their quorum and approval thresholds together already imply a minimum affirmative share.

Quorum thresholds are defined in DAO Parameters and may vary by proposal type.

---

### 6.4 Approval Thresholds

Approval thresholds vary by proposal type:

* Constitutional: supermajority required
* Governance: higher threshold
* Treasury: standard majority
* Temperature Check (TC): simple majority — YES / NO only, no Abstain (see §6.2.6)

All approval thresholds are measured against Decisive Votes (§6.3). Standard votes are additionally subject to the Minimum Affirmative Support floor (DAO Parameters §3.3A), measured against eligible voting power. Majority Judgment (§6.2.4) is outside this section: it has no approval threshold measured against a denominator, and its equivalent test is the Minimum Median Grade (§6.3, §6.2.4).

Exact thresholds defined in DAO Parameters.

---

### 6.5 Result Determination Procedure

The RAC is responsible for formally determining the outcome of each vote and publishing the official result. This procedure applies to all vote types regardless of which governance platform is in use.

1. **Retrieve results.** After the voting period closes, the RAC retrieves the raw vote data from the governance platform.

2. **Verify quorum.** The RAC confirms that Participation (§6.3) meets the quorum threshold for the proposal type, expressed as a percentage of eligible voting power (DAO Parameters §3.2). Any quorum indicator displayed by the governance platform is informational; the percentage threshold in DAO Parameters is authoritative.

3. **Apply approval threshold (Standard votes).** For Standard votes, the RAC confirms that the YES share of Decisive Votes (§6.3) meets the type-specific approval threshold (DAO Parameters §3.3).

3A. **Verify Minimum Affirmative Support (Standard votes).** For Standard votes, the RAC confirms that YES voting power, expressed as a percentage of eligible voting power, meets the Minimum Affirmative Support floor for the proposal type (DAO Parameters §3.3A). A proposal that meets quorum and the approval threshold but fails this floor does not pass. The RAC publishes the Abstain volume and the computed affirmative-support percentage alongside the result under step 5.

4. **Determine winner (Approval Voting).** The RAC identifies the option with the highest total voting power and confirms it meets the minimum winner threshold (DAO Parameters §3.5). If no option meets the threshold, the proposal fails.

4A. **Determine result (Majority Judgment).** For a Majority Judgment election (§6.2.4), the RAC computes each candidate's grade distribution and median grade; applies the Minimum Median Grade in force for the round to determine which candidates are electable; ranks candidates by median grade; applies the tie-break where a tie affects the outcome, and adjudicates any tie the tie-break does not resolve; assigns seats in ranking order with fallback advancement past candidates who are not electable; records the reserve list and the number of seats referred to vacancy handling. Where the round closed below quorum, the RAC instead takes one of the two routes in §6.2.4 — opening the single permitted rerun and publishing the rerun notice required there, or restarting the election under the two-stage mechanism — and publishes which route it has taken and its reasons.

5. **Publish result.** The RAC publishes the official outcome — including raw results, quorum calculation, threshold applied, and winner determination — within the result publication window (DAO Parameters §3.5). For a Majority Judgment election the published result must additionally include each candidate's full grade distribution, each candidate's median grade, the Minimum Median Grade applied, the quorum classification for the round, whether a tie-break or an RAC tie adjudication was applied and to which candidates, the seated candidates in ranking order, the reserve list, and any seats referred to vacancy handling. Publication constitutes the official record and opens the 48-hour veto window (§8).

---

## 7. Proposal Conflicts

If two proposals conflict and cannot both be implemented:

* The proposal with the higher YES share of Decisive Votes (§6.3) prevails
* If the margin between them is less than 5 percentage points, both are invalidated and must be resubmitted as a single proposal with clearly defined alternatives. The margin is measured between the two YES shares of Decisive Votes, so differing Abstain volumes cannot by themselves create or remove a conflict
* If one proposal passed quorum and the other did not, the one that met quorum prevails regardless of vote share

These rules turn on a Yes share of Decisive Votes and so apply only to vote types that produce one. They do not apply to an Election proposal (§4.5): an election does not compete with another proposal for the same outcome, and a Majority Judgment result has no Yes share to compare (§6.3). Where a passed proposal would abolish, merge, or alter a role for which an election is running, the RAC publishes the conflict and the DAO resolves it by proposal; the election result stands unless and until it is displaced by that proposal.

The RAC flags conflicts at the start of the voting period where possible, so the DAO can be aware before voting closes.

---

## 8. Veto Mechanism

### 8.1 Purpose

The veto mechanism exists to:

* Prevent proposals that violate governance rules
* Protect against malicious or invalid proposals

---

### 8.2 Conditions

A veto may only be filed if the proposal:

* Violates the Charter, or
* Violates an existing governance process document

Disagreement with the policy substance of a proposal is not grounds for veto.

---

### 8.3 Who May File

Any Governance Participant holding at least the Veto Filing Threshold (DAO Parameters §4 — 0.1% of eligible voting power, verified against the most recent governance snapshot) may file a veto challenge. No aggregate participation or co-signature requirement applies: a single valid filing triggers RAC review under §8.4, which is the substantive filter on veto grounds.

---

### 8.3A Identification and Proof of Holding

A veto filing must identify the filer and evidence the Veto Filing Threshold. The filing must state:

* the proposal identifier and the date of RAC result publication
* each account address relied on to meet the Veto Filing Threshold
* for each such address, a message signed by that account over the proposal identifier

The RAC verifies the signatures and the aggregate holding against the most recent governance snapshot.

A filing that meets the requirements of §8.2 and §8.4 but carries an incomplete holding proof is not rejected outright. The RAC notifies the filer and allows the **Holding Proof Cure Period** (DAO Parameters §4) to complete it. The cure period runs inside the RAC's determination window under §8.4 and does not extend it. A filing whose proof is not completed within the cure period lapses.

---

### 8.4 Process

1. **Filing.** A veto challenge is filed either by transmission to the **Veto Filing Channel** (DAO Parameters §4) or by publication of the filing to the **Official Venue**. The two routes are independently valid: a filer who uses the Channel is not required to publish, and a filer who publishes is not required to use the Channel. Filing is effective on the earlier of transmission and publication, and must occur within the veto window defined in **DAO Parameters §4**. Where recorded transmission time and recorded receipt time differ, the earlier governs.
2. **Content.** The filing must cite the specific Charter section or governance rule alleged to be violated, and must meet the identification and holding-proof requirements in §8.3A.
3. **Publication of Channel filings.** The Governance Operator publishes every filing received at the Channel verbatim to the Official Venue, together with its receipt timestamp, within the **Channel Publication Window** (DAO Parameters §4). Failure to publish does not invalidate the filing and is a reportable breach of the Governance Operator's duties under the Delegate Mandate. Where the Governance Operator is unavailable, or is the subject of the filing, the RAC publishes.
4. **Determination.** The RAC reviews the challenge and issues a determination within **48 hours** of the effective filing time:
   - If the RAC determines the proposal violates governance rules, the proposal is **halted** pending a corrective resubmission
   - If the RAC determines no violation exists, the proposal **proceeds** to execution
5. **Override.** The DAO may override any RAC determination via a Governance Process proposal

The Channel is a convenience route, not a gate. Because publication to the Official Venue is independently sufficient at all times, no operator of the Channel — and no failure, filter, or unavailability of it — can prevent a veto from being validly filed.

---

### 8.5 Limitations

* Cannot be used to block proposals based on policy disagreement
* Repeated frivolous filings may result in sanctions under the **Code of Conduct §4** and, once active, the Dispute Resolution & Arbitration Policy
* Cannot be used after the 48-hour window has closed

---

## 9. Cooldowns & Resubmission

### 9.1 Failed Proposals

Failed proposals may not be resubmitted until the applicable cooldown period has elapsed. Cooldown periods are defined in **DAO Parameters §3.4**.

---

### 9.2 Exception

A proposal may be resubmitted without cooldown only if it failed due to a technical issue with the governance platform and the resubmission makes no change to the proposal's intent, category, or budget. Substantive revisions require the standard cooldown.

---

## 10. Proposal Validity

A proposal is invalid if:

* It violates the Charter
* It exceeds DAO authority
* It lacks required information

The RAC may flag invalid proposals but does not decide outcomes.

---

## 11. Transparency

All proposals must:

* Be publicly accessible
* Include sufficient information for decision-making

Exceptions allowed only under defined confidentiality rules.

---

## 12. Execution Handoff

Once a proposal passes, the execution handoff proceeds as follows:

1. The RAC publishes the official result (§6.5).
2. The veto window closes with no valid veto filed, or any veto challenge is resolved in favour of the proposal (§8; DAO Parameters §4).
3. The pre-execution hold elapses (DAO Parameters §9).
4. The RAC or named executor confirms execution readiness and notifies the relevant execution body (Treasury Signers, Working Group, or smart contract).
5. Execution follows the workflow defined in **Execution & Treasury Actions Policy §9**.

---

## 13. Governance Parameters

The following are defined separately and may be updated:

* Quorum thresholds
* Voting duration
* Approval thresholds
* Minimum Affirmative Support floors (DAO Parameters §3.3A)
* Cooldown periods
* Veto parameters, including the Veto Filing Channel, Channel Publication Window, and Holding Proof Cure Period (DAO Parameters §4)

---

## 14. Amendments

_Amendment procedures and classification requirements are defined in the **Governance Maintenance & Upgrade Framework**._
