# Memory Card Game

A feature-rich, single-file HTML memory card matching game with stunning neon glow design, multiple difficulty levels, and interactive feedback systems. Built with pure HTML5, CSS3, and JavaScript (ES6+).

## Features

- **🎮 Multiple Difficulty Levels** - Choose from Easy (4×3), Medium (4×4), or Hard (6×6) grids
- **✨ Flip Animations** - Smooth 3D card flip animations with visual feedback
- **⏱️ Move Counter & Timer** - Track your performance with real-time statistics
- **⭐ Star Rating System** - Earn 1-3 stars based on your moves and efficiency
- **🎊 Confetti Celebration** - Win animations with confetti burst effects
- **🏆 Local Best Scores** - Persistent high scores saved per difficulty level
- **🔊 Sound Effects** - Audio feedback for flips, matches, and victories
- **💎 Neon Glow Design** - Modern aesthetic with glowing card borders and animations
- **📱 Responsive Grid Layout** - Adapts seamlessly to desktop, tablet, and mobile devices
- **🔄 Shuffle Animation** - Cards shuffle with visual animation at game start

## Installation

No installation required! This is a single-file application.

### Option 1: Direct Download

1. Download the `index.html` file from this repository
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge)

### Option 2: Clone Repository

```bash
git clone https://github.com/yourusername/memory-card-game.git
cd memory-card-game
open index.html
```

### Option 3: Host Online

Upload the `index.html` file to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Any web server

## Usage

1. **Start the Game**: Open `index.html` in your browser
2. **Select Difficulty**: Choose from the difficulty buttons at the top
3. **Play**: Click cards to flip them and find matching pairs
4. **Track Progress**: Monitor your moves, time, and star rating
5. **Win**: Match all pairs to trigger the celebration animation
6. **Play Again**: Click "New Game" to reset and try for a better score

### Game Controls

- **Difficulty Buttons**: Easy (12 cards), Medium (16 cards), Hard (36 cards)
- **New Game Button**: Resets the current game
- **Card Click**: Flips card to reveal emoji

### Scoring System

| Difficulty | 3 Stars | 2 Stars | 1 Star |
|------------|---------|---------|--------|
| Easy       | ≤ 12 moves | ≤ 18 moves | > 18 moves |
| Medium     | ≤ 16 moves | ≤ 24 moves | > 24 moves |
| Hard       | ≤ 36 moves | ≤ 54 moves | > 54 moves |

## Project Structure

```
memory-card-game/
├── index.html          # Single-file application (HTML + CSS + JS)
├── README.md           # Project documentation
└── assets/             # (Optional) Additional resources
    └── sounds/         # Sound effect files (if external)
```

The entire application is contained within a single `index.html` file, making it incredibly portable and easy to deploy.

### Code Architecture

- **HTML**: Semantic structure with game board, controls, and stats display
- **CSS**: Responsive grid layout, neon glow effects, flip animations, and mobile-first design
- **JavaScript**: Game logic including card matching, timer, scoring, local storage, and confetti effects

## Contributing

Contributions are welcome! Please follow these guidelines:

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines

- Maintain single-file architecture (keep everything in `index.html`)
- Follow ES6+ JavaScript standards
- Ensure responsive design works on all screen sizes
- Test across multiple browsers
- Add comments for complex logic
- Preserve the neon glow aesthetic

### Feature Suggestions

- Additional difficulty levels
- Custom card themes
- Multiplayer support
- Accessibility improvements
- Keyboard navigation
- Additional sound effects

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Memory Card Game

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

**Enjoy the game!** 🎮✨