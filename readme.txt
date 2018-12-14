Diablo: Save States
2018 Gregor Ulm

Diablo is a dungeon crawler that was released by Blizzard in 1996. Despite its
old age, it is as captivating to play as ever. The game is nowadays considered
abandonware. Blizzard no longer officially supports it, but with fan-made
patches it can be made to run on modern versions of Windows. I have used the
patch available at [1], which works quite well, apart from rare crashes.
Playing Diablo on a virtual machine is an alternative.
[1] https://github.com/elishacloud/dxwrapper/wiki/Diablo (cf. Diablo-fix.zip)

This repository contains a backup of some of my Diablo (v. 1.09) characters:

multi_0.sv  : Warrior  (lv. 30)
single_0.sv : Warrior  (lv. 40)
single_1.sv : Rogue    (lv. 38)
single_2.sv : Sorcerer (lv. 37)

I consider the single player characters complete; they made it through the
entire game on Hell with little difficulty. All characters are legitimate, i.e.
all equipment was found in the dungeon or acquired from NPCs. Genre aficionados
refer to this as "solo self-found". I did not "hack" any characters, nor did I
exploit the duplication glitch.

The multi player character is needed to set the game to a higher difficulty in
the single player mode. This works via an undocumented but well-known feature:

1) Create a new multi player game with the difficulty setting of your choice
2) Exit that game and, without quitting Diablo, start (or load) a single player
   game
3) As a consequence, for the duration of the current session, the single player
   game will be set to the characteristics of a multi player game of the chosen
   difficulty

The default single player mode is quite manageable with a straight play-through.
At the end, you will have a character who is at around level 26. If you want to
increase the challenge or level up your character further, you will have to use 
the approach above. The differences between single player and multi player 
difficulties have been documented extensively elsewhere. Briefly, it works 
roughly as follows:

                     Monster Health | Damage dealt | Experience Points (Base)
Single - default   :      1x             1x                1x  
Multi  - normal    :      2x             1x                1x
Multi  - nightmare :      6x           2.4x                3x
Multi  - hell      :      8x           4.8x                6x

In addition, at higher difficulties, monsters have more immunities or
resistances and are much more likely to hit or hit-stun you.

If you want to up level up your single-player character beyond level 30, it's
probably a good idea to finish the default single player mode twice for the
experience points and an increased chance to get good item drops. Afterwards,
you'll be in a fine position to continue on Nightmare difficulty, on which you
may want to play until your character hits the mid-30s. Hell difficulty is 
quite tough with a warrior, but much more straightforward with the other two
character classes. If you struggle, I would suggest that you go through the
dungeon for as long as you can on Hell, and drop the difficulty to Nightmare
once you hit a wall. At Hell, the game becomes quite dependent on luck as you 
will need very good equipment to advance further down the labyrinth, affecting
mostly the warrior and to a lesser extent the rogue. As item drops are random, 
you may have to struggle for a while with those two classes. On the other hand, 
with a sorcerer, you will primarily rely on spells which are learned from 
books. If you do not find the ones you need, you can buy them from Adria.

Playing the multi player game on your own is the ultimate difficulty. Not only
is there a cap on the amount of experience per kill you can get, meaning that
your character will level up much more slowly, there is also a high penalty
for dying as you drop your equipment. Recovering it while wearing replacement
equipment can be tough. If your character died due to an ambush of foes that
are difficult to defeat for your current character, your old equipment may be
gone for good. It is also detrimental that elixirs that permanently boost your
character's stats are much more difficult to come by as Pepin will not sell
them, and Adria only sporadically.