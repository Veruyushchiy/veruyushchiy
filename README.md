# Project Name

A short one-line description of the project.

Example:
A modular Unity gameplay system focused on inventory management, item data, and scalable game architecture.

---

## Overview

This project was developed as a Unity/C# system showcase for game development portfolio purposes.

It demonstrates:
- Clean Unity project structure
- Object-oriented programming
- Scalable gameplay system design
- Data-driven workflow
- Maintainable C# code

---

## Project Links

- **Portfolio:** [Your Portfolio Link Here](https://your-link-here.com)
- **Gameplay Demo / Video:** [Demo Video Link Here](https://your-link-here.com)
- **Itch.io / Steam Page:** [Game Page Link Here](https://your-link-here.com)
- **Contact:** your.email@example.com

---

## Features

- Modular inventory system
- Item data using ScriptableObjects
- Stackable and non-stackable item support
- Item pickup and item usage workflow
- UI-ready structure for inventory display
- Designed for expansion into crafting, equipment, and save/load systems

---

## Technologies Used

- Unity
- C#
- ScriptableObjects
- Git / GitHub
- JetBrains Rider

---

## My Role

**Role:** Unity Developer / Gameplay Programmer

Responsibilities:
- Designed the system architecture
- Implemented core gameplay logic
- Organized code for scalability and readability
- Tested system behavior inside Unity
- Documented usage and setup instructions

---

## System Design

The system is separated into several responsibilities:

```text
ItemSO
 └── Stores static item data

InventoryItem
 └── Stores runtime item quantity and state

InventoryManager
 └── Handles adding, removing, and checking items

InventoryUI
 └── Displays inventory data to the player
