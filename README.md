# Crystal Match (HTML, CSS, JavaScript)

A captivating browser-based match-3 puzzle game built entirely with **HTML**, **CSS**, and **vanilla JavaScript**. Match colorful crystals in this addictive gem-matching adventure featuring **100 challenging levels**, stunning SVG graphics, and progressive difficulty!

-----

## 💎 Features

* **100 Unique Levels:** Progressive difficulty with increasing challenges and crystal types.
* **6 Beautiful Crystal Types:** Match diamonds, emeralds, sapphires, topazes, amethysts, and rubies with gorgeous SVG graphics.
* **Star Rating System:** Earn up to 3 stars per level based on your score performance.
* **Strategic Gameplay:** Limited moves per level-plan ahead to reach the target score!
* **Smart Hints:** Get helpful suggestions when you're stuck.
* **Board Shuffle:** Rearrange crystals when no valid moves are available.
* **Auto-Save Progress:** Your game state is automatically saved-never lose your progress!
* **Cascading Matches:** Chain reactions give bonus points for strategic combos.
* **Level Selection:** Jump to any unlocked level and replay for better scores.
* **Responsive Design:** Optimized for desktop, tablet, and mobile devices with touch controls.
* **Smooth Animations:** Polished visual effects for matches, swaps, and cascades.

-----

## 🚀 Getting Started

### Play Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/crystalmatch/crystalmatch.github.io
   ```

2. Navigate to the project folder:

   ```bash
   cd crystalmatch.github.io
   ```

3. Open `index.html` in your browser.

That's it! No build tools or server required.

## 🌐 Play Online

You can play the latest version live here: **[crystalmatch.github.io](https://crystalmatch.github.io)**

-----

## 🎮 How to Play

### Objective
Match 3 or more crystals of the same type to score points and reach the target score before running out of moves!

### Controls
* **Tap/Click** a crystal to select it
* **Tap/Click** an adjacent crystal to swap them
* Create matches of 3 or more crystals in a row (horizontal or vertical)
* Cascading matches give bonus points and multiply your score!

### Scoring
* **3 crystals** = 50 points
* **4+ crystals** = bonus points
* **Cascade combos** multiply your score
* **Higher levels** give more points per match

### Star Ratings
* ⭐ Complete the level (reach target score)
* ⭐⭐ Score 1.5x the target
* ⭐⭐⭐ Score 2x the target

### Tips
* Look for potential cascading matches
* Use the hint button when stuck (💡)
* Shuffle the board if no moves are available (🔄)
* Plan your moves ahead to create powerful combos
* Replay levels to earn all 3 stars!

-----

## 📁 Project Structure

```
index.html       # Complete game implementation (HTML, CSS, JavaScript)
favicon.ico      # Game favicon
README.md        # This file
```

-----

## 💻 Technologies Used

* **HTML5** for the game structure and grid layout
* **CSS3** for responsive design, animations, and gradient effects
* **JavaScript (ES6+)** for all game logic including:
  * Match detection algorithm
  * Board generation and validation
  * Cascade and gravity physics
  * Level progression system
  * Local storage for save states
  * Touch and click event handling
* **SVG Graphics** for crisp, scalable crystal designs

-----

## 🎨 Game Mechanics

### Crystal Types
The game features 6 distinct crystal types, introduced progressively:
* **Diamond** (Red) - Available from Level 1
* **Emerald** (Green) - Available from Level 1
* **Sapphire** (Blue) - Available from Level 1
* **Topaz** (Yellow) - Available from Level 20
* **Amethyst** (Purple) - Available from Level 40
* **Ruby** (Orange) - Available from Level 60

### Level Progression
* **Levels 1-19:** 3 crystal types, 25 moves
* **Levels 20-39:** 4 crystal types, 23 moves
* **Levels 40-59:** 5 crystal types, 21 moves
* **Levels 60-100:** 6 crystal types, 15-20 moves
* Target score increases by 150 points per level

### Features
* **Match Detection:** Intelligent algorithm detects all horizontal and vertical matches
* **Gravity System:** Crystals fall naturally to fill empty spaces
* **Cascade Mechanics:** Chain reactions automatically trigger after initial matches
* **Move Validation:** Only valid swaps that create matches are allowed
* **No Dead Ends:** Board automatically shuffles if no valid moves exist
* **Progress Tracking:** Best scores and star ratings saved per level

-----

## 📱 Browser Compatibility

* ✅ Chrome/Edge (recommended)
* ✅ Firefox
* ✅ Safari (desktop & mobile)
* ✅ Mobile browsers (iOS Safari, Chrome Mobile)

Optimized for screens from 320px to 4K displays with responsive breakpoints.

-----

## 💾 Local Storage

The game uses browser Local Storage to save:
* Current game state (board, score, moves, level)
* Unlocked levels
* Best scores per level
* Star ratings per level
* Auto-saves every 5 seconds and on page visibility change

-----

## 📄 License

This project is released under the **MIT License**.

-----

## 🙏 Acknowledgments

* Inspired by classic match-3 games like Bejeweled and Candy Crush
* Designed with pure vanilla JavaScript—no frameworks needed!
* SVG crystal graphics created with CSS gradients for a polished look

-----

## 🛠️ Future Enhancements

Potential features for future versions:
* Special power-up crystals (bomb, lightning, rainbow)
* Timed challenge mode
* Daily challenges
* Sound effects and background music
* Social sharing of high scores
* Dark mode theme
* Additional game modes (endless, puzzle)

-----

## 🐛 Bug Reports & Contributions

Found a bug or have a suggestion? Feel free to:
* Open an issue on GitHub
* Submit a pull request
* Contact the developer

-----

**Enjoy matching crystals and challenge yourself to complete all 100 levels!** 💎✨
