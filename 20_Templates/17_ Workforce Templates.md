# 17-Workforce Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 17 — Workforce**.

Consequential AI governance depends on people who have the authority, competence, capacity, independence and situational understanding required to govern, assure, authorise, supervise and safely employ AI capabilities.

The central principle is:

> **No consequential AI capability should depend on people who lack the authority, competence, capacity, independence or information necessary to govern, assure, authorise, supervise or safely employ it.**

The workforce governance chain is:

**Roles → Authority → Competence → Capacity → Training → Oversight → Accountability → Monitoring → Learning → Improvement**

---

# 2. Template Set

The recommended Workforce template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-17-001 | Workforce Governance Record |
| D-AIGAAF-T-17-002 | AI Role & Responsibility Record |
| D-AIGAAF-T-17-003 | Competence, AI Literacy & Qualification Assessment |
| D-AIGAAF-T-17-004 | Human Authority, Oversight & Intervention Record |
| D-AIGAAF-T-17-005 | Workforce Capacity, Workload & Continuity Assessment |
| D-AIGAAF-T-17-006 | Independence, Separation & Professional Conduct Record |
| D-AIGAAF-T-17-007 | Training, Exercises & Competence Maintenance Record |
| D-AIGAAF-T-17-008 | Workforce Risk & Corrective Action Record |
| D-AIGAAF-T-17-009 | Workforce Knowledge, Records & Continuous Learning Record |
| D-AIGAAF-T-17-010 | Workforce Governance Review & Improvement Record |

---

# 3. Template 17-001 — Workforce Governance Record

## Purpose

Defines the governance arrangements required to ensure that people responsible for AI capabilities are appropriately structured, qualified and supported.

## Required Fields

- Capability ID
- Mission / Use Case
- Workforce owner
- Governance authority
- Operational authority
- Risk owner
- TEVV authority
- Security authority
- Training authority
- HR / workforce authority
- Records authority
- Review date

## Governance Questions

- Which roles are required?
- Which roles require formal authority?
- Which roles require technical competence?
- Which roles require operational competence?
- Which roles require independence?
- What happens if a key person becomes unavailable?
- How is competence maintained?
- How are workforce risks monitored?

---

# 4. Template 17-002 — AI Role & Responsibility Record

## Purpose

Defines the people and organisational roles involved across the AI lifecycle.

## Roles to Consider

- mission owner;
- use-case owner;
- capability owner;
- AI developer;
- system integrator;
- data owner;
- model owner;
- security authority;
- TEVV authority;
- assurance authority;
- risk owner;
- operational commander;
- operator;
- supervisor;
- maintainer;
- incident responder;
- auditor;
- authorisation authority;
- procurement authority;
- supplier representative.

## Required Fields

- Role
- Person / organisational unit
- Responsibilities
- Decision rights
- Required competence
- Required authority
- Independence requirement
- Delegation
- Escalation route
- Backup / alternate
- Review date

Responsibilities should be assigned explicitly rather than inferred from organisational hierarchy.

---

# 5. Template 17-003 — Competence, AI Literacy & Qualification Assessment

## Purpose

Determines whether personnel possess the competence required for their assigned AI-related responsibilities.

## Competence Domains

Consider:

### Operational

- mission understanding;
- operational procedures;
- threat awareness;
- environmental understanding.

### AI

- AI fundamentals;
- model limitations;
- uncertainty;
- failure modes;
- autonomy;
- human-AI interaction.

### Governance

- risk;
- authorisation;
- accountability;
- policy;
- assurance.

### Security

- AI attack surfaces;
- adversarial threats;
- information security;
- model/data integrity.

### Technical

Where required:

- system architecture;
- data;
- software;
- model configuration;
- monitoring.

## Required Fields

- Role
- Required competence
- Current competence
- Evidence
- Qualification
- Gap
- Risk
- Training requirement
- Assessor
- Review date

Competence should be assessed against the actual role, not against generic AI knowledge.

---

# 6. Competence and Consequence

Higher-consequence AI should generally require stronger competence.

Consider:

**Consequence**
+
**Autonomy**
+
**Operational Complexity**
+
**Environmental Uncertainty**
+
**Human-Control Requirement**

→ **Required Workforce Competence**

A person competent to use AI for administrative analysis may not be competent to supervise an AI capability involved in consequential operational decisions.

---

# 7. Template 17-004 — Human Authority, Oversight & Intervention Record

## Purpose

Records whether assigned personnel have the practical ability to exercise meaningful human control.

## Required Fields

- Capability
- Mission
- Human role
- Authority
- Decision rights
- Information available
- AI outputs presented
- Uncertainty presented
- Time available
- Intervention method
- Override capability
- Safe-state mechanism
- Escalation
- Accountability
- Limitations

## Assessment

Test whether the human has:

**Authority + Competence + Information + Time + Intervention + Accountability**

If one or more elements are materially absent, meaningful human control may be compromised.

---

# 8. Workforce and Situational Awareness

Human control depends on situational awareness.

Assess whether personnel understand:

- current mission state;
- AI operating state;
- AI confidence / uncertainty;
- relevant environmental conditions;
- known limitations;
- system anomalies;
- autonomy state;
- available intervention options.

A human cannot meaningfully supervise a capability they cannot adequately understand in the time available.

---

# 9. Template 17-005 — Workforce Capacity, Workload & Continuity Assessment

## Purpose

Determines whether personnel have sufficient capacity to safely perform assigned AI responsibilities.

## Assess

- staffing;
- workload;
- duty duration;
- fatigue;
- shift patterns;
- alert volume;
- decision frequency;
- simultaneous systems;
- operator-to-system ratio;
- supervision requirements;
- backup personnel;
- continuity.

## Required Fields

- Role
- Required staffing
- Actual staffing
- Workload
- Peak demand
- Fatigue considerations
- Critical dependencies
- Backup arrangements
- Continuity risk
- Mitigation
- Residual risk

## Principle

> **A human-control requirement that cannot realistically be performed under operational workload is not an effective control.**

---

# 10. Template 17-006 — Independence, Separation & Professional Conduct Record

## Purpose

Assesses whether personnel involved in consequential decisions have sufficient independence and professional integrity.

## Consider

- conflict of interest;
- separation of development and acceptance;
- independence of evaluation;
- pressure to approve;
- commercial incentives;
- command pressure;
- supplier influence;
- professional standards;
- protected escalation;
- whistleblowing / reporting mechanisms.

## Required Fields

- Role
- Independence requirement
- Actual arrangement
- Conflict
- Mitigation
- Escalation route
- Review authority
- Determination

Independence should be proportionate to consequence and the nature of the decision.

---

# 11. Workforce Separation of Duties

Where appropriate, separate:

**Development**
from
**Evaluation**

**Evaluation**
from
**Authorisation**

**Operational Employment**
from
**Independent Audit**

**Supplier**
from
**Acceptance Authority**

The objective is not bureaucracy for its own sake.

The objective is to prevent a person or organisation from being the sole judge of its own consequential work where independent challenge is required.

---

# 12. Template 17-007 — Training, Exercises & Competence Maintenance Record

## Purpose

Records initial and continuing preparation of personnel responsible for AI capabilities.

## Training Areas

Consider:

- AI fundamentals;
- AI limitations;
- uncertainty;
- human control;
- autonomy;
- mission procedures;
- security;
- adversarial threats;
- fail-safe;
- incident response;
- degraded/disconnected operations;
- escalation;
- authorisation conditions.

## Exercise Types

- tabletop;
- simulation;
- operational rehearsal;
- adversarial exercise;
- fail-safe exercise;
- degraded-environment exercise;
- intervention / override exercise;
- incident-response exercise.

## Required Fields

- Person / role
- Training
- Exercise
- Date
- Competence objective
- Result
- Deficiency
- Remedial action
- Recertification requirement
- Assessor

---

# 13. Training Must Reflect Operational Reality

Training should not rely exclusively on normal operating conditions.

Where relevant, personnel should experience:

- degraded communications;
- unreliable data;
- adversarial manipulation;
- unexpected AI outputs;
- uncertainty;
- loss of system availability;
- unexpected autonomy;
- human-machine interface failure;
- time pressure;
- conflicting information.

The objective is to determine whether human control survives realistic operational stress.

---

# 14. Template 17-008 — Workforce Risk & Corrective Action Record

## Purpose

Records workforce-related risks, deficiencies and corrective actions.

## Risk Sources

Consider:

- competence gaps;
- understaffing;
- excessive workload;
- fatigue;
- inadequate training;
- unclear authority;
- poor supervision;
- insufficient independence;
- loss of key personnel;
- supplier dependency;
- inadequate continuity;
- weak incident response competence.

