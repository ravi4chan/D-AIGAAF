# 18 Operational Readiness

## 1. Purpose

Operational readiness is the final pre-employment determination that an authorised Defence AI capability can be used safely, effectively and within its approved boundaries for the specific mission, environment, autonomy level, human authority, configuration and conditions under which employment is intended.

Operational readiness does not replace operational authorisation. **Authorisation grants permission; readiness confirms that the capability is currently able to enter operational employment on the authorised basis.**

---

## 2. Core Principle

A Defence AI capability shall not be employed merely because an operational authorisation exists.

Before operational entry, the responsible authority shall establish that:

- the intended mission and use case remain valid;
- the authorised configuration is available and verified;
- required assurance evidence remains current and applicable;
- the operating environment is within the authorised envelope;
- human authority, competence and supervision are available;
- the authorised autonomy level can be maintained;
- required data, information and dependencies are available and trustworthy;
- security controls remain effective;
- fail-safe, intervention and contingency arrangements are available;
- monitoring and escalation mechanisms are functioning; and
- no known condition invalidates the basis of authorisation.

---

## 3. Readiness Object

Operational readiness should be assessed against the same contextual object used for operational authorisation:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Readiness is therefore specific to the intended employment rather than being an intrinsic property of the AI system.

A capability may be:

- ready for one mission but not another;
- ready in one environment but not another;
- ready at one autonomy level but not at a higher level;
- ready with one configuration but not after an unassessed change; or
- technically functional but operationally not ready because human authority or required safeguards are unavailable.

---

## 4. Readiness Dimensions

Operational readiness should consider, at minimum:

### 4.1 Mission Readiness

Confirm that:

- the authorised mission remains valid;
- the approved use case has not materially changed;
- mission objectives and success criteria remain applicable;
- authorised functions remain appropriate; and
- no new mission condition invalidates the assurance basis.

### 4.2 System and Configuration Readiness

Confirm:

- approved hardware and software are available;
- the authorised model/system version is installed;
- the configuration baseline is verified;
- unauthorised modifications are absent;
- interfaces and dependencies are functioning; and
- required rollback or recovery mechanisms are available.

### 4.3 Assurance and Evidence Readiness

Confirm that:

- required TEVV evidence remains current;
- relevant limitations are understood;
- unresolved critical findings are absent or formally controlled;
- evidence applies to the intended mission and environment; and
- material changes since the last assurance activity have been assessed.

### 4.4 Environmental Readiness

Confirm that the current operating environment is within the authorised envelope, including relevant:

- physical conditions;
- sensor conditions;
- communications availability;
- information conditions;
- electromagnetic conditions;
- navigation conditions;
- computing and power conditions;
- human factors; and
- adversarial conditions.

### 4.5 Human Readiness

Confirm:

- authorised personnel are available;
- required competence and AI literacy are present;
- decision rights are understood;
- supervision arrangements are established;
- intervention and override responsibilities are clear; and
- workload and situational-awareness conditions are acceptable.

### 4.6 Autonomy and Control Readiness

Confirm:

- the authorised autonomy level is known;
- autonomy boundaries are configured;
- transitions between autonomy states are controlled;
- human supervision is available where required;
- intervention and override mechanisms are functional; and
- the capability cannot silently exceed its authorised autonomy.

### 4.7 Security Readiness

Confirm:

- required security controls are active;
- system integrity is established;
- relevant threats and vulnerabilities have been considered;
- security monitoring is functioning; and
- no unresolved security condition invalidates operational employment.

### 4.8 Data and Information Readiness

Confirm:

- required data sources are available;
- data integrity and provenance remain acceptable;
- information is sufficiently timely and relevant;
- known data limitations are understood;
- uncertainty can be communicated appropriately; and
- degraded data conditions are within authorised boundaries.

### 4.9 Dependency and Continuity Readiness

Confirm availability and acceptable status of critical dependencies, including:

- communications;
- navigation;
- power;
- compute resources;
- external services;
- supporting systems;
- maintenance support; and
- human expertise.

Critical dependencies should have defined fallback or contingency arrangements where practicable.

### 4.10 Fail-Safe and Contingency Readiness

Confirm:

- fail-safe mechanisms are available;
- intervention mechanisms are functional;
- safe-state behaviour is understood;
- contingency procedures are available;
- degraded and disconnected modes have been considered; and
- responsible personnel understand when and how protective action may be taken.

### 4.11 Monitoring and Record Readiness

Confirm that:

- required operational monitoring is active;
- relevant thresholds and alerts are configured;
- escalation channels are available;
- operational records can be captured; and
- significant events can be reconstructed after employment.

---

## 5. Readiness States

D-AIGAAF defines the following working readiness states:

| State | Meaning |
|---|---|
| **Ready** | All mandatory readiness conditions are satisfied and the capability may enter employment within the authorisation scope. |
| **Conditionally Ready** | Employment may proceed only under explicitly defined additional conditions or restrictions. |
| **Not Ready** | One or more mandatory readiness requirements are not satisfied. Employment should not begin. |
| **Temporarily Not Ready** | Readiness is absent because of a temporary condition that may be corrected without necessarily changing the authorisation basis. |
| **Suspended** | Operational authority or readiness has been suspended and employment shall not proceed until the defined restoration requirements are satisfied. |

Readiness status should be recorded rather than inferred.

---

## 6. Pre-Employment Entry Criteria

Before operational entry, the responsible authority should confirm at least:

1. The intended mission is within the authorised use case.
2. The current environment is within the authorised operating envelope.
3. The authorised configuration has been verified.
4. The approved autonomy level is available and correctly configured.
5. Required human authority and supervision are present.
6. Required personnel are competent and available.
7. Assurance evidence remains applicable and sufficiently current.
8. Required security controls are functioning.
9. Required data and information are available and sufficiently trustworthy.
10. Critical dependencies are available or approved contingency arrangements are active.
11. Fail-safe and intervention mechanisms are available.
12. Monitoring and escalation arrangements are functioning.
13. No unresolved incident or change invalidates the authorisation basis.
14. Any conditional authorisation requirements are satisfied.
15. The readiness decision is recorded.

---

## 7. No-Go Criteria

Operational entry should not occur where, for example:

- the capability is outside its authorised mission;
- the current environment exceeds the approved operating envelope;
- the configuration cannot be verified;
- required human authority is unavailable;
- required supervision cannot be maintained;
- authorised autonomy cannot be reliably enforced;
- critical safety or security controls are unavailable;
- required evidence has been invalidated by material change;
- critical data integrity cannot be established;
- a mandatory dependency has failed without an approved fallback;
- fail-safe or intervention mechanisms are unavailable where required;
- a serious unresolved incident affects operational safety or assurance; or
- a mandatory authorisation condition has not been satisfied.

A technical ability to operate shall not override a no-go condition.

---

## 8. Final Pre-Employment Check

The final readiness check should be performed as close as reasonably practicable to operational entry.

It should verify:

**Mission → Environment → Configuration → Autonomy → Human Authority → Security → Data → Dependencies → Fail-Safe → Monitoring → Conditions**

Where a significant delay occurs between readiness confirmation and employment, the responsible authority should determine whether the readiness assessment remains valid.

---

## 9. Last-Minute Changes

Changes occurring after readiness has been confirmed should be assessed before employment.

Examples include:

- model or software updates;
- configuration changes;
- changes to data sources;
- loss of communications;
- environmental deterioration;
- change in mission;
- change in autonomy;
- change in available personnel;
- security alerts;
- dependency failures; or
- changes to authorised conditions.

A material change should trigger the applicable change-control, revalidation or reauthorisation process.

---

## 10. Readiness Recheck

A readiness recheck should be conducted where:

- employment is delayed materially;
- the operating environment changes;
- the system configuration changes;
- personnel or decision authority changes;
- a critical dependency becomes unavailable;
- a security or data-integrity concern arises;
- an incident occurs; or
- a condition supporting readiness can no longer be demonstrated.

The objective is to prevent **readiness drift** between the original assessment and actual employment.

---

## 11. Conditional Readiness

Conditional readiness may be used where operational employment remains acceptable under additional controls.

Examples include:

- reduced autonomy;
- increased human supervision;
- restricted mission scope;
- restricted environment;
- enhanced monitoring;
- additional confirmation before consequential actions;
- reduced dependency on external services;
- additional reporting requirements; or
- shorter review intervals.

Every condition should have:

- a responsible authority;
- a clear requirement;
- an acceptance criterion;
- a method of verification; and
- a defined response if the condition is not met.

---

## 12. Readiness Decision Rights

Readiness should be determined by the authority designated under the operational governance model.

The decision should consider inputs from:

- Command/Operational Authority;
- Authorising Authority;
- Operational AI Advisor;
- Technical Authority;
- Assurance/TEVV Authority;
- Security Authority;
- System Manager;
- Risk Owner; and
- Operator/User.

Technical personnel may confirm technical readiness, but technical functionality alone does not establish operational readiness.

Where readiness is uncertain and the consequence of failure is significant, the decision should default toward restriction, additional assurance or non-entry until the uncertainty is resolved or explicitly accepted by the appropriate authority.

---

## 13. Operational Briefing and Acknowledgement

Before employment, relevant personnel should understand:

- mission and authorised purpose;
- operational boundaries;
- authorised autonomy;
- human decision rights;
- system limitations;
- known uncertainty;
- prohibited or restricted uses;
- intervention and override procedures;
- fail-safe behaviour;
- contingency arrangements;
- escalation procedures; and
- incident-reporting requirements.

Where appropriate, acknowledgement of these conditions should form part of the operational record.

---

## 14. Readiness Record

The readiness decision should generate or update an **Operational Readiness Record** containing, as applicable:

- capability identifier;
- authorisation identifier;
- mission/use case;
- date and time of assessment;
- configuration baseline;
- environment assessment;
- autonomy level;
- human authority;
- responsible personnel;
- assurance status;
- security status;
- data/information status;
- dependency status;
- fail-safe/contingency status;
- conditions and restrictions;
- readiness state;
- unresolved issues;
- decision authority;
- decision rationale;
- validity period or reassessment requirement; and
- relevant evidence references.

The record should be traceable to the Operational Authorisation Record and supporting assurance evidence.

---

## 15. Relationship to Operational Authorisation

Operational authorisation and readiness answer different questions:

| Governance Decision | Core Question |
|---|---|
| **Assurance** | Is the capability sufficiently understood and evidenced? |
| **Operational Authorisation** | Is this capability permitted for this defined operational use? |
| **Operational Readiness** | Is it currently ready to enter that authorised use? |
| **Operational Employment** | What actually happened during use? |
| **Continuous Assurance** | Does the basis for safe and authorised use remain valid? |

The sequence is therefore:

**Assurance → Authorisation → Readiness → Employment → Monitoring**

Readiness does not expand authorisation.

---

## 16. Relationship to Degraded and Disconnected Operations

Readiness must consider whether the capability can remain within authorised boundaries when communications, data, sensors, navigation, computing or other dependencies degrade.

Where degraded operation is authorised:

- the approved degraded mode should be known;
- autonomy restrictions should be understood;
- human authority should remain defined;
- fail-safe behaviour should be available;
- transition thresholds should be established; and
- recovery or safe-state procedures should be known.

Loss of connectivity shall not silently create additional AI authority.

---

## 17. Relationship to Continuous Assurance

Operational readiness is a point-in-time determination within a wider continuous-assurance system.

Operational monitoring may identify conditions that invalidate readiness after employment begins.

This creates the feedback loop:

**Readiness → Employment → Monitoring → Change/Incident → Reassessment → Revalidation/Reauthorisation where required**

Readiness should therefore be treated as a controlled state rather than a permanent attribute.

---

## 18. Golden Thread

Operational readiness should remain traceable through the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Readiness → Employment → Monitoring → Change/Incident → Reauthorisation**

Every readiness decision should be capable of being traced backward to the evidence and authority supporting it, and forward to the operational record showing what occurred.

---

## 19. Governance Questions

Before declaring an AI capability operationally ready, the responsible authority should be able to answer:

1. What mission is about to be undertaken?
2. Is that mission within the authorised scope?
3. What environment is the capability entering?
4. Is that environment within the demonstrated operating envelope?
5. What configuration is being used?
6. Has the configuration changed since assurance or authorisation?
7. What autonomy level is authorised?
8. Can that autonomy level be reliably maintained?
9. Who holds human decision authority?
10. Are the required personnel competent and available?
11. Is meaningful human control practicable?
12. Are data and information sufficiently reliable?
13. Are critical dependencies available?
14. Are security controls functioning?
15. Are fail-safe and intervention mechanisms available?
16. Are monitoring and escalation mechanisms active?
17. Are all mandatory authorisation conditions satisfied?
18. What known uncertainties remain?
19. What would cause readiness to be withdrawn?
20. Has the readiness decision been recorded?

If these questions cannot be answered with sufficient confidence, operational entry should not be assumed.

---

## 20. Core Rule

> **An operationally authorised Defence AI capability shall not be employed merely because authority exists; current readiness for the specific mission, environment, configuration, autonomy and human-control conditions shall be established before operational entry.**
