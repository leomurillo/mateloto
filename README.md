# Mateloto 🎯

A digital implementation of Mateloto, a multiplication bingo game invented by Willy Gerardo Murillo Rivas in Costa Rica during the 1980s. This educational game helps children learn multiplication tables while having fun.

[Demo](https://xplorandia.com/mateloto.html) | [Print Version](https://xplorandia.com/mateloto-printer.html)

## 🎮 About Mateloto

Mateloto combines the excitement of bingo with multiplication practice. Players have scorecards with 24 multiplication results and try to achieve winning patterns (5 in a row, four corners, or full card) as a caller announces multiplication problems.

### Features

- 🌐 **Bilingual**: English and Spanish support
- 📱 **Responsive**: Works on desktop and mobile devices
- 🎯 **Three Game Modes**:
  - **Caller Mode**: For calling out multiplication problems
  - **Player Mode**: For playing with a scorecard
  - **Both Mode**: Combined caller and player experience
- 🔄 **Sync System**: QR codes and manual codes for synchronization
- 🖨️ **Print Support**: Generate physical scorecards and problem sheets
- ↩️ **Undo/Redo**: Full history support for player moves
- 🏆 **Multiple Win Conditions**: Rows, columns, diagonals, four corners, full card

## 🚀 Quick Start

### Play Online
Simply open `mateloto.html` in a web browser. No installation required!

### Print Materials
Use `mateloto-printer.html` to generate:
- Multiplication problem sheets for callers
- Scorecards for players (1, 2, or 4 per page)

## 📖 How to Play

1. **As a Caller**: 
   - Click "Siguiente" to call the next multiplication
   - Use arrows to review previous calls
   - Share sync code with players

2. **As a Player**:
   - Mark results on your scorecard as they're called
   - Use the answer input to verify your math
   - Sync with the caller using QR codes

3. **Win Conditions**:
   - 5 in a row (horizontal, vertical, or diagonal)
   - Four corners
   - Full card

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript (no build process required)
- No external dependencies for core game
- Uses QRCode.js for QR generation
- Uses jsQR for QR scanning
- Combinatorial algorithm for 393,693,300 unique scorecards

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Credits

- **Original Game**: Invented and patented by Willy Gerardo Murillo Rivas
- **Digital Version**: Developed by Leonardo Murillo, [Xplorandia](https://xplorandia.com)
- **Based on**: The original Mateloto game sold in Costa Rican schools

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Areas for Contribution
- Additional language translations
- Accessibility improvements
- New visual themes
- Sound effects
- Tournament mode
- Statistics tracking

## 🐛 Bug Reports

Please use the [GitHub Issues](https://github.com/yourusername/mateloto/issues) page to report bugs.

## 📱 Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers with camera support (for QR scanning)

---

*Mateloto - Making multiplication fun since the 1980s!* 🌟
