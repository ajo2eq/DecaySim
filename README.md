#DecaySim
----------------------------------

DecaySim provides classes and methods for simulating a relativistic particle undergoing a two body decay.

##Dependencies

DecaySim is compatible with python >= 2.7 including 3.x. 
It requires pyROOT bindings for CERN's ROOT to use the histplot submodule.
The massPDG() function in the distributions submodule relies on pypdt, which is available on pypi.

##Submodules

The **particle** submodule provides a base particle class, and a mother class which decays into daguhter particles.

The **histplot** submodule allows basic plotting functionality by interfacing to CERN's PyROOT.

The **distributions** submodule provides basic random distributions, useful for momenta and mass distributions

The **utils** module provides functions for calculating observables.

##To do

  * Create fuller documentation and examples.
  * Clean up the code, particularly in particle.py
  * Create a plotting submodule based on matplotlib or pyglet.
  * Run comparison tests against other MC generators
  * Write \_\_init\_\_.py and setup.py scripts.
