---
world: The Forgotten Realms
campaign: The Forgotten Realms
status: active
role: player
system:
type: world
---
# The World of The Forgotten Realms

## Player Characters

-

## Sessions

*Put your cursor where the session link should be. Then, from the Command Palette (CMD/CTRL+P), select either QuickAdd: Macro - Add session-player or QuickAdd: Macro - Add session-gm*.




```dataview
table summary as "Summary" from "ttrpgs/The Forgotten Realms"
where contains(type,"session")
SORT sessionNum ASC
```


## Truths about the campaign/world

*Write down some facts about this campaign or the world that the characters find themselves in.*

- 


## Factions

```dataview
TABLE description as "Description" from "ttrpgs/The Forgotten Realms"
WHERE contains(lower(type),"faction")
```

## Custom rules

- [[Character options]]
- [[ttrpgs/The Forgotten Realms/House Rules|House Rules]]

## [[Safety Tools]]