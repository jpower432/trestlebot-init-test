---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ir-5.1
      description: Rule for ir-5.1
x-trestle-param-values:
  ir-5.1_prm_1:
  ir-05.01_odp.01:
  ir-05.01_odp.02:
  ir-05.01_odp.03:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ir-05.01
---

# ir-5.1 - \[Incident Response\] Automated Tracking, Data Collection, and Analysis

## Control Statement

Track incidents and collect and analyze incident information using {{ insert: param, ir-5.1_prm_1 }}.

## Control Assessment Objective

- \[IR-05(01)[01]\] incidents are tracked using {{ insert: param, ir-05.01_odp.01 }};

- \[IR-05(01)[02]\] incident information is collected using {{ insert: param, ir-05.01_odp.02 }};

- \[IR-05(01)[03]\] incident information is analyzed using {{ insert: param, ir-05.01_odp.03 }}.

## Control guidance

Automated mechanisms for tracking incidents and collecting and analyzing incident information include Computer Incident Response Centers or other electronic databases of incidents and network monitoring devices.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ir-5.1 -->

### Rules:

  - rule-ir-5.1

### Implementation Status: planned

______________________________________________________________________
