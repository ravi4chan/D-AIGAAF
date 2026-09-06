# 02 Authorisation Assessment

## 1. Purpose

This document defines the assessment process used to determine whether a Defence AI capability satisfies the requirements for proposed operational authorisation.

The assessment converts evidence, risks, limitations, controls and operational conditions into a structured recommendation for the appropriate authorising authority.

It does not itself grant operational authority.

---

## 2. Assessment Principle

Operational authorisation assessment shall determine whether the complete authorised context is sufficiently understood and controlled:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Assessment shall be:

- Evidence-based
- Risk-proportionate
- Context-specific
- Traceable
- Independent where appropriate
- Explicit about uncertainty
- Reversible
- Proportionate to consequence and autonomy

---

## 3. Assessment Inputs

The assessment should consider, as applicable:

- Mission definition
- Use-case definition
- Operational context
- Mission constraints
- Risk assessment
- Autonomy assessment
- Human-control assessment
- AI lifecycle records
- Data and information assurance
- AI security assessment
- Supply-chain assessment
- TEVV evidence
- Operational environment assessment
- Fail-safe arrangements
- Known limitations and failure modes
- Configuration baseline
- Monitoring plan
- Incident history
- Lessons learned
- Legal and policy constraints
- Residual-risk statement

---

## 4. Assessment Domains

The assessment should evaluate at least the following domains:

| Domain | Assessment Question |
|---|---|
| Capability | Is the capability sufficiently understood for the proposed use? |
| Mission | Is the intended mission/use case clearly bounded? |
| Risk | Are material risks identified and appropriately treated? |
| Autonomy | Is the proposed autonomy level justified and controlled? |
| Human Authority | Are decision rights, oversight and intervention clear? |
| Environment | Is the operating envelope sufficiently demonstrated? |
| Data | Are data quality, provenance and limitations understood? |
| Security | Are relevant AI and system security risks controlled? |
| Supply Chain | Are critical dependencies understood and acceptable? |
| TEVV | Is there sufficient evidence for the proposed use? |
| Fail-Safe | Can unacceptable behaviour be limited or safely terminated? |
| Monitoring | Can material degradation or emerging risk be detected? |
| Governance | Are accountability and authorisation responsibilities clear? |

---

## 5. Assessment Rating

Each material assessment criterion may be assigned one of the following ratings:

### A1 — Demonstrated

The requirement is supported by sufficient relevant evidence for the proposed operational context.

### A2 — Conditionally Demonstrated

The requirement is sufficiently supported only under specified conditions or restrictions.

### A3 — Partially Demonstrated

Some evidence exists, but material uncertainty or limitations remain.

### A4 — Not Demonstrated

Required evidence is absent, inadequate or not applicable to the proposed use.

### A5 — Contradicted

Available evidence indicates that the requirement or assumption is not satisfied.

These ratings are D-AIGAAF working constructs and may be mapped to formal national or organisational assurance terminology.

---

## 6. Evidence Sufficiency

Evidence sufficiency shall consider:

- Relevance to the proposed mission.
- Relevance to the operating environment.
- Representativeness of test conditions.
- Currency of evidence.
- Configuration tested.
- Independence of evaluation where appropriate.
- Reproducibility.
- Known limitations.
- Contradictory findings.
- Remaining uncertainty.

A large quantity of evidence does not necessarily constitute sufficient assurance if the evidence does not address the actual operational context.

---

## 7. Configuration Consistency

The assessment shall confirm that evidence corresponds to the configuration proposed for authorisation.

Particular attention should be given to:

- Model version.
- Model weights or equivalent model state where applicable.
- Software version.
- Hardware configuration.
- Data version or relevant data pipeline.
- System interfaces.
- Security controls.
- Autonomy settings.
- Human-machine interface.
- External dependencies.

Material differences between tested and proposed configurations shall be assessed for impact on authorisation.

---

## 8. Risk and Consequence Assessment

The assessment shall consider whether the proposed controls are proportionate to:

- Potential consequence.
- Mission criticality.
- Autonomy.
- Human-control capability.
- Environmental uncertainty.
- Adversarial exposure.
- Dependency risk.
- Failure detectability.
- Failure recoverability.

Higher-consequence uses should require stronger evidence and more restrictive conditions where appropriate.

---

## 9. Autonomy Assessment

The proposed autonomy level shall be assessed against:

- Intended function.
- Consequence of autonomous error.
- Human supervision.
- Intervention time.
- Override capability.
- Boundary controls.
- Transition conditions.
- Fail-safe behaviour.
- Evidence from autonomy testing.

Increasing autonomy shall normally require increased assurance and explicit authority.

---

## 10. Human Authority Assessment

The assessment shall determine whether:

- A responsible human authority is identified.
- Decision rights are explicit.
- The human understands the AI's role and limitations.
- Meaningful oversight is practicable.
- Intervention and override are available where required.
- Human workload is acceptable.
- Automation bias and over-reliance risks are addressed.
- Escalation arrangements exist.
- Material decisions can be appropriately recorded.

Human presence alone shall not be treated as meaningful human control.

---

## 11. Operational Environment Assessment

The assessment shall compare the proposed operating environment with demonstrated conditions.

It should consider:

- Nominal conditions.
- Challenging conditions.
- Boundary conditions.
- Degraded conditions.
- Disconnected conditions.
- Adversarial conditions.
- Sensor and information limitations.
- Human operating conditions.

Use outside the demonstrated envelope shall require explicit treatment rather than being assumed safe.

---

## 12. Security Assessment

The assessment shall determine whether relevant security risks have been:

- Identified.
- Tested.
- Controlled.
- Monitored.
- Assigned to accountable owners.

Material unresolved vulnerabilities may require restrictions, additional controls, suspension or refusal of authorisation.

---

## 13. Fail-Safe Assessment

The assessment shall determine whether fail-safe and fallback arrangements are:

- Defined.
- Accessible to authorised personnel.
- Appropriate to consequence and autonomy.
- Tested under relevant conditions.
- Resistant to foreseeable misuse or failure.
- Capable of placing the system in a controlled state.

Where immediate protective action is necessary, pre-authorised emergency procedures may be used subject to subsequent reporting and review.

---

## 14. Dependency Assessment

Critical dependencies shall be evaluated for:

- Availability.
- Integrity.
- Resilience.
- External control.
- Update mechanisms.
- Failure impact.
- Substitutability.
- Recovery options.

A capability should not receive unrestricted authorisation where critical dependencies are poorly understood.

---

## 15. Residual Risk Assessment

After controls are considered, remaining risk shall be explicitly documented.

The assessment should identify:

- Residual risk.
- Reason the risk remains.
- Existing controls.
- Additional proposed controls.
- Responsible risk owner.
- Risk acceptance authority.
- Conditions attached to acceptance.
- Review triggers.

Residual risk shall not be hidden within a general assurance conclusion.

---

## 16. Assessment Outcomes

The assessment may produce one of the following recommendations:

### Outcome 1 — Authorisation Recommended

Evidence and controls are sufficient for the proposed context.

### Outcome 2 — Conditional Authorisation Recommended

Operational use may proceed only under specified restrictions or conditions.

### Outcome 3 — Additional Assurance Required

Material evidence gaps remain and should be addressed before operational authorisation.

### Outcome 4 — Revalidation Required

Changes, evidence or findings require the capability to undergo additional validation before a decision is made.

### Outcome 5 — Authorisation Not Recommended

The capability does not currently demonstrate sufficient assurance or control for the proposed use.

### Outcome 6 — Suspension or Restriction Recommended

New evidence, incidents or changing conditions indicate that existing authority should be restricted or suspended.

---

## 17. Conditions and Restrictions

Where conditional authorisation is recommended, conditions should specify:

- Mission limitations.
- Environmental limitations.
- Autonomy limitations.
- Human supervision requirements.
- Configuration restrictions.
- Monitoring requirements.
- Duration.
- Required additional evidence.
- Specific prohibited uses.
- Escalation requirements.
- Suspension triggers.

Conditions should be measurable and auditable where practicable.

---

## 18. Assessment Independence

Assessment independence shall be proportionate to risk.

For higher-consequence capabilities, critical elements of assurance should be independently reviewed where practicable.

The organisation responsible for developing or operating the AI should not be the sole source of assurance for consequential authorisation decisions.

Independence may include:

- Independent technical evaluation.
- Independent TEVV.
- Operational review.
- Security review.
- Governance review.
- Authorising authority review.

---

## 19. Uncertainty and Limitations

The assessment shall explicitly identify uncertainty.

This includes:

- Unknown behaviour.
- Untested conditions.
- Data limitations.
- Model limitations.
- Environmental uncertainty.
- Human factors uncertainty.
- Security uncertainty.
- Dependency uncertainty.

AI outputs should communicate material uncertainty to human decision makers where that uncertainty could affect consequential decisions.

Confidence should not be represented as evidence of correctness.

---

## 20. Assessment Record

The assessment record should contain:

- Capability identifier.
- Mission and use case.
- Environment.
- Proposed autonomy.
- Human authority.
- Assessment criteria.
- Evidence references.
- Assessment ratings.
- Findings.
- Limitations.
- Residual risks.
- Conditions.
- Open actions.
- Assessor roles.
- Independent review where applicable.
- Assessment outcome.
- Date.
- Configuration baseline.
- Recommended authorisation state.

---

## 21. Decision Traceability

Each material assessment conclusion should be traceable to supporting evidence.

The assessment should allow an independent reviewer to answer:

1. What was being authorised?
2. For which mission?
3. Under what conditions?
4. At what autonomy level?
5. Under whose authority?
6. What evidence supports the decision?
7. What limitations remain?
8. What risks were accepted?
9. What controls are mandatory?
10. What would cause the authorisation to change?

---

## 22. Golden Thread Integration

The assessment connects evidence to operational authority through the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

The assessment should identify any break in this chain before authorisation is recommended.

---

## 23. Core Rule

**An operational authorisation assessment shall establish not merely that an AI system works, but that it is sufficiently understood, controlled and assured for the specific operational context in which authority is being requested.**

Technical capability is therefore necessary but not, by itself, sufficient for operational authorisation.

---

## 24. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `01_Authorisation_Requirements.md`
- `03 Risk & Autonomy`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
