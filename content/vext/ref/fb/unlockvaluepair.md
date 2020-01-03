---
title: UnlockValuePair
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                | Description                                                                                                           |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| UnlockValuePair()                                                          | Create a new instance of this container type.                                                                         |
| UnlockValuePair(UnlockValuePair other)                                     | Create a reference copy of an instance of the same type.                                                              |
| UnlockValuePair([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UnlockValuePair](/vext/ref/fb/unlockvaluepair/). |

## Properties

| Name | Type   | Description |
| ---- | ------ | ----------- |
| id   | string |             |

## Methods

| Type                               | Name            | Parameters                                     |
| ---------------------------------- | --------------- | ---------------------------------------------- |
| [UnlockValuePair](/vext/ref/fb/unlockvaluepair/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UnlockValuePair](/vext/ref/fb/unlockvaluepair/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |