# Operational Scenarios

## 1. Purpose

Operational Scenarios describe the realistic conditions in which an AI use case is expected to operate.

They translate the abstract use case into representative situations that can be used for:

- requirements definition;
- risk assessment;
- TEVV;
- human-AI evaluation;
- operational trials;
- authorisation;
- continuous assurance.

---

## 2. Core Principle

AI performance cannot be established solely in ideal or laboratory conditions.

The governing relationship is:

**Mission → Use Case → Operational Scenario → Risk → Evidence → Assurance → Authorisation**

Operational scenarios should represent the conditions, pressures, constraints and uncertainties that could materially affect mission performance.

---

## 3. Scenario Scope

Scenarios should cover, where relevant:

- normal operations;
- degraded operations;
- abnormal conditions;
- failure conditions;
- adversarial conditions;
- communications-denied conditions;
- information-degraded conditions;
- high-workload conditions;
- recovery conditions;
- foreseeable misuse.

The required scenario depth should be proportionate to consequence and autonomy.

---

## 4. Scenario Identification

Each consequential scenario should have a unique identifier.

A scenario should remain traceable to:

- mission;
- use case;
- operational environment;
- constraints;
- risk profile;
- success criteria;
- requirements;
- tests and evaluations;
- evidence;
- authorisation conditions.

---

## 5. Scenario Components

A scenario should define, where applicable:

| Component | Description |
|---|---|
| Scenario ID | Unique identifier |
| Mission | Supported mission |
| Use Case | AI use case |
| Objective | Intended operational outcome |
| Actors | Relevant human and system actors |
| Environment | Physical and technical environment |
| Inputs | Data and information available |
| Constraints | Applicable mission constraints |
| Communications | Connectivity conditions |
| Human Conditions | Workload, staffing and decision context |
| Threat Conditions | Adversarial or security conditions |
| AI Role | Expected AI behaviour |
| Human Role | Required human actions |
| Autonomy | Applicable autonomy level |
| Expected Outcome | Desired result |
| Failure Conditions | Relevant failure modes |
| Recovery | Expected response to failure |
| Evidence | Required evaluation evidence |

---

## 6. Normal Operational Scenarios

Normal scenarios represent expected operating conditions.

They should establish:

- intended inputs;
- expected AI behaviour;
- human interaction;
- normal decision flow;
- expected mission outcome.

Normal scenarios establish the baseline but should not be the only basis for assurance.

---

## 7. Degraded Operational Scenarios

Degraded scenarios assess behaviour when supporting conditions deteriorate.

Examples may include:

- reduced communications;
- intermittent connectivity;
- degraded sensors;
- incomplete information;
- reduced computing resources;
- degraded positioning;
- reduced staffing;
- increased workload.

The scenario should specify whether the required response is:

- continued operation;
- reduced functionality;
- transfer to human control;
- controlled degradation;
- fail-safe;
- shutdown.

---

## 8. Communications-Denied Scenarios

Where communications loss is foreseeable, scenarios should assess:

- system behaviour during loss of connectivity;
- dependence on remote services;
- availability of local data;
- human ability to intervene;
- behaviour when communication is restored;
- protection against stale or conflicting information.

Communications loss should not result in unexpected expansion of AI authority.

---

## 9. Information-Degraded Scenarios

AI systems may receive information that is:

- incomplete;
- inaccurate;
- stale;
- contradictory;
- ambiguous;
- manipulated;
- unavailable.

Scenarios should assess whether the system:

- identifies information limitations;
- communicates uncertainty;
- avoids unsupported conclusions;
- requests additional information where appropriate;
- degrades safely.

---

## 10. Adversarial Scenarios

Adversarial scenarios assess behaviour when an actor deliberately attempts to manipulate, deceive, disrupt or compromise the AI capability.

Relevant conditions may include:

- manipulated inputs;
- deceptive information;
- adversarial examples;
- malicious instructions;
- compromised data;
- cyber attack;
- compromised dependencies;
- deliberate denial of service.

Testing should focus on both technical resilience and operational consequences.

---

## 11. Human Workload Scenarios

AI may be used during periods of high cognitive or operational workload.

Scenarios should consider:

- time pressure;
- multiple simultaneous alerts;
- fatigue where relevant;
- incomplete information;
- competing priorities;
- reduced staffing;
- ambiguous AI outputs.

Human control should be demonstrated under realistic conditions rather than assumed from interface design.

---

## 12. High-Consequence Scenarios

Where an AI error could cause death, serious injury, major property damage or strategic consequences, scenarios should explicitly examine:

- worst credible outcomes;
- decision latency;
- human intervention;
- escalation;
- fail-safe behaviour;
- recovery;
- accountability;
- evidence requirements.

High-consequence scenarios should receive proportionately greater assurance attention.

---

## 13. Autonomous Behaviour Scenarios

For higher autonomy levels, scenarios should assess:

- adherence to authorised objectives;
- adherence to operational boundaries;
- response to unexpected inputs;
- response to communications loss;
- response to human intervention;
- behaviour under degraded conditions;
- behaviour near authority boundaries;
- prevention of unauthorised actions.

The objective is to demonstrate that autonomy remains bounded and predictable within the authorised envelope.

---

## 14. Human Override Scenarios

Where human override is required, scenarios should demonstrate:

- detection of the need for intervention;
- availability of the override mechanism;
- time required to intervene;
- reliability of intervention;
- system response to override;
- confirmation that authority has transferred as intended.

An override mechanism that cannot realistically be used under operational conditions should not be treated as meaningful human control.

---

## 15. Fail-Safe Scenarios

Fail-safe scenarios should test defined protective responses to serious failure.

Possible responses include:

- safe state;
- controlled degradation;
- transfer to human control;
- isolation;
- shutdown;
- termination of autonomous activity.

The fail-safe mechanism should be tested against realistic failure conditions.

Where delay could create unacceptable harm, pre-authorised emergency protective procedures may permit immediate action.

---

## 16. Recovery Scenarios

Recovery scenarios assess what happens after a failure or disruption.

They may cover:

- restoration of communications;
- recovery from sensor failure;
- rollback;
- restart;
- restoration of human control;
- replacement of failed components;
- transition to manual operation.

Recovery should not silently restore a previous authority state if the underlying assurance position has changed.

---

## 17. Foreseeable Misuse

Scenarios should include reasonably foreseeable ways in which a capability could be used incorrectly or outside its intended purpose.

Examples include:

- use outside the authorised mission;
- use in an unauthorised environment;
- use by an unqualified operator;
- use with unsuitable data;
- excessive reliance on AI recommendations;
- use beyond the authorised autonomy level.

Foreseeable misuse should inform controls, training, assurance and authorisation conditions.

---

## 18. Boundary Scenarios

Boundary scenarios test conditions close to the limits of the authorised operational envelope.

Examples include:

- maximum environmental conditions;
- minimum data quality;
- minimum communications availability;
- maximum workload;
- maximum authorised autonomy;
- transition between authorised and unauthorised conditions.

Boundary testing is particularly important where small changes could produce materially different behaviour.

---

## 19. Scenario Combinations

Operational risks may arise from combinations of conditions rather than individual conditions.

Examples include:

**Poor Data + Communications Loss + High Workload**

or:

**Adversarial Inputs + Sensor Degradation + High Autonomy**

Important combinations should be identified through risk assessment and evaluated where proportionate.

---

## 20. Scenario-Based TEVV

Operational scenarios should inform TEVV planning.

The relationship is:

**Scenario → Test Condition → Observation → Evidence → Assurance Claim**

Scenarios should be converted into appropriate:

- test cases;
- evaluation cases;
- red-team cases;
- human factors assessments;
- operational trials.

---

## 21. Scenario Coverage

Scenario coverage should be assessed systematically.

A scenario coverage assessment should identify:

- scenarios defined;
- scenarios tested;
- scenarios partially tested;
- scenarios not tested;
- evidence available;
- evidence gaps;
- residual uncertainty.

