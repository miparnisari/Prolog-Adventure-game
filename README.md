# Prolog-Adventure-game

Adventure game with prolog language. The player has to find the treasure hidden inside the castle to win the game. A total of 3 lives will be available. Implemented interactive gameplay mechanics such as locked doors, hidden objects, incomplete objects, limited resources, and inventory management.

```
$ swipl -s treasure_hunt.pl
Welcome to SWI-Prolog (threaded, 64 bits, version 9.2.9)
SWI-Prolog comes with ABSOLUTELY NO WARRANTY. This is free software.
Please run ?- license. for legal details.

For online help and background, visit https://www.swi-prolog.org
For built-in help, use ?- help(Topic). or ?- apropos(Word).

?- start.

Enter commands using standard Prolog syntax.
Available commands are:
start.                  -- to start the game.
up. down. right. left.  -- to go in that direction.
take(Object).           -- to pick up an object.
drop(Object).           -- to put down an object.
look.                   -- to look around you again.
i.                      -- list the inventory of items.
find.                   -- to find the treasure.
instructions.           -- to see this message again.
halt.                   -- to end the game and quit.
```
