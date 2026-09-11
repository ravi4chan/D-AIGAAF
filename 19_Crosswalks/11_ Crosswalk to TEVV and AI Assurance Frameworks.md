# 11-Crosswalk to TEVV and AI Assurance Frameworks

## 1. Purpose

This document establishes the relationship between D-AIGAAF — Defence AI Governance, Assurance & Operational Authorisation Framework and major approaches to **Testing, Evaluation, Verification & Validation (TEVV)** and **AI assurance**.

The purpose is to establish a coherent bridge between:

**Requirements → Testing → Evidence → Evaluation → Assurance → Operational Readiness → Authorisation**

This crosswalk is especially important because D-AIGAAF deliberately separates:

- testing;
- evaluation;
- verification;
- validation;
- assurance;
- readiness; and
- operational authorisation.

These terms are related but are not interchangeable.

## 2. Scope

The crosswalk considers relevant assurance concepts from sources including:

- NIST AI Risk Management Framework;
- NIST AI RMF Playbook and related measurement/evaluation guidance;
- NIST AI 100-3 Adversarial Machine Learning Taxonomy;
- ISO/IEC 42001;
- ISO/IEC 23894;
- ISO/IEC 25059 for AI system quality model concepts;
- ISO/IEC TR 24028 for trustworthiness in AI;
- ISO/IEC 24029 series concerning neural-network robustness;
- ISO/IEC 25059 and related AI system quality work;
- NATO and defence-AI assurance approaches;
- U.S. Department of Defense responsible-AI implementation and testing concepts;
- UK MOD dependable-AI assurance concepts;
- established systems-engineering V&V concepts where relevant.

These sources are treated as reference inputs.

They do not automatically establish a defence operational authorisation decision.

## 3. Why TEVV and Assurance Require a Separate Crosswalk

AI systems create a fundamental governance problem:

> **How do we establish justified confidence that an AI capability will behave acceptably for its intended purpose and conditions?**

Traditional software testing alone may not answer this question because AI behaviour can depend on:

- training data;
- model architecture;
- learned parameters;
- uncertainty;
- distribution shift;
- emergent behaviour;
- environmental conditions;
- human interaction;
- adversarial inputs;
- system dependencies.

D-AIGAAF therefore treats TEVV and assurance as a **multi-dimensional evidence system**, not a single test event.

## 4. Core Definitions

### Testing

Determining system behaviour against defined test cases or requirements.

### Evaluation

Assessing performance, characteristics, risks or suitability against defined criteria.

### Verification

Establishing whether specified requirements have been satisfied.

### Validation

Establishing whether the system is suitable for its intended purpose and operational context.

### Assurance

Providing justified confidence, based on evidence, that relevant requirements, risks and controls remain adequately addressed.

### Readiness

A decision state indicating that defined prerequisites for deployment or employment have been met.

### Authorisation

A formal decision by an appropriately empowered authority permitting specified use under specified conditions.

D-AIGAAF therefore maintains:

**TEVV ≠ Assurance ≠ Readiness ≠ Authorisation**

## 5. High-Level Crosswalk

| Assurance Concept | D-AIGAAF Modules | D-AIGAAF Treatment |
|---|---|---|
| Requirements-based testing | 04 AI Lifecycle; 09 TEVV | Converts requirements into testable criteria |
| AI performance evaluation | 09 TEVV | Evaluates technical and mission-relevant performance |
| Verification | 09 TEVV; 16 Audit | Establishes whether requirements and controls are satisfied |
| Validation | 02 Mission; 09 TEVV; 10 Environment | Establishes fitness for intended mission and environment |
| Reliability | 03 Risk; 09 TEVV; 13 Assurance | Tests dependable behaviour under relevant conditions |
| Robustness | 09 TEVV; 10 Environment | Assesses behaviour under variability and stress |
| AI safety | 03 Risk; 09 TEVV; 14 Fail-Safe | Evaluates foreseeable hazards and protective controls |
| Security assurance | 06 Security; 09 TEVV; 13 Assurance | Integrates AI security and adversarial evaluation |
| Human-AI evaluation | 08 Human Authority; 09 TEVV | Evaluates meaningful human control and interaction |
| Autonomy evaluation | 03 Risk; 09 TEVV; 11 Authorisation | Tests autonomy boundaries and transitions |
| Operational trials | 09 TEVV; 10 Environment | Evaluates realistic operational conditions |
| Continuous assurance | 13 Continuous Assurance | Maintains confidence after deployment |
| Independent assurance | 09 TEVV; 16 Audit | Provides independent challenge where required |
| Evidence management | 09 TEVV; 16 Audit; 25 Documentation | Maintains traceable assurance evidence |
| Revalidation | 15 Change; 04 Lifecycle | Reassesses fitness following relevant change |
| Reauthorisation | 11 Authorisation; 15 Change | Restores explicit authority following material change |

## 6. NIST AI RMF and Measurement

NIST AI RMF structures AI risk management through GOVERN, MAP, MEASURE and MANAGE.

The MEASURE function focuses on analysing, assessing and tracking identified AI risks using appropriate quantitative and qualitative methods.

D-AIGAAF aligns strongly with this concept through:

- TEVV planning;
- risk-based evaluation;
- performance indicators;
- evidence;
- continuous assurance;
- corrective action.

D-AIGAAF extends measurement into a defence authorisation chain:

**Measure → Evaluate → Assure → Determine Readiness → Authorise**

The measurement result itself does not automatically establish authority.

## 7. ISO/IEC 42001 and Assurance

ISO/IEC 42001 establishes an AI Management System and includes performance evaluation, internal audit, management review and continual improvement.

D-AIGAAF maps these organisational assurance concepts into the AI capability lifecycle.

Relevant D-AIGAAF elements include:

- TEVV;
- continuous assurance;
- audit;
- governance review;
- corrective action;
- change control;
- revalidation;
- reauthorisation.

The key extension is that D-AIGAAF connects organisational management-system assurance with **mission-specific operational assurance**.

## 8. ISO/IEC 23894 and Risk-Based Evaluation

ISO/IEC 23894 provides guidance for managing AI-related risks.

D-AIGAAF uses risk to determine the depth and scope of assurance.

Higher-risk systems may require stronger:

- evidence;
- test coverage;
- independent evaluation;
- human-control assessment;
- security testing;
- operational trials;
- monitoring;
- revalidation.

This creates a proportionality principle:

> **Assurance effort should be commensurate with consequence, uncertainty and risk.**

## 9. AI System Quality

AI quality cannot be represented adequately by one metric.

D-AIGAAF evaluates multiple dimensions, as applicable:

- functional performance;
- accuracy;
- robustness;
- reliability;
- safety;
- security;
- explainability;
- maintainability;
- interoperability;
- human interaction;
- operational suitability.

The relevant question is:

> **Does the system provide the required quality for the intended mission and operating conditions?**

A high benchmark score does not automatically establish operational suitability.

## 10. Verification

Verification addresses whether the system satisfies specified requirements.

Examples include verifying:

- required functionality;
- security controls;
- interface requirements;
- data controls;
- logging;
- autonomy boundaries;
- fail-safe behaviour;
- configuration;
- access controls.

D-AIGAAF requires verification evidence to be traceable to requirements.

The basic chain is:

**Requirement → Verification Method → Test → Result → Evidence → Finding**

## 11. Validation

Validation asks a different question:

> **Does the system actually satisfy the intended mission purpose under relevant conditions?**

Validation therefore requires consideration of:

- mission;
- operational context;
- users;
- environment;
- constraints;
- consequences;
- human interaction;
- realistic data;
- adversarial conditions.

A system can be verified against technical requirements and still fail validation because it is unsuitable for the intended operational purpose.

## 12. Test Design

D-AIGAAF requires test design to consider:

- intended use;
- foreseeable misuse;
- operational scenarios;
- edge cases;
- failure modes;
- environmental variability;
- adversarial conditions;
- uncertainty;
- human interaction;
- autonomy transitions;
- system dependencies.

Testing should include both expected and challenging conditions.

Where appropriate, testing should evaluate:

- normal operation;
- boundary conditions;
- degraded conditions;
- recovery;
- fail-safe;
- abnormal inputs;
- security compromise scenarios;
- human intervention.

## 13. AI-Specific Test Challenges

AI TEVV must account for characteristics that distinguish AI from deterministic software.

Relevant issues include:

### Data dependence

Performance depends on training and evaluation data.

### Distribution shift

Performance can change when operational data differs from evaluation data.

### Non-determinism

Some systems may produce different outputs under apparently similar conditions.

### Uncertainty

