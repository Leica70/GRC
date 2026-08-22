# Vendor Due-Diligence Assessment

## Assessment record

| Field | Value |
|---|---|
| Organisation | NorthStar Construction & Engineering Ltd (fictional) |
| Supplier | PeopleCore Payroll Services Ltd (fictional) |
| Service | Cloud payroll and workforce-management service |
| Business owner | HR Director |
| Assessment owner | GRC Analyst |
| Assessment type | New supplier / pre-contract |
| Proposed decision | Conditional approval |
| Inherent risk | High |
| Residual risk | Medium |
| Reassessment cadence | Quarterly until actions close; annually thereafter |

## 1. Service scope and data flow

NorthStar will transmit employee identity, contact, employment, salary, bank-payment and absence data to PeopleCore through an encrypted integration. PeopleCore hosts the application with a cloud infrastructure subcontractor in the EEA. HR administrators use SSO and MFA. Payroll outputs are transferred to NorthStar Finance and the banking provider.

## 2. Inherent-risk assessment

| Risk domain | Assessment | Rating | Rationale |
|---|---|---:|---|
| Business criticality | Payroll disruption could delay employee payment | 5 | Time-sensitive and reputationally important |
| Data sensitivity | Employee, payroll and bank data processed | 5 | High confidentiality and privacy impact |
| System access | API and privileged support access required | 4 | Supplier access creates misuse and compromise risk |
| Availability | Monthly processing has limited tolerance for outage | 4 | Manual workarounds are limited |
| Geographic risk | Primary and backup processing within EEA | 2 | Lower transfer complexity, subject to verification |
| Fourth-party risk | Cloud host and support subcontractor used | 4 | Dependency and notification obligations required |
| Concentration risk | Same cloud provider supports several NorthStar services | 4 | Common-provider outage could affect multiple services |

**Inherent score:** 28/35 — High.

## 3. Security and privacy review

| Area | Supplier response/evidence | Assessment |
|---|---|---|
| Security governance | ISO 27001 certificate and policy index supplied | Adequate, certificate scope must be confirmed annually |
| Identity and access | SSO, MFA and role-based access supported | Adequate, privileged access review evidence requested |
| Encryption | TLS 1.2+ in transit and AES-256 at rest | Adequate |
| Logging and monitoring | Central logging and 24/7 alerting stated | Partially evidenced; sample monitoring report requested |
| Vulnerability management | Monthly scanning and annual penetration test | Adequate subject to executive-summary review |
| Privacy | DPA available; deletion and data-subject support described | Legal and DPO review required before execution |
| Resilience | Daily backups and documented recovery objectives | Restoration-test evidence is outstanding |
| Incident management | 24-hour customer notification proposed | Adequate if included contractually |
| Subcontractors | Cloud host listed; changes notified on request | Insufficient: proactive notification and objection process required |

## 4. Evidence reviewed

- ISO/IEC 27001 certificate and scope statement
- SOC 2 Type II executive summary
- Penetration-test executive summary
- Information-security policy index
- Business-continuity and disaster-recovery summary
- Data-flow and hosting-location diagram
- Subprocessor register
- Standard data-processing agreement
- Sample incident-notification procedure
- Access-control and privileged-access summary

## 5. Key risks and conditions

| ID | Finding | Risk | Required condition |
|---|---|---|---|
| F-01 | No recent backup restoration-test evidence | Recovery capability may be unproven | Provide successful test evidence within 30 days |
| F-02 | Subprocessor-change wording is reactive | NorthStar may not assess new fourth parties promptly | Add advance notification and objection clause |
| F-03 | Privileged-access review evidence not supplied | Excessive supplier access may remain undetected | Provide latest quarterly review |
| F-04 | Monitoring evidence is high level | Detection effectiveness cannot be confirmed | Provide sample redacted monitoring KPI/report |

## 6. Approval decision

**Conditional approval** is recommended because core preventive controls are present and the service supports a valid business need. Contract signature and production onboarding are conditional on:

1. DPA and security schedule approval by authorised Legal and Data Protection stakeholders.
2. Closure or formally approved treatment of F-01 to F-04.
3. Named service owner and risk owner.
4. Quarterly monitoring until all High/Medium findings close.
5. Annual reassessment, plus event-driven reassessment following a material incident, control failure, acquisition, hosting-location change or new critical subprocessor.

## 7. Roles and boundaries

The GRC analyst coordinates assessment, challenges evidence, records risk and tracks remediation. Procurement owns commercial onboarding; Legal owns contractual advice; the DPO/privacy function determines privacy requirements; the business risk owner accepts residual risk within delegated authority.
