# AI Security Governance Model

## 1. Purpose

This document defines the governance model for securing defence AI capabilities across their lifecycle.

The objective is to ensure that AI systems are protected against compromise, manipulation, misuse, unauthorised modification, data attacks, supply-chain threats, and failures that could create unacceptable operational consequences.

## 2. Core Principle

> **AI security is not limited to protecting the infrastructure around an AI system; it must protect the integrity, confidentiality, availability, behaviour, dependencies, and authorised boundaries of the AI capability itself.**

Security controls should therefore be connected to mission consequence, AI dependence, autonomy, operational environment, and human authority.

## 3. Scope

D-AIGAAF AI security governance applies to:

- AI models;
- AI-enabled applications;
- data and datasets;
- training and inference infrastructure;
- sensors and data sources;
- software and dependencies;
- APIs and interfaces;
- model weights and configurations;
- development environments;
- deployment environments;
- communications dependencies;
- supply-chain components;
- operators and administrators;
- update mechanisms;
- monitoring and logging systems.

## 4. Security Objectives

AI security governance should protect:

1. **Confidentiality** — prevent unauthorised disclosure.
2. **Integrity** — prevent unauthorised or undetected modification.
3. **Availability** — maintain required capability availability.
4. **Authenticity** — establish that systems, data and inputs are genuine.
5. **Traceability** — support reconstruction of consequential events.
6. **Behavioural Integrity** — prevent unauthorised changes to AI behaviour.
7. **Dependency Integrity** — control critical external components.
8. **Operational Boundary Integrity** — prevent unauthorised expansion of capability or authority.

## 5. Security as a Lifecycle Requirement

Security should be addressed from:

**Need → Requirements → Design → Development / Acquisition → Integration → TEVV → Deployment → Employment → Monitoring → Change → Revalidation → Retirement**

Security introduced only after deployment may be insufficient for consequential AI systems.

## 6. Mission-Based Security

Security requirements should be derived from the authorised mission.

A useful relationship is:

**Mission Consequence → Threat Exposure → Security Requirements → Controls → Testing → Evidence → Operational Authority**

A low-consequence administrative AI system may require substantially different controls from an AI system supporting consequential operational decisions.

## 7. AI Security Risk

A working relationship is:

**AI Security Risk = Consequence × Threat Exposure × Vulnerability × AI Dependence × Autonomy**

This is a D-AIGAAF working construct and should be adapted to established organisational risk terminology.

## 8. Security Threat Categories

D-AIGAAF should consider threats including:

- unauthorised access;
- credential compromise;
- malicious insiders;
- model theft;
- model manipulation;
- data poisoning;
- adversarial inputs;
- prompt or instruction manipulation where applicable;
- malicious software;
- compromised dependencies;
- supply-chain compromise;
- unauthorised updates;
- configuration manipulation;
- interface compromise;
- denial of service;
- communications disruption;
- sensor or input manipulation;
- logging or monitoring compromise.

The relevant threat set should be determined by mission and architecture.

## 9. Defence-in-Depth

AI security should use layered controls rather than relying on a single protective mechanism.

Potential layers include:

- identity and access management;
- network and infrastructure security;
- data protection;
- model protection;
- application security;
- interface security;
- configuration control;
- supply-chain controls;
- monitoring and detection;
- human oversight;
- fail-safe mechanisms;
- incident response.

Failure of one control should not automatically result in loss of the authorised security boundary.

## 10. Model Security

Model security should address:

- unauthorised model modification;
- unauthorised model replacement;
- model-weight theft;
- malicious model insertion;
- configuration manipulation;
- unexpected behavioural changes;
- unauthorised fine-tuning;
- compromised update mechanisms.

Where technically feasible, approved model versions should be identifiable and integrity-protected.

## 11. Data Security

Data security should protect:

- training data;
- validation and test data;
- operational inputs;
- labels;
- metadata;
- reference data;
- derived data;
- logs;
- assurance evidence.

Data security should remain connected to the controls defined in **05 Data & Information**.

## 12. Input and Interface Security

AI systems may receive information through multiple interfaces.

Security governance should consider:

- input authentication;
- input validation;
- interface access control;
- data integrity;
- malformed or unexpected inputs;
- malicious inputs;
- API security;
- interface isolation;
- rate or resource controls where relevant.

The system should not assume that all inputs are trustworthy merely because they originate from an approved network or platform.

## 13. Adversarial AI Security

Where relevant, TEVV should assess resilience against adversarial manipulation.

Assessment may include:

- manipulated inputs;
- adversarial examples;
- poisoning;
- deceptive data;
- malicious instructions;
- compromised reference information;
- attempts to cause unsafe or unintended outputs.

Security testing should reflect realistic threat conditions appropriate to the authorised operational environment.

## 14. Autonomous Behaviour and Security

Increasing autonomy increases the potential consequence of a security compromise.

Security assurance should therefore increase with autonomy.

A working relationship is:

**Higher Autonomy + Higher Consequence → Stronger Security Controls + Stronger Assurance + Tighter Operational Boundaries**

An AI capability should not receive higher operational autonomy solely because its technical performance is strong if its security assurance is inadequate.

## 15. Communications and Degraded Operation

AI systems may operate with:

- limited connectivity;
- intermittent communications;
- delayed communications;
- no external network access;
- degraded infrastructure.

Security and safety controls should remain effective under the conditions relevant to the authorised operational environment.

Where critical security functions depend on connectivity, that dependency should be explicit in the operational authorisation.

## 16. Security Boundaries

The authorised security boundary should identify, as appropriate:

- trusted components;
- untrusted components;
- external interfaces;
- data sources;
- users;
- administrators;
- update mechanisms;
- dependencies;
- communications paths;
- physical or logical boundaries.

Changes to the boundary should be assessed for impact on assurance and authorisation.

## 17. Access Control

Access should follow:

**Need → Authority → Eligibility → Least Privilege → Controlled Access → Monitoring → Review → Revocation**

Administrative access to an AI system should not automatically confer authority to change its operational behaviour.

Privileged actions should be controlled and traceable.

## 18. Configuration and Integrity

Critical configuration should be:

- documented;
- version controlled;
- approved;
- protected from unauthorised modification;
- monitored for unauthorised change;
- recoverable where required.

This may include:

- model version;
- system software;
- prompts or system instructions where applicable;
- safety controls;
- thresholds;
- decision rules;
- interfaces;
- data pipelines;
- hardware configuration.

## 19. Security Monitoring

Continuous monitoring should seek to identify:

- unauthorised access;
- anomalous behaviour;
- configuration changes;
- unexpected model changes;
- unusual data patterns;
- compromised dependencies;
- failed security controls;
- suspicious administrative activity;
- unexpected external connections.

Monitoring requirements should be proportionate to consequence and operational criticality.

## 20. Security Incidents

An AI security incident is an event that may compromise:

- confidentiality;
- integrity;
- availability;
- authenticity;
- AI behaviour;
- authorised boundaries;
- critical dependencies;
- operational safety or mission effectiveness.

Examples include suspected model tampering, data poisoning, compromised credentials, unauthorised updates, or malicious modification of critical configuration.

## 21. Security Incident Response

A general response pathway is:

**Detect → Contain → Assess → Escalate → Decide → Recover → Validate → Reauthorise if Required**

Where compromise could create unacceptable operational risk, predefined restrictions or suspension should be available.

Emergency protective procedures should allow immediate action where delay could create unacceptable harm.

## 22. AI Security and Fail-Safe

Security compromise should be considered among the conditions that may trigger degraded operation, restriction, or fail-safe behaviour.

The response should normally follow defined authority pathways involving:

**Detection → Technical Assessment → AI System Management → Operational AI Advisor → Appropriate Command / Authorising Authority**

However, where delay could create unacceptable harm, pre-authorised emergency procedures should permit immediate protective action.

## 23. Supply-Chain Security

Security governance should identify critical dependencies capable of affecting AI behaviour or system integrity.

This includes, where relevant:

- model providers;
- software libraries;
- hardware;
- pretrained models;
- cloud or infrastructure services;
- data providers;
- update mechanisms;
- APIs;
- third-party components.

Supply-chain assurance should connect with **07 Supply Chain & Sovereignty**.

## 24. Security of Updates

AI updates should be:

- authorised;
- attributable;
- integrity-protected;
- version controlled;
- tested;
- assessed for security impact;
- traceable to an approved change.

An update should not automatically be treated as minor merely because its stated purpose is maintenance.

Changes capable of affecting model behaviour or security boundaries may require revalidation or reauthorisation.

## 25. Security and Operational Authorisation

Operational authorisation should consider whether:

- critical security threats have been assessed;
- required controls are implemented;
- security assumptions are documented;
- critical dependencies are controlled;
- monitoring is active;
- incident response is established;
- fail-safe or degraded modes are available where required;
- security evidence supports the authorised mission and environment.

Security conditions should form part of the operational authorisation rather than being treated as separate administrative requirements.

## 26. Security Assurance Record

A working AI Security Assurance Record should include:

| Field | Description |
|---|---|
| AI Capability ID | Unique capability identifier |
| Security Boundary | Approved system boundary |
| Critical Assets | Assets requiring protection |
| Threat Profile | Relevant threats |
| Security Requirements | Required controls |
| Implemented Controls | Controls in place |
| Dependencies | Critical dependencies |
| Configuration Baseline | Approved baseline |
| Security Testing | Testing performed |
| Monitoring | Active monitoring |
| Incidents | Relevant incidents |
| Known Limitations | Security limitations |
| Residual Risk | Remaining security risk |
| Assurance Status | Current security assurance |
| Authorisation Status | Current operational authority |

## 27. Security Assurance Levels

A working five-level security assurance scale may be used:

- **S1 — Basic Protection:** Baseline security controls established.
- **S2 — Controlled Security:** Access, integrity, configuration and monitoring controls established.
- **S3 — Assured Security:** Security controls tested against relevant threats.
- **S4 — Operational Security Assurance:** Security demonstrated in the authorised operational environment.
- **S5 — High-Consequence Security Assurance:** Strong defence-in-depth, adversarial testing, monitoring and response capability appropriate to highly consequential AI use.

These are D-AIGAAF working constructs and should be mapped to established organisational terminology before formal adoption.

## 28. Common Failure Modes

Common weaknesses include:

- treating AI security as conventional IT security only;
- protecting infrastructure while ignoring model integrity;
- assuming approved data is trustworthy;
- failing to control model updates;
- ignoring third-party dependencies;
- insufficient adversarial testing;
- excessive administrative privileges;
- weak configuration control;
- inadequate monitoring;
- failing to account for degraded communications;
- failing to connect security incidents to operational authorisation;
- assuming human oversight alone compensates for weak security controls.

## 29. Core Rules

1. Treat AI security as a lifecycle requirement.
2. Derive security requirements from mission consequence and threat exposure.
3. Protect model, data, software, interfaces, infrastructure and dependencies.
4. Maintain integrity of approved configurations and model versions.
5. Control privileged access and consequential changes.
6. Test against relevant adversarial conditions.
7. Account for degraded and disconnected operation.
8. Monitor for security and behavioural anomalies.
9. Maintain predefined incident, restriction and fail-safe pathways.
10. Revalidate and reauthorise when material security changes occur.

## 30. Relationship to Other D-AIGAAF Domains

This document connects directly with:

- **03 Risk & Autonomy** — consequence, autonomy and security risk;
- **04 AI Lifecycle** — security throughout development and change;
- **05 Data & Information** — data integrity, provenance and poisoning;
- **07 Supply Chain & Sovereignty** — dependency and supplier risk;
- **08 Human Authority** — privileged access and consequential decisions;
- **09 TEVV** — adversarial and security testing;
- **10 Operational Environment** — degraded and contested conditions;
- **11 Operational Authorisation** — security conditions of authority;
- **13 Continuous Assurance** — security monitoring;
- **14 Incident & Fail-Safe** — response to compromise;
- **15 Change & Reauthorisation** — security impact of updates;
- **16 Audit & Evidence** — traceability and investigation;
- **24 Architecture & Technical Controls** — technical implementation of security controls.

## 31. Summary

The key question is:

> **Can the organisation demonstrate that the AI capability, its data, dependencies, interfaces, configurations and authorised boundaries are sufficiently protected against compromise or manipulation for the mission and environment in which it operates?**

If not, the resulting security uncertainty must be reflected in assurance, operational constraints, and authorisation decisions.
