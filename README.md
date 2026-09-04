# 🏹 Bow & Arrow — Retro & Reimagined

A **No Ads Studio by TheOneKiK** game — zero ads, zero tracking. Fire arrows at scoring targets across different terrains!

Two ways to play, both pure HTML/CSS/JS with zero dependencies — just open in any modern browser, no server needed:

| File | What it is |
|------|-----------|
| `index.html` | Landing page — pick an edition, then play |
| `beautiful.html` | The reimagined edition — realistic archer, recurve bow, cinematic impacts, tougher rules |
| `retro.html` | The original retro edition — pixel-art archers (Spider-Man, Iron-Man, Legolas), 3 terrains |

## 🎮 How to Play

1. Open `index.html` in any modern browser and pick your edition (or open `beautiful.html` / `retro.html` directly)
2. Choose your **terrain** (Forest, Snow Mountain, Desert)
3. Choose your **archer** (Ember, Azure, Sage)
4. **Aim** with your mouse — **click** to fire each arrow
5. Survive **5 rounds** of 10 arrows each — the target gets further (up to 865px), smaller (down to 0.6×), and faster every round!
6. Score points by hitting the target rings:
   - **Center**: 10pts | **2nd**: 5pts | **3rd**: 3pts | **4th**: 2pts | **5th**: 1pt
   - **Miss**: −10 points
7. ⚠️ **3 misses in a row ends your run!** Any hit resets the count.
8. Watch the **wind** — it changes every 2–3 shots and pushes your arrows!
9. Build **streaks** for a score multiplier (every 2 consecutive hits = +0.5×)
10. Enter your name on the game-over screen to save your score — **top 5** on the leaderboard

## ✨ Beautiful edition highlights

- Realistic human archer — breathing idle, flowing cape, back quiver, mouse-tracked aim
- Recurve bow with release snap, wood-grain shafts, steel broadheads, feather fletching
- Arrows **drive into the board** along their flight path and ride the moving target
- Cinematic impacts — screen shake, shockwave rings, wood chips, dust, pitch-by-ring thunks
- Challenging distances from round 1 — no easy start
- Sudden-death pressure — 3 consecutive misses ends the game
- No-ads branding by No Ads Studio by TheOneKiK

## 🏆 Scoring

| Ring | Points | Streak Bonus |
|------|--------|-------------|
| Center (13px) | 10 | 1.5× at 2 hits |
| 2nd (32px) | 5 | 2.0× at 4 hits |
| 3rd (58px) | 3 | 2.5× at 6 hits |
| 4th (92px) | 2 | 3.0× at 8 hits |
| 5th (130px) | 1 | ... |
| Miss | −10 | Streak resets, 3-in-a-row ends game |

## 🛠️ Tech

Pure HTML, CSS, and JavaScript — zero dependencies. High scores persist via localStorage. Just open and play!
