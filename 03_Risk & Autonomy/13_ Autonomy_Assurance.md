# Autonomy Assurance

## Purpose

The D-AIGAAF Autonomy Assurance framework establishes the evidence, testing and evaluation required to demonstrate that an AI-enabled capability can operate within its defined and authorised autonomy boundaries.

The central principle is:

> **Autonomy should not be authorised because a system appears capable of autonomous operation. It should be authorised only when sufficient evidence demonstrates that the claimed autonomy is reliable, controllable, bounded and appropriate for the intended mission and environment.**

---

## 1. Core Assurance Model

```text
Technical Capability
        ↓
Actual Behaviour
        ↓
Autonomy Assessment
        ↓
Defined Boundaries
        ↓
Constraints & Controls
        ↓
Testing & Evaluation
        ↓
Evidence
        ↓
Assurance Judgment
        ↓
Risk Acceptance
        ↓
Operational Authorisation
        ↓
Continuous Assurance
```

Assurance is therefore an evidence-based judgement, not merely a certification statement.

---

## 2. Definition

Autonomy assurance is the structured process of determining whether evidence supports the safe, reliable and authorised use of a specified level of AI autonomy within a defined operational envelope.

It addresses:

- what the system can actually do;
- what autonomy it demonstrates;
- under what conditions it performs;
- what limitations exist;
- whether human control remains effective;
- whether boundaries are enforced;
- whether failure and degradation behaviour is acceptable;
- whether evidence remains valid.

---

## 3. What Assurance Must Demonstrate

Assurance should establish, to an appropriate level of confidence, that:

1. the claimed autonomy is technically real;
2. the observed behaviour is sufficiently understood;
3. the autonomy boundary is defined;
4. constraints operate as intended;
5. human control is effective where required;
6. failure modes are identified;
7. degraded behaviour is understood;
8. the system performs within the intended environment;
9. evidence supports the stated risk position;
10. operational authority is limited to the assured envelope.

---

## 4. Capability, Performance and Authority

Three concepts must remain separate:

**Capability** — what the system can technically do.

**Performance** — how well it performs under specified conditions.

**Authority** — what the system is permitted to do operationally.

Therefore:

```text
Capability ≠ Performance
Performance ≠ Authority
Capability ≠ Authority
```

Assurance connects evidence about capability and performance to an informed authority decision.

---

## 5. Actual vs Intended Autonomy

Assurance should consider:

- intended autonomy;
- configured autonomy;
- demonstrated autonomy;
- effective autonomy;
- authorised autonomy.

The most important distinction is:

> **A system must be assessed according to what it can actually do, not only what developers or operators intend it to do.**

Unexpected capabilities or behaviours must be considered.

---

## 6. Assurance Scope

Assurance should cover the complete AI-enabled capability where relevant, including:

- model;
- software;
- hardware;
- sensors;
- data;
- interfaces;
- communications;
- computing;
- human operators;
- supporting infrastructure;
- external dependencies;
- security controls;
- operational procedures.

Model-level assurance alone may be insufficient for mission-level autonomy.

---

## 7. Assurance Dimensions

D-AIGAAF autonomy assurance should consider at least:

### 7.1 Decision Behaviour

Can the system produce decisions or recommendations consistently within the intended scope?

### 7.2 Action Behaviour

Does the system execute only authorised actions?

### 7.3 Boundary Compliance

Does it remain within defined autonomy boundaries?

### 7.4 Human Control

Can authorised humans understand, supervise and intervene where required?

### 7.5 Reliability

Does the system maintain expected behaviour over relevant operating conditions?

### 7.6 Robustness

Does performance remain acceptable under variation and degradation?

### 7.7 Adversarial Resilience

Does the system remain within its authorised envelope when exposed to adversarial conditions?

### 7.8 Environmental Performance

Does autonomy remain valid across the intended operational environment?

### 7.9 Information Integrity

Does the system appropriately handle uncertain, incomplete, conflicting or manipulated information?

### 7.10 Security and Integrity

Can unauthorised actors or components modify system behaviour or authority?

### 7.11 Recovery

Does the system move to an appropriate state following failure or abnormal conditions?

### 7.12 Mission Effectiveness

Does the capability achieve its intended operational purpose without unacceptable risk?

---

## 8. Consequence-Proportionate Assurance

Assurance effort should increase with:

- consequence;
- autonomy;
- mission criticality;
- environmental uncertainty;
- system complexity;
- human-control difficulty;
- security exposure;
- dependency risk;
- uncertainty.

Conceptually:

```text
Higher Consequence
        +
Higher Autonomy
        +
Higher Uncertainty
        ↓
Greater Assurance Burden
```

There should be no assumption that every AI capability requires identical assurance.

---

## 9. Progressive Assurance

Evidence should mature progressively:

```text
Laboratory
   ↓
Controlled Environment
   ↓
Representative Environment
   ↓
Adversarial / Red-Team
   ↓
Operational Environment
   ↓
Mission-Level Evaluation
   ↓
Assurance
   ↓
Operational Authorisation
```

Passing one stage does not automatically establish suitability for the next.

---

## 10. Laboratory Evidence

Laboratory testing can establish:

- functional behaviour;
- basic performance;
- repeatability;
- known failure conditions;
- baseline system behaviour;
- initial boundary compliance.

Laboratory evidence is necessary but may not be sufficient for operational autonomy.

---

## 11. Controlled Environment

Controlled testing should introduce realistic but manageable conditions.

It may examine:

- operational workflows;
- human interaction;
- representative data;
- system integration;
- expected environmental variation;
- communications conditions.

---

## 12. Representative Environment

Testing should progressively approximate the intended operational environment.

Relevant factors may include:

- terrain;
- weather;
- visibility;
- altitude;
- infrastructure;
- sensor conditions;
- communications;
- information availability;
- workload.

---

## 13. Adversarial and Red-Team Assurance

Autonomy assurance should consider deliberate attempts to cause:

- incorrect decisions;
- unsafe actions;
- boundary violations;
- unexpected autonomy escalation;
- loss of human control;
- manipulation of information;
- exploitation of dependencies;
- security compromise.

Red-team activity should test both the AI and the surrounding system.

---

## 14. Operational Environment Assurance

A system should demonstrate relevant performance under the environments in which it is intended to operate.

The framework should not assume that success in one environment establishes performance in another.

Where operational environments differ materially, separate evidence may be required.

---

## 15. Mission-Level Evaluation

Mission-level evaluation should determine whether:

- the capability supports the intended mission;
- human decision-making remains effective;
- autonomy creates acceptable operational effects;
- system limitations are understood;
- the capability remains within authorised boundaries;
- residual risk remains acceptable.

Mission effectiveness should not be inferred solely from technical benchmark performance.

---

## 16. Human-Autonomy Assurance

Assurance should evaluate the complete human-AI decision chain:

```text
Operational Situation
        ↓
Information / Sensors
        ↓
AI Processing
        ↓
AI Output / Recommendation
        ↓
Human Assessment
        ↓
Human Decision
        ↓
Authorised Action
        ↓
Operational Effect
        ↓
Review / Feedback
```

The assessment should consider:

- comprehension;
- workload;
- decision time;
- automation bias;
- trust;
- uncertainty communication;
- intervention;
- override;
- accountability.

---

## 17. Uncertainty Assurance

AI should communicate meaningful uncertainty where uncertainty is material to a decision.

Assurance should test whether:

- uncertainty is represented appropriately;
- confidence is calibrated where applicable;
- low-confidence cases are detectable;
- conflicting information is surfaced;
- the system avoids presenting unsupported conclusions as facts.

A system that produces confident but unreliable outputs may require restricted autonomy.

---

## 18. Boundary Assurance

Assurance should establish that:

- mission boundaries work;
- action boundaries work;
- environmental boundaries work;
- geographic restrictions work where relevant;
- temporal limits work;
- data restrictions work;
- authority restrictions work;
- escalation restrictions work;
- recovery boundaries work.

Boundary assurance should include attempts to exceed the authorised envelope.

---

## 19. Constraint Assurance

Critical autonomy constraints should be tested for:

- correctness;
- reliability;
- independence where appropriate;
- failure detection;
- override;
- degradation;
- recovery.

The evidence should demonstrate that controls actually constrain behaviour.

---

## 20. Autonomy Transition Assurance

Where the system can transition between autonomy states, assurance should evaluate:

- transition triggers;
- transition thresholds;
- upward transitions;
- downward transitions;
- protective transitions;
- human-directed transitions;
- communications-loss transitions;
- recovery transitions;
- emergency transitions.

Unexpected transitions should be treated as assurance findings.

---

## 21. Fail-Safe Assurance

Fail-safe behaviour should be tested under realistic failure conditions.

Testing should establish:

- trigger reliability;
- safe-state behaviour;
- remaining permissions;
- human notification;
- intervention;
- recovery;
- evidence preservation.

Fail-safe should be treated as a last-resort protective mechanism.

---

## 22. Communications-Loss Assurance

Where autonomy may continue without communications, assurance should establish:

- what functions remain available;
- what authority remains;
- how long autonomous operation may continue;
- how uncertainty is handled;
- whether autonomy is reduced;
- whether a safe state is reached;
- how human control is restored.

Communications loss should be treated as an explicit operational condition rather than an exceptional assumption.

---

## 23. Information-Degradation Assurance

Testing should include:

- missing information;
- stale information;
- conflicting information;
- sensor disagreement;
- corrupted information;
- reduced information availability.

The objective is to determine whether autonomy remains appropriate as information quality changes.

---

## 24. Adversarial Autonomy Assurance

Testing should consider whether an AI system can:

- manipulate its own operating conditions;
- exploit permissions;
- circumvent constraints;
- generate unexpected actions;
- maintain operation after authority is withdrawn;
- interfere with monitoring;
- behave differently under adversarial inputs.

The objective is not only to test external compromise but also to identify unsafe autonomous behaviour.

---

## 25. Security and Integrity Assurance

Assurance should consider whether:

- model integrity is protected;
- software integrity is protected;
- data integrity is protected;
- configuration integrity is protected;
- dependencies are controlled;
- interfaces are secured;
- updates are controlled;
- unauthorised privilege escalation is prevented.

Security failures that can alter autonomy should be treated as autonomy-assurance issues.

---

## 26. Supply-Chain Assurance

Where third-party components materially affect autonomy, assurance should consider:

- provenance;
- supplier identity;
- component dependencies;
- update mechanisms;
- software supply chain;
- model supply chain;
- integrity controls;
- change notification.

The objective is to understand who can potentially modify behaviour and through which dependencies.

---

## 27. Evidence Quality

Evidence should be assessed for:

- relevance;
- validity;
- reliability;
- repeatability;
- traceability;
- independence;
- recency;
- coverage;
- limitations.

Evidence should directly support the claim being made.

---

## 28. Evidence Gaps

Assurance should explicitly identify:

- untested conditions;
- unknown behaviours;
- insufficient sample sizes;
- missing environmental evidence;
- unresolved failure modes;
- uncertain dependencies;
- human-control gaps;
- security gaps.

An evidence gap should not automatically be treated as evidence of safety.

---

## 29. Evidence Confidence

Assurance conclusions should communicate the strength of the evidence.

Possible categories include:

- High Confidence;
- Moderate Confidence;
- Limited Confidence;
- Insufficient Evidence;
- Not Assessable.

These are qualitative constructs and should not be treated as universal numerical scores.

---

## 30. Assurance Findings

Findings may include:

- Compliant;
- Partially Compliant;
- Non-Compliant;
- Evidence Gap;
- Limitation;
- Conditional Assurance;
- Critical Finding.

Findings should be linked to the relevant risk and authorisation decision.

---

## 31. Assurance Conditions

Autonomy may be assured only under specified conditions.

Conditions may include:

- specific environment;
- defined mission;
- defined autonomy level;
- human supervision;
- communications requirements;
- sensor availability;
- data quality;
- configuration baseline;
- monitoring;
- operating duration.

Conditional assurance should clearly state what invalidates the assurance position.

---

## 32. Assurance Limitations

Every assurance conclusion should identify material limitations.

Examples include:

- untested environment;
- uncertain data;
- limited adversarial testing;
- insufficient operational exposure;
- unresolved human factors;
- dependency uncertainty;
- limited evidence for degraded conditions.

Limitations should feed directly into operational restrictions where appropriate.

---

## 33. Assurance Independence

Where practicable, critical assurance activities should include appropriate independence from the development or operational team.

The required degree of independence should be proportionate to:

- consequence;
- autonomy;
- complexity;
- conflict of interest;
- operational significance.

---

## 34. Assurance Review

Assurance should be reviewed when:

- system behaviour changes;
- autonomy changes;
- mission changes;
- environment changes;
- dependencies change;
- threats change;
- significant incidents occur;
- new evidence emerges;
- previous assumptions become invalid.

Assurance is not necessarily permanent.

---

## 35. Continuous Assurance

After operational authorisation, evidence should continue to be collected.

Sources may include:

- operational logs;
- performance monitoring;
- incidents;
- user feedback;
- commander observations;
- maintenance;
- security monitoring;
- red-team results;
- TEVV;
- configuration records;
- supplier notifications.

Operational evidence should feed the assurance position.

---

## 36. Assurance and Operational Authorisation

Assurance provides evidence and an assurance judgement.

Operational authority decides whether the capability may be employed.

Therefore:

**Assurance ≠ Operational Authorisation**

The relationship is:

**Evidence → Assurance → Risk Acceptance → Operational Authorisation**

---

## 37. Assurance and Risk Acceptance

Assurance should inform whether residual risk is understood and adequately controlled.

However, assurance does not itself accept risk.

**Assurance advises; authorised authority accepts risk and decides employment.**

---

## 38. Assurance and Autonomy Boundaries

The authorised autonomy boundary should not exceed the boundary supported by evidence.

Conceptually:

```text
Technical Capability
        ↓
Demonstrated Capability
        ↓
Assured Capability
        ↓
Authorised Capability
```

If evidence supports only A3, A4 should not be authorised merely because the system is technically capable of A4.

---

## 39. Operational AI Advisor

The OAIA may:

- interpret operational implications of evidence;
- identify assurance gaps;
- advise on mission suitability;
- assess human-control implications;
- advise on operational restrictions;
- advise command authority on residual uncertainty.

The OAIA does not replace the assurance function or command authority.

**OAIA advises; authorised authority decides.**

---

## 40. Assurance Record

A D-AIGAAF Autonomy Assurance Record should include:

| Field | Description |
|---|---|
| Assurance ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Supported mission |
| Use Case | Relevant use case |
| Configuration | Assessed baseline |
| Autonomy Level | Assessed autonomy |
| Environment | Assessed environment |
| Human Control | Human-control position |
| Boundaries | Applicable autonomy boundaries |
| Constraints | Critical constraints |
| Test Scope | Testing performed |
| Evaluation Scope | Evaluation performed |
| Evidence | Supporting evidence |
| Findings | Key findings |
| Limitations | Evidence limitations |
| Residual Risk | Relevant risk position |
| Assurance Conclusion | Overall judgement |
| Conditions | Conditions of assurance |
| Validity | Assurance validity |
| Review Trigger | Reassessment triggers |
| Authority | Responsible assurance authority |
| Status | Current status |

