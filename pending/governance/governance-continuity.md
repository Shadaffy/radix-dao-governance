# Governance Continuity Framework

---

## 1. Purpose

This document defines how the DAO maintains or restores governance when:

* governance bodies fail
* execution becomes blocked
* normal processes cannot function

---

## 2. Guiding Principle

> Governance must remain recoverable under all circumstances.

---

## 3. Scope

Applies to failures involving:

* Accountability Council (RAC)
* Authorized Signers
* Working Groups
* Governance participation (quorum failure)

---

## 4. Failure Scenarios

---

### 4.1 RAC Failure

Trigger:

* full resignation, inactivity, or inability to function

Response — Tier 1 (surviving RAC members):

If the RAC cannot meet quorum due to deaths or incapacitations, any single surviving RAC member may take the following specific activation actions:

* Declare a RAC continuity event on the governance forum
* Declare a signer continuity event if applicable (see §4.2)
* Appoint interim signers from the Emergency Signer Reserve (Authorized Signers Rules §15)

Tier 1 scope is strictly limited to these triggering and appointment actions. Appointment of an interim Legal Signatory is explicitly excluded — that function is covered by Operating Agreement §5.5 (Compliance Liaison steps in automatically). All Tier 1 actions must be publicly disclosed on the governance forum immediately. Interim signer appointments take effect 24 hours after disclosure to allow a community challenge, except where treasury assets are at immediate risk. All Tier 1 actions are subject to GP ratification within 30 days.

Response — Tier 2 (no RAC members available):

If no RAC members are available, the Governance & Legal Working Group Stewards (internal majority vote) may:

* Declare a RAC continuity event on the governance forum
* Appoint interim signers from the Emergency Signer Reserve
* Initiate the emergency election process

Tier 2 authority is explicitly granted in the Governance & Legal WG Charter §13. WG Stewards may not appoint themselves as interim signers or RAC members. All Tier 2 actions require immediate public disclosure and a 24-hour challenge window before taking effect. Subject to GP ratification within 30 days.

Response — Tier 3 (token holders):

If neither Tier 1 nor Tier 2 can be activated, authority reverts to token holders per Charter §9. Emergency election may be initiated by any token holder via the standard governance forum process.

In all cases:

* Emergency election for permanent RAC replacement must begin within 7 days of the continuity event
* Election must complete within 21 days of the continuity event
* Reconstitution Spend Limit (DAO Parameters §6.1) is available upon declaration of a RAC continuity event

---

### 4.2 Signer Failure

Trigger:

* active Authorized Signers fall below execution quorum (fewer than 3 of 5 available)
* key compromise confirmed by any signer or RAC
* refusal to execute a valid approved action without documented grounds (per Authorized Signers Rules §9)

Response:

**Immediate (within 24 hours):**

* RAC declares a signer continuity event and notifies the governance forum. If the RAC cannot meet quorum, the Tier 1 or Tier 2 fallback authority defined in §4.1 satisfies this declaration requirement.
* All non-urgent treasury execution is suspended until quorum is restored
* Emergency actions under the Emergency & Safeguards Policy remain available if required thresholds can be met with available signers

**Forced-execution backstop:** If a passed proposal has not been executed within 10 business days from the close of the veto window (DAO Parameters §4), and no valid refusal is currently on record with RAC (i.e., RAC has not acknowledged a legitimate hold under Authorized Signers Rules §9), RAC may instruct the remaining available signers to proceed with execution using the minimum 3-of-5 threshold, bypassing the unresponsive or non-compliant signer. This instruction must be published publicly on the governance forum within 24 hours of being issued and is treated as a signer continuity event for reporting purposes. The 10-business-day clock runs from veto window close, not from proposal passage.

**Interim signer appointment (if active signers < 3):**

* RAC may appoint up to 2 interim signers from the pre-approved Emergency Signer Reserve (maintained by the Governance & Legal Working Group; approved by DAO vote at each annual term cycle)
* Interim signers are subject to the full Authorized Signers Rules
* The signing threshold for interim-period actions is raised to **4-of-5** (regardless of whether interim or permanent signers hold the seats)
* Interim appointment must be disclosed to the governance forum within **24 hours** of appointment
* Interim appointment is valid for a maximum of **30 days** or until a formal replacement election is complete, whichever comes first

**Formal replacement:**

* Emergency election for permanent replacement(s) must begin within **7 days** of the continuity event
* Election must complete within **21 days** of the continuity event
* Upon election of permanent replacements, interim appointments are immediately void

**Key compromise:**

* Compromised keys must be rotated and the affected signer suspended pending review
* If compromise affects treasury access, RAC invokes Emergency & Safeguards Policy to secure assets

---

### 4.3 Governance Inactivity

Trigger:

* 3 consecutive quorum failures on the same proposal type (as defined in DAO Parameters §9A)

Response:

* extended voting periods (double standard duration)
* reduced quorum threshold (50% of standard quorum, minimum 1%)
* activation of fallback governance proposal if reduced quorum is still not met after two additional attempts

Thresholds are defined in the **DAO Parameters Registry §9A**.

---

### 4.4 Working Group Failure

Trigger:

* inactivity or inability to execute

Response:

* re-election or restructuring via DAO vote

---

### 4.5 Governance Interface Unavailability

Trigger:

* The primary governance voting interface is inaccessible or non-functional for more than **48 continuous hours**

Response:

**Active votes in progress:**

* All active voting periods are automatically extended by the duration of the outage plus a **48-hour buffer** upon restoration
* RAC must announce the extension via the governance forum within 12 hours of confirming the outage

**New proposals:**

* No new proposals may enter the voting phase until the primary interface is restored or an alternative interface is confirmed
* Draft and review periods may continue

**If outage exceeds 7 days:**

* RAC may invoke the Emergency & Safeguards Policy if time-sensitive matters (e.g., expiring treasury actions, security incidents) cannot wait for restoration
* RAC must propose and confirm an alternative voting mechanism via public announcement to the governance forum; the alternative must be:
  * Publicly auditable
  * Token-holder accessible
  * Recorded on-chain or in a tamper-evident off-chain record

**Restoration:**

* Upon restoration of the primary interface, RAC must publish a brief incident report (cause, duration, actions taken) within 48 hours
* Any alternative voting results must be migrated or acknowledged in the primary interface record

---

## 5. Emergency Recovery Actions

In critical failure scenarios:

* Emergency Policy may be invoked
* RAC may take temporary stabilizing actions within its defined limits
* DAO retains final authority

---

## 6. Reconstitution

After failure:

* roles must be re-established via governance within **30 days** of the failure event
* authority must return to standard processes
* temporary measures must be removed once reconstitution is complete

---

## 7. Minimum Operational State

The DAO is considered operational if:

* proposals can be submitted and voted
* signers can execute approved actions
* governance processes are functional

---

## 8. Transparency

All continuity actions must be:

* documented
* publicly reported
* subject to DAO review

---

## 9. Relationship to Other Documents

This framework operates alongside:

* Emergency & Safeguards Policy
* Elections & Role Governance Policy
* Execution & Treasury Policy

---

## 10. Guiding Principle

> If governance fails, recovery must be **clear, fast, and decentralized**.
