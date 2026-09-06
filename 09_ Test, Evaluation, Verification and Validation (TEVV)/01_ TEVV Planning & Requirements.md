# D-AIGAAF — TEVV Planning & Requirements

## 1. Purpose

This document defines how Test, Evaluation, Verification and Validation (TEVV) should be planned from the earliest stages of a Defence AI capability lifecycle.

TEVV planning ensures that requirements, risks, operational conditions, autonomy, human control, and assurance evidence are connected before testing begins.

## 2. Core Principle

> **TEVV should be designed from the requirements and risk profile of the mission, not added as a final testing activity after development.**

The planned evidence should be sufficient to support an informed assurance and operational-authorisation decision.

## 3. TEVV Planning Inputs

TEVV planning should consider:

- Mission need.
- Use case.
- Operational context.
- Mission success criteria.
- Consequence of failure.
- Mission criticality.
- Authorised autonomy.
- Operational environment.
- Threat model.
- AI requirements.
- Data characteristics.
- Human authority arrangements.
- Security requirements.
- Applicable legal and policy requirements.
- Supply-chain dependencies.

## 4. Requirements-to-Test Traceability

Each material requirement should have a defined method of demonstrating satisfaction.

A useful chain is:

**Requirement → Risk → Test/Evaluation Method → Evidence → Acceptance Criterion → Assurance Decision**

Requirements without an appropriate verification or validation method should be identified early.

## 5. TEVV Strategy

A TEVV strategy should define:

- What will be tested.
- What will be evaluated.
- What will be verified.
- What will be validated.
- When testing will occur.
- Who will conduct it.
- What evidence is required.
- What constitutes acceptable performance.
- What limitations must be recorded.
- What findings require escalation.

## 6. Risk-Based TEVV

TEVV depth should increase with:

- Consequence.
- Mission criticality.
- Autonomy.
- Environmental uncertainty.
- System complexity.
- Security exposure.
- Novelty.
- Irreversibility of potential outcomes.

Low-risk functions may require limited evidence, while high-consequence autonomous functions require substantially stronger evidence.

## 7. Test Categories

The TEVV plan should consider applicable categories such as:

### 7.1 Functional Testing

Does the system perform the functions it was designed to perform?

### 7.2 Performance Testing

Does it meet defined performance thresholds?

### 7.3 Robustness Testing

How does it behave under degraded or unexpected conditions?

### 7.4 Security Testing

Can security controls withstand relevant threats?

### 7.5 Human Factors Testing

Can authorised personnel correctly understand and use the system?

### 7.6 Autonomy Testing

Does the system remain within its authorised autonomy boundaries?

### 7.7 Operational Testing

Does the capability perform effectively in representative operational conditions?

### 7.8 Mission Validation

Does the capability provide meaningful mission value under realistic conditions?

## 8. Acceptance Criteria

Acceptance criteria should be established before final evaluation where practicable.

They may address:

- Minimum performance.
- Maximum acceptable error.
- Availability.
- Latency.
- Robustness.
- Security.
- Human intervention.
- Autonomy boundaries.
- Fail-safe behaviour.
- Mission effectiveness.

Acceptance criteria should reflect mission consequences rather than arbitrary technical targets.

## 9. Operationally Representative Testing

Testing should reproduce relevant operational characteristics wherever practicable.

This may include:

- Relevant environmental conditions.
- Realistic sensor characteristics.
- Communication constraints.
- Data quality variation.
- Expected workload.
- Representative users.
- Relevant adversarial conditions.
- Resource limitations.

A capability should not be considered operationally validated solely because it performs well under laboratory conditions.

## 10. Edge Cases and Failure Conditions

The TEVV plan should deliberately identify important edge cases.

These may include:

- Unusual inputs.
- Missing data.
- Conflicting information.
- Sensor failure.
- Communications loss.
- Unexpected environmental conditions.
- Adversarial inputs.
- Model uncertainty.
- System degradation.
- Human intervention.
- Failure of supporting dependencies.

Testing should seek to understand how the system fails, not only how it succeeds.

## 11. Autonomy-Specific Planning

For autonomous or semi-autonomous functions, the TEVV plan should explicitly address:

- Autonomy level.
- Permitted actions.
- Operating envelope.
- Constraint enforcement.
- Transition conditions.
- Human supervision.
- Intervention mechanisms.
- Fail-safe behaviour.
- Loss of communications.
- Loss of required information.

Autonomy claims should be supported by observed evidence.

## 12. Human-AI TEVV

Human-AI interaction should be evaluated as part of the complete system.

Testing should consider whether personnel can:

- Understand outputs.
- Recognise uncertainty.
- Detect incorrect recommendations.
- Exercise judgement.
- Reject AI recommendations.
- Override authorised behaviour.
- Respond within required time.
- Maintain situational awareness.

## 13. Security and Adversarial TEVV

The plan should incorporate testing derived from the system threat model.

Where applicable, this may include:

- Adversarial inputs.
- Data poisoning.
- Evasion.
- Model manipulation.
- Dependency compromise.
- Access-control failure.
- Configuration tampering.
- Data integrity attacks.

The scope should be proportionate to the threat and consequence.

## 14. Data for TEVV

TEVV data should be appropriately controlled and documented.

Records should identify, where relevant:

- Data source.
- Data characteristics.
- Version.
- Provenance.
- Preparation method.
- Known limitations.
- Representativeness.
- Separation of development and evaluation data.

Evaluation should avoid creating misleading confidence through inappropriate data reuse or leakage.

## 15. Test Environment and Baseline

Each significant evaluation should identify the relevant:

- System configuration.
- Model version.
- Software version.
- Hardware.
- Data.
- Dependencies.
- Security configuration.
- Operating conditions.

This enables results to be reproduced or interpreted correctly.

## 16. Independent Evaluation

The required degree of independent evaluation should be determined by risk.

Higher-consequence systems should receive greater scrutiny independent of the development team where practicable.

Independence may involve:

- Separate personnel.
- Separate test environments.
- Independent review.
- External assessment where appropriate.

## 17. TEVV Findings

Findings should be categorised according to their significance.

A finding may result in:

- Acceptance.
- Risk treatment.
- Additional testing.
- Restricted employment.
- Increased monitoring.
- Revalidation.
- Reauthorisation.
- Suspension of deployment.

Unresolved high-consequence findings should not be obscured by aggregate performance metrics.

## 18. TEVV Exit Criteria

Before a capability progresses to operational assurance or authorisation, the TEVV process should establish:

- Required testing completed.
- Critical requirements assessed.
- Material risks evaluated.
- Significant failures understood.
- Limitations documented.
- Evidence recorded.
- Unresolved issues dispositioned.
- Relevant acceptance criteria addressed.

Passing a test should not automatically mean that operational authorisation is granted.

## 19. Core Principle

TEVV planning should create a deliberate evidence architecture:

**Mission Requirement → Risk → Test Objective → Representative Condition → Result → Evidence → Finding → Assurance → Authorisation**

This ensures that testing answers the questions that matter for safe, secure, reliable, and accountable Defence AI employment.
