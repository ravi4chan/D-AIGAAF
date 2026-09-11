# 02-Crosswalk to ISO IEC 42001

## 1. Purpose

This crosswalk maps D-AIGAAF against **ISO/IEC 42001:2023 — Information technology — Artificial intelligence — Management system**.

ISO/IEC 42001 specifies requirements for establishing, implementing, maintaining, and continually improving an Artificial Intelligence Management System (AIMS). ISO identifies it as an international management-system standard applicable to organisations that develop, provide, or use AI systems. citeturn0search0turn0search5

The standard is organisational in orientation. D-AIGAAF uses compatible management-system principles but extends them into defence mission governance, operational assurance, autonomy, human authority, operational authorisation, and employment.

This crosswalk is therefore an **alignment and integration analysis**, not a certification or conformity claim.

## 2. Standard Baseline

The assessed reference is:

- **Standard:** ISO/IEC 42001:2023
- **Title:** Information technology — Artificial intelligence — Management system
- **Edition:** First edition
- **Publication:** December 2023
- **Status:** International Standard
- **Technical committee:** ISO/IEC JTC 1/SC 42

ISO describes ISO/IEC 42001 as an AI management-system standard covering the establishment, implementation, maintenance, and continual improvement of an AIMS. It is intended for organisations across sectors and contexts. citeturn0search0

ISO also describes the standard as using a management-system approach, including leadership, planning, support, operation, performance evaluation, and continual improvement. citeturn0search5turn0search6

## 3. Fundamental Relationship

The relationship can be expressed as:

**ISO/IEC 42001 → Organisational AI Management System**

**D-AIGAAF → Defence AI Governance, Assurance, Operational Authorisation and Employment Framework**

ISO/IEC 42001 provides the organisational management-system foundation.

D-AIGAAF adds a defence-specific layer for situations where AI governance must extend from organisational management into consequential operational decision-making.

The two should therefore be treated as **complementary**, not competing, frameworks.

## 4. High-Level Crosswalk

| ISO/IEC 42001 Area | Principal D-AIGAAF Coverage | Relationship |
|---|---|---|
| Organisational context | 01 Strategy & Governance; 02 Mission & Use Case | Direct Alignment + Defence Extension |
| Leadership | 01 Strategy & Governance; 08 Human Authority | Direct Alignment |
| AI policy | 01 Strategy & Governance; 21 Legal & Policy | Direct Alignment |
| Roles and responsibilities | 01 Governance; 08 Human Authority; 17 Workforce | Direct Alignment + Extension |
| AI objectives | 01 Governance; 02 Mission & Use Case | Direct Alignment |
| Risk management | 03 Risk & Autonomy | Direct Alignment + Defence Extension |
| AI impact considerations | 02 Mission & Use Case; 03 Risk & Autonomy; 05 Data & Information | Complementary |
| AI lifecycle | 04 AI Lifecycle | Direct Alignment + Defence Extension |
| Data governance | 05 Data & Information | Direct Alignment + Extension |
| Transparency / information | 08 Human Authority; 12 Operational Employment; 16 Audit & Evidence | Direct Alignment + Operational Extension |
| Performance evaluation | 09 TEVV; 13 Continuous Assurance | Direct Alignment + Extension |
| Internal audit | 16 Audit & Evidence | Direct Alignment |
| Management review | 01 Governance; 13 Assurance; 18 Maturity | Direct Alignment |
| Corrective action | 14 Incident & Fail-Safe; 15 Change & Reauthorisation; 16 Audit | Direct Alignment + Extension |
| Continual improvement | 13 Continuous Assurance; 18 Maturity; 27 Implementation | Direct Alignment |
| AI operational authority | 11 Operational Authorisation | D-AIGAAF Specific |
| Autonomy boundaries | 03 Risk & Autonomy; 11 Operational Authorisation | D-AIGAAF Extension |
| Defence operational employment | 12 Operational Employment | D-AIGAAF Specific |
| Degraded/disconnected operations | 10 Operational Environment; 12 Operational Employment | D-AIGAAF Specific |
| Fail-safe / safe state | 14 Incident & Fail-Safe | D-AIGAAF Extension |
| Reauthorisation | 15 Change & Reauthorisation | D-AIGAAF Extension |

## 5. Organisational Context

ISO/IEC 42001 uses organisational context to establish the conditions relevant to the AI management system.

D-AIGAAF develops this concept into two connected levels:

### Organisational Context

Covered primarily through:

- Module 01 — Strategy & Governance;
- Module 07 — Supply Chain & Sovereignty;
- Module 17 — Workforce;
- Module 21 — Legal & Policy;
- Module 22 — Acquisition & Procurement;
- Module 23 — Interoperability & Coalition.

### Operational Context

Covered through:

- Module 02 — Mission & Use Case;
- Module 10 — Operational Environment;
- Module 11 — Operational Authorisation;
- Module 12 — Operational Employment.

This distinction is important because an organisation can have a mature AI management system while an individual AI capability remains inappropriate for a particular mission or operational environment.

## 6. Leadership and Accountability

ISO/IEC 42001 places importance on leadership, policy, responsibilities, and accountability within the AI management system.

D-AIGAAF provides corresponding mechanisms through:

- governance committees;
- decision rights;
- risk governance;
- human decision rights;
- accountability and decision traceability;
- workforce roles;
- operational authority; and
- governance review.

D-AIGAAF adds a critical defence distinction:

**Organisational Accountability ≠ Operational Decision Authority**

The person or body accountable for maintaining an AI governance system is not necessarily the person authorised to approve a specific consequential operational action.

That distinction should remain explicit in implementation.

## 7. AI Policy and Governance

ISO/IEC 42001 requires an organisational AI policy and associated management-system arrangements.

D-AIGAAF addresses equivalent governance needs through:

- Module 01 — Strategy & Governance;
- Module 21 — Legal & Policy;
- Module 25 — Documentation & Knowledge;
- Module 27 — Implementation.

D-AIGAAF additionally requires governance policy to address operational questions such as:

- acceptable autonomy;
- human authority;
- mission boundaries;
- environmental constraints;
- operational authorisation;
- fail-safe expectations;
- reauthorisation;
- degraded operations; and
- continued assurance.

This is an extension of management-system policy into operational governance.

## 8. Roles, Responsibilities and Authorities

ISO/IEC 42001 requires appropriate responsibilities and authorities within the AI management system.

D-AIGAAF provides a more explicit separation among:

- AI developer;
- system owner;
- data owner;
- security authority;
- evaluator;
- assurance function;
- operational user;
- human decision maker;
- authorising authority;
- governance body; and
- audit or independent-review function.

The D-AIGAAF principle is:

> Responsibility shall be assigned to the role with appropriate authority, competence, information, and capacity to discharge that responsibility.

This is particularly important for consequential AI where technical responsibility and operational accountability can otherwise become confused.

## 9. AI Objectives

ISO/IEC 42001 requires AI-related objectives to be established within the management-system context.

D-AIGAAF connects objectives to:

**Mission Success Criteria → Risk → Controls → Evidence → Assurance → Authorisation Conditions**

This prevents AI objectives from being expressed solely as technical performance targets.

A defence AI capability may, for example, need objectives concerning:

- mission effectiveness;
- reliability;
- uncertainty;
- human control;
- security;
- resilience;
- autonomy boundaries;
- operational availability;
- fail-safe behaviour; and
- evidence required for continued authorisation.

## 10. Risk Management

ISO/IEC 42001 provides a management-system approach for identifying and treating AI-related risks and opportunities.

D-AIGAAF provides detailed risk governance through Module 03.

The D-AIGAAF risk architecture includes:

- risk model;
- autonomy assessment;
- human-control assessment;
- loss-of-control analysis;
- risk treatment;
- residual risk;
- risk acceptance;
- monitoring;
- autonomy boundaries;
- autonomy transitions; and
- risk-autonomy matrix.

This creates a direct alignment with the management-system risk approach while adding explicit treatment of autonomy and operational consequence.

## 11. AI Impact and Mission Consequence

ISO/IEC 42001's organisational risk approach can be extended through D-AIGAAF's mission and use-case architecture.

D-AIGAAF asks:

**What is the AI intended to do?**

then:

**What happens if it is wrong?**

then:

**Who has authority over the resulting decision or action?**

then:

**Under what operational conditions may the capability be used?**

This produces a consequence-aware chain:

**Use Case → Mission → Consequence → Risk → Autonomy → Human Authority → Operational Conditions**

That chain is a core D-AIGAAF extension.

## 12. AI Lifecycle

ISO/IEC 42001 addresses AI management across the relevant lifecycle.

D-AIGAAF provides a dedicated lifecycle architecture:

**Need → Requirements → Development/Acquisition → Data → Model → Integration → Configuration → TEVV → Deployment → Employment → Monitoring → Change → Revalidation → Reauthorisation → Retirement → Decommissioning**

This extends management-system governance into explicit operational lifecycle gates.

The important distinction is:

**Management System Lifecycle Governance**

versus

**Capability-Specific Operational Lifecycle Governance**

D-AIGAAF addresses both.

## 13. Data Governance

ISO/IEC 42001 includes AI management considerations involving data and lifecycle controls.

D-AIGAAF Module 05 provides detailed governance covering:

- data governance;
- quality and integrity;
- provenance and lineage;
- representativeness;
- drift;
- data assurance;
- lifecycle;
- incidents;
- sharing;
- retention; and
- disposal.

The defence-specific extension is the connection between data characteristics and operational risk.

For example, data drift or poor representativeness may affect not merely model performance but:

- mission effectiveness;
- situational awareness;
- human decision-making;
- autonomy boundaries; and
- operational authorisation.

## 14. AI Security

ISO/IEC 42001 operates within a broader organisational management-system environment, and ISO itself identifies AI and information-security management systems as complementary standards. citeturn0search3

D-AIGAAF explicitly integrates AI security through Module 06.

It covers:

- security requirements;
- threat modelling;
- adversarial AI security;
- security controls;
- security assurance;
- incidents and response.

D-AIGAAF further connects security status to:

**Assurance → Authorisation → Operational Conditions → Continued Employment**

This is important because a material security degradation may require more than a technical remediation; it may require reassessment of operational authority.

## 15. Supply Chain and External Providers

ISO/IEC 42001 applies to organisations that develop, provide, or use AI systems and therefore provides a management-system basis for governing externally provided AI.

D-AIGAAF expands this through Module 07:

- supplier risk;
- provenance;
- traceability;
- supplier assurance;
- dependency management;
- sovereignty;
- continuity;
- supply-chain change; and
- reauthorisation.

The central D-AIGAAF question is:

> Can the organisation continue to exercise appropriate governance and operational authority if a critical external AI dependency changes, fails, becomes unavailable, or becomes untrusted?

## 16. Transparency and Information

ISO/IEC 42001 addresses transparency and information provision as part of AI management.

D-AIGAAF treats information as an operational-control issue.

Relevant requirements include:

- communicating AI limitations;
- communicating uncertainty;
- maintaining decision traceability;
- recording relevant AI outputs;
- ensuring human decision makers have sufficient information;
- maintaining operational records; and
- preserving evidence for later review.

The D-AIGAAF principle is:

> Information provided to a human decision maker must be sufficient for the intended level of human authority and consequence.

This avoids equating transparency with merely publishing technical documentation.

## 17. Human Oversight

ISO/IEC 42001 supports organisational governance of AI systems.

D-AIGAAF goes further by defining human authority as a structured governance domain.

Module 08 covers:

- human decision rights;
- human-AI interaction;
- meaningful human control;
- AI literacy;
- oversight;
- intervention;
- override;
- accountability;
- decision traceability.

The critical distinction is:

**Human Presence ≠ Meaningful Human Control**

For consequential AI, D-AIGAAF requires the human authority structure to have appropriate:

- competence;
- authority;
- information;
- time;
- intervention capability; and
- accountability.

## 18. TEVV and Performance Evaluation

ISO/IEC 42001 requires performance evaluation within the management system.

D-AIGAAF develops performance evaluation into a dedicated TEVV architecture covering:

- planning;
- requirements;
- test design;
- operational environment;
- human-AI evaluation;
- adversarial evaluation;
- autonomy;
- reliability;
- robustness;
- mission effectiveness;
- independent evaluation;
- operational acceptance;
- evidence management.

This creates the following relationship:

**ISO/IEC 42001 Performance Evaluation**

→ **D-AIGAAF TEVV**

→ **Assurance**

→ **Operational Readiness**

→ **Operational Authorisation**

The final stages are D-AIGAAF-specific extensions.

## 19. Monitoring and Continuous Assurance

ISO/IEC 42001 is designed around continual improvement and a management-system cycle. ISO describes the standard as using a Plan-Do-Check-Act approach for establishing, implementing, maintaining, and continually improving AI management. citeturn0search1turn0search12

D-AIGAAF operationalises this through:

- Module 13 — Continuous Assurance;
- Module 14 — Incident & Fail-Safe;
- Module 15 — Change & Reauthorisation;
- Module 16 — Audit & Evidence;
- Module 18 — Maturity Model;
- Module 27 — Implementation.

D-AIGAAF therefore adds explicit mechanisms for ensuring that previous confidence remains justified after deployment and operational change.

## 20. Internal Audit

ISO/IEC 42001 follows the management-system model in which internal audit and management review support system effectiveness.

D-AIGAAF provides dedicated audit architecture in Module 16:

**Plan → Define Criteria → Collect Evidence → Test → Find → Challenge → Correct → Verify → Report → Learn**

This provides a direct management-system alignment.

D-AIGAAF additionally connects audit findings to:

- assurance;
- operational authorisation;
- incidents;
- change;
- revalidation;
- reauthorisation; and
- maturity improvement.

## 21. Management Review

ISO/IEC 42001 requires management-system performance to be reviewed at the appropriate organisational level.

D-AIGAAF distributes management review across governance mechanisms including:

- governance committees;
- risk governance;
- continuous assurance review;
- audit review;
- operational governance review;
- workforce governance;
- maturity review; and
- implementation governance.

This creates a layered governance architecture rather than a single management-review event.

## 22. Corrective Action

ISO/IEC 42001's continual-improvement approach requires organisations to address nonconformities and improve the management system.

D-AIGAAF provides several corresponding mechanisms:

| Corrective Need | D-AIGAAF |
|---|---|
| Governance weakness | Module 01 |
| Risk weakness | Module 03 |
| Technical/lifecycle weakness | Module 04 |
| Data weakness | Module 05 |
| Security weakness | Module 06 |
| Human-control weakness | Module 08 |
| TEVV finding | Module 09 |
| Operational weakness | Module 12 |
| Assurance finding | Module 13 |
| Incident | Module 14 |
| Change | Module 15 |
| Audit finding | Module 16 |
| Workforce weakness | Module 17 |
| Maturity gap | Module 18 |

This provides a distributed corrective-action architecture.

## 23. Continual Improvement

ISO/IEC 42001's management-system approach places continual improvement at the centre of organisational AI governance. citeturn0search5

D-AIGAAF adopts this principle but makes improvement explicitly linked to operational consequences.

The D-AIGAAF improvement loop is:

**Observe → Assess → Identify Gap → Treat → Verify → Assure → Reauthorise Where Required → Monitor → Learn**

The addition of reauthorisation is particularly important where changes affect operational authority or autonomy.

## 24. Documentation and Evidence

A management system depends on documented information and demonstrable implementation.

D-AIGAAF reinforces this through:

