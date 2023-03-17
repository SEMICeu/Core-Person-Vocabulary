# Core Person Changelog

## Introduction

This document describes the (major) changes to [the current version 2.0.0](https://github.com/SEMICeu/Core-Person-Vocabulary/tree/master/releases/2.00) of the Core Person Vocabulary for which a new version is being proposed ([version 2.1.0](https://semiceu.github.io/Core-Person-Vocabulary/releases/2.1.0/)). The list of changes results in the new version to be considered as a major release.

## Changes from  v2.0.0 to v2.1.0
The table below gives an overview of the classes (and their definitions) within both data models. Classes that are related are juxta-positioned.

**C** stands for changes in classes

**R** stands for changes in relationships

**P** stands for changes in properties

**D** stands for changes in data types

### Terms

| Nr  | Core Person Vocabulary v2.0.0    | Core Person Vocabulary v2.1.0     | Rationale                                                  | GitHub/Change                                                            |
| --- | -------------------------------- | --------------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------------ |
| P1  | \-                               | Person.sex                        | differentiate gender and sex                               | [#38](https://github.com/SEMICeu/Core-Person-Vocabulary/issues/38)       |
| C1  | \-                               | ContactPoint                      | add contact information to a person                        | [#36](https://github.com/SEMICeu/Core-Person-Vocabulary/issues/36)       |
| P2  | \-                               | Agent.type                        | Comply with ADMS                                           |                                                                          |
| P3  | \-                               | Agent.name                        | Comply with ADMS                                           |                                                                          |
| P4  | Address.addressID:String         | Address.addressID:Literal         | Comply with Core Location                                  | [CLV #24](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/24) |
| P5  | Address.locatorDesignator:String | Address.locatorDesignator:Literal | Comply with Core Location                                  | [CLV #24](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/24) |
| P6  | Address.postCode:String          | Address.postCode:Literal          | Comply with Core Location                                  | [CLV #24](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/24) |
| P7  | Address.poBox:String             | Address.poBox:Literal             | Comply with Core Location                                  | [CLV #24](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/24) |
| P8  | Address.adminUnitL1              | Address.adminUnitL1               | Removed round brackets in the label                        | [CLV #23](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/23) |
| P9  | Address.adminUnitL2              | Address.adminUnitL2               | Removed round brackets in the label                        | [CLV #23](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/23) |
| P10 | Address.postName                 | Address.postName                  | Removed round brackets in the label                        | [CLV #23](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/23) |
| P11 | Person.familyName                | Person.familyName                 | Removed round brackets in the label                        | [CLV #23](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/23) |
| P12 | Person.givenName                 | Person.givenName                  | Removed round brackets in the label and adapted usage note | [CLV #23](https://github.com/SEMICeu/Core-Location-Vocabulary/issues/23) |
| P13 | Person                           | Person                            | Usage note adapted to the current model                    |                                                                          |
| R1  | \-                               | Person.contactPoint:ContactPoint  | add contact information to a person                        | [#36](https://github.com/SEMICeu/Core-Person-Vocabulary/issues/36)       |

