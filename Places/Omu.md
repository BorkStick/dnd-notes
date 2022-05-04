---
type: city
world: Forgotten Realms
campaign: Tomb of Annihilation
description: "The Forgotten City"
---

# Omu

```leaflet 
id: omu-map 
image: [[PlayerOmuMap.jpg]] 
height: 500px 
lat: 0 
long: 0 
minZoom: 6 
maxZoom: 10 
defaultZoom: 7 
unit: meters 
scale: 1 
```

## Places
```dataview
TABLE description as "Description"
WHERE type = "place" and contains(location,"Omu")
```

## Shops
```dataview
TABLE proprietor as "Proprietor"
WHERE type = "shop" and contains(location,"Omu")
```

## People
```dataview
TABLE description as "Description"
WHERE type = "NPC" and contains(location,"Omu")
```




### Shrines
frog
dropbear
snail 