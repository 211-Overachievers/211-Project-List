# Lab-3: Tic-Tac-Toe, Player vs CPU
* Implemented `detectwin.v` to detect when one someone has won
    * Made tests in `detectwin_tb.v`
* Improved game logic by adding capability to play adjacent edge
    * Module in `tictactoe.v`
    * Made tests in `gameplay_tb.v`
* Light up LEDs on De1-Soc when game is over to signify whether player has won, lost, or tied
* Further improved game logic so that CPU never loses 