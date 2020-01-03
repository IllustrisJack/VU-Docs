---
title: EnvmapEntityData
---
### Base Classes

[EntityData](/vext/ref/fb/entitydata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                 | Description                                                                                                             |
| --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| EnvmapEntityData()                                                          | Create a new instance of this container type.                                                                           |
| EnvmapEntityData(EnvmapEntityData other)                                    | Create a reference copy of an instance of the same type.                                                                |
| EnvmapEntityData([EntityData](/vext/ref/fb/entitydata/) other)                            | Upcast an instance of type [EntityData](/vext/ref/fb/entitydata/) to [EnvmapEntityData](/vext/ref/fb/envmapentitydata/).                            |
| EnvmapEntityData([GameObjectData](/vext/ref/fb/gameobjectdata/) other)                    | Upcast an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata/) to [EnvmapEntityData](/vext/ref/fb/envmapentitydata/).                    |
| EnvmapEntityData([GameDataContainer](/vext/ref/fb/gamedatacontainer/) other)              | Upcast an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer/) to [EnvmapEntityData](/vext/ref/fb/envmapentitydata/).              |
| EnvmapEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [EnvmapEntityData](/vext/ref/fb/envmapentitydata/). |

## Methods

| Type                                 | Name            | Parameters                                     |
| ------------------------------------ | --------------- | ---------------------------------------------- |
| [EnvmapEntityData](/vext/ref/fb/envmapentitydata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [EnvmapEntityData](/vext/ref/fb/envmapentitydata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |