---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-si-7.7
      description: Rule for si-7.7
x-trestle-param-values:
  si-07.07_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: si-07.07
---

# si-7.7 - \[System and Information Integrity\] Integration of Detection and Response

## Control Statement

Incorporate the detection of the following unauthorized changes into the organizational incident response capability: {{ insert: param, si-07.07_odp }}.

## Control Assessment Objective

the detection of {{ insert: param, si-07.07_odp }} are incorporated into the organizational incident response capability.

## Control guidance

Integrating detection and response helps to ensure that detected events are tracked, monitored, corrected, and available for historical purposes. Maintaining historical records is important for being able to identify and discern adversary actions over an extended time period and for possible legal actions. Security-relevant changes include unauthorized changes to established configuration settings or the unauthorized elevation of system privileges.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: si-7.7 -->

### Rules:

  - rule-si-7.7

### Implementation Status: planned

______________________________________________________________________
