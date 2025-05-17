# Roblox Notification System
## 版权所有，禁止二改

--HA TEAM
Httadmin专属
--Github.com.DevSloPo
--作者↑

右下角堆叠式通知系统，支持自定义图标、进度条和动画效果

## 功能特性

- 右下角堆叠显示
- 可自定义颜色和样式
- 自动消失进度条
- 支持图标显示
- 平滑入场/退场动画

## 使用方法

```lua
local Notification = require(path.to.NotificationSystem)

--普通通知
Notification.send("标题", "内容", 5)

--带图标通知
Notification.send("标题", "内容", 4, "rbxassetid://6031071050")

--自定义进度条颜色
Notification.send("标题", "内容", 3, nil, Color3.fromRGB(255, 0, 0))