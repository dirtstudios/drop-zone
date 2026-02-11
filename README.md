# Drop Zone: Kitchen Chaos 🍕

A 3D physics-based merge puzzle game built with Three.js and Cannon.js.

## 🎮 Game Features

- **Multiple Game Modes**: Classic, Zen, Time Attack, Puzzle, and Daily Challenge
- **Physics-Based Gameplay**: Realistic 3D physics with object interactions
- **Merge System**: Combine same foods to create higher tiers (🍓→🍎→🍊→🍉→🎃→🎂)
- **Power-ups**: Magnet, Bomb, Freeze, and Golden Touch abilities
- **Achievement System**: 20 unique achievements to unlock
- **Upgrade Shop**: Spend coins on permanent improvements
- **Theme System**: Unlock different visual themes
- **Enhanced Audio**: Procedural sound generation with external audio support

## 🍓 How to Play

1. Use **WASD** to move around the kitchen
2. **E** to grab/release objects, **Q** to yeet them away
3. **Space** to jump, **Shift** to sprint
4. Merge same food items by making them touch
5. Create birthday cakes (🎂) to break floors and advance levels
6. Chain merges quickly for combo bonuses!

## 🏆 New Achievements (v1.1)

- **Speed Demon** ⚡: Complete 5 merges in under 10 seconds
- **Cake Baker** 🎂: Create 10 birthday cakes total  
- **Zen Master** 🧘: Play Zen mode for 10 minutes straight
- **Perfectionist** 💯: Reach level 5 without yeeting any objects
- **Airborne** 🚁: Have 20 objects in the air simultaneously

## 🛠 Technical Features

- Built with Three.js for 3D graphics
- Cannon.js for realistic physics simulation
- Advanced post-processing effects (bloom, vignette)
- Smart audio system with external file support + procedural fallbacks
- Mobile-friendly touch controls
- Local storage for persistent progress
- Modular upgrade and achievement systems

## 🎵 Audio Enhancement

The game supports external `.wav` audio files in `assets/sounds/`:
- `merge.wav`, `yeet.wav`, `grab.wav`, `jump.wav`
- `powerup.wav`, `bomb.wav`, `floor_break.wav`
- And many more! See `assets/sounds/README.md` for details.

## 🚀 Running the Game

1. Clone the repository
2. Start a local web server (e.g., `python -m http.server 8080`)
3. Open `http://localhost:8080` in your browser
4. Click to start and enjoy!

---

**Latest Update**: v1.1 - Enhanced Achievement System
- Added 5 challenging new achievements
- Improved tracking for complex gameplay metrics  
- Better session management for zen mode
- Real-time airborne object monitoring

Ready to become the ultimate Kitchen Chef? 👨‍🍳