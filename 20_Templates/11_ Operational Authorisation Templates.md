# 11-Operational Authorisation Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 11 — Operational Authorisation**.

Operational authorisation is the formal governance decision that permits a defined AI capability to perform a defined function for a defined mission, within specified environmental, autonomy, human-authority and risk boundaries.

The central principle is:

> **AI capability does not equal operational authority. Operational authority exists only when explicitly granted by an authorised human governance mechanism under defined conditions.**

D-AIGAAF treats authorisation as a multidimensional decision:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Operational authorisation must remain distinct from:

- development;
- testing;
- assurance;
- deployment;
- operational readiness;
- employment.

The governing distinctions are:

> **Assured ≠ Authorised**  
> **Authorised ≠ Ready**  
> **Ready ≠ Deployed**  
> **Deployed ≠ Employed**

---

# 2. Template Set

The recommended Operational Authorisation template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-11-001 | Operational Authorisation Governance Record |
| D-AIGAAF-T-11-002 | Authorisation Application |
| D-AIGAAF-T-11-003 | Authorisation Scope & Boundary Record |
| D-AIGAAF-T-11-004 | Authorisation Evidence Assessment |
| D-AIGAAF-T-11-005 | Risk & Residual Risk Decision Record |
| D-AIGAAF-T-11-006 | Human Authority & Accountability Assessment |
| D-AIGAAF-T-11-007 | Autonomy Authorisation Assessment |
| D-AIGAAF-T-11-008 | Operational Environment Authorisation Assessment |
| D-AIGAAF-T-11-009 | Security & Supply Chain Authorisation Assessment |
| D-AIGAAF-T-11-010 | Operational Conditions & Constraints Record |
| D-AIGAAF-T-11-011 | Authorisation Decision Record |
| D-AIGAAF-T-11-012 | Authorisation Certificate / Statement |
| D-AIGAAF-T-11-013 | Conditional Authorisation Record |
| D-AIGAAF-T-11-014 | Temporary / Emergency Authorisation Record |
| D-AIGAAF-T-11-015 | Delegated Operational Authority Record |
| D-AIGAAF-T-11-016 | Authorisation Register |
| D-AIGAAF-T-11-017 | Authorisation Monitoring Record |
| D-AIGAAF-T-11-018 | Authorisation Breach / Boundary Deviation Record |
| D-AIGAAF-T-11-019 | Authorisation Suspension / Withdrawal Record |
| D-AIGAAF-T-11-020 | Reauthorisation Assessment |
| D-AIGAAF-T-11-021 | Authorisation Review Record |
| D-AIGAAF-T-11-022 | Authorisation Evidence & Records Index |

---

# 3. Template 11-001 — Operational Authorisation Governance Record

## Purpose

Defines who may recommend, approve, condition, suspend, review and withdraw operational authorisation.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Authorisation authority
- Operational authority
- Risk owner
- Assurance authority
- Technical authority
- Security authority
- Human authority
- Review authority
- Delegation arrangements
- Escalation arrangements
- Review date

## Governance Questions

- Who has authority to authorise?
- Is the authority legally and organisationally valid?
- What evidence must be available before authorisation?
- Who accepts residual risk?
- Who can impose conditions?
- Who can suspend or withdraw authorisation?
- Who can approve emergency use?
- Who reviews continued validity?

---

# 4. Template 11-002 — Authorisation Application

## Purpose

Provides the structured application for operational authorisation.

## Required Sections

### Capability

- capability name;
- version;
- configuration;
- AI functions;
- autonomy level.

### Mission

- mission;
- use case;
- intended effect;
- decision/action supported.

### Environment

- geographic area;
- physical conditions;
- information environment;
- technical environment;
- threat environment.

### Human Authority

- responsible authority;
- operator;
- supervisor;
- intervention authority.

### Risk

- consequence;
- risk assessment;
- residual risk;
- risk treatment.

### Evidence

- TEVV;
- security assurance;
- human-control evidence;
- environmental evidence;
- supply-chain evidence.

### Requested Authority

Specify exactly what the AI is being authorised to do.

---

# 5. Template 11-003 — Authorisation Scope & Boundary Record

## Purpose

Defines the exact boundaries within which authorisation applies.

## Boundary Categories

- mission;
- geography;
- time;
- environment;
- system configuration;
- data;
- autonomy;
- human authority;
- users;
- targets/objects where applicable;
- connected systems;
- external services.

## Required Fields

- Boundary
- Permitted condition
- Prohibited condition
- Trigger
- Detection
- Required response
- Authority
- Evidence

The scope should be sufficiently precise to prevent an authorisation from being interpreted more broadly than intended.

---

# 6. Template 11-004 — Authorisation Evidence Assessment

## Purpose

Determines whether available evidence is sufficient to support the requested authorisation.

## Evidence Domains

Consider:

- mission requirements;
- risk assessment;
- TEVV;
- security;
- adversarial evaluation;
- autonomy;
- human control;
- operational environment;
- supply chain;
- workforce competence;
- continuity;
- incident history.

## Required Fields

- Evidence
- Requirement
- Source
- Relevance
- Currency
- Independence
- Limitation
- Confidence
- Gap
- Decision impact

Evidence should be assessed for the actual configuration, mission and environment being authorised.

---

# 7. Template 11-005 — Risk & Residual Risk Decision Record

## Purpose

Records the risk decision underlying authorisation.

## Required Fields

- Hazard
- Consequence
- Likelihood
- Inherent risk
- Controls
- Residual risk
- Uncertainty
- Risk owner
- Acceptance authority
- Conditions
- Review date

## Decision Options

- accept;
- accept with conditions;
- reduce risk before authorisation;
- restrict scope;
- restrict autonomy;
- defer;
- reject.

Risk acceptance should be explicit rather than inferred from silence.

---

# 8. Template 11-006 — Human Authority & Accountability Assessment

## Purpose

Confirms that appropriate human authority exists for the requested operational use.

## Assess

- legitimate authority;
- role clarity;
- competence;
- AI literacy;
- situational awareness;
- decision rights;
- workload;
- supervision;
- intervention;
- override;
- escalation;
- accountability.

## Required Fields

- Human role
- Authority
- Responsibility
- Competence
- Control capability
- Intervention
- Capacity
- Evidence
- Gap
- Risk
- Acceptance

A named operator alone is not evidence of meaningful human control.

---

# 9. Template 11-007 — Autonomy Authorisation Assessment

## Purpose

Determines the maximum AI autonomy permitted for the specific mission and environment.

## Required Fields

- AI function
- Baseline autonomy
- Requested autonomy
- Consequence
- Human control
- Environmental uncertainty
- Adversarial exposure
- Reversibility
- Constraints
- Transition conditions
- Intervention
- Evidence
- Decision

## Autonomy Levels

| Level | Description |
|---|---|
| A0 | No meaningful AI decision |
| A1 | Information / observation |
| A2 | Analysis / recommendation |
| A3 | Human-authorised action |
| A4 | Supervised autonomous action |
| A5 | Independent consequential autonomy |

The authorisation should specify the permitted autonomy level rather than merely approving the capability generally.

---

# 10. Template 11-008 — Operational Environment Authorisation Assessment

## Purpose

Determines whether the capability is authorised for the specified operating environment.

## Assess

- geography;
- terrain;
- weather;
- communications;
- sensors;
- information quality;
- electromagnetic conditions;
- threat conditions;
- human environment;
- infrastructure.

## Required Fields

- Environment
- Condition
- Authorised range
- Evidence
- Limitation
- Risk
- Boundary
- Monitoring
- Exit trigger

Authorisation in one environment should not automatically imply authorisation in another.

---

# 11. Template 11-009 — Security & Supply Chain Authorisation Assessment

## Purpose

Determines whether security and supply-chain conditions support operational authorisation.

## Assess

- system security;
- model integrity;
- data integrity;
- adversarial resilience;
- supplier assurance;
- critical dependencies;
- external services;
- update mechanisms;
- access;
- vulnerabilities;
- continuity.

## Required Fields

- Risk
- Dependency
- Control
- Evidence
- Residual risk
- Condition
- Decision

Material security or supply-chain uncertainty should be reflected in authorisation conditions where appropriate.

---

# 12. Template 11-010 — Operational Conditions & Constraints Record

## Purpose

Defines conditions that must be satisfied during employment.

## Conditions May Include

- approved configuration;
- approved data sources;
- environmental limits;
- human supervision;
- communication requirements;
- security controls;
- autonomy limits;
- operating hours;
- geographic boundaries;
- intervention capability;
- staffing.

## Required Fields

- Condition
- Threshold
- Monitoring method
- Responsible role
- Consequence of breach
- Required action
- Authority

---

# 13. Template 11-011 — Authorisation Decision Record

## Purpose

Records the formal decision.

## Required Fields

- Decision ID
- Capability
- Mission
- Environment
- Autonomy
- Human authority
- Evidence reviewed
- Risk
- Conditions
- Decision
- Decision authority
- Date/time
- Validity period
- Review date
- Rationale

## Decision Options

- authorised;
- authorised with conditions;
- restricted authorisation;
- deferred;
- rejected;
- suspended.

The decision record should clearly identify what was authorised and what was not.

---

# 14. Template 11-012 — Authorisation Certificate / Statement

## Purpose

Provides the formal statement of operational authorisation.

## Minimum Content

- capability;
- configuration/version;
- mission;
- environment;
- autonomy;
- human authority;
- permitted functions;
- prohibited functions;
- conditions;
- validity period;
- monitoring requirements;
- suspension triggers;
- approving authority.

The certificate should never be interpreted independently of its conditions and scope.

---

# 15. Template 11-013 — Conditional Authorisation Record

## Purpose

Records authorisation subject to specified controls or restrictions.

## Examples

- restricted geography;
- reduced autonomy;
- enhanced supervision;
- limited mission type;
- additional monitoring;
- mandatory communications;
- specific data sources;
- temporary staffing;
- additional safeguards.

## Required Fields

- Condition
- Reason
- Risk addressed
- Monitoring
- Breach consequence
- Expiry
- Authority

Conditional authorisation should be treated as a deliberate risk-control mechanism, not as an administrative compromise.

---

# 16. Template 11-014 — Temporary / Emergency Authorisation Record

## Purpose

Provides controlled governance for exceptional situations requiring temporary use.

## Required Fields

- Emergency justification
- Mission
- Capability
- Requested scope
- Risk
- Evidence available
- Missing evidence
- Compensating controls
- Duration
- Conditions
- Authority
- Review trigger
- Termination condition
- Post-use review

Emergency circumstances should not create unlimited or indefinite authority.

---

# 17. Template 11-015 — Delegated Operational Authority Record

## Purpose

Records delegation of authorisation-related authority.

## Required Fields

- Delegating authority
- Delegated authority
- Scope
- Mission
- Capability
- Autonomy
- Conditions
- Duration
- Restrictions
- Escalation
- Revocation
- Record

Delegated authority must remain within the legal and organisational authority of the delegating party.

---

# 18. Template 11-016 — Authorisation Register

## Purpose

Provides the authoritative inventory of AI operational authorisations.

## Required Fields

- Authorisation ID
- Capability
- Mission
- Environment
- Autonomy
- Human authority
- Configuration
- Status
- Conditions
- Validity
- Review date
- Suspension status
- Reauthorisation status

Possible status values:

- proposed;
- under review;
- authorised;
- conditionally authorised;
- restricted;
- suspended;
- expired;
- withdrawn;
- retired.

---

# 19. Template 11-017 — Authorisation Monitoring Record

## Purpose

Monitors whether authorised conditions continue to be satisfied during operational use.

## Monitor

- configuration;
- mission;
- environment;
- autonomy;
- human control;
- performance;
- security;
- dependencies;
- incidents;
- conditions.

## Required Fields

- Time
- Condition
- Status
- Evidence
- Deviation
- Impact
- Action
- Authority
- Escalation

Monitoring should identify conditions that may invalidate authorisation before they become incidents where practical.

---

# 20. Template 11-018 — Authorisation Breach / Boundary Deviation Record

## Purpose

Records use or system behaviour outside an authorised boundary.

## Examples

- unauthorised mission;
- unauthorised geography;
- unauthorised autonomy;
- unauthorised configuration;
- exceeded environmental limit;
- unauthorised user;
- prohibited function;
- exceeded validity period.

## Required Fields

- Event ID
- Authorisation
- Boundary
- Deviation
- Detection
- Duration
- Consequence
- Immediate action
- Authority
- Investigation
- Risk reassessment
- Revalidation
- Reauthorisation

A boundary breach should be treated as a governance event even where no immediate harm occurs.

---

# 21. Template 11-019 — Authorisation Suspension / Withdrawal Record

## Purpose

Records suspension or withdrawal of operational authority.

## Trigger Categories

- unacceptable risk;
- material incident;
- loss of human control;
- security compromise;
- major configuration change;
- environmental change;
- evidence invalidation;
- supplier compromise;
- failed monitoring;
- expired authorisation.

## Required Fields

- Authorisation ID
- Trigger
- Decision
- Effective time
- Scope
- Immediate controls
- Notification
- Recovery criteria
- Revalidation
- Reauthorisation
- Authority

---

# 22. Template 11-020 — Reauthorisation Assessment

## Purpose

Determines whether existing operational authorisation should continue following change, incident, review or expiry.

## Assess

- mission;
- capability;
- configuration;
- data;
- environment;
- autonomy;
- human authority;
- security;
- supply chain;
- TEVV;
- incidents;
- residual risk.

## Required Fields

- Existing authorisation
- Change/event
- Impact
- Evidence
- New risk
- New conditions
- Revalidation status
- Decision
- Authority
- Validity

Reauthorisation should not be treated as a simple administrative renewal.

---

# 23. Template 11-021 — Authorisation Review Record

## Purpose

Provides periodic governance review of operational authorisation.

## Review Questions

1. Is the authorised capability unchanged?
2. Is the configuration unchanged?
3. Is the mission unchanged?
4. Is the operating environment unchanged?
5. Is the autonomy level unchanged?
6. Is human authority still effective?
7. Is the risk assessment current?
8. Is TEVV evidence still valid?
9. Have security conditions changed?
10. Have supplier dependencies changed?
11. Have incidents occurred?
12. Have environmental assumptions changed?
13. Are authorisation conditions being met?
14. Is continued authorisation justified?

---

# 24. Template 11-022 — Authorisation Evidence & Records Index

## Purpose

Provides an authoritative index of evidence supporting each authorisation.

## Required Fields

- Authorisation ID
- Evidence ID
- Evidence type
- Source
- Requirement
- Configuration
- Mission
- Environment
- Date
- Integrity
- Confidence
- Limitation
- Owner
- Retention
- Review relevance

The evidence index should allow an independent reviewer to reconstruct why the authorisation was granted and under what conditions.

---

# 25. Authorisation Object

Every consequential operational authorisation should explicitly define:

**AI Capability**
+
**Mission**
+
**Environment**
+
**Autonomy**
+
**Human Authority**

Changing any of these dimensions may change the validity of the authorisation.

For example:

**Same AI**
+
**Different Mission**
=
Potentially Different Risk and Authorisation

Likewise:

**Same AI**
+
**Same Mission**
+
**Different Environment**
=
Potentially Different Risk and Authorisation

---

# 26. Authorisation Decision Logic

A useful decision sequence is:

**Mission Need**
→ **Use Case**
→ **Risk**
→ **Requirements**
→ **Controls**
→ **TEVV**
→ **Evidence**
→ **Assurance**
→ **Human Authority**
→ **Operational Conditions**
→ **Authorisation Decision**

The decision should answer:

> **Is this capability sufficiently assured, sufficiently controlled and appropriately governed to be used for this specific mission, in this specific environment, at this specific autonomy level, under this specific human authority?**

---

# 27. Authorisation Conditions

Conditions should be measurable where practical.

Weak condition:

> Use responsibly.

Stronger condition:

> A2 recommendation-only mode is authorised while the designated supervisor is available, required sensor coverage remains above the defined threshold, and the system remains within the approved configuration.

Conditions should specify:

- what;
- who;
- when;
- where;
- threshold;
- monitoring;
- response to breach.

---

# 28. Authorisation and Risk Acceptance

Risk acceptance must identify:

- the risk;
- the uncertainty;
- the controls;
- the residual exposure;
- the accepting authority;
- the conditions;
- the review period.

A technical team should not implicitly accept operational risk merely because it declares a system ready.

Likewise:

> **Readiness evidence does not automatically constitute authority to accept operational risk.**

---

# 29. Authorisation and Human Authority

Authorisation should identify the human authority responsible for consequential decisions.

Where applicable, specify:

- decision-maker;
- supervisor;
- operator;
- intervention authority;
- escalation authority;
- incident authority.

The authorisation should remain valid only while the required human-control arrangements remain available.

---

# 30. Authorisation and Autonomy

The authorisation should state:

- permitted autonomy level;
- permitted functions;
- prohibited functions;
- transition conditions;
- supervision requirements;
- intervention requirements;
- safe-state requirements.

AI should not infer greater authority from:

- successful previous operation;
- system confidence;
- connectivity;
- operator behaviour;
- interaction with another AI;
- mission urgency.

Authority must remain explicitly granted.

---

# 31. Authorisation Under Degraded Conditions

Where degraded or disconnected operations are expected, the authorisation should specify:

- which degraded states are authorised;
- which autonomy level applies;
- what human control is required;
- what information may be unavailable;
- when the capability must restrict itself;
- when it must enter a safe state.

Example governance logic:

**Normal**
→ authorised autonomy

**Degraded**
→ reduced autonomy

**Severely degraded**
→ recommendation/restricted mode

**Loss of critical control**
→ safe state

The actual thresholds must be defined and tested for the capability.

---

# 32. Authorisation and AI-to-AI Interaction

Where AI systems interact, authorisation must define the authority boundaries between them.

One AI cannot grant another AI:

- operational authority;
- mission authority;
- targeting authority;
- access authority;
- expanded autonomy;

unless such authority has already been explicitly established through an authorised governance mechanism.

The governing principle is:

> **AI-to-AI interaction cannot create authority that does not already exist.**

---

# 33. Authorisation and Configuration

Operational authorisation should be linked to an identifiable configuration.

Where material, record:

- model version;
- model weights/version identifier;
- software;
- firmware;
- hardware;
- data;
- prompts/instructions;
- tools;
- external services;
- security controls.

An authorisation should not silently migrate to an materially different configuration.

---

# 34. Authorisation and Change

Material change may require:

- change classification;
- impact assessment;
- additional TEVV;
- revalidation;
- revised risk assessment;
- revised human-control assessment;
- revised autonomy assessment;
- reauthorisation.

The governing sequence is:

**Change**
→ **Impact**
→ **Test**
→ **Revalidate**
→ **Reauthorise where required**

---

# 35. Authorisation and Incident

An incident may invalidate assumptions underlying an authorisation.

Following a material incident, consider:

- immediate suspension;
- protective controls;
- investigation;
- evidence preservation;
- risk reassessment;
- corrective action;
- additional TEVV;
- revalidation;
- reauthorisation.

Incident closure does not automatically restore authorisation.

---

# 36. Authorisation Validity

Authorisation should have a defined validity concept.

Validity may depend on:

- time;
- configuration;
- mission;
- environment;
- autonomy;
- human authority;
- security posture;
- supplier status;
- operational assumptions.

Expiry should trigger review rather than automatic continuation.

---

# 37. Authorisation Status Model

D-AIGAAF recommends the following lifecycle:

**Proposed**
→ **Under Review**
→ **Assured**
→ **Authorised**
→ **Conditionally Authorised**
→ **Operationally Employed**
→ **Under Review**
→ **Reauthorised / Restricted / Suspended / Withdrawn**
→ **Retired**

The lifecycle makes clear that assurance and authorisation are different governance states.

---

# 38. Authorisation Evidence Package

For a consequential AI capability, the authorisation evidence package should normally include:

- authorisation application;
- scope and boundaries;
- risk assessment;
- residual risk decision;
- TEVV evidence;
- security assurance;
- human-control assessment;
- autonomy assessment;
- operational environment assessment;
- supply-chain assessment;
- workforce competence evidence;
- operating conditions;
- monitoring plan;
- incident history;
- exceptions;
- decision record.

---

# 39. Anti-Pattern — Approval by Availability

D-AIGAAF rejects:

**Capability Exists**
→ **Capability Tested**
→ **Capability Available**
→ **Capability Used**

Availability is not authority.

A capability may be technically available but:

- not authorised;
- outside its approved mission;
- outside its environmental boundary;
- operating at unauthorised autonomy;
- missing required human control.

---

# 40. Anti-Pattern — Blanket Authorisation

D-AIGAAF rejects vague authorisations such as:

> “The AI system is approved for operational use.”

For consequential capabilities, authorisation should specify:

**What**
+ **For which mission**
+ **Where**
+ **Under what conditions**
+ **At what autonomy**
+ **Under whose authority**
+ **With what restrictions**
+ **For how long**

---

# 41. Anti-Pattern — Authorisation by Technical Readiness

Technical readiness does not automatically establish:

- acceptable residual risk;
- meaningful human control;
- legal/policy compliance;
- operational suitability;
- environmental suitability;
- supply-chain acceptability.

Technical readiness is one input into the authorisation decision.

---

# 42. Anti-Pattern — Permanent Authorisation

AI capabilities can change through:

- software updates;
- model changes;
- data changes;
- environmental changes;
- threat changes;
- supplier changes;
- mission changes;
- human-system interaction changes.

Therefore:

> **Operational authorisation should be treated as a controlled governance state, not as an irreversible certification.**

---

# 43. Final Operational Authorisation Principle

D-AIGAAF treats operational authorisation as the formal bridge between assurance and operational authority.

The complete chain is:

**Mission Need**
→ **Risk**
→ **Requirements**
→ **Controls**
→ **TEVV**
→ **Evidence**
→ **Assurance**
→ **Human Authority**
→ **Conditions**
→ **Boundaries**
→ **Authorisation**
→ **Employment**
→ **Monitoring**
→ **Change / Incident**
→ **Revalidation**
→ **Reauthorisation**

The governing principle is:

> **No AI capability should acquire operational authority merely because it exists, performs well, is connected, is deployed, has previously been used successfully, or interacts with another authorised system. Operational authority must be explicitly granted, bounded, traceable, continuously monitored and capable of suspension or withdrawal when its governing assumptions no longer hold.**
