# Mission Constraints

## 1. Purpose

Mission Constraints define the conditions, limitations and boundaries that restrict how an AI capability may be designed, tested, authorised and employed for a particular mission.

Constraints are not merely implementation limitations.

A constraint may determine:

- whether the capability is suitable for the mission;
- the required level of assurance;
- the appropriate autonomy;
- the human authority required;
- the operational envelope;
- whether deployment is permissible at all.

---

## 2. Core Principle

The governing principle is:

> **A capability must be assessed against the constraints under which it is actually expected to operate.**

A system that performs well under favourable conditions may not be suitable when mission constraints materially reduce information, connectivity, human intervention or system resilience.

---

## 3. Types of Mission Constraints

Mission constraints may arise from:

1. Operational conditions
2. Environmental conditions
3. Information and data
4. Communications
5. Technology
6. Human factors
7. Time
8. Security
9. Legal and policy requirements
10. Resources
11. Supply chain
12. Interoperability
13. Safety
14. Autonomy and human authority

Multiple constraints may interact and create greater risk than any individual constraint considered separately.

---

## 4. Operational Constraints

Operational constraints may include:

- mission objectives;
- geographic boundaries;
- operating areas;
- authorised users;
- available personnel;
- command structure;
- operating procedures;
- mission tempo;
- operational phase;
- permitted functions;
- rules and restrictions on system use.

Operational constraints should be explicitly reflected in the use case and operational authorisation.

---

## 5. Environmental Constraints

Environmental constraints may include:

- temperature;
- humidity;
- dust;
- smoke;
- rain;
- snow;
- ice;
- fog;
- darkness;
- glare;
- vibration;
- altitude;
- terrain;
- water exposure;
- electromagnetic interference.

Where environmental conditions can materially affect system behaviour, they should be included in TEVV.

---

## 6. Information and Data Constraints

AI systems may operate with imperfect information.

Relevant constraints may include:

- incomplete data;
- stale data;
- delayed data;
- low-quality data;
- conflicting information;
- limited data availability;
- uncertain provenance;
- sensor limitations;
- classification restrictions;
- access restrictions;
- data drift.

The capability should define how it behaves when required information is unavailable or unreliable.

---

## 7. Communications Constraints

Communication constraints may include:

- limited bandwidth;
- intermittent connectivity;
- high latency;
- communication loss;
- disconnected operation;
- offline operation;
- restricted external connectivity.

Where possible, the system should define safe behaviour following communications degradation or loss.

A system requiring continuous connectivity should not be treated as equivalent to a system designed to operate safely while disconnected.

---

## 8. Computing and Infrastructure Constraints

Relevant technical constraints may include:

- processing capacity;
- memory;
- storage;
- power;
- network availability;
- hardware availability;
- edge-computing limitations;
- cooling;
- maintenance;
- system availability.

Resource constraints should be considered during representative testing rather than assumed to have no operational effect.

---

## 9. Sensor Constraints

AI-enabled systems may depend on sensors that can degrade or fail.

Potential constraints include:

- limited field of view;
- reduced resolution;
- occlusion;
- weather effects;
- sensor noise;
- calibration errors;
- sensor failure;
- spoofing;
- conflicting sensors.

The use case should identify what happens when critical sensor inputs become unreliable.

---

## 10. Human Constraints

Human factors can materially affect the effectiveness of AI-enabled capabilities.

Relevant constraints may include:

- limited staffing;
- fatigue;
- workload;
- stress;
- training;
- experience;
- attention;
- decision time;
- availability of specialist personnel;
- ability to understand AI outputs;
- ability to intervene.

A human-control mechanism should not be considered effective merely because an operator is nominally present.

---

## 11. Time Constraints

Some missions impose strict time limits.

These may include:

- response time;
- decision windows;
- processing latency;
- time available for human review;
- time between detection and action;
- duration of system availability;
- time required to recover from failure.

If human review cannot realistically occur within the available decision window, the claimed human-control model may not be meaningful.

---

## 12. Security Constraints

Security requirements may constrain:

- system connectivity;
- data access;
- external services;
- software updates;
- model updates;
- supplier access;
- remote administration;
- logging;
- storage;
- system interfaces.

Security controls should not be removed merely to improve convenience or performance without appropriate risk assessment and authority.

---

## 13. Legal and Policy Constraints

AI employment must remain within applicable:

- law;
- national policy;
- defence policy;
- doctrine;
- directives;
- rules and procedures;
- safety requirements;
- information-handling requirements.

D-AIGAAF does not override these constraints.

Where legal or policy requirements are stricter than technical capability, the stricter requirement governs.

---

## 14. Resource Constraints

Mission resources may include:

- personnel;
- equipment;
- power;
- communications;
- computing;
- maintenance;
- training;
- logistics;
- specialist support;
- time.

A capability should not depend on resources that cannot reliably be provided within the intended operational environment.

---

## 15. Supply-Chain Constraints

Supply-chain constraints may include:

- supplier availability;
- critical third-party dependencies;
- update mechanisms;
- proprietary components;
- licensing;
- support arrangements;
- foreign dependencies;
- limited ability to inspect components;
- limited ability to independently verify critical behaviour.

Critical dependencies should be identified before operational authority is granted.

---

## 16. Interoperability Constraints

AI capabilities may need to operate with existing systems.

Constraints may arise from:

- incompatible interfaces;
- data formats;
- communication protocols;
- legacy systems;
- authentication mechanisms;
- security boundaries;
- timing requirements;
- dependency on external systems.

Interoperability assumptions should be tested in representative configurations.

---

## 17. Autonomy Constraints

Mission constraints should define the maximum acceptable autonomy for the intended use case.

The technically possible autonomy level may exceed the operationally authorised level.

Constraints may specify:

- tasks AI may perform;
- decisions AI may recommend;
- actions requiring explicit human approval;
- actions permitted under supervision;
- actions prohibited entirely.

Autonomy should be constrained by consequence, context and human authority.

---

## 18. Human Authority Constraints

The use case should specify what humans must retain authority over.

This may include:

- approval;
- rejection;
- override;
- escalation;
- suspension;
- fail-safe activation;
- mission termination;
- restoration of operation.

Human authority should remain explicit even where AI systems perform highly automated functions.

---

## 19. Safety Constraints

Safety constraints should identify actions or behaviours that are unacceptable regardless of technical performance.

Examples may include:

- unsafe system states;
- uncontrolled physical action;
- operation outside defined limits;
- unsafe failure recovery;
- loss of human control;
- unauthorised interaction with critical systems.

Safety constraints should be reflected in system requirements and tested where practical.

---

## 20. Constraint Interactions

Constraints should be assessed in combination.

For example:

**Communications loss + incomplete information + high time pressure + reduced human availability**

may create a substantially different operational risk from any single condition.

Important combinations should therefore be considered during risk assessment and TEVV.

---

## 21. Constraint Hierarchy

Where constraints conflict, the implementing organisation should establish a clear hierarchy.

A generic ordering may be:

**Law and mandatory policy → Safety and protection of life → Command authority → Operational requirements → Security requirements → Technical and resource considerations**

The precise hierarchy must be determined by applicable law, policy and organisational authority.

D-AIGAAF does not establish legal precedence where such precedence is already defined elsewhere.

---

## 22. Constraints and Risk

Constraints are direct inputs to risk assessment.

The relationship can be represented as:

**Mission + Use Case + Constraints → Risk**

Constraints may increase:

- probability of failure;
- uncertainty;
- consequence;
- human-control difficulty;
- dependency risk;
- loss-of-control risk.

Risk assessment should therefore explicitly record material mission constraints.

---

## 23. Constraints and Assurance

Assurance evidence should demonstrate performance under relevant constraints.

For each significant constraint, the organisation should determine whether the condition is:

- demonstrated;
- partially demonstrated;
- controlled;
- unsupported;
- unknown.

Unknown or unsupported constraints should not silently be treated as acceptable operating conditions.

---

## 24. Constraints and Operational Authorisation

Operational authorisation should translate important constraints into explicit conditions.

Examples include:

- geographic restriction;
- connectivity requirement;
- minimum sensor availability;
- maximum autonomy;
- required human supervision;
- minimum operator competency;
- prohibited environmental conditions;
- restricted mission functions.

Conditions should be visible to operators and decision-makers.

---

## 25. Constraint Monitoring

Where constraints can change during operation, they should be monitored where practical.

Examples include:

- communications status;
- sensor availability;
- data quality;
- system integrity;
- environmental conditions;
- human availability;
- system configuration.

A material transition outside the authorised constraint set may require:

- reduced autonomy;
- controlled degradation;
- human intervention;
- suspension;
- escalation;
- reauthorisation.

---

## 26. Constraint Violations

A constraint violation occurs when an AI capability operates outside an explicitly defined mission condition.

Examples include:

- operating outside the authorised geography;
- using unsupported data;
- exceeding authorised autonomy;
- operating after a critical dependency fails;
- operating outside tested environmental conditions;
- continuing after a material configuration change.

Constraint violations should be recorded and assessed for their effect on risk and authorisation.

---

## 27. Mission Constraint Record

A consequential AI capability should maintain a Mission Constraint Record containing, as applicable:

- operational constraints;
- environmental constraints;
- data constraints;
- communications constraints;
- computing constraints;
- sensor constraints;
- human constraints;
- time constraints;
- security constraints;
- legal and policy constraints;
- resource constraints;
- supply-chain constraints;
- interoperability constraints;
- autonomy constraints;
- human-authority constraints;
- safety constraints;
- constraint interactions;
- monitoring requirements;
- violation handling.

---

## 28. Minimum Mission Constraint Requirements

Before consequential operational use, the capability should have:

1. Identified material operational constraints.
2. Identified relevant environmental constraints.
3. Identified information and data limitations.
4. Defined communications dependencies.
5. Defined technical and infrastructure limitations.
6. Identified sensor limitations.
7. Assessed human constraints.
8. Defined relevant time constraints.
9. Identified security constraints.
10. Identified legal and policy constraints.
11. Identified critical resource and supply-chain constraints.
12. Defined autonomy and human-authority limits.
13. Defined safety constraints.
14. Assessed important combinations of constraints.
15. Defined how constraint violations are detected and handled.

---

## 29. Relationship With D-AIGAAF

This module connects directly with:

- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `03 Risk & Autonomy`
- `05 Data & Information`
- `06 AI Security`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`

It strengthens the Golden Thread by ensuring that:

**Mission → Use Case → Context → Constraints → Requirements → Risk → Assurance → Authority**

remains traceable.

---

## 30. Summary

Mission constraints define the conditions under which an AI capability must remain reliable, controllable and authorised.

They transform broad operational assumptions into explicit boundaries.

The central rule is:

> **A capability should not be authorised on the assumption that constraints will always be favourable.**

Material constraints must be identified, tested where practical, reflected in operational conditions and monitored throughout employment.
