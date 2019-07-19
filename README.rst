****************************************
The scf-:math:`x`\ :sub:`n`\  Test Suite
****************************************

Version 0.1
###########


The scf-:math:`x`\ :sub:`n`\  is a suite of input systems (geometries and input parameters) designed to exploit weaknesses in methodology to find a minimum of the Kohn-Sham energy functional. 


**********
How To Use
**********

The geometries are given in CASTEP .cell format. The file format is fairly transparant and should be readily portable to any file format either manually or automatically (using, for example, https://www.c2x.org.uk/).

Parameters can be set by the user, provided they remain constant for the benchmark (e.g. keep same smearing scheme, same pseudopotentials, etc.). The method and method parameters are the variables for each full run of the test suite. 
