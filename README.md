# 🎲 Tenzies Game

A fun and interactive dice game built with React! The goal is to **roll until all dice show the same number** while allowing the user to "hold" dice between rolls. Once all dice are the same, the game automatically highlights the victory with **confetti animation**. 🚀

## ✨ Features

- 🎯 **Interactive Gameplay**: Click on dice to hold them and roll the rest.
- 🎊 **Confetti Celebration**: Winning triggers a confetti effect!
- 🎮 **Keyboard Accessibility**: The "New Game" button is auto-focused upon victory for better UX.
- ⚡ **Optimized State Management**: Efficient use of React Hooks for smooth rendering.
- 🎲 **Randomized Dice Rolls**: Ensures every game is unique and engaging!

## 🚀 Technologies Used

- ⚛️ **React** - Core library for building UI components.
- 🎲 **useState Hook** - Manages dice states dynamically.
- 🎯 **useRef Hook** - Focuses the "New Game" button when the game is won.
- 🔄 **useEffect Hook** - Watches for game completion and triggers focus changes.
- ✨ **Confetti Library** - Adds a fun celebration effect upon victory.
- 🆔 **nanoid** - Generates unique IDs for dice elements.

## 🎮 How the Game Works

1. 🎲 The game starts with 10 dice showing random values.
2. 🔒 Click on a die to "hold" its value while rolling the others.
3. 🔄 Press "Roll" to re-roll unheld dice.
4. 🏆 Win the game when all dice show the same number!
5. 🎊 Confetti animation appears, and "New Game" button is automatically focused.
6. 🔄 Press "New Game" to restart and play again!

## 🏗️ Component Breakdown

### **App Component**
- Manages game state, dice values, and win conditions.
- Uses **useState** for dice management.
- Uses **useEffect** to focus on the "New Game" button when the game is won.
- Implements dice rolling and holding mechanics.

### **Die Component**
- Displays an individual die with a dynamic background color.
- Uses **props** to determine value and hold state.
- Implements **aria-labels** for better accessibility.

## 🎯 Accessibility Considerations
- ✅ **Screen Reader Friendly**: Live region updates game status.
- ✅ **Keyboard Navigation**: Auto-focuses the button for easy interaction.
- ✅ **ARIA Attributes**: Improves usability for assistive technologies.

## 🎉 Acknowledgment
This project was inspired by **Scrimba**, a fun and interactive platform for learning web development. Their hands-on approach makes coding enjoyable and effective. Learning by doing is the best way to grow as a developer! 🚀

