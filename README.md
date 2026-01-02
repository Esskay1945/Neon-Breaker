# Neon-Breaker
**Neon Breakout** is a modern, neon-inspired brick-breaker game built using pure HTML5, CSS3, and vanilla JavaScript. It combines glowing visual effects, smooth animations, power-ups, combo scoring, and increasing difficulty to deliver an engaging, arcade-style browser gaming experience with no external dependencies.



# 🎮 Neon Breakout

A stunning, modern take on the classic brick-breaker game with vibrant neon visuals, power-ups, and addictive gameplay. Built with pure HTML5, CSS3, and JavaScript.

![Neon Breakout Demo](https://img.shields.io/badge/status-playable-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

### 🎨 Visual Effects
- **Animated gradient background** that shifts dynamically
- **Twinkling star field** for immersive space atmosphere
- **Neon glow effects** on all game elements
- **Particle explosions** when bricks are destroyed
- **Trail effects** following the ball
- **Smooth animations** and transitions throughout

### 🎯 Gameplay Mechanics
- **3 Lives System** - Get three chances to beat each level
- **Progressive Difficulty** - More rows added with each level
- **Multi-hit Bricks** - Some bricks require multiple hits to destroy
- **Combo System** - Chain hits for bonus points
- **Score Multipliers** - Higher combos mean higher scores
- **Level Progression** - Complete levels to advance with increasing difficulty

### ⚡ Power-ups
Collect power-ups dropped by destroyed bricks:

| Power-up | Icon | Effect | Duration |
|----------|------|--------|----------|
| **Multi-Ball** | ⚡ | Spawns 2 additional balls | Until lost |
| **Wide Paddle** | 🔵 | Increases paddle width | 10 seconds |
| **Slow Motion** | 🌀 | Reduces ball speed | 8 seconds |
| **Fire Ball** | 🔥 | Ball destroys bricks instantly | 10 seconds |
| **Extra Life** | ❤️ | Adds one additional life | Permanent |
| **Laser Paddle** | 🔫 | Shoot lasers to destroy bricks | 12 seconds |

### 🎮 Controls
- **Arrow Keys** or **Mouse** - Move paddle left/right
- **Spacebar** - Fire lasers (when Laser power-up is active)
- **Escape** - Pause/Resume game
- **Pause Button** - Toggle pause state
- **Menu Button** - Return to main menu

## 🚀 Quick Start

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/neon-breakout.git
cd neon-breakout
```

2. **Open the game**
Simply open `index.html` in any modern web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or drag and drop `index.html` into your browser.

### Live Demo

🎮 **[Play Now](https://yourusername.github.io/neon-breakout)** *(Replace with your GitHub Pages link)*

## 📁 Project Structure

```
neon-breakout/
│
├── index.html          # Main game file (HTML, CSS, JS all-in-one)
├── README.md           # This file
└── LICENSE             # MIT License (optional)
```

## 🎯 How to Play

1. **Start the Game** - Click "PLAY NOW" on the main menu
2. **Break Bricks** - Use your paddle to bounce the ball and destroy all bricks
3. **Collect Power-ups** - Catch falling power-ups with your paddle
4. **Build Combos** - Hit bricks in quick succession for bonus points
5. **Complete Levels** - Destroy all bricks to advance to the next level
6. **Survive** - Don't let the ball fall! You have 3 lives per game

## 🏆 Scoring System

- **Basic brick**: 10 points × brick strength
- **Combo multiplier**: Every 3 combo hits adds 1× multiplier
- **Level bonus**: Lives × 500 + Level × 1000
- **Max combo tracking**: Try to beat your highest combo!

## 🛠️ Technology Stack

- **HTML5 Canvas** - For game rendering
- **Vanilla JavaScript** - Game logic and mechanics
- **CSS3** - Animations and visual effects
- **No dependencies** - Pure web technologies, no frameworks needed

## 🎨 Customization

Want to modify the game? Here are some easy tweaks:

### Change Colors
```javascript
// Find these in the code and modify:
const colors = ['#FF0080', '#FF00FF', '#8000FF']; // Brick colors
gradient.addColorStop(0, '#FFFF00'); // Ball gradient
```

### Adjust Difficulty
```javascript
// Change initial ball speed
const ball = createBall(canvas.width / 2, canvas.height - 50, 5, -5); // Last two numbers are speed

// Change paddle speed
paddle: { width: 120, height: 15, x: canvas.width / 2 - 60, speed: 10 }
```

### Modify Power-up Probability
```javascript
const hasPowerup = Math.random() < 0.2; // 20% chance, adjust as needed
```

## 🐛 Known Issues

- None currently! Report issues on the [Issues page](https://github.com/yourusername/neon-breakout/issues)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add sound effects and background music
- Create new power-ups
- Add mobile touch controls
- Implement a high score system with localStorage
- Add new brick types or obstacles
- Create additional levels or level editor


## 🌟 Acknowledgments

- Inspired by classic Breakout and Arkanoid games
- Built as a modern HTML5 game showcase
- Created with passion for retro gaming aesthetics


Project Link: https://neonbreakerr.netlify.app/


⭐ **If you enjoyed this game, please consider giving it a star!** ⭐

Made with 💜 and JavaScript
