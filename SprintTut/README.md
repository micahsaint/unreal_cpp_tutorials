Character Sprinting
===================

In this project we give the default Unreal Engine third person character the
ability to sprint.  
  
[Youtube Video](https://www.youtube.com/watch?v=yyelCzlIWsM)



### Files Changed


#### [SprintTutCharacter.h](Source/SprintTut/SprintTutCharacter.h)

In this file we create a new class variable `float SprintSpeedMultiplier` and
define two new method templates `void Sprint()` and `void StopSprinting()`


#### [SprintTutCharacter.cpp](Source/SprintTut/SprintTutCharacter.cpp)

Here we set the SprintSpeedMultiplier value in the constructor, implement the
`void Sprint` and `void StopSprinting` methods and add two new event listeners
for "Sprint" key pressed and key released.
