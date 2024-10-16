---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ca-5
      description: Rule for ca-5
x-trestle-param-values:
  ca-05_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ca-05
---

# ca-5 - \[Assessment, Authorization, and Monitoring\] Plan of Action and Milestones

## Control Statement

- \[a.\] Develop a plan of action and milestones for the system to document the planned remediation actions of the organization to correct weaknesses or deficiencies noted during the assessment of the controls and to reduce or eliminate known vulnerabilities in the system; and

- \[b.\] Update existing plan of action and milestones {{ insert: param, ca-05_odp }} based on the findings from control assessments, independent audits or reviews, and continuous monitoring activities.

## Control Assessment Objective

- \[CA-05a.\] a plan of action and milestones for the system is developed to document the planned remediation actions of the organization to correct weaknesses or deficiencies noted during the assessment of the controls and to reduce or eliminate known vulnerabilities in the system;

- \[CA-05b.\] existing plan of action and milestones are updated {{ insert: param, ca-05_odp }} based on the findings from control assessments, independent audits or reviews, and continuous monitoring activities.

## Control guidance

Plans of action and milestones are useful for any type of organization to track planned remedial actions. Plans of action and milestones are required in authorization packages and subject to federal reporting requirements established by OMB.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ca-5 -->

### Rules:

  - rule-ca-5

### Implementation Status: planned

______________________________________________________________________
