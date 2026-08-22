# Regulatory and Assurance Awareness Notes

## Purpose and boundary

These prompts help a vendor-risk analyst recognise when specialist input is needed. They do **not** claim that the portfolio author owns Legal, Data Protection, Internal Audit, Finance, Procurement or regulatory-accountability decisions.

## DORA ICT third-party oversight

For an EU financial entity or an in-scope service, prompts would include:

- Is the supplier an ICT third-party service provider supporting a critical or important function?
- Are all required contractual provisions present?
- Are subcontracting chains, locations and concentration dependencies understood?
- Are access, inspection, audit, incident support, resilience testing and exit rights adequate?
- Is the arrangement captured in the required register of information?
- Does the exit strategy prevent disruption and lock-in?

**Escalate to:** Legal, Operational Resilience, Regulatory Compliance and the accountable business owner.

## GDPR Article 28 processor obligations

Where a supplier processes personal data on behalf of the organisation:

- Are subject matter, duration, purpose, data types and data-subject categories documented?
- Are confidentiality, security, breach assistance, data-subject rights, DPIA support, deletion/return and audit duties included?
- Is prior authorisation and notification for subprocessors addressed?
- Are international transfers and data locations understood?
- Has the controller confirmed sufficient guarantees?

**Escalate to:** DPO/privacy counsel and Legal. The GRC analyst records evidence and dependencies but does not provide legal advice.

## RCSA interface

Supplier risks may feed a Risk and Control Self-Assessment when they affect business-process objectives. Prompts include:

- Which process and risk taxonomy entry does the supplier dependency affect?
- What controls are performed by the organisation versus the supplier?
- Are control owners, frequency, evidence and effectiveness recorded?
- Do incidents, KRIs or overdue findings change the residual assessment?

**Escalate to:** Enterprise/Operational Risk and process owners.

## RoPA and DPIA interfaces

- Does the supplier introduce or change a personal-data processing activity that must be reflected in the Record of Processing Activities?
- Does the processing involve high-risk monitoring, sensitive data, vulnerable individuals, large scale or innovative technology?
- Has the privacy function determined whether a DPIA is required?
- Do data flows, retention, recipients, locations and security measures align across the assessment, RoPA and DPIA?

**Escalate to:** DPO/privacy team. The analyst flags the trigger and supplies technical/vendor evidence.

## SOC 2 assurance review

When reviewing a SOC 2 report:

- Is it Type I or Type II, and is the period current?
- Does the scope include the service, system, locations and relevant Trust Services Criteria?
- Are there qualified opinions, exceptions or subservice organisations?
- Is the carve-out/inclusive method understood?
- Are Complementary User Entity Controls assigned internally?
- Does a bridge letter cover the period since report end?

A SOC 2 report supports assurance but does not replace risk assessment or contract controls.

## PCI DSS scoping

Where payment-card data may be stored, processed or transmitted:

- Does the service touch cardholder data or the cardholder-data environment?
- Can tokenisation or outsourcing reduce scope?
- Is the supplier listed as a service provider in the organisation's PCI scope?
- Is an appropriate Attestation of Compliance available and current?
- Are shared responsibilities and required customer controls documented?
- Could remote access, logging or segmentation connect the service to the CDE?

**Escalate to:** PCI programme owner, Qualified Security Assessor where applicable, Security Architecture and Legal.

## Governance reporting prompts

A committee update should show:

- critical and high-risk suppliers;
- inherent versus residual risk;
- overdue remediation by age;
- expiring assurance and risk acceptances;
- incidents and material supplier changes;
- concentration and fourth-party dependencies;
- decisions required, named owners and deadlines.
