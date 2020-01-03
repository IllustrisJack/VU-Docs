---
title: DestructionVolumeProjectionData
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                                                            | Description                                              |
| ---------------------------------------------------------------------- | -------------------------------------------------------- |
| DestructionVolumeProjectionData()                                      | Create a new instance of this structure type.            |
| DestructionVolumeProjectionData(DestructionVolumeProjectionData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name         | Type                              | Description |
| ------------ | --------------------------------- | ----------- |
| normal       | [Vec3](/vext/ref/shared/class/vec3) |             |
| tangentAngle | number                            |             |

## Methods

| Type                                                               | Name            | Parameters |
| ------------------------------------------------------------------ | --------------- | ---------- |
| [DestructionVolumeProjectionData](/vext/ref/fb/destructionvolumeprojectiondata/) | [Clone](#clone) |            |

### Clone

> [DestructionVolumeProjectionData](/vext/ref/fb/destructionvolumeprojectiondata/) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).