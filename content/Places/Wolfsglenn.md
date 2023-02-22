---
aliases: 
tags: places
---

## General Information


## Map of Wolfsglenn

```leaflet
id: wolfsglenn-map
image: [[Pasted image 20221213194521.png]]
bounds: 
    - [0,0]
    - [157, 228]
lat: 78
long: 114
minZoom: 1
maxZoom: 10
defaultZoom: 1.5
zoomDelta: 0.5
```



![[Pasted image 20221216195930.png]]

## Places and Shops

```dataview
TABLE WITHOUT ID
  file.link AS "Shops and Places",
  type AS "Type of Shop"
FROM #Wolfsglenn AND #shops 
```

## People

```dataview
TABLE WITHOUT ID
  file.link AS "People",
  role AS "Function"
FROM #Wolfsglenn  AND #NPCs 
```

