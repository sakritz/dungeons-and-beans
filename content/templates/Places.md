---
title: "{{title}}"
aliases: 
tags: places
---


## General Information
-  

## Map
{insert image}

## Places and Shops

```dataview
TABLE WITHOUT ID
  file.link AS "Shops and Places",
  type AS "Type of Shop"
FROM #city AND #shops 
```

## People

```dataview
TABLE WITHOUT ID
  file.link AS "People",
  role AS "Function"
FROM #city AND #NPCs 
```