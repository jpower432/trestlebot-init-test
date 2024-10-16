---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-si-4.10
      description: Rule for si-4.10
x-trestle-param-values:
  si-04.10_odp.01:
  si-04.10_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: si-04.10
---

# si-4.10 - \[System and Information Integrity\] Visibility of Encrypted Communications

## Control Statement

Make provisions so that {{ insert: param, si-04.10_odp.01 }} is visible to {{ insert: param, si-04.10_odp.02 }}.

## Control Assessment Objective

provisions are made so that {{ insert: param, si-04.10_odp.01 }} is visible to {{ insert: param, si-04.10_odp.02 }}.

## Control guidance

Organizations balance the need to encrypt communications traffic to protect data confidentiality with the need to maintain visibility into such traffic from a monitoring perspective. Organizations determine whether the visibility requirement applies to internal encrypted traffic, encrypted traffic intended for external destinations, or a subset of the traffic types.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: si-4.10 -->

### Rules:

  - rule-si-4.10

### Implementation Status: planned

______________________________________________________________________
