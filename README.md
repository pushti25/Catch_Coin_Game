# 🪙 Catch Coin Game — Python Arcade Game

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pygame](https://img.shields.io/badge/Pygame-2.x-green.svg)](https://www.pygame.org/)
[![GitHub](https://img.shields.io/badge/GitHub-pushti25-black.svg)](https://github.com/pushti25)

> **Project Name:** Catch Coin Game  
> **Developer:** Pushti Doshi  
> **Repository:** [Catch_Coin_Game](https://github.com/pushti25/Catch_Coin_Game)

---

## 🎮 Overview

**Catch Coin Game** is a simple 2D arcade game developed using **Python and Pygame**. The player controls a character at the bottom of the screen and catches falling objects to increase the score.

The game includes falling gold coins and apples, background music, sound effects, animated player graphics, a countdown timer, and a highest-score system.

## ✨ Key Features

- 🪙 Coin catching gameplay
- 🍎 Multiple falling objects
- 🎯 Collision detection
- ⏱️ 90-second game timer
- 🏆 Highest score system
- 🎵 Background music
- 🔊 Sound effects
- 🎞️ Player animation
- ⌨️ Keyboard controls
- 🖥️ 800 × 600 game window

---

## 🕹️ Controls

| Key | Action |
|---|---|
| `A` | Move Left |
| `D` | Move Right |
| `←` | Move Left |
| `→` | Move Right |

---

## 🛠️ Technologies Used

- **Python**
- **Pygame**
- Python `random`
- Python file handling
- Pygame Sprite System
- Pygame Collision Detection
- Pygame Audio
- Keyboard Event Handling

---

## 📁 Repository Structure

```text
Catch_Coin_Game/
│
├── modules/                    # Game classes and supporting modules
│
├── resources/
│   ├── images/                 # Game images and player frames
│   ├── audios/                 # Game audio resources
│   └── font/                   # Game font
│
├── cfg.py                      # Game configuration and resource paths
├── game.py                     # Main game program
├── highest.rec                 # Highest score record
└── README.md                   # Project documentation
```

---

## ⚡ Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/pushti25/Catch_Coin_Game.git
```

### 2. Open the Project Directory

```bash
cd Catch_Coin_Game
```

### 3. Check Python

```bash
python --version
```

### 4. Install Pygame

```bash
pip install pygame
```

### 5. Run the Game

```bash
python game.py
```

---

## 🎯 How to Play

1. Start the game by running `game.py`.
2. The player appears at the bottom of the game screen.
3. Use `A` / `D` or the **Left/Right Arrow keys** to move.
4. Catch the falling gold coins and apples.
5. Successfully caught objects increase the score.
6. Continue playing until the 90-second timer reaches zero.
7. The final score is compared with the stored highest score.
8. The highest score is saved in `highest.rec`.

---

## 🏆 Scoring System

The game maintains:

```text
Score
Highest Score
```

When an object is caught, its corresponding score value is added to the current score.

If the current score exceeds the previous highest score, the highest score is updated.

The highest score is stored in:

```text
highest.rec
```

---

## ⚙️ Game Configuration

```text
Screen Size : 800 × 600
FPS         : 30
Game Time   : 90 seconds
```

The configuration file also defines paths for the game's images, audio, font, and highest-score record.

---

## 🧩 Main Components

### `game.py`

The main game file handles:

- Pygame initialization
- Game window creation
- Loading images and audio
- Creating the player
- Generating falling objects
- Player movement
- Collision detection
- Score calculation
- Countdown timer
- Highest-score management
- Main game loop
- End-game interface

### `cfg.py`

The configuration file manages:

- Image resource paths
- Audio resource paths
- Font path
- Highest-score file
- Screen size
- Background settings
- FPS

### `modules/`

Contains supporting game classes used by the main game program.

---

## 🎵 Game Resources

The project includes:

### Images

- Gold coin
- Apple
- Background
- Player animation frames

### Audio

- Background music
- Object collection sound

### Font

- Custom TrueType font used for displaying game information

---

## 📸 Game Screenshot

Add your gameplay screenshot here:

```markdown
![Catch Coin Game](resources/images/screenshot.png)
```

Replace `screenshot.png` with your actual screenshot filename.

---

## 🔮 Future Enhancements

- ❤️ Lives and health system
- 🎚️ Multiple difficulty levels
- 🪙 Different types of coins with different scores
- ⚡ Power-ups and special items
- 🏅 Online leaderboard
- ⏸️ Pause and resume functionality
- 🎮 Multiple playable characters
- 🌟 Multiple game levels
- ✨ Improved animations and visual effects
- 📱 Mobile version
- 🔊 Additional sound effects

---

## 📚 Learning Outcomes

This project provides practical experience with:

- Python programming
- Pygame game development
- Object-oriented game components
- Sprite-based game objects
- Collision detection
- Keyboard input handling
- Random object generation
- Audio integration
- Image and animation handling
- File handling
- Game loops and frame-rate control

---

## 👨‍💻 Developer

**Pushti Doshi**

GitHub: [@pushti25](https://github.com/pushti25)

Project Repository: [Catch_Coin_Game](https://github.com/pushti25/Catch_Coin_Game)

---

## 🛡️ License

This project was developed for **educational and learning purposes**.

---

⭐ **If you found this project interesting, consider giving the repository a star!**
