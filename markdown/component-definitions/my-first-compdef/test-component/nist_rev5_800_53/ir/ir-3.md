---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ir-3
      description: Rule for ir-3
x-trestle-param-values:
  ir-03_odp.01:
  ir-03_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ir-03
---

# ir-3 - \[Incident Response\] Incident Response Testing

## Control Statement

Test the effectiveness of the incident response capability for the system {{ insert: param, ir-03_odp.01 }} using the following tests: {{ insert: param, ir-03_odp.02 }}.

## Control Assessment Objective

the effectiveness of the incident response capability for the system is tested {{ insert: param, ir-03_odp.01 }} using {{ insert: param, ir-03_odp.02 }}.

## Control guidance

Organizations test incident response capabilities to determine their effectiveness and identify potential weaknesses or deficiencies. Incident response testing includes the use of checklists, walk-through or tabletop exercises, and simulations (parallel or full interrupt). Incident response testing can include a determination of the effects on organizational operations and assets and individuals due to incident response. The use of qualitative and quantitative data aids in determining the effectiveness of incident response processes.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ir-3 -->

### Rules:

  - rule-ir-3

### Implementation Status: planned

______________________________________________________________________
