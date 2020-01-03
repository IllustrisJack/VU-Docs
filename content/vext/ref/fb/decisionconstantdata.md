---
title: DecisionConstantData
---
### Base Classes

[Asset](/vext/ref/fb/asset/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| DecisionConstantData()                                                          | Create a new instance of this container type.                                                                                   |
| DecisionConstantData(DecisionConstantData other)                                | Create a reference copy of an instance of the same type.                                                                        |
| DecisionConstantData([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [DecisionConstantData](/vext/ref/fb/decisionconstantdata/).                                      |
| DecisionConstantData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [DecisionConstantData](/vext/ref/fb/decisionconstantdata/). |

## Properties

| Name                           | Type   | Description |
| ------------------------------ | ------ | ----------- |
| newEnemyDecideMaxDistance      | number |             |
| allowEmergencyGoalInterrupt    | bool   |             |
| allowUninterruptibleBehaviours | bool   |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [DecisionConstantData](/vext/ref/fb/decisionconstantdata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [DecisionConstantData](/vext/ref/fb/decisionconstantdata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |