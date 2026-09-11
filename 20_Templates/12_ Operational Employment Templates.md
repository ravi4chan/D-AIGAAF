# 12-Operational Employment Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 12 — Operational Employment**.

Operational employment is the point at which an authorised AI capability is actually used in a mission.

This module translates authorisation into controlled operational practice and ensures that:

- authorised boundaries are understood;
- personnel know their roles;
- AI outputs are interpreted appropriately;
- uncertainty is visible;
- human authority remains meaningful;
- autonomy remains within approved limits;
- operational conditions are monitored;
- deviations are detected;
- intervention remains possible;
- decisions and actions are traceable;
- incidents and lessons feed back into governance.

The central principle is:

> **Operational authorisation permits employment; it does not replace the operational controls required during employment.**

---

# 2. Template Set

The recommended Operational Employment template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-12-001 | Operational Employment Governance Record |
| D-AIGAAF-T-12-002 | AI Employment Plan |
| D-AIGAAF-T-12-003 | Pre-Employment Readiness Checklist |
| D-AIGAAF-T-12-004 | Mission Configuration & Activation Record |
| D-AIGAAF-T-12-005 | Operational Execution Record |
| D-AIGAAF-T-12-006 | Human Control & Decision Record |
| D-AIGAAF-T-12-007 | AI Output & Uncertainty Record |
| D-AIGAAF-T-12-008 | Situational Awareness Record |
| D-AIGAAF-T-12-009 | Autonomy & Boundary Monitoring Record |
| D-AIGAAF-T-12-010 | Degraded / Disconnected Employment Record |
| D-AIGAAF-T-12-011 | Intervention & Override Record |
| D-AIGAAF-T-12-012 | Operational Performance Monitoring Record |
| D-AIGAAF-T-12-013 | Decision / Action / Activity Log |
| D-AIGAAF-T-12-014 | Employment Deviation Record |
| D-AIGAAF-T-12-015 | Operational Incident & Immediate Response Record |
| D-AIGAAF-T-12-016 | Mission Closeout Record |
| D-AIGAAF-T-12-017 | Operational Lessons Learned Record |
| D-AIGAAF-T-12-018 | Operational Employment Review |

---

# 3. Template 12-001 — Operational Employment Governance Record

## Purpose

Defines governance responsibilities during operational employment.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Operational commander/authority
- AI operator
- Supervisor
- Decision authority
- Intervention authority
- Technical support
- Security support
- Incident authority
- Escalation authority
- Assurance authority
- Review date

## Governance Questions

- Who controls employment?
- Who may activate the AI?
- Who may change operating parameters?
- Who may approve a transition in autonomy?
- Who may intervene?
- Who may terminate employment?
- Who receives operational alerts?
- Who decides whether a deviation requires suspension?

---

# 4. Template 12-002 — AI Employment Plan

## Purpose

Defines how the authorised capability will be used during a specific mission.

## Required Sections

### Mission

- mission;
- objective;
- use case;
- intended effect.

### Capability

- system;
- configuration;
- model;
- functions;
- autonomy.

### Environment

- operating area;
- conditions;
- threats;
- communications;
- data.

### Human Authority

- commander;
- operator;
- supervisor;
- intervention authority.

### Controls

- operating boundaries;
- restrictions;
- monitoring;
- escalation;
- fail-safe.

## Required Fields

- Mission ID
- Capability ID
- Authorisation ID
- Configuration
- Operating conditions
- Human roles
- Autonomy
- Boundaries
- Monitoring
- Contingencies
- Approval

---

# 5. Template 12-003 — Pre-Employment Readiness Checklist

## Purpose

Confirms that required conditions exist before operational employment begins.

## Check

- authorisation valid;
- approved configuration loaded;
- personnel available;
- competence current;
- communications available where required;
- sensors operational;
- data acceptable;
- security controls active;
- intervention mechanism operational;
- safe-state mechanism operational;
- environment within authorised bounds;
- dependencies available;
- monitoring active.

## Required Fields

- Criterion
- Requirement
- Status
- Evidence
- Responsible person
- Exception
- Authority
- Decision

A critical readiness failure should prevent employment unless explicitly authorised otherwise.

---

# 6. Template 12-004 — Mission Configuration & Activation Record

## Purpose

Records the exact configuration activated for a mission.

## Required Fields

- Mission ID
- Capability
- Authorisation ID
- Model/version
- Software
- Firmware
- Hardware
- Data
- Configuration
- Instructions/prompts where applicable
- Connected tools
- External services
- Security state
- Activation time
- Activating authority

This record establishes the operational configuration baseline.

---

# 7. Template 12-005 — Operational Execution Record

## Purpose

Records significant events during AI-supported mission execution.

## Required Fields

- Time
- Mission phase
- AI function
- Operating condition
- AI state
- Human role
- AI output/action
- Human response
- Consequence
- Intervention
- Outcome
- Evidence

The level of logging should be proportionate to consequence and operational feasibility.

---

# 8. Template 12-006 — Human Control & Decision Record

## Purpose

Records consequential decisions involving AI.

## Required Fields

- Decision ID
- Time
- Decision-maker
- Authority
- Mission context
- Information available
- AI recommendation/output
- AI uncertainty
- Human assessment
- Alternatives
- Decision
- Reason
- Action
- Outcome

The record should distinguish:

**AI Output**
from

**Human Decision**
from

**Resulting Action**.

---

# 9. Template 12-007 — AI Output & Uncertainty Record

## Purpose

Records significant AI outputs and the uncertainty associated with them.

## Required Fields

- Output ID
- Time
- AI function
- Input context
- Output
- Confidence
- Uncertainty
- Known limitations
- Data freshness
- Human interpretation
- Decision relevance
- Action

The system should not create a false impression of certainty.

---

# 10. Template 12-008 — Situational Awareness Record

## Purpose

Records information necessary for human decision-makers to maintain situational awareness.

## Assessment Areas

- mission state;
- AI state;
- system health;
- relevant inputs;
- data freshness;
- environmental conditions;
- threat information;
- uncertainty;
- anomalies;
- human/machine activity.

## Required Fields

- Information requirement
- Source
- Time
- Quality
- Availability
- Interpretation
- Gap
- Consequence
- Action

---

# 11. Template 12-009 — Autonomy & Boundary Monitoring Record

## Purpose

Monitors whether the AI remains within its authorised autonomy and operational boundaries.

## Monitor

- autonomy level;
- permitted functions;
- geographic limits;
- environmental limits;
- mission limits;
- human-control requirements;
- prohibited actions;
- transition conditions.

## Required Fields

- Time
- Boundary
- Status
- AI state
- Observed behaviour
- Deviation
- Consequence
- Response
- Authority

AI should not be allowed to infer expanded authority from changing circumstances.

---

# 12. Template 12-010 — Degraded / Disconnected Employment Record

## Purpose

Records operational employment under degraded conditions.

## Conditions

Consider:

- communications loss;
- network loss;
- sensor degradation;
- stale data;
- external service loss;
- power degradation;
- compute limitation;
- electromagnetic disruption;
- personnel reduction.

## Required Fields

- Condition
- Trigger
- AI state
- Autonomy
- Human role
- Expected response
- Actual response
- Safe state
- Intervention
- Recovery
- Decision

---

# 13. Template 12-011 — Intervention & Override Record

## Purpose

Records human intervention in AI behaviour.

## Intervention Types

- pause;
- stop;
- reject;
- override;
- constrain;
- isolate;
- revert;
- transfer authority;
- safe-state transition.

## Required Fields

- Event ID
- Trigger
- AI state
- Human authority
- Intervention
- Response time
- Technical result
- Operational result
- Consequence
- Follow-up

Intervention events should be analysed for both technical and human factors.

---

# 14. Template 12-012 — Operational Performance Monitoring Record

## Purpose

Monitors AI performance during actual employment.

## Metrics

Depending on mission:

- accuracy;
- precision;
- recall;
- false positives;
- false negatives;
- latency;
- availability;
- reliability;
- mission effectiveness;
- human workload;
- intervention rate;
- autonomy transitions.

## Required Fields

- Metric
- Threshold
- Observation
- Trend
- Confidence
- Deviation
- Consequence
- Action
- Owner

Operational performance should be interpreted in mission context rather than by metrics alone.

---

# 15. Template 12-013 — Decision / Action / Activity Log

## Purpose

Maintains traceability of significant AI-supported decisions and actions.

## Required Fields

- Event ID
- Time
- Mission
- AI system
- Human authority
- AI contribution
- Decision
- Action
- Actor
- Result
- Evidence
- Record integrity

Where technically and operationally feasible, logs should be tamper-evident and time-synchronised.

---

# 16. Template 12-014 — Employment Deviation Record

## Purpose

Records deviations from authorised operating conditions.

## Examples

- unauthorised configuration;
- boundary exceedance;
- unexpected autonomy;
- unavailable human supervisor;
- environmental limit exceeded;
- prohibited function;
- unavailable dependency;
- operating outside approved mission conditions.

## Required Fields

- Deviation ID
- Requirement
- Actual condition
- Duration
- Detection
- Consequence
- Immediate action
- Authority
- Risk assessment
- Follow-up

A deviation may require incident handling, revalidation or suspension.

---

# 17. Template 12-015 — Operational Incident & Immediate Response Record

## Purpose

Records incidents occurring during operational employment and the immediate protective response.

## Required Fields

- Incident ID
- Time
- Mission
- Capability
- Condition
- AI behaviour
- Human response
- Consequence
- Immediate protection
- Fail-safe
- Containment
- Notification
- Evidence preservation
- Escalation

This template interfaces directly with Module 14 — Incident & Fail-Safe.

---

# 18. Template 12-016 — Mission Closeout Record

## Purpose

Provides controlled closure of an AI-supported mission.

## Required Fields

- Mission
- Capability
- Authorisation
- Final configuration
- Mission outcome
- AI performance
- Significant decisions
- Interventions
- Incidents
- Deviations
- Data/records captured
- Outstanding issues
- Follow-up
- Closeout authority

Mission closeout should verify that no unresolved event has been incorrectly treated as routine completion.

---

# 19. Template 12-017 — Operational Lessons Learned Record

## Purpose

Captures operational experience for improvement of the AI governance lifecycle.

## Required Fields

- Lesson ID
- Mission
- Environment
- AI capability
- Observation
- Expected behaviour
- Actual behaviour
- Cause
- Consequence
- Lesson
- Recommendation
- Required governance change
- Owner
- Validation

Lessons may feed into:

- requirements;
- risk;
- TEVV;
- human training;
- operating boundaries;
- autonomy;
- authorisation;
- security;
- acquisition;
- architecture.

---

# 20. Template 12-018 — Operational Employment Review

## Purpose

Provides periodic or mission-specific review of AI employment.

## Review Areas

- mission effectiveness;
- authorised use;
- configuration;
- performance;
- uncertainty;
- human control;
- autonomy;
- environmental conditions;
- security;
- incidents;
- deviations;
- workload;
- interventions;
- lessons.

## Review Questions

1. Was the AI used only within its authorisation?
2. Did the configuration remain unchanged?
3. Were human authority arrangements effective?
4. Did operators understand AI limitations?
5. Was uncertainty communicated appropriately?
6. Did autonomy remain within authorised limits?
7. Were environmental conditions within bounds?
8. Did performance remain acceptable?
9. Were interventions effective?
10. Did any deviations occur?
11. Did any incidents occur?
12. Are additional TEVV activities required?
13. Is revalidation required?
14. Is reauthorisation required?

---

# 21. Operational Employment Lifecycle

D-AIGAAF models operational employment as:

**Prepare**
→ **Verify Readiness**
→ **Activate**
→ **Employ**
→ **Monitor**
→ **Decide**
→ **Intervene if Required**
→ **Respond to Degradation**
→ **Closeout**
→ **Review**
→ **Learn**

Operational employment should remain connected to the wider lifecycle rather than becoming a governance dead end.

---

# 22. Employment and Authorisation

Employment must remain within the boundaries established by operational authorisation.

The relationship is:

**Authorisation**
→ **Employment Conditions**
→ **Mission Execution**
→ **Monitoring**
→ **Deviation Detection**
→ **Intervention / Escalation**

The operational team should not expand authority merely because the mission evolves.

---

# 23. Employment and Human Authority

The designated human authority should remain:

- identifiable;
- available;
- competent;
- informed;
- capable of intervention;
- accountable.

If these conditions fail, the authorised mode of AI employment may no longer be valid.

---

# 24. Employment and Uncertainty

Operational users should be able to distinguish:

- what the AI knows;
- what the AI estimates;
- what the AI does not know;
- what information may be stale;
- what assumptions underpin the output.

The governing principle is:

> **Operational users should not be required to treat uncertain AI output as established fact.**

---

# 25. Employment and Autonomy

During employment, autonomy should be actively monitored.

Potential transition logic may include:

**A2**
→ **A3**
→ **A4**

or, when conditions deteriorate:

**A4**
→ **A3**
→ **A2**
→ **Safe State**

The authorised transition logic must be defined before employment and supported by appropriate TEVV.

---

# 26. Employment in Degraded Conditions

Operational employment must account for:

- disconnected operations;
- reduced data;
- degraded sensors;
- communications failure;
- cyber attack;
- electromagnetic disruption;
- loss of personnel;
- infrastructure failure.

A capability should not silently continue operating under assumptions that no longer hold.

---

# 27. Employment and AI-to-AI Interaction

Where multiple AI systems interact:

- authority boundaries must remain explicit;
- outputs should remain attributable;
- automated delegation should be controlled;
- AI-generated instructions should not automatically create authority;
- consequential actions should remain within the authorised governance chain.

The governing rule is:

> **Operational interaction between AI systems cannot create new operational authority.**

---

# 28. Operational Logging

Logging requirements should be proportionate to consequence.

For higher-consequence systems, consider recording:

- AI inputs;
- outputs;
- confidence;
- uncertainty;
- model/version;
- configuration;
- human decisions;
- actions;
- interventions;
- autonomy transitions;
- environmental conditions;
- system health;
- significant errors.

Records should support reconstruction of consequential events.

---

# 29. Operational Employment and Continuous Assurance

Operational employment produces real-world evidence.

That evidence should feed:

**Employment**
→ **Monitoring**
→ **Evidence**
→ **Assurance**
→ **Risk Review**
→ **Learning**
→ **Revalidation**
→ **Reauthorisation where required**

Operational data should therefore be treated as part of the assurance ecosystem.

---

# 30. Operational Employment and Incidents

When an incident occurs:

**Protect**
→ **Stabilise**
→ **Preserve Evidence**
→ **Report**
→ **Investigate**
→ **Correct**
→ **Reassess**
→ **Revalidate**
→ **Reauthorise if Required**

Operational teams should not independently declare a capability safe for continued use following a material incident without the appropriate governance decision.

---

# 31. Operational Employment and Workforce

Safe employment depends on:

- adequate staffing;
- competence;
- AI literacy;
- workload management;
- clear authority;
- intervention capability;
- shift continuity;
- training;
- exercises.

Workforce conditions should be monitored because they can materially affect human control.

---

# 32. Operational Employment and Security

Operational use should monitor for:

- adversarial inputs;
- suspicious data;
- unexpected model behaviour;
- prompt/instruction manipulation;
- compromised tools;
- cyber attack;
- model integrity anomalies;
- unauthorised access;
- supply-chain indicators.

Security events may require immediate restriction or suspension of employment.

---

# 33. Anti-Pattern — Authorised Means Automatically Safe to Use

D-AIGAAF rejects:

**Authorised**
→ **Use Without Operational Checks**

Authorisation assumes defined conditions.

Before and during employment, those conditions must remain valid.

---

# 34. Anti-Pattern — Operator as Passive Consumer

The operator should not be treated as merely a recipient of AI output.

The operator may need to:

- interpret;
- question;
- verify;
- reject;
- intervene;
- escalate;
- terminate.

Meaningful human control requires active operational capability.

---

# 35. Anti-Pattern — Mission Urgency Automatically Expands AI Authority

Operational urgency may increase pressure to use AI, but it does not automatically expand its authority.

If emergency use is required, it should occur through:

- predefined emergency conditions;
- delegated authority;
- temporary authorisation;
- compensating controls;
- explicit duration;
- post-use review.

---

# 36. Final Operational Employment Principle

Operational employment is where governance assumptions encounter operational reality.

The complete employment chain is:

**Authorisation**
→ **Preparation**
→ **Readiness**
→ **Activation**
→ **Employment**
→ **Human Decision**
→ **AI Action / Recommendation**
→ **Monitoring**
→ **Intervention**
→ **Closeout**
→ **Incident / Lesson**
→ **Assurance**
→ **Revalidation / Reauthorisation**

The governing principle is:

> **During operational employment, an AI capability must remain within its authorised mission, configuration, environment, autonomy and human-authority boundaries, while its performance, uncertainty, security, human control and operational conditions are continuously observed and acted upon when material deviations occur.**
