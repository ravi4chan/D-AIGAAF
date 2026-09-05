# Risk Model

## 1. Purpose

The Risk Model defines the conceptual method D-AIGAAF uses to identify, analyse, treat, monitor and communicate risk associated with defence AI capabilities.

The model connects mission consequence, autonomy, operational context, human control, security, information integrity, dependencies and uncertainty to the level of assurance and authority required.

---

## 2. Core Principle

AI risk is not a property of a model in isolation.

> **Risk arises from the interaction between an AI capability, its mission, use case, operational environment, autonomy, human authority and potential consequence.**

The same AI capability may therefore have materially different risk profiles in different missions or operating conditions.

---

## 3. Risk Chain

The core D-AIGAAF risk relationship is:

**Mission + Capability + Use Case + Context + Constraints → Inherent Risk → Controls → Residual Risk → Required Assurance → Operational Authorisation**

Risk assessment therefore informs assurance and authority but does not itself grant operational authority.

---

## 4. Risk Assessment Scope

Risk assessment should consider, where relevant:

- mission consequence;
- mission criticality;
- autonomy;
- operational environment;
- human control;
- information integrity;
- security;
- reliability and robustness;
- availability;
- loss of control;
- supply chain;
- dependencies;
- foreseeable misuse;
- uncertainty;
- legal and policy conditions.

The relevant dimensions should be selected according to the use case.

---

## 5. Consequence

Consequence describes the potential effect if the AI capability produces an incorrect, unsafe, unauthorised or unavailable outcome.

A working construct may be:

- **C1 — Negligible:** limited consequence.
- **C2 — Minor:** recoverable operational or material impact.
- **C3 — Significant:** material mission, safety, security or operational impact.
- **C4 — Severe:** serious harm, major mission failure or substantial loss.
- **C5 — Catastrophic:** death, catastrophic harm, strategic consequence or major loss of control.

These levels are a working construct and should be validated against the organisation's established risk terminology.

---

## 6. Mission Criticality

Mission criticality describes how essential the AI-supported function is to mission success.

A working construct may be:

- **M1 — Low:** limited mission dependency.
- **M2 — Supporting:** useful but readily replaceable.
- **M3 — Important:** material contribution to mission effectiveness.
- **M4 — Critical:** major dependency for mission execution.
- **M5 — Mission-Critical:** failure may prevent safe or effective mission execution.

Mission criticality is distinct from consequence.

---

## 7. Autonomy

Autonomy describes the degree to which the AI system can act or make decisions without direct human intervention.

A working construct may be:

- **A0 — No meaningful AI decision:** AI has no meaningful decision role.
- **A1 — Information/Observation:** provides or organises information.
- **A2 — Analysis/Recommendation:** analyses information or provides recommendations.
- **A3 — Human-Authorised Action:** proposes or prepares an action requiring explicit human authorisation.
- **A4 — Supervised Execution:** executes predefined actions under defined human supervision.
- **A5 — Independent Consequential Action:** independently makes or executes consequential decisions or actions.

This is a working construct and must be validated against established autonomy terminology before formal adoption.

Technical capability and authorised autonomy are separate concepts.

---

## 8. Operational Environment

Environment describes the conditions under which the AI capability operates.

A working construct may range from:

- **E1 — Controlled:** predictable and well-controlled conditions.
- **E2 — Routine Operational:** normal operational variability.
- **E3 — Complex:** substantial environmental or operational variability.
- **E4 — Degraded:** significant degradation of data, communications, sensors or infrastructure.
- **E5 — Extreme/Adversarial:** extreme, contested or strongly adversarial conditions.

Environment should be assessed against the actual intended mission context.

---

## 9. Human Control

Human control describes the practical ability of an authorised human to understand, supervise, intervene and terminate AI-supported activity.

A working construct may range from:

- **H1 — Immediate Control:** human can readily understand and intervene.
- **H2 — Responsive Control:** intervention is available within the required timeframe.
- **H3 — Constrained Control:** intervention is possible but materially constrained.
- **H4 — Delayed Control:** meaningful intervention is difficult or delayed.
- **H5 — No Meaningful Immediate Control:** effective human intervention is unavailable during consequential operation.

Human presence does not automatically establish meaningful human control.

---

## 10. Information Integrity

Risk should consider the integrity and reliability of information used by the AI system.

Relevant factors include:

- provenance;
- accuracy;
- completeness;
- timeliness;
- consistency;
- authenticity;
- susceptibility to manipulation.

A highly capable model cannot compensate reliably for materially corrupted information.

---

## 11. Security Risk

Security risk should consider threats to:

- data;
- models;
- software;
- hardware;
- interfaces;
- credentials;
- communications;
- infrastructure;
- suppliers;
- supporting systems.

Security risk should be assessed in relation to mission consequence and operational exposure.

---

## 12. Loss-of-Control Risk

Loss-of-control risk should be assessed separately from ordinary technical failure.

It includes the possibility that an AI capability:

- acts outside its authorised function;
- exceeds its operational boundary;
- continues after authority is withdrawn;
- cannot be reliably interrupted;
- affects unauthorised systems;
- modifies critical behaviour without authorisation;
- causes cascading or self-reinforcing effects.

For high-consequence systems, loss-of-control risk may become a dominant risk driver.

---

## 13. Reliability and Robustness

Risk assessment should consider:

- failure frequency;
- performance degradation;
- recovery;
- edge cases;
- environmental sensitivity;
- adversarial sensitivity;
- repeatability;
- resilience to unexpected inputs.

Reliability should be assessed under representative operational conditions, not only laboratory conditions.

---

## 14. Availability Risk

Availability risk concerns the consequences of the AI capability or a critical dependency becoming unavailable.

Assessment should consider:

- mission dependency;
- alternative methods;
- recovery time;
- degraded operation;
- manual fallback;
- communications;
- power;
- infrastructure.

Loss of availability may be less harmful than incorrect operation in some missions and more harmful in others.

---

## 15. Dependency Risk

Dependency risk concerns external systems, services, people and resources required for safe or effective operation.

Examples include:

- communications;
- sensors;
- data;
- navigation;
- computing;
- power;
- external services;
- suppliers;
- specialist personnel.

Critical dependencies should be explicitly identified and linked to risk controls.

---

## 16. Supply-Chain Risk

Supply-chain risk should consider:

- provenance;
- supplier concentration;
- jurisdiction;
- critical dependencies;
- update control;
- component substitution;
- supplier security;
- continuity;
- ability to independently verify changes.

Supplier assurance does not automatically replace independent assurance.

---

## 17. Uncertainty

Uncertainty should be treated as a risk factor rather than hidden inside a single risk score.

Relevant uncertainty may concern:

- system behaviour;
- data quality;
- operational conditions;
- threat conditions;
- model limitations;
- human response;
- dependencies;
- unknown failure modes.

Where uncertainty is material, the organisation should determine whether additional evidence, controls or restrictions are required.

---

## 18. Foreseeable Misuse

Risk assessment should consider reasonably foreseeable misuse.

Examples include:

- use outside the intended mission;
- use outside the authorised environment;
- excessive reliance on AI recommendations;
- use by unauthorised personnel;
- unauthorised autonomy;
- use with unsuitable data;
- bypassing required human approval.

Controls should address material foreseeable misuse.

---

## 19. Risk Interactions

Risk dimensions should not always be treated independently.

Examples include:

**High Consequence + High Autonomy**

**High Consequence + Low Human Control**

**Degraded Environment + Communications Loss + High Autonomy**

**Poor Data Integrity + High Mission Criticality**

**Security Compromise + Loss of Control**

Combined conditions may produce materially greater risk than any single dimension suggests.

---

## 20. Inherent Risk

Inherent risk is the risk before considering additional controls or mitigations.

It should reflect the capability as proposed, including:

- mission;
- consequence;
- autonomy;
- environment;
- human control;
- information;
- security;
- dependencies;
- uncertainty.

Inherent risk establishes the starting point for risk treatment.

---

## 21. Controls

Controls are measures intended to prevent, detect, reduce or respond to risk.

Controls may include:

- technical controls;
- procedural controls;
- human controls;
- security controls;
- information controls;
- autonomy restrictions;
- operational boundaries;
- redundancy;
- monitoring;
- fail-safe mechanisms;
- training;
- supplier controls.

Controls should be linked to the risks they address.

---

## 22. Control Effectiveness

Control effectiveness should consider:

- whether the control exists;
- whether it operates as intended;
- whether it is available under degraded conditions;
- whether it can be bypassed;
- whether it has been independently tested;
- whether its limitations are understood.

A documented control should not automatically be treated as an effective control.

---

## 23. Residual Risk

Residual risk is the risk remaining after applicable controls are implemented.

Residual risk should reflect:

- remaining vulnerabilities;
- evidence gaps;
- uncertainty;
- operational limitations;
- human-control limitations;
- dependency exposure;
- threat exposure.

Residual risk should be explicitly accepted, reduced, transferred where appropriate, restricted or otherwise managed by the appropriate authority.

---

## 24. Risk Acceptance

Risk acceptance must be performed by an authority with appropriate legal, organisational and delegated authority.

The authority should understand:

- the risk;
- the evidence;
- the limitations;
- the controls;
- the uncertainty;
- the potential consequence.

Risk acceptance does not automatically constitute operational authorisation.

---

## 25. Risk Appetite and Tolerance

Organisations may establish risk appetite and tolerance according to:

- mission;
- consequence;
- policy;
- operational role;
- legal requirements;
- strategic priorities.

D-AIGAAF should not create universal acceptable-risk thresholds without appropriate institutional validation.

Some risks may be inherently unacceptable regardless of technical controls.

---

## 26. Risk Treatment

Risk treatment options may include:

- avoid;
- eliminate;
- reduce;
- control;
- restrict;
- transfer where appropriate;
- accept;
- monitor.

Risk treatment should address the actual source of risk rather than simply reducing a numerical score.

---

## 27. Risk and Assurance

Risk determines the strength and breadth of assurance required.

Higher risk may require:

- broader testing;
- more representative environments;
- adversarial testing;
- independent evaluation;
- stronger human-control evidence;
- greater evidence depth;
- tighter operational boundaries;
- more frequent review.

The principle is:

> **Burden of evidence should scale with consequence, autonomy, uncertainty and operational exposure.**

---

## 28. Risk and Operational Authorisation

Residual risk is one input to operational authorisation.

Operational authority should consider:

**Residual Risk + Assurance Evidence + Operational Boundaries + Human Authority + Conditions**

Risk assessment alone cannot authorise operational employment.

---

## 29. Risk and Autonomy

Increasing autonomy may increase risk when it:

- reduces opportunities for human intervention;
- increases speed of action;
- expands decision scope;
- increases consequence;
- creates new failure pathways;
- reduces observability.

Autonomy should therefore be assessed against mission consequence and human-control capability.

---

## 30. Risk Escalation

Risk should be escalated when:

- consequence increases;
- autonomy increases;
- human control decreases;
- environment becomes more degraded or adversarial;
- evidence becomes inadequate;
- a critical dependency fails;
- a new threat emerges;
- security is compromised;
- system behaviour changes;
- an incident occurs.

Escalation thresholds should be defined before operational employment where practical.

---

## 31. Risk Monitoring

Operational risk should be monitored using:

- system performance;
- environmental conditions;
- data quality;
- security indicators;
- human workload;
- dependency status;
- incidents;
- near misses;
- boundary violations;
- emerging threats.

Monitoring should support timely operational decisions.

---

## 32. Risk Review Triggers

Formal review should occur when:

- mission changes;
- use case changes;
- model or system behaviour changes;
- autonomy changes;
- operational environment changes;
- critical dependency changes;
- threat conditions change;
- legal or policy conditions change;
- significant incidents occur;
- evidence becomes outdated.

---

## 33. Risk Assessment Record

A Risk Assessment Record should contain, as applicable:

- mission;
- use case;
- capability;
- consequence;
- mission criticality;
- autonomy;
- environment;
- human control;
- information integrity;
- security risk;
- loss-of-control risk;
- reliability;
- availability;
- dependency risk;
- supply-chain risk;
- foreseeable misuse;
- uncertainty;
- inherent risk;
- controls;
- control effectiveness;
- residual risk;
- risk owner;
- risk acceptance authority;
- evidence;
- review triggers;
- review date.

---

## 34. Working Risk Profile

A D-AIGAAF risk profile may initially be represented as:

| Dimension | Assessment |
|---|---|
| Consequence | C1–C5 |
| Mission Criticality | M1–M5 |
| Autonomy | A0–A5 |
| Environment | E1–E5 |
| Human Control | H1–H5 |
| Information Integrity | Low / Medium / High / Critical |
| Security Risk | Low / Medium / High / Critical |
| Loss-of-Control Risk | Low / Medium / High / Critical |
| Reliability | Low / Medium / High |
| Availability | Low / Medium / High |
| Supply-Chain Risk | Low / Medium / High |
| Uncertainty | Low / Medium / High |
| Critical Dependencies | Identified / Not Identified |

This is a structured assessment framework, not a universal numerical risk formula.

---

## 35. Risk Decision Logic

A simplified decision logic is:

**1. Identify the mission and use case.**

**2. Identify consequence and mission criticality.**

**3. Identify autonomy and human control.**

**4. Identify operational and threat conditions.**

**5. Identify information, security and dependency risks.**

**6. Identify uncertainty and foreseeable misuse.**

**7. Determine inherent risk.**

**8. Define and assess controls.**

**9. Determine residual risk.**

**10. Identify required assurance.**

**11. Determine whether the residual risk is acceptable to the appropriate authority.**

**12. Inform operational authorisation and conditions.**

**13. Monitor and reassess continuously.**

---

## 36. Risk Failure Modes

D-AIGAAF should guard against:

- treating model risk as total mission risk;
- using a single numerical score to hide important dimensions;
- ignoring human-control risk;
- ignoring loss-of-control risk;
- assuming benign operating conditions;
- treating uncertainty as zero;
- accepting risk without authority;
- confusing risk acceptance with authorisation;
- treating controls as effective without evidence;
- allowing risk assessments to become outdated;
- failing to reassess after incidents or change.

---

## 37. Relationship With Golden Thread

Risk is a central link in the Golden Thread:

**Mission Need → Use Case → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Risk should remain traceable to:

- mission need;
- use case;
- requirements;
- controls;
- evidence;
- assurance;
- authorisation;
- operational outcomes.

---

## 38. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Principles`
- `00 Framework/Terminology`
- `00 Framework/Lifecycle`
- `00 Framework/Golden Thread`
- `01 Strategy & Governance`
- `02 Mission & Use Case`
- `03 Risk & Autonomy`
- `04 AI Lifecycle`
- `05 Data & Information`
- `06 AI Security`
- `07 Supply Chain & Sovereignty`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`

---

## 39. Summary

The D-AIGAAF Risk Model treats AI risk as a mission- and context-dependent problem rather than a property of the model alone.

It connects consequence, mission criticality, autonomy, environment, human control, information integrity, security, dependencies and uncertainty to controls, residual risk, assurance and operational authority.

The central principle is:

> **Risk must be assessed in the context in which AI will actually be used, and the burden of evidence, control and authority should increase with consequence, autonomy, uncertainty and operational exposure.**
