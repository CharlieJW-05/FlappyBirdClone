# 🐦 Flappy Bird Clone

A professional, feature-rich Flappy Bird clone built with pure HTML5 Canvas and vanilla JavaScript.

## 🎮 Features

### Core Gameplay
- **Smooth 60 FPS gameplay** with requestAnimationFrame
- **Realistic physics** with gravity and momentum
- **Responsive controls** - Spacebar, click, or touch to jump
- **Progressive difficulty** - Gets harder as you score more points

### Visual Polish
- **Beautiful bird character** with detailed yellow design and wing animation
- **Enhanced pipe graphics** with 3D caps and gradients
- **Parallax scrolling clouds** in the background
- **Textured ground** with grass details
- **Smooth death animation** - Bird rotates and falls when hit
- **Screen shake effect** on collision
- **Particle effects** when bird flaps

### Audio System
- **Realistic wing flap sounds** using Web Audio API
- **Score point sound effects**
- **Collision/game over sounds**
- **Mute button** for audio control

### High Score System
- **Persistent high scores** using localStorage
- **Visual indicators** when you beat your high score
- **Medal achievements** - Bronze (10), Silver (25), Gold (50), Platinum (100)

### User Experience
- **Beginner-friendly difficulty** - Starts easy and gradually increases
- **Pause functionality** - Press P to pause/resume
- **Clean UI** - Title disappears during gameplay for unobstructed view
- **Mobile-friendly** - Touch controls and responsive design
- **Professional start screen** with glowing yellow title

## 🚀 How to Play

1. **Start**: Press SPACE or click to begin
2. **Jump**: Press SPACE, click, or tap to make the bird flap
3. **Avoid**: Don't hit the pipes or ground
4. **Score**: Pass through pipe gaps to increase your score
5. **Pause**: Press P to pause/resume the game
6. **Restart**: Press SPACE on game over to play again

## 🎯 Difficulty Progression

- **Level 1 (0-4 points)**: Gap 200px, Speed 2.0 - Very easy
- **Level 2 (5-9 points)**: Gap 200px, Speed 2.2 - Still easy  
- **Level 3 (10-14 points)**: Gap 192px, Speed 2.4 - Getting harder
- **Level 4 (15-19 points)**: Gap 192px, Speed 2.6 - Moderate
- **Level 5+ (20+ points)**: Gap decreases by 8px every 10 points, speed increases by 0.2 per level

## 🛠️ Technical Details

- **Pure HTML5 Canvas** - No external dependencies
- **Vanilla JavaScript** - Clean, modular code structure
- **Web Audio API** - Realistic sound effects
- **localStorage** - Persistent high score tracking
- **Responsive design** - Scales to window size
- **Mobile optimized** - Touch-friendly controls

## 📱 Browser Compatibility

Works in all modern browsers that support:
- HTML5 Canvas
- Web Audio API
- localStorage
- requestAnimationFrame

## 🎨 Customization

The game is built with a clean, modular structure making it easy to customize:
- **Bird appearance** - Modify colors, size, and animations in the Bird class
- **Pipe design** - Adjust colors and styling in the Pipe class
- **Difficulty curve** - Modify progression in the updateDifficulty method
- **Audio effects** - Customize sounds in the AudioManager class

## 🏆 Achievements

- 🥉 **Bronze Medal**: Score 10+ points
- 🥈 **Silver Medal**: Score 25+ points  
- 🥇 **Gold Medal**: Score 50+ points
- 🏆 **Platinum Medal**: Score 100+ points

## 📄 License

This project is open source and available under the MIT License.

---

**Enjoy playing!** 🎮
