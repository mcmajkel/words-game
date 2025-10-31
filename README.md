# 🎲 Polish Word Guessing Game

A fun, interactive learning game for 5-year-old children to guess Polish words by letter and category!

## 🎮 Features

- **8 Categories:** Fruits (Owoce), Vegetables (Warzywa), Animals (Zwierzęta), Cars (Auta), Colors (Kolory), Home (Dom), Clothing (Ubiór), Sports (Sport)
- **2,500+ Polish Words:** Comprehensive database covering all letters A-Z with Polish characters (Ą, Ć, Ę, Ł, Ń, Ó, Ś, Ź, Ż)
- **Smart Randomization:** Only shows letter/category combinations that have available words
- **Category Selection:** Choose which categories to play with - toggle between selecting all or none
- **Hint System:** Click "Podpowiedź" (Hint) button to see all available words
- **Answer Validation:** Game checks if the answer starts with the correct letter and exists in the category
- **Auto-Advance:** Moves to next round automatically after correct answer
- **Dark Mode:** Toggle between light and dark themes with persistent preference storage
- **Beautiful UI:** Colorful, kid-friendly interface with smooth animations
- **Fully Responsive:** Works on mobile, tablet, and desktop

## 🚀 Quick Start

### Play Online
Visit the live game: **[Polish Word Game](https://jade-sunshine-33d783.netlify.app/)**

Or use the short URL: **[tinyurl.com/stasiozagadki](https://tinyurl.com/stasiozagadki)**

### Play Locally
1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. No installation or build process needed!

## 📋 How to Play

1. **Click "🎲 WYLOSUJ LITERĘ I KATEGORIĘ!"** - Randomly selects a letter and category
2. **Choose Categories** - Click the toggle button to show/hide categories, then check/uncheck what you want
3. **Click "✓ Wszystkie"** - Quick button to select all or none
4. **Type your answer** - Enter a Polish word that starts with the letter from the selected category
5. **Press Check or Enter** - Game validates your answer
6. **Get Hints** - Click "💡 Podpowiedź" if stuck to see all available words
7. **View Words** - Click "👀 Pokaż / Ukryj Słowa" to see the complete word list for that letter

## 🗂️ Project Structure

```
drawing-game/
├── index.html          # Complete game (all CSS, JS, and data embedded)
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── .git/               # Git repository
```

## 🎨 Customization

### Add More Words

Edit the `wordsDatabase` in `index.html`. Structure:

```javascript
"categoryName": {
  "A": ["word1", "word2", "word3"],
  "B": ["word1", "word2"],
  ...
}
```

### Change Colors

Modify CSS variables in the `<style>` section:
- Primary color: `#667eea` (purple)
- Success color: `#51cf66` (green)
- Error color: `#ff6b6b` (red)

### Add New Categories

1. Add to `allCategories` array
2. Add icon and name to `categoryNames` object
3. Add word database object
4. Add checkbox HTML in categories pane

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies, no build process
- **Embedded Database** - All 2,500+ words included in single file (53KB)
- **Responsive Design** - Mobile-first CSS with media queries
- **Accessibility** - Keyboard support, proper labels, good contrast

## 📱 Browser Support

- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment

### Netlify (Recommended - Easiest)

1. Push code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click "New site from Git"
4. Connect GitHub repository
5. Deploy automatically!

### GitHub Pages

1. Go to repository Settings
2. Scroll to "GitHub Pages"
3. Select main branch as source
4. Site published at `https://username.github.io/word-game-for-son/`

### Manual Hosting

- Upload `index.html` to any web server
- No special requirements needed

## 📊 Game Statistics

| Category | Words | Icon |
|----------|-------|------|
| Zwierzęta (Animals) | 515 | 🦁 |
| Dom (Home) | 432 | 🏠 |
| Owoce (Fruits) | 353 | 🍎 |
| Warzywa (Vegetables) | 279 | 🥕 |
| Kolory (Colors) | 259 | 🎨 |
| Auta (Cars) | 249 | 🚗 |
| Ubiór (Clothing) | 229 | 👕 |
| Sport (Sports) | 214 | ⚽ |
| **TOTAL** | **2,530** | **🎮** |

## 👨‍👩‍👧‍👦 For Parents/Teachers

Perfect for:
- Learning Polish vocabulary
- Understanding word patterns and letter associations
- Building confidence in reading and spelling
- Fun educational screen time for young learners (5+)

The game encourages:
- Active vocabulary building
- Pattern recognition
- Spelling awareness
- Category organization skills
- Problem-solving

## 🐛 Known Limitations

- Game requires JavaScript enabled
- Category selection resets on page refresh
- No persistent statistics/scoring
- Polish diacritical marks case-sensitive (lowercase "a" ≠ uppercase "A")

## 📝 License

Created for educational purposes. Free to use, modify, and distribute.

## 🎯 Future Ideas

- [ ] Add sound effects and background music
- [ ] Implement scoring system
- [ ] Add difficulty levels
- [ ] Include more categories
- [ ] Add more word variations
- [ ] Multi-language support
- [ ] Add timer/speed challenges

## 👤 Author

Created as a fun learning tool for young Polish learners.

---

**Happy learning! Have fun playing! 🎉**
