# 🧩 Mystic Cube Match

**Playable – In Development | Unity & C# | Puzzle Systems & Level Tooling**

Mystic Cube Match is a playable puzzle game currently in development with Unity and C#.

The game uses a target-pool based matching mechanic where the player selects cubes while managing limited slots and completing active target sets.

---

## 🎮 Gameplay

The core gameplay revolves around selecting cubes and completing target pools with matching sets.

**select cube → evaluate target → complete matching set → clear**

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 053219" src="https://github.com/user-attachments/assets/eee9ddd7-7805-4bae-a5f7-221ba2a3c874" />

---

## 🎯 Core Gameplay

Players interact with available cubes while trying to complete active target pools.

Incorrect selections occupy the limited bottom slots, so the player must manage both target progress and slot capacity.

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 053313" src="https://github.com/user-attachments/assets/e6bced34-aca9-4bd6-885f-335af87b7a07" />


---

## 🔒 Special Mechanics

Mystic Cube Match includes modular special mechanics that can be enabled independently or combined in the same level.

### Seal / Lock
Cubes can be hidden behind colored seals.  
The required matching target must be completed before the hidden cube becomes available.

### Chain
Some cubes are affected by neighboring connections and positional rules.

### Decoy / Bait
Decoy elements introduce additional decision-making without changing the core matching rules.

<img width="600" height="1000" alt="Ekran görüntüsü 2026-10-13 053335" src="https://github.com/user-attachments/assets/0a414909-4cb8-4fc2-bc98-e48ebd1dda14" />


---

## 🛠️ Level Authoring Tools

A custom Unity editor workflow is used to create, test, validate, and publish playable levels.

Current workflow:

**Generate → Play Test → Save Snapshot → Approve to Published**

The tooling is designed to support both normal levels and levels containing optional special mechanics.

<img width="800" height="1200" alt="Ekran görüntüsü 2026-10-13 053414" src="https://github.com/user-attachments/assets/1d24ebff-e196-4a5f-be57-ce613b20fb2c" />


---

## 🧠 Solver-Aware Generation

Generated levels are checked against the active gameplay rules so enabled mechanics remain compatible with solvable level states.

The generation system takes special mechanics into account rather than treating them only as visual modifiers.

---

## ⚙️ Core Systems

- Target-pool based puzzle gameplay
- Limited slot management
- Modular special mechanics
- Seal / Lock system
- Chain system
- Decoy / Bait system
- Custom Unity level editor
- Procedural level generation
- Play-test and snapshot workflow
- Published level pool
- Solver-aware level validation
- Data-driven gameplay configuration

---

## 🧱 Tech Stack

- Unity
- C#
- ScriptableObjects
- Custom Unity Editor Tools
- Git / GitHub
- Unity UI / TextMeshPro

---

## 📱 Project Status

**Playable – In Development**

The core gameplay loop, special mechanics, and level-authoring workflow are currently playable and actively being developed.

The mobile release version is not yet prepared.

The full production source code is kept private.  
This repository showcases the game's gameplay systems and development tools for portfolio purposes.
