                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


https://www.thingiverse.com/thing:3027141
Infill coasters by jmdbcool is licensed under the Creative Commons - Attribution - Non-Commercial - Share Alike license.
http://creativecommons.org/licenses/by-nc-sa/3.0/

# Summary

**Slicer settings are important!** If you use default settings this will be a functional but boring coaster.

I love the patterns created by different types of infill. Wouldn’t it be cool to have some finished 3D printed pieces with the infill exposed? The pattern becomes more than a functional support, it becomes part of the piece itself. It would be a good tool for learning/demonstration and a neat coffee table conversation piece.

Coasters are great for this. The infill catches drips from condensation, like any good coaster should (I hate the flat kind where water just pools on top). Plus, you can choose different infill patterns, which makes for an interesting set.

Oh, and coasters should be round. Why are there so many square coasters in the world? Nobody has square cups!

The STL itself is simple; the infill patterns are determined by you and your slicer settings (most importantly: zero top layers). I used Slic3r PE; my settings and explanation are included below. If you choose to figure this out in another slicer, post your settings in the comments.

There is a little lip on top and chamfer underneath so multiple coasters will nest / stack together without a stand.

You can use whatever infill and density you choose. They're easy to print, functional, educational, and they look cool. Enjoy.

For extra credit: try a color change where the infill starts (1.8mm– and maybe change back again at 3.4mm where it stops). That would really emphasize the pattern.

# How I Designed This

This is in the current version of Slic3r PE (1.40.0 at time of posting).

Default settings for 0.20mm with the following changes:

**Layers and perimeters:**

**Perimeters: 7**

The outer ring is about 2.8mm thick, divided by 0.4mm nozzle width equals 7 perimeters. This is unusually high but it forces the slicer to work the way I want: the outer ring remains solid while the large flat area becomes infill.

**Solid layers: Top: 0, Bottom: 8**

This is how to expose the infill at the top. I decided to use 8 layers of infill and 8 solid layers. The flat area is 3.2mm thick, divided by 0.2mm layer height equals 16 layers (8 infill, 8 solid).

**Ensure vertical shell thickness: OFF**

Slic3r PE fills in some areas near the perimeter unless this is turned off. I'm using way more perimeters than normal so it’s not necessary.

![Alt text](https://cdn.thingiverse.com/assets/de/2f/d2/6d/d4/infill-coaster-settings-1.PNG)

**Infill:**

**Fill density / fill pattern:** whatever you like! I used these:

* Honeycomb, 10% (yellow)
* Hilbert curve, 10% (neon green)
* Octagram spiral, 10% (purple)
* Gyroid, 20% (turquoise)

![Alt text](https://cdn.thingiverse.com/assets/24/17/ca/b9/a8/infill-coaster-settings-2.PNG)