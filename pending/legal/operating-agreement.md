# Radix DLT DAO LLC — Operating Agreement

> **Status: Pre-adoption draft — not yet operative.**
>
> This document has not been formally adopted by Governance Proposal. It is the proposed Operating Agreement for Radix DLT DAO LLC, published for transparency and community review. Formal adoption requires a Governance Proposal vote (Governance Process category, ≥60% approval, ≥7% quorum).
>
> Until adopted, governance operations proceed under the Transition Governance Framework and the 10 Phase 1 active documents. The **Certificate of Formation** (`Legal/Formation/Certificate-of-Formation.md`) is the sole operative formation instrument at this time.
>
> Sections marked `[ORIGINAL DRAFT]` reproduce content from the formation document RFC. Sections marked `[AMENDED]` or `[NEW]` reflect changes agreed during framework integration. These markers will be removed upon formal adoption.
>
> Source RFC: https://radixtalk.com/t/rfc-draft-formation-documents-for-marshall-islands-dao-llc/2270

---

## Defined Terms

For the purposes of this Agreement, the following terms have the meanings given below:

**"Agreement"** means this Operating Agreement, as amended from time to time by Governance Proposal.

**"Company"** means Radix DLT DAO LLC, a Marshall Islands Non-Profit DAO LLC.

**"Delegate"** means a Member elected by Governance Proposal to perform one or more Delegated Functions under Article V.

**"Delegated Function"** means any of the five operational functions described in §5.3.

**"Founding Transferor"** means the entity that transferred the initial founding assets to the Company at or following formation, as identified in the Continuity Statement executed under §3.2. The identity of the Founding Transferor is recorded in the Continuity Statement and is not required to be named in this Agreement.

**"Asset Transferor"** or **"Grantor"** means any entity — including the Founding Transferor — that transfers assets or grants funds to the Company under a formal Asset Transfer Agreement or a Governance Proposal approved by the Members.

**"Governance Proposal"** or **"GP"** means a formal governance vote conducted through the Governance smart contract in accordance with the operational policies adopted under §12.4.

**"Member"** means any person or entity that holds governance tokens, in accordance with §4.1.

**"Temperature Check"** or **"TC"** means a preliminary community sentiment poll conducted before a Governance Proposal is elevated.

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

No income, assets, or profits of the Company shall be distributed to Members. All assets and income must be applied solely toward the purposes set out in §2.1 and the operational policies adopted under §12.4. The following are permitted consistent with applicable law and adopted operational policies:

* reasonable and proper remuneration to any Member, Delegate, or service provider for services rendered to the Company;
* interest at a reasonable and proper rate on money lent by any Member or Delegate;
* reasonable and proper rent for premises provided by any Member or Delegate;
* reimbursement of legitimate out-of-pocket expenses properly incurred.

---

## Article III — Continuity

### §3.1 Formation Purpose [AMENDED]

The Company is formed to receive and manage assets — including from the Founding Transferor and subsequent Asset Transferors — in order to continue and support the advancement of decentralized ledger technology consistent with the purposes set forth in Article II.

### §3.2 Continuity Statement Authority [AMENDED]

The Legal Signatories (§5.3(c)) are authorized to execute a standalone continuity statement on behalf of the Company in substantially the form required by the Founding Transferor, or in such other form as a Governance Proposal may approve for any subsequent Asset Transferor. Each executed continuity statement must be publicly recorded.

### §3.3 Received Assets Liability Limitation [NEW]

The Company receives assets from Asset Transferors in good-faith reliance on the representations made by the transferring party. No Member or Delegate shall be personally liable for claims, obligations, or liabilities arising from the nature, title, encumbrances, or defects of assets received from any Asset Transferor, provided that the Member or Delegate acted in good faith and in accordance with this Agreement and applicable Governance Proposals. This limitation applies to the personal liability of Members and Delegates and does not limit the Company's own liability as a legal entity.

---

## Article IV — Membership

### §4.1 Membership Criteria [AMENDED]

Membership is open to any person or entity that holds governance tokens. A person or entity becomes a Member upon acquiring governance tokens. Membership Interests are not independently transferable.

### §4.2 Membership Termination [ORIGINAL DRAFT]

Membership terminates when a Member holds no voting assets (governance tokens or delegated voting power) and has no active votes recorded on the Governance smart contract.

### §4.3 Membership Rights [ORIGINAL DRAFT]

Members exercise governance rights through the Governance smart contract. On-chain governance decisions constitute legally binding decisions of the LLC membership.

### §4.4 No Economic Rights [ORIGINAL DRAFT]

Membership confers governance participation rights only. Members have no economic ownership interest in the Company's assets and no right to share in income, profits, or distributions.

### §4.5 Standard of Conduct — Members [ORIGINAL DRAFT]

Members shall act in good faith and in the best interests of the Radix Network ecosystem per §709 of the DAO Act. No Member has any fiduciary duty to the Company or any other Member beyond the implied contractual covenant of good faith and fair dealing, as permitted by §709 of the Marshall Islands DAO Act.

### §4.6 UBO Compliance

Any Member exceeding 25% of total eligible voting power is classified as an Ultimate Beneficial Owner (UBO) and is subject to mandatory KYC obligations in accordance with the operational policies adopted under §12.4 and the Marshall Islands DAO Act.

### §4.7 Member Liability Limitation [ORIGINAL DRAFT]

No Member is personally liable for the debts, obligations, or liabilities of the Company solely by reason of membership or serving as a Delegate.

---

## Article V — Delegated Functions

### §5.1 Member-Managed Structure [ORIGINAL DRAFT]

The Company does not have managers, directors, officers, or trustees. Management is vested in the Members collectively per §708 of the Marshall Islands DAO Act. Operational functions are performed by Delegates elected by Governance Proposal.

### §5.2 Election of Delegates [ORIGINAL DRAFT]

Delegates (minimum 3, maximum 7 Members) are elected by Governance Proposal. Delegates allocate the Delegated Functions among themselves in accordance with §5.3. All Delegates are subject to KYC verification before assuming their function.

### §5.3 Delegated Functions [ORIGINAL DRAFT]

The following functions are delegated to elected Delegates:

**(a) Treasury Signing**

Execute treasury transactions via multi-signature wallet. Treasury Signers may only sign transactions authorized by a Governance Proposal. In an emergency, Treasury Signers may act to preserve assets or services, subject to GP ratification within 30 days.

**(b) Governance Operations**

Operate the Governance smart contract: elevate approved Temperature Checks to Governance Proposals via the Owner Badge; update governance parameters per GP; maintain the Governance smart contract.

**(c) Legal Signatory**

Sign contracts, continuity statements, and other legal instruments on behalf of the Company, only as authorized by Governance Proposal. Act as the Company's legal representative for entity maintenance and compliance filings. Initiate, pursue, settle, or defend legal proceedings on behalf of the Company as authorized by Governance Proposal; or, in urgent circumstances where a delay of more than 48 hours would cause material and irreversible harm to the Company, take protective legal action subject to GP ratification within 30 days.

**(d) Compliance Liaison**

Act as Registered Agent liaison; file the annual Beneficial Owner Information Report (BOIR); coordinate KYC for Delegates and UBO Members; maintain KYC and sanctions records in accordance with applicable law.

**(e) Web2 Custodian**

Manage social media accounts, GitHub repositories, domain names, and other Web2 assets using an enterprise password manager. The Web2 Custodian may not transfer domain ownership or delete repositories without a Governance Proposal.

### §5.4 Governance Oversight Indemnification [NEW]

The Company shall indemnify any Member performing a DAO-mandated governance oversight function — including but not limited to accountability review, governance process monitoring, emergency governance coordination, and compliance verification — against claims arising from the good-faith performance of that function, on the same terms as §11.3 applies to Delegates. This indemnification applies to oversight functions recognized in the operational policies adopted under §12.4.

### §5.5 Removal and Replacement [AMENDED]

Any Delegate may be removed by Governance Proposal. If a Delegate vacates their function, the remaining Delegates may appoint a temporary replacement from among the Members, subject to GP ratification within 30 days.

**Legal Signatory continuity.** If the Legal Signatory Delegate is unavailable, conflicted, or unresponsive for more than 24 hours in circumstances requiring time-critical legal action, the Compliance Liaison Delegate is authorised to act as interim Legal Signatory for protective or time-critical purposes only. Any action taken under this provision must be disclosed to the governance forum within 24 hours and is subject to GP ratification within 30 days.

### §5.6 Standard of Conduct — Delegates [ORIGINAL DRAFT]

Delegates shall act in good faith with diligence, accountability, and transparency per §709 of the DAO Act and §216 of the Non-Profit Act. Delegates shall disclose conflicts of interest and recuse themselves from decisions where a material conflict exists. No Delegate has any fiduciary duty beyond good faith and the obligations of their assigned Delegated Function, as permitted by §709 of the Marshall Islands DAO Act.

**Primary law obligation.** In performing their Delegated Function, each Delegate's primary legal obligation is to the laws of the Republic of the Marshall Islands and this Agreement. Where a Delegate receives a demand, order, or regulatory inquiry from a foreign jurisdiction that conflicts with a DAO-approved decision or with this Agreement, the Delegate shall seek DAO-authorized legal counsel before compliance and, where legally possible under Marshall Islands law, treat DAO authorization as a condition of compliance. This is an obligation of conduct within the Delegate's assigned function; it does not create a fiduciary duty beyond what is stated in this section. This obligation does not prevent a Delegate from taking protective action necessary to avoid criminal liability, provided they notify RAC immediately in accordance with Legal Wrapper §14A.

---

## Article VI — Governance

### §6.1 On-Chain Governance System

The Company conducts its governance through the on-ledger governance system identified in §1.4 (the "Governance Platform"). The Governance Platform is the authoritative record of all Temperature Checks, Governance Proposals, votes cast, and results determined.

On-chain governance outcomes recorded by the Governance Platform constitute legally binding decisions of the LLC membership under §4.3 of this Agreement and §708 of the Marshall Islands DAO Act.

The Governance Operator (§5.3(b)) administers the Governance Platform using the Owner Badge (§1.4). The Governance Operator acts only within the limits of Governance Proposals and the operational policies adopted under §12.4.

### §6.2 Proposal Process

Governance decisions follow a two-stage process:

**(a) Temperature Check (TC):** A preliminary community sentiment poll submitted to the Governance Platform. The Temperature Check stage allows the community to assess support before a binding vote is opened. Duration, eligibility, and submission requirements are defined in the **Proposal & Voting Framework** (operational policy).

**(b) Governance Proposal (GP):** A formal binding proposal elevated from an approved Temperature Check by the Governance Operator via the Owner Badge. The Governance Proposal constitutes the binding membership decision upon passing. Proposal categories, required content, voting period, and eligibility are defined in the **Proposal & Voting Framework** (operational policy).

The Governance Operator may not elevate a Temperature Check to a Governance Proposal unless the TC has met the approval conditions specified in the Proposal & Voting Framework. The Governance Operator may not modify, delay, or suppress an eligible elevation without a Governance Proposal authorizing the deviation.

### §6.3 Voting Power and Snapshot

Each Member's voting power is determined at a snapshot taken at the start of each Governance Proposal's voting period. Voting power is proportional to eligible token holdings; one token equals one vote.

Eligible holdings and the snapshot methodology — including treatment of Liquid Staking Units (LSUs) and delegated voting power — are defined in the **DAO Parameters Registry §8** (operational policy). Parameters governing eligible assets may be updated by Governance Proposal.

### §6.4 Thresholds and Parameters

All numerical governance parameters — including quorum thresholds by proposal type, approval thresholds by proposal type, voting period durations, review periods, cooldown periods, and veto windows — are defined in the **DAO Parameters Registry** (operational policy).

The DAO Parameters Registry may be updated by Governance Proposal. Updates to governance parameters take effect on the date specified in the amending Governance Proposal, or immediately upon passage if no date is specified, and apply only to proposals submitted after the effective date.

### §6.5 Result Determination and Recording

The RAC (as defined in the operational policies adopted under §12.4) is responsible for formally determining the outcome of each vote and publishing the official result within the window specified in **DAO Parameters §3.5**.

