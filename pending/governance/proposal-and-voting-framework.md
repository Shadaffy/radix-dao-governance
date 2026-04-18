# Proposal & Voting Framework

---

## 1. Scope

This document defines:

* How proposals are created, discussed, and approved
* Voting mechanisms and thresholds
* Proposal categories and requirements
* Safeguards such as veto and resubmission rules

---

## 2. Out of Scope

This document does NOT define:

* Treasury management rules (see Treasury Policy)
* Execution authority (see Execution Policy)
* Emergency actions (see Emergency Policy)

---

## 3. Proposal Lifecycle

All proposals follow this lifecycle:

### 3.1 Draft Stage

* Idea introduced publicly (e.g., forum, RadixTalk)
* Open discussion and feedback

---

### 3.2 Formal Submission

* Proposal submitted via governance interface
* Must include required fields (see Section 5)

---

### 3.3 Review Period

* Minimum review period before voting
* Community discussion continues

---

### 3.4 Voting Period

* Token holders vote
* Voting power determined by snapshot

---

### 3.5 Outcome

* Passed → moves to execution
* Failed → cooldown applies

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

> **Phase 1 note:** In Phase 1, no standing Working Groups or funded operational bodies exist. Any Executable proposal that requires compensated work — including fixed-rate service delivery — must include a Treasury & Budget component specifying the cost arrangement and receiving party. Such combined proposals are evaluated against Treasury & Budget quorum and approval thresholds (the more stringent of the two proposal types). Executable proposals with zero cost may proceed under Executable thresholds.

---

### 4.5 Signaling Proposals

* Non-binding decisions
* Community sentiment

---

### 4.6 Election Proposals

Selection of candidates for DAO roles: RAC members, Working Group Stewards, Strategic Coordination WG members, and Authorized Signers.

Elections follow a two-stage process:

**Stage 1 — Shortlisting (Approval Voting)**
A Signaling proposal using Approval Voting (§6.2.2) is published listing all eligible nominees. Voters may select up to the number of open seats (see DAO Parameters §6B). The top candidates by total voting power — up to the shortlist size defined in DAO Parameters §6B — advance to Stage 2. The Stage 1 result is procedurally binding.

**Stage 2 — Confirmation (Standard Vote)**
Each shortlisted candidate is put to a separate Standard (YES/NO/ABSTAIN) proposal (§6.2.1). A candidate is confirmed if they meet the quorum and approval threshold for Election proposals (DAO Parameters §3.2–3.3). Stage 2 proposals may run concurrently.

**Fallback**
If a shortlisted candidate fails Stage 2, the next-highest candidate from Stage 1 is automatically advanced to a replacement confirmation vote. This continues until all seats are filled or the shortlist is exhausted. If the shortlist is exhausted, remaining vacancies follow the vacancy handling process in the Elections & Role Governance Policy §11.

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
* **Executor commitment declaration** *(required for all Executable and combined Executable + Treasury proposals)* — Named executor(s) must be identified by name and wallet address, and must have confirmed in writing (forum post or signed statement) that they accept the execution responsibility before the proposal enters the Review Period. Where the proposer is also the executor, this must be declared as a conflict of interest.
* **Cumulative recipient disclosure** (Treasury & Budget proposals only): total disbursements to the same recipient, entity, or affiliated group over the trailing 90 days. The RAC verifies this field before opening the veto window. A missing or materially incorrect disclosure is valid grounds for a veto filing (Charter / rule violation: failure to meet required proposal content).

---

## 6. Voting Mechanics

### 6.1 Voting Power

* Voting power is determined at a fixed snapshot
* Snapshot occurs at start of voting period
* Measured in XRD-equivalent units; eligible holdings include:
  * Liquid XRD held directly
  * LSU (Liquid Staking Units) — converted to XRD equivalent based on the LSU redemption rate at the time of the snapshot

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

* Applies to: Signaling proposals with multiple options
* Voters may select any number of options from a defined list (maximum per DAO Parameters §3.5)
* Each selected option receives the voter's full voting power
* Result: the option with the highest total voting power wins, provided it meets the minimum winner threshold defined in DAO Parameters §3.5
* If no option meets the threshold, the proposal fails; the proposer may resubmit with revised options after the standard cooldown

---

#### 6.2.3 Weighted Allocation

* Applies to: Treasury / Budget proposals distributing funds across multiple recipients
* Voters distribute 100 points across the available options
* The final allocation per option equals the power-weighted average of all voter distributions, normalised by total voting power
* Options receiving less than the minimum weight threshold (see DAO Parameters §3.5) are excluded and their weight redistributed proportionally across remaining options
* The overall proposal still requires quorum and approval threshold as defined for Treasury proposals (DAO Parameters §3.2 and §3.3)
* Weighted Allocation activates in Phase 2; the RAC confirms activation by publishing a notice to the governance forum when the required tooling is in place

---

#### 6.2.4 Elections

* Applies to: Election Proposals (§4.6)
* Stage 1 uses Approval Voting (§6.2.2) for shortlisting
* Stage 2 uses Standard voting (§6.2.1) for confirmation
* Full procedure defined in §4.6 and Elections & Role Governance Policy §7

---

### 6.3 Quorum

A proposal is valid only if quorum is met.

Quorum thresholds are defined in DAO Parameters and may vary by proposal type.

---

### 6.4 Approval Thresholds

Approval thresholds vary by proposal type:

* Constitutional: supermajority required
* Governance: higher threshold
* Treasury: standard majority
* Signaling: simple majority

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

Any token holder may file a veto challenge, provided the minimum participation threshold is met (see DAO Parameters §4).

---

### 8.4 Process

1. A veto challenge must be filed via the governance interface within **48 hours** of the vote closing (see DAO Parameters §4)
2. The filing must cite the specific Charter section or governance rule being violated
3. The RAC reviews the challenge and issues a determination within **48 hours** of filing:
   - If the RAC determines the proposal violates governance rules, the proposal is **halted** pending a corrective resubmission
   - If the RAC determines no violation exists, the proposal **proceeds** to execution
4. The DAO may override any RAC determination via a Governance Process proposal

---

### 8.5 Limitations

* Cannot be used to block proposals based on policy disagreement
* Repeated frivolous filings may result in sanctions per Dispute Resolution Policy
* Cannot be used after the 48-hour window has closed

---

## 9. Cooldowns & Resubmission

### 9.1 Failed Proposals

* Cannot be immediately resubmitted

---

### 9.2 Exception

Resubmission is allowed if:

* Proposal failed due to technical issue
* Minor corrections are made

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

Approved proposals are forwarded to:

* Execution mechanisms (on-chain or off-chain)
* Relevant Working Groups

Execution rules are defined in the Execution Policy.

---

## 13. Governance Parameters

The following are defined separately and may be updated:

* Quorum thresholds
* Voting duration
* Approval thresholds
* Cooldown periods

---

## 14. Amendments

This framework may be updated via governance proposals.
