# 🎲 ProbQuest

### 🥽 An Immersive WebXR Probability Adventure

<p align="center">

**Learn • Experiment • Practice • Solve • Reward**

</p>

<p align="center">
  <img src="https://img.shields.io/badge/WebXR-Immersive-blueviolet?style=for-the-badge&logo=webxr" alt="WebXR">
  <img src="https://img.shields.io/badge/IWSDK-0.5.3-blue?style=for-the-badge" alt="IWSDK">
  <img src="https://img.shields.io/badge/Three.js-3D-black?style=for-the-badge&logo=three.js" alt="Three.js">
  <img src="https://img.shields.io/badge/TypeScript-Logic-blue?style=for-the-badge&logo=typescript" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vite-Build-purple?style=for-the-badge&logo=vite" alt="Vite">
  <img src="https://img.shields.io/badge/Blender-3D%20Assets-orange?style=for-the-badge&logo=blender" alt="Blender">
</p>

---

## 🧠 Overview

**ProbQuest** is an interactive **WebXR educational game** designed to help **10th Standard students** understand and solve **Probability** problems through immersive experiments and gameplay.

Instead of working with probability only through textbook questions, players interact with virtual objects such as **coins, dice, coloured balls, and playing cards**, observe outcomes, understand the underlying concept, and then solve related probability problems.

### Core Experience

> **Learn → Experiment → Practice → Solve → Reward**

---

## 🎯 Project Concept

ProbQuest combines:

- 🧮 Mathematics
- 🥽 Virtual Reality / XR
- 🎮 Game-based Learning
- 🧩 Interactive Experiments
- 🏆 Gamification

into one immersive learning experience.

Each area focuses on a specific probability concept and uses a corresponding physical interaction to connect mathematical reasoning with an actual experiment.

The game is designed specifically around:

> **10th Standard Mathematics – Probability**

---

# 🌎 Game World

The player enters a virtual mathematical world where the **Probability Gate** is locked.

To progress through the world, the player explores different probability-based environments, completes challenges, and collects keys.

### 🗺️ World Structure

```text
                         🏆 VICTORY / EXIT
                                │
                                ▼
                    🔐 FINAL PROBABILITY GATE
                                │
                                ▼
                      ⚔️ CHALLENGE ZONE
                                │
              ┌─────────────────┴─────────────────┐
              │                                   │
              ▼                                   ▼
       📦 MYSTERY BOX                         🃏 CARD ROOM
          LEVEL 3                               LEVEL 4
              │                                   │
              ▼                                   ▼
       🪙 COIN CASTLE                         🎲 DICE DUNGEON
          LEVEL 1                               LEVEL 2
              │                                   │
              └─────────────────┬─────────────────┘
                                ▼
                         🚪 START / HUB
```

---

# 🏰 Game Zones

| Level | Zone                      | Probability Focus                           | Main Interaction     | Reward         |
| ----: | ------------------------- | ------------------------------------------- | -------------------- | -------------- |
|     1 | 🪙 Coin Castle            | Basic probability & equally likely outcomes | Toss a coin          | 🔑 Coin Key    |
|     2 | 🎲 Dice Dungeon           | Dice outcomes & compound events             | Roll a die           | 🔑 Dice Key    |
|     3 | 📦 Mystery Box            | Random selection & group composition        | Pick a coloured ball | 🔑 Mystery Key |
|     4 | 🃏 Card Room              | Probability with a 52-card sample space     | Draw a card          | 🔑 Card Key    |
|     5 | ⚔️ Challenge Zone         | Mixed probability application               | Mixed interactions   | —              |
|     6 | 🔐 Final Probability Gate | Cumulative probability mastery              | Mixed challenge      | 🏆 Victory     |

---

# 🧠 Learning Approach

ProbQuest is designed as more than a conventional quiz.

Each room introduces the concept through an interactive experiment before asking the player to solve questions.

### 🔄 Room Learning Flow

```text
        📖 LEARN
           │
           ▼
      🧪 EXPERIMENT
           │
           ▼
       ✏️ PRACTICE
           │
           ▼
       🧩 CHALLENGE
           │
           ▼
        🏆 REWARD
```

### 📖 Learn

Introduction to the probability concept using concise visual and interactive explanations.

### 🧪 Experiment

The player physically interacts with the corresponding object and observes an outcome.

Examples:

- 🪙 Toss a coin
- 🎲 Roll a die
- 🔴 Pick a ball
- 🃏 Draw a card

### ✏️ Practice

Guided questions help the player apply the concept.

### 🧩 Challenge

The player independently solves probability questions.

### 🏆 Reward

Successful completion provides progression and unlocks the next area.

This connects mathematical formulas with the actual random experiments represented by the questions.

---

# 🥽 XR Experience

ProbQuest is designed as a **browser-based WebXR application**.

Players interact with the environment using XR controllers or supported hand interaction.

### ✋ Core Interactions

| Interaction     | Example                     |
| --------------- | --------------------------- |
| 🤏 Grab         | Coin, dice, ball, card, key |
| 👉 Select       | Menus, answers, hints       |
| 🔄 Flip         | Coin                        |
| 🎲 Roll         | Dice                        |
| 🖐️ Pick         | Ball                        |
| 🃏 Draw         | Card                        |
| 📦 Open / Close | Mystery Box                 |
| 🔑 Place        | Keys and answer objects     |
| 🔍 Inspect      | Dice and cards              |

The objective is to make the player **physically perform the experiment** before solving the associated probability problem.

---

# 🛠️ Technology Stack

| Technology          | Purpose                                 |
| ------------------- | --------------------------------------- |
| 🥽 **WebXR**        | Browser-based immersive XR              |
| ⚙️ **IWSDK**        | XR framework and interaction foundation |
| 🎨 **Three.js**     | 3D rendering                            |
| 💙 **TypeScript**   | Application & gameplay logic            |
| ⚡ **Vite**         | Development & build tooling             |
| 🧊 **Blender**      | 3D environment & asset creation         |
| 📦 **GLB / GLTF**   | 3D asset format                         |
| 🐙 **Git & GitHub** | Version control & collaboration         |

---

# 🧩 Architecture

The high-level architecture of ProbQuest is:

```text
                    🎮 PROBQUEST
                         │
                         ▼
                    TypeScript
                         │
                         ▼
                       IWSDK
                         │
                ┌────────┴────────┐
                │                 │
                ▼                 ▼
             Three.js           WebXR
                │                 │
                └────────┬────────┘
                         ▼
                   Browser / VR
                         │
                         ▼
                     🥽 Player
```

### 🎨 Asset Pipeline

```text
🧊 Blender
    │
    ▼
 GLB / GLTF
    │
    ▼
 IWSDK Asset System
    │
    ▼
 Three.js
    │
    ▼
  WebXR
    │
    ▼
 🥽 VR Headset
```

---

# 📚 Probability Scope

ProbQuest focuses strictly on:

> **10th Standard Mathematics – Probability**

The primary concepts represented in the experience include:

- 🔹 Sample space
- 🔹 Outcomes
- 🔹 Favourable outcomes
- 🔹 Probability of an event
- 🔹 Equally likely outcomes
- 🔹 Compound probability situations
- 🔹 Coin experiments
- 🔹 Dice experiments
- 🔹 Random selection
- 🔹 Card-based probability

The central probability principle reinforced throughout the game is:

```text
              Favourable Outcomes
Probability = ----------------------
               Total Outcomes
```

No unrelated Mathematics topics are part of the game's core subject scope.

---

# 🎮 Gameplay & Progression

Player progression is based on successfully completing probability challenges.

### ⭐ Points

Measure player performance.

### ❤️ Lives

Provide a limited number of attempts during gameplay.

### 💡 Hints

Provide assistance when the player is stuck.

### 🔑 Keys

Represent successful completion of major areas.

### 🔓 Level Unlocking

Allows access to subsequent areas after completing required challenges.

The interaction with the probability experiment is directly connected to the question-solving experience.

---

# 🌍 3D Environment

The environments and interactive objects are created in **Blender** and prepared for WebXR use.

The project uses modular 3D assets so environments and individual interactive objects can be developed and replaced independently.

### Example Assets

- 🏛️ Room environments
- 🪙 Coins
- 🎲 Dice
- 🔴 Coloured balls
- 🃏 Playing cards
- 📦 Mystery box
- 🔑 Probability keys
- 🖥️ Interactive boards and UI elements

---

# 📁 Repository

The repository contains the WebXR application, IWSDK configuration, source code, scenes, assets, and project documentation required to develop and run ProbQuest.

### Main Project Areas

```text
src/          → Application and gameplay logic
public/       → Scenes, models, media and public assets
IWSDK files   → XR configuration and framework setup
README.md     → Project documentation
```

---

# ▶️ Running the Project

ProbQuest is developed as a local WebXR application.

After installing the project dependencies, start the configured development server and open the generated development URL in a compatible browser.

For physical VR testing, the computer and headset must be able to access the same development server over the local network.

### 🌐 Development Environment

```text
Developer Computer
        │
        ▼
    Vite Server
        │
        ▼
  HTTPS WebXR App
        │
    ┌───┴────┐
    ▼        ▼
 Browser   VR Headset
```

---

# 🥽 VR Compatibility

ProbQuest is intended for **WebXR-compatible VR devices and browsers**.

Development and testing currently focuses on:

- 🖥️ Desktop WebXR emulation
- 🥽 Physical VR headset testing
- 🎮 XR controllers
- ✋ Supported hand interaction

The application does not require a Unity build or a traditional game-engine installation on the headset.

---

# 🧪 Development Philosophy

ProbQuest prioritizes:

```text
FUNCTIONALITY
      ↓
LEARNING EXPERIENCE
      ↓
XR INTERACTION
      ↓
GAMEPLAY
      ↓
VISUAL POLISH
```

The experience is designed to remain simple, understandable, and practical while maintaining an immersive XR environment.

---

# 🎯 Project Vision

ProbQuest aims to make Probability more intuitive by connecting mathematical reasoning with direct interaction.

The intended learning experience is:

> **See it → Interact with it → Understand it → Solve it**

---

# 🤝 Project

ProbQuest is being developed as an academic/college XR project focused on combining **mathematics education with immersive WebXR technology**.

The repository serves as the central development space for the ProbQuest application, XR environments, interactive probability experiments, educational content, and gameplay systems.

---

## 💡 ProbQuest

### **Experience Probability. Master the Quest. 🎲🥽**
