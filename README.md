
## 3D Kingdom rush 

# Feature
This project is the clone game of [Kingdom Rush Vengence](https://www.youtube.com/watch?v=hTdWNCxofTc) (Ironhide Studio). The Kingdom Rush series is tower defense games, defending the borderline from rushing enemies. The basic rule of the clone is the same as the original. The difference is converted into 3D from 2D. All the units and skills are original.

Genre: RTS, TD, RPG

# Development:
Tools: C++, UE4
Period: 19.09 ~ 19.12
Team size: 1 (David Chun)

# About game rules:
A stage has several waves. For each wave, various enemies rush. A player can defend by building towers and controlling a hero to attack. If the last wave ends, the player wins. If an enemy crosses the borderline, the player gets damage depending on the enemy spec.

# This game includes functions:
logics: win/lose, enemy wave, gold earning, hero level-up, auto-combat, 
controls: hero move/attack, heroic skill, unit production, building tower, early wave call
algorithms: pathfinding, auto melee/ranged attack
math: quaternion, spline
UI: game status UI, hero status UI, skill UI, setting UI, tower building UI, tootips
IO: data load from the tables, save/load status

# Implementation features:
GameTag to call an object
GameAsset to avoid hard coding
Projectile tracking of the target
Materials and effects using graphical nodes
Behavior tree of units
Animation blending of upper/lower body animations