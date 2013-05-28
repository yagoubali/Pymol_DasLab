-----------------------
 pymol_rhiju.py    ![1q9a example image](1q9a.png)
-----------------------
(C) R. Das 2008-2013

------------
What this is
------------

This python script includes a few useful, short functions for making pictures of RNA and proteins in pymol in our 'lab style':

<ul>
<li><code>rr()</code>
 useful for RNA, with 2' OH as spheres, bases as filled rings, and backbone as cartoon ribbons, rainbow colored from 5' to 3'. No hydrogens, white background. 
</li>

<li>
<code>rd()</code>
 useful for proteins -- side chains are all-atom and colored CPK, backbone is rainbow cartoon from N to C terminus.
</li>

<li>
<code>sa()</code>
 superimposes all models to the first one. [Thanks to Kyle Beauchamp for this one]
</li>
</ul>

and more...

--------------
Example images & help
--------------
Check out: 

[example images and help](https://docs.google.com/document/d/1uWeEEGPjAceaw07ESf9bec-FrxW4Bx6jGaBqoHbSXuo/edit)


--------------
How to install
--------------

Get the script. Either download the pymol_daslab.py script from [this link](https://raw.github.com/DasLab/pymol_daslab/master/pymol_daslab.py).
Or, if you are planning to make edits, type:

<code>git clone https://github.com/DasLab/pymol_daslab</code>

In pymol, type 

<code>
 run pymol_daslab.py
</code>

Or (much easier) create or edit a <code>.pymolrc</code> text file in your home directory, and add a line like:

<code>
 run ~/src/pymol_daslab/pymol_daslab.py
</code>

--------------
Quick test
--------------

Open up pymol. Type:

<code>
fetch 1q9a
rr()
</code>

