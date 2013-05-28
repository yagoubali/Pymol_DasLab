-----------------------
 pymol_rhiju.py
-----------------------
(C) R. Das 2008-2013

------------
What this is
------------

This python script includes a few useful, short functions for making pictures of RNA and proteins in pymol in our 'lab style':

rr()
 useful for RNA, with 2' OH as spheres, bases as filled rings, and backbone as cartoon ribbons, rainbow colored from 5' to 3'. No hydrogens, white background. 

rd()
 useful for proteins -- side chains are all-atom and colored CPK, backbone is rainbow cartoon from N to C terminus.

sa()   
 superimposes all models to the first one. [Thanks to Kyle Beauchamp for this one]

and more...

--------------
Example images & help
--------------
Check out: 

[example images and help](https://docs.google.com/document/d/1uWeEEGPjAceaw07ESf9bec-FrxW4Bx6jGaBqoHbSXuo/edit)


--------------
How to install
--------------

In pymol, type 

 run pymol_rhiju.py

Or (much easier) create or edit a .pymolrc text file in your home directory, and add a line like:

 run ~/src/pymol_daslab/pymol_daslab.py

--------------
Quick test
--------------

Open up pymol. Type:

<code>
fetch 1q9a
rr()
</code>

