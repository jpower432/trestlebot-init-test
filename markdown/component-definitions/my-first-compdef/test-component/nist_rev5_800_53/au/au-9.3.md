---
x-trestle-comp-def-rules:
  test-component:
    - name: rule-au-9.3
      description: Rule for au-9.3
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
    href: trestle://profiles/nist_rev5_800_53/profile.json
  sort-id: au-09.03
---

# au-9.3 - \[Audit and Accountability\] Cryptographic Protection

## Control Statement

Implement cryptographic mechanisms to protect the integrity of audit information and audit tools.

## Control Assessment Objective

cryptographic mechanisms to protect the integrity of audit information and audit tools are implemented.

## Control guidance

Cryptographic mechanisms used for protecting the integrity of audit information include signed hash functions using asymmetric cryptography. This enables the distribution of the public key to verify the hash information while maintaining the confidentiality of the secret key used to generate the hash.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: au-9.3 -->

### Rules:

  - rule-au-9.3

### Implementation Status: planned

______________________________________________________________________
