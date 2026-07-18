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
| Draft Discussion Period | ≥5 days  | Minimum time for community discussion on the RAC-designated platform. Does not apply to Election proposals; see Election Nomination & Discussion Window below. |
| Election Nomination & Discussion Window | 7–10 days | Combined nomination and community discussion period for Election proposals. Nominations open at the start of this window; community discussion runs concurrently. Replaces the separate Draft Discussion and Nomination Period for elections. After this window closes, the Temperature Check opens immediately. |
| Temperature Check Voting Period | 5–7 days | Duration of the TC vote for Constitutional, Governance Process, Treasury/Budget, and Executable proposals |
| Temperature Check Voting Period (Short) | ≥1 day | Duration of the TC vote for Election proposals and multi-option Approval Voting polls |
| DAO Proposal Voting Period | 5–7 days | Duration of the binding DAO Proposal vote |
| TC Elevation Window | 5 business days | Maximum time from the close of a passed Temperature Check to its elevation by the Governance Operator, or to documented grounds for delay being recorded with the RAC. Elapse without either triggers the elevation backstop (Governance Continuity Framework §4.2A) |
| Elevation Backstop Compliance Window | 2 business days | Time for the Governance Operator to comply with a formal RAC elevation instruction before backstop execution proceeds (Governance Continuity Framework §4.2A) |

---

### 3.2 Quorum Requirements

Quorum is measured as a percentage of eligible voting power. Eligible voting power is determined at the voting snapshot and includes all sources listed in §8A — at minimum liquid XRD holdings and LSU holdings converted to their XRD equivalent (the constitutional floor per Charter §12.1 item 4).

| Proposal Type      | Quorum                      |
| ------------------ | --------------------------- |
| Constitutional     | 10% of eligible voting power |
| Governance Process | 7%                     |
| Treasury / Budget  | 7%                     |
| Executable         | 5%                     |
| Temperature Check (TC) | 3%                 |

**Absolute Participation Floor (Treasury / Budget proposals):** In addition to the percentage quorum above, a Treasury / Budget proposal requires a minimum of 50 unique voting addresses. Both conditions must be met. This floor is not subject to the Governance Continuity Fallback (§9A).

---

### 3.3 Approval Thresholds

| Proposal Type      | Approval  |
| ------------------ | --------- |
| Constitutional     | ≥ 66% YES |
| Governance Process | ≥ 60% YES |
| Treasury / Budget  | ≥ 50% YES |
| Executable         | ≥ 50% YES |
| Temperature Check (TC) | ≥ 50% YES |

---

### 3.4 Cooldown Periods

| Scenario               | Cooldown    |
| ---------------------- | ----------- |
| Failed Proposal        | 7 days      |
| Minor Fix Resubmission | No cooldown |
| Major Resubmission     | 7 days      |
| Per-Proposer Treasury Submission Limit | 1 Treasury & Budget proposal per rolling 30-day period per wallet address. A second submission within the window requires prior RAC notification and acknowledgement posted to the governance forum before the TC voting period opens. |

---

### 3.5 Multi-Choice Voting Parameters

| Parameter | Value | Description |
| --------- | ----- | ----------- |
| Approval Voting: Maximum Options | 8 | Maximum number of options on the ballot per multi-option Executable proposal (§4.4). Does not apply to election shortlisting; election ballots list all eligible nominees (§6B). |
| Approval Voting: Minimum Winner Threshold | ≥ 30% of total votes cast | Minimum voting power an option must receive to be declared winner. Applies to multi-option Executable proposals (§4.4). Does not apply to election Stage 1 shortlisting; Stage 1 ranks candidates by total voting power only (§4.5). |
| Weighted Allocation: Maximum Options | 12 | Maximum number of options per Treasury / Budget allocation GP |
| Weighted Allocation: Minimum Option Weight | 5% | Options receiving less than this share of total distributed weight are excluded; weight redistributed proportionally |
| Majority Judgment: Grade Scale | Excellent / Very Good / Good / Acceptable / Poor | Standard five-grade scale for election votes |
| Result Publication Window | Within 48 hours of vote close | Deadline for RAC to publish the official outcome, quorum calculation, threshold applied, and winner determination; the veto window (§4) opens upon publication |

---

## 3A. Activation, Ratification & Transition Parameters

These parameters carry the activation and transition mechanics that the **Charter §4A** and the **Operating Agreement** (Article VIII, Schedule 5, §§5.7–5.9, §12.2) defer to the policy framework. They apply during the Advisory Governance Period (formation to the Activation Date).

### 3A.1 Framework Ratification (Activation Condition 6)

| Parameter | Value | Description |
| --------- | ----- | ----------- |
| Ratification Quorum | 10% of eligible voting power | Constitutional-level quorum for the one-time community ratification of the Charter and full policy framework (OA Schedule 5, condition 6) |
| Ratification Approval | ≥ 66% YES | Constitutional-level approval threshold for ratification |
| Scope | Charter **and** the full policy library | Ratification covers the entire community-written framework, not the Charter alone |

### 3A.2 Activation Vote (sole binding pre-activation vote)

| Parameter | Value | Description |
| --------- | ----- | ----------- |
| Activation Vote Voting Period | 5–7 days | Duration of the binding Activation Vote (OA §8.6) conducted after publication of the Activation Statement |
| Activation Vote Quorum | 10% of eligible voting power | Constitutional-level quorum |
| Activation Vote Approval | ≥ 66% YES | Constitutional-level approval |
| Quorum/Majority Failure | Re-run after the standard failed-proposal cooldown (§3.4) | If the Activation Vote fails to reach quorum or majority, it may be re-initiated after cooldown once the Transition RAC re-confirms the Schedule 5 evidence; the Transition RAC's non-discretionary initiation duty (OA §8.5) continues to apply |

### 3A.3 Advisory-Outcome Recognition Thresholds (OA §5.9)

| Parameter | Value | Description |
| --------- | ----- | ----------- |
| Advisory Recognition — Participation | ≥ 7% of eligible voting power | Participation an advisory outcome must reach to be "recognised", triggering the Transition RAC's acknowledgement/explanation duty (OA §5.9; period set in RAC Mandate) |
| Advisory Recognition — Majority | ≥ 50% YES | Majority required for recognition |
| Advisory Recognition — Entrenched-Provision amendments (higher threshold) | ≥ 10% participation and ≥ 66% YES | The elevated recognition threshold for an advisory outcome supporting a proposed amendment to an Entrenched Provision during the Transition Period (OA §12.2(c)(ii)) |

### 3A.4 Entrenched-Provision Amendment Thresholds

| Phase | Requirements |
| ----- | ------------ |
| During the Transition Period (OA §12.2(c)) | Unanimous affirmative vote of all **seated** Transition RAC members, being **not fewer than two** (OA §12.2(c)(i)), **and** a concurrent recognised advisory outcome meeting the higher threshold in §3A.3 **and** ≥14 days' prior notice to the registered agent and the Official Venue |
| Following the Activation Date (OA §12.2(d)) | Quorum **≥ 20%** of eligible voting power (not less than twice the 10% Constitutional quorum); approval **≥ two-thirds** of all Governance Tokens participating; where the amendment affects the Permanent RAC's constitutional role, composition, election mechanics, or removal, the prior written consent of the Permanent RAC by **≥ 2/3 of seated members**; and ≥21 days' prior public disclosure to the Official Venue |

### 3A.5 Permanent RAC Election Gating (Activation Condition 7)

| Parameter | Value | Description |
| --------- | ----- | ----------- |
| Minimum Seats for Activation | 5 | Minimum number of Permanent RAC members that must be duly elected and **formally seated** before the Activation Vote (OA Schedule 5, condition 7; §5.1) |
| KYC Before Seating | Mandatory | Every elected Permanent RAC member must complete KYC Tier 1 verification (Compliance Operations Policy) **before** being seated, satisfying OA §1.24 "Seated" and the §114(1)(d) natural-person-control requirement |
| Election Initiation Deadline | Within 90 days of framework ratification (Activation Condition 6) | The Transition RAC must open the Permanent RAC election within this fixed window so the election cannot be stalled |
| Seating Deadline | Before publication of the Activation Statement | Elected members must be seated before the Transition RAC publishes the Activation Statement (OA §8.5) |

---

## 4. Veto Parameters

| Parameter                  | Value              |
| -------------------------- | ------------------ |
| Veto Window                | 48 hours from RAC result publication |
| Veto Filing Threshold      | 0.1% of eligible voting power (all sources per §8A) held by the filer, verified against the most recent governance snapshot. The RAC's review of the challenge grounds (Proposal & Voting Framework §8.4) is the substantive filter; no aggregate participation requirement applies |
| Optional Stake Requirement | None               |

---

## 5. RAC Parameters

---

### 5.1 RAC Composition

| Parameter                        | Value                                                                  |
| -------------------------------- | ---------------------------------------------------------------------- |
| Transition RAC Members           | Exactly 3 (named in GP-PRE-1; constituted under Operating Agreement Article VI) |
| Permanent RAC Members            | Between 5 and 7 (set per election; defined in RAC Mandate §7). Adjustable by Governance Process proposal; minimum 5. |
| Term Length (Permanent RAC)      | 6 months                                                               |
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
| Legal Defense Advancement Limit    | $25,000 USDC per legal proceeding — a bridging pool covering immediate legal response costs for one or more Delegates or RAC members named in the same proceeding arising from their role, before a GP can authorize ongoing funding; the $12,000 Single Transaction Limit does not apply within this pool; does not require a declared continuity event; subject to GP ratification within 30 days and the repayment undertaking in OA §12.5 |
| Rolling 30-Day Outflow Cap         | $50,000 USDC or 5% of treasury value (whichever is lower) — maximum total Treasury / Budget disbursements across all passed proposals in any rolling 30-day window. Signers must refuse execution of any proposal that would cause the rolling total to breach this cap and must report the refusal to RAC immediately. Adjustable by Treasury & Budget proposal. |
| Emergency Safe Address             | Must be designated **before the Company receives the principal asset transfer** (OA Schedule 5, conditions 8–9). During the Transition Period, designation is made by Transition RAC resolution published to the Official Venue, as part of establishing the treasury and custody framework (OA §6.5(d)); thereafter, changes to the designated address require a Treasury & Budget proposal. Until designated, Tier 2 emergency asset movement (Emergency & Safeguards Policy §6) is not available. |

---

### 6.2 Treasury Structure

| Parameter                 | Value       |
| ------------------------- | ----------- |
| Multi-account Requirement | Yes         |
| Multisig Threshold        | See §6A. Post-activation: 3-of-5 standard, 4-of-5 high-risk. Transition Period: 2-of-3 standard; protected/high-risk unanimous among all seated signers, minimum two (3-of-3 at full strength) (3 Transition RAC signers; OA §9.10–9.11) |
| Audit Requirement         | Mandatory — an independent treasury audit is required annually. The RAC is responsible for scoping the audit and bringing an auditor appointment to governance for approval. The first audit process must be initiated within the first 12 months of entity formation. |

---

## 6A. Treasury Signers Parameters

> **Phase scope.** The table below specifies the **post-activation** (permanent) signer set. During the **Transition Period** the signer set is the **3 Transition RAC members** acting as initial signers (Operating Agreement §9.10–9.11): **2-of-3** for standard actions and, for protected / high-risk matters, **unanimity of all seated signers, being not fewer than two** (3-of-3 at full strength), with the continuity floor at fewer than **2** available signers (Treasury Signers Rules §15; Governance Continuity Framework §4.6) and seat replacement under Operating Agreement §6.11. The 5-signer / 3-of-5 / 4-of-5 values below take effect on the **Activation Date**, when Treasury Signing passes to the 5 elected Delegates.

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
| Auto-Renewal                        | Yes — unless challenged | Incumbent role holders are automatically renewed at term end unless a challenge is filed or the role holder declines (see Elections & Role Governance Policy §9) |
| Term Renewal Challenge Window       | 14 days (opens 21 days before expiry, closes 7 days before expiry) | Period during which an eligible Governance Participant may file a unilateral challenge notice to trigger a new election |
| Challenge Filing Threshold          | 0.1% of eligible voting power | Minimum holding required to file a valid challenge notice; verified against the most recent governance snapshot |
| Consecutive Renewal Cap             | 4 terms (2 years maximum continuous service) | After 4 consecutive terms in the same role, a standard election is mandatory; successful re-election resets the count to 1 |
| Election Voting Duration            | 5-7 days  | Length of election voting                |
| Nomination Period                   | 7–10 days (concurrent with Discussion; see §3.1) | Nominations open at the start of the Nomination & Discussion Window and close when the window closes. Governed by the combined window parameter in §3.1. |
| Minimum Participation for Elections | Gov quorum| Quorum requirement                       |
| Removal Vote Threshold              | ≥ 50% YES | Required support to remove a role holder |
| Inactivity Threshold                | 21 days   | Time before inactivity review; declared unavailability periods are excluded. **"Inactivity"** means: no response to governance execution requests, no participation in any multisig signing actions, and no communication with the RAC within the threshold period. Passive activities (reading updates, monitoring forums) do not constitute activity. Declared unavailability periods (per Treasury Signers Rules §15) are excluded from inactivity counting. |
| Replacement Election Trigger Time   | 7 days    | Time before election must start          |
| Replacement Completion Time         | 21 days   | Max time to fill vacancy                 |
| Floor-Protected Resignation Notice  | 14 days   | Advance notice a RAC member (or Treasury Signer) must give where their resignation would reduce seated members below the applicable RAC floor (Permanent RAC: 5; Transition RAC: 3 — §5.1) or active Treasury Signers below the applicable execution quorum (post-activation 3-of-5; Transition Period 2-of-3 — §6A). During the notice period the member remains in office and the replacement process begins; the resignation takes effect on the earlier of a qualified replacement being seated or notice expiry. If the member cannot or will not serve the notice, the seat vacates immediately and the vacancy is escalated as a continuity event (Governance Continuity Framework §4.1/§4.2). A resignation leaving the body at or above the floor takes effect immediately. Operative rule: Elections & Role Governance Policy §11.2. |
| Delegate Count — Minimum            | 5         | Minimum total Delegates; bounded below by the 5 Treasury Signers required under §6A. May not fall below 5 while the Treasury Signing roster requires 5 holders. |
| Delegate Count — Maximum            | 12        | Maximum total Delegates. Adjustable by Governance Process proposal. Set above 7 to allow growth past the founding configuration; reduce to 7 if the DAO prefers a tighter roster. |
| Max Concurrent Roles per Individual | 2         | Limits role concentration. A "role" is an elected or appointed position: a RAC seat, a Delegate seat (regardless of how many Delegated Functions the Delegate holds), a Working Group Steward seat, or a Strategic Coordination WG seat. Delegated Functions held by a single Delegate do not multiply the role count. |
| Conflict Disclosure Requirement     | Mandatory | Required for all roles                   |
| Election Shortlist Multiplier       | 2×        | Stage 1 shortlist slots per open seat (e.g. 3 seats → top 6 advance to Stage 2) |
| Election Stage 1 Max Selections     | Unrestricted | Voters may approve any number of nominees in the Stage 1 Approval Voting proposal |
| Election Stage 2 Quorum             | 7% (Governance Process) | Quorum required for each Stage 2 confirmation vote |
| Election Stage 2 Approval Threshold | ≥ 60% YES (Governance Process) | Approval required for each Stage 2 confirmation vote |
| Election Stage 2 Rerun Quorum       | 5%        | Reduced quorum for the single permitted rerun of a **quorum-held-over** Stage 2 candidate — one who met the Election Stage 2 Approval Threshold in the prior round but missed the Election Stage 2 Quorum (Elections & Role Governance Policy §7.3). Applies only to such candidates; a candidate below the approval threshold is rejected and does not rerun, so a quorum shortfall cannot rescue a rejected candidate. |
| Election Stage 2 Rerun Approval Threshold | ≥ 75% YES | Raised approval threshold for the reduced-quorum rerun, compensating for the lower quorum with a stronger mandate requirement (Elections & Role Governance Policy §7.3) |
| Election Stage 2 Rerun Voting Period | Double the standard DAO Proposal Voting Period (§3.1) | Extended voting window for a Stage 2 rerun, giving thin turnout more time to participate |
| Max Election Stage 2 Reruns         | 1         | A quorum-held-over candidate may be re-run at the reduced rerun quorum at most once; if still short, the seat is filled by fallback advancement or, failing that, the vacancy / founding re-run process (Elections & Role Governance Policy §7.3, §11, §17.1) |
| Reserve List Validity Period        | 90 days   | Period after an election's completion during which a candidate confirmed at Stage 2 but not seated (Elections & Role Governance Policy §7.2.1) may be seated from the reserve list to fill a same-role vacancy without a replacement election (Elections & Role Governance Policy §7.5). Measured from election completion. |

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
| Stewards per WG     | 1–3      |
| Term Length         | 6 months |
| Reporting Frequency | Monthly  |

---

## 8. Identity & Participation Parameters

| Parameter | Value | Description |
| --------- | ----- | ----------- |
| Voting Basis | XRD and LSU (constitutional floor, entrenched per Charter §12.1 item 4) plus RAC-governed supplementary sources as listed in §8A below | — |
| LSU Inclusion | Active — snapshot-based XRD conversion | — |
| Delegation | Disabled — not yet supported by the governance platform | — |
| Sybil Resistance | Not active | — |
| UBO KYC Threshold | >25% of eligible voting power | Triggers mandatory KYC under Marshall Islands DAO Act; annual BOIR filing required Jan 1–Mar 31 |
| Compensation KYC Requirement | Required before first payment | Applies to all compensated contributors, contractors, and grant recipients (Standard and Strategic) |

---

## 8A. Eligible Voting Power Sources

| Tier | Source | How to change |
|---|---|---|
| 1 — Constitutional floor | Liquid XRD | Constitutional Proposal (66% approval, 10% quorum) — cannot be removed |
| 1 — Constitutional floor | LSU → XRD-equivalent at snapshot | Constitutional Proposal (66% approval, 10% quorum) — cannot be removed |
| 2 — RAC-governed | LSULP → XRD-equivalent at snapshot | RAC routine decision + 30-day notice |
| 2 — RAC-governed | Fungible LP pool units (Ociswap, CaviarNine, DefiPlaza) | RAC routine decision + 30-day notice |
| 2 — RAC-governed | Ociswap precision pools (V1 and V2) | RAC routine decision + 30-day notice |
| 2 — RAC-governed | CaviarNine shape pools | RAC routine decision + 30-day notice |

**Rules for RAC changes to Tier 2 sources:**

- Any change must specify an `effectiveFrom` date at least 30 days in the future, ensuring no active proposal is caught between source configurations.
- The RAC must publish the change to the governance forum and notify Governance Participants at least 30 days before `effectiveFrom`.
- The standard 48-hour DAO veto window (§4) applies to all RAC source-list decisions.
- Adding a new source requires a written rationale demonstrating that the source represents genuine XRD-network economic alignment.
- Removing a Tier 2 source follows the same process as adding one.

---

## 9. Execution Parameters

| Parameter                 | Value          |
| ------------------------- | -------------- |
| Pre-Execution Hold        | 48 hours after RAC result publication (mandatory) — Treasury Signers may not initiate execution of any Treasury / Budget or Executable proposal until the veto window (§4) has fully closed |
| High-Risk Execution Delay | 24 hours additional after the pre-execution hold (mandatory) — applies to transactions classified as high-risk (4-of-5 signing threshold post-activation; unanimous-of-seated, minimum two, during the Transition Period, per §6A); total minimum 72 hours after RAC result publication |

---

## 9A. Governance Continuity Parameters

| Parameter | Value | Description |
|---|---|---|
| Governance Inactivity Trigger | 3 consecutive quorum failures on the **same proposal** — the same substantive proposal, resubmitted after each failed attempt | Threshold before reduced quorum activates. The trigger is **per-proposal**, not per-category: three unrelated proposals of the same type failing quorum do **not** place other proposals of that type into reduced-quorum mode. Reduced quorum attaches only to the specific proposal that has failed three times in a row |
| Reduced Quorum Threshold | 50% of the standard quorum for that proposal type (minimum 1%) | Applies after inactivity trigger is met. For Constitutional proposals the reduced quorum may not fall below the entrenched 7% floor (Charter §12.1 item 2); the effective reduced Constitutional quorum is therefore 7% |
| Reduced-Quorum Approval Uplift | +15 percentage points | A proposal confirmed **under the reduced quorum** must reach a YES share at least 15 percentage points above its standard approval threshold (Governance Process 60% → 75%; Executable 50% → 65%), compensating the lower quorum with a stronger mandate. Constitutional proposals are unaffected — they retain their standard ≥66% approval and the entrenched 7% quorum floor. Does not apply to a proposal that meets its ordinary quorum |
| Extended Voting Period | Double the standard voting duration | Applies alongside reduced quorum during inactivity |
| Reconstitution Deadline | 30 days after failure event | Maximum time to re-establish a failed role or body |

**Reduced-quorum notice:** When the reduced quorum activates for a proposal, the RAC must publish a reduced-quorum activation notice to the Official Venue at the opening of the reduced-quorum voting window, stating that the vote proceeds under reduced quorum and the raised approval threshold (Reduced-Quorum Approval Uplift). The extended (doubled) voting period runs from that notice, giving the wider community time to participate before the vote can finalise.

**Treasury / Budget exclusion:** Treasury / Budget proposals are excluded from the Governance Continuity Fallback. A Treasury / Budget proposal that fails to meet quorum must be resubmitted with revised scope or timing; the reduced quorum threshold and extended voting period do not apply.

**Elections exclusion:** Election proposals (Stage 1 shortlisting and Stage 2 confirmation votes) are excluded from the Governance Continuity Fallback. Low-turnout handling for elections is governed by the Stage 2 quorum-held-over rerun in the Elections & Role Governance Policy §7.3 — a reduced rerun quorum paired with a **raised** approval threshold (§6B) — not by the reduced quorum threshold in this section.

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
