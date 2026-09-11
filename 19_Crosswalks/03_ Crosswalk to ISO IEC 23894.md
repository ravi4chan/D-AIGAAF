# 03-Crosswalk to ISO IEC 23894

## 1. Purpose

This crosswalk maps D-AIGAAF against **ISO/IEC 23894:2023 — Information technology — Artificial intelligence — Guidance on risk management**.

ISO/IEC 23894 provides guidance for organisations that develop, produce, deploy, or use products, systems, and services that utilise AI to manage AI-specific risk and integrate AI risk management into organisational activities and functions. ISO states that its application can be customised to the organisation and its context. citeturn0search0turn0search5

D-AIGAAF uses the same fundamental risk-management logic but extends it into defence-specific mission risk, autonomy, human authority, operational environment, operational authorisation, operational employment, fail-safe behaviour, reauthorisation, and continuous operational assurance.

This document is an analytical crosswalk. It does not establish conformity or compliance with ISO/IEC 23894.

## 2. Standard Baseline

The assessed reference is:

- **Standard:** ISO/IEC 23894:2023
- **Title:** Information technology — Artificial intelligence — Guidance on risk management
- **Edition:** First edition
- **Publication:** February 2023
- **Status:** International Standard
- **Technical committee:** ISO/IEC JTC 1/SC 42

ISO describes ISO/IEC 23894 as guidance that can be integrated into an organisation's AI-related activities and functions and customised according to organisational context. citeturn0search0

ISO currently lists ISO/IEC 23894:2023 as a published International Standard. citeturn0search2

## 3. Fundamental Relationship

The relationship can be expressed as:

**ISO/IEC 23894 → AI Risk Management Guidance**

**D-AIGAAF → Defence AI Risk, Autonomy, Assurance, Authorisation and Operational Governance**

ISO/IEC 23894 provides a general AI risk-management foundation.

D-AIGAAF operationalises that foundation for defence environments where risk can include:

- harm to human life;
- mission failure;
- loss of human control;
- unintended autonomous action;
- adversarial manipulation;
- degraded or disconnected operation;
- incorrect situational awareness;
- compromised AI dependencies;
- unsafe interaction between AI and humans; and
- failure of operational authorisation controls.

## 4. High-Level Crosswalk

| ISO/IEC 23894 Risk Area | Principal D-AIGAAF Coverage | Relationship |
|---|---|---|
| AI risk-management framework | 01 Strategy & Governance; 03 Risk & Autonomy | Direct Alignment + Defence Extension |
| Organisational context | 01 Governance; 02 Mission & Use Case; 10 Operational Environment | Direct Alignment + Extension |
| AI risk identification | 02 Mission & Use Case; 03 Risk & Autonomy | Direct Alignment |
| Risk analysis | 03 Risk & Autonomy | Direct Alignment + Extension |
| Risk evaluation | 03 Risk & Autonomy; 09 TEVV; 13 Assurance | Direct Alignment |
| Risk treatment | 03 Risk & Autonomy; 14 Incident & Fail-Safe; 15 Change | Direct Alignment |
| Risk monitoring | 03 Risk & Autonomy; 13 Continuous Assurance | Direct Alignment |
| Lifecycle integration | 04 AI Lifecycle | Direct Alignment + Extension |
| Data-related risk | 05 Data & Information | Direct Alignment + Extension |
| Security risk | 06 AI Security | Direct Alignment + Extension |
| Supplier/dependency risk | 07 Supply Chain & Sovereignty | Direct Alignment + Extension |
| Human-related risk | 08 Human Authority; 17 Workforce | Direct Alignment + Defence Extension |
| Testing and evidence | 09 TEVV; 16 Audit & Evidence | Direct Alignment |
| Operational environment | 10 Operational Environment | D-AIGAAF Extension |
| Operational decision authority | 11 Operational Authorisation | D-AIGAAF Specific |
| Operational employment | 12 Operational Employment | D-AIGAAF Specific |
| Continuous assurance | 13 Continuous Assurance | Direct Alignment + Extension |
| Incident/fail-safe | 14 Incident & Fail-Safe | D-AIGAAF Extension |
| Change/reassessment | 15 Change & Reauthorisation | Direct Alignment + Extension |
| Maturity | 18 Maturity Model | Complementary |
| Governance implementation | 27 Implementation | Direct Alignment |

## 5. Risk Management as the Common Foundation

ISO/IEC 23894 treats AI risk management as something that should be integrated into AI-related organisational activities rather than performed as a detached exercise. citeturn0search0

D-AIGAAF adopts the same principle.

Risk is therefore embedded throughout:

**Mission → Requirements → Development/Acquisition → Data → Model → Integration → TEVV → Deployment → Employment → Monitoring → Change → Reauthorisation → Retirement**

Risk management is not a single approval event.

It is a continuous governance process.

## 6. Context Establishment

A meaningful AI risk assessment requires an understanding of context.

D-AIGAAF expands context into several layers.

### Organisational Context

Covered through:

- governance;
- policy;
- workforce;
- legal and regulatory environment;
- acquisition;
- supply chain;
- interoperability.

### Mission Context

Covered through:

- mission definition;
- use-case definition;
- operational context;
- mission constraints;
- success criteria;
- dependencies;
- exit criteria.

### Operational Context

Covered through:

- environmental variability;
- degraded conditions;
- disconnected operations;
- adversarial conditions;
- information environment;
- human environment;
- operational boundaries.

### Authority Context

Covered through:

- decision rights;
- autonomy level;
- human authority;
- authorisation conditions;
- intervention and override.

The resulting D-AIGAAF context model is:

**Organisation + Mission + Capability + Environment + Autonomy + Human Authority + Dependencies**

## 7. Risk Identification

ISO/IEC 23894 provides a basis for identifying AI-related risks.

D-AIGAAF structures risk identification through:

- mission risk;
- AI capability risk;
- autonomy risk;
- human-control risk;
- data risk;
- security risk;
- supply-chain risk;
- operational-environment risk;
- workforce risk;
- legal and policy risk;
- change risk; and
- incident risk.

The framework is designed to prevent a narrow interpretation in which AI risk is treated only as model error.

## 8. Consequence-Based Risk

D-AIGAAF gives particular importance to consequences.

The key sequence is:

**AI Behaviour → Decision → Action → Consequence**

The assessment should ask:

1. What can the AI influence?
2. What decisions can be affected?
3. What actions can follow?
4. Who or what can be harmed?
5. How reversible is the consequence?
6. How quickly can human intervention occur?
7. What happens if communications are unavailable?
8. What happens if the AI is wrong but appears confident?

This extends conventional AI risk assessment into operational consequence analysis.

## 9. Autonomy as a Risk Variable

ISO/IEC 23894 provides general AI risk-management guidance.

D-AIGAAF explicitly treats autonomy as a major risk variable.

The D-AIGAAF autonomy model is:

| Level | Description |
|---|---|
| A0 | No Meaningful AI Decision |
| A1 | Information / Observation |
| A2 | Analysis / Recommendation |
| A3 | Human-Authorised Action |
| A4 | Supervised Autonomous Action |
| A5 | Independent Consequential Autonomy |

The framework evaluates:

**Autonomy × Consequence × Environment × Human Control**

rather than treating autonomy as a purely technical system property.

## 10. Human Risk and Human Control

AI risk is also human-system risk.

D-AIGAAF therefore assesses:

- competence;
- AI literacy;
- workload;
- decision authority;
- situational awareness;
- intervention capability;
- override capability;
- automation bias;
- over-reliance;
- misunderstanding of AI outputs;
- communication limitations;
- fatigue and operational tempo; and
- accountability.

The principle is:

> Human involvement is meaningful only when the human has the competence, authority, information, capacity, and opportunity necessary to exercise the assigned control.

## 11. Risk Analysis

D-AIGAAF risk analysis should consider:

### Likelihood

How likely is the undesirable event?

### Consequence

What happens if it occurs?

### Exposure

How frequently and under what conditions is the capability exposed?

### Detectability

Can the organisation recognise the failure or degradation?

### Controllability

Can humans intervene effectively?

### Reversibility

Can the resulting action or consequence be reversed?

### Propagation

Can an AI error propagate through connected systems or other AI capabilities?

### Dependency

Does failure depend on external data, communications, services, models, suppliers, or infrastructure?

This produces a more operational risk picture than a model-performance score alone.

## 12. Risk Evaluation

D-AIGAAF evaluates risk against:

- mission consequence;
- operational conditions;
- autonomy;
- human authority;
- applicable controls;
- evidence;
- residual risk;
- authorisation conditions.

A capability may therefore have acceptable technical risk but unacceptable operational risk.

For example:

**Model Accuracy → Acceptable**

does not necessarily mean:

**Operational Risk → Acceptable**

if the model operates in a high-consequence environment with weak human intervention or uncertain inputs.

## 13. Risk Treatment

D-AIGAAF risk treatment options include:

- eliminate the use case;
- modify the mission;
- reduce autonomy;
- restrict operational scope;
- add human approval;
- strengthen controls;
- improve data;
- increase TEVV;
- improve security;
- strengthen monitoring;
- impose environmental boundaries;
- improve workforce competence;
- reduce dependencies;
- defer deployment;
- suspend employment; or
- accept residual risk through the appropriate authority.

The treatment hierarchy should favour reducing risk at source before relying solely on additional human or procedural controls.

## 14. Residual Risk

After controls are applied, D-AIGAAF requires explicit treatment of residual risk.

Residual risk should consider:

- remaining uncertainty;
- known failure modes;
- unknown or emergent failure modes;
- environmental variability;
- autonomy;
- human-control effectiveness;
- security posture;
- data limitations;
- dependency risks;
- evidence confidence.

Residual risk acceptance shall remain separate from maturity scoring.

## 15. Risk Acceptance

Risk acceptance shall identify:

- the risk;
- affected mission or capability;
- controls;
- residual risk;
- evidence;
- acceptance authority;
- conditions;
- validity period;
- monitoring requirements;
- reassessment triggers.

The core principle is:

> The person or body accepting residual risk must have the authority to accept that risk.

Technical ownership alone does not establish risk-acceptance authority.

## 16. Risk Monitoring

ISO/IEC 23894 supports ongoing risk management.

D-AIGAAF implements continuous monitoring through:

- risk indicators;
- performance indicators;
- assurance indicators;
- security indicators;
- environmental indicators;
- human-control indicators;
- incident indicators;
- dependency indicators;
- change indicators.

Monitoring should detect deterioration before it becomes an operational failure.

## 17. Lifecycle Risk Management

D-AIGAAF provides explicit lifecycle integration.

### Concept

Identify mission and AI risk.

### Requirements

Translate risk into requirements and controls.

### Development/Acquisition

Assess design and supply-chain risk.

### Data/Model

Assess data and model-related risk.

### Integration

Assess system-level and human-system risk.

### TEVV

Generate evidence.

### Deployment

Confirm readiness.

### Employment

Control operational risk.

### Monitoring

Observe performance and conditions.

### Change

Reassess risk.

### Reauthorisation

Re-establish operational authority where required.

### Retirement

Control residual and transition risk.

This is an extension of general AI risk management into a formal operational lifecycle.

## 18. Data Risk Crosswalk

ISO/IEC 23894 recognises data-related AI risks.

D-AIGAAF Module 05 expands data risk into:

- data quality;
- integrity;
- provenance;
- lineage;
- representativeness;
- drift;
- poisoning;
- data handling;
- sharing;
- retention;
- disposal.

The risk chain is:

**Data Quality → Model Behaviour → AI Output → Human Decision → Operational Consequence**

Therefore, data assurance can become an operational-authorisation consideration.

## 19. Security Risk Crosswalk

D-AIGAAF Module 06 treats AI security as a dedicated risk domain.

Relevant risks include:

- adversarial manipulation;
- model compromise;
- data poisoning;
- prompt or input manipulation where applicable;
- unauthorised model changes;
- dependency compromise;
- interface compromise;
- loss of integrity;
- availability failures;
- malicious use.

D-AIGAAF further links security risk to operational authority.

A material change in security posture may require:

**Incident → Assurance Reassessment → Revalidation → Reauthorisation**

## 20. Supply Chain Risk Crosswalk

D-AIGAAF Module 07 expands supply-chain risk beyond procurement.

It includes:

- supplier provenance;
- component traceability;
- dependency concentration;
- strategic dependency;
- continuity;
- supplier assurance;
- external updates;
- changes to externally supplied models or services;
- sovereignty considerations.

The governing question is:

> Can the organisation continue to control and assure the AI capability when critical external dependencies change?

## 21. Operational Environment Risk

This is one of the largest D-AIGAAF extensions.

Risk is assessed against actual or intended operational conditions, including:

- environmental variability;
- degraded infrastructure;
- disconnected operation;
- adversarial conditions;
- information uncertainty;
- electromagnetic conditions where relevant;
- human workload;
- changes in operating context.

A system that is safe in a controlled test environment may not be safe in a materially different operational environment.

Therefore:

**Environment Change → Risk Reassessment → Assurance Review → Reauthorisation Where Required**

## 22. Degraded and Disconnected Operations

D-AIGAAF explicitly considers operations where normal assumptions fail.

Examples of generic governance questions include:

- What happens if communications are lost?
- What happens if external services become unavailable?
- What happens if data becomes stale?
- What happens if sensor quality degrades?
- What happens if human supervision is delayed?
- What happens if an AI dependency fails?
- What happens if the system cannot obtain updated information?

The framework does not assume continuous connectivity as a prerequisite for safe governance.

## 23. Risk and Operational Authorisation

D-AIGAAF creates a direct relationship:

**Risk Assessment → Assurance Evidence → Authorisation Decision**

The authorisation object is:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

This prevents risk assessments from becoming disconnected from operational decisions.

An AI system can therefore be:

- technically functional;
- tested;
- secure;
- maturely governed;

and still not be authorised for a specific mission.

## 24. Risk and Operational Employment

Risk controls continue after authorisation.

During employment, the organisation must monitor:

- performance;
- uncertainty;
- environmental conditions;
- autonomy;
- human control;
- security;
- dependencies;
- incidents;
- changes.

If the assumptions underlying authorisation change materially, continued employment may no longer be justified.

## 25. Incident and Risk Treatment

Incidents may provide evidence that previous risk assumptions were wrong or incomplete.

D-AIGAAF therefore uses:

**Detect → Classify → Protect → Fail-Safe → Investigate → Correct → Recover → Reassess → Reauthorise → Learn**

Incident learning feeds back into:

- risk assessment;
- TEVV;
- assurance;
- controls;
- training;
- operational boundaries;
- authorisation;
- maturity.

## 26. Change-Driven Risk Reassessment

Changes can alter AI risk even where technical performance improves.

Relevant changes include:

- model updates;
- retraining;
- data changes;
- system integration;
- autonomy changes;
- new users;
- new missions;
- environmental changes;
- supplier changes;
- architecture changes;
- security changes.

D-AIGAAF requires change impact assessment and, where necessary:

**Revalidation → Reauthorisation**

## 27. Risk Interactions

D-AIGAAF treats AI risk as an interconnected system.

Examples:

**Data Risk → Model Risk → Decision Risk**

**Security Risk → Integrity Risk → Operational Risk**

**Workforce Risk → Human-Control Risk → Mission Risk**

**Supply-Chain Risk → Availability Risk → Operational Risk**

**Environmental Change → Performance Degradation → Decision Risk**

**Autonomy Increase → Consequence Exposure → Authority Requirement**

The risk model should therefore identify interactions rather than assessing each risk in isolation.

## 28. Uncertainty

Uncertainty is a central risk consideration.

D-AIGAAF requires AI systems and governance processes to recognise and communicate relevant uncertainty.

The framework distinguishes:

- known limitations;
- measurable uncertainty;
- incomplete information;
- distribution shift;
- unknown failure modes;
- uncertainty in human interpretation;
- uncertainty in environmental conditions.

An AI system must not create a false impression of certainty merely because it produces a definitive output.

## 29. Risk Communication

Risk information should be communicated to the people who need it to exercise their responsibilities.

Relevant recipients may include:

- commanders or decision authorities;
- system owners;
- operational users;
- security authorities;
- assurance personnel;
- technical teams;
- governance bodies;
- acquisition authorities.

The information provided should be proportionate to the recipient's authority and decision responsibility.

## 30. Risk Records and Traceability

D-AIGAAF requires risk records to remain connected to evidence and decisions.

The traceability chain is:

**Risk → Cause → Consequence → Control → Test → Evidence → Residual Risk → Decision → Authority → Conditions → Monitoring**

Changes to material assumptions should be traceable to subsequent reassessment or reauthorisation.

## 31. Relationship to ISO/IEC 42001

ISO/IEC 23894 and ISO/IEC 42001 should not be treated as identical.

A useful conceptual relationship is:

**ISO/IEC 42001 → AI Management System**

**ISO/IEC 23894 → AI Risk Management Guidance**

**D-AIGAAF → Defence AI Governance + Risk + Assurance + Authorisation + Employment**

D-AIGAAF can therefore use ISO/IEC 23894 to strengthen risk methodology while using ISO/IEC 42001 principles for organisational management-system integration.

## 32. Relationship to NIST AI RMF

D-AIGAAF also aligns with the risk-management logic of NIST AI RMF.

A conceptual mapping is:

| NIST AI RMF | ISO/IEC 23894 | D-AIGAAF |
|---|---|---|
| GOVERN | Organisational risk governance | Strategy & Governance |
| MAP | Context and risk identification | Mission, Use Case, Environment |
| MEASURE | Risk analysis/evaluation | TEVV, Evidence, Assurance |
| MANAGE | Risk treatment/monitoring | Risk Treatment, Authorisation, Employment |

This demonstrates that D-AIGAAF is intended to interoperate with established AI risk-management practice rather than create an isolated vocabulary.

## 33. Risk Governance and Maturity

