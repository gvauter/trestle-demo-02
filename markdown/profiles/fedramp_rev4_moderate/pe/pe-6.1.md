---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: pe-06.01
sort-id: pe-06.01
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
    smt-part: pe-6.1_obj
  - name: method
    value: EXAMINE
    smt-part: pe-6.1_obj
  - name: method
    value: INTERVIEW
    smt-part: pe-6.1_obj
  - name: method
    value: TEST
    smt-part: pe-6.1_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: pe-6.1_smt
---

# pe-6.1 - \[Physical and Environmental Protection\] Intrusion Alarms / Surveillance Equipment

## Control Statement

The organization monitors physical intrusion alarms and surveillance equipment.

## Control Objective

Determine if the organization monitors physical intrusion alarms and surveillance equipment.

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
