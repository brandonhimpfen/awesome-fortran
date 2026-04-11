# Awesome Fortran [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of compilers, libraries, tools, standards, numerical frameworks, and learning resources for **Fortran**, with a focus on scientific computing, high-performance computing (HPC), and numerical analysis.

## Contents

- [Foundations & Standards](#foundations--standards)
- [Compilers](#compilers)
- [Build Systems & Tooling](#build-systems--tooling)
- [Numerical & Scientific Libraries](#numerical--scientific-libraries)
- [Parallelism & HPC](#parallelism--hpc)
- [Interoperability](#interoperability)
- [Testing, Debugging & Profiling](#testing-debugging--profiling)
- [Package Management](#package-management)
- [Applications & Use Cases](#applications--use-cases)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)
  
## Foundations & Standards

- [Fortran Language Standard](https://wg5-fortran.org/) – Official ISO working group defining Fortran language standards.
- [Fortran Wiki](https://fortranwiki.org/) – Community-maintained documentation and examples for modern Fortran.
- [Fortran-lang](https://fortran-lang.org/) – Central hub for modern Fortran tooling, tutorials, and ecosystem news.
- [ISO_C_BINDING](https://gcc.gnu.org/onlinedocs/gfortran/ISO_005fC_005fBINDING.html) – Standard module for C interoperability.
- [Modern Fortran Explained](https://global.oup.com/academic/product/modern-fortran-explained-9780198811893) – Definitive reference for modern Fortran features.

## Compilers

- [GNU Fortran (gfortran)](https://gcc.gnu.org/fortran/) – Widely used open-source Fortran compiler.
- [Intel oneAPI Fortran Compiler](https://www.intel.com/content/www/us/en/developer/tools/oneapi/fortran-compiler.html) – Optimizing compiler for Intel CPUs and HPC workloads.
- [LLVM Flang](https://github.com/llvm/llvm-project/tree/main/flang) – Modern Fortran front-end for the LLVM ecosystem.
- [NVHPC Fortran](https://developer.nvidia.com/hpc-compilers) – NVIDIA Fortran compiler optimized for GPUs and accelerators.
- [Cray Fortran](https://www.hpe.com/us/en/compute/hpc/cray.html) – High-performance compiler used on Cray supercomputers.
- [LFortran](https://lfortran.org/) – Interactive and LLVM-based modern Fortran compiler.

## Build Systems & Tooling

- [CMake Fortran Support](https://cmake.org/cmake/help/latest/manual/cmake-fortran.7.html) – Build system support for Fortran projects.
- [Make](https://www.gnu.org/software/make/) – Traditional build automation tool commonly used with Fortran.
- [Meson](https://mesonbuild.com/) – Modern build system with Fortran support.
- [FORD](https://github.com/Fortran-FOSS-Programmers/ford) – Automatic documentation generator for Fortran code.
- [ffmt](https://github.com/sbryngelson/ffmt) – Fast, configurable Fortran formatter with support for Fypp, Doxygen, and OpenACC/OpenMP directives, written in Rust.
- [fprettify](https://github.com/pseewald/fprettify) – Code formatter for modern Fortran.

## Numerical & Scientific Libraries

- [BLAS](http://www.netlib.org/blas/) – Basic linear algebra subprograms foundational to numerical computing.
- [LAPACK](https://www.netlib.org/lapack/) – Library for solving linear algebra problems.
- [ScaLAPACK](https://www.netlib.org/scalapack/) – Distributed-memory linear algebra library.
- [FFTW](https://www.fftw.org/) – Fast Fourier Transform library with Fortran bindings.
- [ARPACK](https://www.caam.rice.edu/software/ARPACK/) – Eigenvalue solver for large sparse systems.
- [NetCDF-Fortran](https://www.unidata.ucar.edu/software/netcdf/) – Data format and library for array-oriented scientific data.

## Parallelism & HPC

- [MPI](https://www.mpi-forum.org/) – Message Passing Interface standard for distributed-memory parallelism.
- [OpenMP](https://www.openmp.org/) – Shared-memory parallel programming model supported by Fortran.
- [Coarray Fortran](https://coarrays.sourceforge.net/) – Native Fortran parallel programming feature.
- [OpenACC](https://www.openacc.org/) – Directive-based GPU and accelerator programming model.
- [Kokkos Kernels](https://github.com/kokkos/kokkos-kernels) – Performance-portable numerical kernels interoperable with Fortran.

## Interoperability

- [Fortran–C Interoperability Guide](https://fortran-lang.org/learn/intrinsics/cfi/) – Practical guidance on mixing Fortran and C.
- [f2py](https://numpy.org/doc/stable/f2py/) – Tool for connecting Fortran code with Python via NumPy.
- [ISO_C_BINDING Examples](https://fortranwiki.org/fortran/show/iso_c_binding) – Practical examples of C interoperability.
- [SWIG](https://www.swig.org/) – Tool for generating bindings between Fortran, C, and higher-level languages.

## Testing, Debugging & Profiling

- [pFUnit](https://github.com/Goddard-Fortran-Ecosystem/pFUnit) – Unit testing framework for Fortran.
- [CTest](https://cmake.org/cmake/help/latest/manual/ctest.1.html) – Testing tool commonly used with CMake-based Fortran projects.
- [GDB](https://www.gnu.org/software/gdb/) – Debugger with Fortran language support.
- [Valgrind](https://valgrind.org/) – Memory debugging and profiling tool.
- [Intel VTune](https://www.intel.com/content/www/us/en/developer/tools/oneapi/vtune-profiler.html) – Performance profiling for HPC applications.

## Package Management

- [fpm (Fortran Package Manager)](https://github.com/fortran-lang/fpm) – Official package manager for modern Fortran projects.
- [Spack](https://spack.io/) – HPC-oriented package manager supporting Fortran libraries.
- [Conda-forge Fortran Packages](https://conda-forge.org/) – Community-maintained Fortran packages for Conda environments.

## Applications & Use Cases

- [Weather & Climate Modeling](https://www.noaa.gov/) – Fortran-based models used in meteorology and climate science.
- [Computational Fluid Dynamics (CFD)](https://openfoam.org/) – Physics simulations leveraging Fortran numerical kernels.
- [Quantum Chemistry Codes](https://www.quantum-espresso.org/) – Electronic structure and materials modeling software.
- [Finite Element Analysis](https://www.ansys.com/) – Engineering simulations built on Fortran solvers.
- [Astrophysics Simulations](https://www.nasa.gov/) – Large-scale simulations for space and cosmology research.

## Learning Resources

### Tutorials
- [Fortran-lang Tutorials](https://fortran-lang.org/learn/) – Modern Fortran tutorials and examples.
- [GNU Fortran Documentation](https://gcc.gnu.org/onlinedocs/gfortran/) – Official compiler and language reference.
- [Learn Modern Fortran](https://www.fortran90.org/) – Practical introduction to modern Fortran syntax.

### Guides
- [Modern Fortran Best Practices](https://fortran-lang.org/en/learn/best_practices/) – Recommended patterns for maintainable Fortran code.
- [HPC with Fortran](https://www.archer2.ac.uk/training/) – Training materials for Fortran in supercomputing.
- [Numerical Recipes](http://numerical.recipes/) – Classic reference for numerical methods.

### Courses
- *Scientific Computing with Fortran* – Numerical programming using modern Fortran.
- *High-Performance Computing* – Parallel computing concepts using Fortran and MPI.
- *Computational Physics* – Simulation-focused course leveraging Fortran.

## Related Awesome Lists

- [Awesome Scientific Computing](https://github.com/awesomelistsio/awesome-scientific-computing)
- [Awesome HPC](https://github.com/awesomelistsio/awesome-hpc)
- [Awesome Numerical Computing](https://github.com/awesomelistsio/awesome-numerical-computing)
- [Awesome Physics](https://github.com/awesomelistsio/awesome-physics)
- [Awesome Data Science](https://github.com/awesomelistsio/awesome-data-science)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
