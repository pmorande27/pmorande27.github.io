---
title: "Hydrogen Atom"
categories:
  - blog
tags:
  - Physics
  - Computational
---
## Introduction
This computational project was undertaken during the 2022/2021 academic year. This project was done as part of the Numerical-Recipes course that I took as part of my degree in Theoretical Physics at the University of Edinburgh.

This project explores the eigenvalue problem of the Hydrogen Atom.
In one dimension, the time-independent Schrödinger equation is given by

HΨ = EΨ,

where H is the Hamiltonian. Here, E and Ψ are the eigenvectors and eigenvalues of H, respectively. The Hamiltonian is expressed as

H =hbar^2/2m Δ+ V(r)

where V(r) is the electric potential energy, given by

V(r) = -e^2/4πεr

In matrix form, the Schrödinger equation is solved for N equally spaced values of r, such that r goes from r_{max}/N to r_{max}, where r_{max} ≈ 1.5 nm is a sensible choice. To turn the Schrödinger equation into a matrix, V(r) should be a diagonal matrix with the values of the potential at each r along the diagonal.

The main aim of this project is to get accurate values for the possible values of the energy of this system using scipy. This project also looks for the same system with a small perturbation to the potential. 
## Code
[Github Repository](https://github.com/pmorande27/Hydrogen-Atom)