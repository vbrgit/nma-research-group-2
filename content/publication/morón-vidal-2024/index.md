---
title: An explicit substructuring method for overlapping domain decomposition based
  on stochastic calculus
authors:
- J. Morón-Vidal
- F. Bernal
- A. Suzuki
date: '2024-01-01'
publishDate: '2024-12-20T11:30:45.219990Z'
publication_types:
- article-journal
publication: '*Applied Numerical Mathematics*'
doi: 10.1016/j.apnum.2024.02.011
abstract: In a recent paper [7], a hybrid supercomputing algorithm for elliptic equations
  has been proposed. The idea is that the interfacial nodal solutions solve a linear
  system, whose coefficients are expectations of functionals of stochastic differential
  equations confined within patches of about subdomain size. Compared to standard
  substructuring techniques, such as the Schur complement method for the skeleton,
  the hybrid approach produces an explicit and sparse shrunken matrix—hence suitable
  for substructuring again. The ultimate goal is to push strong scalability beyond
  the state of the art by leveraging the potential for parallelisation of stochastic
  calculus. Here, we present a major revamping of that framework, based on the insight
  of embedding the domain in a cover of overlapping circles (in two dimensions). This
  allows for efficient Fourier interpolation along the interfaces (now circumferences)
  and—crucially—for the evaluation of most of the interfacial system entries as the
  solution of small boundary value problems on a circle. This is both extremely efficient
  (as they can be solved in parallel and by the pseudospectral method) and free of
  Monte Carlo error. Stochastic numerics are only needed on the relatively few circles
  intersecting the domain boundary. In sum, the new formulation is significantly faster,
  simpler, and more accurate while retaining all of the advantageous properties of
  PDDSparse. Numerical experiments are included for the purpose of illustration. ©
  2024 The Author(s)
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85188202887&doi=10.1016%2fj.apnum.2024.02.011&partnerID=40&md5=0513c52ace245613d4a4fb3dbb379bc4
---
