# ProbQuest

### An Immersive WebXR Probability Adventure

ProbQuest is an interactive WebXR educational game designed to help 10th Standard students understand and solve Probability problems through immersive experiments and gameplay.

Instead of working with probability only through textbook questions, players interact with virtual objects such as coins, dice, coloured balls, and playing cards, observe outcomes, understand the underlying concept, and then solve related probability problems.

---

## Overview

ProbQuest combines education, virtual reality, and game-based learning into a single interactive experience.

The core experience follows:

**Learn → Experiment → Practice → Solve → Reward**

Each area of the game focuses on a specific probability concept and uses a corresponding physical interaction to make the concept easier to understand and apply.

The game is designed specifically around the **10th Standard Mathematics – Probability** syllabus.

---

## Game Concept

The player enters a virtual world where the final Probability Gate is locked.

To progress, the player explores different probability-based environments, completes challenges, and collects keys.

The game world consists of:

- **Coin Castle** – Probability using coin tosses
- **Dice Dungeon** – Probability using dice and compound events
- **Mystery Box** – Probability using randomly selected coloured balls
- **Card Room** – Probability using a standard 52-card deck
- **Challenge Zone** – Mixed probability challenges
- **Final Probability Gate** – Final cumulative probability challenge

Completing the required challenges allows the player to progress through the world and ultimately unlock the final gate.

---

## Learning Approach

ProbQuest is designed as more than a conventional quiz.

Each room introduces a concept through an interactive experiment before asking the player to solve questions.

A typical room follows:

**Learn**  
Introduction to the probability concept.

**Experiment**  
The player physically interacts with the corresponding object and observes an outcome.

**Practice**  
Guided questions help the player apply the concept.

**Challenge**  
The player independently solves probability questions.

**Reward**  
Successful completion provides progression and unlocks the next area.

This approach connects mathematical formulas with the actual random experiments represented by the questions.

---

## XR Experience

ProbQuest is designed as a browser-based WebXR application.

The player interacts with the virtual environment using XR controllers or supported hand interaction.

Core interactions include:

- Grabbing objects
- Pointing and selecting
- Tossing a coin
- Rolling a die
- Picking a coloured ball
- Drawing and inspecting cards
- Opening and closing objects
- Collecting and placing keys

The experience is designed to work directly from a WebXR-compatible browser without requiring a traditional game engine.

---

## Technology

ProbQuest uses the following technologies:

**IWSDK**  
WebXR framework providing the foundation for XR interaction, scene management, locomotion, grabbing, physics, and related XR functionality.

**Three.js**  
Used for 3D rendering and the underlying Web-based 3D experience.

**WebXR**  
Provides browser-based access to immersive XR experiences and compatible VR hardware.

**TypeScript**  
Used for application and gameplay logic.

**Vite**  
Used for development and application building.

**Blender**  
Used to create the game's 3D environments and interactive assets.

**GLB / GLTF**  
Used to transfer 3D assets from Blender into the WebXR application.

**Git & GitHub**  
Used for source control and collaborative development.

---

## Architecture

At a high level, the project follows this structure:

**Blender Assets → GLB/GLTF → IWSDK → Three.js → WebXR → VR Headset**

IWSDK provides the XR foundation while ProbQuest implements the educational content, probability interactions, gameplay, questions, progression, and rewards on top of it.

---

## Probability Scope

The project focuses strictly on **10th Standard Probability**.

The main concepts are represented through:

- Sample space
- Outcomes
- Favourable outcomes
- Probability of an event
- Equally likely outcomes
- Compound probability situations
- Coin experiments
- Dice experiments
- Random selection
- Card-based probability

The central probability principle reinforced throughout the game is:

**Probability = Favourable Outcomes / Total Outcomes**

No unrelated Mathematics topics are part of the game's core subject scope.

---

## Gameplay & Progression

Player progression is based on successfully completing probability challenges.

The game uses:

**Points**  
Measure player performance.

**Lives**  
Provide a limited number of attempts during gameplay.

**Hints**  
Provide assistance when the player is stuck.

**Keys**  
Represent successful completion of major areas.

**Level Unlocking**  
Allows access to subsequent areas after completing required challenges.

The system is designed so that interaction with the probability experiment is directly connected to the question-solving experience.

---

## 3D Environment

The environments and interactive objects are created in Blender and prepared for WebXR use.

The project uses modular 3D assets so that environments and individual interactive objects can be developed and replaced independently.

Typical assets include:

- Room environments
- Coins
- Dice
- Coloured balls
- Playing cards
- Mystery box
- Probability keys
- Interactive boards and interface elements

---

## Repository

The repository contains the WebXR application, IWSDK configuration, source code, scenes, assets, and project documentation required to develop and run ProbQuest.

The main project areas include:

- `src` – application and gameplay logic
- `public` – scenes, models, media, and other public assets
- IWSDK configuration and project files
- Project documentation and development instructions

---

## Running the Project

ProbQuest is developed as a local WebXR application.

After installing the project dependencies, the development server can be started through the project's configured development workflow.

The application can then be accessed through a compatible desktop browser or WebXR-compatible VR headset.

For physical VR testing, the computer and headset must be able to access the same development server over the local network.

---

## VR Compatibility

ProbQuest is intended for WebXR-compatible VR devices and browsers.

Development and testing currently focuses on:

- Desktop WebXR emulation for development
- Physical VR headset testing through the browser
- XR controllers and supported hand interaction

The application does not require a Unity build or a native game-engine installation on the headset.

---

## Current Project

ProbQuest is currently in its early WebXR development stage, with the core IWSDK-based environment established and the project being developed toward its first complete interactive probability experience.

The repository serves as the main development base for the ProbQuest application and its associated XR environments, interactions, and educational systems.

---

## Project Vision

ProbQuest aims to make Probability more intuitive by connecting mathematical reasoning with direct interaction.

The intended experience is simple:

**See it → Interact with it → Understand it → Solve it**

---

## License

This project is being developed as an academic/college XR project.
