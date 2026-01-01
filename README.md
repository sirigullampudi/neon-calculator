# ⚡simple Calculator

A futuristic, cyberpunk-themed calculator with stunning neon visual effects, smooth animations, and interactive features.

## Features

### Visual Design
- **Neon Glow Effects**: Authentic LED-style glowing buttons with smooth transitions
- **Cyberpunk Aesthetic**: Dark gradient background with animated grid overlay
- **Smooth Animations**: 
  - Hover effects with scale transitions
  - Ripple click effects
  - Display glow animations
  - Pulsing container glow
  - Status bar animations

### Functionality
- **Basic Operations**: Addition (+), Subtraction (−), Multiplication (×), Division (÷)
- **Advanced Features**:
  - Decimal point support
  - Delete/backspace button (⌫)
  - Clear button (AC) to reset
  - Smart number formatting
  - Display length limitation with exponential notation

### Interactive Elements
- **Color-Coded Buttons**:
  - 🔵 Numbers → Neon Blue
  - 💜 Operators → Neon Pink/Purple
  - 💚 Equals → Neon Green
  - ❤️ Clear → Neon Red
  - 🔷 Decimal → Cyan

- **Sound Feedback** (Toggle): Optional click sounds using Web Audio API
- **Mood Themes** (4 Themes):
  - **Cyan Vibes** (Default) - Classic cyan neon
  - **Synthwave** - Pink-dominated neon
  - **Matrix** - Green dominant neon
  - **Vaporwave** - Purple/Blue dominant neon

- **Idle Status Display**: Shows "⚡ Ready" when inactive, updates during calculations

## Tech Stack

- **HTML5**: Semantic structure
- **CSS3**: Advanced styling with animations, gradients, and effects
- **JavaScript (ES6+)**: OOP with class-based calculator logic
- **Web Audio API**: Sound feedback synthesis

**No external dependencies or libraries required!**

## Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/neon-calculator.git
cd neon-calculator
```

2. Open in browser:
```bash
# Simply open the index.html file in any modern web browser
open index.html
```

Or use a local server:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (using http-server)
npx http-server
```

Then navigate to `http://localhost:8000`

## Usage

- **Numbers**: Click number buttons (0-9) to input values
- **Operations**: Click operator buttons (+, −, ×, ÷) to perform calculations
- **Decimal**: Click the decimal button (.) to add decimal points
- **Delete**: Click the backspace button (⌫) to remove the last digit
- **Clear**: Click AC to reset the calculator
- **Equals**: Click = to get the result
- **Sound Toggle**: Enable/disable click sound effects
- **Mood Selector**: Switch between 4 neon color themes

## Code Structure

```
neon-calculator/
├── index.html           # Main HTML file with embedded CSS and JS
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── .gitignore          # Git ignore file
```

### Key JavaScript Classes

#### NeonCalculator
Main calculator class handling:
- Event listeners and button interactions
- Calculator state management
- Display updates and animations
- Sound synthesis and playback
- Theme switching
- Idle status monitoring

## Browser Compatibility

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features in Detail

### Animation System
- **Container Pulse**: Subtle glowing animation (4s cycle)
- **Display Glow**: Dynamic text shadow enhancement on input
- **Status Pulse**: Smooth color transition on activity
- **Button Hover**: Scale and glow increase on hover
- **Ripple Effect**: Click ripple animation using pseudo-elements
- **Equals Flash**: Special flash effect on calculation

### Sound System
- Web Audio API for real-time sound synthesis
- 800Hz sine wave tone
- 100ms duration with exponential fade
- Optional toggle switch with visual feedback

### Theme System
Dynamic CSS class switching:
- `.mood-synthwave`: Pink neon theme
- `.mood-matrix`: Green neon theme
- `.mood-vaporwave`: Purple neon theme
- Default (no class): Cyan neon theme

### Responsive Design
- Mobile-optimized layout
- Touch-friendly button sizing
- Adaptive font sizes
- Works on screens from 320px to 4K+

## Performance

- Pure CSS animations (no JavaScript animation loops)
- Efficient DOM queries with `querySelectorAll`
- Event delegation where applicable
- Minimal repaints and reflows
- GPU-accelerated transforms and filters

## Future Enhancements

- [ ] Keyboard input support
- [ ] Calculation history display
- [ ] Advanced operations (percentage, square root, power)
- [ ] Dark/Light mode toggle
- [ ] Additional color themes
- [ ] Desktop app wrapper (Electron)
- [ ] PWA support for offline use

## License

MIT License © 2026 - See [LICENSE](LICENSE) file for details

## Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Support

For issues, feature requests, or suggestions, please open an issue on GitHub.

## Author

Created with ⚡ for cyberpunk enthusiasts and calculator lovers.

---

**Enjoy your futuristic calculator experience!**
