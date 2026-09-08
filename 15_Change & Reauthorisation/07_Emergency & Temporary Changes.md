# 07 — Emergency & Temporary Changes

## 1. Purpose

This document defines governance for emergency and temporary changes to Defence AI capabilities when normal change timelines are insufficient or when a controlled temporary deviation is necessary.

The objective is to preserve safety, human authority, accountability and assurance while allowing proportionate responses to urgent operational, safety, security or resilience requirements.

---

## 2. Core Principle

> **Urgency may justify accelerated governance, but it shall not eliminate governance. Emergency and temporary changes shall remain bounded, authorised, traceable, monitored and subject to appropriate retrospective assurance.**

---

## 3. Scope

This process applies to urgent or time-limited changes involving:

- software;
- models;
- data;
- hardware;
- configuration;
- interfaces;
- dependencies;
- security controls;
- operating parameters;
- autonomy;
- human-control arrangements;
- operational procedures.

---

## 4. Emergency Change

An emergency change is a change requiring accelerated action because delay may create unacceptable:

- safety risk;
- security risk;
- operational risk;
- resilience risk;
- mission risk.

---

## 5. Temporary Change

A temporary change is an intentionally time-limited modification introduced for a defined purpose and bounded by explicit conditions.

Temporary status should not be used to bypass normal governance.

---

## 6. Emergency versus Temporary

The two concepts are distinct:

**Emergency Change:** driven primarily by urgency.

**Temporary Change:** defined primarily by limited duration or scope.

A change may be both emergency and temporary.

---

## 7. Emergency Governance Principle

Emergency circumstances may alter:

- timing;
- decision sequence;
- review depth;
- available evidence.

They should not remove:

- accountability;
- authority;
- human control;
- safety boundaries;
- traceability;
- post-change review.

---

## 8. Emergency Trigger

An emergency change may be considered where delay in implementing a necessary change could create greater risk than controlled implementation.

The trigger should be documented.

---

## 9. Temporary Change Trigger

Temporary changes may be used for:

- controlled trials;
- limited operational need;
- interim risk treatment;
- restoration;
- contingency arrangements;
- pending permanent remediation.

---

## 10. Change Definition

The proposed change should clearly define:

- what will change;
- why;
- affected configuration;
- intended duration;
- intended scope;
- expected effect;
- known risks.

---

## 11. Emergency Risk Assessment

A rapid risk assessment should consider:

- immediate risk;
- consequence;
- uncertainty;
- affected controls;
- human control;
- autonomy;
- environment;
- security;
- dependencies.

The assessment may be abbreviated where necessary, but material uncertainty should remain visible.

---

## 12. Minimum Safe Basis

Before an emergency change is implemented, the organisation should establish the minimum practical basis for controlled action, including where applicable:

- responsible authority;
- human control;
- essential safety controls;
- operational boundaries;
- rollback or recovery;
- monitoring.

---

## 13. Emergency Authority

Emergency decision authority should be predefined.

It should specify:

- who may approve;
- scope of authority;
- limits;
- escalation;
- duration;
- retrospective review.

---

## 14. Temporary Authority

Temporary changes should have explicitly assigned authority.

No temporary technical configuration should acquire operational authority merely because it has been deployed.

---

## 15. Autonomy Restrictions

Where evidence is incomplete, emergency or temporary changes should not automatically retain the previous autonomy level.

Where appropriate, autonomy should be:

- reduced;
- constrained;
- placed under enhanced supervision.

---

## 16. Human Control

Emergency and temporary changes should preserve practical human ability to:

- understand relevant behaviour;
- intervene;
- override;
- reduce autonomy;
- suspend operation.

---

## 17. Safety Controls

Critical safety controls should remain operational unless an explicitly authorised emergency decision determines otherwise.

Any loss or modification of a critical control should receive heightened scrutiny.

---

## 18. Security Controls

Emergency changes should not create uncontrolled security exposure.

Where security controls are temporarily altered, the organisation should define:

- reason;
- compensating controls;
- monitoring;
- restoration requirement.

---

## 19. Configuration Baseline

The emergency or temporary configuration should receive a unique identifier and remain traceable to the previous baseline.

---

## 20. Change Classification

Even under emergency conditions, the organisation should determine the likely significance of the change.

If classification cannot initially be completed, it should be finalised as soon as practicable.

---

## 21. Rapid TEVV

Where feasible, emergency changes should undergo proportionate rapid testing or verification before operational use.

Testing should focus on the highest-consequence effects.

---

