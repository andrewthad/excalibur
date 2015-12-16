# Excalibur

This is a game created by Greg Hart many years in the past. It runs 
on the Apple II, so emulation is required to play it now. To play 
it, visit [http://www.calormen.com/jsbasic/](http://www.calormen.com/jsbasic/)
in your web browser. From this repository, copy the contents of
`excalibur.txt` and paste them into the textbox beside the emulator.
Hit run (located above the text box), and the game should begin
with a screen that says `WELCOME TO EXCALIBUR`.

## Choosing a Character

In this game, you can choose a race and a class. Note that some classes
are unavailable if you stats are not high enough. If you find 
yourself unable to choose any class (which occassionally happens),
choose the option to delete the character and restart.

## Dungeon Control Keys

Once you enter the dungeon, you can navigate with the following 
characters:

- `E`: Go east
- `W`: Go west
- `N`: Go north
- `S`: Go south
- `A`: Attack (only available when a monster appears)
- `R`: Run away (only available when a monster appears)
- `D`: Descend to the next level of the dungeon (only available 
       in the blue room, where you are told that this is an option)
- `U`: Ascend to the previous level of the dungeon (only available after descending)

## Modifications

The game differs from its original version in several ways. The protagonist
has been given more health, more money, and better base stats. Otherwise, the game
is much too difficult.

Also, there were several screens with loops that would stall for 1000 clock
cycles. Since modern hardware is thousands of times faster than the hardware
in the Apple II, these screens get skipped on the emulator. They have been 
replaced by prompts that ask the user to press a key to continue.

## Incomplete Parts

After reaching the second level of the dungeon, the game map in defective.
Some passage lead back to the first floor of the dungeon. There is no 
way to get to the end of game. It is unclear
whether or not it was ever completed.

