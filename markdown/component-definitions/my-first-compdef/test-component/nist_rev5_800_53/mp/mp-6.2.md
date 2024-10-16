---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-mp-6.2
      description: Rule for mp-6.2
x-trestle-param-values:
  mp-6.2_prm_1:
  mp-06.02_odp.01:
  mp-06.02_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: mp-06.02
---

# mp-6.2 - \[Media Protection\] Equipment Testing

## Control Statement

Test sanitization equipment and procedures {{ insert: param, mp-6.2_prm_1 }} to ensure that the intended sanitization is being achieved.

## Control Assessment Objective

- \[MP-06(02)[01]\] sanitization equipment is tested {{ insert: param, mp-06.02_odp.01 }} to ensure that the intended sanitization is being achieved;

- \[MP-06(02)[02]\] sanitization procedures are tested {{ insert: param, mp-06.02_odp.02 }} to ensure that the intended sanitization is being achieved.

## Control guidance

Testing of sanitization equipment and procedures may be conducted by qualified and authorized external entities, including federal agencies or external service providers.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: mp-6.2 -->

### Rules:

  - rule-mp-6.2

### Implementation Status: planned

______________________________________________________________________