Untested high-consequence scenarios should remain visible as assurance gaps.

---

## 22. Scenario Selection by Risk

Not every conceivable scenario needs to be tested.

Priority should be based on factors such as:

- consequence;
- likelihood or plausibility;
- autonomy;
- human control;
- environmental variability;
- adversarial exposure;
- uncertainty;
- critical dependencies.

Higher-consequence scenarios generally warrant stronger and more representative evidence.

---

## 23. Scenario Data and Reproducibility

Where practical, scenarios should record:

- input conditions;
- system configuration;
- model version;
- relevant data;
- environmental conditions;
- human participants;
- system dependencies;
- actions taken;
- outputs;
- outcomes.

This supports repeatability and later investigation.

---

## 24. Scenario Outcomes

Scenario outcomes should record:

- expected result;
- actual result;
- deviations;
- errors;
- human intervention;
- system limitations;
- safety events;
- security events;
- evidence generated.

Unexpected behaviour should be investigated rather than automatically treated as an isolated anomaly.

---

## 25. Scenario Failure Classification

Failures may be classified as:

- technical failure;
- data failure;
- human-AI interaction failure;
- human control failure;
- security failure;
- autonomy failure;
- environmental failure;
- communications failure;
- operational failure;
- governance failure.

A technically functioning system can still produce an operational or governance failure.

---

## 26. Scenario-Based Authorisation

Operational authorisation should consider whether sufficient representative scenarios have been evaluated for the proposed:

- mission;
- environment;
- autonomy;
- consequence;
- human authority.

Authorisation should not assume that success in one scenario automatically demonstrates success in another materially different scenario.

---

## 27. Scenario Changes

Scenarios should be reviewed when:

- the mission changes;
- the use case changes;
- the environment changes;
- autonomy changes;
- system behaviour changes;
- new threats emerge;
- new failure modes are discovered;
- incidents occur;
- critical dependencies change;
- policy or legal requirements change.

Material changes may require additional TEVV, revalidation or reauthorisation.

---

## 28. Scenario Record

A controlled Operational Scenario Record should contain, as applicable:

- scenario identifier;
- mission;
- use case;
- objective;
- operational conditions;
- actors;
- inputs;
- constraints;
- autonomy;
- human authority;
- expected behaviour;
- failure conditions;
- recovery conditions;
- test/evaluation method;
- results;
- evidence;
- limitations;
- review status.

---

## 29. Minimum Operational Scenario Requirements

For consequential AI use cases, D-AIGAAF should require:

1. Representative normal scenarios.
2. Relevant degraded scenarios.
3. Relevant communications-loss scenarios.
4. Information-degraded scenarios where applicable.
5. Adversarial scenarios where relevant.
6. Human workload scenarios where human control matters.
7. High-consequence scenarios where applicable.
8. Autonomy boundary scenarios where applicable.
9. Human override scenarios where required.
10. Fail-safe and recovery scenarios.
11. Foreseeable misuse scenarios.
12. Appropriate combinations of adverse conditions.
13. Scenario coverage assessment.
14. Traceability from scenarios to TEVV evidence.
15. Review of scenarios after material change or incident.

---

## 30. Relationship With D-AIGAAF

This module connects directly with:

- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Mission_Success_Criteria.md`
- `02 Mission & Use Case/Use_Case_Register.md`
- `03 Risk & Autonomy`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `12 Operational Employment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`

Operational scenarios provide the bridge between the defined use case and representative evidence.

---

## 31. Summary

Operational scenarios establish the conditions under which an AI capability must demonstrate acceptable behaviour.

They prevent assurance from being based solely on ideal conditions and provide a structured way to evaluate:

- operational variability;
- degraded conditions;
- adversarial pressure;
- human workload;
- autonomy;
- human intervention;
- failure;
- recovery;
- foreseeable misuse.

The central principle is:

> **An AI capability should be trusted only to the extent that its relevant behaviour has been demonstrated under conditions representative of its intended operational use.**
