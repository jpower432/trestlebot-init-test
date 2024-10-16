---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-au-9.2
      description: Rule for au-9.2
x-trestle-param-values:
  au-09.02_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: au-09.02
---

# au-9.2 - \[Audit and Accountability\] Store on Separate Physical Systems or Components

## Control Statement

Store audit records {{ insert: param, au-09.02_odp }} in a repository that is part of a physically different system or system component than the system or component being audited.

## Control Assessment Objective

audit records are stored {{ insert: param, au-09.02_odp }} in a repository that is part of a physically different system or system component than the system or component being audited.

## Control guidance

Storing audit records in a repository separate from the audited system or system component helps to ensure that a compromise of the system being audited does not also result in a compromise of the audit records. Storing audit records on separate physical systems or components also preserves the confidentiality and integrity of audit records and facilitates the management of audit records as an organization-wide activity. Storing audit records on separate systems or components applies to initial generation as well as backup or long-term storage of audit records.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: au-9.2 -->

### Rules:

  - rule-au-9.2

### Implementation Status: planned

______________________________________________________________________
