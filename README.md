# Blasius_BL_OpenFoam
This is a laminar BL using OpenFoam's icoFoam solver

The boundary conditions in the U file are :
zeroGradient on the top and bottom of the entrance region.
constant velocity on left side of entrance region.
zeroGradient on top of the flat plate region and the right hand side.
noslip condition on bottom of flat plate region.


The fluid is water. The visc is 1.0e-6.
