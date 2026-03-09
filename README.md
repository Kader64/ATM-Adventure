# 🎮 ATM-Adventure

**ATM-Adventure** is a **C# console-based platform game** built on top of a custom **console graphics engine**.
The project demonstrates how a simple game can be implemented entirely in the **terminal/console environment** using ASCII graphics and modular architecture.

---

## 📦 Project Structure

The project consists of **three main parts**:

### 🕹️ 1. Platform Game

A console platformer created using a custom graphics engine.
Player has to connect cable from ATM to socket.
The game includes:

* 🧱 Levels and obstacles
* 🎯 Basic gameplay mechanics (jump, move, etc.)
* ⏱️ Level timer system
* ⚙️ Collision handling
* 🎧 Custom soundtrack

---

### 🧩 2. Console Graphics Engine

A custom engine responsible for **rendering graphics and managing core systems inside the console window**.

Main components:

* 🖼️ **ASCIICanvas.cs** – Renders ASCII graphics in the console
* ⚙️ **CGE.cs** – Core of the Console Game Engine
* 🖥️ **ConsoleManager.cs** – Manages console configuration and settings
* 🎨 **EscapeColor.cs** – Enables colored console output
* ⌨️ **KeyboardManager.cs** – Handles keyboard input
* 🔁 **LoopStream.cs** – Supports looping audio streams
* 🔊 **Sound.cs** – Basic sound functionality
* 🎵 **SoundManager.cs** – Manages game sound playback
* ⏲️ **Timer.cs** – Timer used for levels and gameplay events

---

### 📋 3. Console Game Menu

A console-based menu system that allows players to:

* ▶️ Start the game
* 🏆 View Leaderboard
* ⚙️ Access game options

---

## 🧪 Tests

The repository also includes an **xUnitTests** project containing **example unit tests** that demonstrate how parts of the application can be tested.

---

## 🛠️ Technologies Used

* 💻 **C#**
* ⚡ **.NET Console Application**
* 🔤 **ASCII-based rendering**
* 🧪 **xUnit** for unit testing

---

## 🎯 Purpose of the Project

This project demonstrates:

* 🧠 Building a **simple console-based game engine**
* 🎨 Rendering **ASCII graphics in a console environment**
* 🧩 Designing a **modular game architecture**
* 🧪 Implementing **unit tests with xUnit**
* 🎮 Creating a playable **terminal-based platform game**

---

## 🚀 Screenshot

<img width="916" height="503" alt="obraz" src="https://github.com/user-attachments/assets/3400a32e-2570-4fcc-a757-b61e7ceb19a3" />

---

✨ *A small experiment showing that even a console can become a game engine.*
