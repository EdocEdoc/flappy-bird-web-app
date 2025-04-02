# Simple JavaScript Flappy Bird

A lightweight, browser-based implementation of the classic Flappy Bird game using pure JavaScript, HTML5, and CSS. This single-file game requires no external dependencies and runs directly in your web browser.

## Features

- Complete single-file implementation
- Pure JavaScript with no external libraries
- Responsive design that works on both desktop and mobile devices
- Classic Flappy Bird mechanics:
  - Gravity-affected bird
  - Randomly generated pipes
  - Score tracking
  - Game over detection

## How to Play

1. **Getting Started:**

   - Download the `flappy-bird.html` file
   - Open the file in any modern web browser (Chrome, Firefox, Safari, Edge)
   - Click the "Start Game" button

2. **Controls:**

   - Press the **spacebar** on desktop
   - **Click** or **tap** the screen on mobile devices
   - Each press/tap makes the bird flap its wings and fly upward

3. **Objective:**
   - Navigate the bird through the gaps between pipes
   - Avoid hitting the pipes or the ground
   - Score points by successfully passing through pipe gaps

## Game Mechanics

- The bird constantly falls due to gravity
- Each flap gives the bird upward momentum
- Pipes randomly generate at different heights
- Colliding with pipes or the ground ends the game
- Score increases each time you successfully pass through a pipe gap

## Technical Implementation

This game is built with:

- **HTML5 Canvas** for rendering the game
- **CSS** for styling the interface
- **JavaScript** for game logic and interaction

All components are contained in a single HTML file for simplicity and portability.

## Customization

You can easily customize the game by modifying the JavaScript variables:

- `gravity`: Controls how quickly the bird falls
- `flapStrength`: Controls how high the bird jumps on flap
- `pipeWidth`: Sets the width of pipe obstacles
- `pipeGap`: Controls the gap size between top and bottom pipes
- `pipeSpeed`: Determines how fast pipes move from right to left
- `spawnRate`: Controls how frequently new pipes appear

## Browser Compatibility

Tested and working on:

- Chrome 88+
- Firefox 85+
- Safari 14+
- Edge 88+
- Mobile browsers with touch support

## License

This project is released under the MIT License. Feel free to use, modify, and distribute it as you wish.

## Credits

This implementation was inspired by the original Flappy Bird game created by Dong Nguyen.

## Future Improvements

Potential enhancements for future versions:

- Animated sprites for the bird
- Sound effects and background music
- High score tracking with local storage
- Difficulty levels
- Mobile-optimized touch controls
