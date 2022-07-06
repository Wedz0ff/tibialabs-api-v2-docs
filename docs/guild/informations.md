---
sidebar_position: 1
---

# Informations

Display some informations about a specific guild.

`https://api.tibialabs.com/v2/guildinfo/GUILD_NAME`

#### Example URL

`https://api.tibialabs.com/v2/guildinfo/Rangers`

#### Output

```
Rangers (World: Belobra - Avg Level: 967) has 7/173 members online right now. This guild was founded on 04/11/2019.
```

## Integration

### NightBot

```
!addcom !guildinfo $(urlfetch https://api.tibialabs.com/v2/guildinfo/$(querystring))
```

### StreamElements

```
!cmd add guildinfo $(customapi.https://api.tibialabs.com/v2/guildinfo/${queryescape ${1:}})
```
