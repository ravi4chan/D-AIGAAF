# D-AIGAAF Principles

## 1. Purpose

The principles of D-AIGAAF establish the foundational propositions that guide the governance, assurance, security, authorisation and operational employment of AI-enabled capabilities in defence.

They provide the basis for translating operational requirements into governance requirements, technical controls, assurance activities and operational decisions.

The principles are intended to apply across the AI lifecycle.

---

# 2. Authority Principles

## P-01 — Primacy of Command Authority

AI may support military decision-making, but AI capability does not itself constitute command authority.

Where human command authority is required, the authorised human decision-maker retains responsibility for the employment decision.

> **AI recommendation is not command authority.**

---

## P-02 — No Authority Beyond Law and Policy

Operational authorisation remains subject to applicable law, policy, rules, delegated authority and other governing requirements.

Technical capability or AI assurance shall not itself create authority to employ an AI capability.

> **Technical capability does not create operational permission.**

---

## P-03 — No Authority Without Evidence

Operational authority should not be granted solely on the basis of developer claims, demonstrations, documentation or assumed performance.

The level of authority granted should be supported by evidence proportionate to the consequence, autonomy, mission criticality, operational environment and degree of human control involved.

---

## P-04 — No Silent Expansion of Authority

Authorisation for one mission, environment, autonomy level, configuration or operational condition shall not automatically be assumed to apply to another.

Changes in authorised scope require appropriate assessment.

> **Authority must be explicit.**

---

## P-05 — Conditional Authority

AI operational authority should be expressed through defined conditions, limitations, restrictions and operating boundaries rather than as unrestricted approval.

An authorisation should define where, when, how and by whom the capability may be employed.

---

# 3. Assurance Principles

## P-06 — Mission- and Context-Dependent Assurance

AI assurance shall consider the intended mission and operational context.

The same AI capability may present different risks when used for different:

- missions;
- environments;
- users;
- autonomy levels;
- information conditions; or
- consequences.

Therefore:

> **AI assurance is not necessarily transferable across missions or contexts.**

---

## P-07 — Evidence-Based Assurance

Assurance conclusions shall be supported by documented evidence.

Evidence may include:

- testing;
- evaluation;
- verification;
- validation;
- adversarial assessment;
- cybersecurity assessment;
- environmental testing;
- human-AI assessment;
- operational trials; and
- mission-level evaluation.

Assertions without supporting evidence should not be treated as equivalent to demonstrated assurance.

---

## P-08 — Assurance Is Proportionate to Risk

The assurance burden should increase with:

- consequence;
- autonomy;
- mission criticality;
- operational uncertainty;
- adversarial exposure; and
- reduction in meaningful human control.

High-consequence systems require stronger and more independent evidence than low-consequence systems.

---

## P-09 — Continuous Assurance

AI assurance does not end when a system is authorised.

Operational performance, behaviour, environment, security, configuration, incidents and changes should be monitored throughout the authorised lifecycle.

> **Trust must be maintained, not merely established.**

---

## P-10 — Traceable Evidence

Significant assurance conclusions should be traceable to:

- the requirement;
- the identified risk;
- the control;
- the test;
- the evidence;
- the assessment; and
- the resulting decision.

This enables reconstruction of why an AI capability was considered suitable for employment.

---

# 4. Security Principles

## P-11 — Adversarial Robustness

AI capabilities should be assessed against deliberate attempts to deceive, manipulate, disrupt, compromise or exploit them.

Assurance should consider relevant threats including:

- manipulated inputs;
- sensor spoofing;
- adversarial examples;
- data poisoning;
- model manipulation;
- prompt or instruction manipulation;
- retrieval manipulation;
- interface exploitation;
- cyber compromise; and
- deliberate denial of service.

---

## P-12 — Least Authority

An AI capability should receive only the permissions necessary for its authorised mission.

Permissions may include access to:

- data;
- systems;
- tools;
- communications;
- external services;
- planning functions;
- actuation; or
- other AI systems.

AI shall not possess authority to grant itself additional permissions.

> **Capability does not imply authority.**

---

## P-13 — Defence in Depth

No single control should be assumed to provide complete protection for a high-consequence AI capability.

Protection should be distributed across appropriate layers, which may include:

- model safeguards;
- input validation;
- access controls;
- policy enforcement;
- human authority;
- monitoring;
- independent controls;
- fail-safe mechanisms;
- isolation; and
- incident response.

---

## P-14 — No AI Self-Expansion of Authority

An AI system shall not be permitted to independently expand its:

- operational permissions;
- autonomy;
- mission scope;
- system access;
- communication authority; or
- ability to modify critical behaviour.

Any material expansion of authority requires authorised human governance.

---

# 5. Operational Principles

## P-15 — Operational Independence and Resilience

Critical AI capabilities should be assessed for their ability to operate safely and predictably when normal supporting conditions are unavailable or degraded.

Relevant conditions may include:

- limited connectivity;
- intermittent communications;
- degraded sensors;
- incomplete information;
- constrained computing resources;
- power limitations;
- environmental stress; and
- loss of external services.

---

## P-16 — Controlled Degradation

AI capabilities should have defined responses to degraded conditions.

A capability should not simply transition from normal operation to uncontrolled failure.

Possible states include:

```text
Normal
   ↓
Restricted
   ↓
Human-Only / Manual
   ↓
Suspended
   ↓
Safe State
   ↓
Emergency Shutdown
