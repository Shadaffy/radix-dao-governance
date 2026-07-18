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

---

### 4.4 Executable Proposals

* Technical or operational changes
* On-chain or system execution

**Multi-option Approval Voting polls** are a sub-type of Executable proposals for cases where the community must choose between several defined options rather than a binary question. They use Approval Voting (§6.2.2) rather than the Standard vote type. A shortened 1-day Temperature Check applies (DAO Parameters §3.1). The result is advisory unless the proposal text mandates execution of the winning option.

Any Executable proposal that requires compensated work — including fixed-rate service delivery — must include a Treasury & Budget component specifying the cost arrangement and receiving party. Such combined proposals are evaluated against Treasury & Budget quorum and approval thresholds (the more stringent of the two proposal types). Executable proposals with zero cost proceed under Executable thresholds.

---

### 4.5 Election Proposals

Selection of candidates for DAO roles: RAC members, Working Group Stewards, Strategic Coordination WG members, and Treasury Signers.

Election proposals use a modified version of the standard pipeline (§3): the Draft Discussion and Nomination Period are merged into a single combined Nomination & Discussion Window (DAO Parameters §3.1 and §6B), and the Temperature Check is compressed to a minimum of 1 day (DAO Parameters §3.1). The election pipeline is therefore: Nomination & Discussion Window → Temperature Check → Stage 1 Shortlisting → Stage 2 Confirmation.

**Two-Stage Election Process**

The current election mechanism is a two-stage Approval Voting → confirmation process. A Majority Judgment upgrade is described under §6.2.4 and may be activated by future Governance Proposal once the required tooling is available; until activation, the two-stage process below is the operative procedure.

**Stage 1 — Shortlisting (Approval Voting)**
An Approval Voting poll (§6.2.2) is published listing all eligible nominees. Voters may select any number of nominees they approve. The top candidates by total voting power — up to the shortlist size defined in DAO Parameters §6B — advance to Stage 2. The Stage 1 result is procedurally binding. Stage 1 has no separate quorum requirement; the Temperature Check result is sufficient. The minimum winner threshold (DAO Parameters §3.5) does not apply; candidates are ranked by total voting power only. If two or more candidates are tied in voting power for the last available shortlist slot, all tied candidates are included in the shortlist; the shortlist size is expanded by the number of additional tied candidates.

**Stage 2 — Confirmation (Standard Vote)**
Each shortlisted candidate is put to a separate Standard (YES/NO/ABSTAIN) proposal (§6.2.1). A candidate is confirmed if they meet the quorum and approval threshold defined by the DAO parameters "Election Stage 2 Quorum" and "Election Stage 2 Approval Threshold" in DAO Parameters §6B. Stage 2 proposals may run concurrently.

**Seating of confirmed candidates**
Because the shortlist is larger than the number of open seats (DAO Parameters §6B — Election Shortlist Multiplier), more candidates may be confirmed at Stage 2 than there are seats. Where that occurs, seats are filled by confirmed candidates in descending order of total voting power received in Stage 1: Stage 2 confirmation establishes eligibility to be seated, and the Stage 1 ranking determines the order of seating. If two or more confirmed candidates are tied in Stage 1 total voting power for the last available seat, the tie is resolved in favour of the candidate with the higher YES-to-total-votes-cast ratio in their Stage 2 confirmation vote; if the tie persists, the RAC conducts a single runoff Approval Voting poll between the tied candidates using the short Temperature Check period (DAO Parameters §3.1). The Stage 1 tie-expansion rule above does not apply at the seat boundary, where the number of seats is fixed. A confirmed candidate who is not seated is not elected, but is placed on the reserve list for the role and may be seated to fill a later same-role vacancy without a further election (Elections & Role Governance Policy §7.5).

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
* Snapshot occurs at start of voting period
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

* Applies to: Constitutional, Governance Process, Executable proposals
* Voters cast one of three options: Yes, No, or Abstain
* Abstain counts toward quorum but not toward the approval threshold
* Result: proposal passes if the YES share of votes cast (excluding Abstain) meets the approval threshold for the proposal type (see DAO Parameters §3.3)

---

#### 6.2.2 Approval Voting

* Applies to: Election shortlisting (§4.5) and multi-option Executable proposals (§4.4)
* Voters may select any number of options from a defined list. For multi-option Executable proposals, the ballot is capped at 8 options (DAO Parameters §3.5). For election shortlisting, the ballot lists all eligible nominees and selections are unrestricted (DAO Parameters §6B).
* Each selected option receives the voter's full voting power
* Result: the option with the highest total voting power wins. For multi-option Executable proposals, the winner must meet the minimum winner threshold (DAO Parameters §3.5); if no option meets the threshold, the proposal fails and the proposer may resubmit after the standard cooldown. For election Stage 1 shortlisting, the minimum winner threshold does not apply — the top candidates by total voting power advance to Stage 2 (§4.5).

---

#### 6.2.3 Weighted Allocation

* Applies to: Treasury / Budget proposals distributing funds across multiple recipients
* Voters distribute 100 points across the available options
* The final allocation per option equals the power-weighted average of all voter distributions, normalised by total voting power
* Options receiving less than the minimum weight threshold (see DAO Parameters §3.5) are excluded and their weight redistributed proportionally across remaining options
* The overall proposal still requires quorum and approval threshold as defined for Treasury proposals (DAO Parameters §3.2 and §3.3)
* Weighted Allocation activates once the required tooling is in place; the RAC confirms activation by publishing a notice to the governance forum

---

#### 6.2.4 Majority Judgment

* Applies to: Election Proposals (§4.5), once tooling is available
* Voters assign a grade to each candidate from a defined scale (see DAO Parameters §3.5)
* The winner is the candidate with the highest median grade across all voter submissions
* In multi-seat elections, the top candidates by median grade fill all open seats — the median-grade ranking is itself the seating order, so the oversubscribed-confirmation question addressed for the two-stage process in §4.5 and Elections & Role Governance Policy §7.2.1 (seating by Stage 1 power), and the reserve-list mechanism that reuses surplus confirmations (Elections & Role Governance Policy §7.5), do not arise here and are specific to the two-stage process
* Tie-break: one ballot showing the tied candidates' median grade is removed from each tied candidate in turn; repeat until the tie is broken
* Majority Judgment activates once the required tooling is in place; the RAC confirms activation by publishing a notice to the governance forum. Until activation, elections use the two-stage process in §6.2.5.

---

#### 6.2.5 Two-Stage Elections

* Applies to: Election Proposals (§4.5) — the operative election mechanism until Majority Judgment (§6.2.4) is activated
* Stage 1 uses Approval Voting (§6.2.2) for shortlisting — voters may select any number of nominees
* Stage 2 uses Standard voting (§6.2.1) for confirmation of each shortlisted candidate
* Full procedure defined in §4.5 and Elections & Role Governance Policy §7

---

#### 6.2.6 Temperature Check Vote (YES / NO)

* Applies to: The Temperature Check stage (§3.2) for all proposal types
* Voters cast one of two options: Yes or No. There is no Abstain option.
* Quorum is measured by total voting power cast (YES + NO only)
* Result: TC passes if the YES share of votes cast meets the TC approval threshold (≥50% YES; see DAO Parameters §3.3)

---

### 6.3 Quorum

A proposal is valid only if quorum is met. Quorum is measured by total voting power cast — Yes, No, and Abstain votes all count toward the quorum threshold. Abstain counts toward quorum but not toward the approval calculation (§6.2.1). For Temperature Check votes (§6.2.6), there is no Abstain option; quorum is measured by YES + NO votes only.

Quorum thresholds are defined in DAO Parameters and may vary by proposal type.

---

### 6.4 Approval Thresholds

Approval thresholds vary by proposal type:

* Constitutional: supermajority required
* Governance: higher threshold
* Treasury: standard majority
* Temperature Check (TC): simple majority — YES / NO only, no Abstain (see §6.2.6)

Exact thresholds defined in DAO Parameters.

---

### 6.5 Result Determination Procedure

The RAC is responsible for formally determining the outcome of each vote and publishing the official result. This procedure applies to all vote types regardless of which governance platform is in use.

1. **Retrieve results.** After the voting period closes, the RAC retrieves the raw vote data from the governance platform.

2. **Verify quorum.** The RAC confirms that total voting power cast meets the quorum threshold for the proposal type, expressed as a percentage of eligible voting power (DAO Parameters §3.2). Any quorum indicator displayed by the governance platform is informational; the percentage threshold in DAO Parameters is authoritative.

3. **Apply approval threshold (Standard votes).** For Standard votes, the RAC confirms that the YES share of votes cast (excluding Abstain) meets the type-specific approval threshold (DAO Parameters §3.3).

4. **Determine winner (Approval Voting).** The RAC identifies the option with the highest total voting power and confirms it meets the minimum winner threshold (DAO Parameters §3.5). If no option meets the threshold, the proposal fails.

5. **Determine allocation (Weighted Allocation).** The RAC computes the power-weighted average allocation per option, applies the minimum weight threshold exclusion rule (DAO Parameters §3.5), and publishes the final allocation breakdown.

6. **Publish result.** The RAC publishes the official outcome — including raw results, quorum calculation, threshold applied, and winner determination — within the result publication window (DAO Parameters §3.5). Publication constitutes the official record and opens the 48-hour veto window (§8).

---

## 7. Proposal Conflicts

If two proposals conflict and cannot both be implemented:

* The proposal with the higher YES vote share (as a percentage of total votes cast) prevails
* If the margin between them is less than 5 percentage points, both are invalidated and must be resubmitted as a single proposal with clearly defined alternatives
* If one proposal passed quorum and the other did not, the one that met quorum prevails regardless of vote share

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

### 8.4 Process

1. A veto challenge must be filed via the governance interface within the veto window defined in **DAO Parameters §4**
2. The filing must cite the specific Charter section or governance rule being violated
3. The RAC reviews the challenge and issues a determination within **48 hours** of filing:
   - If the RAC determines the proposal violates governance rules, the proposal is **halted** pending a corrective resubmission
   - If the RAC determines no violation exists, the proposal **proceeds** to execution
4. The DAO may override any RAC determination via a Governance Process proposal

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
* Cooldown periods

---

## 14. Amendments

_Amendment procedures and classification requirements are defined in the **Governance Maintenance & Upgrade Framework**._
