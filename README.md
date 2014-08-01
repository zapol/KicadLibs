KicadLibs
=========

My own precious KiCAD libraries

Footprints
==========
More or less consistent with KiCad Library Convention (https://github.com/KiCad/kicad-library/blob/master/KiCad_Library_Convention.txt)
Differences:
Silkscreen might not be completely visible after board assembly, uses 0.2mm line width.

Additional layers used:
 - Cmts.User - to print on assembly drawing. Elements are meant to resemble the look of actual components without worrying about pads (as it is with silkscreen drawing)
 - Eco1.User - to be used as Courtyard
 
Symbols
=======
More or less consistent with KiCad Library Convention.
Differences:
Pin has a length of 100mil or more in increments of 50mil if number needs more space. Pins with hidden numbers have length of 50mil.

Naming Convention
=================
Is a mess... Literally.
Maybe time will come when I fix it, maybe not. I did not intend to share this library anyway.

BUT
If you use it, let me know. Might encourage me to put some order in it.
