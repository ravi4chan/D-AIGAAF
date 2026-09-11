# 06-AI Security Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 06 — AI Security**.

These templates provide practical instruments for identifying, assessing, controlling, testing and responding to security risks affecting AI capabilities across their lifecycle.

D-AIGAAF treats AI security as broader than conventional cybersecurity.

The security boundary includes:

- data;
- models;
- model weights;
- prompts and instructions;
- retrieval systems;
- tools;
- interfaces;
- agents;
- dependencies;
- infrastructure;
- human users;
- operational authority;
- AI-to-AI interactions.

The central principle is:

> **AI security must protect not only the system that runs the AI, but also the information, model behaviour, instructions, tools and operational authority through which the AI can create consequences.**

---

# 2. Template Set

The recommended AI Security template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-06-001 | AI Security Governance Record |
| D-AIGAAF-T-06-002 | AI Security Requirements Record |
| D-AIGAAF-T-06-003 | AI Threat Model |
| D-AIGAAF-T-06-004 | AI Attack Surface Assessment |
| D-AIGAAF-T-06-005 | Adversarial AI Security Assessment |
| D-AIGAAF-T-06-006 | AI Security Control Assessment |
| D-AIGAAF-T-06-007 | AI Security Assurance Record |
| D-AIGAAF-T-06-008 | AI Security Incident Record |
| D-AIGAAF-T-06-009 | AI Red-Team Assessment |
| D-AIGAAF-T-06-010 | AI Model Integrity Assessment |
| D-AIGAAF-T-06-011 | AI Data Poisoning Assessment |
| D-AIGAAF-T-06-012 | Prompt Injection & Instruction Security Assessment |
| D-AIGAAF-T-06-013 | AI Agent & Tool Security Assessment |
| D-AIGAAF-T-06-014 | AI Supply-Chain Security Assessment |
| D-AIGAAF-T-06-015 | AI Access & Privilege Assessment |
| D-AIGAAF-T-06-016 | AI Security Monitoring Record |
| D-AIGAAF-T-06-017 | AI Security Change Assessment |
| D-AIGAAF-T-06-018 | AI Security Recovery & Revalidation Record |
| D-AIGAAF-T-06-019 | AI Security Exception Record |
| D-AIGAAF-T-06-020 | AI Security Governance Review |

---

# 3. Template 06-001 — AI Security Governance Record

## Purpose

Defines security governance responsibilities for an AI capability.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Security owner
- Technical owner
- Risk owner
- Assurance owner
- Operational authority
- Authorisation authority
- Classification
- Security policy basis
- Security baseline
- Review date

## Governance Questions

- Who owns AI security risk?
- Who can approve security exceptions?
- Who can suspend the capability?
- Who evaluates security evidence?
- Who determines whether security conditions remain suitable for operation?

---

# 4. Template 06-002 — AI Security Requirements Record

## Purpose

Defines security requirements specific to the AI capability.

## Requirement Categories

- confidentiality;
- integrity;
- availability;
- authenticity;
- provenance;
- model integrity;
- data integrity;
- instruction integrity;
- access control;
- supply-chain security;
- adversarial robustness;
- monitoring;
- incident response;
- recovery.

## Required Fields

- Requirement ID
- Requirement
- Threat addressed
- Rationale
- Control
- Verification method
- Evidence
- Owner
- Status

Security requirements should be linked to mission consequence and risk.

---

# 5. Template 06-003 — AI Threat Model

## Purpose

Provides a structured threat model for the AI capability.

## Threat Categories

Consider:

- malicious users;
- insiders;
- external attackers;
- adversarial inputs;
- data poisoning;
- model manipulation;
- backdoors;
- model extraction;
- prompt injection;
- tool abuse;
- supply-chain compromise;
- compromised dependencies;
- sensor manipulation;
- information manipulation;
- denial of service;
- privacy/inference attacks.

## Required Fields

- Threat ID
- Threat actor
- Asset
- Attack path
- Preconditions
- Likelihood
- Consequence
- Existing controls
- Detection
- Response
- Residual risk

The threat model should be updated when the architecture, environment or threat landscape changes.

---

# 6. Template 06-004 — AI Attack Surface Assessment

## Purpose

Identifies interfaces and components through which the AI capability may be attacked or manipulated.

## Attack Surface Areas

- data inputs;
- sensors;
- networks;
- APIs;
- model endpoints;
- prompts;
- system instructions;
- retrieval systems;
- plugins/tools;
- external models;
- human interfaces;
- update mechanisms;
- logging;
- administrative interfaces;
- physical access.

## Required Fields

- Attack surface
- Exposure
- Asset
- Threat
- Control
- Test
- Residual risk
- Owner

---

# 7. Template 06-005 — Adversarial AI Security Assessment

## Purpose

Assesses how the AI behaves under deliberate adversarial manipulation.

## Assessment Areas

- adversarial inputs;
- evasion;
- poisoning;
- model manipulation;
- prompt injection;
- jailbreaks;
- data manipulation;
- sensor deception;
- retrieval manipulation;
- tool manipulation;
- denial of service.

## Required Fields

- Attack scenario
- Objective
- Preconditions
- Method
- Observed behaviour
- Defence
- Detection
- Impact
- Severity
- Remediation
- Retest requirement

---

# 8. Template 06-006 — AI Security Control Assessment

## Purpose

Determines whether required security controls are implemented and effective.

## Control Categories

### Preventive

- access control;
- isolation;
- validation;
- authentication;
- input controls.

### Detective

- monitoring;
- anomaly detection;
- logging;
- integrity checking.

### Corrective

- containment;
- rollback;
- credential revocation;
- model replacement;
- safe-state transition.

## Required Fields

- Control ID
- Requirement
- Control
- Implementation status
- Evidence
- Test
- Finding
- Effectiveness
- Residual risk
- Owner

---

# 9. Template 06-007 — AI Security Assurance Record

## Purpose

Provides a consolidated assessment of security assurance.

## Assessment Inputs

- threat model;
- security requirements;
- control assessment;
- adversarial testing;
- red-team results;
- incidents;
- vulnerabilities;
- configuration;
- monitoring;
- supplier evidence.

## Required Fields

- Assurance scope
- Evidence
- Findings
- Limitations
- Confidence
- Residual security risk
- Reviewer
- Conclusion
- Conditions

Security assurance should communicate uncertainty and evidence limitations.

---

# 10. Template 06-008 — AI Security Incident Record

## Purpose

Records security incidents affecting an AI capability.

## Incident Categories

- compromise;
- data poisoning;
- model manipulation;
- prompt injection;
- credential compromise;
- malicious tool use;
- data exfiltration;
- denial of service;
- sensor manipulation;
- supply-chain compromise;
- unauthorised access.

## Required Fields

- Incident ID
- Date/time
- Capability
- Detection
- Attack vector
- Affected component
- Operational impact
- Immediate protection
- Containment
- Evidence
- Root cause
- Recovery
- Risk reassessment
- Revalidation
- Reauthorisation requirement

---

# 11. Template 06-009 — AI Red-Team Assessment

## Purpose

Records structured adversarial evaluation of the AI capability.

## Required Sections

### Objective

What security or safety property is being challenged?

### Scope

- model;
- application;
- data;
- tools;
- interfaces;
- human interaction;
- operational environment.

### Scenarios

Include, as appropriate:

- adversarial inputs;
- manipulation;
- deception;
- prompt injection;
- tool abuse;
- model extraction;
- data poisoning;
- loss of control.

### Results

Record:

- attack;
- outcome;
- severity;
- detectability;
- exploitability;
- consequence;
- mitigation;
- retest.

Red teaming should be proportionate to mission consequence and threat exposure.

---

# 12. Template 06-010 — AI Model Integrity Assessment

## Purpose

Assesses whether the deployed model corresponds to the approved and evaluated model.

## Required Fields

- Model ID
- Approved version
- Deployed version
- Hash/checksum where appropriate
- Source
- Build process
- Dependencies
- Integrity controls
- Verification result
- Anomaly
- Response

## Key Question

> **Is the model being used operationally the model that was assessed and authorised?**

---

# 13. Template 06-011 — AI Data Poisoning Assessment

## Purpose

Assesses the risk that malicious or compromised data could influence AI behaviour.

## Assessment Areas

- training data;
- fine-tuning data;
- validation data;
- operational inputs;
- retrieval sources;
- feedback data.

## Required Fields

- Dataset
- Source
- Trust level
- Integrity control
- Poisoning scenario
- Detection
- Impact
- Mitigation
- Residual risk
- Monitoring

---

# 14. Template 06-012 — Prompt Injection & Instruction Security Assessment

## Purpose

Assesses threats arising from manipulation of prompts, system instructions, retrieved content or other instruction channels.

## Assessment Areas

- direct prompt injection;
- indirect prompt injection;
- malicious retrieved content;
- instruction hierarchy;
- tool invocation;
- privilege escalation;
- system-prompt leakage;
- instruction conflicts.

## Required Fields

- Scenario
- Attack vector
- Expected behaviour
- Observed behaviour
- Control
- Test
- Severity
- Remediation
- Retest

For agentic systems, instruction security should be assessed together with tool permissions and action authority.

---

# 15. Template 06-013 — AI Agent & Tool Security Assessment

## Purpose

Assesses security risks arising when AI systems can use tools, APIs or external systems.

## Assessment Areas

- tool inventory;
- permissions;
- authentication;
- privilege;
- action scope;
- data access;
- external communications;
- human approval;
- rate limits;
- logging;
- rollback;
- safe state.

## Required Fields

- Agent ID
- Tool
- Permission
- Allowed action
- Prohibited action
- Human approval
- Consequence
- Control
- Test
- Monitoring

## Principle

> **The authority available to an AI agent should not exceed the authority necessary for its authorised mission.**

---

# 16. Template 06-014 — AI Supply-Chain Security Assessment

## Purpose

Assesses security risks introduced by suppliers, dependencies and externally sourced AI components.

## Assessment Areas

- model provenance;
- software;
- libraries;
- datasets;
- hardware;
- firmware;
- APIs;
- external models;
- cloud services;
- update channels;
- subcontractors.

## Required Fields

- Supplier/component
- Dependency
- Criticality
- Threat
- Assurance
- Evidence
- Alternative
- Continuity
- Monitoring
- Exit strategy

---

# 17. Template 06-015 — AI Access & Privilege Assessment

## Purpose

Determines whether human and machine access to the AI capability is appropriately restricted.

## Assessment Areas

- users;
- administrators;
- developers;
- operators;
- agents;
- service accounts;
- APIs;
- tools.

## Required Fields

- Identity
- Role
- Permission
- Required authority
- Privilege level
- Authentication
- Approval
- Monitoring
- Review date

Principle of least privilege should be applied proportionately.

---

# 18. Template 06-016 — AI Security Monitoring Record

## Purpose

Records ongoing monitoring of security indicators.

## Indicators

Monitor as appropriate:

- anomalous inputs;
- failed authentication;
- unusual tool calls;
- data access;
- model integrity;
- prompt attacks;
- security alerts;
- network anomalies;
- performance anomalies;
- unexpected autonomy.

## Required Fields

- Indicator
- Baseline
- Threshold
- Current status
- Trend
- Alert
- Response
- Owner
- Review date

---

# 19. Template 06-017 — AI Security Change Assessment

## Purpose

Determines whether a change affects the security posture of the AI capability.

## Changes

Consider:

- model;
- software;
- data;
- prompt/instructions;
- tools;
- APIs;
- network;
- infrastructure;
- supplier;
- access permissions.

## Assessment

Determine impact on:

- attack surface;
- threats;
- controls;
- evidence;
- residual risk;
- assurance;
- authorisation.

Material changes should enter Module 15 change governance.

---

# 20. Template 06-018 — AI Security Recovery & Revalidation Record

## Purpose

Records recovery following a significant security event or compromise.

## Required Sections

### Protection

- containment;
- isolation;
- suspension;
- credential revocation.

### Investigation

- evidence;
- affected components;
- root cause;
- scope.

### Recovery

- remediation;
- restoration;
- integrity verification;
- security testing.

### Revalidation

- tests;
- residual risk;
- assurance;
- authorisation implications.

The capability should not automatically return to operational use merely because technical restoration is complete.

---

# 21. Template 06-019 — AI Security Exception Record

## Purpose

Records deviations from required security controls.

## Required Fields

- Exception ID
- Requirement
- Control
- Deviation
- Reason
- Risk
- Compensating control
- Duration
- Approval authority
- Monitoring
- Expiry
- Review

Exceptions should be:

- explicit;
- time-bounded where possible;
- risk-assessed;
- authorised.

---

# 22. Template 06-020 — AI Security Governance Review

## Purpose

Provides periodic review of the overall AI security posture.

## Review Areas

- threat landscape;
- vulnerabilities;
- attack surface;
- controls;
- red-team findings;
- incidents;
- model integrity;
- data integrity;
- supply chain;
- agent/tool permissions;
- monitoring;
- changes;
- residual risk.

## Review Questions

1. Has the threat environment changed?
2. Has the attack surface changed?
3. Are security controls effective?
4. Has the model changed?
5. Has operational data changed?
6. Have new dependencies been introduced?
7. Have new AI-specific attacks emerged?
8. Are red-team findings closed?
9. Is security assurance still sufficient?
10. Does the authorisation remain valid?

---

# 23. AI Security Boundary

D-AIGAAF uses a broad AI security boundary:

**Data**
→ **Model**
→ **Instructions**
→ **Application**
→ **Tools**
→ **Interfaces**
→ **Infrastructure**
→ **Human**
→ **Operational Authority**

