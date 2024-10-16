---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ir-2.2
      description: Rule for ir-2.2
x-trestle-param-values:
  ir-02.02_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ir-02.02
---

# ir-2.2 - \[Incident Response\] Automated Training Environments

## Control Statement

Provide an incident response training environment using {{ insert: param, ir-02.02_odp }}.

## Control Assessment Objective

an incident response training environment is provided using {{ insert: param, ir-02.02_odp }}.

## Control guidance

Automated mechanisms can provide a more thorough and realistic incident response training environment. This can be accomplished, for example, by providing more complete coverage of incident response issues, selecting more realistic training scenarios and environments, and stressing the response capability.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ir-2.2 -->

### Rules:

  - rule-ir-2.2

### Implementation Status: planned

______________________________________________________________________
