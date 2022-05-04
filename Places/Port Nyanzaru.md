---
type: city
world: Forgotten Realms
campaign: Tomb of Annihilation
description:
---

# Port Nyanzaru
```leaflet 
id: leaflet-map image: [[Image.jpg]] height: 500px lat: 50 long: 50 minZoom: 1 maxZoom: 10 defaultZoom: 5 unit: meters scale: 1 marker: default, 39.983334, -82.983330, [[Note]] darkMode: true 
```


## Places
```dataview
TABLE description as "Description"
WHERE type = "place" and contains(location,"Port Nyanzaru")
```

## Shops
```dataview
TABLE proprietor as "Proprietor"
WHERE type = "shop" and contains(location,"Port Nyanzaru")
```

## People
```dataview
TABLE description as "Description"
WHERE type = "NPC" and contains(location,"Port Nyanzaru")
```