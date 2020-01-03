---
title: FloatRecordingData
---
### Base Classes

[PropertyRecordingData](/vext/ref/fb/propertyrecordingdata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                   | Description                                                                                                                 |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| FloatRecordingData()                                                          | Create a new instance of this container type.                                                                               |
| FloatRecordingData(FloatRecordingData other)                                  | Create a reference copy of an instance of the same type.                                                                    |
| FloatRecordingData([PropertyRecordingData](/vext/ref/fb/propertyrecordingdata/) other)      | Upcast an instance of type [PropertyRecordingData](/vext/ref/fb/propertyrecordingdata/) to [FloatRecordingData](/vext/ref/fb/floatrecordingdata/).      |
| FloatRecordingData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [FloatRecordingData](/vext/ref/fb/floatrecordingdata/). |

## Properties

| Name   | Type       | Description |
| ------ | ---------- | ----------- |
| values | number\[\] |             |

## Methods

| Type                                     | Name            | Parameters                                     |
| ---------------------------------------- | --------------- | ---------------------------------------------- |
| [FloatRecordingData](/vext/ref/fb/floatrecordingdata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [FloatRecordingData](/vext/ref/fb/floatrecordingdata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |