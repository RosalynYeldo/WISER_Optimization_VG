# Project Name : Quantum Portfolio Optimization with PennyLane

## Team Name : Rosalyn Yeldo  

## Team Members & WISER Enrollment IDs  
- Rosalyn Yeldo - gst-VWNmCG4gXLfEwC4

---

## Project Summary   
This project, Quantum Portfolio Optimization with PennyLane, explores how quantum algorithms can be applied to asset allocation problems in finance. The goal is to find an optimal mix of assets that balances expected returns with risk, based on the Markowitz model.
I reformulated the problem as a Quadratic Unconstrained Binary Optimization (QUBO) task, which can be solved using the Quantum Approximate Optimization Algorithm (QAOA). Using PennyLane, I built a hybrid quantum-classical workflow:
Prepared synthetic asset return data and calculated the covariance matrix.
Encoded the optimization problem into a QUBO format.
Designed a QAOA circuit and optimized its parameters using a classical optimizer.
Interpreted the quantum output to determine asset selections.

Tests on small asset sets showed that QAOA could identify portfolio configurations close to the classical optimum, while exploring alternative solutions.

Due to current quantum hardware limitations, the implementation was tested on a simulator. Future work could involve using real market data, trying deeper QAOA circuits, and running on actual quantum devices.

---

## Presentation Deck 
