# 🕹️ Hunter Assassin

Hunter Assassin is a stealth-based action game developed in Unity, inspired by mobile games where players tactically eliminate enemies while avoiding detection. This project focuses on enemy AI, pathfinding, state machines, and stealth mechanics within a confined level design.

---

## 🎯 Features

- 👣 **Enemy Patrol AI**: Enemies follow patrol routes and react to player proximity.
- 🔍 **Line of Sight Detection**: Enemies detect players using Nav mesh agent for stealth gameplay.
- 🧠 **Finite State Machines**: Enemies use FSM for clean behavior transitions.
- 🗺️ **Level-based Design**: Multiple levels with increasing difficulty and unique layouts.
- 🕹️ **Player Controls**: WASD keys for movement & spacebar for attacks.
- 🎨 **Simple UI**: Displays player health, level progress, and enemy count.

---

## 🔁 Design Patterns & Principles Used

| Pattern/Principle          | Usage                                                       |
|----------------------------|-------------------------------------------------------------|
| **State Pattern**          | For enemy and player behavior management                    |
| **Separation of Concerns** | Modular scripts for AI, player input, UI, and level control |
| **DRY Principle**          | Reusable methods for detection and movement                 |

---

## 📷 Gameplay Video

