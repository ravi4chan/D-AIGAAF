# 03 — AI Output, Uncertainty and Situational Awareness

## 1. Purpose

This document defines governance requirements for the interpretation and operational use of AI-generated information, analysis, predictions and recommendations, particularly where those outputs contribute to situational awareness or consequential decision-making.

The objective is to ensure that AI improves operational understanding without creating false certainty, inappropriate trust or loss of human judgement.

---

## 2. Core Principle

> **AI-generated information shall be treated as an evidence input to operational judgement, not as an unquestionable representation of reality. Material uncertainty, limitations, conflicting information and information gaps shall be visible to the appropriate human decision-maker.**

---

## 3. AI Output Categories

D-AIGAAF distinguishes:

### Observation

Information detected, received or extracted by the system.

### Analysis

AI-generated processing or interpretation of available information.

### Prediction

An estimate concerning a possible future state or event.

### Recommendation

A proposed action, prioritisation or decision.

### Authorised Action

An action that the system or authorised human is explicitly permitted to perform.

These categories should not be conflated.

---

## 4. Situational Awareness

AI may contribute to situational awareness through:

- information aggregation;
- detection;
- classification;
- correlation;
- anomaly identification;
- pattern recognition;
- prediction;
- summarisation;
- decision support.

AI-derived situational awareness should remain one component of the operational picture.

---

## 5. Operational Picture

Where AI contributes to an operational picture, personnel should be able to distinguish:

- human-observed information;
- sensor-derived information;
- AI-derived information;
- externally supplied information;
- inferred information;
- predicted information;
- uncertain information;
- missing information.

This distinction supports appropriate human judgement.

---

## 6. Information Provenance

Where material to a decision, AI outputs should retain or expose appropriate information about:

- source;
- time;
- data origin;
- processing;
- relevant model/system;
- configuration;
- material transformations.

Provenance requirements should be proportionate to consequence and operational feasibility.

---

## 7. Timeliness

Operational information can lose value as conditions change.

AI outputs should therefore be interpreted in relation to:

- time generated;
- time received;
- expected validity;
- information freshness;
- rate of environmental change.

Stale information should not be presented as current without appropriate qualification.

---

## 8. Uncertainty

Material uncertainty should be communicated in a manner appropriate to the user and decision context.

Uncertainty may arise from:

- incomplete data;
- noisy sensors;
- conflicting information;
- model limitations;
- distribution shift;
- environmental conditions;
- adversarial activity;
- insufficient training data;
- changing circumstances.

---

## 9. Confidence versus Correctness

A confidence score, probability or similar indicator should not automatically be interpreted as proof of real-world correctness.

Personnel should understand:

- what the indicator represents;
- what it does not represent;
- known limitations;
- applicable operating conditions.

High apparent confidence should not eliminate appropriate human review.

---

## 10. Unknown and Missing Information

The system and operational process should distinguish:

**Known → Inferred → Uncertain → Unknown → Missing**

The absence of information should not silently become an assumption that a condition is absent.

---

## 11. Conflicting Information

Where AI output conflicts with:

- human observation;
- other sensors;
- other information sources;
- another AI system;
- established operational information;

the conflict should be visible where practicable.

The appropriate human authority should determine how the conflict is resolved.

---

## 12. AI Hallucination and Confabulation

AI systems may produce plausible but unsupported information.

Operational use should therefore include controls against:

- fabricated facts;
- unsupported explanations;
- invented sources;
- false precision;
- misleadingly coherent outputs.

The system should not present unsupported information as established fact.

---

## 13. False Positives

A false positive occurs when the system identifies or predicts something that is not actually present or applicable.

The governance assessment should consider:

- frequency;
- consequence;
- operational impact;
- human review;
- mitigation;
- environmental dependence.

High false-positive rates may create alert fatigue and inappropriate decisions.

---

## 14. False Negatives

A false negative occurs when the system fails to identify or predict something that is present or relevant.

For consequential applications, the organisation should assess:

- acceptable miss rates;
- consequences;
- human detection;
- redundancy;
- environmental dependence;
- mitigation.

The importance of false negatives may differ from false positives depending on the mission.

---

## 15. Bias and Systematic Error

Operational personnel should consider whether AI outputs may be systematically affected by:

- data bias;
- incomplete representation;
- sensor bias;
- environmental bias;
- model limitations;
- population or context differences.

Systematic error may remain invisible if only average performance is considered.

---

## 16. Distribution Shift

AI performance may change when operational conditions differ from development or testing conditions.

Potential changes include:

- environment;
- terrain;
- weather;
- illumination;
- sensor characteristics;
- information patterns;
- operational behaviour;
- adversarial activity.

Material distribution shift should trigger appropriate monitoring and governance action.

---

## 17. Situational Awareness Boundaries

AI-generated situational awareness should have defined limitations.

Personnel should understand:

- what the system can observe;
- what it cannot observe;
- what information it requires;
- where blind spots exist;
- what assumptions it makes;
- what conditions reduce reliability.

A system should not imply comprehensive awareness when its information is incomplete.

---

## 18. Human Situational Awareness

AI should support rather than replace human situational awareness.

Operational personnel should retain awareness of:

- mission context;
- relevant external information;
- system limitations;
- changing conditions;
- uncertainty;
- conflicting evidence.

Over-reliance on AI may itself become an operational risk.

---

## 19. Automation Bias

Automation bias may occur when personnel:

- accept AI recommendations without sufficient review;
- assume AI is more accurate than human judgement;
- ignore contradictory information;
- defer to system outputs because they appear objective;
- continue trusting AI after conditions change.

Training, interface design and operational procedures should reduce this risk.

---

## 20. Alert Management

AI systems may generate large numbers of alerts.

Governance should consider:

- alert frequency;
- severity;
- prioritisation;
- false positives;
- false negatives;
- escalation;
- operator workload.

Excessive alerts can reduce rather than improve situational awareness.

---

## 21. Human Review Thresholds

The authorisation and employment process should define when AI outputs require:

- routine human review;
- enhanced review;
- confirmation from another source;
- escalation;
- rejection;
- suspension of the relevant AI function.

Thresholds should be proportionate to consequence and uncertainty.

---

## 22. Consequential Recommendations

Where an AI recommendation may materially affect:

- human life;
- physical safety;
- critical infrastructure;
- significant property;
- major mission outcomes;

the system should provide sufficient information for the authorised human decision-maker to exercise appropriate judgement.

---

## 23. Recommendation Acceptance and Rejection

A human decision-maker may:

- accept;
- reject;
- modify;
- defer;
- seek additional information;
- escalate.

For material decisions, the rationale for rejection or bypass should be recorded where required.

Rejecting an AI recommendation should not automatically be treated as a governance failure.

---

## 24. AI and Human Disagreement

When AI and human judgement disagree, the organisation should consider:

- evidence quality;
- uncertainty;
- context;
- source reliability;
- system limitations;
- human observation;
- time sensitivity.

Disagreement should become a reason for examination where consequence warrants it, not an automatic instruction to follow the AI.

---

## 25. Multi-AI Outputs

Where multiple AI systems contribute to situational awareness or decision-making, personnel should consider:

- conflicting outputs;
- duplicated errors;
- shared data;
- common model assumptions;
- correlated failure;
- recommendation chaining.

Multiple AI outputs should not automatically be interpreted as independent confirmation.

---

## 26. Human Factors

Operational employment should consider:

- workload;
- cognitive load;
- attention;
- fatigue;
- alert saturation;
- interface complexity;
- trust;
- over-trust;
- under-trust.

Human factors should be evaluated as part of operational assurance.

---

## 27. Interface Requirements

Where appropriate, interfaces should make visible:

- AI contribution;
- uncertainty;
- information freshness;
- source/provenance;
- system status;
- autonomy;
- material limitations;
- warnings;
- required human action.

Important information should not be hidden behind unnecessary complexity.

---

## 28. Explainability

The level of explanation should be proportionate to:

- consequence;
- user role;
- decision type;
- time available;
- system capability.

The objective is actionable understanding, not necessarily complete technical interpretability of every internal model operation.

---

## 29. Model Limitations

Operational personnel should have access to relevant information about:

- known limitations;
- tested conditions;
- untested conditions;
- known failure modes;
- data limitations;
- environmental limitations;
- autonomy limitations.

Limitations should be reflected in employment procedures and authorisation conditions where material.

---

## 30. Environmental Effects

AI output quality may change due to:

- weather;
- terrain;
- lighting;
- sensor degradation;
- communications;
- electromagnetic conditions;
- adversarial interference;
- information availability.

Material environmental effects should be monitored.

---

## 31. Degraded Information

When information quality deteriorates, personnel should reassess:

- output reliability;
- uncertainty;
- mission suitability;
- human-control requirements;
- autonomy.

The system should not silently maintain the same level of confidence when its information basis has materially degraded.

---

## 32. Disconnected Operations

During communication loss, the system may continue operating only within authorised continuity conditions.

Personnel should understand:

- what information remains available;
- what information becomes stale;
- what functions remain authorised;
- what autonomy remains permitted;
- what conditions trigger restriction.

Disconnection should not create additional authority.

---

## 33. Adversarial Manipulation

AI outputs may be influenced by deliberate attempts to:

- manipulate inputs;
- deceive sensors;
- corrupt data;
- exploit model weaknesses;
- create misleading patterns;
- manipulate interfaces.

Material indicators of possible manipulation should trigger appropriate security and operational responses.

---

## 34. Output Integrity

The organisation should protect against:

- unauthorised modification;
- corrupted output;
- manipulated data;
- incorrect configuration;
- interface compromise.

Where output integrity cannot be established for a consequential use, the relevant function should be reassessed.

---

## 35. Operational Monitoring

During employment, monitor where applicable:

- output quality;
- uncertainty;
- error patterns;
- false positives;
- false negatives;
- environmental sensitivity;
- human interaction;
- alert burden;
- autonomy;
- security.

Monitoring should support timely intervention.

---

## 36. Output-Related Escalation

Escalation should occur where:

- uncertainty becomes material;
- output quality degrades;
- conflicting information cannot be resolved;
- unexpected behaviour appears;
- false positives or negatives exceed thresholds;
- AI output materially affects a consequential decision;
- system information becomes unreliable.

---

## 37. Protective Response

Where AI output becomes unreliable, the organisation may apply:

**Verify → Increase Human Review → Restrict Function → Reduce Autonomy → Human Control → Safe State → Suspend**

The response should be proportionate to consequence.

---

## 38. Records

For material outputs and consequential decisions, appropriate records may include:

- output;
- time;
- system/configuration;
- relevant input or source;
- uncertainty;
- human assessment;
- decision;
- action;
- outcome.

Record requirements should be proportionate to consequence and operational feasibility.

---

## 39. Lessons and Feedback

Operational observations concerning AI output should feed into:

- monitoring;
- TEVV;
- risk assessment;
- model/system improvement;
- training;
- authorisation conditions;
- environmental boundaries;
- revalidation.

Operational experience should not remain isolated from lifecycle governance.

---

## 40. Governance Questions

The organisation should be able to answer:

1. What exactly did the AI observe, infer, predict or recommend?
2. What information supported the output?
3. How current was the information?
4. What is known and what is uncertain?
5. What information may be missing?
6. What are the system's known limitations?
7. Could the output be systematically wrong under current conditions?
8. Is the human able to understand and challenge the output?
9. Is human workload affecting judgement?
10. Are multiple AI systems providing genuinely independent information?
11. Has the environment changed?
12. Is the output still reliable enough for the authorised use?
13. What happens if confidence or reliability deteriorates?
14. Can the relevant AI function be restricted or stopped?

---

## 41. Golden Thread

AI output governance remains connected to:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Output → Human Assessment → Decision → Action → Monitoring → Incident/Change → Learning → Revalidation/Reauthorisation**

---

## 42. Core Rule

> **Defence AI outputs used during operational employment shall be interpreted in their operational context and shall not be treated as unquestionable representations of reality. Material uncertainty, information gaps, provenance, freshness, limitations, conflicting information and relevant failure modes shall be communicated appropriately to the responsible human decision-maker. AI-generated situational awareness should support rather than replace human judgement. Where output reliability, human understanding, situational awareness or control becomes materially degraded, the organisation shall apply proportionate verification, increased human review, restriction, reduced autonomy, human control, safe-state transition or suspension as required.**
