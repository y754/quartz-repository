---
title: Homepage
description: Session & lore notes for our D&D campaigns!
tags: 
 - home
 - index
publish: true
---
# Campaigns
## Chains of Asmodeus 
- [[Chains of Asmodeus/index|Campaign summary]]
## Into the Void
- [[Into the Void/index|Campaign summary]]
## Season of Ghosts
- [[Season of Ghosts/index|Campaign summary]]
## City of Doors
- [[City of Doors/index|Campaign summary]]

# Mini-campaigns
## Feywild Friday
## Weddingquest

> [!caption|text-center clean wfull]
>>```dataview
>>TABLE WITHOUT ID file.link AS "Session", date AS "Date"
>>FROM "01 - Session Notes" AND #complete
>>```

> [!caption|text-center clean wfull]
>>```dataview
>>TABLE WITHOUT ID file.link AS "Upcoming", date AS "Date"
>>FROM "01 - Session Notes" AND !#index AND !#complete
>>```

# Player Characters
```dataview
LIST FROM "02 - Lore/2.1 - Characters/2.1.1 - Player Characters" AND !#index
```

# Lore
```dataview
LIST FROM "02 - Lore" AND !#index AND !#npc AND !#player-character
```

# NPCs
```dataview
LIST FROM "02 - Lore/2.1 - Characters/2.1.2 - NPCs" AND !#index
```

# To Do
![[To Do]]