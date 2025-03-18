## QOCO - Quadratic Objective Conic Optimizer
<p align="center">
  <img src="https://github.com/user-attachments/assets/7bd44fa7-d198-4739-bb79-a5c15e04a8de" alt="drawing" width="500"/>
</p>

<p align="center">
  <a href="https://img.shields.io/pypi/dm/qoco.svg?label=Pypi%20downloads"><img src="https://img.shields.io/pypi/dm/qoco.svg?label=Pypi%20downloads" alt="PyPI Downloads" /></a>
  <a href="https://opensource.org/licenses/BSD-3-Clause"><img src="https://img.shields.io/badge/License-BSD_3--Clause-green.svg" alt="License" /></a>
  <a href="https://qoco-org.github.io/qoco/"><img src="https://img.shields.io/badge/docs-online-brightgreen?logo=read-the-docs&style=flat" alt="Documentation" /></a>
</p>

QOCO is a convex solver for Second-Order Cone Programs (SOCPs) which implements a primal-dual interior point method. It is written in C, has a BSD-3-Clause license, and is contained in [qoco](https://github.com/qoco-org/qoco).

QOCOGEN is a code generator housed in [qocogen](https://github.com/qoco-org/qocogen) which takes in an second-order cone program problem family and generates a customized C solver (called qoco_custom) for the specified problem family which implements the same algorithm as QOCO. This customized solver is library-free, only uses static memory allocation, and can be a few times faster than QOCO.

QOCO has a python interface, and can be used in CVXPY.

[**Check out the documentation**](https://qoco-org.github.io/qoco/) to learn how to use QOCO and QOCOGEN in your projects.

## Installing

### C

QOCO's C code can be found [here](https://github.com/qoco-org/qoco), and build instructions can be found [here](https://qoco-org.github.io/qoco/install/C.html).

### Python

QOCO is available through [PyPI](https://pypi.org/project/qoco/) by running
```
pip install qoco
```
QOCOGEN is only available through [PyPI](https://pypi.org/project/qocogen/) and can be installed by running
```
pip install qocogen
```

### Matlab

QOCO's matlab wrapper can be found [here](https://github.com/qoco-org/qoco-matlab), and build instructions can be found [here](https://qoco-org.github.io/qoco/install/matlab.html).

## Citing
```
@article{chari2025qoco,
  author      = {Chari, Govind M and A{\c{c}}{\i}kme{\c{s}}e, Beh{\c{c}}et},
  title       = {Custom Solver Generation for Quadratic Objective Second-Order Cone Programs},
  journal     = {In Review},
  year        = {2025},
  url         = {https://arxiv.org/abs/2503.12658},
}
```

