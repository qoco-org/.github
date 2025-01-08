## QOCO - Quadratic Objective Conic Optimizer

![License](https://img.shields.io/github/license/qoco-org/qoco)

QOCO is a convex solver for Second-Order Cone Programs (SOCPs) which implements a primal-dual interior point method. QOCO is written in C, has a BSD-3-Clause license, and is contained in [qoco](https://github.com/qoco-org/qoco).

QOCOGEN is a code generator housed in [qoco-python](https://github.com/qoco-org/qoco-python) which takes in an second-order cone program problem family and generates a customized C solver (called qoco_custom) for the specified problem family which implements the same algorithm as QOCO. 
This customized solver is library-free, only uses static memory allocation, and can be a few times faster than QOCO.

QOCO has a python interface, and can be used in CVXPY.

[**Check out the documentation**](https://qoco.org/) to learn how to use QOCO and QOCOGEN in your projects.

## Installing

### C

QOCO's C code can be found [here](https://github.com/qoco-org/qoco), and build instructions can be found in the documentation.

### Python

QOCO is available through [PyPI](https://pypi.org/project/qoco/) by running
```
pip install qoco
```
