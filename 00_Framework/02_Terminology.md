# D-AIGAAF Terminology

**Defence AI Governance, Assurance & Operational Authorisation Framework**

**Version:** 0.1  
**Status:** Working Draft  
**Classification:** Open / Unclassified

---

## 1. Purpose

This document establishes the controlled vocabulary for D-AIGAAF.

D-AIGAAF uses several terms that have different meanings across artificial intelligence, defence, safety, security, software engineering, risk management and governance communities.

The purpose of this document is to establish a consistent meaning for terms used throughout the framework.

Where a D-AIGAAF definition is a working construct rather than an established external definition, this is explicitly identified.

---

# 2. How to Use This Terminology

The terminology hierarchy is:

**Term → Definition → D-AIGAAF Interpretation → Application**

Terms in this document should be used consistently across:

- policies;
- requirements;
- risk assessments;
- TEVV;
- assurance records;
- operational authorisations;
- incident records;
- audit evidence; and
- implementation guidance.

A term should not acquire a different meaning merely because it appears in a different D-AIGAAF module.

Where an external standard uses a materially different definition, the relevant D-AIGAAF module should identify the difference rather than silently mixing definitions.

---

# 3. Core Framework Terms

## 3.1 D-AIGAAF

**Definition:** Defence AI Governance, Assurance & Operational Authorisation Framework.

**D-AIGAAF interpretation:** A defence-specific lifecycle framework for governing, securing, testing, assuring, authorising, employing and continuously monitoring AI-enabled capabilities according to mission, environment, autonomy, consequence and human authority.

---

## 3.2 AI Capability

**Definition:** A capability that uses one or more AI-enabled components to perform, support or influence a function.

**D-AIGAAF interpretation:** The object being governed. An AI capability may include the model, software, data, hardware, interfaces, human processes, infrastructure and operational procedures required to perform its intended function.

---

## 3.3 AI System

**Definition:** The technical system or integrated set of components that uses AI to produce outputs or perform actions.

**D-AIGAAF interpretation:** The technical implementation of an AI capability.

An AI capability may therefore be broader than the AI system itself.

---

## 3.4 AI Model

**Definition:** A computational representation learned, configured or otherwise constructed to generate outputs from inputs.

**D-AIGAAF interpretation:** A model is one component of an AI capability and should not automatically be treated as the complete system being authorised.

---

## 3.5 AI-Enabled Capability

**Definition:** A capability in which AI contributes materially to information processing, decision support or action.

**D-AIGAAF interpretation:** Used interchangeably with AI capability where appropriate, but preferably used when emphasising the integration of AI into a wider operational system.

---

# 4. Mission and Operational Terms

## 4.1 Mission

**Definition:** The intended operational purpose or objective for which a capability is employed.

**D-AIGAAF interpretation:** The mission establishes why the AI capability exists and provides the basis for determining requirements, risk, assurance and authority.

---

## 4.2 Use Case

**Definition:** A defined scenario describing how a capability is intended to be used to achieve an objective.

**D-AIGAAF interpretation:** A use case provides greater specificity than a broad mission and helps establish the conditions against which the capability should be assessed.

---

## 4.3 Operational Context

**Definition:** The circumstances, conditions and constraints within which a capability is employed.

These may include:

- mission;
- environment;
- threat;
- communications;
- information availability;
- human control;
- system configuration; and
- consequence.

---

## 4.4 Operational Environment

**Definition:** The physical, digital, informational, electromagnetic, human and organisational conditions in which an AI capability operates.

**D-AIGAAF interpretation:** Operational environment is part of the assurance problem, not merely background context.

---

## 4.5 Operational Envelope

**Definition:** The defined set of conditions and constraints within which an AI capability is authorised to operate.

The envelope may include:

- mission;
- environment;
- autonomy;
- human authority;
- system configuration;
- data conditions;
- communications conditions;
- sensor conditions; and
- other relevant limitations.

---

## 4.6 Mission Criticality

**Definition:** The importance of an AI capability to successful mission execution.

**D-AIGAAF interpretation:** Mission criticality is a risk dimension and should be assessed separately from technical performance.

---

# 5. Risk and Consequence Terms

## 5.1 Risk

**Definition:** The effect of uncertainty on objectives, commonly considering the combination of potential consequences and the likelihood of those consequences.

**D-AIGAAF interpretation:** Risk describes what could go wrong, how serious the consequences could be and what uncertainty surrounds the outcome.

---

## 5.2 Inherent Risk

**Definition:** Risk before considering the effect of additional controls or mitigations.

**D-AIGAAF interpretation:** The baseline risk associated with the intended capability and operating context.

---

## 5.3 Residual Risk

**Definition:** Risk remaining after controls and mitigations have been applied.

**D-AIGAAF interpretation:** Residual risk is a central input to operational authorisation.

---

## 5.4 Consequence

**Definition:** The outcome or impact resulting from an event, failure or action.

**D-AIGAAF interpretation:** Consequence may include effects on human life, force protection, mission success, infrastructure, information, national interests or other protected objectives.

---

## 5.5 Mission-Critical AI

**Definition:** AI whose failure, degradation or compromise could materially affect the success or safety of an important mission.

**D-AIGAAF interpretation:** A governance classification requiring appropriate levels of assurance and operational control.

---

## 5.6 Loss of Control

**Definition:** A condition in which an AI capability behaves, acts or continues operating outside the control intended by its authorised operators or governing system.

**D-AIGAAF interpretation:** Loss of control may result from malfunction, compromise, unexpected behaviour, inadequate controls, authority expansion or other causes.

---

# 6. Autonomy Terms

## 6.1 Autonomy

**Definition:** The degree to which a system can perform functions or make decisions without direct human intervention.

**D-AIGAAF interpretation:** Autonomy must be assessed in relation to the function being performed, the authority available to the system and the consequence of its actions.

---

## 6.2 Autonomy Level

**Definition:** A defined classification describing the degree of independent decision-making or action available to an AI-enabled capability.

### D-AIGAAF Working Taxonomy

| Level | Description |
|---|---|
| **A0** | No meaningful AI decision-making |
| **A1** | Information, observation or classification |
| **A2** | Analysis, prediction or recommendation |
| **A3** | Recommendation or action requiring explicit human authorisation |
| **A4** | Execution of predefined actions under human supervision |
| **A5** | Independent consequential decision or action |

**Status:** Working construct.

This taxonomy should be validated against established defence, regulatory and technical terminology before formal adoption.

---

## 6.3 Human Control

**Definition:** The ability of an authorised human to understand, direct, constrain, override or stop an AI capability as appropriate to its function and risk.

---

## 6.4 Meaningful Human Control

**Definition:** Human control that is substantive rather than merely nominal.

**D-AIGAAF interpretation:** Meaningful control depends on factors such as authority, information, competency, timing, system design and realistic ability to intervene.

---

## 6.5 Human-on-the-Loop

**Definition:** A human supervises an AI system while the system performs functions with some degree of independent execution.

**D-AIGAAF interpretation:** The label alone is insufficient to establish meaningful control. The actual ability to intervene must be assessed.

---

## 6.6 Human-in-the-Loop

**Definition:** A human is required to participate in a defined decision or action before the system proceeds.

**D-AIGAAF interpretation:** The existence of a human approval step does not automatically establish meaningful control.

---

## 6.7 Human-out-of-the-Loop

**Definition:** A system performs a defined function without a human being required to participate in each individual decision or action.

**D-AIGAAF interpretation:** Such operation requires particularly careful assessment of authority, consequence, constraints, failure modes and assurance.

---

# 7. Assurance and TEVV Terms

## 7.1 Assurance

**Definition:** A structured basis for establishing justified confidence that a system or capability satisfies specified requirements and is suitable for its intended purpose, within stated limitations.

**D-AIGAAF interpretation:** Assurance is evidence-based and contextual.

---

## 7.2 Operational Assurance

**Definition:** Assurance that considers whether an AI capability can perform its intended function safely, reliably and effectively in the conditions in which it is authorised to operate.

---

## 7.3 Trustworthiness

**Definition:** The degree to which a system demonstrates characteristics necessary for its intended use, such as reliability, robustness, security, safety, transparency, accountability and resilience.

**D-AIGAAF interpretation:** Trustworthiness is multidimensional and should not be reduced to a single technical performance measure.

---

## 7.4 Testing

**Definition:** The execution of a defined procedure to determine system behaviour or performance against specified conditions or criteria.

**D-AIGAAF interpretation:** Testing generates evidence; it does not by itself determine authorisation.

---

## 7.5 Verification

**Definition:** The process of determining whether specified requirements have been correctly implemented.

**Practical question:** **Did we build the system right?**

---

## 7.6 Validation

**Definition:** The process of determining whether the system satisfies its intended purpose and operational need.

**Practical question:** **Did we build the right system?**

---

## 7.7 Evaluation

**Definition:** The process of examining evidence to determine effectiveness, limitations, risks and suitability for the intended purpose.

---

## 7.8 TEVV

**Definition:** Testing, Evaluation, Verification and Validation.

**D-AIGAAF interpretation:** TEVV is a major evidence-generating activity within the assurance lifecycle.

---

## 7.9 Evidence

**Definition:** Information that supports a claim, conclusion, assessment or decision.

**D-AIGAAF interpretation:** Evidence should be relevant, sufficient, traceable and appropriate to the claim being made.

---

## 7.10 Evidence Gap

**Definition:** A condition in which available evidence is insufficient to support a required assurance claim or decision.

---

## 7.11 Assurance Claim

**Definition:** A statement about a capability, system property or operational condition that is supported by evidence.

---

# 8. Authorisation Terms

## 8.1 Operational Authorisation

**Definition:** A formal organisational decision permitting an AI capability to operate within specified conditions and constraints.

**D-AIGAAF interpretation:** Operational authorisation is conditional and should bind:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

---

## 8.2 Authorising Authority

**Definition:** The person, body or organisational authority empowered to approve operational use within the applicable governance framework.

---

## 8.3 Authorisation Condition

**Definition:** A requirement, limitation or constraint that forms part of an operational authorisation.

---

## 8.4 Authorisation Boundary

**Definition:** The defined limit of what an operational authorisation permits.

---

## 8.5 Suspension

**Definition:** Temporary withdrawal of operational permission while a capability, incident, condition or assurance position is assessed.

---

## 8.6 Revocation

**Definition:** Withdrawal of an existing operational authorisation.

---

## 8.7 Reauthorisation

**Definition:** A new or renewed operational authorisation following a change, reassessment, expiry, incident or other trigger requiring renewed authority.

---

# 9. Human Authority Terms

## 9.1 Command Authority

**Definition:** Legitimate organisational authority to make or direct decisions within an established command structure.

**D-AIGAAF interpretation:** AI systems do not inherently possess command authority.

---

## 9.2 Decision Authority

**Definition:** The authority assigned to a person or organisation to make a specified decision.

---

## 9.3 Human Authority

**Definition:** The legitimate human authority responsible for deciding, approving, directing or controlling an AI-enabled function.

---

## 9.4 Human Override

**Definition:** An authorised human intervention that changes, rejects, interrupts or prevents an AI recommendation or action.

---

## 9.5 Operational AI Advisor (OAIA)

**Definition:** A qualified human advisor who bridges operational command and AI technical expertise.

**D-AIGAAF interpretation:** The OAIA advises commanders and other authorised decision-makers on matters including:

- AI capability;
- limitations;
- autonomy;
- operational risk;
- assurance evidence;
- system behaviour;
- incidents;
- changes; and
- appropriate employment conditions.

The OAIA does not replace command authority.

---

# 10. Security Terms

## 10.1 AI Security

**Definition:** The protection of AI capabilities, models, data, infrastructure, interfaces and operational functions against compromise, manipulation, misuse and loss of control.

**D-AIGAAF interpretation:** AI security includes conventional cybersecurity as well as AI-specific threats and failure modes.

---

## 10.2 Adversarial Robustness

**Definition:** The ability of an AI system to maintain acceptable behaviour when exposed to intentionally manipulated or hostile inputs or conditions.

---

## 10.3 Fail-Safe

**Definition:** A mechanism or condition that moves a system toward a safer state when continued operation presents unacceptable risk.

**D-AIGAAF interpretation:** Fail-safe is a last-resort control and does not replace prevention, assurance or command oversight.

---

## 10.4 Safe State

**Definition:** A defined system condition intended to reduce risk following failure, loss of control or other hazardous conditions.

---

## 10.5 Controlled Degradation

**Definition:** A designed transition from normal operation toward restricted or safer modes when required performance cannot be maintained.

---

## 10.6 Least Authority

**Definition:** The principle that a system should possess only the access, permissions and ability to act necessary for its authorised function.

---

# 11. Information and Data Terms

## 11.1 Data Integrity

**Definition:** The property that data remains accurate, complete and protected against unauthorised or unintended alteration.

---

## 11.2 Data Provenance

**Definition:** Information describing the origin, history and relevant transformations of data.

---

## 11.3 Model Provenance

**Definition:** Information describing the origin, development, training, modification and relevant dependencies of an AI model.

---

## 11.4 System Provenance

**Definition:** Information describing the origin and relevant dependencies of the components that make up an AI capability.

---

## 11.5 Uncertainty

**Definition:** A state in which available information or evidence does not provide sufficient confidence about an outcome, assessment or prediction.

**D-AIGAAF interpretation:** Meaningful uncertainty should be communicated rather than concealed behind unwarranted confidence.

---

## 11.6 Confabulation / Hallucination

**Definition:** An AI-generated output that is presented as factual or reliable despite lacking adequate supporting basis.

**D-AIGAAF interpretation:** The terminology used in specific technical or governance contexts may vary, but the operational concern is the same: unsupported outputs can create unsafe decisions.

---

# 12. Supply Chain Terms

## 12.1 AI Supply Chain

**Definition:** The network of organisations, technologies, services and dependencies involved in developing, providing, integrating, operating, maintaining or updating an AI capability.

---

## 12.2 Critical Dependency

**Definition:** A component, supplier, service or dependency whose failure, compromise or withdrawal could materially affect an AI capability.

---

## 12.3 Sovereignty

**Definition:** The degree to which an organisation or state retains the ability to control, sustain and employ a capability without unacceptable external dependency.

**D-AIGAAF interpretation:** Sovereignty is multidimensional and may involve technology, data, models, hardware, software, infrastructure, suppliers and update mechanisms.

---

# 13. Lifecycle Terms

## 13.1 AI Lifecycle

**Definition:** The sequence of activities through which an AI capability is conceived, specified, acquired or developed, assured, authorised, employed, monitored, changed and eventually retired.

---

## 13.2 Configuration Baseline

**Definition:** The formally identified version and configuration of a system against which assurance and operational authorisation are established.

---

## 13.3 Material Change

**Definition:** A change that could materially affect system behaviour, performance, security, autonomy, authority, operational environment or risk.

---

## 13.4 Revalidation

**Definition:** Reassessment to determine whether an AI capability continues to satisfy its intended operational need following a change, incident or other trigger.

---

## 13.5 Retirement

**Definition:** The formal withdrawal of an AI capability from operational use.

---

## 13.6 Decommissioning

**Definition:** The technical and organisational process of removing a capability from service and eliminating or controlling its residual access, dependencies and authority.

---

# 14. Governance Terms

## 14.1 Governance

**Definition:** The system by which an organisation directs, controls, oversees and accounts for a capability.

---

## 14.2 Policy

**Definition:** An authoritative organisational statement establishing required direction, rules or expectations.

---

## 14.3 Control

**Definition:** A measure intended to prevent, detect, mitigate or manage a risk or achieve a defined governance objective.

---

## 14.4 Requirement

**Definition:** A specified condition or capability that a system, process or organisation must satisfy.

---

## 14.5 Accountability

**Definition:** The obligation of an identified person or organisation to answer for decisions, actions or outcomes within their assigned authority.

---

## 14.6 Responsibility

**Definition:** The duty assigned to a person or organisation to perform a defined function or task.

---

