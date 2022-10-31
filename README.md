# GuessTheNumber-Game
# GuessTheNumber
This is the Guess The number game, Written By Raghav bansal.
The Java code is written in Spring Boot Application

Task: To create simple game that is a Spring Boot application. The game has (at least) one player. 

1. It create (at least) one player on the server
2. It get player information from the server
3. Players play the game in turns with the player

For the Spring boot Application, These are the commands User should type


  POST mapping : localhost:8090/player?id=1&name=name - to create players 1
  POST mapping : localhost:8090/player?id=1&name=name - to create player 2
  GET Mapping: localhost:8090/player?id=1 - Player 1 information
  GET Mapping: localhost:8090/player?id=2 - Player 2 information
  POST mapping: localhost:8090/game - Creating the game and instruction
  PUT mapping: localhost:8090/game?id=1&move=5 - playing game turn by turn
  PUT mapping: localhost:8090/game?id=2&move=4 - player 2 playing his move
  (If there is a winner and want to check player information)
  GET mapping: localhost:8090/player?id=1 - Check the winner and overall information
  GET mapping: localhost:8090/game?id=1 - check the moves, Player plaeyed
  DELETE mapping: localhost:8090/player?id=1 - to delete any player
