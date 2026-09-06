# 28 Operational Authorisation Cross-System and Multi-AI Governance

## 1. Purpose

Defence AI capabilities may operate alongside other AI systems, conventional software, sensors, human decision-makers and external information sources.

A capability may therefore produce outputs that influence another AI system, while another system may influence the first. In such environments, authorisation of individual systems may not be sufficient to establish safe and accountable operational use.

This document defines governance for situations in which multiple AI capabilities interact, exchange information, depend on one another or contribute collectively to consequential outcomes.

The objective is to ensure that:

- authority remains attributable;
- system boundaries remain identifiable;
- combined behaviour is considered;
- autonomy does not increase unintentionally through system interaction;
- dependencies remain visible;
- human authority remains explicit;
- interfaces are controlled;
- cross-system changes are assessed; and
- operational outcomes remain traceable.

---

## 2. Core Principle

**A collection of individually authorised AI capabilities does not automatically constitute an authorised combined capability.**

Where interaction between systems can materially change risk, autonomy, behaviour, mission effectiveness or human control, the combined arrangement should be assessed and authorised appropriately.

---

## 3. Multi-System Authorisation Object

Where applicable, the governance object should be:

**AI Capability A × AI Capability B × Mission × Environment × Autonomy × Human Authority**

For larger systems, this may become:

**AI Ecosystem × Mission × Environment × Autonomy × Human Authority**

The relevant unit of governance should reflect the way the systems actually operate together.

---

## 4. Types of Interaction

Interactions may include:

- information exchange;
- sequential recommendations;
- decision support;
- shared data;
- shared sensors;
- shared infrastructure;
- task allocation;
- autonomous action coordination;
- one AI controlling or configuring another system;
- feedback loops;
- common external services; or
- human-mediated coordination.

The interaction type should be identified where it can affect operational risk.

---

## 5. System-of-Systems Context

A system-of-systems arrangement may contain:

- AI components;
- non-AI software;
- sensors;
- communication systems;
- human operators;
- command systems;
- external information services;
- autonomous platforms; and
- supporting infrastructure.

D-AIGAAF should consider the governance implications of the complete operational arrangement rather than assessing every AI component only in isolation.

---

## 6. Authority Boundaries

Each capability should have clearly defined authority boundaries.

The governance record should identify:

- what each system may decide;
- what each system may recommend;
- what each system may execute;
- what information each system may provide to another;
- what actions require human authority;
- which system has precedence where outputs conflict; and
- what actions remain prohibited.

No AI system should acquire additional operational authority merely because another system supplies it with an instruction or recommendation.

---

## 7. Emergent Behaviour

Interactions may produce behaviour that was not observed when individual components were tested separately.

Potential sources include:

- feedback loops;
- correlated errors;
- conflicting recommendations;
- automation cascades;
- unexpected data propagation;
- shared dependencies;
- timing interactions;
- inconsistent assumptions;
- autonomous adaptation; and
- unexpected human-AI interaction.

Where such behaviour could materially affect operational risk, combined-system TEVV should be considered.

---

## 8. Autonomy Composition

The combined autonomy of multiple systems should be assessed explicitly.

For example:

**AI Recommendation → AI Interpretation → AI Action**

may create a materially different operational effect from:

**AI Recommendation → Human Assessment → Human Decision → Action**

Therefore, autonomy should not be assessed solely at the component level.

The organisation should determine whether interactions create:

- effective autonomy escalation;
- reduced human oversight;
- hidden delegation;
- automated decision chains; or
- loss of meaningful human control.

---

## 9. Human Authority

Human authority should remain identifiable across the complete decision chain.

Where multiple AI systems contribute to a consequential outcome, the governance record should establish:

- who receives the information;
- who evaluates it;
- who has decision authority;
- who may intervene;
- who may override;
- who may terminate the process; and
- who is accountable for the resulting action.

AI systems should not collectively create an ambiguous authority structure.

---

## 10. Interface Governance

Interfaces between AI capabilities should be governed for:

- data meaning;
- data format;
- timing;
- integrity;
- provenance;
- uncertainty;
- confidence information;
- error handling;
- authentication;
- authorisation;
- availability;
- failure behaviour; and
- change control.

An interface should not be considered safe merely because data can technically be exchanged.

---

## 11. Information and Recommendation Chaining

Where one AI system consumes another AI system's output, the receiving system should be able to distinguish, where relevant:

- human-originated information;
- sensor information;
- conventional software output;
- AI-generated information;
- AI recommendation;
- AI-derived inference; and
- uncertain or degraded information.

This supports appropriate weighting, validation and human interpretation.

---

## 12. Uncertainty Propagation

Uncertainty may increase as outputs pass through multiple systems.

The governance approach should consider:

**Source Uncertainty → AI Interpretation → Secondary AI Processing → Decision Context**

The organisation should avoid situations where uncertain information becomes represented as highly certain information merely because it passed through additional processing.

---

## 13. Conflicting AI Outputs

Where AI systems produce conflicting recommendations, the organisation should define:

- how conflicts are identified;
- whether human review is mandatory;
- which authority resolves the conflict;
- whether one system has defined precedence;
- what information must be retained; and
- when conflict triggers restriction or escalation.

AI systems should not silently resolve high-consequence conflicts unless such behaviour is explicitly authorised.

---

## 14. Cross-System Dependencies

Dependencies between systems should be identified.

The dependency record should consider:

**System A → Interface/Dependency → System B → Operational Effect**

Dependencies may involve:

- data;
- communications;
- sensors;
- identity;
- compute;
- software;
- model services;
- security controls;
- navigation;
- external services; or
- human supervision.

Critical dependencies should have defined failure responses.

---

## 15. Failure Propagation

The organisation should consider how failure of one system could affect another.

Potential effects include:

- incorrect recommendations;
- delayed information;
- corrupted data;
- loss of situational awareness;
- unintended task allocation;
- autonomy escalation;
- cascading failure;
- loss of human control; or
- unsafe action.

Cross-system failure modes should be included in risk assessment and TEVV where material.

---

## 16. Cross-System Security

Security assessment should consider not only each system individually but also the interfaces between them.

Relevant concerns include:

- compromised upstream information;
- compromised downstream action;
- trust-boundary violations;
- credential propagation;
- malicious data;
- interface manipulation;
- supply-chain dependencies;
- compromised shared services; and
- lateral propagation of compromise.

Security controls should reflect the combined architecture.

---

## 17. Cross-System Configuration

A combined operational arrangement should have a known configuration baseline.

The baseline should identify, as applicable:

- participating systems;
- model versions;
- software versions;
- interfaces;
- configuration;
- data dependencies;
- autonomy settings;
- human-control mechanisms; and
- relevant external dependencies.

A material change to one component may affect the authorisation basis of the overall arrangement.

---

## 18. Cross-System Change Impact

Change assessment should determine whether a change to one capability affects:

- another AI capability;
- system interactions;
- autonomy;
- human control;
- mission effectiveness;
- security;
- data integrity;
- environmental assumptions;
- dependencies; or
- assurance evidence.

A component change should not automatically be treated as non-material merely because the component's standalone function remains unchanged.

---

## 19. Combined TEVV

Where material interaction exists, TEVV should consider:

- component behaviour;
- interface behaviour;
- system-of-systems behaviour;
- emergent behaviour;
- autonomy composition;
- human-AI interaction;
- failure propagation;
- degraded operation;
- adversarial conditions;
- security;
- mission effectiveness; and
- recovery.

Testing should reflect realistic operational interactions.

---

## 20. Operational Environment

Cross-system governance should consider the combined operational environment.

This includes:

- communications;
- electromagnetic conditions;
- sensors;
- navigation;
- physical conditions;
- information availability;
- adversarial activity;
- human workload; and
- infrastructure dependencies.

A combination that works in a controlled environment may behave differently when operating under degraded or adversarial conditions.

---

## 21. Multi-AI Human Interface

Where several AI capabilities support the same human decision-maker, governance should address:

- information overload;
- conflicting recommendations;
- automation bias;
- inconsistent uncertainty representations;
- duplicate alerts;
- hidden dependencies;
- excessive cognitive workload; and
- loss of situational awareness.

Human authority is meaningful only if the human can reasonably understand and control the decision process.

---

## 22. Operational AI Advisor

Where appropriate, the Operational AI Advisor may help commanders understand interactions between AI capabilities.

The OAIA may advise on:

- system roles;
- autonomy;
- limitations;
- uncertainty;
- interaction risks;
- human-control implications;
- configuration changes;
- assurance evidence; and
- operational consequences.

The OAIA does not replace command authority or authorising authority.

---

## 23. Cross-System Operational Authority

Where several AI systems contribute to a single consequential outcome, the authorisation record should identify:

- individual authorities;
- combined authority;
- human decision point;
- permitted interactions;
- prohibited interactions;
- autonomy boundaries;
- intervention points; and
- termination authority.

This prevents authority from becoming distributed without accountability.

---

## 24. Dynamic Conditions

Cross-system arrangements should be reassessed when:

- a participating system changes;
- a dependency fails;
- communications degrade;
- data quality changes;
- one system enters contingency mode;
- autonomy changes;
- human supervision changes;
- environmental conditions change;
- a security incident occurs; or
- unexpected system interaction occurs.

The combined arrangement should remain within defined authority.

---

## 25. Disconnected and Degraded Operation

Where connectivity between systems is lost, the arrangement should have predefined behaviour.

Possible responses include:

**Continue Within Boundary → Restrict Interaction → Reduce Autonomy → Human Control → Safe State → Suspend**

Loss of an interface should not cause an AI system to assume additional authority or create a new decision pathway without authorisation.

---

## 26. Cross-System Incident Management

Material incidents should assess both:

- the affected capability; and
- connected capabilities that may have received or acted on affected information.

The review should determine whether the incident has:

- local impact;
- cross-system impact; or
- ecosystem-level impact.

Related capabilities may require restriction or additional assurance.

---

## 27. Cross-System Decision Traceability

For consequential outcomes, traceability should identify:

**System Context → AI Contribution(s) → Human Assessment → Authority → Decision → Action → Outcome**

Where multiple AI systems contributed, the record should distinguish their individual contributions.

This prevents the collective system from becoming a black box for accountability.

---

## 28. Cross-System Monitoring

Monitoring should identify:

- system health;
- interface health;
- information integrity;
- conflicting outputs;
- uncertainty;
- unexpected interactions;
- autonomy transitions;
- human-control status;
- dependency failures; and
- mission effectiveness.

Monitoring should consider the combined operational state.

---

## 29. Cross-System Suspension

Where a material issue affects the combined arrangement, the organisation should determine whether to:

- restrict one system;
- restrict an interface;
- reduce autonomy;
- place a system under human control;
- suspend the combined arrangement; or
- suspend affected capabilities individually.

Suspension scope should match the identified risk.

---

## 30. Reauthorisation

Reauthorisation should be considered where:

- new AI capabilities are integrated;
- existing interactions materially change;
- autonomy composition changes;
- human-control arrangements change;
- material interfaces change;
- emergent behaviour is identified;
- critical dependencies change; or
- assurance evidence is invalidated.

The combined arrangement should not inherit authority automatically from previously authorised components.

---

## 31. Governance Records

Cross-system governance should maintain links between:

- individual Capability Registers;
- Assurance Records;
- Operational Authorisation Records;
- configuration baselines;
- interface records;
- dependency records;
- TEVV evidence;
- incident records;
- operational records; and
- change records.

---

## 32. Cross-System Authorisation Matrix

A practical matrix may include:

| Dimension | System A | System B | Combined Arrangement |
|---|---|---|---|
| Mission | Defined | Defined | Assessed |
| Environment | Defined | Defined | Assessed |
| Autonomy | Defined | Defined | Assessed |
| Human Authority | Defined | Defined | Integrated |
| Configuration | Controlled | Controlled | Controlled |
| Dependencies | Identified | Identified | Assessed |
| Security | Assured | Assured | Assessed |
| TEVV | Completed | Completed | Interaction Tested |
| Operational Authority | Defined | Defined | Explicit |
| Monitoring | Defined | Defined | Integrated |

The matrix should be adapted to the capability.

---

## 33. Governance Questions

Responsible authorities should be able to determine:

1. Which AI systems interact?
2. What does each system contribute?
3. What decisions can each system make?
4. Does interaction increase effective autonomy?
5. Who holds human decision authority?
6. How are conflicting outputs handled?
7. How is uncertainty propagated?
8. What interfaces are critical?
9. What dependencies exist?
10. Can failure propagate between systems?
11. What configuration is authorised?
12. Has the combined arrangement been tested?
13. Has emergent behaviour been considered?
14. What happens if communications are lost?
15. What happens if one system becomes degraded?
16. What security risks arise from system interaction?
17. What changes require reassessment?
18. What incidents affect connected capabilities?
19. Can consequential outcomes be reconstructed?
20. Is the combined arrangement itself operationally authorised?

---

## 34. Core Rule

> **Where multiple AI capabilities interact in a manner that can materially affect mission outcomes, autonomy, human control, security or operational risk, D-AIGAAF shall assess and govern the combined arrangement rather than relying solely on the authorisation of individual components. Individually authorised AI systems shall not acquire additional operational authority merely through interaction, and consequential multi-AI outcomes shall remain attributable, traceable and subject to defined human authority.**
