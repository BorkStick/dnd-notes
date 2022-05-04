---
type: city
world: Forgotten Realms
campaign: Tomb of Annihilation
description:
---

# Port Nyanzaru

```leaflet 
id: port-nyanzaru-map 
image: [[Port_Nyanzaru.jpg]] 
height: 500px 
lat: 0 
long: 0 
minZoom: 6 
maxZoom: 10 
defaultZoom: 8 
unit: meters 
scale: 1 
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