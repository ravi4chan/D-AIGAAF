# D-AIGAAF — AI Security Controls

## 1. Purpose

This document defines the control framework for protecting Defence AI systems against compromise, misuse, manipulation, unauthorised access, and unintended security consequences.

Controls should be proportionate to:

- Consequence of failure
- Mission criticality
- Autonomy level
- Operational environment
- Threat exposure
- System complexity
- Dependence on external components

## 2. Control Objectives

AI security controls should preserve:

1. **Confidentiality** — protect information and system assets from unauthorised disclosure.
2. **Integrity** — prevent unauthorised modification of data, models, software, configurations, and outputs.
3. **Availability** — maintain required capability or safe degraded operation.
4. **Authenticity** — establish trust in users, systems, data, models, and dependencies.
5. **Traceability** — maintain sufficient records to reconstruct relevant security events.
6. **Resilience** — withstand, detect, contain, and recover from security disruption.
7. **Human Authority** — prevent security compromise from silently transferring consequential authority to an AI system.

## 3. Security Control Domains

D-AIGAAF should organise controls across the following domains:

| Domain | Primary Objective |
|---|---|
| Identity & Access | Ensure only authorised entities can access or influence the system |
| Data Security | Protect data integrity, provenance, confidentiality, and availability |
| Model Security | Protect models from unauthorised alteration, substitution, or extraction |
| Software & Infrastructure | Protect the technical environment supporting AI |
| Interface Security | Control interactions between AI and external systems |
| Runtime Security | Detect and respond to abnormal behaviour during operation |
| Configuration Security | Maintain an approved and traceable system baseline |
| Supply-Chain Security | Establish trust in developers, components, dependencies, and updates |
| Human Security | Reduce misuse, insider threats, and unsafe operator practices |
| Recovery & Continuity | Restore or safely degrade capability following compromise |

## 4. Identity and Access Controls

Access should follow least privilege and role-based principles.

Controls should address:

- User authentication
- Privileged access
- Service identities
- Administrative access
- Role separation
- Credential protection
- Access review
- Removal of inactive or unauthorised accounts
- Logging of privileged actions

Access to consequential AI functions should require stronger controls than access to low-risk informational functions.

## 5. Data Security Controls

Data controls should protect the complete data lifecycle.

Controls should include, where appropriate:

- Data classification
- Authorised collection
- Source verification
- Integrity protection
- Provenance recording
- Access control
- Secure transfer
- Controlled modification
- Retention rules
- Secure disposal

Data used to train, validate, operate, or evaluate AI should be protected against unauthorised manipulation.

## 6. Model Security Controls

Model security should establish confidence that the deployed model corresponds to the authorised baseline.

Controls may include:

- Model version identification
- Model integrity verification
- Controlled repositories
- Digital signing where appropriate
- Restricted model modification
- Version history
- Independent comparison after updates
- Protection against unauthorised model substitution
- Controlled model export and replication

Material changes to model behaviour should trigger the applicable D-AIGAAF change and revalidation process.

## 7. Software and Infrastructure Controls

The supporting technical environment should be treated as part of the AI security boundary.

Controls should address:

- Secure software development
- Dependency management
- Vulnerability management
- Patch management
- Configuration hardening
- Platform integrity
- Secure deployment
- Infrastructure access
- Logging
- Backup and recovery
- Isolation of critical functions

Security assurance should include components on which AI behaviour materially depends.

## 8. Interface and Integration Controls

AI systems frequently interact with other systems, users, sensors, databases, applications, or tools.

Each integration should define:

- Purpose
- Trust relationship
- Data exchanged
- Permitted commands or actions
- Authentication requirements
- Authorisation boundaries
- Failure behaviour
- Logging requirements
- Security monitoring
- Disconnection or isolation procedures

Interfaces capable of influencing consequential actions require particular scrutiny.

## 9. Runtime Security Controls

During operation, the system should be monitored for security-relevant anomalies.

Monitoring may include:

- Unexpected inputs
- Abnormal output patterns
- Configuration changes
- Unauthorised access attempts
- Unexpected system interactions
- Integrity failures
- Performance anomalies
- Increased uncertainty
- Unexpected changes in model behaviour

Security monitoring should support escalation to appropriate human authorities.

## 10. Configuration and Baseline Controls

Every operationally authorised AI capability should have an identifiable configuration baseline.

The baseline should identify, as applicable:

- Model version
- Software version
- Hardware/platform configuration
- Data and knowledge dependencies
- External services
- Interfaces
- Security controls
- Relevant parameters
- Approved operating conditions

Unauthorised deviation from the baseline should be detected and assessed.

## 11. Supply-Chain Security Controls

Supply-chain assurance should establish confidence in the provenance and integrity of critical AI components.

Assessment should consider:

- Developer and supplier identity
- Component provenance
- Third-party dependencies
- Open-source dependencies
- Model origin
- Update mechanisms
- Maintainer access
- Subcontractors
- Software and model repositories
- Known vulnerabilities
- Ability of external parties or components to modify system behaviour

Critical dependencies should have appropriate alternatives, mitigation measures, or risk acceptance.

## 12. Human and Insider Controls

Security controls should account for authorised personnel who may intentionally or unintentionally compromise a system.

Measures may include:

- Role separation
- Access limitation
- Training
- Security awareness
- Privileged-action monitoring
- Dual control for selected consequential functions
- Conflict-of-interest management
- Incident reporting mechanisms

Controls should support accountability without assuming that every security event is caused by an external attacker.

## 13. Fail-Safe and Protective Controls

AI systems with consequential functions should have defined protective states.

Depending on the capability, these may include:

- Safe degradation
- Function restriction
- Isolation
- Human takeover
- Suspension
- Controlled shutdown

A fail-safe mechanism should be tested before operational authorisation.

Where immediate action is necessary to prevent unacceptable harm, pre-authorised emergency procedures may permit immediate protective intervention.

## 14. Control Effectiveness

Security controls should not be considered effective merely because they exist.

Effectiveness should be demonstrated through:

- Inspection
- Testing
- Adversarial assessment
- Technical validation
- Operational exercises
- Monitoring evidence
- Incident experience
- Independent assurance

Evidence should be retained in the Defence AI Assurance Record.

## 15. Security Control Selection

Control intensity should increase with risk.

A simplified principle is:

**Higher Consequence + Higher Autonomy + Higher Threat Exposure = Stronger Controls + Stronger Assurance**

Controls should therefore be tailored rather than applied uniformly to every AI capability.

## 16. Security Exceptions

Any deviation from required security controls should be:

- Explicitly identified
- Risk assessed
- Documented
- Approved by the appropriate authority
- Time bounded where practicable
- Monitored
- Reviewed before continuation

A security exception should not silently become the permanent operating condition.

## 17. Continuous Improvement

Security controls should be reassessed following:

- Security incidents
- Newly identified vulnerabilities
- Material system changes
- New dependencies
- Changes in mission
- Changes in autonomy
- Changes in the threat environment
- Evidence of unexpected behaviour

Material changes should trigger the applicable D-AIGAAF revalidation and reauthorisation process.

## 18. Core Principle

> **AI security controls should protect not only the AI model, but the complete socio-technical system through which AI can influence information, decisions, and consequential actions.**
