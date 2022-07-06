---
sidebar_position: 3
---

# Shared Level

Display the level range that a specific level can share experience.

`https://api.tibialabs.com/v2/sharelevel/TARGET_LEVEL`

#### Example URL

`https://api.tibialabs.com/v2/sharelevel/623`

#### Output

```
A level 623 can share experience with levels 415 to 935.
```

## Integration

### NightBot

```
!addcom !sharelevel $(urlfetch https://api.tibialabs.com/v2/sharelevel/$(querystring))
```

### StreamElements

```
!cmd add sharelevel $(customapi.https://api.tibialabs.com/v2/sharelevel/${queryescape ${1:}})
```
