---
x-trestle-global:
  profile:
    title: FedRAMP Rev 4 Moderate Baseline
  sort-id: si-04
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
  si-4_prm_1:
    values:
  si-4_prm_2:
    values:
  si-4_prm_3:
    values:
  si-4_prm_4:
    values:
  si-4_prm_5:
    values:
  si-4_prm_6:
    values:
sort-id: si-04
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
    smt-part: si-4
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.a.1_obj.1
  - name: method
    value: EXAMINE
    smt-part: si-4.a.1_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.a.1_obj.2
  - name: method
    value: INTERVIEW
    smt-part: si-4.a.1_obj.2
  - name: method
    value: TEST
    smt-part: si-4.a.1_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.a.2_obj
  - name: method
    value: INTERVIEW
    smt-part: si-4.a.2_obj
  - name: method
    value: TEST
    smt-part: si-4.a.2_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.b.1_obj
  - name: method
    value: EXAMINE
    smt-part: si-4.b.1_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.b.2_obj
  - name: method
    value: INTERVIEW
    smt-part: si-4.b.2_obj
  - name: method
    value: TEST
    smt-part: si-4.b.2_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.c_obj
  - name: method
    value: INTERVIEW
    smt-part: si-4.c_obj
  - name: method
    value: TEST
    smt-part: si-4.c_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.d_obj
  - name: method
    value: INTERVIEW
    smt-part: si-4.d_obj
  - name: method
    value: TEST
    smt-part: si-4.d_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.e_obj
  - name: method
    value: INTERVIEW
    smt-part: si-4.e_obj
  - name: method
    value: TEST
    smt-part: si-4.e_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.f_obj
  - name: method
    value: EXAMINE
    smt-part: si-4.f_obj
  - name: method
    value: INTERVIEW
    smt-part: si-4.f_obj
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.g_obj.1
  - name: method
    value: EXAMINE
    smt-part: si-4.g_obj.1
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.g_obj.2
  - name: method
    value: EXAMINE
    smt-part: si-4.g_obj.2
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.g_obj.3
  - name: method
    value: EXAMINE
    smt-part: si-4.g_obj.3
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: si-4.g_obj.4
  - name: method
    value: INTERVIEW
    smt-part: si-4.g_obj.4
  - name: method
    value: TEST
    smt-part: si-4.g_obj.4
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: a.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: b.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: c.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: d.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: e.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: f.
  - name: response-point
    value: You must fill in this response point.
    ns: https://fedramp.gov/ns/oscal
    smt-part: g.
---

# si-4 - \[System and Information Integrity\] Information System Monitoring

## Control Statement

The organization:

- \[a.\] Monitors the information system to detect:

  - \[1.\] Attacks and indicators of potential attacks in accordance with {{ insert: param, si-4_prm_1 }}; and
  - \[2.\] Unauthorized local, network, and remote connections;

- \[b.\] Identifies unauthorized use of the information system through {{ insert: param, si-4_prm_2 }};

- \[c.\] Deploys monitoring devices:

  - \[1.\] Strategically within the information system to collect organization-determined essential information; and
  - \[2.\] At ad hoc locations within the system to track specific types of transactions of interest to the organization;

- \[d.\] Protects information obtained from intrusion-monitoring tools from unauthorized access, modification, and deletion;

- \[e.\] Heightens the level of information system monitoring activity whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information;

- \[f.\] Obtains legal opinion with regard to information system monitoring activities in accordance with applicable federal laws, Executive Orders, directives, policies, or regulations; and

- \[g.\] Provides {{ insert: param, si-4_prm_3 }} to {{ insert: param, si-4_prm_4 }} {{ insert: param, si-4_prm_5 }}.

## Control Objective

Determine if the organization:

- \[SI-4(a)\]

  - \[SI-4(a)(1)\]

    - \[SI-4(a)(1)[1]\] defines monitoring objectives to detect attacks and indicators of potential attacks on the information system;
    - \[SI-4(a)(1)[2]\] monitors the information system to detect, in accordance with organization-defined monitoring objectives,:

      - \[SI-4(a)(1)[2][a]\] attacks;
      - \[SI-4(a)(1)[2][b]\] indicators of potential attacks;

  - \[SI-4(a)(2)\] monitors the information system to detect unauthorized:

    - \[SI-4(a)(2)[1]\] local connections;
    - \[SI-4(a)(2)[2]\] network connections;
    - \[SI-4(a)(2)[3]\] remote connections;

- \[SI-4(b)\]

  - \[SI-4(b)(1)\] defines techniques and methods to identify unauthorized use of the information system;
  - \[SI-4(b)(2)\] identifies unauthorized use of the information system through organization-defined techniques and methods;

- \[SI-4(c)\] deploys monitoring devices:

  - \[SI-4(c)[1]\] strategically within the information system to collect organization-determined essential information;
  - \[SI-4(c)[2]\] at ad hoc locations within the system to track specific types of transactions of interest to the organization;

- \[SI-4(d)\] protects information obtained from intrusion-monitoring tools from unauthorized:

  - \[SI-4(d)[1]\] access;
  - \[SI-4(d)[2]\] modification;
  - \[SI-4(d)[3]\] deletion;

- \[SI-4(e)\] heightens the level of information system monitoring activity whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information;

- \[SI-4(f)\] obtains legal opinion with regard to information system monitoring activities in accordance with applicable federal laws, Executive Orders, directives, policies, or regulations;

- \[SI-4(g)\]

  - \[SI-4(g)[1]\] defines personnel or roles to whom information system monitoring information is to be provided;
  - \[SI-4(g)[2]\] defines information system monitoring information to be provided to organization-defined personnel or roles;
  - \[SI-4(g)[3]\] defines a frequency to provide organization-defined information system monitoring to organization-defined personnel or roles;
  - \[SI-4(g)[4]\] provides organization-defined information system monitoring information to organization-defined personnel or roles one or more of the following:

    - \[SI-4(g)[4][a]\] as needed; and/or
    - \[SI-4(g)[4][b]\] with the organization-defined frequency.

## Control guidance

Information system monitoring includes external and internal monitoring. External monitoring includes the observation of events occurring at the information system boundary (i.e., part of perimeter defense and boundary protection). Internal monitoring includes the observation of events occurring within the information system. Organizations can monitor information systems, for example, by observing audit activities in real time or by observing other system aspects such as access patterns, characteristics of access, and other actions. The monitoring objectives may guide determination of the events. Information system monitoring capability is achieved through a variety of tools and techniques (e.g., intrusion detection systems, intrusion prevention systems, malicious code protection software, scanning tools, audit record monitoring software, network monitoring software). Strategic locations for monitoring devices include, for example, selected perimeter locations and near server farms supporting critical applications, with such devices typically being employed at the managed interfaces associated with controls SC-7 and AC-17. Einstein network monitoring devices from the Department of Homeland Security can also be included as monitoring devices. The granularity of monitoring information collected is based on organizational monitoring objectives and the capability of information systems to support such objectives. Specific types of transactions of interest include, for example, Hyper Text Transfer Protocol (HTTP) traffic that bypasses HTTP proxies. Information system monitoring is an integral part of organizational continuous monitoring and incident response programs. Output from system monitoring serves as input to continuous monitoring and incident response programs. A network connection is any connection with a device that communicates through a network (e.g., local area network, Internet). A remote connection is any connection with a device communicating through an external network (e.g., the Internet). Local, network, and remote connections can be either wired or wireless.

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

See US-CERT Incident Response Reporting Guidelines.
