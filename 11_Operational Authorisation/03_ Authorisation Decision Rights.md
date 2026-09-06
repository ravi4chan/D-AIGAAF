# 03 Authorisation Decision Rights

## 1. Purpose

This document defines the decision rights and accountability required to grant, condition, restrict, suspend, revoke or otherwise modify operational authorisation for Defence AI capabilities.

The objective is to ensure that operational authority is exercised by appropriately designated human authorities and is not implicitly transferred to developers, technical systems or AI outputs.

---

## 2. Core Principle

**AI may inform an authorisation decision, but AI shall not hold operational authorisation authority.**

Operational authorisation is a human governance decision based on evidence, risk, mission requirements, operational conditions and defined accountability.

Decision rights shall be explicit, documented and traceable.

---

## 3. Authorisation Decision Object

Decision rights shall apply to the complete authorisation context:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

A decision to authorise one combination shall not automatically authorise another.

Any material change to one or more elements shall be assessed for its effect on the existing authority.

---

## 4. Decision Rights Principles

Decision rights should follow these principles:

1. **Human accountability** — consequential authority remains with designated human authorities.
2. **Competence** — decisions should be made by personnel with appropriate operational, technical, legal and assurance understanding.
3. **Separation of functions** — development, assurance and authorisation should be appropriately separated.
4. **Proportionality** — higher-consequence or higher-autonomy uses require stronger and more senior authority.
5. **Traceability** — material decisions should be recorded.
6. **Clarity** — no ambiguity should exist regarding who may authorise, restrict or suspend employment.
7. **Reversibility** — authority should be capable of being restricted or withdrawn.
8. **Escalation** — unresolved or exceptional issues should move to the appropriate higher authority.
9. **Independence** — consequential decisions should not rely solely on the system developer's assessment.
10. **Continuity** — authority arrangements should remain effective during degraded or disconnected operations.

---

## 5. Separation of Roles

The following roles should be distinguished where practicable:

| Role | Primary Responsibility |
|---|---|
| Capability Owner | Overall accountability for the AI capability |
| Developer / System Provider | Design, development, technical documentation and defect remediation |
| System Manager | Configuration, deployment, maintenance and operational system management |
| Technical Authority | Technical judgement and system integrity |
| Assurance / TEVV Authority | Independent or appropriately separated evaluation and assurance |
| Security Authority | AI and system security assessment |
| Operational AI Advisor (OAIA) | Bridges operational requirements, AI behaviour, risk and assurance |
| Command / Operational Authority | Determines operational need and employment within authorised boundaries |
| Authorising Authority | Grants, conditions, restricts, suspends or revokes operational authority |
| Operator / User | Employs the capability within authorised conditions |
| Risk Owner | Owns and accepts specified residual risks within delegated authority |

One individual may hold multiple roles only where organisational policy permits and conflicts of interest are adequately controlled.

---

## 6. Authorising Authority

The authorising authority shall have explicit organisational authority to:

- Grant operational authorisation.
- Impose conditions and restrictions.
- Define the scope of authorised employment.
- Approve specified autonomy levels.
- Require additional assurance.
- Restrict or suspend employment.
- Revoke operational authority.
- Require revalidation or reauthorisation.
- Accept residual risk within delegated limits.

The authority should be appropriate to the consequence, mission criticality, autonomy and operational scope of the proposed use.

---

## 7. Capability Owner Decision Rights

The capability owner should be responsible for ensuring that:

- The capability has a defined purpose.
- Lifecycle governance is established.
- Required assessments are completed.
- Known limitations are documented.
- Configuration is controlled.
- Changes are reported.
- Incidents are escalated.
- Evidence remains current.
- Conditions of authorisation are understood and supported.

The capability owner should not unilaterally expand the authorised mission, environment or autonomy.

---

## 8. Developer and System Provider Responsibilities

Developers and system providers should:

- Provide accurate technical information.
- Identify known limitations.
- Support testing and evaluation.
- Disclose material changes.
- Support incident investigation.
- Maintain appropriate technical records.
- Identify critical dependencies.
- Provide relevant security and supply-chain information.

Technical assurance provided by a developer shall not, by itself, constitute operational authorisation.

---

## 9. Technical Authority

The technical authority should determine whether the system is technically suitable for the proposed use within its defined scope.

This may include:

- Architecture assessment.
- Configuration integrity.
- Performance assessment.
- Reliability.
- Interoperability.
- Technical limitations.
- Failure behaviour.
- Dependency analysis.

Technical suitability should be clearly distinguished from operational authorisation.

---

## 10. Assurance and TEVV Authority

The assurance function should:

- Assess evidence against requirements.
- Identify evidence gaps.
- Evaluate test limitations.
- Review material findings.
- Assess whether conclusions are supported by evidence.
- Identify residual uncertainty.
- Provide an assurance recommendation.

For higher-consequence capabilities, independent assurance should be used where practicable.

---

## 11. Security Authority

The security authority should assess relevant:

- AI security risks.
- Cybersecurity risks.
- Model and software integrity.
- Data integrity.
- Supply-chain risks.
- Adversarial threats.
- Access and configuration controls.
- Security monitoring and incident response.

Material security findings should be communicated to the authorising authority before the decision.

---

## 12. Operational AI Advisor

The **Operational AI Advisor (OAIA)** provides a bridge between operational command, AI capabilities and technical/assurance functions.

The OAIA should:

- Translate operational requirements into AI-relevant considerations.
- Explain AI limitations and uncertainty to operational decision makers.
- Assess implications of proposed AI use.
- Support interpretation of assurance evidence.
- Identify potential mismatches between AI capability and operational context.
- Advise on autonomy and human-control implications.
- Support incident and change assessment.
- Help determine when additional technical or assurance expertise is required.

The OAIA is advisory unless separately designated with formal decision authority.

The OAIA should not replace the commander, authorising authority, technical authority or assurance function.

---

## 13. Command and Operational Authority

Operational command should determine:

- Whether the capability is needed for the mission.
- Whether the proposed use is operationally appropriate.
- Whether personnel are prepared to employ it.
- Whether operational conditions remain within authorised boundaries.
- Whether AI recommendations should be accepted, rejected or escalated within the authorised decision framework.

Command authority does not automatically permit expansion of the authorised autonomy or mission scope.

---

## 14. Operator Decision Rights

Operators may:

- Use the capability within authorised conditions.
- Exercise authorised intervention and override.
- Report anomalies.
- Escalate uncertainty.
- Stop or transition the system where authorised.
- Record material incidents and decisions.

Operators shall not be expected to compensate indefinitely for known system deficiencies through informal workarounds.

---

## 15. Risk Owner

The risk owner should:

- Own identified residual risk.
- Ensure appropriate treatment is implemented.
- Confirm whether risk remains within delegated tolerance.
- Escalate risks exceeding delegated authority.
- Participate in reassessment following material change or incident.

Risk acceptance shall not be implied merely because an operational need exists.

---

## 16. Decision Rights by Authorisation State

| Authorisation State | Primary Decision |
|---|---|
| Proposed | Determine whether assessment should commence |
| Under Assurance | Determine whether evidence and assessment are sufficient to proceed |
| Conditionally Authorised | Approve defined restricted employment |
| Operationally Authorised | Approve employment within defined boundaries |
| Restricted | Define or maintain reduced scope of authority |
| Suspended | Remove or pause operational employment authority |
| Revoked | Withdraw operational authority |
| Retired | End lifecycle authority and transition to retirement/decommissioning |

The exact authorities should be defined by the adopting organisation.

---

## 17. Emergency Protective Authority

Organisations may establish pre-authorised emergency procedures for situations where delay could create unacceptable harm.

Such procedures should:

- Define who may act.
- Define the circumstances in which emergency authority applies.
- Specify the permitted protective action.
- Minimise unintended consequences.
- Require subsequent notification and recording.
- Trigger review where appropriate.

Emergency authority shall not be interpreted as unrestricted authority for AI systems to act independently.

---

## 18. Decision Escalation

Issues should be escalated when:

- Evidence is insufficient.
- Residual risk exceeds delegated authority.
- Mission scope is unclear.
- Proposed autonomy exceeds existing authority.
- Environmental conditions exceed the authorised envelope.
- Human control is degraded.
- A material security concern emerges.
- A significant incident occurs.
- A critical dependency becomes unavailable or untrusted.
- A material change is proposed.

Escalation shall continue until an appropriately authorised decision is reached.

---

## 19. Conflicts of Interest

Where a decision maker has responsibility for both capability delivery and authorisation, the organisation should apply additional safeguards.

Possible safeguards include:

- Independent assurance.
- Separate review authority.
- Additional senior approval.
- Documented conflict assessment.
- Independent legal or security review.

The objective is to prevent delivery pressure from becoming an implicit basis for operational approval.

---

## 20. Decision Traceability

Material authorisation decisions should record:

- Decision maker.
- Decision date.
- Capability and configuration.
- Mission and use case.
- Environment.
- Autonomy level.
- Human authority.
- Evidence considered.
- Key findings.
- Residual risks.
- Conditions and restrictions.
- Rationale.
- Review date.
- Suspension or revocation triggers.

The record should support later reconstruction of why the authority was granted or changed.

---

## 21. Rejection and Bypass of AI Recommendations

Where an AI system provides consequential recommendations, the governance framework should preserve appropriate human decision authority.

A commander or authorised decision maker may reject or bypass an AI recommendation within their lawful authority.

Where operationally appropriate, the system should support recording:

- The AI recommendation.
- Relevant uncertainty or confidence information.
- The human decision.
- Reason for rejection or bypass.
- Material consequences or follow-up actions.

This is intended to strengthen accountability and learning, not to discourage justified human judgement.

---

## 22. Delegation

Decision rights may be delegated only when:

- Delegation is formally authorised.
- The delegated authority is competent.
- Scope is explicit.
- Limits are documented.
- Escalation mechanisms exist.
- Accountability remains identifiable.

Delegation shall not obscure the ultimate accountable authority.

---

## 23. Decision Rights During Degraded or Disconnected Operations

Decision rights shall remain defined when communications or supporting infrastructure are degraded or unavailable.

Where applicable, the framework should establish:

- Pre-authorised actions.
- Local decision authority.
- Autonomy limits.
- Fail-safe behaviour.
- Escalation alternatives.
- Reconnection and reporting requirements.

Loss of communication shall not silently create broader AI authority.

---

## 24. Decision Rights During Incidents

During an AI-related incident, defined authorities should determine:

- Whether employment continues.
- Whether autonomy should be reduced.
- Whether the capability should be suspended.
- Whether protective action is required.
- Whether escalation is mandatory.
- Whether revalidation or reauthorisation is required.

Incident response authority should be established before deployment wherever practicable.

---

## 25. Golden Thread

Decision rights connect operational authority to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

At each stage, the responsible decision authority should be identifiable.

---

## 26. Core Rule

**No consequential AI capability should operate on implied authority. Every material operational decision should have a clearly identifiable human authority, defined decision rights and an auditable basis for the decision.**

---

## 27. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `01_Authorisation_Requirements.md`
- `02_Authorisation_Assessment.md`
- `03 Risk & Autonomy`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
