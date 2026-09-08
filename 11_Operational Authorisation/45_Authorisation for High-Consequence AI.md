# 45 — Authorisation for High-Consequence AI

## 1. Purpose

This document defines enhanced operational authorisation requirements for Defence AI capabilities whose use may create significant consequences for human life, physical safety, critical infrastructure, property, mission continuity or other material outcomes.

High-consequence AI requires stronger governance because errors, unexpected behaviour, loss of control or misuse may produce consequences that cannot be readily reversed.

---

## 2. Core Principle

> **The greater the potential consequence of Defence AI employment, the stronger the evidence, human authority, control, assurance, monitoring and operational restrictions required before and during authorised use.**

High consequence should therefore result in proportionate increases in governance rather than reliance on ordinary authorisation procedures alone.

---

## 3. High-Consequence Classification

A capability should be considered high consequence where an AI-supported or AI-enabled decision or action could materially affect:

- human life;
- physical safety;
- critical infrastructure;
- significant property;
- essential services;
- major mission outcomes;
- sensitive information;
- other consequential interests defined by applicable law or policy.

The adopting organisation should define its formal thresholds.

---

## 4. Consequence and Authority

Higher consequence should generally require:

- higher or more specifically designated authorising authority;
- stronger evidence;
- greater independence of review;
- clearer human decision rights;
- tighter operational boundaries;
- stronger fail-safe arrangements;
- increased monitoring;
- lower tolerance for unresolved uncertainty.

The exact authority level should be determined by applicable organisational governance.

---

## 5. Consequence Assessment

The authorisation package should assess:

- potential severity;
- affected persons or assets;
- reversibility;
- speed of consequence;
- scale;
- likelihood;
- uncertainty;
- ability to intervene;
- ability to recover;
- potential cascading effects.

The assessment should consider both intended and foreseeable unintended outcomes.

---

## 6. Consequence Categories

D-AIGAAF may use the following working categories:

### C1 — Limited Consequence

Failure produces limited and readily recoverable effects.

### C2 — Moderate Consequence

Failure may produce material operational or resource impact.

### C3 — Significant Consequence

Failure may materially affect safety, mission success, infrastructure or property.

### C4 — Severe Consequence

Failure may cause serious injury, significant loss or major mission impact.

### C5 — Critical Consequence

Failure may create potentially catastrophic or irreversible effects, including material risk to human life.

These are working D-AIGAAF constructs and should be mapped to applicable national, defence, legal and organisational terminology.

---

## 7. Consequence versus Autonomy

Consequence and autonomy should be assessed independently.

A low-autonomy AI system may still be high consequence if its recommendation directly informs a critical decision.

Similarly, higher autonomy may increase consequence because the opportunity for human intervention can decrease.

The authorisation assessment should therefore consider:

**Consequence × Autonomy × Human Control**

---

## 8. Human Authority

High-consequence AI should have clearly identified:

- authorising authority;
- operational authority;
- decision-maker;
- operator;
- supervisor;
- risk owner;
- technical authority;
- assurance authority;
- security authority;
- escalation authority.

Responsibility should not be distributed so widely that no individual or role can be identified as accountable.

---

## 9. Meaningful Human Control

Where human control is required, the organisation should demonstrate that the human can realistically:

- understand the relevant AI output;
- assess uncertainty;
- maintain situational awareness;
- make the required decision;
- intervene;
- override;
- stop or restrict the capability;
- escalate concerns.

The assessment should reflect actual operational conditions and time constraints.

---

## 10. Human Decision Quality

For consequential decisions, the organisation should avoid treating the human merely as a formal approval step.

The human should have:

- relevant competence;
- sufficient information;
- adequate time where practicable;
- authority to reject the AI output;
- ability to seek additional information;
- ability to escalate.

Automation bias and over-reliance on AI recommendations should be considered.

---

## 11. AI Uncertainty

High-consequence AI should communicate material uncertainty clearly.

The system should not:

- present uncertain information as fact;
- conceal conflicting information;
- imply unsupported precision;
- create unjustified confidence.

The authorisation should identify how uncertainty affects operational decision-making.

---

## 12. Evidence Requirements

Evidence should be proportionate to consequence.

High-consequence capabilities should generally require stronger evidence covering:

- technical performance;
- reliability;
- robustness;
- adversarial resilience;
- operational environment;
- human-AI interaction;
- security;
- autonomy and control;
- mission effectiveness.

Evidence should represent realistic operating conditions.

---

## 13. Independent Evaluation

High-consequence capabilities should receive appropriate independent evaluation.

Independence should be sufficient to challenge:

- developer claims;
- test assumptions;
- risk assessments;
- autonomy claims;
- human-control assumptions;
- environmental assumptions;
- security conclusions.

Independent challenge should occur before authority is granted where practicable.

---

## 14. Operational Environment

High-consequence authorisation should explicitly assess:

- nominal conditions;
- degraded conditions;
- disconnected operations;
- sensor limitations;
- communications disruption;
- navigation uncertainty;
- electromagnetic conditions;
- adversarial conditions;
- human workload.

The capability should not receive broad authority merely because it performs well under controlled conditions.

---

## 15. Operational Boundaries

High-consequence capabilities should have clearly defined:

- mission boundaries;
- geographic boundaries;
- environmental boundaries;
- autonomy boundaries;
- human-authority boundaries;
- configuration boundaries;
- data boundaries;
- dependency boundaries;
- consequence boundaries.

Where practicable, critical boundaries should be technically enforced.

---

## 16. Prohibited Use

The authorisation should explicitly identify prohibited uses.

These may include:

- unauthorised mission;
- unauthorised function;
- unauthorised autonomy;
- operation outside the demonstrated environment;
- operation without required human authority;
- use of an unauthorised configuration;
- use following a material security compromise;
- continued operation after mandatory suspension conditions.

---

## 17. Fail-Safe and Safe State

High-consequence capabilities should have credible mechanisms for:

- intervention;
- autonomy reduction;
- human control;
- safe-state transition;
- suspension;
- recovery.

Fail-safe mechanisms should be tested under representative conditions.

A fail-safe that exists only in documentation should not be treated as sufficient assurance.

---

## 18. Emergency Operation

Emergency arrangements should be defined before operational employment.

They should specify:

- who may take immediate protective action;
- what actions are pre-authorised;
- when autonomy must be reduced;
- when human control is required;
- when suspension is mandatory;
- how escalation occurs;
- how the event is recorded.

Emergency procedures should protect human authority rather than create unrestricted AI authority.

---

## 19. Monitoring

High-consequence capabilities should receive enhanced monitoring.

Monitoring may cover:

- performance;
- mission effectiveness;
- AI behaviour;
- uncertainty;
- human interaction;
- autonomy;
- environmental conditions;
- security;
- data integrity;
- dependencies;
- incidents;
- boundary conditions.

Thresholds should be established before employment.

---

## 20. Intervention Thresholds

The authorisation should define thresholds for:

**Continue → Increased Monitoring → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

Thresholds should be understandable to operators and authorities.

Where uncertainty prevents reliable assessment, the safer predefined state should normally apply.

---

## 21. Configuration Control

High-consequence authorisation should be tightly linked to configuration.

Material changes to:

- model;
- model state;
- software;
- hardware;
- safety controls;
- security controls;
- interfaces;
- data;
- dependencies;

should trigger change assessment.

Material changes should not automatically inherit the original authority.

---

## 22. Security Assurance

High-consequence capabilities should receive proportionate security assurance addressing:

- model integrity;
- data integrity;
- configuration integrity;
- adversarial manipulation;
- unauthorised access;
- dependency compromise;
- supply-chain risk;
- detection;
- response;
- recovery.

A serious security concern should be capable of triggering restriction or suspension.

---

## 23. Dependency Resilience

Critical dependencies should have:

- identified owners;
- criticality classification;
- failure conditions;
- fallback arrangements;
- monitoring;
- recovery procedures.

The capability should not silently increase autonomy or risk when a critical dependency fails.

---

## 24. Risk Acceptance

Residual risk should be:

- explicitly identified;
- supported by evidence;
- assigned to a risk owner;
- accepted by an appropriately authorised human authority;
- linked to conditions and controls.

High-consequence residual risk should not be accepted by an authority lacking the required mandate.

---

## 25. Decision Package

The high-consequence authorisation package should clearly present:

- mission;
- consequence;
- autonomy;
- human control;
- environment;
- evidence;
- uncertainty;
- risks;
- controls;
- boundaries;
- conditions;
- residual risk;
- monitoring;
- fail-safe;
- dependencies;
- legal/policy requirements;
- proposed decision.

The authorising authority should be able to understand the principal risks without reconstructing the case from technical documents.

---

## 26. Review Board

High-consequence capabilities should normally receive enhanced independent review.

Review should include appropriate expertise in:

- operations;
- AI;
- assurance;
- risk;
- security;
- human factors;
- legal/policy;
- technical systems.

The review should be sufficiently independent to challenge the authorisation basis.

---

## 27. Operational Readiness

Before each operational entry, high-consequence capabilities should confirm:

- current authorisation;
- configuration;
- environment;
- human authority;
- competence;
- autonomy;
- security;
- data;
- dependencies;
- fail-safe;
- monitoring;
- conditions.

Authorisation alone does not establish current readiness.

---

## 28. Deployment

Deployment should be controlled and traceable.

For high-consequence capabilities, staged or restricted deployment may be appropriate.

Deployment should verify:

- authorised configuration;
- environment;
- human authority;
- autonomy;
- safeguards;
- monitoring;
- communications;
- contingency arrangements.

---

## 29. Operational Employment

During employment:

- authorised boundaries remain enforceable;
- human authority remains active;
- AI uncertainty remains visible;
- autonomy remains controlled;
- monitoring remains active;
- consequential decisions remain traceable;
- intervention remains available where required.

Operational urgency should not silently expand authority.

---

## 30. Incident Response

A significant incident should trigger:

1. Immediate protective action;
2. Human authority notification;
3. Appropriate restriction or suspension;
4. Evidence preservation;
5. Investigation;
6. Risk reassessment;
7. Assurance review;
8. Revalidation or reauthorisation where required.

Incident closure should not automatically restore authority.

---

## 31. Revalidation and Reauthorisation

High-consequence capabilities should have clearly defined triggers for:

- additional assurance;
- revalidation;
- reauthorisation;
- restriction;
- suspension.

Triggers may include:

- material model change;
- unexpected behaviour;
- serious incident;
- security compromise;
- autonomy change;
- environment expansion;
- mission expansion;
- material dependency change;
- loss of human-control effectiveness.

---

## 32. Decision Traceability

Consequential activity should preserve:

**Context → AI Contribution → Human Assessment → Authority → Decision → Action → Outcome**

The level of traceability should reflect consequence and operational feasibility.

Where autonomous action is authorised, the authorisation and relevant system state should remain attributable to the human authority that approved the autonomy and operating conditions.

---

## 33. Governance Questions

Before granting authority, the organisation should be able to answer:

1. Why is AI required for this high-consequence function?
2. What is the maximum foreseeable consequence?
3. What autonomy is requested?
4. What human authority remains?
5. What evidence demonstrates safe and effective operation?
6. What remains uncertain?
7. What happens when the AI is wrong?
8. What happens when communications fail?
9. What happens when the environment changes?
10. What prevents unauthorised action?
11. Who can intervene or suspend the capability?
12. Who accepts residual risk?
13. What triggers revalidation or reauthorisation?
14. Can consequential decisions be reconstructed afterwards?

---

## 34. Golden Thread

High-consequence authorisation should remain connected to:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Incident/Change → Revalidation/Reauthorisation**

This ensures that stronger governance is maintained throughout the lifecycle rather than only at the initial approval stage.

---

## 35. Core Rule

> **Defence AI capabilities capable of producing high-consequence outcomes shall be subject to enhanced, proportionate operational authorisation. The level of evidence, independent challenge, human authority, control, monitoring, security, environmental assurance, configuration control and risk acceptance shall increase with consequence and autonomy. High-consequence AI shall operate only within clearly defined and enforceable boundaries, and material uncertainty, loss of human control, unexpected behaviour, security compromise or other conditions that undermine the authorisation basis shall trigger proportionate protective action, review, revalidation, reauthorisation or suspension.**
