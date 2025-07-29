# Daily Micro Habit

A fully offline, static website that helps you build better habits through small, manageable daily actions. Built with pure HTML, CSS, and vanilla JavaScript - no external dependencies required!

## 🚀 Features

- **100+ Unique Micro Habits**: A curated collection of simple, actionable habits
- **Motivational Quotes**: Inspirational quotes to keep you motivated
- **7-Step Progress Tracker**: Visual progress bar that resets every 7 habits
- **Dark/Light Mode**: Toggle between themes with persistent preference saving
- **Smooth Animations**: Engaging fade-in and bounce animations
- **Sound Effects**: Audio feedback on button clicks (ding.mp3)
- **Mobile Responsive**: Works perfectly on desktop and mobile devices
- **Offline First**: No internet connection required after initial load
- **Accessibility**: Keyboard navigation and screen reader friendly

## 📁 File Structure

```
Daily-Micro-Habit/
├── index.html          # Main HTML structure
├── style.css           # Styling and responsive design
├── script.js           # All JavaScript functionality
├── ding.mp3           # Sound effect file (you need to add this)
└── README.md          # This file
```

## 🔧 Setup Instructions

1. **Clone or Download** the project files to your local machine
2. **Add Sound File**: Place a `ding.mp3` file in the root directory (same folder as index.html)
3. **Open with Live Server**: 
   - Install the "Live Server" extension in Visual Studio Code
   - Right-click on `index.html` and select "Open with Live Server"
   - Or simply open `index.html` in any modern web browser

## 🎯 How to Use

1. **Get a Habit**: Click "Show Another Habit" to receive a random micro habit
2. **Read the Quote**: Each habit comes with a motivational quote
3. **Track Progress**: Watch your progress bar fill up (resets after 7 habits)
4. **Toggle Theme**: Use the switch in the top-right corner for dark/light mode
5. **Keyboard Shortcuts**: 
   - Press `T` to toggle theme
   - Press `Enter` or `Space` when button is focused to get new habit

## 📱 Mobile Support

The app is fully responsive and includes:
- Touch-friendly button interactions
- Optimized layout for small screens
- Smooth animations on mobile devices
- Proper viewport scaling

## 🔊 Sound Requirements

**Important**: You need to manually add a `ding.mp3` file to the project folder. The app will attempt to play this sound when you click the button. If the file is missing, the app will still work but without sound effects.

You can:
- Record your own ding sound
- Download a free sound effect from sites like Freesound.org
- Use any short audio file (rename it to `ding.mp3`)

## 🌟 Example Micro Habits

- "Drink a glass of water"
- "Do 10 pushups"
- "Write down one thing you're grateful for"
- "Stretch for 1 minute"
- "Smile at yourself in the mirror"
- "Take 5 deep breaths"
- And 100+ more!

## 🎨 Customization

### Adding More Habits
Edit the `microHabits` array in `script.js` to add your own habits:

```javascript
const microHabits = [
    "Your custom habit here",
    // ... existing habits
];
```

### Adding More Quotes
Edit the `motivationalQuotes` array in `script.js`:

```javascript
const motivationalQuotes = [
    "Your inspiring quote here - Author",
    // ... existing quotes
];
```

### Changing Colors
Modify the CSS variables in `style.css`:

```css
:root {
    --primary-color: #4A90E2;     /* Main brand color */
    --secondary-color: #F39C12;   /* Accent color */
    /* ... other variables */
}
```

## 🔧 Technical Details

- **Pure Vanilla JavaScript**: No frameworks or libraries
- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Custom Properties**: For theming and easy customization
- **Local Storage**: Saves theme preference and progress
- **Progressive Enhancement**: Works even if JavaScript fails
- **Modern CSS**: Uses CSS animations, transitions, and transforms

## 🌐 Browser Compatibility

Works on all modern browsers including:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to:
- Add more micro habits to the array
- Improve the design
- Add new animations
- Enhance accessibility features
- Report bugs or suggest improvements

## 💡 Tips for Success

1. **Start Small**: These are micro habits for a reason - they should take 1-5 minutes max
2. **Be Consistent**: Try to complete at least one habit daily
3. **Celebrate Progress**: The progress bar is there to celebrate your wins!
4. **Mix It Up**: Use different types of habits (physical, mental, social, etc.)
5. **Build Momentum**: Use these micro habits as stepping stones to larger goals

---

**Build better habits, one micro step at a time! 🌱**