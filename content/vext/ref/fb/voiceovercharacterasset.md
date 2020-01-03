---
title: VoiceOverCharacterAsset
---
### Base Classes

[Asset](/vext/ref/fb/asset/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                        | Description                                                                                                                           |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| VoiceOverCharacterAsset()                                                          | Create a new instance of this container type.                                                                                         |
| VoiceOverCharacterAsset(VoiceOverCharacterAsset other)                             | Create a reference copy of an instance of the same type.                                                                              |
| VoiceOverCharacterAsset([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [VoiceOverCharacterAsset](/vext/ref/fb/voiceovercharacterasset/).                                      |
| VoiceOverCharacterAsset([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [VoiceOverCharacterAsset](/vext/ref/fb/voiceovercharacterasset/). |

## Methods

| Type                                               | Name            | Parameters                                     |
| -------------------------------------------------- | --------------- | ---------------------------------------------- |
| [VoiceOverCharacterAsset](/vext/ref/fb/voiceovercharacterasset/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [VoiceOverCharacterAsset](/vext/ref/fb/voiceovercharacterasset/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |