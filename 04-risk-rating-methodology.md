# Vendor Risk-Rating Methodology

## 1. Purpose

This methodology supports consistent vendor-risk decisions across onboarding, periodic review, material change and termination. It follows the principles of **ISO 31000**: integrated, structured, customised, inclusive, dynamic, evidence-based and continually improved.

## 2. Assessment process

1. Establish scope, service, data flows, stakeholders and risk criteria.
2. Identify threats, dependencies, regulatory interfaces and failure scenarios.
3. Assess inherent likelihood and impact before considering controls.
4. Evaluate control design and available evidence.
5. Calculate residual risk.
6. Compare the result with acceptance thresholds.
7. Select treatment: avoid, reduce, transfer/share or accept.
8. Record owners, deadlines, approval and monitoring cadence.
9. Review periodically and when a material event occurs.

## 3. Likelihood scale

| Score | Rating | Description |
|---:|---|---|
| 1 | Rare | Exceptional; not expected within five years |
| 2 | Unlikely | Could occur but limited indicators exist |
| 3 | Possible | Credible and may occur during the service term |
| 4 | Likely | Has occurred or strong indicators exist |
| 5 | Almost certain | Expected repeatedly or controls are absent |

## 4. Impact scale

Impact uses the highest credible consequence across confidentiality, integrity, availability, privacy, legal/regulatory, financial, operational, safety and reputation.

| Score | Rating | Example consequence |
|---:|---|---|
| 1 | Insignificant | Minor local disruption; no sensitive data |
| 2 | Minor | Limited service or data effect; quickly recovered |
| 3 | Moderate | Reportable internal incident or material operational delay |
| 4 | Major | Significant sensitive-data exposure, prolonged outage or contractual breach |
| 5 | Severe | Threat to major projects, systemic outage, major regulatory exposure or safety consequence |

## 5. Inherent-risk calculation

**Inherent risk score = Likelihood × Impact**

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

Where multiple scenarios are assessed, the overall inherent rating is the highest material scenario, supported by narrative judgement.

## 6. Control-effectiveness scale

| Rating | Factor | Evidence expectation |
|---|---:|---|
| Ineffective | 1.00 | Control absent, failed or unsupported |
| Weak | 0.80 | Partially designed; inconsistent evidence |
| Moderate | 0.60 | Designed and operating, with some gaps |
| Strong | 0.40 | Consistent independent or test evidence |
| Optimised | 0.20 | Measured, automated and continually improved |

**Residual score = Inherent score × control-effectiveness factor**, rounded up. The analyst must document judgement and must not use arithmetic to override a clearly material risk.

## 7. Decision thresholds

| Residual rating | Decision and authority |
|---|---|
| Low | Business owner may approve; annual review |
| Medium | Conditional approval by business risk owner; documented treatment; at least annual review |
| High | Senior risk/CISO-level review; time-bound remediation; quarterly monitoring |
| Critical | Do not onboard or suspend service unless executive exception is explicitly approved |

## 8. Escalation rules

Escalation is mandatory when:

- a Critical residual risk remains;
- a supplier refuses a material security or privacy obligation;
- critical evidence is missing or appears unreliable;
- regulated or highly sensitive data is involved;
- risk acceptance exceeds delegated authority;
- remediation is overdue by more than 30 days;
- a material incident, ownership change, location change or new critical subprocessor occurs;
- service concentration creates a systemic dependency.

## 9. Risk acceptance

Acceptance must state the risk scenario, rationale, compensating controls, owner, expiry date and review trigger. Acceptance does not close the underlying finding. Expired acceptance automatically returns to review.

## 10. Quality checks

A second reviewer should confirm scope, evidence, scoring consistency, unsupported assumptions and approval authority for High or Critical assessments. Methodology performance should be reviewed using overdue actions, incidents, reassessment completion and rating-challenge outcomes.
