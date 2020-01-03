---
title: DifficultyData
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                               | Description                                                                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| DifficultyData()                                                          | Create a new instance of this container type.                                                                       |
| DifficultyData(DifficultyData other)                                      | Create a reference copy of an instance of the same type.                                                            |
| DifficultyData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [DifficultyData](/vext/ref/fb/difficultydata/). |

## Properties

| Name                                | Type                                         | Description |
| ----------------------------------- | -------------------------------------------- | ----------- |
| stickyBoxModifier                   | [Vec3](/vext/ref/shared/class/vec3)            |             |
| snapBoxModifier                     | [Vec3](/vext/ref/shared/class/vec3)            |             |
| humanHealthModifier                 | number                                       |             |
| gameType                            | [PersistenceGameType](/vext/ref/fb/persistencegametype/)   |             |
| friendsHealthModifier               | number                                       |             |
| friendlyDamageModifier              | number                                       |             |
| vehicleDamageModifier               | number                                       |             |
| humanInCriticalHealth               | number                                       |             |
| enemiesHealthModifier               | number                                       |             |
| humanRegenerationRateModifier       | number                                       |             |
| humanInCriticalHealthDamageModifier | number                                       |             |
| interactiveManDownDamageModifier    | number                                       |             |
| interactiveManDownTimeMultiplier    | number                                       |             |
| interactiveManDownReviveTime        | number                                       |             |
| adrenalineKillLimit                 | number                                       |             |
| criticalHealthJesusModeTimeModifier | number                                       |             |
| difficulty                          | [Difficulty](/vext/ref/fb/difficulty/)                     |             |
| criticalFakeImmortalModifier        | number                                       |             |
| suckZoomModifier                    | number                                       |             |
| aiData                              | [GameAIDifficultyData](/vext/ref/fb/gameaidifficultydata/) |             |
| aiBulletDamageHumanCooldown         | number                                       |             |
| usePitchZoomSnap                    | bool                                         |             |

## Methods

| Type                             | Name            | Parameters                                     |
| -------------------------------- | --------------- | ---------------------------------------------- |
| [DifficultyData](/vext/ref/fb/difficultydata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [DifficultyData](/vext/ref/fb/difficultydata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |