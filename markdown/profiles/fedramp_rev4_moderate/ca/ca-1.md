---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: ca-01
x-trestle-set-params:
    # This section contains the parameters that are part of this control.
  # Each parameter has properties. Only the profile-values and display-name properties are editable.
  # The other properties are informational.
  #
  # The values property for a parameter represents values inherited from the OSCAL catalog.
  # To override the catalog settings, use bullets under profile-values as shown below:
  #
  #   profile-values:
  #     - value 1
  #     - value 2
  #
  # If the "- <REPLACE_ME>" placeholder appears under profile-values, it is the same as if
  # the profile-values property were left empty.
  #
  # Some parameters may show an aggregates property which lists other parameters. This means
  # the parameter value is made up of the values from the other parameters. For parameters
  # that aggregate, profile-values is not applicable.
  #
  # Property param-value-origin is meant for putting the origin from where that parameter comes from.
  # In order to be changed in the current profile, profile-param-value-origin property will be displayed with
  # the placeholder "<REPLACE_ME>" for you to be replaced. If a parameter already has a param-value-origin
  # coming from an inherited profile, do no change this value, instead use profile-param-value-origin as follows:
  #
  #    param-value-origin: DO NOT REPLACE - this is the original value
  #    profile-param-value-origin: <REPLACE_ME> - replace the new value required HERE
  #
  ca-1_prm_1:
    values:
  ca-1_prm_2:
    profile-values:
    values:
  ca-1_prm_3:
    profile-values:
    values:
sort-id: ca-01
x-trestle-add-props:
  # Add or modify control properties here
  # Properties may be at the control or part level
  # Add control level properties like this:
  #   - name: ac1_new_prop
  #     value: new property value
  #
  # Add properties to a statement part like this, where "b." is the label of the target statement part
  #   - name: ac1_new_prop
  #     value: new property value
  #     smt-part: b.
  #
  - name: CORE
    value: 'true'
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.a.1_obj.1
  - name: method
    value: EXAMINE
    smt-part: ca-1.a.1_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.a.1_obj.2
  - name: method
    value: EXAMINE
    smt-part: ca-1.a.1_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.a.1_obj.3
  - name: method
    value: EXAMINE
    smt-part: ca-1.a.1_obj.3
  - name: method
    value: INTERVIEW
    smt-part: ca-1.a.1_obj.3
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.a.2_obj.1
  - name: method
    value: EXAMINE
    smt-part: ca-1.a.2_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.a.2_obj.2
  - name: method
    value: EXAMINE
    smt-part: ca-1.a.2_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.a.2_obj.3
  - name: method
    value: EXAMINE
    smt-part: ca-1.a.2_obj.3
  - name: method
    value: INTERVIEW
    smt-part: ca-1.a.2_obj.3
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.b.1_obj.1
  - name: method
    value: EXAMINE
    smt-part: ca-1.b.1_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.b.1_obj.2
  - name: method
    value: EXAMINE
    smt-part: ca-1.b.1_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.b.2_obj.1
  - name: method
    value: EXAMINE
    smt-part: ca-1.b.2_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1.b.2_obj.2
  - name: method
    value: EXAMINE
    smt-part: ca-1.b.2_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: a.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1_smt.b.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ca-1_smt.b.2
---

# ca-1 - \[Security Assessment and Authorization\] Security Assessment and Authorization Policy and Procedures

## Control Statement

The organization:

- \[a.\] Develops, documents, and disseminates to {{ insert: param, ca-1_prm_1 }}:

  - \[1.\] A security assessment and authorization policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
  - \[2.\] Procedures to facilitate the implementation of the security assessment and authorization policy and associated security assessment and authorization controls; and

- \[b.\] Reviews and updates the current:

  - \[1.\] Security assessment and authorization policy {{ insert: param, ca-1_prm_2 }}; and
  - \[2.\] Security assessment and authorization procedures {{ insert: param, ca-1_prm_3 }}.

## Control Objective

Determine if the organization:

- \[CA-1(a)\]

  - \[CA-1(a)(1)\]

    - \[CA-1(a)(1)[1]\] develops and documents a security assessment and authorization policy that addresses:

      - \[CA-1(a)(1)[1][a]\] purpose;
      - \[CA-1(a)(1)[1][b]\] scope;
      - \[CA-1(a)(1)[1][c]\] roles;
      - \[CA-1(a)(1)[1][d]\] responsibilities;
      - \[CA-1(a)(1)[1][e]\] management commitment;
      - \[CA-1(a)(1)[1][f]\] coordination among organizational entities;
      - \[CA-1(a)(1)[1][g]\] compliance;

    - \[CA-1(a)(1)[2]\] defines personnel or roles to whom the security assessment and authorization policy is to be disseminated;
    - \[CA-1(a)(1)[3]\] disseminates the security assessment and authorization policy to organization-defined personnel or roles;

  - \[CA-1(a)(2)\]

    - \[CA-1(a)(2)[1]\] develops and documents procedures to facilitate the implementation of the security assessment and authorization policy and associated assessment and authorization controls;
    - \[CA-1(a)(2)[2]\] defines personnel or roles to whom the procedures are to be disseminated;
    - \[CA-1(a)(2)[3]\] disseminates the procedures to organization-defined personnel or roles;

- \[CA-1(b)\]

  - \[CA-1(b)(1)\]

    - \[CA-1(b)(1)[1]\] defines the frequency to review and update the current security assessment and authorization policy;
    - \[CA-1(b)(1)[2]\] reviews and updates the current security assessment and authorization policy with the organization-defined frequency;

  - \[CA-1(b)(2)\]

    - \[CA-1(b)(2)[1]\] defines the frequency to review and update the current security assessment and authorization procedures; and
    - \[CA-1(b)(2)[2]\] reviews and updates the current security assessment and authorization procedures with the organization-defined frequency.

## Control guidance

This control addresses the establishment of policy and procedures for the effective implementation of selected security controls and control enhancements in the CA family. Policy and procedures reflect applicable federal laws, Executive Orders, directives, regulations, policies, standards, and guidance. Security program policies and procedures at the organization level may make the need for system-specific policies and procedures unnecessary. The policy can be included as part of the general information security policy for organizations or conversely, can be represented by multiple policies reflecting the complex nature of certain organizations. The procedures can be established for the security program in general and for particular information systems, if needed. The organizational risk management strategy is a key factor in establishing policy and procedures.

# Editable Content

<!-- Make additions and edits below -->
<!-- The above represents the contents of the control as received by the profile, prior to additions. -->
<!-- If the profile makes additions to the control, they will appear below. -->
<!-- The above markdown may not be edited but you may edit the content below, and/or introduce new additions to be made by the profile. -->
<!-- If there is a yaml header at the top, parameter values may be edited. Use --set-parameters to incorporate the changes during assembly. -->
<!-- The content here will then replace what is in the profile for this control, after running profile-assemble. -->
<!-- The added parts in the profile for this control are below.  You may edit them and/or add new ones. -->
<!-- Each addition must have a heading either of the form ## Control my_addition_name -->
<!-- or ## Part a. (where the a. refers to one of the control statement labels.) -->
<!-- "## Control" parts are new parts added after the statement part. -->
<!-- "## Part" parts are new parts added into the top-level statement part with that label. -->
<!-- Subparts may be added with nested hash levels of the form ### My Subpart Name -->
<!-- underneath the parent ## Control or ## Part being added -->
<!-- See https://oscal-compass.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->
