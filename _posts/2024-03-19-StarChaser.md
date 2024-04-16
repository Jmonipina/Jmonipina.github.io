---
layout: post
title: Star Chaser
subtitle: Galaga clone game
cover-img: /assets/img/Starchaser.png
tags: [Unity, 2D]
author: Javier
---

<img src="/assets/img/Unity%20Galaga%20Clone.gif" width="320" height="620"/>
#### Things learned:
* Simple AI moving patterns in Unity.
* Spawning new enemies through instantiating a prefab object.
* Creating prefabs of objects to later manipulate said objects.
* Using the audio system in Unity to play sound effects and background music.
* Creating parallax scrolling background effect using Unity. 

## Post-course changes
After the course had ended, I decided to expand on the project to learn different applications of features that were not implemented during the course.
A Data Persistence Manager has been implemented to manage a Save and Load system. The system will save the data into an encrypted json file.

The current model saves the current score and the position of the player when the application ends.
The game loads the data once the user presses the "Continue" button in the main menu.


Later to be implemented:
* Save the player's health and carry it to a new scene.
* Save the player's progress once a level has been completed.
* Multiple different levels.
* Creating powerups for the player to use.

## Placeholder code block
```c#
var foo = function(x) {
  return(x + 5);
}
foo(3)
```
