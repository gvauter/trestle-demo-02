---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: ia-02.11
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
  ia-2.11_prm_1:
    profile-values:
    values:
sort-id: ia-02.11
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
    smt-part: ia-2.11_obj.1
  - name: method
    value: INTERVIEW
    smt-part: ia-2.11_obj.1
  - name: method
    value: TEST
    smt-part: ia-2.11_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ia-2.11_obj.2
  - name: method
    value: INTERVIEW
    smt-part: ia-2.11_obj.2
  - name: method
    value: TEST
    smt-part: ia-2.11_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ia-2.11_obj.3
  - name: method
    value: EXAMINE
    smt-part: ia-2.11_obj.3
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ia-2.11_obj.4
  - name: method
    value: EXAMINE
    smt-part: ia-2.11_obj.4
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ia-2.11_obj.5
  - name: method
    value: INTERVIEW
    smt-part: ia-2.11_obj.5
  - name: method
    value: TEST
    smt-part: ia-2.11_obj.5
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ia-2.11_obj.6
  - name: method
    value: INTERVIEW
    smt-part: ia-2.11_obj.6
  - name: method
    value: TEST
    smt-part: ia-2.11_obj.6
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: ia-2.11_smt
---

# ia-2.11 - \[Identification and Authentication\] Remote Access - Separate Device

## Control Statement

The information system implements multifactor authentication for remote access to privileged and non-privileged accounts such that one of the factors is provided by a device separate from the system gaining access and the device meets {{ insert: param, ia-2.11_prm_1 }}.

## Control Objective

Determine if:

- \[IA-2(11)[1]\] the information system implements multifactor authentication for remote access to privileged accounts such that one of the factors is provided by a device separate from the system gaining access;

- \[IA-2(11)[2]\] the information system implements multifactor authentication for remote access to non-privileged accounts such that one of the factors is provided by a device separate from the system gaining access;

- \[IA-2(11)[3]\] the organization defines strength of mechanism requirements to be enforced by a device separate from the system gaining remote access to privileged accounts;

- \[IA-2(11)[4]\] the organization defines strength of mechanism requirements to be enforced by a device separate from the system gaining remote access to non-privileged accounts;

- \[IA-2(11)[5]\] the information system implements multifactor authentication for remote access to privileged accounts such that a device, separate from the system gaining access, meets organization-defined strength of mechanism requirements; and

- \[IA-2(11)[6]\] the information system implements multifactor authentication for remote access to non-privileged accounts such that a device, separate from the system gaining access, meets organization-defined strength of mechanism requirements.

## Control guidance

For remote access to privileged/non-privileged accounts, the purpose of requiring a device that is separate from the information system gaining access for one of the factors during multifactor authentication is to reduce the likelihood of compromising authentication credentials stored on the system. For example, adversaries deploying malicious code on organizational information systems can potentially compromise such credentials resident on the system and subsequently impersonate authorized users.

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

PIV=separate device. Please refer to NIST SP 800-157 Guidelines for Derived Personal Identity Verification (PIV) Credentials.
