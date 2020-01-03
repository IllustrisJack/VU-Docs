---
title: RadiosityMaterial
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| RadiosityMaterial()                                                          | Create a new instance of this container type.                                                                             |
| RadiosityMaterial(RadiosityMaterial other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| RadiosityMaterial([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [RadiosityMaterial](/vext/ref/fb/radiositymaterial/). |

## Properties

| Name     | Type                              | Description |
| -------- | --------------------------------- | ----------- |
| color    | [Vec3](/vext/ref/shared/class/vec3) |             |
| name     | string                            |             |
| emissive | bool                              |             |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [RadiosityMaterial](/vext/ref/fb/radiositymaterial/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [RadiosityMaterial](/vext/ref/fb/radiositymaterial/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |