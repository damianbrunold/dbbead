This is the source code folder of DB-BEAD, a bead
crochet ropes design software. See
http://www.brunoldsoftware.ch/dbb.html for more
information.

The project is written in C++, using the (now ancient)
C++Builder 5 product from Borland. Since it uses the
VCL library extensively, it is not easy to port it to
some newer programming environment.

The whole project is licensed under the GPL v3 or later.
See LICENSE.txt for details.

A setup suitable for distribution can be created using
the free NSIS setup system. You can download it from
http://nsis.sourceforge.net/Main_Page. The necessary
setup script is included in this folder and named
dbb.nsi. Copy dbbead.exe, license.txt and source.zip
together with dbb.nsi in a folder, and run the NSIS 
system to create the dbbead_setup.exe file. This can
be distributed and installs the whole program.
