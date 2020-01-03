---
title: TextureAtlasAsset
---
### Base Classes

[Asset](/vext/ref/fb/asset/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| TextureAtlasAsset()                                                          | Create a new instance of this container type.                                                                             |
| TextureAtlasAsset(TextureAtlasAsset other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| TextureAtlasAsset([Asset](/vext/ref/fb/asset/) other)                                      | Upcast an instance of type [Asset](/vext/ref/fb/asset/) to [TextureAtlasAsset](/vext/ref/fb/textureatlasasset/).                                      |
| TextureAtlasAsset([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [TextureAtlasAsset](/vext/ref/fb/textureatlasasset/). |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [TextureAtlasAsset](/vext/ref/fb/textureatlasasset/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [TextureAtlasAsset](/vext/ref/fb/textureatlasasset/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |