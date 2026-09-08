# 06 — Intervention, Override and Safe State

## 1. Purpose

This document defines governance requirements for intervening in Defence AI operations when system behaviour, risk, autonomy, environmental conditions, human control, security or other circumstances require the capability to be restricted, overridden, paused, placed in a safe state or suspended.

The objective is to ensure that protective intervention is available, effective, attributable and proportionate to operational consequence.

---

## 2. Core Principle

> **A Defence AI capability shall have effective and appropriately tested mechanisms through which authorised humans or predefined safety mechanisms can interrupt, restrict, reduce, override or safely terminate AI-supported activity when required. The existence of an intervention mechanism is not sufficient unless responsible personnel can understand when and how to use it.**

---

## 3. Intervention Model

D-AIGAAF uses the following graduated response:

**Monitor → Verify → Restrict → Reduce Autonomy → Human Control → Override/Pause → Safe State → Suspend**

The applicable response should reflect:

- consequence;
- urgency;
- uncertainty;
- autonomy;
- human control;
- environmental conditions;
- security;
- system integrity.

---

## 4. Intervention Authority

The organisation should define:

- who may intervene;
- who may reduce autonomy;
- who may pause or override;
- who may place the system in a safe state;
- who may suspend employment;
- who must be notified;
- who may restore operation.

Intervention authority should be explicit rather than implied.

---

## 5. Immediate Protective Action

Where continued operation could create unacceptable harm, authorised personnel should be able to take immediate protective action without waiting for a lengthy governance process.

Protective actions may include:

- stopping a function;
- reducing autonomy;
- restricting scope;
- assuming human control;
- entering safe state;
- suspending employment.

Emergency intervention should remain within applicable authority and be recorded where practicable.

---

## 6. Intervention Triggers

Intervention may be required following:

- unexpected AI behaviour;
- loss of human control;
- material uncertainty;
- boundary violation;
- environmental change;
- system degradation;
- security concern;
- data integrity failure;
- navigation uncertainty;
- communications loss;
- critical dependency failure;
- unsafe autonomous behaviour;
- excessive performance degradation;
- conflicting information;
- failure of a safety mechanism.

---

## 7. Intervention Thresholds

Thresholds should be defined for material conditions.

Possible levels include:

### I1 — Monitor

No immediate intervention; continue enhanced observation.

### I2 — Verify

Require additional information or human confirmation.

### I3 — Restrict

Reduce operational scope or disable affected functions.

### I4 — Reduce Autonomy

Move to a lower authorised autonomy state.

### I5 — Human Control

Transfer relevant control to an authorised human.

### I6 — Safe State

Place the capability in a predefined risk-reducing state.

### I7 — Suspend

Terminate authorised operational employment pending review.

---

## 8. Human Intervention

Human intervention should be:

- timely;
- understandable;
- operationally feasible;
- appropriately authorised;
- tested;
- recorded where required.

A nominal override that cannot realistically be exercised under operational conditions should not be treated as effective human control.

---

## 9. Intervention Availability

For consequential systems, intervention should be available under the conditions in which intervention may actually be required.

Consider:

- communications;
- workload;
- time available;
- interface accessibility;
- environmental conditions;
- system latency;
- personnel competence;
- degraded operation.

---

## 10. Intervention Latency

The organisation should consider the time between:

**Risk Detected → Intervention Initiated → Intervention Effective**

For time-sensitive functions, the intervention mechanism should be sufficiently responsive for the foreseeable consequence.

---

## 11. Intervention Failure

If an intervention mechanism fails or cannot be confirmed to have worked, the organisation should apply a predefined protective response.

Possible responses include:

- secondary intervention;
- autonomy reduction;
- system isolation;
- safe state;
- suspension.

Failure of an intervention mechanism should itself be treated as an assurance concern.

---

## 12. Override

An override allows an authorised human or control mechanism to supersede an AI-supported function or action within defined authority.

The organisation should specify:

- scope;
- authority;
- trigger;
- method;
- system response;
- safeguards;
- records;
- recovery.

---

## 13. Override versus Authorisation

An override does not create new operational authority.

It should only permit an authorised person or mechanism to act within the authority applicable to the situation.

An override should not be used to bypass mandatory legal, safety or governance requirements.

---

## 14. Override Priority

Where multiple controls or instructions conflict, the applicable precedence model should determine which control prevails.

In general:

**Legal / Binding Requirements → Authorisation Boundaries → Mandatory Safety Controls → Defined Human Authority → Technical Controls → AI Outputs**

The detailed precedence applicable to the organisation should be established through its governance framework.

---

## 15. Pause

A pause temporarily stops or limits relevant system activity while preserving the ability to assess and determine the next action.

Pause conditions should define:

- who may initiate it;
- what functions stop;
- what functions remain active;
- whether autonomous activity continues;
- conditions for resumption.

---

## 16. Safe State

A safe state is a predefined system condition intended to reduce risk following a significant operational concern.

Safe-state design should be specific to the capability and mission.

Possible characteristics include:

- stopping consequential actions;
- reducing autonomy;
- maintaining controlled observation;
- preserving system integrity;
- preventing further boundary expansion;
- enabling human assessment.

---

## 17. Safe-State Entry

Safe-state entry may be triggered by:

- loss of human control;
- critical system failure;
- unsafe autonomy;
- boundary uncertainty;
- security compromise;
- critical dependency failure;
- environmental conditions;
- failed intervention;
- other predefined thresholds.

---

## 18. Safe-State Behaviour

The organisation should define what the capability does after entering the safe state.

This may include:

- cease affected activity;
- maintain limited observation;
- reduce autonomy;
- preserve evidence;
- await human instruction;
- transition to controlled shutdown.

Safe-state behaviour should not be left to an undefined system response.

---

## 19. Safe-State Exit

Exit from safe state should require defined conditions.

These may include verification of:

- system integrity;
- configuration;
- environment;
- human authority;
- autonomy;
- security;
- dependencies;
- mission status;
- applicable authorisation;
- readiness.

---

## 20. Suspension

Where safe-state operation cannot adequately control risk, employment should be suspended.

Suspension should:

- prevent unintended continuation;
- identify responsible authority;
- preserve evidence;
- initiate investigation;
- assess assurance implications;
- establish restoration requirements.

---

## 21. Autonomous Safety Mechanisms

Where automated protective mechanisms exist, their authority and behaviour should be explicitly governed.

Automated safety mechanisms may:

- reduce autonomy;
- stop a function;
- enter safe state;
- restrict operation.

They should not acquire unrelated operational authority merely because they are designed to protect the system.

---

## 22. Fail-Safe versus Fail-Operational

The organisation should determine whether the appropriate response to failure is:

- continued operation with reduced functionality;
- reduced autonomy;
- human control;
- safe state;
- suspension.

The decision should be based on consequence, mission requirements and assurance evidence.

---

## 23. Human Control Recovery

Where human control is lost, the capability should have predefined mechanisms for restoring control where practicable.

Recovery should establish:

- responsible authority;
- current system state;
- current autonomy;
- available information;
- intervention mechanism;
- operational boundaries.

---

## 24. Loss of Control

Loss of meaningful human control should be treated as a material operational event.

Depending on consequence, the response may include:

**Reduce Autonomy → Human Control → Safe State → Suspend**

The system should not be permitted to continue at an unchanged autonomy level merely because technical functions remain available.

---

## 25. Intervention under Communications Loss

Where communications are unavailable, intervention arrangements should rely on predefined local mechanisms where appropriate.

The organisation should determine:

- what local intervention remains possible;
- what autonomy is permitted;
- what safe-state behaviour applies;
- how decisions are recorded;
- how authority is restored after reconnection.

---

## 26. Intervention under Adversarial Conditions

Adversarial activity may attempt to:

- prevent intervention;
- manipulate interfaces;
- create false intervention signals;
- disable safeguards;
- cause unsafe transitions.

Intervention mechanisms should therefore be protected and tested against relevant threats.

---

## 27. Intervention under Environmental Change

Where environmental conditions materially change, intervention may be required before normal operation can continue.

Consider:

- visibility;
- terrain;
- weather;
- electromagnetic conditions;
- navigation;
- communications;
- information availability.

---

## 28. Intervention and Uncertainty

Increasing uncertainty may require increased human involvement.

Where the system can no longer provide sufficiently reliable information for its authorised function, the organisation should consider:

**Verify → Restrict → Reduce Autonomy → Human Control → Safe State**

---

## 29. Intervention and Boundary Violation

A suspected or confirmed boundary violation should trigger proportionate action.

Possible responses include:

- restrict affected function;
- reduce autonomy;
- assume human control;
- safe state;
- suspend.

Boundary events should be recorded and investigated according to their materiality.

---

## 30. Intervention and Security

Security events affecting:

- model integrity;
- software;
- data;
- interfaces;
- identity;
- configuration;
- dependencies;

may require immediate intervention.

Security response and operational response should remain coordinated.

---

## 31. Intervention during Multi-AI Employment

Where multiple AI systems interact, intervention should consider:

- dependency chains;
- cascading effects;
- shared interfaces;
- shared data;
- combined autonomy;
- system-of-systems behaviour.

Stopping one component may not be sufficient to restore control.

---

## 32. Intervention Testing

Intervention mechanisms should be tested under representative conditions, including where appropriate:

- normal operations;
- degraded conditions;
- disconnected conditions;
- high workload;
- communications loss;
- security events;
- unexpected AI behaviour;
- autonomy transitions.

Testing should establish both technical effectiveness and human usability.

---

## 33. Human Factors

Intervention design should account for:

- workload;
- cognitive load;
- alert fatigue;
- interface complexity;
- time pressure;
- automation bias;
- training;
- authority ambiguity.

Personnel should know the consequences of available intervention options.

---

## 34. Intervention Training

Relevant personnel should be trained to:

- recognise intervention triggers;
- assess AI behaviour;
- reduce autonomy;
- assume human control;
- use override mechanisms;
- initiate safe-state procedures;
- suspend employment;
- document material intervention.

Training should be maintained at a level proportionate to operational consequence.

---

## 35. Intervention Records

Material intervention events should record where practicable:

- time;
- system;
- configuration;
- operational state;
- trigger;
- detected condition;
- intervention authority;
- intervention taken;
- autonomy before and after;
- system response;
- outcome;
- subsequent decision.

---

## 36. Intervention Evidence

Evidence should demonstrate, where applicable:

- intervention mechanisms exist;
- authority is defined;
- mechanisms function;
- intervention is timely enough;
- personnel can use them;
- safe-state behaviour is understood;
- recovery is controlled.

Evidence should feed TEVV and continuous assurance.

---

## 37. Post-Intervention Assessment

Following material intervention, the organisation should determine whether:

- normal employment can continue;
- restrictions are required;
- additional monitoring is required;
- an incident should be declared;
- revalidation is required;
- reauthorisation is required;
- suspension should continue.

---

## 38. Restoration after Intervention

Restoration should not be automatic.

Before resuming normal employment, verify the relevant:

- system condition;
- configuration;
- environment;
- human authority;
- autonomy;
- security;
- dependencies;
- authorisation;
- readiness.

---

## 39. Governance Questions

The organisation should be able to answer:

1. Who can intervene?
2. What triggers intervention?
3. How quickly can intervention take effect?
4. Can autonomy be reduced immediately?
5. Can an authorised human assume control?
6. What happens if override fails?
7. What is the defined safe state?
8. Who can place the system in safe state?
9. What happens during communication loss?
10. What happens during a security compromise?
11. How are intervention mechanisms tested?
12. How are material interventions recorded?
13. What must be verified before restoration?
14. When does intervention require suspension, revalidation or reauthorisation?

---

## 40. Golden Thread

Intervention governance remains connected to:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Autonomy → Employment → Monitoring → Intervention → Safe State/Suspension → Recovery → Learning → Revalidation/Reauthorisation**

---

## 41. Core Rule

> **Defence AI employment shall include effective, authorised and appropriately tested mechanisms for intervention, autonomy reduction, human control, override, safe-state transition and suspension. Material loss of human control, unexpected behaviour, boundary violation, security compromise, critical dependency failure or other unacceptable risk shall trigger proportionate protective action. Intervention and safe-state mechanisms shall not create new operational authority, and their effectiveness shall be demonstrated under conditions in which they may actually be required. Restoration shall require controlled verification of system integrity, configuration, environment, autonomy, human authority, security, dependencies, authorisation and readiness rather than relying solely on technical recovery.**
