# 04-Crosswalk to ISO IEC 27001

## 1. Purpose

This crosswalk maps D-AIGAAF against **ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements**.

ISO/IEC 27001 specifies requirements for establishing, implementing, maintaining, and continually improving an information security management system (ISMS), including requirements for assessing and treating information-security risks. citeturn0search0turn0search5

D-AIGAAF uses the ISMS concept as an important foundation for AI security and information protection but extends it to address AI-specific risks, model and data integrity, adversarial AI threats, autonomy, human authority, operational environments, operational authorisation, and continuous assurance.

This document is an alignment crosswalk, not a declaration that D-AIGAAF is compliant with ISO/IEC 27001 or that implementation of D-AIGAAF automatically satisfies ISO/IEC 27001 certification requirements.

## 2. Standard Baseline

The assessed reference is:

- **Standard:** ISO/IEC 27001:2022
- **Title:** Information security, cybersecurity and privacy protection — Information security management systems — Requirements
- **Edition:** Third edition
- **Publication:** October 2022
- **Status:** International Standard

ISO describes ISO/IEC 27001 as the world's best-known standard for information security management systems and states that it defines requirements for an ISMS. citeturn0search0

ISO also explains that organisations using the standard can manage information-security risks in a structured manner and that certification is possible through an independent certification process. citeturn0search0turn0search5

## 3. Fundamental Relationship

The relationship can be expressed as:

**ISO/IEC 27001 → Information Security Management System**

**D-AIGAAF → Defence AI Governance, including AI Security and Operational Governance**

Information security is a necessary component of defence AI governance, but it is not sufficient by itself.

D-AIGAAF therefore treats information security as one part of a larger governance chain:

**Mission → AI Risk → Data/Information → Security → Human Authority → TEVV → Assurance → Authorisation → Employment**

## 4. High-Level Crosswalk

| ISO/IEC 27001 Area | Principal D-AIGAAF Coverage | Relationship |
|---|---|---|
| ISMS governance | 01 Strategy & Governance | Direct Alignment + Extension |
| Organisational context | 01 Governance; 02 Mission & Use Case | Direct Alignment |
| Information-security risk | 03 Risk & Autonomy; 06 AI Security | Direct Alignment + AI Extension |
| Risk treatment | 03 Risk & Autonomy; 06 AI Security | Direct Alignment |
| Security policy | 01 Governance; 06 AI Security; 21 Legal & Policy | Direct Alignment |
| Roles and responsibilities | 01 Governance; 08 Human Authority; 17 Workforce | Direct Alignment |
| Asset / information protection | 05 Data & Information; 06 AI Security; 24 Architecture | Direct Alignment + Extension |
| Access control | 06 AI Security; 24 Architecture & Technical Controls | Direct Alignment |
| Supplier security | 07 Supply Chain & Sovereignty; 22 Acquisition | Direct Alignment + Extension |
| Security incident management | 06 AI Security; 14 Incident & Fail-Safe | Direct Alignment + AI Extension |
| Business continuity | 07 Supply Chain; 10 Operational Environment; 14 Incident | Complementary + Defence Extension |
| Logging / evidence | 06 Security; 12 Employment; 16 Audit & Evidence | Direct Alignment + Extension |
| Monitoring | 06 Security; 13 Continuous Assurance | Direct Alignment + Extension |
| Internal audit | 16 Audit & Evidence | Direct Alignment |
| Continual improvement | 13 Assurance; 18 Maturity; 27 Implementation | Direct Alignment |
| AI-specific security | 06 AI Security | D-AIGAAF Extension |
| Adversarial AI | 06 AI Security | D-AIGAAF Extension |
| Model integrity | 05 Data; 06 Security; 24 Architecture | D-AIGAAF Extension |
| AI autonomy security | 03 Risk & Autonomy; 06 Security; 11 Authorisation | D-AIGAAF Extension |
| Human control | 08 Human Authority; 12 Employment | D-AIGAAF Extension |
| Operational authorisation | 11 Operational Authorisation | D-AIGAAF Specific |

## 5. ISMS and AI Security Governance

ISO/IEC 27001 provides a management-system architecture for information security.

D-AIGAAF adopts a compatible management-system principle but recognises that AI introduces additional security concerns.

For AI systems, security may involve:

- training data;
- model weights;
- model behaviour;
- inference inputs;
- prompts and instructions where applicable;
- interfaces;
- tools;
- connected systems;
- AI agents;
- model updates;
- supply-chain components;
- deployment infrastructure;
- operational users.

