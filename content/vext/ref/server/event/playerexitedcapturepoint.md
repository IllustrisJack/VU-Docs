---
title: Player:ExitedCapturePoint
---
## Description

## Parameters

| Type                                  | Name         | Description |
| ------------------------------------- | ------------ | ----------- |
| [Player](/vext/ref/server/class/player) | player       |             |
| [Entity](/vext/ref/shared/class/entity) | capturePoint |             |

## Usage Example

``` lua
local function OnPlayerExitedCapturePoint(player, capturePoint)
    -- Add your logic here
end

Events:Subscribe('Player:ExitedCapturePoint', OnPlayerExitedCapturePoint)
```