# 15. D-AIGAAF Core Records

## 15.1 Defence AI Capability Register (DAICR)

**Definition:** The authoritative record of AI capabilities subject to D-AIGAAF governance.

**Purpose:** Establish what AI capabilities exist, where they are used and what governance status applies.

---

## 15.2 Defence AI Assurance Record (DAAR)

**Definition:** The structured record of assurance evidence, findings, limitations, assumptions and conclusions associated with an AI capability.

**Purpose:** Establish what has been demonstrated and what remains uncertain.

---

## 15.3 Defence AI Operational Authorisation (DAOA)

**Definition:** The formal record establishing why, where, how and under whose authority an AI capability may be operationally employed.

**Purpose:** Establish the conditions under which operational authority exists.

---

## 15.4 Operational Record

**Definition:** The record of significant AI-enabled operational activity, decisions, interventions, incidents, deviations and relevant outcomes.

**Purpose:** Support accountability, audit, learning and continuous assurance.

---

# 16. Important Conceptual Distinctions

## 16.1 Risk vs Assurance

**Risk asks:**

> What could go wrong, and how serious could the consequences be?

**Assurance asks:**

> What evidence demonstrates that the capability is sufficiently trustworthy for its intended use?

---

## 16.2 Assurance vs Authorisation

**Assurance asks:**

> What does the evidence demonstrate?

**Authorisation asks:**

> Given the evidence, risk, law, policy and operational context, should this capability be permitted to operate?

---

## 16.3 Capability vs System

**Capability:** The broader operational function.

**System:** The technical implementation supporting that function.

Governance should normally consider both.

---

## 16.4 Human Presence vs Human Control

A human being present somewhere in the decision chain does not automatically establish meaningful human control.

Control depends on actual authority, information, competency, timing and ability to intervene.

---

## 16.5 Testing vs Assurance

Testing generates evidence.

Assurance interprets evidence against defined claims, requirements and risk.

---

## 16.6 Validation vs Authorisation

Validation determines whether the capability meets its intended purpose.

Authorisation determines whether the organisation permits its operational use.

---

## 16.7 Technical Failure vs Operational Failure

A system may function according to its technical specification while still failing to achieve the intended operational objective.

D-AIGAAF therefore distinguishes technical performance from mission effectiveness.

---

## 16.8 Security Compromise vs Loss of Control

A system may lose control because of a cyberattack, but loss of control can also arise from:

- unexpected model behaviour;
- incorrect data;
- unsafe integration;
- configuration errors;
- inadequate human control;
- unintended autonomy; or
- other system or organisational failures.

AI security therefore cannot be reduced to cybersecurity alone.

---

# 17. Terminology Governance

The terminology should be reviewed when:

- a new D-AIGAAF module introduces a significant concept;
- an external standard materially affects a definition;
- operational experience exposes ambiguity;
- technical developments change the meaning or application of a term; or
- two modules begin using the same term differently.

New terminology should not be introduced unnecessarily.

Where an established term is adequate, D-AIGAAF should preferably use the established term and clearly state any framework-specific interpretation.

---

# 18. Working Status and External Alignment

This document contains both:

1. terminology derived from established professional usage; and
2. D-AIGAAF working constructs created specifically for the framework.

The distinction is important.

A D-AIGAAF working definition should not be represented as an internationally accepted or legally authoritative definition unless independently established.

Before formal adoption, key terminology should be cross-checked against relevant sources such as:

- NIST AI Risk Management Framework;
- ISO/IEC AI standards;
- NATO AI principles and related guidance;
- established defence AI terminology;
- applicable national policy;
- safety engineering terminology;
- cybersecurity terminology; and
- applicable legal frameworks.

---

# 19. D-AIGAAF Terminology Rule

The framework follows one simple rule:

> **If a term can materially affect risk, assurance, authority or accountability, its meaning must be explicit.**

This prevents ambiguity from becoming a governance gap.

---

**D-AIGAAF Terminology v0.1**

Working controlled vocabulary for framework development.

Definitions may be refined as D-AIGAAF develops and is cross-referenced against authoritative standards, policy, law and operational practice.
