# 19 Operational Deployment Readiness and Entry

## 1. Purpose

Operational deployment is the controlled transition of an authorised and operationally ready Defence AI capability into its intended operational setting.

This stage confirms that the capability can move from readiness assessment to actual deployment without losing the mission, assurance, human authority, autonomy, security, environmental and operational boundaries on which its authorisation depends.

Deployment shall not be treated as an administrative act. It is a controlled governance transition between **readiness** and **operational employment**.

---

## 2. Core Principle

A Defence AI capability shall enter operational deployment only when:

- the required operational authorisation is valid;
- current readiness has been established;
- the deployed configuration matches the authorised configuration;
- deployment conditions are within the approved scope;
- human authority and required competence are available;
- required security, data and dependency controls are functioning;
- monitoring and escalation mechanisms are active; and
- any deployment-specific restrictions or conditions are satisfied.

Deployment shall not create, expand or imply operational authority beyond the existing authorisation.

---

## 3. Deployment Object

Deployment should remain linked to the D-AIGAAF operational authorisation object:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

A deployment is therefore valid only when the deployed capability, intended mission, operating environment, autonomy level and human authority remain consistent with the authorised basis.

---

## 4. Deployment States

D-AIGAAF defines the following working deployment states:

| State | Meaning |
|---|---|
| **Planned** | Deployment is being prepared but has not received final entry confirmation. |
| **Approved for Deployment** | Required governance conditions have been satisfied and deployment may proceed. |
| **In Deployment** | The capability is being transitioned into the intended operational setting. |
| **Operationally Deployed** | Deployment has been completed and the capability is available for authorised employment. |
| **Restricted Deployment** | Deployment is permitted only within specified additional restrictions. |
| **Deployment Halted** | Deployment has been stopped because required conditions are no longer satisfied. |
| **Deployment Reversed** | The capability has been withdrawn from the deployment process and returned to an approved prior state or safe state. |

These states should be recorded and traceable.

---

## 5. Deployment Entry Criteria

Before deployment begins, the responsible authority should confirm:

1. A valid Operational Authorisation Record exists.
2. The capability is currently Ready or Conditionally Ready.
3. The deployment destination and environment are authorised.
4. The approved configuration baseline is verified.
5. Required software, hardware and interfaces are available.
6. Required data and information sources are available and sufficiently trustworthy.
7. Required security controls are active.
8. Critical dependencies are available or approved contingencies are established.
9. Human authority and supervision arrangements are established.
10. Personnel required for deployment and subsequent operation are competent and available.
11. Fail-safe, intervention and recovery mechanisms are available.
12. Monitoring and escalation mechanisms are active.
13. Deployment-specific conditions are understood and accepted.
14. No unresolved material change or incident invalidates readiness.
15. The deployment decision is recorded.

---

## 6. Deployment Configuration Control

The configuration deployed shall be positively identified and traceable.

At minimum, the deployment record should identify, where applicable:

- system identifier;
- model identifier;
- model version;
- software version;
- relevant hardware configuration;
- configuration baseline;
- data or knowledge baseline where material;
- security configuration;
- interfaces and dependencies;
- enabled capabilities;
- enabled autonomy functions;
- disabled or restricted functions; and
- deployment date and responsible authority.

The deployed configuration shall not be assumed to be identical to the tested or authorised configuration without verification.

---

## 7. Deployment Verification

Deployment verification should establish that the deployed capability corresponds materially to the configuration for which assurance and authorisation were established.

Verification should consider:

- configuration integrity;
- software and model identity;
- approved interfaces;
- data sources;
- security controls;
- system dependencies;
- autonomy controls;
- human-control mechanisms;
- fail-safe mechanisms;
- logging and monitoring;
- communication pathways; and
- operational support arrangements.

Where verification identifies a material discrepancy, deployment should pause until the discrepancy is assessed.

---

## 8. Deployment Environment Confirmation

The deployment environment should be assessed against the authorised operating envelope.

Relevant conditions may include:

- physical environment;
- terrain and weather;
- sensor conditions;
- communications;
- information availability;
- electromagnetic conditions;
- navigation;
- computing and power;
- human operating conditions; and
- adversarial conditions.

The purpose is not to require perfect environmental conditions, but to establish that the actual environment remains within the conditions for which the capability is authorised.

---

## 9. Human Authority at Deployment

Deployment shall preserve clearly identifiable human authority.

Before deployment:

- responsible command authority should be identified;
- operational decision rights should be understood;
- operator and supervisor responsibilities should be established;
- escalation paths should be available;
- intervention and override responsibilities should be clear; and
- the Operational AI Advisor role should be available where required by the governance model.

AI systems may support deployment decisions but shall not independently grant themselves operational authority.

---

## 10. Autonomy Verification

The autonomy level deployed shall match the authorised autonomy level.

Verification should establish:

- authorised autonomy state;
- permitted actions;
- prohibited actions;
- human approval requirements;
- supervision requirements;
- autonomy transition conditions;
- intervention mechanisms; and
- fail-safe behaviour.

A system capable of higher autonomy shall not be considered authorised for that higher autonomy merely because the capability exists technically.

---

## 11. Security and Integrity Verification

Before deployment, appropriate controls should establish that:

- the deployed system is authentic and has not been materially altered;
- security-relevant configuration is correct;
- critical interfaces are protected;
- monitoring is functioning;
- known critical vulnerabilities are appropriately managed;
- data integrity controls are active; and
- relevant security incidents or warnings have been assessed.

Deployment should be halted where a material security condition could invalidate the authorisation basis.

---

## 12. Data and Information Verification

Deployment should confirm that:

- required data sources are available;
- data provenance is sufficiently understood;
- data integrity requirements are satisfied;
- information latency is within authorised limits;
- relevant uncertainty can be communicated;
- known data limitations are understood; and
- degraded data conditions have defined responses.

The presence of data shall not be treated as evidence that the data is suitable for the intended decision.

---

## 13. Dependency and Continuity Verification

Critical dependencies should be identified and assessed before deployment.

These may include:

- communications;
- navigation;
- power;
- compute infrastructure;
- external services;
- supporting information systems;
- maintenance arrangements;
- human expertise; and
- other systems required for safe or effective operation.

For each critical dependency, the deployment plan should identify appropriate fallback, degraded or safe-state behaviour where practicable.

---

## 14. Deployment in Degraded or Disconnected Conditions

Where deployment into degraded or disconnected conditions is authorised, the deployment assessment should confirm:

- the relevant degraded operating mode;
- autonomy restrictions;
- local processing requirements;
- human-control arrangements;
- data limitations;
- communication-loss behaviour;
- fail-safe behaviour;
- recovery procedures; and
- conditions for returning to normal operation.

Loss of connectivity shall not automatically expand autonomy or decision authority.

---

## 15. Deployment Handover

Where responsibility moves between organisations, teams or operational authorities, a controlled handover should occur.

The handover should establish:

- capability identity;
- authorisation status;
- configuration;
- mission and use case;
- operating boundaries;
- autonomy level;
- human decision rights;
- known limitations;
- current risk status;
- monitoring requirements;
- contingency arrangements;
- incident status;
- support arrangements; and
- responsible authorities.

The receiving authority should acknowledge the information required to operate within the authorisation.

---

## 16. Deployment Restrictions

A deployment may be approved with additional restrictions where residual uncertainty or operational conditions require additional controls.

Restrictions may include:

- reduced mission scope;
- reduced autonomy;
- additional human supervision;
- restricted environment;
- additional monitoring;
- limited duration;
- restricted functions;
- additional confirmation before consequential actions;
- enhanced reporting; or
- staged operational entry.

Restrictions should be explicit, recorded and enforceable.

---

## 17. Staged Deployment

For higher-consequence or higher-autonomy capabilities, staged deployment may provide an additional control layer.

A staged approach may progress through:

**Controlled Introduction → Limited Operational Use → Expanded Authorised Use → Full Authorised Employment**

Progression should depend on evidence and operational observations rather than automatic passage of time.

Each stage should have defined:

- entry criteria;
- operating boundaries;
- monitoring requirements;
- success criteria;
- stop criteria;
- escalation criteria; and
- approval authority.

---

## 18. Deployment Halt Criteria

Deployment should be halted where:

- authorisation becomes invalid;
- readiness is lost;
- the configuration cannot be verified;
- a material unauthorised change is identified;
- required human authority is unavailable;
- critical security controls fail;
- critical data integrity is compromised;
- a required dependency fails without an approved fallback;
- fail-safe or intervention mechanisms are unavailable where required;
- the environment moves outside the authorised envelope;
- material unexpected AI behaviour is observed; or
- a serious incident creates uncertainty about safe deployment.

A deployment halt is a protective governance action and should not itself be treated as evidence of system failure.

---

## 19. Deployment Reversal

Where deployment cannot safely continue, the capability should have an approved mechanism for:

- stopping deployment;
- reverting to a verified prior configuration where appropriate;
- entering a safe state;
- restricting functionality;
- withdrawing the capability;
- preserving evidence; and
- notifying responsible authorities.

Reversal should not silently restore a configuration whose authorisation or assurance status is no longer valid.

---

## 20. Operational Acceptance

Following successful deployment, the responsible authority should confirm that:

- the deployed capability matches the authorised configuration;
- deployment conditions were satisfied;
- required human authority is established;
- monitoring is functioning;
- restrictions are understood;
- contingency arrangements are available; and
- the capability is ready to transition into operational employment.

Operational acceptance should be recorded.

---

## 21. Relationship to Operational Employment

Deployment and employment are distinct governance states.

**Deployment** establishes that the authorised capability has been introduced into the intended operational setting.

**Employment** concerns the actual use of that capability to perform its authorised functions.

The sequence should therefore be:

**Assurance → Authorisation → Readiness → Deployment → Operational Acceptance → Employment → Monitoring**

Deployment shall not be interpreted as permission to use the capability outside its authorisation.

---

## 22. Relationship to Continuous Assurance

Deployment creates an important assurance checkpoint.

Evidence generated during deployment may identify:

- environmental differences;
- configuration discrepancies;
- unexpected behaviour;
- human factors;
- dependency weaknesses;
- data limitations;
- security concerns; or
- previously unidentified operational risks.

Such findings should feed into continuous assurance and, where material, into revalidation or reauthorisation.

---

## 23. Deployment Record

A controlled Deployment Record should contain, as applicable:

- capability identifier;
- authorisation identifier;
- readiness record identifier;
- deployment location/environment;
- mission/use case;
- deployed configuration;
- autonomy level;
- human authority;
- responsible personnel;
- security status;
- data/information status;
- dependency status;
- deployment conditions;
- restrictions;
- verification results;
- issues identified;
- deployment decision;
- operational acceptance decision;
- date and time;
- decision authority; and
- supporting evidence.

The Deployment Record should remain linked to the Operational Authorisation Record and subsequent Operational Record.

---

## 24. Golden Thread

Deployment should remain traceable through the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Readiness → Deployment → Employment → Monitoring → Change/Incident → Reauthorisation**

This ensures that the deployed capability can be traced back to the mission need, assurance evidence and authority that justify its use.

---

## 25. Governance Questions

Before approving deployment, the responsible authority should be able to answer:

1. What capability is being deployed?
2. Under which operational authorisation?
3. What configuration is being deployed?
4. Has that configuration been verified?
5. What mission and use case apply?
6. What environment is the capability entering?
7. Is that environment within the authorised envelope?
8. What autonomy level is authorised?
9. Can that autonomy level be enforced?
10. Who holds human decision authority?
11. Are required personnel competent and available?
12. Are security controls functioning?
13. Are data and information sufficiently reliable?
14. Are critical dependencies available?
15. Are fail-safe and intervention mechanisms available?
16. Are monitoring and escalation mechanisms active?
17. Are deployment-specific restrictions satisfied?
18. What would require deployment to be halted?
19. Can the deployment be safely reversed if required?
20. Has operational acceptance been recorded?

If these questions cannot be answered with sufficient confidence, deployment should not proceed without appropriate escalation or additional assurance.

---

## 26. Core Rule

> **Deployment is a controlled transition, not an expansion of authority. A Defence AI capability shall enter its operational setting only after its authorisation, current readiness, configuration, environment, autonomy, human authority and required safeguards have been verified and recorded.**
