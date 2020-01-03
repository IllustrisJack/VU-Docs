---
title: TimerNodeData
---
### Base Classes

[AudioGraphNodeData](/vext/ref/fb/audiographnodedata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                              | Description                                                                                                       |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| TimerNodeData()                                                          | Create a new instance of this container type.                                                                     |
| TimerNodeData(TimerNodeData other)                                       | Create a reference copy of an instance of the same type.                                                          |
| TimerNodeData([AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) other)            | Upcast an instance of type [AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) to [TimerNodeData](/vext/ref/fb/timernodedata/).            |
| TimerNodeData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [TimerNodeData](/vext/ref/fb/timernodedata/). |

## Properties

| Name     | Type                                     | Description |
| -------- | ---------------------------------------- | ----------- |
| start    | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| stop     | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| period   | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| tick     | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| progress | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| mode     | [TimerMode](/vext/ref/fb/timermode/)                   |             |

## Methods

| Type                           | Name            | Parameters                                     |
| ------------------------------ | --------------- | ---------------------------------------------- |
| [TimerNodeData](/vext/ref/fb/timernodedata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [TimerNodeData](/vext/ref/fb/timernodedata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |