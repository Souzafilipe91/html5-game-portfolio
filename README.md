# 🎮 Game Dev Portfolio - HTML5 Games

A professional portfolio with 3 HTML5 games built from scratch, demonstrating expertise in game development, gameplay design, and implementation of complex mechanics.

## 📋 Included Games

### 1. **Match Master** (2D Puzzle)
A classic match-3 game with addictive mechanics and a progressive combo system.

**Features:**
- Match-3 mechanics with automatic line detection
- Combo system that multiplies points
- Smooth elimination animations
- Dynamic sound effects with Web Audio API
- Responsive and intuitive interface
- Move limit for progressive challenge

**Technologies:**
- HTML5 Canvas for rendering
- Vanilla JavaScript with OOP
- Web Audio API for sound synthesis
- RequestAnimationFrame for 60 FPS

**Main Mechanic:**
Click on two adjacent tiles to swap them. Form lines of 3 or more tiles of the same color to eliminate them. The longer your match streak, the higher your point multiplier!

---

### 2. **Asteroid Blaster** (Arcade)
A classic arcade game with fast action, multiple waves, and progressive difficulty.

**Features:**
- Responsive arcade gameplay with smooth movement
- Wave system with progressive difficulty
- Optimized collision detection
- Particle system for explosions
- Dynamic sound effects
- Precise mouse-based aiming

**Technologies:**
- HTML5 Canvas with optimized rendering
- AABB (Axis-Aligned Bounding Box) collision detection
- Custom particle system
- Web Audio API for sound effects

**Main Mechanic:**
Use your mouse to move your ship and click to shoot. Destroy all asteroids before they reach you. Each completed wave increases the difficulty!

---

### 3. **Pixel Runner** (Platform)
A platformer with precise controls, coin collection, and progressive level design.

**Features:**
- Precise jump controls with realistic physics
- Coin collection system with visual feedback
- Automatic level progression
- AABB collision detection
- Particle effects (sparkles and explosions)
- Difficulty scaling based on progress

**Technologies:**
- HTML5 Canvas with sprite rendering
- Simplified physics system (gravity, velocity)
- Collision detection for platforms
- Web Audio API for sound effects

**Main Mechanic:**
Press SPACE or UP ARROW to jump. Collect coins to earn points and avoid obstacles. Every 5 coins collected, you level up and the game gets faster!

---

## 🎯 Technical Architecture

### Code Structure
Each game follows an OOP pattern with a main class that encapsulates:
- **Initialization**: Canvas setup, context, and event listeners
- **Game Loop**: Update → Draw → RequestAnimationFrame
- **State Management**: Score, health, levels
- **Input Handling**: Mouse, keyboard
- **Collision Detection**: Optimized collision checking
- **Audio**: Real-time sound synthesis with Web Audio API

### Performance
- **60 FPS**: RequestAnimationFrame for refresh rate synchronization
- **Canvas Optimization**: Redraw only necessary areas
- **Collision Detection**: O(n²) AABB algorithm for acceptable performance
- **Garbage Collection**: Cleanup of off-screen objects

### Responsiveness
- All games adapt to different screen sizes
- Maintain aspect ratio
- Work on desktop, tablet, and mobile

---

## 🚀 How to Use

### Opening the Games
1. **Main Portfolio**: Open `index.html` in a modern browser
2. **Individual Games**:
   - Match Master: `match-master.html`
   - Asteroid Blaster: `asteroid-blaster.html`
   - Pixel Runner: `pixel-runner.html`

### Requirements
- Modern browser with support for:
  - HTML5 Canvas
  - Web Audio API
  - ES6 JavaScript
  - RequestAnimationFrame

### Supported Browsers
- Chrome/Chromium 60+
- Firefox 55+
- Safari 11+
- Edge 79+

---

## 💻 Clean and Professional Code

### Code Features
- **No External Dependencies**: Pure HTML5 vanilla
- **Modular Structure**: Each game is self-contained
- **Well-Documented**: Code with explanatory comments
- **Design Patterns**: OOP, Game Loop Pattern
- **Scalability**: Easy to add new features

### Example Structure (Match Master)
```javascript
class MatchMasterGame {
    constructor() {
        // Initialization
    }

    resetGame() {
        // State reset
    }

    handleClick(e) {
        // Input handling
    }

    findMatches() {
        // Game logic
    }

    draw() {
        // Rendering
    }

    gameLoop() {
        // Main loop
    }
}
```

---

## 🎨 Visual Design

### Color Palettes
- **Match Master**: Purple/blue gradient with vibrant colors
- **Asteroid Blaster**: Dark theme with red accents
- **Pixel Runner**: Classic theme with blue sky and green grass

### Typography
- Default font: Arial/Segoe UI (web-safe)
- Clear size hierarchy
- Good contrast for readability

---

## 🔊 Audio

### Web Audio API
All games use real-time sound synthesis:
- **Oscillators**: Generate pure tones
- **ADSR Envelope**: Dynamic volume control
- **Variable Frequencies**: Different sounds for different events

### Sound Effects
- **Match Master**: Selection beeps, match sounds
- **Asteroid Blaster**: Shooting sounds, explosions, level up
- **Pixel Runner**: Jump sounds, coin collection, game over

---

## 📊 Statistics

| Aspect | Match Master | Asteroid Blaster | Pixel Runner |
|--------|-------------|-----------------|--------------|
| Type | Puzzle | Arcade | Platform |
| Mechanics | Match-3, Combo | Shooting, Waves | Jump, Collection |
| Difficulty | Progressive | Progressive | Progressive |
| HTML Size | ~8 KB | ~10 KB | ~10 KB |
| Lines of Code | ~350 | ~400 | ~400 |
| Dependencies | 0 | 0 | 0 |

---

## 🎓 Technical Skills Demonstrated

1. **Game Development Fundamentals**
   - Game loop pattern
   - State management
   - Input handling
   - Collision detection

2. **HTML5 Canvas**
   - 2D rendering
   - Transformations (rotate, translate, scale)
   - Shadows and visual effects
   - Performance optimization

3. **Advanced JavaScript**
   - OOP with classes
   - Event handling
   - RequestAnimationFrame
   - Closures and scope

4. **Web Audio API**
   - Sound synthesis
   - Oscillators and gain nodes
   - Volume envelope
   - Precise timing

5. **UX/UI Design**
   - Visual feedback
   - Smooth animations
   - Responsiveness
   - Accessibility

---

## 🔧 Possible Future Improvements

- Backend integration for high scores
- Save/load game progress system
- Online multiplayer
- Optimized mobile touch controls
- Customizable visual themes
- Global leaderboard
- Achievements/Badges
- Dark/light theme support
- Gamepad support
- Replay system

---

## 📝 License

This portfolio is provided as a demonstration of HTML5 game development skills.

---

## 👨‍💻 About the Developer

This portfolio demonstrates proficiency in:
- Game design and implementation
- HTML5 and Canvas API
- Vanilla JavaScript
- Web Audio API
- Performance optimization
- UI/UX design

Ready for integration with external APIs and backend systems for interactive advertising platforms!

---

**Built with ❤️ in HTML5**
