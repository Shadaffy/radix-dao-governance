# Radix DAO Delegate Mandate

> **Scope of this document.** This Mandate is the primary definition of the **Delegates** of the
> Company and the **Delegated Functions** they perform — the DAO's operational execution roles.
> It sits alongside the **RAC Mandate**, which governs the DAO's governance-process oversight body.
> The Delegated Functions are operational and delegated functions established under **Operating
> Agreement §11.5**. They confer legal Membership and beneficial-owner status; the legal force of
> those consequences is located in the **Charter** (§4.2, Membership attachment) and the **Operating
> Agreement** (delegated functions §11.5, indemnification §12.5, the DAO Act §109 standard-of-conduct
> disclaimer in §12.7, and beneficial-owner reporting under Article X). This Mandate defines the roles
> and their operational rules; the legal instruments give them legal effect.

## 1. Purpose

Delegates perform the Company's defined operational functions on behalf of the DAO. They are
**execution agents, not decision-makers**: their authority is limited to carrying out validly
authorized decisions of the Company and to the specific operational scope of the Delegated Function
they hold. Under the Operating Agreement, binding community governance outcomes take legal effect from
the **Activation Date** (**Operating Agreement §5.7**); during the **Advisory Governance Period** the
Company is **member-managed** and authorized decisions are made by the Transition RAC within its
formation mandate (**Operating Agreement Article VI**), while community governance outcomes are
advisory (**§§5.8–5.9**).

The Company is member-managed during the Transition Period and becomes Algorithmically Governed on the
Activation Date (**Operating Agreement §§8.1, 8.8**), after which binding governance authority is
exercised by Governance Participants through the Governance Mechanism. In neither phase do Delegates
govern — they execute.

---

## 2. The Delegated Functions

There are five Delegated Functions. Each is defined below by its scope and authority; the detailed
operational procedure for each lives in the specialized policy cross-referenced under the function.

A single Delegate may hold more than one Delegated Function where the combination does not create a
structural conflict; the safeguards for specific combinations are governed by the **Conflict of
Interest Policy §3.5** (Delegated Function Consolidation). For the role-concentration cap in **DAO
Parameters §6B**, a Delegate counts as **one seat** regardless of how many functions the Delegate
holds.

### 2.1 Treasury Signing

Execute treasury transactions via the multi-signature account. Treasury Signers may only sign
transactions authorized by a Governance Proposal or falling within a budget previously approved by
Governance Proposal. In an emergency, Treasury Signers may act to preserve assets or services,
subject to Governance Proposal ratification within the period specified in the **Emergency &
Safeguards Policy §10**.

The Treasury Signing function must be held by **exactly five Delegates** to support the signing
thresholds in **DAO Parameters §6A** (3-of-5 standard; 4-of-5 high-risk). The comprehensive
operational rules — refusal grounds, custody standards, availability, emergency actions, and breach
of duty — are defined in the **Treasury Signers Rules**.

### 2.2 Governance Operations

Operate the Governance smart contract: elevate approved Temperature Checks to Governance Proposals
via the Owner Badge; update governance parameters per Governance Proposal; maintain the Governance
smart contract. The Governance Operator may not elevate a Temperature Check that has not met the
approval conditions, and may not modify, delay, or suppress an eligible elevation without a
Governance Proposal authorizing the deviation. Elevation and proposal-administration procedure is
defined in the **Proposal & Voting Framework**. The Governance Operator must elevate an eligible
passed Temperature Check within the TC Elevation Window (**DAO Parameters §3.1**) or record
documented grounds for the delay with the RAC; an eligible TC left unelevated beyond that window
triggers the elevation backstop in the **Governance Continuity Framework §4.2A**. The custody and
recovery arrangement for the Owner Badge is determined at deployment of the Governance smart
contract and recorded in the **On-Chain Identifiers & Verification Policy §3** (per **Operating Agreement §11.4 / Schedule 4**);
whatever arrangement is chosen must enable an elevation or badge rotation to proceed without the
Governance Operator's cooperation, sufficient to give effect to that backstop.

**Veto Filing Channel.** The Governance Operator holds the primary Veto Filing Channel address
recorded in the **On-Chain Identifiers & Verification Policy §3**, monitors it, and publishes every
filing received verbatim to the Official Venue with its receipt timestamp within the Channel
Publication Window (**DAO Parameters §4**). The Governance Operator may not filter, withhold, delay,
or edit a filing. Failure to publish does not invalidate the filing (**Proposal & Voting Framework
§8.4**) and is a breach of the standard of conduct in §4. Where the Governance Operator is unavailable, or is the
subject of a filing, the RAC publishes from the copy address.

### 2.3 Legal Signatory

Sign contracts, continuity statements, and other legal instruments on behalf of the Company, only as
authorized by Governance Proposal. Act as the Company's legal representative for entity maintenance
and compliance filings. Initiate, pursue, settle, or defend legal proceedings as authorized by
Governance Proposal; or, in urgent circumstances where a delay of more than 48 hours would cause
material and irreversible harm to the Company, take protective legal action subject to Governance
Proposal ratification within 30 days. Regulatory-demand handling is governed by the **Compliance
Operations Policy §5**. The Legal Signatory Delegated Function is the Legal Signatory recognised in
**Operating Agreement §1.15 and §9.2**, and acts only within the authority conferred by the Operating
Agreement, the Charter, and a valid governance decision.

### 2.4 Compliance Liaison

Act as Registered Agent liaison; file the annual Beneficial Owner Information Report (BOIR);
coordinate KYC for Delegates, RAC members, and UBO Governance Participants; maintain KYC and
sanctions records in accordance with applicable law; and maintain the Company's good standing with
the Registered Agent. UBO identification, threshold monitoring, BOIR onboarding, and confidentiality
procedures are defined in the **Compliance Operations Policy §2**.

### 2.5 Web2 Custodian

Manage social media accounts, source-code repositories, domain names, and other Web2 assets using an
enterprise password manager. The Web2 Custodian may not transfer domain ownership or delete
repositories without a Governance Proposal. Credential and Web2 asset security standards are defined
in the **Compliance Operations Policy §4**.

---

## 3. Composition & Election

* Delegates are elected by Governance Proposal in accordance with the **Elections & Role Governance
  Policy**, which governs eligibility, nomination, and election procedure.
* The minimum and maximum number of Delegates are defined in **DAO Parameters §6B**. The minimum may
  not fall below the number required to staff the Treasury Signing roster (exactly five Delegates
  hold Treasury Signing). Where the total Delegate count exceeds five, the additional Delegates hold
  non-Treasury functions only.
* The Governance Proposal establishing or modifying the Delegate roster must identify which five
  Delegates hold Treasury Signing and how the non-Treasury functions are allocated.
* All Delegates are subject to KYC verification before assuming their function (**Operating
  Agreement §10.4**).
* A Delegate may simultaneously hold a Permanent RAC seat. Where the DAO is operating at small
  scale, holding both is expected and constitutes the default model; as the DAO grows and additional
  capacity becomes available, separation between RAC oversight and Delegate execution is preferred.
  Both configurations are valid and the choice is made by Governance Proposal when the Delegate
  roster is established. The role-concentration limits in **DAO Parameters §6B** and the recusal
  obligations of the **Conflict of Interest Policy** apply in either configuration.

---

## 4. Standard of Conduct

Delegates shall act in good faith with diligence, accountability, and transparency. Delegates shall
disclose conflicts of interest and recuse themselves from decisions where a material conflict exists,
in accordance with the **Conflict of Interest Policy**.

