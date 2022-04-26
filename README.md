
## 3D Kingdom rush 

# Feature
This project is the clone game of [Kingdom Rush Vengence](https://www.youtube.com/watch?v=hTdWNCxofTc) (Ironhide Studio). The Kingdom Rush series is tower defense games, defending the borderline from rushing enemies. The basic rule of the clone is the same as the original. The difference is converted into 3D from 2D. All the units and skills are original. <br/>

Genre: RTS, TD, RPG <br/>

# Development:
- Tools: C++, UE4 <br/>
- Period: 19.09 ~ 19.12 <br/>
- Team size: 1 (David Chun) <br/>

# About the game rules:
- A stage has several waves. For each wave, various enemies rush. <br/>
- A player can defend by building towers and controlling a hero to attack. <br/>
- If the last wave ends, the player wins. <br/>
- If an enemy crosses the borderline, the player gets damage depending on the enemy health. <br/>

# This game includes functions:
- logics: win/lose, enemy wave, gold earning, hero level-up, auto-combat <br/>
- controls: hero move/attack, heroic skill, unit production, building tower, early wave call <br/>
- algorithms: pathfinding, auto melee/ranged attack <br/>
- math: quaternion, spline <br/>
- UI: game status UI, hero status UI, skill UI, setting UI, tower building UI, tootips <br/>
- IO: data load from the tables, save/load status <br/>

# Implementation features:
- `GameTag` to call an object <br/>
- `GameAsset` to avoid hard coding <br/>
- Projectile tracking of the target <br/>
- Materials and effects using graphical nodes <br/>
- Animation blending of upper/lower body animations <br/>