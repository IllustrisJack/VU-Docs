---
title: IrReverbControllerNodeData
---
### Base Classes

[AudioGraphNodeData](/vext/ref/fb/audiographnodedata/)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                           | Description                                                                                                                                 |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| IrReverbControllerNodeData()                                                          | Create a new instance of this container type.                                                                                               |
| IrReverbControllerNodeData(IrReverbControllerNodeData other)                          | Create a reference copy of an instance of the same type.                                                                                    |
| IrReverbControllerNodeData([AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) other)            | Upcast an instance of type [AudioGraphNodeData](/vext/ref/fb/audiographnodedata/) to [IrReverbControllerNodeData](/vext/ref/fb/irreverbcontrollernodedata/).            |
| IrReverbControllerNodeData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [IrReverbControllerNodeData](/vext/ref/fb/irreverbcontrollernodedata/). |

## Properties

| Name       | Type                                     | Description |
| ---------- | ---------------------------------------- | ----------- |
| reverb0    | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| amplitude0 | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| reverb1    | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |
| amplitude1 | [AudioGraphNodePort](/vext/ref/fb/audiographnodeport/) |             |

## Methods

| Type                                                     | Name            | Parameters                                     |
| -------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [IrReverbControllerNodeData](/vext/ref/fb/irreverbcontrollernodedata/) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [IrReverbControllerNodeData](/vext/ref/fb/irreverbcontrollernodedata/) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](/vext/ref/shared/class/guid/) | An optional GUID to assign to the instance. |