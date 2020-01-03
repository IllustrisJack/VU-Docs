---
title: CharacterHealthComponentData
---
### Base Classes

[ComponentData](/vext/ref/fb/componentdata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                             | Description                                                                                                                                     |
| --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| CharacterHealthComponentData()                                                          | Create a new instance of this container type.                                                                                                   |
| CharacterHealthComponentData(CharacterHealthComponentData other)                        | Create a reference copy of an instance of the same type.                                                                                        |
| CharacterHealthComponentData([ComponentData](/vext/ref/fb/componentdata/) other)                      | Upcast an instance of type [ComponentData](/vext/ref/fb/componentdata/) to [CharacterHealthComponentData](/vext/ref/fb/characterhealthcomponentdata/).                      |
| CharacterHealthComponentData([GameObjectData](/vext/ref/fb/gameobjectdata/) other)                    | Upcast an instance of type [GameObjectData](/vext/ref/fb/gameobjectdata/) to [CharacterHealthComponentData](/vext/ref/fb/characterhealthcomponentdata/).                    |
| CharacterHealthComponentData([GameDataContainer](/vext/ref/fb/gamedatacontainer/) other)              | Upcast an instance of type [GameDataContainer](/vext/ref/fb/gamedatacontainer/) to [CharacterHealthComponentData](/vext/ref/fb/characterhealthcomponentdata/).              |
| CharacterHealthComponentData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [CharacterHealthComponentData](/vext/ref/fb/characterhealthcomponentdata/). |

## Properties

| Name                      | Type   | Description |
| ------------------------- | ------ | ----------- |
| maxHealth                 | number |             |
| regenerateHealthPerSecond | number |             |
| regenerateHealth          | bool   |             |
| isImmortal                | bool   |             |

## Methods

| Type                                                         | Name            | Parameters                                     |
| ------------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [CharacterHealthComponentData](/vext/ref/fb/characterhealthcomponentdata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [CharacterHealthComponentData](/vext/ref/fb/characterhealthcomponentdata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |