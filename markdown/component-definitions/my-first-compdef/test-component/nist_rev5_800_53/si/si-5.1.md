---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-si-5.1
      description: Rule for si-5.1
x-trestle-param-values:
  si-05.01_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: si-05.01
---

# si-5.1 - \[System and Information Integrity\] Automated Alerts and Advisories

## Control Statement

Broadcast security alert and advisory information throughout the organization using {{ insert: param, si-05.01_odp }}.

## Control Assessment Objective

{{ insert: param, si-05.01_odp }} are used to broadcast security alert and advisory information throughout the organization.

## Control guidance

The significant number of changes to organizational systems and environments of operation requires the dissemination of security-related information to a variety of organizational entities that have a direct interest in the success of organizational mission and business functions. Based on information provided by security alerts and advisories, changes may be required at one or more of the three levels related to the management of risk, including the governance level, mission and business process level, and the information system level.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: si-5.1 -->

### Rules:

  - rule-si-5.1

### Implementation Status: planned

______________________________________________________________________
