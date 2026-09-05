# AI Security Requirements

## 1. Purpose

This document defines the requirements framework for AI security within D-AIGAAF.

The objective is to translate mission consequence, threat exposure, AI dependence, autonomy, and operational context into explicit security requirements that can be implemented, tested, evidenced, and linked to operational authorisation.

## 2. Core Principle

> **AI security requirements must be derived from the consequences and threats associated with the authorised use of the AI capability, not from technology alone.**

Requirements should therefore be specific enough to be assessed while remaining technology- and vendor-neutral where practical.

## 3. Scope

Security requirements may apply to:

- models and model weights;
- data;
- applications;
- infrastructure;
- interfaces;
- communications;
- configurations;
- development environments;
- deployment environments;
- update mechanisms;
- monitoring;
- logging;
- users and administrators;
- third-party components;
- supply-chain dependencies.

## 4. Requirement Derivation

A general D-AIGAAF relationship is:

**Mission → Consequence → Threat → Vulnerability / Exposure → Security Requirement → Control → Test → Evidence → Assurance → Authority**

Security requirements should be traceable to the risk they are intended to control.

## 5. Requirement Categories

AI security requirements should be considered across at least the following categories:

1. Identity and Access
2. Data Security
3. Model Security
4. Software and Infrastructure Security
5. Interface and Communications Security
6. Configuration and Change Security
7. Supply-Chain Security
8. Monitoring and Detection
9. Incident Response
10. Recovery and Continuity
11. Security Assurance
12. Operational Boundary Protection

## 6. Requirement Characteristics

A useful security requirement should be:

- clear;
- necessary;
- testable;
- attributable;
- measurable where appropriate;
- traceable to a risk;
- appropriate to the mission;
- feasible within the operational environment;
- maintained through the lifecycle.

Avoid requirements that merely state broad intentions such as “the system shall be secure” without defining what must be demonstrated.

## 7. Identity and Access Requirements

Where applicable, the system should:

- authenticate users and privileged accounts;
- enforce authorised access;
- apply least privilege;
- separate operational and administrative privileges;
- control service accounts;
- protect credentials;
- support timely revocation;
- record consequential privileged actions;
- prevent unauthorised changes to critical AI components.

Access should not be interpreted as authority to alter the AI capability's operational behaviour.

## 8. Data Security Requirements

Where relevant, requirements should address:

- authorised data sources;
- data access;
- data integrity;
- provenance;
- lineage;
- classification and handling;
- data validation;
- data poisoning;
- unauthorised modification;
- secure transfer;
- retention;
- disposal.

Critical data requirements should connect to **05 Data & Information**.

## 9. Model Security Requirements

Where applicable, the AI system should:

- use an approved model version;
- protect model artefacts against unauthorised modification;
- detect or prevent unauthorised replacement;
- control fine-tuning or retraining;
- maintain model version identity;
- preserve relevant model provenance;
- assess model changes before operational use;
- support recovery to an approved baseline where required.

## 10. Software and Infrastructure Requirements

Requirements should address, as applicable:

- secure configuration;
- vulnerability management;
- dependency control;
- patch management;
- system hardening;
- privileged access;
- isolation;
- resource protection;
- secure build processes;
- integrity verification;
- backup and recovery.

The required controls should reflect the AI system's operational consequence.

## 11. Interface and Communications Requirements

AI systems should define security requirements for interfaces that can influence system behaviour.

These may include:

- API authentication;
- input validation;
- interface authorisation;
- message integrity;
- secure communications;
- protection against unauthorised commands;
- protection against malicious inputs;
- interface isolation;
- handling of communications loss.

Where AI can continue operating during communication degradation, that behaviour should be explicitly assessed and authorised.

## 12. Configuration Security Requirements

Critical configuration should be:

- identified;
- version controlled;
- approved;
- protected;
- monitored;
- auditable;
- recoverable where required.

Configuration may include:

- model version;
- software version;
- prompts or system instructions where applicable;
- thresholds;
- rules;
- safety controls;
- data pipelines;
- interfaces;
- autonomy settings.

## 13. Supply-Chain Requirements

Critical suppliers and dependencies should be identified.

Requirements may address:

- supplier provenance;
- component integrity;
- software dependencies;
- pretrained models;
- hardware;
- external services;
- update mechanisms;
- vulnerability notification;
- change notification;
- supplier access;
- end-of-support risk.

Critical dependencies should have appropriate assurance before they become part of an operationally authorised capability.

## 14. Adversarial Security Requirements

Where relevant, security requirements should require assessment against:

- adversarial inputs;
- data poisoning;
- model manipulation;
- malicious instructions;
- compromised data sources;
- malicious dependencies;
- configuration tampering;
- attempts to bypass safety or control mechanisms.

The assessment depth should reflect consequence and threat exposure.

## 15. Autonomy-Related Security Requirements

Security requirements should increase with authorised autonomy where compromise could produce consequential action.

For higher autonomy, requirements may include:

- stronger authentication;
- stronger integrity controls;
- tighter interface restrictions;
- enhanced monitoring;
- independent validation;
- stronger change controls;
- defined loss-of-control behaviour;
- rapid suspension capability;
- additional operational testing.

A system should not receive increased autonomy solely because it performs well under nominal conditions.

## 16. Security Requirements for Degraded Environments

Where the operational environment may involve degraded infrastructure or communications, requirements should define:

- expected behaviour during communication loss;
- local security controls;
- authentication dependencies;
- update restrictions;
- logging requirements;
- safe degradation;
- recovery procedures;
- re-synchronisation requirements.

Security requirements should not assume continuous connectivity unless continuous connectivity is itself an authorised operational dependency.

## 17. Monitoring Requirements

Security monitoring should identify events capable of affecting the AI capability's security boundary.

Requirements may include detection of:

- unauthorised access;
- privileged activity;
- configuration changes;
- model changes;
- unexpected data changes;
- anomalous system behaviour;
- compromised dependencies;
- failed controls;
- suspicious interfaces;
- security-relevant operational events.

Monitoring requirements should define what constitutes an actionable event.

## 18. Incident Response Requirements

Security requirements should define mechanisms for:

- detection;
- reporting;
- containment;
- assessment;
- escalation;
- restriction;
- suspension;
- recovery;
- evidence preservation;
- revalidation.

Where appropriate, requirements should support immediate protective action under pre-authorised emergency procedures.

## 19. Recovery Requirements

For consequential systems, requirements should address recovery from:

- compromise;
- corrupted data;
- unauthorised model modification;
- infrastructure failure;
- configuration failure;
- communications loss;
- compromised dependencies.

Recovery objectives should reflect mission consequence and operational criticality.

## 20. Security and Human Authority

Security requirements should preserve human authority over consequential actions.

Where the AI capability is advisory, security controls should prevent unauthorised mechanisms from converting advisory outputs into autonomous consequential actions.

Where autonomous action is authorised, the authority, boundaries, controls, and suspension mechanisms should be explicit.

## 21. Fail-Safe Requirements

Where required by risk, the system should have defined behaviour for security compromise or loss of control.

Requirements may include:

- safe degradation;
- controlled shutdown;
- isolation;
- restriction of consequential functions;
- return to a defined safe state;
- human escalation;
- emergency protective action.

The fail-safe mechanism itself should be protected against unauthorised activation or disabling, while remaining available to authorised emergency procedures.

## 22. Security Requirements and TEVV

Every consequential security requirement should have a corresponding assurance method.

A simple mapping is:

| Requirement | Control | Verification Method | Evidence |
|---|---|---|---|
| Access restriction | Access control | Test | Test record |
| Model integrity | Integrity mechanism | Verification | Verification evidence |
| Adversarial resilience | Security control | Adversarial test | Test results |
| Configuration control | Baseline management | Inspection / test | Configuration record |
| Incident response | Response procedure | Exercise | Exercise record |
| Recovery | Recovery mechanism | Recovery test | Test evidence |

A requirement without an appropriate verification method should be reviewed for clarity.

## 23. Requirement Prioritisation

Security requirements may be prioritised according to:

- consequence;
- mission criticality;
- threat exposure;
- vulnerability;
- AI dependence;
- autonomy;
- operational environment;
- reversibility of potential harm.

A useful working priority model is:

