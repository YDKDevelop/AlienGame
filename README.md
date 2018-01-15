# AlienGame
Astronaut_Alien Game 

#Example Full Run
'''bash
$ cd Game
$ ls
Alien.cpp		Game_Command.h		Person.cpp
Alien.h			Game_Object.cpp		Person.h
Astronaut.cpp		Game_Object.h		Space_Station.cpp
Astronaut.h		Input_Handling.h	Space_Station.h
Cart_Point.cpp		Makefile		View.cpp
Cart_Point.h		Model.cpp		View.h
Cart_Vector.cpp		Model.h			main.cpp
Cart_Vector.h		Oxygen_Depot.cpp
Game_Command.cpp	Oxygen_Depot.h
$ make
g++ -c Cart_Point.cpp -o Cart_Point.o -g
g++ -c Cart_Vector.cpp -o Cart_Vector.o -g
g++ -c Game_Object.cpp -o Game_Object.o -g
g++ -c Oxygen_Depot.cpp -o Oxygen_Depot.o -g
g++ -c Space_Station.cpp -o Space_Station.o -g
g++ -c Person.cpp -o Person.o -g
g++ -c Astronaut.cpp -o Astronaut.o -g
g++ -c Model.cpp -o Model.o -g
g++ -c Game_Command.cpp -o Game_Command.o -g
g++ -c View.cpp -o View.o -g
g++ -c Alien.cpp -o Alien.o -g
g++ -c main.cpp -o main.o -g
g++ -o PA4 Cart_Point.o Cart_Vector.o Game_Object.o Oxygen_Depot.o Space_Station.o Person.o Astronaut.o Model.o Game_Command.o View.o Alien.o main.o -g
$ ./PA4
Alien Invasion Game
Game_Object constructed.
Person constructed.
Astronaut constructed.
Game_Object constructed.
Person constructed.
Astronaut constructed.
Game_Object constructed.
Alien constructed
Game_Object constructed.
Alien constructed
Game_Object constructed.
Oxygen_Depot constructed.
Game_Object constructed.
Oxygen_Depot constructed.
Game_Object constructed.
Space_Station default constructed.
Game_Object constructed.
Space_Station constructed.
Model default constructed
Would you like to play in Normal Mode (n) or in Computer Mode (c)?
