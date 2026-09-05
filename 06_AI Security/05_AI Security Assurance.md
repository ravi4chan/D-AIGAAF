# D-AIGAAF — AI Security Assurance

## 1. Purpose

This document defines how AI security assurance should demonstrate that security controls are effective, proportionate to risk, and maintained throughout the operational lifecycle.

AI security assurance should establish reasonable confidence that a Defence AI capability can resist, detect, contain, and recover from security threats relevant to its authorised use.

## 2. Assurance Objectives

Security assurance should demonstrate that:

- The AI capability has identified relevant security threats.
- Security requirements are defined and traceable.
- Security controls are implemented as intended.
- Controls operate effectively in the intended environment.
- Models, software, data, and dependencies maintain integrity.
- Security-relevant behaviour is monitored during operation.
- Known limitations and residual risks are documented.
- Material changes trigger appropriate reassessment.
- Evidence supports operational authorisation.

## 3. Assurance Scope

Security assurance should cover the complete AI-enabled system rather than the model alone.

The assessment should consider:

1. Data
2. Models
3. Software
4. Hardware and infrastructure
5. Interfaces
6. Communications and dependencies
7. Users and administrators
8. Operational environment
9. Security controls
10. Human authority and response mechanisms

## 4. Assurance Evidence

The Defence AI Assurance Record should maintain appropriate evidence, including:

- Threat models
- Security requirements
- Architecture and trust-boundary documentation
- Configuration baselines
- Vulnerability assessments
- Adversarial test results
- Security test reports
- Model integrity evidence
- Software and dependency records
- Access-control evidence
- Monitoring and logging evidence
- Incident records
- Remediation records
- Residual-risk assessments
- Independent assessment findings

Evidence should be traceable to the requirement, control, test, finding, and resulting decision where practicable.

## 5. Security Testing

Testing should be proportionate to the capability's consequence, autonomy, and threat exposure.

Testing may include:

- Vulnerability assessment
- Penetration testing
- Adversarial AI testing
- Input-manipulation testing
- Data-poisoning assessment
- Model-integrity testing
- Interface security testing
- Authentication and authorisation testing
- Fault injection
- Availability and resilience testing
- Recovery testing
- Configuration-integrity testing
- Secure update testing

Testing should include realistic operational conditions where those conditions can materially affect security behaviour.

## 6. Adversarial Evaluation

For higher-risk systems, security assurance should include structured adversarial evaluation.

Assessment should attempt to determine whether an adversary can:

- Manipulate inputs
- Corrupt relevant data
- Alter or substitute models
- Exploit interfaces
- Bypass access controls
- Influence system behaviour
- Degrade availability
- Extract protected information
- Cause unsafe or unintended system responses
- Circumvent human authority

Findings should be evaluated against the authorised operational envelope.

## 7. Independent Assurance

Where consequence warrants it, security assurance should include independent assessment.

Independence may be achieved through:

- Separate assessment teams
- Independent technical reviewers
- Red-team or adversarial assessment
- External evaluation where appropriate
- Separation between development and assurance functions

The degree of independence should increase with system criticality and consequence.

## 8. Security Assurance Levels

D-AIGAAF may apply a graduated assurance approach.

| Assurance Level | Typical Application |
|---|---|
| Basic | Low-consequence informational AI |
| Standard | Routine operational decision-support |
| Enhanced | Mission-critical or elevated-threat AI |
| High | Highly autonomous or high-consequence functions |
| Exceptional | Systems capable of independently producing severe consequences |

These levels are a working D-AIGAAF construct and should be mapped to applicable national, defence, legal, and regulatory assurance schemes before formal adoption.

## 9. Security Findings

Security findings should be categorised according to their potential effect.

A finding should identify:

- Description
- Affected component
- Threat or vulnerability
- Potential consequence
- Likelihood or exposure
- Existing mitigation
- Residual risk
- Required corrective action
- Responsible owner
- Due date
- Verification status

Critical unresolved findings should normally prevent operational authorisation unless explicitly accepted by the competent authority under an established risk process.

## 10. Residual Security Risk

Security assurance cannot demonstrate the absence of all possible threats.

The objective is to establish that:

- Significant threats have been identified.
- Appropriate controls are implemented.
- Controls have been tested.
- Known limitations are understood.
- Residual risk is visible.
- The appropriate authority has accepted the remaining risk where necessary.

Residual security risk should remain linked to the operational authorisation.

## 11. Security Assurance and Operational Authorisation

Security assurance provides evidence; it does not itself grant operational authority.

Operational authorisation should consider security assurance together with:

- Mission requirements
- Consequence
- Autonomy
- Human authority
- Operational environment
- Safety
- Legal and policy constraints
- Mission effectiveness
- Remaining limitations

A capability should not be treated as operationally authorised merely because it has passed a security assessment.

## 12. Continuous Security Assurance

Security assurance should continue after deployment.

Monitoring should identify changes in:

- Threat exposure
- Vulnerabilities
- Model behaviour
- Data sources
- Software dependencies
- Configuration
- Interfaces
- Mission use
- Autonomy
- Operational environment

New evidence should be incorporated into the assurance record.

## 13. Trigger Events for Reassessment

Security reassessment should be considered or required following:

- Security incidents
- Newly discovered vulnerabilities
- Material software changes
- Material model changes
- Changes to data sources
- New interfaces
- New external dependencies
- Changes in autonomy
- Changes in mission
- Significant environmental changes
- Evidence of unexpected or anomalous behaviour

The required response should follow the D-AIGAAF change-impact and reauthorisation processes.

## 14. Assurance Status

A capability's security assurance status may be expressed as:

**Not Assessed → Under Assessment → Assured with Conditions → Assured → Restricted → Suspended → Reassessment Required**

These states should be linked to defined decision rights and operational consequences.

## 15. Assurance Limitations

Security assurance should explicitly record what was not tested or could not be demonstrated.

Examples include:

- Unavailable operational environments
- Untested threat conditions
- Unverified third-party dependencies
- Limited test data
- Unknown vulnerabilities
- Unassessed interfaces
- Constraints on independent testing

Uncertainty should be visible rather than represented as assurance.

## 16. Core Principle

> **AI security assurance should provide evidence-based confidence that security risks are understood, controls are effective, limitations are visible, and the capability remains trustworthy within its authorised operational boundaries.**
