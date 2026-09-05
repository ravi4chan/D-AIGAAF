# D-AIGAAF Golden Thread

**Defence AI Governance, Assurance & Operational Authorisation Framework**

**Version:** 0.1  
**Status:** Working Draft  
**Classification:** Open / Unclassified

---

## 1. Purpose

The D-AIGAAF Golden Thread is the traceability chain connecting **mission need to operational authority and subsequent operational learning**.

It provides a common logic for the entire framework:

> **Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

The Golden Thread is not another lifecycle.

It is the **traceability logic that connects the lifecycle stages and framework modules together**.

---

# 2. Why the Golden Thread Matters

AI governance can become fragmented when:

- operational requirements are separated from technical requirements;
- risk assessments are disconnected from testing;
- testing is disconnected from authorisation;
- supplier evidence is accepted without understanding what it demonstrates;
- operational restrictions are not reflected in system design;
- incidents do not feed back into assurance; or
- changes are introduced without reconsidering previous evidence.

The Golden Thread is intended to prevent these breaks.

It establishes a continuous relationship between:

**Why the capability exists → What could go wrong → What must be controlled → What was demonstrated → Who accepted the remaining risk → What authority was granted → What actually happened.**

---

# 3. The D-AIGAAF Golden Thread

```text
MISSION NEED
     ↓
USE CASE
     ↓
RISK
     ↓
REQUIREMENTS
     ↓
CONTROLS
     ↓
TESTING / TEVV
     ↓
EVIDENCE
     ↓
ASSURANCE
     ↓
OPERATIONAL AUTHORISATION
     ↓
OPERATIONAL EMPLOYMENT
     ↓
MONITORING
     ↓
CHANGE / INCIDENT / EMERGING RISK
     ↓
REVALIDATION
     ↓
REAUTHORISATION
     ↓
LESSONS / RETIREMENT
```

Each stage should remain traceably connected to the preceding and following stages.

---

# 4. The Golden Thread in One Question

At any point in the lifecycle, D-AIGAAF should allow an organisation to answer:

> **Why is this AI capability authorised to do what it is currently doing?**

That question should be answerable through evidence rather than assumption.

A corresponding trace should identify:

1. the mission need;
2. the intended use case;
3. the relevant risks;
4. the requirements established to manage those risks;
5. the controls implemented;
6. the testing and evaluation performed;
7. the evidence generated;
8. the assurance conclusions;
9. the authority granted;
10. the conditions attached to that authority;
11. the actual operational use; and
12. any changes, incidents or new evidence affecting the original decision.

---

# 5. Golden Thread Components

## 5.1 Mission Need

The starting point.

The organisation should be able to explain why the AI capability is required.

**Question:**

> What operational or organisational problem are we trying to solve?

---

## 5.2 Use Case

Defines how the capability is intended to address the mission need.

**Question:**

> What exactly will the AI capability do, for whom, and under what conditions?

---

## 5.3 Risk

Identifies what could go wrong and the consequences.

Risk should consider, as appropriate:

- consequence;
- autonomy;
- mission criticality;
- operational environment;
- human control;
- security;
- information integrity;
- supply-chain dependencies.

**Question:**

> What could go wrong, and how serious could the consequences be?

---

## 5.4 Requirements

Translate mission needs and risk considerations into conditions the capability must satisfy.

Requirements should address both:

- **what the capability must do**, and
- **what it must not do**.

The second category is particularly important for consequential AI.

**Question:**

> What must be true before this capability can be trusted for its intended use?

---

## 5.5 Controls

Controls are the technical, procedural, organisational and human measures intended to manage identified risks.

Examples may include:

- access controls;
- autonomy restrictions;
- human approval;
- monitoring;
- data controls;
- security controls;
- fail-safe mechanisms;
- environmental restrictions;
- configuration controls;
- procedural controls.

**Question:**

> What prevents, detects or limits unacceptable outcomes?

---

## 5.6 Testing / TEVV

Testing and evaluation generate evidence about whether requirements and controls are satisfied.

Testing should be proportionate to:

- consequence;
- autonomy;
- mission criticality;
- operational environment;
- human-control conditions.

**Question:**

> Did we test the things that matter for the intended mission?

---

## 5.7 Evidence

Evidence provides the basis for assurance conclusions.

Evidence may include:

- test results;
- evaluation reports;
- verification results;
- validation results;
- security assessments;
- red-team findings;
- operational trials;
- incident records;
- configuration records;
- supplier information.

**Question:**

> What do we actually know, and how do we know it?

---

## 5.8 Assurance

Assurance interprets evidence against defined requirements, risks and intended use.

Assurance should identify:

- what has been demonstrated;
- what has not been demonstrated;
- known limitations;
- assumptions;
- uncertainties;
- residual risks;
- evidence gaps.

**Question:**

> Does the evidence provide sufficient confidence for the intended use?

---

## 5.9 Authority

Authority converts an assurance position into an organisational decision.

Operational authorisation should establish:

- what is permitted;
- what is not permitted;
- under whose authority;
- in what environment;
- at what autonomy;
- under what conditions;
- for how long.

**Question:**

> Given the evidence and residual risk, should this capability be permitted to operate?

---

## 5.10 Operational Employment

The capability is used within its authorised operational envelope.

The Golden Thread requires operational employment to remain connected to the authorisation that permits it.

**Question:**

> Is the system actually being used in the way it was authorised?

---

## 5.11 Monitoring

Operational use generates new information about system performance and risk.

Monitoring should consider:

- performance;
- anomalies;
- security;
- data integrity;
- environmental conditions;
- human interventions;
- incidents;
- mission outcomes;
- configuration.

**Question:**

> Does operational experience continue to support the original assurance position?

---

## 5.12 Change / Incident / Emerging Risk

Changes, incidents and emerging risks can break assumptions underlying previous assurance.

Examples include:

- model updates;
- software changes;
- new data;
- new interfaces;
- changed autonomy;
- changed mission;
- new operating environment;
- security incidents;
- unexpected behaviour;
- newly discovered vulnerabilities.

**Question:**

> Has anything changed that could invalidate our previous evidence or authority?

---

## 5.13 Revalidation

Revalidation determines whether the capability continues to satisfy its intended purpose following a relevant change or event.

**Question:**

> Does the capability still satisfy the intended operational need?

---

## 5.14 Reauthorisation

Reauthorisation determines whether operational authority should continue, change, be restricted or be withdrawn.

**Question:**

> Should the organisation continue to permit this capability to operate under the existing or revised conditions?

---

# 6. Traceability Model

The Golden Thread can be represented as:

```text
Mission Need
     │
     ├──→ Use Case
     │       │
     │       └──→ Requirements
     │                  │
     │                  └──→ Risk
     │                         │
     │                         └──→ Controls
     │                                  │
     │                                  └──→ TEVV
     │                                         │
     │                                         └──→ Evidence
     │                                                │
     │                                                └──→ Assurance
     │                                                       │
     │                                                       └──→ Authority
     │                                                              │
     │                                                              └──→ Employment
     │                                                                     │
     │                                                                     └──→ Monitoring
     │                                                                            │
     │                                                                            └──→ Change / Incident
     │                                                                                   │
     │                                                                                   └──→ Revalidation
     │                                                                                          │
     │                                                                                          └──→ Reauthorisation
     │
     └──────────────────────────────────────────────────────────────────────────────────────────────→ Learning
```

The exact implementation may use a database, register, document set or other information architecture.

The principle is **traceability**, not a particular technology.

---

# 7. Golden Thread and Accountability

For consequential AI, the Golden Thread should support reconstruction of the decision chain.

Where practicable, an organisation should be able to establish:

```text
Mission
  ↓
Requirement
  ↓
AI Output / System Behaviour
  ↓
Human Interpretation
  ↓
Human Decision
  ↓
Authorised Action
  ↓
Outcome
```

This does not imply that every internal model process must be perfectly explainable.

It means that the organisational decision chain should be sufficiently recorded to support accountability, investigation and learning.

---

# 8. Golden Thread and Human Authority

AI output and human authority must remain distinguishable.

The Golden Thread therefore recognises:

**AI Output ≠ Human Decision ≠ Command Authority**

Where AI provides a recommendation:

```text
AI Analysis / Recommendation
             ↓
      Human Assessment
             ↓
      Authorised Decision
             ↓
          Action
```

The exact relationship changes with the authorised autonomy level.

---

# 9. Golden Thread and Autonomy

As autonomy increases, the Golden Thread must still preserve traceability of:

- the authority granted to the system;
- the conditions under which it may act;
- the controls limiting its behaviour;
- the evidence supporting that authority;
- the monitoring applied during operation.

For higher-consequence autonomous functions, the strength and granularity of this traceability should generally increase.

---

# 10. Golden Thread and Evidence

A claim should be connected to evidence.

A useful conceptual structure is:

```text
Claim
  ↓
Requirement
  ↓
Evidence
  ↓
Finding
  ↓
Assurance Conclusion
  ↓
Authorisation Decision
```

This prevents unsupported statements such as:

> "The system is safe."

from becoming governance conclusions.

Instead, the framework should ask:

> **Safe for what, under which conditions, based on what evidence, with what limitations?**

---

# 11. Golden Thread and Operational Envelope

The Golden Thread should connect the operational envelope to evidence.

For example:

