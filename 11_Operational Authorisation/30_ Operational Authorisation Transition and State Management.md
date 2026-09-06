# 30 Operational Authorisation Transition and State Management

## 1. Purpose

A Defence AI capability may move through multiple operational states during its authorised lifecycle: preparation, deployment, active employment, degraded operation, contingency, restriction, safe state, suspension and restoration.

These transitions can affect autonomy, human control, risk, mission effectiveness and operational authority.

This document defines governance for transitions between operational states.

The objective is to ensure that:

- every material state is defined;
- entry and exit criteria are known;
- authority remains explicit during transitions;
- autonomy does not change without appropriate authority;
- human control is preserved;
- transitions are monitored and recorded;
- failed transitions have predefined responses; and
- the capability does not enter an unintended operational state.

---

## 2. Core Principle

**A transition between operational states is itself a governed event.**

A Defence AI capability shall not be assumed to retain the same risk, autonomy or authority simply because it remains technically operational.

---

## 3. State Model

A working state model may include:

**Not Authorised → Authorised → Ready → Deployed → Active Employment → Restricted/Degraded → Contingency → Safe State → Suspended → Revalidated/Reauthorised → Restored**

The exact states should be adapted to the capability.

---

## 4. State Definition

Each material state should define:

- purpose;
- permitted functions;
- prohibited functions;
- authorised autonomy;
- human authority;
- operating environment;
- configuration;
- monitoring;
- entry criteria;
- exit criteria;
- transition authority; and
- records required.

An undefined state should not become an informal operating mode.

---

## 5. Transition Categories

Transitions may be:

- planned;
- condition-triggered;
- command-directed;
- automatically initiated protective transitions where authorised;
- emergency;
- incident-driven;
- environment-driven;
- autonomy-driven;
- configuration-driven; or
- assurance-driven.

The authority and controls should correspond to the type of transition.

---

## 6. Transition Authority

The organisation should identify who may:

- initiate a transition;
- approve a transition;
- direct a reduction in autonomy;
- require human control;
- place the capability into a safe state;
- suspend employment;
- restore a capability; and
- authorise a return to normal employment.

Technical personnel should not automatically possess operational transition authority.

---

## 7. Transition Conditions

Transition conditions should be defined in advance where practicable.

Examples include:

- mission phase;
- environmental boundary;
- communications availability;
- sensor availability;
- system performance;
- security state;
- data integrity;
- human availability;
- autonomy condition;
- dependency status;
- incident status; or
- risk threshold.

---

## 8. Entry Criteria

Before entering a new operational state, the organisation should determine whether required conditions are satisfied.

Entry criteria may include:

- valid authorisation;
- current readiness;
- correct configuration;
- appropriate environment;
- appropriate autonomy;
- available human authority;
- required monitoring;
- required security;
- required data integrity;
- critical dependency availability; and
- operational acceptance.

---

## 9. Exit Criteria

Exit criteria should establish when the capability must leave the current state.

Examples include:

- mission completion;
- environmental boundary crossing;
- loss of required communication;
- loss of human supervision;
- unacceptable performance;
- security compromise;
- critical dependency failure;
- incident;
- autonomy anomaly;
- command direction; or
- authorisation expiry.

---

## 10. Transition Verification

Material transitions should be verified where practicable.

Verification may include:

- system status;
- configuration;
- autonomy;
- human authority;
- environment;
- security;
- data;
- dependencies;
- mission;
- restrictions; and
- monitoring.

The transition should not rely solely on the assumption that the system entered the intended state.

---

## 11. Autonomy Transitions

Autonomy changes require particular governance.

The organisation should identify:

- current autonomy;
- target autonomy;
- reason;
- authority;
- conditions;
- human supervision;
- intervention capability;
- expected behaviour;
- verification; and
- rollback or reduction mechanism.

A transition to a higher-consequence autonomy level should require the appropriate authorisation.

---

## 12. Human-Control Transitions

Transitions affecting human control should be explicitly governed.

Examples include:

**Human Supervision → Reduced Supervision**

or:

**Reduced Supervision → Direct Human Control**

The organisation should verify that the receiving human authority is:

- available;
- competent;
- informed;
- able to intervene; and
- able to understand relevant AI limitations and uncertainty.

---

## 13. Degraded-State Transition

A capability may enter degraded operation because of:

- communications degradation;
- sensor degradation;
- data degradation;
- compute limitations;
- environmental change;
- dependency failure;
- security concerns; or
- performance degradation.

The degraded state should have predefined limitations.

Degradation should not silently expand AI authority.

---

## 14. Contingency Transition

Contingency operation should define:

- trigger;
- authority;
- permitted functions;
- autonomy;
- human control;
- limitations;
- monitoring;
- duration;
- exit criteria; and
- recovery.

Contingency operation should remain bounded by the authorisation framework.

---

## 15. Safe-State Transition

A safe-state transition should be available where continued employment creates unacceptable or uncertain risk.

The transition should define:

- trigger;
- authority;
- system behaviour;
- human involvement;
- operational consequences;
- recovery conditions;
- evidence preservation; and
- restoration authority.

Automatic protective transition may be used where explicitly designed, tested and authorised.

---

## 16. Suspension Transition

Transition to suspension should remove operational authority for the affected scope.

Triggers may include:

- serious incident;
- loss of meaningful human control;
- critical security issue;
- material configuration discrepancy;
- failed mandatory condition;
- unacceptable performance;
- invalid assurance evidence;
- authorisation expiry; or
- other defined conditions.

Suspension should be recorded and visible.

---

## 17. Restoration Transition

Restoration should not simply reverse a previous transition.

Before restoring normal employment, the organisation should determine whether:

- the triggering condition has been resolved;
- system integrity is established;
- configuration is known;
- human authority is available;
- autonomy is appropriate;
- environment is suitable;
- dependencies are available;
- assurance evidence remains valid; and
- authorisation remains applicable.

---

## 18. Failed Transition

A transition may fail because:

- system state is uncertain;
- required condition is absent;
- human authority is unavailable;
- configuration cannot be verified;
- communications fail;
- dependencies are unavailable;
- expected behaviour is not observed; or
- safety controls do not respond as expected.

The response should be predefined.

Possible response:

**Retry Safely → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

---

## 19. Unexpected Transition

Unexpected or unexplained state changes should be treated as governance events.

The organisation should determine:

- what changed;
- why it changed;
- whether the transition was authorised;
- what autonomy changed;
- whether human control was affected;
- whether mission scope changed;
- whether security was affected; and
- whether additional assurance is required.

---

## 20. State Conflicts

Where system indicators, human reports or governance records indicate conflicting states, the organisation should use defined reconciliation procedures.

Examples include:

- system reports Active while command records Suspended;
- system reports authorised configuration while deployed configuration differs;
- AI reports autonomous mode while human authority expects supervised operation.

Ambiguous state should not be interpreted as permission for higher-risk activity.

---

## 21. State and Configuration

A material configuration change may require a state transition before operational use.

For example:

**Operational → Change Control → Revalidation → Readiness → Authorised Employment**

Configuration changes should not occur silently within an operational state where they could invalidate assurance.

---

## 22. State and Environment

Environmental changes may require transition between:

- nominal;
- challenging;
- boundary;
- degraded;
- contingency; or
- outside-envelope conditions.

The appropriate response should be linked to the authorised operating envelope.

---

## 23. State and Mission Changes

A new mission or materially changed mission should not be treated merely as a state transition if it changes the authorisation basis.

Where necessary:

**Current Employment → Closeout → New Mission Assessment → Authorisation → Readiness → Employment**

This prevents mission expansion through informal operational transitions.

---

## 24. State and Incident Management

Incidents may trigger immediate state changes.

The organisation should establish links between:

**Incident → Risk Assessment → Protective State → Investigation → Assurance → Restoration/Reauthorisation**

State transition should not wait for completion of a full investigation when immediate protective action is required.

---

## 25. State and Monitoring

Operational monitoring should detect conditions that require state transition.

Indicators may include:

- performance;
- uncertainty;
- autonomy;
- human-control status;
- environment;
- security;
- data integrity;
- dependencies;
- mission effectiveness; and
- incident indicators.

Thresholds should be established proportionately to risk.

---

## 26. State Transition Records

Material transitions should be recorded.

The record should include:

- capability;
- previous state;
- new state;
- date/time;
- trigger;
- authority;
- conditions;
- configuration;
- autonomy;
- human authority;
- relevant evidence;
- actions taken; and
- outcome.

---

## 27. Transition Auditability

The record should allow reconstruction of:

**Condition → Transition Decision → Authority → System State → Human Control → Action → Outcome**

This supports accountability, audit and continuous assurance.

---

## 28. Offline and Disconnected Operation

Where central services are unavailable, predefined local transition rules may be used where authorised.

Local procedures should identify:

- valid states;
- permitted transitions;
- autonomy limits;
- human authority;
- protective actions;
- evidence requirements; and
- reconciliation procedures.

Local operation should not create authority beyond the approved governance framework.

---

## 29. Training and Exercises

Personnel should understand:

- operational states;
- transition triggers;
- autonomy implications;
- human-control requirements;
- emergency procedures;
- safe-state procedures;
- suspension;
- restoration; and
- reporting requirements.

Exercises should test transition under realistic degraded and time-constrained conditions.

---

## 30. Governance Review

Transition rules should be reviewed after:

- incidents;
- unexpected state changes;
- failed transitions;
- autonomy events;
- configuration changes;
- environmental changes;
- assurance findings; or
- lessons learned.

The objective is to improve both technical and governance resilience.

---

## 31. Relationship to Continuous Assurance

State management creates a direct operational control loop:

**Monitor → Detect Condition → Assess → Transition → Verify → Monitor → Restore/Restrict/Suspend**

This enables continuous assurance to influence operational authority in a controlled manner.

---

## 32. Golden Thread

Operational state management remains connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Readiness → Deployment → Employment → Monitoring → State Transition → Change/Incident → Revalidation/Reauthorisation**

---

## 33. Governance Questions

Responsible authorities should be able to determine:

1. What operational state is the capability currently in?
2. Who defined that state?
3. What functions are permitted in the state?
4. What functions are prohibited?
5. What autonomy is authorised?
6. What autonomy is currently active?
7. Who holds human authority?
8. What conditions triggered the current state?
9. What are the entry and exit criteria?
10. What happens if a transition fails?
11. What happens if the state is uncertain?
12. What happens when communications are lost?
13. What happens when human supervision is unavailable?
14. What happens when the environment changes?
15. What happens when security or data integrity is compromised?
16. What authority is required to restore normal employment?
17. What evidence supports restoration?
18. Has the transition been recorded?
19. Does the transition require revalidation?
20. Does it require reauthorisation?

---

## 34. Core Rule

> **Every material transition in the operational state of a Defence AI capability shall be defined, bounded, attributable and appropriately verified. State changes affecting mission, autonomy, human control, environment, configuration, security or operational risk shall not create implied authority. Where a transition cannot be safely verified, the capability shall move to an appropriately restricted, human-controlled, safe or suspended state until the conditions for controlled operation are re-established.**
