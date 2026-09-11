# 13-Continuous Assurance Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 13 — Continuous Assurance**.

Continuous assurance ensures that confidence in an AI capability is maintained throughout operational life rather than established once and then assumed to remain valid.

The central principle is:

> **Assurance is a continuing state of evidence and justified confidence, not a one-time approval event.**

Continuous assurance should detect changes in:

- AI behaviour;
- model performance;
- data;
- environment;
- threats;
- security;
- human control;
- autonomy;
- suppliers;
- dependencies;
- workforce;
- mission;
- configuration;
- operational conditions.

The objective is not continuous paperwork. It is continuous confidence that the capability remains within its authorised risk, behavioural and operational boundaries.

---

# 2. Template Set

The recommended Continuous Assurance template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-13-001 | Continuous Assurance Governance Record |
| D-AIGAAF-T-13-002 | Assurance Evidence & Confidence Record |
| D-AIGAAF-T-13-003 | Assurance Monitoring & Indicator Record |
| D-AIGAAF-T-13-004 | Assurance Review & Independent Challenge Record |
| D-AIGAAF-T-13-005 | Assurance Finding & Corrective Action Record |
| D-AIGAAF-T-13-006 | Human Control & Autonomy Assurance Record |
| D-AIGAAF-T-13-007 | Environment, Security & Dependency Assurance Record |
| D-AIGAAF-T-13-008 | Change, Revalidation & Reauthorisation Assurance Record |
| D-AIGAAF-T-13-009 | Assurance Reporting & Dashboard Record |
| D-AIGAAF-T-13-010 | Assurance Learning & Continuous Improvement Record |

---

# 3. Template 13-001 — Continuous Assurance Governance Record

## Purpose

Defines responsibility for maintaining assurance throughout the operational lifecycle.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Assurance owner
- Operational authority
- Risk owner
- Technical authority
- Security authority
- TEVV authority
- Human authority
- Monitoring authority
- Independent assurance authority
- Escalation authority
- Review authority
- Review frequency

## Governance Questions

- Who owns continuing assurance?
- What evidence must be monitored?
- Which indicators trigger escalation?
- Who can require additional testing?
- Who can require revalidation?
- Who can recommend suspension?
- Who can require reauthorisation?

---

# 4. Template 13-002 — Assurance Evidence & Confidence Record

## Purpose

Records evidence supporting continuing confidence in the AI capability.

## Evidence Categories

Consider:

- TEVV;
- operational performance;
- security;
- human control;
- autonomy;
- environment;
- data;
- supply chain;
- incidents;
- workforce;
- configuration;
- change history.

## Required Fields

- Evidence ID
- Evidence
- Source
- Date
- Configuration
- Mission
- Environment
- Relevance
- Currency
- Independence
- Limitations
- Confidence
- Assurance conclusion

Evidence confidence should reflect both the strength of evidence and the uncertainty surrounding it.

---

# 5. Template 13-003 — Assurance Monitoring & Indicator Record

## Purpose

Defines and records indicators used to detect deterioration in assurance.

## Indicator Categories

### Technical

- performance;
- latency;
- availability;
- reliability;
- error rates.

### AI Behaviour

- confidence;
- uncertainty;
- drift;
- anomalous outputs;
- unexpected behaviour.

### Operational

- mission effectiveness;
- intervention frequency;
- boundary deviations;
- operator workload.

### Security

- attacks;
- vulnerabilities;
- integrity anomalies;
- suspicious inputs.

### Governance

- expired evidence;
- overdue reviews;
- competence gaps;
- supplier changes;
- unresolved findings.

## Required Fields

- Indicator
- Definition
- Threshold
- Source
- Frequency
- Owner
- Current state
- Trend
- Trigger
- Required action

---

# 6. Template 13-004 — Assurance Review & Independent Challenge Record

## Purpose

Records periodic review and independent challenge of the continuing assurance position.

## Required Fields

- Review ID
- Capability
- Scope
- Evidence reviewed
- Reviewer
- Independence
- Findings
- Evidence gaps
- Confidence
- Challenge
- Management response
- Decision
- Follow-up

Independent challenge should be proportionate to consequence and assurance significance.

---

# 7. Template 13-005 — Assurance Finding & Corrective Action Record

## Purpose

Records weaknesses identified through continuous assurance.

## Finding Categories

- control weakness;
- evidence gap;
- performance degradation;
- security weakness;
- human-control weakness;
- environmental mismatch;
- autonomy concern;
- supplier issue;
- process failure;
- governance nonconformity.

## Required Fields

- Finding ID
- Source
- Requirement/control
- Finding
- Severity
- Consequence
- Root cause
- Corrective action
- Owner
- Due date
- Verification
- Residual risk
- Closure

An assurance finding should remain open until the effectiveness of corrective action has been appropriately verified.

---

# 8. Template 13-006 — Human Control & Autonomy Assurance Record

## Purpose

Provides continuing assurance that human control and authorised autonomy remain effective.

## Assess

- human authority;
- competence;
- workload;
- situational awareness;
- intervention;
- override;
- autonomy level;
- autonomy transitions;
- boundary adherence;
- unexpected autonomy.

## Required Fields

- Capability
- Autonomy
- Human role
- Evidence
- Observation
- Deviation
- Risk
- Control
- Assurance status
- Escalation

A capability should not be considered continuously assured if human control has materially degraded.

---

# 9. Template 13-007 — Environment, Security & Dependency Assurance Record

## Purpose

Assesses whether external conditions and dependencies remain consistent with the assurance basis.

## Assess

### Environment

- geography;
- terrain;
- weather;
- communications;
- electromagnetic conditions;
- threat environment.

### Security

- cyber posture;
- adversarial activity;
- model integrity;
- data integrity;
- vulnerabilities.

### Dependencies

- suppliers;
- cloud;
- APIs;
- external data;
- infrastructure;
- critical services.

## Required Fields

- Domain
- Condition
- Previous state
- Current state
- Change
- Impact
- Evidence
- Risk
- Required action

---

# 10. Template 13-008 — Change, Revalidation & Reauthorisation Assurance Record

## Purpose

Determines whether changes have affected the continuing validity of assurance and authorisation.

## Change Categories

Consider:

- model;
- software;
- hardware;
- data;
- configuration;
- mission;
- environment;
- autonomy;
- human roles;
- supplier;
- security controls.

## Required Fields

- Change
- Impact
- Risk
- Evidence
- TEVV impact
- Revalidation requirement
- Reauthorisation requirement
- Decision
- Authority
- Status

The key question is:

> **Does existing assurance remain valid after the change?**

---

# 11. Template 13-009 — Assurance Reporting & Dashboard Record

## Purpose

Provides governance-level visibility of assurance status.

## Dashboard Domains

- overall assurance status;
- critical findings;
- risk;
- performance;
- security;
- human control;
- autonomy;
- environment;
- supply chain;
- workforce;
- incidents;
- changes;
- overdue actions;
- revalidation;
- authorisation status.

## Status Model

Possible statuses:

- assured;
- assured with conditions;
- degraded assurance;
- assurance concern;
- assurance suspended;
- evidence insufficient.

Dashboard indicators should support decisions rather than become reporting for its own sake.

---

# 12. Template 13-010 — Assurance Learning & Continuous Improvement Record

## Purpose

Captures lessons from operational evidence and converts them into governance improvements.

## Required Fields

- Lesson ID
- Source
- Observation
- Expected state
- Actual state
- Cause
- Consequence
- Lesson
- Recommendation
- Required change
- Owner
- Validation
- Governance impact

Learning may update:

- requirements;
- risk;
- controls;
- TEVV;
- training;
- operating boundaries;
- authorisation;
- architecture;
- procurement;
- security.

---

# 13. Continuous Assurance Model

D-AIGAAF defines continuous assurance as:

**Evidence**
→ **Monitor**
→ **Assess**
→ **Challenge**
→ **Find**
→ **Correct**
→ **Verify**
→ **Reassess Confidence**
→ **Escalate / Revalidate / Reauthorise**
→ **Learn**

The process should operate throughout the capability lifecycle.

---

# 14. Assurance Is a Confidence Claim

Assurance should answer:

> **What do we know, how do we know it, what remains uncertain, and why is the current level of confidence sufficient for the decision being made?**

A useful assurance statement therefore includes:

- evidence;
- scope;
- assumptions;
- limitations;
- uncertainty;
- residual risk;
- confidence;
- decision relevance.

---

# 15. Assurance Confidence

Confidence should not be represented as a single unsupported number.

Consider:

### Evidence Strength

How strong is the evidence?

### Evidence Relevance

Does it apply to the actual mission and configuration?

### Evidence Currency

Is it still current?

### Evidence Independence

Has it been independently challenged where required?

### Evidence Coverage

Does it cover important failure modes and conditions?

### Uncertainty

What remains unknown?

Confidence should be derived from the overall evidence position.

---

# 16. Assurance Indicators

Indicators should be linked to decisions.

Examples:

**Performance deterioration**
→ targeted investigation

**Model/data drift**
→ additional evaluation

**Human workload increase**
→ reassess human control

**Security event**
→ security reassessment

**Environmental change**
→ environment impact assessment

**Supplier change**
→ dependency assessment

**Unexpected autonomy**
→ immediate governance escalation

The indicator itself is not the objective. The objective is timely governance action.

---

# 17. Assurance Thresholds

Thresholds should distinguish between:

- observation;
- warning;
- intervention;
- escalation;
- suspension.

Example:

**Normal**
→ continue monitoring

**Warning**
→ investigate

**Material deviation**
→ restrict or intervene

**Critical deviation**
→ suspend / safe state

Thresholds should be mission- and consequence-specific.

---

# 18. Continuous Assurance and Human Authority

Assurance should monitor whether human control remains effective.

Relevant indicators may include:

- intervention success;
- intervention latency;
- override frequency;
- operator workload;
- training status;
- automation bias;
- decision quality;
- situational awareness;
- staffing.

Human control should be treated as an operational assurance variable.

---

# 19. Continuous Assurance and Autonomy

Monitor:

- actual autonomy level;
- authorised autonomy;
- transitions;
- boundary adherence;
- unexpected autonomous behaviour;
- human supervision;
- intervention.

A material divergence between authorised and observed autonomy should trigger escalation.

---

# 20. Continuous Assurance and Environment

Environmental monitoring should assess whether assumptions supporting authorisation remain valid.

Examples:

**New Threat**
→ threat assessment

**New Geography**
→ environmental assessment

**Communications Degradation**
→ degraded-operation assessment

**New Electromagnetic Conditions**
→ information/EM assessment

**Changed Human Workload**
→ human-control assessment

---

# 21. Continuous Assurance and Security

Security assurance should continue after deployment.

Monitor:

- vulnerabilities;
- attack attempts;
- adversarial inputs;
- model integrity;
- data integrity;
- access;
- supply-chain events;
- anomalous behaviour.

Security deterioration may change operational risk and therefore authorisation status.

---

# 22. Continuous Assurance and Operational Data

Operational data can reveal behaviour that laboratory testing did not expose.

Useful sources include:

- operational logs;
- incident records;
- intervention records;
- performance metrics;
- user feedback;
- environmental observations;
- security events;
- maintenance records.

Operational evidence should be assessed for reliability and relevance before being used to update assurance conclusions.

---

# 23. Continuous Assurance and Drift

Drift may occur in:

- data;
- environment;
- threat;
- user behaviour;
- mission;
- operational patterns;
- system performance.

Drift should trigger proportionate evaluation.

Not all drift requires reauthorisation, but material drift should not be ignored.

---

# 24. Continuous Assurance and Incidents

Incidents should trigger reassessment of assurance assumptions.

The sequence is:

**Incident**
→ **Protect**
→ **Investigate**
→ **Correct**
→ **Verify**
→ **Reassess Assurance**
→ **Revalidate**
→ **Reauthorise if Required**

An incident should not be treated as isolated if it reveals a systemic governance weakness.

---

# 25. Continuous Assurance and Change

Changes may invalidate previous evidence.

Therefore:

**Change**
→ **Impact Assessment**
→ **TEVV**
→ **Revalidation**
→ **Assurance Update**
→ **Reauthorisation where Required**

The required response should be proportional to the change and consequence.

---

# 26. Continuous Assurance and Supply Chain

Monitor:

- supplier ownership;
- supplier security;
- critical dependencies;
- updates;
- service availability;
- external access;
- geopolitical changes;
- substitution options.

A material supplier change may affect the assurance basis even when the user-visible AI behaviour initially appears unchanged.

---

# 27. Assurance Escalation Model

D-AIGAAF recommends four broad states:

### Green — Confidence Maintained

Evidence supports continued assurance.

### Amber — Confidence Reduced

Issue exists but controls remain effective.

### Red — Assurance Concern

Existing evidence or controls may no longer justify confidence.

### Black / Suspended — Assurance Invalid

Critical evidence or control failure requires restriction or suspension.

Actual terminology may be adapted to organisational requirements.

---

# 28. Assurance and Operational Authorisation

Continuous assurance supports, but does not replace, operational authorisation.

The relationship is:

**Continuous Evidence**
→ **Assurance Assessment**
→ **Risk Decision**
→ **Authorisation Status**

Possible outcomes include:

- continue;
- continue with conditions;
- restrict;
- require additional testing;
- revalidate;
- reauthorise;
- suspend.

---

# 29. Assurance Evidence Package

The continuing assurance package may contain:

- current TEVV evidence;
- operational performance;
- monitoring records;
- human-control evidence;
- autonomy evidence;
- security evidence;
- environmental evidence;
- supplier/dependency evidence;
- incident records;
- change records;
- corrective actions;
- independent reviews;
- current authorisation.

---

# 30. Anti-Pattern — Annual Assurance Only

D-AIGAAF rejects:

**Annual Review**
→ **Assured for Another Year**

A consequential AI system may change materially between formal reviews.

Continuous assurance should therefore combine:

- automated monitoring where appropriate;
- operational reporting;
- event-driven review;
- periodic governance review.

---

# 31. Anti-Pattern — Dashboard Equals Assurance

A dashboard is an observation mechanism.

It does not itself establish assurance.

The correct chain is:

**Indicator**
→ **Evidence**
→ **Interpretation**
→ **Judgement**
→ **Action**

A green dashboard should not override credible evidence of an emerging risk.

---

# 32. Anti-Pattern — More Data Equals More Assurance

More telemetry does not automatically create better assurance.

Assurance depends on:

- relevance;
- reliability;
- coverage;
- independence;
- interpretation;
- context.

Large quantities of weak evidence can still produce weak assurance.

---

# 33. Final Continuous Assurance Principle

D-AIGAAF treats assurance as a living confidence judgement maintained through evidence, challenge and action.

The complete chain is:

**Evidence**
→ **Confidence**
→ **Monitoring**
→ **Challenge**
→ **Finding**
→ **Correction**
→ **Verification**
→ **Reassessment**
→ **Authorisation Decision**
→ **Operational Monitoring**
→ **Learning**

The governing principle is:

> **Confidence in a consequential AI capability should be continuously earned through relevant evidence, monitoring, independent challenge, corrective action and reassessment, with material changes in risk, behaviour, environment, security, autonomy, human control or dependencies capable of triggering revalidation or reauthorisation.**
