# 05-Crosswalk to EU AI Act

## 1. Purpose

This crosswalk maps D-AIGAAF against **Regulation (EU) 2024/1689 — the European Union Artificial Intelligence Act (EU AI Act)**.

The EU AI Act establishes harmonised rules for AI in the European Union, including prohibitions on certain AI practices, requirements for certain high-risk AI systems, transparency requirements, rules for general-purpose AI models, governance, market surveillance, enforcement, and measures supporting innovation. citeturn0search0turn0search1

A critical scope point must be established at the outset: the EU AI Act expressly excludes AI systems placed on the market, put into service, or used, with or without modification, **exclusively for military, defence, or national-security purposes**, regardless of the type of entity carrying out those activities. It also addresses systems used for both excluded and non-excluded purposes and systems whose outputs are used in the Union for exclusively military, defence, or national-security purposes. citeturn0search0turn0search24

Therefore, this crosswalk is **not** intended to imply that the EU AI Act directly regulates a purely military or defence implementation of D-AIGAAF.

Instead, the crosswalk identifies:

- concepts that D-AIGAAF can learn from or align with;
- governance controls that may be relevant to dual-use or non-excluded deployments;
- requirements that can inform procurement and supplier expectations;
- areas where D-AIGAAF goes beyond or differs from the EU AI Act; and
- situations where EU AI Act applicability must be determined separately.

This is a governance crosswalk, not legal advice or a legal determination of applicability.

## 2. Legal Baseline

The assessed instrument is:

- **Regulation:** Regulation (EU) 2024/1689
- **Common name:** EU Artificial Intelligence Act / EU AI Act
- **Adoption:** 13 June 2024
- **Publication in Official Journal:** 12 July 2024
- **Entry into force:** 1 August 2024
- **Application:** phased, with different provisions applying on different dates.

The Commission states that the AI Act entered into force on 1 August 2024 and that its provisions apply according to a phased timeline. From 2 August 2026, the Commission and national authorities began enforcing applicable AI Act rules, while certain high-risk provisions have later transition dates. citeturn0search1turn0search10

Because the Act is a regulation, applicability should be determined from the legal text and the specific facts of the AI system, provider, deployer, purpose, location, and activity.

## 3. Critical Defence Scope Exclusion

Article 2 contains a particularly important provision for D-AIGAAF.

The Act does not apply to AI systems where and insofar as they are placed on the market, put into service, or used exclusively for military, defence, or national-security purposes. citeturn0search0

The recital explains that this exclusion reflects, among other considerations, the specific legal and operational context of military and defence activities and the allocation of national-security responsibilities. citeturn0search24

This creates an important distinction:

**EU AI Act applicability ≠ D-AIGAAF applicability**

D-AIGAAF is designed specifically for defence AI governance and does not depend on the AI Act applying.

## 4. Dual-Use and Mixed-Purpose Systems

The exclusion does not mean every AI system associated with a defence organisation is automatically outside the AI Act.

The legal text addresses systems used for military, defence, or national-security purposes as well as systems used for other purposes. It specifically states that systems used for non-excluded purposes, and systems with both excluded and non-excluded purposes, may fall within the Regulation. citeturn0search12

D-AIGAAF should therefore require an applicability assessment where a capability is:

- dual-use;
- offered commercially;
- used for civilian purposes;
- used for law-enforcement or public-security purposes;
- supplied into an EU-regulated market;
- integrated into a non-defence product;
- used outside its original defence purpose.

The result should be recorded rather than assumed.

## 5. High-Level Crosswalk

| EU AI Act Area | Principal D-AIGAAF Coverage | Relationship |
|---|---|---|
| Risk-based approach | 03 Risk & Autonomy | Direct Alignment + Defence Extension |
| Prohibited AI practices | 21 Legal & Policy; 02 Mission & Use Case | Complementary / Applicability-Dependent |
| High-risk governance | 03, 09, 13, 16 | Strong conceptual alignment |
| Risk management | 03 Risk & Autonomy | Direct Alignment |
| Data governance | 05 Data & Information | Direct Alignment + Extension |
| Technical documentation | 04 AI Lifecycle; 16 Audit & Evidence; 25 Documentation | Direct Alignment |
| Record keeping / logging | 12 Operational Employment; 16 Audit & Evidence | Direct Alignment + Extension |
| Transparency | 08 Human Authority; 12 Employment; 25 Documentation | Complementary |
| Human oversight | 08 Human Authority | Strong Alignment + Defence Extension |
| Accuracy / robustness / cybersecurity | 06 Security; 09 TEVV; 13 Assurance | Strong Alignment + Extension |
| Quality management | 01 Governance; 04 Lifecycle; 13 Assurance | Complementary |
| Conformity assessment | 09 TEVV; 16 Audit & Evidence | Complementary, not equivalent |
| Post-market monitoring | 13 Continuous Assurance; 14 Incident; 15 Change | Conceptual Alignment + Defence Extension |
| Serious incidents | 14 Incident & Fail-Safe | Direct Alignment + Extension |
| General-purpose AI | 04 Lifecycle; 06 Security; 07 Supply Chain; 09 TEVV | Relevant mainly to upstream/dual-use providers |
| Systemic-risk GPAI | 03 Risk; 06 Security; 09 TEVV; 13 Assurance | Complementary |
| AI literacy | 17 Workforce | Direct Alignment |
| Governance and enforcement | 01 Governance; 21 Legal & Policy | Complementary |
| Military/defence exclusion | 21 Legal & Policy | Explicit applicability boundary |
| Operational authorisation | 11 Operational Authorisation | D-AIGAAF Specific |
| Defence operational employment | 12 Operational Employment | D-AIGAAF Specific |
| Degraded/disconnected operations | 10 Operational Environment | D-AIGAAF Specific |
| Autonomy levels | 03 Risk & Autonomy; 11 Authorisation | D-AIGAAF Specific |
| Fail-safe / safe state | 14 Incident & Fail-Safe | D-AIGAAF Extension |

## 6. Risk-Based Regulatory Architecture

The EU AI Act follows a risk-based regulatory architecture with different obligations depending on the category and use of the AI system.

The Commission identifies categories including:

- prohibited AI practices;
- high-risk AI;
- transparency-risk obligations;
- general-purpose AI;
- minimal or no-risk systems.

The Act's high-risk regime includes requirements relating to risk assessment and mitigation, data quality, logging, documentation, information to deployers, human oversight, robustness, cybersecurity, and accuracy. citeturn0search1

D-AIGAAF shares the principle that governance intensity should increase with risk and consequence.

However, D-AIGAAF applies this principle to a defence operational context rather than a European market-regulation context.

## 7. Prohibited Practices

The EU AI Act prohibits specified AI practices regarded as posing unacceptable risks.

The Commission's guidance explains that prohibited practices include areas such as harmful manipulation, social scoring, and certain biometric practices. citeturn0search11

For D-AIGAAF, prohibited-practice analysis should be treated as a **legal/policy applicability layer**, not as the complete defence AI risk model.

D-AIGAAF should ask:

1. Is the activity within the EU AI Act's scope?
2. If yes, does a prohibited practice apply?
3. If not, what applicable legal or policy restrictions govern the use?
4. What additional mission-specific restrictions are required?
5. What human authority and operational boundaries apply?

Thus:

**Legal Prohibition ≠ Complete Operational Risk Assessment**

## 8. High-Risk AI Concepts

The EU AI Act places substantial obligations on specified high-risk AI systems.

The Commission identifies requirements including:

- risk assessment and mitigation;
- high-quality datasets;
- logging;
- detailed documentation;
- information to deployers;
- human oversight;
- robustness;
- cybersecurity;
- accuracy. citeturn0search1

These concepts map strongly to D-AIGAAF.

However, D-AIGAAF does not use "high-risk" as its sole operational category.

It additionally considers:

**Mission Consequence × Autonomy × Environment × Human Authority × Evidence**

This means that an AI capability may require strong D-AIGAAF controls even if it does not fall into an EU AI Act high-risk category.

## 9. Risk Management Crosswalk

EU AI Act risk management concepts map primarily to Module 03.

D-AIGAAF provides:

- risk identification;
- risk analysis;
- risk evaluation;
- risk treatment;
- residual risk;
- risk acceptance;
- risk monitoring;
- autonomy assessment;
- human-control assessment;
- loss-of-control assessment.

The major extension is that D-AIGAAF explicitly connects risk to operational authority.

The chain is:

**Risk → Control → Evidence → Assurance → Authority → Conditions → Employment**

## 10. Data Governance

EU AI Act high-risk requirements include expectations around data governance and data quality.

D-AIGAAF Module 05 provides a broader lifecycle architecture:

- data governance;
- quality and integrity;
- provenance;
- lineage;
- representativeness;
- drift;
- poisoning;
- assurance;
- sharing;
- retention;
- disposal.

The D-AIGAAF extension is the explicit connection between data quality and operational consequence.

For example:

**Unrepresentative Data → Model Error → Incorrect Assessment → Human Decision → Mission Consequence**

## 11. Technical Documentation

The EU AI Act requires extensive documentation for relevant regulated AI systems, including information necessary for authorities and other actors to understand the system and assess compliance. citeturn0search1

D-AIGAAF addresses documentation through:

- Module 04 — AI Lifecycle;
- Module 09 — TEVV;
- Module 11 — Operational Authorisation;
- Module 12 — Operational Employment;
- Module 16 — Audit & Evidence;
- Module 25 — Documentation & Knowledge.

D-AIGAAF extends documentation from regulatory compliance into operational accountability.

The relevant record may need to establish:

**What was built → What was tested → What was authorised → Under what conditions → What changed → What happened operationally**

## 12. Logging and Traceability

EU AI Act high-risk obligations include logging to support traceability. citeturn0search1

D-AIGAAF extends this to operational traceability.

Where appropriate and lawful, records may include:

- AI capability/version;
- relevant inputs;
- outputs;
- uncertainty;
- human decisions;
- interventions;
- overrides;
- autonomy state;
- environmental conditions;
- security events;
- configuration;
- incidents;
- authorisation state.

The purpose is not indiscriminate collection.

Records should be proportionate to consequence, mission need, security, privacy, and applicable law.

## 13. Human Oversight

Human oversight is a significant EU AI Act concept for high-risk systems.

D-AIGAAF provides a much more extensive human-authority architecture through Module 08.

The D-AIGAAF distinction is:

**Human Oversight ≠ Human Authority**

A person may monitor a system without having:

- authority to stop it;
- authority to change its operating conditions;
- sufficient information;
- sufficient time;
- competence to interpret its output;
- ability to intervene effectively.

Meaningful human control therefore requires capability, authority, information, capacity, and accountability.

## 14. Human Oversight and Autonomy

D-AIGAAF explicitly links human oversight to autonomy.

Indicative autonomy levels:

| Level | Description |
|---|---|
| A0 | No Meaningful AI Decision |
| A1 | Information / Observation |
| A2 | Analysis / Recommendation |
| A3 | Human-Authorised Action |
| A4 | Supervised Autonomous Action |
| A5 | Independent Consequential Autonomy |

As autonomy and consequence increase, governance expectations should increase accordingly.

This is a D-AIGAAF operationalisation rather than a direct reproduction of the EU AI Act's legal categories.

## 15. Accuracy, Robustness and Cybersecurity

The EU AI Act imposes requirements concerning accuracy, robustness, and cybersecurity for relevant high-risk systems. citeturn0search1

D-AIGAAF addresses these through:

- Module 06 — AI Security;
- Module 09 — TEVV;
- Module 13 — Continuous Assurance;
- Module 24 — Architecture & Technical Controls.

D-AIGAAF additionally asks whether these characteristics remain adequate under the intended operational environment.

The question becomes:

**Is it robust enough for this mission, environment, autonomy level, and consequence?**

rather than merely:

**Does it satisfy a generic technical threshold?**

## 16. Conformity Assessment

The EU AI Act establishes conformity and regulatory obligations for applicable systems.

D-AIGAAF contains TEVV, audit, assurance, and operational-authorisation mechanisms.

These are related but not equivalent.

| EU AI Act | D-AIGAAF |
|---|---|
| Legal conformity | Governance and operational assurance |
| Regulatory requirements | Mission-specific requirements |
| Conformity assessment | TEVV + assurance + governance review |
| Regulatory authority | Operational authorising authority |
| Market access / use obligations | Mission-specific operational permission |

D-AIGAAF must not describe its own assurance or authorisation process as an EU AI Act conformity assessment unless the applicable legal requirements and assessment arrangements actually support that conclusion.

## 17. Quality Management

The EU AI Act includes quality-management expectations for relevant providers.

D-AIGAAF addresses comparable concepts through:

- lifecycle governance;
- configuration management;
- TEVV;
- evidence management;
- audit;
- continuous assurance;
- change management;
- maturity;
- implementation.

The distinction is that D-AIGAAF's quality objective is not limited to regulatory conformity.

It includes:

**Mission Fitness + Operational Control + Assurance + Authorisation**

## 18. Post-Market Monitoring and Continuous Assurance

The EU AI Act contains post-market monitoring concepts for applicable systems.

D-AIGAAF extends continuous monitoring into operational use through Module 13.

The lifecycle is:

**Deployment → Employment → Monitoring → Detection → Assurance Review → Corrective Action → Revalidation → Reauthorisation Where Required**

This is especially important for AI systems whose behaviour may change because of:

- model updates;
- data drift;
- environmental changes;
- new threats;
- changing dependencies;
- changing users;
- new mission contexts.

## 19. Serious Incidents

The EU AI Act establishes obligations concerning serious incidents for relevant regulated systems.

D-AIGAAF provides a broader incident architecture:

**Detect → Classify → Protect → Fail-Safe → Investigate → Correct → Recover → Reassess → Reauthorise → Learn**

The D-AIGAAF incident model considers both:

- compliance and governance implications; and
- operational consequences.

Where the EU AI Act applies, applicable incident-reporting obligations remain separate from D-AIGAAF internal governance requirements.

## 20. General-Purpose AI

The EU AI Act includes rules for providers of general-purpose AI models.

The Commission states that obligations for GPAI providers include technical documentation, information for downstream providers, copyright policy, and training-content summaries. Additional obligations apply to GPAI models with systemic risk, including risk assessment and mitigation, incident reporting, and cybersecurity protections. citeturn0search2turn0search3

D-AIGAAF is not a GPAI regulation.

However, GPAI can become relevant to defence AI through:

- procurement;
- integration;
- model supply chains;
- downstream systems;
- commercial providers;
- dual-use deployments.

D-AIGAAF should therefore require governance of upstream model dependencies even where the EU AI Act does not directly regulate the defence use.

## 21. Systemic-Risk GPAI

The EU AI Act creates additional obligations for GPAI models with systemic risk.

The Commission identifies areas including risk assessment and mitigation, incident reporting, and cybersecurity for such models. citeturn0search3

D-AIGAAF can use these concepts as supplier-assurance inputs.

For example:

**External GPAI Systemic Risk Controls → Supplier Evidence → D-AIGAAF Dependency Assessment → Security/TEVV Review → Operational Conditions**

This prevents upstream model governance from disappearing at the procurement boundary.

## 22. AI Literacy

The EU AI Act contains AI literacy obligations, and the Commission states that these entered into application from 2 February 2025. citeturn0search1

D-AIGAAF Module 17 provides a broader workforce architecture covering:

- AI literacy;
- competence;
- role-specific qualification;
- training;
- exercises;
- currency;
- workload;
- continuity;
- independence;
- human authority.

The D-AIGAAF principle is:

> AI literacy is necessary but may be insufficient for personnel exercising consequential AI authority.

Higher-consequence roles may require deeper competence and demonstrated qualification.

## 23. Transparency

The EU AI Act establishes transparency obligations for specified AI systems and providers/deployers.

The Commission states that Article 50 transparency obligations began applying from 2 August 2026. citeturn0search13turn0search10

D-AIGAAF addresses transparency primarily through:

- human understanding;
- uncertainty communication;
- operational information;
- decision traceability;
- documentation;
- records.

The purpose is somewhat different.

EU AI Act transparency is often connected to regulatory and user-facing obligations.

D-AIGAAF transparency is also concerned with **operational decision quality and human control**.

## 24. Fundamental Rights and Legal Considerations

The EU AI Act is strongly grounded in the protection of health, safety, and fundamental rights.

D-AIGAAF includes legal and policy governance through Module 21.

For systems potentially subject to EU law, D-AIGAAF should not attempt to replace the applicable legal assessment.

Instead:

**Legal Requirements → D-AIGAAF Governance Requirements → Controls → Evidence → Assurance**

This preserves the distinction between legal compliance and governance implementation.

## 25. Defence-Specific Operational Environment

The EU AI Act is a market and regulatory instrument rather than a defence operational-authorisation framework.

D-AIGAAF explicitly governs:

- adversarial conditions;
- degraded communications;
- disconnected operation;
- environmental variability;
- information uncertainty;
- operational boundaries;
- safe states;
- human intervention;
- operational readiness.

These areas are therefore primarily D-AIGAAF-specific.

## 26. Operational Authorisation

D-AIGAAF Module 11 establishes a dedicated operational-authorisation architecture.

The authorisation object is:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

The EU AI Act does not replace this architecture.

Even where the EU AI Act applies, regulatory compliance does not automatically establish operational authorisation under D-AIGAAF.

Conversely, where a purely military/defence use is excluded from the EU AI Act, D-AIGAAF operational authorisation remains fully relevant.

## 27. Operational Employment

D-AIGAAF Module 12 governs how authorised AI is actually employed.

It addresses:

- employment planning;
- human decision making;
- uncertainty;
- situational awareness;
- autonomy boundaries;
- degraded operation;
- intervention;
- monitoring;
- decision records;
- closeout;
- incidents;
- lessons learned.

This is largely a D-AIGAAF-specific extension.

## 28. Fail-Safe and Safe State

The EU AI Act contains requirements concerning risk management, human oversight, robustness, and safety for applicable systems.

D-AIGAAF turns these concepts into a dedicated fail-safe architecture.

The governance lifecycle is:

**Unexpected Behaviour → Detection → Protective Response → Safe State → Investigation → Recovery → Reassessment**

For a consequential defence capability, safe-state behaviour may need to be considered a prerequisite for operational authorisation.

## 29. Change and Reauthorisation

EU AI Act compliance may be affected by significant changes to an AI system.

D-AIGAAF makes this operationally explicit:

**Change → Impact Assessment → TEVV → Revalidation → Reauthorisation**

Changes may include:

- model;
- data;
- architecture;
- autonomy;
- interfaces;
- mission;
- environment;
- suppliers;
- security controls.

The core principle is:

> A system should not retain an old operational authorisation solely because the updated system remains technically similar.

## 30. Procurement and Supplier Governance

The EU AI Act creates obligations for providers and deployers depending on the system and role.

D-AIGAAF Module 22 adds a defence procurement perspective.

Procurement should assess:

- applicable legal obligations;
- AI risk;
- supplier assurance;
- security;
- data;
- model provenance;
- update control;
- TEVV evidence;
- dependencies;
- continuity;
- operational authorisation implications.

This is especially important when acquiring commercial AI capabilities that may later be used in defence contexts.

## 31. Dual-Use Procurement

A defence organisation may procure a system that is:

- civilian;
- commercial;
- dual-use;
- military-specific.

The legal applicability of the EU AI Act must be separately assessed.

D-AIGAAF should nevertheless maintain governance over:

**Supplier → AI Capability → Modification → Integration → Mission → Operational Use**

A civilian-origin AI component can become part of a consequential defence capability without losing the need for rigorous defence governance.

## 32. Regulatory Applicability Decision

D-AIGAAF Module 21 should incorporate an AI Act applicability decision where relevant.

The decision should consider:

1. Is the system an AI system under the Act?
2. Who is the provider/deployer?
3. Where is it placed on the market or put into service?
4. Where is it used?
5. What is the purpose?
6. Is the purpose exclusively military, defence, or national security?
7. Is there a civilian or other non-excluded purpose?
8. Is the system dual-use?
9. Which provisions apply?
10. What evidence supports the conclusion?

This should be recorded as a legal/policy determination and not inferred solely from organisational identity.

## 33. Crosswalk by D-AIGAAF Module

| D-AIGAAF Module | EU AI Act Relationship |
|---|---|
| 00 Framework | Conceptual alignment |
| 01 Strategy & Governance | Governance alignment |
| 02 Mission & Use Case | Risk/context alignment |
| 03 Risk & Autonomy | Strong risk alignment + autonomy extension |
| 04 AI Lifecycle | Lifecycle and documentation alignment |
| 05 Data & Information | Strong data-governance alignment |
| 06 AI Security | Cybersecurity/robustness alignment |
| 07 Supply Chain & Sovereignty | Supplier and dependency extension |
| 08 Human Authority | Human-oversight alignment + operational extension |
| 09 TEVV | Testing/evaluation/verification evidence |
| 10 Operational Environment | D-AIGAAF-specific |
| 11 Operational Authorisation | D-AIGAAF-specific |
| 12 Operational Employment | D-AIGAAF-specific |
| 13 Continuous Assurance | Post-deployment monitoring extension |
| 14 Incident & Fail-Safe | Incident and safety alignment + extension |
| 15 Change & Reauthorisation | Change-control extension |
| 16 Audit & Evidence | Documentation, evidence and governance alignment |
| 17 Workforce | AI literacy and competence alignment |
| 18 Maturity Model | Complementary |
| 19 Crosswalks | Interoperability |
| 20 Templates | Implementation support |
| 21 Legal & Policy | Primary applicability/legal layer |
| 22 Acquisition & Procurement | Provider/deployer and supplier interface |
| 23 Interoperability & Coalition | Cross-jurisdiction / coalition considerations |
| 24 Architecture & Technical Controls | Technical implementation |
| 25 Documentation & Knowledge | Documentation and traceability |
| 26 Retirement & Decommissioning | Lifecycle extension |
| 27 Implementation | Governance implementation |

## 34. EU AI Act Versus D-AIGAAF Risk Model

The two frameworks should not be reduced to identical risk matrices.

The EU AI Act uses legally defined categories and obligations.

D-AIGAAF uses a mission-specific governance model.

D-AIGAAF's risk architecture is:

**Consequence + Risk + Autonomy + Environment + Human Authority + Evidence**

This means a capability can have:

- low regulatory risk classification;
- high operational consequence.

Or:

- high regulatory obligations;
- low operational consequence in a particular use case.

The frameworks answer different questions.

## 35. EU AI Act Versus D-AIGAAF Authorisation

The distinction should be explicit:

| Question | EU AI Act | D-AIGAAF |
|---|---|---|
| Is the activity legally regulated? | Yes, where within scope | Governance applicability |
| Can the system be placed on market / used? | Subject to applicable legal obligations | Not the primary purpose |
| Has risk been assessed? | Required for applicable systems | Required |
| Is human oversight required? | For relevant systems | Explicitly governed |
| Has the system been technically evaluated? | Relevant to applicable obligations | Dedicated TEVV |
| Is it operationally authorised for a mission? | Not the D-AIGAAF concept | Dedicated authorisation |
| Can autonomy be increased? | Subject to applicable law | Requires explicit governance |
| Can continued use remain justified after change? | Subject to applicable obligations | Revalidation/reauthorisation |

## 36. Relationship to NIST AI RMF

A useful combined conceptual architecture is:

**EU AI Act → Legal / Regulatory Requirements**

**NIST AI RMF → AI Risk Management**

**ISO/IEC 42001 → AI Management System**

**ISO/IEC 23894 → AI Risk Management Guidance**

**ISO/IEC 27001 → Information Security Management**

**D-AIGAAF → Defence Mission, Autonomy, Human Authority, Assurance, Authorisation and Employment**

This is a major strength of the D-AIGAAF crosswalk programme.

D-AIGAAF should function as an integrating defence layer rather than attempting to replace every external framework.

## 37. Regulatory and Governance Evidence

Where EU AI Act requirements apply, evidence may include:

- risk-management records;
- data governance records;
- technical documentation;
- logs;
- human-oversight arrangements;
- testing evidence;
- cybersecurity evidence;
- conformity documentation;
- incident records;
- post-market monitoring records.

D-AIGAAF can integrate these into its own evidence chain:

**Requirement → Control → Evidence → Assurance → Authority → Conditions → Monitoring**

However, EU regulatory evidence should retain its own legal status and should not be altered merely to fit D-AIGAAF terminology.

## 38. Open-Source and Public Crosswalk Considerations

D-AIGAAF is intended to be an open, generic, unclassified framework.

Published EU AI Act crosswalk material should therefore:

- use the official Regulation as the authoritative legal source;
- identify the relevant Article/Annex where appropriate;
- avoid reproducing extensive copyrighted third-party guidance;
- distinguish legal text from interpretation;
- distinguish applicability from alignment;
- identify the defence exclusion clearly;
- avoid presenting D-AIGAAF as an EU compliance certification.

## 39. Limitations

This crosswalk has several important limitations.

### Legal Applicability

Whether the EU AI Act applies is a legal question determined by the specific facts and scope provisions.

### Defence Exclusion

Purely military, defence, or national-security use may be excluded under Article 2, but this does not mean every AI system associated with a defence organisation is automatically excluded.

### Dual-Use

Mixed-purpose systems require careful applicability analysis.

### Changing Law

The EU AI Act is being implemented progressively and associated guidance, standards, codes, and enforcement practice continue to develop.

### No Compliance Claim

Alignment with D-AIGAAF does not establish EU AI Act compliance.

## 40. Current Implementation Status

As of September 2026, the EU AI Act is in active implementation.

The Commission states that:

- prohibited AI practices and AI-literacy obligations have applied since 2 February 2025;
- GPAI obligations have applied since 2 August 2025;
- enforcement powers for GPAI obligations began on 2 August 2026;
- transparency obligations under Article 50 apply from 2 August 2026;
- certain high-risk AI rules have later transition dates, including 2 December 2027 for certain Annex III high-risk systems and 2 August 2028 for certain regulated-product systems. citeturn0search1turn0search2turn0search4

The implementation timeline should be treated as dynamic and verified against current official EU sources whenever this crosswalk is used for an actual compliance determination.

## 41. Crosswalk Maintenance

This crosswalk should be reviewed whenever:

- the EU AI Act is amended;
- implementing acts materially change obligations;
- delegated acts materially change requirements;
- Commission guidance changes interpretation;
- harmonised standards become applicable;
- enforcement practice materially develops;
- D-AIGAAF changes;
- defence/dual-use policy changes;
- a new AI use case creates an applicability question.

Each revision should record:

- legal source/version;
- date reviewed;
- D-AIGAAF version;
- crosswalk version;
- responsible owner;
- legal/policy reviewer where appropriate;
- applicability assumptions;
- unresolved questions.

## 42. Overall Assessment

The EU AI Act is highly relevant to D-AIGAAF as a **reference point for modern risk-based AI regulation**, even though exclusively military, defence, and national-security AI uses are expressly excluded from its scope.

The strongest conceptual alignments are:

- risk management;
- data governance;
- documentation;
- traceability;
- human oversight;
- robustness;
- cybersecurity;
- incident management;
- AI literacy;
- lifecycle governance;
- continuous monitoring.

The strongest D-AIGAAF extensions are:

- mission-specific consequence;
- autonomy;
- human operational authority;
- operational environment;
- degraded/disconnected operation;
- operational authorisation;
- operational employment;
- fail-safe;
- reauthorisation;
- defence supply-chain sovereignty.

## 43. Core Rule

> **The EU AI Act should be treated by D-AIGAAF as an important regulatory reference and source of governance principles, not as the legal foundation of defence AI governance. Its explicit military, defence, and national-security scope exclusion makes D-AIGAAF's independent defence governance architecture essential.**

The relationship is:

**EU AI Act → Applicable Legal Requirements Where Within Scope**

**NIST / ISO Frameworks → Risk, Management and Security Foundations**

**D-AIGAAF → Defence Mission + Risk + Autonomy + Human Authority + Assurance + Operational Authorisation + Employment**

The critical principle is:

**Regulatory Compliance ≠ Operational Authorisation**

and:

**Military/Defence Exclusion from EU AI Act ≠ Exemption from AI Governance**

## 44. Source and Version Record

Primary legal source:

**Regulation (EU) 2024/1689 of the European Parliament and of the Council of 13 June 2024 laying down harmonised rules on artificial intelligence (Artificial Intelligence Act).** citeturn0search0turn0search24

Primary implementation source:

**European Commission — AI Act policy and implementation materials.** citeturn0search1turn0search4

The crosswalk should be maintained against the current official EU legal text, implementing measures, delegated acts, Commission guidance, and applicable amendments.

It should not be used as a substitute for legal advice or a formal EU AI Act applicability/conformity assessment.
