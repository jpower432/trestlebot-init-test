---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-si-8
      description: Rule for si-8
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: si-08
---

# si-8 - \[System and Information Integrity\] Spam Protection

## Control Statement

- \[a.\] Employ spam protection mechanisms at system entry and exit points to detect and act on unsolicited messages; and

- \[b.\] Update spam protection mechanisms when new releases are available in accordance with organizational configuration management policy and procedures.

## Control Assessment Objective

- \[SI-08a.\]

  - \[SI-08a.[01]\] spam protection mechanisms are employed at system entry points to detect unsolicited messages;
  - \[SI-08a.[02]\] spam protection mechanisms are employed at system exit points to detect unsolicited messages;
  - \[SI-08a.[03]\] spam protection mechanisms are employed at system entry points to act on unsolicited messages;
  - \[SI-08a.[04]\] spam protection mechanisms are employed at system exit points to act on unsolicited messages;

- \[SI-08b.\] spam protection mechanisms are updated when new releases are available in accordance with organizational configuration management policies and procedures.

## Control guidance

System entry and exit points include firewalls, remote-access servers, electronic mail servers, web servers, proxy servers, workstations, notebook computers, and mobile devices. Spam can be transported by different means, including email, email attachments, and web accesses. Spam protection mechanisms include signature definitions.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: si-8 -->

### Rules:

  - rule-si-8

### Implementation Status: planned

______________________________________________________________________
