.. TurboRVB_manual documentation master file, created by
   sphinx-quickstart on Thu Jan 24 00:11:17 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to our TurboRVB website
===========================================

.. figure:: /_static/07logo/logo.png
    :width: 800px
    
News
########################

- | TurboRVB is now an `open-source project <https://github.com/sissaschool/turborvb>`_!
- | A. Raghav et al. have published a paper in `J. Chem. Theory Comput. 19, 2222-2229 (2023) <https://doi.org/10.1021/acs.jctc.2c01141>`_. 
- | E. Posenitskiy et al. have published a paper in `J. Chem. Phys. 158, 174801 (2023) <https://doi.org/10.1063/5.0148161>`_. 
- | L. Monacelli et al. have published a paper in `Nat. Phys. 19, 845–850 (2023) <https://doi.org/10.1038/s41567-023-01960-5>`_. 
- | A. Tirelli et al. have published a paper in `Phys. Rev. B, 106, L041105  (2022) <https://doi.org/10.1103/PhysRevB.103.L121110>`_. 
- | K. Nakano et al. have published a paper in `J. Chem. Phys. 156, 034101 (2022) <https://doi.org/10.1063/5.0076302>`_. 
- | K. Nakano et al. have published a paper in `Phys. Rev. B 103, L121110 (2021) <https://doi.org/10.1103/PhysRevB.103.L121110>`_. 
  | This paper has been selected as an **Editors' Suggestion**.

Features
########################

`TurboRVB <https://aip.scitation.org/doi/10.1063/5.0005037>`__ is a computational package for **ab initio Quantum Monte Carlo (QMC) simulations** of both molecular and bulk electronic systems. 
The code was initially launched by **Prof. Sandro Sorella** and **Prof. Michele Casula** and has been continuously developed by many contributors for over 20 years. The code implements two types of well established QMC algorithms: Variational Monte Carlo (VMC), and Diffusion Monte Carlo in its robust and efficient lattice regularized variant (LRDMC).

The source codes of TurboRVB and other associated packages are available from :doc:`_sources/03Source_code`.

TurboRVB is distinguishable from other QMC codes in the following features:

- The code employs a resonating valence bond (RVB)-type wave function, such as the Jastrow Geminal/Jastrow Pfaffian. This wave function includes the correlation effect beyond the Jastrow-Slater wave function, which is commonly used in other QMC codes.

- Implemented state-of-art optimization algorithms, such as the stochastic reconfiguration and the linear method, realize a stable optimization of the amplitude and nodal surface of many-body wave functions at the variational quantum Monte Carlo level.

- The code implements the so-called lattice regularized diffusion Monte Carlo method, which provides a numerically stable diffusion quantum Monte Carlo calculation.
  
- The implementation of an adjoint algorithmic differentiation allows us to differentiate many-body wave functions efficiently and to perform structural optimizations and calculate molecular dynamics.

.. toctree::
   :maxdepth: 1
   :caption: Contents:

   _sources/02Developers.rst
   _sources/03Source_code.rst
   _sources/10Workshops.rst
   _sources/11Positions.rst
   _sources/04Publications.rst
   _sources/05PhD_Thesis.rst
   _sources/06Presentations.rst
   _sources/07Basis_set_and_Pseudopotentials.rst
   _sources/08logos.rst
   _sources/09Useful_Links.rst
   
..
    * :ref:`genindex`
    * :ref:`modindex`
    * :ref:`search`
