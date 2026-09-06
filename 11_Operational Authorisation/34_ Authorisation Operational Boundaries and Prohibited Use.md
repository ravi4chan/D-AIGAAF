# 34 — Authorisation Operational Boundaries and Prohibited Use

## 1. Purpose

This document defines how D-AIGAAF establishes, communicates, enforces and reviews the operational boundaries within which a Defence AI capability may be used.

Operational boundaries define what an AI capability is permitted to do, where and when it may operate, under what conditions, with what level of autonomy, and under whose human authority.

The purpose is to prevent technical capability from being mistaken for operational permission.

---

## 2. Core Principle

> **A Defence AI capability shall be treated as authorised only within explicitly defined operational boundaries. Technical ability to perform an action shall not be interpreted as permission to perform that action.**

Operational authority shall arise from a valid authorisation decision, not from the capability of the system itself.

---

## 3. Boundary Model

D-AIGAAF defines the operational boundary as:

**Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions**

A capability shall remain within all applicable dimensions of this boundary during operational employment.

A change to one or more dimensions may require restriction, additional assurance, revalidation or reauthorisation.

---

## 4. Boundary Categories

Operational boundaries should be defined across the following categories:

### 4.1 Mission Boundary

Defines:

- authorised mission;
- authorised objectives;
- mission phase;
- permitted operational purpose;
- prohibited mission purposes;
- conditions for mission termination.

### 4.2 Use-Case and Functional Boundary

Defines:

- authorised functions;
- permitted AI outputs;
- permitted recommendations;
- permitted actions;
- prohibited functions;
- functions requiring additional human approval.

The framework should distinguish between:

**Information → Analysis → Recommendation → Decision Support → Action Support → Authorised Action → Autonomous Action**

Movement toward consequential action requires increasing assurance and clearly defined authority.

### 4.3 Geographic and Operational Boundary

Defines:

- authorised operating area;
- geographic limitations;
- operational boundaries;
- excluded areas;
- transition conditions;
- restrictions associated with crossing a boundary.

### 4.4 Environmental Boundary

Defines the environmental conditions within which the capability has been sufficiently demonstrated.

These may include:

- terrain;
- weather;
- illumination;
- sensor conditions;
- electromagnetic conditions;
- communication availability;
- navigation conditions;
- computing availability;
- adversarial conditions;
- human operating conditions.

### 4.5 Autonomy Boundary

Defines:

- permitted autonomy level;
- actions requiring human approval;
- actions permitted under supervised autonomy;
- prohibited autonomous actions;
- conditions requiring reduction of autonomy;
- conditions requiring human control.

The D-AIGAAF working autonomy scale is:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

This is a D-AIGAAF working construct and should be mapped to applicable national, defence, legal, doctrinal and international terminology before formal adoption.

### 4.6 Human Authority Boundary

Defines:

- responsible human authority;
- operator responsibilities;
- supervisory responsibilities;
- decision rights;
- intervention authority;
- override authority;
- escalation requirements;
- circumstances requiring human control.

AI shall not acquire human decision authority merely because a human is unavailable, delayed or disconnected unless such authority has been explicitly and lawfully authorised.

### 4.7 User Boundary

Defines:

- authorised users;
- required competence;
- role-based permissions;
- supervision requirements;
- prohibited users;
- organisational restrictions.

### 4.8 Configuration Boundary

Defines:

- authorised system version;
- model version;
- model state;
- software baseline;
- hardware configuration;
- interfaces;
- approved settings;
- approved safety controls.

Unapproved material configuration changes shall not inherit operational authority automatically.

### 4.9 Data and Information Boundary

Defines:

- permitted data sources;
- authorised information types;
- data quality requirements;
- provenance requirements;
- data integrity conditions;
- prohibited data sources;
- information-sharing limitations.

### 4.10 Dependency Boundary

Defines reliance on:

- communications;
- navigation;
- sensors;
- compute;
- cloud or external services;
- external AI;
- software components;
- suppliers;
- data providers;
- maintenance services.

Critical dependencies shall have defined failure responses.

### 4.11 Security Boundary

Defines:

- security conditions;
- trusted interfaces;
- authentication requirements;
- integrity requirements;
- monitoring requirements;
- adversarial conditions;
- prohibited connections;
- response to compromise.

### 4.12 Consequence Boundary

Defines the consequences for which the capability has been assured.

Particular attention shall be given to actions that may affect:

- human life;
- physical safety;
- critical infrastructure;
- property;
- sensitive information;
- mission continuity;
- other consequential outcomes.

Higher-consequence applications require proportionately stronger assurance and authority.

---

## 5. Operational Authority versus Technical Capability

D-AIGAAF makes an explicit distinction between:

**What the system can do**

and

**What the system is authorised to do.**

A system may technically be capable of:

- generating an action;
- controlling a platform;
- selecting an object;
- changing configuration;
- communicating with another system;
- operating autonomously;
- producing recommendations outside its intended use.

None of these capabilities create operational authority by themselves.

The authorisation establishes the permitted scope.

---

## 6. Prohibited Use

Prohibited use shall be explicitly identified wherever foreseeable.

Examples may include:

- use outside the authorised mission;
- use outside the approved operating environment;
- use with an unauthorised configuration;
- use beyond the authorised autonomy level;
- use without required human authority;
- use following loss of mandatory safety controls;
- use following material compromise;
- use with materially invalidated data or dependencies;
- use following suspension or revocation;
- use for a function that has not undergone required assurance;
- use after material change without required revalidation or reauthorisation.

The prohibition should be expressed in operationally understandable terms rather than relying only on technical controls.

---

## 7. Boundary Conditions

Every material boundary should have defined conditions for:

1. Entry;
2. Continued operation;
3. Warning;
4. Restriction;
5. Exit;
6. Recovery.

For example, an environmental boundary may define:

**Within Demonstrated Envelope → Warning Zone → Boundary Condition → Outside Envelope**

Crossing into an unvalidated condition should trigger the predefined response.

---

## 8. Boundary Enforcement

Boundary enforcement should use a combination of:

- technical controls;
- configuration controls;
- access controls;
- operational procedures;
- human supervision;
- monitoring;
- alerts;
- autonomy constraints;
- fail-safe mechanisms;
- training;
- command oversight;
- audit and evidence.

No single control should be assumed sufficient for high-consequence applications.

Where technically feasible, critical boundaries should be enforced through technical controls rather than relying exclusively on human memory or procedural compliance.

---

## 9. Boundary Violation

A boundary violation occurs when an AI capability:

- performs an unauthorised function;
- operates outside an authorised environment;
- exceeds its autonomy limit;
- acts without required human authority;
- operates with an unauthorised configuration;
- uses unauthorised data or dependencies;
- continues operating after a mandatory suspension condition;
- crosses a defined operational boundary without appropriate authority.

A boundary violation shall be treated as a governance event.

---

## 10. Response to Boundary Violation

The response should be proportionate to consequence and urgency.

D-AIGAAF uses the following protective sequence:

**Alert → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

The appropriate response should depend on:

- consequence;
- immediacy of risk;
- confidence in the boundary assessment;
- ability to intervene;
- operational context;
- availability of fallback arrangements.

Where delay may create unacceptable harm, pre-authorised emergency protective action may be taken in accordance with the applicable emergency governance provisions.

---

## 11. Boundary Uncertainty

Uncertainty about whether an action or condition is inside an authorised boundary shall not automatically be interpreted as permission.

Where boundary status cannot be reliably established, the capability should move toward the safer predefined operating state.

Examples include:

- uncertain geographic position;
- uncertain target or object classification;
- uncertain environmental conditions;
- uncertain system configuration;
- uncertain autonomy state;
- uncertain human authority;
- uncertain data integrity;
- uncertain communications status.

The system should communicate material uncertainty rather than presenting an uncertain condition as established fact.

---

## 12. Dynamic Boundary Changes

Operational boundaries may change during employment because of:

- mission changes;
- environmental changes;
- degraded communications;
- sensor degradation;
- adversarial activity;
- system behaviour;
- data changes;
- security events;
- changes in human availability;
- changes in autonomy;
- dependency failures;
- legal or policy changes.

Such changes shall be governed through the dynamic operational authority and state-management provisions of D-AIGAAF.

A changing operational situation shall not create implied authority.

---

## 13. Multi-AI and System-of-Systems Boundaries

Where multiple AI systems interact, each system's individual authority shall remain distinct unless the combined arrangement has been appropriately assessed and authorised.

Particular attention shall be given to:

- chained recommendations;
- automated information flows;
- shared data;
- cross-system actions;
- emergent behaviour;
- conflicting outputs;
- autonomy composition;
- failure propagation;
- shared dependencies.

An individually authorised system shall not acquire additional authority merely because it is connected to another authorised system.

---

## 14. Monitoring of Operational Boundaries

Operational monitoring should determine whether the capability remains within:

- mission boundaries;
- environmental boundaries;
- autonomy boundaries;
- human authority boundaries;
- configuration boundaries;
- data boundaries;
- security boundaries;
- dependency boundaries;
- consequence boundaries.

Monitoring should identify:

- boundary approach;
- boundary entry;
- boundary uncertainty;
- boundary violation;
- repeated near-boundary events;
- changes that may invalidate the boundary.

Boundary monitoring should feed continuous assurance.

---

## 15. Boundary Register

A controlled **Operational Boundary Register** should record, where applicable:

| Field | Description |
|---|---|
| Boundary ID | Unique identifier |
| Capability | AI capability covered |
| Mission | Authorised mission/use case |
| Boundary Type | Mission/environment/autonomy/etc. |
| Defined Boundary | Permitted operating condition |
| Prohibited Condition | Condition outside authority |
| Entry Criteria | Conditions for entering the boundary |
| Warning Threshold | Early warning condition |
| Exit Criteria | Conditions requiring exit |
| Protective Response | Required response |
| Human Authority | Responsible authority |
| Evidence | Evidence supporting the boundary |
| Configuration | Applicable baseline |
| Monitoring | Required monitoring |
| Review Trigger | Conditions requiring review |
| Status | Current boundary status |

---

## 16. Relationship with Authorisation

Operational boundaries are an integral component of operational authorisation.

The authorisation should identify:

- what is authorised;
- what is not authorised;
- under what conditions;
- within what environment;
- at what autonomy level;
- under whose authority;
- using which configuration;
- for how long;
- subject to what restrictions.

A boundary should therefore be traceable to the authorisation record and its supporting assurance evidence.

---

## 17. Relationship with Revalidation and Reauthorisation

The following may require revalidation or reauthorisation:

- expansion beyond an established boundary;
- higher autonomy;
- new mission;
- new environment;
- new consequential function;
- material configuration change;
- material data change;
- material dependency change;
- changed human-control arrangements;
- evidence that an existing boundary is no longer valid.

Boundary expansion should not be treated as a routine administrative change where it materially changes risk or authority.

---

## 18. Golden Thread Traceability

Operational boundaries should remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Boundary Event → Change/Incident → Revalidation/Reauthorisation**

This enables an organisation to determine why a boundary exists, what evidence supports it, who approved it and what happens when it is approached or crossed.

---

## 19. Governance Questions

Before operational employment, decision-makers should be able to answer:

1. What exactly is this AI capability authorised to do?
2. What is it explicitly prohibited from doing?
3. Where may it operate?
4. Under what environmental conditions?
5. At what autonomy level?
6. Who holds human authority?
7. What configuration is authorised?
8. What data and dependencies are permitted?
9. What happens when a boundary is approached?
10. What happens when a boundary is crossed?
11. How is uncertainty communicated?
12. Who can restrict, reduce autonomy, place the system in a safe state or suspend it?
13. What evidence supports each material boundary?
14. What changes would require revalidation or reauthorisation?

If these questions cannot be answered clearly, the operational boundary is insufficiently defined.

---

## 20. Core Rule

> **A Defence AI capability shall operate only within clearly defined and enforceable operational boundaries covering its mission, function, environment, autonomy, human authority, configuration, data, dependencies and other material conditions. Technical capability shall not be interpreted as operational permission. Material boundary uncertainty or violation shall trigger proportionate protective action, including restriction, reduced autonomy, human control, safe state or suspension where required.**
