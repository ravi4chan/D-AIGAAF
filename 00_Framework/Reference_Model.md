# D-AIGAAF Reference Model

**Defence AI Governance, Assurance & Operational Authorisation Framework**

**Version:** 0.1  
**Status:** Working Reference Model  
**Classification:** Open / Unclassified  
**Repository:** D-AIGAAF

---

## 1. Purpose

The D-AIGAAF Reference Model defines the overall architecture, concepts, lifecycle, relationships and decision logic of the **Defence AI Governance, Assurance & Operational Authorisation Framework (D-AIGAAF)**.

It provides the master conceptual map for the framework and establishes how its individual components fit together.

D-AIGAAF is intended to support the governance of AI-enabled defence capabilities from initial strategic need through acquisition, development, testing, assurance, operational authorisation, employment, continuous monitoring, change, reauthorisation and retirement.

The framework is particularly concerned with AI systems whose outputs or actions may influence:

- operational decisions;
- intelligence and situational awareness;
- targeting and force employment;
- autonomous or semi-autonomous functions;
- logistics and sustainment;
- critical infrastructure;
- cyber and information environments;
- command decision-making; and
- other activities where AI failure may create significant operational consequences.

This Reference Model is a **conceptual and research framework**. It is not itself a military directive, legal instrument, rules of engagement document or substitute for applicable national law, military doctrine or command authority.

---

# 2. Definition

For the purposes of D-AIGAAF:

> **D-AIGAAF is a defence-specific lifecycle framework for governing, securing, testing, assuring, authorising, employing and continuously monitoring AI-enabled capabilities according to mission, environment, autonomy, consequence and human authority.**

The framework treats AI governance as more than a question of whether a model is technically safe or performs well.

The central concern is whether a particular AI capability can be responsibly and demonstrably employed **for a particular mission, in a particular operational context, under a defined level of autonomy and human authority**.

---

# 3. Problem Statement

Defence AI presents a governance problem that differs from many conventional AI applications.

An AI system may:

- operate in environments substantially different from its development environment;
- encounter adversarial or intentionally manipulated inputs;
- operate with degraded communications;
- experience sensor degradation or loss;
- produce uncertain or incorrect outputs;
- be integrated with other systems whose behaviour it does not control;
- receive software, model or dependency updates;
- operate with limited or delayed human intervention;
- influence decisions involving human life or critical infrastructure; or
- behave differently as its operating environment changes.

Consequently, an AI system that performs satisfactorily during development or controlled testing cannot automatically be assumed to be suitable for every operational context.

D-AIGAAF therefore separates:

**Capability → Risk → Evidence → Assurance → Authority → Employment → Monitoring → Reauthorisation**

---

# 4. Central Question

The central question of D-AIGAAF is:

> **Can this AI capability be trusted to perform this mission, under these conditions, at this level of autonomy, with this level of human authority?**

This question deliberately combines five dimensions:

1. **Capability** — What can the system actually do?
2. **Mission** — What is it being used to accomplish?
3. **Environment** — Under what conditions will it operate?
4. **Autonomy** — What decisions or actions can it perform without direct human intervention?
5. **Human Authority** — Who remains responsible for authorising, supervising, overriding or terminating its employment?

---

# 5. Design Philosophy

D-AIGAAF is built around the following principles.

## 5.1 Mission before technology

AI should be governed according to the operational problem it is intended to solve, rather than merely according to the technology being acquired.

## 5.2 Consequence determines scrutiny

The level of assurance required should increase with the potential consequence of failure.

## 5.3 Context matters

An AI system cannot be assured independently of the environment in which it will operate.

## 5.4 Evidence before authority

Operational authority should be supported by appropriate evidence.

## 5.5 Assurance does not equal authorisation

A system may satisfy technical or assurance requirements and still require a separate operational decision before employment.

## 5.6 Authority must be explicit

AI must not acquire operational authority merely because a technical capability exists.

## 5.7 No silent expansion of authority

Changes in capability, autonomy, mission, environment or human control must not silently expand the authority originally granted to an AI system.

## 5.8 Continuous assurance

Operational authorisation is not the end of assurance.

> **Operational authorisation is the beginning of continuous assurance.**

## 5.9 Uncertainty is information

AI systems should communicate uncertainty and known limitations rather than presenting uncertain outputs as established facts.

## 5.10 Traceability

Important AI-enabled decisions and actions should be traceable to the relevant system, configuration, evidence, human authority and operational context to the extent technically and legally practicable.

---

# 6. Defence Operating Context

D-AIGAAF recognises that defence AI may be required to operate across highly variable environments.

These may include:

- conventional operations;
- counter-insurgency and other complex security environments;
- domestic or own-territory operations;
- operations in contested or denied environments;
- mountains and high-altitude environments;
- glaciers and extreme cold;
- deserts and arid environments;
- jungles and difficult terrain;
- maritime and amphibious environments;
- environments with degraded or intermittent communications;
- environments with limited or unavailable internet connectivity;
- environments with degraded, unavailable or manipulated sensors; and
- environments in which an adversary is actively attempting to deceive, disrupt or compromise AI-enabled capabilities.

The framework therefore requires consideration of the **operational environment as an assurance variable**, rather than treating it merely as background information.

---

# 7. Six-Layer Reference Architecture

D-AIGAAF is organised around six primary layers.

## Layer 1 — Strategy & Governance

Establishes:

- strategic objectives;
- governance structures;
- policy;
- accountability;
- authorities;
- roles and responsibilities;
- legal and ethical boundaries; and
- organisational oversight.

## Layer 2 — Mission & Risk

Establishes:

- mission need;
- intended use;
- operational consequences;
- risk;
- mission criticality;
- operational constraints;
- autonomy requirements; and
- acceptable residual risk.

## Layer 3 — System & Trust

Establishes:

- system architecture;
- model and component provenance;
- data dependencies;
- system boundaries;
- security;
- integrity;
- resilience;
- human-machine interfaces;
- explainability and transparency where appropriate; and
- trust characteristics.

## Layer 4 — Assurance

Establishes the evidence required to determine whether the system is sufficiently trustworthy for its intended use.

This includes:

- testing;
- verification;
- validation;
- evaluation;
- red-teaming;
- adversarial testing;
- operational trials;
- security assessment;
- human factors assessment; and
- evidence management.

## Layer 5 — Operational Authorisation

Determines whether a specific AI capability may be employed.

Authorisation is:

- mission-specific;
- environment-specific;
- autonomy-specific;
- authority-specific;
- evidence-based;
- conditional; and
- subject to suspension, review and revocation.

## Layer 6 — Continuous Assurance

Maintains confidence after deployment through:

- monitoring;
- incident reporting;
- performance monitoring;
- drift detection;
- security monitoring;
- configuration control;
- change assessment;
- reassessment;
- revalidation; and
- reauthorisation.

---

# 8. Repository Module Architecture

The six-layer architecture provides the conceptual structure.

The repository implements that architecture through the following numbered modules:

```text
00_Framework/
01_Strategy_and_Governance/
02_Mission_and_Use_Case/
03_Risk_and_Autonomy/
04_AI_Lifecycle/
05_Data_and_Information/
06_AI_Security/
07_Supply_Chain_and_Sovereignty/
08_Human_Authority/
09_TEVV/
10_Operational_Environment/
11_Operational_Authorisation/
12_Operational_Employment/
13_Continuous_Assurance/
14_Incident_and_FailSafe/
15_Change_and_Reauthorisation/
16_Audit_and_Evidence/
17_Workforce/
18_Maturity_Model/
19_Crosswalks/
20_Templates/
21_Legal_and_Policy/
22_Acquisition_and_Procurement/
23_Interoperability_and_Coalition/
24_Architecture_and_Technical_Controls/
25_Documentation_and_Knowledge/
26_Retirement_and_Decommissioning/
27_Implementation/
```

The numbering provides **stable repository navigation**.

It does **not** imply that the modules are executed sequentially.

Many modules are cross-cutting and operate throughout the AI lifecycle.

---

# 9. AI Lifecycle

D-AIGAAF treats AI governance as a lifecycle rather than a procurement-stage activity.

The conceptual lifecycle is:

```text
Strategic Need
      ↓
Mission Need
      ↓
Requirements
      ↓
Risk & Autonomy Definition
      ↓
Acquisition
      ↓
Design / Development
      ↓
Configuration
      ↓
Testing, Evaluation & Assurance
      ↓
Operational Environment Assessment
      ↓
Operational Authorisation
      ↓
Deployment
      ↓
Operational Employment
      ↓
Continuous Monitoring
      ↓
Change / Incident
      ↓
Revalidation
      ↓
Reauthorisation
      ↓
Retirement / Decommissioning
```

Governance, security, human authority, information assurance and legal/policy considerations operate throughout this lifecycle.

---

# 10. The Golden Thread

D-AIGAAF uses the following **Golden Thread** to connect the lifecycle:

> **Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

The Golden Thread provides traceability between:

- why an AI capability exists;
- what it is intended to do;
- what could go wrong;
- what controls were established;
- what evidence was produced;
- what assurance conclusions were reached;
- who authorised employment;
- how the system was actually employed;
- what happened during operation; and
- why continued, restricted, suspended or renewed authority is justified.

---

# 11. Risk → Assurance → Authority

D-AIGAAF separates three concepts that are often treated as one.

## 11.1 Risk

Risk asks:

> **What could go wrong, how likely is it, and how serious could the consequences be?**

## 11.2 Assurance

Assurance asks:

> **Does the available evidence demonstrate that the system is sufficiently trustworthy for its intended use?**

## 11.3 Authority

Authority asks:

> **Given the evidence, residual risk, legal and policy constraints, mission requirements and operational context, should this capability be permitted to operate?**

Therefore:

> **Risk informs assurance. Assurance informs authority. Assurance does not automatically create authority.**

A system can have acceptable technical performance while still being unsuitable for a particular operational context.

---

# 12. Human-AI Command Relationship

D-AIGAAF establishes a clear distinction between **AI capability** and **command authority**.

Unless a specific autonomy level has been separately authorised:

> **AI remains an advisory or decision-support capability and does not possess command authority.**

The existence of an AI recommendation does not transfer responsibility from the authorised human decision-maker to the AI system.

Where appropriate, the framework should preserve a traceable relationship between:

```text
AI System
    ↓
AI Output / Recommendation
    ↓
Human Interpretation
    ↓
Human Decision
    ↓
Command Authority
    ↓
Operational Action
```

This relationship may differ according to the authorised autonomy level.

---

# 13. Operational AI Advisor

A central concept within D-AIGAAF is the **Operational AI Advisor (OAIA)**.

The OAIA is intended to provide an intermediate professional bridge between:

- AI developers;
- system owners and managers;
- technical assurance personnel; and
- military commanders or operational authorities.

The underlying problem is that AI developers and system owners cannot reasonably anticipate every operational context, edge case or employment condition that may arise during military operations.

Conversely, operational commanders may not possess sufficient technical knowledge to independently evaluate all AI-related risks.

The OAIA therefore provides operationally informed AI advice.

Potential responsibilities include:

- translating operational requirements into AI requirements;
- advising commanders on AI capabilities and limitations;
- interpreting assurance evidence;
- identifying operationally significant failure modes;
- advising on appropriate autonomy;
- advising on degraded or contested environments;
- supporting incident assessment;
- supporting change assessment;
- advising whether revalidation or reauthorisation may be required; and
- facilitating communication between operational and technical stakeholders.

The OAIA does **not** replace command authority.

The OAIA advises; the designated authority authorises.

---

# 14. Operational Environment

Operational environment is a first-class component of assurance.

An AI system should be evaluated against the conditions in which it is expected to operate.

Relevant variables may include:

- terrain;
- weather;
- lighting;
- temperature;
- electromagnetic conditions;
- communications availability;
- bandwidth;
- latency;
- sensor availability;
- sensor quality;
- data availability;
- data integrity;
- adversarial interference;
- cyber conditions;
- infrastructure availability;
- human workload;
- human skill level; and
- availability of external support.

The system should not be assumed to retain the same level of performance when these conditions change significantly.

D-AIGAAF therefore uses the concept of an:

> **Authorised Operational Envelope**

The envelope defines the conditions under which the available evidence supports authorised employment.

Operating outside that envelope should trigger appropriate restrictions, reassessment, escalation or suspension depending on the circumstances.

---

# 15. Autonomy & Human Authority

D-AIGAAF uses a working autonomy taxonomy.

This taxonomy is intended as a framework-development construct and should be validated against established defence, legal and technical terminology before formal adoption.

| Level | Description |
|---|---|
| **A0** | No meaningful AI decision-making |
| **A1** | Information, observation or classification |
| **A2** | Analysis, prediction or recommendation |
| **A3** | Recommendation or action requiring explicit human authorisation |
| **A4** | Execution of predefined actions under human supervision |
| **A5** | Independent consequential decision or action |

The autonomy level should never be considered independently of consequence.

A low-autonomy system can still be highly consequential if its recommendations influence critical decisions.

Similarly, increasing autonomy generally increases the need for:

- assurance;
- control;
- monitoring;
- fail-safe mechanisms;
- traceability;
- human competency; and
- explicit operational authority.

---

# 16. Risk Dimensions

D-AIGAAF proposes assessing AI risk across multiple dimensions rather than relying on a single risk score.

## 16.1 Consequence

Potential consequence of failure:

