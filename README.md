# Tic-Tac-Toe
Tic-Tac-Toe is among the games played between two players played on a 3 x 3 square grid. Each player inhabits a cell in their respective turns, keeping the objective of placing three similar marks in a vertical, horizontal, or diagonal pattern. The first player utilizes the Cross (X) as the marker, whereas the other utilizes the Naught or Zero (O).

Break down the code step by step:

1. The code defines several functions to implement a Tic Tac Toe game. The mytictactoe function is used to print the current state of the Tic Tac Toe board. The myscoreboard function is used to print the scoreboard. The check_Victory function checks if any player has won. The check_Tie function checks if the game is a tie. The singlegame function implements a single game of Tic Tac Toe.

2. The mytictactoe function takes a list val as input, representing the state of the Tic Tac Toe board. It uses formatted string printing to display the board layout.

3. The myscoreboard function takes a dictionary scoreboard as input, representing the scores of the players. It prints the scoreboard using formatted string printing.

4. The check_Victory function takes the positions of a player's moves (playerpos) and the current player (curplayer) as input. It checks if any winning combination of moves has been achieved and returns True if a player has won, otherwise False.

5. The check_Tie function takes the positions of the players' moves (playerpos) as input. It checks if the game is a tie by comparing the total number of moves made with the maximum possible moves (9). It returns True if the game is a tie, otherwise False.

6. The singlegame function implements a single game of Tic Tac Toe. It initializes the Tic Tac Toe board and player positions. It then enters a game loop where players take turns choosing a block on the board. The function validates the input, updates the game information, checks for victory or a tie, and switches the current player. The function returns the winner or 'D' for a tie.

7. The code uses an if __name__ == "__main__": block to specify the starting point of the program. It prompts the players to enter their names and sets up the initial player and player choices.

8. Inside the main loop, players are prompted to make a choice for 'X' or 'O', or quit the game. The input is validated, and the player choices are updated accordingly. The singlegame function is called with the appropriate player's choice.

9. After each game, the scoreboard is updated based on the winner, and the current player is switched.

The code allows players to play multiple games of Tic Tac Toe, keeps track of scores, and provides a menu for players to make their choices.
