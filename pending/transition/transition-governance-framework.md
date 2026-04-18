# Radix DAO Transition Governance Framework

## (Phase 1 Activation & RAC Transitional Authority)

> **Related document:** `Radix-DAO-Phase1.md` contains the original proposal and rationale for this framework. In case of conflict, this document is normative.

---

## 1. Purpose

This document defines the **temporary governance activation model and limited transitional authority** required to move from the pre-registration state (community-deployed Consultation V2 governance without a legal entity) and the Founding Transferor to a fully operational, community-governed DAO with formal legal standing.

This framework exists to:

* Enable secure transfer of assets and responsibilities
* Establish the DAO as a legally and operationally functional system
* Reduce governance complexity during early-stage operations
* Provide controlled coordination during initialization

---

## 2. Scope & Duration

### 2.1 Temporary Nature

All provisions in this document are:

* **Temporary**
* **Strictly limited in scope**
* **Subject to DAO oversight**
* **Automatically expire after the transition period**

---

### 2.2 Transition Model

The DAO operates under a **phased governance activation model**:

#### Phase 1 — Minimum Viable Governance (0–12 months)

* 10 core documents active and enforceable from launch
* RAC and Authorized Signers appointed as founding act
* Asset transfer from the Founding Transferor completed
* Governance decisions possible from launch; Working Groups not operational at launch — established by governance vote after initial RAC and Authorized Signer appointment (activity-triggered within Phase 1; see §3 and §10)
* Voting power includes XRD and LSU (converted to XRD-equivalent at snapshot) from launch
* Complexity added as specific operational needs arise (see §3)

---

#### Phase 2 — Operational Governance (estimated months 6–18)

* Expanded use of full governance framework
* Reduction of RAC delegated responsibilities
* Increased direct DAO control

* Activity-triggered documents activate as operational needs arise (see §3.2)
* Working Groups established by governance vote
* Phase 3 policies brought to governance vote for formal enforcement
* Reduced RAC delegated authority as formal processes replace transitional coordination

Entry into Phase 2 requires a **Governance Process proposal** (≥60% approval, ≥7% quorum) confirming that Phase 1 completion criteria (§10) are substantially met.

**Phase 2 Mandate: Reputation System**

The design and implementation of a community reputation system is a required deliverable of Phase 2. The Governance & Legal Working Group, in collaboration with the Product & Protocol Working Group, is responsible for:

1. **Research & Design (within 3 months of Phase 2 entry)** — Publishing a governance proposal that defines the reputation model, covering at minimum:
   * What actions generate reputation (e.g., on-chain votes cast, proposals authored, peer allocation received, contributor milestones completed)
   * How reputation is weighted and whether it decays over time
   * Whether reputation is transferable or soulbound
   * How reputation interacts with voting power (advisory weighting vs. hard caps)
   * Sybil resistance approach (e.g., Gitcoin Passport integration, proof-of-personhood, or role-based gating)

2. **Community Review (30-day comment period)** — The design proposal must be open for community comment for a minimum of 30 days before a formal governance vote

3. **Implementation (within 9 months of Phase 2 entry)** — A live reputation system, approved by governance vote, must be operational before Phase 3 entry is permitted

The reputation system must not replace token-weighted voting without a Constitutional proposal. Its initial role is advisory — surfacing trusted voices and informing delegation decisions — with expanded governance weight only if explicitly approved by the community.

---

#### Phase 3 — Full DAO Governance (estimated from month 18–24)

* All Phase 3 policies formally approved and enforceable
* All transitional RAC delegation expired
* Full governance framework active
* DAO operates entirely under standard rules

Entry into Phase 3 requires a **Governance Process proposal** confirming that all Phase 2 delegation has been replaced by formal governance processes, all Phase 3 policies have been approved by governance vote, and no transitional authority remains active.

---

## 3. Governance Activation

The governance framework activates in three phases. Complexity is introduced deliberately — only when operationally needed.

---

### 3.1 Phase 1 — Fully Active from Launch (10 documents)

These documents are in force and enforceable from the first day of DAO operations:

| Document | Purpose |
|---|---|
| Charter | Constitutional authority and founding principles |
| DAO Parameters Registry | All numerical thresholds, durations, and limits |
| Proposal & Voting Framework | How decisions are proposed, voted on, and recorded |
| Execution & Treasury Actions Policy | How approved decisions are executed and funds moved |
| Emergency & Safeguards Policy | Response to security events and critical failures |
| Authorized Signers Rules | Operational rules for those executing treasury actions |
| RAC Mandate | Authority and limits of the Accountability Council |
| Conflict of Interest Policy | Disclosure and recusal obligations for all role holders |
| Code of Conduct | Behavioral standards for all DAO participants |
| Legal Wrapper & Representation | Legal entity structure and real-world representation |

---

### 3.2 Phase 2 — Activity-Triggered Documents

These documents activate when the DAO begins the relevant activity. They do not need to be in force from day one — they become required the moment the specific operational need arises. The RAC confirms activation by publishing a notice to the governance forum.

| Document | Activation Trigger |
|---|---|
| Token Delegation Policy | When the governance platform supports delegation |
| Election & Role Governance Policy | Before the first role term expires and elections are needed |
| Governance Continuity Framework | Before the first signer or RAC term ends |
| Governance Maintenance & Upgrade Framework | Before the first governance document amendment is proposed |
| Dispute Resolution & Arbitration Policy | Before the first formal dispute is escalated to the RAC |
| Open Source & IP Policy | Before the first grant or RFP with deliverables is issued |
| Source Code Stewardship Policy | Before the first grant or RFP with code deliverables is issued (activates alongside Open Source & IP Policy) |
| Asset Transfer Agreement Template + IP Schedule | Before any material asset transfer from an Asset Transferor is executed |
| Treasury Risk & Diversification Policy | Before the first treasury diversification action is proposed |
| Working Group Framework | When the first Working Groups are proposed by governance vote |
| Working Group Charters | When each respective Working Group is approved by governance vote |
| Transition Governance Framework | Active from launch — governs the transition period itself |

During Phase 1, the RAC supports the functions covered by these documents where gaps arise, under its delegated authority defined in §5.

**Vote type activation note:** The Proposal & Voting Framework defines four vote types. Standard voting (YES / NO / ABSTAIN) and Approval Voting are active from Phase 1. Weighted Allocation and Majority Judgment are Phase 2 vote types and require tooling support before activation; the RAC confirms activation by publishing a notice to the governance forum when the required tooling is in place.

---

### 3.3 Phase 3 — Policies Requiring Formal Governance Approval

The following policies are published and expected to be followed in spirit from launch. They become **formally enforceable** — including under the dispute resolution and sanctions framework — only after a community governance vote approves each one.

**What "guiding principles" means in practice:** a policy in this status is published, visible, and expected to be followed. However, enforcement via dispute resolution or sanctions requires formal governance approval first. Working Groups and role-holders are encouraged to adopt these policies operationally ahead of formal approval.

| Policy | Target Formal Approval | Notes |
|---|---|---|
| Transparency & Reporting Policy | Phase 2, month 2 | |
| Contributor Compensation Policy | Phase 2, month 3 | |
| Grant Program Policy | Phase 2, month 3 | |
| Security Disclosure & Bug Bounty Policy | Phase 2, month 4 | |
| Ethics Reporting Policy | Phase 2, month 4 | |
| Contributor Onboarding & Offboarding | Phase 2, month 6 | |
| Smart Contract Audit Policy | Before first governance contract deployment | Trigger-based regardless of phase |

The Governance & Legal Working Group is responsible for bringing each policy to a governance vote on schedule and for tracking progress in its regular reporting.

---

## 4. Role of the Accountability Council (RAC)

During Phase 1, the RAC acts as a **transitional coordination and integrity layer**, not a governing authority.

The RAC:

* ensures governance processes function correctly
* supports operational continuity
* facilitates the transition to decentralized governance

The RAC acts **on behalf of the DAO**, and remains accountable to it.

---

## 5. Transitional Delegated Authority

During Phase 1, the RAC is granted **limited delegated authority** strictly for operational continuity.

---

### 5.1 Permitted Actions

The RAC may:

* Facilitate asset transfer and custody setup
* Support operational bootstrapping (infrastructure, tooling, services)
* Resolve minor governance ambiguities
* Coordinate urgent operational decisions where a delay of more than 48 hours would cause material harm to the DAO, subject to documented justification and retrospective disclosure. **"Material harm"** means: loss of or credible risk to treasury assets; inability to execute a DAO-approved proposal within its required timeframe; or failure of critical operational infrastructure with no other recovery path available within the governance timeline
* Assist in establishing initial working groups

---

### 5.2 Emergency Authority (Transitional Scope)

During Phase 1, the RAC may exercise emergency powers as defined in the Emergency Policy, including:

* rapid response to security threats
* temporary suspension of unsafe operations
* protection of treasury assets

All such actions must:

* be minimal and necessary
* be documented
* be disclosed
* be subject to retrospective DAO review

---

### 5.3 RAC Decision Quorum (Transitional Actions)

All non-emergency transitional actions under §5.1 require a simple majority of RAC members (more than half of seated members). Decisions must be recorded and disclosed in accordance with §8.

---

### 5.4 Interim Execution Authority (Phase 1 Only)

During Phase 1, where no relevant Working Group exists to coordinate execution, the RAC may act as an interim execution body for operational needs within DAO-approved budgets. This authority is strictly transitional and expires when a relevant Working Group becomes operational.

**Scope**

The RAC may, in the absence of a relevant Working Group:

* Publish and administer RFPs for operational work within a DAO-approved budget
* Select contributors and confirm engagements
* Manage delivery and authorise milestone payments to Authorized Signers

**Conditions**

All interim execution actions must comply with the following:

* A DAO-approved Treasury & Budget proposal must exist covering the work — the RAC may not initiate spending without prior governance approval
* The Open Source & IP Policy must be activated before any RFP with deliverables is issued (per §3.2)
* RFP mechanics follow the Contributor Compensation Policy in spirit: minimum 14-day open period, published evaluation criteria, documented selection rationale
* Selection decisions must be published on the governance forum for a 7-day community acknowledgement period before engagement is confirmed, during which any token holder may file a veto challenge (Proposal & Voting Framework §8) on the grounds of non-compliance with the approved proposal
* All engagements, payments, and decisions are reported to the governance forum within 72 hours (per §8)

**Limitations**

* The RAC may not use this authority to create ongoing structural commitments beyond the current Phase 1 budget period
* This authority lapses for a given workstream the moment a Working Group with a relevant mandate is established by governance vote
* The RAC must include a summary of all interim execution actions in its quarterly delegation status report (§9)

---

## 6. Explicit Limitations

Even during Phase 1, the RAC:

* **may not override DAO-approved proposals**
* **may not define or impose strategy independently**
* **may not allocate treasury funds outside approved mandates**
* **may not create or modify governance structures without DAO approval**

All authority remains ultimately with the DAO.

---

### 6.1 Conflict of Interest

RAC members with a personal, financial, or organizational conflict of interest in a transitional decision must:

* disclose the conflict prior to the decision
* recuse themselves from the relevant vote

Conflict of interest rules are defined in full in the **RAC Mandate**.

---

### 6.2 Community Challenge Mechanism

Any RAC transitional action under §5.1 may be challenged by the community by filing a **Governance Process proposal** within **14 days** of the action being disclosed.

If the proposal passes, the DAO's decision supersedes the RAC action. The RAC must comply with the outcome.

---

## 7. Relationship to Execution

Execution during Phase 1 follows standard governance structure:

* Working Groups coordinate execution
* Authorized Signers execute treasury and legal actions
* RAC verifies compliance and supports continuity

The RAC does not directly control treasury execution.

---

## 8. Transparency Requirements

During the transition:

* All RAC actions must be publicly reported to the DAO governance forum within **72 hours** of the action being taken
* Each report must include: action taken, justification, members who voted, and outcome
* Asset transfers must be transparently documented with transaction references
* Delegated actions must include justification
* Exceptions and emergency actions must be disclosed with retrospective review scheduled within 7 days

---

## 9. Progressive Reduction of Delegation

RAC delegated authority must:

* **decrease over time**
* be replaced by formal governance processes
* be reviewed **quarterly** — the RAC publishes a delegation status report, and the community has a 14-day period to raise concerns via governance proposal

Each phase transition must include:

* explicit reduction of RAC responsibilities
* increased reliance on DAO voting

---

## 10. Completion Criteria

Phase 1 is considered complete when all of the following minimum conditions are met:

**Asset Transfer**

* Asset transfer from the Founding Transferor is complete, verified, and publicly disclosed. For a transfer to be considered verified, all of the following instruments must be in place: a signed Asset Transfer Agreement (using the Asset Transfer Agreement Template), a completed IP Schedule (Exhibit A to the Agreement) enumerating all transferred assets with identifiers, an executed Continuity Statement per Operating Agreement §3.2, and a published Acceptance Statement recorded on the governance forum

**Governance Track Record**

* At least 3 full governance proposal cycles (draft → vote → execution) have completed without RAC intervention
* No active emergency action or unresolved veto challenge exists at the time of the Phase 2 proposal

**Working Groups**

* All 5 Phase 1 Working Groups have operated independently for at least 60 consecutive days, producing required monthly reports

**Phase 2 Document Activation**

* All activity-triggered Phase 2 documents relevant to the DAO's current operations have been activated
* The following Phase 3 policies have been formally activated by governance vote:
  * Transparency & Reporting Policy
  * Contributor Compensation Policy
  * Grant Program Policy

**Participation**

* At least 2 Treasury or Governance Process proposals have met quorum without the reduced-quorum fallback (Governance Continuity §4.3)

**Reporting**

* At least one full quarterly financial transparency report has been published per the Transparency & Reporting Policy

---

Entry into Phase 2 is confirmed when a **Governance Process proposal** (≥60% approval, ≥7% quorum) affirms that the above conditions are met. The proposal must include a checklist attestation prepared by the RAC and reviewed by the Governance & Legal Working Group.

---

## 11. Expiry

After Phase 1 (12 months):

* All transitional delegated authority expires
* Any extension must be explicitly approved by a **Governance Process proposal** (≥60% approval, ≥7% quorum) submitted no later than 30 days before expiry

---

### 11.1 Core Document Continuity

Expiry of transitional delegated authority under §11 does **not** affect the active status of the 10 Phase 1 documents listed in §3.1. Those documents were activated at launch and remain in force until explicitly superseded or amended by a governance vote. Authority expiry and document activation are independent.

### 11.2 Role Holder Tenure Continuity

Expiry of transitional delegated authority does **not** affect the tenure or term renewal rights of constituted role holders (RAC members and Authorized Signers carried forward from the predecessor organization). Their role tenure runs on a separate track from their transitional authority:

* Transitional authority expires on the Phase 1 schedule defined in §11
* Role tenure continues subject to the term lengths and renewal rules defined in the Elections & Role Governance Policy §9
* A role holder whose second term is active at Phase 1 expiry continues in role without interruption — they simply no longer hold transitional delegated powers

This separation ensures that Phase 1 expiry does not inadvertently create vacancies or force simultaneous elections across all founding roles.

---

### 11.3 Failed Transition Procedure

If Phase 1 completion criteria (§10) have not been certified by a governance vote before the 12-month expiry, the DAO enters a **Governance Remediation Period**:

* The 10 core documents remain fully active (per §11.1)
* The RAC retains only its permanent core mandate as defined in the RAC Mandate — all transitional delegated authority under §5 lapses on schedule without extension
* Within **30 days of expiry**, the RAC must publish a Remediation Report to the governance forum identifying which §10 criteria remain unmet and a proposed resolution timeline
* The community must vote within **60 days of expiry** on one of the following:

  * **Option A — Authority Extension:** A time-limited extension of RAC transitional authority (≥60% approval, ≥7% quorum), with a specific remediation plan and hard deadline attached. Maximum extension: 6 months, non-renewable without a new governance vote.
  * **Option B — Conditional Phase 2 Entry:** A declaration of Phase 2 entry (≥60% approval, ≥7% quorum) with unmet §10 criteria formally recorded as governance obligations, to be resolved within the first 90 days of Phase 2.

* If neither option passes within 60 days of expiry, the DAO continues to operate under the 10 core documents without transitional authority. Standard governance rules apply. Any token holder may raise a new proposal to resolve the governance state.

---

## 12. Relationship to the Charter

This document:

* Does **not modify the Charter**
* Exists solely to enable transition

In case of conflict:

* The Charter prevails for all permanent governance
* This framework applies only during Phase 1

---

## 13. Guiding Principle

> This framework exists to **enable the safe activation of decentralization**,
> not to concentrate or delay it.