- **Mandatory** — required before authorised operation;
- **Conditional** — required under defined circumstances;
- **Enhanced** — required for higher consequence or autonomy;
- **Recommended** — beneficial but not essential to the current authorisation.

## 24. Security Requirement Levels

A working five-level model may be used:

- **SR1 — Baseline:** Fundamental security requirements.
- **SR2 — Controlled:** Defined access, integrity and configuration requirements.
- **SR3 — Assured:** Security requirements tested against relevant threats.
- **SR4 — Operational:** Requirements demonstrated in the authorised environment.
- **SR5 — High-Consequence:** Enhanced requirements for highly consequential or highly autonomous use.

These are D-AIGAAF working constructs and should be mapped to established organisational terminology before formal adoption.

## 25. Requirement Traceability

Security requirements should be traceable through:

**Risk → Requirement → Control → Test → Evidence → Assurance → Operational Condition**

This traceability should be maintained throughout the AI lifecycle.

Material changes to requirements should trigger appropriate impact assessment.

## 26. Security Requirements Record

A Security Requirements Record should contain, where appropriate:

| Field | Description |
|---|---|
| Requirement ID | Unique identifier |
| Requirement | Security requirement statement |
| Rationale | Risk or need addressed |
| Risk Link | Associated risk |
| Applicability | Systems / environments affected |
| Priority | Mandatory / Conditional / Enhanced / Recommended |
| Control | Implemented control |
| Verification Method | Test / inspection / analysis / demonstration |
| Evidence | Supporting evidence |
| Owner | Responsible authority |
| Status | Current implementation status |
| Change History | Material changes |
| Authorisation Impact | Effect on operational authority |

## 27. Security Requirements and Authorisation

Operational authorisation should establish that mandatory security requirements have been:

- identified;
- implemented;
- tested;
- evidenced;
- accepted by the appropriate authority.

Where a requirement is not fully satisfied, the residual risk and compensating controls should be explicitly assessed.

Unresolved security deficiencies may require:

- restricted operation;
- reduced autonomy;
- additional human oversight;
- environmental constraints;
- temporary suspension;
- revalidation;
- non-authorisation.

## 28. Common Failure Modes

Common weaknesses include:

- deriving security requirements from generic IT checklists only;
- writing requirements that cannot be tested;
- failing to link requirements to risk;
- ignoring model and data integrity;
- overlooking supply-chain dependencies;
- assuming connectivity is always available;
- failing to specify degraded-mode behaviour;
- treating security requirements as complete once development ends;
- allowing changes without reassessing requirements;
- failing to connect requirements to operational authorisation.

## 29. Core Rules

1. Derive AI security requirements from mission consequence and threat exposure.
2. Make consequential requirements testable and traceable.
3. Protect data, models, software, interfaces, configurations and dependencies.
4. Scale security requirements with consequence and autonomy.
5. Define security behaviour for degraded operational conditions.
6. Require evidence for consequential security requirements.
7. Control privileged access and security-relevant changes.
8. Include adversarial resilience where relevant.
9. Define incident, recovery and fail-safe requirements before deployment.
10. Reassess requirements when mission, threat, architecture, data, autonomy or environment materially changes.

## 30. Relationship to Other D-AIGAAF Domains

This document connects directly with:

- **03 Risk & Autonomy** — risk, consequence and autonomy;
- **04 AI Lifecycle** — requirements through retirement;
- **05 Data & Information** — data security and integrity;
- **06 AI Security** — security governance and controls;
- **07 Supply Chain & Sovereignty** — dependency requirements;
- **08 Human Authority** — human control and decision rights;
- **09 TEVV** — verification and validation;
- **10 Operational Environment** — environmental security requirements;
- **11 Operational Authorisation** — security conditions of authority;
- **13 Continuous Assurance** — monitoring;
- **14 Incident & Fail-Safe** — response and safe degradation;
- **15 Change & Reauthorisation** — requirements after change;
- **16 Audit & Evidence** — traceability and evidence;
- **24 Architecture & Technical Controls** — implementation.

## 31. Summary

The key question is:

> **Can every material AI security risk be translated into an explicit, testable requirement whose implementation and evidence can be traced to operational assurance and authorisation?**

If not, the security requirement set is incomplete.
