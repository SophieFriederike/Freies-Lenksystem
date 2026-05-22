QtAgOpenGPS
===========
Ag Precision Mapping and Section Control Software


License
-------
AOG was originally licensed under the GPLv3, so this port was also 
licensed under the GPLv3.  AOG has since been relicensed to the MIT
license, which is still compatible with the GPLv3, so this project
remains GPLv3 for now.

Requirements
------------
QtAOG requires Qt 6.0 or newer to build, on any Qt-supported platform
that supports OpenGL ES 2 or newer, or DirectX on Windows.
It also requires cmake 3.22 or newer.

Why this Port?
--------------
This port is mainly for my own entertainment, to allow me to run AOG
on Linux, including SBCs like the Raspberry Pi.  But I think the 
most desirable target will be Android some day.

Bugs and TODOs
--------------
- GL font drawing has issues, but only with the AB Line number display.  
  A lot of UI stuff currently drawn with GL should be drawn with QML
  widgets instead.
- Dashed lines are not possible in OpenGL ES, but I think a shader script
  can do it.  Also there's no easy way to do thick lines in opengl ES either.
- Hook in the GUI that David Wedel is contributing.

----------------
