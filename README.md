# Multi-Stranded-Loops-Code
The source files for the FORTRAN hydrodynamic code, Multi-Stranded Loops code developed by the University of Central Lancashire.

About the Multi-Stranded Loops Code
----------------------------------------
The numerical code is written in FORTRAN andisbased on the Lagrangian remap method (LareXd) developed by Arber et al. (2001), which has been modified
for multi-stranded coronal loops (Sarkar & Walsh, 2008,2009). A unique feature of this code is that each individual sub-element strand of a loop is an
individual, independent simulation that are then amalgamated in post-processing to form a single coherent coronal loop. The code is managed in such a 
way that the loop/strand parameters (such as nanoflare energy, loop/strand length and radius, etc) can be edited without the need for recompiling the 
model, allowing for multiple instances/scenarios to run concurrently.
