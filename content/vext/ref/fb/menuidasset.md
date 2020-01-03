---
title: MenuIdAsset
---
### Base Classes

[Asset](/vext/ref/fb/asset/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                            | Description                                                                                                   |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| MenuIdAsset()                                                          | Create a new instance of this container type.                                                                 |
| MenuIdAsset(MenuIdAsset other)                                         | Create a reference copy of an instance of the same type.                                                      |
| MenuIdAsset([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [MenuIdAsset](/vext/ref/fb/menuidasset/).                                      |
| MenuIdAsset([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MenuIdAsset](/vext/ref/fb/menuidasset/). |

## Properties

| Name      | Type   | Description |
| --------- | ------ | ----------- |
| shortName | string |             |

## Methods

| Type                       | Name            | Parameters                                     |
| -------------------------- | --------------- | ---------------------------------------------- |
| [MenuIdAsset](/vext/ref/fb/menuidasset/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MenuIdAsset](/vext/ref/fb/menuidasset/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |