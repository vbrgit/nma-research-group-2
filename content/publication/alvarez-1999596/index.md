---
title: Ion temperature gradient turbulence numerical calculations
authors:
- D. Álvarez
- L. Garcia
date: '1999-01-01'
publishDate: '2024-12-20T11:30:45.915899Z'
publication_types:
- article-journal
publication: '*Computer Physics Communications*'
doi: 10.1016/s0010-4655(06)70004-2
abstract: 'Ion temperature gradient (ITG) turbulence, also referred as ηi-mode, has
  been proposed as one of the dominant mechanisms determining the transport properties
  in the core of magnetic fusion devices such as tokamaks. In this work we intend
  to study the saturated ITG turbulence using a non-linear fluid description of the
  plasma including time evolution equations for perturbed ion density, parallel velocity
  and temperature in cylindrical-toroidal geometry. This problem has been treated
  numerically developing a parallel code to run in a Masivelly Parallel Machine with
  distributed memory, like CRAY-T3E. Finite differences in radius and Fourier mode
  expansion in poloidal and toroidal angles have been used. The numerical scheme is
  time implicit for linear terms and time explicit for nonlinear term. These nonlinear
  terms are quadratic nonlinearities that become convolutions of the Fourier components.
  The implicit linear term is solved with inversion of block tridiagonal matrices.
  To numerically advance these equations, a two-step, second-order accurate, time-centered
  advancement scheme is used. The serial code runs on all processors in a synchronous
  way, each processor works over a part of the problem. The distribution of calculations
  is: in harmonic Fourier to solve the implicit part (mainly invert matrices), and
  in radial points for the explicit calculations (mainly convolutions). In each time
  step, all processors must know the results obtained with the rest. To make this,
  the PVM (Parallel Virtual Machine) routines have been used to send and receive the
  data between processors.'
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-0033185512&doi=10.1016%2fs0010-4655%2806%2970004-2&partnerID=40&md5=59f10fd8e3bdfe5a88dff4358f736327
---
