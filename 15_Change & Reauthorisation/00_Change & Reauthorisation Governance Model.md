# 00 — Change & Reauthorisation Governance Model

## 1. Purpose

This document establishes the governance model for managing changes to Defence AI capabilities and determining when those changes require assessment, revalidation, reauthorisation, restriction or suspension.

The objective is to ensure that a capability does not retain operational authority merely because a changed version remains technically similar to a previously authorised version.

---

## 2. Core Principle

> **A change shall be governed according to its potential effect on mission, risk, assurance, human authority, autonomy, environment, security, dependencies and authorised conditions. Technical implementation of a change shall not by itself determine whether operational authority remains valid.**

---

## 3. Scope

This module applies to changes affecting:

- AI models;
- software;
- hardware;
- data;
- configuration;
- interfaces;
- sensors;
- communications;
- dependencies;
- operating environments;
- missions;
- autonomy;
- human authority;
- security controls;
- operational procedures;
- policies or legal conditions.

---

## 4. Change Governance Object

The change should be assessed against:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

This maintains consistency with the D-AIGAAF authorisation object.

---

## 5. Why Change Matters

A change may alter:

- system behaviour;
- performance;
- uncertainty;
- failure modes;
- risk;
- human interaction;
- autonomy;
- security;
- environmental suitability;
- mission effectiveness.

Therefore, apparently minor technical changes may have material operational consequences.

---

## 6. Change Lifecycle

The governance lifecycle should follow:

**Propose → Identify → Classify → Assess → Decide → Implement → Verify → Revalidate → Reauthorise if Required → Monitor → Record → Learn**

---

## 7. Change Identification

All material changes should be identifiable and traceable.

Change records should include:

- change description;
- reason;
- affected component;
- version;
- owner;
- dependencies;
- intended effect;
- affected operational scope.

---

## 8. Change Classification

Changes should be classified according to potential impact.

A practical classification is:

- **Minor** — no material effect expected on authorised conditions or assurance;
- **Significant** — meaningful effect possible and additional assurance may be required;
- **Material** — authorised basis, risk, assurance or operational behaviour may change.

Classification should be evidence-based and may be revised as assessment progresses.

---

## 9. Change Impact Assessment

The impact assessment should consider:

- mission;
- risk;
- requirements;
- controls;
- evidence;
- assurance;
- human control;
- autonomy;
- environment;
- security;
- dependencies;
- mission effectiveness.

---

## 10. Change and Risk

The organisation should determine whether the change:

- introduces new risks;
- increases existing risks;
- reduces existing risks;
- changes risk assumptions;
- changes residual risk;
- invalidates previous risk acceptance.

---

## 11. Change and Assurance

The organisation should identify affected assurance claims.

For each claim, determine whether existing evidence remains:

- valid;
- partially valid;
- insufficient;
- obsolete;
- contradicted.

---

## 12. Change and Evidence

Existing evidence should not automatically be transferred to a changed capability.

Evidence should be reassessed for:

- relevance;
- applicability;
- currency;
- configuration;
- representativeness;
- coverage.

---

## 13. Change and Human Control

Changes affecting human interaction should assess:

- decision rights;
- interfaces;
- workload;
- situational awareness;
- intervention;
- override;
- training;
- automation bias.

---

## 14. Change and Autonomy

Changes affecting autonomy should assess:

- autonomy level;
- autonomy transitions;
- boundaries;
- decision authority;
- intervention;
- safe-state behaviour;
- observability.

Any change capable of increasing consequential autonomy requires explicit governance review.

---

## 15. Change and Environment

Changes should be assessed against the authorised operating envelope.

Consider:

- terrain;
- weather;
- sensors;
- communications;
- electromagnetic conditions;
- degraded conditions;
- disconnected operation;
- adversarial conditions.

---

## 16. Change and Security

Security impact assessment should consider:

- attack surface;
- interfaces;
- dependencies;
- software;
- model integrity;
- data;
- supply chain;
- configuration;
- monitoring.

---

## 17. Change and Dependencies

Changes to dependencies should assess:

- criticality;
- availability;
- integrity;
- continuity;
- supplier impact;
- fallback;
- interoperability.

---

## 18. Change and Mission Effectiveness

The organisation should determine whether the change affects:

- mission success criteria;
- accuracy;
- reliability;
- timeliness;
- operational suitability;
- decision quality.

---

## 19. Configuration Baseline

Each authorised capability should have an identifiable configuration baseline.

The baseline should include, as applicable:

- model version;
- software version;
- hardware;
- data configuration;
- system configuration;
- interfaces;
- dependencies;
- operating parameters.

---

## 20. Authorised Baseline

The operational authority should be linked to a defined authorised baseline.

A capability should not assume that authorisation automatically transfers to a materially changed baseline.

---

## 21. Change Decision

Change decisions may include:

- approve without additional assurance;
- approve with conditions;
- require additional testing;
- require revalidation;
- require reauthorisation;
- restrict employment;
- suspend operation;
- reject the change.

---

## 22. Revalidation

Revalidation determines whether existing assurance remains supported after change.

It should be proportionate to:

- change significance;
- consequence;
- uncertainty;
- affected claims;
- autonomy;
- environment;
- security.

