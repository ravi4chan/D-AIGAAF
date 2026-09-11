# 10-Crosswalk to Defence AI and Responsible AI Principles

## 1. Purpose

This document establishes a crosswalk between D-AIGAAF — Defence AI Governance, Assurance & Operational Authorisation Framework and major **defence AI responsible-use and responsible-AI principles**.

The purpose is to identify the common principles that have emerged across defence AI governance and to show how D-AIGAAF converts those principles into an integrated governance architecture for consequential defence AI.

This crosswalk is deliberately broader than the IndiaAI-focused files in Serials 06–09.

It considers defence-AI governance references including:

- NATO Principles of Responsible Use for AI in Defence;
- NATO AI governance and autonomy work;
- United States Department of Defense Responsible AI principles and implementation work;
- United Kingdom Ministry of Defence dependable-AI policy;
- broader international responsible-AI principles relevant to defence.

These sources are used as **reference frameworks**, not as legal requirements for India or as authorities over D-AIGAAF.

## 2. Why Defence AI Principles Need a Separate Crosswalk

General responsible-AI principles provide a valuable foundation, but defence applications introduce additional governance questions.

A defence AI system may operate:

- in time-critical environments;
- under adversarial conditions;
- with incomplete information;
- with degraded communications;
- in contested electromagnetic environments;
- alongside human operators;
- as part of a larger system of systems;
- with varying degrees of autonomy;
- where errors can have severe consequences.

NATO's Principles of Responsible Use establish six core principles for defence AI: **lawfulness; responsibility and accountability; explainability and traceability; reliability; governability; and bias mitigation**. NATO states that these principles apply across AI application types and across the lifecycle. citeturn0search0turn0search15

D-AIGAAF adopts these broad principles while adding explicit mechanisms for:

**Mission → Risk → Autonomy → Human Authority → TEVV → Environment → Authorisation → Employment → Continuous Assurance**

## 3. Reference Defence AI Principles

### NATO

NATO's Principles of Responsible Use for AI in Defence establish:

1. Lawfulness.
2. Responsibility and Accountability.
3. Explainability and Traceability.
4. Reliability.
5. Governability.
6. Bias Mitigation.

NATO also links these principles to lifecycle governance, risk/impact assessment, testing, assurance and responsible use of autonomy. citeturn0search0turn0search6

### United States Department of Defense

The U.S. Department of Defense adopted five AI ethical principles:

1. Responsible.
2. Equitable.
3. Traceable.
4. Reliable.
5. Governable.

The principles apply to combat and non-combat AI and are intended to govern development, deployment and use. citeturn0search8turn0search9

The later Responsible AI Strategy and Implementation Pathway translates those principles into a broader implementation approach across AI development, testing, procurement, deployment and use. citeturn0search44

### United Kingdom Ministry of Defence

The UK's JSP 936 establishes a principal policy framework for dependable AI in defence and provides direction on governance, development and assurance throughout the AI lifecycle, including quality, safety, security and human oversight. citeturn0search5

These defence frameworks converge strongly around several ideas:

- lawful use;
- human responsibility;
- clear use cases;
- reliability;
- safety;
- security;
- explainability;
- traceability;
- governability;
- testing and assurance;
- bias mitigation;
- lifecycle governance.

## 4. High-Level Crosswalk

| Defence AI Principle | D-AIGAAF Modules | D-AIGAAF Extension |
|---|---|---|
| Lawfulness | 01 Governance; 02 Mission; 21 Legal & Policy | Links legal requirements to mission, use case, authority and employment |
| Responsibility | 01 Governance; 08 Human Authority; 17 Workforce | Establishes named roles, decision rights and accountable authorities |
| Accountability | 01 Governance; 08 Human Authority; 11 Authorisation; 16 Audit | Makes operational accountability traceable |
| Explainability | 08 Human Authority; 09 TEVV; 12 Employment | Makes explanation decision-relevant and proportionate to consequence |
| Traceability | 04 Lifecycle; 05 Data; 16 Audit; 25 Documentation | Establishes lifecycle, data, configuration and decision traceability |
| Reliability | 03 Risk; 09 TEVV; 10 Environment; 13 Assurance | Tests reliability in mission-relevant conditions |
| Governability | 03 Risk; 08 Human Authority; 11 Authorisation; 14 Fail-Safe | Adds autonomy boundaries, intervention, disengagement and safe-state controls |
| Bias Mitigation / Equity | 05 Data; 09 TEVV; 13 Assurance | Applies contextual bias and performance assessment |
| Safety | 03 Risk; 09 TEVV; 14 Incident & Fail-Safe | Connects safety to consequence, testing and recovery |
| Security | 06 AI Security; 07 Supply Chain; 14 Incident | Adds AI-specific security and adversarial controls |
| Human Oversight | 08 Human Authority; 12 Employment; 17 Workforce | Defines meaningful human control |
| Lifecycle Assurance | 04 Lifecycle; 13 Assurance; 15 Change | Maintains confidence through system life |
| Operational Readiness | 09 TEVV; 10 Environment; 11 Authorisation | Separates technical assurance from permission to operate |

## 5. Lawfulness

Defence AI must operate within applicable law and policy.

NATO explicitly identifies lawfulness as a responsible-use principle and states that AI applications should comply with applicable national and international law, including international humanitarian law and human rights law as applicable. citeturn0search0

D-AIGAAF incorporates lawfulness through:

- mission purpose;
- legal and policy assessment;
- use-case definition;
- operational constraints;
- human authority;
- operational authorisation;
- audit;
- evidence.

The framework does not treat legal review as a one-time activity.

Material changes in:

- mission;
- system capability;
- autonomy;
- operating environment;
- applicable law;
- employment concept

may require renewed legal and governance assessment.

## 6. Responsibility and Accountability

Defence AI principles consistently reject ambiguous responsibility.

D-AIGAAF converts this principle into explicit governance.

Every consequential AI capability should have identifiable responsibility for:

- mission approval;
- system governance;
- risk acceptance;
- TEVV;
- operational authorisation;
- employment;
- monitoring;
- incident response;
- change approval.

The core D-AIGAAF rule is:

> **AI may influence a decision, but responsibility for a consequential decision must remain attributable to an appropriately authorised human or organisation.**

This is particularly important as AI systems become more autonomous.

## 7. Explainability

Defence AI principles require appropriate understandability.

D-AIGAAF treats explainability as a function of:

- consequence;
- autonomy;
- mission;
- operational tempo;
- human competence;
- uncertainty;
- system complexity.

A useful operational explanation may need to communicate:

- what the AI assessed;
- what it produced;
- material factors;
- confidence or uncertainty;
- known limitations;
- relevant assumptions;
- whether the output is within validated conditions.

D-AIGAAF therefore distinguishes:

**Technical interpretability**

from

**Decision-relevant explainability**.

The second is the primary operational objective.

## 8. Traceability

Traceability is a common principle across defence AI frameworks.

D-AIGAAF extends it across:

### Data
Source, provenance, lineage and transformation.

### Model
Version, configuration, training and update history.

### System
Components, dependencies and interfaces.

### TEVV
Tests, findings, limitations and evidence.

### Authority
Who approved what, under which conditions.

### Employment
How the capability was used.

### Decision
Relevant human and AI contributions.

### Incident
What happened and what actions were taken.

### Change
What changed and why.

This creates an auditable chain:

**Requirement → Design → Data → Model → Test → Evidence → Authorisation → Employment → Outcome**

## 9. Reliability

NATO and U.S. DoD principles both emphasise reliable AI with explicit and well-defined use cases. NATO specifically links reliability to safety, security, robustness, testing and assurance across the lifecycle. citeturn0search0turn0search8

D-AIGAAF expands reliability into:

- technical reliability;
- data reliability;
- environmental robustness;
- operational reliability;
- human-AI interaction reliability;
- security resilience;
- recovery reliability.

A model that performs reliably in a laboratory but fails under operational conditions has not demonstrated sufficient mission reliability.

## 10. Governability

Governability is one of the most important defence-AI principles.

NATO defines governability in terms including intended-function behaviour, appropriate human-machine interaction, ability to detect and avoid unintended consequences, and ability to disengage or deactivate systems exhibiting unintended behaviour. citeturn0search0

D-AIGAAF operationalises governability through:

- autonomy classification;
- autonomy boundaries;
- human decision rights;
- intervention;
- override;
- disengagement;
- safe state;
- fail-safe mechanisms;
- operational constraints;
- monitoring;
- incident response;
- reauthorisation.

The core principle is:

> **A system that cannot be meaningfully governed should not be granted a level of autonomy that exceeds available human control.**

## 11. Bias Mitigation and Equity

Defence AI principles recognise the risk of unintended bias.

D-AIGAAF incorporates this through:

- data representativeness;
- bias assessment;
- relevant subgroup/condition testing;
- mission-context analysis;
- performance monitoring;
- corrective action.

The framework avoids assuming that a single fairness metric is appropriate for every defence AI system.

Instead:

> **Bias assessment should be proportionate to the system's purpose, affected populations, mission consequences and applicable law.**

## 12. Safety

Safety is not treated as a single technical attribute.

D-AIGAAF distributes safety across:

- risk assessment;
- requirements;
- system design;
- TEVV;
- operational environment;
- human control;
- authorisation;
- fail-safe;
- incident management;
- continuous assurance.

The safety lifecycle is:

**Identify Hazard → Assess Risk → Design Controls → Test → Evidence → Authorise → Monitor → Respond → Learn**

## 13. Security

Defence AI principles increasingly recognise security as integral to trustworthy AI.

D-AIGAAF provides a dedicated AI-security architecture covering:

- threat modelling;
- adversarial AI;
- model security;
- data security;
- supply-chain security;
- dependency risks;
- access control;
- secure updates;
- incident response;
- autonomy-security interaction.

The framework recognises that compromise of an AI system can alter not only confidentiality or integrity, but potentially:

- decisions;
- recommendations;
- autonomy;
- timing;
- human trust;
- operational outcomes.

## 14. Human Oversight and Meaningful Human Control

Defence AI principles consistently retain a role for human responsibility and appropriate human-machine interaction.

D-AIGAAF goes further by defining meaningful human control in terms of:

- authority;
- competence;
- information;
- situational awareness;
- time;
- intervention;
- override;
- termination;
- workload.

The framework distinguishes:

**Human in the system**

from

**Human supervising**

from

**Human controlling**

from

**Human accountable**.

These should not be assumed to be equivalent.

## 15. Autonomy

Autonomy is a central D-AIGAAF extension.

D-AIGAAF uses the working autonomy scale:

| Level | Description |
|---|---|
| A0 | No Meaningful AI Decision |
| A1 | Information / Observation |
| A2 | Analysis / Recommendation |
| A3 | Human-Authorised Action |
| A4 | Supervised Autonomous Action |
| A5 | Independent Consequential Autonomy |

The level is not itself an authorisation.

It describes the relationship between AI capability, human authority and action.

As autonomy and consequence increase, D-AIGAAF generally requires stronger:

- evidence;
- assurance;
- human authority;
- operational constraints;
- fail-safe mechanisms;
- monitoring;
- authorisation.

## 16. Autonomy and International Humanitarian Law

Autonomous defence systems raise legal and governance questions that cannot be resolved solely through technical performance.

NATO's autonomy work explicitly states that its responsible-use principles apply to AI-enabled autonomous systems and notes that international humanitarian law continues to apply to weapons systems, including emerging technologies in the area of lethal autonomous weapons systems. citeturn0search6

D-AIGAAF therefore requires applicable legal review to remain connected to:

- mission;
- target/use-case definition where relevant;
- autonomy;
- human authority;
- operational constraints;
- TEVV;
- authorisation.

This framework does not attempt to define international law or establish legal conclusions for particular weapons systems.

## 17. Lifecycle Governance

Defence AI principles apply across the lifecycle.

D-AIGAAF implements this as:

**Need → Requirements → Development / Acquisition → Data → Model → Integration → TEVV → Readiness → Authorisation → Employment → Monitoring → Change → Revalidation → Reauthorisation → Retirement**

This prevents responsible-AI governance from becoming concentrated only at procurement or deployment.

## 18. TEVV and Assurance

Defence AI principles strongly support testing and assurance.

NATO explicitly links reliability to testing and assurance throughout the lifecycle, while U.S. DoD principles similarly require testing and assurance within defined uses. citeturn0search0turn0search8

D-AIGAAF treats TEVV evidence as one input into an assurance decision.

But:

**TEVV ≠ Assurance ≠ Authorisation**

They are connected but distinct.

- **TEVV:** What did we test and what did we find?
- **Assurance:** How confident are we that the capability remains fit for its intended use?
- **Authorisation:** Who has formally permitted this capability to be used under defined conditions?

## 19. Operational Environment

A major D-AIGAAF extension is explicit governance of the operational environment.

The system should be assessed for relevant:

- terrain;
- weather;
- electromagnetic conditions;
- communications availability;
- data availability;
- adversarial activity;
- human workload;
- infrastructure dependencies;
- degraded conditions.

NATO's current digital strategy also highlights AI use at the tactical edge for situational awareness and risk-informed decision support in contested environments. citeturn0search12

D-AIGAAF therefore treats operational environment as a governance variable rather than merely a deployment parameter.

## 20. Degraded and Disconnected Operations

Defence AI may need to operate when:

- communications are intermittent;
- cloud connectivity is unavailable;
- external services fail;
- positioning data is degraded;
- supporting infrastructure is unavailable;
- data is incomplete or stale.

D-AIGAAF requires explicit assessment of:

- expected behaviour;
- fallback;
- uncertainty communication;
- autonomy reduction;
- human intervention;
- safe state;
- recovery;
- reauthorisation triggers.

The principle is:

> **Loss of connectivity must not silently create unintended authority or unsafe autonomy.**

## 21. Defence Supply Chain

Responsible defence AI extends beyond the organisation that operates the system.

D-AIGAAF therefore governs:

- suppliers;
- foundation-model providers;
- datasets;
- software dependencies;
- hardware;
- cloud services;
- update mechanisms;
- external APIs;
- maintenance providers.

Relevant risks include:

- hidden dependencies;
- compromised updates;
- supplier changes;
- loss of access;
- foreign dependency;
- model substitution;
- unexplained behaviour changes.

This links responsible AI with sovereignty and continuity.

## 22. Defence Interoperability

Defence AI increasingly operates across:

- multiple systems;
- services;
- nations;
- suppliers;
- coalition partners;
- command structures.

NATO identifies interoperability as a major objective of its AI strategy and uses common responsible-use principles as a baseline for Allies. citeturn0search0

D-AIGAAF therefore treats interoperability as a governance issue as well as a technical issue.

Interoperability should not silently transfer:

- authority;
- responsibility;
- data;
- autonomy;
- trust assumptions.

The governance conditions for interoperability should be explicit.

## 23. Crosswalk to NATO Principles

| NATO Principle | D-AIGAAF Implementation |
|---|---|
| Lawfulness | 01 Governance; 21 Legal & Policy |
| Responsibility & Accountability | 01 Governance; 08 Human Authority; 16 Audit |
| Explainability & Traceability | 08 Human Authority; 09 TEVV; 16 Audit; 25 Documentation |
| Reliability | 03 Risk; 09 TEVV; 10 Environment; 13 Assurance |
| Governability | 03 Risk; 08 Human Authority; 11 Authorisation; 14 Fail-Safe |
| Bias Mitigation | 05 Data; 09 TEVV; 13 Assurance |

NATO itself describes these principles as a baseline for responsible defence AI and states that they should be operationalised across the lifecycle. citeturn0search0

## 24. Crosswalk to U.S. DoD Principles

| DoD Principle | D-AIGAAF Implementation |
|---|---|
| Responsible | 01 Governance; 08 Human Authority; 17 Workforce |
| Equitable | 05 Data; 09 TEVV; 13 Assurance |
| Traceable | 04 Lifecycle; 05 Data; 16 Audit |
| Reliable | 03 Risk; 09 TEVV; 10 Environment |
| Governable | 03 Risk; 08 Human Authority; 11 Authorisation; 14 Fail-Safe |

The U.S. DoD's implementation work also emphasises governance, oversight, risk management, lifecycle integration and an AI-ready workforce, which align closely with D-AIGAAF's architecture. citeturn0search4turn0search9

## 25. Crosswalk to UK Defence AI Policy

UK JSP 936 provides a defence policy framework for dependable AI, including governance, development and assurance across the AI lifecycle and considerations of quality, safety, security and human oversight. citeturn0search5

D-AIGAAF aligns these concepts through:

- lifecycle governance;
- requirements;
- risk;
- TEVV;
- security;
- human authority;
- operational environment;
- assurance;
- authorisation;
- continuous monitoring.

D-AIGAAF extends the architecture by making **operational authorisation** a distinct governance state.

## 26. D-AIGAAF Extensions Beyond Common Defence Principles

Common defence AI principles provide strong foundations.

D-AIGAAF adds explicit mechanisms for:

### Mission Consequence
Governance intensity depends on potential consequences.

### Autonomy
Autonomy is treated as an explicit risk and authority variable.

### Operational Environment
Fitness is assessed in the environment in which the capability will actually operate.

### Operational Authorisation
Assurance does not automatically equal permission.

### Operational Employment
Governance continues during actual use.

### Degraded Operations
Loss of communications or infrastructure is explicitly governed.

### Fail-Safe
Unexpected behaviour triggers defined protective responses.

### Reauthorisation
Material changes or incidents can invalidate previous authority.

### Continuous Assurance
Confidence must remain justified over time.

### Workforce
Competence and capacity become explicit governance controls.

## 27. Defence Responsible-AI Golden Thread

The crosswalk can be expressed as:

**Lawfulness**
→ Mission Purpose

**Responsibility**
→ Governance

**Risk**
→ Requirements

**Traceability**
→ Data / Lifecycle Records

**Reliability**
→ TEVV

**Governability**
→ Human Authority / Autonomy Controls

**Security**
→ AI Security

**Operational Context**
→ Environment Assessment

**Evidence**
→ Assurance

**Authority**
→ Operational Authorisation

**Employment**
→ Controlled Operational Use

**Monitoring**
→ Continuous Assurance

**Incident / Change**
→ Revalidation

**Reauthorisation**
→ Renewed Operational Authority

## 28. Evidence Expectations

Evidence supporting defence responsible-AI alignment may include:

- legal review;
- use-case definition;
- risk assessment;
- autonomy assessment;
- human-authority assignment;
- data-provenance records;
- model/system documentation;
- TEVV evidence;
- security assessment;
- operational-environment assessment;
- deployment-readiness assessment;
- authorisation decision;
- operating conditions;
- monitoring results;
- incident records;
- change records;
- revalidation results;
- reauthorisation decisions.

A responsible-AI claim should therefore be demonstrable through evidence.

## 29. Relationship to Other Module 19 Crosswalks

Serial 10 sits between the general Indian/international governance references and the more technical assurance/security crosswalks.

It complements:

- **Serial 06:** IndiaAI Responsible AI Governance Framework;
- **Serial 07:** IndiaAI Governance Guidelines;
- **Serial 08:** India DPDP Framework;
- **Serial 09:** Indian AI Policy and Standards;
- **Serial 11:** TEVV and AI Assurance Frameworks;
- **Serial 12:** AI Security and Adversarial Frameworks;
- **Serial 13:** Integrated D-AIGAAF Crosswalk and Alignment Method.

The purpose is to establish the **defence responsible-AI principle layer** before moving into detailed assurance and security frameworks.

## 30. Limitations

This crosswalk does not claim:

- that NATO principles are Indian law;
- that U.S. DoD principles apply automatically to Indian defence organisations;
- that UK MOD policy applies to India;
- that these principles create legal obligations for third parties;
- that responsible-AI principles establish operational authorisation;
- that adherence eliminates AI risk;
- that technical testing alone demonstrates responsible use.

The referenced defence frameworks are used as comparative governance sources.

## 31. Implementation Guidance

Organisations applying D-AIGAAF should:

1. Identify applicable defence-AI principles.
2. Determine their normative or legal status.
3. Map them to D-AIGAAF modules.
4. Convert relevant principles into requirements.
5. Identify controls.
6. Define evidence.
7. Evaluate the controls through TEVV and assurance.
8. Assign human authority.
9. Establish operational conditions.
10. Authorise use only when applicable requirements are satisfied.
11. Monitor continued fitness.
12. Revalidate and reauthorise following material changes.

## 32. Final Crosswalk Position

Defence AI governance is converging around a common set of principles:

**Lawfulness → Responsibility → Accountability → Explainability → Traceability → Reliability → Governability → Bias Mitigation**

D-AIGAAF retains these principles but converts them into a more complete operational governance architecture:

**Principles → Mission → Risk → Requirements → Controls → TEVV → Evidence → Assurance → Human Authority → Operational Authorisation → Employment → Monitoring → Incident / Change → Revalidation → Reauthorisation**

The central D-AIGAAF proposition is:

> **Responsible defence AI requires more than responsible principles. It requires an auditable system that converts those principles into requirements, evidence, human authority and controlled operational use.**

This is the bridge between **responsible-AI policy** and **operationally governed defence AI**.