Therefore:

**AI Security ≠ Conventional Information Security Alone**

D-AIGAAF uses ISO/IEC 27001-compatible security governance as a foundation while adding AI-specific threat and control considerations.

## 6. Organisational Context

ISO/IEC 27001 requires the organisation to understand internal and external issues relevant to the ISMS.

D-AIGAAF expands organisational context into:

**Organisation + Mission + AI Capability + Environment + Autonomy + Human Authority + Dependencies**

This matters because the security requirements of an AI capability depend not only on the organisation's information assets but also on what the AI is permitted to influence.

For example, compromise of an AI used solely for administrative analysis may have a different consequence from compromise of an AI supporting consequential operational decisions.

## 7. Information Security Risk Management

ISO/IEC 27001 requires an information-security risk-management process.

D-AIGAAF provides:

- AI threat modelling;
- AI security risk assessment;
- adversarial evaluation;
- AI security controls;
- security assurance;
- security incident response;
- supply-chain risk;
- operational-environment risk.

The key extension is to connect security risk to AI behaviour and operational consequence.

The D-AIGAAF chain is:

**Security Threat → AI Behaviour → Decision Influence → Action → Consequence**

This allows a security vulnerability to be assessed according to its operational significance.

## 8. Risk Assessment and AI-Specific Threats

Traditional information-security risk assessment remains relevant.

D-AIGAAF adds AI-specific threat considerations, including where applicable:

- data poisoning;
- model manipulation;
- adversarial inputs;
- prompt or instruction manipulation;
- model extraction;
- unauthorised model changes;
- compromised dependencies;
- malicious tool use;
- unexpected model behaviour;
- integrity loss;
- availability loss;
- compromised AI supply chains.

The exact threat set should be tailored to the architecture and use case.

## 9. Risk Treatment

ISO/IEC 27001 provides a structured approach to selecting and implementing information-security risk treatments.

D-AIGAAF extends treatment options to include:

- reduce autonomy;
- restrict mission scope;
- impose environmental boundaries;
- increase human approval;
- increase monitoring;
- require additional TEVV;
- isolate or restrict interfaces;
- strengthen model/data controls;
- replace a compromised dependency;
- suspend employment;
- revert to a safe state;
- require revalidation;
- require reauthorisation.

This connects security risk treatment directly to operational governance.

## 10. Statement of Applicability and D-AIGAAF Controls

ISO/IEC 27001 implementations commonly use a risk-based process to determine applicable controls and document their treatment.

D-AIGAAF similarly requires controls to be selected according to:

- mission;
- risk;
- autonomy;
- environment;
- architecture;
- threat;
- human authority;
- dependencies;
- consequence.

The D-AIGAAF control architecture should therefore complement, rather than duplicate, an existing ISO/IEC 27001 control environment.

Where an organisation already operates an ISO/IEC 27001 ISMS, D-AIGAAF can identify AI-specific controls and governance extensions that need to be integrated into the existing security management system.

## 11. Asset and Information Governance

ISO/IEC 27001 addresses information assets and their protection.

D-AIGAAF extends the concept to AI-relevant assets such as:

- training data;
- validation and test data;
- models;
- model parameters or weights;
- prompts and system instructions where relevant;
- AI configurations;
- evaluation datasets;
- AI logs;
- decision records;
- assurance evidence;
- model cards or equivalent documentation;
- system interfaces;
- AI tools;
- supporting infrastructure.

Protection requirements should be determined by the consequence and sensitivity of the asset.

## 12. Data Integrity

Information integrity is central to ISO/IEC 27001.

D-AIGAAF applies this specifically to AI data.

Relevant concerns include:

- unauthorised modification;
- poisoning;
- provenance loss;
- lineage gaps;
- stale information;
- corrupted data;
- unrepresentative data;
- distribution shift.

The operational chain is:

**Data Integrity → Model/Input Integrity → AI Output Integrity → Decision Integrity**

This makes data integrity an AI governance and operational-assurance concern.

## 13. Model Integrity

Model integrity is a specific D-AIGAAF extension.

Governance should establish controls for:

- approved model versions;
- configuration baselines;
- model provenance;
- model change control;
- integrity verification;
- authorised updates;
- rollback capability;
- evaluation evidence;
- revalidation triggers;
- reauthorisation triggers.

A model that changes without appropriate control may no longer be the model that was previously tested or authorised.

## 14. Access Control

ISO/IEC 27001 provides extensive access-control governance.

D-AIGAAF incorporates access control into AI security and technical controls.

Access should be considered for:

- model development;
- training data;
- model repositories;
- deployment environments;
- inference interfaces;
- AI tools;
- administrative functions;
- operational controls;
- configuration;
- autonomy settings;
- logs;
- authorisation records.

Access to autonomy-related controls may require stronger governance than ordinary information access because unauthorised modification can alter the consequences of AI behaviour.

## 15. Human Authority and Access

D-AIGAAF distinguishes technical access from operational authority.

A user may technically have access to an AI system without having authority to:

- change its autonomy;
- alter operational boundaries;
- approve its use;
- accept residual risk;
- change mission scope;
- authorise consequential actions.

Therefore:

**Technical Permission ≠ Operational Authority**

This distinction is important when integrating D-AIGAAF with an existing ISO/IEC 27001 access-control architecture.

## 16. Supplier and Third-Party Security

ISO/IEC 27001 addresses supplier relationships and information-security requirements.

D-AIGAAF expands this through Module 07 and Module 22.

AI supplier governance may include:

- model provenance;
- data provenance;
- supplier security;
- component integrity;
- update mechanisms;
- dependency visibility;
- vulnerability disclosure;
- continuity;
- concentration risk;
- strategic dependency;
- sovereignty considerations.

External AI components should remain subject to appropriate governance after procurement.

## 17. Cloud and External AI Services

Where AI capabilities depend on external infrastructure or services, D-AIGAAF should integrate relevant information-security controls with operational governance.

Governance questions include:

- What happens if the service becomes unavailable?
- What happens if the provider changes the model?
- Can the provider alter system behaviour?
- Can the organisation verify changes?
- What data leaves the controlled environment?
- What happens if connectivity is lost?
- Can the capability operate safely without the external service?
- Does the dependency affect authorisation?

These questions extend ordinary supplier-security assessment into operational continuity and authority.

## 18. Security Incident Management

ISO/IEC 27001 provides information-security incident-management requirements.

D-AIGAAF adds AI-specific incident governance through Module 06 and Module 14.

The combined logic is:

**Detect → Report → Classify → Protect → Contain → Fail-Safe → Investigate → Correct → Recover → Reassess → Reauthorise Where Required → Learn**

The response must consider not only information compromise but also whether the AI capability remains trustworthy and operationally authorised.

## 19. Loss of AI Integrity

A security incident may compromise:

- confidentiality;
- integrity;
- availability;
- authenticity;
- model behaviour;
- data trustworthiness;
- human confidence.

D-AIGAAF therefore treats loss of AI integrity as potentially more than an IT security event.

It may become:

**Security Incident → AI Assurance Event → Operational Risk Event → Authorisation Review**

## 20. Business Continuity and Resilience

ISO/IEC 27001 includes information-security continuity considerations.

D-AIGAAF expands resilience to AI operational continuity.

Relevant scenarios include:

- loss of communications;
- loss of external services;
- degraded data;
- model unavailability;
- sensor degradation;
- infrastructure disruption;
- supplier failure;
- cyber compromise;
- unexpected AI behaviour.

The governance objective is not simply to keep the system running.

It is:

> Maintain safe, controlled, and authorised behaviour when normal operating assumptions fail.

## 21. Degraded and Disconnected Operations

D-AIGAAF Module 10 and Module 12 explicitly address degraded and disconnected operation.

The framework should determine:

- whether the AI remains usable;
- whether its outputs remain sufficiently trustworthy;
- what information becomes stale;
- what functions become unavailable;
- whether human control remains effective;
- whether autonomy boundaries change;
- what safe state applies;
- whether employment should cease.

This extends information-security continuity into operational AI governance.

## 22. Logging and Traceability

ISO/IEC 27001 supports logging and evidence necessary for security monitoring and investigation.

D-AIGAAF extends logging to include, where appropriate:

- AI outputs;
- relevant inputs;
- model/version identity;
- configuration;
- autonomy state;
- human interventions;
- overrides;
- consequential decisions;
- authorisation state;
- security events;
- environmental state;
- changes;
- incidents.

Records should be proportionate to the consequence and legal requirements.

## 23. Monitoring

Security monitoring is integrated into D-AIGAAF Continuous Assurance.

Monitoring should consider:

- security indicators;
- model integrity;
- data integrity;
- anomalous behaviour;
- access events;
- configuration changes;
- dependency status;
- environmental changes;
- performance degradation;
- human-control indicators.

A security monitoring event may therefore trigger an assurance or authorisation review.

