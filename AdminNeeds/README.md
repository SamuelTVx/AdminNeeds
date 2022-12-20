
**Installation**
1) Put into folder into your resource folder
2) Start after es_extended in your server.cfg
3) Edit config.lua file to fit your needs

**Configurations**

`Config.SeeOwnLabel = true/false`
- if true you will be see your own tag above yourself

`Config.SeeDistance = 100`
- distance on which will other player will see your tag

`Config.TextSize = 1.5`
- font size for tags more is bigger

`Config.ZOffset = 1.2`
- offset for tag that determinate how much will be tag above player

`Config.NearCheckWait = 500`
- miliseconds to check if player is near any admin

`Config.TagByPermission = true`
- with this option tag system will use xPlayer.getPermission() function
and labels for tags will be get by permission level not group, you have to have
older ESX to have this function, its deprecated in newer versions.

**Dependency**
- es_extended
