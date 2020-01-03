---
title: SyncedIntEntityData
---
### Base Classes

[EntityData](/vext/ref/fb/entitydata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                    | Description                                                                                                                   |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| SyncedIntEntityData()                                                          | Create a new instance of this container type.                                                                                 |
| SyncedIntEntityData(SyncedIntEntityData other)                                 | Create a reference copy of an instance of the same type.                                                                      |
| SyncedIntEntityData([EntityData](/vext/ref/fb/entitydata/) other)                            | Upcast an instance of type [EntityData](/vext/ref/fb/entitydata/) to [SyncedIntEntityData](/vext/ref/fb/syncedintentitydata/).                            |
| SyncedIntEntityData([GameObjectData](/vext/ref/fb/gameobjectdata/) other)                    | Upcast an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata/) to [SyncedIntEntityData](/vext/ref/fb/syncedintentitydata/).                    |
| SyncedIntEntityData([GameDataContainer](/vext/ref/fb/gamedatacontainer/) other)              | Upcast an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer/) to [SyncedIntEntityData](/vext/ref/fb/syncedintentitydata/).              |
| SyncedIntEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SyncedIntEntityData](/vext/ref/fb/syncedintentitydata/). |

## Properties

| Name    | Type   | Description |
| ------- | ------ | ----------- |
| inValue | number |             |

## Methods

| Type                                       | Name            | Parameters                                     |
| ------------------------------------------ | --------------- | ---------------------------------------------- |
| [SyncedIntEntityData](/vext/ref/fb/syncedintentitydata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SyncedIntEntityData](/vext/ref/fb/syncedintentitydata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |