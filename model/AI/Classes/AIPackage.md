SPDX-License-Identifier: Community-Spec-1.0

# AIPackage

## Summary

Provides information about the fields in the AI package profile.

## Description

Metadata information that can be added to a package to describe an AI application or trained AI model. 

## Metadata

- name: AIPackage
- SubclassOf: /Software/Package
- Instantiability: Concrete

## Properties

- energyConsumption
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- standardCompliance
  - type: xsd:string
  - minCount: 0
- limitation
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- typeOfModel
  - type: xsd:string
  - minCount: 0
- informationAboutTraining
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- informationAboutApplication
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- hyperparameter
  - type: /Core/DictionaryEntry
  - minCount: 0
- modelDataPreprocessing
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- modelExplainability
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- sensitivePersonalInformation
  - type: PresenceType
  - minCount: 0
  - maxCount: 1
- metricDecisionThreshold
  - type: /Core/DictionaryEntry
  - minCount: 0
- metric
  - type: /Core/DictionaryEntry
  - minCount: 0
- domain
  - type: xsd:string
  - minCount: 0
- autonomyType
  - type: PresenceType
  - minCount: 0
  - maxCount: 1
- safetyRiskAssessment
  - type: SafetyRiskAssessmentType
  - minCount: 0
  - maxCount: 1
