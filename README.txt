Main Functions: move_sets(), poke_check()

Use: 
    **FOR CPP VERSION OF POKE USE THIS**
    make
    ./poke327


For this assignment, I started with professors code by the assignment 1.06, and built off that.
I started to change the db_parse.cpp and db_parse.h to solve the problem.
Get the normal spawn mechanism.
Details of each pokemon with all the details in it. Spawn to determine the weather
Whether it's Pokemon or not, the PC puts a check in game_loop() every time.
If you go into the biome of grass there is a 10% chance of spawning a Pokémon. After that
Spawned and generated pokemon id, gender, polished state, level, etc.
All randomly. Creates after assigning levels according to the distance of the PC.
IV value for each statistic. Since everything has been created,
Go and actually parse the stats file and get the basic stats

Thank you for reading this file.

Known Bugs:
mvprintw errors sometimes has occurs. But that will be the my computer's personal problem that vs code,
sometimes, doesn't know what libraries are imported.