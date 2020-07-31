# Google Chrome Dino game Cheats/Hacks

## Speed
Runner.instance_.setSpeed(100) /* Set Speed to 100*/

## Immortality
var original = Runner.prototype.gameOver /* Save orignal gameOver function */
Runner.prototype.gameOver = function(){} /* make it do nothing when gameOver */

## Stop Game Immortality
Runner.prototype.gameOver = original /* Set gameOver to default */

## Current score
Runner.instance_.distanceRan = 12345 / Runner.instance_.distanceMeter.config.COEFFICIENT
/* set currentScore to 12345 */

## Jump Velocity
Runner.instance_.tRex.setJumpVelocity(30) /* set JumpVelocity to 30 */