```text
Authorised Environment
        ↓
Required Performance
        ↓
Relevant Test Conditions
        ↓
Evidence
        ↓
Assurance Conclusion
        ↓
Authorisation Condition
```

This prevents testing in a narrow environment from automatically being interpreted as evidence for every possible operating condition.

---

# 12. Golden Thread and Risk

Risk should remain connected to the controls and evidence intended to manage it.

The basic relationship is:

```text
Risk
 ↓
Control
 ↓
Test
 ↓
Evidence
 ↓
Residual Risk
 ↓
Assurance
 ↓
Authority
```

If a control is changed, the relevant evidence and residual-risk assessment should be reconsidered.

---

# 13. Golden Thread and Change

A material change should be traceable through the Golden Thread.

```text
Change
  ↓
Change Assessment
  ↓
Affected Requirements
  ↓
Affected Risks
  ↓
Affected Controls
  ↓
Required TEVV
  ↓
New / Updated Evidence
  ↓
Updated Assurance
  ↓
Reauthorisation Decision
```

This provides the basis for the principle:

> **Behaviour determines change significance.**

A technically small change can be operationally significant.

---

# 14. Golden Thread and Incidents

An incident should not be treated as an isolated event.

The incident should be connected back to the assumptions and evidence that supported the original authorisation.

```text
Incident
   ↓
System / Human / Environmental Analysis
   ↓
Affected Risk
   ↓
Affected Control
   ↓
Affected Evidence
   ↓
Assurance Reassessment
   ↓
Authority Decision
```

Possible outcomes include:

- continued operation;
- additional controls;
- restricted operation;
- suspension;
- revalidation;
- reauthorisation;
- retirement.

---

# 15. Golden Thread and Operational AI Advisor

The Operational AI Advisor can help maintain the connection between technical evidence and operational decision-making.

The OAIA may assist in interpreting:

- system capability;
- limitations;
- evidence;
- risk;
- autonomy;
- operational conditions;
- incidents;
- proposed changes.

The OAIA provides advice.

The authorised command or organisational authority makes the decision.

---

# 16. Golden Thread Records

The following records should contribute to the Golden Thread:

| Record | Primary Question |
|---|---|
| Mission Need | Why does the capability exist? |
| Use Case | How is it intended to be used? |
| Requirements | What must it satisfy? |
| Risk Assessment | What could go wrong? |
| Control Register | What manages the risk? |
| TEVV Record | What was tested and evaluated? |
| Evidence Repository | What demonstrates the claims? |
| DAAR | What does the evidence establish? |
| DAOA | What operational authority was granted? |
| Operational Record | What actually happened? |
| Incident Record | What went wrong or deviated? |
| Change Record | What changed? |
| Revalidation Record | Does the capability still meet its purpose? |
| Reauthorisation Record | Should authority continue? |
| Retirement Record | Has operational authority ended? |

---

# 17. Minimum Traceability Requirement

For consequential AI capabilities, the organisation should be able to trace at minimum:

```text
Mission
   ↓
Use Case
   ↓
Risk
   ↓
Requirement
   ↓
Control
   ↓
Evidence
   ↓
Assurance
   ↓
Authorisation
   ↓
Operational Use
```

Where an element is not applicable, the reason should be documented rather than silently omitted.

---

# 18. Golden Thread Quality Test

A D-AIGAAF implementation should periodically ask:

### Mission

Can we explain why this capability exists?

### Risk

Can we explain what could go wrong?

### Requirements

Can we identify what the capability must satisfy?

### Controls

Can we identify what manages the relevant risks?

### Evidence

Can we demonstrate that the important requirements and controls have been tested?

### Assurance

Can we explain what the evidence actually demonstrates?

### Authority

Can we identify who authorised the capability and under what conditions?

### Employment

Can we determine whether the capability is being used within those conditions?

### Monitoring

Can we identify whether operational experience changes the assurance position?

### Change

Can we determine whether changes require reassessment?

### Accountability

Can we reconstruct significant decisions and actions?

If these questions cannot be answered, the Golden Thread is incomplete.

---

# 19. Golden Thread Failure Modes

D-AIGAAF should guard against the following conditions:

## 19.1 Orphan Requirement

A requirement exists without corresponding evidence.

## 19.2 Orphan Test

A test exists without a clear requirement, risk or assurance purpose.

## 19.3 Orphan Evidence

Evidence exists but its relevance to an assurance claim is unclear.

## 19.4 Orphan Risk

A material risk is identified but no corresponding control or assurance activity exists.

## 19.5 Orphan Authority

Operational permission exists without a clear assurance basis.

## 19.6 Orphan Change

A material change occurs without corresponding reassessment.

## 19.7 Orphan Incident

An incident occurs but does not feed back into risk, assurance or authorisation.

## 19.8 Orphan Accountability

A consequential decision or action cannot be associated with an identifiable authority.

---

# 20. Golden Thread as an Audit Concept

The Golden Thread provides an audit path:

```text
Authorisation
     ↓
Why was it granted?
     ↓
What evidence supported it?
     ↓
What risks were accepted?
     ↓
What controls were required?
     ↓
What requirements did they address?
     ↓
What mission required the capability?
     ↓
Was the capability actually used within authority?
```

The reverse direction should also be possible:

```text
Incident / Outcome
       ↓
What happened?
       ↓
What system behaviour contributed?
       ↓
What control failed?
       ↓
What risk was involved?
       ↓
What evidence had previously supported confidence?
       ↓
Was that evidence still valid?
       ↓
Was authorisation still appropriate?
```

---

# 21. Golden Thread and Continuous Assurance

The Golden Thread is not complete at authorisation.

It continues during operational employment:

```text
Authorisation
      ↓
Employment
      ↓
Monitoring
      ↓
Operational Evidence
      ↓
Assurance Update
      ↓
Risk Update
      ↓
Change / Reauthorisation
```

This creates a living governance chain rather than a static approval record.

---

# 22. Golden Thread and D-AIGAAF Repository Structure

The Golden Thread connects the numbered D-AIGAAF modules.

Conceptually:

```text
00 Framework
      ↓
01 Strategy & Governance
      ↓
02 Mission & Use Case
      ↓
03 Risk & Autonomy
      ↓
04 AI Lifecycle
      ↓
05 Data & Information
      ↓
06 AI Security
      ↓
07 Supply Chain & Sovereignty
      ↓
08 Human Authority
      ↓
09 TEVV
      ↓
10 Operational Environment
      ↓
11 Operational Authorisation
      ↓
12 Operational Employment
      ↓
13 Continuous Assurance
      ↓
14 Incident & Fail-Safe
      ↓
15 Change & Reauthorisation
      ↓
16 Audit & Evidence
      ↓
17–27 Supporting Governance Domains
```

This diagram is conceptual.

The numbered repository structure does **not** mean that modules operate strictly sequentially.

Many modules are cross-cutting and contribute to multiple points in the Golden Thread.

---

# 23. Master Golden Thread

The complete D-AIGAAF logic can be represented as:

```text
                STRATEGIC NEED
                     ↓
                 MISSION NEED
                     ↓
                  USE CASE
                     ↓
          ┌─────── RISK ───────┐
          │                     │
          ↓                     ↓
     REQUIREMENTS            AUTONOMY
          │                     │
          └─────────┬───────────┘
                    ↓
                 CONTROLS
                    ↓
              TEVV / TESTING
                    ↓
                 EVIDENCE
                    ↓
                ASSURANCE
                    ↓
         OPERATIONAL AUTHORITY
                    ↓
              AUTHORISATION
                    ↓
               EMPLOYMENT
                    ↓
                MONITORING
                    ↓
       ┌────────────┴────────────┐
       ↓                         ↓
    INCIDENT                  CHANGE
       │                         │
       └────────────┬────────────┘
                    ↓
              REASSESSMENT
                    ↓
               REVALIDATION
                    ↓
             REAUTHORISATION
                    ↓
              OPERATIONAL USE
                    ↓
                 LEARNING
                    │
                    └────────→ FUTURE REQUIREMENTS
```

---

# 24. The Golden Thread Rule

The central D-AIGAAF rule is:

> **Every consequential operational authority should be traceable backward to a legitimate mission need, defined risk, appropriate requirements, effective controls, relevant evidence and an explicit assurance and authorisation decision.**

And forward:

> **Every significant operational outcome, incident or change should be capable of feeding back into risk, assurance and future authority decisions.**

---

# 25. Golden Thread Summary

The Golden Thread connects five fundamental questions:

### 1. Why?

**Mission Need**

### 2. What could go wrong?

**Risk**

### 3. What have we done about it?

**Requirements + Controls + TEVV**

### 4. Why are we confident enough?

**Evidence + Assurance**

### 5. Why is it allowed?

**Operational Authority**

After deployment, three additional questions become essential:

### 6. What actually happened?

**Operational Employment + Monitoring**

### 7. What changed?

**Incident + Change + Emerging Risk**

### 8. Should authority continue?

**Revalidation + Reauthorisation**

The Golden Thread therefore turns D-AIGAAF from a collection of governance activities into a **traceable system of decision-making**.

---

## Status

**D-AIGAAF Golden Thread v0.1**

Working traceability model for framework development.

The Golden Thread should be refined as individual D-AIGAAF modules, records, templates and crosswalks are developed.
