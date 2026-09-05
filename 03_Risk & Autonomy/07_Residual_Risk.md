# Residual Risk

## Purpose

The D-AIGAAF Residual Risk framework defines how risk remaining after controls have been implemented and evidenced is assessed, communicated, accepted and monitored.

The central principle is:

> **Residual risk is the risk that remains after applicable controls and treatments have been implemented and their effectiveness has been considered.**

Residual risk is not automatically acceptable because controls exist.

The core chain is:

```text
Inherent Risk
      ↓
Risk Treatment
      ↓
Controls
      ↓
Control Effectiveness
      ↓
Residual Risk
      ↓
Risk Acceptance
      ↓
Assurance
      ↓
Operational Authorisation
      ↓
Continuous Monitoring
```

---

## 1. Definition

For D-AIGAAF:

**Residual Risk** is the remaining risk associated with an AI-enabled capability, mission, use case and operational context after planned risk treatments and controls have been implemented and their demonstrated effectiveness has been considered.

Residual risk may remain because:

- risk cannot be completely eliminated;
- controls have limitations;
- uncertainty remains;
- operational conditions vary;
- human control has limitations;
- dependencies may fail;
- adversaries may adapt;
- evidence may be incomplete;
- some consequences cannot be fully mitigated.

---

## 2. Inherent Risk vs Residual Risk

### Inherent Risk

Risk before considering the effect of controls.

### Residual Risk

Risk after considering implemented controls and their demonstrated effectiveness.

```text
INHERENT RISK
      │
      ├── Preventive Controls
      ├── Detective Controls
      ├── Corrective Controls
      └── Governance Controls
              ↓
      CONTROL EFFECTIVENESS
              ↓
RESIDUAL RISK
```

The distinction should be maintained in risk records.

---

## 3. Residual Risk Is Not Zero Risk

The objective of governance is not necessarily to reduce every risk to zero.

Some risks may remain because:

- the mission itself contains unavoidable risk;
- technical limitations remain;
- information is incomplete;
- the operating environment is uncertain;
- human decisions remain fallible;
- controls introduce trade-offs;
- eliminating the risk would eliminate the mission capability.

The objective is to ensure that remaining risk is:

- understood;
- treated where reasonably practicable;
- supported by evidence;
- within appropriate authority;
- subject to defined conditions;
- continuously monitored.

---

## 4. Dimensions of Residual Risk

Residual risk should be considered across multiple dimensions.

### 4.1 Consequence

Potential severity of the remaining adverse outcome.

Working scale:

- C1 — Minimal
- C2 — Low
- C3 — Significant
- C4 — Severe
- C5 — Critical

### 4.2 Mission Criticality

Importance of the capability to mission success.

Working scale:

- M1 — Limited
- M2 — Supporting
- M3 — Important
- M4 — Critical
- M5 — Mission-Critical

### 4.3 Autonomy

Degree of independent AI decision or action.

Working scale:

- A0 — No Meaningful AI Decision
- A1 — Information / Observation
- A2 — Analysis / Recommendation
- A3 — Human-Authorised Action
- A4 — Supervised Autonomous Action
- A5 — Independent Consequential Autonomy

These scales are D-AIGAAF working constructs and should be mapped to applicable national, defence, legal and doctrinal terminology before formal adoption.

### 4.4 Environment

Degree of operational complexity and degradation.

Working scale:

- E1 — Controlled
- E2 — Managed
- E3 — Operationally Variable
- E4 — Degraded / Adversarial
- E5 — Highly Degraded / Extreme

### 4.5 Human Control

Effectiveness of meaningful human control.

Working scale:

- H1 — Strong
- H2 — Effective
- H3 — Constrained
- H4 — Weak
- H5 — Minimal / Unavailable

Residual risk should consider the interaction among these dimensions rather than treating any single dimension as sufficient.

---

## 5. Residual Risk and Control Effectiveness

Residual risk depends partly on whether controls actually work.

A documented control does not automatically reduce risk.

Evidence should establish, where relevant:

- control exists;
- control operates;
- control operates consistently;
- control works under relevant conditions;
- control remains effective under degradation;
- control does not create unacceptable secondary effects.

Possible control-effectiveness states:

- Effective;
- Effective With Conditions;
- Partially Effective;
- Ineffective;
- Not Assessed;
- Not Applicable.

---

## 6. Residual Risk and Uncertainty

Residual risk should explicitly account for uncertainty.

Uncertainty may arise from:

- incomplete testing;
- limited operational data;
- novel environments;
- unknown failure modes;
- changing threats;
- model opacity;
- incomplete information;
- limited sample sizes;
- changing human behaviour;
- emerging dependencies.

High uncertainty should not be silently converted into low risk.

Possible treatments include:

- additional evidence;
- narrower operational boundaries;
- reduced autonomy;
- increased human control;
- enhanced monitoring;
- additional TEVV;
- restricted employment;
- delayed authorisation.

---

## 7. Residual Risk and Unknowns

Some risks may remain unknown.

D-AIGAAF distinguishes:

**Known Risk**
→ risk has been identified and assessed.

**Known Unknown**
→ uncertainty or limitation has been identified but cannot yet be fully characterised.

**Unknown Risk**
→ risk has not yet been identified.

Unknown risks cannot be assigned a reliable numerical value merely because an assessment process was completed.

This is why continuous assurance and operational learning are required.

---

## 8. Residual Risk and Autonomy

Residual risk generally increases when the system has greater independent decision or action authority, all else being equal.

Higher autonomy may require:

- stronger controls;
- greater assurance;
- more extensive TEVV;
- stronger boundary enforcement;
- more robust fail-safe mechanisms;
- greater resilience;
- stronger human oversight;
- more restrictive operating conditions.

Autonomy should therefore be treated as a material risk variable.

---

## 9. Residual Risk and Human Control

Residual risk should consider whether human control remains effective.

Questions include:

- Can the human understand the AI output?
- Is sufficient information available?
- Is there enough decision time?
- Does the human have authority to intervene?
- Can the human technically intervene?
- Can the human stop or constrain consequential action?
- Is the human sufficiently competent?
- Could automation bias materially affect the decision?
- Is accountability clearly assigned?

If meaningful human control deteriorates, residual risk may increase even when technical performance remains unchanged.

---

## 10. Residual Risk and Operational Environment

Residual risk is context-dependent.

A capability may have acceptable residual risk in one environment and unacceptable residual risk in another.

Relevant conditions include:

- terrain;
- weather;
- visibility;
- altitude;
- electromagnetic conditions;
- communications;
- sensor availability;
- information quality;
- adversarial conditions;
- infrastructure;
- workload;
- mission tempo.

Evidence should support the operational conditions in which the residual risk position is considered valid.

---

## 11. Residual Risk and Information Integrity

Residual risk should include the possibility that information used by the AI or human decision maker is:

- inaccurate;
- incomplete;
- stale;
- manipulated;
- spoofed;
- contradictory;
- unavailable.

Information integrity controls should be reflected in the residual risk position.

A highly accurate model operating on unreliable information may still create unacceptable mission risk.

---

## 12. Residual Risk and Security

Residual security risk may remain after security controls.

Assessment should consider:

- known vulnerabilities;
- threat exposure;
- supply-chain risks;
- dependency risks;
- insider risks;
- adversarial inputs;
- compromised components;
- configuration integrity;
- update mechanisms.

Security risk should be considered alongside mission and operational risk rather than in isolation.

---

## 13. Residual Risk and Dependencies

Residual risk may increase when mission performance depends on:

- communications;
- sensors;
- navigation;
- power;
- computing;
- infrastructure;
- external services;
- suppliers;
- other AI systems;
- human expertise.

Critical dependencies should have:

- identified owners;
- defined failure conditions;
- monitoring;
- fallback options where practicable;
- degraded modes;
- suspension criteria.

---

## 14. Residual Risk and Loss of Control

Loss of control should be explicitly reflected in residual risk.

