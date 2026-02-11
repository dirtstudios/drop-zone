# Drop Zone: Enhanced Audio System 🔊

## Overview
The game now supports **real high-quality sound effects** in addition to procedural generation!

## How It Works
1. **Smart Loading**: Game tries to load external `.wav` files first from `assets/sounds/`
2. **Fallback**: If external sound not found, uses procedural generation
3. **Performance**: Sounds are cached after first load for optimal performance

## Sound Files Supported
Place `.wav` files in `assets/sounds/` with these names:

### Core Gameplay Sounds
- `grab.wav` - Object pickup sound
- `yeet.wav` - Object throwing sound  
- `merge.wav` - Object merging (tier 0, can have merge1.wav, merge2.wav, etc. for different tiers)
- `spawn.wav` - Object spawn pop
- `jump.wav` - Player jump
- `floor_break.wav` - Floor destruction

### UI & Feedback Sounds  
- `level.wav` - Level up fanfare
- `achievement.wav` - Achievement unlock jingle
- `powerup.wav` - Power-up collection
- `pause.wav` - Game pause
- `unpause.wav` - Game unpause
- `gameover.wav` - Game over sound

### Power-up Sounds
- `bomb.wav` - Explosion effect
- `combo.wav` - Combo chain sound

## Sound Requirements
- **Format**: WAV files (best compatibility)
- **Sample Rate**: 44.1kHz recommended
- **Channels**: Mono or stereo
- **Length**: Keep under 2 seconds for responsiveness

## Free Sound Resources
- [OpenGameArt.org](https://opengameart.org/content/cc0-sound-effects) - CC0 game sounds
- [Pixabay](https://pixabay.com/sound-effects/search/cc0/) - Free CC0 effects
- [itch.io CC0 Collection](https://itch.io/c/4003879/cc0-sfx-and-voices) - 4,000+ sounds

## Technical Details
- External sounds play at 50% volume (adjust in `playSound` function)
- Sounds are decoded once and cached for performance  
- Async loading prevents blocking gameplay
- Progressive enhancement: works without external sounds

## Example Usage
```javascript
// This will try to load grab.wav, fall back to procedural if not found
playSound('grab');

// Merge sounds can be tier-specific
playSound('merge', 2); // Tries merge2.wav, then merge.wav, then procedural
```

## Current Status
✅ **Enhanced audio system implemented**  
⚠️ **No sound files included yet** (keeping game lightweight)  
🎯 **Ready for professional sound library integration**

---

**Upgrade the game's audio by adding `.wav` files to this folder!** 🚀