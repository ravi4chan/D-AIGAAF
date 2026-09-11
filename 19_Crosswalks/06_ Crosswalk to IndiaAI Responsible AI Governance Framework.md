# 06-Crosswalk to IndiaAI Responsible AI Governance Framework

## 1. Purpose

This document defines the alignment between D-AIGAAF — Defence AI Governance, Assurance & Operational Authorisation Framework and India's IndiaAI Responsible AI governance principles.

The purpose of this crosswalk is to establish how broad Indian responsible-AI principles can be translated into a defence-oriented governance architecture covering mission context, risk, autonomy, human authority, assurance, security, operational authorisation and continuous governance.

This document is deliberately limited to the **IndiaAI Responsible AI principles/framework layer**.

It does not attempt to duplicate:

- IndiaAI Governance Guidelines — addressed separately in Serial 07;
- India's data-protection framework — addressed separately in Serial 08;
- broader Indian AI policy and standards — addressed separately in Serial 09;
- defence AI and responsible-AI principles — addressed separately in Serial 10;
- TEVV and AI assurance frameworks — addressed separately in Serial 11;
- AI security and adversarial frameworks — addressed separately in Serial 12; or
- the integrated crosswalk methodology — addressed separately in Serial 13.

## 2. Status and Interpretation

IndiaAI's Responsible AI material provides a policy and governance reference for responsible development and use of AI in India.

D-AIGAAF treats the IndiaAI principles as a **normative responsible-AI reference layer**, not as a standalone defence operational authorisation framework.

Accordingly:

> Alignment with IndiaAI responsible-AI principles does not by itself establish legal compliance, technical assurance, operational readiness or permission to employ a defence AI capability.

D-AIGAAF converts responsible-AI principles into a broader governance chain:

**Principle → Requirement → Control → Evaluation → Evidence → Assurance → Human Authority → Operational Authorisation → Employment → Continuous Assurance**

## 3. IndiaAI Responsible AI Principles

The IndiaAI Responsible AI material identifies a set of principles intended to support responsible and trustworthy AI.

The principal areas addressed by the framework include:

1. Safety and Reliability.
2. Equality.
3. Inclusivity and Non-discrimination.
4. Privacy and Security.
5. Transparency.
6. Explainability.
7. Accountability.
8. Protection and Reinforcement of Positive Human Values.

These principles are relevant to D-AIGAAF because defence AI can affect people, operational decisions, resources, safety and potentially human life.

D-AIGAAF therefore treats the principles as high-level governance objectives that must be contextualised according to mission, consequence, autonomy, environment and human authority.

## 4. Crosswalk Overview

| IndiaAI Principle | Primary D-AIGAAF Modules | D-AIGAAF Interpretation |
|---|---|---|
| Safety and Reliability | 03 Risk & Autonomy; 09 TEVV; 10 Operational Environment; 13 Continuous Assurance; 14 Incident & Fail-Safe | Establishes the need for dependable and safe AI, extended by mission-specific risk, testing, operational conditions, monitoring and fail-safe mechanisms |
| Equality | 02 Mission & Use Case; 05 Data & Information; 09 TEVV; 13 Continuous Assurance | Requires relevant assessment of unequal or biased performance in the applicable mission context |
| Inclusivity and Non-discrimination | 02 Mission & Use Case; 05 Data & Information; 08 Human Authority; 09 TEVV | Requires identification and evaluation of relevant affected groups and conditions |
| Privacy and Security | 05 Data & Information; 06 AI Security; 07 Supply Chain & Sovereignty; 21 Legal & Policy | Extends responsible handling of information into AI-specific security, supply-chain and legal controls |
| Transparency | 04 AI Lifecycle; 05 Data & Information; 16 Audit & Evidence; 25 Documentation & Knowledge | Requires appropriate lifecycle documentation, provenance, limitations and traceability |
| Explainability | 08 Human Authority; 09 TEVV; 12 Operational Employment; 16 Audit & Evidence | Requires decision-relevant understanding of AI outputs, limitations and uncertainty |
| Accountability | 01 Strategy & Governance; 08 Human Authority; 11 Operational Authorisation; 16 Audit & Evidence; 17 Workforce | Establishes explicit responsibility, authority, records and governance |
| Positive Human Values | 01 Strategy & Governance; 02 Mission & Use Case; 08 Human Authority; 21 Legal & Policy | Connects AI use with lawful, ethical and human-centred objectives |

## 5. Safety and Reliability

Safety and reliability are foundational responsible-AI considerations.

D-AIGAAF translates them into multiple layers rather than treating them as a single technical property.

Relevant controls include:

