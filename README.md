# Matrix Library (LAPACK)

You can find more details in [this website here](https://ericzhng.github.io/docs-matrix-library/). This repository is only for LAPACK.

## Introduction

LAPACK is a library of Fortran subroutines for solving the most commonly occurring problems in numerical linear algebra. The license used for the software is the modified BSD license, see: https://github.com/Reference-LAPACK/lapack/blob/master/LICENSE

The distribution contains:
* (1) the Fortran source for LAPACK
* (2) its testing programs
* (3) the Fortran reference implementation of the Basic Linear Algebra Subprograms (the Level 1, 2, and 3 BLAS) needed by LAPACK.
* (4) CBLAS, a C interface to the BLAS 
* (5) LAPACKE, a C interface to LAPACK

## Installation

First you need to compile the code and its docs to be installed. Type `make all` or `make man` to compile.

Make sure gcc/gfortran is installed through `sudo apt install gfortran build-essential`. To compile docs, install doxygen through `sudo apt install doxygen`.

To install LAPACK, simply type `make install PREFIX=/opt/apps/lapack/3.8.0` to copy all necessary files to destination. The specified directory can be changed to anywhere you want to install LAPACK to. If it is system directories, use `sudo` ahead.

Both the static and dynamic libraries are built and can be linked. Some external tests will be provided to show how to use LAPACK libraries directly.
