# 02-Defence AI Policy and Governance Requirements

## Purpose

This document establishes a structured D-AIGAAF method for translating defence AI policy, responsible-AI principles, strategic direction, departmental instructions, service-level requirements, and organisational governance decisions into operationally meaningful requirements.

The objective is to prevent defence AI policy from remaining at the level of broad principles. Policy must be translated into accountable decisions, lifecycle controls, technical requirements, evidence, assurance activities, operational boundaries, and review mechanisms.

## Core Principle

**Defence AI policy becomes effective governance only when its principles can be traced to specific requirements, responsible authorities, controls, evidence, and operational decisions.**

Policy intent alone does not demonstrate implementation.

## Policy-to-Governance Chain

**Strategic Intent → Policy Principle → Governance Requirement → Control → Implementation → Evidence → Assurance → Operational Condition → Authorisation → Monitoring → Review**

---

## 1. Scope

This document applies to defence AI policy requirements affecting:

- Strategy
- Governance
- Mission selection
- Use-case approval
- Risk
- Autonomy
- Human authority
- Data
- Security
- Supply chain
- TEVV
- Operational environment
- Operational authorisation
- Employment
- Monitoring
- Incidents
- Change
- Audit
- Workforce
- Acquisition
- Interoperability
- Technical architecture
- Documentation
- Retirement

---

## 2. Sources of Defence AI Policy

Potential sources include:

- National AI strategies
- National-security policy
- Defence AI strategies
- Responsible AI principles
- Ministry / department policy
- Service-level directives
- Acquisition policy
- Cybersecurity policy
- Data policy
- Safety policy
- Information-security policy
- Operational doctrine
- Command directives
- Coalition policy
- Organisational governance decisions

The authority and applicability of each source should be explicitly established.

---

## 3. Policy Classification

Policy statements should be classified according to their governance function.

### 3.1 Strategic Direction

Defines desired outcomes, priorities, capability objectives, or strategic constraints.

### 3.2 Mandatory Governance Requirement

Creates an organisational obligation that must be implemented.

### 3.3 Responsible AI Principle

Establishes a normative expectation requiring translation into specific controls.

### 3.4 Operational Constraint

Restricts where, when, why, or how AI may be employed.

### 3.5 Assurance Requirement

Defines evidence, testing, review, independence, or confidence expectations.

### 3.6 Procedural Requirement

Defines required governance processes or decision steps.

### 3.7 Guidance

Supports interpretation or implementation but does not independently create mandatory authority.

---

## 4. Policy Translation Method

For each material policy statement:

### Step 1 — Identify the Source

Record:

- Policy title
- Issuing authority
- Version
- Effective date
- Applicability
- Status

### Step 2 — Extract the Policy Intent

Determine:

- What outcome is intended?
- What risk is being controlled?
- Who is expected to act?
- What decision is affected?

### Step 3 — Translate into Governance Requirements

Requirements should be:

- Specific
- Assignable
- Testable where appropriate
- Evidence-producing
- Mission-relevant
- Traceable

### Step 4 — Define Controls

Controls may be:

- Organisational
- Procedural
- Technical
- Human
- Contractual
- Operational
- Assurance-based

### Step 5 — Define Evidence

Identify evidence demonstrating that the requirement is implemented.

### Step 6 — Establish Review Triggers

Determine when the interpretation or implementation must be reassessed.

---

## 5. Policy Requirement Register

| Policy ID | Source | Principle / Requirement | Applicability | D-AIGAAF Requirement | Control | Owner | Evidence | Review Trigger |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |

---

## 6. Responsible AI Principles

Defence organisations may adopt responsible AI principles expressed using terms such as:

- Responsibility
- Accountability
- Equitability
- Traceability
- Reliability
- Governability
- Safety
- Security
- Transparency
- Explainability
- Human oversight
- Contestability
- Privacy
- Robustness

D-AIGAAF should not assume that the existence of such principles proves implementation.

Each principle should be translated into operational requirements.

Example:

**Governability → Defined human authority → Intervention mechanism → Tested override → Evidence → Operational condition**

Another example:

**Traceability → Configuration identification → Decision logging → Evidence integrity → Auditability**

---

## 7. Accountability Requirements

Defence AI policy should establish identifiable human and organisational accountability.

At minimum, determine:

- Capability owner
- Mission owner
- Risk owner
- Technical authority
- Data authority
- Security authority
- TEVV authority
- Assurance authority
- Operational authorisation authority
- Operational commander / decision authority

Accountability should not be assigned to an AI system.

---

## 8. Human Authority Requirements

Policy should define where human authority must remain explicit.

Assess:

- Decisions AI may support
- Decisions AI may recommend
- Decisions requiring human approval
- Actions AI may execute
- Actions AI must not execute
- Required intervention capability
- Required override capability
- Escalation conditions

Human presence alone should not be treated as meaningful human control.

---

## 9. Autonomy Requirements

Defence AI policy should address:

- Permitted autonomy
- Prohibited autonomy
- Conditions for increased autonomy
- Human supervision
- Transition between autonomy levels
- Fail-safe behaviour
- Loss-of-control conditions
- Reauthorisation requirements

A system should not gain operational authority merely because its technical capability allows greater autonomy.

---

## 10. Mission and Use-Case Requirements

Policy should require AI capabilities to be linked to defined mission needs.

Governance should establish:

- Mission purpose
- Intended decision or action
- Expected benefit
- Consequence of error
- Operational constraints
- Prohibited uses
- Success criteria
- Exit criteria

This prevents technology-first governance.

---

## 11. Risk Requirements

Defence AI policy should support consequence-based risk governance.

Risk assessment should consider:

- Mission consequence
- Safety
- Security
- Human control
- Autonomy
- Data
- Operational environment
- Adversarial exposure
- Supply chain
- Strategic dependency
- Legal and policy constraints

Risk should be reassessed after material changes.

---

## 12. Data Requirements

Policy requirements may address:

- Data provenance
- Quality
- Integrity
- Representativeness
- Bias
- Classification
- Access
- Retention
- Sharing
- Sovereignty
- Drift
- Operational relevance

Data governance should cover both training data and operational data.

---

## 13. Security Requirements

Defence AI policy should recognise that AI security extends beyond conventional cybersecurity.

Security governance may include:

- Model integrity
- Data poisoning
- Adversarial inputs
- Prompt injection
- Instruction manipulation
- Retrieval security
- Tool access
- Agent security
- Supply-chain compromise
- Privilege escalation
- AI-to-AI interaction
- Model theft
- Operational deception

---

## 14. Supply Chain and Sovereignty Requirements

Policy should establish requirements for:

- Supplier provenance
- Component provenance
- Third-party models
- Cloud dependency
- Foreign dependency
- Update authority
- Supplier access
- Continuity
- Substitution
- Exit
- Strategic dependency

Supplier assurance does not transfer operational accountability.

---

## 15. TEVV Requirements

Policy should define when testing, evaluation, verification and validation are required.

TEVV should address, as applicable:

- Performance
- Reliability
- Robustness
- Security
- Human-AI interaction
- Autonomy
- Operational environment
- Mission effectiveness
- Failure behaviour
- Degraded operation

Benchmark performance alone should not be treated as operational assurance.

---

## 16. Operational Authorisation Requirements

Policy should define:

- Who may authorise
- What is being authorised
- Evidence required
- Conditions
- Boundaries
- Duration
- Review requirements
- Suspension authority
- Withdrawal authority
- Reauthorisation triggers

The D-AIGAAF authorisation object is:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

---

## 17. Operational Employment Requirements

Policy should govern:

- Pre-employment checks
- Mission configuration
- Human control
- Situational awareness
- Uncertainty
- Boundary monitoring
- Degraded operation
- Intervention
- Override
- Activity recording
- Incident escalation
- Mission closeout

---

## 18. Continuous Assurance Requirements

Policy should require continuing confidence rather than one-time approval.

Continuous assurance may include:

- Performance monitoring
- Security monitoring
- Human-control monitoring
- Autonomy monitoring
- Environment monitoring
- Supplier monitoring
- Evidence currency
- Independent challenge
- Corrective action
- Revalidation

---

## 19. Incident and Fail-Safe Requirements

Policy should define expectations for:

**Detect → Classify → Protect → Fail-Safe → Investigate → Correct → Recover → Reassess → Reauthorise → Learn**

Fail-safe behaviour must be mission-specific.

A safe state does not necessarily mean shutdown.

---

## 20. Change and Reauthorisation Requirements

Policy should recognise that material change can occur without code changes.

Relevant changes include:

- Mission
- Environment
- Data
- Model
- Configuration
- Prompt / instruction
- Tool
- Supplier
- Security
- Autonomy
- Human authority
- Policy
- Law

Material changes should trigger proportionate reassessment.

---

## 21. Acquisition Requirements

Defence AI policy should be translated into procurement requirements covering:

- Supplier disclosure
- Provenance
- Security
- Data rights
- Audit rights
- TEVV access
- Evidence
- Update notification
- Configuration control
- Incident reporting
- Exit
- Continuity
- Sovereignty

Acceptance of a procured system does not constitute operational authorisation.

---

## 22. Interoperability and Coalition Requirements

Policy should address:

- Trust boundaries
- Information sharing
- National caveats
- Coalition authority
- AI-to-AI interaction
- Cross-domain interfaces
- Shared data
- Shared evidence
- Security
- Accountability

Information may cross an interface without operational authority crossing it.

---

## 23. Workforce Requirements

Policy should establish competence requirements for personnel who:

- Govern
- Develop
- Acquire
- Test
- Assure
- Authorise
- Operate
- Monitor
- Audit
- Investigate

Critical governance roles should have sufficient competence, capacity, authority and independence.

---

## 24. Documentation and Evidence Requirements

Policy should identify records necessary to reconstruct:

- Mission
- Requirements
- Risk
- Configuration
- Data
- TEVV
- Assurance
- Human authority
- Authorisation
- Employment
- Incidents
- Changes
- Retirement

Documentation alone is not assurance, but assurance without traceable evidence is weak.

---

## 25. Retirement Requirements

Policy should govern:

- Withdrawal
- Suspension
- Retirement
- Authority revocation
- Data disposition
- Model disposition
- Credential revocation
- Supplier exit
- Infrastructure disposal
- Evidence preservation
- Residual risk
- Closure

A retired capability should not retain hidden operational authority.

---

## 26. Policy Exceptions and Waivers

Where policy permits exceptions, record:

- Requirement
- Reason
- Scope
- Duration
- Risk
- Compensating control
- Approval authority
- Review date
- Expiry

A waiver should not be interpreted as removal of the underlying risk.

No governance process should assume that a policy authority can waive a binding legal obligation unless lawful authority exists.

---

## 27. Policy Conflict

Potential conflicts may occur between:

- National policy and coalition practice
- Security and transparency
- Operational urgency and assurance
- Procurement policy and mission need
- Data-sharing policy and sovereignty
- Different organisational directives

Conflicts should be escalated rather than silently resolved by implementers.

Record:

- Conflicting requirements
- Authority of each
- Operational impact
- Interpretation
- Decision
- Conditions
- Review trigger

---

## 28. Policy Change

Policy changes should trigger assessment of affected:

- AI capabilities
- Authorisations
- Missions
- Controls
- Contracts
- Technical architecture
- TEVV
- Training
- Operational procedures

Policy change may require revalidation or reauthorisation even when the AI system itself has not changed.

---

## 29. Policy Assurance

Policy assurance should test whether:

- Requirements are understood
- Responsibilities are assigned
- Controls exist
- Controls operate
- Evidence is available
- Exceptions are controlled
- Operational practice matches policy
- Material changes are detected
- Findings are corrected

A signed policy acknowledgement is not evidence that operational controls are effective.

---

## 30. Governance Review

Periodic review should examine:

- Policy currency
- New defence AI developments
- New threats
- New operational uses
- Incidents
- Assurance findings
- Audit findings
- Supplier changes
- Legal developments
- Coalition developments
- Workforce capability
- Lessons learned

---

## 31. Minimum Defence AI Policy Requirements

For consequential AI capabilities, policy should establish or require:

1. Defined accountability.
2. Mission-based use-case governance.
3. Consequence-based risk assessment.
4. Explicit autonomy classification.
5. Meaningful human authority.
6. Data governance.
7. AI-specific security.
8. Supply-chain governance.
9. TEVV.
10. Operational-environment assessment.
11. Explicit operational authorisation.
12. Operational monitoring.
13. Incident and fail-safe mechanisms.
14. Change and reauthorisation.
15. Evidence and auditability.
16. Workforce competence.
17. Acquisition controls.
18. Interoperability controls.
19. Technical enforcement where required.
20. Controlled retirement.

---

## 32. Policy Implementation Test

For each material defence AI policy principle, ask:

> **What must actually change in governance, engineering, acquisition, testing, human authority, operational employment, monitoring, or evidence for this principle to be demonstrably implemented?**

If no concrete answer exists, the principle has not yet been operationalised.

---

## 33. Anti-Patterns

Avoid:

1. Publishing responsible-AI principles without implementation requirements.
2. Treating policy acknowledgement as compliance.
3. Creating policy without assigning decision rights.
4. Using generic ethical language without controls.
5. Assuming human presence equals human control.
6. Treating TEVV as a one-time technical test.
7. Treating procurement acceptance as operational approval.
8. Allowing autonomy to expand through configuration.
9. Treating supplier assurance as transferred accountability.
10. Measuring implementation only by number of completed forms.
11. Ignoring policy changes after deployment.
12. Allowing policy exceptions to become permanent informal practice.

---

## D-AIGAAF Integration

Defence AI policy should feed the Golden Thread:

**Strategic Intent → Policy Principle → Requirement → Risk → Control → Testing → Evidence → Assurance → Human Authority → Operational Conditions → Authorisation → Employment → Monitoring → Change / Incident → Learning → Revalidation / Reauthorisation → Retirement**

The Legal & Policy module should therefore connect strategic and normative direction to the operational governance mechanisms contained throughout D-AIGAAF.

---

## Final Principle

**A defence AI policy is operationally meaningful only when the organisation can demonstrate how its principles alter requirements, controls, evidence, authority, operational boundaries, and decisions across the AI lifecycle.**