The determination procedure — including quorum verification, approval threshold calculation, winner determination for multi-option votes, and weighted allocation computation — is defined in the **Proposal & Voting Framework §6.5** (operational policy). The on-chain record on the Governance Platform is the authoritative source for raw vote data; the RAC's published result is the authoritative determination of outcome.

A veto challenge mechanism allows token holders to contest results that violate the Charter or governance rules, within the window and conditions defined in **DAO Parameters §4** and the **Proposal & Voting Framework §8** (operational policy).

### §6.6 Smart Contract Changes [ORIGINAL DRAFT]

Changes to the Governance or Treasury smart contracts require:

* (a) an RFC published to the community forum for a minimum 7-day review period
* (b) an independent security audit of the proposed changes
* (c) a Governance Proposal with an enhanced approval threshold as specified in the operational policies

---

## Article VII — Treasury

### §7.1 Multi-Signature Control

The Company's treasury assets are held in the multi-signature account identified in §1.4. All treasury transactions require multi-signature authorization from the Members holding the Treasury Signing function (§5.3(a)).

Signing thresholds are defined in **DAO Parameters §6A**: standard transactions require a minimum of 3-of-5 Treasury Signers; transactions classified as high-risk require 4-of-5. The classification of transaction types and the full operational rules governing treasury execution — including acknowledgement windows, execution windows, and conflict disclosure requirements — are defined in the **Execution & Treasury Actions Policy** and the **Authorized Signers Operational Rules** (operational policies).

Treasury Signers may only execute transactions that have been authorized by a Governance Proposal or that fall within a budget explicitly approved by a prior Governance Proposal. Record-keeping and audit requirements for treasury transactions are defined in the **Execution & Treasury Actions Policy** (operational policy).

### §7.2 Authorized Expenditures [AMENDED]

Treasury expenditures require prior authorization by Governance Proposal, except:

* Routine operational costs within DAO-approved budgets
* Emergency expenditures under §5.3(a) subject to GP ratification within 30 days
* Indemnification payments and expense advancements required under §11.3 and §5.4, subject to GP ratification within 30 days

---

## Article VIII — Compliance

### §8.1 Beneficial Owner Information Report

The Compliance Liaison (§5.3(d)) shall file a Beneficial Owner Information Report (BOIR) with the Registered Agent in accordance with Marshall Islands DAO Act §712 and Non-Profit Entities Act §218:

* **Initial BOIR:** at formation
* **Annual BOIR:** between January 1 and March 31 of each calendar year
* **Updated BOIR:** within 30 days of any material change in beneficial ownership or the Delegate roster

The BOIR must identify all Delegates (who qualify as beneficial owners by virtue of actual control under DAO Act §702(r)) and any Member holding 25% or more of eligible voting power (UBO threshold). The procedure, required fields, and declaration requirements are defined in the **BOIR Template** maintained in the governance repository.

### §8.2 KYC Maintenance

KYC verification is required for all persons reportable under §8.1, in two tiers:

* **KYC Tier 1 (Delegate KYC):** All Delegates must complete KYC verification through the DAO's designated KYC provider before assuming any Delegated Function. Annual reverification is required each January per MIDAO requirements.
* **KYC Tier 2 (UBO KYC):** Any Member reaching the 25% UBO threshold must complete KYC within 14 days of crossing the threshold and notify the Compliance Liaison. Annual reverification applies.

Thresholds, KYC provider selection, and the full UBO monitoring obligations of the Compliance Liaison are defined in **Legal Wrapper §7A** and **DAO Parameters §8** (operational policies). The Compliance Liaison maintains KYC records confidentially with the Registered Agent in accordance with Marshall Islands law.

### §8.3 Sanctions Screening

The Compliance Liaison shall instruct the DAO's KYC provider to cross-check all KYC applicants against applicable sanctions records before verification is granted. A sanctioned individual may not hold a Delegated Function or receive compensation from the Company. Sanctions enforcement, including identity-bound sanctions for KYC-verified persons, is governed by the **Code of Conduct** (operational policy).

### §8.4 Entity Standing

The Compliance Liaison is responsible for maintaining the Company's good standing with the Registered Agent, including:

