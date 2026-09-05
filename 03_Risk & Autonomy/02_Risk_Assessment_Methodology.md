# Risk Assessment Methodology

## Purpose

The D-AIGAAF Risk Assessment Methodology provides a structured method for identifying, analysing, evaluating and treating risks arising from the use of AI-enabled capabilities in defence missions.

The methodology recognises that **AI risk is not determined by the model alone**.

Risk emerges from the interaction between:

**AI Capability + Mission + Use Case + Context + Constraints + Autonomy + Human Control + Dependencies**

The objective is to determine whether identified risks are sufficiently understood, controlled and evidenced to support the next governance or operational decision.

---

## 1. Core Principle

> **Risk assessment must evaluate the AI-enabled capability in its intended mission and operational context, not merely evaluate the underlying model.**

A model may perform well in laboratory conditions while the deployed capability presents unacceptable risk because of:

- poor or manipulated information;
- degraded sensors;
- communications loss;
- adversarial conditions;
- excessive autonomy;
- inadequate human control;
- critical dependencies;
- inappropriate operating conditions;
- unclear authority;
- unexpected interactions with other systems.

Risk assessment must therefore remain connected to the D-AIGAAF Golden Thread.

---

## 2. Risk Assessment Flow

The core assessment process is:

```text
Define Mission and Use Case
        ↓
Identify AI Capability
        ↓
Define Operational Context and Constraints
        ↓
Determine Consequence
        ↓
Assess Mission Criticality
        ↓
Assess Autonomy
        ↓
Assess Human Control
        ↓
Identify Threats, Dependencies and Failure Modes
        ↓
Determine Inherent Risk
        ↓
Identify and Evaluate Controls
        ↓
Determine Residual Risk
        ↓
Identify Evidence and Assurance Requirements
        ↓
Determine Risk Acceptance Authority
        ↓
Link Risk Position to Operational Authorisation
        ↓
Monitor and Reassess
```

---

## 3. Scope of Assessment

A risk assessment should consider the complete AI-enabled capability where relevant, including:

- AI model;
- software;
- hardware;
- sensors;
- data;
- interfaces;
- communications;
- computing infrastructure;
- users;
- human decision makers;
- operators;
- external services;
- supporting systems;
- suppliers;
- critical dependencies;
- security controls;
- safety controls;
- operational procedures.

The assessment should not stop at the model boundary where downstream components can materially affect mission outcomes.

---

## 4. Risk Identification

Risk identification should consider what could cause the capability to:

- fail to achieve its mission objective;
- produce an incorrect output;
- produce an unsafe recommendation;
- generate misleading or overconfident information;
- act outside its authorised boundaries;
- lose human control;
- become unavailable;
- behave unpredictably;
- be manipulated;
- be compromised;
- create unintended consequences;
- cause harm to personnel or civilians;
- compromise information;
- affect critical infrastructure;
- create cascading failures;
- create unsafe interaction with another system;
- undermine situational awareness;
- operate incorrectly in degraded conditions.

Risk identification should include both known failure modes and reasonably foreseeable unknowns.

---

## 5. Risk Dimensions

D-AIGAAF uses multiple dimensions rather than relying on a single universal risk score.

### 5.1 Consequence

The potential severity of harm if the capability fails, is misused or behaves unexpectedly.

Working construct:

- **C1 — Minimal**
- **C2 — Limited**
- **C3 — Significant**
- **C4 — Severe**
- **C5 — Critical / Catastrophic**

The consequence category should reflect credible mission-level outcomes rather than model-level error alone.

---

### 5.2 Mission Criticality

The importance of the capability to the mission.

Working construct:

- **M1 — Non-Critical**
- **M2 — Supporting**
- **M3 — Important**
- **M4 — Mission-Critical**
- **M5 — Strategic / Critical**

Mission criticality and consequence are related but not identical.

A system may be mission-critical without directly causing physical harm, while a non-mission-critical system may still create significant safety or security consequences.

---

### 5.3 Autonomy

The degree to which the AI can independently influence or execute decisions and actions.

Use the D-AIGAAF autonomy scale:

**A0 → A1 → A2 → A3 → A4 → A5**

Higher autonomy generally requires stronger scrutiny where consequences are significant.

---

### 5.4 Operational Environment

Risk should account for the conditions in which the capability is expected to operate.

Relevant factors include:

- normal conditions;
- degraded conditions;
- communications-denied conditions;
- information-degraded conditions;
- adverse weather;
- difficult terrain;
- sensor degradation;
- electronic interference;
- cyber threats;
- adversarial manipulation;
- high workload;
- rapidly changing conditions;
- disconnected or intermittent networks.

Working construct:

- **E1 — Controlled**
- **E2 — Representative**
- **E3 — Complex**
- **E4 — Adversarial / Degraded**
- **E5 — Highly Dynamic / Contested**

The categories are contextual indicators, not universal numerical scores.

---

### 5.5 Human Control

Assess the effectiveness of human control rather than merely the presence of a human.

Working construct:

- **H1 — Direct Human Control**
- **H2 — Frequent Human Review**
- **H3 — Supervised Control**
- **H4 — Limited Intervention**
- **H5 — Minimal or No Immediate Human Intervention**

Assessment should consider information, authority, competence, time, independence, intervention capability and accountability.

---

### 5.6 Information Integrity

Consider the possibility that information used by the AI is:

- incomplete;
- inaccurate;
- stale;
- corrupted;
- contradictory;
- manipulated;
- unavailable;
- generated by another unreliable system.

Information integrity should be assessed as an operational risk, not merely a data-quality issue.

---

### 5.7 Security

Consider risks arising from:

- cyber compromise;
- adversarial inputs;
- model manipulation;
- compromised software;
- malicious dependencies;
- insider threats;
- supply-chain compromise;
- unauthorised access;
- loss of configuration integrity.

---

### 5.8 Reliability and Robustness

Consider whether the capability continues to behave acceptably when:

- inputs change;
- data quality falls;
- sensors degrade;
- communications fail;
- workloads increase;
- operating conditions change;
- unexpected inputs occur.

---

### 5.9 Dependency Risk

Consider dependence on:

- communications;
- navigation;
- sensors;
- power;
- computing;
- data services;
- cloud or external services;
- other AI systems;
- software libraries;
- suppliers;
- command systems;
- supporting infrastructure.

Critical dependencies should be explicitly identified.

---

### 5.10 Uncertainty

Assess uncertainty relating to:

- model behaviour;
- data;
- operating environment;
- threat conditions;
- human interpretation;
- system interactions;
- unknown failure modes;
- evidence limitations.

> **Unknowns are themselves part of the risk picture.**

---

## 6. Inherent Risk

Inherent risk is the risk associated with the capability **before considering the effectiveness of additional risk controls**.

The assessment should consider:

**Mission + Capability + Use Case + Context + Constraints + Autonomy → Inherent Risk**

Inherent risk should not be reduced simply because controls are assumed to exist.

Controls must subsequently be evaluated for effectiveness.

---

## 7. Risk Controls

Risk controls should address identified causes or consequences of risk.

Possible control categories include:

### Preventive Controls
Designed to prevent unsafe behaviour.

Examples include:

- authorised operating boundaries;
- access controls;
- constrained autonomy;
- validated inputs;
- configuration controls;
- technical safeguards.

### Detective Controls
Designed to identify unsafe or abnormal behaviour.

Examples include:

- monitoring;
- anomaly detection;
- integrity checks;
- independent verification;
- human review;
- audit logging.

### Corrective Controls
Designed to reduce harm after an abnormal condition occurs.

Examples include:

- reduced autonomy;
- controlled degradation;
- human intervention;
- isolation;
- suspension;
- fail-safe mechanisms;
- recovery procedures.

### Governance Controls
Designed to prevent inappropriate use or authority.

Examples include:

- approval;
- operational authorisation;
- delegated decision rights;
- risk acceptance;
- independent assurance;
- change control;
- reauthorisation.

---

## 8. Control Effectiveness

A control should not be treated as effective merely because it is documented.

Assessment should consider:

1. Is the control implemented?
2. Is it technically effective?
3. Is it operationally effective?
4. Has it been tested?
5. Has it been tested under relevant conditions?
6. Can it fail?
7. Can it be bypassed?
8. Is there evidence supporting its effectiveness?
9. Is responsibility for the control clear?
10. Is the control continuously monitored where necessary?

Control effectiveness should be recorded as evidence-based wherever practicable.

---

## 9. Residual Risk

Residual risk is the risk remaining after implemented and evidenced controls are considered.

The relationship is:

**Inherent Risk → Controls → Residual Risk**

Residual risk should be reassessed whenever:

- controls change;
- evidence changes;
- system behaviour changes;
- mission changes;
- environment changes;
- threats change;
- dependencies change;
- incidents occur;
- autonomy changes.

Residual risk does not automatically mean acceptable risk.

---

## 10. Risk Evaluation

Risk evaluation asks whether the residual risk is:

- acceptable;
- acceptable only with conditions;
- requires additional controls;
- requires reduced autonomy;
- requires restricted employment;
- requires further assurance;
- requires escalation;
- unacceptable for the intended use.

The evaluation should consider:

- consequence;
- mission criticality;
- autonomy;
- human control;
- operational environment;
- uncertainty;
- evidence quality;
- legal and policy requirements;
- available alternatives;
- reversibility;
- effectiveness of controls;
- authority of the risk decision maker.

---

## 11. Risk Treatment

Risk treatment may include:

1. **Avoid** — do not use the AI capability for the proposed purpose.
2. **Reduce** — modify the capability, mission, environment or process to reduce risk.
3. **Control** — introduce technical, procedural, human or governance safeguards.
4. **Transfer or Share** — allocate appropriate responsibilities where legally and organisationally appropriate.
5. **Accept** — accept residual risk through an authorised decision.
6. **Monitor** — maintain controls and observe the risk where continued operation is justified.

Risk acceptance should not be used as a substitute for missing evidence or ineffective controls.

---

## 12. Risk Acceptance

Risk acceptance is a formal decision to accept a defined residual risk.

The person or body accepting the risk must have:

- appropriate authority;
- sufficient information;
- access to relevant evidence;
- understanding of limitations;
- understanding of potential consequences;
- awareness of alternatives;
- authority appropriate to the consequence and scope of the risk.

> **Risk acceptance is not the same as operational authorisation.**

An authority may accept residual risk while a separate authority remains responsible for deciding whether the capability may be operationally employed.

---

## 13. Risk and Operational Authorisation

Risk assessment informs operational authorisation but does not grant operational authority.

The authorisation decision should consider:

**Risk + Assurance + Mission + Environment + Autonomy + Human Authority**

Operational authorisation should specify the conditions under which the residual risk is accepted.

If those conditions change materially, the authorisation may require reassessment or reauthorisation.

---

## 14. Evidence Requirements

Each significant risk claim should be linked to appropriate evidence.

Evidence may include:

- test results;
- verification results;
- validation results;
- evaluation reports;
- red-team findings;
- operational trials;
- security assessments;
- human factors assessments;
- reliability data;
- incident records;
- configuration records;
- supplier evidence;
- independent assurance findings.

The required evidence should be proportional to:

- consequence;
- autonomy;
- mission criticality;
- uncertainty;
- environmental complexity;
- adversarial exposure;
- human-control limitations.

---

## 15. Risk Assessment Confidence

A risk assessment should distinguish between:

- **Known** — supported by sufficient evidence;
- **Partially Known** — evidence exists but has limitations;
- **Uncertain** — evidence is insufficient or conflicting;
- **Unknown** — relevant behaviour or conditions have not been adequately assessed.

Confidence should not be confused with risk severity.

A low-confidence assessment may itself require additional assurance even where the preliminary risk appears moderate.

---

## 16. Scenario-Based Assessment

Risk should be evaluated against relevant operational scenarios.

At minimum, consider where applicable:

- normal operation;
- degraded operation;
- communications loss;
- information degradation;
- sensor degradation;
- adversarial conditions;
- cyber compromise;
- human overload;
- human disagreement;
- loss of supporting dependencies;
- autonomous behaviour;
- boundary violation;
- fail-safe activation;
- recovery;
- foreseeable misuse.

Particular attention should be given to combinations of conditions.

Example:

**Poor Data + Communications Loss + High Human Workload + High Autonomy**

may create a materially different risk from each condition considered separately.

---

## 17. Worst Credible Consequence

Risk assessment should identify the **worst credible consequence**, not merely the most likely consequence.

This is particularly important for capabilities that can:

- affect human life;
- initiate physical actions;
- influence use of force;
- affect critical infrastructure;
- alter operational decisions;
- operate without immediate human intervention.

The worst credible consequence should inform the required level of assurance and authority.

---

## 18. Risk Assessment Record

A D-AIGAAF Risk Assessment Record should contain, as applicable:

| Field | Description |
|---|---|
| Risk ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Supported mission |
| Use Case | Specific intended use |
| Context | Operational conditions |
| Constraints | Material constraints |
| Autonomy | Authorised/assessed autonomy |
| Human Control | Human-control assessment |
| Consequence | Consequence category |
| Mission Criticality | Mission criticality |
| Environment | Operational environment |
| Threats | Relevant threats |
| Dependencies | Critical dependencies |
| Failure Modes | Identified failure modes |
| Inherent Risk | Pre-control risk |
| Controls | Risk controls |
| Control Evidence | Evidence of effectiveness |
| Residual Risk | Post-control risk |
| Uncertainty | Key unknowns and limitations |
| Risk Treatment | Treatment decision |
| Risk Acceptance | Acceptance decision/authority |
| Assurance Requirement | Required assurance |
| Authorisation Link | Related operational authority |
| Review Trigger | Conditions requiring reassessment |
| Owner | Responsible risk owner |
| Date | Assessment date |
| Status | Current status |

---

## 19. Risk Status

A common status model is:

