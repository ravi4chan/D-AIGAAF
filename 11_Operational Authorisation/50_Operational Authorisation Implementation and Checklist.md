# 50 — Operational Authorisation Implementation and Checklist

## 1. Purpose

This document provides a practical implementation model for establishing and operating the D-AIGAAF Operational Authorisation function.

It converts the governance requirements in Module 11 into an implementable organisational process while preserving the principle that operational authority must remain explicit, bounded, evidence-based, human-accountable and continuously assured.

---

## 2. Core Principle

> **A Defence AI capability shall receive operational authority only through a defined governance process that establishes its mission, risk, assurance basis, operational boundaries, autonomy, human authority, conditions, readiness and accountability, and that continues to monitor and reassess the basis for that authority throughout employment.**

---

## 3. Implementation Objective

An organisation implementing D-AIGAAF should be able to demonstrate:

- who can authorise AI;
- what may be authorised;
- what evidence is required;
- how risk is assessed;
- how autonomy is governed;
- how human authority is maintained;
- how operational boundaries are defined;
- how readiness is established;
- how employment is monitored;
- how changes are governed;
- how incidents affect authority;
- how authority can be restricted, suspended or revoked;
- how lessons improve future decisions.

---

## 4. Implementation Architecture

The Operational Authorisation function should connect:

**Mission → Risk → Assurance → Authority → Readiness → Deployment → Employment → Monitoring → Change/Incident → Revalidation/Reauthorisation**

This should operate as an integrated governance process rather than a one-time approval.

---

## 5. Step 1 — Establish Governance Ownership

The organisation should designate:

- Authorising Authority;
- Command/Operational Authority;
- Risk Owner;
- Technical Authority;
- Assurance/TEVV Authority;
- Security Authority;
- OAIA;
- System Manager;
- Operator/User;
- audit/review function.

Decision rights should be documented.

---

## 6. Step 2 — Establish the AI Capability Register

Create and maintain the:

**Defence AI Capability Register (DAICR)**

For each capability, record at minimum:

- capability identifier;
- system/model;
- owner;
- purpose;
- lifecycle status;
- configuration baseline;
- mission/use-case relationship;
- autonomy;
- consequence;
- dependencies;
- assurance status;
- authorisation status.

---

## 7. Step 3 — Define the Authorisation Object

Every authorisation should identify:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

and, where material:

- configuration;
- data;
- dependencies;
- users;
- conditions;
- restrictions;
- validity period.

This prevents generic or ambiguous authority.

---

## 8. Step 4 — Define the Mission and Use Case

Establish:

- mission need;
- intended purpose;
- use case;
- operational context;
- mission success criteria;
- operational boundaries;
- assumptions;
- dependencies;
- prohibited use.

The organisation should establish why AI is required and what role it will perform.

---

## 9. Step 5 — Assess Consequence

Determine the potential consequence of failure or misuse.

The working D-AIGAAF consequence scale is:

- **C1 — Limited**
- **C2 — Moderate**
- **C3 — Significant**
- **C4 — Severe**
- **C5 — Critical**

Higher consequence should require proportionately stronger governance.

---

## 10. Step 6 — Assess Autonomy

Determine the requested autonomy:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

These are D-AIGAAF working constructs and should be mapped to applicable terminology.

---

## 11. Step 7 — Assess Human Control

Establish:

- who makes consequential decisions;
- what AI contributes;
- what the human must review;
- what uncertainty must be considered;
- who can intervene;
- who can override;
- who can suspend;
- how escalation occurs.

The organisation should demonstrate meaningful rather than nominal human control.

---

## 12. Step 8 — Assess the Operational Environment

Establish the demonstrated operating envelope across relevant:

- physical conditions;
- terrain;
- weather;
- illumination;
- sensors;
- communications;
- navigation;
- electromagnetic conditions;
- information environment;
- computing;
- human conditions;
- adversarial conditions.

Operation outside the demonstrated envelope should require predefined controls.

---

## 13. Step 9 — Establish Risk

Assess:

- consequence;
- likelihood;
- uncertainty;
- human-control risk;
- autonomy risk;
- environmental risk;
- security risk;
- data risk;
- dependency risk;
- supply-chain risk;
- mission risk.

Identify controls and residual risk.

---

## 14. Step 10 — Establish Assurance Evidence

Compile evidence covering applicable:

1. Technical Performance;
2. Reliability and Robustness;
3. Adversarial Resilience;
4. Operational Environment;
5. Human-AI Interaction;
6. Security and Integrity;
7. Autonomy and Control;
8. Mission Effectiveness.

Evidence should demonstrate the specific capability in the proposed context.

---

## 15. Step 11 — Conduct Independent Challenge

Before high-consequence or material authorisation decisions, obtain proportionate independent challenge.

Challenge should examine:

- evidence;
- assumptions;
- risk;
- autonomy;
- human control;
- security;
- environment;
- boundaries;
- dependencies;
- residual risk.

Material unresolved concerns should be visible to the decision-maker.

---

## 16. Step 12 — Define Operational Boundaries

Define:

**Permitted → Restricted → Prohibited**

across:

- mission;
- function;
- environment;
- geography;
- time;
- autonomy;
- human authority;
- configuration;
- data;
- dependencies;
- consequence.

Technical capability should not be interpreted as operational permission.

---

## 17. Step 13 — Define Conditions and Restrictions

Authorisation conditions may address:

- supervision;
- autonomy;
- environment;
- configuration;
- monitoring;
- data;
- security;
- dependencies;
- user competence;
- duration;
- geographic scope;
- contingency;
- reporting.

Mandatory conditions should be treated as part of the authority itself.

---

## 18. Step 14 — Determine Residual Risk Acceptance

Document:

- residual risk;
- risk owner;
- controls;
- uncertainty;
- limitations;
- acceptance authority;
- acceptance rationale;
- review triggers.

Only an appropriately authorised human authority should accept residual risk.

---

## 19. Step 15 — Prepare the Authorisation Decision Package

The package should contain:

- executive summary;
- capability;
- mission/use case;
- environment;
- consequence;
- autonomy;
- human authority;
- risk;
- assurance evidence;
- TEVV;
- security;
- data;
- dependencies;
- configuration;
- fail-safe;
- boundaries;
- prohibited use;
- conditions;
- restrictions;
- residual risk;
- monitoring;
- incidents/lessons;
- legal/policy considerations;
- evidence gaps;
- proposed decision.

---

## 20. Step 16 — Apply Authorisation Gates

Minimum progression:

**Mission Defined → Requirements Defined → Risk Assessed → Controls Implemented → TEVV Completed → Environment Assessed → Assurance Determined → Authorisation Granted → Readiness Confirmed → Deployment Accepted → Employment Permitted**

A failed mandatory gate should prevent progression unless an appropriately authorised exception or alternative governance decision exists.

---

## 21. Step 17 — Record the Decision

Create the controlled:

**Operational Authorisation Record**

The record should identify:

- authority;
- scope;
- conditions;
- restrictions;
- evidence;
- residual risk;
- configuration;
- validity;
- review date;
- suspension triggers;
- revocation triggers;
- decision rationale.

No operational authority should exist solely through informal communication.

---

## 22. Step 18 — Establish Operational Readiness

Before employment, confirm:

- authorisation remains valid;
- configuration matches the authorised baseline;
- environment is suitable;
- human authority is available;
- required personnel are competent;
- autonomy is correct;
- security is acceptable;
- data is suitable;
- dependencies are available;
- fail-safe is available;
- monitoring is active.

**Authorised ≠ Ready**

---

## 23. Step 19 — Control Deployment

Deployment should verify:

- configuration;
- environment;
- human authority;
- autonomy;
- safeguards;
- communications;
- monitoring;
- contingency arrangements.

Deployment should not silently expand authority.

---

## 24. Step 20 — Govern Operational Employment

During employment:

- remain within authorised boundaries;
- maintain human authority;
- monitor performance;
- monitor AI behaviour;
- monitor uncertainty;
- monitor environment;
- monitor security;
- monitor dependencies;
- record consequential decisions and actions.

---

## 25. Step 21 — Manage Dynamic Conditions

When conditions change, apply proportionate response:

**Continue → Monitor Closely → Restrict → Reduce Autonomy → Human Control → Contingency → Safe State → Suspend**

Changes in conditions should not create implied AI authority.

---

## 26. Step 22 — Manage Incidents

For material incidents:

1. Protect people and assets;
2. Apply immediate authorised protective measures;
3. Notify appropriate authorities;
4. Restrict or suspend where required;
5. Preserve evidence;
6. Investigate;
7. Reassess risk;
8. Review assurance;
9. Determine revalidation/reauthorisation requirements;
10. Capture lessons.

---

## 27. Step 23 — Manage Changes

Assess changes to:

- model;
- model state;
- software;
- hardware;
- data;
- configuration;
- interfaces;
- security;
- dependencies;
- mission;
- environment;
- autonomy;
- human authority.

Classify the change and determine whether additional TEVV, revalidation or reauthorisation is required.

---

## 28. Step 24 — Monitor Authorisation Health

Track:

- authorisation status;
- readiness;
- evidence currency;
- risk;
- autonomy;
- human control;
- boundaries;
- incidents;
- changes;
- restrictions;
- expiry;
- revalidation;
- reauthorisation.

The dashboard informs authority but does not create authority.

---

## 29. Step 25 — Review and Renew

Authorisations should be reviewed:

- periodically;
- after material change;
- after serious incident;
- after major environmental change;
- after significant security event;
- when evidence becomes outdated;
- when autonomy changes;
- when mission scope changes;
- when dependencies change;
- when legal or policy requirements change.

Renewal should not be automatic where the authorisation basis has materially changed.

---

## 30. Step 26 — Suspend, Revoke or Close

Authority should have defined end states:

- Restricted;
- Suspended;
- Revoked;
- Expired;
- Closed;
- Retired.

The organisation should prevent unintended continuation after authority ends.

---

## 31. Step 27 — Capture Lessons

Capture:

- incidents;
- near misses;
- unexpected behaviour;
- successful controls;
- failed assumptions;
- environmental observations;
- human factors;
- assurance findings;
- governance weaknesses.

Feed validated lessons back into:

- requirements;
- controls;
- TEVV;
- training;
- authorisation conditions;
- risk;
- future system design.

---

## 32. Minimum Operational Authorisation Checklist

Before granting operational authority, confirm:

### Governance

- [ ] Authorising Authority identified
- [ ] Operational Authority identified
- [ ] Risk Owner identified
- [ ] Technical Authority identified
- [ ] Assurance/TEVV Authority identified
- [ ] Security Authority identified
- [ ] OAIA identified where required

### Mission

- [ ] Mission defined
- [ ] Use case defined
- [ ] Intended purpose defined
- [ ] Success criteria defined
- [ ] Operational boundaries defined
- [ ] Prohibited use defined

### Risk and Autonomy

- [ ] Consequence assessed
- [ ] Risk assessed
- [ ] Residual risk identified
- [ ] Risk acceptance authority identified
- [ ] Autonomy level defined
- [ ] Autonomy boundaries defined
- [ ] Human-control arrangements demonstrated

### Environment

- [ ] Operating envelope defined
- [ ] Environmental suitability assessed
- [ ] Degraded conditions assessed
- [ ] Disconnected conditions assessed where relevant
- [ ] Adversarial conditions assessed where relevant

### Assurance

- [ ] TEVV completed
- [ ] Evidence sufficient
- [ ] Evidence traceable
- [ ] Material limitations documented
- [ ] Uncertainty documented
- [ ] Independent challenge completed where required

### System and Security

- [ ] Configuration baseline established
- [ ] Data requirements satisfied
- [ ] Security assessment completed
- [ ] Dependencies identified
- [ ] Supply-chain risks assessed
- [ ] Fail-safe demonstrated

### Authority

- [ ] Conditions defined
- [ ] Restrictions defined
- [ ] Suspension triggers defined
- [ ] Revocation triggers defined
- [ ] Validity period defined
- [ ] Review triggers defined
- [ ] Emergency authority defined where required

### Readiness and Deployment

- [ ] Operational readiness confirmed
- [ ] Personnel competent
- [ ] Environment currently suitable
- [ ] Configuration verified
- [ ] Monitoring active
- [ ] Deployment accepted

### Records

- [ ] Decision package complete
- [ ] Authorisation Record complete
- [ ] Risk acceptance recorded
- [ ] Evidence register complete
- [ ] Decision rationale recorded
- [ ] Relevant authority register updated

---

## 33. Minimum Employment Checklist

Before each operational employment, confirm:

- [ ] Current authorisation
- [ ] Correct mission
- [ ] Correct environment
- [ ] Correct configuration
- [ ] Correct autonomy
- [ ] Required human authority available
- [ ] Competent personnel available
- [ ] Security status acceptable
- [ ] Data/information suitable
- [ ] Dependencies available
- [ ] Fail-safe available
- [ ] Monitoring active
- [ ] Restrictions understood
- [ ] Emergency procedures available

---

## 34. Minimum Suspension Checklist

Where suspension is required:

- [ ] Immediate protective action taken
- [ ] Operational authority notified
- [ ] Capability restricted or stopped
- [ ] Human control established where possible
- [ ] Evidence preserved
- [ ] Incident recorded
- [ ] Risk reassessed
- [ ] Assurance impact assessed
- [ ] Revalidation requirement determined
- [ ] Reauthorisation requirement determined
- [ ] Restoration authority identified
- [ ] Restoration conditions defined

---

## 35. Minimum Reauthorisation Checklist

Before reauthorisation following material change or incident:

- [ ] Change/incident understood
- [ ] Root cause assessed where applicable
- [ ] Risk reassessed
- [ ] Configuration verified
- [ ] Human-control assessment updated
- [ ] Autonomy assessment updated
- [ ] Environment assessment updated
- [ ] Security assessment updated
- [ ] TEVV completed as required
- [ ] Evidence updated
- [ ] Conditions revised where necessary
- [ ] Residual risk reassessed
- [ ] Independent challenge completed where required
- [ ] New decision package prepared
- [ ] New authorisation decision recorded

---

## 36. Implementation Maturity

Organisations may implement D-AIGAAF progressively.

### Level 1 — Foundational

- authorities identified;
- basic register established;
- authorisation records introduced;
- basic risk and assurance requirements defined.

### Level 2 — Controlled

- formal gates;
- operational boundaries;
- readiness;
- monitoring;
- change control;
- suspension mechanisms.

### Level 3 — Assured

- independent challenge;
- integrated TEVV;
- continuous assurance;
- decision-quality assessment;
- structured lessons management.

### Level 4 — Adaptive

- portfolio governance;
- predictive indicators;
- systematic cross-capability learning;
- dynamic authorisation management;
- mature resilience and continuity.

Maturity should describe governance capability, not imply that higher maturity automatically authorises higher-risk AI.

---

## 37. Implementation Priorities

Organisations should prioritise:

1. Human authority;
2. Consequence and risk;
3. Operational boundaries;
4. Evidence and assurance;
5. Autonomy control;
6. Fail-safe and emergency arrangements;
7. Configuration and change control;
8. Monitoring;
9. Suspension and revocation;
10. Continuous learning.

---

## 38. Implementation Anti-Patterns

Avoid:

- authorisation based solely on technical performance;
- generic approval of an AI model for unlimited use;
- treating deployment as authorisation;
- treating readiness as authorisation;
- assuming human presence equals human control;
- treating AI confidence as certainty;
- allowing autonomy to increase automatically during degraded operations;
- allowing technical capability to define operational permission;
- treating successful previous use as automatic approval for new missions;
- allowing undocumented authority;
- relying on informal communication;
- allowing metrics to replace judgement;
- treating incident-free operation as proof of safety;
- allowing material changes to inherit authority without assessment.

---

## 39. Final Authorisation Decision Test

Before granting authority, the decision-maker should be able to answer:

> **Do we understand what this capability is being authorised to do, where and under what conditions it may do it, what autonomy it has, who remains accountable, what evidence supports the decision, what risks remain, what controls are available, what happens when conditions change, and how authority can be restricted or withdrawn?**

If material answers remain unknown, the organisation should determine whether additional assurance, restriction, revalidation or non-authorisation is appropriate.

---

## 40. D-AIGAAF Operational Authorisation Flow

The complete operational authorisation process can be represented as:

**1. Mission Need**
↓
**2. Use Case**
↓
**3. Consequence**
↓
**4. Risk & Autonomy**
↓
**5. Human Authority**
↓
**6. Operational Environment**
↓
**7. Requirements & Controls**
↓
**8. TEVV**
↓
**9. Evidence & Assurance**
↓
**10. Boundaries & Conditions**
↓
**11. Risk Acceptance**
↓
**12. Authorisation Decision**
↓
**13. Readiness**
↓
**14. Deployment**
↓
**15. Operational Employment**
↓
**16. Continuous Monitoring**
↓
**17. Change / Incident / Emerging Risk**
↓
**18. Revalidation**
↓
**19. Reauthorisation**
↓
**20. Retirement / Decommissioning**

---

## 41. Golden Thread

The final implementation should preserve the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Learning → Revalidation/Reauthorisation**

Every material operational authority decision should be traceable through this chain.

---

## 42. Core Rule

> **D-AIGAAF Operational Authorisation shall be implemented as a continuous governance process rather than a one-time approval. An AI capability shall progress from mission definition through risk, autonomy, human authority, environmental assessment, controls, TEVV, evidence, assurance, authorisation, readiness, deployment and operational employment only through defined decision gates and accountable human authority. During employment, monitoring, incident management, change control, lessons learning, revalidation and reauthorisation shall maintain the validity of the authorisation basis. No technical capability, successful previous use, operational urgency, system availability or organisational status shall create implied authority beyond the defined and currently supported mission, environment, autonomy, human authority, configuration, conditions and boundaries.**
