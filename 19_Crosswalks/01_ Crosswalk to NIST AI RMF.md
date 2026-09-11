# 01-Crosswalk to NIST AI RMF

## 1. Purpose

This crosswalk maps D-AIGAAF against the **NIST Artificial Intelligence Risk Management Framework (AI RMF) 1.0**.

NIST AI RMF 1.0 was published in January 2023 as a voluntary, non-sector-specific and use-case-agnostic framework intended to help organisations manage AI risks and promote trustworthy and responsible AI. Its Core is organised around four functions:

**GOVERN → MAP → MEASURE → MANAGE**

NIST describes GOVERN as a cross-cutting function that informs and is integrated with the other three functions. The framework is intended to be applied continuously throughout the AI lifecycle.

As of the preparation of this crosswalk, NIST states that AI RMF 1.0 is being revised. This crosswalk therefore identifies the assessed edition and should be reviewed when a revised authoritative version is released.

## 2. Crosswalk Interpretation

The relationship between D-AIGAAF and NIST AI RMF is complementary.

NIST AI RMF provides a broad, voluntary AI risk-management structure applicable across sectors and use cases. D-AIGAAF adapts the underlying governance logic to defence environments where AI may operate under:

- consequential mission conditions;
- varying levels of autonomy;
- adversarial conditions;
- degraded or disconnected communications;
- changing operational environments;
- human command authority;
- mission-specific risk;
- operational authorisation requirements; and
- continuous operational employment.

D-AIGAAF therefore should not be represented as a replacement for NIST AI RMF. It can instead function as a defence-specific governance and operational-authorisation framework that incorporates and extends compatible AI risk-management concepts.

## 3. High-Level Mapping

| NIST AI RMF Function | Principal D-AIGAAF Coverage | Relationship |
|---|---|---|
| GOVERN | 01 Strategy & Governance; 08 Human Authority; 17 Workforce; 16 Audit & Evidence; 19 Crosswalks | Direct Alignment + Defence Extension |
| MAP | 02 Mission & Use Case; 03 Risk & Autonomy; 10 Operational Environment; 05 Data & Information | Direct Alignment + Defence Extension |
| MEASURE | 09 TEVV; 13 Continuous Assurance; 16 Audit & Evidence; 06 AI Security | Direct Alignment + Defence Extension |
| MANAGE | 03 Risk & Autonomy; 11 Operational Authorisation; 12 Operational Employment; 14 Incident & Fail-Safe; 15 Change & Reauthorisation; 13 Continuous Assurance | Direct Alignment + Defence Extension |
| Trustworthiness characteristics | 03, 05, 06, 08, 09, 10, 12, 13, 14 | Complementary / Extended Operationalisation |
| Lifecycle risk management | 04 AI Lifecycle | Direct Alignment + Extension |
| Documentation and accountability | 01, 08, 16, 17, 25 | Direct Alignment |
| Continuous monitoring and improvement | 13, 14, 15, 16, 18, 27 | Direct Alignment + Defence Extension |
| Operational authority | 11 Operational Authorisation | D-AIGAAF Specific |
| Defence operational employment | 12 Operational Employment | D-AIGAAF Specific |
| Explicit autonomy governance | 03 Risk & Autonomy; 11 Operational Authorisation | Defence Extension |
| Mission-authority-environment relationship | 02, 10, 11, 12 | D-AIGAAF Specific |

## 4. GOVERN Crosswalk

### NIST Objective

The GOVERN function establishes organisational policies, processes, procedures, practices, accountability, risk-management culture, legal and regulatory awareness, and governance structures for AI risk management.

### D-AIGAAF Alignment

D-AIGAAF provides extensive coverage through:

- **Module 01 — Strategy & Governance**
- **Module 08 — Human Authority**
- **Module 16 — Audit & Evidence**
- **Module 17 — Workforce**
- **Module 18 — Maturity Model**
- **Module 19 — Crosswalks**
- **Module 21 — Legal & Policy**
- **Module 25 — Documentation & Knowledge**
- **Module 27 — Implementation**

These modules establish governance structures, decision rights, accountability, policy alignment, workforce competence, evidence, audit, records, maturity, and implementation.

### Defence Extension

D-AIGAAF extends the governance concept by making **operational authority** an explicit governance object.

In D-AIGAAF, governance must ultimately answer:

- Who has authority to approve the AI capability?
- For which mission?
- Under what conditions?
- At what autonomy level?
- In which operational environment?
- With what human authority?
- Based on what evidence?
- For how long?
- What changes invalidate the decision?

This creates a stronger connection between organisational governance and operational authority than a general enterprise AI governance model normally requires.

## 5. MAP Crosswalk

### NIST Objective

The MAP function establishes context, intended purpose, users, impacts, risks, assumptions, limitations, and other contextual factors necessary to understand AI risk.

### D-AIGAAF Alignment

D-AIGAAF provides detailed coverage through:

- **Module 02 — Mission & Use Case**
- **Module 03 — Risk & Autonomy**
- **Module 05 — Data & Information**
- **Module 06 — AI Security**
- **Module 07 — Supply Chain & Sovereignty**
- **Module 10 — Operational Environment**

The D-AIGAAF mission and operational-context architecture is particularly relevant to NIST's emphasis on establishing and understanding context.

### Defence Extension

D-AIGAAF treats context as more than a deployment setting.

It explicitly links:

**Mission → Consequence → Risk → Autonomy → Human Authority → Environment → Dependencies**

This is important because the same AI capability may present materially different risks when:

- used for information support;
- used for recommendations;
- permitted to initiate an action;
- operating under degraded communications;
- operating in an adversarial environment; or
- operating with increasing autonomy.

## 6. MEASURE Crosswalk

### NIST Objective

The MEASURE function uses quantitative, qualitative, or mixed methods to assess, analyse, benchmark, and monitor AI risk and trustworthiness. It includes measurement, testing, evaluation, uncertainty, documentation, and independent review.

### D-AIGAAF Alignment

Strong alignment exists through:

- **Module 09 — TEVV**
- **Module 13 — Continuous Assurance**
- **Module 16 — Audit & Evidence**
- **Module 06 — AI Security**
- **Module 03 — Risk & Autonomy**
- **Module 10 — Operational Environment**

D-AIGAAF explicitly requires evidence for assurance claims and distinguishes technical evidence from continuing operational confidence.

### Defence Extension

D-AIGAAF expands measurement into operational acceptability.

Measurement is not limited to:

**Does the model perform?**

It also asks:

- Does it perform within the intended operational environment?
- Is uncertainty adequately communicated?
- Can humans understand and appropriately use its outputs?
- Does autonomy remain within authorised boundaries?
- Can human intervention occur when required?
- Does performance remain acceptable under degraded conditions?
- Does a change invalidate previous evidence?
- Does continued operation remain justified?

This connects measurement to operational authorisation and continuous assurance.

## 7. MANAGE Crosswalk

### NIST Objective

The MANAGE function prioritises and responds to AI risks based on outputs from MAP and MEASURE. It includes risk treatment, deployment decisions, incident response, monitoring, and continual improvement.

### D-AIGAAF Alignment

D-AIGAAF provides particularly strong alignment through:

- **Module 03 — Risk & Autonomy**
- **Module 11 — Operational Authorisation**
- **Module 12 — Operational Employment**
- **Module 13 — Continuous Assurance**
- **Module 14 — Incident & Fail-Safe**
- **Module 15 — Change & Reauthorisation**
- **Module 16 — Audit & Evidence**
- **Module 18 — Maturity Model**
- **Module 27 — Implementation**

### Defence Extension

D-AIGAAF introduces an explicit sequence:

**Assurance → Authority → Conditions → Boundaries → Employment → Monitoring**

This creates a formal distinction between knowing that an AI system has been assessed and deciding that it may be used for a particular mission under defined conditions.

## 8. Trustworthiness Characteristics Crosswalk

NIST AI RMF identifies characteristics of trustworthy AI including validity and reliability, safety, security and resilience, accountability and transparency, explainability and interpretability, privacy enhancement, and fairness with harmful bias managed.

D-AIGAAF addresses these characteristics across multiple modules rather than treating them as isolated attributes.

| NIST Trustworthiness Area | D-AIGAAF Coverage | Defence Consideration |
|---|---|---|
| Valid and reliable | 09 TEVV; 13 Continuous Assurance | Mission-specific performance and reliability |
| Safe | 03 Risk & Autonomy; 14 Incident & Fail-Safe | Consequential actions and safe-state requirements |
| Secure and resilient | 06 AI Security; 10 Operational Environment | Adversarial, degraded, disconnected conditions |
| Accountable and transparent | 01 Governance; 08 Human Authority; 16 Audit | Explicit decision authority and traceability |
| Explainable and interpretable | 08 Human Authority; 12 Operational Employment; 09 TEVV | Sufficient understanding for human decisions |
| Privacy enhanced | 05 Data & Information; 21 Legal & Policy | Context-specific data governance |
| Fair / harmful bias managed | 05 Data & Information; 09 TEVV; 21 Legal & Policy | Mission- and context-dependent impact assessment |

The mapping should not imply that every NIST characteristic has identical meaning in every defence context. Applicability must be assessed according to mission, legal framework, operational environment, and use case.

## 9. Lifecycle Crosswalk

NIST AI RMF is intended to support AI risk management throughout lifecycle dimensions.

D-AIGAAF makes lifecycle governance explicit in **Module 04 — AI Lifecycle**:

**Need → Requirements → Development/Acquisition → Data/Model → Integration → Configuration → TEVV → Deployment → Employment → Monitoring → Change → Revalidation → Reauthorisation → Retirement → Decommissioning**

The relationship is complementary.

NIST provides a cross-cutting risk-management structure. D-AIGAAF adds a more explicit lifecycle governance mechanism for operational authorisation and continued employment of consequential defence AI.

## 10. Risk Management Crosswalk

NIST's four functions can be viewed alongside the D-AIGAAF Golden Thread:

| NIST AI RMF | D-AIGAAF Golden Thread |
|---|---|
| GOVERN | Governance, Authority, Workforce, Accountability |
| MAP | Mission, Risk, Context, Environment, Dependencies |
| MEASURE | Testing, Evidence, Assurance |
| MANAGE | Treatment, Authorisation, Employment, Incident, Change |

D-AIGAAF then extends this cycle through:

**Revalidation → Reauthorisation → Workforce → Maturity → Continuous Improvement**

This is particularly important for AI systems whose operational risk changes after deployment.

## 11. Human Oversight and Authority

NIST AI RMF addresses human-AI configurations, accountability, transparency, and governance.

D-AIGAAF expands this into an explicit human-authority architecture.

Relevant modules include:

- Module 08 — Human Authority;
- Module 11 — Operational Authorisation;
- Module 12 — Operational Employment;
- Module 17 — Workforce;
- Module 03 — Risk & Autonomy.

D-AIGAAF distinguishes:

**Human Involvement ≠ Human Oversight ≠ Human Control ≠ Human Authority**

A person being present in the workflow does not automatically establish meaningful human control.

For consequential AI, D-AIGAAF requires the authority to:

- understand the relevant decision;
- recognise uncertainty and limitations;
- intervene where required;
- override or terminate AI behaviour where authorised;
- operate under defined conditions; and
- remain accountable for decisions assigned to the human authority structure.

## 12. Autonomy Crosswalk

NIST AI RMF supports risk-based treatment of AI systems but does not establish D-AIGAAF's specific operational autonomy model.

D-AIGAAF defines an indicative autonomy scale:

| D-AIGAAF | Description |
|---|---|
| A0 | No Meaningful AI Decision |
| A1 | Information / Observation |
| A2 | Analysis / Recommendation |
| A3 | Human-Authorised Action |
| A4 | Supervised Autonomous Action |
| A5 | Independent Consequential Autonomy |

The scale provides a defence-specific mechanism for connecting AI capability to authority and risk.

The core D-AIGAAF principle is:

> Greater technical autonomy does not automatically create greater operational authority.

## 13. Operational Authorisation Crosswalk

This is one of the principal areas where D-AIGAAF extends NIST AI RMF.

NIST MANAGE includes decisions concerning whether an AI system achieves intended purposes and whether development or deployment should proceed.

D-AIGAAF develops this into a dedicated operational-authorisation architecture.

The D-AIGAAF authorisation object is:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

This means that authorisation is contextual and bounded.

An AI system may be technically capable and strongly aligned with NIST AI RMF practices but still not be authorised for a specific mission or autonomy level.

## 14. Continuous Assurance Crosswalk

NIST AI RMF emphasises continuous risk management and repeated measurement as knowledge, contexts, risks, and impacts evolve.

D-AIGAAF operationalises this through **Module 13 — Continuous Assurance**.

D-AIGAAF adds explicit mechanisms for:

- assurance monitoring;
- assurance confidence;
- independent challenge;
- operational indicators;
- environmental change;
- security and dependency changes;
- human-control assurance;
- change-triggered revalidation;
- reauthorisation; and
- continuous learning.

This is a direct extension of the continuous risk-management principle into operational governance.

## 15. Incident and Change Crosswalk

NIST MANAGE includes incident response, risk treatment, and continual improvement.

D-AIGAAF provides dedicated governance modules:

- **Module 14 — Incident & Fail-Safe**
- **Module 15 — Change & Reauthorisation**

The D-AIGAAF distinction is important because an incident or material change may invalidate previous assurance or authority.

The resulting lifecycle is:

**Detect → Protect → Fail-Safe → Investigate → Correct → Recover → Reassess Assurance → Reauthorise → Learn**

For material changes:

**Identify → Classify → Assess Impact → Test → Revalidate → Reauthorise → Implement → Monitor**

## 16. AI Security Crosswalk

NIST AI RMF treats security and resilience as important trustworthy-AI characteristics.

D-AIGAAF provides dedicated AI security governance through **Module 06 — AI Security**.

It further connects security to:

- operational environment;
- adversarial conditions;
- supply-chain dependencies;
- model and data integrity;
- incident response;
- fail-safe behaviour;
- operational authorisation; and
- continuous assurance.

This makes security an operational governance input rather than solely a technical control domain.

## 17. Supply Chain Crosswalk

NIST AI RMF recognises risks arising from AI actors, third parties, data, components, and lifecycle relationships.

D-AIGAAF develops a dedicated **Module 07 — Supply Chain & Sovereignty** covering:

- supplier risk;
- provenance and traceability;
- supplier assurance;
- strategic dependency;
- continuity;
- sovereignty considerations;
- supply-chain change; and
- reauthorisation.

The additional emphasis reflects the potential operational significance of external dependencies in defence AI.

## 18. TEVV Crosswalk

NIST AI RMF explicitly incorporates testing, evaluation, verification, and validation concepts within MEASURE.

D-AIGAAF develops TEVV into a dedicated module with coverage of:

- planning;
- test design;
- operational environment;
- human-AI evaluation;
- security and adversarial evaluation;
- autonomy and control;
- reliability and robustness;
- mission effectiveness;
- independent evaluation;
- operational acceptance;
- evidence management.

Therefore:

**NIST MEASURE → Broad AI risk measurement and evaluation**

**D-AIGAAF TEVV → Defence-specific evidence architecture supporting assurance and operational decisions**

## 19. Audit and Evidence Crosswalk

NIST AI RMF emphasises documentation, transparency, accountability, measurement records, and governance evidence.

D-AIGAAF develops this through:

- Module 16 — Audit & Evidence;
- Module 25 — Documentation & Knowledge;
- Module 17 — Workforce;
- Module 13 — Continuous Assurance.

D-AIGAAF additionally establishes traceability between:

**Requirement → Control → Test → Evidence → Assurance → Authority → Decision**

This supports later audit, investigation, reauthorisation, and learning.

## 20. Maturity Crosswalk

NIST AI RMF is not itself a five-level organisational maturity model.

D-AIGAAF Module 18 provides an independent maturity architecture:

**Initial → Developing → Defined → Managed → Institutionalised**

The maturity model may use NIST AI RMF implementation as one source of evidence, but maturity remains distinct from NIST conformity or compliance.

The distinction is:

**NIST AI RMF = Risk-management framework**

**D-AIGAAF Maturity Model = Assessment of governance capability and institutionalisation**

## 21. Major D-AIGAAF Extensions Beyond NIST AI RMF

The following areas represent particularly important D-AIGAAF extensions:

| Area | D-AIGAAF Treatment |
|---|---|
| Mission-specific governance | Explicit mission and use-case architecture |
| Autonomy | Defined autonomy levels and boundaries |
| Human authority | Explicit decision rights and operational authority |
| Operational environment | Dedicated governance module |
| Operational authorisation | Dedicated authorisation framework |
| Operational employment | Dedicated employment governance |
| Degraded/disconnected operations | Explicit lifecycle and operational treatment |
| Fail-safe | Dedicated fail-safe and safe-state governance |
| Reauthorisation | Explicit change-triggered authority reassessment |
| Defence supply-chain sovereignty | Dedicated governance architecture |
| Consequential autonomy | Explicit consequence/autonomy relationship |
| Workforce | Dedicated governance and competence architecture |
| Maturity | Dedicated governance maturity model |
| Defence-specific Golden Thread | Integrated mission-to-authority lifecycle |

These should be described as extensions rather than shortcomings of NIST AI RMF, because NIST AI RMF was intentionally designed as a broad, sector-agnostic framework.

## 22. Areas Where NIST AI RMF Should Remain the Primary Reference

D-AIGAAF should not attempt to replace NIST AI RMF's broad treatment of general AI risk-management concepts.

Where organisations already use NIST AI RMF, D-AIGAAF can provide a defence-specific layer around it.

A practical relationship is:

**NIST AI RMF**
→ General AI risk-management foundation

**D-AIGAAF**
→ Defence mission, authority, autonomy, operational environment, assurance, authorisation, employment, and continuous operational governance

This relationship reduces unnecessary duplication and enables organisations to preserve established AI risk-management practices.

## 23. Implementation Pattern

An organisation using both frameworks may implement them as follows:

### Step 1 — Establish NIST AI RMF Governance

Adopt the GOVERN function and establish organisational AI risk-management responsibilities.

### Step 2 — Map Defence Context

Use D-AIGAAF Modules 02, 03, 05, 06, 07, and 10 to define mission, risk, autonomy, data, security, dependencies, and operational environment.

### Step 3 — Measure and Assure

Use NIST MEASURE together with D-AIGAAF TEVV, assurance, security, and evidence requirements.

### Step 4 — Apply Risk Treatment

Use NIST MANAGE together with D-AIGAAF risk treatment, incident, fail-safe, change, and operational controls.

### Step 5 — Establish Authority

Apply D-AIGAAF operational-authorisation requirements.

### Step 6 — Govern Employment

Apply D-AIGAAF operational-employment and monitoring requirements.

### Step 7 — Maintain Continuous Assurance

Use NIST's continuous risk-management principle with D-AIGAAF continuous assurance, revalidation, reauthorisation, incident, and change mechanisms.

## 24. Crosswalk Evidence Expectations

A credible NIST-to-D-AIGAAF crosswalk should be supported by:

- the authoritative NIST AI RMF text;
- applicable NIST AI RMF Core functions, categories, and subcategories;
- relevant D-AIGAAF module references;
- identified relationship type;
- implementation evidence where a control is claimed to be operational;
- explicit limitations;
- version information; and
- review history.

The crosswalk should not rely solely on matching terminology.

## 25. Limitations

This crosswalk has several inherent limitations.

First, NIST AI RMF is intentionally flexible and non-prescriptive. A single D-AIGAAF requirement may therefore correspond to multiple NIST outcomes.

Second, D-AIGAAF contains operational-authority concepts that do not have direct one-to-one equivalents in a general AI risk-management framework.

Third, regulatory, legal, mission, and organisational contexts can change the applicability of particular controls.

Fourth, mapping does not establish compliance.

Fifth, NIST has indicated that AI RMF 1.0 is being revised. The crosswalk must therefore be maintained against the authoritative NIST version in force at the time of use.

## 26. Recommended Crosswalk Status Labels

Each mapping should use one of the following labels:

- **Aligned**
- **Partially Aligned**
- **Complementary**
- **D-AIGAAF Extension**
- **D-AIGAAF Specific**
- **Different Scope**
- **Not Addressed**
- **Not Applicable**

A mapping should include explanatory notes where the classification could reasonably be misunderstood.

## 27. Overall Assessment

The relationship between the two frameworks can be summarised as:

**NIST AI RMF provides a general AI risk-management architecture.**

**D-AIGAAF builds a defence-specific governance, assurance, authority, authorisation, and operational-employment architecture around compatible AI risk-management principles.**

The strongest conceptual alignment occurs in:

- governance;
- contextual risk identification;
- measurement;
- risk treatment;
- lifecycle management;
- TEVV;
- documentation;
- accountability; and
- continuous improvement.

The strongest D-AIGAAF extensions occur in:

- mission-specific risk;
- autonomy;
- human authority;
- operational environment;
- operational authorisation;
- operational employment;
- fail-safe;
- reauthorisation;
- defence supply-chain sovereignty; and
- continuous operational assurance.

## 28. Core Rule

> **D-AIGAAF should treat NIST AI RMF as a foundational AI risk-management reference while extending it for the specific governance realities of consequential defence AI. A mapped NIST practice may inform D-AIGAAF implementation, but it does not by itself establish defence operational assurance or authorisation.**

The integrated model is:

**NIST GOVERN → D-AIGAAF Governance**

**NIST MAP → D-AIGAAF Mission + Risk + Environment**

**NIST MEASURE → D-AIGAAF TEVV + Evidence + Assurance**

**NIST MANAGE → D-AIGAAF Risk Treatment + Authorisation + Employment**

**NIST Continuous Risk Management → D-AIGAAF Continuous Assurance + Revalidation + Reauthorisation**

This preserves interoperability with an established AI risk-management framework while retaining D-AIGAAF's central defence principle:

**AI capability does not create operational authority. Authority must be explicitly established, bounded, evidenced, and continuously justified.**

## 29. Source and Version Record

Primary source:

**National Institute of Standards and Technology, Artificial Intelligence Risk Management Framework (AI RMF 1.0), NIST AI 100-1, January 2023.**

The NIST AI RMF is a voluntary framework and is designed to be flexible, non-sector-specific, and use-case agnostic. NIST's current AI RMF resources indicate that AI RMF 1.0 is being revised.

This D-AIGAAF crosswalk should therefore be reviewed when:

- a revised NIST AI RMF is formally released;
- material changes are made to the NIST AI RMF Core;
- relevant NIST profiles materially change the applicable risk-management approach; or
- D-AIGAAF modules materially change the mapped governance architecture.
