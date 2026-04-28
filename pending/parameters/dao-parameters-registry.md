# DAO Parameters Registry

---

## 1. Purpose

This document defines the **configurable parameters** governing DAO operations.

These parameters:

* Enable flexibility without modifying core governance documents
* Provide clarity on thresholds, durations, and limits
* May be updated via governance proposals

---

## 2. Scope

This registry defines:

* Voting thresholds
* Quorum requirements
* Time durations
* Budget limits
* Emergency thresholds

---

## 3. Governance Parameters

---

### 3.1 Voting Durations

| Parameter               | Value    | Description                           |
| ----------------------- | -------- | ------------------------------------- |
| Draft Discussion Period | 5–7 days | Minimum time for community discussion |
| Review Period           | 2–3 days | Time between submission and voting    |
| Voting Period           | 5–7 days | Duration of voting                    |

---

### 3.2 Quorum Requirements

Quorum is measured as a percentage of eligible voting power. Eligible voting power includes liquid XRD holdings and LSU holdings converted to their XRD equivalent at the time of the voting snapshot.

| Proposal Type      | Quorum                      |
| ------------------ | --------------------------- |
| Constitutional     | 10% of eligible voting power |
| Governance Process | 7%                     |
| Treasury / Budget  | 7%                     |
| Executable         | 5%                     |
| Signaling          | 3%                     |

**Absolute Participation Floor (Treasury / Budget proposals):** In addition to the percentage quorum above, a Treasury / Budget proposal requires a minimum of 50 unique voting addresses. Both conditions must be met. This floor is not subject to the Governance Continuity Fallback (§9A).

---

### 3.3 Approval Thresholds

| Proposal Type      | Approval  |
| ------------------ | --------- |
| Constitutional     | ≥ 66% YES |
| Governance Process | ≥ 60% YES |
| Treasury / Budget  | ≥ 50% YES |
| Executable         | ≥ 50% YES |
| Signaling          | ≥ 50% YES |

---

### 3.4 Cooldown Periods

| Scenario               | Cooldown    |
| ---------------------- | ----------- |
| Failed Proposal        | 7 days      |
| Minor Fix Resubmission | No cooldown |
| Major Resubmission     | 7 days      |
| Per-Proposer Treasury Submission Limit | 1 Treasury & Budget proposal per rolling 30-day period per wallet address. A second submission within the window requires prior RAC notification and acknowledgement posted to the governance forum before the proposal enters the review period. |

---

### 3.5 Multi-Choice Voting Parameters

| Parameter | Value | Description |
| --------- | ----- | ----------- |
| Approval Voting: Maximum Options | 8 | Maximum number of selectable options per GP |
| Approval Voting: Minimum Winner Threshold | ≥ 30% of total votes cast | Minimum voting power an option must receive to be declared winner |
| Weighted Allocation: Maximum Options | 12 | Maximum number of options per Treasury / Budget allocation GP |
| Weighted Allocation: Minimum Option Weight | 5% | Options receiving less than this share of total distributed weight are excluded; weight redistributed proportionally |
| Majority Judgment: Grade Scale | Excellent / Very Good / Good / Acceptable / Poor | Standard five-grade scale for election votes |
| Result Publication Window | Within 48 hours of vote close | Deadline for RAC to publish the official outcome, quorum calculation, threshold applied, and winner determination; aligned with the veto window (§4) which runs concurrently |

---

## 4. Veto Parameters

| Parameter                  | Value              |
| -------------------------- | ------------------ |
| Veto Window                | 48 hours post-vote |
| Minimum Participation      | 3% quorum (XRD and LSU-equivalent combined) |
| Optional Stake Requirement | None               |

---

## 5. RAC Parameters

---

### 5.1 RAC Composition

| Parameter                        | Value                                                                  |
| -------------------------------- | ---------------------------------------------------------------------- |
| Members                          | 5 minimum (exact count ≥5, set by initial Constitutional Proposal before Phase 1 launch; may only be reduced below 5 by Constitutional Proposal) |
| Term Length                      | 6 months                                                               |
| Routine Decision Quorum          | Simple majority (more than half of seated members)                     |
| Routine Decision Approval        | Simple majority YES                                                    |
| Seat Vacancy Definition          | A seat is immediately vacated upon: (a) confirmed death notified by a pre-registered emergency contact; (b) written resignation; or (c) written declaration from a pre-registered emergency contact that the member is medically incapacitated and unable to perform their function. Vacated seats are excluded from quorum calculations immediately upon notification. |
| Emergency Contact Requirement    | Each RAC member must register an emergency contact at appointment and update it at each term renewal. Emergency contacts are held by the Compliance Liaison and the Governance & Legal WG. |

---

### 5.2 RAC Emergency Thresholds

| Parameter                 | Value         |
| ------------------------- | ------------- |
| Quorum                    | ≥ 2/3 members |
| Approval Threshold        | ≥ 75%         |
| Emergency Action Duration | Max 7 days    |

---

## 6. Treasury Parameters

---

### 6.1 Budget Limits

| Parameter                          | Value                |
| ---------------------------------- | -------------------- |
| Working Group Budget Cap           | Defined per proposal |
| Single Transaction Limit           | $12,000 USDC |
| Emergency Spend Limit              | $5,000 USDC — for operational emergencies (asset security, key rotation, critical infrastructure) |
| Governance Reconstitution Limit    | $25,000 USDC — available only when a RAC or signer continuity event has been declared under Governance Continuity §4.1 or §4.2; covers emergency election costs, legal filings, and Registered Agent compliance fees; subject to GP ratification within 30 days |
| Legal Defense Advancement Limit    | $25,000 USDC per legal proceeding — a bridging pool covering immediate legal response costs for one or more Delegates or RAC members named in the same proceeding arising from their role, before a GP can authorize ongoing funding; the $12,000 Single Transaction Limit does not apply within this pool; does not require a declared continuity event; subject to GP ratification within 30 days and the repayment undertaking in OA §11.3 |
| Rolling 30-Day Outflow Cap         | $50,000 USDC or 5% of treasury value (whichever is lower) — maximum total Treasury / Budget disbursements across all passed proposals in any rolling 30-day window. Signers must refuse execution of any proposal that would cause the rolling total to breach this cap and must report the refusal to RAC immediately. Adjustable by Treasury & Budget proposal. |
| Emergency Safe Address             | To be designated by separate Treasury & Budget proposal before the treasury holds material value. Until designated, Tier 2 emergency asset movement (Emergency & Safeguards Policy §6) is not available. Changes to the designated address require a Treasury & Budget proposal. |

---

### 6.2 Treasury Structure

| Parameter                 | Value       |
| ------------------------- | ----------- |
| Multi-account Requirement | Yes         |
| Multisig Threshold        | See §6A: 3-of-5 standard, 4-of-5 high-risk |
| Audit Requirement         | Mandatory — an independent treasury audit is required annually. The RAC is responsible for scoping the audit and bringing an auditor appointment to governance for approval. The first audit process must be initiated within the Phase 1 completion window (see Activation Roadmap). |

---

## 6A. Treasury Signers Parameters

| Parameter                       | Value                           | Description                                           |
| ------------------------------- | ------------------------------- | ----------------------------------------------------- |
| Number of Treasury Signers    | 5                               | Total signer pool                                     |
| Minimum Signing Threshold       | 3 of 5                          | Minimum approvals required for standard actions       |
| High-Risk Signing Threshold     | 4 of 5                          | Minimum approvals required for high-risk actions      |
| Signer Term Length              | 6 months                        | Standard appointment term                             |
| Max Execution Window            | 5 business days                 | Time allowed to execute an approved action            |
| Max Acknowledgement Window      | 2 business days                 | Time allowed to acknowledge a valid execution request |
| Emergency Execution Window      | ASAP, within 24 hours           | Required response time during emergencies             |
| Required Availability Standard  | Respond within 2 business days  | Minimum expected responsiveness during active periods; declared unavailability periods are excluded (see Treasury Signers Rules §15) |
| Key Rotation Review Interval    | Every 6 months                  | Frequency of key / access review                      |
| Max Unexcused Inactivity Period | 21 days                         | Inactivity threshold before replacement review; declared unavailability periods are excluded (see §6B and Treasury Signers Rules §15) |
| Signer Replacement Window       | 21 days                         | Time to fill a vacant signer seat                     |
| Allowed Unilateral Actions      | None unless explicitly approved | Default rule for signer authority                     |
| Conflict Disclosure Requirement | Mandatory                       | Public or confidential as appropriate                 |
| Signer KYC Requirement          | Required where applicable       | Compliance standard                                   |

---

## 6B. Elections & Roles Parameters

