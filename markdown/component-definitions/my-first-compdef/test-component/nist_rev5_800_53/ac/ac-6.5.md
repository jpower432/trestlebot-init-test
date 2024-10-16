---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ac-6.5
      description: Rule for ac-6.5
x-trestle-param-values:
  ac-06.05_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ac-06.05
---

# ac-6.5 - \[Access Control\] Privileged Accounts

## Control Statement

Restrict privileged accounts on the system to {{ insert: param, ac-06.05_odp }}.

## Control Assessment Objective

privileged accounts on the system are restricted to {{ insert: param, ac-06.05_odp }}.

## Control guidance

Privileged accounts, including super user accounts, are typically described as system administrator for various types of commercial off-the-shelf operating systems. Restricting privileged accounts to specific personnel or roles prevents day-to-day users from accessing privileged information or privileged functions. Organizations may differentiate in the application of restricting privileged accounts between allowed privileges for local accounts and for domain accounts provided that they retain the ability to control system configurations for key parameters and as otherwise necessary to sufficiently mitigate risk.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-6.5 -->

### Rules:

  - rule-ac-6.5

### Implementation Status: planned

______________________________________________________________________
