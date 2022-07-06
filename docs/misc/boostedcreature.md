---
sidebar_position: 1
---

# Boosted Creature

Display the current boosted creature.

`https://api.tibialabs.com/v2/boostedcreature`

`https://api.tibialabs.com/v2/boostedcreature/name`

#### Output

```
Today's boosted creature: Werewolf

Werewolf
```

## List

Alternatively, we provide an endpoint in JSON format containing all tracked boosted creatures so far.

`https://api.tibialabs.com/v2/boostedcreature/all`

#### Output

```json
{
  "data": [
    {
      "id": 1285,
      "name": "Werewolf",
      "date": "05/07/2022"
    },
    {
      "id": 1284,
      "name": "Orclops Doomhauler",
      "date": "04/07/2022"
    },
    {
      "id": 1283,
      "name": "Quara Hydromancer",
      "date": "03/07/2022"
    }
  ],
  "informations": {
    "api_version": 2,
    "timestamp": 1657063926441
  }
}
```

## Integration

### NightBot

```
!addcom !boostedcreature $(urlfetch https://api.tibialabs.com/v2/boostedcreature)
```

### StreamElements

```
!cmd add boostedcreature $(customapi.https://api.tibialabs.com/v2/boostedcreature)
```
