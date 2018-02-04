# Simple-Bingo-Game (Java)

Generate Bingo Cards:
<br/>
Your program should use a 5 x 5 two-dimensional array of integers to represent the BINGO card. Column 0 is the column for B, column 1 is the column for I, column 2 is the column for N, column 3 is the column for G and column 4 is the column for O. Randomly generate the numbers 1 – 15 for column B, numbers 16 – 30 for column I, numbers 31 – 45 for column N, numbers 46 – 60 for column G and numbers 61 – 75 for column O. The middle position is a free space.  Place the number zero in the free space.

Prompt the user for the number of players.  Your program should generate a card for each player.  The first card generated is for player 0, the second card is for player 1, and the third card is for player 2 and so on.  Allow the game to have up to 3 players.

Play the game:
<br/>
To play the game your program should:
1.	Generate calls.
Randomly generate a number 0 through 4 represent B, I, N, G or O, that is, 0 represents B, 1 represents I, 2 represents N, 3 represents G and 4 represents O.  Then randomly generate a number to correspond with the generated letter. (Make note of the ranges for each letter.)
2.	Check each card and mark the card if the call matches. 
If a position on a card matches the call, place a zero in that position on the card.
3.	Check each card for a winner.
A card is a winner if there are all zeros along a row, column or diagonal. Print out the number of the winning player.  End the game when there is a winner.  If a winner is not found after 200 calls, end the game.

Output:
<br/>
-	Print out each initial card that is generated.
-	Print out each call.
-	Print out each card when the game is over.
-	Print out the number of the winning player or players.