```text
C1 — Negligible
C2 — Minor
C3 — Significant
C4 — Severe
C5 — Catastrophic
```

## 16.2 Autonomy

```text
A0 — No meaningful AI decision
A1 — Information
A2 — Recommendation
A3 — Human-authorised action
A4 — Supervised autonomous execution
A5 — Independent consequential action
```

## 16.3 Mission Criticality

```text
M1 — Non-critical
M2 — Low criticality
M3 — Mission significant
M4 — Mission critical
M5 — Strategic / catastrophic criticality
```

## 16.4 Operational Environment

```text
E1 — Controlled
E2 — Variable
E3 — Complex
E4 — Degraded / contested
E5 — Extreme / adversarial / denied
```

## 16.5 Human Control

```text
H1 — Immediate and effective intervention
H2 — Rapid intervention
H3 — Delayed intervention
H4 — Limited intervention
H5 — No meaningful immediate intervention
```

These dimensions should inform the depth of assurance required.

They should not automatically be converted into a final mathematical risk score without appropriate validation.

---

# 17. AI Security & Loss of Control

AI security within D-AIGAAF extends beyond conventional cybersecurity.

The framework considers risks including:

- malicious manipulation of inputs;
- data poisoning;
- model compromise;
- unauthorised model or software modification;
- adversarial inputs;
- dependency compromise;
- supply-chain compromise;
- unauthorised access;
- model extraction where relevant;
- unsafe system integration;
- unexpected system behaviour; and
- AI-enabled loss of control.

A specific concern is the possibility of an AI-enabled system acting against the interests of its authorised users or operating outside its intended constraints without an external attacker being the initiating cause.

D-AIGAAF therefore requires consideration of:

- authority boundaries;
- system boundaries;
- least-authority design;
- monitoring;
- containment;
- fail-safe mechanisms;
- controlled degradation;
- human override; and
- termination or suspension mechanisms.

---

# 18. Fail-Safe and Emergency Control

A fail-safe mechanism should be treated as a **mandatory last-resort control** for appropriately consequential AI systems.

It may include mechanisms capable of:

- stopping an AI-enabled function;
- restricting system authority;
- reverting to a safer operating mode;
- disconnecting affected functions;
- switching to manual control; or
- otherwise preventing continued unsafe operation.

However, the existence of a technical emergency control does not eliminate the need for governance.

The decision process should distinguish between:

```text
Technical Detection
        ↓
System / Developer Assessment
        ↓
AI System Manager
        ↓
Operational AI Advisor
        ↓
Authorised Command Authority
        ↓
Operational Decision
```

The precise sequence may differ for immediate safety emergencies.

Where delay could itself create unacceptable harm, pre-authorised emergency procedures must allow appropriately empowered personnel or systems to take immediate protective action.

---

# 19. Change and Reauthorisation

AI systems are not static.

Changes may occur to:

- models;
- weights;
- prompts;
- software;
- hardware;
- sensors;
- data;
- interfaces;
- dependencies;
- operating environments;
- security controls; or
- system configuration.

D-AIGAAF distinguishes changes according to whether they can affect operational behaviour.

## 19.1 Minor Change

A change that has no reasonable potential to alter:

- model behaviour;
- system authority;
- operational envelope;
- safety characteristics; or
- mission performance.

Such changes may require controlled documentation without full reauthorisation.

## 19.2 Significant Change

A change that may alter:

- model behaviour;
- decision logic;
- autonomy;
- safety characteristics;
- system boundaries;
- operational environment;
- critical dependencies;
- security posture; or
- mission performance.

Such changes should trigger an appropriate level of:

**assessment → testing → validation → assurance → reauthorisation**

The governing principle is:

> **Behaviour determines change significance.**

---

# 20. Supply Chain and Provenance

AI assurance must extend beyond the immediate system integrator.

D-AIGAAF requires consideration of:

- model origin;
- developer identity;
- system owner;
- supplier;
- critical software;
- hardware dependencies;
- training-data provenance where relevant;
- third-party models;
- open-source components;
- libraries;
- APIs;
- cloud services;
- update mechanisms;
- infrastructure dependencies; and
- components capable of modifying system behaviour.

The objective is to establish sufficient **provenance and accountability** to understand:

> **Who created the capability, what components influence its behaviour, and who can change it?**

Supplier assurance is valuable but does not replace independent assurance by the acquiring or employing organisation where the consequences justify it.

---

# 21. Core Records

D-AIGAAF proposes four core records.

## 21.1 Defence AI Capability Register

**DAICR — Defence AI Capability Register**

Records what AI capabilities exist within the organisation.

It provides enterprise visibility of:

- capability;
- owner;
- purpose;
- mission;
- autonomy;
- risk classification;
- assurance status;
- authorisation status;
- dependencies; and
- lifecycle status.

## 21.2 Defence AI Assurance Record

**DAAR — Defence AI Assurance Record**

Records the evidence supporting trust in the AI capability.

It should capture:

- requirements;
- test plans;
- test results;
- verification;
- validation;
- evaluation;
- red-team results;
- operational trials;
- limitations;
- known failure modes;
- security assessments;
- human factors assessments; and
- outstanding assurance gaps.

## 21.3 Defence AI Operational Authorisation

**DAOA — Defence AI Operational Authorisation**

Records the decision to permit operational employment.

It should specify:

- capability;
- mission;
- environment;
- autonomy;
- authorised operational envelope;
- human authority;
- limitations;
- required controls;
- evidence relied upon;
- fail-safe arrangements;
- system baseline;
- critical dependencies;
- authorising authority;
- validity period;
- review requirements;
- suspension triggers;
- revocation triggers; and
- reauthorisation requirements.

## 21.4 Operational Record

The Operational Record captures what actually happened during employment.

Where appropriate it should record:

- system configuration;
- relevant AI outputs;
- human decisions;
- significant overrides;
- incidents;
- failures;
- degraded conditions;
- changes;
- interventions;
- mission outcomes; and
- lessons identified.

The objective is to create a feedback loop:

> **Operational Experience → Evidence → Assurance → Improved Governance**

---

# 22. Decision Gates

D-AIGAAF uses decision gates throughout the lifecycle.

A conceptual gate structure is:

### Gate 1 — Strategic Need

Is there a legitimate strategic or operational need for an AI-enabled capability?

### Gate 2 — Mission Definition

Is the intended mission, use case and operational context sufficiently defined?

### Gate 3 — Risk & Autonomy

Have consequence, risk, autonomy and human authority been appropriately established?

### Gate 4 — Acquisition / Development

Can the capability be acquired or developed while maintaining required governance, security and assurance?

### Gate 5 — Assurance

Is there sufficient evidence that the system performs as intended and remains within acceptable risk boundaries?

### Gate 6 — Operational Authorisation

Has the appropriate authority explicitly permitted operational employment?

### Gate 7 — Operational Employment

Is the system being used within its authorised operational envelope?

### Gate 8 — Continuous Assurance

Does evidence from actual employment continue to support confidence?

### Gate 9 — Change / Incident

Has a change or incident occurred that could affect the basis of authorisation?

### Gate 10 — Reauthorisation

Does continued employment require renewed authority?

### Gate 11 — Retirement

Should the capability continue to possess operational authority?

---

# 23. Testing, Evaluation, Verification and Validation

D-AIGAAF adopts a broad **TEVV** approach.

Eight assurance dimensions are proposed:

1. Technical Performance
2. Reliability & Robustness
3. Adversarial Resilience
4. Operational Environment
5. Human-AI Interaction
6. Security & Integrity
7. Autonomy & Control
8. Mission Effectiveness

Evidence should progressively increase in operational relevance:

```text
Laboratory
    ↓
Controlled Environment
    ↓
Representative Environment
    ↓
Adversarial / Red-Team Testing
    ↓
Operational Environment
    ↓
Mission-Level Evaluation
    ↓
Operational Authorisation
```

The terms are distinguished as follows:

### Testing

> Did we execute the test correctly?

### Verification

> Did we build the system according to specified requirements?

### Validation

> Does the system satisfy the intended operational need?

### Evaluation

> What does the evidence tell us about effectiveness, limitations and risk?

---

# 24. Evidence and Traceability

Assurance conclusions should be traceable to evidence.

The framework should maintain relationships between:

```text
Requirement
    ↓
Risk
    ↓
Control
    ↓
Test
    ↓
Evidence
    ↓
Assurance Finding
    ↓
Residual Risk
    ↓
Authorisation Decision
```

This creates an auditable basis for operational authority.

Where evidence is incomplete, the gap should be explicitly recorded rather than hidden within an overall assurance statement.

---

# 25. Situational Awareness

Situational awareness is a critical operational consideration for AI-enabled command systems.

AI should support commanders by helping establish:

- what is known;
- what is unknown;
- what is estimated;
- what is uncertain;
- what has changed;
- what assumptions underpin an assessment; and
- what information may invalidate the current assessment.

The framework therefore treats:

> **Uncertainty as information.**

