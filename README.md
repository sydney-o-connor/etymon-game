# 🌳 Etymon — The Linguistic Arboreum

> A daily word deduction game linking modern English words back to their prehistoric ancestral roots.

[Play live](https://sydney-o-connor.github.io/etymon-game/)

---

## 🍃 About the Game
Every day, players are presented with an ancient reconstructed root (such as Proto-Indo-European `*der-` meaning *"to split or peel"*). The goal is to deduce four modern descendant words that seem unrelated on the surface, but share this common historical ancestor.

### Key Mechanics
- **The Living Specimen:** Your tree dynamically responds to play. Successful grafts elevate canopy height and bloom blossoms; incorrect guesses and manual leaf hints prune your score.
- **Sunshine Chronometer:** Solve at your own pace without hard timers. Quick thinkers earn an ambient morning sunshine height bonus.
- **Leaf Hints:** Stuck? Manually request a leaf hint at the cost of branch height without ruining your near-miss guesses.
- **Global Canopy Bell Curve:** Compare your final tree height against community distributions inspired by *Krillion*.

---

## 🛠️ Tech Stack
- **Frontend:** Single-file vanilla HTML5, CSS3, and ES6 JavaScript
- **Graphics:** Procedural, dynamic SVG rendering with ink-bleed SVG filters
- **Audio:** Native Web Audio API tone synthesis (no external audio files)
- **Deployment:** GitHub Pages

---

## 📜 Puzzle Rotation & Content
Puzzles are cataloged sequentially. Each daily entry contains:
- Root term, reconstructed ancestor language, and historical meaning
- 4 modern target words with parts of speech and definitions
- Historical sound-shift transit path (`PIE -> Germanic -> Old English`)
- Curated etymological trivia fact
