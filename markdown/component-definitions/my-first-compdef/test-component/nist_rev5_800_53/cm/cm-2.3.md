---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-cm-2.3
      description: Rule for cm-2.3
x-trestle-param-values:
  cm-02.03_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: cm-02.03
---

# cm-2.3 - \[Configuration Management\] Retention of Previous Configurations

## Control Statement

Retain {{ insert: param, cm-02.03_odp }} of previous versions of baseline configurations of the system to support rollback.

## Control Assessment Objective

{{ insert: param, cm-02.03_odp }} of previous baseline configuration version(s) of the system is/are retained to support rollback.

## Control guidance

Retaining previous versions of baseline configurations to support rollback include hardware, software, firmware, configuration files, configuration records, and associated documentation.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cm-2.3 -->

### Rules:

  - rule-cm-2.3

### Implementation Status: planned

______________________________________________________________________
