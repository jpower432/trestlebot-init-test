---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-cm-7.2
      description: Rule for cm-7.2
x-trestle-param-values:
  cm-07.02_odp.01:
  cm-07.02_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: cm-07.02
---

# cm-7.2 - \[Configuration Management\] Prevent Program Execution

## Control Statement

Prevent program execution in accordance with {{ insert: param, cm-07.02_odp.01 }}.

## Control Assessment Objective

program execution is prevented in accordance with {{ insert: param, cm-07.02_odp.01 }}.

## Control guidance

Prevention of program execution addresses organizational policies, rules of behavior, and/or access agreements that restrict software usage and the terms and conditions imposed by the developer or manufacturer, including software licensing and copyrights. Restrictions include prohibiting auto-execute features, restricting roles allowed to approve program execution, permitting or prohibiting specific software programs, or restricting the number of program instances executed at the same time.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cm-7.2 -->

### Rules:

  - rule-cm-7.2

### Implementation Status: planned

______________________________________________________________________
