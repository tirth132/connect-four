# Connect Four
This is a command line game project introduced in JetBrains academy Kotlin
Basics path. The goal of project is to get you familiar with basic syntax of
language, conditional statements, loops, jump and break, standard input/output
etc. You need to know basic Kotlin to be able to complete the project. It is a 
fun project.

# Get on your computer
To get the game on your computer you need to clone the repository from GitHub.
Enter following command to clone the repository.
```
git clone git@github.com:tirth132/connect-four.git
```
or
```
git clone https://github.com/tirth132/connect-four.git
```
The project uses Gradle as build system and doesn't include any IDE
configuration files. You can open it in any IDE and run it. You can also run it
 manually from terminal without any IDE.
 
# How to play
Run the `Main.kt` class from your IDE(or from command line if you want to). It
will print game name on startup and then ask for player names. After that you
will be asked to enter board size. Press enter for default.
```
Connect Four

First player's name
> Thor
Second player's name
> Hulk
Set the board dimensions (Rows x Columns)
Press Enter for default (6 x 6)
> 8x6
Thor VS Hulk
8 x 6 board
```
Next it will print board to console using some ASCII characters. It will ask
first player to enter the column number in which he/she wants to add disk. It
column number is valid and in range it will add disk to column. The game will
end if any player enters `end`. If player wins, it will announce the name of
winner and end the game.
