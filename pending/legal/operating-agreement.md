# Radix DLT DAO LLC — Operating Agreement

> **Pre-adoption notice:** This is the proposed Operating Agreement submitted for community adoption as part of GP-PRE-1. It becomes operative upon passage of that Constitutional Proposal.

---

## Defined Terms

For the purposes of this Agreement, the following terms have the meanings given below:

**"Agreement"** means this Operating Agreement, as amended from time to time by Governance Proposal.

**"Company"** means Radix DLT DAO LLC, a Marshall Islands Non-Profit DAO LLC.

**"Delegate"** means a person elected by Governance Proposal to perform one or more Delegated Functions under Article V.

**"Delegated Function"** means any of the five operational functions described in §5.3.

**"Founding Transferor"** means the entity that transferred the initial founding assets to the Company at or following formation, as identified in the Continuity Statement executed under §3.2. The identity of the Founding Transferor is recorded in the Continuity Statement and is not required to be named in this Agreement.

**"Asset Transferor"** or **"Grantor"** means any entity — including the Founding Transferor — that transfers assets or grants funds to the Company under a formal Asset Transfer Agreement or a Governance Proposal approved through the on-chain governance system.

**"Governance Participant"** means any person or entity that holds Governance Tokens and participates in the Company's on-chain governance system, in accordance with §4.2. Governance Participants exercise binding decision-making rights delegated to them under this Agreement, but are not legal Members of the Company unless they have separately been admitted to Membership under §4.1.

**"Governance Platform"** means the on-chain governance system identified in §1.4, through which the Company conducts its governance.

**"Governance Proposal"** or **"GP"** means a formal governance vote conducted through the Governance Platform in accordance with the operational policies adopted under §12.4.

**"Governance Tokens"** means the token types designated as eligible for governance participation and voting under the **DAO Parameters Registry §8**, as amended by Governance Proposal. At formation, Governance Tokens consist of XRD and Liquid Staking Units (LSUs) on the Radix Network, with LSUs converted to their XRD equivalent at the relevant snapshot.

**"Member"** means a person who has been admitted to membership in the Company in accordance with this Agreement and whose membership has not ceased or been terminated in accordance with this Agreement. For the avoidance of doubt, holding a Governance Token, participating in the Company's on-chain governance, contributing to the protocol, or otherwise participating in the wider Radix community shall not, of itself, constitute admission as a Member of the Company unless and until the conditions for admission expressly set out in this Agreement and, where applicable, the Charter have been satisfied. Admission and the legal status of Membership are governed by §4.1.

**"Membership"** means the legal status of being admitted as a Member of the Company in accordance with this Agreement.

**"Permanent RAC"** means the Permanent Radix Accountability Council constituted following the Transition Period in accordance with this Agreement and the Charter, as the standing governance-process oversight body of the Company. The Permanent RAC is the guardian of the governance process and constitutional order of the Company and is not, unless expressly stated otherwise, a general executive, treasury-management or policy-making authority. The composition, election, and detailed mandate of the Permanent RAC are governed by the Charter and the operational policies adopted under §12.4.

**"Temperature Check"** or **"TC"** means a preliminary community sentiment poll conducted before a Governance Proposal is elevated.

**"Transition Period"** means the period commencing on the date the Company is formed under §1.1 and ending on the date the Permanent RAC is seated following the election conducted under the Charter and the Elections & Role Governance Policy. The Transition Period is a formation period only; full governance under this Agreement and the operational policies adopted under §12.4 is operative from the date of formation.

**"Transition RAC"** means the temporary Transition Radix Accountability Council constituted under this Agreement for the limited purpose of implementing the Transition Period, including completion of the formation of the Company, establishment of the Transition Treasury and related control architecture, satisfaction of initial compliance and onboarding requirements, receipt and safeguarding of assets, rights and control positions transferred to the Company, and implementation of the handover to the Permanent RAC. The Transition RAC is a temporary implementation authority only and has no continuing or general governance authority except as expressly set out in this Agreement. The constitution and mandate of the Transition RAC are set out in Article XIII.

---

## Article I — Formation

### §1.1 Name and Entity Type

The Company is organized as a Non-Profit DAO LLC under the Marshall Islands Limited Liability Company Act (52 MIRC Ch. 3) and the Marshall Islands DAO Act (52 MIRC Ch. 7).

### §1.2 Registered Agent

The registered agent of the Company is MIDAO Directory Services, Inc., Majuro, Marshall Islands, or such other registered agent as the Compliance Liaison may designate by Governance Proposal.

### §1.3 Duration

The Company has perpetual duration unless dissolved in accordance with Article IX or by operation of law.

### §1.4 Smart Contract Identifiers

The on-ledger components through which the Company's governance and treasury operate are identified below. These identifiers are recorded with the Registered Agent at formation. Any update requires a Governance Proposal, after which the Governance Operator updates the record with the Registered Agent.

The governance system is implemented using the Consultation V2 platform (`github.com/radixdlt/consultation_v2`).

| Component | Identifier | Notes |
|---|---|---|
| Governance Package | `[packageAddress — to be recorded at formation]` | Scrypto package containing the governance blueprints |
| Governance Component | `[componentAddress — to be recorded at formation]` | Instantiated governance component; authoritative record of votes and proposals |
| Owner Badge | `[adminBadgeAddress — to be recorded at formation]` | Authorization token held by Governance Operators to elevate Temperature Checks to Governance Proposals |
| Treasury Multisig | `[multisigAddress — to be recorded at formation]` | Multi-signature account holding Company treasury assets |

These identifiers shall be inserted by the Legal Signatory within 72 hours of entity formation and the record updated per §10.2. The Governance Operator shall notify the Registered Agent of the recorded identifiers within 14 days of formation. No separate Governance Proposal is required solely to record the initial identifiers at formation; the adoption of this Agreement by GP-PRE-1 constitutes sufficient authorization for the Legal Signatory to complete this record.

---

## Article II — Purpose

### §2.1 Non-Profit Purpose

The Company is organized exclusively for charitable and educational purposes within the meaning of the Marshall Islands Non-Profit Entities Act (2020), specifically:

* Education in decentralized ledger technology and its applications
* Development and management of decentralized ledger technology, blockchain protocols, and distributed systems
* Advancement of cryptographic systems and open-source software
* Research and governance of distributed and decentralized protocols
* Support for token-based participation and distributed governance mechanisms

### §2.2 Non-Distribution Constraint

No income, assets, or profits of the Company shall be distributed to Members, Delegates, or Governance Participants by virtue of their respective status. All assets and income must be applied solely toward the purposes set out in §2.1 and the operational policies adopted under §12.4.

**Permitted exceptions.** Notwithstanding the constraint above, the following exceptions are permitted and do not constitute prohibited distributions:

* **(a)** Reasonable compensation for genuine services rendered to the Company;
* **(b)** Interest at a reasonable rate on money lent to the Company by any Member, Delegate, or Governance Participant;
* **(c)** Reasonable rent for premises or assets provided to the Company by any Member, Delegate, or Governance Participant;
* **(d)** Reimbursement of legitimate out-of-pocket expenses properly incurred on behalf of the Company;
* **(e)** Indemnification payments and expense advancements made in accordance with §11.3 and §5.4.

None of the permitted exceptions creates any beneficial ownership interest in the Company's assets. Operational procedures for administering these exceptions — including documentation, eligibility verification, and disclosure — are defined in the **Compliance Operations Policy** (operational policy).

---

## Article III — Continuity

### §3.1 Formation Purpose
The Company is formed to receive and manage assets — including from the Founding Transferor and subsequent Asset Transferors — in order to continue and support the advancement of decentralized ledger technology consistent with the purposes set forth in Article II.

### §3.2 Continuity Statement Authority
The Legal Signatory (§5.3(c)) is authorized to execute a standalone continuity statement on behalf of the Company in substantially the form required by the Founding Transferor, or in such other form as a Governance Proposal may approve for any subsequent Asset Transferor. Each executed continuity statement must be publicly recorded.

### §3.3 Received Assets Liability Limitation
The Company receives assets from Asset Transferors in good-faith reliance on the representations made by the transferring party. No Member or Delegate shall be personally liable for claims, obligations, or liabilities arising from the nature, title, encumbrances, or defects of assets received from any Asset Transferor, provided that the Member or Delegate acted in good faith and in accordance with this Agreement and applicable Governance Proposals. This limitation applies to the personal liability of Members and Delegates and does not limit the Company's own liability as a legal entity.

---

## Article IV — Membership and Governance Participation

This Article establishes two distinct categories of participation in the Company: formal legal **Membership** (§4.1) and **Governance Participation** (§4.2). Each category carries its own rights, obligations, and standards of conduct. A person may hold Membership, Governance Participation, both, or neither; the categories are independent.

### §4.1 Membership

**(a) Admission.** A person becomes a Member of the Company only by admission in accordance with this Agreement. During the Transition Period, Membership is held by the five Transition RAC members identified in Article XIII. Following the seating of the Permanent RAC, Membership is held by the Permanent RAC members and the Delegates elected under Article V.

**(b) No automatic Membership from token holding.** Holding a Governance Token, participating in the Company's on-chain governance, contributing to the protocol, or otherwise participating in the wider Radix community shall not, of itself, constitute admission as a Member of the Company.

**(c) Membership Interest.** Each Member holds a Membership Interest by virtue of admission. Membership Interests are not independently transferable and confer no economic rights (§4.4).

**(d) Termination.** Membership terminates automatically upon the Member ceasing to hold the role by virtue of which Membership was conferred (cessation of Transition RAC membership during the Transition Period; cessation of Permanent RAC seat or Delegate function thereafter), upon resignation, or upon removal by Governance Proposal. A person whose Membership terminates retains any Governance Participation rights they hold by virtue of token ownership.

### §4.2 Governance Participation

**(a) Right of participation.** Any person or entity holding Governance Tokens is a Governance Participant. Governance Participation is acquired upon acquiring Governance Tokens and ceases when the holder no longer holds any Governance Tokens and has no active votes recorded on the Governance Platform.

**(b) Exercise of governance rights.** Governance Participants exercise governance rights through the Governance Platform in accordance with this Agreement, the Charter, and the operational policies adopted under §12.4. Governance rights include the right to submit Temperature Checks, propose Governance Proposals, and vote on Temperature Checks and Governance Proposals.

**(c) Voting power.** Each Governance Participant's voting power is proportional to their eligible Governance Token holdings determined at the snapshot taken at the start of each vote, in accordance with §6.3 and the **DAO Parameters Registry §8**.

**(d) Relationship to Membership.** Governance Participation does not confer Membership. A Governance Participant who is not a Member exercises governance rights solely by virtue of the delegation set out in §4.3.

### §4.3 Binding Effect of On-Chain Governance Decisions

Governance authority of the Company is vested in the Governance Participants and is exercised through the Governance Platform. The Company hereby delegates to the Governance Platform the authority to record and determine governance decisions of the Company in accordance with this Agreement and the operational policies adopted under §12.4.

On-chain governance outcomes recorded by the Governance Platform, having satisfied the quorum and approval thresholds applicable to their proposal category, constitute legally binding decisions of the Company. Such decisions bind the Company, its Members, its Delegates, and its Governance Participants, and shall be given full legal effect under this Agreement and the laws of the Republic of the Marshall Islands, regardless of whether the persons participating in such governance hold formal Membership in the Company at the time of the decision.

This delegation of governance authority is a foundational provision of this Agreement, intended to give effect to the algorithmic management model contemplated by the Marshall Islands DAO Act. No amendment to this section may be effected other than by a Constitutional Amendment passed in accordance with §10.1(a).

### §4.4 No Economic Rights
Neither Membership nor Governance Participation confers economic ownership in the Company's assets or any right to share in income, profits, or distributions. Membership and Governance Participation confer participation rights only, subject to the permitted exceptions to the non-distribution principle set out in §2.2.

### §4.5 Standard of Conduct

**(a) Members.** Members shall act in good faith and in the best interests of the Radix Network ecosystem per §709 of the Marshall Islands DAO Act. No Member has any fiduciary duty to the Company or any other Member beyond the implied contractual covenant of good faith and fair dealing, as permitted by §709 of the Marshall Islands DAO Act.

**(b) Governance Participants.** Governance Participants shall act in good faith when exercising their governance rights. Governance Participants have no fiduciary duty to the Company or to other Governance Participants by virtue of their participation, beyond the implied covenant of good faith and fair dealing.

### §4.6 UBO Compliance

Any Governance Participant — whether or not also a Member — whose eligible voting power exceeds 25% of total eligible voting power is classified as an Ultimate Beneficial Owner (UBO) and is subject to mandatory KYC obligations in accordance with the operational policies adopted under §12.4 and the Marshall Islands DAO Act. UBO classification follows the statutory test of voting power or actual control and is not contingent on Membership status.

### §4.7 Liability Limitation
No Member, Delegate, or Governance Participant is personally liable for the debts, obligations, or liabilities of the Company solely by reason of their Membership, Delegated Function, or Governance Participation, or for acts of the Governance Platform executed as authorized by this Agreement.

---

## Article V — Delegated Functions

### §5.1 Algorithmic Management Structure
The Company does not have managers, directors, officers, or trustees in the conventional sense. Management is vested in the Governance Participants collectively, exercising binding governance authority through the Governance Platform under §4.3 and consistent with §708 of the Marshall Islands DAO Act on algorithmic management. Operational functions are performed by Delegates elected by Governance Proposal. Upon election and following the Transition Period, Delegates are admitted to Membership by virtue of their role per §4.1(a).

### §5.2 Election of Delegates
Delegates (minimum 5, maximum 7 persons) are elected by Governance Proposal. Delegates allocate the non-Treasury Delegated Functions among themselves in accordance with §5.3. All Delegates are subject to KYC verification before assuming their function. A Delegate may simultaneously hold a Permanent RAC seat, subject to the role-concentration limits set out in the **DAO Parameters Registry §6B** and the recusal obligations of the **Conflict of Interest Policy**.

The Treasury Signing function (§5.3(a)) must be held by exactly 5 Delegates to support the signing thresholds defined in DAO Parameters §6A. The Governance Proposal establishing or modifying the Delegate roster must identify which 5 Delegates hold Treasury Signing. Where the total Delegate count differs from 5, the remaining Delegates hold non-treasury functions only.

### §5.3 Delegated Functions
The following functions are delegated to elected Delegates:

**(a) Treasury Signing**

Execute treasury transactions via multi-signature wallet. Treasury Signers may only sign transactions authorized by a Governance Proposal. In an emergency, Treasury Signers may act to preserve assets or services, subject to GP ratification within the period specified in the **Emergency & Safeguards Policy §10**.

**(b) Governance Operations**

Operate the Governance smart contract: elevate approved Temperature Checks to Governance Proposals via the Owner Badge; update governance parameters per GP; maintain the Governance smart contract.

**(c) Legal Signatory**

Sign contracts, continuity statements, and other legal instruments on behalf of the Company, only as authorized by Governance Proposal. Act as the Company's legal representative for entity maintenance and compliance filings. Initiate, pursue, settle, or defend legal proceedings on behalf of the Company as authorized by Governance Proposal; or, in urgent circumstances where a delay of more than 48 hours would cause material and irreversible harm to the Company, take protective legal action subject to GP ratification within 30 days.

