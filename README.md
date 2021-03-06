# SmashBreak
Smash Break is a casual, mobile game developed by me.

Smash Break is meant for iOS devices but it also runs on macOS and Windows PCs.

The lack of a license is **NOT** an oversight.

This repository is intended to showcase the coding behind my most recent project/game - **Smash Break**.

-------------------------------------------------------------------------------------------------------

**Smash Break**'s development started near the end of my "college life". The game was meant to be the project/game for my Thesis as well as a means to evaluate my skills as a Game Developer and more specifically, as a programmer. 

Being a "one man team" I decided to pick a game that seemed simple enough to create, a game so simple that I alone would be able to take care of all of its aspects (Audio, materials, scripts, animation, etc.), and so I picked 'Smash Hit" and decided to make my own version of it. 

Thus my game was to become a mobile 3D rail shooter game in which the player would always travel in a forward direction with the objective to reach the final level, which he would accomplish by destroying the objects found in his way with metal balls.

The game currently has 5 levels. New features, levels and obstacles are being planned upon for future implementation.
All in all the game performs as it was meant to perform, works on mobile phones (although it has not been tested on Android devices), works on PCs and the core gameplay resembles that of Smash Hit.

---------------------------------------------------------------------------------------------------------

**General descritpion of the Scripts**

-The **[Ball](https://github.com/PauloB04/SmashBreak/blob/master/Ball.cs)** script is attached to the player (Main Camera) and it essentially manages the whole player experience - The direction, strength and velocity of the balls, the "BallForce" feature as well as the Penalty management.

-The  **[AI](https://github.com/PauloB04/SmashBreak/blob/master/AI.cs)** takes care of the navigation system.

-The **[RobotScript](https://github.com/PauloB04/SmashBreak/blob/master/RobotScript.cs)** allows the Gamedev to freely move throughout the gameworld while in Playmode.

-The **[Coluna](https://github.com/PauloB04/SmashBreak/blob/master/Coluna.cs)** and **[MovingObstacle](https://github.com/PauloB04/SmashBreak/blob/master/MovingObstacle.cs)** are essentially the same, managing the movement of obstacles.

-The **[HitCrystals](https://github.com/PauloB04/SmashBreak/blob/master/HitCrystals.cs)** manages the allocation of points to the player.

-The **[PlayerSensor](https://github.com/PauloB04/SmashBreak/blob/master/PlayerSensor.cs)** is essentially the enemy AI, which activates certain obstacles only upon player proximity.

-The **[PointsScript](https://github.com/PauloB04/SmashBreak/blob/master/PointsScript.cs)** works together with the **Ball** to manage the Score and Penalty system.

-The rest is self explanatory.

---------------------------------------------------------------------------------------------------------

**The tools used in the creation of Smash Break**

Game Engine - **Unity**;

IDE - **Unity Monodevelop & Microsoft Visual Studio**;

Programming Language - **C#**;

Creation & modelling of objects: **Autodesk 3ds Max**;

iOS Deployment - **Xcode**;

Certain Game components - **Unity Asset Store**;

Others - **Youtube Tutorials and of course, Stack Overflow <3**

-----------------------------------------------------------------------------------------------------------

**A video of the game can be found [here](https://youtu.be/xWd_8ni4U-g).**

