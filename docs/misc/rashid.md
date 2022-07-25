---
sidebar_position: 3
---

# Rashid

Display the current city that Rashid is located.

`https://api.tibialabs.com/v2/rashid`

`https://api.tibialabs.com/v2/rashid/city`

#### Output

```
Today Rashid is located on Svargrond.

Svargrond
```

## Integration

### NightBot

```
!addcom !rashid $(urlfetch https://api.tibialabs.com/v2/rashid)
```

### StreamElements

```
!cmd add rashid $(customapi.https://api.tibialabs.com/v2/rashid)
```
