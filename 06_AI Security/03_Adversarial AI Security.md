# D-AIGAAF — Adversarial AI Security

## 1. Purpose

This document defines the requirements for assessing and managing adversarial threats against Defence AI systems throughout their lifecycle.

Adversarial AI security addresses attempts to manipulate, deceive, degrade, exploit, or subvert an AI system through inputs, data, models, software, dependencies, interfaces, or operational conditions.

The objective is to preserve:

- Integrity of AI outputs and decisions
- Availability of AI-enabled functions
- Confidentiality of protected information
- Reliability and robustness under hostile conditions
- Human authority and control
- Mission effectiveness
- Traceability and accountability

## 2. Scope

Adversarial AI security should consider threats arising from:

1. Manipulated or deceptive inputs
2. Adversarial examples and crafted inputs
3. Data poisoning or corruption
4. Model manipulation or tampering
5. Prompt or instruction manipulation
6. Compromised software, libraries, models, or dependencies
7. Interface and integration vulnerabilities
8. Sensor deception or spoofing
9. Communications manipulation or degradation
10. Model extraction, inference, or unauthorised access
11. Attempts to induce unsafe or unintended behaviour
12. Insider or supply-chain compromise
13. Adversarial conditions not represented in development or testing

The assessment should be tailored to the AI capability, mission, autonomy level, environment, and consequence of failure.

## 3. Adversarial Threat Model

Every consequential Defence AI capability should maintain an adversarial threat model covering:

- Assets requiring protection
- Threat actors and sources
- Attack surfaces
- Trust boundaries
- Attack objectives
- Plausible attack paths
- Expected effects
- Existing controls
- Detection mechanisms
- Recovery and fail-safe measures
- Residual risk

Threat modelling should be updated when the system, mission, environment, threat picture, or dependencies materially change.

## 4. Adversarial Attack Categories

D-AIGAAF should consider at least the following categories.

### 4.1 Input Manipulation

Inputs may be deliberately altered to cause incorrect classification, detection, recommendation, or action.

Examples include:

- Crafted sensor inputs
- Misleading imagery
- False or manipulated observations
- Malicious prompts or instructions
- Deliberately ambiguous inputs

### 4.2 Data Poisoning

Training, validation, fine-tuning, retrieval, or operational data may be manipulated to introduce persistent or context-dependent undesirable behaviour.

Controls should address:

- Data-source trust
- Provenance
- Integrity verification
- Access control
- Dataset review
- Anomaly detection
- Controlled update pipelines

### 4.3 Model Manipulation

The model or model-serving environment may be altered to change behaviour.

Controls should include:

- Model integrity verification
- Cryptographic signing where appropriate
- Controlled model repositories
- Version control
- Configuration baselines
- Access restrictions
- Independent validation after material changes

### 4.4 Instruction and Interface Manipulation

AI systems may receive conflicting, malicious, or unauthorised instructions through user interfaces, connected applications, tools, or data sources.

Systems should establish:

- Trusted instruction boundaries
- Authorised user roles
- Instruction precedence
- Input validation
- Tool-use restrictions
- Logging and traceability
- Human confirmation for consequential actions

### 4.5 Sensor and Perception Deception

Where AI relies on sensors or external observations, adversaries may attempt to create false perceptions of the operating environment.

Testing should consider whether the AI can:

- Detect inconsistent observations
- Express uncertainty
- Reject unreliable inputs
- Seek corroboration
- Degrade safely
- Avoid converting uncertain observations into unjustified consequential actions

### 4.6 Availability Attacks

An adversary may attempt to prevent an AI capability from functioning when required.

Potential mechanisms include:

- Resource exhaustion
- Denial of service
- Communications disruption
- Dependency failure
- Deliberate degradation of supporting systems

Critical capabilities should have defined degraded modes and recovery procedures.

### 4.7 Confidentiality and Model Extraction

AI systems may expose sensitive information through:

- Unauthorised queries
- Model outputs
- Logs
- Interfaces
- Retrieval systems
- Model extraction techniques

Controls should follow applicable security classification, information assurance, and access-control requirements.

## 5. Adversarial Robustness Requirements

Before operational authorisation, the system should demonstrate resilience appropriate to its risk level.

Assessment should include, where applicable:

- Adversarial input testing
- Data integrity testing
- Robustness testing
- Fault injection
- Sensor-deception testing
- Interface abuse testing
- Model integrity verification
- Dependency compromise scenarios
- Degraded communications testing
- Offline or disconnected operation
- Recovery testing

Higher-consequence and higher-autonomy systems require proportionately stronger adversarial assurance.

## 6. Defence-in-Depth Controls

No single security control should be assumed sufficient.

Controls should operate across multiple layers:

**Data → Model → Software → Infrastructure → Interface → Human → Mission**

Controls may include:

- Input validation
- Data provenance
- Secure development practices
- Model integrity controls
- Access control
- Network and interface protections
- Runtime monitoring
- Anomaly detection
- Human confirmation
- Fail-safe mechanisms
- Independent assurance
- Incident response

## 7. Detection and Monitoring

Operational monitoring should identify indications of adversarial interference or unexpected behaviour.

Relevant indicators may include:

- Sudden performance degradation
- Unusual input distributions
- Unexpected output patterns
- Increased uncertainty
- Repeated rejected inputs
- Abnormal system interactions
- Configuration changes
- Unexpected model behaviour
- Dependency or integrity alerts

Detection thresholds should be linked to operational risk and escalation procedures.

## 8. Response to Suspected Adversarial Compromise

When adversarial compromise is suspected, the system should support a graduated response.

A response may include:

1. Detect
2. Record
3. Assess
4. Contain
5. Restrict or suspend affected functions
6. Notify the responsible authorities
7. Preserve relevant evidence
8. Recover or transition to a safe state
9. Revalidate before restoration
10. Reauthorise where required

Emergency protective actions may be taken immediately where delay could create unacceptable harm, subject to pre-authorised procedures.

## 9. Human Authority

Adversarial AI security must preserve meaningful human authority over consequential outcomes.

Where an AI system produces an anomalous, compromised, or highly uncertain recommendation:

- Human decision-makers should be able to reject or override it.
- The system should communicate relevant uncertainty and limitations.
- Consequential autonomous functions should have defined suspension mechanisms.
- The decision and circumstances should be recorded where practicable.

The ability to disable an AI capability is a safeguard, not a substitute for layered prevention, detection, assurance, and human judgement.

## 10. Assurance Evidence

The Defence AI Assurance Record should contain evidence appropriate to the capability, including:

- Adversarial threat model
- Security requirements
- Test plans and results
- Known attack limitations
- Vulnerability findings
- Mitigation status
- Model and software integrity evidence
- Configuration baseline
- Monitoring arrangements
- Incident-response procedures
- Residual risk assessment
- Revalidation evidence following material changes

## 11. Continuous Adversarial Assurance

Adversarial security is not a one-time certification activity.

Assurance should be revisited when:

- The threat environment changes
- New vulnerabilities are identified
- The model or software changes
- Data sources change materially
- New interfaces or dependencies are introduced
- Mission use changes
- Autonomy increases
- Operational evidence indicates unexpected behaviour
- An adversarial incident occurs

Material changes should trigger the applicable D-AIGAAF change-impact, revalidation, and reauthorisation processes.

## 12. Core Principle

> **A Defence AI system should be assumed to operate in an adversarial environment and should demonstrate appropriate resilience before being trusted with consequential operational functions.**

Adversarial AI security should therefore be integrated with risk management, autonomy controls, TEVV, human authority, operational authorisation, supply-chain assurance, and continuous monitoring rather than treated as a standalone cybersecurity activity.
