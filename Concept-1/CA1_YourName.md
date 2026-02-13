# CS2053 - Concept Assignment 1
## Luke Garnett

---

**1**:
While player lives > 0

input dir d = input value of left right or nothing by default

while ball b is on screen
  update player postition with d
  if player collides with ball b
    calculate angle and deflect ball
  if ball collides with block x
    destroy block and bounce ball
    have a chance for each broken block to drop powers
  have ball b collide with walls and bounce off
  if ball collides with enemy e
    destroy the enemy
loop ends when ball goes offscreen
lose a life when ball goes off screen
reset the player position but keep destroyed blocks
if lives s = 0 
  game over screen

end

**2-a**:
Ready is called once when the node first enters the scene tree and is fully initialized 

process(delta) is called every rendered frame, this can vary from machine to machine due to hardware. 

physics process runs at a constant rate typicaly 60 times per second

**2-b**:
Answer here
ready allows initial values to be set like base amounts for lives and stats like speed or health.

process is for updating things every rendered frame like graphics, camera movement, essentially any non physics based logic

physics process allows for consistent movement that wont vary from machine to machine or have issues when framerate dips
**2-c**:
Answer here
ready is just triggered once, unless remove the node and add it again

process runs every frame, so we can only directly affect with max fps caps or pausing it for a specific node 

physics process is a set rate we can pick in project settings
**3**:
Answer here

**4**:
Answer here

**5-a**:
Answer here

**5-b**:
Answer here

**6**:
Answer here

**7-a**:
Answer here

**7-b**:
Answer here

**8-a**:
Answer here

**8-b**:
Answer here

**8-c**:
Answer here

**8-d**:
Answer here

**9**:
Answer here

**10**:
Answer here


---
