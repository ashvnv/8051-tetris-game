# 8051-tetris-game
Tetris game on 8051

![GitHub](https://img.shields.io/github/license/ashvnv/FPGA-Ping-Pong-game)

Program is written in Assembly Language on Keil uVision and simulation was done on Proteus 8.15

## Proteus Schematic
<img src="https://raw.githubusercontent.com/ashvnv/8051-tetris-game/refs/heads/main/Pics/Tetris2.png?raw=true">

<img src="https://raw.githubusercontent.com/ashvnv/8051-tetris-game/refs/heads/main/Pics/tetris4.gif?raw=true" width=500>

## Game Controls ##
When the simulation starts, tetris pieces will start falling which is to be navigated using the buttons "Right" (Shift Right), "Left" (Shift Left), "CLK" (Rotate Clockwise), "ACLK" (Rotate Anticlockwise), "DOWN" (Move the piece down). When any horizontal row is filled completely, the row will disappear and score on the 7-segment display will increment by 1. If the shapes fill-up till the top, the game will get over and dot matrix display will pause (showing a single active dot anywhere on the matrix). To restart the game, click on "RESTART GAME" button.

<img src="https://raw.githubusercontent.com/ashvnv/8051-tetris-game/refs/heads/main/Pics/Tetris3.png?raw=true" width=150>
