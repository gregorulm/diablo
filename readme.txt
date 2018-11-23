Diablo: Save States
2018 Gregor Ulm

Diablo is a dungeon crawler that was released by Blizzard in 1996. Despite its
old age, it is as captivating to play as ever. The game is nowadays considered
abandonware. Blizzard no longer officially supports it, but with fan-made
patches it can be made to run under modern versions of Windows. I have used the
patch available at [1], which works quite well, apart from rare crashes.
Playing Diablo on a virtual machine is an alternative.

[1] https://github.com/elishacloud/dxwrapper/wiki/Diablo (cf. Diablo-fix.zip)


This repository contains a backup of some of my Diablo (v. 1.09) characters:

multi_0.sv  : Warrior (lv. 30)
single_0.sv : Warrior (lv. 38) -> defeated final boss on Hell difficulty

The multi player character is needed to set the game to a higher difficulty in
the single player mode. This works via an undocumented but well-known feature:

1) Create a new multi player game at the difficulty of your choice
2) Exit that game and, without quitting Diablo, start (or load) a single player
   game
3) As a consequence, for the duration of the current session, the single player
   game will be played according to the characteristics of a multiplayer game.

The default single player mode is quite manageable with a straight play-through.
At the end, you will have a character who is at around level 26. It should have
little difficulty finishing the game. If you want to increase the challenge or
level up your character further, you will have to use the approach above. The
differences between single player and multi player have been documented
extensively elsewhere. Briefly, it works roughly as follows:

Single - default   : Monsters give 1x experience and have 1x health
Multi  - normal    :               2x                     2x
Multi  - nightmare :               3x                     3x
Multi  - hell      :               4x                     4x

In addition, at higher difficulties, monsters have more immunities or
resistances and are much more likely to hit or hit-stun you.

If you want to up level your single-player character beyond level 30, it's
probably a good idea to finish the default single player mode twice for the
experience and an increased chance to get good item drops. Afterwards, you'll
be in a fine position to continue with higher difficulty settings. Hell
difficulty is quite tough, so you may want to build your character on Nightmare
for a few play throughs. Eventually, you may want to tackle Hell. For that, go
through the dungeon for as long as you can on Hell, and drop the difficulty to
Nightmare once you hit a wall. At Hell, the game becomes quite dependent
on luck as you will need very good equipment to advance further down the
labyrinth. Yet, as item drops are random, you may not be able to do so.

Playing the multi player game on your own is the ultimate difficulty. Not only
is there a cap on the amount of experience per kill you can get, there is also
a high penalty for dying. It is also detrimental that elixirs that permanently
boost your character's stats are much more difficult to come by as Pepin will
not sell them.
