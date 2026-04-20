# Triasha Sarkar

PhD student in Aerospace Engineering at Georgia Tech (ASDL),
working at the intersection of physics-based simulation and
scientific machine learning.

My current focus is on understanding the mathematics behind
surrogate modeling, not just building models that work in
practice, but being able to prove why they work, quantify
what they guarantee, and predict when they will fail. That
shift from empirical to rigorous is what's driving my
independent research right now.

---

## What I'm working on

**Multifidelity surrogate modeling**
Engineering simulations exist at multiple fidelity levels -
fast and approximate, or slow and accurate. Multifidelity
methods combine both to get near-high-fidelity accuracy at
low-fidelity cost. I'm interested in the mathematical
framework that makes this combination provably sound, not
just intuitively reasonable. Connected to: Qian et al. (2025),
control variate estimators, Gaussian process regression.

**Operator learning and model reduction**
When a surrogate maps from input parameters to full field
solutions, geometry to B-field distribution, for example:
it's learning an operator between function spaces. I'm
studying how Operator Inference (OpInf) and projection-based
model reduction give this a rigorous mathematical structure,
rather than treating it as a black-box regression problem.

**Physics-informed machine learning**
Instead of ignoring governing equations during training,
physics-informed methods embed PDEs directly as constraints.
I'm interested in when this improves generalization in the
scarce data regime and when it doesn't and why.

**Gaussian process regression**
The mathematical foundation of GP surrogates is covariance
structure, posterior inference, uncertainty quantification,
is what I'm building toward. I want to be able to derive
the confidence intervals I've been computing, not just use
them.

---

## Projects

**[NURBS_BEM_EMSolver](https://github.com/triasha72/NURBS_BEM_EMSolver)**
Mesh-free NURBS-based boundary element solver for solenoid
magnetic field computation. Biot-Savart + surface bound
current BEM, solving a 3000×3000 linear system for surface
magnetization. Generates a multi-fidelity dataset (N=20
and N=50 grids, 25 solenoid geometries) for surrogate
training. Currently building a POD feasibility study to
assess whether B-field snapshots live on a low-dimensional
manifold, motivated by parametric Operator Inference as a
structured surrogate architecture.

**[Surrogate-model-learning](https://github.com/triasha72/Surrogate-model-learning)**
Systematic study of surrogate methods from mathematical
first principles, not just applying them, but understanding
what they're computing. GP surrogate on a 2D benchmark
(R²=0.9553, 20 LHS samples), 4D beam deflection where
log-transforming inputs outperformed adding data, and a
three-way RSM vs GP vs RBF comparison on the Rosenbrock
function showing exactly where polynomial approximation
breaks down and why.

---

## What I'm building toward

The gap I'm trying to close: I can build surrogate models
that produce correct results. I can't always derive why they
produce correct results or prove when they won't. Closing
that gap,from empirical to mathematical, is the thread
connecting everything I'm working on.

Planned next: multifidelity GP applied to the EM solver
dataset, POD feasibility study for parametric OpInf.

---

## Stack

Python · NumPy · SciPy · scikit-learn · PyTorch · geomdl ·
pythonocc-core · pyDOE2 · Jupyter · Git

---

## Find me

tsarkar34@gatech.edu
[linkedin.com/in/triasha-sarkar](https://www.linkedin.com/in/triasha-sarkar)
