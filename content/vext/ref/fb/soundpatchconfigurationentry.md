---
title: SoundPatchConfigurationEntry
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                             | Description                                                                                                                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| SoundPatchConfigurationEntry()                                                          | Create a new instance of this container type.                                                                                                   |
| SoundPatchConfigurationEntry(SoundPatchConfigurationEntry other)                        | Create a reference copy of an instance of the same type.                                                                                        |
| SoundPatchConfigurationEntry([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SoundPatchConfigurationEntry](/vext/ref/fb/soundpatchconfigurationentry/). |

## Methods

| Type                                                         | Name            | Parameters                                     |
| ------------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [SoundPatchConfigurationEntry](/vext/ref/fb/soundpatchconfigurationentry/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SoundPatchConfigurationEntry](/vext/ref/fb/soundpatchconfigurationentry/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |