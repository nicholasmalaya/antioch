Antioch
=======

A New Templated Instantiation Of Chemistry for Hydrodynamics (Antioch) was initiated to centralize work by some of the Antioch authors within the realm of hypersonic aerodynamics, based on the [libMesh](https://github.com/libMesh/libmesh.git) finite element library. In particular, although there exist C++ chemistry libraries, such as [Cantera](http://code.google.com/p/cantera/), we had needs for both thread-safety and high performance. Thus, Antioch was born. Antioch originally lived within the [PECOS](https://pecos.ices.utexas.edu) center at the Institute for Computational Engineering and Sciences ([ICES](https://www.ices.utexas.edu)) at [The University of Texas at Austin](https://www.utexas.edu).

Dependencies
============

Requirements
------------

Antioch has no required dependencies other than a reasonably modern C++ compiler.

Optional Packages
-----------------

Antioch has been designed to allow several optional packages to facilitate vectorized evaluation of thermochemistry quantities. In particular, Antioch currently can support:

1. [VexCL](https://github.com/ddemidov/vexcl.git) - This package will enable GPU offload capabilities
2. [Eigen](http://eigen.tuxfamily.org) - Highly optimized vector and matrix types

Building Antioch
================