## Required Fields

- Workforce risk
- Role
- Cause
- Consequence
- Likelihood
- Existing controls
- Residual risk
- Corrective action
- Owner
- Due date
- Verification
- Closure authority

---

# 15. Workforce Risk and AI Risk

Workforce risk can become AI system risk.

Examples:

**Insufficient AI literacy**
→ misinterpretation of outputs

**High workload**
→ missed warnings

**Poor training**
→ ineffective intervention

**Unclear authority**
→ delayed decisions

**Insufficient staffing**
→ degraded supervision

**Loss of expertise**
→ configuration or maintenance errors

Therefore workforce assessment should be integrated with the capability risk assessment.

---

# 16. Template 17-009 — Workforce Knowledge, Records & Continuous Learning Record

## Purpose

Maintains institutional knowledge relating to AI governance and employment.

## Required Fields

- Knowledge item
- Source
- Capability
- Role
- Lesson
- Decision
- Evidence
- Owner
- Training implication
- Policy implication
- Control implication
- Review date

## Knowledge Sources

Consider:

- incidents;
- exercises;
- audits;
- TEVV;
- operational experience;
- change events;
- supplier events;
- lessons learned;
- governance reviews.

Critical knowledge should not depend solely on one individual.

---

# 17. Workforce Continuity

D-AIGAAF should address the risk of **single-person dependency**.

For critical roles, consider:

- alternates;
- succession;
- cross-training;
- documented procedures;
- configuration knowledge;
- decision history;
- access continuity;
- emergency delegation.

A capability should not become unsafe merely because one qualified person is unavailable.

---

# 18. Template 17-010 — Workforce Governance Review & Improvement Record

## Purpose

Provides periodic review of workforce adequacy and its relationship to AI governance.

## Review Areas

- role coverage;
- competence;
- AI literacy;
- staffing;
- workload;
- training;
- exercises;
- independence;
- human control;
- continuity;
- incidents;
- audit findings;
- operational lessons.

## Review Questions

1. Are required roles clearly defined?
2. Are decision rights explicit?
3. Are personnel competent for their actual responsibilities?
4. Is AI literacy adequate?
5. Is workload compatible with meaningful human control?
6. Are intervention capabilities realistic?
7. Is independence sufficient?
8. Are critical roles resilient to personnel loss?
9. Are training and exercises producing measurable competence?
10. Are workforce weaknesses creating AI governance or operational risk?

---

# 19. Human Control as a Workforce Control

Human authority should not be treated as a statement that:

> “A human remains in the loop.”

The assessment should establish whether the human can actually:

- understand;
- question;
- delay;
- reject;
- intervene;
- override;
- escalate;
- stop;
- operate safely when AI is unavailable.

This is especially important for high-autonomy systems.

---

# 20. Human–AI Workload

AI may reduce workload in some contexts while increasing it in others.

Potential effects include:

- alert fatigue;
- verification burden;
- monitoring burden;
- automation bias;
- complacency;
- excessive trust;
- decision acceleration;
- information overload.

Workforce assessment should therefore examine the **net cognitive and operational effect** of AI.

---

# 21. Automation Bias

Personnel may over-trust AI recommendations because they appear:

- objective;
- quantitative;
- fast;
- technically sophisticated;
- consistently formatted.

Training and operational design should address the risk that AI recommendations are accepted without appropriate challenge.

The objective is not to require humans to reject AI routinely.

The objective is to ensure that acceptance remains an informed decision.

---

# 22. Workforce and Uncertainty

Personnel should understand that:

**AI output ≠ fact**

Where uncertainty is material, the system should communicate it in a form the responsible human can understand and use.

Training should include:

- uncertainty interpretation;
- confidence limitations;
- ambiguity;
- incomplete information;
- false positives;
- false negatives;
- model failure.

---

# 23. Workforce and Autonomy

Personnel should understand the difference between:

- intended autonomy;
- actual autonomy;
- authorised autonomy.

They should know:

- current autonomy state;
- permitted transitions;
- prohibited transitions;
- intervention mechanisms;
- authority boundaries;
- escalation requirements.

Unexpected autonomy should be treated as a governance and potentially operational incident.

---

# 24. Workforce and Degraded / Disconnected Operations

Where AI is expected to operate without reliable connectivity, personnel should be trained for:

- loss of communications;
- loss of external data;
- local-only operation;
- stale information;
- degraded AI capability;
- manual fallback;
- safe-state transition;
- restoration of communications.

The workforce model should not assume perfect connectivity unless the authorisation explicitly depends on it.

---

# 25. Workforce and Incident Response

Personnel should know what to do when:

- AI behaves unexpectedly;
- confidence becomes unreliable;
- autonomy changes unexpectedly;
- human control is degraded;
- data integrity is questioned;
- security compromise is suspected;
- system boundaries are exceeded;
- fail-safe activates.

Training should establish clear:

**Detect → Report → Protect → Intervene → Escalate → Recover → Record → Learn**

procedures.

---

# 26. Workforce and Operational Authorisation

Operational authorisation should specify, where relevant:

- authorised human roles;
- required qualifications;
- minimum staffing;
- supervision requirements;
- intervention authority;
- escalation;
- duty continuity;
- training status.

If required human conditions are not met, the capability may no longer satisfy its authorisation conditions.

---

# 27. Workforce Evidence

Useful evidence may include:

- qualification records;
- training completion;
- exercise results;
- competence assessments;
- staffing records;
- workload analysis;
- duty rosters;
- intervention tests;
- incident performance;
- audit findings;
- operational lessons.

Evidence should demonstrate capability, not merely attendance.

For example:

**Training completed**
does not necessarily mean
**competence demonstrated**.

---

# 28. Anti-Pattern — Human in the Loop = Human Control

D-AIGAAF rejects:

> “A human is present, therefore the system is under human control.”

A human may be:

- overloaded;
- uninformed;
- unqualified;
- too slow;
- unable to intervene;
- unable to understand the output;
- unclear about authority.

Meaningful control must be demonstrated in context.

---

# 29. Anti-Pattern — AI Expertise Without Operational Expertise

Technical AI knowledge alone may be insufficient for consequential defence applications.

Likewise, operational expertise alone may be insufficient for complex AI systems.

Where appropriate, governance should provide personnel capable of bridging:

**Operational Context ↔ AI Behaviour ↔ Risk ↔ Human Authority**

This intermediate competence can be critical for translating technical limitations into operational decisions.

---

# 30. Anti-Pattern — Training as a One-Time Event

AI capabilities, threats and operational contexts change.

Competence should therefore be maintained through:

- refresher training;
- exercises;
- incident learning;
- system updates;
- mission changes;
- role changes;
- periodic reassessment.

Training should evolve with the capability.

---

# 31. Workforce and Accountability

Every consequential AI decision or action should have an appropriate accountability path.

Depending on the capability, records should allow identification of:

- responsible human;
- authority exercised;
- AI state;
- AI output;
- relevant information;
- decision;
- action;
- intervention;
- applicable conditions.

Accountability should not be transferred to the AI.

---

# 32. Workforce and AI-to-AI Interaction

AI-to-AI interaction cannot create human authority.

An AI system cannot legitimately:

- delegate operational authority;
- expand its own authority;
- authorise another AI;
- redefine mission boundaries;
- approve its own autonomy.

Any consequential authority must trace back to an appropriately authorised human governance mechanism.

---

# 33. Workforce Golden Thread Integration

The Workforce module connects people to the D-AIGAAF Golden Thread:

**Mission Need**
→ **Risk**
→ **Requirements**
→ **Controls**
→ **Testing**
→ **Evidence**
→ **Assurance**
→ **Authority**
→ **Conditions**
→ **Boundaries**
→ **Employment**
→ **Monitoring**
→ **Change / Incident**
→ **Learning**
→ **Revalidation / Reauthorisation**
→ **Workforce**
→ **Roles**
→ **Competence**
→ **Capacity**
→ **Human Authority**
→ **Accountability**
→ **Continuous Improvement**

The workforce is therefore not a supporting administrative function. It is part of the control system.

---

# 34. Final Workforce Principle

D-AIGAAF treats workforce capability as a substantive AI governance control.

The governing principle is:

> **A consequential AI capability should not be considered adequately governed merely because appropriate roles have been named; the organisation should demonstrate that the people exercising those roles possess the required authority, competence, information, capacity, independence and practical ability to maintain meaningful human control under the conditions in which the capability is authorised to operate.**
