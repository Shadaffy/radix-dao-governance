# On-Chain Identifiers & Verification Policy

---

## 1. Purpose

This policy establishes the single authoritative operational register of the Company's on-chain identifiers, states how each identifier is configured and used under the governance rules, and provides public links through which any person may independently verify the on-chain data.

It exists so that the governance and treasury infrastructure of the Company is publicly recorded, independently verifiable, and maintained by the community through governance rather than embedded in the Company's legal instruments.

The identifiers recorded in this policy are the operational record referred to in **Operating Agreement §11.4** and **Certificate of Formation Article VII**. Those instruments incorporate this register by reference; this policy does not alter, and remains subordinate to, the Operating Agreement and the Charter.

---

## 2. Scope

This policy covers:

* the governance smart-contract component(s) and the Owner Badge;
* the resources that constitute eligible voting power;
* the recognised Governance Platform and Official Venue(s);
* the treasury multi-signature account(s), any segmented pool accounts, and the Emergency Safe Address.

This policy does **not** cover:

* the numeric thresholds, limits, and durations governing these identifiers, which remain in the **DAO Parameters Registry**;
* the identities of the persons holding signer or role keys, which are governed by the **Treasury Signers Operational Rules**, the **Elections & Role Governance Policy**, and **Operating Agreement Schedule 2**.

This policy records *what the identifiers are and how they are verified*; the operative rules governing their use live in the policies cross-referenced below and are not restated here.

---

## 3. Identifier Register — Governance

The following identifiers are recorded on the Radix network. Each entry carries a public verification link. Values marked *[to be recorded at deployment]* are completed when the corresponding on-chain entity is deployed and confirmed, in accordance with §8.

| Function | Network | Identifier | Verify |
|---|---|---|---|
| Governance smart-contract component | Radix Mainnet | `[component_rdx1… — to be recorded at deployment]` | `https://dashboard.radixdlt.com/component/[component_rdx1…]` |
| Owner Badge (governance control) | Radix Mainnet | `[resource_rdx1… — to be recorded at deployment]` | `https://dashboard.radixdlt.com/resource/[resource_rdx1…]` |
| Governance package | Radix Mainnet | `[package_rdx1… — to be recorded at deployment]` | `https://dashboard.radixdlt.com/package/[package_rdx1…]` |
| Voting-power resource — XRD | Radix Mainnet | `resource_rdx1tknxxxxxxxxxxxradxrdxxxxxxxxx009923554798xxxxxxxxxxxxxx` | `https://dashboard.radixdlt.com/resource/resource_rdx1tknxxxxxxxxxxxradxrdxxxxxxxxx009923554798xxxxxxxxxxxxxx` |
| Recognised Governance Platform | — | `[https://… — to be recorded]` | Live URL, publicly accessible |
| Official Venue(s) | — | `[https://… — to be recorded]` | Live URL, publicly accessible |

**Voting-power sources are not all single resources.** XRD has one fixed resource address across all of Radix Mainnet and is therefore recorded above with its address and a working verification link. **LSUs (Liquid Staking Units) are not a single shared resource:** each validator mints its own distinct LSU resource with its own resource address, so there is no single "LSU address" to record. LSUs are recognised as a *class* of eligible voting power and converted to their XRD-equivalent at the redemption rate at snapshot; their identification is governed by the snapshot methodology (**DAO Parameters §8 and §8A**; **Proposal & Voting Framework §6**), not by a resource entry in this register. The same applies to any other supplementary source (**DAO Parameters §8A**) that is per-validator or per-pool rather than a single resource: where such a source *does* resolve to a single fixed resource address it may be recorded above for convenience; where it does not, it is verified through the snapshot methodology, not this register. XRD and LSU together are the entrenched constitutional floor of eligible voting power (**Charter §12.1 item 4**), whether or not each carries a register entry.

---

## 4. Governance Identifiers — Setup & Use Rules

Each governance identifier is used strictly as provided by the governance framework. This section states the applicable rule by cross-reference; it does not restate the mechanics.

* **Governance component & Owner Badge.** The Owner Badge governs elevation of passed Temperature Checks to Governance Proposals and is operated by the Governance Operator within a non-discretionary mandate (**Delegate Mandate §2.2**). The custody and recovery arrangement for the Owner Badge, chosen at deployment, must permit an elevation or badge rotation to proceed **without the Governance Operator's cooperation**, sufficient to give effect to the elevation and badge-compromise backstop (**Governance Continuity Framework §4.2A**, §7). A deployment lacking this capability does not satisfy the Minimum Operational State.
* **Voting-power resources.** Eligible voting power is measured at the voting snapshot from the sources defined in **DAO Parameters §8 and §8A**, subject to the entrenched XRD + LSU floor (**Charter §12.1 item 4**). Only single-resource sources (such as XRD) carry a fixed resource address in §3; class-based sources such as LSUs are per-validator and are identified and converted to XRD-equivalent through the snapshot methodology, not through a register address (see the note in §3).
* **Security review.** No governance or on-chain system is relied upon before it has been subject to the security-review standard the DAO maintains for smart contracts and on-chain systems it governs (**Charter §9**).

---

## 5. Identifier Register — Treasury

| Function | Network | Identifier | Verify |
|---|---|---|---|
| Primary multi-signature treasury account | Radix Mainnet | `[account_rdx1… — to be recorded at deployment]` | `https://dashboard.radixdlt.com/account/[account_rdx1…]` |
| Operational treasury pool (if segmented) | Radix Mainnet | `[account_rdx1… — if established by Governance Proposal]` | `https://dashboard.radixdlt.com/account/[account_rdx1…]` |
| Reserve treasury pool (if segmented) | Radix Mainnet | `[account_rdx1… — if established by Governance Proposal]` | `https://dashboard.radixdlt.com/account/[account_rdx1…]` |
| Grants pool (if segmented) | Radix Mainnet | `[account_rdx1… — if established by Governance Proposal]` | `https://dashboard.radixdlt.com/account/[account_rdx1…]` |
| Emergency Safe Address | Radix Mainnet | `[account_rdx1… — designated per DAO Parameters §6.1]` | `https://dashboard.radixdlt.com/account/[account_rdx1…]` |

---

## 6. Treasury Identifiers — Setup & Use Rules

* **Multi-signature control.** Treasury assets are held in the multi-signature account(s) recorded in §5, under the phase-dependent threshold structure in **DAO Parameters §6.2 and §6A** and **Treasury Signers Operational Rules §10A** — during the Transition Period 2-of-3 for ordinary actions and unanimity of all seated signers (not fewer than two) for protected matters, and from the Activation Date 3-of-5 standard and 4-of-5 high-risk. High-risk transactions correspond to the protected matters in **Operating Agreement §9.12**.
* **Segmentation & account architecture.** Establishing and changing the treasury account architecture is phase-dependent (**Treasury Signers Operational Rules §10A.1**; **DAO Parameters §6.2**): during the Transition Period the Transition RAC establishes and may adjust it by resolution published to the Official Venue under **Operating Agreement §6.5(d)**, settling once the Activation Statement is published so the Permanent RAC inherits a reviewed structure; from the Activation Date it may be changed only by Governance Proposal. Each account remains under multi-signature control on the same threshold structure. A new or changed account is recorded in §5 on establishment.
* **Emergency Safe Address.** The Emergency Safe Address must be designated before the Company receives the principal asset transfer; designation and any later change follow **DAO Parameters §6.1** and the Tier 2 emergency asset-movement rule in **Emergency & Safeguards Policy §6**.
* **Execution discipline.** All movement of treasury assets is subject to the pre-execution hold and irreversible-action controls in **Execution & Treasury Actions Policy §14** and the veto window in **Proposal & Voting Framework §8**.

---

## 7. Verification

Every identifier recorded in this policy carries a working public verification link. Any Governance Participant may confirm an identifier by opening its link on the Radix Dashboard (`https://dashboard.radixdlt.com`) or an equivalent public explorer and comparing the on-chain entity — component, resource, package, or account — against the value recorded here.

The current register is published to the **Official Venue** and kept accurate. Its public accessibility and accuracy are the evidence supporting **Operating Agreement Schedule 5, condition 5** (the Governance Mechanism, governance contracts, voting mechanism, and Official Venue(s) identified, recorded, and publicly accessible as at the Activation Statement date).

---

## 8. Change & Update Procedure

A change to a recorded identifier is classified by the identifier's significance:

* **Routine.** Recording a newly deployed non-critical identifier, correcting a link, or recording a segmented account already authorised by a passed Governance Proposal — recorded by the Governance Operator or RAC and published to the Official Venue, with the standard 48-hour DAO veto window (**Proposal & Voting Framework §8**) applying.
* **Governance-critical.** A change to the Governance smart-contract component, the Owner Badge, a voting-power resource, or the primary treasury account requires an approved Governance Proposal of the applicable class, published to the Official Venue with prior notice, before the change takes effect. Modelled on the RAC source-change discipline in **DAO Parameters §8A**: notice to Governance Participants and the standard veto window apply.

On any change, the Company updates the record held with the Registered Agent and, to the extent required by section 106(2) or section 107 of the DAO Act, notifies MIDAO and procures an amendment to the Certificate of Formation to reflect the updated identifier (**Operating Agreement §11.4**).

During the Transition Period, identifier recording and changes are made by the Transition RAC by written resolution published to the Official Venue (**Operating Agreement §6.5**); from the Activation Date, authority passes to the standing governance process and the Governance Operator as set out above.

---

## 9. Relationship to Other Documents

This policy operates alongside:

* Operating Agreement (§9.10–§9.12, §11.4, Schedules 2, 4 and 5)
* Charter (§6A, §9, §12.1)
* Execution & Treasury Actions Policy
* Treasury Signers Operational Rules
* Delegate Mandate
* Emergency & Safeguards Policy
* Governance Continuity Framework
* DAO Parameters Registry

If a conflict arises, the Operating Agreement prevails, followed by the Charter, then approved governance decisions (see **Operating Agreement §11.3**). Nothing in this policy overrides the Operating Agreement or the Charter.

---

## 10. Amendments

_Amendment procedures and classification requirements are defined in the **Governance Maintenance & Upgrade Framework**._