A compromise at any relevant layer may affect the overall security posture.

---

# 24. Security-to-Mission Relationship

AI security assessment should be consequence-driven.

The sequence is:

**Threat**
→ **Vulnerability**
→ **AI Behaviour**
→ **Operational Consequence**
→ **Risk**
→ **Control**
→ **Adversarial Test**
→ **Evidence**
→ **Assurance**

This prevents security analysis from becoming detached from mission impact.

---

# 25. AI Security and Autonomy

Security failures can change effective autonomy.

For example:

- compromised instructions may cause unexpected behaviour;
- compromised tools may expand action capability;
- manipulated inputs may change decisions;
- compromised models may alter outputs.

Therefore:

> **A security compromise that changes AI behaviour or authority may also constitute an autonomy and authorisation event.**

Such events should trigger the relevant D-AIGAAF processes.

---

# 26. AI Security and Human Authority

Human control must remain meaningful during security incidents.

Templates should identify:

- who can suspend the system;
- who can isolate it;
- who can revoke permissions;
- who can transition it to a safe state;
- who can authorise restoration.

Security controls should not create an unintended situation in which authorised humans cannot intervene.

---

# 27. AI Security and Degraded Operations

Security assessments should consider:

- loss of network;
- limited bandwidth;
- disconnected operation;
- degraded sensors;
- limited compute;
- unavailable security services.

The capability should have defined behaviour when security dependencies become unavailable.

---

# 28. AI Security and Fail-Safe

Where a security condition creates unacceptable risk, the capability should have an authorised protective response.

Possible responses include:

- restrict;
- isolate;
- reduce autonomy;
- require human confirmation;
- disable affected function;
- transition to safe state;
- suspend operation.

The appropriate response depends on mission and system consequence.

---

# 29. Security Evidence Package

For a consequential AI capability, the security evidence package should normally include:

- governance record;
- security requirements;
- threat model;
- attack surface assessment;
- adversarial assessment;
- control assessment;
- security assurance;
- red-team assessment;
- model integrity;
- data poisoning assessment;
- instruction security;
- agent/tool assessment;
- supply-chain assessment;
- access/privilege assessment;
- monitoring;
- change records;
- incident records;
- recovery/revalidation;
- exceptions.

---

# 30. Review Questions

Before operational authorisation, reviewers should ask:

1. What are the credible AI-specific threats?
2. What can an attacker influence?
3. What is the mission consequence?
4. Can the model be manipulated?
5. Can operational data be poisoned?
6. Can instructions be manipulated?
7. Can tools be abused?
8. Can privileges be escalated?
9. Is the model's integrity verifiable?
10. Are suppliers and dependencies understood?
11. Has adversarial testing been performed?
12. Has red teaming challenged the relevant assumptions?
13. Can humans detect and intervene following compromise?
14. What happens if communications fail?
15. What happens after compromise?
16. Is revalidation required?
17. Is reauthorisation required?

---

# 31. Anti-Pattern — Cybersecurity Alone

D-AIGAAF rejects:

**Traditional Cybersecurity**
→ **AI Security Complete**

AI introduces additional attack and failure surfaces involving:

- model behaviour;
- data;
- instructions;
- retrieval;
- agents;
- tools;
- adversarial examples;
- model integrity;
- AI-to-AI interaction.

Traditional cybersecurity remains necessary but may not be sufficient.

---

# 32. Anti-Pattern — Security as a Pre-Deployment Gate

Security should not be treated as:

**Test Once**
→ **Secure Forever**

The correct lifecycle is:

**Threat**
→ **Control**
→ **Test**
→ **Deploy**
→ **Monitor**
→ **Detect**
→ **Respond**
→ **Reassess**
→ **Revalidate**
→ **Reauthorise where required**

---

# 33. Final AI Security Principle

The AI Security templates establish a security governance chain spanning the complete AI capability.

The governing principle is:

> **Protect the AI capability against threats that could alter its information, behaviour, authority or ability to operate safely within its authorised mission.**

The complete security chain is:

**Threat**
→ **Attack Surface**
→ **Risk**
→ **Requirement**
→ **Control**
→ **Adversarial Test**
→ **Evidence**
→ **Assurance**
→ **Human Authority**
→ **Operational Authorisation**
→ **Monitoring**
→ **Incident**
→ **Recovery**
→ **Revalidation**
→ **Reauthorisation**

AI security is therefore not merely protection of the infrastructure around the model.

It is protection of the **entire socio-technical system through which AI can influence consequential decisions and actions**.
