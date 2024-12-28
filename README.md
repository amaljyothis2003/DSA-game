# The Adventures of Detective Hash

## Overview
"The Adventures of Detective Hash" is an interactive web-based mystery game that combines engaging storytelling with computer science concepts, specifically hash tables and data organization. Set in the futuristic city of Cryptopolis, players take on the role of Detective Hash to solve the mysterious theft of the Emerald Crown using the innovative HashTable-O-Matic device.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Game Structure](#game-structure)
- [How to Play](#how-to-play)
- [Technical Implementation](#technical-implementation)
- [Development](#development)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [Troubleshooting](#troubleshooting)

## Features
- **Interactive Gameplay**: Drag-and-drop evidence organization system
- **Story-Driven Experience**: Rich narrative with character dialogue and chapter progression
- **Visual Design**: Cyberpunk noir aesthetic with modern UI elements
- **Educational Content**: Learn about hash tables and data structures while playing
- **Scoring System**: Track progress and earn detective ranks
- **Multiple Chapters**: Progressive story development with increasing complexity
- **Collision Resolution**: Learn different strategies for handling hash collisions
- **Responsive Design**: Playable on various screen sizes

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/detective-hash-game.git
cd detective-hash-game
```

2. Open `index.html` in a modern web browser:
- Chrome (recommended, version 88+)
- Firefox (version 85+)
- Safari (version 14+)
- Edge (version 88+)

No additional installation or server setup is required as the game runs entirely in the browser.

## Game Structure

### Chapters
1. **The Museum Break-in**
   - Introduction to the case
   - Basic evidence organization
   - Time-based challenges

2. **The Encryption Collision**
   - Advanced hash table mechanics
   - Collision resolution strategies
   - Pattern recognition challenges

3. **The Final Decode**
   - Complex evidence analysis
   - Multi-step puzzle solving
   - Case resolution

### Game Mechanics
- **HashTable-O-Matic**: Virtual device for organizing and analyzing evidence
- **Evidence Classification**: Sort clues using hash functions
- **Time Management**: Complete tasks within specified time limits
- **Scoring System**: Points awarded for accuracy and speed
- **Detective Ranks**: Progress from Rookie to Master Detective

## How to Play

### Basic Controls
- **Mouse/Touch**: Drag and drop clues
- **Click/Tap**: Select options and navigate menus
- **Keyboard**: Shortcuts available for desktop users (see below)

### Keyboard Shortcuts
- `Space`: Pause/Resume game
- `Esc`: Open menu
- `R`: Restart current level
- `H`: Show hints (when available)

### Game Objectives
1. Organize evidence using the HashTable-O-Matic
2. Solve collision puzzles using different strategies
3. Complete levels within the time limit
4. Achieve the highest possible detective rank
5. Uncover the mystery of the stolen Emerald Crown

## Technical Implementation

### Technologies Used
- HTML5
- CSS3 (with modern features like CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- Local Storage for game progress

### Key Components
- **Drag and Drop API**: Native HTML5 implementation
- **Animation System**: CSS animations and transitions
- **State Management**: JavaScript-based game state handling
- **Responsive Design**: CSS Grid and media queries
- **Story Engine**: JSON-based dialogue and narrative system

## Development

### Setup Development Environment
1. Install a code editor (VS Code recommended)
2. Install Live Server extension for local development
3. Enable developer tools in your browser

### Building and Testing
```bash
# Run local server (if using VS Code Live Server)
# Right-click index.html and select "Open with Live Server"

# Run tests (if implemented)
npm run test
```

### Code Style
- Follow JavaScript Standard Style
- Use meaningful variable and function names
- Comment complex logic and algorithms
- Maintain consistent indentation (2 spaces)

## File Structure
```
detective-hash/
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   ├── game.js
│   │   ├── story.js
│   │   └── utils.js
│   └── images/
├── docs/
└── README.md
```

## Dependencies
- No external libraries required
- Built with vanilla JavaScript
- Modern browser with ES6 support required

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to the branch
5. Create a Pull Request

### Guidelines
- Follow the existing code style
- Add comments for complex logic
- Update documentation as needed
- Test thoroughly before submitting

## Troubleshooting

### Common Issues
1. **Game Not Loading**
   - Check browser compatibility
   - Clear cache and reload
   - Enable JavaScript

2. **Drag and Drop Not Working**
   - Verify browser support
   - Check touch screen compatibility
   - Clear browser data

3. **Performance Issues**
   - Close unnecessary browser tabs
   - Check system resources
   - Update browser to latest version

### Support
For additional support:
- Open an issue on GitHub
- Contact: support@detectivehash.game
- Check the wiki for more information

---

## License
MIT License - See LICENSE.md for details

## Credits
- Game Design: [Your Name]
- Story: [Your Name]
- Programming: [Your Name]
- Visual Design: [Your Name]

## Version History
- v1.0.0: Initial release
- v1.1.0: Added collision resolution mechanics
- v1.2.0: Enhanced visual design and story elements

---
Last Updated: December 2024
