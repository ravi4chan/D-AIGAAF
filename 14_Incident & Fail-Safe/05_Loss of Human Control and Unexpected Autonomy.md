# 05 — Loss of Human Control and Unexpected Autonomy

## 1. Purpose

This document defines governance requirements for detecting, managing and learning from situations in which human control over a Defence AI capability is lost, materially degraded or unexpectedly bypassed, including unexpected or unauthorised autonomous behaviour.

The objective is to ensure that human authority remains meaningful throughout AI-supported operations and that loss of control or unexpected autonomy results in timely protective action and appropriate assurance review.

---

## 2. Core Principle

> **A Defence AI capability shall not be considered safely governed where authorised humans cannot exercise the degree of understanding, supervision, intervention, override or termination required by its consequence and authorisation. Unexpected or unauthorised autonomy, or material loss of human control, shall trigger proportionate protective action and assurance reassessment.**

---

## 3. Human-Control Object

Assessment should consider:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions**

Human control is contextual and should be assessed against the actual operational use.

---

## 4. Human Control

Human control includes the practical ability of authorised personnel to:

- understand relevant AI outputs;
- assess uncertainty;
- make required decisions;
- supervise AI activity;
- intervene;
- override;
- reduce autonomy;
- place the system in a safe state;
- suspend operation.

The required degree of control depends on consequence and autonomy.

---

## 5. Meaningful Human Control

Meaningful human control requires more than nominal human presence.

It should consider:

- appropriate authority;
- sufficient information;
- adequate time;
- relevant competence;
- practical intervention;
- effective override;
- awareness of system state;
- ability to terminate or restrict activity.

---

## 6. Loss of Human Control

Loss of human control may occur when:

- the authorised person cannot intervene;
- intervention is ineffective;
- override fails;
- system behaviour cannot be sufficiently understood;
- communications prevent required supervision;
- workload prevents meaningful assessment;
- autonomy exceeds authority;
- the system acts outside defined boundaries.

---

## 7. Degrees of Control

A capability may experience:

### Normal Control

Human authority and intervention operate as intended.

### Degraded Control

Human control remains possible but with reduced effectiveness.

### Restricted Control

Human control is significantly constrained and additional restrictions are required.

### Loss of Control

Required human authority or intervention is no longer reliably available.

---

## 8. Control Failure Indicators

Indicators may include:

- inability to obtain system status;
- inability to determine current autonomy;
- delayed or failed intervention;
- unexpected actions;
- unexpected state transitions;
- conflicting system states;
- unavailable override;
- excessive workload;
- loss of communication where communication is required.

---

## 9. Unexpected Autonomy

Unexpected autonomy is behaviour in which the AI performs, enters or attempts an autonomous function beyond what was:

- authorised;
- expected;
- configured;
- operationally bounded.

Unexpected autonomy should be treated as an assurance-significant event.

---

## 10. Unauthorised Autonomy

Unauthorised autonomy occurs where the system operates at an autonomy level or performs autonomous functions not permitted by the applicable authority.

This may occur even when the underlying technical capability was previously assured.

---

## 11. Autonomy States

D-AIGAAF uses the working autonomy model:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

The applicable authorised state must be known during employment.

---

## 12. Autonomy State Awareness

Personnel should be able to determine, where practicable:

- current autonomy state;
- authorised autonomy state;
- transition status;
- functions operating autonomously;
- applicable boundaries;
- intervention options.

Ambiguity about autonomy state may itself constitute a control concern.

---

## 13. Unexpected Autonomy Transitions

Potential events include:

- A2 → A3 without required human authorisation;
- A3 → A4 without authorisation;
- A4 → higher or broader autonomous behaviour;
- failure to reduce autonomy;
- autonomous continuation after human withdrawal of authority.

Such events require immediate assessment.

---

## 14. Autonomy Boundary

Autonomy should remain bounded by:

- mission;
- function;
- geography;
- time;
- environment;
- data;
- configuration;
- consequence;
- human authority.

Technical capability does not establish operational permission.

---

## 15. Loss of Human Authority

Loss of human authority may result from:

- unclear delegation;
- conflicting instructions;
- unavailable responsible authority;
- communication failure;
- organisational ambiguity;
- system behaviour that bypasses authorised decision points.

Authority gaps should be treated as governance concerns.

---

## 16. Human-AI Disagreement

Where the AI and authorised human disagree, the applicable authority and decision rules should remain clear.

AI output should not automatically override authorised human judgement unless a separately defined and authorised autonomous function applies.

---

## 17. Automation Bias

Human control may be degraded where personnel:

- over-trust AI output;
- fail to question recommendations;
- defer to system confidence indicators;
- ignore conflicting evidence;
- assume the system is correct because it is authorised.

Training and interface design should address automation bias.

---

## 18. Situational Awareness

Meaningful human control requires sufficient awareness of:

- mission context;
- relevant information;
- AI contribution;
- uncertainty;
- system state;
- autonomy;
- environmental conditions;
- limitations.

AI should not reduce human situational awareness to the point that effective control becomes impracticable.

---

## 19. Time Pressure

Where decisions are time-critical, human-control requirements should account for:

- available decision time;
- response latency;
- workload;
- intervention time;
- consequences of delay.

A nominal human approval step may not constitute meaningful control if the person cannot realistically assess or intervene.

---

## 20. Human Workload

Workload should be monitored where it may affect:

- attention;
- decision quality;
- supervision;
- intervention;
- situational awareness.

Excessive workload can create practical loss of human control even where technical controls remain available.

---

## 21. Intervention Capability

Intervention mechanisms should permit authorised personnel, where required, to:

- pause;
- stop;
- restrict;
- reduce autonomy;
- override;
- transition to safe state.

Mechanisms should be usable under realistic operational conditions.

---

## 22. Intervention Failure

Failure to intervene successfully should trigger appropriate protective action.

Possible responses include:

- secondary intervention;
- autonomy reduction;
- function restriction;
- safe state;
- suspension.

---

## 23. Override Capability

Override should be:

- clearly defined;
- appropriately authorised;
- accessible;
- tested;
- protected against inappropriate use.

The existence of an override mechanism is not sufficient if it cannot be reliably exercised.

---

## 24. Loss of Control Response

A practical response sequence is:

**Detect → Assess → Reduce Autonomy → Restore Human Control → Restrict → Safe State → Suspend**

Immediate action may bypass intermediate stages where necessary.

---

## 25. Unexpected Autonomy Response

Where unexpected autonomy occurs:

1. establish system status where practicable;
2. identify the actual autonomy state;
3. reduce autonomy;
4. restore human control;
5. restrict affected functions;
6. enter safe state or suspend if required;
7. preserve evidence;
8. initiate incident assessment.

---

## 26. Communication Loss

Where communication loss prevents required human supervision:

- predefined degraded-operation rules should apply;
- autonomy should not increase merely because human contact is unavailable;
- the capability should transition to the authorised degraded state.

---

## 27. Sensor or Information Degradation

Loss or degradation of information may reduce human ability to assess AI outputs.

The organisation should consider:

- increased uncertainty;
- reduced autonomy;
- increased human verification;
- restriction;
- safe state.

---

## 28. Environmental Effects

Human control may be affected by:

- degraded visibility;
- electromagnetic conditions;
- communication limitations;
- operational stress;
- unfamiliar environments;
- adversarial conditions.

Human-control assurance should therefore be evaluated in representative environments.

---

## 29. Security Effects

A security compromise may affect:

- AI behaviour;
- system status;
- autonomy;
- intervention;
- human authority.

Security incidents that threaten human control should receive appropriate safety and operational escalation.

---

## 30. Multi-AI Control

Where multiple AI systems interact, human control should remain understandable across the combined system.

The organisation should assess:

- conflicting recommendations;
- conflicting actions;
- responsibility boundaries;
- cascading behaviour;
- shared dependencies;
- ability to intervene across components.

---

## 31. Human-Control Assurance

Continuing assurance should establish that:

- responsible personnel remain competent;
- interfaces remain usable;
- intervention works;
- override works;
- autonomy remains bounded;
- human workload remains acceptable;
- decision authority remains clear.

---

## 32. Testing

Human-control and autonomy behaviour should be tested through:

- normal scenarios;
- degraded scenarios;
- time-critical scenarios;
- disconnected scenarios;
- adversarial scenarios;
- unexpected behaviour;
- intervention failure.

---

## 33. Independent Challenge

Material human-control or autonomy concerns should receive independent challenge where proportionate to:

- consequence;
- autonomy;
- uncertainty;
- complexity;
- operational significance.

---

## 34. Assurance Impact

Loss of human control or unexpected autonomy may affect:

- assurance claims;
- evidence validity;
- risk;
- controls;
- operational boundaries;
- authorisation.

Material events may require revalidation or reauthorisation.

---

## 35. Incident Classification

Material loss of human control or unexpected autonomy should normally be considered for incident classification.

Severity should reflect:

- actual consequence;
- potential consequence;
- duration;
- autonomy;
- intervention success;
- uncertainty.

---

## 36. Restoration

Restoration after a control-loss or autonomy event should require confirmation that:

- the condition is understood sufficiently;
- human control is restored;
- autonomy is within authority;
- intervention is effective;
- required evidence is available;
- applicable authorisation remains valid.

---

## 37. Suspension

Suspension should be considered where:

- control cannot be reliably restored;
- autonomy remains outside authority;
- intervention fails;
- assurance is insufficient;
- critical causes remain unresolved.

---

## 38. Records

Material events should record:

- expected control;
- actual control;
- authorised autonomy;
- observed autonomy;
- trigger;
- human actions;
- system actions;
- intervention;
- outcome;
- evidence;
- assurance impact;
- resulting decision.

---

## 39. Learning

Lessons should inform:

- autonomy design;
- human authority;
- interfaces;
- training;
- TEVV;
- monitoring;
- fail-safe;
- operational authorisation;
- future assurance.

---

## 40. Governance Questions

The organisation should be able to answer:

1. What constitutes meaningful human control?
2. How is loss of control detected?
3. How is degraded control distinguished from complete loss?
4. How is current autonomy made visible?
5. How are unexpected autonomy transitions detected?
6. Who may reduce autonomy?
7. Who may override or suspend?
8. What happens when communication is lost?
9. How are workload and time pressure considered?
10. How is automation bias addressed?
11. How are human-control mechanisms tested?
12. How are multi-AI systems controlled?
13. When does loss of control become an incident?
14. When does it affect assurance?
15. When does it trigger revalidation or reauthorisation?
16. What conditions are required before restoration?

---

## 41. Core Rule

> **Human presence shall not be treated as equivalent to human control. Where a Defence AI capability has material operational consequence, authorised humans shall retain the practical authority and capability required to supervise, assess, intervene, override, reduce autonomy or suspend the capability as defined by its authorisation. Unexpected or unauthorised autonomy, or material loss of human control, shall trigger proportionate protective action and assurance reassessment.**

---

## 42. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Human Control → Autonomy → Detection → Protective Response → Safe State/Suspension → Investigation → Corrective Action → Assurance Reassessment → Revalidation/Reauthorisation → Learning**