Relevant questions include:

- What happens if the AI behaves unexpectedly?
- Can autonomy be reduced?
- Can human control be restored?
- Can the system be isolated?
- Can it reach a safe state?
- What happens if communications fail?
- What happens if information becomes unreliable?
- What happens if safeguards fail?
- What happens if the system acts against authorised intent?

Residual risk should reflect the effectiveness of these controls.

---

## 15. Residual Risk Categories

A capability may use a qualitative residual-risk classification such as:

### Low

Remaining risk is limited and supported by adequate controls and evidence.

### Moderate

Remaining risk is material but may be manageable under defined conditions.

### High

Remaining risk is significant and requires stronger controls, restrictions or explicit senior acceptance.

### Critical

Remaining risk may be unacceptable for the intended use without substantial change, additional controls or a different operational concept.

These categories are conceptual. Organisations should define their own thresholds and decision rules.

---

## 16. No Universal Risk Score

D-AIGAAF should not prescribe a universal mathematical risk score without validation.

A single number may hide:

- high consequence;
- high autonomy;
- weak human control;
- severe uncertainty;
- critical dependency;
- adversarial exposure.

A qualitative or multi-dimensional assessment may therefore be more informative.

Where an organisation adopts a numerical method, the method should be:

- documented;
- validated;
- repeatable;
- auditable;
- appropriate to the mission;
- periodically reviewed.

---

## 17. Risk Acceptance

Residual risk should be explicitly accepted by an appropriately empowered authority where acceptance is required.

The acceptance decision should identify:

- residual risk;
- rationale;
- controls;
- evidence;
- limitations;
- operating conditions;
- authority;
- validity period;
- monitoring;
- reassessment triggers.

Risk acceptance should not be delegated merely because a technical team owns the system.

---

## 18. Risk Acceptance Is Not Operational Authorisation

The distinction is fundamental.

**Risk Acceptance**
→ an appropriately empowered authority accepts a defined residual risk.

**Operational Authorisation**
→ an appropriately empowered authority permits the capability to be employed for a defined mission, under defined conditions.

A risk may be accepted while operational employment remains prohibited.

Conversely, operational authorisation should not be granted without an appropriate understanding and disposition of relevant residual risks.

---

## 19. Conditional Risk Acceptance

Residual risk may be accepted only under specified conditions.

Conditions may include:

- restricted mission;
- restricted geography;
- restricted environment;
- restricted autonomy;
- mandatory human approval;
- minimum communications;
- minimum information quality;
- minimum staffing;
- enhanced monitoring;
- additional verification;
- defined suspension triggers.

If conditions are no longer satisfied, the acceptance may no longer remain valid.

---

## 20. Residual Risk Boundaries

Risk acceptance should have clear boundaries.

A residual-risk acceptance should specify:

- capability;
- mission;
- use case;
- environment;
- autonomy;
- human authority;
- configuration;
- dependencies;
- operating period;
- conditions;
- limitations.

Risk accepted for one use case should not automatically be treated as accepted for another.

---

## 21. Residual Risk and Operational Authorisation

Operational authorisation should consider:

```text
Residual Risk
      +
Evidence
      +
Operational Conditions
      +
Human Authority
      +
Assurance
      ↓
Operational Authorisation Decision
```

Operational authorisation should specify the conditions under which the residual risk remains acceptable.

---

## 22. Residual Risk and Assurance

Assurance should determine whether the evidence supports the claimed residual risk position.

The chain is:

**Risk → Controls → Evidence → Assurance → Residual Risk → Authority**

Assurance should challenge:

- whether risks were correctly identified;
- whether controls address them;
- whether controls work;
- whether evidence is representative;
- whether limitations are visible;
- whether uncertainty is understood;
- whether residual risk has been understated.

---

## 23. Residual Risk and Operational AI Advisor

The OAIA may advise on:

- operational meaning of residual risk;
- whether controls are realistic in the operational environment;
- impact of autonomy;
- human-control limitations;
- mission trade-offs;
- environmental limitations;
- operational restrictions;
- implications of uncertainty.

The OAIA should not substitute for the authority legally or organisationally empowered to accept risk.

**OAIA advises; authority decides.**

---

## 24. Residual Risk Monitoring

Residual risk should be monitored for changes in:

- system behaviour;
- mission;
- use case;
- autonomy;
- environment;
- human control;
- information;
- threats;
- dependencies;
- security;
- performance;
- configuration;
- assumptions.

Monitoring should determine whether the residual-risk position remains valid.

---

## 25. Triggers for Residual Risk Reassessment

Reassessment should occur when:

- material incidents occur;
- loss of control occurs;
- model behaviour changes;
- software changes;
- autonomy changes;
- mission changes;
- use case changes;
- operating environment changes;
- threats change;
- dependencies change;
- assumptions are invalidated;
- human-control conditions change;
- control effectiveness declines;
- evidence becomes outdated;
- legal or policy requirements change.

---

## 26. Residual Risk Escalation

A changing residual-risk position may require:

```text
Continue
   ↓
Continue With Conditions
   ↓
Restrict
   ↓
Suspend
   ↓
Revalidate
   ↓
Reauthorise
```

The appropriate response depends on consequence and materiality.

Emergency protective measures may occur immediately where required.

---

## 27. Risk Treatment When Residual Risk Is Unacceptable

If residual risk is not acceptable, possible actions include:

- redesign;
- additional controls;
- improved data;
- additional testing;
- narrower mission;
- narrower operational envelope;
- reduced autonomy;
- stronger human control;
- additional redundancy;
- improved fail-safe;
- improved security;
- alternative technology;
- alternative operating concept;
- suspension;
- non-deployment.

The objective should be to reduce the risk to a position that is legitimately supportable, rather than simply changing its label.

---

## 28. Risk Treatment When Residual Risk Is Uncertain

Where the residual-risk position cannot be reliably established, possible responses include:

- gather additional evidence;
- conduct additional TEVV;
- restrict employment;
- reduce autonomy;
- increase human control;
- narrow the operational envelope;
- increase monitoring;
- defer authorisation.

> **Insufficient evidence should not automatically be treated as acceptable residual risk.**

---

## 29. Residual Risk Record

A D-AIGAAF Residual Risk Record should include:

| Field | Description |
|---|---|
| Risk ID | Unique risk identifier |
| Mission | Supported mission |
| Use Case | Relevant use case |
| Capability | AI-enabled capability |
| Inherent Risk | Risk before treatment |
| Controls | Implemented controls |
| Control Effectiveness | Evidence-based assessment |
| Residual Risk | Remaining risk |
| Consequence | C1–C5 or approved scale |
| Criticality | M1–M5 or approved scale |
| Autonomy | A0–A5 or approved scale |
| Environment | E1–E5 or approved scale |
| Human Control | H1–H5 or approved scale |
| Uncertainty | Known limitations and unknowns |
| Dependencies | Material dependencies |
| Conditions | Conditions attached to acceptance |
| Evidence | Supporting evidence |
| Assurance | Assurance conclusion |
| Acceptance Authority | Appropriate authority |
| Acceptance Date | Decision date |
| Validity | Applicable period |
| Monitoring | Monitoring arrangements |
| Triggers | Reassessment triggers |
| Status | Current status |

---

## 30. Validity Period

Residual-risk acceptance should not be assumed permanent.

Validity should depend on:

- configuration;
- mission;
- environment;
- autonomy;
- evidence currency;
- threat conditions;
- dependency conditions;
- control effectiveness.

A material change may invalidate the previous residual-risk assessment before the nominal review date.

---

## 31. Configuration and Residual Risk

Residual risk is tied to the configuration that was assessed.

Configuration should include, where relevant:

- model version;
- software version;
- hardware;
- sensors;
- data;
- system configuration;
- interfaces;
- dependencies;
- security controls;
- autonomy settings.

A materially changed configuration may require reassessment.

---

## 32. Residual Risk and Change Significance

Change significance should be determined by potential impact on:

- behaviour;
- performance;
- autonomy;
- human control;
- security;
- operational boundaries;
- mission effectiveness;
- consequence.

A change described as “minor” by a supplier or developer should not automatically be treated as minor by the operational authority.

---

## 33. Residual Risk and Incidents

An incident may change the residual-risk position even if the system configuration has not changed.

This can occur because the incident may reveal:

- previously unknown failure modes;
- incorrect assumptions;
- ineffective controls;
- environmental limitations;
- human-control weaknesses;
- dependency weaknesses;
- security weaknesses.

Therefore:

> **Incident evidence can invalidate previous assurance without any software change.**

---

## 34. Residual Risk and Continuous Assurance

Continuous assurance should determine whether:

**The evidence supporting the accepted residual risk remains valid.**

This includes monitoring:

- performance;
- incidents;
- controls;
- assumptions;
- threats;
- environment;
- human factors;
- autonomy;
- dependencies;
- configuration.

Continuous assurance should feed risk reassessment and operational authority.

---

## 35. Failure Modes

D-AIGAAF should guard against:

- treating residual risk as zero because controls exist;
- accepting residual risk without evidence;
- hiding high-risk dimensions inside a single score;
- ignoring uncertainty;
- treating unknown risks as assessed;
- accepting risk beyond delegated authority;
- treating risk acceptance as operational authorisation;
- allowing acceptance to become permanent by default;
- ignoring changing operational conditions;
- ignoring control degradation;
- ignoring incident evidence;
- assuming supplier claims determine residual risk;
- allowing material configuration changes without reassessment;
- assuming previous assurance remains valid indefinitely.

---

## 36. Golden Thread

Residual risk should remain traceable through:

**Mission Need → Use Case → Risk → Treatment → Controls → Testing → Evidence → Control Effectiveness → Residual Risk → Risk Acceptance → Assurance → Operational Authorisation → Employment → Monitoring → Change / Incident → Reassessment**

The record should make it possible to answer:

> **What risk remained, what controls reduced it, what evidence demonstrated their effectiveness, who accepted the remaining risk, and under what conditions?**

---

## 37. Core Rules

1. **Residual risk is the risk remaining after treatment and controls.**
2. **Residual risk is not automatically acceptable because controls exist.**
3. **Control effectiveness should be supported by evidence.**
4. **Residual risk must be assessed in mission and operational context.**
5. **Consequence, autonomy, human control, environment and uncertainty must be considered.**
6. **Unknown risk cannot be made acceptable merely by assigning a score.**
7. **Risk acceptance requires appropriately empowered authority.**
8. **Risk acceptance is not operational authorisation.**
9. **Conditional risk acceptance must have explicit conditions.**
10. **Risk acceptance should have defined validity and reassessment triggers.**
11. **Material changes can invalidate a previous residual-risk position.**
12. **Incidents can invalidate assurance even without configuration changes.**
13. **Continuous monitoring is necessary for consequential AI capabilities.**
14. **Unacceptable residual risk should lead to further treatment, restriction, suspension or non-deployment.**
15. **Operational authority remains with the appropriately empowered human authority.**

---

## 38. Summary Model

```text
INHERENT RISK
      ↓
RISK TREATMENT
      ↓
CONTROLS
      ↓
CONTROL EFFECTIVENESS
      ↓
RESIDUAL RISK
      ↓
IS RESIDUAL RISK ACCEPTABLE?
      │
      ├── NO → FURTHER TREATMENT / RESTRICT / SUSPEND
      │
      └── YES
            ↓
       RISK ACCEPTANCE
            ↓
         ASSURANCE
            ↓
  OPERATIONAL AUTHORISATION
            ↓
        EMPLOYMENT
            ↓
       MONITORING
            ↓
   CHANGE / INCIDENT / NEW RISK
            ↓
        REASSESSMENT
```

The objective is to ensure that **risk remaining after controls is visible, evidence-based, explicitly accepted by appropriate authority, bounded by operational conditions, and continuously reassessed as the capability and its environment change.**
