# D-AIGAAF — Operational Environment Assessment

## 1. Purpose

This document establishes a structured approach for assessing whether a Defence AI capability is sufficiently understood and assured for its intended operational environment.

The assessment connects environmental characterisation with risk, TEVV, human authority, autonomy and operational authorisation.

## 2. Core Principle

> **Operational environment suitability should be demonstrated through evidence and bounded by explicit assumptions, limitations and conditions.**

## 3. Assessment Scope

The assessment should consider, as relevant:

- Physical environment.
- Environmental variability.
- Degraded and disconnected conditions.
- Information environment.
- Electromagnetic environment.
- Adversarial conditions.
- Human operating environment.
- System dependencies.
- Autonomy implications.

The assessment should be proportionate to consequence, mission criticality and autonomy.

## 4. Assessment Inputs

The assessment should draw upon:

- Mission definition.
- Operational context.
- Environmental profile.
- Risk assessment.
- Autonomy assessment.
- TEVV results.
- Operational trials.
- Human factors evaluation.
- Security assessment.
- Known incidents and lessons.
- System and configuration records.

## 5. Assessment Questions

The assessment should establish:

1. Is the intended environment clearly defined?
2. Are material environmental variables understood?
3. Are important dependencies identified?
4. Are relevant conditions represented in TEVV?
5. Are degraded and disconnected conditions understood?
6. Are adversarial conditions considered?
7. Is human control achievable?
8. Are autonomy boundaries appropriate?
9. Are environmental limitations reflected in authorisation?

## 6. Environmental Evidence

Evidence should demonstrate, where relevant:

- Performance under representative conditions.
- Reliability.
- Robustness.
- Human-AI interaction.
- Security resilience.
- Degradation behaviour.
- Recovery behaviour.
- Mission effectiveness.

Evidence should be traceable to the relevant capability baseline and environmental conditions.

## 7. Environment Coverage

Assessment should distinguish between:

| Coverage | Meaning |
|---|---|
| Demonstrated | Supported by appropriate evidence |
| Partially demonstrated | Evidence exists but has limitations |
| Untested | Insufficient evidence available |
| Outside envelope | Not authorised for the condition |

These categories should not be treated as equivalent.

## 8. Environmental Gaps

Material gaps should be documented.

A gap record should identify:

- Condition not adequately assessed.
- Why the gap exists.
- Potential consequences.
- Associated risk.
- Existing controls.
- Additional evidence required.
- Responsible owner.
- Resolution status.

## 9. Boundary Assessment

The assessment should determine whether environmental boundaries are:

- Clearly defined.
- Evidence-based.
- Detectable where necessary.
- Operationally meaningful.
- Linked to appropriate controls.

Boundary conditions should be connected to risk and autonomy decisions.

## 10. Degraded and Disconnected Assessment

Where relevant, assessment should establish:

- What functions remain available.
- What information becomes unavailable or stale.
- What happens to autonomy.
- What human authority remains.
- What fallback mechanisms exist.
- How recovery occurs.

## 11. Adversarial Assessment

The assessment should consider whether foreseeable adversarial conditions can:

- Degrade inputs.
- Manipulate information.
- Disrupt communications.
- Affect system integrity.
- Mislead human users.
- Cause unsafe or uncontrolled behaviour.

Relevant findings should feed the AI Security and Risk & Autonomy processes.

## 12. Human Environment Assessment

Assessment should establish whether personnel can realistically:

- Understand relevant AI outputs.
- Interpret uncertainty.
- Exercise authority.
- Challenge recommendations.
- Intervene when required.
- Operate under expected workload and time pressure.

A technically available control should not be considered effective if it cannot realistically be exercised.

## 13. Environment and Autonomy Assessment

The assessment should determine whether the proposed autonomy level remains appropriate under:

- Nominal conditions.
- Challenging conditions.
- Degraded conditions.
- Communication loss.
- Information uncertainty.
- Adversarial conditions.

Autonomy should remain bounded by the demonstrated operating environment.

## 14. Dependency Assessment

Material dependencies should be assessed for:

- Availability.
- Reliability.
- Integrity.
- Failure modes.
- Recovery.
- Alternatives or fallback.

A capability should not rely on an unrecognised dependency for safe operation.

## 15. Assessment Outcomes

A practical assessment outcome may be:

- **Suitable** — sufficient evidence supports the intended environment.
- **Conditionally suitable** — operation is acceptable subject to defined restrictions and controls.
- **Insufficiently demonstrated** — additional evidence is required.
- **Not suitable** — identified environmental risks cannot currently be accepted.

These labels are a governance construct and may be adapted by the adopting organisation.

## 16. Conditions and Restrictions

Where suitability is conditional, the assessment should identify:

- Permitted environments.
- Restricted conditions.
- Required human supervision.
- Autonomy restrictions.
- Monitoring requirements.
- Fallback requirements.
- Suspension triggers.

Conditions should be reflected in the operational authorisation record.

## 17. Independent Review

For higher-consequence capabilities, an appropriately independent review should assess whether:

- Evidence is sufficient.
- Environmental assumptions are reasonable.
- Important gaps are recognised.
- Boundaries are justified.
- Controls are effective.
- Conclusions are supported by evidence.

## 18. Relationship to Operational Authorisation

The operational environment assessment should provide an input to the authorisation decision.

The authorising authority should be able to determine:

**What the capability can do → where it can do it → under what conditions → with what controls → with what residual risk**

## 19. Continuous Assurance

Operational environment assessment does not end at authorisation.

Operational evidence should be reviewed for:

- Unexpected environmental effects.
- Performance degradation.
- New environmental conditions.
- New dependencies.
- Repeated boundary crossings.
- New failure modes.

Material findings should feed continuous assurance.

## 20. Revalidation and Reauthorisation

Revalidation should be considered when:

- Environmental assumptions materially change.
- New operating conditions are introduced.
- Significant incidents occur.
- New evidence contradicts previous conclusions.
- AI or supporting systems materially change.
- Threat conditions change significantly.

Reauthorisation should follow where required by the significance of the change.

## 21. Assessment Record

The operational environment assessment record should contain, as appropriate:

- Capability identifier.
- Mission/use case.
- Environmental profile.
- Operating envelope.
- Key assumptions.
- Dependencies.
- TEVV evidence.
- Known limitations.
- Environmental gaps.
- Risk implications.
- Autonomy implications.
- Human-control considerations.
- Conditions and restrictions.
- Assessment conclusion.
- Review authority.
- Date and validity.

## 22. Governance Questions

Before authorisation, decision-makers should be able to answer:

1. Is the environment adequately characterised?
2. Is the operating envelope explicit?
3. Is there sufficient evidence across relevant conditions?
4. What remains unknown or untested?
5. What happens under degradation?
6. What happens under adversarial conditions?
7. Can humans maintain meaningful control?
8. Is the authorised autonomy appropriate?
9. What restrictions are required?
10. What future changes would require reassessment?

## 23. Core Rule

> **Operational environment suitability is an evidence-based assurance judgement, not an assumption that successful laboratory performance will transfer unchanged to operational conditions.**
