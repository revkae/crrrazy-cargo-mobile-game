# 🚗 CrrrazzyCar-Go

<p align="center">
  <img width="682" height="556" alt="Crrazycargologo" src="https://github.com/user-attachments/assets/1908833d-31d0-4e11-8482-07f7a7e7bd40" />
</p>

<p align="center">
  <img alt="Unity" src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white"/>
  <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img alt="Mobile" src="https://img.shields.io/badge/Mobile-Android%20%7C%20iOS-green?style=for-the-badge"/>
</p>

<p align="center">
  <b>An arcade-style delivery racing game where you drive through endless procedurally generated roads, collect packages, and deliver them to post offices for cash!</b>
</p>

> 🎮 **This project was developed by the OGAT team as a collaborative practice project to improve our Unity game development skills.**

---

## 🎬 Demo

<p align="center">
  <img src="https://via.placeholder.com/600x300?text=Gameplay+GIF" alt="Gameplay GIF"/>
</p>

---

## 🕹️ Gameplay

| Feature | Description |
|---------|-------------|
| 🛣️ **Endless Racing** | Navigate through procedurally generated roads that scale in difficulty |
| 📦 **Delivery Mechanic** | Collect packages on the road and deliver them to post offices to earn money |
| ⚠️ **Dodge Hazards** | Avoid airstrikes, barriers, pedestrians, and NPC traffic |
| 🔓 **Unlock & Upgrade** | Earn money to unlock new cars and upgrade their stats |

---

## ✨ Features

### 🚙 Multiple Cars
Each vehicle comes with unique stats, handling characteristics, and special abilities.

### ⬆️ Car Upgrades
- **Resistivity** - Take more hits before destruction
- **Drop Chance** - Higher chance for package spawns
- **Money Multiplier** - Earn more cash per delivery

### 💥 Special Skills
<p align="left">
  <img src="https://img.shields.io/badge/Dash-⚡-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/Shield-🛡️-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Ram-💪-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/Jump-🦘-green?style=flat-square"/>
</p>

### 📈 Dynamic Difficulty
Roads progress from **Easy** → **Normal** → **Hard** as you advance

### 🎯 Game Modes
- **Race Mode** - Pure speed challenge
- **Police Chase** - Escape the cops
- **Delivery Mode** - Maximize your deliveries

### 🛤️ Road Variants
- 2-Lane layouts for tight maneuvering
- 3-Lane layouts for more strategic play

---

## 📸 Screenshots

<p align="center">
  <img src="https://via.placeholder.com/250x450?text=Main+Menu" alt="Main Menu" width="200"/>
  <img src="https://via.placeholder.com/250x450?text=Gameplay+1" alt="Gameplay 1" width="200"/>
  <img src="https://via.placeholder.com/250x450?text=Gameplay+2" alt="Gameplay 2" width="200"/>
  <img src="https://via.placeholder.com/250x450?text=Car+Select" alt="Car Select" width="200"/>
</p>

<p align="center">
  <img src="https://via.placeholder.com/250x450?text=Upgrade+Shop" alt="Upgrade Shop" width="200"/>
  <img src="https://via.placeholder.com/250x450?text=Game+Over" alt="Game Over" width="200"/>
  <img src="https://via.placeholder.com/250x450?text=Delivery+Mode" alt="Delivery Mode" width="200"/>
  <img src="https://via.placeholder.com/250x450?text=Police+Chase" alt="Police Chase" width="200"/>
</p>

---

## 🛠️ Tech Stack

<p align="left">
  <img alt="Unity" src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white"/>
  <img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white"/>
</p>

### Architecture & Patterns

| Pattern | Usage |
|---------|-------|
| **Event-Driven** | Decoupled game systems communication |
| **ScriptableObjects** | Data-driven car configs, road settings, upgrade values |
| **Singleton** | Game managers (Audio, Score, Game State) |
| **Object Pooling** | Efficient spawning of roads, obstacles, packages |
| **Addon/Plugin System** | Modular car abilities and upgrades |

---

## 🎮 Controls

| Input | Action |
|-------|--------|
| ← Swipe Left | Steer left |
| → Swipe Right | Steer right |
| 🔘 Skill Button | Activate special ability |
| 🚗 Auto | Progressive speed increase |

---

## 🏗️ Project Structure

```
Assets/
├── Scripts/
│   ├── Car/              # Vehicle controllers & stats
│   ├── Road/             # Procedural generation
│   ├── Hazards/          # Obstacles & enemies
│   ├── Delivery/         # Package & post office logic
│   ├── Skills/           # Special abilities
│   ├── UI/               # Menus & HUD
│   └── Managers/         # Game state & systems
├── Prefabs/
│   ├── Cars/
│   ├── Roads/
│   └── Obstacles/
├── ScriptableObjects/
│   ├── CarConfigs/
│   ├── RoadConfigs/
│   └── UpgradeConfigs/
└── Scenes/
```

---

## 👥 OGAT Team

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/DENIZSEKER99">
        <img src="https://github.com/DENIZSEKER99.png" width="80px;" alt="DENIZSEK"/><br />
        <sub><b>DENIZSEK</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/revkae">
        <img src="https://github.com/revkae.png" width="80px;" alt="revkae"/><br />
        <sub><b>revkae</b></sub>
      </a>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/80?text=👤" width="80px;" alt="egemenasim"/><br />
      <sub><b>egemenasim</b></sub>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/80?text=👤" width="80px;" alt="Sadoran45"/><br />
      <sub><b>Sadoran45</b></sub>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/80?text=👤" width="80px;" alt="Reyhan Sena Çimen"/><br />
      <sub><b>Reyhan Sena Çimen</b></sub>
    </td>
    <td align="center">
      <img src="https://via.placeholder.com/80?text=👤" width="80px;" alt="Sarper Sakmak"/><br />
      <sub><b>Sarper Sakmak</b></sub>
    </td>
  </tr>
</table>

---

## 🚀 Getting Started

### Prerequisites
- Unity 2022.3 LTS or later
- Android/iOS build support modules

### Installation

```bash
# Clone the repository
git clone https://github.com/revkae/CrrrazzyCar-Go.git

# Open in Unity Hub
# Select the project folder and open with Unity 2022.3+
```

### Build

1. Open **File → Build Settings**
2. Select target platform (Android/iOS)
3. Click **Build and Run**

---

## 🎯 Roadmap

- [ ] Online leaderboards
- [ ] Daily challenges
- [ ] New car models
- [ ] Weather effects
- [ ] Multiplayer mode

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with ❤️ by <b>OGAT Team</b> @ TED University
</p>

<p align="center">
  <a href="https://revkae.itch.io/">
    <img src="https://img.shields.io/badge/Play_on_Itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white" alt="Play on Itch.io"/>
  </a>
</p>
