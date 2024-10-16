---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-cp-4
      description: Rule for cp-4
x-trestle-param-values:
  cp-4_prm_2:
  cp-04_odp.01:
  cp-04_odp.02:
  cp-04_odp.03:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: cp-04
---

# cp-4 - \[Contingency Planning\] Contingency Plan Testing

## Control Statement

- \[a.\] Test the contingency plan for the system {{ insert: param, cp-04_odp.01 }} using the following tests to determine the effectiveness of the plan and the readiness to execute the plan: {{ insert: param, cp-4_prm_2 }}.

- \[b.\] Review the contingency plan test results; and

- \[c.\] Initiate corrective actions, if needed.

## Control Assessment Objective

- \[CP-04a.\]

  - \[CP-04a.[01]\] the contingency plan for the system is tested {{ insert: param, cp-04_odp.01 }};
  - \[CP-04a.[02]\] {{ insert: param, cp-04_odp.02 }} are used to determine the effectiveness of the plan;
  - \[CP-04a.[03]\] {{ insert: param, cp-04_odp.03 }} are used to determine the readiness to execute the plan;

- \[CP-04b.\] the contingency plan test results are reviewed;

- \[CP-04c.\] corrective actions are initiated, if needed.

## Control guidance

Methods for testing contingency plans to determine the effectiveness of the plans and identify potential weaknesses include checklists, walk-through and tabletop exercises, simulations (parallel or full interrupt), and comprehensive exercises. Organizations conduct testing based on the requirements in contingency plans and include a determination of the effects on organizational operations, assets, and individuals due to contingency operations. Organizations have flexibility and discretion in the breadth, depth, and timelines of corrective actions.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cp-4 -->

### Rules:

  - rule-cp-4

### Implementation Status: planned

______________________________________________________________________
