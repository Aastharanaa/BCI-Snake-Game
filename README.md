# 🧠 BCI-Controlled Snake Game 🎮🐍

A brain-computer interface (BCI) integrated Snake game where player movement is controlled using real EEG data. Built using Python and Pygame, the game reads mean values from a pre-recorded dataset and maps them to directional commands (left, right, up, down).

## 🚀 Features
- Real-time Snake game built in Python using Pygame
- Brain signals interpreted from CSV dataset (Mean values)
- EEG signals mapped to movement commands
- Collision detection and scoring logic included
- Visually interactive and functional

## 🧠 How It Works
- The system loads a CSV file containing EEG-derived mean values
- Each frame samples a value and maps it:
  - Mean < -1 → Left
  - Mean > 1 → Right
  - Mean between -1 to 0 → Up
  - Else → Down
- Snake movement is controlled accordingly

## 🛠 Tech Stack
- Python
- Pygame
- Pandas
- EEG Dataset (CSV format)

