README.txt

How to compile and run the Battleship application:

WINDOWS
1. Download the three files (zip, readme, class diagram)
2. Extract all the files in the zip file
3. Open command prompt
4. Change directories to the parent directory of the battleship directory
5. Enter the following command:
javac battleship\board\*.java battleship\coordinates\*.java battleship\game\*.java battleship\gui\*.java battleship\player\*.java battleship\ships\*.java battleship\statistics\*.java
6. Enter the following command:
java battleship.game.Game


UNIX
1. Download the three files (zip, readme, class diagram)
2. Extract all the files in the zip file
3. Open terminal
4. Change directories to the parent directory of the battleship directory
5. Enter the following command:
javac battleship/*/*.java
6. Enter the following command:
java battleship.game.Game