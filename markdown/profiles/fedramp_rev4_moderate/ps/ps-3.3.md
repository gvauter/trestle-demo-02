---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: ps-03.03
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
  ps-3.3_prm_1:
    profile-values:
    values:
sort-id: ps-03.03
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
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ps-3.3.a_obj
  - name: method
    value: INTERVIEW
    smt-part: ps-3.3.a_obj
  - name: method
    value: TEST
    smt-part: ps-3.3.a_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ps-3.3.b_obj.1
  - name: method
    value: EXAMINE
    smt-part: ps-3.3.b_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ps-3.3.b_obj.2
  - name: method
    value: INTERVIEW
    smt-part: ps-3.3.b_obj.2
  - name: method
    value: TEST
    smt-part: ps-3.3.b_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: (a)
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: (b)
---

# ps-3.3 - \[Personnel Security\] Information with Special Protection Measures

## Control Statement

The organization ensures that individuals accessing an information system processing, storing, or transmitting information requiring special protection:

- \[(a)\] Have valid access authorizations that are demonstrated by assigned official government duties; and

- \[(b)\] Satisfy {{ insert: param, ps-3.3_prm_1 }}.

## Control Objective

Determine if the organization:

- \[PS-3(3)(a)\] ensures that individuals accessing an information system processing, storing, or transmitting information requiring special protection have valid access authorizations that are demonstrated by assigned official government duties;

- \[PS-3(3)(b)\]

  - \[PS-3(3)(b)[1]\] defines additional personnel screening criteria to be satisfied for individuals accessing an information system processing, storing, or transmitting information requiring special protection; and
  - \[PS-3(3)(b)[2]\] ensures that individuals accessing an information system processing, storing, or transmitting information requiring special protection satisfy organization-defined additional personnel screening criteria.

## Control guidance

Organizational information requiring special protection includes, for example, Controlled Unclassified Information (CUI) and Sources and Methods Information (SAMI). Personnel security criteria include, for example, position sensitivity background screening requirements.

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
