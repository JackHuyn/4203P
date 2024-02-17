# Issues report for SWE4203 Tic-Tac-Toe Project

## Current issues

    1.  If the next player chooses any position that already been occupied, the program will skip that player's turn altogether. (Corrective)

    2.  The notification will be wrong if the error above occurs, for example player (O) has more moves and wins but the result is shown as a draw. (Corrective)

    3. Winning in less than 6 moves results in no winner notification (Corrective) 

    4. Placing any move at (1,1) and (3,3) after move #3 returns placement_conflict error (Corrective)

    5. Winning condition is coded wrong, but can still trigger (Corrective)


## Usability issues

    1. The winning/losing/drawing notification is not eye-catching, which can lead to confusion. (Perfective)

    2. The client does not automatically open when running, the user has to press ctrl + click the localhost link being generated in the cmd. (Adaptive)

    3. The generated code when hosting a game don't have copy function, making the player has to copy manually. (Adaptive)

    4. If anyone leaves the game while playing, the game waits for that player indefinitely and the remaining player is stuck. (Corrective)