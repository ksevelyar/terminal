# Enemies

## Requirements
* Players and enemies can damage and kill each other.
* Fighter and gunner deaths drop their weapons and stop their attack animations.
* A killed moving fighter keeps its momentum.
* Shots to an enemy's head and hand can kill it.
* A killed enemy starts falling from its current pose.
* A gunner has one visible hairstyle.
* A dead player's camera follows their fallen head.
* A gunner's body follows its animation without visible self-intersection.

## User scenarios
### 1. A player damages a fighter on the first hit and kills it on the second
### 2. A fighter damages a player on the first hit and kills them on the second
### 3. A killed fighter drops its weapon
### 4. A killed gunner drops its weapon
### 5. A killed fighter stops its attack animation
### 6. A killed gunner stops its attack animation
### 7. A fighter killed while running keeps its momentum
### 8. A gunner falls from its attack pose when the player kills it
### 9. A head shot kills a fighter
### 10. A head shot kills a gunner
### 11. A gunner loads one hairstyle
### 12. A hand shot kills a fighter
### 13. A hand shot kills a gunner
### 14. A gunner's ragdoll colliders do not overlap
### 15. A gunner's ragdoll colliders follow its animation
### 16. A gunner kills the player and the camera falls with the player's head
### 17. A fighter kills the player in melee and the camera falls with the player's head