| Parameter                           | Value     | Description                              |
| ----------------------------------- | --------- | ---------------------------------------- |
| Standard Term Length                | 6 months  | Default role duration                    |
| Auto-Renewal                        | Yes — unless challenged | Incumbent role holders are automatically renewed at term end unless a challenge is filed or the role holder declines (see Election & Role Governance Policy §9) |
| Term Renewal Challenge Window       | 14 days (opens 21 days before expiry, closes 7 days before expiry) | Period during which an eligible token holder may file a unilateral challenge notice to trigger a new election |
| Challenge Filing Threshold          | 0.1% of eligible voting power | Minimum holding required to file a valid challenge notice; verified against the most recent governance snapshot |
| Consecutive Renewal Cap             | 4 terms (2 years maximum continuous service) | After 4 consecutive terms in the same role, a standard two-stage election is mandatory; successful re-election resets the count to 1 |
| Election Voting Duration            | 5-7 days  | Length of election voting                |
| Nomination Period                   | 5-7 days  | Time allowed for candidate submissions   |
| Minimum Participation for Elections | Gov quorum| Quorum requirement                       |
| Removal Vote Threshold              | ≥ 50% YES | Required support to remove a role holder |
| Inactivity Threshold                | 21 days   | Time before inactivity review; declared unavailability periods are excluded. **"Inactivity"** means: no response to governance execution requests, no participation in any multisig signing actions, and no communication with the RAC within the threshold period. Passive activities (reading updates, monitoring forums) do not constitute activity. Declared unavailability periods (per Treasury Signers Rules §15) are excluded from inactivity counting. |
| Replacement Election Trigger Time   | 7 days    | Time before election must start          |
| Replacement Completion Time         | 21 days   | Max time to fill vacancy                 |
| Max Concurrent Roles per Individual | 2         | Limits role concentration                |
| Conflict Disclosure Requirement     | Mandatory | Required for all roles                   |
| Election Shortlist Multiplier       | 2×        | Stage 1 shortlist slots per open seat (e.g. 3 seats → top 6 advance to Stage 2) |
| Election Stage 1 Max Selections     | Unrestricted | Voters may approve any number of nominees in the Stage 1 Approval Voting proposal |
| Election Stage 2 Quorum             | 7% (Governance Process) | Quorum required for each Stage 2 confirmation vote |
| Election Stage 2 Approval Threshold | ≥ 60% YES (Governance Process) | Approval required for each Stage 2 confirmation vote |

---

## 6C. Dispute Resolution Parameters

| Parameter                       |   Value   | Description                          |
| ------------------------------- | --------- | ------------------------------------ |
| Level 1 Resolution Window       | 3–5 days  | Time for direct resolution           |
| Level 2 Mediation Window        | 5–7 days  | WG mediation time                    |
| RAC Review Window               | 5–7 days  | Time for RAC review                  |
| Max Escalation Time             | 21 days   | Total allowed escalation time        |
| Signer Response Time            | 48 hours  | Time to respond to execution request |
| Signer Dispute Escalation Time  | 48 hours  | Time before escalation allowed       |
| Misconduct Review Window        | 7–14 days | Time to review misconduct claims     |
| Governance Escalation Threshold | quorum    | Participation required to escalate   |
| Abuse Threshold                 | Case by case (RAC discretion, subject to DAO review) | Limit on repeated frivolous disputes |

---

## 7. Working Group Parameters

| Parameter           | Value    |
| ------------------- | -------- |
| Stewards per WG     | 2–3      |
| Term Length         | 6 months |
| Reporting Frequency | Monthly  |

---

## 8. Identity & Participation Parameters

| Parameter | Value | Description |
| --------- | ----- | ----------- |
| Voting Basis | XRD holdings and LSU (converted to XRD-equivalent via snapshot) | — |
| LSU Inclusion | Active (Phase 1) — snapshot-based XRD conversion | — |
| Delegation | Disabled — not yet supported by the governance platform | — |
| Sybil Resistance | Not active | — |
| UBO KYC Threshold | >25% of eligible voting power | Triggers mandatory KYC under Marshall Islands DAO Act; annual BOIR filing required Jan 1–Mar 31 |
| Compensation KYC Requirement | Required before first payment | Applies to all compensated contributors, contractors, and grant recipients (Standard and Strategic) |

---

## 9. Execution Parameters

| Parameter                 | Value          |
| ------------------------- | -------------- |
| Pre-Execution Hold        | 48 hours after vote close (mandatory) — Treasury Signers may not initiate execution of any Treasury / Budget or Executable proposal until the veto window (§4) has fully closed |
| High-Risk Execution Delay | 24 hours additional after the pre-execution hold (mandatory) — applies to transactions classified as high-risk (4-of-5 signing threshold per §6A); total minimum 72 hours after vote close |

---

## 9A. Governance Continuity Parameters

| Parameter | Value | Description |
|---|---|---|
| Governance Inactivity Trigger | 3 consecutive quorum failures on the same proposal type | Threshold before reduced quorum activates |
| Reduced Quorum Threshold | 50% of the standard quorum for that proposal type (minimum 1%) | Applies after inactivity trigger is met |
| Extended Voting Period | Double the standard voting duration | Applies alongside reduced quorum during inactivity |
| Reconstitution Deadline | 30 days after failure event | Maximum time to re-establish a failed role or body |

**Treasury / Budget exclusion:** Treasury / Budget proposals are excluded from the Governance Continuity Fallback. A Treasury / Budget proposal that fails to meet quorum must be resubmitted with revised scope or timing; the reduced quorum threshold and extended voting period do not apply.

---

## 10. Emergency Parameters

| Parameter           | Value           |
| ------------------- | --------------- |
| Emergency Duration  | Max 7 days      |
| Disclosure Deadline | Within 48 hours |
| Post-Review Window  | 7 days          |

---

## 11. Amendments

_Amendment procedures, change classification (minor parameter adjustment vs. major structural change), and versioning requirements are defined in the **Governance Maintenance & Upgrade Framework §4–6**._
