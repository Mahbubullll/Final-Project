ULTIMATE SNAKE GAME by Woyhi Tahin and Mahbubul Khan

The purpose of this project is to create the classic snake game but with our own twist to it.

Key functions in this project include: 
    'print_score' = which updates the score by changing the text of the score at the corner
    'draw_snake' = updates teh snake size and its position as it consumes food
    'def run_game' = this is the lengthiest function and the most important for in game movement and game display 
        more in detail: 
        food size 
        super food size
        initializes super food timer 
        enables in game movement using keys (up, down, left, right)
        also enables quit and restart (key 1, key 2)
        closes game if the snake goes out the boundary 
        updates movement
        setting the background to display the snake, food, and super food
        game over screen if the snake eats itself
        global function includes snake speed throughout the function 
    
        adding super food effect which should change the snake speed for a certain time

We were able to get a working, functioning snake game going, but we were unable to fix the issue regarding our super food. The effect works by slowing the snake down but we also wanted it to slow it down for only 30 seconds and also have it appear on the display every minute but we were not able to do that and instead the superfood appeared instantly and would appear right away once eaten. we ran into the proble where the snake speed was appearing as an error due to snake speed already appearing early on and to fix this issue where snake speed changes when super food is eaten we used the global function.


https://youtu.be/6nEZgpCmeGI
