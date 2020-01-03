---
title: RoundOverEvent
---
### Base Classes

[MetricEvent](/vext/ref/fb/metricevent/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                               | Description                                                                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| RoundOverEvent()                                                          | Create a new instance of this container type.                                                                       |
| RoundOverEvent(RoundOverEvent other)                                      | Create a reference copy of an instance of the same type.                                                            |
| RoundOverEvent([MetricEvent](/vext/ref/fb/metricevent/) other)                          | Upcast an instance of type [MetricEvent](/vext/ref/fb/metricevent/) to [RoundOverEvent](/vext/ref/fb/roundoverevent/).                          |
| RoundOverEvent([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [RoundOverEvent](/vext/ref/fb/roundoverevent/). |

## Properties

| Name        | Type   | Description |
| ----------- | ------ | ----------- |
| winningTeam | number |             |
| ticketsLeft | number |             |

## Methods

| Type                             | Name            | Parameters                                     |
| -------------------------------- | --------------- | ---------------------------------------------- |
| [RoundOverEvent](/vext/ref/fb/roundoverevent/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [RoundOverEvent](/vext/ref/fb/roundoverevent/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |