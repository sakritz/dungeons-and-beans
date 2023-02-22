
```dataview
TABLE WITHOUT ID
  file.link AS "Spell",
  school-of-magic AS "School of Magic",
  level AS "Level",
  type-of-spell AS "Type of Spell"
FROM #spell 
SORT level
```


## Cantrips

```dataview
TABLE WITHOUT ID
  file.link AS "Spell",
  school-of-magic AS "School of Magic",
  type-of-spell AS "Type of Spell",
  casting-time AS "Casting Time",
  save AS "Save"
FROM #spell 
WHERE level="Cantrip"
```

## Level 1

```dataview
TABLE WITHOUT ID
  file.link AS "Spell",
  type-of-spell AS "Type of Spell",
  casting-time AS "Casting Time", 
  ritual AS "Ritual",
  concentration AS "Concentration", 
  save AS "Save"
FROM #spell 
WHERE level=1
SORT type-of-spell
```

## Level 2

```dataview
TABLE WITHOUT ID
  file.link AS "Spell",
  type-of-spell AS "Type of Spell",
  casting-time AS "Casting Time", 
  ritual AS "Ritual",
  concentration AS "Concentration",
  save AS "Save"
FROM #spell 
WHERE level=2
SORT type-of-spell
```

## Level 3

```dataview
TABLE WITHOUT ID
  file.link AS "Spell",
  type-of-spell AS "Type of Spell",
  casting-time AS "Casting Time", 
  ritual AS "Ritual",
  concentration AS "Concentration",
  save AS "Save"
FROM #spell 
WHERE level=3
SORT type-of-spell
```



