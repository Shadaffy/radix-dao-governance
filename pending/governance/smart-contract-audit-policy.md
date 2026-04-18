# Smart Contract Audit Policy

---

## 1. Purpose

This policy establishes mandatory audit and security review requirements before the DAO deploys or governs changes to smart contracts and on-chain systems.

The DAO governs protocol-level decisions and controls treasury infrastructure on the Radix network. Unaudited code changes to these systems represent a direct risk to community funds and governance integrity.

This policy defines:

* Which deployments and changes require an audit
* Audit tiers and what each requires
* Who is responsible for commissioning and reviewing audits
* Minimum standards for audit firms and reports
* What happens when audit findings are unresolved
* The relationship between audits and governance approval

---

## 2. Scope

### 2.1 In Scope

The following require a security audit before deployment or governance approval:

* New smart contracts deployed to mainnet that are controlled by or interact with DAO treasury
* Upgrades to existing DAO governance contracts (voting, proposal submission, multisig components)
* New treasury management components or custody infrastructure
* Smart contracts funded by the DAO that will hold user funds or exercise protocol-level authority
* Changes to access control systems governing DAO-controlled accounts

---

### 2.2 Out of Scope

The following are not subject to mandatory audit under this policy:

* Off-chain tooling, dashboards, and front-end interfaces (though security review is recommended)
* Documentation and governance process changes
* Smart contracts funded by grants where the DAO has no operational control (grant recipients are responsible for their own security)
* Testnet deployments (though pre-mainnet testing is expected)

---

## 3. Audit Tiers

Audit requirements are tiered by risk level. The Product & Protocol WG, in consultation with the RAC, determines the appropriate tier for each deployment.

### Tier 1 — Full Independent Audit

**Required for:**
* New governance contracts
* New treasury custody components
* Any contract that can move, lock, or burn DAO treasury funds above the Tier 1 threshold defined in DAO Parameters
* Major upgrades that materially change the logic of existing Tier 1 contracts

**Requirements:**
* Conducted by a qualified independent audit firm (see Section 5)
* Full manual code review plus automated tooling
* Published audit report with all findings, severities, and resolutions
* All Critical and High findings resolved before deployment
* Medium findings either resolved or accompanied by a documented mitigation rationale accepted by the Product & Protocol WG
* Audit report included in the governance proposal for community review

---

### Tier 2 — Targeted Security Review

**Required for:**
* Minor upgrades to existing audited contracts where the change scope is limited and well-defined
* New contracts below the Tier 1 threshold that interact with but do not control DAO treasury
* Time-sensitive fixes to known issues where a full Tier 1 audit is not practical within the required response window

**Requirements:**
* Conducted by a qualified independent auditor or audit firm (see Section 5)
* Focused review scoped to the changed or new components
* Written review report with findings and resolutions
* All Critical findings resolved before deployment; High findings resolved or mitigated with documented rationale
* Review report included in the governance proposal

---

### Tier 3 — Internal Security Review

**Required for:**
* Low-risk parameter changes to existing audited contracts
* Configuration changes that do not alter contract logic

**Requirements:**
* Conducted by the Product & Protocol WG with at least one reviewer who did not write the change
* Written internal review checklist completed and published
* No Critical or High findings open at deployment
* RAC may escalate any Tier 3 assessment to Tier 2 or Tier 1 if warranted

---

## 4. Audit Process

### 4.1 Engagement Timing

Audits must be commissioned before a governance proposal for the relevant deployment is submitted for vote. The audit report must be available to the community during the proposal review period.

Emergency deployments are an exception — see Section 7.

---

### 4.2 Audit Brief

The Product & Protocol WG must prepare an audit brief for every engagement containing:

* The contract(s) and commit hash(es) to be audited
* A description of the system's purpose and trust assumptions
* Known areas of complexity or risk to focus on
* Any prior audit reports for related systems
* The deployment context (mainnet, treasury interaction, governance authority)

---

### 4.3 Code Freeze

The code submitted for audit must be frozen at a specific commit. Any changes made after the audit begins — other than fixes to findings — invalidate the audit and require a new engagement or a delta review scoped to the changes.

---

### 4.4 Finding Resolution

For each finding in the audit report, the Product & Protocol WG must document one of:

* **Fixed** — change made, verified by auditor where possible
* **Mitigated** — risk reduced by design or operational controls; rationale documented
* **Accepted** — risk acknowledged and accepted with documented justification; only permitted for Low and Informational findings
* **Disputed** — the WG disagrees with the finding; disagreement documented with technical rationale; RAC notified

Critical and High findings must be Fixed or, in exceptional cases for High findings, Mitigated with auditor acknowledgement. They may not be Accepted.

---

### 4.5 Auditor Verification

Where possible, fixes to Critical and High findings should be re-reviewed by the original auditor before deployment. For Tier 2 reviews, written auditor acknowledgement of the fix is acceptable in lieu of a full re-review.

---

## 5. Auditor Standards

### 5.1 Independence

Audit firms and auditors must be:

* Financially and organizationally independent from the DAO and from the team that wrote the code
* Free of conflicts of interest with the DAO (disclosed per **Conflict of Interest Policy**)

RAC members and WG Stewards may not audit code they have contributed to.

---

### 5.2 Qualification

Audit firms engaged for Tier 1 audits must:

* Have demonstrated experience auditing Scrypto / Radix Engine smart contracts, or — if Radix-specific expertise is unavailable — deep expertise in the closest comparable environments with a documented rationale for the selection
* Be able to provide references or a public portfolio of prior audit work
* Not be subject to known professional sanctions or reputational concerns

A list of pre-approved audit firms, maintained by the Product & Protocol WG and reviewed annually, is published in the DAO's public documentation repository. Engagements outside this list require RAC sign-off.

---

### 5.3 Report Standards

A valid audit report must include:

* Scope definition (files, commit hash, systems reviewed)
* Methodology description
* All findings with: severity classification, description, location, recommendation
* Summary of resolution status for each finding
* Overall risk assessment
* Auditor name(s) and firm

---

## 6. Governance Integration

### 6.1 Audit Report as Proposal Requirement

Any governance proposal to deploy or upgrade an in-scope contract must include:

* A link to the full published audit report
* A summary of findings and their resolution status
* Confirmation that no Critical or High findings remain unresolved

The RAC must verify these requirements are met before a proposal advances to the voting stage. A proposal that fails to include a required audit report is invalid per **Proposal & Voting Framework §10**.

---

### 6.2 Community Review Period

The audit report must be available for the full community review period before voting begins (minimum per DAO Parameters §3.1). The community may raise questions about findings or resolutions during this period.

---

### 6.3 Post-Deployment Monitoring

The Product & Protocol WG is responsible for monitoring deployed contracts for anomalous behaviour after deployment. Any issues observed post-deployment should be assessed under the **Security Disclosure and Bug Bounty Policy** or escalated to the RAC if immediate risk is identified.

---

## 7. Emergency Deployments

Where the **Emergency & Safeguards Policy** authorises an emergency deployment to address an active exploit or critical vulnerability:

* The normal pre-deployment audit requirement is suspended for the duration of the emergency
* The emergency fix must be reviewed using an expedited Tier 2 process as soon as practicable — target within **7 days** of deployment
* A full Tier 1 audit of the emergency change must be completed within **60 days** of deployment
* The post-emergency governance ratification vote must include the expedited review findings

Emergency deployments that cannot be retroactively audited within 60 days must be disclosed to the community with a documented plan and timeline.

---

## 8. Audit Budget

The DAO must maintain a designated audit budget approved by governance. The Product & Protocol WG is responsible for managing this budget and ensuring sufficient funds are available ahead of planned deployments.

Where an urgent audit requirement exceeds the available budget, the Product & Protocol WG may bring an emergency Treasury proposal.

Audit costs are not grounds for skipping a required audit.

---

## 9. Responsibility Summary

| Responsibility | Owner |
|---|---|
| Determining audit tier | Product & Protocol WG + RAC |
| Commissioning audits | Product & Protocol WG |
| Preparing audit brief and code freeze | Product & Protocol WG |
| Resolving and documenting findings | Product & Protocol WG |
| Verifying proposal audit requirements | RAC |
| Maintaining approved auditor list | Product & Protocol WG (annual review) |
| Managing audit budget | Product & Protocol WG |
| Post-deployment monitoring | Product & Protocol WG |
| Emergency audit oversight | RAC |

---

## 10. Relationship to Other Policies

* **Emergency & Safeguards Policy** — governs emergency deployments; suspends normal audit requirements during active incidents
* **Security Disclosure and Bug Bounty Policy** — post-deployment vulnerability discovery and responsible disclosure
* **Proposal & Voting Framework §10** — audit report as a proposal validity requirement
* **Execution & Treasury Actions Policy** — execution of deployment actions following governance approval
* **Contributor Compensation Policy / Grant Program Policy** — audit costs are a legitimate DAO expense

---

## 11. Amendments

This policy may be updated via a Governance Process proposal.

Amendment procedures and classification requirements are defined in the **Governance Maintenance & Upgrade Framework**.
