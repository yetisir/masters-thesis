
# Up-Scaling Distinct Element Method Simulations of Discontinua

This repository hosts the thesis that was presented to the University of Waterloo, Ontario, Canada in fulfillment of the thesis requirement for the degree of Master of Applied Science in Civil Engineering.

© Michael Yetisir 2017

## Abstract
Pre-existing fractures significantly influence the geomechanical response of the rock mass at the reservoir scale. For geomechanical applications, these natural fractures need to be considered in the mechanical response of the system. Distinct Element Methods (DEM) are often used to explicitly model the mechanics of Naturally Fractured Rock (NFR); however, they are often too computationally prohibitive for reservoir-scale problems. A DEM up-scaling framework is presented that facilitates estimating a representative parameter set for continuum constitutive models that capture the salient feature of Naturally Fractured
Rock (NFR) behaviour.

Up-scaling is achieved by matching homogenized DEM stress-strain curves from multiple load paths to those of continuum constitutive models using a Particle Swarm Optimization (PSO) algorithm followed by a Damped Least-Squares (DLS) algorithm. The effectiveness of the framework is demonstrated by up-scaling a DEM model of a NFR to a Drucker- Prager damage-plasticity model; the up-scaled model is shown to capture well the effect of confinement on the the yielding and sliding of natural fractures in the rock mass.

The goal of this thesis is to present a framework to facilitate effective simulation of fine-scale behaviour in full-scale NFR systems while significantly reducing the computational demands associated with modelling these systems with DEM. 

As such, four main research objectives have been identified and achieved: 1) Develop and implement stress and strain homogenization algorithms for DEM models with deformable blocks, 2) present a methodology to parameterize complex nonlinear continuum constitutive models, 3) develop and implement an automated modular software framework for up-scaling DEM simulations, and 4) demonstrate that the performance of the up-scaled continuum models are accurate and significantly more computationally efficient.

The up-scaling methodology is verified through a case study on a naturally fractured granite slope in which the top surface is loaded until failure. The up-scaled continuum model is shown to compare quite well to Direct Numerical Simulation (DNS) in a slope stability analysis and requires two orders of magnitude less computational effort.

## Software

Software developed in conjunction with this thesis can be found here:

* [Up-Frac](https://github.com/yetisir/up-frac)
* [MOUSE](https://github.com/yetisir/MOUSE)

Please note these are <em>**unmaintained**</em> repositories.

## License
This thesis is licensed under the Creative Commons [CC-BY](https://creativecommons.org/licenses/by/4.0/) License.

