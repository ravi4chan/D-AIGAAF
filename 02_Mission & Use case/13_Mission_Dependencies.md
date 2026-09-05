# Mission Dependencies

## 1. Purpose

Mission Dependencies identifies external conditions, systems, services, people, organisations and resources on which an AI-enabled mission depends.

The purpose is to ensure that dependency failure is considered as part of mission risk, assurance, operational authorisation and continuous monitoring.

---

## 2. Core Principle

An AI capability is rarely operationally independent.

> **A capability should be authorised with an understanding of the dependencies required for it to perform its intended mission safely and effectively.**

A dependency that can materially affect mission performance, human control, security or authority must be explicitly identified and managed.

---

## 3. Dependency Scope

Mission dependencies may include:

- data;
- sensors;
- communications;
- navigation;
- positioning;
- computing;
- power;
- infrastructure;
- software;
- models;
- external services;
- personnel;
- suppliers;
- maintenance;
- logistics;
- security services;
- command systems;
- other AI systems.

---

## 4. Dependency Categories

### 4.1 Data Dependencies

Examples include:

- operational data;
- training data;
- reference data;
- maps;
- imagery;
- intelligence feeds;
- metadata;
- external data services.

Data dependencies should include requirements for availability, integrity, provenance and timeliness.

### 4.2 Sensor Dependencies

Examples include:

- cameras;
- radar;
- electro-optical systems;
- navigation sensors;
- environmental sensors;
- other mission-specific sensing systems.

The impact of sensor degradation or loss should be understood.

### 4.3 Communications Dependencies

Examples include:

- tactical networks;
- radio systems;
- satellite communications;
- fixed networks;
- local links;
- data links.

Dependency analysis should consider latency, bandwidth, intermittent connectivity and complete loss of communications.

### 4.4 Computing Dependencies

Examples include:

- edge computing;
- servers;
- accelerators;
- storage;
- operating systems;
- virtualisation;
- local processing infrastructure.

The capability should identify what happens when computing resources are degraded or unavailable.

### 4.5 Power Dependencies

Examples include:

- batteries;
- generators;
- fixed power;
- vehicle power;
- energy storage.

Power loss may affect availability, safe shutdown and recovery.

### 4.6 Human Dependencies

Examples include:

- operators;
- commanders;
- maintainers;
- analysts;
- AI specialists;
- security personnel;
- technical support.

Human availability and competency may be prerequisites for safe employment.

### 4.7 Infrastructure Dependencies

Examples include:

- data centres;
- command facilities;
- network infrastructure;
- physical security;
- environmental control;
- transport infrastructure.

### 4.8 Software and Model Dependencies

Examples include:

- operating systems;
- libraries;
- APIs;
- model components;
- runtime environments;
- update services;
- third-party software.

Critical dependencies should have identified provenance and configuration status.

### 4.9 External Service Dependencies

Examples include:

- external data providers;
- hosted services;
- cloud services;
- positioning services;
- third-party APIs.

External services should not be assumed to remain available or trustworthy without appropriate evidence.

### 4.10 Supply-Chain Dependencies

Dependencies may exist on:

- vendors;
- subcontractors;
- component manufacturers;
- software suppliers;
- model developers;
- maintenance providers.

Supply-chain dependency should be considered in relation to sovereignty, continuity, security and change.

---

## 5. Dependency Criticality

Dependencies should be classified according to their effect on the mission.

A working classification may include:

- **D1 — Non-Critical:** failure has limited mission effect.
- **D2 — Supporting:** failure reduces performance but alternatives exist.
- **D3 — Significant:** failure materially degrades mission effectiveness.
- **D4 — Critical:** failure may make the mission unsafe, ineffective or unauthorised.
- **D5 — Mission-Critical:** failure may create unacceptable consequence, loss of control or inability to perform a critical function.

The classification should be validated against the specific mission.

---

## 6. Single Points of Failure

The dependency assessment should identify single points of failure.

Examples include:

- one communications link;
- one data source;
- one positioning service;
- one supplier;
- one specialist operator;
- one computing platform;
- one external service.

Where a dependency is critical and has no credible alternative, this should be explicitly recorded.

---

## 7. Dependency Relationships

Dependencies may be:

**Direct**

The AI capability directly requires the dependency.

**Indirect**

A supporting system depends on another service.

**Cascading**

Failure of one dependency causes failure in several dependent systems.

**Shared**

Multiple capabilities depend on the same underlying service.

Shared dependencies can create correlated failure across multiple missions.

---

## 8. Dependency Failure Modes

Dependency failure may result from:

- technical failure;
- cyber compromise;
- physical disruption;
- environmental conditions;
- communications loss;
- power loss;
- supplier failure;
- software change;
- model change;
- data degradation;
- human unavailability;
- policy or legal change.

The assessment should consider both accidental and deliberate failure.

---

## 9. Dependency Resilience

Critical dependencies should be assessed for:

- redundancy;
- diversity;
- backup;
- failover;
- graceful degradation;
- manual alternatives;
- recovery capability;
- replacement time.

Resilience should be proportionate to mission consequence.

---

## 10. Dependency Loss and Mission Continuity

For each critical dependency, the use case should identify what happens when it becomes unavailable.

Possible responses include:

- continue normally;
- continue with reduced capability;
- reduce autonomy;
- transfer to human control;
- switch to an alternative dependency;
- suspend the use case;
- invoke fail-safe;
- terminate the mission activity.

The response should be explicitly defined where the consequence warrants it.

---

## 11. Dependency Loss and Human Control

A dependency may support the ability of a human to supervise or intervene.

Examples include:

- communications required for human approval;
- displays required for situational awareness;
- authentication required for intervention;
- power required for override;
- network connectivity required for shutdown.

Loss of such dependencies may change the effective human-control level.

---

## 12. Dependency Loss and Autonomy

Loss of dependencies may require a change in autonomy.

For example:

**Normal Conditions → Reduced Communications → Reduced Autonomy**

**Reliable Sensors → Sensor Degradation → Restricted Operation**

**Full Human Connectivity → Communications Loss → Predefined Safe Behaviour**

Autonomy should therefore be conditional on the dependencies necessary to support it.

---

## 13. Dependency and Operational Boundaries

Dependencies should be reflected in the operational envelope.

If a capability requires a specific dependency, the absence or degradation of that dependency may constitute an operational boundary condition.

Example:

> If the required navigation source is unavailable beyond the validated tolerance, the affected autonomous function is suspended.

---

## 14. Dependency and Risk

Dependency analysis should feed directly into risk assessment.

The relationship is:

**Dependency → Failure Condition → Mission Impact → Risk → Control → Evidence → Authority**

Critical dependencies should be linked to the relevant risk records.

---

## 15. Dependency and TEVV

Where a dependency materially affects mission performance, its failure should be considered in TEVV.

Testing may include:

- communications loss;
- sensor loss;
- data-source failure;
- power degradation;
- computing degradation;
- external-service outage;
- human unavailability;
- dependency substitution.

Testing should establish whether the system behaves as expected when critical dependencies fail.

---

## 16. Dependency and Assurance

Assurance should identify whether evidence supports claims under relevant dependency conditions.

Evidence should distinguish:

- fully supported dependencies;
- conditionally supported dependencies;
- untested dependencies;
- known dependency limitations;
- residual dependency risk.

A system should not be considered resilient merely because its primary dependencies work under ideal conditions.

---

## 17. Dependency and Security

Dependencies can introduce security exposure.

The assessment should consider:

- trust relationships;
- privileged access;
- external connections;
- shared infrastructure;
- software provenance;
- update channels;
- supplier access;
- data pathways.

Critical dependencies should have appropriate security controls.

---

## 18. Dependency and Supply-Chain Sovereignty

Where dependency on an external supplier or jurisdiction materially affects mission continuity, security or authority, the dependency should be assessed for:

- ownership;
- provenance;
- jurisdiction;
- availability;
- substitutability;
- supplier concentration;
- update control;
- support continuity.

Sovereignty requirements should be determined by applicable policy and mission need.

---

## 19. Dependency Monitoring

Material dependencies should be monitored where practical.

Monitoring may include:

- availability;
- performance;
- integrity;
- security status;
- version;
- configuration;
- supplier status;
- data quality;
- service status.

Monitoring should provide sufficient warning to support appropriate operational decisions.

---

## 20. Dependency Change

Changes to a dependency may change the assurance position.

Examples include:

- new supplier;
- new software library;
- new model component;
- new communications architecture;
- changed data source;
- changed infrastructure;
- changed external service;
- changed hardware.

The significance of a dependency change should be determined by its potential effect on behaviour, risk, security or operational authority.

---

## 21. Dependency Reassessment Triggers

Reassessment should occur when:

- a critical dependency changes;
- a dependency is degraded;
- a dependency is compromised;
- a dependency becomes unavailable;
- a new dependency is introduced;
- a single point of failure emerges;
- supplier conditions change;
- evidence no longer represents the dependency configuration;
- an incident reveals an unrecognised dependency.

---

## 22. Dependency Register

A Mission Dependency Register should contain, as applicable:

| Field | Description |
|---|---|
| Dependency ID | Unique identifier |
| Dependency | System, service, person or resource |
| Category | Data, sensor, communications, etc. |
| Criticality | D1–D5 or validated equivalent |
| Owner | Responsible authority |
| Provider | Internal or external provider |
| Purpose | Mission function supported |
| Failure Mode | How dependency may fail |
| Mission Impact | Effect of failure |
| Control | Mitigation |
| Alternative | Backup or substitute |
| Monitoring | Monitoring mechanism |
| Security Status | Relevant security condition |
| Configuration | Relevant baseline/version |
| Evidence | Supporting evidence |
| Review Date | Reassessment date |

---

## 23. Dependency Recovery

Recovery planning should consider:

- detection;
- diagnosis;
- failover;
- restoration;
- validation;
- return to service;
- human confirmation where required.

Recovery should not automatically restore the highest level of autonomy or authority.

---

## 24. Dependency Recovery and Reauthorisation

Following significant dependency failure or change, the organisation should determine whether:

- existing authority remains valid;
- restricted operation is appropriate;
- revalidation is required;
- reauthorisation is required.

Restoring technical availability does not necessarily restore operational authority.

---

## 25. Dependency Escalation

Escalation should occur when:

- a critical dependency fails;
- multiple dependencies fail;
- a dependency becomes compromised;
- human control is degraded;
- operational boundaries are approached;
- mission consequence increases;
- an unrecognised dependency is discovered.

Escalation authority should be predefined.

---

## 26. Dependency Assumptions

Dependency assumptions should be linked to `Operational_Assumptions.md`.

Where safe operation depends on an assumption such as communications availability, that assumption should be:

- explicit;
- monitored where practical;
- tested where material;
- linked to a defined response.

---

## 27. Operational Dependency Record

The operational record should capture material dependency events, including:

- dependency availability;
- degradation;
- failure;
- substitution;
- recovery;
- operational impact;
- human response;
- autonomy change;
- suspension;
- fail-safe activation.

This creates evidence for continuous assurance and future reauthorisation.

---

## 28. Minimum Mission Dependency Requirements

For consequential AI use cases:

1. Material dependencies should be identified.
2. Critical dependencies should be classified.
3. Single points of failure should be identified.
4. Dependency failure modes should be assessed.
5. Critical dependency loss should have a defined operational response.
6. Dependencies affecting human control should be explicitly assessed.
7. Dependencies affecting autonomy should be explicitly assessed.
8. Critical dependencies should inform TEVV.
9. Dependency risks should inform assurance.
10. Security and supply-chain implications should be assessed.
11. Material dependencies should be monitored where feasible.
12. Significant dependency changes should trigger reassessment.
13. Dependency failure should not automatically restore authority after recovery.
14. Dependency information should be traceable through the Golden Thread.

---

## 29. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Golden Thread`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Operational_Scenarios.md`
- `02 Mission & Use Case/Operational_Boundaries.md`
- `02 Mission & Use Case/Operational_Assumptions.md`
- `02 Mission & Use Case/Mission_Threat_Context.md`
- `03 Risk & Autonomy`
- `05 Data & Information`
- `06 AI Security`
- `07 Supply Chain & Sovereignty`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`

Mission Dependencies establishes the connection between AI capability and the wider systems, people, services and infrastructure required for safe and effective mission employment.

---

## 30. Summary

AI-enabled missions depend on more than the AI system itself.

A communications link, data source, sensor, power system, specialist, software component or external service may be essential to safe operation and human control.

D-AIGAAF therefore treats material dependencies as part of the operational assurance and authorisation problem.

The central principle is:

> **A mission should not be treated as independently resilient when its AI capability, human control or operational authority depends on critical systems, services, people or conditions that have not been explicitly identified and assessed.**
