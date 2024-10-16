---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-pe-4
      description: Rule for pe-4
x-trestle-param-values:
  pe-04_odp.01:
  pe-04_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: pe-04
---

# pe-4 - \[Physical and Environmental Protection\] Access Control for Transmission

## Control Statement

Control physical access to {{ insert: param, pe-04_odp.01 }} within organizational facilities using {{ insert: param, pe-04_odp.02 }}.

## Control Assessment Objective

physical access to {{ insert: param, pe-04_odp.01 }} within organizational facilities is controlled using {{ insert: param, pe-04_odp.02 }}.

## Control guidance

Security controls applied to system distribution and transmission lines prevent accidental damage, disruption, and physical tampering. Such controls may also be necessary to prevent eavesdropping or modification of unencrypted transmissions. Security controls used to control physical access to system distribution and transmission lines include disconnected or locked spare jacks, locked wiring closets, protection of cabling by conduit or cable trays, and wiretapping sensors.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pe-4 -->

### Rules:

  - rule-pe-4

### Implementation Status: planned

______________________________________________________________________
