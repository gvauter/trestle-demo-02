---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: si-07.01
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
  si-7.1_prm_1:
    values:
  si-7.1_prm_2:
    values:
  si-7.1_prm_3:
    profile-values:
    values:
  si-7.1_prm_4:
    profile-values:
    values:
sort-id: si-07.01
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
    smt-part: si-7.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-7.1_obj.1
  - name: method
    value: EXAMINE
    smt-part: si-7.1_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-7.1_obj.2
  - name: method
    value: EXAMINE
    smt-part: si-7.1_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-7.1_obj.3
  - name: method
    value: EXAMINE
    smt-part: si-7.1_obj.3
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-7.1_obj.4
  - name: method
    value: INTERVIEW
    smt-part: si-7.1_obj.4
  - name: method
    value: TEST
    smt-part: si-7.1_obj.4
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-7.1_smt
---

# si-7.1 - \[System and Information Integrity\] Integrity Checks

## Control Statement

The information system performs an integrity check of {{ insert: param, si-7.1_prm_1 }} {{ insert: param, si-7.1_prm_2 }}.

## Control Objective

Determine if:

- \[SI-7(1)[1]\] the organization defines:

  - \[SI-7(1)[1][a]\] software requiring integrity checks to be performed;
  - \[SI-7(1)[1][b]\] firmware requiring integrity checks to be performed;
  - \[SI-7(1)[1][c]\] information requiring integrity checks to be performed;

- \[SI-7(1)[2]\] the organization defines transitional states or security-relevant events requiring integrity checks of organization-defined:

  - \[SI-7(1)[2][a]\] software;
  - \[SI-7(1)[2][b]\] firmware;
  - \[SI-7(1)[2][c]\] information;

- \[SI-7(1)[3]\] the organization defines a frequency with which to perform an integrity check of organization-defined:

  - \[SI-7(1)[3][a]\] software;
  - \[SI-7(1)[3][b]\] firmware;
  - \[SI-7(1)[3][c]\] information;

- \[SI-7(1)[4]\] the information system performs an integrity check of organization-defined software, firmware, and information one or more of the following:

  - \[SI-7(1)[4][a]\] at startup;
  - \[SI-7(1)[4][b]\] at organization-defined transitional states or security-relevant events; and/or
  - \[SI-7(1)[4][c]\] with the organization-defined frequency.

## Control guidance

Security-relevant events include, for example, the identification of a new threat to which organizational information systems are susceptible, and the installation of new hardware, software, or firmware. Transitional states include, for example, system startup, restart, shutdown, and abort.

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
