---
title: Asset
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                      | Description                                                                                       |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| Asset()                                                          | Create a new instance of this container type.                                                     |
| Asset(Asset other)                                               | Create a reference copy of an instance of the same type.                                          |
| Asset([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [Asset](/vext/ref/fb/asset/). |

## Properties

| Name | Type   | Description |
| ---- | ------ | ----------- |
| name | string |             |

## Methods

| Type           | Name            | Parameters                                     |
| -------------- | --------------- | ---------------------------------------------- |
| [Asset](/vext/ref/fb/asset/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [Asset](/vext/ref/fb/asset/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |