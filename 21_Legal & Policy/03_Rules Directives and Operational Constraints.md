# 03-Rules Directives and Operational Constraints

## Purpose

This document establishes the D-AIGAAF approach for identifying, translating, implementing, enforcing, monitoring, and reviewing rules, directives, orders, mission conditions, and operational constraints that govern the employment of defence AI capabilities.

The objective is to ensure that operational authority is bounded not merely by what an AI system can technically do, but by what it is explicitly permitted to do for a defined mission, environment, configuration, autonomy level, and human-authority structure.

## Core Principle

**Operational capability does not create operational authority. Rules, directives, and constraints must remain explicit, enforceable, observable, and traceable throughout AI employment.**

## Governance Chain

**Authority → Rule / Directive → Operational Constraint → Control → Configuration → Human Authority → Verification → Authorisation → Employment → Monitoring → Deviation → Response → Review**

---

## 1. Scope

Rules and operational constraints may govern:

- Mission
- Geography
- Time
- Targets or objects
- Users
- Data
- Information sharing
- AI outputs
- Decision authority
- Autonomy
- Human approval
- Tool access
- External interfaces
- Communications
- Security
- Operational environment
- Escalation
- Intervention
- Fail-safe behaviour
- Duration of authorisation

---

## 2. Sources

Relevant sources may include:

- Law
- Regulation
- Defence policy
- Service regulations
- Command directives
- Operational orders
- Rules of engagement
- Standing operating procedures
- National caveats
- Coalition agreements
- Security directives
- Data-handling rules
- Mission-specific instructions
- Operational authorisation conditions
- Temporary restrictions
- Emergency directions

The source, authority, version, effective period, and applicability of each material constraint should be recorded.

---

## 3. Constraint Classification

### 3.1 Prohibition
An action or use the AI capability must not perform or support.

### 3.2 Mandatory Condition
A condition that must be satisfied before an action or use is permitted.

### 3.3 Human-Approval Requirement
A decision or action requiring explicit human authority.

### 3.4 Geographic Constraint
A restriction based on location, area, boundary, jurisdiction, or theatre.

### 3.5 Temporal Constraint
A restriction based on time, duration, phase, window, or expiry.

### 3.6 Object / Target Constraint
A restriction on the type of object, entity, activity, or target to which AI-supported action may relate.

### 3.7 Data / Information Constraint
A restriction on collection, processing, access, retention, transfer, or disclosure.

### 3.8 Autonomy Constraint
A restriction on the level or mode of autonomous behaviour.

### 3.9 Technical Constraint
A system-enforced limitation.

### 3.10 Environmental Constraint
A condition defining the authorised operating environment.

---

## 4. Operational Constraint Register

| Constraint ID | Source | Authority | Scope | Constraint | Enforcement | Owner | Evidence | Expiry / Review |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |

Each constraint should be linked to the relevant mission, system configuration, operational authorisation, and responsible human authority.

---

## 5. Constraint Translation

Rules expressed in legal, policy, command, or operational language should be translated into actionable controls.

Use:

**Rule → Operational Requirement → Control → Verification → Evidence → Monitoring**

Possible controls include:

- Human approval gate
- Software policy rule
- Access restriction
- Geofence
- Time restriction
- Object whitelist / blacklist
- Tool restriction
- Network segmentation
- Data filter
- Rate limit
- Confidence threshold
- Mandatory escalation
- Safe-state trigger
- Manual confirmation

Where technical enforcement is not feasible, procedural controls should be explicit and their limitations understood.

---

## 6. Human Authority

For each consequential rule, identify:

- Who has authority to approve action
- Who may deny action
- Who may override the AI
- Who may suspend employment
- Who may modify constraints
- Who may approve exceptions
- Who must be notified after deviation

AI systems must not reinterpret their own authority beyond explicitly authorised boundaries.

---

## 7. Autonomy Boundaries

Operational constraints should define:

- Authorised autonomy level
- Permitted autonomous functions
- Functions requiring human approval
- Prohibited autonomous functions
- Conditions for autonomy transition
- Conditions requiring reduced autonomy
- Conditions requiring human takeover
- Conditions requiring safe state

A change in connectivity, system capability, mission urgency, or AI-to-AI interaction must not automatically expand autonomy authority.

---

## 8. Mission Boundaries

Record:

- Authorised mission
- Authorised use case
- Permitted decisions
- Permitted actions
- Prohibited uses
- Success criteria
- Exit criteria

Reuse for a materially different mission should trigger reassessment.

---

## 9. Geographic and Jurisdictional Boundaries

Where relevant, define:

- Authorised geographic area
- Excluded areas
- Jurisdictional boundaries
- Host-nation restrictions
- Coalition boundaries
- Cross-border restrictions
- Geofence accuracy assumptions

Boundary uncertainty should be addressed rather than assumed away.

---

## 10. Temporal Boundaries

Define:

- Start time
- Expiry time
- Mission phase
- Review period
- Temporary authority
- Emergency authority
- Conditions terminating authority

Expired authority must not silently persist through system configuration.

---

## 11. Information and Data Constraints

Define:

- Permitted data sources
- Prohibited data
- Classification limits
- Sharing restrictions
- Cross-domain restrictions
- Retention requirements
- Disclosure constraints
- Coalition-sharing conditions
- Data minimisation where applicable

The AI should not acquire broader information access merely because a technical interface becomes available.

---

## 12. Tool and Action Constraints

For AI systems capable of invoking tools or external actions, define:

- Permitted tools
- Prohibited tools
- Permission level
- Human approval requirement
- Rate / volume limits
- Action scope
- External-system restrictions
- Transaction limits
- Logging requirements

Tool access should follow least privilege.

---

## 13. Degraded and Disconnected Operations

Rules should define behaviour when:

- Communications fail
- Human supervision is degraded
- Positioning is uncertain
- Data feeds are unavailable
- Identity services fail
- Coalition connectivity is lost
- Monitoring is unavailable
- Security controls degrade

Loss of supervision should not automatically justify increased autonomy unless explicitly authorised.

---

## 14. Constraint Verification

Before operational employment, verify:

- Constraint is correctly implemented
- Technical control functions
- Human approval path functions
- Prohibited actions are blocked
- Override functions
- Logging works
- Failure mode is acceptable
- Degraded behaviour remains bounded

Verification should use representative scenarios.

---

## 15. Monitoring

During employment, monitor where appropriate:

- Boundary proximity
- Constraint violations
- Override events
- Failed action attempts
- Human approval events
- Autonomy transitions
- Tool use
- Geographic position
- Time validity
- Data-access events
- Security state

Monitoring should support timely intervention.

---

## 16. Constraint Deviation

A deviation occurs when the capability:

- Operates outside authorised scope
- Attempts a prohibited action
- Exceeds autonomy authority
- Uses unauthorised data
- Accesses an unauthorised tool
- Crosses an operational boundary
- Operates after authority expires
- Loses required human control
- Violates an authorisation condition

Deviation should trigger proportionate action.

---

## 17. Response to Deviation

Possible actions:

- Alert
- Human intervention
- Reject action
- Reduce autonomy
- Isolate capability
- Enter safe state
- Suspend employment
- Withdraw authorisation
- Initiate incident response
- Preserve evidence
- Revalidate
- Reauthorise

The response should reflect consequence and urgency.

---

## 18. Emergency Rules

Emergency or temporary authority should specify:

- Trigger
- Authority
- Scope
- Duration
- Permitted deviation
- Prohibited actions
- Human control
- Monitoring
- Evidence
- Expiry
- Post-event review

Emergency governance may be accelerated but should not disappear.

---

## 19. Rule Conflict

Where rules conflict:

1. Identify each rule.
2. Establish source and authority.
3. Determine hierarchy.
4. Escalate unresolved conflict.
5. Record interpretation.
6. Apply temporary restrictions if necessary.
7. Preserve decision evidence.

AI systems should not independently resolve material legal, policy, command, or operational conflicts unless an explicitly authorised rule mechanism governs that resolution.

---

## 20. Change Control

Changes to rules or constraints should be configuration-controlled.

Assess impact on:

- Risk
- Human authority
- Autonomy
- TEVV
- Security
- Mission
- Environment
- Authorisation

Material changes may require revalidation and reauthorisation.

---

## 21. Constraint Evidence

Evidence may include:

- Directive
- Operational order
- Rules of engagement
- Authorisation statement
- Configuration record
- Policy-engine configuration
- Test result
- Access-control record
- Geofence configuration
- Human approval log
- Override record
- Monitoring log
- Incident record

Evidence should allow reconstruction of which rules were active at a material decision point.

---

## 22. Operational Authorisation Integration

Operational authorisation should explicitly identify material constraints.

The authorisation object remains:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Constraints define the authorised envelope around that object.

---

## 23. AI-to-AI Interaction

Where AI systems interact:

- Authority must remain explicit
- One AI must not confer authority on another
- Constraints should propagate where required
- Interface permissions should be bounded
- Conflicting constraints should trigger escalation
- Logs should support reconstruction

**AI-to-AI interaction cannot create operational authority.**

---

## 24. Minimum Operational Constraint Set

For consequential AI, assess at minimum:

1. Mission boundary
2. Geographic boundary
3. Temporal boundary
4. Human-authority boundary
5. Autonomy boundary
6. Data boundary
7. Tool / action boundary
8. Security boundary
9. Environmental boundary
10. Escalation condition
11. Intervention mechanism
12. Safe-state condition
13. Monitoring requirement
14. Expiry / review trigger

---

## 25. Governance Test

Before employment, ask:

> **Can the organisation identify the authoritative rules governing this AI capability, translate them into operational constraints, enforce or supervise those constraints, detect material deviation, intervene when required, and reconstruct which rules and authority applied when a consequential decision or action occurred?**

If not, the operational governance boundary is incomplete.

---

## Anti-Patterns

Avoid:

1. Treating system capability as authority.
2. Encoding constraints without recording their source.
3. Relying only on operator memory.
4. Allowing expired authority to remain technically active.
5. Increasing autonomy when communications fail without explicit authority.
6. Treating geofencing alone as sufficient operational governance.
7. Allowing AI systems to resolve material rule conflicts without authorised logic.
8. Failing to test prohibited-action controls.
9. Treating emergency authority as indefinite.
10. Changing constraints without configuration control or reassessment.

---

## D-AIGAAF Integration

Rules, directives, and operational constraints connect legal and policy authority directly to operational employment:

**Authority → Rule → Requirement → Constraint → Control → Verification → Evidence → Assurance → Authorisation → Employment → Monitoring → Deviation → Incident / Change → Reassessment → Reauthorisation**

They integrate particularly with Human Authority, Risk & Autonomy, Operational Environment, Operational Authorisation, Operational Employment, Incident & Fail-Safe, Change & Reauthorisation, Architecture & Technical Controls, and Audit & Evidence.

---

## Final Principle

**Defence AI must operate inside an explicit authorised envelope defined by human authority, mission, environment, autonomy, rules, and constraints. Technical capability must never be allowed to silently expand that envelope.**
