# AlienGame
Astronaut_Alien Game 

### Running
```
$ cd Game
$ ./PA4
  Would you like to play in Normal Mode (n) or in Computer Mode (c)?
```
# Commands
### m ID x y
"move": command Astronaut ID to move to location (x, y)
### w ID1 ID2
 "work a depot": command Astronaut ID1 to start supplying at Oxygen_Depot.
18
### d ID1 ID2
 “deposit moon stones”: command Astronaut ID1 to start depositing moonstones
at Space_Station ID2.
### s ID
 "stop": command Astronaut ID to stop doing whatever it is doing
### l ID1 ID2
 “lock in at station”: command Astronaut ID1 to lock into station ID2.
### g
 "go": advance one time step by updating each object once.
### r
 "run": advance one time step and update each object, and repeat until either the
update function returns true for at least one of the objects, or 5 time steps have
been done.
### q
 "quit": terminate the program
 
### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

