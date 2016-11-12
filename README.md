# Snakes and Traps!
A two-level game, supporting Snakes and Ladders and Classic Snake's game through Bash Shell Scripting.

The project basically involves SNAKE and LADDER game,where players have to roll dice to get random numbers.
The random values determine the number of spaces to move ahead. 
In our program we are generating random numbers using $RANDOM command.
This command generates numbers more than 6,but in our case we need numbers only from 0-5.
So we take the modulus of 6 and add 1.

Now, for the Snake's Game we have mainly focussed on the escape-sequences for the color, design. 
The logical implementation included much dealing of the Process ID’s
The foreground process `getchar()` ignores `SIGINT` and `SIGQUIT`, and replies to the signal of death `SIG_HEAD` by returning from the function `getchar()`. 
The background process `game_loop()` traps direction control signals from the keyboard.
Self-defined signal `SIG_QUIT` which results on pressing 'Q'.
