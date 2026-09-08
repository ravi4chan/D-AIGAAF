# 06 — Assurance of Environment, Security and Dependencies

## 1. Purpose

This document defines how D-AIGAAF maintains continuing assurance that a Defence AI capability remains suitable for its authorised operational environment, secure against relevant threats and adequately supported by its critical dependencies.

The focus is on the continuing validity of environmental, security and dependency assumptions established during earlier lifecycle stages.

---

## 2. Core Principle

> **Continuing assurance shall establish that the operational environment, security posture and critical dependencies remain consistent with the conditions under which the Defence AI capability was assessed and authorised. Material environmental change, security degradation or dependency failure shall trigger proportionate assessment and, where necessary, restriction, intervention, revalidation, reauthorisation or suspension.**

---

## 3. Assurance Object

The assurance object is:

**AI Capability × Mission × Environment × Security × Dependencies × Autonomy × Human Authority × Configuration**

This ensures that technical assurance is not separated from the conditions required for safe and authorised operation.

---

## 4. Environmental Assurance

Environmental assurance should determine whether:

- the capability remains within its assessed operating envelope;
- environmental assumptions remain valid;
- environmental monitoring remains effective;
- material environmental changes are detected;
- degraded conditions remain supported where authorised.

---

## 5. Environmental Domains

Relevant domains may include:

- physical environment;
- terrain;
- weather;
- illumination;
- sensor environment;
- electromagnetic environment;
- communications;
- navigation;
- information environment;
- computing environment;
- human environment;
- adversarial environment.

---

## 6. Environmental Baseline

The organisation should maintain an environmental baseline identifying:

- expected conditions;
- boundary conditions;
- known limitations;
- dependencies;
- monitoring requirements;
- applicable evidence.

The baseline should support comparison with actual operational conditions.

---

## 7. Environmental Change

Environmental changes should be assessed for potential impact on:

- AI performance;
- data quality;
- sensors;
- communications;
- navigation;
- human control;
- autonomy;
- mission effectiveness.

Material changes should trigger the applicable change-assessment process.

---

## 8. Environmental Boundary Assurance

Assurance should establish whether the capability remains within:

- geographic boundaries;
- physical conditions;
- weather conditions;
- sensor conditions;
- electromagnetic conditions;
- communications conditions;
- information conditions;
- human operating conditions.

Boundary uncertainty should be treated as an assurance concern.

---

## 9. Degraded Environment Assurance

Where degraded operation is authorised, evidence should demonstrate continued suitability under relevant:

- communications loss;
- sensor degradation;
- navigation uncertainty;
- data degradation;
- computing limitations;
- dependency failure.

Normal-condition evidence should not automatically be assumed to apply.

---

## 10. Disconnected Operation

Where disconnected operation is authorised, assurance should establish:

- permitted local functionality;
- autonomy restrictions;
- local human-control arrangements;
- local monitoring;
- recording capability;
- safe-state behaviour;
- recovery arrangements.

---

## 11. Adversarial Environment Assurance

Assurance should consider whether deliberate interference could affect:

- AI inputs;
- sensors;
- data;
- communications;
- navigation;
- interfaces;
- models;
- system integrity;
- human decision-making.

Relevant adversarial evidence should remain current.

---

## 12. Security Assurance

Security assurance should establish whether relevant security controls remain effective against current threats.

Domains may include:

- identity;
- access;
- data;
- model;
- software;
- hardware;
- interfaces;
- communications;
- dependencies;
- supply chain.

---

## 13. Security Baseline

A security baseline should identify:

- applicable controls;
- known threats;
- expected security conditions;
- monitoring requirements;
- known limitations;
- response arrangements.

Changes to the threat environment should be assessed against this baseline.

---

## 14. Security Change

Security assurance should be reassessed following:

- significant vulnerabilities;
- new attack methods;
- security incidents;
- compromised credentials;
- integrity concerns;
- supplier compromise;
- software changes;
- model changes;
- architecture changes.

---

## 15. Model Integrity

Where relevant, assurance should establish confidence in:

- model identity;
- model integrity;
- approved version;
- deployment integrity;
- update status;
- protection against unauthorised modification.

Unexpected model behaviour should be assessed alongside model-integrity evidence.

---

## 16. Data Integrity

Continuing assurance should consider:

- data provenance;
- integrity;
- authenticity;
- completeness;
- timeliness;
- manipulation;
- poisoning indicators.

Data integrity concerns should be evaluated for their effect on AI outputs and mission decisions.

---

## 17. Software and Configuration Security

Assurance should consider whether:

- approved software remains deployed;
- configuration remains controlled;
- security patches are governed;
- interfaces remain trusted;
- unauthorised changes are detected.

Security controls should remain aligned with the authorised configuration.

---

## 18. Dependency Assurance

Critical dependencies should be identified and monitored.

Dependencies may include:

- communications;
- navigation;
- sensors;
- computing;
- power;
- external information;
- software libraries;
- cloud or hosted services;
- supporting AI systems.

---

## 19. Dependency Criticality

Dependencies should be classified according to their effect on:

- mission;
- safety;
- human control;
- autonomy;
- security;
- continuity.

Critical dependencies should receive proportionate assurance attention.

---

## 20. Dependency Failure

Where a critical dependency fails, the organisation should determine:

- what functionality is affected;
- whether autonomy changes;
- whether human control remains effective;
- whether mission continuation is appropriate;
- whether safe state or suspension is required.

Technical availability alone should not determine continuation.

---

## 21. Dependency Change

Material dependency changes should be assessed before continued unrestricted employment.

