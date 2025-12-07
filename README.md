# Coal-Project
You have to implement main screen of your game with following requirements: ROAD in the mid of screen with 3 lanes LANDSCAPE on the left and right side of the road RACE CAR in bottom and center of the road
[Phase II –Play Game]
MoveScreen Function: all the screen except your race car should move down by one row and last row will reappear at row one (top).
Animation: call the MoveScreen function in loop
Randomly appearing other cars and bonus object (that improves the score) from top of screen 
Implement collisions
Score
[Phase III]
[Part I - Keyboard Interrupt]
Change the lane of car using Left,Right keys.
[Part II – Software Interrupts]
Add following in your game using software interrupts:
Introduction Screen: including name of game, your roll numbers, names, semester (Fall 2025)
Esc and Exit Screen: If user presse ESC (implement it using int 9), show a confirmation message asking “Are you sure you want to exit the game?”. If user press Y (Yes) (take this input using software interrupt) display score and terminate, otherwise resume where he stopped.
End Screen: If the car crashes terminate the game after showing user’s score.
[Part III – Timer]
Scroll down the screen in timer ISR.
