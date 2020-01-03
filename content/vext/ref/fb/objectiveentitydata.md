---
title: ObjectiveEntityData
---
### Base Classes

[GameEntityData](/vext/ref/fb/gameentitydata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| ObjectiveEntityData()                                                          | Create a new instance of this container type.                                                                                 |
| ObjectiveEntityData(ObjectiveEntityData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| ObjectiveEntityData([GameEntityData](/vext/ref/fb/gameentitydata/) other)                    | Upcast an instance of type [GameEntityData](/vext/ref/fb/gameentitydata/) to [ObjectiveEntityData](/vext/ref/fb/objectiveentitydata/).                    |
| ObjectiveEntityData([SpatialEntityData](/vext/ref/fb/spatialentitydata/) other)              | Upcast an instance of type [SpatialEntityData](/vext/ref/fb/spatialentitydata/) to [ObjectiveEntityData](/vext/ref/fb/objectiveentitydata/).              |
| ObjectiveEntityData([EntityData](/vext/ref/fb/entitydata/) other)                            | Upcast an instance of type [EntityData](/vext/ref/fb/entitydata/) to [ObjectiveEntityData](/vext/ref/fb/objectiveentitydata/).                            |
| ObjectiveEntityData([GameObjectData](/vext/ref/fb/gameobjectdata/) other)                    | Upcast an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata/) to [ObjectiveEntityData](/vext/ref/fb/objectiveentitydata/).                    |
| ObjectiveEntityData([GameDataContainer](/vext/ref/fb/gamedatacontainer/) other)              | Upcast an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer/) to [ObjectiveEntityData](/vext/ref/fb/objectiveentitydata/).              |
| ObjectiveEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [ObjectiveEntityData](/vext/ref/fb/objectiveentitydata/). |

## Properties

| Name                            | Type                                               | Description |
| ------------------------------- | -------------------------------------------------- | ----------- |
| objectiveBriefSid               | string                                             |             |
| objectiveSid                    | string                                             |             |
| hudData                         | [MissionObjectiveHudData](/vext/ref/fb/missionobjectivehuddata/) |             |
| objectiveType                   | [ObjectiveType](/vext/ref/fb/objectivetype/)                     |             |
| displayTime                     | number                                             |             |
| delayTime                       | number                                             |             |
| squadId                         | [SquadId](/vext/ref/fb/squadid/)                                 |             |
| teamId                          | [TeamId](/vext/ref/fb/teamid/)                                   |             |
| successSid                      | string                                             |             |
| reciever                        | [MessageReciever](/vext/ref/fb/messagereciever/)                 |             |
| retriggerSuccessOnShowObjective | bool                                               |             |
| tutorial                        | bool                                               |             |
| displaySuccess                  | bool                                               |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [ObjectiveEntityData](/vext/ref/fb/objectiveentitydata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [ObjectiveEntityData](/vext/ref/fb/objectiveentitydata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |