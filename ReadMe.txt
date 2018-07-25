Haoran Chen
Unreal homework project.

You are trying to escape from the foe who is always trying to catch you and the all the traps in the scene, and try to collect as many balls as you can to extend your life in the game. The bomb is turned on when entering the small room, and is turned off when leaving it.

** You get 10 points when you collect the balls.
** You lose 5 points when you are on a trap. (Please try to walk through the trap.)
** You lose 10 points when you are caught by your foe.
** Your game will be over if your score is lower than 0 for 10 secs!!!
** Try to get 100 points!

There are 5 balls in the scene at maximum, if the ball is collected, or if it is not collected for 15 secs, the balls are destroyed and respawn back to 5 at a random location.

The blueprints I generated are located at: ..\EAE3010-Unreal-2\Haoran_Chen_Unreal2\Content\ThirdPersonBP\BPScript

## Collectable
This BP is for the collectable ball. It can be collected and destroyed in functions.

## Trap
This BP is for the traps. The player lose score when colliding on the trap.

## Foe
This BP is for the foe. It can always try to catch the player with the AI, and the player lose score when colliding with the foe.

## GameScene
This is the manager of the game. All the score gaining and losing, ball respawning, and timing for gaming over are all in this BP.

## Survive
This BP is for updating the time tick for tracking the gaming over. 

## PointLight
This BP is for the light controlling in the small room. When the player entering the room, the light is turned on and when the player leaves the room, the light is turned off.