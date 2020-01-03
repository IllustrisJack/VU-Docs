---
title: UIColor
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                        | Description                                                                                           |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------- |
| UIColor()                                                          | Create a new instance of this container type.                                                         |
| UIColor(UIColor other)                                             | Create a reference copy of an instance of the same type.                                              |
| UIColor([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UIColor](/vext/ref/fb/uicolor/). |

## Properties

| Name      | Type                              | Description |
| --------- | --------------------------------- | ----------- |
| color     | [Vec4](/vext/ref/shared/class/vec4) |             |
| colorType | [UIColorType](/vext/ref/fb/uicolortype/)        |             |

## Methods

| Type               | Name            | Parameters                                     |
| ------------------ | --------------- | ---------------------------------------------- |
| [UIColor](/vext/ref/fb/uicolor/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UIColor](/vext/ref/fb/uicolor/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |