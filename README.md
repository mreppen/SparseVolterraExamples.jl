# SparseVolterraExamples.jl
This Julia package containts examples which implement the method described in https://arxiv.org/abs/2005.06081 for solving nonlinear and integro-differential Volterra equations. It additionally also contains some linear examples.

In its current state, this package serves two purposes: 
- Complimentary role to the paper, providing code samples to those curious about the actual implementation.
- Reproduce the figures found in the paper by providing a documented (via comments) step-by-step walkthrough of each of the numerical experiments in the paper.

While the package is not meant for nor setup for user-friendly general use, the interested reader should nevertheless find the code to be mostly straightforward to generalize.

# Installation

The following installation guide assumes a clean install of Julia Version 1.3.1 (2019-12-30), which can be found here: https://julialang.org/downloads/oldreleases/
Newer Julia releases may work if all the appropriate dependenceies can be resolved.

# References

- Gutleb, T. S. (2020). A fast sparse spectral method for nonlinear integro-differential Volterra equations with general kernels. arXiv:2005.06081.

- Gutleb, T. S., & Olver, S. (2020). A sparse spectral method for Volterra integral equations using orthogonal polynomials on the triangle. SIAM Journal on Numerical Analysis, 58(3), 1993-2018.
