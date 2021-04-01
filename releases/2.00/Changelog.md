# Transition from Core Person v1.0.0 to v2.0.0

## Introduction

This document describes the (major) changes to [the current version 1.0.0](https://github.com/SEMICeu/Core-Person-Vocabulary/tree/master/releases/1.00) of the Core Person Vocabulary for which a new version is being proposed ([version 2.0.0](https://semiceu.github.io/Core-Person-Vocabulary/releases/2.00/)). The list of changes results in the new version to be considered as a major release.

## Detailed changes

The table below gives an overview of the classes (and their definitions) within both data models. Classes that are related are juxta-positioned.

**C** stands for changes in classes

**R** stands for changes in relationships

**P** stands for changes in properties

**D** stands for changes in data types

| Nr | Core Person Vocabulary v1.0.0 | Core Person Vocabulary v2.0.0 | Rationale | GitHub / Change |
| --- | --- | --- | --- | --- |
| C1 | **Change** | **Change class removed** Issue created: https://github.com/SEMICeu/Core-Person-Vocabulary/issues/10** | There should be a discussion on Github about the interest of keeping the Change class. | GitHub |
| P1 | **Jurisdiction id** | **Jurisdiction id** | Why is an ID property required for this class and not for others? Should we add/remove ID properties? | GitHub |
| D1 | **Person.familyName: String** | **Person.familyName: Text** | Alignment with SDG WP4 where the datatype was changed to allow for multi-script. |Change|
| D2 | **Person.givenName: String** | **Person.givenName: Text** | Alignment with SDG WP4 where the datatype was changed to allow for multi-script. | Change |
| D3 | **Person.alternativeName: String** | **Person.alternativeName: Text** | Following the same rationale as for given and family name. | Change |
| D4 | **Person.birthName: String** | **Person.birthName: Text** | Following the same rationale as for given and family name. | Change |
| D5 | **Person.fullName: String** | **Person.fullName: Text** | Following the same rationale as for given and family name. | Change |
| D6 | **Person.patronymicName: String** | **Person.patronymicName: Text** | Following the same rationale as for given and family name. | Change |
| P2 | **Person.givenName** | **Person.givenName (forename)** | Alignment with public documents schema. | Change |
| P3 | **Person.familyName** | **Person.familyName (surname)** | Alignment with public documents schema. | Change |
| R1 | **-** | **Person.registeredAddress: Address** | This relationship was needed by SDG WP4. | Change |
| P4 | **-** | **Person.identifier: added reference to eIDAS regulation and mapping.** | | Change |
| P5 | **Definition of Person.dateOfBirth/dateOfDeath:** &quot;A date that specifies the birth/death date of a Person.&quot; | &quot;The day on which the Person was born/died.&quot; | Improved definitions based on SDG WP4. | Change |
| R2 | **Definition of Person.placeOfBirth/placeOfDeath:**&quot;A Person&#39;s place of birth/death.&quot; | &quot;The Location where the Person was born / died.&quot; | Improved definitions based on SDG WP4. | Change |
