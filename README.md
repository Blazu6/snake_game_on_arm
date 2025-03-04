# Snake Game for EasyMx PRO M4 (ARM)

This is a simple Snake game implemented on the **EasyMx PRO M4** development board. The game uses a 240x320 ILI9341 TFT display and supports basic joystick controls for navigating the snake. The game features a special bonus object that allows the snake to pass through walls for a limited time.

## Features

- **Joystick controls** for snake movement:
  - Up
  - Down
  - Left
  - Right
- **Collisions** with walls and the snake's body.
- **Food mechanics** to grow the snake.
- **Special bonus object** that allows passing through walls for a limited duration.
- **Score and High Score** tracking.
- **Game over screen** when the snake collides with itself or a wall.

## Requirements

- **Hardware**: EasyMx PRO M4 (ARM)
- **Display**: 240x320 ILI9341 TFT display
- **Joystick**: 4 buttons for controlling the snake's movement
- **Compiler**: ARM GCC or equivalent
- **Libraries**:
  - TivaWare (for controlling peripherals)
  - GrLib (for graphics rendering)
  - ILI9341 display driver
