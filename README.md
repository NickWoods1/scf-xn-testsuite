***********************
The `scf-xn` Test Suite
***********************

## How To Reference

This test suite was created primarily for the following article "Computing the self-consistent field in Kohn-Sham density functional theory" which can be found at `https://doi.org/10.1088/1361-648X/ab31c0`. This article can be used as a citation for the test suite. 


# Version 0.1
The `scf-xn` is a suite of input systems (geometries and input parameters) designed to exploit weaknesses in methodology used to find a minimum of the Kohn-Sham energy functional. 

# How To Use

The geometries are given in CASTEP .cell format. The file format is fairly transparant and should be readily portable to any other file format either manually or automatically (using, for example, `https://www.c2x.org.uk/`).

Parameters can be set by the user, provided they remain constant for the benchmark (e.g. keep same smearing scheme, same pseudopotentials, etc.). The method and method parameters are the variables for each full run of the test suite. 
