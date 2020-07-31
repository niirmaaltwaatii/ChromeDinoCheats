## _How to play Dino Game on chrome_
* _Type **Chrome://dino** in URL bar & press Enter_
* Press Spacebar to start game
* Use up & down(_space_) keys

# _Google Chrome Dino game Cheats/Hacks_

## Speed
**_Runner.instance_.setSpeed(100)_** (Set Speed to 100)

## Immortality
**var original = Runner.prototype.gameOver** (Save orignal gameOver function) <br/>
**_Runner.prototype.gameOver = function(){ }_** (make it do nothing when gameOver)

## Stop Game Immortality
**Runner.prototype.gameOver = original** (Set gameOver to default)

## Current score
**Runner.instance_.distanceRan = 12345 / Runner.instance_.distanceMeter.config.COEFFICIENT**
(set currentScore to 12345)

## Jump Velocity
**Runner.instance_.tRex.setJumpVelocity(30)** (set JumpVelocity to 30)