**(d) Compliance Liaison**

Act as Registered Agent liaison; file the annual Beneficial Owner Information Report (BOIR); coordinate KYC for Delegates and UBO Members; maintain KYC and sanctions records in accordance with applicable law.

**(e) Web2 Custodian**

Manage social media accounts, GitHub repositories, domain names, and other Web2 assets using an enterprise password manager. The Web2 Custodian may not transfer domain ownership or delete repositories without a Governance Proposal.

### §5.4 Governance Oversight Indemnification
The Company shall indemnify any person performing a DAO-mandated governance oversight function — including but not limited to accountability review, governance process monitoring, emergency governance coordination, and compliance verification — against claims arising from the good-faith performance of that function, on the same terms as §11.3 applies to Delegates. This indemnification applies to oversight functions recognized in the operational policies adopted under §12.4. For the purposes of this section, a "DAO-mandated governance oversight function" means a function explicitly assigned by Governance Proposal or defined in an operational policy adopted under §12.4, and does not extend to unilateral or self-appointed oversight activities.

### §5.5 Removal and Replacement
Any Delegate may be removed by Governance Proposal. If a Delegate vacates their function, the remaining Delegates may appoint a temporary replacement from among eligible Governance Participants, subject to GP ratification within 30 days.

**Legal Signatory continuity.** If the Legal Signatory Delegate is unavailable, conflicted, or unresponsive for more than 24 hours in circumstances requiring time-critical legal action, the Compliance Liaison Delegate is authorised to act as interim Legal Signatory for protective or time-critical purposes only. Any action taken under this provision must be disclosed to the governance forum within 24 hours and is subject to GP ratification within 30 days.

### §5.6 Standard of Conduct — Delegates
Delegates shall act in good faith with diligence, accountability, and transparency per §709 of the DAO Act and §216 of the Non-Profit Act. Delegates shall disclose conflicts of interest and recuse themselves from decisions where a material conflict exists. No Delegate has any fiduciary duty beyond good faith and the obligations of their assigned Delegated Function, as permitted by §709 of the Marshall Islands DAO Act.

**Primary law obligation.** In performing their Delegated Function, each Delegate's primary legal obligation is to the laws of the Republic of the Marshall Islands and this Agreement. Where a Delegate receives a demand, order, or regulatory inquiry from a foreign jurisdiction that conflicts with a DAO-approved decision or with this Agreement, the Delegate shall seek DAO-authorized legal counsel before compliance and, where legally possible under Marshall Islands law, treat DAO authorization as a condition of compliance. This is an obligation of conduct within the Delegate's assigned function; it does not create a fiduciary duty beyond what is stated in this section. This obligation does not prevent a Delegate from taking protective action necessary to avoid criminal liability, provided they notify RAC immediately in accordance with the Regulatory Demand Disclosure Protocol in the **Compliance Operations Policy §5**.

---

## Article VI — Governance

### §6.1 On-Chain Governance System

The Company conducts its governance through the Governance Platform identified in §1.4. The Governance Platform is the authoritative record of all Temperature Checks, Governance Proposals, votes cast, and results determined.

On-chain governance outcomes recorded by the Governance Platform constitute legally binding decisions of the Company under §4.3 of this Agreement and §708 of the Marshall Islands DAO Act. Such decisions bind the Company, its Members, its Delegates, and its Governance Participants regardless of whether participating persons hold formal Membership at the time of the decision.

The Governance Operator (§5.3(b)) administers the Governance Platform using the Owner Badge (§1.4). The Governance Operator acts only within the limits of Governance Proposals and the operational policies adopted under §12.4.

### §6.2 Proposal Process

Governance decisions follow a two-stage process:

**(a) Temperature Check (TC):** A preliminary community sentiment poll submitted to the Governance Platform. The Temperature Check stage allows the community to assess support before a binding vote is opened. Duration, eligibility, and submission requirements are defined in the **Proposal & Voting Framework** (operational policy).

**(b) Governance Proposal (GP):** A formal binding proposal elevated from an approved Temperature Check by the Governance Operator via the Owner Badge. The Governance Proposal constitutes the binding membership decision upon passing. Proposal categories, required content, voting period, and eligibility are defined in the **Proposal & Voting Framework** (operational policy).

The Governance Operator may not elevate a Temperature Check to a Governance Proposal unless the TC has met the approval conditions specified in the Proposal & Voting Framework. The Governance Operator may not modify, delay, or suppress an eligible elevation without a Governance Proposal authorizing the deviation.

### §6.3 Voting Power and Snapshot

Each Governance Participant's voting power is determined at a snapshot taken at the start of each Governance Proposal's voting period. Voting power is proportional to eligible Governance Token holdings; one token equals one vote.

Eligible holdings and the snapshot methodology — including treatment of Liquid Staking Units (LSUs) and delegated voting power — are defined in the **DAO Parameters Registry §8** (operational policy). Parameters governing eligible assets may be updated by Governance Proposal.

### §6.4 Thresholds and Parameters

