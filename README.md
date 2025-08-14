# Snake Game (Python + Tkinter)
A classic Snake game built with Python’s Tkinter. Eat the red food to grow, avoid walls and your own body. The snake’s head has animated eyes that track the current direction.
## Features
- Smooth grid movement with arrow keys
- Live score display
- Growing snake on each food pickup
- Collision detection (walls & self)
- Game Over screen when you lose
- Simple, readable code structure (classes: Snake, Food)
## Screenshots 
### Gameplay
<img width="400" height="452" alt="image" src="https://github.com/user-attachments/assets/85c91171-28cb-4395-be93-59c252a42d1d" />

### Game Over
<img width="400" height="455" alt="image" src="https://github.com/user-attachments/assets/71490a8b-37f6-40d3-bc6c-bb7274473d52" />

## How to Run
Requirements: Python 3.x (Tkinter is included with standard Python on most systems).
```
# save your script as snake.py (or sns.py)
python snake.py
```
If you’re on Windows and double-clicking doesn’t show a console, run it from PowerShell or CMD.

## Controls

- ⬆ Up — move up

- ⬇ Down — move down

- ⬅ Left — move left

- ➡ Right — move right

Note: the snake can’t instantly reverse into itself (e.g., from left to right in one step).

## Code Structure

- Snake — stores coordinates and canvas rectangles for body segments

- Food — spawns food at random grid positions

- next_turn() — updates movement, growth, score, and collisions

- draw_eyes() — draws the two white eyes on the head and repositions them every tick

- check_collisions() — checks wall & self collision

- game_over() — clears canvas and shows GAME OVER
