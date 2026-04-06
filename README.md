# Pig-Game

A simple and fun two-player dice game built with HTML, CSS, and JavaScript.
Players take turns rolling the dice and can either keep rolling to increase their score or hold to save it.
Rolling a 1 resets the current score and passes the turn. The first to reach 100 points wins! 🏆

## Live Demo

## How the Game Works

1. The game starts with Player 1.
2. On a turn, the player rolls the dice:
   - The dice number is added to their current score.
   - If they roll a 1, their current score resets and the turn switches to the other player.
3. The player can choose to “Hold” at any time:
   - Their current score is added to their total score.
   - The turn then passes to the other player.
4. The first player to reach 100 points wins the game! 🎉

## Features

- 🎲 Random dice roll simulation using Math.random()
- 🔄 New Game button to reset scores and start fresh
- 👥 Two-player system with active player highlight
- 🏆 Winning state display with styled highlight
- 🎨 Modern UI with gradient background, blur effects, and smooth transitions
- 📱 Responsive design that adapts to different screen sizes

## Technologies Used

- HTML5 → Game layout and structure
- CSS3 → Styling, layout, gradients, and transitions
- JavaScript (ES6) → Game logic, score tracking, DOM updates, and user interaction

## Learning Goals

This project was built to:

- Practice JavaScript fundamentals (functions, conditionals, loops, arrays).
- Gain hands-on experience with DOM manipulation.
- Work with event listeners and handle real-time user interaction.
- Understand state management in small projects.
- Improve frontend design skills with clean CSS and user-focused layout.

## Future Improvements

- 🎨 Add sound effects for dice rolls and winning
- 📱 Improve mobile responsiveness further
- 🎯 Allow customizable winning score (instead of fixed 100)
- 🔀 Add a single-player mode vs. computer AI
