---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: ac-02.12
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
  ac-2.12_prm_1:
    values:
  ac-2.12_prm_2:
    values:
sort-id: ac-02.12
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
    smt-part: ac-2.12
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-2.12.a_obj.1
  - name: method
    value: EXAMINE
    smt-part: ac-2.12.a_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-2.12.a_obj.2
  - name: method
    value: INTERVIEW
    smt-part: ac-2.12.a_obj.2
  - name: method
    value: TEST
    smt-part: ac-2.12.a_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-2.12.b_obj.1
  - name: method
    value: EXAMINE
    smt-part: ac-2.12.b_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ac-2.12.b_obj.2
  - name: method
    value: INTERVIEW
    smt-part: ac-2.12.b_obj.2
  - name: method
    value: TEST
    smt-part: ac-2.12.b_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: (a)
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: (b)
---

# ac-2.12 - \[Access Control\] Account Monitoring / Atypical Usage

## Control Statement

The organization:

- \[(a)\] Monitors information system accounts for {{ insert: param, ac-2.12_prm_1 }}; and

- \[(b)\] Reports atypical usage of information system accounts to {{ insert: param, ac-2.12_prm_2 }}.

## Control Objective

Determine if the organization:

- \[AC-2(12)(a)\]

  - \[AC-2(12)(a)[1]\] defines atypical usage to be monitored for information system accounts;
  - \[AC-2(12)(a)[2]\] monitors information system accounts for organization-defined atypical usage;

- \[AC-2(12)(b)\]

  - \[AC-2(12)(b)[1]\] defines personnel or roles to whom atypical usage of information system accounts are to be reported; and
  - \[AC-2(12)(b)[2]\] reports atypical usage of information system accounts to organization-defined personnel or roles.

## Control guidance

Atypical usage includes, for example, accessing information systems at certain times of the day and from locations that are not consistent with the normal usage patterns of individuals working in organizations.

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

## Control item

### guidance

Required for privileged accounts.

### guidance

Required for privileged accounts.
