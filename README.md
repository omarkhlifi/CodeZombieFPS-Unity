# 🧟 CodeZombieFPS

> A fully procedural, code-generated First-Person Zombie Survival game built with Unity.

![Unity](https://img.shields.io/badge/Unity-6-black?logo=unity)
![C#](https://img.shields.io/badge/C%23-.NET-blue?logo=csharp)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)

---

## Gameplay

![Gameplay](Assets/Docs/Images/gameplay.png)

---

## Hierarchy

![Hierarchy](Assets/Docs/Images/Hierarchy.png)

---

## GameEntryPoint

![GameEntryPoint](Assets/Docs/Images/GameEntryPoint.png)

---

# Overview

**CodeZombieFPS** is a Unity project demonstrating how an entire FPS survival game can be created almost entirely through **code generation** instead of traditional game assets.

The world, environment, player, enemies, weapons, UI, materials, and gameplay systems are generated programmatically at runtime.

This project focuses on software engineering practices, procedural generation, clean architecture, and scalable game development rather than handcrafted art assets.

---

# Features

## 🌲 Procedural World

- Runtime world generation
- Procedural terrain
- Dense procedural forests
- Random tree placement
- Procedural rocks
- Procedural grass
- Dynamic fog
- Night environment
- Runtime generated materials

---

## 🌕 Atmospheric Environment

- Giant procedural red moon
- Moon rotation
- Dark forest atmosphere
- Dynamic lighting
- Volumetric-style fog
- Runtime generated sky colors

---

## 🔫 First Person Gameplay

- First Person Controller
- Mouse Look
- Walking
- Sprinting
- Jumping
- Crouching
- Gravity
- Smooth movement
- Camera bob
- Camera shake
- Weapon sway
- FOV sprint effect

---

## 🔥 Weapons

- Procedural rifle
- Automatic fire
- Raycast shooting
- Ammo system
- Reloading
- Recoil
- Muzzle flash
- Bullet impact effects
- Shell ejection

---

## 🧟 Zombie AI

- Infinite zombie waves
- Procedural spawning
- Increasing difficulty
- Target tracking
- Obstacle avoidance
- Health system
- Death animations (code-driven)
- Object pooling
- Wave progression

---

## ❤️ Survival Mechanics

- Player Health
- Zombie attacks
- Damage system
- Death screen
- Restart system
- Wave counter
- Score tracking

---

## 🖥 User Interface

Generated entirely from code.

Includes:

- Crosshair
- Health
- Ammo
- Current Wave
- Zombie Count
- Game Over Screen
- Pause Menu
- Debug Information

---

# No Imported Assets

The project intentionally avoids traditional game assets wherever practical.

Everything is created using code including:

- Materials
- Primitive meshes
- World objects
- Environment
- Trees
- Rocks
- Moon
- UI
- Enemy bodies
- Weapon model

The project demonstrates how much of a game can be generated procedurally.

---

# Technologies

- Unity 6
- C#
- New Input System
- CharacterController
- NavMesh
- Object Pooling
- Procedural Generation
- Runtime Mesh Generation
- Runtime Material Generation
- Event Driven Architecture

---

# Architecture

```
Assets
│
├── Scripts
│   ├── Core
│   ├── Managers
│   ├── Player
│   ├── Weapons
│   ├── Zombies
│   ├── World
│   ├── Camera
│   ├── UI
│   ├── Audio
│   └── Utilities
│
├── Settings
│
└── Input
```

---

# Gameplay Loop

```
Start Game
      │
      ▼
Bootstrap
      │
      ▼
Generate World
      │
      ▼
Spawn Player
      │
      ▼
Spawn Forest
      │
      ▼
Spawn Moon
      │
      ▼
Spawn Zombies
      │
      ▼
Fight
      │
      ▼
Survive Waves
      │
      ▼
Difficulty Increases
      │
      ▼
Repeat
```

---

# Gameplay

The player spawns inside a procedurally generated forest during the night.

A giant red moon illuminates the landscape while zombies emerge from between the trees.

The objective is simple:

- Stay alive
- Eliminate zombies
- Survive increasingly difficult waves
- Achieve the highest score possible

---

# Design Goals

This project is designed to demonstrate:

- Procedural world generation
- Clean Unity architecture
- Modern C# practices
- Runtime object generation
- Modular game systems
- Scalable codebase
- Performance optimization
- Minimal dependency on external assets

---

# Performance

The project is designed with performance in mind.

Features include:

- Object Pooling
- Cached References
- Runtime Material Reuse
- Minimal Garbage Collection
- Event Driven Systems
- Efficient Update Loops
- Procedural Generation at Startup

---

# Future Features

- Day/Night Cycle
- Dynamic Weather
- Multiplayer
- Boss Zombies
- Loot System
- Inventory
- Crafting
- Save System
- Procedural Buildings
- Underground Bunkers
- Advanced AI
- Audio System
- Procedural Animations
- Blood Effects
- Dynamic Objectives
- Achievements
- Steam Integration

---

# Development Philosophy

The project follows several software engineering principles:

- SOLID
- DRY
- KISS
- Event Driven Architecture
- Single Responsibility Principle
- Dependency Injection (where applicable)
- Modular Design

---

# Requirements

- Unity 6 (Latest LTS Recommended)
- .NET Compatible Runtime
- New Input System Package

---

# Controls

| Action | Key |
|---------|-----|
| Move | WASD |
| Look | Mouse |
| Shoot | Left Mouse Button |
| Reload | R |
| Jump | Space |
| Sprint | Left Shift |
| Crouch | Left Ctrl |
| Pause | Escape |

---

# Project Status

🚧 Active Development

New systems are continuously being added including procedural environments, gameplay mechanics, AI improvements, optimization, and additional survival features.

---

# Contributing

Contributions, ideas, bug reports, and pull requests are welcome.

If you'd like to improve the project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

# License

This project is released under the **MIT License**.

You are free to use, modify, distribute, and build upon this project in accordance with the license terms.

---

# Acknowledgments

Built with:

- Unity Engine
- C#
- Procedural Generation Techniques
- Modern Game Development Practices

---

# Vision

**CodeZombieFPS** aims to showcase how a modern first-person survival game can be architected with a strong emphasis on code-driven content generation. While some Unity built-in resources and engine features are used, the project's primary goal is to minimize reliance on imported art assets and demonstrate scalable, maintainable gameplay systems generated programmatically.

If you find this project interesting, consider ⭐ starring the repository and following its development.
