---
title: LowPassFir64NodeData
---
### Base Classes

[AudioGraphNodeData](/vext/ref/fb/audiographnodedata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                     | Description                                                                                                                     |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| LowPassFir64NodeData()                                                          | Create a new instance of this container type.                                                                                   |
| LowPassFir64NodeData(LowPassFir64NodeData other)                                | Create a reference copy of an instance of the same type.                                                                        |
| LowPassFir64NodeData([AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) other)            | Upcast an instance of type [AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) to [LowPassFir64NodeData](/vext/ref/fb/lowpassfir64nodedata/).            |
| LowPassFir64NodeData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [LowPassFir64NodeData](/vext/ref/fb/lowpassfir64nodedata/). |

## Properties

| Name      | Type                                       | Description |
| --------- | ------------------------------------------ | ----------- |
| inValue   | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/)   |             |
| frequency | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/)   |             |
| out       | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/)   |             |
| plugin    | [SoundGraphPluginRef](/vext/ref/fb/soundgraphpluginref/) |             |

## Methods

| Type                                         | Name            | Parameters                                     |
| -------------------------------------------- | --------------- | ---------------------------------------------- |
| [LowPassFir64NodeData](/vext/ref/fb/lowpassfir64nodedata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [LowPassFir64NodeData](/vext/ref/fb/lowpassfir64nodedata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |