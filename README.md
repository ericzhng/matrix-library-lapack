# LAPACK

LAPACK is a library of Fortran subroutines for solving the most commonly
occurring problems in numerical linear algebra.

LAPACK is a freely-available software package. It can be included in commercial
software packages (and has been). We only ask that that proper credit be given
to the authors, for example by citing the LAPACK Users' Guide. The license used
for the software is the modified BSD license, see:
https://github.com/Reference-LAPACK/lapack/blob/master/LICENSE

Like all software, it is copyrighted. It is not trademarked, but we do ask the
following: if you modify the source for these routines we ask that you change
the name of the routine and comment the changes made to the original.

LAPACK is available from github at:
https://github.com/reference-lapack/lapack

The distribution contains:
 (1) the Fortran source for LAPACK
 (2) its testing programs
 (3) the Fortran reference implementation of the Basic Linear Algebra Subprograms (the Level 1, 2, and 3 BLAS) needed by
LAPACK.
 (4) CBLAS, a C interface to the BLAS 
 (5) LAPACKE, a C interface to LAPACK

## Installation

To install:
make install PREFIX=/opt/apps/lapack/3.8.0

Before that:
make
make man1

## User Guide

## LAPACKE

