# Design

This document shall show how the game is to be built from different
blocks.

As of 2015-03-09, most details are still to be figured out, and I think
rather than diving right into coding we should design the game we want
prior to writing any code.

Pre-coding
----------

  * The game's name will be 'Box Tanks'
  * The game will be written in JavaScript
  * The game will be browser-based
  * The game should be downloadable
 
Possibilities 
-------------
  * There could be server hosted multiplayer

Rendering
---------
  * Should be in 3D
  * We will probably end up rendering using simple geometric shapes (e.g. voxels)

Misc
----

  * We don't have that many people working on this repository so progress will be slow

Classes
-------

This is where we explain how the game will be formed from different
subsystems, which classes will form each subclasses, and the routines
that such classes should have.

  * Interface
    * InterfaceGui
    * InterfaceCli