An AI system should not communicate confidence beyond what the available evidence justifies.

Avoiding confident but unsupported outputs is particularly important when AI contributes to consequential decisions.

---

# 26. Human Authority and Accountability

D-AIGAAF requires explicit identification of relevant human authorities.

Depending on the capability, this may include:

- system owner;
- technical authority;
- information assurance authority;
- security authority;
- operational AI advisor;
- commander;
- designated authorising authority; and
- other legally or organisationally responsible personnel.

The framework seeks to establish:

> **Who had the authority to decide, what information they had, what AI contribution they received, and what authority the AI system itself possessed.**

Where a commander rejects or bypasses an AI recommendation, the framework may require the decision to be recorded when the consequence or policy warrants it.

The purpose is not to force commanders to follow AI recommendations.

It is to preserve **decision accountability and learning**.

---

# 27. Operational Trust

D-AIGAAF uses the following conceptual model:

> **Operational Trust = Capability + Evidence + Context + Human Authority + Continuous Assurance**

This is **not a mathematical formula**.

It expresses the proposition that operational trust cannot be derived from model accuracy alone.

A system may be technically capable but unsuitable for an operational environment.

A system may have extensive test evidence but lack appropriate authority.

A system may be authorised but no longer trustworthy if its environment, configuration or behaviour changes significantly.

Operational trust therefore requires all five elements to remain aligned.

---

# 28. Operational Authorisation Model

Operational authorisation binds five variables:

> **AI Capability × Mission × Environment × Autonomy × Human Authority**

Authorisation should therefore not simply state:

> "System X is approved."

Instead, it should establish:

> "System X is authorised for Mission Y, within Environment Z, at Autonomy Level A, under Human Authority H, subject to defined conditions."

This prevents authority from silently expanding from one mission or environment to another.

---

# 29. Operational Authorisation States

A common status model is:

```text
Proposed
   ↓
Under Assurance
   ↓
Conditionally Authorised
   ↓
Operationally Authorised
   ↓
Restricted
   ↓
Suspended
   ↓
Revoked / Retired
```

Transitions should be supported by documented decisions and evidence appropriate to the risk.

Authorisation may be:

- time-limited;
- condition-limited;
- mission-limited;
- environment-limited;
- autonomy-limited; or
- authority-limited.

---

# 30. No Silent Expansion of Authority

One of the core D-AIGAAF principles is:

> **An AI system must not acquire additional operational authority merely because its technical capability has expanded.**

For example, an AI initially authorised for:

- information analysis

does not automatically become authorised for:

- consequential recommendations;

and an AI authorised for:

- recommendations

does not automatically become authorised for:

- autonomous action.

Changes in authority require explicit consideration and, where necessary, additional assurance and authorisation.

---

# 31. Controlled Degradation

AI capabilities may encounter conditions under which normal performance cannot be maintained.

D-AIGAAF therefore considers controlled degradation as an explicit design and assurance requirement.

Possible responses include:

```text
Normal Operation
      ↓
Degraded Operation
      ↓
Restricted Function
      ↓
Human-Controlled Mode
      ↓
Safe State / Suspension
```

The appropriate response depends on:

- mission;
- consequence;
- autonomy;
- operational environment;
- human availability; and
- system architecture.

The key requirement is that degraded behaviour should be **understood, bounded and controlled** rather than discovered unexpectedly during operations.

---

# 32. Information Assurance and Data Integrity

AI output is dependent on the information available to the system.

D-AIGAAF therefore distinguishes:

> **Information → Processing → Intelligence / Assessment → Decision**

The framework recognises that failures may originate before model inference itself.

Relevant concerns include:

- incorrect information;
- stale information;
- manipulated information;
- incomplete information;
- ambiguous information;
- unavailable information; and
- loss of provenance.

Consequently:

> **Data integrity is an operational security concern.**

---

# 33. Procurement and Acquisition

Governance requirements should begin before an AI system enters service.

Acquisition processes should consider:

- ownership;
- provenance;
- intellectual property;
- model access;
- update control;
- dependency management;
- supplier assurance;
- security;
- data requirements;
- testing rights;
- auditability;
- interoperability;
- portability;
- lifecycle support;
- incident reporting;
- change notification; and
- revalidation requirements.

Procurement should preserve the ability of the employing organisation to maintain assurance throughout the system lifecycle.

---

# 34. Workforce and Competency

Effective AI governance requires personnel capable of understanding both AI and operational consequences.

Relevant competencies may include:

