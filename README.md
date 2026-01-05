# Pixel Harmony - Professional Animated Puzzle Game

![Pixel Harmony Puzzle Game](https://img.shields.io/badge/Puzzle-Game-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

A beautifully animated sliding puzzle game with professional visual design, smooth animations, and engaging gameplay. Built with pure HTML, CSS, and JavaScript.

![Game Screenshot](https://via.placeholder.com/800x450/1a1a2e/ffffff?text=Pixel+Harmony+Puzzle+Game)

## 🎮 Features

### **Professional Visual Design**
- Modern gradient-based UI with glassmorphism effects
- Responsive layout that works on desktop and mobile devices
- Particle background animation system
- Smooth transitions and hover effects

### **Engaging Gameplay**
- 3x3 sliding puzzle mechanics
- Three difficulty levels (Easy, Medium, Hard)
- Move counter and timer with professional styling
- Hint system for strategic assistance
- Auto-solve demonstration feature

### **Advanced Animations**
- Smooth tile sliding with custom easing functions
- Win celebration with trophy animation
- Interactive particle system
- Pulsing effects and visual feedback

### **User Experience**
- Intuitive controls with both mouse and keyboard support
- Clear visual indicators for available moves
- Responsive feedback for all interactions
- Professional statistics tracking

## 🚀 How to Play

1. **Objective**: Arrange the numbered tiles in order (1-8) with the empty space in the bottom-right corner
2. **Controls**:
   - Click on tiles adjacent to the empty space to move them
   - Use arrow keys (↑, ↓, ←, →) for keyboard control
3. **Game Interface**:
   - **Timer**: Tracks your completion time
   - **Moves**: Counts each tile movement
   - **Difficulty**: Adjusts shuffle complexity

## 📁 Project Structure

```
Pixel-Harmony-Puzzle/
│
├── index.html          # Main game file (all-in-one HTML/CSS/JS)
├── README.md           # This documentation file
│
└── (No external dependencies required)
```

## 💻 Installation & Usage

### **Option 1: Direct File Open**
1. Download the `index.html` file
2. Open it directly in any modern web browser
3. No installation or setup required

### **Option 2: Online Deployment**
1. Upload to any static web hosting service (GitHub Pages, Netlify, Vercel, etc.)
2. The game works immediately without any build process

### **Option 3: Local Development**
```bash
# Clone or download the project
git clone [repository-url]

# Navigate to the project folder
cd Pixel-Harmony-Puzzle

# Open the game in your default browser
# On Windows:
start index.html
# On macOS:
open index.html
# On Linux:
xdg-open index.html
```

## 🎯 Game Controls

| Control | Action |
|---------|--------|
| **Mouse Click** | Move adjacent tile to empty space |
| **Arrow Keys** | Move tiles in direction (keyboard control) |
| **Shuffle Button** | Randomize puzzle tiles |
| **Hint Button** | Highlight possible moves |
| **Auto-Solve** | Demonstration of solving algorithm |
| **Difficulty Buttons** | Change puzzle complexity |

## 🎨 Visual Features

### **Color Scheme**
- Primary: `#6c5ce7` to `#a29bfe` (gradient purple)
- Background: `#1a1a2e` to `#16213e` (dark gradient)
- Accents: Glassmorphism effects with transparency

### **Animations**
- **Tile Movement**: Smooth sliding with cubic-bezier easing
- **Particle System**: Floating background elements
- **UI Transitions**: Fade, slide, and scale animations
- **Win Celebration**: Trophy pulse animation

### **Responsive Design**
- Adapts to screen sizes from 320px to 1920px+
- Touch-optimized for mobile devices
- Flexible grid and flexbox layouts

## 🔧 Technical Implementation

### **Core Technologies**
- **HTML5**: Semantic structure and game container
- **CSS3**: Grid layout, animations, and responsive design
- **Vanilla JavaScript**: Game logic, state management, and DOM manipulation

### **Key Algorithms**
```javascript
// 1. Shuffle Algorithm
// Performs random valid moves to ensure solvability

// 2. Move Validation
// Checks adjacency to empty space before allowing movement

// 3. Win Condition Check
// Verifies all tiles are in correct positions

// 4. Animation System
// CSS custom properties for smooth tile transitions
```

### **Performance Features**
- Optimized DOM updates with minimal reflows
- Efficient event delegation
- CSS hardware acceleration for animations
- Debounced user interactions

## 📱 Browser Compatibility

| Browser | Status | Notes |
|---------|--------|-------|
| Chrome 60+ | ✅ Fully Supported | Optimal performance |
| Firefox 55+ | ✅ Fully Supported | All features working |
| Safari 12+ | ✅ Fully Supported | Minor animation differences |
| Edge 79+ | ✅ Fully Supported | All features working |
| Mobile Browsers | ✅ Fully Supported | Touch-optimized |

## 🛠️ Customization

### **Changing Difficulty**
Modify the shuffle complexity in the JavaScript:
```javascript
// In shufflePuzzle() function
case 'easy': shuffleMoves = 20;
case 'medium': shuffleMoves = 50;
case 'hard': shuffleMoves = 100;
```

### **Customizing Visuals**
Edit CSS variables for different themes:
```css
/* Primary color scheme */
:root {
  --primary-color: #6c5ce7;
  --secondary-color: #a29bfe;
  --bg-gradient: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
}
```

### **Adding Images**
Replace gradient backgrounds with actual images:
```javascript
// In initPuzzle() function
tile.style.backgroundImage = 'url("your-image.jpg")';
tile.style.backgroundSize = '400px 400px';
tile.style.backgroundPosition = `${-col * 400}px ${-row * 400}px`;
```

## 🏆 Achievements System

The game tracks:
- **Completion Time**: Fastest solve records
- **Move Efficiency**: Minimum moves to solve
- **Difficulty Progression**: Track performance across levels

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### **Areas for Improvement**
- Add multiplayer/competitive mode
- Implement image-based puzzles
- Create level progression system
- Add sound effects and background music
- Implement save/load functionality

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Font Awesome** for iconography
- **Google Fonts** for typography
- **CSS Gradient** for background inspiration
- **All contributors** and testers

## 📧 Contact

For questions, suggestions, or feedback:
- Create an issue in the GitHub repository
- Email: [your-email@example.com]
- Twitter: [@yourhandle]

---

<div align="center">
  <p>Made with ❤️ by <b>Pixel Harmony Team</b></p>
  <p>If you enjoy this game, please give it a ⭐ on GitHub!</p>
</div>
