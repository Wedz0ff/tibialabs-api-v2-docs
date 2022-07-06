---
sidebar_position: 2
---

# Party Tracker

Display a summary information about a group of characters.

`https://api.tibialabs.com/v2/partytracker/CHARACTER_NAME/CHARACTER_NAME/...`

#### Example URL

`https://api.tibialabs.com/v2/partytracker/Punbel/Highlord Baby/Minuttz/Wedzy`

#### Output

```
EK: Punbel (Level: 1987) - ED: Highlord Baby (Level: 1617) - RP: Minuttz (Level: 1699) - MS: Wedzy (Level: 1995)
```

## Integration

### NightBot

```
!addcom !myparty $(urlfetch https://api.tibialabs.com/v2/partytracker/Punbel/Highlord Baby/Minuttz/Wedzy)
```

### StreamElements

```
!cmd add myparty $(customapi.https://api.tibialabs.com/v2/partytracker/Punbel/Highlord Baby/Minuttz/Wedzy)
```
