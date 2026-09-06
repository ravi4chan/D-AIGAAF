# 01 Authorisation Requirements

## 1. Purpose

This document defines the minimum requirements that should be satisfied before a Defence AI capability receives operational authorisation.

The requirements establish a structured basis for determining whether a capability is sufficiently understood, assured, controlled and governed for its intended operational use.

Operational authorisation is contextual. Meeting these requirements does not create unrestricted approval for a capability across all missions, environments, autonomy levels or configurations.

---

## 2. Scope

These requirements apply to Defence AI capabilities proposed for operational employment, including:

- Command decision support
- Intelligence, surveillance and reconnaissance (ISR)
- Targeting support
- Autonomous or semi-autonomous functions
- Logistics and sustainment
- Other AI-enabled systems with operational consequences

They apply across the AI lifecycle and should be adapted according to mission criticality, consequence, autonomy, environment and human-control requirements.

---

## 3. Core Authorisation Requirement

An AI capability shall not be operationally authorised unless there is sufficient evidence that:

1. Its intended purpose and authorised use are clearly defined.
2. Its operational risks have been identified and assessed.
3. Its applicable autonomy level is explicitly defined.
4. Human decision rights and intervention authority are established.
5. Its operating environment and boundaries are understood.
6. Required technical, security and safety controls are implemented.
7. Appropriate TEVV has been completed.
8. Known limitations and failure modes are documented.
9. Fail-safe and degraded-operation behaviour is defined and demonstrated.
10. Dependencies and critical supply-chain risks are understood.
11. Monitoring and incident-management arrangements are established.
12. Evidence is sufficient to support the proposed authorisation decision.
13. The authorised configuration is identifiable and controlled.
14. Conditions, restrictions and suspension triggers are documented.
15. The responsible and accountable authorities are identified.

---

## 4. Authorisation Object

Authorisation requirements shall be assessed against the complete operational context:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

A capability should therefore not be considered authorised merely because the underlying model or system has passed technical testing.

The authorisation decision applies to the defined combination of capability, mission, environment, autonomy and human authority.

---

## 5. Capability Requirements

The capability shall have:

- A clearly defined operational purpose.
- Identifiable system and model components.
- A documented functional scope.
- Defined intended outputs and actions.
- Known limitations and assumptions.
- An identifiable configuration baseline.
- Defined interfaces and dependencies.
- Appropriate performance measures.
- A documented change history.

Where relevant, the capability should distinguish between information generation, recommendation, decision support and action execution.

---

## 6. Mission Requirements

The proposed use shall identify:

- Mission or operational objective.
- Specific use case.
- Intended users.
- Decisions or actions supported by the AI.
- Consequences of incorrect, delayed or unavailable outputs.
- Mission-critical functions.
- Prohibited or out-of-scope uses.
- Conditions under which the capability may or may not be employed.

Mission scope shall be sufficiently precise to prevent an authorised capability from being interpreted as having broader authority than intended.

---

## 7. Risk Requirements

A documented risk assessment shall consider, as applicable:

- Consequence of failure.
- Mission criticality.
- Autonomy level.
- Human-control capability.
- Environmental uncertainty.
- Adversarial conditions.
- Data and information risks.
- Cyber and AI security risks.
- Supply-chain dependencies.
- Failure propagation.
- Potential impact on personnel, civilians, infrastructure and other assets.

Higher-consequence and higher-autonomy uses shall require proportionately stronger evidence, controls and authority.

---

## 8. Autonomy Requirements

The proposed autonomy level shall be explicitly identified.

The authorisation package shall define:

- What the AI may observe.
- What it may analyse.
- What it may recommend.
- What it may execute.
- What requires human confirmation.
- What actions are prohibited.
- Conditions for transition between autonomy states.
- Conditions requiring reduction, suspension or termination of autonomy.

No increase in autonomy shall be inferred from technical capability alone.

A capability that is authorised for advisory use shall not automatically be authorised for autonomous action.

---

## 9. Human Authority Requirements

Authorisation shall identify:

- Responsible human authority.
- Decision rights.
- Human supervisory role.
- Intervention and override mechanisms.
- Required competence and AI literacy.
- Escalation arrangements.
- Accountability for consequential decisions.
- Requirements for recording material human decisions.

Where an AI recommendation is rejected or bypassed, the framework should support recording the relevant decision rationale where operationally appropriate.

---

## 10. Operational Environment Requirements

The authorisation shall define the applicable operating envelope, including relevant:

- Physical conditions.
- Terrain and environmental variability.
- Sensor conditions.
- Communications availability.
- Navigation conditions.
- Information environment.
- Electromagnetic conditions.
- Computing and power dependencies.
- Human operating conditions.
- Adversarial conditions.

The capability shall not be authorised for conditions that have not been sufficiently assessed unless the authorisation explicitly identifies the limitation and establishes appropriate controls.

---

## 11. Evidence and TEVV Requirements

Authorisation shall be supported by proportionate evidence from relevant TEVV activities.

Evidence should address, as applicable:

1. Technical performance
2. Reliability and robustness
3. Adversarial resilience
4. Operational environment
5. Human-AI interaction
6. Security and integrity
7. Autonomy and control
8. Mission effectiveness

Evidence shall be traceable to requirements and shall identify:

- What was tested.
- Under what conditions.
- With which configuration.
- What was observed.
- What limitations remain.
- Whether findings affect authorisation.

Untested or insufficiently demonstrated behaviour shall not be represented as demonstrated assurance.

---

## 12. Security Requirements

Before authorisation, applicable AI security risks and controls shall be assessed, including:

- Model and software integrity.
- Data integrity.
- Adversarial manipulation.
- Unauthorised access.
- Supply-chain compromise.
- Configuration tampering.
- Interface and dependency risks.
- Monitoring and response capability.

Critical security findings shall be resolved, accepted by the appropriate authority, or reflected as explicit authorisation restrictions.

---

## 13. Data and Information Requirements

Where AI performance depends materially on data or information, the authorisation package shall address:

- Data provenance.
- Data quality and integrity.
- Representativeness.
- Known gaps and biases.
- Data drift.
- Information timeliness.
- Source reliability.
- Handling and access requirements.
- Relevant data dependencies.

Material uncertainty in the information supporting an AI output should be capable of being communicated to the human decision maker.

---

## 14. Fail-Safe and Degraded Operation Requirements

The capability shall have defined behaviour for foreseeable:

- System failures.
- Sensor failures.
- Data failures.
- Communication loss.
- Navigation degradation.
- Computing or power constraints.
- Model anomalies.
- Security incidents.
- Loss of human supervision.

Fail-safe behaviour shall be proportionate to consequence and autonomy.

Emergency protective actions may be pre-authorised where necessary, but such provisions shall not create unrestricted AI authority.

---

## 15. Dependency and Supply-Chain Requirements

Critical dependencies shall be identified and assessed, including:

- Model provenance.
- Software components.
- Hardware dependencies.
- Data dependencies.
- External services.
- Update mechanisms.
- Suppliers capable of materially affecting system behaviour.

Material uncertainty regarding a critical dependency shall be reflected in the risk assessment and, where necessary, in authorisation conditions.

---

## 16. Monitoring Requirements

An operational monitoring plan shall define:

- Performance indicators.
- Risk indicators.
- Environment indicators.
- Security indicators.
- Autonomy indicators.
- Human-control indicators.
- Thresholds and escalation criteria.
- Required records.
- Actions following significant deviations.

Monitoring shall support continuous assurance rather than treating authorisation as a one-time approval.

---

## 17. Authorisation Conditions

The authorisation may impose conditions such as:

- Restricted missions.
- Restricted environments.
- Reduced autonomy.
- Additional human supervision.
- Configuration restrictions.
- Additional monitoring.
- Time-limited employment.
- Specific training requirements.
- Additional TEVV.
- Prohibited functions or actions.

Conditions shall be explicit and traceable.

---

## 18. Preconditions and Entry Criteria

Before operational entry, the responsible authority shall confirm, as applicable:

- Approved use case.
- Approved configuration.
- Required evidence available.
- Required personnel available and competent.
- Human authority established.
- Operating environment within authorised boundaries.
- Required security controls active.
- Fail-safe mechanisms available.
- Monitoring active.
- Dependencies within accepted conditions.
- Outstanding risks formally addressed.

Failure to satisfy a mandatory entry criterion should prevent operational entry unless an authorised exception process exists.

---

## 19. Review, Suspension and Revocation Requirements

Authorisation requirements shall define triggers for review, including:

- Material system change.
- Model or hidden-layer change affecting behaviour.
- Significant data change.
- Change in mission.
- Change in operating environment.
- Change in autonomy.
- Change in human-control arrangements.
- Significant security event.
- Material incident.
- New threat information.
- Evidence that invalidates an important assumption.

Depending on severity, the outcome may be continued authorisation, additional controls, revalidation, reauthorisation, restriction, suspension or revocation.

---

## 20. Traceability to the Golden Thread

Every material authorisation requirement should be traceable through the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

This traceability should allow an authorising authority to understand why a capability is considered suitable for its authorised use.

---

## 21. Minimum Authorisation Evidence Set

The authorisation package should normally contain, as applicable:

- Mission and use-case definition.
- Operational context and boundaries.
- Risk and autonomy assessment.
- Human authority assessment.
- AI lifecycle records.
- Data and information assurance.
- AI security assessment.
- Supply-chain and dependency assessment.
- TEVV evidence.
- Operational environment assessment.
- Known limitations and failure modes.
- Fail-safe and degraded-operation evidence.
- Monitoring plan.
- Incident and escalation arrangements.
- Configuration baseline.
- Proposed authorisation conditions.
- Residual-risk statement.
- Authorisation recommendation.

The required depth of evidence shall be proportionate to risk and consequence.

---

## 22. Core Rule

**No operational authorisation without sufficient evidence, defined authority, controlled boundaries and a credible means of detecting, limiting and responding to unacceptable behaviour.**

Operational authorisation is therefore a governed decision, not a technical certification alone.

---

## 23. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `03 Risk & Autonomy`
- `04 AI Lifecycle`
- `05 Data & Information`
- `06 AI Security`
- `07 Supply Chain & Sovereignty`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
