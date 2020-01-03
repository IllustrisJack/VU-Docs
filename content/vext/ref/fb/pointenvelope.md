---
title: PointEnvelope
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                              | Description                                                                                                       |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| PointEnvelope()                                                          | Create a new instance of this container type.                                                                     |
| PointEnvelope(PointEnvelope other)                                       | Create a reference copy of an instance of the same type.                                                          |
| PointEnvelope([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [PointEnvelope](/vext/ref/fb/pointenvelope/). |

## Properties

| Name   | Type                                         | Description |
| ------ | -------------------------------------------- | ----------- |
| points | [PointEnvelopePoint](/vext/ref/fb/pointenvelopepoint/)\[\] |             |

## Methods

| Type                           | Name            | Parameters                                     |
| ------------------------------ | --------------- | ---------------------------------------------- |
| [PointEnvelope](/vext/ref/fb/pointenvelope/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [PointEnvelope](/vext/ref/fb/pointenvelope/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |