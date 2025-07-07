<b>Tic Tac Toe Game</b> - This fully functional game can be played by 2 players.  The code determines the winner and posts a
congragulatory message based on the results.  The 'Reset' button can be used at any time to restart another tic tac toe game.
https://audreyrwilliams.github.io/Tic-Tac-Toe/ 

![Screen Shot 2025-07-06 at 6 00 14 PM](https://github.com/user-attachments/assets/9838fa92-ff37-4020-b06e-c163bd353910)
![Screen Shot 2025-07-06 at 6 00 42 PM](https://github.com/user-attachments/assets/9d2969b8-a4a0-44df-97b7-c93dbb480920)

1. The 'X' and 'O' png images were downloaded from Canva and moved to the 'Assets' folder.
2. The 'React' app was created in VS Code and later pushed to github pages.  I created 3 folders in the 'src' directory: 'Components',
   'Components/Assets', and 'Components/TicTacToe'.  The 'circle.png' and 'ex.png' files were copied to the 'Assets' folder.
   The 'TicTacToe.css' and 'TicTacToe.jsx' files were created in the 'TicTacToe' folder. The TicTacToe.jsx file was imported into the 'App.js'
   file, and the TicTacToe.css file was imported into the TicTacToe.jsx file so that this style sheet could be referenced by the JSX.
3. The <title> tag of the 'index.html' file is where I updated the name that would appear on the internet tab for the web page.
4. The 'TicTacToe.jsx' file is where the core of the game functionality was created.  A one dimensional 'data' array was created to keep track
   of the selections as well as the winner.  Another array was created for the 'Reset' functionality that makes each box blank.
