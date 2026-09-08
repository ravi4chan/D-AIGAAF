# 02 — Change Control & Configuration Baseline

## 1. Purpose

This document defines how Defence AI configurations are established, controlled, identified and maintained so that operational authority remains linked to a known and governed capability state.

---

## 2. Core Principle

> **A Defence AI capability shall be operated only against an identifiable and controlled configuration baseline whose components, dependencies and applicable conditions are known to the organisation.**

---

## 3. Scope

Configuration control may include:

- AI models;
- model parameters and versions;
- software;
- hardware;
- data;
- interfaces;
- sensors;
- communications;
- security controls;
- operating parameters;
- dependencies;
- human-machine interfaces;
- supporting infrastructure.

---

## 4. Configuration Baseline

A configuration baseline is the defined reference state against which authorised capability is assessed.

It should identify, as applicable:

- component;
- version;
- configuration;
- dependency;
- interface;
- applicable restriction;
- approval status.

---

## 5. Authorised Configuration

The authorised configuration represents the state for which the relevant assurance and operational authority apply.

A capability should not assume that authorisation transfers automatically to an unassessed configuration.

---

## 6. Configuration Identification

Each controlled configuration should have a unique identifier.

Identification should allow the organisation to determine:

- what is deployed;
- what was tested;
- what was authorised;
- what has changed.

---

## 7. Configuration Items

Configuration items should be defined according to operational relevance.

A configuration item may be:

- a model;
- software component;
- hardware component;
- dataset;
- interface;
- sensor;
- dependency;
- security component;
- operational parameter.

---

## 8. Version Control

Versions should be uniquely identifiable and traceable.

Version records should support reconstruction of the configuration associated with:

- testing;
- deployment;
- employment;
- incident;
- assurance;
- authorisation.

---

## 9. Configuration Ownership

Responsibilities should be defined for:

- configuration ownership;
- technical maintenance;
- change control;
- verification;
- assurance;
- operational authority.

Technical ownership should not be confused with operational authority.

---

## 10. Configuration Status

Configuration status should distinguish at least:

- proposed;
- under assessment;
- tested;
- approved;
- authorised;
- deployed;
- restricted;
- suspended;
- retired.

---

## 11. Configuration Integrity

Controls should protect configuration information against:

- unauthorised modification;
- accidental alteration;
- incomplete recording;
- version confusion;
- substitution;
- loss of traceability.

---

## 12. Baseline Establishment

A baseline should be established after the relevant:

- requirements;
- testing;
- assurance;
- security;
- operational assessments;
- authorisation decisions

have been completed.

---

## 13. Baseline Change

A baseline should be updated only through controlled change processes.

Every baseline change should have:

- change identifier;
- reason;
- affected items;
- impact assessment;
- approval;
- verification;
- effective date.

---

## 14. Configuration Drift

Configuration drift occurs when the deployed or employed state differs from the approved baseline without appropriate governance.

Potential causes include:

- uncontrolled updates;
- dependency changes;
- parameter changes;
- software patches;
- data changes;
- hardware substitution.

Configuration drift should be detected and addressed.

---

## 15. Automatic Updates

Automatic updates should not bypass change governance.

Where automatic updating is necessary, the organisation should establish:

- permitted update scope;
- verification mechanisms;
- rollback;
- monitoring;
- authority;
- emergency controls.

---

## 16. Data Configuration

Where data materially affects operational behaviour, configuration control should consider:

- dataset version;
- source;
- provenance;
- processing;
- validation;
- update status.

---

## 17. Model Configuration

Model configuration should identify, as applicable:

- model version;
- relevant parameters;
- associated software;
- supporting data;
- evaluation baseline;
- applicable limitations.

---

## 18. Software Configuration

Software configuration should support traceability of:

- version;
- build;
- dependencies;
- patches;
- interfaces;
- security updates.

---

## 19. Hardware Configuration

Hardware changes should be controlled where they may affect:

- performance;
- sensors;
- processing;
- communications;
- reliability;
- environmental suitability;
- safety.

---

## 20. Interface Configuration

Interfaces should be controlled where changes may affect:

- data;
- commands;
- human interaction;
- other AI systems;
- external systems;
- security.

---

## 21. Dependency Configuration

Critical dependencies should be identified and versioned or otherwise uniquely specified where feasible.

Changes to critical dependencies should enter the change-impact process.

---

## 22. Configuration and TEVV

The configuration tested should be traceable to the configuration proposed for deployment.

Where they differ materially, the difference should be assessed.

---

## 23. Configuration and Assurance

Assurance claims should reference the configuration to which the evidence applies.

Evidence should not be treated as configuration-independent unless this has been demonstrated.

---

## 24. Configuration and Authorisation

Operational authority should reference the relevant authorised configuration or defined configuration class.

This creates a direct relationship between:

**Configuration → Assurance → Authorisation**

---

## 25. Configuration Verification

Before operational entry, verification should establish that the deployed configuration matches the approved and authorised state.

---

## 26. Configuration During Employment

Configuration should be monitored during employment where changes may occur.

Relevant indicators may include:

- unexpected version changes;
- parameter changes;
- dependency changes;
- integrity failures;
- unauthorised modifications.

---

## 27. Emergency Configuration Change

Emergency changes may be permitted where required to:

- protect personnel;
- contain an incident;
- restore safe operation;
- address critical security issues.

Emergency changes should remain traceable and undergo retrospective assessment.

---

## 28. Rollback Configuration

Rollback procedures should identify:

- known-good configuration;
- rollback authority;
- trigger conditions;
- dependencies;
- verification requirements.

---

## 29. Configuration Recovery

After rollback or recovery, the organisation should verify:

- configuration identity;
- integrity;
- expected functionality;
- applicable controls;
- assurance status;
- authorisation status.

---

## 30. Configuration Mismatch

A detected mismatch between deployed and authorised configurations should trigger proportionate action.

Possible actions include:

- investigate;
- restrict;
- reduce autonomy;
- restore baseline;
- revalidate;
- reauthorise;
- suspend.

---

## 31. Configuration Exceptions

Exceptions should be:

- explicitly approved;
- bounded;
- time-limited where appropriate;
- monitored;
- recorded.

An exception should not become an uncontrolled alternate baseline.

---

## 32. Configuration Security

Configuration records and mechanisms should themselves be protected against:

- tampering;
- unauthorised access;
- malicious substitution;
- integrity compromise.

---

## 33. Configuration Records

Records should support reconstruction of:

- baseline;
- changes;
- approvals;
- deployments;
- test configurations;
- operational configurations;
- incidents.

---

## 34. Configuration Audit

Periodic or event-driven audits should verify:

- configuration accuracy;
- baseline integrity;
- change traceability;
- authorisation alignment;
- unauthorised drift.

---

## 35. Configuration Status Reporting

Decision-makers should be able to determine:

- current configuration;
- authorised status;
- outstanding changes;
- restrictions;
- assurance status;
- unresolved discrepancies.

---

## 36. Configuration Closure

When a configuration is retired or superseded, records should preserve sufficient information to support:

- audit;
- incident investigation;
- lessons learned;
- historical assurance;
- accountability.

---

## 37. Governance Questions

The organisation should be able to answer:

1. What is the authorised configuration?
2. Which components constitute the baseline?
3. How is each component uniquely identified?
4. Who controls configuration changes?
5. How is configuration integrity protected?
6. How is configuration drift detected?
7. How are automatic updates governed?
8. How are model, data and software versions linked?
9. How are dependencies controlled?
10. How is tested configuration linked to deployed configuration?
11. How is configuration linked to assurance?
12. How is configuration linked to authorisation?
13. What happens when a mismatch is detected?
14. How are emergency changes controlled?
15. How is rollback verified?
16. How are historical configurations retained?

---

## 38. Core Rule

> **The organisation shall be able to identify the configuration of a Defence AI capability at the time it was tested, authorised, deployed, employed and involved in any material incident.**

---

## 39. Golden Thread

**Mission Need → Risk → Requirements → Controls → Configuration Baseline → Testing → Evidence → Assurance → Authority → Change → Impact Assessment → Controlled Implementation → Configuration Verification → Revalidation/Reauthorisation → Employment → Monitoring → Incident/Learning**
