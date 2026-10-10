This catalogue helps the AI Vendor Assurance Agent request proportionate evidence and connect risks to practical controls. Evidence must be assessed for scope, recency, relevance and reliability; possession of a document does not by itself establish effective control operation.

# Evidence quality checks

- Scope: Does the evidence cover the assessed service, model, region, environment and subprocessors?

- Recency: Is it current enough for the vendor, model version and risk being assessed?

- Authority: Who produced, approved or independently assessed it?

- Traceability: Can the claim be linked to a test, record, owner, date and acceptance criterion?

- Exceptions: What exclusions, qualifications, unresolved findings or customer responsibilities apply?

# Core evidence catalogue

| **Area** | **Examples of relevant evidence** |
|:--:|----|
| Governance and accountability | AI policy; roles and authority map; AI inventory entry; risk acceptance record; training records; management review. |
| Use case and system description | Purpose statement; architecture; model and product documentation; intended users; limitations; prohibited uses; change history. |
| Data governance | Data sources and provenance; lawful basis; data-flow map; retention; transfer mechanism; data-quality checks; DPA. |
| Performance and responsible AI | Metric definitions; validation results; subgroup analysis; robustness testing; explainability approach; known failure modes. |
| Human oversight | Review points; competence requirements; override and fallback procedures; appeal process; monitoring responsibilities. |
| Security | Security architecture; access control; threat model; vulnerability management; logging; penetration or assurance reports; incident response. |
| Resilience and continuity | Availability commitments; backup and recovery tests; service continuity; degradation modes; manual fallback; exit plan. |
| Third parties | Subprocessor list; external model and API register; flow-down requirements; change notification; concentration and substitution analysis. |
| Compliance and assurance | Applicable-requirements register; DPIA or equivalent assessment; audit reports; certifications and scope statements; remediation records. |
| Contract and lifecycle | Service levels; audit rights; incident notification; data-use restrictions; IP terms; deletion and portability; termination assistance. |

# Control catalogue

| **Control family** | **Expected control** | **Indicative evidence** |
|:--:|----|----|
| Inventory and ownership | Register the AI service, purpose, owner, provider and dependencies before use. | Approved inventory record and named accountable owner. |
| Risk classification | Classify use and impact before procurement or deployment and repeat after material change. | Completed assessment with rationale and approvals. |
| Data controls | Limit data to approved purposes; validate provenance, quality, access, retention and deletion. | Data map, DPA, access records and validation results. |
| Performance controls | Define metrics and acceptance thresholds for the intended context; test limitations and affected groups. | Test plan, results, thresholds, exceptions and sign-off. |
| Human oversight | Provide competent review, meaningful intervention, override, escalation and fallback. | Procedure, training evidence, logs and exercise results. |
| Security controls | Apply secure configuration, identity and access management, logging, testing and incident response. | Configuration evidence, logs, test reports and tickets. |
| Third-party controls | Identify subprocessors and external models; require notification, flow-down duties and audit rights. | Dependency register, contract clauses and review records. |
| Change management | Assess material model, data, feature, hosting and subprocessor changes before release. | Change notices, impact assessment and approval history. |
| Monitoring and incidents | Monitor performance, misuse, drift, complaints, security events and control failures. | Dashboards, incident log, complaint trends and review minutes. |
| Exit and continuity | Maintain portability, deletion, replacement and operational fallback arrangements. | Exit plan, export test, deletion evidence and continuity exercise. |

# Contextual due diligence questions

- Which components and operating conditions support the claimed performance, and when does performance deteriorate?

- What data was used to develop, fine-tune, evaluate and operate the service, and how was provenance established?

- Which decisions or actions can the system influence or execute, and where can a person intervene effectively?

- Which external models, APIs, tools, plugins, subprocessors or hosting providers are required for the service to function?

- How are model, policy and dependency changes communicated, assessed and rolled back?

- What incidents, material complaints, regulatory findings or unresolved assurance issues have affected the service?

- Which controls are operated by the vendor and which remain the customer’s responsibility?

- How can the customer retrieve data, stop processing, migrate the service and verify deletion at exit?

# Monitoring triggers

Reassess when the use case, model, data, autonomy, integration, jurisdiction, subprocessor, ownership or regulatory context changes; when performance falls below an agreed threshold; after a material incident or complaint; before contract renewal; and at the review frequency assigned to the risk tier.