* annual entity filings per Non-Profit Entities Act §218
* payment of Registered Agent fees
* updating the Registered Agent record when smart contract identifiers change (§1.4)
* ensuring the BOIR on file with the Registered Agent is current at all times

Failure to maintain entity standing is a material governance failure and must be reported to the Members via the governance forum within 48 hours of the Compliance Liaison becoming aware of the issue.

---

## Article IX — Dissolution

### §9.1 Dissolution Events [ORIGINAL DRAFT]

The Company shall be dissolved upon:

* (a) a Governance Proposal with ≥80% approval and ≥20% quorum of Members
* (b) expiry of term, if any
* (c) events specified in the smart contracts or this Agreement
* (d) a Registrar order if the Company is no longer lawful or no longer under natural person control
* (e) voluntary resignation of all Members

### §9.2 Asset Disposition on Dissolution [AMENDED]

On dissolution, the Company's remaining assets shall not be distributed to Members. Remaining assets shall be transferred to a successor entity approved by Governance Proposal. A successor entity qualifies only if it meets all of the following criteria:

* **(a)** it is organized on a non-profit or non-distribution basis under applicable law, such that its assets cannot be distributed to its own members for personal gain
* **(b)** it operates primarily in the domain of decentralized ledger technology, open-source cryptographic protocols, or substantially equivalent blockchain infrastructure
* **(c)** it maintains a non-distribution principle that prevents its members from extracting assets for personal benefit
* **(d)** it commits to applying received assets toward ecosystem development, open-source software, public education, or equivalent public-benefit activities consistent with the purposes in Article II
* **(e)** it is approved by a Governance Proposal with ≥80% approval and ≥20% quorum

Prior to executing any asset transfer upon dissolution, the Legal Signatories shall provide written notice to any primary Asset Transferor that contributed material assets to the Company, giving that party 30 days to submit written comment to the governance forum. Such comments shall be published and available to Members before the dissolution GP vote concludes. Asset Transferors have no veto right; this notification obligation is a transparency measure only.

The Legal Signatories shall execute a statement of dissolution in the prescribed form upon completion of the asset transfer.

### §9.3 Asset Provenance Record [NEW]

Prior to any dissolution asset transfer, the Company shall publish a public accounting of all assets held, their provenance (including all assets received from any Asset Transferor), and their proposed disposition. This record must be published to the governance forum before the dissolution GP vote concludes.

---

## Article X — Amendments

### §10.1 Standard Amendment Process

This Agreement may be amended by Governance Proposal. Amendments are classified as follows:

**(a) Constitutional Amendments** — changes to Articles I (Formation), II (Purpose), III (Continuity), IV (Membership), or XI (Disputes and Liability), and changes to the Charter. Constitutional Amendments require a Constitutional Proposal with ≥66% YES approval and ≥10% quorum, as defined in **DAO Parameters §3.2–3.3**.

**(b) Governance Amendments** — changes to Articles V (Delegated Functions) through XII (General Provisions). Governance Amendments require a Governance Process Proposal with ≥60% YES approval and ≥7% quorum, as defined in **DAO Parameters §3.2–3.3**.

The classification of any proposed amendment and the document versioning requirements are governed by the **Governance Maintenance & Upgrade Framework** (operational policy). In case of conflict between this Article and the Governance Maintenance & Upgrade Framework on questions of classification, this Article prevails.

### §10.2 Amendment Record

The Governance Operator shall record each amendment to this Agreement with:

* the amended section(s)
* the new text
* the version number (incremented per the Governance Maintenance & Upgrade Framework)
* the date of effect
* the Governance Proposal number authorizing the amendment

All amendment records are maintained in the governance repository and are publicly accessible. The version of this Agreement in effect at any given time is the version whose effective date is most recent as of that date.

### §10.3 Emergency Amendments [ORIGINAL DRAFT]

Emergency amendments to this Agreement may be adopted by unanimous written consent of the Delegates, subject to ratification by Governance Proposal within 30 days. Emergency amendments that are not ratified within 30 days are void and of no effect.

---

## Article XI — Disputes and Liability

### §11.1 Dispute Resolution [ORIGINAL DRAFT]

Disputes shall first be referred to the Compliance Liaison for mediation. If unresolved within 30 days, the Compliance Liaison may raise a Governance Proposal directly for the Members to decide, bypassing the Temperature Check stage. If any party is not satisfied with the GP outcome, or if the dispute is not suitable for community vote, it shall be settled by binding arbitration under the International Arbitration Rules of the ICDR (International Centre for Dispute Resolution), seated in the Republic of the Marshall Islands, conducted in English, by a sole arbitrator.

### §11.2 Governing Law [ORIGINAL DRAFT]

This Agreement is governed by the laws of the Republic of the Marshall Islands.

### §11.3 Liability and Indemnification [AMENDED]

**Limitation of Liability.** No Member or Delegate is personally liable for the debts, obligations, or liabilities of the Company solely by reason of membership or service, or for acts of the smart contracts executed as authorized by this Agreement.

**Indemnification.** To the fullest extent permitted by applicable law, the Company shall indemnify, defend, and hold harmless each Delegate and each Member performing a DAO-mandated governance oversight function (including RAC members acting within their mandate) against any claims, liabilities, damages, losses, costs, and expenses (including reasonable legal fees) arising from or relating to the good-faith performance of their Delegated Function or governance oversight role.

**Advancement of Expenses.** The Company shall advance reasonable legal expenses to any Delegate or RAC member who is a party or threatened to be a party to any proceeding arising from their role, provided that the recipient undertakes in writing to repay such amounts if it is ultimately determined by final adjudication that they are not entitled to indemnification under this section. Such advancement does not require prior Governance Proposal authorization; Treasury Signers are authorized to execute advancement payments directly, subject to GP ratification within 30 days and the repayment undertaking required by this section.

**Exclusions.** Indemnification and expense advancement under this section do not apply to claims arising from: (a) gross negligence; (b) willful misconduct; (c) fraud; (d) breach of the duty of loyalty to the Company; or (e) knowing violation of applicable law.

**Scope.** This section does not limit any additional protections available to Members or Delegates under Marshall Islands law or any insurance policy maintained by the Company.

---

## Article XII — General Provisions

### §12.1 Notices

Written notice posted to the DAO's designated governance forum constitutes valid and sufficient notice for all internal governance matters under this Agreement, including proposals, disclosures, and regulatory announcements to Members.

Legal notices to the Company (including service of process, regulatory correspondence, and formal demands) must be served at the address of the Registered Agent identified in §1.2. The Compliance Liaison shall forward any such notice to the Delegates and publish notice of receipt to the governance forum within 48 hours.

### §12.2 Severability

If any provision of this Agreement is held to be invalid, illegal, or unenforceable under applicable law, that provision shall be modified to the minimum extent necessary to make it valid and enforceable, or if modification is not possible, it shall be severed from this Agreement. The validity and enforceability of the remaining provisions shall not be affected.

### §12.3 Entire Agreement

This Agreement, together with the operational policies adopted by the Members under §12.4, constitutes the entire agreement of the Members with respect to the governance, operation, and management of the Company. It supersedes all prior agreements, representations, or understandings relating to the same subject matter. In the event of conflict between this Agreement and any operational policy adopted under §12.4, this Agreement prevails.

### §12.4 Operational Policies [ORIGINAL DRAFT]

The Members may, by Governance Proposal, adopt operational policies, procedures, and guidelines that supplement this Agreement. Such documents are subordinate to this Agreement and may be amended or revoked by Governance Proposal. The governance framework documents adopted as operational policies are listed in the most recent Governance Proposal activating them.

---

## Execution

This Agreement shall be deemed adopted upon approval by the required Governance Proposal (Governance Process category, ≥60% approval, ≥7% quorum). Upon adoption, it shall be executed by the Legal Signatories as authorized by that proposal, and the on-chain governance record of the approving proposal shall constitute the adoption evidence.

*This section is prospective. As of the current repository state, the adoption Governance Proposal has not yet been passed. See the status header at the top of this document.*

---

*This document is maintained in the Radix DAO governance repository. Amendments require a Governance Proposal in accordance with Article X and the Governance Maintenance & Upgrade Framework.*
