# 21 Operational Performance and Effectiveness Monitoring

## 1. Purpose

Operational performance and effectiveness monitoring establishes whether a Defence AI capability continues to perform its authorised functions adequately during operational employment.

Monitoring shall consider not only technical performance, but also mission effectiveness, human-AI interaction, autonomy, environmental conditions, security, data quality, dependencies and emerging risk.

The objective is to determine whether the capability remains within the assurance and operational-authorisation basis established by D-AIGAAF.

---

## 2. Core Principle

Operational performance shall be assessed against the **authorised operational purpose**, not merely against whether the AI system remains technically available.

A capability may remain technically functional while becoming operationally unsuitable because of:

- changing mission conditions;
- environmental variation;
- data drift;
- degraded sensors;
- changing adversarial behaviour;
- human factors;
- unexpected autonomy behaviour;
- dependency failure;
- security threats; or
- declining mission effectiveness.

Therefore:

**Technical Availability ≠ Operational Effectiveness ≠ Continued Authorisation**

---

## 3. Monitoring Object

Monitoring should remain aligned with:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Performance indicators should therefore be interpreted in operational context.

The same technical performance level may be acceptable for one mission and unacceptable for another.

---

## 4. Monitoring Dimensions

D-AIGAAF recommends monitoring across at least the following dimensions:

1. Technical performance
2. AI behaviour
3. Reliability and robustness
4. Mission effectiveness
5. Human-AI interaction
6. Autonomy and control
7. Operational environment
8. Data and information
9. Security and integrity
10. Dependencies and continuity
11. Safety and incident indicators
12. Assurance and evidence currency

---

## 5. Technical Performance Monitoring

Relevant measures may include:

- accuracy;
- precision and recall where applicable;
- false-positive and false-negative rates;
- latency;
- availability;
- processing performance;
- system error rates;
- resource utilisation;
- failure frequency; and
- recovery performance.

Measures should be selected according to the intended function rather than applied generically.

Technical thresholds should be defined where meaningful and should distinguish between:

- normal variation;
- warning conditions;
- degraded performance; and
- unacceptable performance.

---

## 6. AI Behaviour Monitoring

Operational monitoring should identify material changes in AI behaviour.

Indicators may include:

- unexpected outputs;
- anomalous recommendations;
- unexplained confidence changes;
- unusual decision patterns;
- changes in error distribution;
- unexpected refusals or actions;
- inconsistent behaviour under similar conditions;
- unexpected autonomy transitions; and
- behaviour outside demonstrated boundaries.

Where behaviour changes materially, the organisation should determine whether the change is caused by:

- environmental conditions;
- data changes;
- system configuration;
- model changes;
- interaction effects;
- dependency changes; or
- previously unidentified limitations.

---

## 7. Uncertainty Monitoring

AI systems should not only communicate uncertainty at the point of decision; operational governance should also monitor whether uncertainty behaves as expected.

Monitoring may consider:

- confidence calibration;
- frequency of low-confidence outputs;
- disagreement with trusted information;
- uncertainty under degraded conditions;
- changes in confidence distributions;
- unexplained high-confidence errors; and
- situations where the system cannot reliably determine an answer.

A persistent pattern of unjustified confidence should be treated as an assurance concern.

---

## 8. Reliability and Robustness Monitoring

Operational use should provide evidence about whether the capability remains reliable under real conditions.

Monitoring may include:

- repeated failures;
- intermittent failures;
- edge-case behaviour;
- environmental sensitivity;
- recovery behaviour;
- degraded-mode performance;
- resilience to unexpected inputs; and
- consistency across operating conditions.

Repeated minor failures may become material when considered collectively.

---

## 9. Mission Effectiveness Monitoring

Mission effectiveness should assess whether AI is actually contributing to the authorised operational objective.

Relevant measures may include:

- achievement of defined mission success criteria;
- decision-support usefulness;
- timeliness;
- reduction of avoidable workload;
- quality of situational awareness;
- operational efficiency;
- error reduction;
- successful completion of authorised functions; and
- unintended operational consequences.

Mission effectiveness should not be reduced to model accuracy alone.

---

## 10. Human-AI Interaction Monitoring

Operational monitoring should assess whether AI is affecting human decision-making as intended.

Indicators may include:

- automation bias;
- excessive reliance on AI;
- inappropriate rejection of AI;
- alert fatigue;
- workload;
- loss of situational awareness;
- misunderstanding of AI outputs;
- failure to recognise uncertainty;
- inability to intervene;
- delayed human response; and
- inappropriate delegation of decision authority to the system.

A technically successful AI capability can become operationally unsafe if human interaction degrades.

---

## 11. Autonomy and Control Monitoring

Monitoring should establish whether the capability remains within its authorised autonomy boundary.

Indicators may include:

- unauthorised actions;
- unexpected autonomy transitions;
- failure to obtain required human confirmation;
- loss of supervision;
- intervention failures;
- unexpected persistence of actions;
- deviation from configured autonomy; and
- inability to return to the authorised state.

Any material divergence between authorised and observed autonomy should trigger immediate assessment.

---

## 12. Environmental Monitoring

Operational performance should be interpreted against environmental conditions.

Relevant indicators may include:

- terrain;
- weather;
- illumination;
- sensor conditions;
- communications;
- information availability;
- electromagnetic conditions;
- navigation;
- computing and power;
- human operating conditions; and
- adversarial activity.

Where performance degradation correlates with an environmental condition, the organisation should determine whether that condition remains within the authorised operating envelope.

---

## 13. Data and Information Monitoring

Monitoring should consider whether operational data remains suitable.

Indicators may include:

- data quality;
- provenance;
- completeness;
- timeliness;
- distribution changes;
- sensor degradation;
- source inconsistency;
- missing data;
- anomalous inputs; and
- evidence of manipulation or poisoning.

Material data changes should feed into the Data & Information governance processes.

---

## 14. Security Monitoring

Operational monitoring should identify security conditions capable of affecting AI behaviour or operational authority.

Relevant indicators may include:

- unauthorised access;
- integrity failures;
- suspicious inputs;
- malicious manipulation;
- abnormal system behaviour;
- compromised dependencies;
- security-control failures;
- unusual configuration changes; and
- emerging vulnerabilities.

Security findings that materially affect trust or operational risk should be escalated through the AI Security and authorisation governance processes.

---

## 15. Dependency Monitoring

Critical dependencies should be monitored for:

- availability;
- integrity;
- performance;
- capacity;
- continuity;
- failure;
- degradation; and
- unexpected changes.

Dependency degradation should be assessed for its effect on:

**Mission → Risk → Performance → Human Control → Autonomy → Authorisation**

A capability that depends on a failed or unreliable service may no longer be operationally suitable even if its core model remains functional.

---

## 16. Monitoring Thresholds

Where practicable, each critical indicator should have defined thresholds.

A working classification may be:

| Level | Meaning |
|---|---|
| **Normal** | Performance and conditions remain within expected limits. |
| **Watch** | Variation or emerging concern requires increased observation. |
| **Degraded** | Performance or conditions have materially deteriorated but authorised restricted operation may remain possible. |
| **Critical** | Conditions may invalidate operational employment or authorisation. |

Thresholds should be mission- and risk-specific.

---

## 17. Monitoring Response

Monitoring should be linked to predefined responses.

Possible responses include:

**Observe → Increase Monitoring → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

The appropriate response should depend on:

- consequence;
- urgency;
- confidence in the observed condition;
- reversibility;
- ability to intervene;
- mission context; and
- authorised procedures.

Monitoring without a defined response mechanism provides limited governance value.

---

## 18. Performance Degradation

Performance degradation should be assessed for:

- magnitude;
- duration;
- frequency;
- operational consequence;
- affected functions;
- affected environments;
- affected users;
- cause;
- recoverability; and
- impact on assurance evidence.

Repeated or unexplained degradation should trigger deeper investigation.

Where degradation invalidates a mandatory authorisation condition, operational use should be restricted or suspended as appropriate.

---

## 19. Emerging Behaviour

Operational experience may reveal behaviour not identified during development or TEVV.

Examples include:

- unexpected interactions between system components;
- new failure modes;
- unexpected environmental sensitivity;
- unanticipated user behaviour;
- novel adversarial effects;
- unexpected autonomy transitions; or
- previously unidentified data limitations.

Emerging behaviour should be captured as assurance evidence and assessed for wider implications.

---

## 20. Operational Performance Review

Periodic performance reviews should consider:

- monitoring results;
- incidents;
- near misses;
- user feedback;
- mission outcomes;
- environmental observations;
- autonomy events;
- security findings;
- data-quality trends;
- dependency performance;
- assurance findings; and
- changes to the operational context.

Review frequency should reflect:

- consequence;
- autonomy;
- mission criticality;
- operational tempo;
- rate of change; and
- observed risk.

---

## 21. Trigger-Based Review

A performance review should be initiated when, for example:

- a critical threshold is exceeded;
- repeated degradation occurs;
- unexpected AI behaviour is observed;
- autonomy behaviour changes;
- meaningful human control is impaired;
- a material incident occurs;
- security conditions change;
- data drift becomes material;
- a critical dependency changes;
- the environment moves toward or beyond the operating boundary; or
- new evidence materially changes the risk assessment.

Trigger-based review should operate alongside scheduled review.

---

## 22. Performance Evidence

Operational monitoring should produce evidence that can support:

- assurance;
- risk assessment;
- TEVV;
- operational environment assessment;
- human-control assessment;
- security assurance;
- data governance;
- authorisation review;
- change impact assessment;
- revalidation; and
- reauthorisation.

Evidence should be sufficiently traceable to establish:

**What happened → Under what conditions → With what configuration → With what human authority → With what consequence**

---

## 23. Monitoring and Authorisation

Operational performance monitoring should inform whether an existing authorisation remains valid.

Possible governance outcomes include:

1. Continue unchanged.
2. Continue with increased monitoring.
3. Continue with additional restrictions.
4. Reduce autonomy.
5. Require additional assurance.
6. Trigger revalidation.
7. Trigger reauthorisation.
8. Restrict employment.
9. Suspend employment.
10. Revoke operational authority where justified.

Operational performance monitoring should therefore be connected directly to authorisation governance.

---

## 24. Monitoring During Degraded Operations

When operating under authorised degraded or disconnected conditions, monitoring should focus on:

- available data;
- communication status;
- sensor reliability;
- navigation confidence;
- local processing;
- autonomy restrictions;
- human-control availability;
- fail-safe status; and
- recovery conditions.

The system should not silently continue at the same level of authority when the conditions supporting that authority have materially deteriorated.

---

## 25. Operational Lessons

Performance monitoring should contribute to the D-AIGAAF lessons-learned cycle:

**Observe → Record → Assess → Learn → Act → Verify → Update**

Lessons should be assessed for:

- local impact;
- capability-wide impact;
- mission-wide impact;
- environment-specific implications;
- training implications;
- TEVV implications;
- design implications; and
- authorisation implications.

---

## 26. Performance Record

A controlled Operational Performance Record should contain, as applicable:

- capability identifier;
- authorisation identifier;
- mission/use case;
- configuration;
- autonomy;
- relevant environment;
- performance indicators;
- thresholds;
- observations;
- anomalies;
- incidents;
- human factors;
- security observations;
- data-quality observations;
- dependency status;
- interventions;
- decisions;
- outcomes;
- evidence references; and
- resulting governance actions.

Records should be proportionate to consequence and operational significance.

---

## 27. Relationship to Continuous Assurance

Operational performance monitoring is a central component of continuous assurance.

The relationship is:

**Operational Employment → Monitoring → Evidence → Assessment → Risk → Assurance → Authorisation Decision**

This ensures that operational experience can modify governance when the original assurance basis no longer reflects observed reality.

---

## 28. Golden Thread

Performance monitoring remains traceable through the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Readiness → Deployment → Employment → Monitoring → Change/Incident → Reauthorisation**

The purpose is to ensure that operational performance evidence can be traced back to the mission and forward into governance decisions.

---

## 29. Governance Questions

Responsible authorities should periodically ask:

1. Is the capability still achieving its authorised mission purpose?
2. Is technical performance within expected limits?
3. Has AI behaviour changed materially?
4. Is uncertainty being communicated appropriately?
5. Are false or misleading outputs increasing?
6. Is human reliance on AI changing?
7. Is meaningful human control being maintained?
8. Is authorised autonomy being maintained?
9. Are environmental conditions changing?
10. Is data quality or distribution changing?
11. Are security conditions changing?
12. Are critical dependencies reliable?
13. Are incidents or near misses increasing?
14. Are there new failure modes?
15. Has any monitoring threshold been exceeded?
16. Does observed performance remain consistent with assurance evidence?
17. Does the authorisation basis remain valid?
18. Is additional assurance required?
19. Is revalidation or reauthorisation required?
20. Should employment be restricted or suspended?

---

## 30. Core Rule

> **Operational performance monitoring shall determine not merely whether a Defence AI capability continues to function, but whether it continues to perform its authorised purpose with acceptable risk, human control, security, reliability and effectiveness under the conditions in which it is actually employed. Material deterioration or unexpected behaviour shall trigger proportionate governance action, including restriction, additional assurance, revalidation, reauthorisation or suspension where required.**
