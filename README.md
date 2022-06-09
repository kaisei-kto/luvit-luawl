# <b>[luawl](https://luawl.com)</b>, also known as <b>luaGuard</b>

<center><a href="https://discord.gg/w7ubyMZyyw"><img src="https://img.shields.io/discord/917573858461102080?color=5865F2&logo=discord&logoColor=white" alt="Discord Server"/></a></center>

```
lit install kaisei-kto/luvit-luawl
```

## Example
```lua
local luawl = require('luvit-luawl')

luawl:set_luawl_key('API_TOKEN')

table.foreach(luawl:get_whitelist('luawl'), print)
```