The system may not know when it is outside its reliable operating domain.

### Emergent behaviour

Complex systems may exhibit behaviour not fully captured by conventional test cases.

### Interaction effects

AI behaviour can change when integrated with humans, tools or other systems.

### Adversarial manipulation

Inputs or data can be deliberately manipulated.

D-AIGAAF requires these characteristics to be considered within the TEVV plan.

## 14. Operational Environment Testing

A major D-AIGAAF requirement is evaluation in the environment relevant to intended use.

This may include:

- terrain;
- weather;
- electromagnetic conditions;
- communications availability;
- sensor conditions;
- data availability;
- infrastructure;
- human workload;
- adversarial activity.

Where practical, testing should progressively move from:

**Laboratory → Controlled Environment → Representative Environment → Operational Trial → Operational Monitoring**

The level of realism should be proportionate to risk.

## 15. Degraded and Disconnected TEVV

Defence AI may operate without continuous access to:

- cloud services;
- communications;
- external data;
- positioning;
- supporting systems.

TEVV should therefore assess:

- expected degradation behaviour;
- loss of dependencies;
- stale data;
- incomplete data;
- fallback;
- uncertainty communication;
- autonomy reduction;
- safe state;
- recovery;
- human intervention.

The key question is not merely:

> “Does the system work when connected?”

but:

> **“What does the system do when an important dependency fails?”**

## 16. Human-AI TEVV

Human performance is part of system performance.

D-AIGAAF therefore evaluates:

- operator understanding;
- workload;
- trust calibration;
- alerting;
- explanation;
- uncertainty communication;
- intervention;
- override;
- response time;
- automation bias;
- inappropriate reliance;
- skill degradation.

A system should not be considered assured solely because its model-level metrics are strong.

The human-machine system must also be evaluated.

## 17. Autonomy TEVV

Autonomous functions require specific testing of:

- autonomy boundaries;
- transition conditions;
- decision thresholds;
- human intervention;
- override;
- loss of communications;
- unexpected inputs;
- system uncertainty;
- safe-state behaviour;
- recovery.

D-AIGAAF requires autonomy evaluation to demonstrate not only what the system **can** do, but also what it **cannot** do under authorised conditions.

This is important because:

**Capability ≠ Authority**

## 18. Security and Adversarial Evaluation

AI systems require security-oriented evaluation in addition to conventional cybersecurity testing.

Relevant evaluation areas include:

- adversarial inputs;
- data poisoning;
- model manipulation;
- prompt/instruction attacks;
- model extraction;
- privacy leakage;
- compromised dependencies;
- malicious updates;
- unsafe tool use;
- AI-enabled attacks.

D-AIGAAF connects this testing to Module 06 and provides the detailed AI-security crosswalk separately in Serial 12.

## 19. Evidence

TEVV produces evidence.

Evidence should be:

- attributable;
- traceable;
- reproducible where practical;
- sufficiently complete;
- protected against inappropriate alteration;
- linked to requirements;
- linked to test conditions;
- linked to system configuration.

Evidence should identify:

- what was tested;
- why it was tested;
- how it was tested;
- under which configuration;
- with which data;
- under which conditions;
- what was observed;
- what limitations remain.

## 20. Evidence Hierarchy

D-AIGAAF can use a layered evidence model:

### Level 1 — Documentation Evidence

Policies, requirements, architecture and procedures.

### Level 2 — Analytical Evidence

Risk assessments, modelling, analysis and simulations.

### Level 3 — Test Evidence

Laboratory and controlled test results.

### Level 4 — Evaluation Evidence

Independent or structured evaluation findings.

### Level 5 — Operational Evidence

Representative or real-world operational performance.

### Level 6 — Continuous Evidence

Post-deployment monitoring and assurance.

Higher-consequence decisions should generally require stronger and more diverse evidence.

## 21. Evidence Sufficiency

More evidence does not automatically mean better assurance.

Evidence should be assessed for:

- relevance;
- quality;
- independence;
- coverage;
- recency;
- configuration validity;
- operational realism;
- uncertainty;
- contradictions.

A thousand low-quality tests do not necessarily outweigh a small number of high-quality tests that expose a critical failure mode.

D-AIGAAF therefore treats **evidence quality and relevance** as essential.

## 22. Assurance Confidence

D-AIGAAF treats assurance as a justified confidence judgement rather than a binary “safe/unsafe” label.

