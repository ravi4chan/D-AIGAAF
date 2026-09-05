# D-AIGAAF Principles

**Defence AI Governance, Assurance & Operational Authorisation Framework**

**Version:** 0.1  
**Status:** Working Draft  
**Classification:** Open / Unclassified

---

## 1. Purpose

This document defines the foundational principles of D-AIGAAF.

These principles provide the normative foundation for the framework and should guide the development of its policies, controls, assurance processes, operational authorisation mechanisms and implementation guidance.

The principles are intended to answer a fundamental question:

> **What should always remain true when AI is developed, acquired, assured, authorised and employed for defence purposes?**

The principles should be interpreted together rather than as isolated rules.

---

# 2. Foundational Principle

## P-01 — Mission, Consequence and Context Determine Governance

AI governance shall be determined by the intended mission, potential consequence, operational context, autonomy and human authority associated with the capability.

The same underlying AI technology may require different governance and assurance depending on how and where it is employed.

---

# 3. Authority Principles

## P-02 — Primacy of Command Authority

AI shall not replace legitimate command authority.

Where an AI system supports military decision-making, the designated human authority remains responsible for decisions within their assigned authority.

Where a specific autonomous function has been authorised, that authority must itself be explicitly established.

---

## P-03 — No Authority Beyond Law and Policy

AI-enabled capabilities shall operate only within authority granted by applicable law, policy, doctrine, rules and organisational decisions.

Technical capability shall never be treated as evidence of legal or operational authority.

---

## P-04 — No Silent Expansion of Authority

An AI system shall not acquire additional operational authority merely because its technical capability, software, model, data or integration has changed.

Any material expansion of:

- mission;
- environment;
- autonomy;
- consequence;
- system authority; or
- human-control conditions

shall require appropriate assessment and, where necessary, additional assurance and authorisation.

---

## P-05 — Conditional Operational Authority

Operational authorisation shall be conditional rather than absolute.

Authorisation should specify, as applicable:

- what capability is authorised;
- for what mission;
- in what environment;
- at what autonomy;
- under whose authority;
- subject to what limitations; and
- for what period.

---

# 4. Assurance Principles

## P-06 — No Authority Without Evidence

Operational authority shall be supported by evidence proportionate to the potential consequences of failure.

Evidence should demonstrate that the system is suitable for its intended operational purpose rather than merely demonstrating technical functionality.

---

## P-07 — Assurance Does Not Equal Authorisation

Successful testing or assurance does not automatically create operational authority.

Assurance determines what the available evidence demonstrates.

Authorisation is a separate organisational decision that considers:

- assurance evidence;
- residual risk;
- mission requirements;
- operational context;
- legal and policy constraints; and
- human authority.

---

## P-08 — Mission- and Context-Dependent Assurance

AI assurance shall consider the intended mission and operational environment.

Evidence obtained in one environment should not automatically be assumed to demonstrate equivalent performance in a materially different environment.

---

## P-09 — Burden of Evidence Scales With Consequence

The level and depth of assurance should increase as potential consequences increase.

Greater scrutiny should generally apply where AI failure could result in:

- death or serious harm;
- loss of control;
- significant mission failure;
- compromise of critical infrastructure;
- strategic consequences; or
- other catastrophic outcomes.

---

## P-10 — Evidence Must Be Traceable

Important assurance conclusions should be traceable to identifiable evidence.

Where practicable, the relationship should be maintained between:

**Requirement → Risk → Control → Test → Evidence → Finding → Assurance → Authorisation**

Unresolved evidence gaps should be explicitly recorded.

---

## P-11 — Continuous Assurance

Assurance shall continue throughout the operational lifecycle.

Operational authorisation is not the end of assurance.

> **Operational authorisation is the beginning of continuous assurance.**

Operational experience, incidents, changes and emerging threats should feed back into assurance.

---

# 5. Operational Principles

## P-12 — Authorised Operational Envelope

Every consequential AI capability should have a defined operational envelope appropriate to its risk.

The envelope may include:

- mission;
- terrain;
- environmental conditions;
- communications conditions;
- sensor conditions;
- data conditions;
- human-control conditions;
- autonomy;
- system configuration; and
- other relevant constraints.

Operation outside the authorised envelope should trigger appropriate assessment, restriction, escalation or suspension.

---

## P-13 — Operational Independence and Resilience

AI capabilities shall be assessed for their ability to function safely and predictably under the communications, infrastructure, data and environmental conditions expected during operations.

Where a capability is expected to operate with limited or no connectivity, this condition must be considered during assurance.

---

## P-14 — Controlled Degradation

AI systems should have defined behaviour for conditions in which normal performance cannot be maintained.

Degradation should, where practicable, progress toward controlled states such as:

**Normal Operation → Degraded Operation → Restricted Function → Human-Controlled Mode → Safe State / Suspension**

The appropriate response depends on mission, consequence, autonomy, environment and system architecture.

---

## P-15 — AI Recommendation Is Not Command Authority

An AI recommendation shall not itself constitute an order or command decision.

The system's output, the human interpretation of that output and the resulting authorised decision should remain conceptually distinct.

---

# 6. Human Authority Principles

## P-16 — Meaningful Human Control

Where human control is required, it must be meaningful rather than nominal.

Meaningful control should consider whether the human has:

- appropriate authority;
- sufficient information;
- adequate understanding of system limitations;
- sufficient time to intervene;
- a realistic ability to override or stop the system; and
- appropriate training and competency.

---

## P-17 — Traceable Human Authority

For consequential AI-enabled decisions or actions, the relevant human authority should be identifiable to the extent practicable.

The framework should support determination of:

- who was authorised to decide;
- what authority they possessed;
- what AI contribution was available;
- what decision was made; and
- what action followed.

---

## P-18 — Qualified Human Authority

Human oversight should be performed by personnel with competency appropriate to the AI capability and its operational consequences.

Human presence alone does not constitute effective human oversight.

---

## P-19 — AI Must Not Displace Accountability

AI assistance shall not be used to obscure or transfer accountability away from the authorised human or organisational authority.

AI may support a decision without becoming the accountable authority for that decision.

---

## P-20 — Recording of Significant Human Overrides

Where appropriate to the consequence and governance requirements, significant human decisions to reject, override or bypass AI recommendations should be recorded.

The purpose is not to compel acceptance of AI recommendations.

The purpose is to preserve accountability, enable learning and support future assurance.

---

# 7. Autonomy Principles

## P-21 — Autonomy Must Be Explicitly Defined

The autonomy of an AI-enabled capability shall be explicitly defined and understood.

A working D-AIGAAF taxonomy is:

| Level | Description |
|---|---|
| **A0** | No meaningful AI decision-making |
| **A1** | Information, observation or classification |
| **A2** | Analysis, prediction or recommendation |
| **A3** | Recommendation or action requiring explicit human authorisation |
| **A4** | Execution of predefined actions under human supervision |
| **A5** | Independent consequential decision or action |

This taxonomy is a working construct and should be validated against established terminology before formal adoption.

---

## P-22 — Autonomy Must Be Matched to Consequence

Increasing autonomy should generally require increasing assurance and control when the consequences of failure increase.

Autonomy must therefore be considered together with:

- consequence;
- mission criticality;
- operational environment;
- human control; and
- system authority.

---

## P-23 — AI Shall Not Self-Expand Its Authority

An AI system shall not modify, extend or acquire operational authority beyond what has been explicitly authorised.

Technical mechanisms should support this principle through appropriate system boundaries, access controls, monitoring and control mechanisms.

---

# 8. Security Principles

## P-24 — Adversarial Robustness

AI systems intended for defence use should be assessed against conditions in which inputs, data, communications or system components may be intentionally manipulated.

Assurance should consider relevant adversarial conditions rather than relying exclusively on benign testing.

---

## P-25 — Least Authority

AI systems should possess only the permissions, access and ability to act necessary for their authorised function.

Reducing unnecessary authority reduces the consequences of compromise, malfunction or unexpected behaviour.

---

## P-26 — Defence in Depth

No single control should be assumed to provide complete protection for a consequential AI system.

Security and safety should be supported through multiple complementary layers, including where appropriate:

- system boundaries;
- access controls;
- monitoring;
- human oversight;
- validation;
- containment;
- fail-safe mechanisms; and
- organisational controls.

---

## P-27 — Fail-Safe as Last Resort

Appropriately consequential AI systems should have a reliable mechanism for transitioning to a safer state when continued operation presents unacceptable risk.

A fail-safe mechanism should be treated as a last resort, not as a substitute for prevention, assurance or responsible command.

---

# 9. Information Principles

## P-28 — Information Before Intelligence

AI-generated assessments are dependent on the quality of the information provided to the system.

Governance should therefore consider the chain:

**Information → Processing → Assessment → Decision**

Failure may originate in the information layer rather than in the AI model itself.

---

## P-29 — Provenance by Design

The origin, integrity and relevant history of information, models and critical system components should be established to the extent practicable.

Provenance should support accountability and assurance.

---

## P-30 — Uncertainty Is Information

AI systems should communicate meaningful uncertainty and relevant limitations.

The system should not express greater confidence than the available evidence supports.

Where uncertainty is operationally significant, it should be visible to the appropriate human decision-maker.

---

## P-31 — Data Integrity Is Operational Security

Compromised, manipulated, incomplete, stale or misleading data can produce unsafe AI behaviour.

Data integrity should therefore be treated as an operational security and assurance concern.

---

# 10. Supply Chain and Sovereignty Principles

## P-32 — Procurement Must Preserve Assurance

Procurement decisions should preserve the organisation's ability to:

- test;
- evaluate;
- monitor;
- audit;
- secure;
- update;
- restrict; and
-, where necessary, suspend or retire

the AI capability throughout its lifecycle.

---

## P-33 — Supplier Assurance Does Not Replace Independent Assurance

Supplier claims, certifications and test results may contribute to assurance but should not automatically be treated as sufficient evidence for operational authorisation.

The depth of independent assurance should be proportionate to risk and consequence.

---

## P-34 — No Blind Updates

AI systems should not receive material updates without appropriate awareness and change assessment.

Where an update can alter system behaviour, authority, security or operational performance, the change should be assessed before continued operational use where practicable.

---

## P-35 — Sovereignty Must Be Assessed

For strategically or operationally significant AI capabilities, governance should consider dependencies that may affect national or organisational freedom of action.

Relevant dependencies may include:

- models;
- hardware;
- software;
- cloud services;
- data;
- APIs;
- critical suppliers;
- update mechanisms; and
- other external dependencies.

---

# 11. Change and Lifecycle Principles

## P-36 — Behaviour Determines Change Significance

Changes should be classified according to their potential effect on system behaviour, authority, security, performance and operational risk.

A change that appears technically minor may still require significant assurance if it can alter consequential behaviour.

---

## P-37 — Change Does Not Preserve Authority Automatically

Existing operational authorisation should not automatically be assumed to remain valid after a significant change.

The organisation should determine whether:

- existing evidence remains valid;
- additional testing is required;
- additional assurance is required; or
- reauthorisation is required.

---

## P-38 — Incident Changes the Assurance Position

A significant incident, unexpected behaviour, security event or material failure may invalidate assumptions on which previous assurance or authorisation was based.

The appropriate response may include:

- investigation;
- restriction;
- suspension;
- reassessment;
- revalidation; and
- reauthorisation.

---

## P-39 — Retirement Must Remove Authority

When an AI capability is retired, its operational authority should also be formally terminated.

Retirement should address, as appropriate:

- system access;
- credentials;
- interfaces;
- deployed instances;
- data;
- models;
- dependencies;
- records; and
- residual operational authority.

---

# 12. Operational AI Advisor Principles

## P-40 — Bridge Technical and Operational Expertise

The Operational AI Advisor should provide a structured interface between AI expertise and operational command.

The OAIA should help translate between:

**Technical Capability ↔ Operational Requirement ↔ Assurance Evidence ↔ Command Decision**

---

## P-41 — OAIA Advises; Authority Decides

The Operational AI Advisor does not replace command authority.

The OAIA provides professional advice on:

- capability;
- limitations;
- risk;
- autonomy;
- assurance;
- operational context;
- incidents; and
- changes.

The designated authority remains responsible for the operational decision.

---

## P-42 — Operational Experience Must Inform Assurance

The OAIA and relevant operational personnel should help ensure that experience from real-world employment is incorporated into:

- assurance evidence;
- risk assessments;
- training;
- controls;
- requirements; and
- future authorisation decisions.

---

# 13. Governance Principles

## P-43 — Accountability Must Be Explicit

Every consequential AI capability should have clearly identified organisational responsibility.

At minimum, governance should establish appropriate ownership for:

- capability;
- system;
- security;
- assurance;
- operational employment; and
- authorisation.

---

## P-44 — Governance Must Follow the Lifecycle

AI governance should begin before acquisition and continue until retirement.

Governance should not be treated as a one-time approval exercise.

---

## P-45 — Cross-Functional Governance

Consequential AI governance should bring together relevant technical, operational, legal, security, information, acquisition and policy expertise.

No single professional discipline can adequately govern every dimension of a consequential AI capability.

---

# 14. Evidence and Learning Principles

## P-46 — Operational Experience Becomes Assurance Evidence

Where appropriately captured, operational experience should become part of the evidence base for future assurance.

This includes:

- successful performance;
- failures;
- unexpected behaviour;
- human overrides;
- environmental limitations;
- incidents; and
- changes in operational conditions.

---

## P-47 — Known Limitations Must Be Visible

Known limitations, assumptions and failure modes should be explicitly documented and communicated to relevant authorities.

A system should not be considered fully assured merely because its limitations are hidden within technical documentation.

---

## P-48 — Unknowns Must Be Managed

The absence of evidence should not automatically be interpreted as evidence of safety or suitability.

Where important uncertainty remains, it should be:

- identified;
- documented;
- assessed;
- mitigated where possible; and
- considered in the authorisation decision.

---

# 15. Core D-AIGAAF Principle Set

The principles can be condensed into the following core propositions:

1. **Mission determines purpose.**
2. **Consequence determines scrutiny.**
3. **Context determines applicability.**
4. **Autonomy must be explicit.**
5. **Human authority must be explicit.**
6. **Evidence precedes operational authority.**
7. **Assurance does not equal authorisation.**
8. **Authority must not expand silently.**
9. **AI does not inherently possess command authority.**
10. **Operational environments are part of assurance.**
11. **Uncertainty must be communicated.**
12. **AI security includes loss-of-control risk.**
13. **Fail-safe capability is a last-resort control.**
14. **Provenance matters throughout the supply chain.**
15. **Material behavioural changes require reassessment.**
16. **Operational authorisation is conditional.**
17. **Assurance continues after deployment.**
18. **Operational experience becomes evidence.**
19. **Retirement must terminate operational authority.**
20. **Accountability must remain identifiable.**

---

# 16. Relationship to the D-AIGAAF Reference Model

The principles in this document provide the foundation for the broader D-AIGAAF architecture.

They inform:

- Strategy & Governance;
- Mission & Use Case;
- Risk & Autonomy;
- AI Lifecycle;
- Data & Information;
- AI Security;
- Supply Chain & Sovereignty;
- Human Authority;
- TEVV;
- Operational Environment;
- Operational Authorisation;
- Operational Employment;
- Continuous Assurance;
- Incident & Fail-Safe;
- Change & Reauthorisation;
- Audit & Evidence;
- Workforce;
- Maturity;
- Acquisition; and
- Implementation.

The relationship is:

```text
Principles
    ↓
Governance & Policy
    ↓
Requirements & Controls
    ↓
Testing & Evidence
    ↓
Assurance
    ↓
Operational Authorisation
    ↓
Operational Employment
    ↓
Continuous Assurance
    ↓
Lessons & Change
    └──────────────→ Principles / Policy / Controls
```

---

# 17. Principle Evolution

These principles are not considered final.

As D-AIGAAF develops, each principle should be tested against:

- existing standards;
- defence requirements;
- legal and policy requirements;
- operational experience;
- technical feasibility;
- assurance practice;
- implementation evidence; and
- emerging AI risks.

A principle should be retained, modified or removed based on evidence and reasoning rather than terminology alone.

---


**D-AIGAAF Principles v0.1**

Working draft for framework development.

The principles are intended to provide a foundation for subsequent D-AIGAAF policies, controls, methodologies, templates and implementation guidance.
