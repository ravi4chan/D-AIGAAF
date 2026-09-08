# 08 — Change Implementation, Rollback & Monitoring

## 1. Purpose

This document defines how approved changes to Defence AI capabilities are implemented, verified, monitored and, where necessary, reversed or restricted.

The objective is to ensure that an approved change remains controlled during transition into operational use and that unexpected effects are detected early.

---

## 2. Core Principle

> **Approval of a change does not make implementation risk-free. Implementation, rollback and post-change monitoring shall remain controlled activities linked to the authorised configuration, assurance basis and operational conditions.**

---

## 3. Scope

This process applies to implementation of changes involving:

- models;
- software;
- hardware;
- data;
- configuration;
- interfaces;
- sensors;
- communications;
- dependencies;
- security controls;
- autonomy;
- human-AI interaction;
- operating procedures.

---

## 4. Implementation Object

Implementation should maintain traceability across:

**Approved Change × Configuration × Mission × Environment × Autonomy × Human Authority**

---

## 5. Implementation Readiness

Before implementation, confirm:

- change approval;
- required TEVV;
- assurance status;
- revalidation status;
- reauthorisation status where applicable;
- implementation authority;
- rollback capability;
- monitoring arrangements.

---

## 6. Implementation Plan

The plan should define:

- scope;
- sequence;
- responsible personnel;
- dependencies;
- prerequisites;
- verification points;
- rollback criteria;
- monitoring period.

---

## 7. Pre-Implementation Checks

Checks should establish that:

- correct change package is available;
- configuration is identified;
- prerequisites are satisfied;
- required controls are active;
- personnel are prepared;
- rollback arrangements are available.

---

## 8. Configuration Integrity

The implementation process should prevent:

- unauthorised modification;
- incorrect version deployment;
- incomplete updates;
- configuration mismatch;
- loss of traceability.

---

## 9. Controlled Implementation

Implementation should occur through approved and controlled procedures.

Where practical, implementation should be staged to reduce exposure to unintended effects.

---

## 10. Deployment Verification

Immediately following implementation, verify:

- expected configuration;
- component versions;
- dependencies;
- interfaces;
- security controls;
- operating parameters.

---

## 11. Functional Verification

Verify that the intended changed functionality operates as expected.

Unexpected functionality or behaviour should be recorded and assessed.

---

## 12. Operational Readiness

Before normal operational employment, determine whether:

- required evidence exists;
- authorised conditions are satisfied;
- human authority is ready;
- monitoring is active;
- known limitations are understood.

---

## 13. Controlled Introduction

Where appropriate, changes may be introduced through:

- limited scope;
- restricted mission;
- restricted environment;
- reduced autonomy;
- enhanced supervision;
- increased monitoring.

---

## 14. Rollback Strategy

A rollback strategy should identify:

- known-good configuration;
- rollback trigger;
- rollback authority;
- required sequence;
- dependencies;
- verification after rollback.

---

## 15. Rollback Triggers

Rollback or restriction may be required where:

- critical functionality fails;
- unexpected behaviour occurs;
- risk becomes unacceptable;
- human control is degraded;
- autonomy exceeds authorised limits;
- security integrity is uncertain;
- critical conditions are violated.

---

## 16. Rollback Authority

Rollback authority should be defined before implementation where practical.

Emergency rollback authority should be available where delay could increase risk.

---

## 17. Rollback Verification

Following rollback, verify:

- configuration identity;
- integrity;
- functionality;
- safety controls;
- human control;
- autonomy;
- authorisation status.

---

## 18. Rollback Limitations

Rollback should not be assumed to restore the previous risk or assurance position automatically.

The organisation should assess:

- residual effects;
- changed dependencies;
- data changes;
- operational consequences;
- evidence implications.

---

## 19. Implementation Failure

Where implementation fails partially or unexpectedly:

- protect the operational environment;
- establish configuration state;
- preserve evidence;
- restrict capability where necessary;
- determine recovery or rollback.

---

## 20. Monitoring Period

Changes should receive proportionate post-implementation monitoring.

The monitoring period should reflect:

- consequence;
- uncertainty;
- change significance;
- autonomy;
- operational exposure.

---

## 21. Performance Monitoring

Monitor relevant:

- accuracy;
- reliability;
- availability;
- timeliness;
- robustness;
- mission effectiveness.

---

## 22. Uncertainty Monitoring

Monitor whether the change affects:

- confidence;
- uncertainty;
- calibration;
- detection of insufficient information;
- communication of limitations.

---

## 23. Human-Control Monitoring

Monitor:

- operator workload;
- situational awareness;
- intervention;
- override;
- decision quality;
- automation bias;
- escalation.

---

## 24. Autonomy Monitoring

Monitor:

- actual autonomy state;
- transitions;
- boundary compliance;
- autonomous actions;
- intervention;
- safe-state behaviour.

---

## 25. Environmental Monitoring

Monitor whether actual conditions remain within the assessed operating envelope, including relevant:

- degraded conditions;
- disconnected conditions;
- adversarial conditions;
- sensor conditions;
- communications conditions.

---

## 26. Security Monitoring

Monitor relevant:

- integrity;
- access;
- interfaces;
- anomalous activity;
- dependencies;
- security controls.

---

## 27. Dependency Monitoring

Monitor critical dependencies for:

- availability;
- integrity;
- continuity;
- performance;
- unexpected changes.

---

## 28. Thresholds and Escalation

Monitoring should define thresholds for:

- investigation;
- increased supervision;
- autonomy reduction;
- restriction;
- rollback;
- suspension.

Thresholds should be proportionate to consequence.

---

## 29. Unexpected Behaviour

Unexpected behaviour should be:

- recorded;
- assessed;
- escalated where necessary;
- linked to the change record.

Where the behaviour creates a credible incident, Module 14 should apply.

---

## 30. Change-Related Incidents

An incident associated with implementation or post-change operation should link:

**Change Record ↔ Incident Record ↔ Evidence ↔ Assurance Assessment**

---

## 31. Post-Implementation Assurance

The organisation should determine whether observed behaviour remains consistent with:

- tested behaviour;
- assurance claims;
- risk assumptions;
- authorised conditions.

---

## 32. Revalidation Trigger

Post-change monitoring should trigger revalidation where evidence indicates that:

- assurance claims may no longer hold;
- assumptions are invalidated;
- performance changes materially;
- controls are ineffective.

---

## 33. Reauthorisation Trigger

Reauthorisation should be considered where observed effects alter:

- authorised mission;
- environment;
- autonomy;
- human authority;
- boundaries;
- conditions;
- risk acceptance.

---

## 34. Stabilisation

A change may be considered stabilised when:

- expected behaviour is observed;
- monitoring remains within thresholds;
- controls are effective;
- no material unexpected effects remain unresolved;
- assurance remains sufficient.

---

## 35. Change Closure

Closure should require:

- implementation verification;
- monitoring completion;
- assurance assessment;
- required revalidation;
- required reauthorisation;
- outstanding actions recorded.

---

## 36. Post-Change Review

Material changes should receive a post-change review to determine:

- whether objectives were achieved;
- whether unexpected effects occurred;
- whether controls worked;
- whether monitoring was adequate;
- whether further action is required.

---

## 37. Lessons Learned

Implementation and rollback experience should feed into:

- change procedures;
- TEVV;
- risk assessment;
- configuration management;
- monitoring;
- training;
- future change planning.

---

## 38. Records

Implementation records should preserve:

- approved change;
- implementation plan;
- configuration;
- implementation events;
- verification;
- monitoring results;
- rollback events;
- decisions;
- final status.

---

## 39. Governance Questions

The organisation should be able to answer:

1. Was implementation authorised?
2. What configuration was deployed?
3. Were prerequisites satisfied?
4. Was deployment verified?
5. What rollback configuration was available?
6. Who could initiate rollback?
7. What triggered rollback or restriction?
8. How was rollback verified?
9. What post-change monitoring was performed?
10. Were performance and uncertainty monitored?
11. Were human-control and autonomy monitored?
12. Were environmental and security conditions monitored?
13. Were dependencies monitored?
14. Did unexpected behaviour occur?
15. Did monitoring trigger revalidation?
16. Did monitoring trigger reauthorisation?
17. When was the change considered stabilised?
18. Were lessons captured?

---

## 40. Core Rule

> **A change is not complete when it is deployed. It is complete only when the implemented configuration has been verified, its operational behaviour has been monitored, required assurance and authority decisions have been confirmed, and the resulting state is fully recorded.**

---

## 41. Golden Thread

**Mission Need → Risk → Requirements → Controls → Authorised Baseline → Change → Impact Assessment → TEVV → Revalidation → Reauthorisation → Implementation → Verification → Monitoring → Rollback/Restriction if Required → Stabilisation → Closure → Learning**
