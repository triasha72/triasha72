# Triasha Sarkar

PhD student in Aerospace Engineering at Georgia Tech, 
working on making simulations run faster without 
sacrificing the physics that makes them useful.

Most of my work sits somewhere between traditional 
numerical methods and machine learning which means 
I spend a lot of time explaining to CFD people why 
neural networks aren't magic, and to ML people why 
you can't just ignore the governing equations.

---

## What I'm actually working on

**Surrogate modeling** : training neural networks to 
approximate expensive CFD/FEM simulations. The goal 
is to get you 95% of the accuracy in 1% of the 
compute time. Sometimes that works. Sometimes the 
physics disagrees.

**Physics-Informed Neural Networks (PINNs)** instead 
of feeding a network pure data, you bake the PDEs 
directly into the loss function. It's a cleaner 
approach and it doesn't need nearly as much labeled 
data. Still figuring out when it beats classical 
solvers and when it doesn't.

**Reduced-Order Models** high-dimensional simulation 
data compressed into something a human (or an 
optimizer) can actually reason about.

**Optimization under uncertainty** because real 
engineering data is noisy and real decisions still 
need to be made.

---

## Projects

**[Surrogate-model-learning](https://github.com/triasha72/Surrogate-model-learning)**  
My main repo right now. Neural network surrogates 
for aerospace simulations, still building this out.

More coming: F1 telemetry analysis with LSTM networks, 
PINN implementations from scratch.

---

## Stack

Python · PyTorch · TensorFlow · NumPy · scikit-learn · Jupyter

---

## Find me

triasha72@gmail.com  
[linkedin.com/in/triasha-sarkar](https://www.linkedin.com/in/triasha-sarkar)
