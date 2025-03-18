# Computational-Science-Studies
Mainly codes and reports that I've done for "Computational Methods for Material Science and Complex Systems" course.

This repository contains various homework projects covering numerical methods and simulations in material science and complex systems. Below is a brief overview of each folder and the methods/topics involved, along with example plots taken from the reports.

---

## Newton

**Homework 01**  
**Topic**: Three-mass system connected by springs with different stiffnesses, solved via two numerical methods:  
- **Velocity Verlet Algorithm**  
- **Time-Evolution Operator (Matrix Exponential)**  

**Key Points**  
- Velocity Verlet is symplectic and conserves energy well.  
- Time-Evolution operator is exact for linear systems but can be computationally expensive for large ones.  

**Example Plot**  
Shows the positions of the three masses over time for both methods:

```markdown
![Three-mass system trajectories](images/newton_plot.png)
