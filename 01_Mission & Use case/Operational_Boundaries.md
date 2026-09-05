# Operational Boundaries

## 1. Purpose

Operational Boundaries define the limits within which an AI-enabled capability is permitted to operate.

They establish the conditions under which the capability has been evaluated, assured and, where applicable, authorised.

---

## 2. Core Principle

**Capability is not the same as authority.**

An AI system may technically be capable of operating outside its authorised conditions.

That does not mean it is permitted to do so.

The governing relationship is:

**Capability → Tested Boundary → Assured Boundary → Authorised Boundary**

The authorised boundary must remain explicit.

---

## 3. Boundary Dimensions

Operational boundaries may apply to:

- mission;
- use case;
- geography;
- environment;
- information and data;
- communications;
- users;
- system configuration;
- autonomy;
- human authority;
- time;
- security conditions;
- dependencies;
- permitted actions.

The applicable dimensions should be determined by the specific capability and mission.

---

## 4. Mission Boundary

The mission boundary defines what mission objectives the AI capability may support.

It should identify:

- authorised mission;
- intended operational purpose;
- prohibited mission uses;
- conditions requiring reassessment.

A capability authorised for one mission should not automatically be considered authorised for another.

---

## 5. Use Case Boundary

The use case boundary defines the specific activity for which AI is authorised.

It should specify:

- intended function;
- authorised users;
- expected inputs;
- expected outputs;
- human role;
- permitted actions;
- foreseeable misuse.

Expansion to a materially different use case should trigger review.

---

## 6. Geographic Boundary

Where location affects performance or consequence, the authorised geographic environment should be defined.

Relevant considerations may include:

- terrain;
- climate;
- infrastructure;
- population density;
- communications coverage;
- positioning availability;
- other location-dependent conditions.

Evidence from one geographic environment should not automatically be assumed valid in another materially different environment.

---

## 7. Environmental Boundary

Environmental boundaries define conditions under which the system has demonstrated acceptable performance.

These may include:

- temperature;
- altitude;
- weather;
- visibility;
- terrain;
- electromagnetic conditions;
- vibration;
- dust;
- moisture;
- other relevant environmental factors.

The specific conditions should be determined by the capability.

---

## 8. Information and Data Boundary

The capability should define the information conditions within which it is expected to operate.

This may include:

- data sources;
- data quality;
- data freshness;
- data completeness;
- supported formats;
- provenance requirements;
- minimum information availability.

If information falls outside the validated conditions, the required response should be defined.

---

## 9. Communications Boundary

Where communications affect capability or human control, boundaries should define:

- required connectivity;
- acceptable latency;
- permitted communication paths;
- loss-of-communications behaviour;
- restoration behaviour.

Communications loss must not result in unintended expansion of AI authority.

---

## 10. User and Human Authority Boundary

Only appropriately authorised users should operate the capability.

The boundary should identify:

- permitted user roles;
- required competency;
- decision authority;
- escalation authority;
- override authority;
- suspension authority.

Technical access should not automatically confer operational authority.

---

## 11. Autonomy Boundary

The authorised autonomy level must be explicit.

The capability should not:

- operate at a higher autonomy level than authorised;
- independently expand its authority;
- reinterpret human instructions as broader authority;
- continue autonomous consequential activity after authority has been withdrawn.

Where technical capability exceeds authorised autonomy, the additional capability remains outside the operational authority boundary.

---

## 12. Human Control Boundary

Where meaningful human control is required, the boundary should specify:

- when human review is mandatory;
- what decisions require explicit approval;
- intervention mechanisms;
- intervention time requirements;
- override conditions;
- circumstances requiring transfer to human control.

Human control should be practical under the actual operating conditions.

---

## 13. Temporal Boundary

Some authorisations may be limited by:

- date;
- operational phase;
- mission duration;
- system lifecycle state;
- review period;
- threat condition.

Expiration of an authorisation should not silently result in continued operational authority.

---

## 14. Configuration Boundary

Operational authority should be tied to an approved configuration baseline.

This may include:

- model version;
- software;
- hardware;
- system configuration;
- data;
- critical dependencies.

A material configuration change should trigger change assessment.

---

## 15. Dependency Boundary

Critical dependencies should be identified.

These may include:

- external data;
- sensors;
- communications;
- positioning;
- infrastructure;
- third-party models;
- software components;
- cloud or remote services;
- power.

If a critical dependency falls outside its assured condition, the capability may need to degrade, transfer to human control or cease operation.

---

## 16. Security Boundary

The authorised operating environment should define relevant security assumptions.

Consider:

- trusted infrastructure;
- authentication;
- access control;
- model integrity;
- data integrity;
- supply-chain integrity;
- cyber threat conditions.

A security compromise may invalidate assumptions supporting operational authority.

---

## 17. Permitted Actions

The boundary should identify what actions the AI may perform.

Actions may range from:

- information presentation;
- analysis;
- recommendation;
- actions requiring human approval;
- predefined automated actions;
- higher-autonomy actions where separately authorised.

The ability to perform an action technically does not establish authority to perform it operationally.

---

## 18. Prohibited Actions

Where appropriate, the boundary should identify actions that are not authorised.

Prohibited actions may include:

- operating outside the approved mission;
- exceeding authorised autonomy;
- acting without required human approval;
- using unauthorised data;
- operating outside validated environments;
- modifying critical behaviour without approval;
- bypassing security controls;
- continuing operation after a defined suspension condition.

---

## 19. Boundary Conditions

A boundary should distinguish between:

### Normal Conditions

Conditions within the validated and authorised operating envelope.

### Warning Conditions

Conditions approaching an operational limit and requiring increased monitoring or human attention.

### Boundary Conditions

Conditions at or near the limit of validated performance.

### Out-of-Bounds Conditions

Conditions outside the authorised operational envelope.

Each category should have a defined operational response.

---

## 20. Out-of-Bounds Behaviour

When the capability detects or encounters an out-of-bounds condition, the response should be defined in advance where practical.

Possible responses include:

- warning;
- request for human confirmation;
- reduced functionality;
- transfer to human control;
- controlled degradation;
- fail-safe;
- suspension.

The appropriate response depends on consequence and autonomy.

---

## 21. Boundary Monitoring

Material operational boundaries should be monitored where technically and operationally feasible.

Monitoring may include:

- environmental conditions;
- communications status;
- data quality;
- system health;
- configuration;
- autonomy state;
- human availability;
- security state;
- dependency status.

Monitoring should support timely intervention.

---

## 22. Boundary Violations

A boundary violation should be treated as a potentially significant event.

The response may include:

- immediate operational restriction;
- human intervention;
- suspension;
- incident reporting;
- investigation;
- risk reassessment;
- additional testing;
- revalidation;
- reauthorisation.

Not every boundary excursion has the same consequence; response should be proportionate.

---

## 23. Boundary and Risk

Operational boundaries are risk controls.

They reduce exposure by limiting:

- where the capability operates;
- what it does;
- who controls it;
- how much autonomy it has;
- what information it uses;
- what conditions it can tolerate.

Risk assessment should therefore explicitly consider whether boundaries are sufficient.

---

## 24. Boundary and Assurance

Assurance claims should identify the conditions under which evidence was generated.

An assurance claim should not be interpreted as universally valid if its evidence was limited to a specific:

- mission;
- environment;
- configuration;
- autonomy level;
- data condition;
- human operating condition.

The boundary defines the scope of confidence.

---

## 25. Boundary and Authorisation

Operational authorisation should explicitly define the authorised boundary.

At minimum, where relevant, it should identify:

**Capability × Mission × Environment × Autonomy × Human Authority**

The authorisation record should also identify important limitations and conditions.

---

## 26. Boundary and Change

A change may affect an operational boundary even when the change appears technically minor.

Examples include:

- new model behaviour;
- changed data sources;
- new deployment environment;
- new users;
- new dependencies;
- increased autonomy;
- changed communications;
- changed mission;
- changed security conditions.

Behaviour and operational effect should determine whether additional assurance is required.

---

## 27. Boundary and Incidents

An incident may demonstrate that an existing boundary was:

- insufficient;
- incorrectly defined;
- poorly monitored;
- poorly enforced;
- no longer valid.

After a significant incident, the relevant boundary should be reassessed.

---

## 28. Boundary Enforcement

Where practical, important boundaries should be technically enforced rather than relying entirely on human memory or procedure.

Possible mechanisms include:

- access controls;
- configuration controls;
- policy enforcement;
- autonomy restrictions;
- geofencing where appropriate;
- data controls;
- authentication;
- system interlocks;
- monitoring and alerts.

Technical enforcement does not remove the need for human governance.

---

## 29. Boundary Exceptions

Exceptions to operational boundaries should be:

- explicitly authorised;
- limited in scope;
- time-bound where appropriate;
- risk-assessed;
- recorded;
- subject to appropriate oversight.

An exception should not become an informal permanent expansion of authority.

---

## 30. Emergency Conditions

Emergency conditions may require immediate protective action.

Where delay could create unacceptable harm, pre-authorised emergency procedures may permit:

- suspension;
- isolation;
- transfer to human control;
- controlled degradation;
- fail-safe;
- termination of autonomous activity.

Emergency action should remain traceable and subject to subsequent review.

---

## 31. Operational Boundary Record

A controlled Operational Boundary Record should contain, as applicable:

- capability;
- mission;
- use case;
- geographic conditions;
- environmental conditions;
- information conditions;
- communications conditions;
- human authority;
- autonomy;
- configuration baseline;
- dependencies;
- security assumptions;
- permitted actions;
- prohibited actions;
- warning conditions;
- out-of-bounds conditions;
- required responses;
- monitoring arrangements;
- exception arrangements;
- review triggers.

---

## 32. Example Boundary Structure

| Boundary | Authorised Condition | Warning | Out of Bounds | Required Response |
|---|---|---|---|---|
| Mission | Defined mission | Expansion considered | Different mission | Restrict/review |
| Environment | Validated conditions | Approaching limit | Outside validated range | Degrade/restrict |
| Data | Defined quality | Reduced quality | Unreliable data | Warn/degrade |
| Communications | Defined condition | Degradation | Loss beyond limit | Human control/fail-safe |
| Autonomy | Authorised level | Change requested | Higher level | Prevent/restrict |
| Human Control | Required authority available | Reduced availability | No meaningful control | Restrict/suspend |
| Configuration | Approved baseline | Pending change | Unapproved baseline | Prevent/revalidate |

Values must be defined for the specific capability.

---

## 33. Minimum Operational Boundary Requirements

For consequential AI capabilities, D-AIGAAF should require:

1. Explicit operational boundaries.
2. Defined mission and use case scope.
3. Defined relevant environmental conditions.
4. Defined information and data conditions.
5. Defined communications conditions where applicable.
6. Defined authorised users and human authority.
7. Explicit autonomy limits.
8. Defined configuration baseline.
9. Identified critical dependencies.
10. Defined permitted and prohibited actions.
11. Defined warning and out-of-bounds conditions.
12. Defined responses to boundary violations.
13. Appropriate boundary monitoring.
14. Controlled exception procedures.
15. Emergency protective procedures where required.
16. Reassessment following material change or incident.

---

## 34. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Reference Model`
- `00 Framework/Principles`
- `00 Framework/Golden Thread`
- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Mission_Success_Criteria.md`
- `02 Mission & Use Case/Operational_Scenarios.md`
- `02 Mission & Use Case/Mission_Decision_Context.md`
- `02 Mission & Use Case/Use_Case_Register.md`
- `03 Risk & Autonomy`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `12 Operational Employment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`

Operational boundaries connect mission definition and risk with the conditions of actual authority.

---

## 35. Summary

Operational Boundaries define where, when, how and under what conditions an AI capability may operate.

They prevent technical capability from being confused with operational authority and establish a controlled relationship between:

- mission;
- environment;
- information;
- communications;
- human authority;
- autonomy;
- configuration;
- security;
- dependencies;
- permitted actions.

The central principle is:

> **An AI capability must operate within an explicit, evidence-supported and authorised operational envelope; capability beyond that envelope is not automatically authority.**
