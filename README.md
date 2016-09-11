EasyRPG Tools
=============

EasyRPG Tools is a suite of small file related applications to use and
convert RPG Maker 2000/2003 files.

EasyRPG Tools is part of the EasyRPG Project.
More information is available at the project website:

https://easy-rpg.org/


Tool details
------------

These are the currently available tools:

 * LCF2XML: converts LMU, LMT, LDB and LSD files into XML and vice-versa.

   Syntax: `lcf2xml inputfile outputfile`

 * LMU2PNG: renders LMU maps to PNG images with events as tiles support.

   Syntax: `lmu2png mapfile chipsetfile outputfile`

 * PNG2XYZ: converts PNG images into XYZ images. It supports wildcards.

   Syntax: `png2xyz file1 [... fileN]`

 * XYZ2PNG: converts XYZ images into PNG images. It supports wildcards.

   Syntax: `xyz2png file1 [... fileN]`
   
 * LcfTrans: extracts text out of LMU and LSD files and creates po files.
 
   Syntax: `lcftrans`

 * xyz-thumbnailer: displays thumbnails for XYZ files in your file manager
                    (currently Windows and Linux/GTK3 only)

   Windows: Shell extension for Windows explorer, see included README.md for
            install instructions.

   Syntax (Linux): `xyz-thumbnailer input output [size]`


Daily builds
------------

Up to date binaries are available at:

https://easy-rpg.org/jenkins/


Source code
-----------

EasyRPG Tools development is hosted by GitHub, project files are available in
Git repositories.

https://github.com/EasyRPG/Tools


License
-------

The EasyRPG Tools are free software under different licenses. Read the LICENSE
file available in the respective tool directories for details.
