MUS - Multimachine Universally Scalable (massive or light)
===========

4d PlaDruMas - 4 degree of freedom Platinen Druck Maschine
------------

4d CiPriMa - 4 degree of freedom Circuit Print Machine
------------


* A scalable multimachine.
* Minimal material amount.
* Minimal part count.
* Optional 4th DOF (degree of freedom).
* Linux system (not reinventing the wheel when we have a gem like GNU/Linux).


<img alt="" title=""/>

Context
----
###There are two distinct 3D manufacturing machines under development + 1 hybrid:###

* HOG  - HOchGeschwindigkeit (lightweight, medium volume, high velocity)
    * <a href="https://forum.opensourceecology.de/viewtopic.php?f=28&t=619">3D PlaDruMas (PUS - Printer Uniprokit Speedy)</a> [UniProKit Parts + Belts]
* HOF  - HOchFestigkeit (massive, medium to huge, slow)
    * <a href="https://forum.opensourceecology.de/viewtopic.php?f=30&p=3132#p3132">4D FräDreMas (MUS - Mill Universally Scalable Variant Sheets)</a> [Scrap + precision manufactured massive metal and plexiglas sheets]
* HOFHOG - Best of both worlds (scalable, tiny to giant, probably slow).
    * <a href="https://forum.opensourceecology.de/viewtopic.php?f=30&p=3132#p3132">4D CiPriMa (MUS - Mill Universally Scalable Variant Crossings)</a> [Easy to source parts (U-profiles, flat/sheet profiles, symmetric parts!, few different parts!)]


###Current development status:###
* Sourcing parts for HOFHOG. Engineering a Linux based solution.

###Current prototype under evaluation:###
<!-- <img href="http://forum.opensourceecology.de/download/file.php?id=59" alt="" title=""/> -->
![CiPriMa Structure Overview](multimachine_universally_scalable.white.axis_coloured_rgb.all_axes.jpg "CiPriMa Structure Overview! All sides symmetric and equal.")

All 4 side structures (five with the roof) are completely the same! Simplifies assembly. The cross structure makes it rigid.

The square metal blocks in the corners are the expensive part.
The rest (leadscrews, U-profiles and flat/sheet-cut profiles) is all readily available at local hardware stores.

The steel plates of the previous design were much too heavy to lift. And so expensive!! I never managed to source them. Thus now this ultra easy to build design. It's my last chance. This missing mill thingy is stopping all my progress on a whole multitude of projects.




###Goals and design considerations:###

* save structural parts,
* keep the sliding axes open at the underside,
* and still create a rigid frame!
* protect all axes against twisting around X, Y and Z.
* use the complete work volume that is available (so no trapezoidal and no sliding sub-table Y-axis, which limits the useful space).
* employ  a Z-axis that is sliding on the X-axis,
* and a Y-axis that is sliding on the Z-axis construction,
* so that the Z-axis is very rigid and 
* it's possible to mount all tools as there will not occur twisting due to too long lever (Archimedes) or vibrating.[/list]

The way the twist-protection works has benefits but also downsides as more rods and lead screws (ACME or usual rods) are requried.
It's a base structure where any tools can be employed

###This machine can be built/equipped as a: (from cheaper to more expensive top to bottom)###

* Circuit mill: low weight & small, hence more precise.
* 3D printer common size: build it using very light material.
* 3D printer with large printing volume to finally construct those Statue of Rhodes replica. (in order to get a precise machine to be able to print small parts too and to use this a s circuit mill additionally, this will not get cheap as a high focus has to be on precision manufacturing and that's not a easy DIY thing without the expensive equipment and long-time experience - I lack these also, I'm afraid).
* Heavy duty mill: build it massive (Steel, no hollow rods, ...). For bigger parts. (like Treehouses I planned to construct since long.)
* Heavy duty high precision mill: finally that's very difficult and very expensive, too. You can try, but I think it's almost impossible as DIY project, unless you have robots helping out with manufacturing.


