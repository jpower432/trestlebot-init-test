---
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
  pl-04_odp.01:
    alt-identifier: pl-4_prm_1
    profile-values:
      - <REPLACE_ME>
    profile-param-value-origin: <REPLACE_ME>
  pl-04_odp.02:
    alt-identifier: pl-4_prm_2
    profile-values:
      - <REPLACE_ME>
    profile-param-value-origin: <REPLACE_ME>
  pl-04_odp.03:
    alt-identifier: pl-4_prm_3
    profile-values:
      - <REPLACE_ME>
    profile-param-value-origin: <REPLACE_ME>
x-trestle-global:
  profile:
    title: NIST Special Publication 800-53 Revision 5 HIGH IMPACT BASELINE
  sort-id: pl-04
---

# pl-4 - \[Planning\] Rules of Behavior

## Control Statement

- \[a.\] Establish and provide to individuals requiring access to the system, the rules that describe their responsibilities and expected behavior for information and system usage, security, and privacy;

- \[b.\] Receive a documented acknowledgment from such individuals, indicating that they have read, understand, and agree to abide by the rules of behavior, before authorizing access to information and the system;

- \[c.\] Review and update the rules of behavior {{ insert: param, pl-04_odp.01 }} ; and

- \[d.\] Require individuals who have acknowledged a previous version of the rules of behavior to read and re-acknowledge {{ insert: param, pl-04_odp.02 }}.

## Control Assessment Objective

- \[PL-04a.\]

  - \[PL-04a.[01]\] rules that describe responsibilities and expected behavior for information and system usage, security, and privacy are established for individuals requiring access to the system;
  - \[PL-04a.[02]\] rules that describe responsibilities and expected behavior for information and system usage, security, and privacy are provided to individuals requiring access to the system;

- \[PL-04b.\] before authorizing access to information and the system, a documented acknowledgement from such individuals indicating that they have read, understand, and agree to abide by the rules of behavior is received;

- \[PL-04c.\] rules of behavior are reviewed and updated {{ insert: param, pl-04_odp.01 }};

- \[PL-04d.\] individuals who have acknowledged a previous version of the rules of behavior are required to read and reacknowledge {{ insert: param, pl-04_odp.02 }}.

## Control guidance

Rules of behavior represent a type of access agreement for organizational users. Other types of access agreements include nondisclosure agreements, conflict-of-interest agreements, and acceptable use agreements (see [PS-6](#ps-6) ). Organizations consider rules of behavior based on individual user roles and responsibilities and differentiate between rules that apply to privileged users and rules that apply to general users. Establishing rules of behavior for some types of non-organizational users, including individuals who receive information from federal systems, is often not feasible given the large number of such users and the limited nature of their interactions with the systems. Rules of behavior for organizational and non-organizational users can also be established in [AC-8](#ac-8) . The related controls section provides a list of controls that are relevant to organizational rules of behavior. [PL-4b](#pl-4_smt.b) , the documented acknowledgment portion of the control, may be satisfied by the literacy training and awareness and role-based training programs conducted by organizations if such training includes rules of behavior. Documented acknowledgements for rules of behavior include electronic or physical signatures and electronic agreement check boxes or radio buttons.

# Editable Content

<!-- Make additions and edits below -->
<!-- The above represents the contents of the control as received by the profile, prior to additions. -->
<!-- If the profile makes additions to the control, they will appear below. -->
<!-- The above markdown may not be edited but you may edit the content below, and/or introduce new additions to be made by the profile. -->
<!-- If there is a yaml header at the top, parameter values may be edited. Use --set-parameters to incorporate the changes during assembly. -->
<!-- The content here will then replace what is in the profile for this control, after running profile-assemble. -->
<!-- The current profile has no added parts for this control, but you may add new ones here. -->
<!-- Each addition must have a heading either of the form ## Control my_addition_name -->
<!-- or ## Part a. (where the a. refers to one of the control statement labels.) -->
<!-- "## Control" parts are new parts added after the statement part. -->
<!-- "## Part" parts are new parts added into the top-level statement part with that label. -->
<!-- Subparts may be added with nested hash levels of the form ### My Subpart Name -->
<!-- underneath the parent ## Control or ## Part being added -->
<!-- See https://oscal-compass.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->
