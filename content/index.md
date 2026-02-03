---
publish: true
title: Homepage
description: Homepage
created: 1970-01-01T01:00:00.000+01:00
modified: 2026-02-03T18:35:13.607+00:00
tags:
  - home
  - index
cssclasses: ""
---
>[!column|2 clean no-t]
>> ```dataview
>> TABLE WITHOUT ID file.link AS "Session", date AS "Date"
>> FROM "01 - Session Notes" AND #complete
>> ```
>
>> ```dataview
>> TABLE WITHOUT ID file.link AS "Upcoming", date AS "Date"
>> FROM "01 - Session Notes" AND !#index AND !#complete
>> ```
# Player Characters
- [[02 - Lore/2.1 - Characters/2.1.1 - Player Characters/Pandemonium\|Pandemonium]]
- [[02 - Lore/2.1 - Characters/2.1.1 - Player Characters/Malachi\|Malachi]]
- [[02 - Lore/2.1 - Characters/2.1.1 - Player Characters/Fugue\|Fugue]]
- [[02 - Lore/2.1 - Characters/2.1.1 - Player Characters/Fletcher\|Fletcher]]


# Lore
- [[02 - Lore/2.4 Items/Cube\|Cube]]
- [[02 - Lore/2.3 Luden's Rest/Diver's Guild\|Diver's Guild]]
- [[02 - Lore/2.3 Luden's Rest/Apothecary's Guild\|Apothecary's Guild]]
- [[02 - Lore/2.2 The Void/Void Matter\|Void Matter]]
- [[02 - Lore/2.2 The Void/Levels\|Levels]]


# NPCs
```dataview
LIST FROM "02 - Lore/2.1 - Characters/2.1.2 - NPCs" AND !#index
```

# To Do
![[To Do]]