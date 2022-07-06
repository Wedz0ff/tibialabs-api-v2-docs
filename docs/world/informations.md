---
sidebar_position: 1
---

# Informations

Display some informations about a specific world or all worlds.

`https://api.tibialabs.com/v2/worldinfo/WORLD_NAME`

`https://api.tibialabs.com/v2/worldinfo/online/WORLD_NAME`

`https://api.tibialabs.com/v2/worldinfo/online/all`

#### Example URLs

`https://api.tibialabs.com/v2/worldinfo/Belobra`

`https://api.tibialabs.com/v2/worldinfo/online/Belobra`

`https://api.tibialabs.com/v2/worldinfo/online/all`

#### Output

```
Belobra (Optional PvP) was created on 12/2016. Online record: 1050 on 05/2020. There are 506 players online.

There are 506 players online on Belobra.

There are currently 15949 players online on Tibia.
```

## Integration

### NightBot

```
!addcom !worldinfo $(urlfetch https://api.tibialabs.com/v2/worldinfo/$(querystring))
```

### StreamElements

```
!cmd add worldinfo $(customapi.https://api.tibialabs.com/v2/worldinfo/${queryescape ${1:}})
```
