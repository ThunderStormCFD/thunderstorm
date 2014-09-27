thunderstorm
============

########################################################################################################
Project: ThunderStorm Solver Serial V1.0 Release 
Release Notes : Author: Vatsalya Sharma IIT Hyderabad, me12m1030@iith.ac.in
#########################################################################################################
This is a Unstructured grid serial single zone incompressible Navier Stokes solver using SemiImplicit algorithm, with collocated formulation. 
It reads unstructured grid of hybrid type (Quad, hex, tet, tet+hex, pyramid, prism) of cgns 2.4 to 2.1 version into the solver and produces output 
in the same version.
Please install cgnsTools from cgns website for conversion from cgns to other formats.
Grid generation can be done in any unstructured grid generator.
Post processing: Tecplot, paraview

To compile the solver type:
sh runfile

Run the executable Hurricane by first changing directory to bin
cd bin
Then inside the bin type:
./Hurricane InputGrid.cgns Outputgrid.cgns

if we have an input file, type:
 ./Hurricane InputGrid.cgns Outputgrid.cgns<inputfile

please contact at me12m1030@iith.ac.in for any doubts/clarifications with "proper doubts". 