## 24. Vulnerability and Exposure Management

D-AIGAAF should integrate AI-specific vulnerabilities into the organisation's broader vulnerability-management processes.

Potential AI-specific considerations include:

- model vulnerabilities;
- data vulnerabilities;
- AI framework dependencies;
- tool vulnerabilities;
- inference-interface weaknesses;
- supply-chain weaknesses;
- model update mechanisms;
- adversarial attack surfaces.

The risk treatment should be linked to consequence and operational exposure.

## 25. Secure Development and AI Lifecycle

ISO/IEC 27001 security controls can support secure development practices.

D-AIGAAF integrates security throughout the AI lifecycle:

**Requirements → Development → Data → Model → Integration → TEVV → Deployment → Employment → Monitoring → Change → Revalidation → Reauthorisation**

Security is therefore not limited to deployment.

Security requirements should be established early enough to influence architecture, data, model selection, integration, and procurement decisions.

## 26. Security and TEVV

D-AIGAAF Module 09 includes dedicated security and adversarial evaluation.

Security evidence may include:

- threat-model results;
- adversarial testing;
- vulnerability assessment;
- robustness testing;
- integrity verification;
- security-control testing;
- dependency assessment;
- incident-response exercises.

Security assurance should feed into operational authorisation.

## 27. Security and Autonomy

Autonomous behaviour increases the significance of certain security failures.

The relevant relationship is:

**Security Compromise → Autonomy → Potential Consequence**

As autonomy increases, governance should consider:

- attack surface;
- speed of AI action;
- ability to detect compromise;
- human intervention time;
- reversibility;
- boundary enforcement;
- fail-safe behaviour.

A security control that is adequate for advisory AI may be inadequate for higher-consequence autonomous behaviour.

## 28. Security and Human Control

Security failures can undermine meaningful human control.

Examples include situations where:

- the human receives manipulated information;
- AI outputs conceal relevant uncertainty;
- interfaces prevent effective intervention;
- autonomy settings are altered;
- communications are degraded;
- system status is misleading.

D-AIGAAF therefore treats security as a prerequisite for trustworthy human control.

## 29. Security and Operational Authorisation

Security posture should form part of the conditions under which an AI capability is authorised.

The authorisation logic is:

**Security Requirements → Security Controls → Security Testing → Security Evidence → Assurance → Authorisation Conditions**

A material deterioration in security posture may require:

**Suspend / Restrict → Investigate → Reassess → Revalidate → Reauthorise**

## 30. Security and Continuous Assurance

Security assurance does not end after deployment.

D-AIGAAF requires ongoing monitoring of:

- threats;
- vulnerabilities;
- dependencies;
- model changes;
- data changes;
- configuration changes;
- operational environment;
- incidents.

This creates:

**Security Monitoring → Assurance Update → Risk Review → Authorisation Review Where Required**

## 31. Audit Crosswalk

ISO/IEC 27001 includes internal audit and management review within the ISMS.

D-AIGAAF Module 16 provides an integrated audit architecture.

Security audit evidence should be connected to:

**Requirement → Control → Implementation → Test → Finding → Corrective Action → Verification**

Where a finding affects AI assurance or operational authority, it should also connect to:

**Assurance → Revalidation → Reauthorisation**

## 32. Corrective Action

ISO/IEC 27001 uses corrective action and continual improvement to maintain ISMS effectiveness.

D-AIGAAF expands corrective action to account for AI-specific consequences.

Possible actions include:

- patch;
- retrain;
- replace data;
- replace model;
- restrict capability;
- reduce autonomy;
- increase human oversight;
- isolate dependency;
- change operational boundary;
- suspend employment;
- initiate revalidation;
- initiate reauthorisation.

## 33. Security Governance Maturity

D-AIGAAF Module 18 may assess the maturity of AI-security governance.

Maturity should consider:

**Initial → Developing → Defined → Managed → Institutionalised**

Assessment should include:

- governance;
- threat modelling;
- controls;
- testing;
- monitoring;
- incident response;
- workforce;
- supply chain;
- evidence;
- continuous improvement.

A mature security-management system does not guarantee that a particular AI system is secure against every threat.

## 34. Relationship to ISO/IEC 42001

ISO/IEC 42001 and ISO/IEC 27001 address different but complementary management-system needs.

Conceptually:

**ISO/IEC 42001 → AI Management System**

**ISO/IEC 27001 → Information Security Management System**

**D-AIGAAF → Defence AI Governance and Operational Authorisation**

D-AIGAAF can integrate the outputs of both management systems.

For example:

**AIMS → AI Risk**

**ISMS → Information/Security Risk**

**D-AIGAAF → Mission/Autonomy/Human Authority/Operational Risk**

These should converge before operational authorisation.

## 35. Relationship to ISO/IEC 23894

ISO/IEC 23894 provides AI-specific risk-management guidance.

D-AIGAAF can integrate:

**ISO/IEC 23894 → AI Risk Management**

with:

**ISO/IEC 27001 → Information Security Management**

and:

**ISO/IEC 42001 → AI Management System**

to create a more comprehensive governance environment.

D-AIGAAF then adds the defence operational layer.

## 36. Defence-Specific Extensions

The principal D-AIGAAF extensions beyond conventional ISMS governance include:

1. AI-specific threat modelling;
2. adversarial AI evaluation;
3. model integrity governance;
4. AI data integrity;
5. autonomy-security interaction;
6. human-control security;
7. operational environment;
8. degraded/disconnected operation;
9. operational authorisation;
10. operational employment;
11. fail-safe and safe-state governance;
12. change-triggered reauthorisation.

These extensions recognise that an AI security compromise can affect decisions and actions, not merely information assets.

## 37. Integrated Security Governance Model

An organisation using ISO/IEC 27001 and D-AIGAAF may implement the following architecture:

### Layer 1 — ISMS

Establish information-security governance, risk management, controls, monitoring, audit, and continual improvement.

### Layer 2 — AI Security

Use D-AIGAAF Module 06 to identify and govern AI-specific security risks.

### Layer 3 — AI Risk

Use D-AIGAAF Module 03 and ISO/IEC 23894-compatible methods to assess AI risk.

### Layer 4 — TEVV and Assurance

Use Modules 09 and 13 to generate and maintain evidence.

### Layer 5 — Operational Governance

Use Modules 10–12 to assess environment, authorisation, and employment.

### Layer 6 — Incident and Change

Use Modules 14–15 to maintain control after incidents or changes.

## 38. Recommended Combined Control Flow

**Identify Information Assets**

↓

**Identify AI Assets and Dependencies**

↓

**Threat Model**

↓

**Assess Risk**

↓

**Select Security and AI Controls**

↓

**Implement**

↓

**Test / Evaluate**

↓

**Generate Evidence**

↓

**Assure**

↓

**Set Operational Conditions**

↓

**Authorise**

↓

**Employ**

↓

**Monitor**

↓

**Detect Security or AI Changes**

↓

**Reassess**

↓

**Revalidate / Reauthorise Where Required**

## 39. What D-AIGAAF Should Not Claim

D-AIGAAF should not state that:

- implementing D-AIGAAF automatically establishes ISO/IEC 27001 conformity;
- an ISO/IEC 27001-certified ISMS automatically provides AI security assurance;
- information-security certification automatically authorises AI operational use;
- ISO/IEC 27001 covers every AI-specific threat;
- AI security is equivalent to conventional cybersecurity; or
- a high security maturity score guarantees safe AI behaviour.

The correct position is:

> ISO/IEC 27001 provides a foundational information-security management system that D-AIGAAF can integrate with and extend for AI-specific and defence operational risks.

## 40. Crosswalk Maintenance

This crosswalk should be reviewed when:

- ISO/IEC 27001 is revised;
- amendments or corrigenda materially affect requirements;
- relevant ISO/IEC 27002 guidance changes;
- AI-security threats materially evolve;
- D-AIGAAF Module 06 changes;
- major AI architectural patterns change;
- regulatory requirements change;
- operational experience identifies a material gap.

The crosswalk record should contain:

- standard edition;
- D-AIGAAF version;
- crosswalk version;
- assessment date;
- responsible owner;
- reviewer;
- assumptions;
- limitations;
- identified gaps;
- review trigger.

## 41. Source and Version Record

Primary source:

**ISO/IEC 27001:2022 — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.**

ISO identifies ISO/IEC 27001:2022 as the current published requirements standard for information security management systems and states that it provides requirements for establishing, implementing, maintaining, and continually improving an ISMS. citeturn0search0turn0search5

ISO also describes the standard as providing a systematic approach to managing information-security risks and supporting independent certification where an organisation chooses to pursue it. citeturn0search0

This crosswalk should be reviewed against the authoritative ISO publication and relevant supporting standards, particularly ISO/IEC 27002 and AI-specific security guidance, as D-AIGAAF evolves.
