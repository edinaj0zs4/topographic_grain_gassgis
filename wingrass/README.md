Topographic Grain
==================
In this subfolder are the necessary files to use the script tool on WinGRASS versions. (Tested on 7.x.)
- To the best of my knowledge it is up to date and works, but please compare the change date to the version in root.


This README provides the information to install r.tg.geom.


Dependencies:
-------------

-   suggested GRASS GIS 7.x
-   Python packages (os, platform, sys, subprocess, csv, grass.script, grass.exceptions)
-   GRASS GIS addon r.geomorphon 
    https://grass.osgeo.org/grass72/manuals/addons/r.geomorphon.html

Installation:
-------------
* Supposing you have a GRASS GIS version installed.

1.  Install GRASS GIS addon
    (g.extension extension=r.geomorphon operation=add)
    * otherwise the tool will inform you, that you miss it
2a.  Copy r.tg.geom.py script to path\to\grassversion\scripts folder (e.g. X:\Program Files\GRASS GIS 7.2.0\scripts)
2b.  Copy TG_jozsa.R script to path\to\grassversion\scripts folder
2c.  Copy r.tg.geom.html help page to path\to\grassversion\docs\html folder

3.  Open GRASS GIS and run command r.tg.geom - the tool should work and you should see the available information on manual page