Confidence may be influenced by:

- evidence quality;
- test coverage;
- independent challenge;
- residual risk;
- operational realism;
- known limitations;
- environmental uncertainty;
- data quality;
- security posture;
- human-control effectiveness;
- system changes.

The framework should explicitly communicate uncertainty rather than manufacture confidence where evidence is insufficient.

## 23. Assurance Levels

Organisations may define assurance levels appropriate to their governance system.

A conceptual model could include:

| Level | Meaning |
|---|---|
| A1 | Limited evidence and preliminary confidence |
| A2 | Evidence established for defined conditions |
| A3 | Strong evidence across representative conditions |
| A4 | Independently challenged and operationally demonstrated |
| A5 | Continuously assured under defined conditions |

These levels are illustrative rather than mandatory.

They should not be confused with D-AIGAAF autonomy levels A0–A5.

The framework should avoid creating terminology that makes assurance level appear equivalent to autonomy level.

## 24. Independent Evaluation

Independence is particularly important for high-consequence AI.

D-AIGAAF may require independent evaluation where:

- consequences are severe;
- autonomy is high;
- system complexity is high;
- supplier evidence is relied upon heavily;
- conflicts of interest exist;
- assurance uncertainty is significant;
- governance authorities require independent challenge.

Independence may involve:

- separate evaluation teams;
- independent reviewers;
- external assessors;
- red teams;
- audit functions.

Independence should be proportionate to risk.

## 25. Red Teaming

Red teaming should be treated as one component of TEVV and assurance.

It can examine:

- adversarial behaviour;
- misuse;
- system boundaries;
- security;
- human interaction;
- unsafe assumptions;
- unexpected autonomy;
- information manipulation.

A successful red-team exercise does not prove that the system is safe.

Its purpose is to discover weaknesses that may otherwise remain hidden.

Findings should feed:

**Risk → Corrective Action → Retesting → Assurance → Authorisation**

## 26. Mission Effectiveness

Technical performance is not identical to mission effectiveness.

D-AIGAAF therefore evaluates whether AI contributes meaningfully to the intended mission.

Examples of mission-level questions include:

- Does AI improve the intended outcome?
- Does it create unacceptable new risks?
- Does it increase operator workload?
- Does it produce actionable information?
- Does it perform within operational time constraints?
- Does it remain useful under degraded conditions?
- Does it introduce new dependencies?

Mission effectiveness should be assessed alongside technical performance.

## 27. Acceptance and Readiness

TEVV findings feed into a readiness decision.

A readiness assessment should consider:

- requirements;
- test results;
- unresolved findings;
- residual risk;
- limitations;
- operating conditions;
- human competence;
- security;
- dependencies;
- recovery;
- monitoring.

D-AIGAAF maintains:

**Tested → Evaluated → Assured → Ready**

as distinct states.

## 28. Relationship Between Assurance and Authorisation

Operational authorisation is a governance decision.

Assurance provides evidence to support that decision.

Therefore:

**Assurance ≠ Authorisation**

A capability can be:

- technically assured but not authorised;
- authorised only for a restricted mission;
- authorised only at a lower autonomy level;
- authorised only in specified environments;
- temporarily suspended despite previously strong assurance.

The authorisation decision must consider the total context.

## 29. Continuous Assurance

AI assurance cannot end at deployment.

D-AIGAAF monitors:

- performance;
- drift;
- environmental changes;
- security;
- human interaction;
- incidents;
- dependencies;
- model changes;
- data changes.

Evidence should be refreshed where necessary.

The assurance cycle becomes:

**Evaluate → Assure → Deploy → Monitor → Detect Change → Reassess → Revalidate → Reauthorise**

## 30. Change and Revalidation

A model update can alter:

- performance;
- bias;
- uncertainty;
- robustness;
- security;
- autonomy;
- human interaction.

Therefore, significant changes should trigger impact assessment.

Depending on the change, D-AIGAAF may require:

- regression testing;
- targeted TEVV;
- full revalidation;
- independent review;
- revised risk assessment;
- revised assurance;
- reauthorisation.

## 31. TEVV Failure and Findings

A TEVV process should not hide failures.

Findings should be:

- recorded;
- classified;
- assessed for risk;
- assigned owners;
- tracked to closure;
- independently verified where appropriate.

Critical findings may trigger:

