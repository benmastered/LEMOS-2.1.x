LEMOS Rostock Extensions
====================
Collections of OpenFOAM-Extensions created at the Institute for
Modeling and Numerical Simulation at the University of Rostock


Installation
============

1. move the Folder "LEMOS-2.1.x" into $FOAM_SRC
2. add the following line to your ~/.bashrc after ". ~/OpenFOAM/OpenFOAM-2.1.x/bashrc":
     . $FOAM_SRC/LEMOS-2.1.x/bashrc
3. parse your ~/.bashrc or open a new terminal
4. Execute $LEMOSEXT/ApplyPatches
   This will patch some files of the OpenFOAM sources from Sourceforge and recompile the necessary libraries
5. Execute $LEMOSEXT/Allwmake to build the library and executables
