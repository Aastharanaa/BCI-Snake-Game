# 🧠 BCI-Controlled Snake Game 🎮🐍

A fun and innovative Snake game controlled using real EEG signals from a brain-computer interface dataset.

## 🧠 How It Works
- Reads values from a CSV dataset (`FinalDataset.csv`)
- Maps the `Mean` column to movement:
  - `< -1`: Left
  - `> 1`: Right
  - `-1 to 0`: Up
  - `0 to 1`: Down

## 🛠️ Tech Stack
- Python
- Pygame
- Pandas
- EEG Dataset (CSV)

## 🚀 Run It Locally
```bash
git clone https://github.com/Aastharanaa/BCI-Snake-Game.git
cd BCI-Snake-Game
pip install -r requirements.txt
python final_a.py

