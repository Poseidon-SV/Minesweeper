# Minesweeper
This is a Python implementation of 2-D Minesweeper!

You start a game by running the program :

(If you do not edit the parameters in the script, the script will automatically initialize it to a 10x10 board, with 10 bombs)
```
   0 1 2 3 4 5 6 7 8 9 
------------------------
0 |_|_|_|_|_|_|_|_|_|_|
1 |_|_|_|_|_|_|_|_|_|_|
2 |_|_|_|_|_|_|_|_|_|_|
3 |_|_|_|_|_|_|_|_|_|_|
4 |_|_|_|_|_|_|_|_|_|_|
5 |_|_|_|_|_|_|_|_|_|_|
6 |_|_|_|_|_|_|_|_|_|_|
7 |_|_|_|_|_|_|_|_|_|_|
8 |_|_|_|_|_|_|_|_|_|_|
9 |_|_|_|_|_|_|_|_|_|_|
------------------------
Where would you like to dig ;) ?? Input row,col:
```
Input row and column in terminal for example:
```
3,4
```
Press `Enter` 
```
Where would you like to dig ;) ?? Input row,col: 3,4
   0 1 2 3 4 5 6 7 8 9  
------------------------
0 |0|0|0|0|0|0|1|_|_|_| 
1 |0|0|0|0|0|0|1|_|_|_| 
2 |0|0|0|0|0|0|1|2|2|1| 
3 |1|1|1|0|0|0|0|0|0|0| 
4 |_|_|1|0|0|0|0|1|1|1| 
5 |_|_|1|0|0|1|1|2|_|_| 
6 |_|_|1|0|0|1|_|_|_|_| 
7 |_|_|1|0|0|1|2|_|_|_|
8 |1|1|1|0|0|0|1|_|_|_|
9 |0|0|0|0|0|0|1|_|_|_|
------------------------
Where would you like to dig ;) ?? Input row,col:
```
Continue your move and enjoy :)

For now, this program does not have a GUI and you can use terminal :D (If you want to make a GUI, feel free to make a pull request)

In order to "dig" at a certain location, you type in the index of the row, then the column, separated by a comma (whitespace optional). The game "digs" recursively around that location if there are no bombs nearby.

You can continue digging until either you hit a bomb (which is game over) or you've successfully dug up all n-b non-bomb locations (which is victory)!

This repo contains two files:

- `Mine_Sweeper.py`: implementation of minesweeper
- `Mine_Sweeper_help.py`: empty code template for you to try on your own by seeing given comments :)
