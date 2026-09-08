# 05 — Assurance of Human Control and Autonomy

## 1. Purpose

This document defines how D-AIGAAF maintains continuing assurance that human authority, meaningful human control and authorised autonomy remain effective during the operational life of a Defence AI capability.

The focus is not on defining autonomy levels or allocating decision rights, which are addressed elsewhere. This document establishes how the organisation determines whether those arrangements continue to work in practice.

---

## 2. Core Principle

> **For Defence AI capabilities where human authority or controlled autonomy is material to safety, legality or operational legitimacy, continuing assurance shall establish that authorised humans remain able to understand, supervise, intervene in, override or terminate AI-supported activity to the degree required by the applicable mission and consequence. Autonomy shall remain observable, bounded and consistent with its authorisation.**

---

## 3. Assurance Objective

Human-control and autonomy assurance should determine whether:

- the responsible human authority remains identifiable;
- decision rights remain clear;
- personnel remain competent;
- meaningful oversight remains possible;
- intervention remains effective;
- override mechanisms remain available;
- workload remains manageable;
- situational awareness remains adequate;
- automation bias is controlled;
- autonomy remains within authorised limits;
- autonomy transitions behave as expected.

---

## 4. Assurance Object

The assurance object is:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions**

Human-control assurance therefore depends on both the AI capability and the circumstances in which it is employed.

---

## 5. Human Authority Assurance

The organisation should periodically confirm:

- who holds operational authority;
- who may approve AI-supported actions;
- who may intervene;
- who may override;
- who may reduce autonomy;
- who may suspend employment;
- whether authority transfers remain controlled.

Authority ambiguity should be treated as an assurance concern.

---

## 6. Meaningful Human Control

Meaningful human control should be assessed in practice rather than inferred from system design.

Relevant factors include:

- information available to the human;
- understanding of AI limitations;
- decision time;
- ability to intervene;
- ability to override;
- ability to stop consequential activity;
- clarity of authority;
- competence;
- workload.

---

## 7. Human Decision Quality

Where AI materially supports decisions, assurance should consider whether humans:

- understand the AI contribution;
- can identify uncertainty;
- consider relevant alternatives;
- challenge recommendations;
- recognise conflicting information;
- make decisions consistent with their authority.

The objective is not to require humans to reject AI, but to ensure that acceptance is meaningful rather than automatic.

---

## 8. Automation Bias

Assurance should consider whether personnel are:

- accepting AI recommendations without appropriate assessment;
- over-trusting confidence indicators;
- ignoring contradictory information;
- assuming AI outputs are facts;
- becoming dependent on automated recommendations.

Material automation bias may require:

- additional training;
- interface changes;
- increased human review;
- operational restrictions.

---

## 9. Human-AI Disagreement

Disagreement between human judgement and AI output should be treated as an important assurance signal.

The organisation should assess:

- frequency;
- circumstances;
- consequences;
- resolution;
- whether the AI or human was correct;
- whether the disagreement reveals a system limitation.

Repeated unexplained disagreement may indicate a need for review.

---

## 10. Human Workload

Continuing assurance should assess whether workload allows effective oversight.

Indicators may include:

- excessive task load;
- alert burden;
- decision compression;
- delayed intervention;
- missed warnings;
- fatigue;
- insufficient attention.

A system may become operationally unsuitable if human supervision is no longer realistically achievable.

---

## 11. Human Competence

Personnel should retain sufficient competence to:

- understand system purpose;
- interpret outputs;
- recognise uncertainty;
- understand limitations;
- exercise decision rights;
- intervene;
- override;
- enter safe state;
- respond to abnormal behaviour.

Competence should be reassessed following material system or autonomy changes.

---

## 12. Situational Awareness

Human-control assurance should consider whether personnel maintain sufficient awareness of:

- current mission;
- system status;
- active autonomy;
- AI outputs;
- uncertainty;
- environment;
- relevant dependencies;
- restrictions;
- intervention availability.

AI should support situational awareness rather than create an opaque operational picture.

---

## 13. Intervention Assurance

Intervention mechanisms should be assessed for:

- availability;
- accessibility;
- authority;
- effectiveness;
- response time;
- reliability;
- human usability.

Testing should establish whether intervention works under conditions where it may actually be needed.

---

## 14. Override Assurance

Override mechanisms should be assessed for:

- correct authority;
- accessibility;
- effectiveness;
- response time;
- unintended consequences;
- protection against unauthorised use.

A nominal override that cannot be effectively exercised does not provide meaningful control.

---

## 15. Safe-State Assurance

Where safe-state mechanisms exist, assurance should establish:

- defined entry conditions;
- predictable behaviour;
- appropriate risk reduction;
- human awareness;
- controlled exit;
- restoration requirements.

Safe-state behaviour should be verified after relevant system changes.

---

## 16. Autonomy State Assurance

The organisation should confirm that:

- current autonomy is observable;
- authorised autonomy is documented;
- active autonomy matches authorisation;
- autonomy transitions are controlled;
- unexpected transitions are detected.

Technical capability must not be interpreted as operational authority.

---

## 17. Autonomy Transition Assurance

Material transitions should be assessed for:

- trigger;
- authority;
- expected behaviour;
- human awareness;
- intervention opportunity;
- resulting risk.

Unexpected transitions should trigger appropriate review.

---

## 18. Autonomy Boundary Assurance

Continuing assurance should assess whether autonomy remains within:

- mission boundaries;
- functional boundaries;
- geographic boundaries;
- temporal boundaries;
- environmental boundaries;
- consequence boundaries;
- human-authority boundaries;
- configuration boundaries.

---

## 19. Autonomous Action Assurance

Where autonomous action is authorised, assurance should establish:

- actions remain within authorised scope;
- relevant conditions remain valid;
- performance remains demonstrated;
- intervention remains possible where required;
- failure behaviour remains acceptable.

---

## 20. Human Control under Degraded Conditions

Assurance should determine whether meaningful human control remains possible during:

- communications degradation;
- disconnected operations;
- sensor degradation;
- navigation uncertainty;
- computing limitations;
- dependency failure.

If effective human control cannot be maintained, the applicable restriction or safe-state process should apply.

---

## 21. Human Control under Adversarial Conditions

Assurance should consider whether adversarial activity could:

- manipulate AI outputs;
- mislead operators;
- interfere with intervention;
- create false alerts;
- conceal system state;
- disrupt communications.

Human-control mechanisms should be tested against relevant threats.

---

## 22. Human Control under Time Pressure

Where decisions are time-sensitive, assurance should assess:

- available decision time;
- information processing demands;
- intervention latency;
- interface usability;
- human workload;
- probability of meaningful review.

The required level of human control should be compatible with realistic operational time constraints.

---

## 23. Human Control and Uncertainty

Where uncertainty increases, human involvement may need to increase.

Possible responses include:

**Increase Review → Restrict Function → Reduce Autonomy → Human Control → Safe State**

Assurance should determine whether these mechanisms remain effective.

---

## 24. Human Control and Environmental Change

Material environmental change may affect:

- perception;
- AI reliability;
- human awareness;
- intervention;
- communications;
- autonomy.

Assurance should assess whether human-control assumptions remain valid.

---

## 25. Human Control and Security

Security events may undermine human authority by affecting:

- identity;
- interfaces;
- system state;
- AI outputs;
- communications;
- intervention mechanisms.

Material security concerns should trigger appropriate assurance review.

---

## 26. Human-Control Indicators

Possible indicators include:

- intervention success rate;
- intervention latency;
- override usage;
- unexpected autonomy events;
- human-AI disagreement;
- workload;
- alert burden;
- training currency;
- control failures.

Indicators should be interpreted in context.

---

## 27. Autonomy Indicators

Possible indicators include:

- active autonomy;
- authorised autonomy;
- transition frequency;
- unexpected transitions;
- boundary events;
- autonomous action outcomes;
- intervention frequency.

Trends may be more informative than individual events.

---

## 28. Assurance Evidence

Evidence may include:

- operational records;
- intervention records;
- training assessments;
- human-factors evaluations;
- TEVV results;
- monitoring data;
- incident investigations;
- user observations;
- autonomy logs.

Evidence should be sufficiently current and representative.

---

## 29. Human-Control Testing

Testing should evaluate:

- recognition of system state;
- understanding of uncertainty;
- decision-making;
- intervention;
- override;
- safe-state entry;
- recovery.

Testing should include representative operational conditions where practicable.

---

## 30. Independence

For high-consequence capabilities, human-control and autonomy assurance should receive appropriate independent challenge.

Reviewers should be able to question:

- whether human control is genuinely meaningful;
- whether autonomy remains appropriate;
- whether intervention assumptions are realistic;
- whether evidence is sufficient.

---

## 31. Assurance Findings

Findings may concern:

- unclear authority;
- ineffective intervention;
- inadequate training;
- excessive workload;
- unexpected autonomy;
- boundary failure;
- poor situational awareness;
- automation bias.

Material findings should enter the corrective-action process.

---

## 32. Corrective Measures

Possible measures include:

- additional training;
- interface modification;
- additional monitoring;
- reduced autonomy;
- restricted mission;
- increased supervision;
- additional testing;
- revised authorisation conditions.

---

## 33. Revalidation

Revalidation should be considered where evidence indicates that a previously demonstrated human-control or autonomy claim may no longer hold.

Examples include:

- material interface change;
- autonomy change;
- new operational environment;
- intervention failure;
- changed human role.

---

## 34. Reauthorisation

Reauthorisation may be required where human authority or autonomy materially changes.

Examples include:

- new autonomy state;
- changed decision rights;
- expanded mission;
- changed environment;
- changed consequences.

---

## 35. Suspension

Where meaningful human control cannot be demonstrated or restored, continued operational employment should be restricted or suspended as appropriate to consequence.

---

## 36. Human-Control Assurance Record

The organisation should maintain evidence covering, where applicable:

- human authority;
- competence;
- oversight;
- workload;
- intervention;
- override;
- safe state;
- autonomy;
- human-AI interaction;
- findings;
- review date.

---

## 37. Assurance Statement

A human-control assurance statement should identify:

- what level of control is required;
- under what conditions;
- what evidence supports the conclusion;
- known limitations;
- residual uncertainty;
- events that would invalidate the conclusion.

---

## 38. Governance Questions

The organisation should be able to answer:

1. Who holds human authority?
2. Is that authority clear during employment?
3. Is meaningful human control demonstrated?
4. Can humans understand relevant AI outputs and uncertainty?
5. Can they intervene in time?
6. Does override work under realistic conditions?
7. Is safe-state behaviour assured?
8. Is active autonomy observable?
9. Does actual autonomy match authorisation?
10. Are autonomy transitions controlled?
11. Is workload compatible with effective oversight?
12. Is automation bias being detected?
13. Does human control remain effective during degraded operations?
14. What evidence supports the conclusion?
15. What findings would trigger restriction, revalidation or suspension?

---

## 39. Core Rule

> **Continuing assurance shall demonstrate that human authority and meaningful human control remain effective under the conditions in which Defence AI is employed. Where autonomy is authorised, the organisation shall maintain evidence that actual autonomy remains within authorised and demonstrated boundaries, that transitions are controlled and observable, and that humans retain the degree of intervention and override capability required by consequence. Material loss of control or unexplained autonomy behaviour shall trigger proportionate protective and governance action.**

---

## 40. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Human-Control/Autonomy Claim → Monitoring → Review → Finding → Corrective Action → Verification → Assurance → Authority → Employment → Revalidation/Reauthorisation**