**Identified → Analysed → Treated → Assessed → Accepted / Rejected → Monitored**

Additional statuses may include:

- Open;
- Escalated;
- Conditionally Accepted;
- Under Review;
- Invalidated;
- Closed.

Risk status should remain linked to the relevant use case and operational authorisation.

---

## 20. Reassessment Triggers

Risk assessment should be reconsidered following:

- material changes to the AI model;
- software or system changes;
- changes to autonomy;
- changes to mission;
- changes to use case;
- changes to operational environment;
- changes to threat conditions;
- changes to dependencies;
- changes to human control arrangements;
- security incidents;
- unexpected AI behaviour;
- significant performance degradation;
- new evidence;
- evidence becoming obsolete;
- changes in law or policy;
- changes in doctrine or operational procedures;
- incidents or near misses.

> **Incident, change or emerging risk can change the assurance position.**

---

## 21. Risk Monitoring

Risk monitoring should determine whether:

- assumptions remain valid;
- controls remain effective;
- performance remains within acceptable limits;
- operational conditions remain within the authorised envelope;
- threats have changed;
- dependencies remain available;
- human control remains effective;
- uncertainty has increased;
- new failure modes have emerged.

Monitoring should feed back into:

**Risk → Assurance → Authorisation → Employment**

and, where required:

**Change/Incident → Reassessment → Revalidation → Reauthorisation**

---

## 22. Risk and the Operational AI Advisor

Where a capability has significant operational consequence or complexity, the **Operational AI Advisor (OAIA)** may support the command authority by:

- interpreting AI-related risk;
- explaining system limitations;
- identifying operational assumptions;
- assessing whether proposed employment remains within the risk envelope;
- advising on autonomy and human-control implications;
- identifying when additional technical or operational expertise is required;
- supporting interpretation of assurance evidence.

The OAIA advises.

**Operational authority remains with the appropriately empowered human authority.**

---

## 23. Risk Governance Failure Modes

D-AIGAAF should guard against:

- treating model accuracy as total mission risk;
- using one numerical score to hide important risk dimensions;
- ignoring human-control risk;
- ignoring loss-of-control risk;
- assuming benign operating conditions;
- treating uncertainty as zero;
- accepting risk without appropriate authority;
- assuming controls are effective without evidence;
- relying solely on supplier risk assessments;
- allowing outdated evidence to support current risk decisions;
- failing to reassess after material changes;
- confusing risk acceptance with operational authorisation;
- allowing technical capability to determine acceptable risk;
- failing to account for dependency or supply-chain risk;
- ignoring interactions between multiple risk dimensions.

---

## 24. Relationship to the Golden Thread

The risk assessment must remain traceable:

**Mission Need → Use Case → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Every significant risk should be traceable to:

- the mission or use case that creates it;
- the requirement or control intended to address it;
- the evidence supporting the control;
- the resulting assurance position;
- the authority that accepted or constrained the risk;
- the operational outcome.

---

## 25. Core Rules

D-AIGAAF adopts the following rules:

1. **Risk belongs to the AI-enabled capability in context, not merely the model.**
2. **Consequence, autonomy, mission criticality, environment and human control must be considered explicitly.**
3. **Inherent risk must be assessed before relying on controls.**
4. **Controls require evidence of effectiveness.**
5. **Residual risk does not automatically mean acceptable risk.**
6. **Risk acceptance requires appropriate authority.**
7. **Risk acceptance does not itself create operational authority.**
8. **Higher consequence and autonomy require stronger evidence and assurance.**
9. **Uncertainty and unknowns must be visible.**
10. **Risk must be continuously monitored.**
11. **Material changes and incidents can invalidate previous risk conclusions.**
12. **Risk assessment must remain connected to operational authorisation.**

---

## 26. Summary Model

```text
MISSION
   ↓
USE CASE
   ↓
CONTEXT + CONSTRAINTS
   ↓
CONSEQUENCE + CRITICALITY
   ↓
AUTONOMY + HUMAN CONTROL
   ↓
THREATS + DEPENDENCIES + FAILURE MODES
   ↓
INHERENT RISK
   ↓
CONTROLS
   ↓
EVIDENCE
   ↓
RESIDUAL RISK
   ↓
RISK EVALUATION
   ↓
RISK ACCEPTANCE / TREATMENT
   ↓
ASSURANCE
   ↓
OPERATIONAL AUTHORISATION
   ↓
EMPLOYMENT
   ↓
MONITORING
   ↓
REASSESSMENT / REAUTHORISATION
```

The purpose of the methodology is not to eliminate all risk.

It is to ensure that **risk is explicitly understood, appropriately treated, supported by evidence, accepted by the right authority, and continuously reconsidered as the AI capability and operational environment change.**
