---
x-trestle-comp-def-rules:
  comp-def-test-01-component-01:
    - name: rule-ac-2.1
      description: Rule for ac-2.1
x-trestle-param-values:
  ac-2.1_prm_1:
x-trestle-global:
  profile:
    title: ACME Inc. official controls profile.
    href: trestle://profiles/ACME_custom_profile/profile.json
  sort-id: ac-02.01
---

# ac-2.1 - \[Access Control\] Automated System Account Management

## Control Statement

Support the management of system accounts using {{ insert: param, ac-2.1_prm_1 }}.

## Control guidance

Automated system account management includes using automated mechanisms to create, enable, modify, disable, and remove accounts; notify account managers when an account is created, enabled, modified, disabled, or removed, or when users are terminated or transferred; monitor system account usage; and report atypical system account usage. Automated mechanisms can include internal system functions and email, telephonic, and text messaging notifications.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-2.1 -->

### Rules:

  - rule-ac-2.1

### Implementation Status: planned

______________________________________________________________________
