This document provides a transparent scoring model for provisional vendor assessment. Scores support consistent judgment but do not replace expert review. A mandatory escalation rule overrides a low numerical score.

# Risk scale

| **Score** | **Level** | **Interpretation** |
|:--:|----|----|
| 1 | Low | Limited adverse impact, narrow exposure and straightforward recovery. |
| 2 | Moderate | Meaningful but contained impact requiring documented safeguards and ownership. |
| 3 | High | Serious impact, broad exposure, difficult recovery or material regulatory concern. |
| 4 | Critical | Potential for severe rights, safety, systemic, financial or operational harm. |

# Scoring dimensions

| **Dimension** | **Assess** |
|:--:|----|
| Business and operational criticality | Impact of failure, interruption, incorrect output or unavailable service. |
| People and fundamental rights | Potential effects on access, employment, health, safety, equality, dignity or due process. |
| Data protection and confidentiality | Sensitivity, volume, provenance, lawful handling, retention and cross-border exposure. |
| Security and misuse | Attack surface, model abuse, prompt or data leakage, access control and incident exposure. |
| Autonomy and human oversight | Degree of automated action, meaningful review, override, contestability and fallback. |
| Model performance and transparency | Accuracy, robustness, bias, limitations, explainability and conditions of valid use. |
| Third and fourth party dependency | External models, APIs, subprocessors, concentration, substitutability and change control. |
| Regulatory and contractual exposure | Applicable rules, customer promises, audit rights and ability to evidence compliance. |
| Reversibility and exit | Ability to stop, replace, migrate or recover without disproportionate harm or lock-in. |

# Provisional tier calculation

Score each dimension from 1 to 4. Calculate the average, then apply the escalation rules below. Retain both the numerical result and the written rationale.

| **Average**  | **Provisional tier** |
|:------------:|----------------------|
| 1.00 to 1.49 | Low                  |
| 1.50 to 2.49 | Moderate             |
| 2.50 to 3.24 | High                 |
| 3.25 to 4.00 | Critical             |

# Mandatory escalation rules

- Escalate for specialist review when the use case may be prohibited or high risk under applicable AI regulation.

- Escalate when AI materially affects employment, education, credit, insurance, healthcare, essential services, biometric identification, safety or other rights-sensitive decisions.

- Escalate when sensitive data is involved and lawful basis, data provenance, security, retention or transfer arrangements remain unclear.

- Escalate when the system can act through tools or agents with material financial, operational or cyber impact.

- Escalate when performance claims cannot be traced to defined metrics, datasets, test conditions and limitations.

- Escalate when a critical dependency, fourth party, incident history or material model change is undisclosed.

- Do not assign Low residual risk when essential evidence is missing.

# Residual risk rules

A safeguard may reduce risk only when the evidence is relevant to the assessed service and use case. Design documentation alone normally supports control design, not operating effectiveness. Certifications and assurance reports may support confidence within their stated scope and period but do not eliminate the need to examine exclusions, complementary controls and current applicability.

# Decision outcomes

| **Outcome** | **Use when** |
|:--:|----|
| Proceed | Risk is within tolerance, essential evidence is available, controls are supported and accountable approval is recorded. |
| Proceed with Conditions | Risk can be accepted only after specified actions, contract clauses, monitoring or evidence deadlines are assigned. |
| Escalate for Specialist Review | Legal, privacy, security, model, safety, procurement or executive judgment is required before a decision. |
| Do Not Proceed | Risk exceeds tolerance, a prohibited or unacceptable use is indicated, critical evidence is unavailable, or remediation is not credible. |

# Required decision statement

State the recommended outcome, the three most important reasons, conditions precedent, accountable owner, specialist reviewers, monitoring frequency, reassessment triggers and any deadline for closing evidence gaps.
