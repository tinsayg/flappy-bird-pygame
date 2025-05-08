# Flappy Bird - Pygame Edition

A modified version of Flappy Bird implemented in Pygame with new gameplay mechanics.

## New Gameplay Features

### Finger-Follow Movement
- Instead of tapping to flap, the bird now follows your mouse/finger position vertically
- Simply move your mouse up and down to control the bird's movement
- The bird will smoothly follow your cursor position
- No more tapping needed - just hover where you want the bird to go

### Slow Mode
- Press the 'S' key to toggle slow mode
- When slow mode is active:
  - Bird moves at half speed
  - Pipes move slower
  - A "SLOW MODE" indicator appears in the top-left corner
- Perfect for players who need more time to react
- Toggle on/off at any time during gameplay

## Controls
- Mouse Movement: Control bird's vertical position
- 'S' Key: Toggle slow mode
- 'P' Key: Pause game
- 'ESC' Key: Quit game

## Requirements
- Python 3.x
- Pygame

## Installation
1. Clone this repository
2. Install required packages:
   ```
   pip install pygame
   ```
3. Run the game:
   ```
   python flappybird.py
   ```

## Game Objective
- Navigate the bird through the gaps between pipes
- Each successful pass through a pipe scores one point
- The game ends if the bird hits a pipe or the screen boundaries

## Tips
- Use slow mode when you're learning the game
- Try to maintain smooth movements with your mouse
- The bird's movement is slightly delayed to create a more natural feel
- Practice makes perfect!

## Credits
Original game concept by Dong Nguyen
Modified by [Your Name]
