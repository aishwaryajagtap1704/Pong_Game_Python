# Pong_Game_Python
This Python code uses the Turtle graphics library to create a simple Pong game. Here's a description of its functionality:

Window Setup: Creates a window for the game with a black background and sets its size to 800x600 pixels.
Bars Setup: Creates two bars (bar_A and bar_B) that act as paddles for the players. These bars are white squares positioned on the left and right sides of the window, respectively.
Ball Setup: Creates a ball (circle) at the center of the window. The ball's initial movement is set to a small value in both the x and y directions.
Score Setup: Creates a scoreboard at the top of the window to display the current scores for players A and B.
Player Controls: Sets up keyboard bindings to allow players to control their bars. Player A can move their bar up with the 'w' key and down with the 's' key, while player B can move their bar up with the 'Up' arrow key and down with the 'Down' arrow key.
Game Loop: Enters a game loop that continuously updates the game state and checks for collisions, player inputs, and score updates.
Ball Movement: Updates the ball's position based on its current velocity in the x and y directions.
Border Collision: Checks if the ball hits the top or bottom borders of the window and reverses its y velocity if it does.
Score Updates: Checks if the ball passes the left or right borders of the window (indicating a point scored by player B or player A, respectively) and updates the scores accordingly.
Bar Collision: Checks if the ball collides with either player's bar. If it does, it reverses its x velocity, simulating a bounce off the bar.
