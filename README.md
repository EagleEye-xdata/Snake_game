#🎮 Game Title: Python Snake Classic

🌟 Overview:
A grid-based Snake game where you control a red snake to eat green snacks, grow in length, and avoid collisions. With a minimalistic and clean visual style, the game offers a nostalgic yet upgraded experience with features like:

Exit button 🟥

Live score display 📊

Tkinter pop-up for game over 💥

Classic control system with arrow keys ⬅️⬆️➡️⬇️

#💡 Key Features:

🕹️ Controls:

Arrow keys: Move the snake (Up, Down, Left, Right)

ESC key or 🟥 Exit Button: Quit the game

#🧱 Game Mechanics:

The snake is made of cubes (cube class) and moves on a 20x20 grid.

Eating a snack grows the snake's body.

Colliding with the wall or your own body ends the game.

Snake turns are managed with a turn tracking system so all body parts follow the head smoothly.

#🍏 Snack Logic:

Green snacks appear randomly on the grid.

The position is ensured not to overlap with the snake's body using a filtered random selection.

#💥 Game Over:

If you crash into yourself or the wall:

Final score is printed in the console.

A Tkinter popup displays your score.

Snake is reset to start again!

#💻 Interface Design:

Clean black background.

Grid lines drawn to give a visual structure.

Real-time score display at the top left corner.

Exit button at top-right (clickable with mouse).

#🧩 Code Architecture:

cube class: Represents each segment of the snake and the snack.

snake class: Manages movement, growth, reset, and rendering.

randomSnack(): Spawns the snack at an unoccupied location.

draw_exit_button(): Renders a clickable exit button.

show_game_over(): Uses tkinter.messagebox to show score popup.

main(): The main game loop — handles game flow, rendering, collisions, and inputs.

#💡 Bonus Functionalities:

🚪 Clickable Exit Button (top-right corner)

📈 Live Score display on screen

🧠 Memory-safe movement using deep copying of positions

🔄 Automatic Reset after collision with wall or self
