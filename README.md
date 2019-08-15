# Matrix Library

You can find more details in the website [here](https://ericzhng.github.io/docs-matrix-library/).

## Introduction

LAPACK is a library of Fortran subroutines for solving the most commonly occurring problems in numerical linear algebra. The license used for the software is the modified BSD license, see: https://github.com/Reference-LAPACK/lapack/blob/master/LICENSE

The distribution contains:
* (1) the Fortran source for LAPACK
* (2) its testing programs
* (3) the Fortran reference implementation of the Basic Linear Algebra Subprograms (the Level 1, 2, and 3 BLAS) needed by LAPACK.
* (4) CBLAS, a C interface to the BLAS 
* (5) LAPACKE, a C interface to LAPACK

## Installation

First you need to compile the code and its docs to be installed. Type the following:
`make`
`make man1`

Make sure gcc/gfortran is installed through `sudo apt install gfortran build-essential`. To compile docs, install doxygen through `sudo apt install doxygen`.

To install lapack, simply type:
`sudo make install PREFIX=/opt/apps/lapack/3.8.0`
