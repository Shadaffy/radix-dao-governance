# Governance Continuity Framework

---

## 1. Purpose

This framework defines how the DAO maintains or restores governance capability when governance bodies fail, when execution becomes blocked, or when normal processes cannot function. The continuity mechanisms here are designed to be activated only when standard governance procedures are insufficient, and to surrender authority back to standard processes as soon as recovery is complete.

---

## 2. Guiding Principle

> Governance must remain recoverable under all circumstances.

---

## 3. Scope

This framework applies to failures affecting:

* The Accountability Council (RAC)
* Treasury Signers
* Working Groups
* Governance participation (sustained quorum failure)
* The governance interface itself (interface unavailability)

It governs the procedures by which interim authority may be exercised during such failures and the conditions under which standard governance authority is restored.

---

## 4. Failure Scenarios

---

### 4.1 RAC Failure

Trigger:

* full resignation, inactivity, or inability to function

**Response — Tier 1 (surviving RAC members):**

If the RAC cannot meet quorum due to deaths or incapacitations, any single surviving RAC member may take the following specific activation actions:

* Declare a RAC continuity event on the governance forum
* Declare a signer continuity event if applicable (see §4.2)
* Appoint interim signers from the Emergency Signer Reserve (Treasury Signers Rules §15)

Tier 1 scope is strictly limited to these triggering and appointment actions. Appointment of an interim Legal Signatory is explicitly excluded — that function is covered by Delegate Mandate §5 (the Compliance Liaison is authorised to act as interim Legal Signatory for protective or time-critical purposes). All Tier 1 actions must be publicly disclosed on the governance forum immediately. Interim signer appointments take effect 24 hours after disclosure to allow a community challenge, except where treasury assets are at immediate risk. All Tier 1 actions are subject to GP ratification within 30 days.

**Response — Tier 2 (no RAC members available):**

If no RAC members are available, the Governance & Legal Working Group Stewards (internal majority vote) may:

* Declare a RAC continuity event on the governance forum
* Appoint interim signers from the Emergency Signer Reserve
* Initiate the emergency election process

Tier 2 authority is granted by this policy and is to be incorporated into the Governance & Legal Working Group Charter when that charter is adopted. Working Group Stewards may not appoint themselves as interim signers or RAC members. All Tier 2 actions require immediate public disclosure and a 24-hour challenge window before taking effect. All Tier 2 actions are subject to GP ratification within 30 days.

**Response — Tier 3 (Governance Participants):**

If neither Tier 1 nor Tier 2 can be activated, authority reverts to Governance Participants per Charter §9. An emergency election may be initiated by any Governance Participant via the standard governance forum process.

In all cases:

* Emergency election for permanent RAC replacement must begin within 7 days of the continuity event (DAO Parameters §6B)
* Election must complete within 21 days of the continuity event (DAO Parameters §6B)
* The Governance Reconstitution Limit (DAO Parameters §6) is available upon declaration of a RAC continuity event

---

### 4.2 Signer Failure

Trigger:

* active Treasury Signers fall below execution quorum (fewer than 3 of 5 available)
* key compromise confirmed by any signer or the RAC
* refusal to execute a valid approved action without documented grounds (per Treasury Signers Rules §9)

Response:

**Immediate (within 24 hours):**

* RAC declares a signer continuity event and notifies the governance forum. If the RAC cannot meet quorum, the Tier 1 or Tier 2 fallback authority defined in §4.1 satisfies this declaration requirement.
* All non-urgent treasury execution is suspended until quorum is restored
* Emergency actions under the Emergency & Safeguards Policy remain available if required thresholds can be met with available signers

**Forced-execution backstop:** If a passed proposal has not been executed within 10 business days from the close of the veto window (DAO Parameters §4), and no valid refusal is currently on record with the RAC (i.e., the RAC has not acknowledged a legitimate hold under Treasury Signers Rules §9), the RAC may instruct the remaining available signers to proceed with execution using the minimum 3-of-5 threshold, bypassing the unresponsive or non-compliant signer. This instruction must be published publicly on the governance forum within 24 hours of being issued and is treated as a signer continuity event for reporting purposes. The 10-business-day clock runs from veto window close, not from proposal passage.

**Interim signer appointment (if active signers < 3):**

* The RAC may appoint up to 2 interim signers from the pre-approved Emergency Signer Reserve (maintained by the Governance & Legal Working Group; approved by DAO vote at each annual term cycle — Treasury Signers Rules §15)
* Interim signers are subject to the full Treasury Signers Rules
* The signing threshold for interim-period actions is raised to **4-of-5** (regardless of whether interim or permanent signers hold the seats)
* Interim appointment must be disclosed to the governance forum within **24 hours** of appointment
* Interim appointment is valid for a maximum of **30 days** or until a formal replacement election is complete, whichever comes first

**Formal replacement:**

* Emergency election for permanent replacement(s) must begin within **7 days** of the continuity event (DAO Parameters §6B)
* Election must complete within **21 days** of the continuity event (DAO Parameters §6B)
* Upon election of permanent replacements, interim appointments are immediately void

**Key compromise:**

* Compromised keys must be rotated and the affected signer suspended pending review
* If compromise affects treasury access, the RAC invokes the Emergency & Safeguards Policy to secure assets

---

### 4.3 Governance Inactivity

Trigger:

* 3 consecutive quorum failures on the same proposal type (as defined in DAO Parameters §9A)

Response:

* extended voting periods (double standard duration)
* reduced quorum threshold (50% of standard quorum, minimum 1%)
* activation of fallback governance proposal if reduced quorum is still not met after two additional attempts

The fallback preserves the DAO's decision-making capability during periods of low engagement without abandoning the quorum principle entirely. Thresholds are defined in the **DAO Parameters Registry §9A**.

---

### 4.4 Working Group Failure

A Working Group is treated as failed when it has become inactive or has demonstrated an inability to execute against its mandate — for example, by missing two consecutive reporting cycles, exhausting its budget without delivery, or becoming non-responsive to RAC inquiries. On a finding of Working Group failure, the RAC may initiate a Governance Proposal to restructure the body, replace its Stewards by emergency election, or dissolve it under the Working Group Framework §4. Active contributor engagements and unspent budget funds are handled per the Working Group Framework and the Contributor Onboarding and Offboarding Policy §7.

---

### 4.5 Governance Interface Unavailability

Trigger:

* The primary governance voting interface is inaccessible or non-functional for more than **48 continuous hours**

Response:

**Active votes in progress:**

* All active voting periods are automatically extended by the duration of the outage plus a **48-hour buffer** upon restoration
* The RAC must announce the extension via the governance forum within 12 hours of confirming the outage

**New proposals:**

* No new proposals may enter the voting phase until the primary interface is restored or an alternative interface is confirmed
* Draft and review periods may continue

**If outage exceeds 7 days:**

* The RAC may invoke the Emergency & Safeguards Policy if time-sensitive matters (e.g., expiring treasury actions, security incidents) cannot wait for restoration
* The RAC must propose and confirm an alternative voting mechanism via public announcement to the governance forum; the alternative must be:
  * Publicly auditable
  * Accessible to all Governance Participants
  * Recorded on-chain or in a tamper-evident off-chain record

**Restoration:**

* Upon restoration of the primary interface, the RAC must publish a brief incident report (cause, duration, actions taken) within 48 hours
* Any alternative voting results must be migrated or acknowledged in the primary interface record

---

### 4.6 Transition RAC Vacancy (Pre-Activation)

The RAC-failure response in §4.1 presumes a **seated body that reconstitutes through an emergency election under the Elections & Role Governance Policy**. The **Transition RAC** is different: its five seats are recited in GP-PRE-1 and fixed in the Operating Agreement (OA §6.3, Schedule 1), and are **not** elected under the Elections Policy. The §4.1 reconstitution route therefore does not directly apply to a Transition RAC seat that vacates before the Activation Date (death, incapacity, or resignation under the Floor-Protected Resignation rule, Elections Policy §11.2).

**Operational response (within existing Operating Agreement authority):**

* The surviving Transition RAC members continue to act. Ordinary formation decisions remain valid under the **simple-majority-of-seated** decision rule in **Operating Agreement §6.6**, which already operates on seated members and is unaffected by a seat falling vacant.
* Any surviving member must **declare a continuity event** on the Official Venue, and the body must treat restoration of full strength as a priority transition task under its mandate (OA §6.5(g)); a sub-strength state may not be treated as permanent or as a basis to defer the Activation Date (OA §8.3).
* Where the vacancy also reduces active Treasury Signers below the 3-of-5 execution quorum, the **signer-failure** response in §4.2 applies in addition.

**Limits — matters reserved to the Operating Agreement:**

* **Seat replacement.** Admitting a new member to the Transition RAC (a change to the persons fixed in OA §6.3 / Schedule 1) is a formation matter reserved to the Operating Agreement. This framework cannot itself add or substitute a Transition RAC member. Until the Operating Agreement provides a Transition RAC replacement mechanism, the surviving members continue under OA §6.6, and the gap is recorded for counsel in the OA review notes.
* **Critical-floor interaction.** The Entrenched-Provision amendment threshold and the Schedule 5 condition-waiver both require the affirmative vote of **all five seated Transition RAC members** (Operating Agreement §12.2(c); DAO Parameters §3A.4). If the Transition RAC falls below five, that threshold cannot be met — which can in turn disable the only formal path to activate where the Permanent RAC election cannot seat the minimum (Elections Policy §17.1–§17.3). This interaction is escalated to the community under Charter §9 and flagged for the Operating-Agreement fix; it cannot be resolved at the policy layer alone.

---

## 5. Emergency Recovery Actions

In critical failure scenarios, the Emergency & Safeguards Policy may be invoked alongside this framework. The RAC may take temporary stabilizing actions within its defined limits — for example, suspending non-essential treasury execution or pausing a malfunctioning Working Group — while continuity procedures complete. The DAO retains final authority over all such actions, which remain subject to GP ratification within 30 days unless the Emergency & Safeguards Policy specifies otherwise.

---

## 6. Reconstitution

After any continuity event, the affected roles must be re-established through standard governance within the Reconstitution Deadline defined in DAO Parameters §9A (currently 30 days). Authority must return to standard processes as soon as the relevant election or replacement completes. All temporary measures — interim signer appointments, elevated signing thresholds, fallback voting mechanisms — must be unwound once reconstitution is complete.

---

## 7. Minimum Operational State

The DAO is considered operational when proposals can be submitted and voted on through the governance interface, signers can execute approved actions, and governance processes (including the RAC's oversight function) are functional. A state in which any of these capabilities is missing is a continuity event triggering the response procedures in §4.

---

## 8. Transparency

All continuity actions must be documented at the time they are taken, publicly reported to the governance forum within the disclosure windows specified in §4, and made subject to DAO review through GP ratification or, where applicable, a retrospective Governance Proposal.

---

## 9. Relationship to Other Documents

This framework operates alongside:

* **Emergency & Safeguards Policy** — emergency response authority and protocol
* **Elections & Role Governance Policy** — emergency elections, vacancy handling, and interim-appointment renewal rules
* **Execution & Treasury Actions Policy** — execution mechanics and forced-execution backstop
* **Treasury Signers Rules §9, §15** — valid refusal grounds and the Emergency Signer Reserve
* **RAC Mandate** — RAC authority limits, including in continuity events
* **Delegate Mandate §5** — Legal Signatory continuity (Compliance Liaison interim authority)
* **Working Group Framework §4** — Working Group dissolution
* **DAO Parameters Registry §6, §6B, §9A** — Governance Reconstitution Limit, replacement timing, and continuity fallback parameters

---

## 10. Amendments

_Amendment procedures and classification requirements are defined in the **Governance Maintenance & Upgrade Framework**._

---

## 11. Guiding Principle

> If governance fails, recovery must be clear, fast, and decentralized.
