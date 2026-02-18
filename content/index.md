---
title: Index
description: Homepage
tags: 
 - home
 - index
publish: true
title: index
created: 1970-01-01T01:00:00.000+01:00
modified: 2026-02-05T18:00:28.000+00:00
published: 2026-02-05T18:00:28.000+00:00
cssclasses: ""
---
> [!caption|center text-center clean c-p-med]
>>```dataview
>>TABLE WITHOUT ID file.link AS "Session", date AS "Date"
>>FROM "01 - Session Notes" AND #complete
>>```

> [!caption|center text-center clean c-p-med]
>>```dataview
>>TABLE WITHOUT ID file.link AS "Upcoming", date AS "Date"
>>FROM "01 - Session Notes" AND !#index AND !#complete
>>```

# Player Characters
```dataview
LIST FROM "02 - Lore/2.1 - Characters/2.1.1 - Player Characters" AND !#index
```


- [ ] factions
	- [ ] mercykillers
	- [ ] harmonium
	- [ ] senate & courts
	- [ ] cult
- [ ] sigil
	- [ ] wards
	- [ ] merchants
- [ ] npcs
- [ ] player characters
- [ ] timeline