---

## 41. Assurance Status

Possible statuses include:

- **Under Assessment**
- **Evidence Developing**
- **Conditionally Assured**
- **Assured**
- **Restricted Assurance**
- **Assurance Expired**
- **Assurance Suspended**
- **Assurance Withdrawn**
- **Not Assured**

---

## 42. Revalidation and Reauthorisation

Revalidation should be considered when:

- model behaviour changes;
- software changes materially;
- autonomy changes;
- constraints change;
- environment expands;
- mission changes;
- human-control assumptions change;
- security conditions change;
- critical dependencies change;
- incidents invalidate previous evidence.

The governing sequence is:

**Change → Risk Assessment → TEVV → Revalidation → Assurance → Risk Acceptance → Reauthorisation**

---

## 43. Assurance Failure

Assurance may fail when:

- evidence is insufficient;
- behaviour is not reproducible;
- boundaries cannot be demonstrated;
- human control is ineffective;
- critical failure modes remain unresolved;
- operational conditions exceed evidence;
- security integrity is uncertain;
- monitoring cannot detect material changes.

Possible outcomes include:

- restricted autonomy;
- additional controls;
- additional testing;
- suspension;
- non-authorisation.

---

## 44. Golden Thread

Autonomy assurance should remain traceable through:

**Mission Need → Use Case → Risk → Autonomy Assessment → Human Control → Boundaries → Constraints → TEVV → Evidence → Assurance → Risk Acceptance → Operational Authorisation → Employment → Monitoring → Change / Incident → Revalidation → Reauthorisation**

The record should allow an authorised reviewer to answer:

> **What evidence demonstrates that this level of autonomy is reliable, bounded, controllable and appropriate for this mission and environment?**

---

## 45. Core Rules

1. **Autonomy must be evidence-based, not assumption-based.**
2. **Technical capability does not establish operational suitability.**
3. **Operational authorisation must not exceed the assured envelope.**
4. **Assurance should be proportionate to consequence, autonomy and uncertainty.**
5. **Model-level testing alone may not establish mission-level assurance.**
6. **Human-AI interaction must be part of autonomy assurance.**
7. **Environmental and degraded-condition performance must be assessed where relevant.**
8. **Boundary and constraint enforcement must be demonstrated.**
9. **Fail-safe and recovery behaviour must be tested.**
10. **Adversarial conditions should be included for consequential autonomy.**
11. **Evidence gaps must be explicitly recorded.**
12. **Assurance conclusions must state limitations and conditions.**
13. **Assurance is not the same as risk acceptance or operational authorisation.**
14. **Operational evidence should feed continuous assurance.**
15. **Material changes may invalidate previous assurance.**
16. **Incidents may invalidate assurance even without configuration changes.**
17. **OAIA advises; authorised authority decides.**
18. **No autonomy level should be authorised beyond what the evidence supports.**

---

## 46. Summary Model

```text
CLAIMED AUTONOMY
        ↓
ACTUAL BEHAVIOUR
        ↓
AUTONOMY ASSESSMENT
        ↓
BOUNDARIES & CONSTRAINTS
        ↓
PROGRESSIVE TEVV
        ↓
EVIDENCE
        ↓
ASSURANCE JUDGEMENT
        ↓
RESIDUAL RISK
        ↓
RISK ACCEPTANCE
        ↓
OPERATIONAL AUTHORISATION
        ↓
OPERATIONAL EMPLOYMENT
        ↓
CONTINUOUS EVIDENCE
        ↓
REVALIDATION
        ↓
REAUTHORISATION / RESTRICTION / SUSPENSION
```

The objective is to ensure that **AI autonomy is authorised only to the extent that evidence demonstrates the capability is sufficiently reliable, bounded, controllable and appropriate for its intended operational context.**
