# 14-Incident and Fail-Safe Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 14 — Incident & Fail-Safe**.

This module establishes the governance and operational mechanisms required when an AI capability:

- behaves unexpectedly;
- produces materially incorrect or unsafe outputs;
- exceeds an authorised boundary;
- loses meaningful human control;
- exhibits unexpected autonomy;
- suffers a security compromise;
- encounters a critical environmental condition;
- experiences a material technical failure;
- creates or contributes to unacceptable consequences.

The central principle is:

> **A consequential AI capability must have defined mechanisms to detect abnormal behaviour, protect people and assets, transition to a controlled state, preserve evidence, investigate, recover and determine whether revalidation or reauthorisation is required.**

The core incident lifecycle is:

**Detect → Classify → Protect → Fail-Safe → Investigate → Correct → Recover → Reassess Assurance → Reauthorise → Learn**

---

# 2. Template Set

The recommended Incident & Fail-Safe template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-14-001 | Incident & Fail-Safe Governance Record |
| D-AIGAAF-T-14-002 | AI Incident Classification Record |
| D-AIGAAF-T-14-003 | Incident Detection & Reporting Record |
| D-AIGAAF-T-14-004 | Immediate Protective Response Record |
| D-AIGAAF-T-14-005 | Fail-Safe & Safe-State Assessment |
| D-AIGAAF-T-14-006 | Loss of Human Control / Unexpected Autonomy Record |
| D-AIGAAF-T-14-007 | Incident Investigation & Evidence Record |
| D-AIGAAF-T-14-008 | Corrective Action, Recovery & Restoration Record |
| D-AIGAAF-T-14-009 | Assurance, Revalidation & Reauthorisation Review |
| D-AIGAAF-T-14-010 | Incident Learning & Continuous Improvement Record |
| D-AIGAAF-T-14-011 | Incident Register & Records Index |
| D-AIGAAF-T-14-012 | Fail-Safe Test & Validation Record |

---

# 3. Template 14-001 — Incident & Fail-Safe Governance Record

## Purpose

Defines governance responsibilities for AI incidents and fail-safe actions.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Incident authority
- Operational authority
- Safety authority
- Security authority
- Technical authority
- Risk owner
- Assurance authority
- Investigation authority
- Recovery authority
- Reauthorisation authority
- Escalation authority
- Review date

## Governance Questions

- Who can declare an AI incident?
- Who can order immediate restriction?
- Who can activate a fail-safe?
- Who can suspend operational use?
- Who owns the investigation?
- Who accepts residual risk after recovery?
- Who decides whether reauthorisation is required?

---

# 4. Template 14-002 — AI Incident Classification Record

## Purpose

Classifies an incident according to its nature, consequence and governance significance.

## Classification Dimensions

Consider:

### Behaviour

- incorrect output;
- unexpected behaviour;
- hallucination/confabulation;
- unsafe recommendation;
- unexpected autonomy;
- boundary violation.

### Security

- compromise;
- adversarial manipulation;
- data poisoning;
- prompt/instruction manipulation;
- cyber attack;
- unauthorised access.

### Human Control

- intervention failure;
- override failure;
- authority ambiguity;
- workload-related failure;
- loss of situational awareness.

### Environment

- environmental boundary breach;
- sensor degradation;
- communications loss;
- electromagnetic disruption;
- adversarial environmental change.

## Required Fields

- Incident ID
- Category
- Severity
- Consequence
- Mission impact
- Immediate risk
- Escalation level
- Required response
- Authority

---

# 5. Template 14-003 — Incident Detection & Reporting Record

## Purpose

Records how an incident was detected and reported.

## Detection Sources

- automated monitoring;
- operator;
- supervisor;
- commander;
- security monitoring;
- system diagnostics;
- external report;
- post-mission review.

## Required Fields

- Incident ID
- Detection time
- Detection source
- Capability state
- Observed behaviour
- Expected behaviour
- Initial assessment
- Immediate action
- Reporting authority
- Escalation
- Evidence

Detection should occur as early as reasonably practicable.

---

# 6. Template 14-004 — Immediate Protective Response Record

## Purpose

Records actions taken to prevent escalation of harm.

## Possible Actions

- pause;
- stop;
- isolate;
- restrict;
- reduce autonomy;
- disable affected function;
- transfer human authority;
- transition to safe state;
- disconnect external service;
- suspend mission use.

## Required Fields

- Incident ID
- Trigger
- Immediate action
- Authority
- Time
- AI state
- Human state
- Expected effect
- Actual effect
- Residual risk
- Escalation

The first objective during a serious incident is control of consequences, not explanation of the root cause.

---

# 7. Template 14-005 — Fail-Safe & Safe-State Assessment

## Purpose

Determines whether the capability can transition to an appropriate safe or controlled state.

## Assessment Areas

- trigger detection;
- safe-state definition;
- transition mechanism;
- human involvement;
- autonomy reduction;
- shutdown;
- isolation;
- loss of communication;
- recovery;
- prevention of unintended continuation.

## Required Fields

- Failure condition
- Trigger
- Safe state
- Transition
- Time to safe state
- Human authority
- Technical mechanism
- Expected outcome
- Observed outcome
- Test evidence
- Residual risk

A safe state must be defined in mission context.

---

# 8. Template 14-006 — Loss of Human Control / Unexpected Autonomy Record

## Purpose

Records incidents where human control was weakened, lost or bypassed.

## Examples

- AI acted without required approval;
- AI exceeded autonomy boundary;
- human could not intervene;
- override failed;
- AI continued after authority withdrawal;
- AI transitioned to a higher autonomy state unexpectedly;
- human authority became unavailable.

## Required Fields

- Incident ID
- Authorised autonomy
- Observed autonomy
- Human authority
- Expected control
- Actual control
- Trigger
- Consequence
- Immediate response
- Evidence
- Root cause
- Corrective action
- Revalidation
- Reauthorisation

Unexpected autonomy should receive heightened governance attention.

---

# 9. Template 14-007 — Incident Investigation & Evidence Record

## Purpose

Provides a structured record of incident investigation.

## Investigation Areas

- timeline;
- system state;
- configuration;
- model;
- data;
- inputs;
- outputs;
- instructions;
- tools;
- environment;
- human actions;
- security;
- supplier dependencies;
- external services.

## Required Fields

- Incident ID
- Investigator
- Scope
- Evidence
- Timeline
- Configuration
- Root cause
- Contributing factors
- Uncertainty
- Findings
- Confidence
- Recommendations

Investigators should distinguish established facts from hypotheses.

---

# 10. Template 14-008 — Corrective Action, Recovery & Restoration Record

## Purpose

Records measures required to correct the incident and restore controlled operation.

## Corrective Actions

Consider:

- technical correction;
- configuration change;
- model change;
- data correction;
- security control;
- human training;
- operating restriction;
- autonomy reduction;
- supplier remediation;
- process change.

## Required Fields

- Incident ID
- Finding
- Corrective action
- Owner
- Due date
- Verification
- Recovery condition
- Residual risk
- Approval
- Restoration decision

Recovery should not occur solely because the immediate symptom disappears.

---

# 11. Template 14-009 — Assurance, Revalidation & Reauthorisation Review

## Purpose

Determines whether the incident changed the assurance or authorisation basis.

## Assess

- risk;
- requirements;
- controls;
- TEVV;
- model;
- data;
- security;
- human control;
- autonomy;
- environment;
- supply chain;
- workforce;
- authorisation assumptions.

## Required Fields

- Incident
- Changed assumption
- Impact
- Evidence
- Risk
- Revalidation required
- Reauthorisation required
- Conditions
- Authority
- Decision

Possible outcomes:

- resume;
- resume with restrictions;
- additional testing;
- revalidation;
- reauthorisation;
- continued suspension;
- retirement.

---

# 12. Template 14-010 — Incident Learning & Continuous Improvement Record

## Purpose

Converts incident experience into improvements across the governance lifecycle.

## Required Fields

- Lesson ID
- Incident
- Observation
- Root cause
- Contributing factors
- Consequence
- Lesson
- Recommendation
- Required change
- Owner
- Validation
- Governance impact

Lessons may update:

- requirements;
- risk models;
- controls;
- TEVV;
- operating boundaries;
- autonomy;
- training;
- security;
- acquisition;
- architecture;
- authorisation.

---

# 13. Template 14-011 — Incident Register & Records Index

## Purpose

Maintains the authoritative record of incidents and associated evidence.

## Required Fields

- Incident ID
- Capability
- Mission
- Date/time
- Classification
- Severity
- Status
- Fail-safe action
- Investigation status
- Corrective action
- Revalidation
- Reauthorisation
- Closure
- Evidence location
- Retention

Possible status values:

- detected;
- contained;
- investigating;
- corrective action;
- under revalidation;
- under reauthorisation;
- recovered;
- closed;
- unresolved.

---

# 14. Template 14-012 — Fail-Safe Test & Validation Record

## Purpose

Provides evidence that fail-safe mechanisms actually operate as intended.

## Test Areas

- trigger;
- detection;
- transition;
- shutdown;
- autonomy reduction;
- isolation;
- human intervention;
- communications loss;
- power loss;
- cyber event;
- sensor failure;
- recovery.

## Required Fields

- Test ID
- Failure scenario
- Trigger
- Expected safe state
- Observed state
- Transition time
- Human action
- System action
- Result
- Limitations
- Evidence
- Finding
- Acceptance

Fail-safe mechanisms should be tested under representative and degraded conditions where relevant.

---

# 15. Incident Severity Model

Incident severity should reflect consequence rather than technical inconvenience alone.

Consider:

### Level 1 — Low

Limited impact; no material loss of control or mission consequence.

### Level 2 — Moderate

Material degradation or contained governance/control issue.

### Level 3 — High

Significant mission, security, safety or human-control impact.

### Level 4 — Critical

Severe or potentially catastrophic consequence, loss of control, unauthorised consequential action or major compromise.

Organisations may adapt the terminology while retaining consequence-based classification.

---

# 16. Fail-Safe Philosophy

D-AIGAAF does not assume that every failure should result in immediate complete shutdown.

The appropriate response depends on:

- mission;
- consequence;
- failure mode;
- reversibility;
- autonomy;
- environment;
- human control;
- safety requirements.

Possible safe responses include:

**Continue**
→ **Restrict**
→ **Reduce Autonomy**
→ **Transfer Control**
→ **Isolate**
→ **Stop**
→ **Safe State**

The correct fail-safe state should be defined during design, TEVV and authorisation.

---

# 17. Fail-Safe Is Mission-Specific

A safe state for one AI capability may not be safe for another.

For example:

- a logistics optimisation system may safely stop;
- a monitoring system may safely continue with reduced functionality;
- a navigation system may need controlled degraded operation;
- a consequential autonomous system may require immediate transition to human control.

Therefore:

> **“Fail-safe” should describe the safest authorised state for the mission and failure condition, not merely system shutdown.**

---

# 18. Fail-Safe and Human Authority

Where human intervention is required, assess:

- authority;
- availability;
- competence;
- response time;
- communications;
- workload;
- situational awareness;
- intervention effectiveness.

A theoretical override that cannot be exercised within the relevant operational timescale is not an effective fail-safe control.

---

# 19. Fail-Safe Under Loss of Communications

Where disconnected operation is possible, define:

- what happens when communications are lost;
- whether autonomy changes;
- whether the AI can continue;
- what information becomes unavailable;
- whether human intervention remains possible;
- when the system must restrict or stop;
- how authority is transferred or restored.

These conditions should be tested before operational authorisation where relevant.

---

# 20. Fail-Safe and Unexpected Autonomy

Unexpected autonomy should be treated as a potentially serious incident.

Response may include:

**Detect**
→ **Restrict**
→ **Reduce Autonomy**
→ **Human Control**
→ **Safe State**
→ **Investigate**
→ **Revalidate**
→ **Reauthorise**

The response should be proportionate to consequence and the nature of the deviation.

---

# 21. Incident Evidence Preservation

For material incidents, preserve relevant evidence including:

- system logs;
- model/version;
- configuration;
- data;
- inputs;
- outputs;
- instructions/prompts;
- tool activity;
- network/security events;
- environmental state;
- human decisions;
- interventions;
- autonomy transitions.

Evidence integrity should be protected so that subsequent investigation can distinguish reliable records from reconstructed accounts.

---

# 22. Incident Investigation and Uncertainty

Investigations should explicitly distinguish:

**Known**
from

**Probable**
from

**Possible**
from

**Unknown**

An investigation should not manufacture certainty simply to close an incident.

Where root cause remains uncertain, residual uncertainty should be incorporated into the recovery and reauthorisation decision.

---

# 23. Incident and Operational Authorisation

A material incident may invalidate the basis for operational authorisation.

The relationship is:

**Incident**
→ **Immediate Protection**
→ **Investigation**
→ **Risk Reassessment**
→ **Assurance Review**
→ **Revalidation**
→ **Reauthorisation**

The capability should not automatically return to its previous authorised state.

---

# 24. Incident and Change Management

Corrective actions may create changes requiring governance.

Examples:

- model modification;
- software patch;
- data change;
- new security control;
- changed autonomy;
- altered operating boundary.

These should enter the Module 15 change and reauthorisation process.

---

# 25. Incident and Continuous Assurance

Incidents provide important assurance evidence.

A single incident may reveal:

- weak controls;
- incomplete TEVV;
- environmental assumptions;
- human-control weaknesses;
- security gaps;
- supplier dependencies;
- insufficient monitoring.

The lesson should therefore be assessed for systemic significance.

---

# 26. Incident and Supply Chain

Where a supplier contributes to an incident, assess:

- component provenance;
- supplier access;
- update mechanism;
- dependency;
- vulnerability;
- contractual controls;
- supplier response;
- substitution options.

Supplier involvement should not prevent independent organisational investigation.

---

# 27. Incident and Workforce

Investigate whether human factors contributed to the incident.

Consider:

- training;
- competence;
- workload;
- fatigue;
- authority;
- supervision;
- communication;
- situational awareness;
- automation bias.

The purpose is to identify system weaknesses, not automatically attribute blame to individuals.

---

# 28. Recovery Criteria

Recovery criteria should be defined before restoring normal operation where practical.

They may include:

- cause understood sufficiently;
- immediate hazard controlled;
- corrective action implemented;
- corrective action verified;
- required TEVV completed;
- human-control capability restored;
- security restored;
- environmental assumptions confirmed;
- residual risk accepted;
- authorisation restored or renewed.

---

# 29. Anti-Pattern — Restart Equals Recovery

D-AIGAAF rejects:

**System Restarted**
→ **Incident Resolved**

Restarting a system may remove a symptom without correcting the underlying condition.

Recovery requires evidence that:

- the hazard is controlled;
- the relevant cause is understood sufficiently;
- corrective controls work;
- residual risk is acceptable;
- authority to resume exists.

---

# 30. Anti-Pattern — Safe State Equals Power Off

Powering down may not always be the safest operational response.

A safe state must consider:

- mission;
- physical consequences;
- autonomous activity;
- system dependencies;
- human control;
- environment.

The appropriate response may instead be:

**Restricted Function**
or
**Reduced Autonomy**
or
**Human-Controlled Degraded Mode**.

---

# 31. Anti-Pattern — Incident Closure Without Learning

Closing the incident record does not necessarily close the governance problem.

Material incidents should be assessed for implications across:

- risk;
- TEVV;
- security;
- human authority;
- autonomy;
- environment;
- supply chain;
- workforce;
- architecture;
- authorisation.

---

# 32. Final Incident & Fail-Safe Principle

D-AIGAAF treats incident response as a governance lifecycle rather than an isolated technical support activity.

The complete chain is:

**Detect**
→ **Classify**
→ **Protect**
→ **Fail-Safe**
→ **Investigate**
→ **Correct**
→ **Recover**
→ **Reassess Assurance**
→ **Revalidate**
→ **Reauthorise**
→ **Learn**

The governing principle is:

> **A consequential AI capability should have predefined, tested and operationally usable mechanisms to detect abnormal behaviour, protect against escalating consequences, transition to an appropriate safe or controlled state, preserve evidence, investigate uncertainty, correct identified weaknesses and determine whether continued assurance and operational authorisation remain justified.**
