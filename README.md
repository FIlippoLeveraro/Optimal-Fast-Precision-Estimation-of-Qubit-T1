

Using Lindbladian formalism to describe open quantum system behavior, and focusing on quantum jumps
for decay rate measurement using weak continuous measurements, first in the context of
Gaussian variables and later within a Poisson framework, I demonstrate both theoretically and numerically how my newly developed method can significantly enhance qubit decay rate measurements to its theoretical limit. 

Part of this work has been then experimentally executed by MIT researcher F.Berritta et al (2026) Real-time adaptive tracking of fluctuating relaxation rates in superconducting qubits, published on Physical Review X 16 (1), 011025

Most of this protocol still needs to be experimentally proven.

Using Lindblad Master equation

<img width="348" height="58" alt="image" src="https://github.com/user-attachments/assets/65a5cf1d-4128-4d51-89ff-abadd1f1cadf" />

and considering weak gaussian measuerements

<img width="417" height="74" alt="image" src="https://github.com/user-attachments/assets/7380780a-ed2d-4720-bd13-d4193cd8ce09" />

we can transition to poisson framwork

<img width="220" height="69" alt="image" src="https://github.com/user-attachments/assets/5ed59be7-582a-4212-a560-092e8a20f823" />

determine the outocome statistics

<img width="463" height="64" alt="image" src="https://github.com/user-attachments/assets/23bea4ff-5fb0-4d06-afe9-5ec4a801293a" />
<img width="129" height="73" alt="image" src="https://github.com/user-attachments/assets/73bbccc4-eca8-46bf-9c0c-9aebd29a25a8" />

and solve Lindblad Master Equation for the dynamics, so that state evolves

<img width="487" height="112" alt="image" src="https://github.com/user-attachments/assets/da4acc58-572b-4085-b45d-c1d013e2de93" />

This can be solve stochastically using Lindblad SME

<img width="343" height="49" alt="image" src="https://github.com/user-attachments/assets/eab64f4b-20d3-4524-972a-224645e10cc7" />

Now the target is to determine precision-time optimized measurment.
Wecan derive the maximum likelihood estimator of the decay paramenter of the jump operators.

We first determine the dynamics

<img width="447" height="126" alt="image" src="https://github.com/user-attachments/assets/59607f3f-d4ca-4617-bb3e-98c4f2729f08" />

we then find that the optimal measurment is given by Lambert W function function-like for a single body problem.

<img width="258" height="65" alt="image" src="https://github.com/user-attachments/assets/9e46c86e-03a8-41f4-bada-98c66e271f24" />

For 3 body problem, we can solve 3 different partial differential equation like the following one

<img width="458" height="225" alt="image" src="https://github.com/user-attachments/assets/37ce5677-25b6-47ee-868d-3603a1a283c1" />

and then solve for 

<img width="458" height="86" alt="image" src="https://github.com/user-attachments/assets/ac0569a7-56f7-44a6-8380-18c42631dbcb" />