---

## 23. Reauthorisation

Reauthorisation determines whether operational authority remains justified after a change to the authorised basis.

It may be required where changes affect:

- mission;
- risk;
- environment;
- autonomy;
- human authority;
- conditions;
- boundaries.

---

## 24. Revalidation versus Reauthorisation

These decisions are distinct:

**Revalidation:** Is the assurance basis still supported?

**Reauthorisation:** Is operational authority still justified?

A capability may require one, both, or neither depending on the change.

---

## 25. Emergency Changes

Emergency changes may be necessary to:

- protect personnel;
- contain an incident;
- address a critical security issue;
- restore safe operation;
- maintain essential resilience.

Emergency changes should remain subject to documented authority and retrospective assurance review.

---

## 26. Temporary Changes

Temporary changes should have:

- defined purpose;
- defined scope;
- start and end conditions;
- responsible authority;
- applicable restrictions;
- monitoring;
- restoration criteria.

Temporary status should not become a mechanism for avoiding normal governance.

---

## 27. Change Implementation

Approved changes should be implemented through controlled processes.

Implementation should preserve:

- configuration integrity;
- traceability;
- rollback capability;
- evidence;
- authorisation boundaries.

---

## 28. Verification

Following implementation, verification should establish that:

- the intended change occurred;
- the correct version is deployed;
- controls remain effective;
- unintended effects are identified;
- required tests were completed.

---

## 29. Rollback

Where a change produces unacceptable behaviour or assurance degradation, rollback or restriction should be available where technically and operationally feasible.

Rollback itself should be controlled and recorded.

---

## 30. Post-Change Monitoring

Changes should receive proportionate monitoring after implementation.

Monitoring should examine:

- performance;
- uncertainty;
- human control;
- autonomy;
- environment;
- security;
- dependencies;
- unexpected behaviour.

---

## 31. Change-Induced Incidents

Where a change contributes to an incident, the event should enter the incident-management process defined in Module 14.

Change governance should then incorporate the resulting findings and lessons.

---

## 32. Change Authority

Change approval authority should be defined according to:

- change significance;
- consequence;
- autonomy;
- affected scope;
- assurance impact;
- risk.

No technical team should acquire operational authority solely through implementation responsibility.

---

## 33. Escalation

Changes should be escalated when:

- impact is uncertain;
- assurance claims may be invalidated;
- risk increases materially;
- autonomy changes;
- human control changes;
- operating boundaries change;
- security posture changes;
- dependencies become critical.

---

## 34. Independence and Challenge

Material changes should receive proportionate independent review or challenge.

Independent challenge should test:

- classification;
- impact assessment;
- evidence;
- assumptions;
- residual risk;
- proposed controls;
- revalidation decision.

---

## 35. Change Records

Change records should provide traceability from:

**Change → Impact → Evidence → Decision → Implementation → Verification → Revalidation/Reauthorisation**

---

## 36. Change Register

An organisation should maintain a change register containing, as appropriate:

- change identifier;
- capability;
- baseline;
- classification;
- owner;
- impact assessment;
- assurance decision;
- authority decision;
- implementation status;
- verification status;
- closure.

---

## 37. Relationship with Continuous Assurance

Module 13 establishes continuing assurance.

This module defines the governance response when change threatens to alter the basis of that assurance.

Change monitoring and assurance monitoring should therefore remain connected.

---

## 38. Relationship with Incident Management

Module 14 addresses incidents and their consequences.

This module addresses planned, emergency and operational changes.

Where an incident causes a required change, both governance processes should apply.

---

## 39. Relationship with Operational Authorisation

Module 11 defines operational authorisation.

This module determines when a change requires that authorisation to be reconsidered.

The authorisation decision remains governed by Module 11.

---

## 40. Governance Review

Material changes should be reviewed after implementation where appropriate to determine whether:

- assumptions remain valid;
- controls remain effective;
- assurance remains sufficient;
- operational authority remains justified;
- additional action is required.

---

## 41. Closure

A change should not be considered closed merely because implementation is complete.

Closure should require:

- verification;
- required assurance activity;
- required authorisation activity;
- record completion;
- monitoring arrangements;
- outstanding actions identified.

---

## 42. Governance Questions

The organisation should be able to answer:

1. What constitutes a change?
2. How is change significance classified?
3. What is the authorised configuration baseline?
4. How is change impact assessed?
5. Which assurance claims are affected?
6. When is revalidation required?
7. When is reauthorisation required?
8. Who has authority to approve each class of change?
9. How are emergency and temporary changes governed?
10. How is rollback controlled?
11. How is post-change monitoring performed?
12. How are change-related incidents handled?
13. How are systemic effects identified?
14. How is independent challenge applied?
15. How is the final change decision recorded?

---

## 43. Core Rule

> **Operational authority attaches to an assured and authorised configuration within defined mission, environmental, autonomy and human-authority boundaries. A change that materially affects that basis shall not be treated as automatically covered by the previous authorisation.**

---

## 44. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Baseline → Change → Impact Assessment → Verification → Revalidation → Reauthorisation → Operational Employment → Monitoring → Incident/Learning → Continuous Improvement**
