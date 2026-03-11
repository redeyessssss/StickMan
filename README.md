# 🥊 Stick Fight Web

A feature-rich 2D fighting game built with HTML5 Canvas and vanilla JavaScript. Fight through 25 acts, unlock skills, customize controls, and master the art of stick fighting!

![Stick Fight](https://img.shields.io/badge/Game-Stick%20Fight-orange)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-red)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)

## 🎮 Features

### Game Modes
- **Story Mode**: 25 acts across 5 chapters with increasing difficulty
- **Survival Mode**: Endless waves of enemies - how long can you survive?
- **Daily Challenges**: Complete 3 random challenges each day for bonus rewards

### Combat System
- **Advanced Mechanics**: Combos, Perfect Parry, Critical Hits, Air Juggling, Wall Bounce
- **Multiple Attacks**: Punch, Kick, Magic/Special, Ultimate, Grab/Throw
- **Defensive Options**: Block, Parry, Dash
- **Rage Mode**: Power boost when HP is low (requires skill unlock)

### Progression
- **Skill Tree**: 10 unlockable abilities with unique powers
- **Weapons**: 5 weapons with unique stats and special moves
- **Characters**: 5 fighters with different playstyles
- **Upgrades**: Improve Attack, Defense, Speed, and Energy Regen (10 levels each)
- **Achievements**: 10 achievements to unlock

### Customization
- **Custom Controls**: Rebind all keyboard controls to your preference
- **Multiple Characters**: Each with unique stats
- **Weapon Variety**: Choose your fighting style

## 🎯 Controls (Default)

### Movement
- **W** - Jump (double jump available)
- **A** - Move Left
- **D** - Move Right
- **S** - Crouch

### Combat
- **J** - Punch
- **K** - Kick
- **L** - Magic/Special Attack
- **U** - Ultimate Attack

### Defense & Special
- **Z** - Block/Parry
- **E** - Dash
- **G** - Grab/Throw

*All controls can be customized in the RULES menu!*

## 🚀 How to Play

### Option 1: Play Directly
Simply open `index.html` in your web browser!

### Option 2: Local Server
```bash
# Using Python
python3 -m http.server 8080

# Using Node.js (if you have http-server installed)
npx http-server -p 8080
```

Then visit `http://localhost:8080/index.html`

### Option 3: Build with Webpack (Optional)
```bash
npm install
npm run dev    # Development server
npm run build  # Production build
```

## 📊 Game Mechanics

### Combo System
Chain attacks within 1.5 seconds to build combos and deal bonus damage!

### Perfect Parry
Block within 0.2 seconds of an enemy attack to:
- Take zero damage
- Stun the enemy
- Trigger counter attack (with skill)

### Critical Hits
- Base: 20% chance for 2x damage
- With Critical Strike+ skill: 35% chance

### Air Juggling
Hit enemies while airborne for +20% damage per hit. Keep them in the air for massive combos!

### Energy System
- Build energy by dealing damage
- Spend 100 energy for Ultimate attacks
- Unlock skills to start with 50 energy or reduce cost to 75

### Rage Mode
When HP drops below 25% (requires skill unlock):
- +50% attack damage
- +30% movement speed

## 🌟 Skill Tree

Unlock powerful abilities using Skill Points earned from:
- Perfect wins (+1 point)
- Every 5 wins (+1 point)
- High combo achievements (+1 point)

**Available Skills:**
- Double Jump
- Counter Attack
- Life Steal
- Combo Master
- Energy Boost
- Critical Strike+
- Rage Mode
- Weapon Mastery
- Dodge Roll
- Ultimate Charge

## 💰 Progression System

### Coins
Earned by winning fights. Use to purchase:
- Weapons (100-300 coins)
- Characters (200-400 coins)
- Upgrades (100-200 coins per level)
- Some skills (200 coins)

### Skill Points
Earned from achievements and milestones. Spend on skill tree abilities.

## 🏆 Achievements

Complete special challenges to earn bonus coins:
- First Blood (50 coins)
- Combo Master (100 coins)
- Untouchable (200 coins)
- Speed Demon (150 coins)
- Ultimate Power (100 coins)
- Stick Master (1000 coins)
- Perfect Defense (150 coins)
- Air Master (150 coins)
- Wealthy Warrior (200 coins)
- Shopaholic (300 coins)

## 🎨 Features

- **Silhouette Graphics**: Shadow Fight 2 inspired visual style
- **Smooth Animations**: Realistic martial arts movements
- **Particle Effects**: Hit effects, trails, energy auras
- **Sound System**: Procedural audio for all actions
- **Save System**: Progress saved to localStorage
- **Responsive Design**: Works on desktop and mobile
- **Mobile Controls**: Touch controls for mobile devices

## 🛠️ Technical Details

- **Pure HTML5 Canvas**: No external game engines
- **Vanilla JavaScript**: No frameworks required
- **LocalStorage**: Persistent save system
- **Web Audio API**: Dynamic sound generation
- **Responsive**: Adapts to different screen sizes

## 📱 Mobile Support

The game includes touch controls for mobile devices:
- Virtual buttons for movement
- Touch controls for attacks
- Optimized UI for smaller screens

## 🔧 Development

### Project Structure
```
StickMan/
├── index.html          # Main game file (all-in-one)
├── package.json        # NPM dependencies (optional)
├── webpack.config.js   # Webpack config (optional)
├── src/                # Phaser version (optional)
└── README.md          # This file
```

### Technologies Used
- HTML5 Canvas
- JavaScript ES5
- CSS3
- Web Audio API
- LocalStorage API

## 🎯 Tips & Tricks

1. **Master Perfect Parry**: Timing is everything - practice the 0.2s window
2. **Build Combos**: Chain attacks for massive damage bonuses
3. **Use Air Juggling**: Launch enemies and keep them airborne
4. **Unlock Life Steal**: Essential for survival mode
5. **Complete Daily Challenges**: Easy way to earn extra coins
6. **Experiment with Weapons**: Each has unique special attacks
7. **Save Ultimate**: Use it strategically in tough fights
8. **Customize Controls**: Find what works best for you

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork, modify, and submit pull requests!

## 🎮 Credits

Inspired by Shadow Fight 2 by Nekki

---

**Enjoy the fight! 🥊**
