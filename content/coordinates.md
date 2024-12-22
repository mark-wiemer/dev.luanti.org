---
title: Coordinates
aliases:
- /Coordinates
---

# Coordinates


The [Luanti](https://wiki.luanti.org/Luanti "Luanti") world is a large cube. And because of this, a position in the world can be easily expressed with Cartesian **coordinates**. That is, for each position in the world, there are 3 values X, Y and Z.

Notation
--------

Coordinates are expressed like this: (5, 45, -12)

This refers to the position where X=5, Y=45 and Z=-12. The 3 letters are called “axes”: Y is for the height. X and Z are for the horizontal position.

Orientation
-----------

The values for X, Y and Z work like this:

* If you go up, Y increases
* If you go down, Y decreases
* If you follow the sun, X increases
* If you go to the reverse direction, X decreases
* Look to the sun's direction, then turn 90° to the right and go forwards: Z increases
* Look to the sun's direction, then turn 90° to the left and go forwards: Z decreases
* The side length of a full cube is 1

Finding your coordinates
------------------------

### Debug screen

You usually can view your coordinates by using the [debug](https://wiki.luanti.org/Debug "Debug") screen (open with F5).

For this to work, the game/server needs to allow this _or_ you have the “debug” [privilege](https://wiki.luanti.org/Privileges "Privileges").

By default, games _do_ allow you to access the coordinates in the debug screen, so this works most of the time.

Some games might choose to hide the coordinates from the debug screen to regular players. Maybe you’re suppoed to “earn” the right to see the coordinates (e.g. with a special item), or maybe the coordinates are hidden completely to make the game more difficult. But, if you have the “debug” privilege, you are guaranteed to have access.

### Mods

There are also mods which add tools which, when you carry then, show you the coordinates:

* [Orienteering](https://content.luanti.org/packages/Wuzzy/orienteering/) \[orienteering\]
* [Compass GPS](https://forum.minetest.net/viewtopic.php?t=9373) \[compassgps\]