# Security Disclosure and Bug Bounty Policy

---

## 1. Purpose

This policy establishes how security vulnerabilities in DAO-governed systems are responsibly disclosed, assessed, and resolved — and how researchers who identify and report them in good faith are rewarded and protected.

It covers:

* What is in scope for responsible disclosure
* How to report a vulnerability
* How the DAO receives, assesses, and responds to reports
* Bounty reward tiers and payment
* Safe harbour protections for researchers
* Conditions that disqualify a report or researcher

The **Emergency & Safeguards Policy** governs the DAO's response once an active exploit or critical incident is underway. This policy governs the period *before* that — proactive discovery and responsible disclosure.

---

## 2. Scope

### 2.1 In Scope

The following systems are in scope for this policy:

* DAO governance smart contracts deployed on the Radix network
* Treasury multisig infrastructure and associated smart components
* DAO-operated on-chain voting and proposal mechanisms
* Official DAO web interfaces used for governance participation
* Access control systems governing DAO-controlled accounts and credentials

---

### 2.2 Out of Scope

The following are not covered by this policy:

* The Radix protocol itself (network layer, consensus, Scrypto runtime) — these are the responsibility of RDX Works and covered by their own disclosure processes
* Third-party applications or dApps built on Radix that are not DAO-operated
* Social engineering or phishing attacks targeting individual community members
* Denial of service attacks
* Issues in DAO governance processes (process disputes are handled via the **Dispute Resolution & Arbitration Policy**)

Where a researcher is uncertain whether a system is in scope, they should contact the security channel listed in Section 4 before proceeding.

---

## 3. Severity Classification

All reported vulnerabilities are classified by the RAC and Product & Protocol WG using the following tiers:

| Severity | Definition |
|---|---|
| **Critical** | Direct loss or theft of treasury funds; complete governance takeover; ability to execute unauthorized transactions without multisig |
| **High** | Significant manipulation of voting outcomes; unauthorized access to DAO-controlled systems; contract logic errors enabling unintended behavior at scale |
| **Medium** | Partial manipulation of governance processes; information disclosure enabling targeted attacks; access control weaknesses not immediately exploitable |
| **Low** | Minor logic errors with limited impact; user-facing bugs affecting governance interface usability; non-exploitable configuration issues |
| **Informational** | Best practice observations; documentation gaps; issues with no direct security impact |

Classification is performed by the RAC in consultation with the Product & Protocol WG within **5 business days** of a report being acknowledged.

---

## 4. How to Report

### 4.1 Responsible Disclosure Channel

Vulnerabilities must be reported through the DAO's designated private security channel. The current channel details are published in the DAO's public documentation repository.

Reports must not be posted publicly on the governance forum, social media, or any other public channel until the coordinated disclosure process is complete (see Section 6).

---

### 4.2 Report Contents

A valid report should include:

* Description of the vulnerability and the affected system
* Steps to reproduce the issue
* Proof of concept (where safe to produce — see Section 5.2)
* Assessed severity and potential impact
* Researcher's contact details or pseudonym for communication and payment

Incomplete reports may still be acknowledged and triaged, but bounty eligibility may be affected by the quality of information provided.

---

### 4.3 Acknowledgement

The RAC must acknowledge receipt of a report within **48 hours**. Acknowledgement does not constitute confirmation of validity or severity.

---

## 5. Researcher Obligations and Safe Harbour

### 5.1 Safe Harbour

Researchers who comply with this policy are granted safe harbour from DAO-initiated legal action in relation to their security research activities.

Safe harbour applies where the researcher:

* Reports the vulnerability through the designated channel before any public disclosure
* Does not exploit the vulnerability beyond what is necessary to demonstrate the issue
* Does not access, modify, or exfiltrate data beyond what is needed to establish proof of concept
* Does not disrupt DAO services or operations in the course of research
* Cooperates with the RAC during the remediation period

Safe harbour does not apply where a researcher has acted in bad faith, extracted funds, or violated the conditions in Section 5.3.

---

### 5.2 Proof of Concept Standards

Researchers must limit proof-of-concept activity to what is strictly necessary to demonstrate the vulnerability. In particular:

* Do not execute transactions that move, lock, or destroy DAO funds
* Do not alter governance state (e.g., fake votes, manipulated proposals)
* Do not access private key material or credentials

Where a full proof of concept cannot be safely constructed within these limits, a theoretical description with technical evidence is acceptable.

---

### 5.3 Disqualifying Conduct

A researcher is not eligible for safe harbour or bounty payment where they have:

* Publicly disclosed the vulnerability before the coordinated disclosure date
* Exploited the vulnerability for personal gain (including extracting any funds)
* Used the vulnerability to disrupt DAO operations
* Submitted the report after an exploit is already underway
* Submitted a report in bad faith (e.g., fabricated or pre-arranged vulnerability)
* Violated the **Code of Conduct** in the course of their disclosure

---

## 6. Coordinated Disclosure Process

Upon receiving a valid report, the following process applies:

1. **Acknowledgement** — RAC acknowledges within 48 hours
2. **Triage and classification** — RAC and Product & Protocol WG classify severity within 5 business days
3. **Remediation** — The responsible WG develops and tests a fix. Target timelines by severity:

| Severity | Target Remediation Window |
|---|---|
| Critical | 7 days |
| High | 14 days |
| Medium | 30 days |
| Low / Informational | 90 days or next scheduled maintenance |

4. **Researcher update** — Researcher is kept informed of progress. For Critical and High issues, updates are provided at least every 48 hours
5. **Fix deployment** — Remediation is deployed after testing and, where governance approval is required, a governance vote
6. **Public disclosure** — After the fix is deployed, a public post-mortem is published (see Section 8)
7. **Bounty payment** — Payment is processed within 14 days of fix deployment

The total coordinated disclosure window (from report to public disclosure) must not exceed **90 days** except in exceptional circumstances agreed with the researcher.

---

## 7. Bug Bounty Rewards

### 7.1 Reward Tiers

Bounty amounts are defined in DAO Parameters and reviewed by governance periodically. The following tiers apply:

| Severity | Bounty Range |
|---|---|
| Critical | Up to the maximum defined in DAO Parameters |
| High | Defined in DAO Parameters |
| Medium | Defined in DAO Parameters |
| Low | Discretionary — small reward or public recognition |
| Informational | Public recognition only |

Exact current amounts are published in the DAO Parameters Registry and on the DAO's public documentation repository.

---

### 7.2 Payment

* Bounties are paid in XRD or stablecoins at the researcher's preference, subject to treasury availability
* Payment is subject to the researcher providing a valid receiving address
* Where KYC is required by applicable law for a payment of the relevant size, the researcher must comply or accept an alternative arrangement
* Bounty payments are approved by the RAC and executed by the Authorized Signers within 14 days of fix deployment

---

### 7.3 Duplicate Reports

Where the same vulnerability is reported by multiple researchers:

* The first valid report receives the full bounty
* Subsequent reports of the same issue receive public recognition only
* Where two reports arrive within 24 hours of each other and are clearly independent, the RAC may exercise discretion to split or supplement the reward

---

### 7.4 No Bounty Without Valid Report

Vulnerabilities discovered and exploited before or without responsible disclosure are not eligible for bounty payment regardless of the severity.

---

## 8. Post-Mortem Publication

Following remediation of any Critical or High severity vulnerability, the RAC must publish a public post-mortem within **14 days** of fix deployment containing:

* Summary of the vulnerability (without details that could enable re-exploitation on other systems)
* Timeline from report to fix
* Impact assessment (actual or potential)
* Remediation steps taken
* Recognition of the reporting researcher (unless they request anonymity)
* Any process or governance improvements arising from the incident

For Medium, Low, and Informational issues, public disclosure is at the RAC's discretion and may be batched into periodic security update summaries.

---

## 9. Governance of This Policy

### 9.1 Responsible Bodies

* **RAC** — receives reports, coordinates triage and remediation, approves bounty payments, publishes post-mortems
* **Product & Protocol WG** — provides technical assessment and implements fixes
* **Governance & Legal WG** — advises on legal dimensions of disclosure and researcher engagements

---

### 9.2 Bug Bounty Budget

The DAO must maintain a designated bug bounty budget approved by governance. Where a Critical bounty would exceed the available budget, the RAC may bring an emergency Treasury proposal to fund the payment.

---

### 9.3 Relationship to Emergency Policy

Where a reported vulnerability is already being actively exploited, the **Emergency & Safeguards Policy** takes precedence and the RAC activates emergency procedures immediately. This policy's coordinated disclosure timelines are suspended for the duration of the active incident.

---

## 10. Relationship to Other Policies

* **Emergency & Safeguards Policy** — governs active exploit response
* **Code of Conduct** — conduct standards applicable to researchers and DAO participants
* **Transparency and Reporting Policy** — post-mortem publication cadence
* **Execution & Treasury Actions Policy** — bounty payment execution by Authorized Signers

---

## 11. Amendments

This policy may be updated via a Governance Process proposal.

Amendment procedures and classification requirements are defined in the **Governance Maintenance & Upgrade Framework**.