- mission-specific risk assessment;
- identification of foreseeable harmful outcomes;
- autonomy assessment;
- safety requirements;
- reliability requirements;
- TEVV;
- operational-environment assessment;
- deployment-readiness assessment;
- operational authorisation;
- human oversight;
- intervention and override;
- safe-state requirements;
- incident response;
- continuous assurance;
- change control;
- revalidation; and
- reauthorisation.

A key D-AIGAAF distinction is:

**Technical reliability does not automatically establish operational safety.**

An AI system can perform well under laboratory or benchmark conditions and still be inappropriate for a particular defence mission because of:

- environmental variability;
- adversarial inputs;
- degraded communications;
- sensor limitations;
- distribution shift;
- uncertain data;
- excessive autonomy;
- inadequate human response time;
- mission-specific consequences; or
- inability to recover safely from failure.

Therefore:

**Reliable ≠ universally safe ≠ authorised.**

## 6. Equality

Equality is incorporated through contextual assessment rather than a single universal metric.

D-AIGAAF addresses:

- data representativeness;
- potential bias;
- performance differences across relevant conditions;
- mission-specific impacts;
- evaluation methodology;
- monitoring for systematic degradation;
- corrective action.

The relevant question is not simply whether a model satisfies a generic fairness threshold.

It is:

> **Could systematic differences in AI performance create unacceptable operational, legal, safety or human consequences in this use case?**

The answer may depend on:

- who or what is affected;
- the purpose of the system;
- the consequences of an incorrect output;
- the operating environment;
- the degree of autonomy; and
- applicable legal and policy requirements.

## 7. Inclusivity and Non-discrimination

D-AIGAAF incorporates inclusivity and non-discrimination through:

- appropriate identification of affected stakeholders;
- representative data where relevant;
- assessment of potential discriminatory effects;
- human review;
- documentation of limitations;
- testing across relevant operating conditions;
- monitoring;
- escalation and corrective action.

The framework recognises that defence AI applications differ substantially.

For example, an AI capability supporting:

- logistics;
- maintenance;
- engineering;
- intelligence analysis;
- situational awareness;
- decision support; or
- a highly consequential operational function

may require different assessments of equality and non-discrimination.

D-AIGAAF therefore requires **contextual application rather than mechanical checklist compliance**.

## 8. Privacy and Security

IndiaAI identifies privacy and security as fundamental responsible-AI considerations.

D-AIGAAF expands the security dimension into a dedicated AI-security architecture.

Relevant areas include:

- data governance;
- access control;
- information protection;
- AI security requirements;
- threat modelling;
- adversarial AI;
- model and data integrity;
- supply-chain security;
- dependency management;
- security assurance;
- incident response;
- safe-state behaviour;
- change assessment.

AI introduces attack and failure surfaces that may not be adequately addressed by conventional information-security controls alone.

Examples include:

- data poisoning;
- adversarial inputs;
- model manipulation;
- malicious model or software updates;
- compromised dependencies;
- prompt or instruction manipulation;
- model extraction;
- unsafe AI-agent/tool interaction;
- unexpected autonomous behaviour; and
- loss of meaningful human control.

D-AIGAAF therefore treats AI security as an integral component of responsible AI.

## 9. Transparency

IndiaAI's responsible-AI material places importance on transparency and lifecycle documentation, including information about capabilities and limitations.

D-AIGAAF implements this through:

- AI lifecycle documentation;
- data provenance;
- data lineage;
- model/system documentation;
- configuration baselines;
- assumptions;
- known limitations;
- TEVV records;
- assurance evidence;
- authorisation conditions;
- operational records;
- audit evidence.

Defence introduces an important constraint:

> **Transparency must be proportionate to purpose, authority, security requirements, classification, intellectual-property considerations and decision consequence.**

D-AIGAAF therefore uses the concept of **controlled transparency**.

The objective is to provide authorised stakeholders with enough information to:

- understand the system;
- make informed decisions;
- assess limitations;
- exercise human authority;
- conduct assurance;
- investigate incidents; and
- maintain accountability,

while protecting information that cannot appropriately be disclosed.

## 10. Explainability

IndiaAI recognises explainability as an important responsible-AI principle, particularly where AI influences significant decisions.

D-AIGAAF interprets explainability primarily from the perspective of the authorised human decision-maker.

Depending on risk and autonomy, useful explanation may include:

- what the system assessed;
- what output it generated;
- relevant supporting evidence;
- material factors influencing the output;
- uncertainty;
- limitations;
- assumptions;
- known failure conditions; and
- whether the output is within validated operating conditions.

Explainability should be proportionate to:

- consequence;
- autonomy;
- operational tempo;
- human competence;
- system complexity;
- uncertainty;
- mission context.

A technically sophisticated explanation is not necessarily operationally useful.

D-AIGAAF therefore prioritises **decision-relevant explainability**.

## 11. Accountability

Accountability is one of the strongest points of alignment between IndiaAI responsible-AI principles and D-AIGAAF.

IndiaAI emphasises organisational structures, policies, lifecycle responsibilities and human supervisory control.

D-AIGAAF operationalises accountability through:

- governance roles;
- decision rights;
- accountable authorities;
- human oversight;
- operational authorisation;
- decision traceability;
- evidence management;
- audit;
- incident investigation;
- change control;
- workforce competence.

The framework establishes a fundamental rule:

> **AI may contribute to a consequential decision, but AI itself is not the accountable authority for that decision.**

Accountability must remain assigned to an appropriately authorised human or organisation.

## 12. Human Supervisory Control

IndiaAI responsible-AI material recognises the importance of human supervisory control.

D-AIGAAF develops this into a structured human-authority model.

Meaningful human control requires more than simply placing a person somewhere in the process.

The human should have, as appropriate:

- legitimate authority;
- relevant competence;
- sufficient situational awareness;
- access to necessary information;
- sufficient time to act;
- ability to question the AI output;
- ability to intervene;
- ability to override;
- ability to stop or place the system in a safe state.

D-AIGAAF therefore distinguishes:

**Human presence**

from

**Human oversight**

from

**Meaningful human control**

from

**Human accountability**.

These are related but not interchangeable concepts.

## 13. Positive Human Values

IndiaAI includes protection and reinforcement of positive human values within its responsible-AI principles.

D-AIGAAF connects this principle to:

- mission purpose;
- legal obligations;
- ethical constraints;
- human authority;
- accountability;
- responsible use;
- safety;
- protection of human interests;
- governance review.

In defence applications, this requires the organisation to establish why the AI capability should exist, what legitimate purpose it serves and what boundaries apply to its use.

This is reflected in the D-AIGAAF sequence:

**Purpose → Mission Need → Risk → Authority → Constraints → Employment → Accountability**

The existence of a technically feasible AI capability is therefore not sufficient justification for its operational use.

## 14. Responsible AI Across the D-AIGAAF Lifecycle

The IndiaAI principles can be embedded across the D-AIGAAF lifecycle.

| Lifecycle Stage | Responsible-AI Considerations |
|---|---|
| Mission Need | Legitimate purpose, human values, foreseeable impact |
| Requirements | Safety, reliability, security, transparency, accountability |
| Data | Privacy, quality, representativeness, provenance |
| Development | Responsible development practices and documentation |
| Integration | Security, human interaction, system boundaries |
| TEVV | Safety, reliability, bias, security, explainability |
| Deployment Readiness | Evidence and limitations |
| Authorisation | Human authority, risk acceptance and conditions |
| Employment | Responsible operational use and human control |
| Monitoring | Performance, safety, security and emerging harms |
| Incident | Protective response, investigation and corrective action |
| Change | Impact assessment and revalidation |
| Reauthorisation | Renewed assurance and authority |
| Retirement | Responsible withdrawal and records |

## 15. IndiaAI Principles and D-AIGAAF Golden Thread

The IndiaAI principles map onto the D-AIGAAF Golden Thread:

**Mission Need**
→ purpose and positive human values

**Risk**
→ safety, reliability, equality, security and potential harm

**Requirements**
→ responsible-AI principles translated into measurable requirements

**Controls**
→ transparency, privacy, security, human oversight and accountability

**Testing**
→ safety, reliability, fairness, security and explainability evaluation

**Evidence**
→ documentation, provenance, test results and records

**Assurance**
→ evidence-based confidence

**Authority**
→ human accountability and decision rights

**Conditions**
→ operating assumptions, limitations and safeguards

**Boundaries**
→ mission, autonomy, environment and human-control boundaries

**Employment**
→ responsible operational use

**Monitoring**
→ continuing responsible performance

**Change / Incident**
→ corrective action and protective response

**Learning**
→ governance improvement

**Revalidation / Reauthorisation**
→ renewed confidence and authority

## 16. Defence-Specific Extensions

The IndiaAI responsible-AI principles are broad enough to provide a useful foundation, but D-AIGAAF adds explicit mechanisms required for consequential defence applications.

### 16.1 Mission Consequence

The severity of potential consequences influences governance intensity.

### 16.2 Autonomy

Autonomy is explicitly treated as a risk and authority variable.

### 16.3 Human Authority

Decision rights and intervention authority are explicitly assigned.

### 16.4 Operational Environment

AI is assessed under relevant environmental, adversarial and degraded conditions.

### 16.5 Operational Authorisation

Responsible-AI alignment does not automatically grant permission to operate.

### 16.6 Operational Employment

The framework governs how an authorised AI capability is used in practice.

### 16.7 Fail-Safe

Critical failures and loss of control require predefined protective behaviour.

### 16.8 Continuous Assurance

Responsible operation must remain justified as conditions change.

### 16.9 Reauthorisation

Material changes or incidents can invalidate previous authority.

### 16.10 Traceability

Important decisions, actions and system states require appropriate records.

## 17. D-AIGAAF Defence Extension Matrix

| IndiaAI Concept | D-AIGAAF Extension |
|---|---|
| Safety | Consequence-based risk, fail-safe, safe-state and operational controls |
| Reliability | Testing under mission-relevant and degraded conditions |
| Equality | Context-specific bias and performance assessment |
| Inclusivity | Relevant affected-stakeholder and operational-context assessment |
| Privacy | Data governance and applicable legal controls |
| Security | AI-specific security and adversarial threat controls |
| Transparency | Controlled transparency and lifecycle traceability |
| Explainability | Decision-relevant explanations and uncertainty communication |
| Accountability | Named authority, decision rights and traceability |
| Human supervision | Meaningful human control, intervention and override |
| Positive human values | Mission legitimacy, legal/ethical constraints and responsible use |

## 18. Evidence of Alignment

Alignment with IndiaAI responsible-AI principles should be supported by evidence.

Examples include:

- responsible-AI policy;
- defined AI purpose;
- use-case documentation;
- risk assessment;
- data-governance records;
- data provenance;
- bias/fairness assessment where applicable;
- safety and reliability testing;
- explainability assessment;
- security assessment;
- human-oversight design;
- accountability matrix;
- TEVV evidence;
- operational limitations;
- authorisation records;
- monitoring records;
- incident records;
- change and revalidation records.

The governing principle is:

> **A claim of responsible AI should be supported by demonstrable evidence.**

## 19. Relationship to Other Module 19 Crosswalks

Serial 06 establishes the **IndiaAI responsible-AI principles layer**.

The remaining Indian and international crosswalks provide complementary layers:

- **Serial 07 — IndiaAI Governance Guidelines:** operational and policy guidance emerging from India's AI governance framework.
- **Serial 08 — India DPDP Framework:** data-protection and privacy legal requirements.
- **Serial 09 — Indian AI Policy and Standards:** broader Indian policy, standards and regulatory ecosystem.
- **Serial 10 — Defence AI and Responsible AI Principles:** defence-specific principles and international defence-AI governance references.
- **Serial 11 — TEVV and AI Assurance Frameworks:** testing, evaluation, verification, validation and assurance.
- **Serial 12 — AI Security and Adversarial Frameworks:** AI-specific security and adversarial-risk frameworks.
- **Serial 13 — Integrated D-AIGAAF Crosswalk and Alignment Method:** method for integrating all applicable frameworks.

This separation prevents different types of authority from being incorrectly treated as equivalent.

## 20. Limitations

This crosswalk does not claim that:

- D-AIGAAF is endorsed by IndiaAI or MeitY;
- IndiaAI responsible-AI principles are defence-specific;
- IndiaAI principles constitute legislation;
- alignment with the principles establishes legal compliance;
- alignment establishes operational authorisation;
- responsible-AI principles eliminate AI risk; or
- a crosswalk is itself evidence of compliance.

The purpose is alignment, interpretation and structured integration.

## 21. Implementation Guidance

An organisation applying D-AIGAAF should use the IndiaAI responsible-AI principles during:

1. AI strategy development.
2. Governance-policy development.
3. Mission and use-case definition.
4. Risk assessment.
5. Data and information governance.
6. Human-authority design.
7. AI lifecycle planning.
8. TEVV planning.
9. Operational authorisation.
10. Continuous assurance.

The principles should then be converted into explicit requirements and evidence expectations.

## 22. Primary Reference Basis

The crosswalk is based on IndiaAI and Government of India material concerning responsible and trustworthy AI, including IndiaAI Responsible AI principles and associated responsible-AI governance material.

Particular relevance is given to the IndiaAI treatment of:

- safety and reliability;
- equality;
- inclusivity and non-discrimination;
- privacy and security;
- transparency;
- explainability;
- accountability;
- human supervisory control; and
- positive human values.

Current Government of India AI-governance material should be consulted when implementing this crosswalk because India's AI governance ecosystem continues to evolve.

## 23. Final Crosswalk Position

The IndiaAI Responsible AI principles provide a valuable Indian foundation for trustworthy, human-centred and accountable AI.

D-AIGAAF adopts that foundation and extends it for defence operations through explicit treatment of:

**Mission → Consequence → Risk → Autonomy → Human Authority → TEVV → Security → Environment → Authorisation → Employment → Continuous Assurance**

The resulting position is:

> **IndiaAI provides the responsible-AI principles; D-AIGAAF provides the defence governance architecture needed to operationalise those principles under consequential, adversarial and potentially degraded conditions.**
