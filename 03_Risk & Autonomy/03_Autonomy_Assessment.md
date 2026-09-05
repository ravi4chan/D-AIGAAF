# Autonomy Assessment

## Purpose

The D-AIGAAF Autonomy Assessment provides a structured method for determining the **actual, intended and authorised degree of autonomy** of an AI-enabled capability.

The assessment establishes whether the system's technical behaviour, human-control arrangements, operational boundaries and evidence support the proposed autonomy level.

The central principle is:

> **Autonomy must be assessed from what the system can actually do, not merely what it is intended or claimed to do.**

Autonomy assessment therefore connects technical capability with mission consequence, operational context, human authority, risk and assurance.

---

## 1. Core Principle

A D-AIGAAF autonomy assessment should distinguish between:

**Technical Autonomy → Intended Autonomy → Assessed Autonomy → Assured Autonomy → Authorised Autonomy**

These are not automatically equivalent.

A system may technically be capable of higher autonomy than the level authorised for operational use.

Similarly, a system described as "human-in-the-loop" may not provide meaningful human control if the human cannot understand, intervene in or stop the relevant action.

---

## 2. Objectives

The autonomy assessment should determine:

- what the AI can technically do;
- what the system is designed to do;
- what the use case requires;
- what the human is expected to do;
- what the AI can decide;
- what the AI can initiate;
- what the AI can execute;
- how long it can operate independently;
- what operational scope it can affect;
- whether it can adapt;
- whether it can escalate its behaviour;
- how human intervention works;
- what happens when conditions degrade;
- what happens when communications are lost;
- what evidence supports the claimed autonomy;
- whether the proposed autonomy is appropriate to consequence and mission;
- what autonomy can be operationally authorised.

---

## 3. Assessment Principle

Autonomy should be assessed at the level at which consequential outcomes can occur.

The assessment should consider the complete chain:

```text
Input
  ↓
Perception / Information Processing
  ↓
Assessment
  ↓
Recommendation
  ↓
Decision
  ↓
Action Selection
  ↓
Action Execution
  ↓
Operational Effect
```

The assessment should identify which steps are performed by:

- AI;
- automated software;
- human operators;
- commanders;
- external systems;
- combinations of these.

The highest consequential autonomy in the chain should be explicitly identified.

---

## 4. Autonomy Assessment Scope

Assessment should cover, as applicable:

### AI Model
- output generation;
- prediction;
- classification;
- recommendation;
- uncertainty;
- adaptation.

### System
- decision logic;
- rules;
- automation;
- interfaces;
- sensors;
- actuators;
- connected systems.

### Human
- operator;
- analyst;
- commander;
- authorising authority;
- technical personnel.

### Operational Context
- mission;
- environment;
- communications;
- information;
- adversarial conditions;
- time pressure;
- human workload.

### Dependencies
- sensors;
- networks;
- navigation;
- computing;
- power;
- external services;
- other systems;
- suppliers.

---

## 5. D-AIGAAF Autonomy Scale

The assessment uses the working D-AIGAAF autonomy construct:

| Level | Description | Key Question |
|---|---|---|
| **A0** | No meaningful AI decision | Does AI have no meaningful role in the decision/action? |
| **A1** | Information / observation | Does AI primarily observe, detect, classify or organise information? |
| **A2** | Analysis / recommendation | Does AI analyse information or recommend an option while a human decides? |
| **A3** | Human-authorised action | Can AI formulate or initiate a consequential action that requires explicit human approval before execution? |
| **A4** | Supervised autonomous action | Can AI execute predefined actions within an authorised envelope while humans supervise and retain defined intervention authority? |
| **A5** | Independent consequential autonomy | Can AI independently decide and execute consequential actions without immediate human authorisation? |

This is a **D-AIGAAF working construct**. It should be mapped to applicable national, defence, legal, doctrinal and international terminology before formal adoption.

---

## 6. Assessment Dimensions

Autonomy should not be determined using a single question.

At minimum, assess the following dimensions.

### 6.1 Decision Autonomy

Determine whether AI:

- only provides information;
- provides analysis;
- recommends a decision;
- selects between alternatives;
- makes a decision independently.

### 6.2 Action Autonomy

Determine whether AI:

- cannot initiate action;
- proposes an action;
- initiates a human-authorised action;
- executes predefined actions;
- independently selects and executes actions.

### 6.3 Temporal Autonomy

Determine:

- whether continuous human attention is required;
- how frequently human review is required;
- how long the system can operate without human intervention;
- what happens if the review window is missed.

### 6.4 Scope Autonomy

Determine the maximum scope over which the AI can act, including:

- objects;
- users;
- systems;
- geographic area;
- mission;
- actions;
- duration.

### 6.5 Adaptation Autonomy

Determine whether the system can:

- operate only from fixed rules;
- adjust within predefined parameters;
- change behaviour based on new information;
- modify operational behaviour beyond predefined expectations.

### 6.6 Escalation Autonomy

Determine whether the system can move from:

- observation to recommendation;
- recommendation to action;
- low-consequence action to high-consequence action;
- one operational boundary to another.

> **AI must not be permitted to expand its own authority.**

### 6.7 Recovery Autonomy

Determine whether the system can independently:

- detect faults;
- change operating modes;
- reduce capability;
- isolate itself;
- transfer control;
- enter a safe state;
- recover operation.

Recovery autonomy should be assessed separately from mission autonomy.

---

## 7. Technical Autonomy Assessment

The first assessment should determine the system's **maximum credible technical autonomy**.

Questions include:

1. What decisions can the system technically make?
2. What actions can it technically initiate?
3. What actions can it technically execute?
4. Can it select between alternatives?
5. Can it operate without communications?
6. Can it operate without direct human supervision?
7. Can it continue after a human becomes unavailable?
8. Can it modify its own behaviour?
9. Can it interact with other systems?
10. Can it trigger consequential downstream actions?
11. Can it continue operating after detecting abnormal conditions?
12. Can it cross a predefined boundary?

The assessment should identify capabilities that may exist even if they are not intended for operational use.

---

## 8. Intended Autonomy

The intended autonomy level should be explicitly defined for the particular use case.

For example:

```text
Technical Capability: A4
        ↓
Intended Use Case: A2
        ↓
Authorised Operational Use: A2
```

This means the system may technically support greater automation, but only the lower level is intended and authorised.

Technical capability beyond the authorised level should be controlled through appropriate technical and procedural safeguards.

---

## 9. Effective Autonomy

Effective autonomy is the degree of autonomy that exists **in practice during operation**.

It may differ from the intended level because of:

- configuration;
- automation settings;
- software behaviour;
- human workload;
- interface design;
- communications conditions;
- dependency failures;
- unexpected system behaviour;
- operator workarounds;
- degraded conditions;
- system integration.

For this reason:

> **Effective autonomy must be assessed in representative operational conditions.**

---

## 10. Human Control Assessment

The autonomy assessment must determine whether human control is meaningful.

Assess:

### Information
Does the human receive sufficient information to understand the situation and AI output?

### Authority
Can the human legitimately approve, reject, modify or stop the relevant action?

### Competence
Does the human understand the AI system and its limitations?

### Time
Is there sufficient time to exercise meaningful judgement?

### Independence
Can the human disagree with the AI recommendation?

### Intervention
Can the human technically intervene?

### Accountability
Is responsibility for the resulting decision or action clearly assigned?

Human presence alone is not sufficient.

---

## 11. Human-AI Decision Chain

For consequential decisions, document:

```text
AI Observation / Analysis
        ↓
AI Recommendation
        ↓
Human Assessment
        ↓
Human Decision
        ↓
Authorised Action
        ↓
Operational Effect
```

Where the system can bypass one or more of these stages, the autonomy assessment should explicitly identify the bypass.

The distinction remains:

**AI Output ≠ Human Decision ≠ Command Authority**

---

## 12. Autonomy and Consequence

The proposed autonomy level should be assessed against the potential consequence of system behaviour.

Higher scrutiny is required where autonomy can affect:

- human life;
- physical safety;
- use of force;
- friendly-force safety;
- civilian safety;
- critical infrastructure;
- strategic decisions;
- major operational outcomes;
- significant property;
- irreversible outcomes.

The assessment should identify the **worst credible consequence** of autonomous behaviour.

---

## 13. Operational Environment Assessment

Autonomy should be assessed under conditions representative of intended employment.

Consider:

- normal conditions;
- degraded conditions;
- communications denial;
- intermittent communications;
- sensor degradation;
- conflicting information;
- incomplete information;
- adversarial inputs;
- cyber compromise;
- electronic interference;
- high workload;
- rapidly changing situations;
- loss of dependencies;
- disconnected operation.

A system that is A4 under controlled conditions may not safely remain A4 under degraded or contested conditions.

The effective autonomy level may need to reduce automatically or through human intervention.

---

## 14. Autonomy Under Communications Loss

Communications loss should be explicitly assessed where relevant.

Determine:

- whether the system can continue operating;
- how long it can continue;
- what decisions it can make;
- what actions it can execute;
- whether autonomy changes;
- whether human control remains meaningful;
- whether the system transitions to a safe state;
- how authority is restored.

Example:

```text
Communications Available
        ↓
A4 Supervised Autonomy
        ↓
Communications Lost
        ↓
Predefined Transition
        ↓
A2 / Reduced Autonomy / Safe State
```

The transition should be defined and tested rather than assumed.

---

## 15. Autonomy Under Information Degradation

Assess system behaviour when information is:

- missing;
- stale;
- contradictory;
- corrupted;
- manipulated;
- uncertain;
- unavailable.

The system should not silently treat degraded information as reliable information.

Where information quality falls below the authorised threshold, predefined responses may include:

- warning;
- increased human review;
- reduced autonomy;
- controlled degradation;
- suspension;
- fail-safe action.

---

## 16. Uncertainty and Autonomy

Higher autonomy increases the importance of uncertainty communication.

The assessment should determine whether the system:

- identifies uncertainty;
- communicates confidence appropriately;
- distinguishes known from inferred information;
- identifies missing information;
- avoids presenting uncertain outputs as facts;
- triggers appropriate human review when uncertainty is high.

A system that cannot reliably communicate important uncertainty should not automatically be granted higher autonomy.

---

## 17. Adversarial Autonomy Assessment

Where relevant, assess whether autonomy remains controlled under:

- manipulated inputs;
- adversarial examples;
- deceptive information;
- compromised sensors;
- cyber attacks;
- malicious instructions;
- compromised dependencies;
- insider threats;
- attempts to induce unsafe actions.

Assessment should determine whether adversarial conditions can cause:

- incorrect decisions;
- unsafe actions;
- boundary violations;
- loss of human control;
- unexpected escalation;
- failure of fail-safe mechanisms.

---

## 18. Autonomy Boundary Testing

The assessment should identify:

### Within Boundary
Conditions under which the proposed autonomy has been tested and supported by evidence.

### Boundary Condition
Conditions close to the edge of authorised operation requiring additional scrutiny or monitoring.

### Outside Boundary
Conditions where the autonomy has not been adequately demonstrated or is not authorised.

The governing relationship is:

**Tested Boundary → Assured Boundary → Authorised Boundary**

Capability beyond the authorised boundary does not create operational authority.

---

## 19. Autonomy Transition Assessment

Where autonomy can change during operation, assess every material transition.

For each transition define:

- starting autonomy level;
- trigger;
- destination autonomy level;
- authority;
- operational condition;
- human-control requirement;
- maximum duration;
- fail-safe response;
- logging requirement.

Example:

```text
A2 → A3
Trigger: Explicit human authorisation
Authority: Designated operational authority
Condition: Defined operational envelope
Evidence: Validated transition behaviour
```

No increase in autonomy should occur without a defined authority basis.

---

## 20. Fail-Safe Assessment

The assessment should determine whether the system can safely respond when:

- it detects abnormal behaviour;
- it loses required information;
- it loses communications;
- a critical dependency fails;
- human control becomes unavailable;
- operating conditions exceed the authorised envelope;
- security integrity is compromised.

Possible responses include:

- warning;
- reduced autonomy;
- controlled degradation;
- isolation;
- human control;
- suspension;
- fail-safe;
- emergency protective action.

Fail-safe should be treated as a **last-resort protective mechanism**, supported by testing.

---

## 21. Autonomy Evidence

Evidence should demonstrate the actual behaviour of the system.

Evidence may include:

- laboratory testing;
- controlled trials;
- representative environment trials;
- adversarial testing;
- red-team testing;
- human factors evaluation;
- operational trials;
- failure testing;
- communications-loss testing;
- degraded-condition testing;
- intervention testing;
- fail-safe testing;
- configuration verification;
- security testing;
- mission-level evaluation.

Evidence should be traceable to the claimed autonomy level.

---

## 22. Progressive Assurance

Autonomy evidence should generally progress through:

```text
Laboratory
    ↓
Controlled Environment
    ↓
Representative Environment
    ↓
Adversarial / Red-Team
    ↓
Operational Environment
    ↓
Mission-Level Evaluation
    ↓
Assurance
    ↓
Operational Authorisation
```

Higher-consequence autonomy requires stronger and more representative evidence.

Passing a laboratory test does not establish operational autonomy.

---

## 23. Autonomy Assessment Outcome

The assessment should produce one of the following outcomes:

### Supported
Evidence supports the proposed autonomy level within the defined conditions.

### Supported With Conditions
The autonomy level may be supported subject to specified controls or restrictions.

### Partially Supported
Evidence supports only part of the proposed autonomy envelope.

### Not Supported
Evidence does not justify the proposed autonomy level.

### Not Assessable
Insufficient evidence exists to determine the autonomy level reliably.

### Restricted
Only a lower autonomy level or narrower operational envelope may be considered.

---

## 24. Recommended Assessment Record

A D-AIGAAF Autonomy Assessment Record should contain:

| Field | Description |
|---|---|
| Assessment ID | Unique identifier |
| Capability | AI-enabled capability |
| Model / System | Relevant system components |
| Mission | Supported mission |
| Use Case | Specific use case |
| Technical Autonomy | Maximum credible technical autonomy |
| Intended Autonomy | Intended autonomy level |
| Effective Autonomy | Observed/assessed operational autonomy |
| Decision Autonomy | Decision-making capability |
| Action Autonomy | Action capability |
| Temporal Autonomy | Duration without human intervention |
| Scope Autonomy | Operational scope |
| Adaptation | Adaptation capability |
| Escalation | Escalation capability |
| Recovery | Recovery autonomy |
| Human Control | Human-control assessment |
| Environment | Assessed conditions |
| Threats | Relevant adversarial conditions |
| Dependencies | Critical dependencies |
| Boundaries | Tested/assured boundaries |
| Transitions | Autonomy transitions |
| Fail-Safe | Protective behaviour |
| Evidence | Supporting evidence |
| Limitations | Known limitations |
| Uncertainty | Material uncertainty |
| Risk | Linked risk assessment |
| Assurance | Assurance position |
| Proposed Authority | Required operational authority |
| Status | Assessment status |
| Reviewer | Responsible assessor |
| Date | Assessment date |

---

## 25. Relationship With Risk

Autonomy assessment must feed directly into risk assessment.

The relationship is:

**Autonomy → Consequence → Risk → Required Controls → Evidence → Assurance → Authority**

An increase in autonomy may increase risk even if technical performance remains unchanged.

For example:

```text
A2 Recommendation
       ↓
Human evaluates and decides
       ↓
Limited autonomous consequence
```

may have a materially different risk profile from:

```text
A4 Autonomous Action
       ↓
System executes within envelope
       ↓
Reduced immediate human intervention
```

The model performance may be identical; the operational risk is not.

---

## 26. Relationship With Operational Authorisation

Autonomy assessment informs operational authorisation.

The authorisation should bind autonomy to:

**Capability × Mission × Environment × Human Authority**

An authorisation should state:

- permitted autonomy level;
- permitted transitions;
- operational envelope;
- human-control requirements;
- prohibited behaviours;
- fail-safe conditions;
- monitoring requirements;
- review period;
- suspension triggers;
- reauthorisation triggers.

---

## 27. Change and Reassessment

Autonomy should be reassessed when material changes occur.

Examples include:

- model updates;
- software updates;
- changes to decision logic;
- new sensors;
- changed data sources;
- new interfaces;
- changed dependencies;
- changes in human-machine interface;
- changes in operating environment;
- changes in mission;
- changes in autonomy settings;
- security incidents;
- unexpected behaviour.

A change that materially affects behaviour should trigger appropriate revalidation, TEVV and potentially reauthorisation.

> **Previous autonomy authorisation does not automatically authorise changed behaviour.**

---

## 28. Continuous Autonomy Monitoring

During operational employment, monitor for:

- autonomy drift;
- unexpected decisions;
- unexpected actions;
- boundary violations;
- changes in system behaviour;
- changes in human workload;
- degraded intervention effectiveness;
- changes in operating conditions;
- dependency failures;
- security events;
- abnormal escalation;
- fail-safe activation.

Operational observations should feed the risk and assurance processes.

---

## 29. Failure Modes

D-AIGAAF should guard against:

- confusing intended autonomy with actual autonomy;
- assuming model capability equals system autonomy;
- assessing only normal operating conditions;
- ignoring communications-denied conditions;
- assuming human presence equals meaningful control;
- failing to test human intervention;
- failing to assess maximum technical capability;
- allowing hidden autonomy through system integration;
- allowing silent autonomy escalation;
- treating supervision as equivalent to decision authority;
- ignoring recovery autonomy;
- ignoring adaptation;
- relying only on supplier claims;
- treating laboratory performance as operational evidence;
- failing to reassess after changes;
- treating previous authorisation as permanent;
- failing to record consequential autonomous behaviour.

---

## 30. Golden Thread

The autonomy assessment should remain traceable through:

**Mission Need → Use Case → Risk → Autonomy → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Every significant autonomy claim should therefore be traceable to:

- the mission requiring it;
- the use case defining it;
- the risk created by it;
- the controls constraining it;
- the evidence supporting it;
- the assurance conclusion;
- the authority permitting it.

---

## 31. Core Rules

1. **Assess actual capability, not only intended behaviour.**
2. **Technical autonomy does not equal operational authority.**
3. **Autonomy must be assessed at the system and mission level where consequences occur.**
4. **Human presence does not automatically constitute meaningful human control.**
5. **Higher consequence requires stronger autonomy evidence and controls.**
6. **Autonomy must be assessed under representative and degraded conditions.**
7. **Autonomy transitions must be explicit and controlled.**
8. **AI must not silently increase its own autonomy or authority.**
9. **Loss of control must be explicitly assessed.**
10. **Fail-safe behaviour must be tested.**
11. **Autonomy claims must be supported by traceable evidence.**
12. **Material changes require reassessment.**
13. **Previous authorisation does not automatically authorise changed behaviour.**
14. **Effective autonomy must be continuously monitored.**
15. **Autonomy assessment informs authority; it does not create authority.**

---

## 32. Summary Model

```text
TECHNICAL CAPABILITY
        ↓
INTENDED AUTONOMY
        ↓
ACTUAL / EFFECTIVE AUTONOMY
        ↓
HUMAN CONTROL
        ↓
CONSEQUENCE + MISSION CRITICALITY
        ↓
OPERATIONAL ENVIRONMENT
        ↓
THREATS + DEPENDENCIES
        ↓
AUTONOMY BOUNDARIES
        ↓
AUTONOMY EVIDENCE
        ↓
ASSURED AUTONOMY
        ↓
OPERATIONAL AUTHORITY
        ↓
EMPLOYMENT
        ↓
CONTINUOUS MONITORING
        ↓
REASSESSMENT / REAUTHORISATION
```

The purpose of autonomy assessment is not to maximise or minimise autonomy.

It is to establish whether **the autonomy actually available, intended, demonstrated and authorised is appropriate to the mission, consequence, operational environment, human authority, risk and available evidence.**
