# Risk & Autonomy Matrix

## Purpose

The D-AIGAAF Risk & Autonomy Matrix provides a structured method for considering the relationship between mission consequence, mission criticality, autonomy, operational environment and human control.

The central principle is:

> **Risk cannot be determined by autonomy alone. The acceptable level of autonomy depends on what the system does, the consequences of failure, where and how it operates, and the effectiveness of human control.**

The matrix is a decision-support construct. It is not intended to create a universal numerical risk score or automatically determine operational authorisation.

---

## 1. Core Relationship

D-AIGAAF uses the following conceptual relationship:

```text
Mission
   +
Use Case
   +
Consequence
   +
Mission Criticality
   +
Autonomy
   +
Environment
   +
Human Control
   +
Threats / Dependencies / Uncertainty
   ↓
Inherent Risk
   ↓
Controls & Constraints
   ↓
Residual Risk
   ↓
Assurance
   ↓
Risk Acceptance
   ↓
Operational Authorisation
```

---

## 2. Purpose of the Matrix

The matrix should help decision-makers:

- identify high-risk combinations;
- determine the appropriate assurance burden;
- identify required autonomy constraints;
- identify human-control requirements;
- compare alternative autonomy levels;
- determine where additional evidence is required;
- support risk treatment;
- inform operational authorisation.

It should not replace detailed risk assessment.

---

## 3. Working Dimensions

D-AIGAAF uses five primary dimensions:

| Dimension | Working Scale |
|---|---|
| Consequence | C1–C5 |
| Mission Criticality | M1–M5 |
| Autonomy | A0–A5 |
| Environment | E1–E5 |
| Human Control | H1–H5 |

These scales are conceptual working constructs and should be calibrated and mapped to applicable organisational, national, defence, legal and doctrinal frameworks before formal adoption.

---

## 4. Consequence Scale

| Level | Description |
|---|---|
| C1 | Minimal consequence |
| C2 | Limited consequence |
| C3 | Significant consequence |
| C4 | Severe consequence |
| C5 | Critical consequence, potentially including loss of life or major strategic effects |

Consequence should consider the worst credible outcome, not only the most likely outcome.

---

## 5. Mission Criticality Scale

| Level | Description |
|---|---|
| M1 | Low mission dependency |
| M2 | Limited mission dependency |
| M3 | Important mission function |
| M4 | High mission dependency |
| M5 | Critical mission function |

Mission criticality reflects how significantly mission success depends on the AI-enabled capability.

A system can have low consequence but high mission criticality, or high consequence but lower mission criticality. The two dimensions should remain separate.

---

## 6. Autonomy Scale

| Level | Description |
|---|---|
| A0 | No Meaningful AI Decision |
| A1 | Information / Observation |
| A2 | Analysis / Recommendation |
| A3 | Human-Authorised Action |
| A4 | Supervised Autonomous Action |
| A5 | Independent Consequential Autonomy |

These levels are D-AIGAAF working constructs.

They should not be interpreted as universal definitions of military autonomy.

---

## 7. Environment Scale

| Level | Description |
|---|---|
| E1 | Stable / Highly Controlled |
| E2 | Moderately Variable |
| E3 | Complex Operational Environment |
| E4 | Degraded / Adversarial Environment |
| E5 | Highly Uncertain / Contested Environment |

The environment scale should consider factors such as:

- terrain;
- weather;
- visibility;
- information availability;
- communications;
- sensor conditions;
- infrastructure;
- adversarial activity;
- uncertainty.

---

## 8. Human Control Scale

| Level | Description |
|---|---|
| H1 | Strong, immediate and effective human control |
| H2 | Effective human control with minor constraints |
| H3 | Conditional or delayed human control |
| H4 | Limited human control |
| H5 | Minimal or ineffective human control |

Human control should be assessed based on actual ability to understand, intervene and exercise authority.

---

## 9. Illustrative Risk Pattern

The following conceptual pattern can be used:

| Consequence | Autonomy | Environment | Human Control | Indicative Concern |
|---|---|---|---|---|
| Low | Low | Stable | Strong | Lower |
| Moderate | Moderate | Variable | Strong | Moderate |
| High | High | Complex | Conditional | High |
| Critical | High | Degraded | Limited | Very High |
| Critical | Independent | Contested | Minimal | Extreme concern |

This is an illustrative pattern, not a formal scoring system.

---

## 10. Why a Single Score Is Insufficient

A single numerical score can conceal important differences.

For example:

```text
High Consequence + Low Autonomy
```

may present a different risk profile from:

```text
Low Consequence + High Autonomy
```

Similarly:

```text
Same Autonomy + Different Environment
```

can produce materially different operational risk.

Therefore D-AIGAAF recommends preserving the individual dimensions rather than collapsing them prematurely into one number.

---

## 11. Consequence × Autonomy

This relationship should receive particular attention.

| | A0–A1 | A2 | A3 | A4 | A5 |
|---|---|---|---|---|---|
| Low consequence | Lower concern | Low–Moderate | Moderate | Moderate | Higher |
| Moderate consequence | Low | Moderate | Moderate–High | High | Very High |
| High consequence | Moderate | High | High | Very High | Critical |
| Critical consequence | High | Very High | Critical | Critical | Extreme concern |

The table is illustrative.

The actual risk position depends on environment, human control, system reliability, security and other factors.

---

## 12. Environment × Autonomy

As environmental uncertainty increases, the assurance burden for a given autonomy level should generally increase.

| | Stable | Variable | Complex | Degraded | Contested |
|---|---|---|---|---|---|
| Low autonomy | Lower | Lower–Moderate | Moderate | Moderate | Higher |
| Medium autonomy | Moderate | Moderate | High | High | Very High |
| High autonomy | Higher | High | Very High | Critical | Extreme concern |

This is not a universal risk rating.

It illustrates why autonomy validated under stable conditions cannot automatically be extended to degraded or contested environments.

---

## 13. Human Control × Autonomy

Human control should generally become more demanding as autonomy and consequence increase.

| Autonomy | Expected Human-Control Requirement |
|---|---|
| A0 | Basic oversight as applicable |
| A1 | Information awareness |
| A2 | Informed human assessment |
| A3 | Effective human authorisation |
| A4 | Effective supervision and intervention |
| A5 | Exceptional assurance and authority scrutiny |

A nominal human presence is not equivalent to meaningful human control.

---

## 14. Consequence × Human Control

Higher consequence combined with weak human control creates particular concern.

For high-consequence systems, the assessment should consider:

- decision time;
- information quality;
- human workload;
- ability to intervene;
- authority;
- system transparency;
- uncertainty communication;
- override reliability.

If meaningful human control cannot be demonstrated, autonomy may need to be reduced or the capability restricted.

---

## 15. Mission Criticality × Autonomy

A highly mission-critical system can create significant systemic risk even if individual outputs appear low consequence.

The assessment should therefore consider:

- dependency on the AI capability;
- availability;
- resilience;
- fallback mechanisms;
- common-mode failures;
- human alternatives;
- cascading mission effects.

High mission criticality should increase resilience and assurance requirements.

---

## 16. Multi-Dimensional Assessment

A complete risk position should be represented as a profile.

For example:

```text
C4 / M4 / A3 / E4 / H2
```

This indicates:

- C4 — severe consequence;
- M4 — high mission criticality;
- A3 — human-authorised action;
- E4 — degraded/adversarial environment;
- H2 — effective human control with minor constraints.

The profile is more informative than a single number.

---

## 17. Risk Bands

D-AIGAAF may use qualitative risk bands:

- Low;
- Moderate;
- High;
- Very High;
- Critical.

These are conceptual categories.

Organisations may define formal thresholds, scoring methods and escalation rules appropriate to their own governance systems.

---

## 18. Risk Treatment Implications

As the risk profile increases, treatment may include:

- reducing autonomy;
- narrowing mission scope;
- narrowing operating environment;
- strengthening human control;
- increasing monitoring;
- improving redundancy;
- strengthening security;
- increasing TEVV;
- restricting deployment;
- requiring higher authority.

The preferred treatment should address the underlying source of risk rather than simply adding documentation.

---

## 19. Autonomy Reduction as Risk Treatment

Reducing autonomy can be an effective risk treatment.

For example:

```text
A4 → A3
```

may introduce explicit human authorisation.

Or:

```text
A3 → A2
```

may move the capability from action to recommendation.

Autonomy reduction should be considered where:

- evidence is insufficient;
- environmental conditions deteriorate;
- human control becomes weaker;
- uncertainty increases;
- critical dependencies fail.

---

## 20. Environmental Restriction as Risk Treatment

Risk may also be reduced by restricting where or when the system operates.

Examples include:

- limiting deployment to validated environments;
- excluding degraded conditions;
- restricting operation during specified conditions;
- requiring additional human supervision.

This may be preferable to unnecessarily reducing the capability across all environments.

---

## 21. Human-Control Strengthening

Where risk is driven by weak human control, treatment may include:

- improved interfaces;
- better information presentation;
- uncertainty indicators;
- reduced workload;
- additional personnel;
- stronger approval gates;
- faster intervention mechanisms;
- improved training.

Human control should be treated as a system property, not simply a staffing assumption.

---

## 22. Matrix and Assurance Burden

The risk profile should inform the assurance burden.

Conceptually:

```text
Higher Consequence
        +
Higher Autonomy
        +
Higher Environmental Uncertainty
        +
Weaker Human Control
        ↓
Greater Evidence Requirement
```

Assurance should therefore be proportional to the operational risk profile.

---

## 23. Matrix and TEVV

The matrix should inform the scope of TEVV.

Higher-risk profiles may require greater emphasis on:

- representative environments;
- degraded conditions;
- adversarial testing;
- human-AI interaction;
- boundary testing;
- fail-safe;
- recovery;
- mission-level evaluation.

TEVV results should feed back into the risk profile.

---

## 24. Matrix and Operational Authorisation

Operational authorisation should consider the complete profile rather than autonomy level alone.

For example:

```text
Capability
× Mission
× Consequence
× Autonomy
× Environment
× Human Authority
× Evidence
```

The authorising authority should determine whether the complete combination is acceptable.

---

## 25. Matrix and Risk Acceptance

Risk acceptance should reference the assessed profile.

Acceptance should specify, where relevant:

- consequence;
- mission criticality;
- autonomy;
- environment;
- human control;
- limitations;
- conditions;
- validity period.

Acceptance should not be interpreted as blanket approval for all autonomy states or environments.

---

## 26. Matrix and Autonomy Boundaries

The matrix can help identify where boundaries should be established.

Examples:

```text
A4 allowed only at E1–E2
A3 allowed at E3
A2 required at E4
Operation suspended at E5
```

These are illustrative only.

Actual thresholds must be established through evidence, risk assessment and authority.

---

## 27. Matrix and Autonomy Transitions

The matrix should inform permitted transitions.

For example:

```text
Normal Conditions → A4
Degraded Conditions → A3
Severe Uncertainty → A2
Critical Control Failure → Safe State
```

Transitions should be pre-defined, tested and authorised where appropriate.

---

## 28. Matrix and Loss of Control

Loss of control may rapidly alter the risk profile.

For example:

```text
H2 → H4
```

may represent a material degradation in human control.

If this occurs during high-consequence autonomy, the system may need to:

- reduce autonomy;
- restrict operation;
- enter a safe state;
- suspend;
- trigger immediate human intervention.

---

## 29. Uncertainty

Uncertainty should be represented explicitly.

Sources may include:

- unknown operating conditions;
- insufficient test evidence;
- uncertain model behaviour;
- incomplete data;
- uncertain dependencies;
- novel adversarial conditions.

High uncertainty should generally increase assurance requirements and may justify narrower autonomy.

---

## 30. Unknown Unknowns

Not all risks can be identified before deployment.

Therefore the matrix should not be treated as proof that all risk has been captured.

Continuous assurance should identify:

- emerging failure modes;
- unexpected behaviour;
- new operating conditions;
- new dependencies;
- new threats;
- previously unrecognised interactions.

New information may require the risk profile to be reassessed.

---

## 31. Risk Profile Example

An illustrative profile might be:

```text
Capability: AI-enabled decision-support system
Mission Criticality: M4
Consequence: C4
Autonomy: A2
Environment: E4
Human Control: H2
```

This could indicate a high assurance burden despite the system being advisory rather than directly autonomous.

The reason is the combination of:

- severe consequence;
- high mission dependency;
- degraded/adversarial environment.

The matrix therefore prevents the assumption that advisory systems are automatically low risk.

---

## 32. Alternative Configuration Comparison

The matrix can compare alternative designs.

### Configuration A

```text
C4 / M4 / A4 / E4 / H3
```

### Configuration B

```text
C4 / M4 / A3 / E4 / H2
```

Configuration B may present a lower-risk profile because it reduces autonomy and strengthens human control.

This does not automatically make B acceptable; evidence and detailed assessment remain necessary.

---

## 33. Matrix Record

A D-AIGAAF Risk & Autonomy Matrix Record should include:

| Field | Description |
|---|---|
| Assessment ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Mission |
| Use Case | Use case |
| Consequence | C1–C5 |
| Mission Criticality | M1–M5 |
| Autonomy | A0–A5 |
| Environment | E1–E5 |
| Human Control | H1–H5 |
| Threats | Relevant threats |
| Dependencies | Critical dependencies |
| Uncertainty | Key uncertainty |
| Inherent Risk | Pre-control position |
| Controls | Risk controls |
| Residual Risk | Post-control position |
| Assurance | Assurance status |
| Conditions | Restrictions |
| Authority | Decision authority |
| Review Trigger | Reassessment triggers |
| Review Date | Review date |
| Status | Current status |

---

## 34. Matrix Review

The risk-autonomy matrix should be reviewed when:

- mission changes;
- use case changes;
- autonomy changes;
- environment changes;
- human-control conditions change;
- system behaviour changes;
- configuration changes;
- threats change;
- dependencies change;
- incidents occur;
- new evidence becomes available.

---

## 35. Matrix Limitations

The matrix does not:

- replace detailed risk assessment;
- replace TEVV;
- replace assurance;
- determine legal permissibility;
- grant operational authority;
- accept residual risk;
- replace command judgement.

It is a structured decision-support mechanism.

---

## 36. Operational AI Advisor

The OAIA may use the matrix to advise on:

- risk-autonomy trade-offs;
- environmental restrictions;
- human-control requirements;
- assurance burden;
- autonomy reduction;
- mission implications.

The OAIA does not independently determine the final risk acceptance or operational authorisation.

**OAIA advises; authorised authority decides.**

---

## 37. Governance Use

The matrix may support:

- capability review;
- acquisition decisions;
- design reviews;
- TEVV planning;
- operational authorisation;
- risk acceptance;
- configuration review;
- incident review;
- change assessment;
- portfolio-level comparison.

---

## 38. Golden Thread

The Risk & Autonomy Matrix should remain traceable through:

**Mission Need → Use Case → Consequence → Mission Criticality → Autonomy → Environment → Human Control → Risk Assessment → Controls → Residual Risk → TEVV → Evidence → Assurance → Risk Acceptance → Operational Authorisation → Employment → Monitoring → Change / Incident → Reassessment**

The record should allow an authorised reviewer to answer:

> **How did the combination of consequence, criticality, autonomy, environment and human control influence the risk, assurance and authority decision?**

---

## 39. Core Rules

1. **Risk cannot be determined by autonomy alone.**
2. **Consequence, mission criticality, autonomy, environment and human control should be assessed separately.**
3. **A single numerical score should not conceal material risk dimensions.**
4. **Higher consequence and autonomy generally require greater assurance.**
5. **Environmental uncertainty can materially change the risk of the same autonomy level.**
6. **Human control must be assessed as an actual capability, not a nominal role.**
7. **The matrix is a decision-support tool, not an authorisation mechanism.**
8. **Autonomy reduction can be used as a risk treatment.**
9. **Environmental and mission restrictions can reduce risk exposure.**
10. **Risk acceptance should reference the specific assessed profile and conditions.**
11. **Authorisation should not exceed the evidence-supported risk and autonomy envelope.**
12. **Unexpected behaviour or changed conditions may invalidate the existing matrix assessment.**
13. **Unknowns and evidence gaps must be explicitly represented.**
14. **The matrix should inform TEVV and assurance requirements.**
15. **The matrix should support, not replace, human professional judgement.**
16. **OAIA advises; authorised authority decides.**

---

## 40. Summary Model

```text
CONSEQUENCE
     +
MISSION CRITICALITY
     +
AUTONOMY
     +
ENVIRONMENT
     +
HUMAN CONTROL
     +
THREATS / DEPENDENCIES / UNCERTAINTY
     ↓
RISK PROFILE
     ↓
RISK TREATMENT
     ↓
RESIDUAL RISK
     ↓
ASSURANCE BURDEN
     ↓
RISK ACCEPTANCE
     ↓
OPERATIONAL AUTHORISATION
     ↓
CONTINUOUS MONITORING
     ↓
REASSESSMENT
```

The objective is to ensure that **autonomy decisions are made in the context of consequence, mission criticality, operating environment and human control rather than treating autonomy as an isolated technical property.**
