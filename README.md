# 🏹 Bow & Arrow Retro

A retro-style arcade game where you fire arrows at scoring targets in different terrains!

## 🎮 How to Play

1. Open `index.html` in any modern browser — no server needed!
2. Choose your **terrain** (Forest, Snow Mountain, Desert)
3. Choose your **character** (Spider-Man, Iron-Man, Legolas)
4. **Aim** with your mouse — **click** to fire each arrow
5. Survive **5 rounds** of 10 arrows each — the target gets further and smaller each round!
6. Score points by hitting the target rings:
   - **Center**: 10pts | **2nd**: 5pts | **3rd**: 3pts | **4th**: 2pts | **5th**: 1pt
   - **Miss**: -10 points
7. Watch the **wind** — it changes every 2-3 shots and pushes your arrows!
8. Build **streaks** for a score multiplier (every 2 consecutive hits = +0.5x)
9. Enter your name after each game to save your score
10. The **top 5 scores** are displayed on the leaderboard

## 🎯 Features

- **5 Rounds** — target moves further away and shrinks each round
- **Moving Target** — oscillates up and down, requiring timing
- **Wind System** — dynamic wind pushes arrows horizontally
- **Streak Multiplier** — consecutive hits multiply your score
- **Stats** — accuracy %, best streak, average score per session
- 3 unique terrains with distinct backgrounds
- 3 playable characters with pixel-art sprites
- Persistent high scores via localStorage
- Retro pixel-art aesthetic

## 🏆 Scoring

| Ring | Points | Streak Bonus |
|------|--------|-------------|
| Center (12px) | 10 | 1.5x at 2 hits |
| 2nd (32px) | 5 | 2.0x at 4 hits |
| 3rd (60px) | 3 | 2.5x at 6 hits |
| 4th (100px) | 2 | 3.0x at 8 hits |
| 5th (150px) | 1 | ... |
| Miss | -10 | Streak resets |

## 🛠️ Tech

Pure HTML, CSS, and JavaScript — zero dependencies. Just open and play!