# soplex
SoPlex is an optimization package for solving linear programming problems (LPs) based on an advanced implementation of the primal and dual revised simplex algorithm. It provides special support for the exact solution of LPs with rational input data. It can be used as a standalone solver reading MPS or LP format files via a command line interface as well as embedded into other programs via a C++ class library.

### Build instructions

These directions should work without issues on ubuntu 16.04 and better:

 - Install the GMP arithmetic support library v3, the package name is ```libgmp3-dev```
 - Navigate to the root folder of your local copy of this repo and invoke ```make```
 - Once finishes compiling, install to ```/usr/local``` (or elsewhere it suits you) with the command ```make install INSTALLDIR=<prefix>```
