# 38 — Authorisation Operational Authority Escalation Thresholds and Triggers

## 1. Purpose

This document defines when an operational issue involving a Defence AI capability must be escalated to a higher level of human authority.

The purpose is to prevent consequential decisions from remaining at an inappropriate level when risk, uncertainty, autonomy, mission consequence, environmental conditions, security concerns or authority ambiguity exceed predefined thresholds.

Escalation is a governance control. It does not transfer authority to the AI system.

---

## 2. Core Principle

> **Material increases in consequence, uncertainty, autonomy, risk or authority ambiguity shall trigger proportionate escalation to an appropriately competent and authorised human decision-maker.**

The absence of an explicit escalation instruction shall not be interpreted as permission to continue higher-risk activity.

---

## 3. Escalation Model

D-AIGAAF uses the following conceptual escalation path:

**Operator → Supervisor → Operational AI Advisor / Specialist → Command or Operational Authority → Risk / Technical / Security / Assurance Authority → Authorising Authority**

The exact organisational structure may vary.

The principle remains that escalation shall reach the human authority possessing the required decision rights.

---

## 4. Escalation versus Delegation

Escalation and delegation are different.

### Escalation

Moves an issue to a higher or more appropriate decision authority because the existing authority cannot or should not resolve it.

### Delegation

Allows another authorised person to exercise defined decision rights on behalf of an authority.

Escalation does not automatically transfer accountability.

Delegation does not eliminate the need for escalation when predefined thresholds are exceeded.

---

## 5. Escalation Thresholds

Escalation thresholds should be defined according to:

- consequence;
- mission criticality;
- autonomy;
- risk;
- uncertainty;
- human-control availability;
- environmental conditions;
- security;
- configuration;
- data integrity;
- dependency criticality;
- legal or policy significance;
- operational scope.

Higher consequence and higher autonomy should generally require lower tolerance for unresolved uncertainty and stronger escalation requirements.

---

## 6. Risk-Based Escalation

Escalation should occur when:

- residual risk exceeds the accepted threshold;
- risk increases materially;
- a new risk is identified;
- existing controls become ineffective;
- risk ownership becomes unclear;
- the risk cannot be adequately assessed at the current authority level.

A change in risk should not be hidden by retaining the same operational status.

---

## 7. Consequence-Based Escalation

Escalation should occur when an AI-supported decision or action could materially affect:

- human life;
- physical safety;
- critical infrastructure;
- significant property;
- mission continuity;
- sensitive information;
- wider operational outcomes.

The greater the potential consequence, the greater the need for appropriately senior and competent human authority.

---

## 8. Autonomy-Based Escalation

Escalation should occur when:

- autonomy increases;
- the system approaches an autonomy boundary;
- an unexpected autonomy transition occurs;
- human supervision becomes ineffective;
- the system behaves as though operating at a higher autonomy level;
- an autonomous action has consequences beyond the authorised scope.

An AI system shall not escalate its own authority merely because operational circumstances become urgent.

---

## 9. Human-Control Escalation

Immediate escalation should be considered when:

- the responsible operator cannot understand the AI output sufficiently;
- intervention becomes difficult;
- override capability is unavailable;
- human workload becomes excessive;
- situational awareness is degraded;
- human supervision is interrupted;
- operator and system state become inconsistent;
- meaningful human control is no longer demonstrable.

Loss or degradation of human control should generally increase restrictions rather than increase AI autonomy.

---

## 10. Uncertainty-Based Escalation

Escalation should occur when uncertainty becomes material to a consequential decision.

Examples include:

- uncertain identification;
- conflicting sensor information;
- uncertain environmental state;
- uncertain system configuration;
- uncertain autonomy state;
- uncertain data integrity;
- uncertain dependency status;
- unexplained system behaviour;
- uncertainty about applicable authority.

AI systems should communicate material uncertainty rather than presenting uncertain conclusions as established facts.

---

## 11. Environmental Escalation

Escalation should occur when the operating environment:

- approaches a defined boundary;
- enters a warning condition;
- exceeds a demonstrated envelope;
- changes materially from the assurance basis;
- creates unexpected sensor conditions;
- causes communications degradation;
- creates navigation uncertainty;
- introduces significant electromagnetic disruption;
- becomes materially more adversarial.

The appropriate response may include increased monitoring, restriction, reduced autonomy, human control or suspension.

---

## 12. Security Escalation

Security-related escalation should occur when there is evidence or credible suspicion of:

- unauthorised access;
- model compromise;
- data poisoning;
- adversarial manipulation;
- software compromise;
- configuration tampering;
- supply-chain compromise;
- integrity loss;
- unexpected behaviour potentially caused by security events.

Security uncertainty should not be treated as a routine operational inconvenience.

---

## 13. Configuration Escalation

Escalation should occur where:

- configuration differs from the authorised baseline;
- model state is uncertain;
- software has changed unexpectedly;
- hardware has changed materially;
- safety or security controls differ;
- an external dependency has updated;
- update provenance is uncertain.

Material configuration uncertainty should prevent silent continuation of authority.

---

## 14. Data and Information Escalation

Escalation should occur when:

- data integrity is uncertain;
- sources conflict materially;
- data becomes stale;
- distribution drift is detected;
- critical data is unavailable;
- provenance cannot be established;
- information conditions materially differ from those assessed during assurance.

The decision-maker should understand whether the AI's evidence base remains appropriate for the mission.

---

## 15. Dependency Escalation

Escalation should occur when a critical dependency:

- becomes unavailable;
- changes materially;
- becomes untrusted;
- behaves unexpectedly;
- cannot be verified;
- creates a new operational risk.

Critical dependencies may include:

- communications;
- navigation;
- sensors;
- computing;
- external AI;
- data services;
- identity/security services;
- software components.

---

## 16. Mission and Scope Escalation

Escalation is required when proposed employment would materially change:

- mission;
- use case;
- function;
- operating area;
- environment;
- user population;
- duration;
- consequence;
- autonomy;
- human authority;
- configuration;
- data;
- dependencies.

Scope expansion should not be approved merely because the underlying AI system is unchanged.

---

## 17. Authorisation Boundary Escalation

Escalation should occur when:

- a boundary is approached;
- a boundary becomes uncertain;
- a boundary is crossed;
- a prohibited use is suspected;
- an operational condition conflicts with the authorisation;
- the current authority does not clearly cover the proposed activity.

The capability should remain within its existing authority until the appropriate human authority resolves the issue.

---

## 18. Performance-Based Escalation

Escalation should occur where:

- performance falls below an authorised threshold;
- mission effectiveness deteriorates;
- reliability declines;
- unexpected behaviour appears;
- false positives or false negatives materially increase;
- uncertainty increases materially;
- repeated near-failures occur;
- previously demonstrated behaviour is no longer reproducible.

Performance monitoring should therefore connect directly to governance action.

---

## 19. Incident-Based Escalation

Immediate escalation should be considered following:

- consequential AI error;
- loss of human control;
- unauthorised action;
- safety-control failure;
- unexpected autonomy;
- security compromise;
- significant boundary violation;
- serious near miss;
- material dependency failure.

The escalation level should reflect consequence and urgency.

---

## 20. Legal and Policy Escalation

Escalation should occur where:

- applicable law is unclear;
- policy requirements conflict;
- a new legal or policy requirement may affect authority;
- a proposed action raises unresolved legal concerns;
- an existing authorisation may no longer be legally or policy valid.

Operational urgency should not be treated as a substitute for lawful authority.

---

## 21. Escalation Levels

D-AIGAAF may use a four-level working model:

### E1 — Local Resolution

Issue can be safely resolved within existing authority and controls.

### E2 — Supervisory Escalation

Issue requires review by a supervisor or designated specialist.

### E3 — Command / Specialist Authority

Issue materially affects mission, risk, autonomy, security, human control or operational boundaries.

### E4 — Authorising Authority

Issue may alter or invalidate the basis of operational authority, including:

- material scope expansion;
- major autonomy change;
- material risk acceptance;
- serious loss of control;
- significant security compromise;
- reauthorisation;
- suspension or revocation.

These levels are a D-AIGAAF working construct and should be adapted to the adopting organisation.

---

## 22. Escalation Trigger Matrix

| Trigger | Minimum Response |
|---|---|
| Minor uncertainty | Monitor / local resolution |
| Increased uncertainty | Supervisory review |
| Material risk increase | Specialist or command escalation |
| Autonomy boundary approach | Supervisory review |
| Autonomy boundary violation | Immediate restriction and escalation |
| Human-control degradation | Immediate escalation |
| Security concern | Security escalation |
| Configuration uncertainty | Technical and operational escalation |
| Environment outside envelope | Restrict and escalate |
| Critical dependency failure | Continuity / command escalation |
| Consequential incident | Immediate incident escalation |
| Material scope expansion | Authorisation review |
| Material change | Change-control escalation |
| Unclear authority | Escalate before consequential action |
| Serious loss of control | Immediate protective action and senior escalation |

---

## 23. Escalation During Time-Critical Operations

Time pressure does not remove the need for escalation.

Where immediate escalation is impossible:

1. Apply the predefined protective response;
2. Remain within existing authority;
3. Reduce autonomy where appropriate;
4. Preserve human control where practicable;
5. Apply pre-authorised emergency procedures;
6. Escalate as soon as communications or authority become available;
7. Record the event and decision basis.

The objective is to manage urgency without creating uncontrolled authority.

---

## 24. Escalation During Disconnected Operations

Where communications are unavailable:

- predefined escalation arrangements should apply;
- local authority should remain within its defined scope;
- autonomous authority should not expand by default;
- local protective actions may be taken where pre-authorised;
- decisions should be recorded;
- unresolved issues should be escalated when communication is restored.

Restoration of communications does not automatically validate actions taken outside the authorised boundary.

---

## 25. AI-Generated Escalation Alerts

AI systems may identify and communicate escalation triggers.

Examples include:

- unusual behaviour;
- threshold exceedance;
- uncertainty;
- environmental boundary approach;
- performance degradation;
- security anomalies;
- dependency failure.

AI may **identify and recommend escalation**, but the authority to escalate operational decision rights remains human unless explicitly defined otherwise.

---

## 26. Escalation Failure

A governance failure occurs where:

- a material trigger is not recognised;
- an alert is suppressed;
- an escalation is delayed without justification;
- an issue is resolved by an unauthorised person;
- escalation reaches an authority without appropriate competence;
- responsibility becomes ambiguous;
- an AI system silently continues consequential activity despite a mandatory escalation condition.

Escalation failures should be treated as assurance and governance events.

---

## 27. Escalation and Protective Action

Escalation and protective action may occur simultaneously.

Where there is immediate risk, the organisation should not wait for a higher authority before applying a pre-authorised protective response.

Possible responses include:

**Continue with Monitoring → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

The protective response should be proportionate to the consequence and urgency.

---

## 28. Escalation Ownership

Every material escalation should identify:

- triggering party or system;
- receiving authority;
- decision owner;
- supporting technical authority;
- supporting assurance/security authority where applicable;
- time of escalation;
- required response;
- final decision.

An escalation should not disappear into an undefined organisational queue.

---

## 29. Escalation Record

A controlled **Authorisation Escalation Record** should capture:

| Field | Description |
|---|---|
| Escalation ID | Unique identifier |
| Capability | AI capability |
| Mission | Relevant mission |
| Trigger | Reason for escalation |
| Risk | Potential consequence |
| Current State | Operational state |
| Autonomy | Current/proposed autonomy |
| Human Authority | Current authority |
| Receiving Authority | Escalated authority |
| Immediate Action | Protective action |
| Decision | Decision made |
| Rationale | Decision basis |
| Outcome | Result |
| Follow-up | Required action |
| Status | Open/Closed |

---

## 30. Relationship with Revalidation and Reauthorisation

Repeated or material escalation events may indicate that the existing authorisation basis is no longer adequate.

Triggers may include:

- repeated boundary events;
- repeated performance degradation;
- recurring uncertainty;
- repeated loss of human control;
- recurring security anomalies;
- recurring authority conflicts;
- repeated emergency intervention.

Such patterns should trigger consideration of:

- additional assurance;
- change assessment;
- revalidation;
- reauthorisation;
- restriction;
- suspension.

---

## 31. Governance Review

Escalation data should be periodically reviewed to identify:

- recurring triggers;
- delayed responses;
- unclear thresholds;
- inappropriate delegation;
- human-factor problems;
- technical control weaknesses;
- environmental assumptions;
- training gaps;
- systemic governance weaknesses.

The objective is to improve the governance system, not merely resolve individual events.

---

## 32. Golden Thread

Escalation should remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Escalation/Incident → Change → Revalidation/Reauthorisation**

This ensures that repeated escalation events can improve future assurance, authorisation and operational controls.

---

## 33. Governance Questions

Before operational employment, the organisation should be able to answer:

1. What conditions require escalation?
2. Who receives each type of escalation?
3. What decisions can be made at each escalation level?
4. Which decisions require the authorising authority?
5. What happens when escalation is impossible?
6. What happens when human control is degraded?
7. What happens when the AI approaches or crosses an autonomy boundary?
8. What happens when security or data integrity becomes uncertain?
9. Can the AI identify and report an escalation trigger?
10. What protective action occurs while escalation is underway?
11. How are escalations recorded?
12. When does repeated escalation trigger revalidation or reauthorisation?

---

## 34. Core Rule

> **Defence AI operational issues shall be escalated whenever consequence, risk, uncertainty, autonomy, human-control degradation, environmental change, security concern, configuration uncertainty, dependency failure or authority ambiguity exceeds predefined thresholds. Escalation shall reach an appropriately competent and authorised human decision-maker, while immediate protective action shall remain available where delay could create unacceptable harm. Escalation shall not create additional AI authority, and unresolved escalation shall result in proportionate restriction, reduced autonomy, human control, safe state or suspension where required.**
