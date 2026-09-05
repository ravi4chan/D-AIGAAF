# AI Threat Model

## 1. Purpose

This document defines the threat-modelling approach for defence AI capabilities within D-AIGAAF.

The objective is to identify credible threats to AI systems, understand how those threats could affect mission outcomes, and ensure that appropriate controls, testing, monitoring, and operational constraints are established before and during authorised use.

## 2. Core Principle

> **AI security must be assessed against how an adversary, malicious insider, compromised dependency, environmental condition, or unintended interaction could cause the AI capability to behave outside its authorised purpose or create unacceptable consequences.**

Threat modelling should therefore extend beyond conventional infrastructure vulnerabilities to include data, models, interfaces, human interaction, autonomy, supply chain, and operational context.

## 3. Scope

Threat modelling should consider:

- AI models;
- training and operational data;
- software and infrastructure;
- sensors and inputs;
- interfaces and APIs;
- communications;
- configurations;
- update mechanisms;
- supply-chain dependencies;
- human users and administrators;
- autonomous functions;
- monitoring and assurance systems;
- operational environments.

## 4. Threat-Modelling Objectives

The threat model should establish:

1. What must be protected?
2. Who or what could threaten it?
3. How could the threat act?
4. Which vulnerabilities or dependencies could be exploited?
5. What could happen if the threat succeeds?
6. What controls reduce the likelihood or consequence?
7. How would compromise or manipulation be detected?
8. What would happen if controls failed?
9. What operational authority or restrictions are required?

## 5. Threat-Modelling Chain

A general D-AIGAAF relationship is:

**Asset → Threat Actor / Hazard → Attack or Failure Path → Vulnerability / Exposure → AI Effect → Mission Effect → Consequence → Control → Assurance**

The threat model should connect technical events to operational consequences.

## 6. Threat Sources

Potential threat sources include:

- external adversaries;
- malicious insiders;
- compromised users or administrators;
- compromised suppliers;
- compromised software or hardware;
- compromised data sources;
- hostile or deceptive information;
- automated attacks;
- accidental human actions;
- configuration errors;
- unintended system interactions;
- environmental conditions.

Not every threat source applies to every AI capability.

## 7. Threat Actor Categories

A working categorisation may include:

- **External Adversary** — actor outside the authorised system boundary.
- **Insider** — authorised individual misusing access.
- **Compromised Account** — legitimate account controlled by an unauthorised party.
- **Compromised Dependency** — trusted component or supplier that has been compromised.
- **Malicious Data Source** — source intentionally providing deceptive or manipulated information.
- **Accidental Actor** — user or administrator causing unintended security impact.
- **Unintended System Behaviour** — behaviour arising without deliberate human attack.

These categories are analytical constructs and should be adapted to organisational threat terminology.

## 8. Critical Assets

Threat modelling should identify assets whose compromise could affect mission outcomes.

Examples include:

- model weights;
- model configuration;
- training datasets;
- operational data;
- labels;
- system instructions;
- safety controls;
- autonomy settings;
- decision thresholds;
- authentication mechanisms;
- privileged accounts;
- interfaces;
- update mechanisms;
- logs;
- assurance evidence;
- operational authorisation records.

## 9. Security Properties

Threat modelling should assess threats to:

- confidentiality;
- integrity;
- availability;
- authenticity;
- traceability;
- behavioural integrity;
- safety controls;
- operational boundaries.

For AI systems, integrity and behavioural integrity may be particularly important where unauthorised changes could produce consequential outputs or actions.

## 10. AI-Specific Threat Categories

The threat model should consider, where relevant:

- data poisoning;
- adversarial inputs;
- model manipulation;
- model theft;
- prompt or instruction manipulation;
- malicious fine-tuning;
- compromised pretrained models;
- supply-chain compromise;
- malicious dependencies;
- unauthorised model updates;
- configuration manipulation;
- output manipulation;
- interface abuse;
- excessive permissions;
- monitoring evasion;
- denial of service;
- data leakage.

The relevant threat categories should be selected according to the architecture and mission.

## 11. Data Threats

Potential data threats include:

- unauthorised modification;
- poisoned training data;
- manipulated operational inputs;
- incorrect labels;
- forged data;
- compromised sources;
- corrupted metadata;
- loss of provenance;
- unauthorised disclosure;
- deliberate distribution manipulation.

Data threats should connect with the controls defined in **05 Data & Information**.

## 12. Model Threats

Potential model threats include:

- unauthorised replacement;
- model-weight modification;
- malicious fine-tuning;
- compromised model provenance;
- hidden behavioural changes;
- malicious model insertion;
- extraction or theft;
- manipulation of safety-related behaviour.

Model integrity should be assessed relative to the approved configuration baseline.

## 13. Software and Infrastructure Threats

Potential threats include:

- vulnerable software;
- compromised libraries;
- malicious code;
- compromised infrastructure;
- privilege escalation;
- unauthorised configuration changes;
- compromised build environments;
- malicious updates;
- resource exhaustion.

AI-specific assurance should complement, rather than replace, conventional cyber-security controls.

## 14. Interface and Input Threats

Interfaces can create pathways for unintended or malicious behaviour.

Threat modelling should consider:

- unauthorised inputs;
- malformed inputs;
- malicious commands;
- deceptive inputs;
- API abuse;
- interface compromise;
- excessive permissions;
- unauthorised output routing;
- manipulation of context or instructions.

Where an interface can influence consequential AI behaviour, it should be treated as a critical security boundary.

## 15. Supply-Chain Threats

Supply-chain threat modelling should consider:

- unknown model origin;
- compromised pretrained models;
- malicious software dependencies;
- compromised hardware;
- supplier compromise;
- unauthorised supplier access;
- compromised update mechanisms;
- hidden external services;
- uncontrolled third-party data.

Critical dependencies should be identified before operational authorisation.

## 16. Human Threats

Humans may create or amplify AI security risks through:

- excessive privileges;
- credential compromise;
- intentional misuse;
- accidental configuration changes;
- bypassing security controls;
- accepting manipulated AI outputs;
- disabling monitoring;
- introducing unapproved data or models.

Threat modelling should therefore include the interaction between technical controls and human authority.

## 17. Autonomy and Threat Consequence

The potential consequence of compromise generally increases as AI autonomy increases.

A working relationship is:

**Threat Severity × Consequence × Autonomy × AI Dependence**

Higher values should drive stronger controls and assurance.

An advisory AI system and an AI system authorised to perform consequential actions should not automatically receive the same threat tolerance.

## 18. Threats to Human Control

Threat modelling should specifically consider whether an attack or failure could:

- bypass human review;
- manipulate human decision-makers;
- conceal relevant uncertainty;
- generate misleading confidence;
- prevent authorised intervention;
- trigger unauthorised actions;
- interfere with suspension or fail-safe mechanisms.

Human oversight should be treated as a security-relevant control rather than assumed to be infallible.

## 19. Threats to Operational Boundaries

The threat model should assess whether the AI capability could be caused to:

- operate outside its authorised mission;
- access unauthorised data;
- interact with unauthorised systems;
- exceed authorised autonomy;
- perform unauthorised functions;
- continue operating after required suspension;
- bypass environmental restrictions.

Protection of the operational boundary is a core AI security objective.

## 20. Threats in Degraded Environments

Threat modelling should consider:

- communications loss;
- delayed communications;
- unavailable external services;
- sensor degradation;
- incomplete data;
- infrastructure degradation;
- isolated operation.

The threat model should identify whether degraded conditions could unintentionally expand risk or reduce human control.

## 21. Threat Scenarios

Threat modelling should use concrete scenarios rather than relying only on abstract threat lists.

A scenario should identify:

**Actor / Hazard → Entry Point → Action → AI Effect → Human Effect → Operational Effect → Consequence**

Scenarios should cover both malicious attacks and credible unintended events.

## 22. Threat Severity

A working threat severity model may consider:

- likelihood;
- consequence;
- exploitability;
- exposure;
- detectability;
- recoverability;
- autonomy;
- mission criticality.

A simple conceptual relationship is:

**Threat Severity = Likelihood × Consequence × Exposure × Exploitability**

This is a working D-AIGAAF construct and should be adapted to established organisational risk methodology.

## 23. Threat Treatment

Threat treatment options include:

- eliminate;
- reduce;
- isolate;
- detect;
- deter;
- constrain;
- transfer where appropriate;
- accept residual risk;
- prohibit the capability or use case.

Treatment should be linked to operational consequences.

## 24. Threat Controls

Controls may include:

- identity and access controls;
- data integrity controls;
- model integrity controls;
- network and interface controls;
- sandboxing or isolation;
- configuration management;
- supply-chain controls;
- adversarial testing;
- monitoring;
- human review;
- autonomy constraints;
- fail-safe mechanisms;
- incident response.

No single control should be assumed to address all credible threats.

## 25. Detection and Monitoring

For material threats, the organisation should define how compromise or abnormal behaviour could be detected.

Detection may rely on:

- security logs;
- integrity checks;
- data monitoring;
- behavioural monitoring;
- anomaly detection;
- access monitoring;
- configuration monitoring;
- human reporting;
- independent assurance checks.

Threats that cannot be detected promptly may require stronger preventive or containment controls.

## 26. Threat-to-Control Traceability

A threat model should support traceability:

**Threat → Risk → Requirement → Control → Test → Evidence → Assurance → Operational Condition**

This is part of the D-AIGAAF Golden Thread.

## 27. Threat-Modelling Record

A Threat Model Record should contain, where appropriate:

| Field | Description |
|---|---|
| Threat ID | Unique identifier |
| Asset | Asset at risk |
| Threat Source | Actor or hazard |
| Threat Scenario | Credible scenario |
| Entry Point | Potential attack or failure path |
| Vulnerability / Exposure | Relevant weakness |
| AI Effect | Effect on AI behaviour |
| Mission Effect | Operational consequence |
| Consequence | Severity of potential harm |
| Existing Controls | Current mitigations |
| Detection | Detection mechanism |
| Residual Risk | Remaining risk |
| Assurance Evidence | Supporting evidence |
| Owner | Responsible authority |
| Status | Current treatment status |

## 28. Threat Assurance Levels

A working five-level threat assurance scale may be used:

- **T1 — Basic Threat Review:** Major obvious threats identified.
- **T2 — Structured Threat Model:** Relevant assets, actors and attack paths documented.
- **T3 — Assured Threat Model:** Material threats tested against implemented controls.
- **T4 — Operational Threat Assurance:** Threat model validated against the authorised operational environment.
- **T5 — High-Consequence Threat Assurance:** Adversarial assessment, monitoring, response and residual-risk controls demonstrated for highly consequential use.

These are D-AIGAAF working constructs and should be mapped to established organisational terminology before formal adoption.

## 29. Threat Model Maintenance

Threat models should be reviewed when:

- mission changes;
- new threats emerge;
- architecture changes;
- models change;
- data sources change;
- interfaces change;
- autonomy changes;
- operational environments change;
- suppliers or dependencies change;
- incidents reveal previously unidentified threats.

Threat modelling should therefore be a continuous assurance activity.

## 30. Security Incidents and Threat Models

Security incidents should feed back into threat modelling.

A relevant incident may indicate:

- a previously unknown threat;
- an underestimated vulnerability;
- inadequate detection;
- ineffective controls;
- an incorrect assumption;
- a changed threat environment.

The threat model should be updated where lessons materially affect risk.

## 31. Operational Authorisation

Operational authorisation should consider whether:

- credible material threats have been identified;
- threat assumptions are documented;
- critical attack paths have appropriate controls;
- controls have been tested;
- monitoring is adequate;
- residual risks are understood;
- threat changes can trigger reassessment.

A capability should not be considered secure merely because no known attack has yet succeeded.

## 32. Common Failure Modes

Common weaknesses include:

- treating threat modelling as a one-time workshop;
- considering only conventional cyber threats;
- ignoring model and data manipulation;
- failing to model supply-chain compromise;
- ignoring malicious insiders;
- overlooking degraded operation;
- failing to connect threats to mission consequences;
- relying on a single security control;
- failing to test threat assumptions;
- not updating the threat model after incidents or material changes.

## 33. Core Rules

1. Model threats against the complete AI capability, not only its infrastructure.
2. Connect technical attack paths to mission consequences.
3. Include data, model, interface, human, autonomy and supply-chain threats.
4. Consider both malicious and unintended threat scenarios.
5. Scale threat treatment with consequence and autonomy.
6. Identify how material threats will be detected.
7. Test critical threat assumptions and controls.
8. Protect operational boundaries and human authority.
9. Update threat models when the system, mission, environment or threat changes.
10. Feed incidents and emerging threats back into the assurance lifecycle.

## 34. Relationship to Other D-AIGAAF Domains

This document connects directly with:

- **03 Risk & Autonomy** — risk, consequence and autonomy;
- **04 AI Lifecycle** — threat modelling across lifecycle stages;
- **05 Data & Information** — data threats and provenance;
- **06 AI Security** — security governance and requirements;
- **07 Supply Chain & Sovereignty** — supplier and dependency threats;
- **08 Human Authority** — threats to human control;
- **09 TEVV** — adversarial and security testing;
- **10 Operational Environment** — environmental and degraded conditions;
- **11 Operational Authorisation** — threat-based conditions of authority;
- **13 Continuous Assurance** — threat monitoring;
- **14 Incident & Fail-Safe** — response to compromise;
- **15 Change & Reauthorisation** — reassessment after material change;
- **16 Audit & Evidence** — threat and control traceability;
- **24 Architecture & Technical Controls** — technical implementation.

## 35. Summary

The key question is:

> **Can the organisation identify credible ways in which an adversary, insider, compromised dependency, environmental condition, or unintended interaction could cause the AI capability to leave its authorised security or operational boundaries, and can it demonstrate that those threats are adequately controlled?**

If not, the threat model is incomplete and the resulting uncertainty must be reflected in assurance and operational authorisation.
