## Data Inference to PDEs Using Deep Learning

This set of jupyter notebooks is an emulation of "physics-informed" neural networks, applied to the diffusivity equation.

![eqn](https://wikimedia.org/api/rest_v1/media/math/render/svg/ef7f035a8de948328b8a983c06c099ff52d9ef07)

The diffusivity equation is a fundamental governing equation in reservoir engineering and petrophysics. The equation describes the pressure profile as a function of time t and radius position r. 

The following assumptions were made in approximating the equation with deep neural networks:
1. Homogeneous and isotropic
2. Uniform thickness
3. Single Phase Flow
4. Rock and Fluid Properties were constant with respect to pressure


## Reference & Full Credit
The code is modified for the diffusivity equation. The original code and source of DL methodology is sourced from:

```
M. Raissi, P. Perdikaris, G.E. Karniadakis,
Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations,
Journal of Computational Physics,
https://doi.org/10.1016/j.jcp.2018.10.045.

Abstract: We introduce physics-informed neural networks – neural networks that are trained to solve supervised learning tasks while respecting any given laws of physics described by general nonlinear partial differential equations. In this work, we present our developments in the context of solving two main classes of problems: data-driven solution and data-driven discovery of partial differential equations. Depending on the nature and arrangement of the available data, we devise two distinct types of algorithms, namely continuous time and discrete time models. 

The first type of models forms a new family of data-efficient spatio-temporal function approximators, while the latter type allows the use of arbitrarily accurate implicit Runge–Kutta time stepping schemes with unlimited number of stages. The effectiveness of the proposed framework is demonstrated through a collection of classical problems in fluids, quantum mechanics, reaction–diffusion systems, and the propagation of nonlinear shallow-water waves.
```
