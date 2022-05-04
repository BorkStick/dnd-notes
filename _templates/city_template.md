---
type: city
world: Forgotten Realms
campaign: Tomb of Annihilation
description:
---

# {{title}}

## Places
```dataview
TABLE description as "Description"
WHERE type = "place" and contains(location,"{{title}}")
```

## Shops
```dataview
TABLE proprietor as "Proprietor"
WHERE type = "shop" and contains(location,"{{title}}")
```

## People
```dataview
TABLE description as "Description"
WHERE type = "NPC" and contains(location,"{{title}}")
```