All numerical governance parameters — including quorum thresholds by proposal type, approval thresholds by proposal type, voting period durations, review periods, cooldown periods, and veto windows — are defined in the **DAO Parameters Registry** (operational policy).

The DAO Parameters Registry may be updated by Governance Proposal. Updates to governance parameters take effect on the date specified in the amending Governance Proposal, or immediately upon passage if no date is specified, and apply only to proposals submitted after the effective date.

### §6.5 Result Determination and Recording

The RAC (the Radix Accountability Council — the governance oversight body, constituted as the Transition RAC during the Transition Period under Article XIII and as the Permanent RAC thereafter under the Charter; in either form, a body of persons elected by Governance Proposal to perform governance integrity and compliance verification functions) is responsible for formally determining the outcome of each vote and publishing the official result within the window specified in **DAO Parameters §3.5**.

The determination procedure — including quorum verification, approval threshold calculation, winner determination for multi-option votes, and weighted allocation computation — is defined in the **Proposal & Voting Framework §6.5** (operational policy). The on-chain record on the Governance Platform is the authoritative source for raw vote data; the RAC's published result is the authoritative determination of outcome.

A veto challenge mechanism allows Governance Participants to contest results that violate the Charter or governance rules, within the window and conditions defined in **DAO Parameters §4** and the **Proposal & Voting Framework §8** (operational policy).

### §6.6 Smart Contract Changes
Changes to the Governance or Treasury smart contracts require:

* (a) an RFC published to the community forum for a minimum 7-day review period
* (b) an independent security audit of the proposed changes
* (c) a Governance Proposal with an enhanced approval threshold as specified in the operational policies

---

## Article VII — Treasury

### §7.1 Multi-Signature Control

The Company's treasury assets are held in the multi-signature account identified in §1.4. All treasury transactions require multi-signature authorization from the Members holding the Treasury Signing function (§5.3(a)).

Signing thresholds are defined in **DAO Parameters §6A**: standard transactions require a minimum of 3-of-5 Treasury Signers; transactions classified as high-risk require 4-of-5. The classification of transaction types and the full operational rules governing treasury execution — including acknowledgement windows, execution windows, and conflict disclosure requirements — are defined in the **Execution & Treasury Actions Policy** and the **Treasury Signers Operational Rules** (operational policies).

Treasury Signers may only execute transactions that have been authorized by a Governance Proposal or that fall within a budget explicitly approved by a prior Governance Proposal. Record-keeping and audit requirements for treasury transactions are defined in the **Execution & Treasury Actions Policy** (operational policy).

### §7.2 Authorized Expenditures
Treasury expenditures require prior authorization by Governance Proposal, except:

* Routine operational costs within DAO-approved budgets
* Emergency expenditures under §5.3(a) subject to GP ratification within 30 days
* Indemnification payments and expense advancements required under §11.3 and §5.4 — no prior GP authorization is required; Treasury Signers may execute these directly, subject to GP ratification within 30 days of payment

---

## Article VIII — Compliance

### §8.1 Beneficial Owner Information Report

The Compliance Liaison (§5.3(d)) shall file a Beneficial Owner Information Report (BOIR) with the Registered Agent in accordance with Marshall Islands DAO Act §712 and Non-Profit Entities Act §218:

* **Initial BOIR:** at formation
* **Annual BOIR:** between January 1 and March 31 of each calendar year
* **Updated BOIR:** within 30 days of any material change in beneficial ownership, in the Delegate roster, or in the composition of the Transition RAC or Permanent RAC

The BOIR must identify:

* All Delegates (who qualify as beneficial owners by virtue of actual control under DAO Act §702(r));
* During the Transition Period, all Transition RAC members (who qualify as beneficial owners by virtue of holding Membership and acting as the formation authority);
* Following the Transition Period, all Permanent RAC members (who qualify as beneficial owners by virtue of holding Membership);
* Any Governance Participant — whether or not also a Member — holding 25% or more of eligible voting power (UBO threshold).

BOIR identification follows the statutory tests of voting power and actual control, and is not contingent on Membership status. The procedure, required fields, and declaration requirements are defined in the **BOIR Template** maintained in the governance repository.

### §8.2 KYC Maintenance

KYC verification is required for all persons reportable under §8.1, in two tiers:

* **KYC Tier 1 (Role-Holder KYC):** All Delegates and all members of the Transition RAC and Permanent RAC must complete KYC verification through the DAO's designated KYC provider before assuming their function or seat. Annual reverification is required each January per MIDAO requirements.
* **KYC Tier 2 (UBO KYC):** Any Governance Participant reaching the 25% UBO threshold must complete KYC within 14 days of crossing the threshold and notify the Compliance Liaison. Annual reverification applies.

Thresholds, KYC provider selection, and the full UBO monitoring obligations of the Compliance Liaison are defined in the **Compliance Operations Policy** and **DAO Parameters §8** (operational policies). The Compliance Liaison maintains KYC records confidentially with the Registered Agent in accordance with Marshall Islands law.

### §8.3 Sanctions Screening

The Compliance Liaison shall instruct the DAO's KYC provider to cross-check all KYC applicants against applicable sanctions records before verification is granted. A sanctioned individual may not hold a Delegated Function or receive compensation from the Company. Sanctions enforcement, including identity-bound sanctions for KYC-verified persons, is governed by the **Code of Conduct** (operational policy).

### §8.4 Entity Standing

The Compliance Liaison is responsible for maintaining the Company's good standing with the Registered Agent, including:

* annual entity filings per Non-Profit Entities Act §218
* payment of Registered Agent fees
* updating the Registered Agent record when smart contract identifiers change (§1.4)
* ensuring the BOIR on file with the Registered Agent is current at all times

Failure to maintain entity standing is a material governance failure and must be reported to the Members via the governance forum within 48 hours of the Compliance Liaison becoming aware of the issue. If the Compliance Liaison is unavailable or is the source of the failure, the Legal Signatory shall assume the reporting and remediation obligation under this section and notify the RAC immediately.

---

## Article IX — Dissolution

### §9.1 Dissolution Events
The Company shall be dissolved upon:

* (a) a Governance Proposal with ≥80% approval and ≥20% quorum of Members
* (b) events specified in the smart contracts or this Agreement
* (c) a Registrar order if the Company is no longer lawful or no longer under natural person control
* (d) voluntary resignation of all Members

### §9.2 Asset Disposition on Dissolution
On dissolution, the Company's remaining assets shall not be distributed to Members. Remaining assets shall be transferred to a successor entity approved by Governance Proposal. A successor entity qualifies only if it meets all of the following criteria:

* **(a)** it is organized on a non-profit or non-distribution basis under applicable law, such that its assets cannot be distributed to its own members for personal gain
* **(b)** it operates primarily in the domain of decentralized ledger technology, open-source cryptographic protocols, or substantially equivalent blockchain infrastructure
* **(c)** it maintains a non-distribution principle that prevents its members from extracting assets for personal benefit
* **(d)** it commits to applying received assets toward ecosystem development, open-source software, public education, or equivalent public-benefit activities consistent with the purposes in Article II
* **(e)** it is approved by a Governance Proposal with ≥80% approval and ≥20% quorum

Prior to executing any asset transfer upon dissolution, the Legal Signatory shall provide written notice to any primary Asset Transferor that contributed material assets to the Company, giving that party 30 days to submit written comment to the governance forum. Such comments shall be published and available to Members before the dissolution GP vote concludes. Asset Transferors have no veto right; this notification obligation is a transparency measure only.

The Legal Signatory shall execute a statement of dissolution in the prescribed form upon completion of the asset transfer.

### §9.3 Asset Provenance Record
Prior to any dissolution asset transfer, the Company shall publish a public accounting of all assets held, their provenance (including all assets received from any Asset Transferor), and their proposed disposition. This record must be published to the governance forum before the dissolution GP vote concludes.

---

## Article X — Amendments

### §10.1 Standard Amendment Process

This Agreement may be amended by Governance Proposal. Amendments are classified as follows:

**(a) Constitutional Amendments** — changes to Articles I (Formation), II (Purpose), III (Continuity), IV (Membership and Governance Participation), XI (Disputes and Liability), or XIII (Transition Period), and changes to the Charter. Constitutional Amendments require a Constitutional Proposal, with quorum and approval thresholds as defined in **DAO Parameters §3.2–3.3**.

**(b) Governance Amendments** — changes to Articles V (Delegated Functions) through XII (General Provisions). Governance Amendments require a Governance Process Proposal, with quorum and approval thresholds as defined in **DAO Parameters §3.2–3.3**.

The classification of any proposed amendment and the document versioning requirements are governed by the **Governance Maintenance & Upgrade Framework** (operational policy). In case of conflict between this Article and the Governance Maintenance & Upgrade Framework on questions of classification, this Article prevails.

### §10.2 Amendment Record

The Governance Operator shall record each amendment to this Agreement with:

* the amended section(s)
* the new text
* the version number (incremented per the Governance Maintenance & Upgrade Framework)
* the date of effect
* the Governance Proposal number authorizing the amendment

All amendment records are maintained in the governance repository and are publicly accessible. The version of this Agreement in effect at any given time is the version whose effective date is most recent as of that date.

### §10.3 Emergency Amendments
Emergency amendments to this Agreement may be adopted by unanimous written consent of the Delegates, subject to ratification by Governance Proposal within 30 days. Emergency amendments that are not ratified within 30 days are void and of no effect. For the purposes of this section, "written consent" means a signed statement from each Delegate published to the DAO governance forum, or a transaction signed by each Delegate's KYC-verified wallet address, or a signed instrument delivered to the Legal Signatory — all three forms are equally valid.

---

## Article XI — Disputes and Liability

### §11.1 Dispute Resolution
Disputes shall first be referred to the Compliance Liaison for mediation. Where the Compliance Liaison is a party to, or has a material conflict of interest in, the dispute, the RAC shall serve as first-stage mediator in place of the Compliance Liaison. If unresolved within 30 days, the mediating party may raise a Governance Proposal directly for the Members to decide, bypassing the Temperature Check stage. If any party is not satisfied with the GP outcome, or if the dispute is not suitable for community vote, it shall be settled by binding arbitration under the International Arbitration Rules of the ICDR (International Centre for Dispute Resolution), seated in the Republic of the Marshall Islands, conducted in English, by a sole arbitrator.

### §11.2 Governing Law
This Agreement is governed by the laws of the Republic of the Marshall Islands.

### §11.3 Liability and Indemnification
**Limitation of Liability.** No Member or Delegate is personally liable for the debts, obligations, or liabilities of the Company solely by reason of membership or service, or for acts of the smart contracts executed as authorized by this Agreement.

**Indemnification.** To the fullest extent permitted by applicable law, the Company shall indemnify, defend, and hold harmless each Delegate and each Member performing a DAO-mandated governance oversight function (including RAC members acting within their mandate) against any claims, liabilities, damages, losses, costs, and expenses (including reasonable legal fees) arising from or relating to the good-faith performance of their Delegated Function or governance oversight role.

**Advancement of Expenses.** The Company shall advance reasonable legal expenses to any Delegate or RAC member who is a party or threatened to be a party to any proceeding arising from their role, provided that the recipient undertakes in writing to repay such amounts if it is ultimately determined by final adjudication that they are not entitled to indemnification under this section. Such advancement does not require prior Governance Proposal authorization; Treasury Signers are authorized to execute advancement payments directly, subject to GP ratification within 30 days and the repayment undertaking required by this section.

**Exclusions.** Indemnification and expense advancement under this section do not apply to claims arising from: (a) gross negligence; (b) willful misconduct; (c) fraud; (d) breach of the duty of loyalty to the Company; or (e) knowing violation of applicable law.

**Scope.** This section does not limit any additional protections available to Members or Delegates under Marshall Islands law or any insurance policy maintained by the Company.

---

## Article XII — General Provisions

### §12.1 Notices

Written notice posted to the DAO's designated governance forum constitutes valid and sufficient notice for all internal governance matters under this Agreement, including proposals, disclosures, and regulatory announcements to Members.

Legal notices to the Company (including service of process, regulatory correspondence, and formal demands) must be served at the address of the Registered Agent identified in §1.2. The Compliance Liaison shall forward any such notice to the Delegates and publish notice of receipt to the governance forum within 48 hours, in accordance with the Regulatory Demand Disclosure Protocol defined in the **Compliance Operations Policy §5**.

### §12.2 Severability

If any provision of this Agreement is held to be invalid, illegal, or unenforceable under applicable law, that provision shall be modified to the minimum extent necessary to make it valid and enforceable, or if modification is not possible, it shall be severed from this Agreement. The validity and enforceability of the remaining provisions shall not be affected.

### §12.3 Entire Agreement

This Agreement, together with the Charter and the operational policies adopted under §12.4, constitutes the complete governance framework of the Company with respect to the governance, operation, and management of the Company. It supersedes all prior agreements, representations, or understandings relating to the same subject matter.

The Charter is the governance constitution of the DAO, containing the principles, structural authority, and entrenched provisions adopted by the community. This Agreement recognizes the Charter and incorporates it by reference, subject to the priority rules established in §12.5. The Charter is designed to remain stable across legal jurisdictions; this Agreement gives the Charter legal effect within the Marshall Islands legal structure.

In the event of conflict between this Agreement and the Charter, this Agreement prevails. In the event of conflict between this Agreement and any operational policy adopted under §12.4, this Agreement prevails.

### §12.4 Operational Policies
Operational policies, procedures, and guidelines may be adopted by Governance Proposal to supplement this Agreement and the Charter. Such documents are subordinate to this Agreement and the Charter, and may be amended or revoked by Governance Proposal. A provision of an operational policy that conflicts with this Agreement or the Charter is void to the extent of the conflict. The governance framework documents adopted as operational policies are listed in the most recent Governance Proposal activating them.

### §12.5 Document Hierarchy

The Company's governance documents rank in the following order of precedence for conflict resolution purposes:

**(a) Marshall Islands law and Articles of Organization.** Marshall Islands law (including 52 MIRC Ch. 3 and 52 MIRC Ch. 7) and the Company's Articles of Organization are supreme by operation of law. No provision of this Agreement, the Charter, or any operational policy may override a mandatory provision of Marshall Islands law or the Articles of Organization. Where a provision of this Agreement or the Charter restates a mandatory statutory provision, that provision is binding by force of law.

**(b) This Agreement.** This Agreement is the Company's primary legal instrument and the registered legal entity document of the Company. It prevails over the Charter and all operational policies in the event of conflict. The Charter and all operational policies derive their legal force from the recognition given to them in this Agreement.

**(c) The Charter.** The Charter is the governance constitution of the DAO, subordinate to this Agreement but prevailing over all operational policies. Where the Charter and an operational policy conflict, the Charter prevails. The Charter contains the governance principles, structural authority, and entrenched provisions of the DAO.

**(d) Operational policies.** Operational policies adopted under §12.4 are subordinate to both this Agreement and the Charter. A provision of an operational policy that conflicts with this Agreement or the Charter is void to the extent of the conflict.

---

## Article XIII — Transition Period

### §13.1 Recognition of the Transition Period

The Company recognizes a Transition Period commencing on the date of formation and ending on the date the Permanent RAC is seated following the election conducted under the Charter and the Elections & Role Governance Policy. The Transition Period is a formation period only. The full governance framework — including this Agreement, the Charter, and the operational policies adopted under §12.4 — is operative from the date of formation. Standard on-chain governance under §4.3 and Article VI proceeds from formation, in parallel with the Transition RAC's formation activities under this Article.

### §13.2 Constitution of the Transition RAC

The Transition RAC is constituted with five members, identified in the Governance Proposal authorizing this Agreement (GP-PRE-1). All Transition RAC members are admitted as Members of the Company under §4.1(a) upon entity formation, and all are subject to KYC verification (§8.2) before assuming their seats.

The Transition RAC has no continuing or general governance authority except as expressly set out in this Article.

### §13.3 Mandate of the Transition RAC

The Transition RAC's mandate is strictly limited to the following formation-period functions:

* **(a)** Completion of the formation of the Company, including filing of the Certificate of Formation and Operating Agreement with the Registered Agent and recording of smart contract identifiers under §1.4;
* **(b)** Initial Beneficial Owner Information Report (BOIR) filing under §8.1;
* **(c)** Establishment of the Treasury Multisig and recording of the multisig identifier under §1.4;
* **(d)** Receipt and safeguarding of assets, rights, and control positions transferred to the Company from the Founding Transferor, in accordance with Article III and an Asset Transfer Agreement approved under §3.2;
* **(e)** Satisfaction of initial compliance and onboarding requirements, including KYC for Transition RAC members and initial Delegates;
* **(f)** Coordination of the election of the Permanent RAC under the Charter and the Elections & Role Governance Policy;
* **(g)** Implementation of the handover to the Permanent RAC upon its seating.

The Transition RAC may not exercise any general executive, treasury-allocation, or policy-making authority beyond what is expressly set out above. All other governance decisions during the Transition Period are made by Governance Participants through the on-chain governance system under §4.3 and Article VI.

### §13.3A Transition RAC Internal Process

**(a) Decision rule.** Transition RAC decisions on matters within its mandate require a simple majority of seated Transition RAC members.

**(b) Non-delegation.** The Transition RAC may not delegate its core formation functions under §13.3 to any other body. Coordination with Working Groups, contributors, or external counsel is permitted; final decisions on the formation mandate remain with the Transition RAC.

**(c) Transparency.** All Transition RAC actions taken under §13.3 must be publicly reported to the governance forum within 72 hours of the action, including the action taken, the justification, the members who participated, and the outcome. Decisions and their justifications must be recorded and disclosed accordingly.

**(d) No override of standard governance.** The Transition RAC may not override, suppress, or delay any decision made by Governance Participants through the on-chain governance system under §4.3 and Article VI.

### §13.4 Treasury Signer Authority During the Transition Period

During the Transition Period, the Treasury Signing function (§5.3(a)) is held by the five Transition RAC members. Treasury transactions require signing thresholds as set out in §7.1 and the **DAO Parameters Registry §6A**:

* Standard transactions: 3-of-5 Treasury Signers;
* High-risk transactions and protected matters: 4-of-5 Treasury Signers.

The classification of high-risk transactions and protected matters is governed by the **Execution & Treasury Actions Policy** and the **Treasury Signers Operational Rules**.

### §13.5 Sunset and Handover

Upon the seating of the Permanent RAC:

* **(a)** The mandate of the Transition RAC expires automatically and immediately;
* **(b)** Membership held by Transition RAC members by virtue of their Transition RAC role terminates, save where any such person also holds Membership by virtue of a Permanent RAC seat or Delegate function;
* **(c)** All formation records, KYC records, asset transfer documentation, and treasury control materials are transferred to the Permanent RAC and the relevant Delegates;
* **(d)** The Treasury Multisig signer set is reconstituted as required to reflect the elected Treasury Signing Delegates under §5.2.

### §13.6 Continuity of Indemnification

Indemnification under §11.3 and §5.4 covers acts taken by Transition RAC members during the Transition Period and survives the sunset of the Transition RAC. No transition or handover under this Article shall diminish the indemnification protections of any person for acts taken in good-faith performance of their Transition RAC role.

### §13.7 Permanent RAC

The Permanent RAC is constituted following the Transition Period in accordance with the **Elections & Role Governance Policy** (operational policy). The Permanent RAC members are admitted as Members of the Company under §4.1(a) upon seating. The composition (between five and seven members), election procedure, mandate, and reporting obligations of the Permanent RAC are governed by the **RAC Mandate** and the **Elections & Role Governance Policy**. The Permanent RAC is the standing governance-process oversight body of the Company and is not, unless expressly stated otherwise, a general executive, treasury-management, or policy-making authority.

---

## Execution

This Agreement shall be deemed adopted upon approval of GP-PRE-1 as a Constitutional Proposal (≥66% YES approval and ≥10% quorum, as defined in DAO Parameters §3.2–3.3). Upon adoption, it shall be executed by the Legal Signatory as authorized by that proposal, and the on-chain governance record of the approving proposal shall constitute the adoption evidence.

---

*This document is maintained in the Radix DAO governance repository. Amendments require a Governance Proposal in accordance with Article X and the Governance Maintenance & Upgrade Framework.*
