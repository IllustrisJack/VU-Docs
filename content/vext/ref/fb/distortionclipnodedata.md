---
title: DistortionClipNodeData
---
### Base Classes

[AudioGraphNodeData](/vext/ref/fb/audiographnodedata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                       | Description                                                                                                                         |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| DistortionClipNodeData()                                                          | Create a new instance of this container type.                                                                                       |
| DistortionClipNodeData(DistortionClipNodeData other)                              | Create a reference copy of an instance of the same type.                                                                            |
| DistortionClipNodeData([AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) other)            | Upcast an instance of type [AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) to [DistortionClipNodeData](/vext/ref/fb/distortionclipnodedata/).            |
| DistortionClipNodeData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [DistortionClipNodeData](/vext/ref/fb/distortionclipnodedata/). |

## Properties

| Name      | Type                                       | Description |
| --------- | ------------------------------------------ | ----------- |
| inValue   | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/)   |             |
| clipLevel | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/)   |             |
| out       | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/)   |             |
| plugin    | [SoundGraphPluginRef](/vext/ref/fb/soundgraphpluginref/) |             |

## Methods

| Type                                             | Name            | Parameters                                     |
| ------------------------------------------------ | --------------- | ---------------------------------------------- |
| [DistortionClipNodeData](/vext/ref/fb/distortionclipnodedata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [DistortionClipNodeData](/vext/ref/fb/distortionclipnodedata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |