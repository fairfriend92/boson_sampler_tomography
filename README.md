# boson_sampler_tomography
Mathematica code that reconstructs the unitary matrix of an integrated boson sampler

This code allows to reconstruct the unitary matrix of an integrated boson sampler chip with 2 waveguides. The code implements the reconstruction algorithm that is described <a href="https://arxiv.org/pdf/1312.3080.pdf">here</a>. The repository includes two scripts for Mathematica. One script simply generates a random unitary matrix and the associated visibility and coupling measurements. The other script reconstructs the unitary matrix from the visibility and coupling measurements. 

The respository also includes a technical report (in Italian, called Tesina) that features a brief introduction to the following topics:

  - Computational complexity
  - Quantum computing
  - Boson sampling
  - Fabrication of an integrated boson sampler
  - Certification of the chip through the Hong-Ou-Mandel effect
  - Unitary matrix reconstruction
