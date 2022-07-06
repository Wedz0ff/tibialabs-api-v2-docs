---
sidebar_position: 1
---

# Informations

Display some informations about a specific character.

`https://api.tibialabs.com/v2/charinfo/CHARACTER_NAME`

#### Example URL

`https://api.tibialabs.com/v2/charinfo/wedzy`

#### Output

```
Character: Wedzy - Level: 1995 - Vocation: Master Sorcerer - World: Belobra - HP: 10120 - MP: 59700 - Cap: 20340
```

## Integration

### NightBot

```
!addcom !charinfo $(urlfetch https://api.tibialabs.com/v2/charinfo/$(querystring))
```

### StreamElements

```
!cmd add charinfo $(customapi.https://api.tibialabs.com/v2/charinfo/${queryescape ${1:}})
```
