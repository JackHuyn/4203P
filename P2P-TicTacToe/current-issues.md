# Issues report for SWE4203 Tic-Tac-Toe Project

## Current issues

    1.  If the next player choose any posittion that already been occupied, the program will skip that player turn, making the game order being changed. (Corrective)

    2.  The notification will be wrong if the error 1 occurs, for example (figure 1) the player (O) has more move and winning but the result is shown as draw. (Corrective)

    3. Winning less than 6 move result in no winner notification (draw) 

    4. Placing any move at (1,1) and (3,3) after move #3, return placement_conflict error (Corrective)

    5. Winning condition is coded wrong, but can still trigger (Corrective)


## Usability issues

    1. The winning/ losing/ and drawing notification is not eye-catching, leading to some confusion if not paying attention. (Perfective)

    2. The client not automatically open when running, the user has to press ctrl + click the local host link being generated in the cmd. (Adaptive)

    3. The generated code when hosting a game don't have copy function, making the player has to copy manually. (Adaptive)

    4. if anyone leave the game while playing, the game still going and stuck. (Corrective)
