---
description: Learn how to create a scoreboard with Skript.
---

# Example: Scoreboard

## OVERVIEW 

Scoreboards are useful tools that can provide players with useful information such as their balance, rank and many more things.

## CODE

### SKRAYFALL SCOREBOARD 
```
on join:
    set name of sidebar of player to "&6skRayFall"
    set score "First Line" in sidebar of player to 1
    set score "Second Line" in sidebar of player to 2
```

### SKBEE SCOREBOARD 
```
on join:
    set title of player's scoreboard to "&6&lServer Info"
    set line 1 of player's scoreboard to "&7• &eOnline: &f%size of all players%" 
```