## 22. Evidence Limitations

Where normal evidence is unavailable, the limitation should be explicitly recorded.

Lack of evidence should not be represented as evidence of safety or effectiveness.

---

## 23. Compensating Controls

Where full assurance is unavailable, compensating controls may include:

- reduced autonomy;
- narrower mission;
- narrower environment;
- additional supervision;
- increased monitoring;
- limited duration.

---

## 24. Operational Boundaries

Emergency and temporary changes should have explicit:

- mission boundaries;
- environmental boundaries;
- autonomy boundaries;
- human-authority boundaries;
- duration boundaries.

---

## 25. Time Limit

Temporary authority should specify:

- start condition;
- expiry condition;
- review point;
- termination criteria.

Where continued use is necessary, a formal reassessment should occur before expiry.

---

## 26. Monitoring

Emergency and temporary changes should receive enhanced monitoring proportionate to uncertainty and consequence.

Monitoring should include relevant:

- performance;
- safety;
- human-control;
- autonomy;
- security;
- environmental indicators.

---

## 27. Escalation

Immediate escalation should occur where:

- expected behaviour is not observed;
- controls fail;
- human control is degraded;
- autonomy exceeds authorised limits;
- security integrity is uncertain;
- risk becomes unacceptable.

---

## 28. Rollback

Where technically and operationally feasible, a known-good rollback configuration should be available.

Rollback criteria should be defined before implementation where practical.

---

## 29. Safe State

If the emergency or temporary configuration cannot be maintained within authorised boundaries, the capability should move to an appropriate:

- restricted state;
- reduced-autonomy state;
- human-controlled state;
- safe state;
- suspended state.

---

## 30. Incident Interaction

If the emergency or temporary change causes or contributes to an incident, Module 14 shall apply.

The change record should remain linked to the incident record.

---

## 31. Post-Change Assessment

After implementation, the organisation should reassess:

- actual effects;
- risk;
- assurance;
- controls;
- human control;
- autonomy;
- environment;
- security;
- dependencies.

---

## 32. Retrospective TEVV

Where normal TEVV could not be completed beforehand, appropriate testing should be conducted retrospectively as soon as practical.

---

## 33. Retrospective Revalidation

Where the change affects assurance claims, revalidation should be conducted as required.

---

## 34. Reauthorisation

Where the change alters the authorised basis, reauthorisation should follow the process defined in Module 11 and Module 15 Serial 06.

---

## 35. Permanent Transition

A temporary change that is intended to become permanent should enter the normal change lifecycle.

It should not become permanent through repeated extensions alone.

---

## 36. Expiry

At expiry, the organisation should:

- revert;
- renew through formal assessment;
- replace with an approved permanent configuration;
- suspend operation.

---

## 37. Emergency Change Closure

An emergency change should be closed only after:

- implementation is verified;
- risk is reassessed;
- assurance implications are addressed;
- required testing is completed;
- authority status is confirmed;
- records are complete.

---

## 38. Decision Record

The record should include:

- trigger;
- change;
- authority;
- configuration;
- risk;
- evidence;
- controls;
- conditions;
- duration;
- monitoring;
- rollback;
- decision;
- follow-up.

---

## 39. Independent Review

Material emergency changes should receive retrospective independent review where proportionate to:

- consequence;
- uncertainty;
- autonomy;
- security;
- systemic significance.

---

## 40. Governance Questions

The organisation should be able to answer:

1. Why was emergency or temporary change required?
2. Who authorised it?
3. What configuration was introduced?
4. What risks were identified?
5. What evidence was available?
6. What evidence was unavailable?
7. What compensating controls were applied?
8. What human-control arrangements applied?
9. What autonomy restrictions applied?
10. What boundaries applied?
11. What monitoring was established?
12. What was the duration?
13. What triggered rollback or suspension?
14. Was retrospective TEVV completed?
15. Was revalidation required?
16. Was reauthorisation required?
17. How was the change closed or transitioned?

---

## 41. Core Rule

> **Emergency and temporary change mechanisms exist to manage urgency and controlled deviation, not to create a parallel path around assurance and authority. Every such change shall remain bounded, accountable, traceable and subject to appropriate subsequent review.**

---

## 42. Golden Thread

**Mission Need → Risk → Requirements → Controls → Authorised Baseline → Emergency/Temporary Change → Rapid Impact Assessment → Minimum Safe Basis → Controlled Implementation → Monitoring → TEVV → Revalidation → Reauthorisation if Required → Normalised Configuration or Rollback → Learning**
