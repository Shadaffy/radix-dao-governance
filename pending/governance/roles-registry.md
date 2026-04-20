# Roles Registry

---

## Purpose

This document is a **navigation aid**, not a source of rules. It maps every governance role to the documents that define it, govern it, and apply to it — so that any participant can quickly find what applies to them or any other role without reading the entire framework.

All definitions, authority limits, and obligations remain in their source documents. Where this registry and a source document differ, the source document prevails.

---

## 1. Quick-Reference Table

| Role | Defined In | Appointed By | Term | Primary Policy Documents |
|------|-----------|--------------|------|--------------------------|
| **Token Holders** | OA §4; Charter §4.1 | Token acquisition | Indefinite | Charter; Proposal & Voting Framework §6–8; DAO Parameters §8 |
| **RAC Members** | RAC Mandate; OA §6.5; Charter §8 | DAO Election Proposal | 6 months (§6B) | RAC Mandate; Emergency Policy §5–6; CoI Policy §8 |
| **Delegates — Treasury Signers** | Treasury Signers Rules; OA §5.3(a) | DAO Election Proposal | 6 months (§6B) | Treasury Signers Rules; Execution Policy §5.3; DAO Parameters §6A |
| **Delegate — Governance Operator** | OA §5.3(b) | DAO Election Proposal | 6 months (§6B) | OA Art V; Proposal & Voting Framework; DAO Parameters §3–3.5 |
| **Delegate — Legal Signatory** | OA §5.3(c); Legal Wrapper §7–8 | DAO Election Proposal | 6 months (§6B) | OA §5.3(c), §5.5; Legal Wrapper §7–8 |
| **Delegate — Compliance Liaison** | OA §5.3(d), §8; Legal Wrapper §3 | DAO Election Proposal | 6 months (§6B) | OA §8; Legal Wrapper §3 |
| **Delegate — Web2 Custodian** | OA §5.3(e) | DAO Election Proposal | 6 months (§6B) | OA §5.3(e) |
| **WG Stewards** | DAO Parameters §7; Proposal & Voting Framework §4.6 | DAO Election Proposal (per WG Charter) | 6 months (§7) | Respective WG Charter; Execution Policy §5.2; CoI Policy §2 |
| **Contributors / Contractors** | Execution Policy §7.3–7.4; Code of Conduct §3.3 | Working Group or RAC (interim) | Per engagement | Code of Conduct §3.3; Execution Policy §7 |

*OA = Operating Agreement; CoI Policy = Conflict of Interest Policy; Emergency Policy = Emergency & Safeguards Policy*

---

## 2. Role Profiles

---

### 2.1 Token Holders (Members)

**Authority & Scope**
Token holders are the ultimate decision-making authority of the DAO. They submit and vote on all governance proposals, may file veto challenges, and can remove any elected role-holder by vote. They hold no economic ownership in DAO assets.

**Defined In**
- Operating Agreement §4 (membership criteria, rights, termination)
- Charter §4.1 (token holder sovereignty)

**Appointment**
Automatic upon acquiring governance tokens. No registration or approval required (Charter §4.1; Proposal & Voting Framework §2.5).

**Term & Renewal**
Indefinite — continues while holding governance tokens (OA §4.2).

**Removal**
Membership terminates automatically when no governance tokens are held (OA §4.2).

**Policies That Apply**
- Charter — constitutional authority and principles
- Proposal & Voting Framework §6–8 — voting mechanics, veto mechanism
- DAO Parameters §8 — voting power basis (XRD and LSU-equivalent)
- DAO Parameters §4 — veto window and participation threshold
- Legal Wrapper §3 — UBO KYC obligation if holding >25% of eligible voting power
- Code of Conduct §3 — behavioral standards for all participants

**Conflict of Interest & Disclosure**
Token holders exercising ordinary voting rights are **not** subject to mandatory disclosure or recusal under the Conflict of Interest Policy (CoI Policy §2; Charter §8). They are encouraged to act in the DAO's best interest. If a token holder also holds a formal role (e.g., RAC member), the obligations of that role apply.

---

### 2.2 Accountability Council (RAC) Members

**Authority & Scope**
The RAC is the guardian of governance process — not a decision-making authority. It may: verify proposal compliance, formally determine vote outcomes, trigger emergency procedures, flag violations, instruct signers to execute under the forced-execution backstop, and receive regulatory escalations. It may not override valid DAO votes, make unilateral strategic decisions, or block proposals without grounds (RAC Mandate §3–4; Charter §12.1).

**Defined In**
- RAC Mandate §1–11 (primary definition, authority, limitations)
- Operating Agreement §6.5 (result determination role)
- Charter §8 (governance integrity function; RAC is not a Delegate body)

**Appointment**
Two-stage Election Proposal process (Proposal & Voting Framework §4.6): Stage 1 shortlisting by Approval Voting, Stage 2 confirmation by standard vote. Founding RAC appointed as part of GP-PRE-1.

**Term & Renewal**
6 months (DAO Parameters §5.1). Auto-renewed unless a challenge is filed during the challenge window (DAO Parameters §6B). Maximum 4 consecutive terms in the same role (DAO Parameters §6B).

**Removal**
DAO vote at any time (RAC Mandate §9). Emergency suspension possible under Emergency & Safeguards Policy procedures. Selective obstruction constitutes misconduct independent of inactivity (RAC Mandate §11A).

**Policies That Apply**
- RAC Mandate — primary authority, limitations, emergency powers, accountability
- Emergency & Safeguards Policy §5–6 — RAC emergency authority and thresholds
- Proposal & Voting Framework §6.5 — result determination procedure
- DAO Parameters §5.1 — composition (minimum 5 members, 6-month term)
- DAO Parameters §5.2 — emergency thresholds (≥2/3 quorum, ≥75% approval)
- DAO Parameters §6B — term, renewal, removal thresholds
- Conflict of Interest Policy §8 — heightened obligations for RAC members
- Code of Conduct §3–6 — behavioral standards
- Legal Wrapper §8 — regulatory demand disclosure obligations
- Transition Governance Framework §4–6 — transitional authority during Phase 1

**Conflict of Interest & Disclosure**
Subject to heightened obligations (CoI Policy §8):
- Must submit a Conflicts Disclosure Statement upon appointment (CoI Policy §4.1)
- Must update disclosure within 14 days of any material change (CoI Policy §4.2)
- Must declare transaction-level conflicts before each relevant determination (CoI Policy §4.3)
- Must recuse from any matter where they have a material conflict (CoI Policy §5)
- If a majority of RAC members are conflicted on a matter, it escalates to community governance vote (CoI Policy §8)

---

### 2.3 Delegates — Treasury Signers

**Authority & Scope**
Treasury Signers execute treasury transactions approved by governance. They are execution agents, not decision-makers. They operate a 3-of-5 multisig (4-of-5 for high-risk transactions). They may refuse or delay execution only on the specific grounds defined in Treasury Signers Rules §9. They may take protective emergency actions when triggered under the Emergency Policy (Treasury Signers Rules §17).

**Defined In**
- Treasury Signers Rules §1–20 (primary definition and operational rules)
- Operating Agreement §5.3(a) (Treasury Signing delegated function)
- Charter §4.3 (binding decisions executed through Treasury Signers)

**Appointment**
Two-stage Election Proposal process (Proposal & Voting Framework §4.6). Exactly 5 signers must be elected to support signing thresholds (OA §5.2; DAO Parameters §6A). KYC required before assuming function.

**Term & Renewal**
6 months (DAO Parameters §6A, §6B). Auto-renewed unless challenged. Maximum 4 consecutive terms (DAO Parameters §6B).

**Removal**
DAO vote at any time (Treasury Signers Rules §7). Immediate emergency suspension may occur for: key compromise, credibly alleged misconduct, or unavailability that threatens operations (Treasury Signers Rules §7). Inactivity threshold: 21 days without excused absence (DAO Parameters §6B).

**Policies That Apply**
- Treasury Signers Rules — comprehensive operational rules (refusal grounds §9, availability §15, emergency actions §17, breach of duty §18)
- Execution & Treasury Actions Policy §5.3 — role in treasury execution; refusal authority references Treasury Signers Rules §9
- DAO Parameters §6A — signing thresholds (3-of-5 standard, 4-of-5 high-risk), execution windows, availability standards
- DAO Parameters §6B — term, renewal, removal, inactivity thresholds
- DAO Parameters §9 — pre-execution hold requirements
- Emergency & Safeguards Policy §5.1, §8 — emergency execution authority
- Conflict of Interest Policy §2–4 — disclosure and recusal obligations
- Code of Conduct §3–6 — behavioral standards
- Legal Wrapper — KYC requirement before assuming function (OA §5.2, §8.2)
- Operating Agreement §11.3 — indemnification (see also Treasury Signers Rules §19A)

**Conflict of Interest & Disclosure**
Subject to CoI Policy §2–4. In addition, an execution-specific rule applies: a signer must not approve execution of a payment or agreement that directly benefits them; they must recuse, disclose, and ensure another signer executes (Treasury Signers Rules §14).

---

### 2.4 Delegates — Governance Operator

**Authority & Scope**
Operates the Governance smart contract: elevates approved Temperature Checks to Governance Proposals via the Owner Badge; updates governance parameters per DAO vote; maintains the Governance smart contract. May not elevate a TC that has not met approval conditions, and may not modify, delay, or suppress an eligible elevation without a Governance Proposal (OA §6.2).

**Defined In**
- Operating Agreement §5.3(b)

**Appointment**
DAO Election Proposal (OA §5.2). One of the 5 Treasury Signing Delegates, or an additional Delegate (up to 7 total). KYC required before assuming function (OA §5.2, §8.2).

**Term & Renewal**
6 months (DAO Parameters §6B). Auto-renewed unless challenged. Maximum 4 consecutive terms.

**Removal**
DAO vote at any time (OA §5.5).

**Policies That Apply**
- Operating Agreement Art V — Delegate structure, standard of conduct (§5.6), removal (§5.5)
- Proposal & Voting Framework — TC elevation, GP administration
- DAO Parameters §3–3.5 — governance parameter values maintained by this role
- Conflict of Interest Policy §2–4 — disclosure and recusal obligations
- Code of Conduct §3–6 — behavioral standards

**Conflict of Interest & Disclosure**
Subject to CoI Policy §2–4 and OA §5.6 (standard of conduct for Delegates: good faith, diligence, conflict disclosure, recusal where material conflict exists).

---

### 2.5 Delegates — Legal Signatory

**Authority & Scope**
Signs contracts, continuity statements, and legal instruments as authorized by Governance Proposal. Acts as the Company's legal representative for entity maintenance and compliance filings. May initiate or defend legal proceedings as authorized by GP, or take protective legal action in urgent circumstances (delay >48 hours would cause irreversible harm) subject to GP ratification. If unavailable, the Compliance Liaison may act as interim Legal Signatory for protective actions only (OA §5.5).

**Defined In**
- Operating Agreement §5.3(c) (Delegated Function definition)
- Legal Wrapper §7 (continuity statement authority)
- Legal Wrapper §8 (regulatory demand disclosure obligations)

**Appointment**
DAO Election Proposal (OA §5.2). KYC required.

**Term & Renewal**
6 months (DAO Parameters §6B). Auto-renewed unless challenged. Maximum 4 consecutive terms.

**Removal**
DAO vote at any time (OA §5.5).

**Policies That Apply**
- Operating Agreement §5.3(c) — Delegated Function scope
- Operating Agreement §5.5 — continuity rules (interim Legal Signatory; 24-hour disclosure requirement)
- Legal Wrapper §7 — continuity statement authority and dissolution notice obligation (see OA §9.2–9.3)
- Legal Wrapper §8 — regulatory demand disclosure protocol (notify RAC within 24 hours)
- Conflict of Interest Policy §2–4 — disclosure and recusal obligations
- Code of Conduct §3–6 — behavioral standards

**Conflict of Interest & Disclosure**
Subject to CoI Policy §2–4 and OA §5.6.

---

### 2.6 Delegates — Compliance Liaison

**Authority & Scope**
Acts as Registered Agent liaison. Files the annual Beneficial Owner Information Report (BOIR). Coordinates KYC for Delegates and UBO Members. Maintains KYC and sanctions records confidentially with the Registered Agent. Monitors on-chain voting power to identify UBOs approaching the 25% threshold (Legal Wrapper §3.2). If unavailable or the source of a compliance failure, the Legal Signatory assumes the reporting obligation (OA §8.4).

**Defined In**
- Operating Agreement §5.3(d) (Delegated Function definition)
- Operating Agreement §8.1–8.4 (BOIR filing, KYC, sanctions screening, entity standing)
- Legal Wrapper §3 (UBO identification, threshold monitoring, confidentiality)

**Appointment**
DAO Election Proposal (OA §5.2). KYC required.

**Term & Renewal**
6 months (DAO Parameters §6B). Auto-renewed unless challenged. Maximum 4 consecutive terms.

**Removal**
DAO vote at any time (OA §5.5).

**Policies That Apply**
- Operating Agreement §5.3(d), §8.1–8.4 — BOIR (initial, annual, updated), KYC tiers, sanctions screening, entity standing obligations
- Legal Wrapper §3 — UBO identification, threshold monitoring, BOIR timeline, confidentiality rules
- DAO Parameters §8 — UBO threshold (>25% of eligible voting power)
- Conflict of Interest Policy §2–4 — disclosure and recusal obligations
- Code of Conduct §3–6 — behavioral standards

**Conflict of Interest & Disclosure**
Subject to CoI Policy §2–4 and OA §5.6.

---

### 2.7 Delegates — Web2 Custodian

**Authority & Scope**
Manages social media accounts, GitHub repositories, domain names, and other Web2 assets using an enterprise password manager. May not transfer domain ownership or delete repositories without a Governance Proposal (OA §5.3(e)).

**Defined In**
- Operating Agreement §5.3(e)

**Appointment**
DAO Election Proposal (OA §5.2). KYC required.

**Term & Renewal**
6 months (DAO Parameters §6B). Auto-renewed unless challenged. Maximum 4 consecutive terms.

**Removal**
DAO vote at any time (OA §5.5).

**Policies That Apply**
- Operating Agreement §5.3(e) — scope and constraints of the function
- Conflict of Interest Policy §2–4 — disclosure and recusal obligations
- Code of Conduct §3–6 — behavioral standards

**Conflict of Interest & Disclosure**
Subject to CoI Policy §2–4 and OA §5.6.

---

### 2.8 Working Group Stewards *(Phase 2 activation-triggered)*

**Authority & Scope**
Lead operational Working Groups within the scope and budget approved by their WG Charter. Coordinate WG members, manage deliverables, authorize milestone payments to Treasury Signers, and report monthly to the DAO. May not make strategic decisions outside the approved WG mandate.

**Defined In**
- DAO Parameters §7 (WG parameters: 2–3 stewards per WG, 6-month terms)
- Proposal & Voting Framework §4.6 (election process for WG Stewards)
- Charter §4.2 (Working Groups as delegated bodies)
- Respective WG Charter (primary operational authority, once adopted)

**Appointment**
DAO Election Proposal (Proposal & Voting Framework §4.6), per each WG Charter. WG Charters are Phase 2 activity-triggered (Transition Framework §3.2).

**Term & Renewal**
6 months (DAO Parameters §7). Renewal per the Elections & Role Governance Policy (Phase 2 activation-triggered). Maximum 4 consecutive terms (DAO Parameters §6B).

**Removal**
DAO vote. Specific procedure defined in the applicable WG Charter and Elections & Role Governance Policy (Phase 2 activation-triggered).

**Policies That Apply**
- Respective WG Charter — primary mandate, authority, and accountability (when adopted)
- Execution & Treasury Actions Policy §5.2 — WG execution role; budget management
- Conflict of Interest Policy §2, §3.2, §3.4 — WG Stewards with budget authority are covered persons; simultaneous role conflicts (e.g., Steward + grant applicant to own WG) must be disclosed
- Code of Conduct §3–6 — behavioral standards
- Transition Governance Framework §5.4 — RAC holds interim WG authority during Phase 1

**Conflict of Interest & Disclosure**
Subject to CoI Policy §2–4 as covered persons with budget and execution authority. Simultaneous role conflicts (CoI Policy §3.4) require particular attention.

> **Note:** WG Charters for the Strategic Coordination WG and Governance & Legal WG are Phase 2 activation-triggered (Transition Framework §3.2). This registry entry will be extended when those charters are adopted by governance vote.

---

### 2.9 Contributors / Contractors

**Authority & Scope**
Individuals or entities receiving compensation from the DAO for work, services, or grants. Execute assigned deliverables within the scope approved by the relevant governance proposal. Have no governance authority; do not sign transactions or make DAO-level decisions.

**Defined In**
- Execution & Treasury Actions Policy §7.3–7.4 (cost models: documented expense recovery, fixed-rate service, fully compensated work; payment document requirements)
- Code of Conduct §3.3 (KYC/AML acceptance required before first payment)

**Appointment**
Selected by the relevant Working Group (within a DAO-approved budget), or by the RAC acting as interim execution body during Phase 1 (Transition Framework §5.4).

**Term**
Per engagement or grant agreement.

**Removal / Termination**
Per engagement terms. Standing service authorizations may be terminated early by Governance Process proposal (Execution Policy §7.5).

**Policies That Apply**
- Code of Conduct §3.3 — KYC/AML compliance required before any payment; Sybil behavior and impersonation prohibited
- Execution & Treasury Actions Policy §7 — cost models, payment documents (invoice or monthly claim), RAC verification before payment release
- Conflict of Interest Policy §2 — applies when a contractor acts in a decision-making capacity on behalf of the DAO

**Conflict of Interest & Disclosure**
Ordinary contractors are not covered by CoI Policy mandatory disclosure unless they are acting in a decision-making capacity (CoI Policy §2). Contributors who are also WG members or advisors with budget authority are subject to full CoI Policy obligations.

---

## 3. Policy-to-Role Matrix

This table shows which governance documents apply to each role. References indicate the most relevant section(s) for that role. "All" means the document applies to everyone.

| Policy Document | Token Holders | RAC Members | Treasury Signers | Delegates | WG Stewards | Contributors |
|----------------|--------------|-------------|-------------------|-----------|-------------|--------------|
| **Charter** | All (§4.1) | §8, §12.1 | §4.3 | Art IV–V | §4.2 | — |
| **Operating Agreement** | §4 | §6.5 | §5.3(a), §11.3 | §5.2–5.6 | — | — |
| **Proposal & Voting Framework** | §6–8 (voters) | §6.5 (result determination) | §8.4 (veto window) | §4.6 (election) | §4.6 (election) | — |
| **RAC Mandate** | — (subject to) | §1–11 (primary) | §3 (subject to) | §3 (subject to) | §3 (subject to) | — |
| **Treasury Signers Rules** | — | §9 (invalid refusal) | §1–20 (primary) | — | — | — |
| **Execution & Treasury Actions Policy** | — | §5.1, §11 | §5.3 | — | §5.2 | §7 |
| **Emergency & Safeguards Policy** | — | §5–6 (primary authority) | §5.1, §8 | §5.3(a) emergency | — | — |
| **Code of Conduct** | §3 (all) | §3–6 | §3–6 | §3–6 | §3–6 | §3.3 |
| **Conflict of Interest Policy** | — (encouraged) | §8 (heightened) | §2–4 | §2–4 | §2, §3.2, §3.4 | §2 (if decision-making) |
| **Legal Wrapper & Representation** | §3 (if UBO) | §8 (regulatory demands) | §4 (custody) | §3 (Compliance Liaison); §7–8 (Legal Signatory) | — | — |
| **DAO Parameters Registry** | §8 (voting power) | §5.1–5.2 | §6A, §6B, §9 | §6B | §6B, §7 | — |
| **Governance Maintenance & Upgrade Framework** | (voters on amendments) | (enforces process) | — | — | — | — |
| **Transition Governance Framework** | — | §4–6 (Phase 1 authority) | §7 | §8 (Legal Signatory) | §3.2, §10 | §5.4 |

---

## 4. Pending Role Definitions

The following Working Group roles are referenced across multiple governance documents but do not yet have adopted charters:

| Working Group | Referenced In | Status |
|--------------|---------------|--------|
| **Strategic Coordination WG** | RAC Mandate §2 (Treasury Outflow Alerts); Conflict of Interest Policy §2 (covered persons); Proposal & Voting Framework §4.6 (election) | Phase 2 activity-triggered. Charter to be proposed by governance vote. |
| **Governance & Legal WG** | Emergency & Safeguards Policy §5.1; Legal Wrapper §8; Treasury Signers Rules §15; Code of Conduct §6.1; Transition Framework §5.1, §5.4; RAC Mandate §12 | Phase 2 activity-triggered. Pre-defined responsibilities across 7+ documents. Charter to be proposed by governance vote. |

During Phase 1, the RAC holds interim authority for functions that would otherwise fall to these Working Groups (Transition Framework §5).

This registry will be updated when each WG Charter is adopted by governance vote.

---

## 5. Amendments

This document may be updated via a Governance Process proposal.

Amendment procedures and classification requirements are defined in the **Governance Maintenance & Upgrade Framework**.
