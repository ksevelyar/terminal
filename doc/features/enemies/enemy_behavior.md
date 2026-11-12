# Enemy behavior

## Requirements
* Enemies patrol configured routes, wait at patrol points, and remain at spawn when no route is configured.
* Fighters detect continuously visible players after two seconds and gunners after four seconds.
* Visibility depends on an enemy's facing, range, and unobstructed line of sight.
* Losing sight before detection resets detection progress.
* Engaged enemies remain engaged after losing sight of the player.
* Enemies investigate audible gunshots and then resume patrol if they have not engaged the player.
* Louder gunshots can be heard from farther away and take priority over quieter or older sounds.
* Damaging an enemy immediately engages it with the player.
* Unalerted enemies do not attack players.
* Engaged gunners face the player.

## User scenarios
### 1. An enemy patrols when the player is not detected
### 2. An enemy cycles through its patrol points
### 3. An enemy waits between patrol points
### 4. An enemy with a default patrol stays at its spawn point
### 5. An enemy returns to patrol after reaching an investigated sound
### 6. A fighter detects a visible player after two seconds
### 7. A gunner detects a visible player after four seconds
### 8. A fighter does not detect a player outside its visibility cone
### 9. A fighter does not detect a player behind it
### 10. A gunner does not detect a player outside its visibility range
### 11. A wall blocks an enemy's visibility
### 12. Interrupted visibility resets an enemy's detection progress
### 13. An engaged enemy remains engaged after losing sight of the player
### 14. An audible gunshot starts an investigation
### 15. An inaudible gunshot does not interrupt patrol
### 16. A louder gunshot replaces the current investigation
### 17. A newer equally loud gunshot replaces the current investigation
### 18. Weapon loudness determines gunshot audibility
### 19. Damaging an enemy immediately engages it with the player
### 20. An engaged gunner turns toward the player
### 21. An unalerted enemy does not attack the player