- deployment restriction;
- autonomy reduction;
- suspension;
- fail-safe;
- incident investigation;
- revalidation;
- reauthorisation.

## 32. TEVV Records

TEVV records should include, as appropriate:

- requirements;
- test plans;
- test cases;
- datasets;
- system configuration;
- model version;
- environment;
- test conditions;
- results;
- anomalies;
- limitations;
- evaluator identity;
- independence status;
- findings;
- corrective actions;
- retest results;
- acceptance decisions.

This creates a durable evidence trail.

## 33. D-AIGAAF TEVV Golden Thread

The TEVV-specific chain is:

**Mission Need**
→ Requirements

**Requirements**
→ Evaluation Criteria

**Evaluation Criteria**
→ Test Design

**Test Design**
→ Test Execution

**Test Execution**
→ Results

**Results**
→ Findings

**Findings**
→ Risk Assessment

**Risk Assessment**
→ Corrective Action

**Corrective Action**
→ Retesting

**Retesting**
→ Evidence

**Evidence**
→ Assurance

**Assurance**
→ Readiness

**Readiness**
→ Operational Authorisation

## 34. Crosswalk Summary

| Framework / Concept | D-AIGAAF Position |
|---|---|
| NIST AI RMF MEASURE | Measurement, evaluation and monitoring |
| ISO/IEC 42001 | Management-system performance evaluation and continual improvement |
| ISO/IEC 23894 | Risk-based assurance |
| AI quality models | Multi-dimensional AI system quality |
| Defence TEVV | Mission and operational evaluation |
| Human factors | Human-AI system evaluation |
| Adversarial ML | Security and adversarial evaluation |
| Red teaming | Adversarial discovery and challenge |
| Operational trials | Environment and mission validation |
| Continuous assurance | Post-deployment confidence |
| Independent evaluation | Objective challenge |
| Revalidation | Change-triggered reassessment |
| Authorisation | Authority decision informed by assurance |

## 35. Implementation Guidance

An organisation implementing D-AIGAAF should establish a TEVV plan that defines:

1. What must be demonstrated.
2. Why it must be demonstrated.
3. Which requirements apply.
4. Which evaluation methods will be used.
5. What operating conditions must be represented.
6. What evidence is required.
7. What constitutes an acceptable result.
8. Who evaluates the result.
9. Who accepts residual risk.
10. What triggers revalidation.
11. What triggers reauthorisation.

The TEVV plan should be established early in the AI lifecycle rather than after development is complete.

## 36. Limitations

This crosswalk does not claim:

- that any one TEVV methodology is universally sufficient;
- that passing tests establishes safety;
- that benchmark performance establishes operational suitability;
- that supplier test evidence is automatically sufficient;
- that assurance eliminates uncertainty;
- that assurance automatically grants operational authority;
- that red teaming alone constitutes assurance.

TEVV must remain risk-based, mission-specific and evidence-driven.

## 37. Primary Reference Basis

Relevant reference sources include:

- NIST AI Risk Management Framework 1.0 and associated measurement/evaluation guidance.
- ISO/IEC 42001:2023 — Artificial Intelligence Management System.
- ISO/IEC 23894:2023 — Guidance on risk management for AI.
- ISO/IEC 25059 — AI system quality model.
- ISO/IEC TR 24028 — Overview of trustworthiness in AI.
- ISO/IEC 24029 series — assessment of robustness of neural networks.
- NATO responsible-AI principles and defence AI assurance work.
- U.S. Department of Defense responsible-AI principles and implementation work.
- UK MOD JSP 936 — Dependable Artificial Intelligence in Defence.

These references should be periodically reviewed because AI assurance methodologies are evolving.

## 38. Final Crosswalk Position

TEVV and assurance provide the evidence foundation for responsible defence AI, but they do not independently create operational authority.

D-AIGAAF establishes the following chain:

**Requirements → Testing → Evaluation → Verification → Validation → Evidence → Assurance → Readiness → Authorisation → Employment → Continuous Assurance**

The governing principle is:

> **An AI capability should not be treated as operationally trustworthy merely because it has passed a test. Confidence must be justified by relevant, sufficient and current evidence across the mission, system, human, security and operational environment.**

And critically:

> **Assured ≠ Authorised.**

Operational authority remains a separate governance decision made by an appropriately empowered human authority under defined conditions.
