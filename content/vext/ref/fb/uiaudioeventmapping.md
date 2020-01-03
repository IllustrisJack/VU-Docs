---
title: UIAudioEventMapping
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                                    | Description                                              |
| ---------------------------------------------- | -------------------------------------------------------- |
| UIAudioEventMapping()                          | Create a new instance of this structure type.            |
| UIAudioEventMapping(UIAudioEventMapping other) | Create a reference copy of a structure of the same type. |

## Properties

| Name       | Type                     | Description |
| ---------- | ------------------------ | ----------- |
| eventName  | string                   |             |
| soundAsset | [SoundAsset](/vext/ref/fb/soundasset/) |             |

## Methods

| Type                                       | Name            | Parameters |
| ------------------------------------------ | --------------- | ---------- |
| [UIAudioEventMapping](/vext/ref/fb/uiaudioeventmapping/) | [Clone](#clone) |            |

### Clone

> [UIAudioEventMapping](/vext/ref/fb/uiaudioeventmapping/) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).