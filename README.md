# Lab-04

Update this README to include your team name and team members. Don't forget to record all your answers to lab 04 here.
### Members
* Devon McGrath
* Komal Jabbar
* Natasha Williams
* Jen Feng William Liang

1. integers, boolean , strings
2. playerLetter
3. 
  ```def inputPlayerLetter():
  Lets the player type which letter they want to be.
  Returns a list with the player’s letter as the first item, and the computer's letter as the second.
 letter = ''
 while not (letter == 'X' or letter == 'O'):
  print('Do you want to be X or O?')
  letter = input().upper()
  if letter == 'X':
  return ['X', 'O']
 else:
  return ['O', 'X']
 ```
4. if isSpaceFree(board, 5):
5. for i in board:
6. board is an example o a list. The list saves position of numbers 1-9 on the board.
7. def drawBoard(board):
``` # This function prints out the board that it was passed.
 # "board" is a list of 10 strings representing the board (ignore index 0)
 print('   |   |')
 print(' ' + board[7] + ' | ' + board[8] + ' | ' + board[9])
 print('   |   |')
 print('-----------')
 print('   |   |')
 print(' ' + board[4] + ' | ' + board[5] + ' | ' + board[6])
 print('   |   |')
 print('-----------')
 print('   |   |')
 print(' ' + board[1] + ' | ' + board[2] + ' | ' + board[3])
 print('   |   |')
 ```
8. 
