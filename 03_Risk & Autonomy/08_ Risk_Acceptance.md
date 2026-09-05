# Risk Acceptance

## Purpose

The D-AIGAAF Risk Acceptance framework defines how residual risk is formally considered and accepted by an appropriately empowered authority.

Risk acceptance is a governance decision, not a technical declaration.

The central principle is:

> **Residual risk may be accepted only by an authority with appropriate responsibility, competence and delegated authority, and only within clearly defined conditions.**

The core chain is:

```text
Risk Identified
      ↓
Risk Assessed
      ↓
Risk Treated
      ↓
Controls Implemented
      ↓
Evidence
      ↓
Residual Risk
      ↓
Risk Acceptance Decision
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

**Risk Acceptance** is the explicit decision by an appropriately empowered authority to accept a defined residual risk for a defined capability, mission, use case and operational context, subject to specified conditions and limitations.

Risk acceptance does not mean:

- the risk has been eliminated;
- the system is risk-free;
- the controls are perfect;
- the capability is automatically authorised;
- future risk is automatically accepted.

---

## 2. Risk Acceptance vs Risk Tolerance

These concepts should be distinguished.

### Risk Tolerance

The level and type of risk an organisation is generally prepared to tolerate under its policy and governance framework.

### Risk Acceptance

A specific decision to accept a defined residual risk for a particular capability or situation.

```text
Organisational Risk Tolerance
            ↓
      Specific Risk
            ↓
      Risk Assessment
            ↓
      Residual Risk
            ↓
     Acceptance Decision
```

Risk tolerance does not automatically constitute acceptance of every individual risk.

---

## 3. Risk Acceptance vs Operational Authorisation

This distinction is fundamental.

### Risk Acceptance

Answers:

> **Are we prepared to accept this defined residual risk?**

### Operational Authorisation

Answers:

> **Are we authorised to employ this AI capability for this mission, under these conditions, at this level of autonomy and with this human authority?**

Therefore:

**Risk Acceptance ≠ Operational Authorisation**

A residual risk may be accepted while operational employment remains prohibited.

Operational authorisation should consider the accepted residual risk as one part of a wider decision.

---

## 4. Authority

Risk acceptance must be assigned to an authority appropriate to:

- consequence;
- mission criticality;
- autonomy;
- operational exposure;
- legal/policy requirements;
- organisational delegation.

Authority should not be inferred merely from:

- technical ownership;
- system development responsibility;
- seniority alone;
- supplier status;
- assurance status.

The person accepting risk should have appropriate authority to do so.

---

## 5. Risk Acceptance Hierarchy

A generic decision structure may be:

```text
Identify Risk
      ↓
Determine Risk Owner
      ↓
Assess Delegated Authority
      ↓
Assess Residual Risk
      ↓
Review Evidence and Assurance
      ↓
Determine Acceptance Conditions
      ↓
Accept / Reject / Escalate
```

Where the residual risk exceeds the delegated authority, the decision should be escalated.

---

## 6. Information Required for Acceptance

A meaningful acceptance decision should normally consider:

- mission;
- use case;
- capability;
- operational context;
- consequence;
- mission criticality;
- autonomy;
- human control;
- operational environment;
- threats;
- dependencies;
- assumptions;
- controls;
- control effectiveness;
- residual risk;
- uncertainty;
- known limitations;
- TEVV evidence;
- assurance conclusion;
- operational boundaries;
- fail-safe and degraded modes;
- legal/policy position;
- workforce competence;
- configuration baseline.

The decision maker should not be expected to infer these from technical documentation.

---

## 7. Evidence-Based Acceptance

Risk acceptance should be supported by evidence appropriate to the risk.

Evidence may include:

- test results;
- verification;
- validation;
- evaluation;
- red-team findings;
- operational trials;
- incident history;
- monitoring data;
- control-effectiveness evidence;
- independent assurance.

The burden of evidence should scale with:

- consequence;
- autonomy;
- uncertainty;
- operational exposure;
- human-control limitations.

---

## 8. High-Consequence Risk

Higher-consequence residual risk requires greater scrutiny.

Examples include risks involving:

- death or serious harm;
- independent consequential action;
- critical infrastructure;
- strategic command decisions;
- loss of meaningful human control;
- significant security compromise;
- widespread cascading effects.

The framework does not prescribe a universal approval threshold.

Applicable law, policy, doctrine and organisational delegation determine the final authority.

---

## 9. Conditions of Acceptance

Risk acceptance may be conditional.

Conditions may include:

- restricted mission;
- restricted geography;
- restricted environment;
- restricted autonomy;
- mandatory human approval;
- minimum information quality;
- minimum communications;
- minimum staffing;
- enhanced monitoring;
- additional verification;
- additional TEVV;
- specific configuration;
- specific dependencies;
- defined operating period.

Conditions should be explicit and measurable where practicable.

---

## 10. Acceptance Boundaries

An acceptance decision should identify what it applies to.

At minimum:

**Capability × Mission × Use Case × Environment × Autonomy × Human Authority**

Acceptance for one configuration or use case should not automatically extend to another.

---

## 11. Acceptance of Uncertainty

Some residual uncertainty may be unavoidable.

The decision should explicitly identify:

- known uncertainties;
- unknowns;
- assumptions;
- limitations;
- confidence in evidence;
- potential consequences if assumptions fail.

Uncertainty should not be hidden by assigning a low numerical risk score.

Where uncertainty is material, possible conditions include:

- reduced autonomy;
- narrower operating envelope;
- enhanced monitoring;
- additional human control;
- additional testing;
- restricted deployment;
- time-limited acceptance.

---

## 12. Acceptance of Unknowns

A distinction should be maintained between:

**Known and Assessed Risk**

and

**Unknown or Poorly Characterised Risk**

Unknown risk should not be treated as automatically accepted.

Where significant unknowns exist, the preferred response may be:

- additional investigation;
- additional TEVV;
- restricted employment;
- reduced autonomy;
- increased monitoring;
- deferred acceptance.

---

## 13. Human Control

The acceptance decision should consider whether human control is adequate for the intended use.

Questions include:

- Who has decision authority?
- Who can intervene?
- Is intervention technically possible?
- Is sufficient information available?
- Is sufficient time available?
- Is the human competent?
- Is automation bias addressed?
- Is accountability explicit?
- What happens if communications fail?

Weak human control may materially change the residual-risk position.

---

## 14. Autonomy

Risk acceptance should explicitly identify the autonomy being accepted.

For D-AIGAAF working purposes:

- A0 — No Meaningful AI Decision
- A1 — Information / Observation
- A2 — Analysis / Recommendation
- A3 — Human-Authorised Action
- A4 — Supervised Autonomous Action
- A5 — Independent Consequential Autonomy

These are working constructs and should be mapped to applicable national, defence, legal and doctrinal terminology before formal adoption.

Acceptance of one autonomy level does not automatically authorise a higher level.

> **AI must not self-expand its authority.**

---

## 15. Operational Environment

Acceptance should identify the environment for which the residual risk is considered valid.

Relevant conditions may include:

- terrain;
- weather;
- visibility;
- altitude;
- electromagnetic conditions;
- communications;
- information quality;
- sensor availability;
- infrastructure;
- adversarial conditions;
- mission tempo;
- human workload.

If the capability moves outside its assessed environment, the acceptance position may no longer remain valid.

---

## 16. Dependencies

Risk acceptance should identify material dependencies.

These may include:

- sensors;
- communications;
- navigation;
- power;
- computing;
- data;
- software;
- external services;
- suppliers;
- other AI systems;
- human expertise.

Where a critical dependency fails, the capability should have predefined responses.

---

## 17. Configuration

Risk acceptance should be tied to the configuration assessed.

Relevant configuration information may include:

- model version;
- software version;
- hardware;
- sensors;
- data;
- interfaces;
- autonomy settings;
- security controls;
- critical dependencies.

Material changes may invalidate the acceptance decision.

---

## 18. Acceptance Period

Risk acceptance should have a defined validity period or review mechanism appropriate to the capability.

Validity may depend on:

- configuration stability;
- evidence currency;
- threat conditions;
- operational environment;
- mission;
- autonomy;
- control effectiveness.

Acceptance should not become permanent merely because no one has formally withdrawn it.

---

## 19. Acceptance Conditions and Monitoring

Each condition should have an appropriate monitoring mechanism where practicable.

For example:

| Condition | Monitoring |
|---|---|
| Maximum autonomy | Autonomy configuration monitoring |
| Approved environment | Environment monitoring |
| Human approval required | Decision records |
| Minimum communications | Communications monitoring |
| Data integrity | Integrity checks |
| Specific configuration | Configuration management |
| Enhanced supervision | Operational records |
| Restricted mission | Use-case controls |

Monitoring should provide evidence that acceptance conditions remain satisfied.

---

## 20. Suspension of Acceptance

Acceptance may need to be suspended when:

- conditions are violated;
- material incidents occur;
- control effectiveness declines;
- security is compromised;
- assumptions are invalidated;
- material system behaviour changes;
- operational conditions change;
- evidence becomes unreliable;
- threats materially change.

Suspension of risk acceptance may require corresponding restriction or suspension of operational employment.

---

## 21. Revocation

Risk acceptance may be revoked where:

- residual risk becomes unacceptable;
- authority changes;
- legal/policy conditions change;
- evidence no longer supports the decision;
- material loss of control occurs;
- the mission changes materially;
- the capability is retired.

Revocation should be recorded and communicated to affected authorities.

---

## 22. Emergency Risk Acceptance

Emergency situations may require rapid decisions.

Where applicable governance permits, pre-authorised emergency procedures may establish:

- who may act;
- what actions may be taken;
- under what conditions;
- what limits apply;
- when normal governance must be restored.

Emergency procedures should not create unrestricted authority.

Where immediate protective action is required to prevent unacceptable harm, the designated emergency authority may act within pre-established authority and record the decision afterwards.

---

## 23. Risk Acceptance Record

A D-AIGAAF Risk Acceptance Record should include:

| Field | Description |
|---|---|
| Acceptance ID | Unique identifier |
| Risk ID | Linked risk |
| Mission | Supported mission |
| Use Case | Relevant use case |
| Capability | AI-enabled capability |
| Configuration | Assessed configuration |
| Inherent Risk | Risk before treatment |
| Controls | Implemented controls |
| Residual Risk | Remaining risk |
| Evidence | Supporting evidence |
| Assurance | Assurance conclusion |
| Uncertainty | Known uncertainties and unknowns |
| Limitations | Material limitations |
| Conditions | Acceptance conditions |
| Autonomy | Accepted autonomy |
| Environment | Accepted environment |
| Dependencies | Material dependencies |
| Authority | Accepting authority |
| Authority Basis | Delegation / mandate |
| Decision | Accept / Reject / Escalate |
| Rationale | Decision rationale |
| Effective Date | Start date |
| Review Date | Review date |
| Expiry / Validity | Applicable period |
| Monitoring | Monitoring arrangements |
| Triggers | Reassessment triggers |
| Status | Current status |

---

## 24. Acceptance Decision Outcomes

Possible outcomes include:

### Accepted

Residual risk is accepted within appropriate authority and conditions.

### Conditionally Accepted

Residual risk is accepted only under specified conditions.

### Deferred

Decision requires additional information, evidence or assurance.

### Rejected

Residual risk is not accepted for the proposed use.

### Escalated

Decision exceeds delegated authority and requires higher-level consideration.

### Restricted

Use may continue only within narrower conditions than originally proposed.

---

## 25. Acceptance Rationale

The rationale should be sufficiently clear to explain:

- why the risk exists;
- what treatments were considered;
- why further treatment was or was not pursued;
- what evidence supports the residual-risk position;
- what uncertainty remains;
- why the accepting authority considers the risk acceptable;
- what conditions apply;
- when the decision must be reviewed.

A rationale should be understandable to both technical and operational stakeholders.

---

## 26. Dissent and Challenge

Risk acceptance should allow challenge from:

- assurance;
- TEVV;
- AI security;
- legal/policy;
- operational personnel;
- OAIA;
- system owners;
- other relevant stakeholders.

Dissent should be recorded where material.

The existence of disagreement does not automatically invalidate the acceptance decision, but unresolved material concerns should be visible to the decision maker.

---

## 27. Operational AI Advisor

The OAIA may support the acceptance process by:

- explaining technical limitations;
- translating evidence into operational implications;
- identifying operational assumptions;
- identifying autonomy implications;
- assessing human-control limitations;
- identifying environmental limitations;
- advising on conditions;
- identifying areas requiring additional evidence.

The OAIA should not replace the authority empowered to accept operational risk.

> **OAIA advises; authorised authority decides.**

---

## 28. Relationship to Assurance

Assurance determines whether available evidence supports the claimed risk and control position.

It does not itself accept the risk.

The distinction is:

```text
TEVV
 ↓
Evidence
 ↓
Assurance
 ↓
Residual Risk
 ↓
Risk Acceptance
 ↓
Operational Authorisation
```

An assurance body should not automatically become the operational risk-acceptance authority unless explicitly empowered to perform that function.

---

## 29. Relationship to Operational Authorisation

Risk acceptance is an input to operational authorisation.

Operational authorisation additionally considers:

- mission;
- operational envelope;
- autonomy;
- human authority;
- legal/policy requirements;
- evidence;
- assurance;
- conditions;
- operational readiness.

Therefore:

> **Risk acceptance does not itself grant permission to employ the capability.**

---

## 30. Continuous Review

Risk acceptance should remain under review during operational employment.

Monitoring should consider:

- incidents;
- loss of control;
- performance;
- autonomy;
- human control;
- environment;
- threats;
- dependencies;
- configuration;
- assumptions;
- control effectiveness;
- new evidence.

A change in the underlying risk position may require renewed acceptance.

---

## 31. Reassessment Triggers

Reassessment should be considered when:

- mission changes;
- use case changes;
- consequence changes;
- autonomy changes;
- human-control conditions change;
- environment changes;
- threats change;
- dependencies change;
- model/software changes;
- configuration changes;
- incidents occur;
- assumptions are invalidated;
- controls degrade;
- evidence becomes outdated;
- law or policy changes.

---

## 32. Reacceptance

Where a material change affects residual risk, a new acceptance decision may be required.

The process may be:

```text
Material Change
      ↓
Risk Reassessment
      ↓
Control Review
      ↓
Evidence / TEVV
      ↓
Assurance
      ↓
Residual Risk
      ↓
Reacceptance
      ↓
Reauthorisation if Required
```

Previous acceptance should not be assumed to survive a material change.

---

## 33. Failure Modes

D-AIGAAF should guard against:

- accepting risk without adequate evidence;
- accepting risk beyond delegated authority;
- confusing acceptance with authorisation;
- accepting unknown risk as low risk;
- allowing acceptance to become indefinite;
- failing to define conditions;
- failing to monitor conditions;
- allowing technical owners to accept operational risk without authority;
- treating supplier acceptance as organisational acceptance;
- ignoring assurance dissent;
- ignoring human-control weaknesses;
- accepting risk for one use case and applying it to another;
- allowing emergency acceptance to become normal practice;
- failing to reassess after incidents;
- assuming previous acceptance survives material change.

---

## 34. Golden Thread

Risk acceptance should remain traceable through:

**Mission Need → Use Case → Risk → Treatment → Controls → Testing → Evidence → Assurance → Residual Risk → Risk Acceptance → Operational Authorisation → Employment → Monitoring → Change / Incident → Reassessment → Reacceptance / Reauthorisation**

The record should make it possible to answer:

> **What residual risk was accepted, by whom, on what evidence, under what conditions, for which mission and configuration, and when must the decision be reconsidered?**

---

## 35. Core Rules

1. **Risk acceptance is a deliberate governance decision.**
2. **Only appropriately empowered authority may accept material residual risk.**
3. **Risk acceptance must be based on an understood residual-risk position.**
4. **Evidence should support the claimed control effectiveness and residual risk.**
5. **Acceptance must consider mission, context, autonomy and human control.**
6. **Uncertainty and unknowns must be visible to the decision maker.**
7. **Risk acceptance should have explicit conditions and boundaries.**
8. **Risk acceptance is not operational authorisation.**
9. **Acceptance should have a defined validity or review mechanism.**
10. **Material changes may invalidate previous acceptance.**
11. **Incidents may require reassessment even without configuration changes.**
12. **Acceptance conditions should be monitored where practicable.**
13. **Emergency authority should be predefined wherever practicable.**
14. **Emergency procedures should not become a routine bypass of governance.**
15. **Operational accountability remains with the appropriately empowered authority.**
16. **OAIA advises; authorised authority decides.**

---

## 36. Summary Model

```text
IDENTIFY RISK
      ↓
ASSESS INHERENT RISK
      ↓
TREAT RISK
      ↓
IMPLEMENT CONTROLS
      ↓
GENERATE EVIDENCE
      ↓
ASSESS RESIDUAL RISK
      ↓
IS AUTHORITY APPROPRIATE?
      │
      ├── NO → ESCALATE
      │
      └── YES
            ↓
      ACCEPT / REJECT / DEFER
            ↓
      DEFINE CONDITIONS
            ↓
          ASSURANCE
            ↓
   OPERATIONAL AUTHORISATION
            ↓
        EMPLOYMENT
            ↓
        MONITORING
            ↓
    CHANGE / INCIDENT
            ↓
       REASSESSMENT
            ↓
 REACCEPT / REAUTHORISE / RESTRICT / SUSPEND
```

The objective is to ensure that **no consequential residual risk is accepted by default, by assumption or by technical ownership; acceptance is explicit, evidence-informed, bounded, reviewable and exercised only by appropriately empowered human authority.**
