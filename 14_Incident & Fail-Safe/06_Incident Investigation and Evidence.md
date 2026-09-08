# 06 — Incident Investigation and Evidence

## 1. Purpose

This document defines the governance requirements for investigating Defence AI incidents and preserving the evidence necessary to establish what occurred, why it occurred, what the AI contributed, what humans did, what controls operated, and what assurance or authorisation consequences follow.

The objective is to produce a reliable, proportionate and traceable understanding of incidents without prematurely attributing cause or treating incomplete evidence as established fact.

---

## 2. Core Principle

> **Material Defence AI incidents shall be investigated using evidence sufficient to reconstruct the relevant system, human, environmental, security and decision context. Investigations shall distinguish observed facts from interpretation and uncertainty, preserve material evidence, examine systemic as well as technical causes, and provide a defensible basis for corrective action and assurance decisions.**

---

## 3. Investigation Object

Investigation should consider:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

The investigation should examine interactions among these factors rather than isolating the AI model unnecessarily.

---

## 4. Investigation Objectives

An investigation should seek to establish:

- what happened;
- when it happened;
- what conditions existed;
- what the AI produced or did;
- what humans observed;
- what decisions were made;
- what actions occurred;
- what controls operated;
- what controls failed;
- what consequences occurred;
- what remains uncertain.

---

## 5. Investigation Scope

Scope should be proportionate to:

- incident severity;
- consequence;
- autonomy;
- uncertainty;
- security implications;
- recurrence;
- systemic significance.

Critical incidents may require broader independent investigation.

---

## 6. Investigation Independence

Investigation should be sufficiently independent from the personnel or functions responsible for the activity being investigated, particularly where:

- consequence is high;
- accountability is disputed;
- systemic failure is suspected;
- security or safety is material;
- organisational conflict exists.

---

## 7. Investigation Authority

The organisation should define authority for:

- opening an investigation;
- appointing investigators;
- obtaining evidence;
- restricting access to affected systems;
- preserving records;
- approving findings;
- escalating conclusions.

---

## 8. Investigation Initiation

Investigation should begin once sufficient immediate protection has been established.

Initial actions should include:

- confirming incident identity;
- establishing scope;
- preserving available evidence;
- identifying responsible authorities;
- preventing unnecessary alteration of system state.

---

## 9. Evidence Preservation

Material evidence should be preserved as early as practicable.

Evidence may include:

- system logs;
- configuration;
- software version;
- model version;
- model or system state where available;
- inputs;
- outputs;
- recommendations;
- actions;
- autonomy state;
- human decisions;
- intervention records;
- environmental conditions;
- communications;
- security records;
- dependency status.

---

## 10. Evidence Integrity

Evidence should be protected against:

- unauthorised modification;
- deletion;
- corruption;
- contamination;
- loss of provenance.

Material evidence should have sufficient integrity and provenance to support later review.

---

## 11. Evidence Chain of Custody

Where appropriate, evidence handling should establish:

- source;
- acquisition time;
- method;
- custodian;
- transfer;
- storage;
- access;
- modification status.

The level of control should be proportionate to the consequence and investigative requirement.

---

## 12. Evidence Categories

Evidence may include:

### Direct Evidence

Evidence directly showing the relevant event or system state.

### Indirect Evidence

Evidence supporting an inference about the event.

### Corroborating Evidence

Independent information supporting another evidence source.

### Contradictory Evidence

Information inconsistent with an existing interpretation.

### Missing Evidence

Evidence that should exist but is unavailable.

---

## 13. Evidence Quality

Evidence should be assessed for:

- authenticity;
- integrity;
- completeness;
- accuracy;
- relevance;
- timeliness;
- provenance;
- reliability.

---

## 14. Missing Evidence

Missing evidence should be explicitly recorded.

Investigators should assess whether missing evidence:

- limits reconstruction;
- increases uncertainty;
- affects attribution;
- affects assurance;
- requires additional controls.

Absence of evidence should not automatically be interpreted as evidence that an event did not occur.

---

## 15. Timeline Reconstruction

Where practicable, investigators should reconstruct:

**Condition → Input → AI Processing/Output → Human Observation → Human Decision → System Action → Intervention → Outcome**

The timeline should distinguish known events from inferred sequence.

---

## 16. AI Contribution

Investigation should establish, where practicable:

- what information entered the AI system;
- what output was produced;
- what uncertainty or limitation was visible;
- whether the output was transmitted or acted upon;
- whether autonomous behaviour occurred.

---

## 17. Human Contribution

Investigation should examine:

- what information humans received;
- what they understood;
- what decisions they made;
- what actions they took;
- whether intervention was attempted;
- whether workload or time pressure affected control.

Human contribution should be analysed objectively.

---

## 18. Human Factors

Relevant factors may include:

- workload;
- training;
- competence;
- interface design;
- automation bias;
- situational awareness;
- fatigue or operational pressure where relevant;
- decision time;
- clarity of authority.

The investigation should avoid reducing complex incidents to individual human error without evidence.

---

## 19. Autonomy Reconstruction

Investigators should determine:

- authorised autonomy;
- configured autonomy;
- observed autonomy;
- autonomy transitions;
- autonomous actions;
- intervention attempts;
- ability to return to an authorised state.

Unexpected autonomy should receive specific examination.

---

## 20. Configuration Reconstruction

The investigation should establish the relevant configuration, including where applicable:

- model version;
- software;
- hardware;
- parameters;
- interfaces;
- data;
- system integration;
- security configuration.

Unknown configuration should be treated as an assurance concern.

---

## 21. Environmental Reconstruction

Relevant conditions may include:

- physical environment;
- weather;
- illumination;
- sensors;
- communications;
- electromagnetic conditions;
- information environment;
- computing conditions;
- human environment;
- adversarial conditions.

Environmental evidence should be linked to the demonstrated operating envelope.

---

## 22. Data and Information Reconstruction

Investigation should examine:

- data source;
- provenance;
- quality;
- timeliness;
- integrity;
- transformations;
- conflicting information;
- missing information.

Where relevant, data conditions should be assessed for their contribution to the incident.

---

## 23. Security Investigation

Where security implications exist, investigation should consider:

- integrity;
- compromise;
- manipulation;
- unauthorised access;
- configuration changes;
- malicious inputs;
- dependency compromise.

Security investigation should be coordinated with operational and safety investigation.

---

## 24. Dependency Investigation

Investigators should examine critical dependencies such as:

- communications;
- data services;
- sensors;
- navigation;
- infrastructure;
- software;
- hardware;
- external services;
- suppliers.

Dependency failure may be a contributing cause rather than the sole cause.

---

## 25. Root Cause Analysis

Investigation should distinguish:

### Immediate Cause

The condition directly associated with the event.

### Contributing Factors

Conditions that increased the likelihood or consequence.

### Latent Weakness

An underlying weakness in design, process, governance or control.

### Systemic Cause

A weakness affecting multiple capabilities or organisational processes.

---

## 26. Cause versus Correlation

Investigators should distinguish:

- confirmed causal relationship;
- plausible contribution;
- correlation;
- unresolved hypothesis.

Causal conclusions should be supported by evidence.

---

## 27. Alternative Explanations

Material investigations should consider plausible alternative explanations.

This helps prevent premature conclusions based on:

- incomplete logs;
- misleading outputs;
- assumptions;
- confirmation bias;
- single-source evidence.

---

## 28. Reproduction

Where safe and appropriate, investigators may attempt controlled reproduction.

Reproduction should consider:

- safety;
- security;
- evidence preservation;
- configuration;
- environmental conditions;
- operational boundaries.

Reproduction should not recreate an unacceptable hazard merely to obtain evidence.

---

## 29. Testing After Incident

Additional testing may be required to determine:

- whether the behaviour is repeatable;
- whether a control works;
- whether the failure mode is understood;
- whether corrective action is effective.

Testing should remain within authorised conditions.

---

## 30. Uncertainty Assessment

Investigators should identify uncertainty concerning:

- event sequence;
- AI behaviour;
- human decisions;
- system state;
- causation;
- consequence.

Uncertainty should remain visible in the final investigation.

---

## 31. Investigation Findings

Findings may identify:

- technical failure;
- human-control weakness;
- autonomy weakness;
- security weakness;
- environmental limitation;
- data issue;
- dependency failure;
- process weakness;
- governance failure.

---

## 32. Assurance Impact

The investigation should assess whether the incident affects:

- assurance claims;
- supporting evidence;
- risk;
- controls;
- operating boundaries;
- human-control assurance;
- autonomy assurance;
- security assurance.

---

## 33. Authorisation Impact

The investigation should identify whether continued authority may require:

- no change;
- restrictions;
- enhanced monitoring;
- additional assurance;
- revalidation;
- reauthorisation;
- suspension.

The investigation should inform, but not improperly replace, the competent authorisation decision.

---

## 34. Corrective Action Inputs

Investigation findings should inform corrective actions concerning:

- model;
- software;
- data;
- configuration;
- controls;
- procedures;
- human factors;
- training;
- monitoring;
- fail-safe;
- authorisation conditions.

---

## 35. Evidence Sufficiency

Before closing an investigation, the responsible authority should determine whether evidence is sufficient to support:

- findings;
- causal conclusions;
- corrective action;
- assurance assessment;
- governance decisions.

Where evidence remains insufficient, limitations should be recorded.

---

## 36. Investigation Report

A material investigation report should contain, as appropriate:

1. incident summary;
2. scope;
3. system and mission context;
4. timeline;
5. evidence;
6. AI contribution;
7. human contribution;
8. environmental conditions;
9. configuration;
10. security and dependency factors;
11. findings;
12. root cause;
13. uncertainty;
14. assurance impact;
15. corrective actions;
16. authorisation implications;
17. lessons.

---

## 37. Review and Challenge

Material investigation reports should undergo appropriate review.

Independent challenge may examine:

- evidence;
- methodology;
- causal reasoning;
- uncertainty;
- findings;
- recommended action.

---

## 38. Disagreement

Where investigators or authorities disagree:

- disagreement should be recorded;
- supporting evidence should be identified;
- unresolved issues should remain visible;
- the appropriate authority should determine the governance outcome.

---

## 39. Confidentiality and Information Handling

Investigation records should be handled according to applicable:

- security requirements;
- classification;
- privacy;
- legal obligations;
- information-sharing restrictions.

The framework itself should remain generic and unclassified.

---

## 40. Investigation Closure

Investigation may be closed when:

- evidence has been adequately assessed;
- material findings are recorded;
- uncertainty is documented;
- assurance impact is determined;
- corrective actions are assigned;
- required authority decisions are recorded.

Closure does not imply that all corrective actions are complete.

---

## 41. Record Retention

Material investigation records should be retained according to:

- legal requirements;
- policy;
- mission consequence;
- audit needs;
- assurance requirements;
- incident investigation requirements.

---

## 42. Investigation and Learning

Investigation outcomes should feed into:

- risk;
- AI lifecycle;
- security;
- TEVV;
- operational environment;
- authorisation;
- employment;
- continuous assurance;
- training.

---

## 43. Governance Questions

The organisation should be able to answer:

1. Who can initiate an investigation?
2. Who appoints investigators?
3. What evidence must be preserved?
4. How is evidence integrity maintained?
5. How is the incident timeline reconstructed?
6. How are AI and human contributions distinguished?
7. How are autonomy events reconstructed?
8. How are environmental conditions established?
9. How are security and dependency factors assessed?
10. How are root causes distinguished from contributing factors?
11. How is uncertainty recorded?
12. When is reproduction or additional testing appropriate?
13. How is independent challenge applied?
14. How are findings linked to assurance?
15. When can an incident require revalidation or reauthorisation?
16. What constitutes sufficient evidence for closure?
17. How are investigation lessons transferred into the governance system?

---

## 44. Core Rule

> **Incident investigation shall establish the best evidence-supported understanding of what occurred while preserving uncertainty where the evidence does not support a definitive conclusion. Investigations shall examine technical, human, environmental, security, dependency and governance factors, and their findings shall provide a traceable basis for corrective action, assurance reassessment and operational-authority decisions.**

---

## 45. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Detection → Protective Response → Evidence Preservation → Investigation → Findings → Root Cause → Corrective Action → Assurance Reassessment → Revalidation/Reauthorisation → Learning**
