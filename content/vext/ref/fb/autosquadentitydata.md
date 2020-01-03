---
title: AutoSquadEntityData
---
### Base Classes

[GameEntityData](/vext/ref/fb/gameentitydata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| AutoSquadEntityData()                                                          | Create a new instance of this container type.                                                                                 |
| AutoSquadEntityData(AutoSquadEntityData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| AutoSquadEntityData([GameEntityData](/vext/ref/fb/gameentitydata/) other)                    | Upcast an instance of type [GameEntityData](/vext/ref/fb/gameentitydata/) to [AutoSquadEntityData](/vext/ref/fb/autosquadentitydata/).                    |
| AutoSquadEntityData([SpatialEntityData](/vext/ref/fb/spatialentitydata/) other)              | Upcast an instance of type [SpatialEntityData](/vext/ref/fb/spatialentitydata/) to [AutoSquadEntityData](/vext/ref/fb/autosquadentitydata/).              |
| AutoSquadEntityData([EntityData](/vext/ref/fb/entitydata/) other)                            | Upcast an instance of type [EntityData](/vext/ref/fb/entitydata/) to [AutoSquadEntityData](/vext/ref/fb/autosquadentitydata/).                            |
| AutoSquadEntityData([GameObjectData](/vext/ref/fb/gameobjectdata/) other)                    | Upcast an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata/) to [AutoSquadEntityData](/vext/ref/fb/autosquadentitydata/).                    |
| AutoSquadEntityData([GameDataContainer](/vext/ref/fb/gamedatacontainer/) other)              | Upcast an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer/) to [AutoSquadEntityData](/vext/ref/fb/autosquadentitydata/).              |
| AutoSquadEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [AutoSquadEntityData](/vext/ref/fb/autosquadentitydata/). |

## Properties

| Name    | Type               | Description |
| ------- | ------------------ | ----------- |
| squadId | [SquadId](/vext/ref/fb/squadid/) |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [AutoSquadEntityData](/vext/ref/fb/autosquadentitydata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [AutoSquadEntityData](/vext/ref/fb/autosquadentitydata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |