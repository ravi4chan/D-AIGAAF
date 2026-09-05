# D-AIGAAF

## Defence AI Governance, Assurance & Operational Authorisation Framework

D-AIGAAF is a defence-specific lifecycle framework for governing, securing, testing, assuring, authorising, employing and continuously monitoring AI-enabled capabilities according to mission, environment, autonomy, consequence and human authority.

---

## 1. Purpose

AI systems are increasingly capable of supporting intelligence, logistics, decision support, planning, sensing, communications, cyber operations and other defence functions.

In defence, however, demonstrating that an AI system works is not sufficient.

A defence organisation must also determine:

- whether the system is suitable for a particular mission;
- what could go wrong;
- whether its behaviour remains reliable under operational and adversarial conditions;
- what level of human authority is required;
- whether the system can operate safely when information, sensors, communications or infrastructure degrade;
- whether its supply chain and dependencies can be trusted;
- whether sufficient evidence exists to justify operational employment;
- who has authority to permit its use; and
- whether that trust remains valid after deployment, changes, incidents or changes in the operational environment.

D-AIGAAF provides a structured method for addressing these questions across the AI lifecycle.

---

## 2. Central Question

> **Can this AI capability be trusted to perform this mission, under these conditions, at this level of autonomy, with this level of human authority?**

This question connects technical capability with operational context, assurance and command authority.

---

## 3. What D-AIGAAF Does

D-AIGAAF connects:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

This is the framework's **Golden Thread**.

Every significant AI capability should be traceable through this chain.

---

## 4. Reference Model

D-AIGAAF is organised around six primary layers.

### Layer 1 — Strategy & Governance

Establishes:

- strategic objectives;
- governance structures;
- accountability;
- policy;
- acceptable risk;
- institutional priorities; and
- organisational responsibilities.

### Layer 2 — Mission & Risk

Determines:

- why AI is required;
- the intended mission;
- the operational use case;
- potential consequences;
- autonomy;
- mission criticality;
- operational environment; and
- human control.

### Layer 3 — System & Trust

Addresses:

- AI models;
- software and hardware;
- data and information;
- sensors and interfaces;
- cybersecurity;
- supply chain;
- dependencies;
- configuration;
- permissions; and
- sovereignty.

### Layer 4 — Assurance

Provides evidence through:

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

### Layer 5 — Operational Authorisation

Determines whether a specific AI capability may be employed for:

**a particular mission + environment + autonomy + configuration + human authority.**

Operational authorisation is therefore conditional rather than a permanent declaration that an AI system is "approved".

### Layer 6 — Continuous Assurance

Continues after deployment through:

- operational monitoring;
- performance assessment;
- anomaly detection;
- incident management;
- configuration control;
- change assessment;
- revalidation; and
- reauthorisation.

> **Operational authorisation is not the end of assurance. It is the beginning of continuous assurance.**

---

## 5. Cross-Cutting Areas

The six layers are supported by several cross-cutting functions:

- Human Authority
- AI Security
- Information Assurance
- Legal & Policy
- Workforce & Competency
- Supply Chain & Sovereignty

These functions operate across the lifecycle rather than belonging to a single stage.

---

## 6. Defence-Specific Focus

D-AIGAAF is designed around characteristics that can materially change the assurance problem in defence.

These include:

- mission-specific assurance;
- operational environments;
- degraded and disconnected operations;
- adversarial conditions;
- graduated autonomy;
- meaningful human control;
- command authority;
- AI-to-AI interaction;
- loss-of-control risks;
- operational envelopes;
- supply-chain dependencies;
- continuous assurance;
- change and reauthorisation; and
- retirement and withdrawal of operational authority.

The framework therefore focuses not only on whether an AI system is technically capable, but on **whether it can be responsibly and authoritatively employed in a defined defence context**.

---

## 7. Operational Trust

D-AIGAAF uses the following conceptual model:

> **Operational Trust = Capability + Evidence + Context + Human Authority + Continuous Assurance**

This is not a mathematical equation.

It expresses the idea that technical capability alone does not establish operational trust.

---

## 8. Risk → Assurance → Authority

D-AIGAAF separates three related but different questions.

### Risk

> What could go wrong, and how serious could the consequences be?

### Assurance

> Does the available evidence demonstrate sufficient trustworthiness for the intended use?

### Authority

> Given the evidence, risk, law, policy and operational context, should the organisation permit employment?

Therefore:

> **Passing assurance does not automatically create operational authority.**

---

## 9. Operational Authorisation

D-AIGAAF defines operational authorisation around five dimensions:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

An authorisation should therefore specify, at minimum:

- the AI capability;
- approved mission/use case;
- approved environment;
- approved autonomy;
- operational envelope;
- required human authority;
- assurance evidence;
- known limitations;
- failure modes;
- fail-safe arrangements;
- configuration baseline;
- dependencies;
- authorising authority;
- validity/review period; and
- suspension, revocation and reauthorisation conditions.

Authorisation for one mission or configuration must not automatically be assumed to apply to another.

> **No Silent Expansion of Authority.**

---

## 10. Lifecycle

The D-AIGAAF lifecycle is:

Strategic Need
      ↓
Mission Need
      ↓
Requirements
      ↓
Risk & Autonomy
      ↓
Acquisition
      ↓
Design / Development
      ↓
Test, Evaluation & Verification
      ↓
Operational Environment
      ↓
AI Assurance
      ↓
Operational Authorisation
      ↓
Deployment
      ↓
Operational Employment
      ↓
Continuous Monitoring
      ↓
Change / Incident
      ↓
Revalidation
      ↓
Reauthorisation
      ↓
Retirement

___
## 11. Repository Structure

The repository is organised into numbered modules representing the major components of D-AIGAAF.

The numbering provides stable navigation and does not imply that the modules are executed sequentially. Many modules operate across the AI lifecycle and are cross-cutting in nature.

```text
D-AIGAAF
│
├── 00 Framework
│   ├── Reference Model
│   ├── Principles
│   ├── Terminology
│   ├── Lifecycle
│   └── Golden Thread
│
├── 01 Strategy & Governance
├── 02 Mission & Use Case
├── 03 Risk & Autonomy
├── 04 AI Lifecycle
├── 05 Data & Information
├── 06 AI Security
├── 07 Supply Chain & Sovereignty
├── 08 Human Authority
├── 09 TEVV
├── 10 Operational Environment
├── 11 Operational Authorisation
├── 12 Operational Employment
├── 13 Continuous Assurance
├── 14 Incident & Fail-Safe
├── 15 Change & Reauthorisation
├── 16 Audit & Evidence
├── 17 Workforce
├── 18 Maturity Model
├── 19 Crosswalks
├── 20 Templates
├── 21 Legal & Policy
├── 22 Acquisition & Procurement
├── 23 Interoperability & Coalition
├── 24 Architecture & Technical Controls
├── 25 Documentation & Knowledge
├── 26 Retirement & Decommissioning
└── 27 Implementation
