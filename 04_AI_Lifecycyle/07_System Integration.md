# System Integration

## Summary

System Integration governs the controlled integration of AI models and components into the wider defence system or capability in which they will operate.

An AI model cannot be considered operationally suitable solely because the model itself performs as expected. Sensors, data pipelines, software, communications, infrastructure, interfaces, users and downstream systems can materially affect AI behaviour and operational risk.

The core chain is:

**AI Model + Data + Software + Hardware + Interfaces + Human Users + Dependencies → Integrated Capability → System TEVV → Assurance → Operational Authorisation**

---

## 1. Purpose

System Integration establishes controls to ensure that:

- AI components are integrated according to approved requirements;
- interfaces are controlled;
- dependencies are understood;
- system-level behaviour is assessed;
- model behaviour remains traceable after integration;
- safety and security controls remain effective;
- human authority is preserved;
- integrated performance is suitable for further TEVV and assurance.

---

## 2. Core Principle

**A validated AI model is not automatically a validated AI system.**

Integration can introduce new:

- failure modes;
- dependencies;
- latency;
- data transformations;
- attack surfaces;
- human factors;
- autonomy pathways;
- safety risks.

Therefore, system integration must be subject to system-level assessment.

---

## 3. Integration Scope

Integration may involve:

- AI models;
- software applications;
- sensors;
- data ingestion systems;
- databases;
- communications;
- compute infrastructure;
- storage;
- user interfaces;
- command-and-control interfaces;
- downstream systems;
- external services;
- human operators;
- safety mechanisms;
- security mechanisms.

The scope should be defined according to the approved use case.

---

## 4. Integration Requirements

Integration should trace to:

- mission requirements;
- AI requirements;
- system requirements;
- security requirements;
- safety requirements;
- interoperability requirements;
- human authority requirements;
- autonomy constraints;
- TEVV requirements.

Material interfaces should have defined acceptance criteria.

---

## 5. System Architecture

The integrated architecture should identify, as applicable:

- AI components;
- data flows;
- interfaces;
- dependencies;
- users;
- external services;
- communications;
- compute resources;
- security boundaries;
- control boundaries;
- failure containment mechanisms.

Architecture documentation should support both technical assurance and operational understanding.

---

## 6. Interface Control

Interfaces can materially affect AI behaviour.

Controls should address:

- input formats;
- output formats;
- data rates;
- timing;
- error handling;
- authentication;
- access control;
- validation;
- version compatibility.

Changes to material interfaces should be subject to change control.

---

## 7. Data Flow

The integrated capability should establish traceability for material data flows:

**Source → Ingestion → Processing → AI Model → Output → User/System → Action or Decision**

Where relevant, the system should record:

- source;
- time;
- transformation;
- model version;
- output;
- uncertainty;
- downstream use.

---

## 8. Sensor Integration

Where AI depends on sensors, integration should consider:

- sensor characteristics;
- calibration;
- field of view;
- resolution;
- latency;
- availability;
- environmental degradation;
- sensor failure;
- conflicting sensor information.

AI performance should not be evaluated independently from material sensor limitations.

---

## 9. Communications

AI systems may operate under:

- reliable communications;
- intermittent communications;
- degraded communications;
- communications loss;
- disconnected conditions.

The integrated system should define expected behaviour under relevant communications states.

A capability that depends on connectivity should not implicitly be treated as equivalent to one capable of operating independently of connectivity.

---

## 10. Offline and Disconnected Operation

Where applicable, integration should establish:

- what functions remain available;
- what information becomes unavailable;
- how uncertainty changes;
- whether autonomy changes;
- what actions are permitted;
- what fail-safe state applies;
- how the system recovers after reconnection.

Operational authorisation should explicitly account for these states where relevant.

---

## 11. Human-Machine Interface

The interface should enable users to understand:

- what the AI is recommending;
- relevant evidence;
- uncertainty;
- limitations;
- system status;
- degraded conditions;
- applicable constraints;
- whether an action was proposed, approved or executed.

Interfaces should avoid creating a false impression of certainty or authority.

---

## 12. Human Authority

Integration must preserve the distinction between:

**AI Output → Human Decision → Authorised Action**

unless a separately authorised autonomy level permits a different pathway.

A system should not bypass established human authority merely because an automated interface makes an action technically possible.

---

## 13. Autonomy Integration

Where autonomous functions exist, integration should define:

- authorised autonomy level;
- conditions for activation;
- operating boundaries;
- human supervision;
- transition mechanisms;
- intervention;
- fallback;
- fail-safe;
- termination.

Autonomy should be evaluated at the integrated-system level rather than inferred from the model alone.

---

## 14. Autonomy Transitions

The system should define transitions such as:

- manual → AI-assisted;
- AI-assisted → human-authorised action;
- human-supervised → autonomous;
- autonomous → supervised;
- autonomous → manual;
- normal → degraded;
- connected → disconnected.

Transition conditions should be explicit and testable.

---

## 15. Safety Integration

Safety mechanisms should be integrated rather than treated as separate documentation.

Examples may include:

- action constraints;
- interlocks;
- bounded outputs;
- safe defaults;
- isolation;
- degradation;
- emergency shutdown;
- recovery.

Safety mechanisms must be tested in the integrated system.

---

## 16. Fail-Safe and Protective Action

Where an AI capability can create consequential harm, the integrated system should have an appropriate fail-safe mechanism.

The fail-safe should:

- be clearly defined;
- have controlled activation;
- establish a known safe or restricted state;
- be tested;
- be auditable.

Under normal circumstances, significant system concerns should follow an escalation path such as:

**Developer → AI System Manager → Operational AI Advisor → Command Authority**

Where delay could create unacceptable harm, pre-authorised emergency procedures should allow immediate protective action.

---

## 17. Security Integration

Integration can create security risks even where individual components are secure.

Assessment should consider:

- interfaces;
- credentials;
- access control;
- network exposure;
- dependencies;
- data flows;
- external services;
- update mechanisms;
- logging;
- monitoring;
- configuration.

Security controls should be assessed end-to-end.

---

## 18. Information Integrity

Integrated systems should protect against:

- corrupted data;
- stale data;
- conflicting sources;
- unauthorised modification;
- incorrect system state;
- misleading outputs.

Where information integrity is uncertain, the system should communicate the limitation to the user where relevant.

---

## 19. Time and Latency

Integration should assess:

- sensor latency;
- data-processing latency;
- model inference latency;
- network latency;
- user response time;
- downstream action latency.

For time-sensitive missions, the combined latency should be evaluated against mission requirements.

---

## 20. Resource Constraints

Integration should account for:

- compute;
- memory;
- power;
- storage;
- bandwidth;
- thermal constraints;
- processing capacity.

Performance demonstrated in a development environment may not represent performance under operational resource constraints.

---

## 21. Interoperability

Where systems interact with other capabilities, integration should assess:

- data standards;
- interface compatibility;
- semantic consistency;
- timing;
- version compatibility;
- failure handling;
- degraded interoperability.

Interoperability failures can create operational risks even when each individual system functions correctly.

---

## 22. Dependency Management

Dependencies should be identified, including:

- software libraries;
- operating systems;
- hardware;
- cloud or external services;
- communications;
- data services;
- models;
- third-party components.

Material dependencies should be included in the authorised configuration baseline.

---

## 23. Configuration Baseline

The integrated system should establish a controlled baseline covering, where applicable:

- model version;
- software version;
- hardware;
- firmware;
- data version;
- interfaces;
- configuration parameters;
- dependencies;
- security controls;
- safety controls.

The baseline should be uniquely identifiable.

---

## 24. Configuration Drift

Operational systems may diverge from their authorised baseline.

Potential sources include:

- software updates;
- model updates;
- hardware replacement;
- configuration changes;
- new data sources;
- interface changes;
- security patches;
- dependency updates.

Material drift should trigger appropriate assessment.

---

## 25. Integration Testing

Testing should establish that components work correctly together.

It may examine:

- interfaces;
- data flow;
- timing;
- error handling;
- failure recovery;
- security controls;
- safety controls;
- human interaction;
- autonomy transitions.

Integration testing should precede system-level operational evaluation.

---

## 26. End-to-End Testing

Where practical, the integrated capability should be tested from:

**Input → Processing → AI → Human/System Decision → Output/Action**

End-to-end testing can identify failures that are invisible during isolated component testing.

---

## 27. Degraded Operation

The integrated system should be evaluated under relevant degraded states, such as:

- sensor degradation;
- incomplete data;
- communications loss;
- reduced compute;
- component failure;
- conflicting information;
- abnormal system conditions.

Expected system behaviour should be documented.

---

## 28. Recovery

Recovery mechanisms should address:

- fault detection;
- containment;
- safe degradation;
- restoration;
- reinitialisation;
- data consistency;
- configuration verification.

Recovery should not silently restore an unauthorised configuration.

---

## 29. System-Level Failure Modes

Integration should identify failures arising from interactions between components.

Examples include:

- incorrect data routing;
- incompatible versions;
- interface errors;
- timing mismatch;
- cascading failures;
- unsafe automation;
- incorrect user interpretation;
- loss of human control;
- failure of safety mechanisms;
- conflicting system outputs.

---

## 30. Operational Environment

Integrated testing should progressively reflect the intended operational environment.

Evidence may progress from:

**Laboratory → Controlled Environment → Representative Environment → Adversarial/Degraded Conditions → Operational Environment**

The required depth depends on mission consequence and autonomy.

---

## 31. System-Level Uncertainty

Uncertainty can arise from:

- model output;
- data quality;
- sensor limitations;
- communications;
- system state;
- environmental conditions;
- conflicting sources.

The integrated system should avoid presenting system outputs with greater certainty than the underlying evidence supports.

---

## 32. Monitoring and Logging

Where appropriate, the integrated system should capture:

- system state;
- model version;
- configuration;
- inputs;
- outputs;
- uncertainty;
- user actions;
- overrides;
- autonomous actions;
- failures;
- alerts.

Logging should support:

- assurance;
- incident investigation;
- audit;
- accountability;
- revalidation.

---

## 33. Decision and Action Traceability

For consequential AI-supported decisions, the system should support reconstruction of:

**Who → Used Which System → In Which Configuration → Received What Information → AI Output → Human Decision → Action → Outcome**

The level of traceability should reflect the consequence of the use case.

---

## 34. Integration Change Management

Material integration changes should be assessed for effects on:

- performance;
- safety;
- security;
- autonomy;
- human authority;
- mission effectiveness;
- operational environment;
- assurance;
- operational authorisation.

---

## 35. Integration Exit Criteria

Before proceeding to formal system-level TEVV or operational readiness, the responsible authority should establish that:

- architecture is documented;
- interfaces are controlled;
- dependencies are identified;
- configuration baseline is established;
- human authority is preserved;
- autonomy behaviour is defined;
- safety controls are integrated;
- security controls are addressed;
- degraded operation is considered;
- recovery mechanisms are assessed;
- system-level testing is complete to the required stage;
- material limitations are documented;
- evidence is retained.

---

## 36. System Integration Record

A System Integration Record should include, as applicable:

| Field | Description |
|---|---|
| System ID | Unique system identifier |
| Integration Version | Controlled integration version |
| AI Model | Model and version |
| Architecture | Integrated architecture |
| Interfaces | Material interfaces |
| Data Flows | Relevant data pathways |
| Dependencies | Material dependencies |
| Configuration | Controlled configuration |
| Human Authority | Decision/action authority |
| Autonomy | Authorised autonomy level |
| Safety | Safety controls |
| Security | Security controls |
| Testing | Integration test results |
| Degraded Modes | Expected degraded behaviour |
| Recovery | Recovery mechanisms |
| Limitations | Known limitations |
| Evidence | Supporting evidence |
| Owner | Responsible authority |
| Status | Lifecycle status |

---

## 37. Core Rules

1. **A validated model is not automatically a validated system.**
2. **Integration can introduce new operational risks.**
3. **Material interfaces must be controlled and tested.**
4. **AI behaviour must remain traceable after integration.**
5. **Human authority must not be weakened by system architecture.**
6. **Autonomy must be assessed at the integrated-system level.**
7. **Safety and security controls must be tested end-to-end.**
8. **Disconnected and degraded states must be considered where relevant.**
9. **Material dependencies must be included in the configuration baseline.**
10. **Configuration drift must be detected and assessed.**
11. **System-level evidence must complement component-level evidence.**
12. **Consequential decisions and actions should be reconstructable to an appropriate degree.**
13. **Material integration changes may require revalidation or reauthorisation.**
14. **Operational authorisation applies to the integrated capability, not merely the underlying model.**

---

## 38. Golden Thread

System Integration maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Integration → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

---

## 39. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 AI Requirements** — defines system and integration requirements.
- **03 AI Development** — governs development of AI components.
- **05 Data & Information** — governs data flows and integrity.
- **06 AI Security** — governs security of integrated systems.
- **07 Supply Chain & Sovereignty** — governs dependencies.
- **08 Human Authority** — establishes human decision and action authority.
- **09 TEVV** — provides system-level testing and evaluation.
- **10 Operational Environment** — defines representative operational conditions.
- **11 Operational Authorisation** — authorises the integrated capability.
- **12 Operational Employment** — governs actual use.
- **13 Continuous Assurance** — monitors operational behaviour.
- **15 Change & Reauthorisation** — governs material integration changes.
- **16 Audit & Evidence** — preserves integration evidence.
- **24 Architecture & Technical Controls** — provides deeper technical architecture controls.

---

## 40. Summary Model

```text
AI Model
   +
Data
   +
Software
   +
Hardware
   +
Sensors
   +
Communications
   +
Interfaces
   +
Human Users
   +
Dependencies
        ↓
System Integration
        ↓
Configuration Baseline
        ↓
Integration Testing
        ↓
End-to-End Testing
        ↓
Degraded / Adversarial Assessment
        ↓
System-Level TEVV
        ↓
Assurance
        ↓
Operational Authorisation
        ↓
Operational Employment
        ↓
Continuous Monitoring
        ↓
Change / Incident
        ↓
Revalidation / Reauthorisation
```

System Integration converts individual AI components into a controlled, traceable and assessable operational capability.
