# 🛩️ River Raid

A modern web-based recreation of the classic Atari 2600 River Raid game, featuring a beautiful retro-futuristic aesthetic with neon glow effects.

![River Raid](https://img.shields.io/badge/Game-River%20Raid-ff6b35?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-00ffff?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-ffd700?style=for-the-badge)

## 🎮 How to Play

### Controls
| Key | Action |
|-----|--------|
| ← → | Move left/right |
| ↑ | Speed up |
| ↓ | Slow down |
| SPACE | Fire missiles |
| P | Pause game |

### Objective
- Navigate your jet through the winding river
- Destroy enemy ships, helicopters, and bridges for points
- Collect fuel depots (yellow "F") to refuel
- Avoid crashing into river banks
- Don't run out of fuel!

## 🎯 Scoring

| Target | Points |
|--------|--------|
| Enemy Ship | 30 |
| Helicopter | 60 |
| Bridge | 100 |
| Fuel Depot | 80 |

## 🚀 Getting Started

### Option 1: Direct File
Simply open `index.html` in your web browser.

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve
```
Then navigate to `http://localhost:8080`

## 🎨 Features

- **Dynamic River** - Procedurally generated winding river that changes as you fly
- **Multiple Enemies** - Ships, helicopters with animated rotors, and bridges
- **Fuel Management** - Collect fuel depots before your tank runs empty
- **Retro-Modern UI** - Neon glow effects, scanlines, and futuristic fonts
- **Responsive Controls** - Smooth player movement and firing
- **Progressive Difficulty** - Game speeds up as your score increases

## 🎮 Game Elements

### Player Jet
- Orange fighter jet with animated engine flames
- Cyan cockpit glow effect
- Smooth movement and collision detection

### Enemies
- **Ships** (Red) - Move side to side, 30 points
- **Helicopters** (Purple) - Faster movement with animated rotors, 60 points
- **Bridges** (Brown) - Stationary obstacles spanning the river, 100 points

### Collectibles
- **Fuel Depots** (Yellow) - Restore 30% fuel, earn 80 points

## 🛠️ Technical Details

- Pure HTML5 Canvas for rendering
- No external dependencies (fonts loaded from Google Fonts)
- Smooth 60 FPS gameplay
- Procedural river generation algorithm
- Particle-based explosion effects

## 📁 Project Structure

```
River_Raid_game/
├── index.html    # Complete game (HTML + CSS + JavaScript)
└── README.md     # This file
```

## 🎪 Credits

Inspired by the original **River Raid** (1982) by Carol Shaw for Activision.

---

*Press START GAME to begin your mission!* ✈️

