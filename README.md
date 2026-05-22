# UML Defender: Protect the Schema 🛸
![screenshot](https://github.com/TaquX/UML-Defender/blob/main/ScreenShots/start%20page.jpeg)

**UML Defender: Protect the Schema** is an interactive, fast-paced, space-invaders-style arcade game designed to test and improve object-oriented programming (OOP) and UML diagramming skills. Players defend a central class architecture from corrupted, mismatching attributes and methods while absorbing the correct ones to build a flawless system schema.

---

## 🎮 Gameplay & Mechanics
In **UML Defender**, you control the system's core blueprint (the yellow Class box at the bottom) and face a barrage of falling UML data packets. Your mission is to filter out the bugs and compile a perfect class.

![Gameplay Interface](https://github.com/TaquX/UML-Defender/blob/main/ScreenShots/gameplay.jpeg)

### 🔴 Red Packets (The Syntax Bugs)
* **What they are:** Invalid or non-matching attributes/methods (e.g., a `breed: String` property falling toward a `BankAccount` class).
* **Your Objective:** **SHOOT THEM!** You must destroy them before they pass the bottom boundary of the screen or collide with your ship.
* **Penalty:** If a red packet hits your class box or slips past the bottom of the screen, you lose one of your **3 Hearts (Lives)**.

### 🔵 Blue Packets (The Compiled Schema)
* **What they are:** Valid, correctly typed attributes and methods that belong to your active class (e.g., `+ deposit(amt): void` for a `BankAccount`).
* **Your Objective:** **COLLECT THEM!** Let them safely land into your class box to progress your schema compilation.

### 💰 Economy & Power-Ups
* **Gold Coins:** Earned by successfully destroying syntax bugs and completing levels.
* **The Shop:** Spend your hard-earned coins between levels to unlock powerful upgrades, improve your system stats, or buy devastating new weapons like the **PULSE** blaster to clear crowded waves.

---

## ⚙️ Difficulty Modes

Choose your mission parameters wisely. Adjusting the difficulty impacts your starting parameters and system stress thresholds:

| Difficulty | Starting Lives | Enemy Speed | Wave Size | Enemy Armor (Tankiness) |
| :--- | :---: | :---: | :---: | :---: |
| **Easy** | Higher | Slow | Small | Standard (1-Shot Kill) |
| **Normal** | 3 Hearts | Moderate | Balanced | Low Chance of Armored Enemies |
| **Hard** | Lower | Fast | Large | High Chance of Armored Enemies |
| **Insane** | Critical | Hyper | Endless | Heavy Armor Dominant |

--- 

![screenshot](https://github.com/TaquX/UML-Defender/blob/main/ScreenShots/paused%20form.jpeg)

---

## 🎮 Controls
← → / A D : Move Class Box Left/Right

SPACEBAR : Shoot Weapon
