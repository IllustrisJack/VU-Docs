---
title: SubScreenData
---
## Description

A structure type representing a Frostbite data type.

## Constructors

| Constructor                        | Description                                              |
| ---------------------------------- | -------------------------------------------------------- |
| SubScreenData()                    | Create a new instance of this structure type.            |
| SubScreenData(SubScreenData other) | Create a reference copy of a structure of the same type. |

## Properties

| Name                         | Type                              | Description |
| ---------------------------- | --------------------------------- | ----------- |
| screenPosition               | [Vec3](/vext/ref/shared/class/vec3) |             |
| projectionAngleY             | number                            |             |
| projectionAngleZ             | number                            |             |
| projectionAngleX             | number                            |             |
| screenSize                   | number                            |             |
| iconSize                     | number                            |             |
| scaleIconSizeByDepthStrength | number                            |             |
| renderTargetApectRatio       | number                            |             |
| renderTargetIndex            | number                            |             |
| useRenderTarget              | bool                              |             |

## Methods

| Type                           | Name            | Parameters |
| ------------------------------ | --------------- | ---------- |
| [SubScreenData](/vext/ref/fb/subscreendata/) | [Clone](#clone) |            |

### Clone

> [SubScreenData](/vext/ref/fb/subscreendata/) **Clone**()

Creates a shallow-copy clone of the structure. Works similarly to [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone).