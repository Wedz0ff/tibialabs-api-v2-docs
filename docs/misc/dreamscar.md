---
sidebar_position: 2
---

# Dream Scar Boss

Display the current Dream Scar Boss on most Tibian Worlds according to [TibiaWiki](https://tibia.fandom.com/wiki/Dream_Scar/Boss_of_the_Day).

`https://api.tibialabs.com/v2/dreamscar`

`https://api.tibialabs.com/v2/dreamscar/name`

#### Output

```
Today's Dream Scar Boss should be Maxxenius on most worlds.

Maxxenius
```

## Integration

### NightBot

```
!addcom !dreamscar $(urlfetch https://api.tibialabs.com/v2/dreamscar)
```

### StreamElements

```
!cmd add dreamscar $(customapi.https://api.tibialabs.com/v2/dreamscar)
```
