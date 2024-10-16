---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-sc-8.1
      description: Rule for sc-8.1
x-trestle-param-values:
  sc-08.01_odp:
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: sc-08.01
---

# sc-8.1 - \[System and Communications Protection\] Cryptographic Protection

## Control Statement

Implement cryptographic mechanisms to {{ insert: param, sc-08.01_odp }} during transmission.

## Control Assessment Objective

cryptographic mechanisms are implemented to {{ insert: param, sc-08.01_odp }} during transmission.

## Control guidance

Encryption protects information from unauthorized disclosure and modification during transmission. Cryptographic mechanisms that protect the confidentiality and integrity of information during transmission include TLS and IPSec. Cryptographic mechanisms used to protect information integrity include cryptographic hash functions that have applications in digital signatures, checksums, and message authentication codes.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sc-8.1 -->

### Rules:

  - rule-sc-8.1

### Implementation Status: planned

______________________________________________________________________
