---
title: Homepage
description: Homepage
tags: 
 - home
 - index
publish: true
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