# 29 Operational Authorisation Interoperability and External Dependency Governance

## 1. Purpose

Defence AI capabilities may depend on systems, data, infrastructure, services or organisations outside their immediate governance boundary.

Interoperability can improve operational effectiveness, but it can also introduce new dependencies, trust relationships, information flows, failure modes and authority ambiguities.

This document defines governance for interoperability and externally connected dependencies that may affect operational authorisation.

The objective is to ensure that:

- external dependencies are identified;
- trust boundaries are explicit;
- authority remains within defined limits;
- information exchanged across boundaries is governed;
- external changes do not silently invalidate authorisation;
- interoperability failures have defined responses;
- cross-organisational responsibilities are clear; and
- operational assurance remains traceable.

---

## 2. Core Principle

**Interoperability does not transfer operational authority.**

Connecting a Defence AI capability to another system, organisation, data source or service shall not automatically expand its authorised mission, autonomy, information access or ability to act.

Where interoperability materially changes risk or operational behaviour, the connected arrangement should be assessed and, where required, reauthorised.

---

## 3. Interoperability Object

The governance object may be represented as:

**AI Capability × External System/Service × Information Flow × Mission × Environment × Autonomy × Human Authority**

The assessment should reflect the actual operational dependency rather than only the technical interface.

---

## 4. Types of External Dependency

External dependencies may include:

- data providers;
- sensor systems;
- communications networks;
- navigation services;
- compute infrastructure;
- cloud services;
- software services;
- identity services;
- security services;
- model providers;
- external AI systems;
- maintenance organisations;
- suppliers;
- coalition partners;
- government organisations; or
- other authorised entities.

Each material dependency should have an identified owner and risk profile.

---

## 5. Trust Boundaries

The organisation should identify trust boundaries between:

- AI capability and external systems;
- military and non-military systems;
- internal and external networks;
- different organisational authorities;
- different security domains;
- different data-governance regimes; and
- different AI governance regimes.

Trust should not be inferred solely from interoperability or technical connectivity.

---

## 6. External Authority

External organisations may provide:

- information;
- technical services;
- maintenance;
- assurance evidence;
- recommendations;
- infrastructure; or
- other support.

They should not acquire operational decision authority merely because their service is technically essential.

Operational authority should remain explicitly assigned to the authorised human or organisational authority.

---

## 7. Information Exchange

Information exchanged across organisational or system boundaries should be governed for:

- purpose;
- provenance;
- integrity;
- timeliness;
- uncertainty;
- classification or handling requirements;
- access;
- retention;
- transformation;
- permitted use; and
- accountability.

AI systems should not treat externally supplied information as inherently trustworthy.

---

## 8. External AI Outputs

Where an external AI system provides information or recommendations, the receiving capability should identify, where practicable:

- source;
- system identity;
- model/version where relevant;
- provenance;
- limitations;
- uncertainty;
- intended purpose;
- assurance status; and
- applicable restrictions.

The receiving system should not automatically convert an external recommendation into authorised action.

---

## 9. External Model or Service Dependency

Where operational capability depends on an externally provided model or service, the authorisation record should identify:

- provider;
- service/model identity;
- version;
- dependency;
- criticality;
- update mechanism;
- availability requirements;
- security requirements;
- fallback arrangements;
- assurance evidence; and
- change-notification arrangements.

Critical external dependencies should have continuity and resilience measures.

---

## 10. Dependency Criticality

A dependency may be classified according to the consequence of its failure.

A working scale may be:

| Level | Meaning |
|---|---|
| **D1 — Low** | Failure has limited operational effect. |
| **D2 — Moderate** | Failure requires compensating controls or reduced capability. |
| **D3 — Significant** | Failure materially affects mission performance or assurance. |
| **D4 — Critical** | Failure may invalidate authorised employment or human control. |

The scale should be adapted to the organisation's risk methodology.

---

## 11. Dependency Failure

For each critical dependency, the organisation should determine:

**Dependency → Failure Mode → Operational Effect → Risk → Control → Fallback → Recovery**

Possible responses include:

**Continue → Restrict → Reduce Capability → Reduce Autonomy → Human Control → Safe State → Suspend**

The response should be defined before critical dependency failure occurs.

---

## 12. External Change

External providers may change:

- models;
- software;
- interfaces;
- infrastructure;
- data;
- security controls;
- service availability;
- terms of service;
- personnel;
- supply chain;
- dependencies; or
- operational assumptions.

The organisation should have mechanisms for identifying changes that may affect the assurance or authorisation basis.

---

## 13. Change Notification

Where practicable, material external dependencies should be subject to change-notification requirements.

Notification should address changes capable of affecting:

- model behaviour;
- system performance;
- security;
- data;
- interfaces;
- availability;
- autonomy;
- human control;
- mission effectiveness; or
- assurance evidence.

Silence from a supplier should not be treated as evidence that no material change occurred.

---

## 14. Uncontrolled External Updates

Operational authorisation should address whether external components may update automatically.

Where automatic updates could materially affect behaviour, the organisation should consider:

- update controls;
- version identification;
- approval requirements;
- testing;
- rollback;
- monitoring;
- notification;
- revalidation; and
- reauthorisation.

An externally updated component should not automatically inherit the authorisation of its previous version.

---

## 15. Interoperability Configuration

The authorised configuration should identify, where applicable:

- participating systems;
- interfaces;
- protocols;
- versions;
- data flows;
- dependencies;
- authentication;
- security controls;
- autonomy relationships; and
- human-control mechanisms.

Configuration should be sufficiently defined to establish what was actually authorised.

---

## 16. Interface Assurance

Interfaces should be assessed for:

- correctness;
- data integrity;
- timing;
- availability;
- authentication;
- authorisation;
- error handling;
- uncertainty propagation;
- failure behaviour;
- security; and
- resilience.

Interface testing should reflect realistic operational conditions.

---

## 17. Cross-Organisational Responsibility

Where several organisations participate, responsibilities should be defined for:

- system ownership;
- operational authority;
- technical responsibility;
- security;
- data;
- assurance;
- incident response;
- change notification;
- continuity;
- risk ownership; and
- authorisation.

Responsibility gaps should be treated as governance risks.

---

## 18. Coalition and Partner Interoperability

Where interoperability involves external or coalition partners, governance should address:

- differing authorisation regimes;
- legal authorities;
- security requirements;
- information-sharing restrictions;
- data handling;
- human decision rights;
- autonomy limitations;
- configuration control;
- assurance evidence;
- incident reporting; and
- termination of interoperability.

A partner's authorisation should not automatically constitute authorisation under the receiving organisation's governance regime.

---

## 19. External Data Dependencies

External data should be assessed for:

- provenance;
- accuracy;
- completeness;
- timeliness;
- representativeness;
- integrity;
- distribution shift;
- manipulation;
- availability; and
- permitted use.

Critical decisions should not rely on external data whose integrity or provenance cannot be reasonably established.

---

## 20. External Security Dependencies

Security dependencies may include:

- identity;
- authentication;
- encryption;
- monitoring;
- threat intelligence;
- endpoint protection;
- software repositories;
- update services; or
- security management.

Loss or compromise of a critical security dependency may affect the validity of operational authority.

---

## 21. External Human Services

Some AI capabilities may depend on external human expertise or support.

This may include:

- specialist technical support;
- maintenance;
- data annotation;
- model operations;
- assurance;
- incident response;
- infrastructure support; or
- subject-matter expertise.

The organisation should determine which external human dependencies are critical to maintaining safe and authorised employment.

---

## 22. Human Authority Across Boundaries

Where decisions cross organisational boundaries, the governance record should identify:

- originating authority;
- receiving authority;
- decision rights;
- approval requirements;
- escalation;
- intervention;
- accountability; and
- termination authority.

AI systems should not bridge organisational authority gaps automatically.

---

## 23. External Dependency and Autonomy

A critical external dependency may effectively constrain the authorised autonomy of a capability.

For example, if a capability requires an external service to maintain reliable situational information, loss of that service may require:

- reduced autonomy;
- increased human supervision;
- restricted operation;
- safe state; or
- suspension.

Autonomy should therefore be assessed in relation to dependencies, not only system design.

---

## 24. External Dependency and Human Control

Where human supervision depends on an external service, the organisation should determine whether meaningful human control remains possible if that service becomes unavailable.

Loss of a critical human-control dependency should trigger the predefined response.

---

## 25. Monitoring External Dependencies

Critical dependencies should be monitored for:

- availability;
- performance;
- integrity;
- security;
- version;
- configuration;
- service changes;
- data quality;
- latency;
- failure indicators; and
- assurance status.

Monitoring should be proportionate to consequence and dependency criticality.

---

## 26. Interoperability Incidents

An interoperability incident may involve:

- incorrect data exchange;
- interface failure;
- conflicting outputs;
- unexpected system interaction;
- compromised external service;
- unauthorised access;
- data-integrity failure;
- loss of critical dependency;
- unexpected model update; or
- loss of human-control capability.

Incident assessment should determine whether connected capabilities are affected.

---

## 27. Termination of External Connectivity

The organisation should define conditions under which interoperability must be terminated or restricted.

These may include:

- security compromise;
- loss of trust;
- material integrity concern;
- unacceptable performance;
- unapproved change;
- dependency failure;
- legal or policy change;
- loss of required assurance; or
- inability to maintain human control.

Termination should be controlled and recorded.

---

## 28. Recovery and Reconnection

Reconnection following an interruption should not automatically restore full interoperability.

Before restoration, the organisation should verify, as applicable:

- system identity;
- configuration;
- security;
- interface integrity;
- data integrity;
- dependency status;
- authorisation;
- human authority; and
- operational readiness.

Material changes may require revalidation or reauthorisation.

---

## 29. Evidence and Assurance

Interoperability assurance should provide evidence that:

- interfaces function as intended;
- dependencies are understood;
- failure modes are known;
- security controls are effective;
- information remains trustworthy;
- human authority is preserved;
- autonomy remains within approved limits; and
- operational outcomes remain traceable.

Evidence should be linked to the relevant Assurance and Authorisation Records.

---

## 30. Dependency Register

A controlled Dependency Register should identify, as applicable:

- dependency;
- provider;
- owner;
- purpose;
- criticality;
- interface;
- authorised use;
- failure mode;
- fallback;
- monitoring;
- change notification;
- security requirements;
- assurance status;
- continuity arrangement; and
- termination criteria.

---

## 31. Governance Review

Interoperability arrangements should be reviewed when:

- a dependency changes;
- a provider changes;
- an interface changes;
- a model changes;
- a mission changes;
- autonomy changes;
- the operational environment changes;
- a security incident occurs;
- an interoperability incident occurs; or
- assurance evidence becomes outdated.

---

## 32. Relationship to Supply Chain and Sovereignty

External interoperability should connect with:

- supply-chain risk;
- provenance;
- strategic dependency;
- sovereignty;
- continuity;
- supplier assurance;
- change control; and
- reauthorisation.

An operationally critical external dependency should be visible within the wider D-AIGAAF governance architecture.

---

## 33. Relationship to Continuous Assurance

The control loop is:

**Dependency Monitoring → Change/Failure Detection → Impact Assessment → Risk → Assurance → Restriction/Recovery/Revalidation/Reauthorisation**

This prevents external dependencies from becoming invisible assumptions.

---

## 34. Golden Thread

Interoperability remains connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Readiness → Deployment → Employment → Monitoring → Change/Incident → Revalidation → Reauthorisation**

---

## 35. Governance Questions

Responsible authorities should be able to determine:

1. What external systems or services does the capability depend on?
2. Which dependencies are critical?
3. Who owns each dependency?
4. What information crosses the boundary?
5. What trust boundaries exist?
6. Who holds operational authority?
7. Can an external system influence consequential decisions?
8. Can an external dependency increase effective autonomy?
9. How are external AI outputs identified and assessed?
10. How are uncertainty and provenance preserved?
11. What happens if a critical dependency fails?
12. Can human control be maintained without the dependency?
13. How are external changes detected?
14. Can external components update automatically?
15. What changes require revalidation?
16. What changes require reauthorisation?
17. How are coalition or partner differences governed?
18. What triggers termination of interoperability?
19. How is reconnection controlled?
20. Can the combined arrangement remain within its authorised boundaries?

---

## 36. Core Rule

> **Interoperability and external dependencies shall be governed as part of the operational authorisation basis where they can materially affect mission performance, risk, autonomy, human control, security, information integrity or continuity. Connection to an external system, service or organisation shall not create implied operational authority, and material changes or failures in critical dependencies shall trigger proportionate restriction, assurance, revalidation or reauthorisation as required.**
