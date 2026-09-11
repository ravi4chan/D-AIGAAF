# 12-Crosswalk to AI Security and Adversarial Frameworks

## 1. Purpose

This document establishes the relationship between D-AIGAAF — Defence AI Governance, Assurance & Operational Authorisation Framework and major **AI security, adversarial machine learning, AI red teaming and secure-AI frameworks**.

The purpose is to ensure that AI security is treated as a distinct governance discipline rather than being assumed to be completely covered by conventional cybersecurity.

D-AIGAAF recognises that an AI system can be compromised or manipulated in ways that affect:

- data;
- models;
- outputs;
- recommendations;
- human trust;
- autonomy;
- system behaviour;
- mission effectiveness;
- safety;
- operational authority.

The crosswalk therefore connects:

**Threat → Risk → Security Requirement → Control → Adversarial Evaluation → Evidence → Assurance → Operational Decision**

## 2. Scope

The crosswalk considers concepts from major AI-security and adversarial-AI references, including:

- NIST AI Risk Management Framework;
- NIST AI 100-2 Adversarial Machine Learning Taxonomy;
- NIST AI 100-3 Adversarial Machine Learning Taxonomy and terminology work;
- MITRE ATLAS;
- OWASP Machine Learning Security Top 10;
- OWASP Top 10 for Large Language Model Applications;
- ISO/IEC 27001;
- ISO/IEC 23894;
- ISO/IEC 42001;
- CISA / UK NCSC guidance on secure AI system development;
- international secure-by-design AI guidance;
- defence AI security and assurance practices.

These sources are used as reference inputs and should be mapped to the applicable organisational and operational context.

## 3. Why AI Security Requires a Dedicated Crosswalk

Traditional cybersecurity generally protects:

- systems;
- networks;
- applications;
- identities;
- infrastructure;
- information.

AI systems introduce additional attack surfaces involving:

- data;
- models;
- prompts;
- embeddings;
- inference;
- training;
- fine-tuning;
- retrieval;
- tools;
- agents;
- model supply chains;
- human-AI interaction.

An attacker may therefore seek not only to gain access to a system but to **change what the system believes, recommends, predicts or does**.

D-AIGAAF consequently treats AI security as part of:

- safety;
- mission risk;
- human control;
- autonomy;
- operational resilience.

## 4. High-Level Crosswalk

| AI Security / Adversarial Concept | D-AIGAAF Modules | D-AIGAAF Treatment |
|---|---|---|
| Secure AI governance | 01 Governance; 06 AI Security | Establishes security ownership and accountability |
| AI threat modelling | 03 Risk; 06 Security | Maps threats to mission consequences |
| Adversarial ML | 06 Security; 09 TEVV | Tests model behaviour under adversarial conditions |
| Data poisoning | 05 Data; 06 Security; 09 TEVV | Protects data integrity and evaluates poisoning resilience |
| Evasion attacks | 06 Security; 09 TEVV | Tests model robustness against manipulated inputs |
| Model extraction | 06 Security; 07 Supply Chain | Protects model assets and intellectual property |
| Model manipulation | 06 Security; 15 Change | Controls unauthorised model/configuration changes |
| Prompt injection | 06 Security; 12 Employment; 24 Architecture | Governs instruction and context manipulation |
| LLM application security | 06 Security; 24 Architecture | Protects prompts, retrieval, tools and outputs |
| AI agents | 03 Risk; 06 Security; 08 Human Authority; 24 Architecture | Controls tools, permissions, autonomy and action boundaries |
| Supply-chain attacks | 07 Supply Chain; 06 Security | Governs dependencies and supplier risk |
| Privacy attacks | 05 Data; 06 Security | Addresses data leakage and inference risks |
| AI-enabled cyber threats | 06 Security; 14 Incident | Includes AI as both target and threat multiplier |
| Red teaming | 09 TEVV; 13 Assurance | Uses adversarial challenge as assurance evidence |
| Incident response | 14 Incident & Fail-Safe | Integrates AI security incidents into operational response |
| Continuous monitoring | 13 Assurance; 06 Security | Detects changing threats and security posture |
| Secure updates | 15 Change; 07 Supply Chain | Controls updates and revalidation |
| Fail-safe | 14 Incident & Fail-Safe | Limits consequences of compromised or unexpected behaviour |

## 5. NIST AI Risk Management Framework

NIST AI RMF provides a broad risk-management structure through:

- GOVERN;
- MAP;
- MEASURE;
- MANAGE.

AI security can be incorporated throughout these functions.

D-AIGAAF extends this by explicitly connecting security threats to:

- mission consequence;
- autonomy;
- human authority;
- operational environment;
- operational authorisation.

Security is therefore not simply a technical control category.

It is a governance variable affecting whether an AI capability can be safely employed.

## 6. Adversarial Machine Learning

Adversarial machine learning addresses attacks intended to manipulate or exploit machine-learning systems.

Relevant attack categories can include:

- evasion;
- poisoning;
- privacy attacks;
- model extraction;
- model manipulation;
- backdoors;
- supply-chain compromise.

NIST's adversarial machine-learning taxonomy is intended to provide common terminology and a structured way to describe attacks against machine-learning systems. citeturn0search3

D-AIGAAF maps these attack classes into:

**Threat Model → Risk Assessment → Security Requirement → TEVV → Assurance → Operational Control**

## 7. MITRE ATLAS

MITRE ATLAS provides a knowledge base of adversarial tactics and techniques targeting AI-enabled systems.

D-AIGAAF can use ATLAS-style threat knowledge to support:

- threat modelling;
- red-team planning;
- attack-surface analysis;
- security requirements;
- adversarial testing;
- incident investigation.

The framework should not treat a threat catalogue as a complete security assessment.

The relevant question remains:

> **Which adversarial behaviours are plausible against this particular AI capability, and what could they cause operationally?**

## 8. OWASP Machine Learning Security

OWASP's machine-learning security work provides practical categories of vulnerabilities and attacks against machine-learning systems.

D-AIGAAF can use these categories during:

- architecture review;
- threat modelling;
- secure development;
- security testing;
- supplier assessment;
- red teaming.

The objective is to translate technical vulnerabilities into governance consequences.

For example:

**Model tampering**
→ altered output

**Altered output**
→ incorrect recommendation

**Incorrect recommendation**
→ human decision risk

**Decision risk**
→ mission consequence

## 9. OWASP LLM Application Security

Generative AI and LLM applications create additional security concerns.

Relevant areas include:

- prompt injection;
- insecure output handling;
- training-data poisoning;
- model denial of service;
- supply-chain vulnerabilities;
- sensitive-information disclosure;
- excessive agency;
- overreliance;
- insecure plugins/tools.

D-AIGAAF maps these risks into:

- AI security;
- human authority;
- architecture;
- autonomy;
- operational employment;
- TEVV.

For AI agents, **excessive agency** is particularly relevant because the system may be capable of taking actions rather than merely generating information.

## 10. AI Agents and Security

AI agents can:

- reason;
- plan;
- call tools;
- access data;
- execute workflows;
- interact with external systems.

This changes the security model.

D-AIGAAF requires explicit governance of:

- available tools;
- permissions;
- credentials;
- action scope;
- autonomy;
- approval requirements;
- human intervention;
- logging;
- termination;
- safe state.

The principle is:

> **An AI system should not possess more operational authority than is necessary for its authorised function.**

## 11. Excessive Agency

Agentic AI introduces a specific governance problem:

**Capability can become authority through permissions.**

D-AIGAAF therefore separates:

- what the model can generate;
- what the system can access;
- what tools it can invoke;
- what actions it can initiate;
- what actions require human approval.

This creates an authority ladder:

**Information**
→ **Analysis**
→ **Recommendation**
→ **Proposed Action**
→ **Human-Authorised Action**
→ **Supervised Autonomous Action**

Each transition should be explicitly governed.

## 12. Prompt Injection and Instruction Manipulation

Prompt injection can attempt to alter how an AI system interprets instructions or retrieved information.

D-AIGAAF treats this as both a security and governance problem.

Controls may include:

- input validation;
- instruction hierarchy;
- privilege separation;
- tool isolation;
- retrieval controls;
- output validation;
- human approval;
- monitoring;
- adversarial testing.

The objective is not merely to block malicious text.

It is to prevent untrusted information from acquiring **unauthorised operational authority**.

## 13. Data Poisoning

Data poisoning can manipulate training or operational data to influence model behaviour.

D-AIGAAF addresses this through:

- data provenance;
- lineage;
- integrity controls;
- source validation;
- dataset governance;
- anomaly detection;
- controlled updates;
- adversarial evaluation.

Where poisoning is plausible, TEVV should assess whether manipulated data can produce unacceptable behaviour.

## 14. Model Manipulation and Backdoors

Models may be compromised through:

- malicious training;
- compromised checkpoints;
- backdoors;
- unauthorised fine-tuning;
- malicious updates;
- compromised dependencies.

D-AIGAAF requires:

- configuration baselines;
- model provenance;
- integrity verification;
- supplier assurance;
- controlled updates;
- change impact assessment;
- revalidation.

A model should not be treated as trustworthy merely because it came from a trusted supplier.

## 15. Model Extraction and Intellectual Property

Attackers may attempt to reconstruct or extract model behaviour.

Relevant controls include:

- access control;
- rate limiting;
- API protection;
- monitoring;
- output controls;
- model confidentiality;
- supplier controls.

For defence systems, model extraction may also create operational-security concerns where model behaviour reveals:

- capabilities;
- limitations;
- decision thresholds;
- operational patterns.

## 16. Privacy and Inference Attacks

AI systems can create privacy risks even when direct database access is unavailable.

Examples include:

- membership inference;
- model inversion;
- training-data extraction;
- sensitive-output generation.

D-AIGAAF connects these risks with:

- Module 05 Data & Information;
- Module 06 AI Security;
- Module 08 Human Authority;
- Module 09 TEVV;
- Module 14 Incident & Fail-Safe.

## 17. Supply-Chain Security

AI supply chains can include:

- models;
- datasets;
- software;
- libraries;
- chips;
- APIs;
- cloud services;
- development environments;
- third-party tools.

A compromise anywhere in this chain can affect the final capability.

D-AIGAAF therefore requires:

**Supplier → Component → Dependency → Change → Assurance → Authorisation**

to remain traceable.

Material supplier changes may trigger:

- security assessment;
- TEVV;
- revalidation;
- reauthorisation.

## 18. Secure-by-Design

D-AIGAAF adopts a secure-by-design principle:

> **Security should be incorporated into the AI lifecycle from requirements and architecture rather than added only after deployment.**

Relevant lifecycle stages include:

- requirements;
- architecture;
- development;
- data preparation;
- integration;
- testing;
- deployment;
- employment;
- monitoring;
- change.

This aligns AI security with broader secure-development principles.

## 19. AI Security Requirements

Security requirements should be established before operational deployment.

They may cover:

- confidentiality;
- integrity;
- availability;
- authenticity;
- access;
- provenance;
- model integrity;
- data integrity;
- secure updates;
- monitoring;
- recovery;
- human intervention;
- autonomy boundaries.

Requirements should be measurable where practical.

## 20. AI Security TEVV

Security testing should assess:

- known attack vectors;
- plausible adversarial behaviour;
- misuse;
- unexpected inputs;
- compromised dependencies;
- malicious updates;
- model manipulation;
- data poisoning;
- prompt injection;
- tool abuse;
- privilege escalation.

Testing should include both:

**Technical attack resilience**

and

**Operational consequence assessment**.

## 21. Red Teaming

AI red teaming should challenge:

- security assumptions;
- model behaviour;
- data;
- interfaces;
- human trust;
- autonomy;
- tool permissions;
- system boundaries.

Red teams should be encouraged to identify unexpected pathways to:

- unsafe behaviour;
- unauthorised action;
- information leakage;
- loss of human control.

Findings should feed directly into risk and assurance processes.

## 22. Human Security

Human operators are part of the AI security boundary.

Security governance should consider:

- social engineering;
- manipulation of operators;
- automation bias;
- alert fatigue;
- misleading AI outputs;
- compromised credentials;
- excessive trust in AI.

An attacker may attempt to compromise the human's **decision process** rather than directly compromise the model.

D-AIGAAF therefore includes human-AI interaction in security assurance.

## 23. Autonomy-Security Interaction

Security risk increases in significance when an AI system can act autonomously.

A compromised recommendation system may influence a human.

A compromised autonomous system may directly initiate actions.

D-AIGAAF therefore requires autonomy to be considered explicitly in security risk assessment.

As autonomy increases, organisations should generally require stronger:

- authentication;
- authorisation;
- monitoring;
- intervention;
- fail-safe;
- testing;
- assurance.

## 24. Operational Environment

Security controls should be evaluated in the environment where the AI operates.

Relevant conditions may include:

- contested communications;
- disconnected operation;
- hostile inputs;
- compromised infrastructure;
- degraded sensors;
- limited maintenance;
- limited external support.

A security control that depends on continuous connectivity may fail precisely when the system is most exposed.

## 25. Fail-Safe and Security Failure

A security compromise can become a safety or mission event.

D-AIGAAF therefore connects:

**Security Failure**
→ **Incident Classification**
→ **Protective Response**
→ **Safe State**
→ **Investigation**
→ **Corrective Action**
→ **Revalidation**
→ **Reauthorisation**

The response should be proportionate to the consequence.

## 26. Continuous Security Assurance

AI security is dynamic.

Threats evolve.

Models change.

Dependencies change.

Operating environments change.

Therefore D-AIGAAF requires continuous monitoring of:

- security indicators;
- attack attempts;
- anomalous behaviour;
- dependency changes;
- model changes;
- data changes;
- vulnerability information;
- incident trends.

Security assurance should be refreshed when evidence changes materially.

## 27. Security Change Management

AI security must be reassessed following changes to:

- model;
- training data;
- prompts;
- system architecture;
- tools;
- APIs;
- dependencies;
- infrastructure;
- permissions;
- operating environment.

Change classification should determine whether the change requires:

- targeted security testing;
- regression testing;
- adversarial evaluation;
- full TEVV;
- revalidation;
- reauthorisation.

## 28. Security Evidence

Security evidence may include:

- threat models;
- architecture reviews;
- vulnerability assessments;
- penetration tests;
- adversarial evaluations;
- red-team reports;
- configuration records;
- supplier assessments;
- incident reports;
- monitoring data;
- remediation records;
- revalidation results.

Evidence should be tied to the actual configuration and environment.

## 29. Security Assurance

Security assurance asks:

> **How confident are we that the AI capability's security controls remain adequate for the intended mission and threat environment?**

Confidence should consider:

- threat coverage;
- evidence quality;
- test depth;
- residual vulnerabilities;
- operational conditions;
- dependency risk;
- autonomy;
- human control;
- incident history.

A system can have a strong cybersecurity posture and still have unacceptable AI-specific risks.

## 30. AI Security and Operational Authorisation

Security evidence informs operational authorisation.

A significant unresolved AI security vulnerability may require:

- additional controls;
- reduced autonomy;
- restricted employment;
- temporary suspension;
- remediation;
- additional testing;
- revalidation;
- reauthorisation.

The principle is:

> **Security assurance is an input to operational authority, not a substitute for it.**

## 31. AI Security Golden Thread

The AI-security chain is:

**Mission**
→ Threat Environment

**Threat Environment**
→ Threat Model

**Threat Model**
→ Security Risk

**Security Risk**
→ Security Requirements

**Security Requirements**
→ Controls

**Controls**
→ Security Testing

**Security Testing**
→ Adversarial Evaluation

**Evaluation**
→ Evidence

**Evidence**
→ Assurance

**Assurance**
→ Operational Conditions

**Conditions**
→ Authorisation

**Employment**
→ Continuous Monitoring

**Incident / Change**
→ Revalidation

**Revalidation**
→ Reauthorisation where required

## 32. Framework Crosswalk Summary

| Reference | Primary Contribution | D-AIGAAF Integration |
|---|---|---|
| NIST AI RMF | AI risk governance | Risk, measurement, management, assurance |
| NIST AML taxonomy | Adversarial ML terminology | Threat modelling and adversarial TEVV |
| MITRE ATLAS | AI attack knowledge | Threat modelling and red teaming |
| OWASP ML Security | ML vulnerabilities | Secure architecture and testing |
| OWASP LLM Top 10 | LLM application risks | LLM and agent security |
| ISO/IEC 27001 | Information-security management | Security governance foundation |
| ISO/IEC 23894 | AI risk management | AI security risk |
| ISO/IEC 42001 | AI management system | AI security governance and improvement |
| Secure-by-design guidance | Security lifecycle | Security from requirements through deployment |
| Defence AI assurance | Mission assurance | Operational security and authorisation |

## 33. Defence-Specific Extensions

D-AIGAAF extends general AI security frameworks with:

### 33.1 Mission Consequence

Security impact is assessed in terms of mission consequences.

### 33.2 Autonomy

Security controls scale with the system's authority to act.

### 33.3 Human Authority

Security boundaries include human decision and intervention mechanisms.

### 33.4 Operational Environment

Threats are assessed under realistic operating conditions.

### 33.5 Degraded Operation

Security assumptions are tested when connectivity and supporting infrastructure fail.

### 33.6 Fail-Safe

Security compromise can trigger protective system states.

### 33.7 Reauthorisation

Material security changes or incidents can invalidate operational authority.

### 33.8 Supply Chain

AI dependencies are included in the security boundary.

## 34. Evidence Expectations

A mature AI-security governance system should be able to demonstrate:

- defined security ownership;
- AI threat model;
- security requirements;
- architecture controls;
- data protection;
- model integrity;
- supplier assurance;
- adversarial evaluation;
- red-team findings;
- vulnerability management;
- incident response;
- continuous monitoring;
- secure change management;
- revalidation;
- authorisation conditions.

## 35. Relationship to Other Module 19 Crosswalks

Serial 12 is the dedicated **AI security and adversarial layer**.

It complements:

- **Serial 06:** IndiaAI responsible-AI principles;
- **Serial 07:** IndiaAI governance guidelines;
- **Serial 08:** DPDP legal data-protection layer;
- **Serial 09:** Indian AI policy and standards;
- **Serial 10:** defence responsible-AI principles;
- **Serial 11:** TEVV and AI assurance;
- **Serial 13:** integrated crosswalk methodology.

This separation prevents cybersecurity, AI safety and AI governance from being treated as identical disciplines.

## 36. Implementation Guidance

An organisation implementing D-AIGAAF should:

1. Define the AI system boundary.
2. Identify assets and dependencies.
3. Establish the threat model.
4. Identify AI-specific attack surfaces.
5. Assess mission consequences.
6. Define security requirements.
7. Implement controls.
8. Conduct adversarial testing.
9. Conduct red teaming where appropriate.
10. Record evidence.
11. Evaluate residual risk.
12. Establish security assurance.
13. Define operational conditions.
14. Feed security results into authorisation.
15. Monitor continuously.
16. Reassess following incidents and changes.

## 37. Limitations

This crosswalk does not claim:

- that any single AI-security framework is complete;
- that conventional cybersecurity is unnecessary;
- that red teaming proves security;
- that passing security tests eliminates risk;
- that threat catalogues predict every attack;
- that a secure AI system is automatically safe;
- that security assurance automatically authorises operational use.

Security must remain contextual and mission-specific.

## 38. Primary Reference Basis

Relevant sources include:

- NIST AI Risk Management Framework and associated AI-security work.
- NIST adversarial machine-learning taxonomy.
- MITRE ATLAS.
- OWASP Machine Learning Security guidance.
- OWASP Top 10 for LLM Applications.
- ISO/IEC 27001.
- ISO/IEC 23894.
- ISO/IEC 42001.
- CISA and UK NCSC secure-AI development guidance.
- NATO and defence responsible-AI and assurance material.

Framework versions should be reviewed periodically because AI threats and defensive techniques evolve rapidly.

## 39. Final Crosswalk Position

AI security is not merely a subset of conventional cybersecurity.

For consequential defence AI:

**Cybersecurity**
→ protects systems and information

**AI Security**
→ additionally protects data, models, inference, instructions, tools, agents and AI behaviour

**AI Safety**
→ addresses harmful behaviour and consequences

**AI Assurance**
→ establishes justified confidence

**Operational Authorisation**
→ determines whether and under what conditions the capability may be used

D-AIGAAF therefore establishes:

**Threat → Risk → Requirement → Control → Adversarial Test → Evidence → Assurance → Authority → Employment → Monitoring → Revalidation**

The central principle is:

> **An AI capability must remain secure not only against compromise of its infrastructure, but against attacks that manipulate what the AI perceives, produces, recommends or does.**

And for autonomous or consequential systems:

> **Security controls must be strong enough to preserve meaningful human authority even when the AI system, its data, its dependencies or its operating environment are under attack.**