- AI fundamentals;
- AI security;
- AI safety;
- risk management;
- assurance;
- data and information assurance;
- operational analysis;
- human-machine interaction;
- legal and policy considerations;
- procurement;
- system engineering; and
- command decision-making.

The OAIA concept is one potential mechanism for bridging technical and operational expertise.

---

# 35. Relationship With Existing Frameworks

D-AIGAAF is not intended to replace established AI governance, risk-management, safety, cybersecurity, engineering or legal frameworks.

Instead, it provides a **defence operational layer** that can integrate and extend existing approaches.

Potential relationships include:

```text
AI Governance
      +
AI Risk Management
      +
AI Safety
      +
Cybersecurity
      +
Systems Engineering
      +
TEVV
      +
Legal / Policy
      +
Defence Operational Authority
      ↓
D-AIGAAF
```

The framework should therefore maintain crosswalks to relevant national, international, defence, technical and industry standards as the framework matures.

---

# 36. Framework Boundaries

D-AIGAAF does not attempt to provide:

- rules of engagement;
- tactical employment doctrine;
- classified operational procedures;
- weapon-specific employment instructions;
- intelligence collection procedures;
- national security classification guidance;
- legal advice; or
- replacement command authorities.

The framework is intended to establish governance and assurance structures within which appropriate authorities can make operational decisions.

Specific implementation must comply with applicable:

- national law;
- international law;
- military doctrine;
- policy;
- rules and regulations;
- security requirements; and
- command authorities.

---

# 37. Implementation Philosophy

D-AIGAAF should be implemented incrementally.

An organisation should not attempt to build every framework component simultaneously.

A representative implementation sequence may be:

### Phase 1 — Governance and Inventory

Establish:

- governance authority;
- AI policy;
- roles;
- Defence AI Capability Register;
- initial risk classification.

### Phase 2 — Risk and Assurance

Establish:

- risk methodology;
- autonomy framework;
- TEVV methodology;
- assurance requirements;
- evidence management.

### Phase 3 — Operational Authorisation

Establish:

- authorisation authorities;
- DAAR;
- DAOA;
- operational envelopes;
- suspension and revocation mechanisms.

### Phase 4 — Operational Employment

Establish:

- monitoring;
- incident reporting;
- operational records;
- human-AI decision traceability.

### Phase 5 — Continuous Assurance

Establish:

- change assessment;
- revalidation;
- reauthorisation;
- drift monitoring;
- continuous evidence collection.

### Phase 6 — Enterprise Maturity

Expand the framework into:

- acquisition;
- supply chain;
- workforce;
- interoperability;
- coalition operations;
- architecture;
- audit;
- legal/policy integration; and
- enterprise-level governance.

---

# 38. Implementation Workstreams

D-AIGAAF can be implemented through eight broad workstreams:

| Workstream | Primary Focus |
|---|---|
| **Governance** | Authorities, accountability and oversight |
| **Policy** | Rules, standards and organisational policy |
| **Risk** | Risk classification and risk treatment |
| **Assurance** | TEVV, evidence and assurance |
| **Technology** | Architecture, security and technical controls |
| **Operations** | Operational employment and monitoring |
| **Workforce** | Skills, training and competency |
| **Supply Chain** | Procurement, provenance and sovereignty |

These workstreams are mutually dependent and should not be treated as isolated programmes.

---

# 39. Maturity Model

D-AIGAAF should ultimately support an organisational maturity model.

A conceptual maturity progression is:

```text
Level 1 — Ad Hoc
AI capabilities developed or acquired without consistent governance.

Level 2 — Managed
Basic inventory, policy and risk processes established.

Level 3 — Assured
Formal assurance, TEVV and evidence processes established.

Level 4 — Authorised
Mission- and context-specific operational authorisation established.

Level 5 — Continuously Assured
Continuous monitoring, revalidation, reauthorisation and lifecycle governance established.

Level 6 — Enterprise Integrated
AI governance is integrated with acquisition, operations, security, command, workforce and strategic decision-making.
```

The maturity model should be developed further as implementation evidence becomes available.

---

# 40. Continuous Improvement

D-AIGAAF is intended to evolve.

Operational experience, incidents, assurance findings, technological changes and changes in the threat environment should feed back into the framework.

The continuous improvement cycle is:

```text
Experience
    ↓
Observation
    ↓
Evidence
    ↓
Analysis
    ↓
Assurance Finding
    ↓
Control / Policy Change
    ↓
Testing
    ↓
Implementation
    ↓
Monitoring
    ↓
Experience
```

This prevents the framework from becoming a static compliance document.

---

# 41. Core D-AIGAAF Principles

The following principles form the current foundational set.

### Authority

1. **Primacy of Command Authority**
2. **No Authority Beyond Law and Policy**
3. **No Silent Expansion of Authority**
4. **Conditional Operational Authority**

### Assurance

5. **Mission- and Context-Dependent Assurance**
6. **No Authority Without Evidence**
7. **Continuous Assurance**
8. **Evidence Must Be Traceable**
9. **Burden of Evidence Scales With Consequence**

### Security

10. **Adversarial Robustness**
11. **Least Authority**
12. **Defence in Depth**
13. **No AI Self-Expansion of Authority**

### Operations

14. **Operational Independence and Resilience**
15. **Controlled Degradation**
16. **Authorised Operational Envelope**
17. **AI Recommendation Is Not Command Authority**

### Human Authority

18. **Meaningful Human Control**
19. **Traceable Human Authority**
20. **Qualified Human Authority**

### Information

21. **Information Before Intelligence**
22. **Provenance by Design**
23. **Uncertainty Is Information**
24. **Data Integrity Is Operational Security**

### Acquisition and Supply Chain

25. **Procurement Must Preserve Assurance**
26. **Supplier Assurance Does Not Replace Independent Assurance**
27. **No Blind Updates**
28. **Sovereignty Must Be Assessed**

### Lifecycle

29. **Behaviour Determines Change Significance**
30. **Retirement Must Remove Authority**
31. **Operational Experience Becomes Assurance Evidence**

---

# 42. The D-AIGAAF Decision Logic

The framework can ultimately be represented through the following decision logic:

```text
                 STRATEGIC NEED
                       ↓
                  MISSION NEED
                       ↓
             DEFINE OPERATIONAL USE
                       ↓
          DEFINE CONSEQUENCE & RISK
                       ↓
             DEFINE AUTONOMY LEVEL
                       ↓
          DEFINE HUMAN AUTHORITY
                       ↓
          DEFINE OPERATIONAL ENVELOPE
                       ↓
             DEFINE REQUIREMENTS
                       ↓
              DEVELOP / ACQUIRE
                       ↓
               TEST & EVALUATE
                       ↓
                  BUILD EVIDENCE
                       ↓
                    ASSURE
                       ↓
             ASSESS RESIDUAL RISK
                       ↓
             OPERATIONAL AUTHORITY
                       ↓
                  AUTHORISE
                       ↓
                   EMPLOY
                       ↓
                 MONITOR
                       ↓
          INCIDENT / CHANGE / DRIFT?
                 ↙           ↘
               NO             YES
                ↓              ↓
             CONTINUE       ASSESS CHANGE
                                ↓
                         REVALIDATE / ASSURE
                                ↓
                           REAUTHORISE
                                ↓
                             EMPLOY
```

---

# 43. Master D-AIGAAF Model

The entire framework can be reduced to the following conceptual relationship:

```text
                    STRATEGY
                       │
                       ▼
                 MISSION NEED
                       │
                       ▼
              ┌─────────────────┐
              │      RISK       │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │   REQUIREMENTS  │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │     SYSTEM      │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │      TEVV       │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │    ASSURANCE    │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │    AUTHORITY    │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │    EMPLOYMENT   │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │    MONITORING   │
              └────────┬────────┘
                       │
                       ▼
              CHANGE / INCIDENT
                       │
                       ▼
                REVALIDATION
                       │
                       ▼
                REAUTHORISATION
                       │
                       └───────────────► CONTINUOUS ASSURANCE
```

Across every stage operate the cross-cutting functions:

```text
Human Authority
AI Security
Information Assurance
Legal & Policy
Workforce & Competency
Supply Chain & Sovereignty
```

---

# 44. Summary

D-AIGAAF is built around a simple proposition:

> **An AI capability should not be considered operationally trustworthy merely because it works. It must be demonstrated to work for the intended mission, within the intended environment, at the intended level of autonomy, under clearly defined human authority, and remain subject to continuous assurance.**

The framework therefore connects:

**Mission → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Reauthorisation**

The ultimate objective is not simply to create safer AI.

It is to create a system of **defensible operational trust and accountable authority** for the employment of AI in defence.

---

## Status of This Reference Model

This document is a **working Version 0.1 reference model**.

The concepts, taxonomies, terminology and decision structures should be progressively validated against:

- established AI risk-management frameworks;
- defence AI governance approaches;
- systems engineering and assurance practices;
- cybersecurity and information assurance standards;
- relevant legal and policy requirements;
- operational requirements; and
- practical implementation experience.

The framework should evolve through evidence rather than through terminology alone.
