---
title: BigWorldSetting
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                | Description                                                                                                           |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BigWorldSetting()                                                          | Create a new instance of this container type.                                                                         |
| BigWorldSetting(BigWorldSetting other)                                     | Create a reference copy of an instance of the same type.                                                              |
| BigWorldSetting([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [BigWorldSetting](/vext/ref/fb/bigworldsetting/). |

## Properties

| Name                  | Type                     | Description |
| --------------------- | ------------------------ | ----------- |
| sound                 | [SoundAsset](/vext/ref/fb/soundasset/) |             |
| minDistance           | number                   |             |
| maxDistance           | number                   |             |
| minDelayTimeInMinutes | number                   |             |
| maxDelayTimeInMinutes | number                   |             |

## Methods

| Type                               | Name            | Parameters                                     |
| ---------------------------------- | --------------- | ---------------------------------------------- |
| [BigWorldSetting](/vext/ref/fb/bigworldsetting/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [BigWorldSetting](/vext/ref/fb/bigworldsetting/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |