# 22-Architecture and Technical Controls Templates

## Purpose

This document provides reusable templates for translating D-AIGAAF governance requirements into system architecture, enforceable technical controls, observable safeguards, evidence mechanisms, and reauthorisation triggers.

The objective is not to prescribe a single technology architecture. It is to ensure that governance requirements become technically implementable, testable, observable, and enforceable where necessary.

## Core Principle

**Governance requirements should become enforceable and observable technical controls where necessary to prevent, detect, constrain, or recover from unacceptable AI behaviour.**

Architecture must preserve the distinction between:

**Capability ≠ Authority**

A system may technically be capable of performing an action without being authorised to perform that action.

## Architecture Governance Chain

**Requirement → Architecture → Control → Implementation → Verification → Evidence → Operation → Monitoring → Change → Revalidation → Reauthorisation**

## Template Use

Each template should be adapted to the mission, AI capability, operational environment, autonomy level, human authority model, security requirements, and applicable policy or legal constraints.

Templates are records of governance activity. Completed templates may themselves become evidence, but completion alone does not constitute assurance or authorisation.

---

# Template 01 — AI Architecture Governance Record

## 1. Identification

- Architecture record ID:
- AI capability:
- Mission / use case:
- Organisation:
- Owner:
- Architecture authority:
- Date:
- Version:
- Status:
- Classification / handling:

## 2. Purpose

- Architectural objective:
- Intended operational role:
- Consequence of architectural failure:
- Relevant operational environments:
- Applicable autonomy level:

## 3. Governance Requirements

| Requirement | Source | Risk addressed | Architectural implication | Control required |
|---|---|---|---|---|
| | | | | |

## 4. Architecture Principles

- Human authority:
- Least privilege:
- Explicit autonomy boundaries:
- Security:
- Resilience:
- Observability:
- Configuration integrity:
- Fail-safe / safe-state:
- Interoperability:
- Data protection:
- Evidence generation:

## 5. Decisions

- Architecture decisions:
- Alternatives considered:
- Key trade-offs:
- Accepted limitations:
- Residual architectural risks:

## 6. Approval

- Technical authority:
- Governance authority:
- Risk owner:
- Approval date:
- Conditions:

---

# Template 02 — AI System Architecture & Component Record

## 1. System Identification

- System:
- AI model(s):
- Model version(s):
- Application:
- Mission:
- Environment:
- Autonomy level:

## 2. Components

| Component | Function | Owner | Dependency | Trust level | Criticality |
|---|---|---|---|---|---|
| | | | | | |

## 3. AI Processing Chain

**Input → Processing → Model / Agent → Output → Human / System Decision → Action**

Document:

- Inputs:
- Pre-processing:
- Model / model ensemble:
- Retrieval systems:
- Prompt / instruction layers:
- Tools:
- Post-processing:
- Human decision points:
- Automated actions:

## 4. Dependencies

- Data sources:
- External APIs:
- Cloud services:
- Communications:
- Positioning / timing:
- Identity services:
- Cybersecurity infrastructure:
- Supplier components:
- Other AI systems:

## 5. Architectural Risks

- Single points of failure:
- Hidden dependencies:
- Uncontrolled pathways:
- Unauthorised action pathways:
- Configuration risks:
- Supply-chain risks:

---

# Template 03 — AI Trust Boundary & Control Boundary Assessment

## 1. Boundary Identification

Identify boundaries between:

- AI model and application
- AI system and human operator
- AI system and external systems
- AI system and tools
- AI system and data sources
- AI system and networks
- Coalition / organisational domains
- Classified and unclassified domains
- Development and operational environments

## 2. Trust Assessment

| Boundary | Parties | Trust assumption | Verification | Failure consequence | Control |
|---|---|---|---|---|---|
| | | | | | |

## 3. Control Boundary

Define:

- What the AI can access:
- What the AI cannot access:
- What the AI can recommend:
- What the AI can execute:
- What requires human approval:
- What is technically prohibited:

## 4. Authority Boundary

- Authorised actions:
- Prohibited actions:
- Conditional actions:
- Human approval requirements:
- Escalation conditions:

## 5. Assessment

- Boundary adequate?:
- Known weaknesses:
- Required controls:
- Residual risk:

---

# Template 04 — Technical Control Requirements Record

## 1. Requirement

- Control ID:
- Governance requirement:
- Risk:
- Consequence:
- Applicable system:
- Applicable environment:

## 2. Control Specification

- Control objective:
- Control mechanism:
- Enforcement point:
- Trigger:
- Expected behaviour:
- Failure behaviour:
- Override conditions:
- Recovery behaviour:

## 3. Verification

- Test method:
- Test conditions:
- Acceptance criteria:
- Evidence generated:
- Independent verification required?:

## 4. Monitoring

- Indicator:
- Threshold:
- Alert:
- Responsible role:
- Response:

## 5. Traceability

**Requirement → Risk → Control → Test → Evidence → Assurance → Authorisation**

---

# Template 05 — Human Control & Intervention Architecture Record

## 1. Human Control Model

- Human role:
- Decision authority:
- Required competence:
- Information available:
- Time available:
- Intervention mechanism:
- Override mechanism:
- Accountability mechanism:

## 2. Decision Points

| AI function | AI authority | Human decision point | Intervention time | Required information |
|---|---|---|---|---|
| | | | | |

## 3. Intervention

- Stop:
- Pause:
- Override:
- Reject:
- Modify:
- Revert:
- Isolate:
- Move to safe state:

## 4. Meaningful Human Control Assessment

Assess whether the human has:

**Authority + Competence + Information + Time + Intervention + Accountability**

## 5. Failure Conditions

- Loss of communications:
- Operator overload:
- Delayed information:
- Misleading AI output:
- Unexpected autonomy:
- Operator disengagement:
- System failure:

## 6. Assurance

- Test evidence:
- Operational trial:
- Known limitations:
- Residual risk:

---

# Template 06 — Autonomy, Policy & Decision Boundary Control Record

## 1. Autonomy Classification

- Current level: A0 / A1 / A2 / A3 / A4 / A5
- Authorised level:
- Mission:
- Environment:
- Human authority:

## 2. Decision Boundary

- Decisions AI may support:
- Decisions AI may recommend:
- Decisions requiring human approval:
- Actions AI may execute:
- Actions technically prohibited:

## 3. Transition Controls

Define controls for:

- Manual → AI-assisted
- AI-assisted → human-authorised action
- Human-authorised → supervised autonomy
- Supervised autonomy → higher autonomy
- Higher autonomy → lower autonomy
- Normal → degraded operation

## 4. Technical Enforcement

- Policy engine:
- Permission controls:
- Action gating:
- Human approval mechanism:
- Rate limits:
- Geographical limits:
- Temporal limits:
- Target / object restrictions:
- Safe-state trigger:

## 5. Verification

- Transition tests:
- Boundary tests:
- Failure tests:
- Adversarial tests:
- Evidence:

## 6. Governance Rule

**AI must not acquire additional operational authority merely because technical capability, connectivity, system state, or interaction with another AI system changes.**

---

# Template 07 — AI Security Architecture & Technical Control Assessment

## 1. Security Scope

Assess:

- Model:
- Data:
- Application:
- Infrastructure:
- Interfaces:
- Instructions:
- Retrieval:
- Tools:
- Agents:
- Credentials:
- Dependencies:
- Human users:

## 2. Threats

| Threat | Attack surface | Consequence | Control | Test | Residual risk |
|---|---|---|---|---|---|
| | | | | | |

## 3. Security Controls

- Authentication:
- Authorisation:
- Isolation:
- Encryption:
- Integrity protection:
- Input validation:
- Prompt / instruction protection:
- Tool restrictions:
- Network controls:
- Secrets management:
- Model integrity:
- Supply-chain controls:
- Monitoring:

## 4. Adversarial Conditions

- Prompt injection:
- Data poisoning:
- Model manipulation:
- Adversarial inputs:
- Tool abuse:
- Privilege escalation:
- Compromised dependency:
- AI-to-AI attack:
- Denial / degradation:

## 5. Security Assurance

- Test evidence:
- Red-team evidence:
- Independent assessment:
- Open findings:
- Residual risk:

---

# Template 08 — Observability, Logging & Evidence Architecture Record

## 1. Observability Objectives

The architecture should enable reconstruction of material:

- Inputs
- Outputs
- Model / version
- Configuration
- Instructions
- Tool use
- Human decisions
- AI decisions / recommendations
- Actions
- Overrides
- Exceptions
- Security events
- Environment state
- Authorisation state

## 2. Logging Requirements

| Event | Required record | Retention | Protection | Responsible owner |
|---|---|---|---|---|
| | | | | |

## 3. Evidence Integrity

- Timestamping:
- Identity:
- Integrity protection:
- Tamper detection:
- Chain of custody:
- Access control:
- Backup:
- Recovery:

## 4. Operational Constraints

Consider:

- Bandwidth:
- Storage:
- Communications loss:
- Classified environments:
- Disconnected operations:
- Electromagnetic constraints:
- Operational security:

## 5. Evidence Sufficiency

- Can material decisions be reconstructed?:
- Can configuration be established?:
- Can human authority be established?:
- Can AI behaviour be evaluated?:
- Can incidents be investigated?:

---

# Template 09 — Architecture Change, Verification & Reauthorisation Record

## 1. Change

- Change ID:
- System:
- Baseline:
- Proposed change:
- Reason:
- Owner:
- Date:

## 2. Change Classification

Assess whether the change affects:

- Model:
- Weights:
- Prompts / instructions:
- Data:
- Retrieval:
- Tools:
- Agent behaviour:
- Interfaces:
- Security:
- Human control:
- Autonomy:
- Environment:
- Supplier:
- Policy / legal requirements:

## 3. Impact Assessment

- Risk impact:
- Assurance impact:
- TEVV impact:
- Human-control impact:
- Security impact:
- Authorisation impact:

## 4. Verification

- Required tests:
- Test environment:
- Acceptance criteria:
- Results:
- Evidence:

## 5. Revalidation

- Revalidation required?:
- Basis:
- Findings:
- Residual uncertainty:

## 6. Reauthorisation

- Reauthorisation required?:
- Decision authority:
- Conditions:
- New boundaries:
- Effective date:

## 7. Implementation

- Deployment plan:
- Rollback plan:
- Monitoring:
- Post-change review:

---

# Template 10 — Architecture Assurance & Governance Review

## 1. Review Scope

- System:
- Mission:
- Environment:
- Architecture baseline:
- Autonomy:
- Human authority:
- Review date:

## 2. Assessment

| Domain | Status | Evidence | Finding | Risk | Action |
|---|---|---|---|---|---|
| Architecture | | | | | |
| Human control | | | | | |
| Autonomy | | | | | |
| Security | | | | | |
| Observability | | | | | |
| Resilience | | | | | |
| Configuration | | | | | |
| Interoperability | | | | | |

## 3. Governance Questions

- Does the architecture still support the authorised mission?
- Are technical controls still effective?
- Can prohibited actions still be technically constrained?
- Is human intervention meaningful?
- Is autonomy within authorised boundaries?
- Can material activity be reconstructed?
- Have dependencies changed?
- Has the operational environment changed?
- Has assurance degraded?
- Is revalidation required?
- Is reauthorisation required?

## 4. Decision

- Continue:
- Continue with conditions:
- Restrict:
- Suspend:
- Revalidate:
- Reauthorise:
- Retire:

## 5. Final Record

- Decision:
- Authority:
- Conditions:
- Evidence reference:
- Next review:
- Lessons learned:

---

# Minimum Architecture Control Set

For consequential defence AI, architecture should address, as applicable:

1. **Human authority enforcement**
2. **Explicit autonomy boundaries**
3. **Least privilege**
4. **Action gating**
5. **Safe-state / fail-safe mechanisms**
6. **Configuration integrity**
7. **Model integrity**
8. **Input and data integrity**
9. **Security isolation**
10. **Identity and access control**
11. **Tool and API restrictions**
12. **Observability and logging**
13. **Decision and action traceability**
14. **Resilience and degraded-operation behaviour**
15. **Interoperability boundaries**
16. **Change detection and control**
17. **Rollback / recovery capability**
18. **Evidence preservation**
19. **Monitoring and alerting**
20. **Revalidation / reauthorisation triggers**

## Architecture Governance Test

A consequential AI architecture should be challenged against the following question:

> **If the AI behaves incorrectly, unexpectedly, or maliciously, does the architecture provide sufficient technical and human mechanisms to detect it, constrain it, intervene, preserve evidence, recover safely, and prevent unauthorised consequences?**

If the answer is no, the governance requirement has not yet been adequately translated into architecture.

## D-AIGAAF Integration

Architecture and technical controls connect governance intent to operational reality:

**Mission Need → Risk → Requirements → Architecture → Controls → Implementation → TEVV → Evidence → Assurance → Human Authority → Operational Authorisation → Employment → Monitoring → Change → Revalidation → Reauthorisation**

Architecture therefore acts as a bridge between **governance requirements** and **observable operational behaviour**.

## Final Principle

**A governance requirement that cannot be implemented, enforced, observed, tested, or evidenced where necessary is not yet a sufficiently operational governance requirement.**

Architecture must therefore make the D-AIGAAF principles technically meaningful without allowing technical capability to become operational authority by default.