D-AIGAAF Module 18 assesses whether risk governance is becoming:

**Initial → Developing → Defined → Managed → Institutionalised**

Maturity should evaluate:

- repeatability;
- effectiveness;
- evidence;
- integration;
- resilience;
- institutionalisation.

A high risk-management maturity score does not mean that every individual AI capability has acceptable residual risk.

## 34. Major D-AIGAAF Extensions

The most significant D-AIGAAF extensions beyond generic AI risk-management guidance are:

1. explicit mission consequence;
2. autonomy as a governance variable;
3. human operational authority;
4. operational environment;
5. degraded/disconnected operation;
6. operational authorisation;
7. operational employment;
8. fail-safe and safe-state governance;
9. change-triggered reauthorisation;
10. defence supply-chain sovereignty;
11. workforce capacity and competence;
12. continuous operational assurance.

These extensions are necessary because defence AI risk may become operationally consequential even where general organisational risk controls are functioning correctly.

## 35. What D-AIGAAF Should Not Claim

D-AIGAAF should not state that:

- implementing D-AIGAAF automatically establishes conformity with ISO/IEC 23894;
- an ISO/IEC 23894-aligned process automatically satisfies D-AIGAAF;
- risk identification automatically establishes acceptable residual risk;
- a high risk-management maturity score authorises an AI capability;
- a technical risk assessment substitutes for operational authorisation; or
- ISO/IEC 23894 is inadequate for general AI risk management.

The correct claim is that D-AIGAAF **integrates and extends AI risk-management concepts for defence operational governance**.

## 36. Crosswalk Maintenance

This crosswalk shall be reviewed when:

- ISO/IEC 23894 is revised or replaced;
- related ISO/IEC AI risk standards materially change;
- D-AIGAAF risk architecture changes;
- new defence AI risks emerge;
- operational experience identifies a material gap;
- new regulatory requirements affect AI risk management; or
- implementation experience identifies a mapping error.

The crosswalk metadata should record:

- ISO edition;
- D-AIGAAF version;
- crosswalk version;
- date reviewed;
- responsible owner;
- reviewer;
- assumptions;
- limitations;
- unresolved interpretation issues.

## 37. Source and Evidence Requirements

A credible crosswalk should use authoritative ISO material and should avoid reproducing copyrighted standard text.

Each substantive mapping should identify:

- ISO/IEC 23894 reference or topic;
- D-AIGAAF reference;
- relationship type;
- rationale;
- defence-specific extension;
- evidence implications;
- limitations.

Where a detailed clause-level mapping is eventually published, it should be based on the licensed or otherwise authorised copy of the standard.

## 38. Overall Assessment

ISO/IEC 23894 is particularly important to D-AIGAAF because risk management is the framework's central connective tissue.

The strongest alignment occurs in:

- context;
- risk identification;
- analysis;
- evaluation;
- treatment;
- monitoring;
- lifecycle integration;
- data;
- security;
- human factors;
- supplier risk;
- continuous improvement.

D-AIGAAF's major contribution is to connect those risk-management activities to explicit defence operational decisions.

The extended chain is:

**AI Risk → Evidence → Assurance → Human Authority → Operational Conditions → Authorisation → Employment → Monitoring → Reassessment**

## 39. Core Rule

> **AI risk management must not end with identifying and treating risk at the organisational or technical level. For consequential defence AI, risk must remain connected to autonomy, human authority, operational environment, operational authorisation, employment, and continuing assurance.**

The integrated model is:

**ISO/IEC 23894 Risk Management**

→ **D-AIGAAF Mission and Risk Context**

→ **Risk and Autonomy Assessment**

→ **Controls**

→ **TEVV**

→ **Evidence**

→ **Assurance**

→ **Operational Authorisation**

→ **Operational Employment**

→ **Continuous Monitoring**

→ **Change / Incident**

→ **Revalidation / Reauthorisation**

→ **Learning**

## 40. Source and Version Record

Primary source:

**ISO/IEC 23894:2023 — Information technology — Artificial intelligence — Guidance on risk management.**

ISO states that the standard provides guidance for organisations that develop, produce, deploy, or use AI-enabled products, systems, and services to manage AI-specific risks and integrate risk management into AI-related activities and functions. ISO identifies the standard as **Edition 1**, published in **February 2023**. citeturn0search0

ISO's AI standards catalogue also lists ISO/IEC 23894:2023 among its published AI standards. citeturn0search6

This crosswalk should be reviewed against the authoritative ISO publication and any subsequent revision, amendment, or related standard that materially changes the AI risk-management landscape.
