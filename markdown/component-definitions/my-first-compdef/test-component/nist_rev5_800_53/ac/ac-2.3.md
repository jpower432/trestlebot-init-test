---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-ac-2.3
      description: Rule for ac-2.3
x-trestle-param-values:
  ac-02.03_odp.01:
  ac-02.03_odp.02:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: ac-02.03
---

# ac-2.3 - \[Access Control\] Disable Accounts

## Control Statement

Disable accounts within {{ insert: param, ac-02.03_odp.01 }} when the accounts:

- \[(a)\] Have expired;

- \[(b)\] Are no longer associated with a user or individual;

- \[(c)\] Are in violation of organizational policy; or

- \[(d)\] Have been inactive for {{ insert: param, ac-02.03_odp.02 }}.

## Control Assessment Objective

- \[AC-02(03)(a)\] accounts are disabled within {{ insert: param, ac-02.03_odp.01 }} when the accounts have expired;

- \[AC-02(03)(b)\] accounts are disabled within {{ insert: param, ac-02.03_odp.01 }} when the accounts are no longer associated with a user or individual;

- \[AC-02(03)(c)\] accounts are disabled within {{ insert: param, ac-02.03_odp.01 }} when the accounts are in violation of organizational policy;

- \[AC-02(03)(d)\] accounts are disabled within {{ insert: param, ac-02.03_odp.01 }} when the accounts have been inactive for {{ insert: param, ac-02.03_odp.02 }}.

## Control guidance

Disabling expired, inactive, or otherwise anomalous accounts supports the concepts of least privilege and least functionality which reduce the attack surface of the system.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-2.3 -->

### Rules:

  - rule-ac-2.3

### Implementation Status: planned

______________________________________________________________________
