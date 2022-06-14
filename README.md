# MONSTER SAKU

## Final Project Team 18 - GWS

### Deskripsi Program
This Pocket Monster Game is a game that can be played by 2 players. Each player gets 6 monsters randomly. Then 1 random monster is chosen to be the current monster for each player. Each monster has its own moves, stats, and element types.

There are four types of moves from each monster, namely normal moves, special moves, default moves, and status moves. Each move has ammunition which indicates the number of times the move can be used. The default move has unlimited ammunition and can always be used. Status moves can cause monsters (both themselves and enemy monsters) to experience a certain status condition that affects the monster's stats or changes to the stats buff. There are also element types of each monster and move that have their own attack effectiveness.

When it's the player's turn, the player can choose 1 of 2 battle commands, namely choosing a move from the current monster to be matched with the opponent's current monster or replacing the current monster with another monster that is still alive.

If both players choose a move, the priority of the two moves will be compared. The bigger priority move will move first. If the priority is the same, then the move that is executed first is the monster with a higher speed. If the speed of the two monsters is the same, the order will be randomized. If one player chooses to switch the current monster and the other chooses to move, then the current monster will be exchanged first and then a move is made. If both players choose to switch current monsters, then both players' current monsters will switch and move directly to the next turn. The game will end and the player will win if all the monsters of the opposing player are dead.

### Team Member 18 - GWS
Michael Ryan Martin 

Akmal Jauhar Sidqi

Dewa Ayu Mutiara Kirana P D

Gresya Angelina E Leman

### How to Compile the Program :
#### [1] Using Gradle
1. Clone this repository. In addition to cloning the repository, this repository folder can be downloaded in the form of a .zip file, then extracted to a folder on the device used to run the program.
2. Open a terminal, then open the folder IF2212-Monster-Pocket-Game
3. Enter the command "gradlew build", then press enter.
4. After a successful build, enter the command "gradlew run" or you can also use the command "gradlew -q --console plain run" for a cleaner look. Then, press enter.

#### [2] If Using Java Compiler
1. Download and set up the java compiler on the device that will be used.
2. Clone this repository.
3. Apart from cloning the repository, this repository folder can be downloaded in the form of a .zip file, then extracted to a folder on the device used to run the program.
4. In running this program, there are 3 configuration files,
namely element-type-effectivity-chart.csv, monsterpool.csv, and movepool.csv, which can be accessed at ...\IF2212-Monster-Pocket-Game\src\main\resources\com\mymonsters\configs

Note: the configuration file can be changed as needed.
