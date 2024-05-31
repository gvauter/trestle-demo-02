---
x-trestle-comp-def-rules:
  comp-def-test-01-component-01:
    - name: rule-sc-1
      description: Rule for sc-1
x-trestle-param-values:
  sc-1_prm_1:
    - assistants
  sc-1_prm_2:
    - hourly
  sc-1_prm_3:
    - bi-monthly
  sc-1_prm_4:
  sc-1_prm_5:
  sc-1_prm_6:
  sc-1_prm_7:
x-trestle-global:
  profile:
    title: ACME Inc. official controls profile.
    href: trestle://profiles/ACME_custom_profile/profile.json
  sort-id: sc-01
---

# sc-1 - \[System and Communications Protection\] Policy and Procedures

## Control Statement

- \[a.\] Develop, document, and disseminate to {{ insert: param, sc-1_prm_1 }}:

  - \[1.\] {{ insert: param, sc-1_prm_2 }} system and communications protection policy that:

    - \[(a)\] Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    - \[(b)\] Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and

  - \[2.\] Procedures to facilitate the implementation of the system and communications protection policy and the associated system and communications protection controls;

- \[b.\] Designate an {{ insert: param, sc-1_prm_3 }} to manage the development, documentation, and dissemination of the system and communications protection policy and procedures; and

- \[c.\] Review and update the current system and communications protection:

  - \[1.\] Policy {{ insert: param, sc-1_prm_4 }} and following {{ insert: param, sc-1_prm_5 }}; and
  - \[2.\] Procedures {{ insert: param, sc-1_prm_6 }} and following {{ insert: param, sc-1_prm_7 }}.

## Control guidance

System and communications protection policy and procedures address the controls in the SC family that are implemented within systems and organizations. The risk management strategy is an important factor in establishing such policies and procedures. Policies and procedures contribute to security and privacy assurance. Therefore, it is important that security and privacy programs collaborate on the development of system and communications protection policy and procedures. Security and privacy program policies and procedures at the organization level are preferable, in general, and may obviate the need for mission- or system-specific policies and procedures. The policy can be included as part of the general security and privacy policy or be represented by multiple policies that reflect the complex nature of organizations. Procedures can be established for security and privacy programs, for mission or business processes, and for systems, if needed. Procedures describe how the policies or controls are implemented and can be directed at the individual or role that is the object of the procedure. Procedures can be documented in system security and privacy plans or in one or more separate documents. Events that may precipitate an update to system and communications protection policy and procedures include assessment or audit findings, security incidents or breaches, or changes in applicable laws, executive orders, directives, regulations, policies, standards, and guidelines. Simply restating controls does not constitute an organizational policy or procedure.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sc-1 -->

### Rules:

  - rule-sc-1

### Implementation Status: planned

______________________________________________________________________