- Module 16 — Audit & Evidence;
- Module 25 — Documentation & Knowledge;
- Module 09 — TEVV Evidence Management;
- Module 13 — Assurance Records;
- Module 15 — Change Records;
- Module 17 — Workforce Records.

The D-AIGAAF traceability chain is:

**Requirement → Control → Implementation → Test → Evidence → Assurance → Decision → Authority → Record**

This supports both management-system assurance and operational accountability.

## 25. ISO/IEC 42001 and D-AIGAAF Maturity

ISO/IEC 42001 establishes requirements for an AI management system. D-AIGAAF Module 18 assesses the maturity of governance capability.

These should not be conflated.

| Concept | Meaning |
|---|---|
| ISO/IEC 42001 | Requirements for an AI management system |
| ISO/IEC 42001 Certification | Formal conformity assessment where undertaken by an appropriate certification body |
| D-AIGAAF Maturity | Assessment of governance capability, effectiveness, resilience, and institutionalisation |
| D-AIGAAF Assurance | Confidence that specified claims and controls remain justified |
| D-AIGAAF Authorisation | Explicit operational permission within defined conditions |

ISO notes that certification can provide additional confidence but is distinct from adopting the standard itself. citeturn0search5

## 26. Management System Versus Operational Authorisation

This distinction is central to D-AIGAAF.

An organisation may have:

- an effective AIMS;
- documented AI policies;
- mature risk management;
- strong internal audit;
- appropriate corrective action; and
- successful ISO/IEC 42001 certification.

Yet a specific AI capability may still not be authorised for a particular defence mission.

Why?

Because operational authorisation depends on:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

ISO/IEC 42001 provides organisational management-system governance.

D-AIGAAF adds capability-specific operational authority.

## 27. Autonomy Crosswalk

ISO/IEC 42001 governs AI management but does not provide D-AIGAAF's specific A0–A5 operational autonomy model.

D-AIGAAF defines:

- A0 — No Meaningful AI Decision;
- A1 — Information / Observation;
- A2 — Analysis / Recommendation;
- A3 — Human-Authorised Action;
- A4 — Supervised Autonomous Action;
- A5 — Independent Consequential Autonomy.

This model allows governance to explicitly connect:

**Capability → Autonomy → Consequence → Human Authority → Authorisation Conditions**

This is a significant D-AIGAAF extension.

## 28. Operational Environment

ISO/IEC 42001 provides organisation-wide management-system governance.

D-AIGAAF explicitly governs the operational environment through Module 10, including:

- environmental characterisation;
- variability;
- boundaries;
- degraded operations;
- disconnected operations;
- adversarial conditions;
- human environment;
- information and electromagnetic environment;
- readiness;
- monitoring;
- environmental change;
- incidents;
- lessons learned;
- exit criteria.

The extension is based on the principle that AI governance cannot be separated from the environment in which consequential decisions or actions occur.

## 29. Fail-Safe and Safe-State Governance

ISO/IEC 42001 supports risk management and responsible AI management.

D-AIGAAF provides explicit fail-safe governance through Module 14.

The lifecycle is:

**Detect → Classify → Protect → Fail-Safe → Investigate → Correct → Recover → Reassess Assurance → Reauthorise → Learn**

This provides an operational response architecture for situations where AI behaviour becomes unsafe, unexpected, compromised, unavailable, or outside authorised conditions.

## 30. Change and Reauthorisation

ISO/IEC 42001 requires management-system control and continual improvement.

D-AIGAAF explicitly addresses the effect of changes on previous assurance and authority.

The change lifecycle is:

**Identify Change → Classify → Impact Assessment → Configuration Control → TEVV → Revalidation → Reauthorisation → Implementation → Monitoring → Learning**

This is particularly important for:

- model updates;
- data changes;
- autonomy changes;
- security changes;
- environmental changes;
- supplier changes;
- architecture changes; and
- changes to mission purpose.

A technically successful update is not automatically an operationally authorised update.

## 31. Acquisition and Supplier Governance

ISO/IEC 42001 can be used by organisations that develop, provide, or use AI systems.

D-AIGAAF adds acquisition-specific governance through Module 22 and supplier/sovereignty governance through Module 07.

This allows procurement decisions to consider:

- AI risk;
- security;
- provenance;
- supplier assurance;
- strategic dependency;
- continuity;
- data;
- TEVV evidence;
- update control;
- operational authority; and
- reauthorisation implications.

## 32. Legal and Regulatory Alignment

ISO/IEC 42001 supports organisational consideration of applicable legal and regulatory requirements.

D-AIGAAF Module 21 expands this into a dedicated legal and policy layer.

However, D-AIGAAF does not replace:

- applicable national law;
- defence policy;
- international law;
- procurement law;
- data-protection requirements;
- sector-specific requirements; or
- formal regulatory obligations.

A crosswalk to ISO/IEC 42001 should therefore identify legal and policy requirements separately from management-system controls.

## 33. Crosswalk by D-AIGAAF Module

| D-AIGAAF Module | Relationship to ISO/IEC 42001 |
|---|---|
| 00 Framework | Terminology, lifecycle, principles and conceptual foundation |
| 01 Strategy & Governance | Strong direct alignment |
| 02 Mission & Use Case | Defence-specific contextual extension |
| 03 Risk & Autonomy | Strong alignment + autonomy extension |
| 04 AI Lifecycle | Strong alignment + operational lifecycle extension |
| 05 Data & Information | Strong alignment + operational consequence extension |
| 06 AI Security | Complementary security governance |
| 07 Supply Chain & Sovereignty | Supplier/dependency extension |
| 08 Human Authority | Governance and accountability extension |
| 09 TEVV | Performance evaluation and evidence extension |
| 10 Operational Environment | Defence-specific extension |
| 11 Operational Authorisation | D-AIGAAF specific |
| 12 Operational Employment | D-AIGAAF specific |
| 13 Continuous Assurance | Continual-improvement and assurance extension |
| 14 Incident & Fail-Safe | Corrective/incident operational extension |
| 15 Change & Reauthorisation | Change-control extension |
| 16 Audit & Evidence | Strong management-system alignment |
| 17 Workforce | Strong governance/competence alignment |
| 18 Maturity Model | Complementary governance capability assessment |
| 19 Crosswalks | Framework interoperability |
| 20 Templates | Implementation support |
| 21 Legal & Policy | Compliance and legal-context extension |
| 22 Acquisition & Procurement | Supplier/acquisition extension |
| 23 Interoperability & Coalition | Defence interoperability extension |
| 24 Architecture & Technical Controls | Technical implementation extension |
| 25 Documentation & Knowledge | Documented-information extension |
| 26 Retirement & Decommissioning | Lifecycle extension |
| 27 Implementation | Management-system implementation extension |

## 34. Recommended Combined Architecture

For an organisation implementing both ISO/IEC 42001 and D-AIGAAF, the recommended relationship is:

### Layer 1 — Management System

**ISO/IEC 42001**

Establishes the organisational AI management system.

### Layer 2 — Defence AI Governance

**D-AIGAAF Modules 01–08**

Translate general AI governance into mission, risk, autonomy, data, security, supply-chain, and human-authority requirements.

### Layer 3 — Evidence and Assurance

**D-AIGAAF Modules 09, 13, 16**

Establish testing, evidence, assurance, audit, and confidence mechanisms.

### Layer 4 — Operational Governance

**D-AIGAAF Modules 10–15**

Connect AI capability to operational environment, authorisation, employment, incidents, fail-safe, change, and reauthorisation.

### Layer 5 — Institutional Capability

**D-AIGAAF Modules 17–27**

Establish workforce, maturity, legal, procurement, interoperability, architecture, documentation, retirement, and implementation capability.

## 35. What D-AIGAAF Should Not Claim

D-AIGAAF should not state that:

- implementing D-AIGAAF automatically provides ISO/IEC 42001 certification;
- mapping a D-AIGAAF control to ISO/IEC 42001 establishes conformity;
- ISO/IEC 42001 certification automatically establishes operational authorisation;
- D-AIGAAF replaces ISO/IEC 42001;
- ISO/IEC 42001 is insufficient for responsible AI generally; or
- D-AIGAAF is itself an ISO management-system standard.

The appropriate claim is:

> D-AIGAAF is designed to be interoperable with established AI management-system approaches and to provide additional defence-specific governance, assurance, operational-authorisation, and employment controls.

## 36. Crosswalk Maintenance

The crosswalk should be reviewed when:

- ISO/IEC 42001 is revised;
- relevant ISO/IEC 42001 guidance changes;
- related ISO/IEC AI standards materially change;
- D-AIGAAF modules change;
- new defence AI governance requirements emerge;
- regulatory requirements materially change; or
- implementation experience identifies a significant mapping error.

The crosswalk metadata should identify:

- standard version;
- D-AIGAAF version;
- mapping version;
- assessment date;
- responsible owner;
- reviewer;
- assumptions;
- limitations; and
- next review trigger.

## 37. Evidence Requirements for Published Mapping

A published crosswalk should be based on authoritative source material.

Evidence should include:

- the applicable ISO/IEC 42001 edition;
- the relevant requirement or subject area;
- D-AIGAAF reference;
- relationship classification;
- rationale for mapping;
- identified extensions;
- limitations;
- implementation evidence where claims are made; and
- review record.

Because ISO standards are copyrighted, public D-AIGAAF crosswalks should avoid reproducing large portions of the standard and instead use concise descriptions and references.

## 38. Overall Assessment

The alignment between ISO/IEC 42001 and D-AIGAAF is substantial at the management-system level.

The strongest common areas are:

- organisational governance;
- leadership;
- policy;
- roles and responsibilities;
- risk management;
- lifecycle governance;
- data governance;
- performance evaluation;
- audit;
- management review;
- corrective action;
- documented information; and
- continual improvement.

The principal D-AIGAAF extensions are:

- defence mission context;
- explicit autonomy governance;
- human operational authority;
- operational environment;
- operational authorisation;
- operational employment;
- degraded/disconnected operation;
- fail-safe;
- reauthorisation;
- defence supply-chain sovereignty; and
- mission-linked continuous assurance.

## 39. Core Rule

> **ISO/IEC 42001 provides an organisational AI management-system foundation. D-AIGAAF should build upon compatible management-system principles while extending governance into mission consequence, autonomy, human authority, operational environment, operational authorisation, operational employment, and continuous defence assurance.**

The integrated relationship is:

**ISO/IEC 42001 AIMS → D-AIGAAF Defence AI Governance → TEVV → Assurance → Operational Authorisation → Employment → Continuous Assurance**

The central distinction remains:

**A mature AI management system does not automatically confer operational authority on an AI capability.**

Operational authority must remain explicit, bounded, evidence-based, human-accountable, mission-specific, and continuously justified.

## 40. Source and Version Record

Primary source:

**ISO/IEC 42001:2023 — Information technology — Artificial intelligence — Management system.**

ISO identifies ISO/IEC 42001:2023 as an International Standard published in December 2023 and describes it as specifying requirements for establishing, implementing, maintaining, and continually improving an AI Management System. citeturn0search0

ISO also describes the standard as applicable to organisations of different sizes and sectors that develop, provide, or use AI systems. citeturn0search0turn0search5

The D-AIGAAF crosswalk should be reviewed against the authoritative ISO publication and any subsequently published amendments, revisions, implementation guidance, or related standards.

Relevant related ISO/IEC AI standards may include ISO/IEC 23894 for AI risk management and ISO/IEC 42005 for AI system impact assessment; these are addressed separately where included in the D-AIGAAF crosswalk programme. ISO currently lists ISO/IEC 42005:2025 among its published AI standards. citeturn0search7
