# Radix DAO LLC — Governance Framework (Pending Adoption)

This folder contains the complete governance framework of **Radix DAO LLC** and the proposals that
bring it into force. Under the **Operating Agreement** (the master legal instrument), the framework is
adopted and activated through a **sequence** of community acts — not a single founding vote.

The Company is **member-managed** at formation, and community governance is **advisory** until the
**Activation Vote** passes. Three community votes are binding during this period: the **framework
ratification**, the **Permanent RAC election**, and the **Activation Vote**.

---

## The activation sequence

```
 1. GP-PRE-1      Constitutional ratification of the framework        (pre-formation)
      │             Operating Agreement Schedule 5, condition 6
 2.   Formation — Transition RAC files the Certificate of Formation + Operating Agreement
      │             Company exists, MEMBER-MANAGED; Advisory Governance Period begins
 3. GP-ELECT-1    Permanent RAC election + seating                    (Schedule 5, condition 7)
      │
 4. GP-ACTIVATE-1 Activation Vote → Activation Date → Algorithmically Governed
```

| # | Proposal | Status |
|---|---|---|
| 1 | [GP-PRE-1: Constitutional Ratification of the Governance Framework](GP-PRE-1-Framework-Ratification.md) | Ready for review |
| 3 | [GP-ELECT-1: Permanent RAC Election](GP-ELECT-1-Permanent-RAC-Election.md) | ⚠️ Draft scaffold |
| 4 | [GP-ACTIVATE-1: Activation Vote](GP-ACTIVATE-1-Activation-Vote.md) | ⚠️ Draft scaffold |

A YES vote on **GP-PRE-1** ratifies the framework below as the DAO's governance framework. It does
**not** form the entity (that mandate is already held by the current RAC) and does **not** activate the
DAO — community governance becomes binding only on the **Activation Date** (GP-ACTIVATE-1).

---

## What GP-PRE-1 ratifies

The community ratifies the **Charter** (governance constitution) and the **operational policy library**.
On formation the Operating Agreement recognises and gives legal effect to this framework (OA §11.1,
§11.2, §11.5; Charter §4A).

| Document | Category | File |
|---|---|---|
| Charter | Constitutional (governance constitution) | [constitutional/charter.md](constitutional/charter.md) |
| DAO Parameters Registry | Parameters | [parameters/dao-parameters-registry.md](parameters/dao-parameters-registry.md) |
| Proposal & Voting Framework | Governance | [governance/proposal-and-voting-framework.md](governance/proposal-and-voting-framework.md) |
| Execution & Treasury Actions Policy | Governance | [governance/execution-and-treasury-actions-policy.md](governance/execution-and-treasury-actions-policy.md) |
| Emergency & Safeguards Policy | Governance | [governance/emergency-and-safeguards-policy.md](governance/emergency-and-safeguards-policy.md) |
| Treasury Signers Rules | Governance | [governance/treasury-signers-rules.md](governance/treasury-signers-rules.md) |
| On-Chain Identifiers & Verification Policy | Governance | [governance/on-chain-identifiers-and-verification-policy.md](governance/on-chain-identifiers-and-verification-policy.md) |
| RAC Mandate (Permanent RAC) | Governance | [governance/rac-mandate.md](governance/rac-mandate.md) |
| Delegate Mandate | Governance | [governance/delegate-mandate.md](governance/delegate-mandate.md) |
| Conflict of Interest Policy | Governance | [governance/conflict-of-interest-policy.md](governance/conflict-of-interest-policy.md) |
| Code of Conduct | Governance | [governance/code-of-conduct.md](governance/code-of-conduct.md) |
| Compliance Operations Policy | Governance | [governance/compliance-operations-policy.md](governance/compliance-operations-policy.md) |
| Governance Maintenance & Upgrade Framework | Governance | [governance/governance-maintenance-and-upgrade-framework.md](governance/governance-maintenance-and-upgrade-framework.md) |
| Working Group Framework | Governance | [governance/working-group-framework.md](governance/working-group-framework.md) |
| Elections & Role Governance Policy | Governance | [governance/elections-and-role-governance-policy.md](governance/elections-and-role-governance-policy.md) |
| Governance Continuity Framework | Governance | [governance/governance-continuity-framework.md](governance/governance-continuity-framework.md) |
| Dispute Resolution & Arbitration Policy | Governance | [governance/dispute-resolution-and-arbitration-policy.md](governance/dispute-resolution-and-arbitration-policy.md) |
| Contributor Compensation Policy | Governance | [governance/contributor-compensation-policy.md](governance/contributor-compensation-policy.md) |
| Contributor Onboarding and Offboarding | Governance | [governance/contributor-onboarding-and-offboarding.md](governance/contributor-onboarding-and-offboarding.md) |
| Source Code Stewardship Policy | Governance | [governance/source-code-stewardship-policy.md](governance/source-code-stewardship-policy.md) |
| Open Source & Intellectual Property Policy | Governance | [governance/open-source-and-ip-policy.md](governance/open-source-and-ip-policy.md) |

*(The [Roles Registry](governance/roles-registry.md) is a navigation aid that maps roles to the documents above; it is not a separate source of rules and is not part of the ratified set.)*

---

## Formation & legal instruments

These are executed and filed by the Transition RAC at formation (not "ratified" by the community vote);
the Operating Agreement is the master instrument that recognises the ratified framework.

| Document | Category | File |
|---|---|---|
| Operating Agreement | Primary legal instrument | [legal/operating-agreement.md](legal/operating-agreement.md) |
| Certificate of Formation | Formation filing | [legal/certificate-of-formation.md](legal/certificate-of-formation.md) |
| BOIR Template | Compliance filing | [legal/BOIR-Template.md](legal/BOIR-Template.md) |

---

## Document precedence (highest to lowest)

1. **Marshall Islands law and the Certificate of Formation** — supreme by operation of law
2. **Operating Agreement** — the Company's primary legal instrument; prevails over the Charter and all policies
3. **Charter** — governance constitution; subordinate to the OA but prevails over all operational policies
4. **Operational policies** — subordinate to both the OA and the Charter
5. **DAO Parameters Registry** — within the operational policy tier; values updated by Governance Proposal

The Operating Agreement is the Company's primary legal instrument under Marshall Islands law and gives
the Charter legal effect (OA §11.1–§11.3; Charter §13). The Charter is the DAO's governance constitution,
designed to remain stable across legal jurisdictions; if the DAO ever redomiciles, the Charter travels
with the community and a new legal wrapper would similarly recognise it.

---

## Suggested reading order

1. **[GP-PRE-1-Framework-Ratification.md](GP-PRE-1-Framework-Ratification.md)** — what the ratification vote does, and the activation sequence
2. **[constitutional/charter.md](constitutional/charter.md)** — purpose, principles, and constitutional authority (see §4A for activation)
3. **[legal/operating-agreement.md](legal/operating-agreement.md)** — the legal entity instrument (member-managed → Algorithmically Governed)
4. **[governance/proposal-and-voting-framework.md](governance/proposal-and-voting-framework.md)** — how decisions are made
5. **[parameters/dao-parameters-registry.md](parameters/dao-parameters-registry.md)** — all numerical thresholds and limits (incl. §3A activation parameters)

**New to the framework?** Two plain-language companion guides explain the *purpose* of each document for non-lawyers. They are companion aids only — not part of the framework, not ratified by GP-PRE-1, and where a guide and an operative document differ, the operative document prevails.

- [Charter Reading Guide](constitutional/charter-reading-guide.md) — why each section of the Charter exists.
- [Policy Library Reading Guide](policy-library-reading-guide.md) — a one-line purpose for every policy and framework.

---

## From ratification to activation

1. **GP-PRE-1 passes** → the framework is the community-ratified governance framework (Activation Condition 6).
2. **Formation** → the Transition RAC files the Certificate of Formation and Operating Agreement; the Company exists and is member-managed; the Advisory Governance Period begins.
3. **GP-ELECT-1** → the Permanent RAC is elected and seated (Activation Condition 7).
4. The Transition RAC publishes the **Activation Statement** once all Schedule 5 conditions are met.
5. **GP-ACTIVATE-1** (Activation Vote) passes → the **Activation Date**: the Company becomes Algorithmically Governed, governance outcomes become binding, and the Transition RAC sunsets.

The full governance reference library, including working drafts, templates, and activation history, is
maintained in the [Radix DAO reference repository](https://github.com/Shadaffy/radix-dao).