Examples include:

- supplier change;
- component replacement;
- software dependency update;
- interface change;
- hosting change;
- communications architecture change;
- external service change.

---

## 22. Dependency Resilience

Assurance should consider:

- redundancy;
- fallback;
- recovery;
- single points of failure;
- degraded operation;
- alternative dependencies.

Where dependency failure could create unacceptable consequences, appropriate resilience should be demonstrated.

---

## 23. Environmental and Security Interaction

Environmental conditions may affect security, and security events may affect environmental awareness.

Examples include:

- communications disruption;
- sensor deception;
- navigation interference;
- electromagnetic effects;
- manipulated information.

Assurance should consider these interactions rather than treating domains as completely independent.

---

## 24. Environmental and Dependency Interaction

Environmental changes may increase dependency reliance.

For example:

- degraded sensors may increase dependence on other information sources;
- communications loss may increase local computing dependence;
- navigation degradation may affect autonomous functions.

These interactions should be reflected in assurance assessments.

---

## 25. Security and Dependency Interaction

A dependency may introduce security risk.

Assurance should consider:

- trust relationships;
- shared infrastructure;
- external services;
- software dependencies;
- supplier access;
- data flows.

---

## 26. Multi-Factor Degradation

Multiple simultaneous changes may create a risk greater than the sum of individual changes.

Examples include:

**Communications Degradation + Sensor Degradation + Increased Autonomy**

or

**Security Concern + Dependency Failure + Reduced Human Availability**

Such combinations should receive explicit assessment where foreseeable.

---

## 27. Environmental Indicators

Useful indicators may include:

- operating conditions;
- sensor availability;
- communication quality;
- navigation quality;
- electromagnetic conditions;
- information availability;
- boundary excursions.

---

## 28. Security Indicators

Useful indicators may include:

- integrity alerts;
- access anomalies;
- unusual system behaviour;
- data anomalies;
- model-integrity concerns;
- vulnerability status;
- security incidents.

---

## 29. Dependency Indicators

Useful indicators may include:

- availability;
- latency;
- integrity;
- failure rate;
- degradation;
- recovery time;
- redundancy status.

---

## 30. Assurance Thresholds

Thresholds should identify conditions requiring additional action.

Possible outcomes include:

**Continue → Enhanced Monitoring → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

The applicable response should depend on consequence and assurance evidence.

---

## 31. Assurance Evidence

Evidence may include:

- environmental observations;
- operational monitoring;
- security assessments;
- incident records;
- dependency testing;
- configuration records;
- supplier evidence;
- resilience testing;
- TEVV results.

---

## 32. Evidence Currency

Environmental, security and dependency evidence should be reviewed when:

- conditions change;
- threats change;
- dependencies change;
- incidents occur;
- configurations change;
- new operational evidence emerges.

---

## 33. Independent Challenge

For high-consequence capabilities, appropriate independent challenge should examine:

- environmental assumptions;
- security assumptions;
- dependency assumptions;
- evidence sufficiency;
- resilience;
- control effectiveness.

---

## 34. Findings

Material findings may include:

- unsupported environmental conditions;
- ineffective security control;
- critical dependency weakness;
- invalid assumption;
- inadequate monitoring;
- insufficient resilience;
- unexpected degradation.

Findings should enter the corrective-action process.

---

## 35. Corrective Action

Corrective actions may include:

- new controls;
- additional testing;
- environmental restriction;
- security improvement;
- dependency replacement;
- redundancy;
- reduced autonomy;
- increased human supervision.

---

## 36. Revalidation

Revalidation should be considered where evidence indicates that:

- environmental assumptions have changed;
- security threats have materially changed;
- dependency behaviour has changed;
- previous evidence is no longer representative.

---

## 37. Reauthorisation

Reauthorisation may be required where material changes affect:

- mission;
- environment;
- security conditions;
- dependencies;
- autonomy;
- human authority;
- operational boundaries.

---

## 38. Suspension

Employment should be restricted or suspended where:

- the environment is outside the demonstrated envelope;
- critical security controls fail;
- critical dependencies become unsafe;
- human control is compromised;
- assurance is materially insufficient.

---

## 39. Recovery

Recovery should establish:

- restored environment suitability;
- system integrity;
- security;
- dependency availability;
- human authority;
- autonomy;
- configuration;
- authorisation.

Restoration should not automatically restore unrestricted operational authority.

---

## 40. Governance Questions

The organisation should be able to answer:

1. What environmental assumptions support assurance?
2. How are environmental changes detected?
3. What conditions invalidate the operating envelope?
4. What security assumptions support assurance?
5. How are emerging threats incorporated?
6. Which dependencies are critical?
7. What happens when a critical dependency fails?
8. How is dependency change governed?
9. How are environmental, security and dependency risks assessed together?
10. What indicators and thresholds are used?
11. When is independent challenge required?
12. What findings require revalidation?
13. What changes require reauthorisation?
14. What conditions require suspension?

---

## 41. Core Rule

> **Continuing assurance shall establish that environmental conditions, security controls and critical dependencies remain within the conditions necessary for safe and authorised Defence AI employment. Material change, degradation, compromise or dependency failure shall be detected and assessed in context, including interactions among multiple degraded conditions. Where confidence cannot be maintained, the capability shall be proportionately restricted, have autonomy reduced, transition to human control or safe state, be revalidated or reauthorised, or be suspended.**

---

## 42. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance Claim → Environment/Security/Dependency Monitoring → Review → Finding → Corrective Action → Verification → Assurance → Revalidation/Reauthorisation → Learning**
