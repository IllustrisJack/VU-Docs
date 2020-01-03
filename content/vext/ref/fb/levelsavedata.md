---
title: LevelSaveData
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                              | Description                                                                                                       |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| LevelSaveData()                                                          | Create a new instance of this container type.                                                                     |
| LevelSaveData(LevelSaveData other)                                       | Create a reference copy of an instance of the same type.                                                          |
| LevelSaveData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [LevelSaveData](/vext/ref/fb/levelsavedata/). |

## Properties

| Name      | Type       | Description |
| --------- | ---------- | ----------- |
| saveSize  | number     |             |
| saveNames | string\[\] |             |

## Methods

| Type                           | Name            | Parameters                                     |
| ------------------------------ | --------------- | ---------------------------------------------- |
| [LevelSaveData](/vext/ref/fb/levelsavedata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [LevelSaveData](/vext/ref/fb/levelsavedata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |