---
sidebar_position: 2
---

# Boosted Boss

Display the current boosted boss.

`https://api.tibialabs.com/v2/boostedboss`

`https://api.tibialabs.com/v2/boostedboss/name`

#### Output

```
Today's boosted boss: Drume

Drume
```

## List

Alternatively, we provide an endpoint in JSON format containing all tracked boosted bosses so far.

`https://api.tibialabs.com/v2/boostedboss/list`

#### Output

```json
{
  "data": [
    {
      "id": 9,
      "name": "Timira The Many-Headed",
      "date": "04/07/2022",
      "created_at": 1656942099
    },
    {
      "id": 8,
      "name": "Ravenous Hunger",
      "date": "02/07/2022",
      "created_at": 1656763961
    },
    {
      "id": 7,
      "name": "Duke Krule",
      "date": "01/07/2022",
      "created_at": 1656689492
    },
    {
      "id": 6,
      "name": "Scarlett Etzel",
      "date": "30/06/2022",
      "created_at": 1656597257
    },
    {
      "id": 5,
      "name": "Drume",
      "date": "29/06/2022",
      "created_at": 1656515205
    },
    {
      "id": 4,
      "name": "Tentugly",
      "date": "28/06/2022",
      "created_at": 1656421984
    },
    {
      "id": 3,
      "name": "Magma Bubble",
      "date": "27/06/2022",
      "created_at": 1656335450
    },
    {
      "id": 2,
      "name": "Timira The Many-Headed",
      "date": "26/06/2022",
      "created_at": 1656249242
    },
    {
      "id": 1,
      "name": "The Sinister Hermit",
      "date": "25/06/2022",
      "created_at": 1656213945
    }
  ],
  "informations": {
    "api_version": 2,
    "timestamp": 1657064462630
  }
}
```

## Integration

### NightBot

```
!addcom !boostedboss $(urlfetch https://api.tibialabs.com/v2/boostedboss)
```

### StreamElements

```
!cmd add boostedboss $(customapi.https://api.tibialabs.com/v2/boostedboss)
```
