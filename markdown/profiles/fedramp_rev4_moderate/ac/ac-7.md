---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: ac-07
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
  ac-7_prm_1:
    profile-values:
    values:
  ac-7_prm_2:
    profile-values:
    values:
  ac-7_prm_3:
    values:
  ac-7_prm_4:
    profile-values:
    values:
  ac-7_prm_5:
    values:
sort-id: ac-07
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
    smt-part: ac-7
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-7.a_obj.1
  - name: method
    value: EXAMINE
    smt-part: ac-7.a_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-7.a_obj.2
  - name: method
    value: EXAMINE
    smt-part: ac-7.a_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-7.a_obj.3
  - name: method
    value: INTERVIEW
    smt-part: ac-7.a_obj.3
  - name: method
    value: TEST
    smt-part: ac-7.a_obj.3
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-7.b_obj.1
  - name: method
    value: EXAMINE
    smt-part: ac-7.b_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-7.b_obj.2
  - name: method
    value: INTERVIEW
    smt-part: ac-7.b_obj.2
  - name: method
    value: TEST
    smt-part: ac-7.b_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: a.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: b.
---

# ac-7 - \[Access Control\] Unsuccessful Logon Attempts

## Control Statement

The information system:

- \[a.\] Enforces a limit of {{ insert: param, ac-7_prm_1 }} consecutive invalid logon attempts by a user during a {{ insert: param, ac-7_prm_2 }}; and

- \[b.\] Automatically {{ insert: param, ac-7_prm_3 }} when the maximum number of unsuccessful attempts is exceeded.

## Control Objective

Determine if:

- \[AC-7(a)\]

  - \[AC-7(a)[1]\] the organization defines the number of consecutive invalid logon attempts allowed to the information system by a user during an organization-defined time period;
  - \[AC-7(a)[2]\] the organization defines the time period allowed by a user of the information system for an organization-defined number of consecutive invalid logon attempts;
  - \[AC-7(a)[3]\] the information system enforces a limit of organization-defined number of consecutive invalid logon attempts by a user during an organization-defined time period;

- \[AC-7(b)\]

  - \[AC-7(b)[1]\] the organization defines account/node lockout time period or logon delay algorithm to be automatically enforced by the information system when the maximum number of unsuccessful logon attempts is exceeded;
  - \[AC-7(b)[2]\] the information system, when the maximum number of unsuccessful logon attempts is exceeded, automatically:

    - \[AC-7(b)[2][a]\] locks the account/node for the organization-defined time period;
    - \[AC-7(b)[2][b]\] locks the account/node until released by an administrator; or
    - \[AC-7(b)[2][c]\] delays next logon prompt according to the organization-defined delay algorithm.

## Control guidance

This control applies regardless of whether the logon occurs via a local or network connection. Due to the potential for denial of service, automatic lockouts initiated by information systems are usually temporary and automatically release after a predetermined time period established by organizations. If a delay algorithm is selected, organizations may choose to employ different algorithms for different information system components based on the capabilities of those components. Responses to unsuccessful logon attempts may be implemented at both the operating system and the application levels.

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
