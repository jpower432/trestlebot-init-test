---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ir-4.1
      description: Rule for ir-4.1
x-trestle-param-values:
  ir-04.01_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ir-04.01
---

# ir-4.1 - \[Incident Response\] Automated Incident Handling Processes

## Control Statement

Support the incident handling process using {{ insert: param, ir-04.01_odp }}.

## Control Assessment Objective

the incident handling process is supported using {{ insert: param, ir-04.01_odp }}.

## Control guidance

Automated mechanisms that support incident handling processes include online incident management systems and tools that support the collection of live response data, full network packet capture, and forensic analysis.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ir-4.1 -->

### Rules:

  - rule-ir-4.1

### Implementation Status: planned

______________________________________________________________________
