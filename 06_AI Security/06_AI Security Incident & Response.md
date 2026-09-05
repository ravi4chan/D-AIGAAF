# D-AIGAAF — AI Security Incident & Response

## 1. Purpose

This document establishes a framework for identifying, reporting, assessing, containing, recovering from, and learning from security incidents involving Defence AI systems.

The objective is to minimise harm, preserve human authority, protect evidence, restore trustworthy operation, and ensure that lessons from incidents improve future assurance.

## 2. Scope

AI security incidents include events that may:

- Compromise model integrity
- Manipulate data or inputs
- Cause unauthorised system behaviour
- Bypass access controls
- Expose protected information
- Degrade availability
- Compromise software or dependencies
- Produce security-relevant unexpected behaviour
- Undermine human authority or control
- Indicate compromise of the authorised operational baseline

An incident may originate internally, externally, accidentally, or through an unknown cause.

## 3. Incident Classification

Incidents should be classified according to potential or actual impact.

| Level | Description |
|---|---|
| I1 | Minor security event with limited operational significance |
| I2 | Confirmed security incident requiring controlled response |
| I3 | Significant incident affecting an operational AI capability |
| I4 | Critical incident with potential for severe mission, security, or safety consequences |
| I5 | Severe incident involving potentially uncontrolled or highly consequential AI behaviour |

The classification should be based on consequence and operational effect rather than technical severity alone.

## 4. Detection and Reporting

AI systems should provide mechanisms for identifying and reporting security-relevant events.

Potential detection sources include:

- Automated monitoring
- Security alerts
- Operators
- AI developers
- AI system managers
- Operational AI Advisors
- Command authorities
- Independent assurance teams
- Supply-chain or vendor notifications

Personnel should be encouraged to report anomalous behaviour without waiting for certainty about its cause.

## 5. Initial Response

The initial response should establish:

1. What happened?
2. Which capability is affected?
3. Is the event ongoing?
4. What functions may be compromised?
5. Could people, property, information, or mission outcomes be harmed?
6. Is the authorised operational envelope being exceeded?
7. What immediate protective action is required?

Initial actions should prioritise prevention of further harm and preservation of evidence.

## 6. Graduated Response

The response should normally follow a graduated sequence:

**Detect → Record → Assess → Contain → Restrict/Suspend → Investigate → Recover → Revalidate → Reauthorise**

Not every incident requires every stage, but consequential incidents should not return directly to unrestricted operation without appropriate assessment.

## 7. Immediate Protective Action

Where an AI capability presents an immediate risk of unacceptable harm, pre-authorised emergency procedures should permit rapid protective intervention.

Depending on the system, this may include:

- Restricting functions
- Moving to a safe degraded mode
- Disconnecting affected interfaces
- Transferring control to an authorised human
- Suspending the capability
- Controlled shutdown

Emergency protective action should not depend on completing the full investigation first.

## 8. Human Authority

Consequential AI security incidents require clear human decision rights.

The response structure should identify:

- Person responsible for immediate operational control
- AI system manager
- Operational AI Advisor, where assigned
- Technical/security authority
- Relevant command authority
- Authority responsible for suspension or reauthorisation

The framework should avoid ambiguity about who can restrict, suspend, or restore an AI capability.

## 9. Operational AI Advisor

For consequential incidents, an Operational AI Advisor may provide the command authority with an assessment of:

- AI behaviour
- Likely technical causes
- Confidence and uncertainty
- Operational implications
- Possible containment options
- Whether the behaviour is consistent with the authorised baseline
- Whether further employment should be permitted

The advisor informs command judgement but does not replace the competent operational authority.

## 10. Evidence Preservation

Incident response should preserve evidence necessary to understand and reconstruct the event.

Evidence may include:

- System logs
- User actions
- Model version
- Configuration state
- Relevant inputs and outputs
- Data provenance
- Software and dependency versions
- Security alerts
- Timeline of events
- Human decisions
- Automated actions
- Communications relevant to the incident

Evidence handling should follow applicable security, legal, privacy, and records-management requirements.

## 11. Investigation

Investigation should determine, where practicable:

- What happened
- When it happened
- How it happened
- Which components were involved
- Whether the event was accidental or adversarial
- Whether the authorised baseline was altered
- Whether the AI behaved outside its expected envelope
- Whether human or procedural controls failed
- Whether other systems may be affected
- Whether continued operation is safe and justified

The investigation should distinguish confirmed facts from hypotheses.

## 12. Containment

Containment should prevent the incident from spreading or causing additional consequences.

Possible measures include:

- Restricting affected functions
- Isolating components
- Revoking access
- Reverting to a verified baseline
- Disabling affected interfaces
- Switching to an approved degraded mode
- Suspending operational employment

Containment measures should themselves be risk assessed where time permits.

## 13. Recovery

Recovery should restore the capability only after sufficient confidence has been established.

Recovery may require:

- Removal of compromised components
- Restoration from a trusted baseline
- Credential or access changes
- Software remediation
- Model verification
- Data integrity checks
- Security testing
- Operational validation
- Review of residual risk

Recovery is not equivalent to reauthorisation.

## 14. Revalidation and Reauthorisation

A security incident may invalidate previous assurance.

Revalidation should determine whether:

- The original security assumptions remain valid
- Controls remain effective
- The system remains within its authorised envelope
- The incident exposed previously unknown failure modes
- Additional controls are required

Where the incident materially affects capability, risk, autonomy, or operational conditions, reauthorisation should be required before unrestricted employment.

## 15. Incident Severity and Escalation

Escalation should consider:

- Actual consequence
- Potential consequence
- Autonomy level
- Mission criticality
- Duration
- Scope
- Ability to contain
- Uncertainty about system behaviour
- Potential for recurrence
- Potential effect on other capabilities

When uncertainty is high and consequences are severe, the response should favour protective measures and human control.

## 16. External and Supply-Chain Incidents

Incidents involving suppliers, third-party software, models, datasets, or infrastructure should be assessed for wider exposure.

Actions may include:

- Identifying affected dependencies
- Suspending affected updates
- Verifying component integrity
- Assessing other deployed systems
- Engaging the relevant supplier
- Applying temporary restrictions
- Reassessing supply-chain risk

A supplier notification should not automatically be treated as proof that an operational system is safe or unsafe; independent assessment may be required.

## 17. Incident Records

Each significant incident should generate an incident record containing, where appropriate:

- Incident identifier
- Capability
- Date and time
- Detection source
- Description
- Classification
- Affected components
- Operational effect
- Immediate actions
- Decisions and authorities
- Evidence
- Root or contributing causes
- Corrective actions
- Residual risk
- Revalidation outcome
- Reauthorisation decision
- Lessons identified

The record should link to the Defence AI Assurance Record.

## 18. Lessons and Corrective Action

Post-incident review should examine both technical and organisational factors.

Corrective action may include:

- Technical remediation
- Security-control changes
- Data changes
- Model changes
- Training changes
- Procedural changes
- Mission restrictions
- Updated threat models
- Updated assurance requirements
- Changes to autonomy limits
- Changes to operational authorisation

Lessons should be incorporated into relevant D-AIGAAF controls and future assessments.

## 19. Incident Closure

An incident should only be closed when:

- Immediate risk has been controlled
- Required evidence has been preserved
- The cause or contributing factors are sufficiently understood
- Corrective actions are assigned
- Residual risk is assessed
- Required assurance activities are complete
- Required reauthorisation decisions are recorded

Closure should not erase unresolved uncertainty.

## 20. Core Principle

> **When an AI security incident occurs, preserving human control and preventing unacceptable harm takes priority over maintaining uninterrupted AI availability.**

Incident response should therefore connect security operations directly to assurance, operational authority, human control, risk management, and reauthorisation.
