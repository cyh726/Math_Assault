# Math Assault
## Architecture
```graphviz 
digraph graphname{
Menu_Scene -> Background_Canvas;
Menu_Scene -> Main_Canvas;
Menu_Scene -> Level_Canvas;
Menu_Scene -> View_Canvas;
Level_Canvas -> Easy;
Level_Canvas -> Normal;
Level_Canvas -> Hard;
View_Canvas -> First_Person;
View_Canvas -> Third_Person;
Main_Canvas -> Start;
Main_Canvas -> Level;
Main_Canvas -> View;
Main_Canvas -> Quit;
}
```
```graphviz 
digraph graphname{
Game_Scene -> Shooting_Canvas;
Game_Scene -> Question_Canvas;
Game_Scene -> Game_Over_Canvas;
Game_Scene -> Player;
Game_Scene -> Environment;
}
```
## Menu Scene
### Main Canvas
![](https://i.imgur.com/tbgzFi0.png =40%x)

### Level Canvas
![](https://i.imgur.com/yndNfvI.png =40%x)

### View Canvas
![](https://i.imgur.com/yKo5nhR.png =40%x)
* First Person View
![](https://i.imgur.com/AVI0O4z.png =40%x)
* Third Person View
![](https://i.imgur.com/0vhKk3T.png =40%x)

## Game Scene

### Shooting Canvas
![](https://i.imgur.com/SUVk7tA.png =40%x)

### Question Canvas
![](https://i.imgur.com/nd21PhQ.png =40%x)

### Game Over Canvas
![](https://i.imgur.com/HreNhcN.png =40%x)

## Contents
### Role
![](https://i.imgur.com/PiM1CLx.png =40%x)
### Enemy
![](https://i.imgur.com/ttvPWG2.png =40%x)
### Random Map
![](https://i.imgur.com/CxgpP6j.png =40%x)
### Bullet Shooting
![](https://i.imgur.com/uY5kZlO.png =40%x)
### Skill 1: Special Shooting
![](https://i.imgur.com/HU1OfjB.png =40%x)
### Skill 2: Special Shooting
![](https://i.imgur.com/aolCakF.png =40%x)
### Enemy Shooting
![](https://i.imgur.com/B8XkV5r.png =40%x)
### Skill Enhancement Items
![](https://i.imgur.com/pC4ebtS.png =40%x)

## How To Play
1. Role moving: W A S D or Arrow keys
2. The direction the character is facing: Move mouse
3. Bullet shooting: Click left mouse
4. Skill 1: Special Shooting: Q key
5. Skill 2: Special Shooting: E key and hold down the left mouse button 
* The total number of bullets is 3 and will be replenished over time; the total number of lives is 5 and will be replenished over time.
* When shooting to the chariot, a math problem will appear. A math question must be completed within a certain period of time. If the answer is correct, the chariot will disappear. In contrast, if the answer is wrong, it will not disappear. Besides, the faster you answer, the higher your score will be.
* When the total life is 0, the game will be over.