**Primary law obligation.** In performing their Delegated Function, each Delegate's primary legal
obligation is to the laws of the Republic of the Marshall Islands and the Operating Agreement. Where
a Delegate receives a demand, order, or regulatory inquiry from a foreign jurisdiction that conflicts
with a DAO-approved decision or with the Operating Agreement, the Delegate shall seek DAO-authorized
legal counsel before compliance and, where legally possible under Marshall Islands law, treat DAO
authorization as a condition of compliance. This does not prevent a Delegate from taking protective
action necessary to avoid criminal liability, provided they notify the RAC immediately in accordance
with the Regulatory Demand Disclosure Protocol in the **Compliance Operations Policy §5**.

The fiduciary-duty standard and disclaimer applicable to Delegates (adopted under §109 of the Marshall
Islands DAO Act 2022) is set in **Operating Agreement §12.7** and is not restated
here; this Mandate states obligations of conduct within each Delegate's assigned function and does not
create any fiduciary duty beyond what the Operating Agreement provides. Delegates are Covered Persons
for the purposes of Operating Agreement §12.7 and the indemnification in §12.5.

---

## 5. Removal & Replacement

* Any Delegate may be removed by Governance Proposal at any time.
* If a Delegate vacates their function, the remaining Delegates may appoint a temporary replacement
  from among eligible Governance Participants to provide interim coverage pending the formal
  replacement election conducted under the **Elections & Role Governance Policy §11**. Interim
  appointments are subject to Governance Proposal ratification within 30 days and terminate
  automatically upon the elected successor taking up their seat.
* Where a vacancy creates an immediate operational risk (for example, Treasury Signers falling below
  execution quorum), the **Governance Continuity Framework §4.2** governs interim coverage and
  prevails over this section.

**Legal Signatory continuity.** If the Legal Signatory is unavailable, conflicted, or unresponsive
for more than 24 hours in circumstances requiring time-critical legal action, the Compliance Liaison
is authorised to act as interim Legal Signatory for protective or time-critical purposes only. Any
action taken under this provision must be disclosed to the governance forum within 24 hours and is
subject to Governance Proposal ratification within 30 days.

---

## 6. Membership & Legal Status

Upon election and following the Transition Period, Delegates are admitted to legal Membership of the
Company. Membership is attached to the Delegated Functions under the **Charter** and given legal
effect by the **Operating Agreement**; this Mandate does not itself confer Membership.

Delegates qualify as beneficial owners of the Company by virtue of actual control (Marshall Islands
DAO Act §702(r)) and are reportable on the BOIR regardless of where their function is defined. BOIR
identification, KYC tiers, and sanctions screening are governed by the **Operating Agreement**
compliance article and the **Compliance Operations Policy**.

During the Transition Period, the Treasury Signing function is held by the three Transition RAC
members, who act as the initial signers in respect of that function (**2-of-3** standard;
protected/high-risk matters require **unanimity of all seated signers, being not fewer than two**)
as set out in **Operating Agreement Article VI and §§9.10–9.11**. The
**exactly-five-Delegates** requirement and the 3-of-5 / 4-of-5 thresholds in §3 above take effect on
the Activation Date, when Treasury Signing passes to the elected Delegates. Article VI-specific
procedures prevail over the corresponding procedures in this Mandate during the Transition Period.

---

## 7. Relationship to the DAO

Delegates operate **on behalf of the DAO** and remain fully subordinate to:

* Governance Participant authority exercised through the Governance Mechanism — advisory during the
  Advisory Governance Period and binding from the Activation Date (**Operating Agreement §§5.7–5.9**);
* approved governance processes; and
* the Charter, the Operating Agreement, and this Mandate.

A Delegate may not exercise authority outside the operational scope of their Delegated Function, and
may not expand that authority of their own accord. Indemnification for the good-faith performance of
a Delegated Function is provided under the **Operating Agreement**.

---

## 8. Amendments

This Mandate is an operational policy and may be amended by Governance Process Proposal. Amendment
procedures, classification, and document versioning are defined in the **Governance Maintenance &
Upgrade Framework**.
