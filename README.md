# Roblox Notification 
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
--使用例子
local Httadmin = loadstring(game:HttpGet("https://raw.githubusercontent.com/DevSloPo/Notifica/refs/heads/main/Main.lua"))()

Httadmin.send("欢迎", "欢迎", 4, "rbxassetid://6031071050")
