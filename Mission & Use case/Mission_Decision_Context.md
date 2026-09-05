# Mission Decision Context

## 1. Purpose

Mission Decision Context defines the circumstances in which an AI capability contributes information, analysis, recommendations or actions to an operational decision.

It establishes what decision is being supported, who holds authority, what information is available, what constraints apply and what consequences may follow.

---

## 2. Core Principle

AI governance must consider not only what the AI does, but **what human decision the AI influences and what operational action may follow**.

The governing relationship is:

**AI Output → Human Assessment → Human Decision → Operational Action → Consequence**

AI output does not automatically become a human decision, and a human decision does not automatically constitute command authority.

---

## 3. Decision Identification

Each consequential AI use case should identify the decision or activity being supported.

The decision context should define:

- decision purpose;
- decision owner;
- decision authority;
- information required;
- AI contribution;
- human contribution;
- available alternatives;
- time available;
- potential consequences.

---

## 4. Decision Objective

The decision objective should state what the decision-maker is trying to achieve.

It should be expressed independently of the AI where practical.

For example:

- identify relevant information;
- prioritise competing activities;
- allocate resources;
- assess possible courses of action;
- detect an emerging condition;
- determine whether further investigation is required.

The objective should not be defined merely as “use AI.”

---

## 5. Decision Authority

The responsible human authority should be explicitly identified.

This may include:

- operational commander;
- delegated decision-maker;
- technical authority;
- duty officer;
- authorised operator;
- other legally or organisationally empowered authority.

Authority should derive from applicable law, policy, doctrine and organisational delegation.

D-AIGAAF does not create command authority.

---

## 6. AI Contribution

The AI contribution should be clearly defined.

Possible contributions include:

- information presentation;
- detection;
- classification;
- prediction;
- analysis;
- prioritisation;
- recommendation;
- planning support;
- execution of authorised predefined actions.

The contribution should correspond to the authorised autonomy level.

---

## 7. Human Contribution

The human role should specify what the decision-maker is expected to do.

This may include:

- review information;
- assess context;
- challenge AI output;
- consider alternatives;
- seek additional information;
- accept or reject a recommendation;
- authorise an action;
- override AI behaviour;
- terminate or suspend AI operation.

Human presence alone is not sufficient to establish meaningful human control.

---

## 8. Information Available to the Decision-Maker

The decision context should identify the information available to the human decision-maker.

This may include:

- AI output;
- source data;
- sensor information;
- intelligence;
- human reporting;
- operational status;
- environmental information;
- communications status;
- relevant policy or rules.

The decision-maker should understand important limitations in the information presented.

---

## 9. Information Quality

Decision context should consider whether information may be:

- incomplete;
- stale;
- contradictory;
- uncertain;
- manipulated;
- unavailable.

Where information quality is degraded, the AI and human decision process should have defined responses.

---

## 10. Time Available

The available decision window should be established where relevant.

Consider:

- time to detect;
- time to analyse;
- time to review;
- time to decide;
- time to act;
- time available for intervention.

An AI system may provide a technically useful recommendation but still be unsuitable if the human cannot meaningfully evaluate it within the available time.

---

## 11. Consequence

The potential consequence of the decision should be identified.

Consider consequences involving:

- human life;
- serious injury;
- mission failure;
- critical infrastructure;
- sensitive information;
- strategic effects;
- property;
- friendly forces;
- civilian populations.

Higher-consequence decisions require proportionately stronger controls, evidence and human authority.

---

## 12. Decision Criticality

Decision criticality should be distinguished from model performance.

A highly accurate AI system may still require strong governance if the decision it influences has severe consequences.

Decision criticality should therefore inform:

- required assurance;
- human authority;
- autonomy;
- escalation;
- monitoring;
- authorisation conditions.

---

## 13. Human-AI Decision Relationship

The framework should explicitly distinguish:

**AI Output**

from

**Human Decision**

from

**Command Authority**

These are separate concepts.

A system may generate a recommendation without having authority to determine the resulting action.

---

## 14. Decision Independence

For consequential decisions, the human decision-maker should retain the ability to:

- consider information other than the AI output;
- reject the AI recommendation;
- request additional information;
- select an alternative course of action;
- escalate the decision.

The design should avoid making the AI recommendation the de facto mandatory decision.

---

## 15. AI Recommendation Rejection

Where appropriate, the decision process should permit recording why a significant AI recommendation was rejected or bypassed.

Possible reasons include:

- contradictory information;
- insufficient confidence;
- known limitation;
- operational context;
- policy constraint;
- human judgement;
- alternative intelligence;
- unacceptable risk.

Recording should be proportionate to consequence and operational burden.

---

## 16. AI Recommendation Acceptance

Where a significant AI recommendation is accepted, the decision process should preserve sufficient information to establish:

- what the AI recommended;
- relevant uncertainty or limitations;
- what human authority accepted it;
- what action followed;
- what outcome occurred.

This supports accountability and learning.

---

## 17. Operational AI Advisor

For complex or high-consequence use cases, an Operational AI Advisor may support the decision-maker.

The OAIA may help explain:

- AI capabilities;
- limitations;
- uncertainty;
- system behaviour;
- relevant evidence;
- risk;
- autonomy;
- security concerns;
- appropriate escalation.

The OAIA does not replace command authority.

**OAIA advises; authorised human authority decides.**

---

## 18. Decision Context and Autonomy

The decision context should identify the relationship between AI autonomy and human authority.

Higher autonomy may reduce the opportunity for direct human intervention and therefore requires stronger evidence that:

- behaviour is bounded;
- authority is explicitly defined;
- failure responses are understood;
- intervention mechanisms work;
- unauthorised actions are prevented.

Autonomy should never be inferred merely from technical capability.

---

## 19. Decision Context Under Degraded Conditions

Decision context should account for conditions such as:

- communications loss;
- sensor degradation;
- reduced information;
- cyber attack;
- environmental degradation;
- high workload;
- reduced staffing.

The framework should establish what decision authority remains available under such conditions.

---

## 20. Decision Context and Fail-Safe

Where serious failure occurs, the decision context should define:

- who can suspend the capability;
- who can invoke fail-safe mechanisms;
- what conditions require immediate action;
- what happens to human authority;
- what happens to ongoing AI activity;
- how recovery is managed.

Where delay could create unacceptable harm, pre-authorised emergency protective procedures may permit immediate intervention.

---

## 21. Decision Context and Rules

The decision process must remain consistent with applicable:

- law;
- government policy;
- defence policy;
- military doctrine;
- rules and directives;
- organisational authorities.

D-AIGAAF does not determine substantive rules governing the use of force or other legally regulated activities.

It provides governance for how AI participates in decision-making within those existing authorities.

---

## 22. Decision Alternatives

Where practical, the decision context should identify alternatives to AI-supported decision-making.

Alternatives may include:

- human-only assessment;
- another information source;
- another AI capability;
- manual process;
- delayed decision;
- escalation.

This helps establish whether AI is genuinely improving the mission rather than merely adding complexity.

---

## 23. Decision Dependencies

The decision process may depend on:

- communications;
- sensors;
- external data;
- other systems;
- human operators;
- positioning;
- infrastructure;
- external services.

Critical dependencies should be identified and their failure consequences understood.

---

## 24. Decision Quality

Where appropriate, evaluation should assess whether AI changes human decision quality.

Relevant measures may include:

- accuracy of decisions;
- decision time;
- missed information;
- inappropriate reliance;
- automation bias;
- over-trust;
- under-trust;
- workload;
- consistency;
- ability to identify AI errors.

The objective is not simply to measure AI output quality, but the quality of the resulting human decision process.

---

## 25. Automation Bias

Users may place excessive confidence in AI recommendations.

Decision context should therefore consider risks such as:

- accepting recommendations without adequate review;
- ignoring contradictory evidence;
- assuming high-confidence output is correct;
- treating AI output as authoritative.

Human control mechanisms should be designed and evaluated against these risks.

---

## 26. Accountability

For consequential decisions, the decision context should allow reconstruction of:

- what information was available;
- what AI produced;
- what uncertainty was communicated;
- who reviewed the output;
- who made the decision;
- what authority they held;
- what action followed;
- what outcome occurred.

The purpose is accountability and learning, not retrospective attribution of blame alone.

---

## 27. Decision Records

The level of recording should be proportionate to consequence.

A significant decision record may include:

- use case;
- date and time;
- operational context;
- AI output;
- relevant confidence or uncertainty;
- human decision;
- decision authority;
- human override or rejection;
- action;
- outcome;
- incident or exception information.

Sensitive operational information should be protected appropriately.

---

## 28. Decision Context Changes

The decision context should be reassessed when:

- the mission changes;
- the decision changes;
- consequence changes;
- autonomy changes;
- human control changes;
- operating conditions change;
- new information sources are introduced;
- AI behaviour changes;
- policy or legal requirements change.

Material changes may require revalidation or reauthorisation.

---

## 29. Mission Decision Context Record

A controlled record should contain, as applicable:

- mission;
- use case;
- decision/activity;
- decision objective;
- decision authority;
- AI role;
- human role;
- information sources;
- information limitations;
- decision window;
- consequence;
- autonomy;
- operational environment;
- constraints;
- alternatives;
- dependencies;
- escalation;
- fail-safe arrangements;
- accountability requirements;
- review triggers.

---

## 30. Minimum Mission Decision Context Requirements

For consequential AI use cases, D-AIGAAF should require:

1. Identification of the supported decision or activity.
2. Definition of the decision objective.
3. Identification of authorised human decision authority.
4. Clear definition of the AI contribution.
5. Clear definition of the human contribution.
6. Assessment of available information and its limitations.
7. Definition of relevant decision time constraints.
8. Assessment of decision consequence and criticality.
9. Explicit separation of AI output, human decision and command authority.
10. Assessment of meaningful human control where required.
11. Consideration of automation bias and inappropriate reliance.
12. Identification of relevant decision alternatives.
13. Identification of critical dependencies.
14. Defined escalation and fail-safe arrangements.
15. Proportionate decision recording.
16. Reassessment following material change or incident.

---

## 31. Relationship With D-AIGAAF

This module connects directly with:

- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Mission_Success_Criteria.md`
- `02 Mission & Use Case/Operational_Scenarios.md`
- `02 Mission & Use Case/Use_Case_Register.md`
- `03 Risk & Autonomy`
- `08 Human Authority`
- `09 TEVV`
- `11 Operational Authorisation`
- `12 Operational Employment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `16 Audit & Evidence`

It provides the decision-level bridge between the defined use case and human authority.

---

## 32. Summary

Mission Decision Context establishes how AI participates in an operational decision without obscuring who holds authority.

It ensures that D-AIGAAF considers:

- what decision is being supported;
- who is authorised to decide;
- what information is available;
- what the AI contributes;
- what the human contributes;
- how much time is available;
- what alternatives exist;
- what happens when conditions degrade;
- how accountability is preserved.

The central principle is:

> **AI may inform a consequential decision, but authority and accountability must remain explicitly assigned to an authorised human decision-maker unless a higher level of autonomy has been separately and lawfully authorised.**
