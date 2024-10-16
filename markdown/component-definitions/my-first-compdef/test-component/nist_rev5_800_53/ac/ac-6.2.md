---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ac-6.2
      description: Rule for ac-6.2
x-trestle-param-values:
  ac-06.02_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ac-06.02
---

# ac-6.2 - \[Access Control\] Non-privileged Access for Nonsecurity Functions

## Control Statement

Require that users of system accounts (or roles) with access to {{ insert: param, ac-06.02_odp }} use non-privileged accounts or roles, when accessing nonsecurity functions.

## Control Assessment Objective

users of system accounts (or roles) with access to {{ insert: param, ac-06.02_odp }} are required to use non-privileged accounts or roles when accessing non-security functions.

## Control guidance

Requiring the use of non-privileged accounts when accessing nonsecurity functions limits exposure when operating from within privileged accounts or roles. The inclusion of roles addresses situations where organizations implement access control policies, such as role-based access control, and where a change of role provides the same degree of assurance in the change of access authorizations for the user and the processes acting on behalf of the user as would be provided by a change between a privileged and non-privileged account.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-6.2 -->

### Rules:

  - rule-ac-6.2

### Implementation Status: planned

______________________________________________________________________
