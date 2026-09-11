# 10-Operational Environment Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 10 — Operational Environment**.

These templates establish practical mechanisms for determining whether an AI capability remains safe, effective, secure, controllable and authorised within the environment in which it is actually used.

The central principle is:

> **An AI capability is not governed independently of its operating environment. The mission, environment, AI behaviour, human control and risk are interdependent.**

The operational environment may include:

- physical terrain;
- weather;
- electromagnetic conditions;
- communications;
- networks;
- sensors;
- data availability;
- adversarial activity;
- human factors;
- infrastructure;
- mission tempo;
- civilian presence;
- legal constraints;
- environmental uncertainty.

---

# 2. Template Set

The recommended Operational Environment template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-10-001 | Operational Environment Governance Record |
| D-AIGAAF-T-10-002 | Operational Environment Characterisation Record |
| D-AIGAAF-T-10-003 | Environment Variability & Boundary Assessment |
| D-AIGAAF-T-10-004 | Degraded & Disconnected Operations Assessment |
| D-AIGAAF-T-10-005 | Adversarial Environment Assessment |
| D-AIGAAF-T-10-006 | Human Operational Environment Assessment |
| D-AIGAAF-T-10-007 | Information & Electromagnetic Environment Assessment |
| D-AIGAAF-T-10-008 | Operational Environment Risk Assessment |
| D-AIGAAF-T-10-009 | Environment Readiness & Entry Criteria Record |
| D-AIGAAF-T-10-010 | Environment Monitoring Record |
| D-AIGAAF-T-10-011 | Environment Change & Impact Assessment |
| D-AIGAAF-T-10-012 | Environment Incident Record |
| D-AIGAAF-T-10-013 | Environment Lessons Learned Record |
| D-AIGAAF-T-10-014 | Operational Environment Governance Review |
| D-AIGAAF-T-10-015 | Operational Environment Evidence & Records Index |
| D-AIGAAF-T-10-016 | Operational Environment Exit Criteria Record |

---

# 3. Template 10-001 — Operational Environment Governance Record

## Purpose

Defines governance responsibilities for characterising, monitoring and controlling environmental conditions relevant to AI use.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Environment owner
- Operational authority
- Safety authority
- Security authority
- Technical authority
- Risk owner
- Assurance authority
- Monitoring authority
- Escalation authority
- Review authority
- Review date

## Governance Questions

- Who defines the authorised environment?
- Who determines whether conditions remain within bounds?
- Who can restrict AI use?
- Who can suspend employment?
- Who monitors environmental change?
- Who determines whether a changed environment requires revalidation or reauthorisation?

---

# 4. Template 10-002 — Operational Environment Characterisation Record

## Purpose

Defines the environment in which the AI capability is intended to operate.

## Environment Domains

### Physical

- terrain;
- weather;
- visibility;
- temperature;
- dust;
- vibration;
- lighting;
- infrastructure.

### Information

- data availability;
- data quality;
- data freshness;
- sensor coverage;
- information reliability.

### Technical

- compute;
- networks;
- communications;
- power;
- sensors;
- positioning.

### Human

- staffing;
- competence;
- workload;
- mission tempo;
- command structure.

### Threat

- adversarial activity;
- cyber threats;
- deception;
- spoofing;
- jamming;
- physical attack.

## Required Fields

- Environment domain
- Condition
- Expected range
- Criticality
- AI dependency
- Risk
- Evidence
- Monitoring method
- Owner

---

# 5. Template 10-003 — Environment Variability & Boundary Assessment

## Purpose

Identifies environmental variation that may affect AI behaviour.

## Assessment Areas

- normal operating range;
- boundary conditions;
- extreme conditions;
- unexpected conditions;
- seasonal variation;
- geographic variation;
- mission variation;
- threat variation.

## Required Fields

- Variable
- Expected range
- Tested range
- Authorised range
- Boundary
- Failure consequence
- Detection
- Mitigation
- Escalation
- Evidence

The authorised operating envelope should be explicit wherever environmental conditions materially affect risk.

---

# 6. Template 10-004 — Degraded & Disconnected Operations Assessment

## Purpose

Assesses AI behaviour when normal connectivity, infrastructure or information availability is degraded.

## Scenarios

Consider:

- loss of communications;
- loss of network connectivity;
- cloud unavailable;
- GPS/GNSS degradation;
- sensor loss;
- stale data;
- partial data;
- power degradation;
- compute degradation;
- external service failure.

## Required Fields

- Degradation
- Trigger
- AI dependency
- Expected behaviour
- Actual behaviour
- Human role
- Autonomy transition
- Safe state
- Recovery
- Consequence
- Evidence

The assessment should establish whether the AI remains within authorised boundaries after loss of assumed dependencies.

---

# 7. Template 10-005 — Adversarial Environment Assessment

## Purpose

Assesses environmental conditions in which an intelligent adversary may deliberately attempt to influence AI behaviour.

## Threats

Consider:

- deception;
- spoofing;
- jamming;
- camouflage;
- adversarial examples;
- manipulated information;
- sensor attacks;
- cyber attacks;
- false data;
- coordinated multi-domain attacks.

## Required Fields

- Threat
- Environment
- Attack objective
- AI dependency
- Expected response
- Observed response
- Human awareness
- Control
- Residual risk
- Evidence

The environment should be treated as potentially contested rather than inherently benign.

---

# 8. Template 10-006 — Human Operational Environment Assessment

## Purpose

Assesses human conditions that affect the ability to govern and operate AI.

## Factors

Consider:

- staffing;
- workload;
- fatigue;
- training;
- command structure;
- decision tempo;
- communications;
- stress;
- competing tasks;
- availability of specialists;
- shift arrangements;
- emergency conditions.

## Required Fields

- Human factor
- Expected condition
- Actual condition
- AI impact
- Human-control impact
- Risk
- Mitigation
- Evidence

Human capability is part of the operational environment.

---

# 9. Template 10-007 — Information & Electromagnetic Environment Assessment

## Purpose

Assesses the information and electromagnetic conditions relevant to AI performance and security.

## Assessment Areas

### Information Environment

- data availability;
- data integrity;
- data latency;
- information overload;
- misinformation;
- conflicting information.

### Electromagnetic Environment

- spectrum availability;
- interference;
- jamming;
- spoofing;
- signal degradation;
- electromagnetic congestion.

## Required Fields

- Condition
- AI dependency
- Expected impact
- Detection
- Mitigation
- Human awareness
- Autonomy impact
- Evidence

---

# 10. Template 10-008 — Operational Environment Risk Assessment

## Purpose

Determines risks arising from the interaction between AI capability and its operational environment.

## Risk Factors

Consider:

- consequence;
- environmental uncertainty;
- variability;
- adversarial exposure;
- reversibility;
- AI dependency;
- human control;
- autonomy;
- communications;
- sensor reliability.

## Required Fields

- Environment
- Condition
- Hazard
- AI behaviour
- Consequence
- Likelihood
- Existing control
- Residual risk
- Treatment
- Owner

---

# 11. Template 10-009 — Environment Readiness & Entry Criteria Record

## Purpose

Defines conditions that must exist before AI employment begins.

## Entry Criteria

May include:

- required communications available;
- sensors operational;
- data quality acceptable;
- environmental conditions within authorised bounds;
- personnel available;
- intervention capability available;
- security controls active;
- required infrastructure operational;
- approved configuration loaded.

## Required Fields

- Criterion
- Threshold
- Measurement
- Status
- Evidence
- Authority
- Exception
- Decision

Failure of a critical entry criterion should prevent employment unless an explicit, authorised exception exists.

---

# 12. Template 10-010 — Environment Monitoring Record

## Purpose

Records monitoring of operational conditions during AI employment.

## Monitoring Areas

- environment;
- data;
- communications;
- sensors;
- network;
- security;
- human workload;
- AI performance;
- autonomy;
- dependencies.

## Required Fields

- Time
- Condition
- Measurement
- Threshold
- Status
- Trend
- AI impact
- Human notification
- Action
- Record

Monitoring thresholds should be linked to operational consequences where practical.

---

# 13. Template 10-011 — Environment Change & Impact Assessment

## Purpose

Determines whether environmental changes affect AI risk, performance or authorisation.

## Change Examples

- new terrain;
- weather change;
- new adversary;
- communications degradation;
- sensor replacement;
- new electromagnetic conditions;
- changed mission tempo;
- changed civilian environment;
- infrastructure degradation;
- changed data source.

## Required Fields

- Change
- Previous condition
- New condition
- AI dependency
- Risk impact
- Performance impact
- Human-control impact
- Autonomy impact
- TEVV impact
- Revalidation requirement
- Reauthorisation requirement

A change in environment can create a material change even when the AI software itself is unchanged.

---

# 14. Template 10-012 — Environment Incident Record

## Purpose

Records incidents in which environmental conditions contributed to unexpected AI behaviour, degraded performance or loss of control.

## Required Fields

- Incident ID
- Mission
- Environment
- Condition
- AI behaviour
- Human response
- Consequence
- Immediate protection
- Evidence
- Root cause
- Corrective action
- Revalidation
- Reauthorisation
- Lessons learned

---

# 15. Template 10-013 — Environment Lessons Learned Record

## Purpose

Captures lessons from operational experience involving environmental conditions.

## Required Fields

- Lesson ID
- Mission
- Environment
- Observation
- What happened
- Expected behaviour
- Actual behaviour
- Cause
- Consequence
- Recommendation
- Required change
- Owner
- Validation

Lessons should feed back into:

- requirements;
- TEVV;
- risk;
- operating boundaries;
- training;
- authorisation;
- monitoring.

---

# 16. Template 10-014 — Operational Environment Governance Review

## Purpose

Provides periodic governance review of the authorised operational environment.

## Review Areas

- environment definition;
- boundaries;
- variability;
- degraded operations;
- adversarial conditions;
- information environment;
- electromagnetic environment;
- human factors;
- incidents;
- lessons;
- changes;
- monitoring;
- readiness criteria.

## Review Questions

1. Has the operational environment changed?
2. Are authorised environmental boundaries still appropriate?
3. Have new threats emerged?
4. Are degraded-operation assumptions still valid?
5. Are communications assumptions valid?
6. Are sensor assumptions valid?
7. Has human workload changed?
8. Has mission tempo changed?
9. Has AI performance changed?
10. Does existing TEVV remain representative?
11. Does assurance remain valid?
12. Does authorisation remain valid?

---

# 17. Template 10-015 — Operational Environment Evidence & Records Index

## Purpose

Provides an authoritative index of evidence relating to the operational environment.

## Required Fields

- Evidence ID
- Environment
- Condition
- Source
- Date
- Capability configuration
- Mission
- Test/trial
- Monitoring record
- Incident
- Finding
- Integrity
- Owner
- Retention
- Authorisation relevance

Evidence should permit reconstruction of the conditions under which AI behaviour was observed or evaluated.

---

# 18. Template 10-016 — Operational Environment Exit Criteria Record

## Purpose

Defines conditions requiring cessation, restriction or transition of AI employment.

## Exit Triggers

Consider:

- environmental boundary exceeded;
- communications lost;
- critical sensor unavailable;
- security compromise;
- AI performance below threshold;
- human control unavailable;
- adversarial conditions exceed assumptions;
- mission conditions changed;
- critical dependency unavailable;
- autonomy control failure.

## Required Fields

- Trigger
- Threshold
- Detection
- Required response
- Human authority
- Safe state
- Recovery condition
- Re-entry requirement
- Record

Exit criteria should be defined before operational employment, not improvised during a failure.

---

# 19. Operational Environment Model

D-AIGAAF models the environment as a multidimensional system:

**Physical Environment**
+
**Information Environment**
+
**Technical Environment**
+
**Electromagnetic Environment**
+
**Human Environment**
+
**Threat Environment**
+
**Mission Environment**

These dimensions interact.

For example:

**Communications degradation**
→ **Reduced information**
→ **Reduced situational awareness**
→ **Changed human control**
→ **Changed autonomy risk**
→ **Changed operational risk**

Environmental assessment should therefore avoid isolated domain analysis where dependencies are material.

---

# 20. Operational Envelope

Each consequential AI capability should have an explicit operational envelope where practical.

The envelope may define:

- geographic limits;
- mission limits;
- environmental limits;
- threat limits;
- data limits;
- communication limits;
- sensor limits;
- autonomy limits;
- human-control requirements;
- temporal limits.

The governing principle is:

> **Operating outside the authorised envelope is a governance event, not merely a technical condition.**

---

# 21. Environment and AI Performance

AI performance should be understood as conditional.

A useful representation is:

**AI Performance = f(Model, Data, System, Human, Mission, Environment)**

Therefore:

**Stable Model**
does not necessarily mean
**Stable Operational Risk**.

Environmental change can alter:

- accuracy;
- confidence;
- latency;
- reliability;
- human interpretation;
- autonomy;
- mission effectiveness.

---

# 22. Environment and Risk

Operational risk should consider interaction effects.

For example:

**High Environmental Uncertainty**
+
**High Autonomy**
+
**Limited Human Intervention**
+
**Adversarial Conditions**
+
**High Consequence**

may create a materially different risk profile from the same AI operating in a controlled environment.

Risk assessment should therefore be mission- and environment-specific.

---

# 23. Environment and Human Authority

Human authority depends partly on environmental conditions.

A human may have formal authority but lose effective control because of:

- communications failure;
- excessive workload;
- incomplete information;
- delayed AI outputs;
- sensor degradation;
- rapidly changing circumstances.

Meaningful human control should therefore be assessed under representative environmental conditions.

---

# 24. Environment and AI Security

Operational environment can create AI-specific security vulnerabilities.

Examples include:

- manipulated sensors;
- spoofed positioning;
- adversarial observations;
- false information;
- communications disruption;
- electromagnetic attack;
- compromised external data.

Security assurance should therefore include relevant environmental attack conditions.

---

# 25. Environment and Autonomy

Environmental changes may require changes in autonomy.

For example:

**Normal Conditions**
→ A4 supervised autonomy

**Degraded Conditions**
→ A3 human-authorised action

**Severe Degradation**
→ A2 recommendation only

**Critical Loss of Control**
→ Safe State

The actual transition rules must be explicitly defined, tested and authorised.

---

# 26. Environment and Operational Authorisation

Operational authorisation should identify the environment within which it applies.

The authorisation object remains:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

An authorisation for one environment should not automatically be interpreted as authorisation for another.

---

# 27. Environmental Change as a Reauthorisation Trigger

Environmental change may require:

- risk reassessment;
- additional TEVV;
- configuration review;
- human-control assessment;
- autonomy reassessment;
- revalidation;
- reauthorisation.

Examples include:

- moving from controlled training conditions to contested operations;
- changing geographical area;
- changing mission type;
- introduction of a new adversary;
- loss of critical communications;
- introduction of a materially different data environment.

---

# 28. TEVV Evidence for Operational Environment

Environment-related evidence should demonstrate, where relevant:

- performance;
- robustness;
- reliability;
- security;
- human control;
- autonomy;
- recovery;
- boundary adherence.

Testing should include representative and adverse conditions proportional to consequence.

---

# 29. Anti-Pattern — Laboratory Environment Equals Operational Environment

D-AIGAAF rejects:

**Laboratory Performance**
→ **Operational Readiness**

A controlled environment may suppress:

- environmental variability;
- adversarial behaviour;
- communication failures;
- sensor degradation;
- human workload;
- information uncertainty.

Operational evidence should therefore be proportionate to mission consequence.

---

# 30. Anti-Pattern — Environment as a Static Background

The environment is not merely a location in which the AI operates.

It can actively influence:

- inputs;
- model behaviour;
- human decisions;
- security;
- autonomy;
- mission effectiveness;
- risk.

Environmental conditions should therefore be governed as part of the AI system's operational context.

---

# 31. Final Operational Environment Principle

D-AIGAAF treats operational environment as a first-class governance variable.

The complete environment chain is:

**Environment**
→ **Conditions**
→ **AI Dependencies**
→ **Behaviour**
→ **Human Interpretation**
→ **Decision**
→ **Action**
→ **Consequence**
→ **Monitoring**
→ **Change**
→ **Revalidation**
→ **Reauthorisation**

The governing principle is:

> **A consequential AI capability should be considered operationally governed only when the conditions under which it is authorised are explicitly understood, bounded, monitored and tested, including relevant degraded, disconnected, adversarial and human operating conditions.**
