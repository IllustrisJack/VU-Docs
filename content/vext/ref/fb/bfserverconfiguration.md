---
title: BFServerConfiguration
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| BFServerConfiguration()                                                          | Create a new instance of this container type.                                                                                     |
| BFServerConfiguration(BFServerConfiguration other)                               | Create a reference copy of an instance of the same type.                                                                          |
| BFServerConfiguration([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [BFServerConfiguration](/vext/ref/fb/bfserverconfiguration/). |

## Properties

| Name      | Type                                                               | Description |
| --------- | ------------------------------------------------------------------ | ----------- |
| schedules | [BFServerConfigurationSchedule](/vext/ref/fb/bfserverconfigurationschedule/)\[\] |             |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [BFServerConfiguration](/vext/ref/fb/bfserverconfiguration/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [BFServerConfiguration](/vext/ref/fb/bfserverconfiguration/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |