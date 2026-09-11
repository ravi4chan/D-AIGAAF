# 03-Risk and Autonomy Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 03 — Risk & Autonomy**.

These templates translate mission consequences, AI capability characteristics and operational conditions into structured assessments of risk, autonomy, human control and residual risk.

The central principle is:

> **The level of AI autonomy must be justified by mission consequence, operational context, system behaviour, human authority and demonstrated assurance—not by technical capability alone.**

The templates support:

- AI risk identification;
- consequence assessment;
- risk analysis;
- autonomy classification;
- human-control assessment;
- loss-of-control analysis;
- risk treatment;
- residual-risk assessment;
- risk acceptance;
- risk monitoring;
- autonomy boundaries;
- autonomy transitions;
- autonomy constraints;
- autonomy assurance;
- integrated risk-autonomy decisions.

---

# 2. Template Set

The recommended Risk & Autonomy template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-03-001 | AI Risk Assessment |
| D-AIGAAF-T-03-002 | AI Risk Register |
| D-AIGAAF-T-03-003 | Consequence Assessment |
| D-AIGAAF-T-03-004 | Autonomy Classification Assessment |
| D-AIGAAF-T-03-005 | Human Control Assessment |
| D-AIGAAF-T-03-006 | Loss-of-Control Assessment |
| D-AIGAAF-T-03-007 | Risk Treatment Plan |
| D-AIGAAF-T-03-008 | Residual Risk Assessment |
| D-AIGAAF-T-03-009 | Risk Acceptance Record |
| D-AIGAAF-T-03-010 | Risk Monitoring Record |
| D-AIGAAF-T-03-011 | Autonomy Boundaries Record |
| D-AIGAAF-T-03-012 | Autonomy Transition Assessment |
| D-AIGAAF-T-03-013 | Autonomy Constraints Record |
| D-AIGAAF-T-03-014 | Autonomy Assurance Assessment |
| D-AIGAAF-T-03-015 | Risk–Autonomy Decision Matrix |

---

# 3. Template 03-001 — AI Risk Assessment

## Purpose

Provides a structured assessment of risks associated with an AI capability and its intended use.

## Required Fields

### Identification

- Risk Assessment ID
- Capability ID
- Mission ID
- Use Case ID
- Assessment date
- Assessor
- Version
- Classification

### Risk Context

- intended purpose;
- operating environment;
- autonomy level;
- human role;
- affected people/assets;
- relevant dependencies.

### Risk Identification

Record:

- hazard;
- threat;
- failure mode;
- vulnerability;
- initiating condition;
- potential consequence.

### Risk Analysis

Assess:

- likelihood;
- consequence;
- exposure;
- detectability;
- reversibility;
- time to harm;
- uncertainty.

### Controls

- preventive controls;
- detective controls;
- corrective controls;
- human controls;
- technical controls;
- environmental controls.

### Conclusion

- inherent risk;
- controlled risk;
- residual risk;
- treatment;
- escalation;
- acceptance authority.

---

# 4. Template 03-002 — AI Risk Register

## Purpose

Provides an authoritative inventory of identified AI risks.

## Required Fields

- Risk ID
- Capability
- Mission
- Risk statement
- Risk category
- Owner
- Consequence
- Likelihood
- Inherent risk
- Controls
- Residual risk
- Treatment
- Assurance status
- Acceptance status
- Escalation
- Review date

## Risk Categories

Consider:

- safety;
- mission;
- operational;
- autonomy;
- human control;
- security;
- data;
- privacy;
- legal;
- supply chain;
- environmental;
- strategic;
- reputational.

The register should support both individual risk management and governance-level aggregation.

---

# 5. Template 03-003 — Consequence Assessment

## Purpose

Determines the potential consequences if an AI system produces an incorrect, unsafe, manipulated or unexpected output or action.

## Consequence Dimensions

### Human

- death;
- injury;
- civilian harm;
- psychological or other material harm.

### Mission

- mission failure;
- loss of operational advantage;
- incorrect decision;
- delayed action.

### Force

- fratricide;
- force protection;
- equipment loss.

### Physical

- infrastructure;
- property;
- environmental damage.

### Information

- confidentiality;
- integrity;
- availability;
- disclosure.

### Strategic

- escalation;
- sovereignty;
- diplomatic consequences;
- loss of trust.

## Required Assessment

Record:

- worst credible consequence;
- reasonably foreseeable consequence;
- affected population;
- reversibility;
- time to consequence;
- confidence in assessment.

---

# 6. Template 03-004 — Autonomy Classification Assessment

## Purpose

Determines the appropriate D-AIGAAF autonomy classification.

## D-AIGAAF Autonomy Levels

### A0 — No Meaningful AI Decision

AI does not materially influence a decision or action.

### A1 — Information / Observation

AI provides information, detection or observation without independently determining a consequential decision.

### A2 — Analysis / Recommendation

AI analyses information or recommends an option; a human makes the consequential decision.

### A3 — Human-Authorised Action

AI may enable or execute an action after explicit human authorisation.

### A4 — Supervised Autonomous Action

AI performs defined actions autonomously under active and meaningful human supervision.

### A5 — Independent Consequential Autonomy

AI independently performs consequential decisions or actions without immediate human authorisation.

## Assessment Fields

- observed system behaviour;
- intended behaviour;
- decision influence;
- action influence;
- autonomy level;
- evidence;
- human involvement;
- intervention capability;
- intervention latency;
- justification.

The assigned level should reflect actual system behaviour, not product terminology.

---

# 7. Template 03-005 — Human Control Assessment

## Purpose

Assesses whether meaningful human control exists for the intended use.

## Assessment Areas

### Understanding

Can the responsible human understand:

- system purpose;
- relevant outputs;
- limitations;
- uncertainty;
- operating conditions?

### Decision Authority

Can the human:

- accept;
- reject;
- modify;
- delay;
- escalate?

### Intervention

Can the human:

- intervene;
- override;
- suspend;
- terminate?

### Timing

Is sufficient time available for meaningful intervention?

### Competence

Does the human possess the required competence?

### Information

Does the human receive the information required for an informed decision?

### Workload

Can the human realistically exercise control under operational conditions?

## Conclusion

- meaningful control demonstrated;
- partially demonstrated;
- not demonstrated.

---

# 8. Template 03-006 — Loss-of-Control Assessment

## Purpose

Identifies circumstances in which human or organisational control over an AI capability may be lost.

## Loss-of-Control Scenarios

Consider:

- unexpected autonomy;
- automation bias;
- operator overload;
- communication loss;
- interface failure;
- software malfunction;
- model degradation;
- adversarial manipulation;
- sensor failure;
- conflicting commands;
- compromised update;
- tool misuse;
- AI-to-AI interaction;
- loss of authority;
- inability to intervene.

## Required Fields

- Scenario
- Trigger
- Detection mechanism
- Time to detect
- Time to intervene
- Available intervention
- Safe state
- Consequence
- Residual risk
- Required control
- TEVV requirement

---

# 9. Template 03-007 — Risk Treatment Plan

## Purpose

Defines how identified risks will be treated.

## Treatment Options

- avoid;
- reduce;
- control;
- transfer where appropriate;
- restrict;
- defer;
- accept;
- terminate.

## Required Fields

- Risk ID
- Treatment
- Control
- Owner
- Due date
- Expected risk reduction
- Verification method
- Evidence required
- Residual risk
- Acceptance authority

Risk treatment should consider whether reducing autonomy is a viable risk-control option.

---

# 10. Template 03-008 — Residual Risk Assessment

## Purpose

Determines whether risk remaining after controls is understood and acceptable to the appropriate authority.

## Required Fields

- Risk ID
- Initial risk
- Controls implemented
- Control effectiveness
- Evidence
- Remaining uncertainty
- Residual risk
- Risk owner
- Acceptance threshold
- Conditions
- Acceptance authority
- Review trigger

## Important Principle

Residual risk is not automatically acceptable because controls have been implemented.

The assessment must consider:

- control effectiveness;
- evidence quality;
- uncertainty;
- operational conditions;
- consequence.

---

# 11. Template 03-009 — Risk Acceptance Record

## Purpose

Records explicit acceptance of residual risk by an authorised human authority.

## Required Fields

### Risk

- Risk ID
- Capability
- Mission
- Use Case
- Risk statement
- Residual risk

### Evidence

- assessment;
- TEVV;
- assurance;
- incidents;
- monitoring.

### Decision

- accepted;
- accepted with conditions;
- rejected;
- deferred.

### Conditions

Record:

- operating limits;
- autonomy restrictions;
- monitoring;
- intervention;
- review date;
- expiry.

### Authority

- accepting authority;
- authority basis;
- date;
- signature/electronic approval.

Risk acceptance must never be inferred merely from deployment or continued use.

---

# 12. Template 03-010 — Risk Monitoring Record

## Purpose

Provides a structured record for monitoring changes in AI risk.

## Indicators

Monitor, where relevant:

- performance degradation;
- data drift;
- environment changes;
- adversarial activity;
- security incidents;
- human-control failures;
- intervention frequency;
- unexpected outputs;
- autonomy transitions;
- near misses;
- emerging threats.

## Required Fields

- Risk ID
- Indicator
- Baseline
- Threshold
- Current status
- Trend
- Trigger
- Action
- Owner
- Review date

Monitoring should support early intervention before risk becomes unacceptable.

---

# 13. Template 03-011 — Autonomy Boundaries Record

## Purpose

Defines the explicit limits on autonomous behaviour.

## Boundary Types

### Functional

What the AI may and may not do.

### Geographic

Where autonomous operation is permitted.

### Temporal

When autonomy is permitted.

### Decision

Which decisions may be influenced.

### Action

Which actions may be initiated or executed.

### Target / Object

Where applicable, which classes of objects or entities are within scope.

### Environmental

Conditions under which autonomy is valid.

### Human

Required supervision and intervention.

### Security

Security conditions and restrictions.

## Required Fields

- Boundary
- Rationale
- Enforcement mechanism
- Verification method
- Owner
- Breach response

---

# 14. Template 03-012 — Autonomy Transition Assessment

## Purpose

Assesses movement between autonomy levels.

Examples include:

- A1 → A2;
- A2 → A3;
- A3 → A4;
- A4 → A3;
- A4 → safe state.

## Required Assessment

- trigger;
- initiating condition;
- authorised transition;
- required human authority;
- system state;
- information requirements;
- intervention capability;
- risk;
- evidence;
- transition test;
- rollback behaviour.

## Principle

An autonomy transition is a governance event, not merely a software state change.

Transitions affecting consequential action should be explicitly authorised and tested.

---

# 15. Template 03-013 — Autonomy Constraints Record

## Purpose

Defines technical and procedural constraints that prevent autonomy from exceeding its authorised boundaries.

## Constraint Categories

- hard technical limits;
- software controls;
- access controls;
- geographic restrictions;
- time restrictions;
- mission restrictions;
- human confirmation;
- rate limits;
- action limits;
- escalation controls;
- safe-state controls.

## Required Fields

- Constraint ID
- Constraint
- Purpose
- Enforcement
- Verification
- Failure consequence
- Owner
- Monitoring
- Change control

Where feasible, critical constraints should be technically enforced rather than relying solely on operator memory or procedure.

---

# 16. Template 03-014 — Autonomy Assurance Assessment

## Purpose

Determines whether there is sufficient evidence that the authorised autonomy level can be safely and reliably maintained under specified conditions.

## Assessment Areas

### Behaviour

- intended behaviour;
- unintended behaviour;
- boundary behaviour.

### Human Control

- supervision;
- intervention;
- override;
- workload.

### Environment

- normal;
- degraded;
- disconnected;
- adversarial;
- variable conditions.

### Security

- manipulation;
- compromise;
- adversarial input;
- model integrity.

### Reliability

- failure rates;
- recovery;
- safe-state performance.

### Evidence

- TEVV;
- operational trials;
- red-team testing;
- monitoring;
- incidents.

## Conclusion

- assured;
- conditionally assured;
- insufficient assurance.

Assurance does not itself grant operational authority.

---

# 17. Template 03-015 — Risk–Autonomy Decision Matrix

## Purpose

Provides an integrated decision aid for determining whether proposed autonomy is proportionate to mission risk.

## Core Dimensions

| Dimension | Assessment |
|---|---|
| Mission consequence | Low / Medium / High / Critical |
| AI decision influence | Low → High |
| AI action influence | None → Consequential |
| Human control | Strong / Partial / Weak |
| Intervention time | Adequate / Limited / None |
| Environment | Controlled / Variable / Degraded / Adversarial |
| Reliability | Demonstrated / Conditional / Insufficient |
| Security | Assured / Conditional / Insufficient |
| Evidence | Strong / Moderate / Weak |
| Residual risk | Low / Medium / High / Critical |
| Proposed autonomy | A0–A5 |

## Decision Outcomes

- autonomy acceptable;
- autonomy acceptable with conditions;
- reduce autonomy;
- restrict employment;
- additional assurance required;
- not authorised for proposed autonomy.

The matrix is a decision-support tool and does not replace formal risk acceptance or operational authorisation.

---

# 18. Risk–Autonomy Relationship

D-AIGAAF uses the following principle:

**Higher Consequence**
+
**Higher Autonomy**
+
**Lower Human Intervention**
+
**Higher Environmental Uncertainty**
+
**Higher Adversarial Exposure**

should generally result in:

**Higher Assurance Requirements**
+
**Stronger Controls**
+
**More Explicit Authority**
+
**Stricter Operating Boundaries**

This is a governance principle rather than a mathematical formula.

---

# 19. Autonomy Is Contextual

The same AI capability may require different autonomy classifications in different missions.

For example, an AI system may be:

- A2 in one mission;
- A3 in another;
- restricted to A1 in a degraded environment.

The autonomy level should therefore be assessed against:

**AI Capability × Mission × Environment × Human Authority**

rather than against the model in isolation.

---

# 20. Consequence-Based Escalation

The following should trigger increased scrutiny:

- action affecting human life;
- action affecting civilians;
- irreversible action;
- high-speed action with limited intervention time;
- operation under severe uncertainty;
- operation under adversarial conditions;
- autonomous interaction with external systems;
- loss of communications;
- loss of human supervision;
- unexpected autonomy.

The appropriate response may include:

- lower autonomy;
- additional controls;
- additional testing;
- additional human supervision;
- restricted environment;
- temporary suspension.

---

# 21. Risk Appetite and AI

Organisations should define risk appetite for AI capabilities.

Risk appetite should address, as appropriate:

- safety;
- mission;
- security;
- legal;
- human control;
- autonomy;
- strategic risk.

However, organisational risk appetite must not be interpreted as permission to disregard mandatory legal, safety or operational requirements.

---

# 22. Uncertainty

Risk assessments should explicitly record uncertainty.

Examples:

- insufficient operational data;
- unknown adversarial behaviour;
- uncertain model performance;
- untested environmental conditions;
- incomplete failure data;
- uncertain human response;
- unknown interactions.

A high level of uncertainty should generally increase governance scrutiny rather than disappear into a numerical score.

---

# 23. Evidence Requirements

Risk and autonomy decisions should identify required evidence.

Potential evidence includes:

- risk assessments;
- system specifications;
- test reports;
- operational trials;
- adversarial evaluations;
- human-factors evaluations;
- incident history;
- monitoring records;
- configuration records;
- independent reviews.

Evidence should be linked to the relevant requirement, control and decision.

---

# 24. Relationship to Operational Authorisation

Risk and autonomy templates provide major inputs to Module 11.

The authorisation decision should establish:

- authorised autonomy;
- authorised mission;
- authorised environment;
- authorised human authority;
- residual risk;
- conditions;
- restrictions;
- monitoring requirements.

The governing distinction remains:

**Assured ≠ Authorised**

and:

**Authorised ≠ Ready**

and:

**Ready ≠ Deployed**

and:

**Deployed ≠ Employed**

---

# 25. Risk Escalation

Risk should be escalated when:

- residual risk exceeds authority;
- evidence becomes insufficient;
- assumptions fail;
- controls fail;
- autonomy increases;
- mission consequence changes;
- operating environment changes;
- security posture changes;
- human control degrades;
- material incidents occur.

Escalation should be documented.

---

# 26. Minimum Risk & Autonomy Package

For a consequential AI capability, the minimum package should normally contain:

- AI risk assessment;
- consequence assessment;
- autonomy classification;
- human-control assessment;
- loss-of-control assessment;
- risk treatment;
- residual-risk assessment;
- risk acceptance;
- autonomy boundaries;
- autonomy constraints;
- autonomy assurance;
- risk monitoring plan.

Additional assessment should be required according to mission consequence and system behaviour.

---

# 27. Review Questions

Before approving a proposed autonomy level, reviewers should ask:

1. What can the AI actually decide or do?
2. What happens if it is wrong?
3. How quickly can harm occur?
4. Can a human understand the AI output?
5. Can a human intervene in time?
6. Is the human actually authorised to intervene?
7. Is the system reliable in the intended environment?
8. Has the system been tested under degraded and adversarial conditions?
9. What happens if communications fail?
10. What happens if the AI behaves unexpectedly?
11. What controls constrain autonomy?
12. Can those controls fail?
13. Who accepts residual risk?
14. What evidence supports the decision?
15. What changes would require reauthorisation?

---

# 28. Anti-Pattern — Autonomy by Technical Capability

D-AIGAAF rejects:

**System Can Do It**
→ **System May Do It**

The correct sequence is:

**System Can Do It**
→ **Mission Requires It**
→ **Risk Is Understood**
→ **Controls Are Established**
→ **Human Authority Is Defined**
→ **TEVV Demonstrates Performance**
→ **Assurance Is Sufficient**
→ **Authority Approves**
→ **Autonomy Is Authorised Under Conditions**

---

# 29. Anti-Pattern — Human-in-the-Loop as a Checkbox

Simply placing a human somewhere in the workflow does not establish meaningful human control.

A meaningful human-control assessment must consider:

- information;
- understanding;
- authority;
- competence;
- workload;
- time;
- intervention capability;
- actual ability to influence the outcome.

A nominal human presence should not be treated as sufficient.

---

# 30. Anti-Pattern — Risk Score Without Consequence

A numerical risk score should not obscure severe consequences.

A low-frequency event may still require stringent controls where the consequence is catastrophic.

Risk assessment should therefore retain explicit visibility of:

**Consequence × Likelihood × Exposure × Uncertainty × Control Effectiveness**

---

# 31. Final Risk & Autonomy Principle

D-AIGAAF treats risk and autonomy as inseparable governance questions.

The fundamental relationship is:

**Mission**
→ **Consequence**
→ **Risk**
→ **Human Authority**
→ **Autonomy**
→ **Controls**
→ **TEVV**
→ **Assurance**
→ **Operational Conditions**
→ **Authorisation**
→ **Monitoring**

The final governing principle is:

> **The more consequential the action and the greater the autonomy, the stronger the evidence, controls, human authority and assurance required before operational employment.**

Autonomy is therefore not a feature that is simply switched on.

It is a **governed operational authority that must be justified, bounded, tested, assured, authorised and continuously monitored**.
