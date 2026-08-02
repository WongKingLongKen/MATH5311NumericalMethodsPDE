## 1 Stability analysis, local truncation error analysis, convergence analysis
### 1.1 Truncation error
### 1.2 Implementaion and stability
### 1.3 Stability and implicit methods
### 1.4 Time stepping and general BCs
## 2 Finite difference method
### 2.1 Finite difference for 2D heat equation
### 2.2 Finite difference for 1d advection
### 2.3 Dispersion analysis and modified equation .
### 2.4 Extension of upwind scheme
## 3 Basics of finite volume method
### 3.1 Finite volume
### 3.2 Godunov scheme and Riemann problem
### 3.3 Wave equation and pollution effects
### 3.4 FD for elliptic equation and general geometry
## 4 Basics of finite element
### 4.1 Variational form and FEM
### 4.2 Boundary conditions and high order FEM
### 4.3 Building Blocks for FEM in 2D
### 4.4 Discontinuous Galerkin method
### 4.5 Some theoretical aspects of FEM
### 4.6 More on time discretization
## 5 Basic linear equation solver 45
### 5.1 Basic iterative linear solvers
### 5.2 Krylov method and preconditioning
### 5.3 Basic Introduction to multigrid
### 5.4 On the nonlinear system solver

---

## Syllabus-to-Reference Mapping

### **1 Stability, truncation error, convergence**
- **Isaacson Ch. 8 (ODEs)** → Sections on truncation error, consistency, convergence, stability (pp. 410–418).  
- **Isaacson Ch. 9 (PDEs)** → General theory of consistency, convergence, stability (pp. 514–523).  
- Still relevant: rigorous foundation for truncation error and stability.  
- Outdated: does not cover modern implicit schemes or adaptive time-stepping.  
  → Use **LeVeque – Finite Difference Methods** for implicit methods and time-stepping.  

---

### **2 Finite Difference Method**
- **Isaacson Ch. 9** → Laplace, wave, and heat equations with FD schemes (pp. 445–505).  
- Good for classical FD schemes and von Neumann stability.  
- Missing: dispersion analysis, modified equations, modern upwind extensions.  
  → Use **LeVeque** for dispersion & upwind schemes; **Strikwerda – Finite Difference Schemes** for deeper PDE-focused FD analysis.  

---

### **3 Finite Volume Method**
- Isaacson does not cover finite volume or Godunov schemes.  
  → Use **LeVeque Ch. 12–13** for finite volume & Godunov; **Toro – Riemann Solvers** for Riemann problems and pollution effects.  

---

### **4 Finite Element Method**
- Isaacson has no FEM coverage.  
  → Use **Johnson – Numerical Solution of PDEs by FEM** for variational form, boundary conditions, DG methods.  
  → Supplement with **Quarteroni & Valli – Numerical Approximation of PDEs** for time discretization and theoretical aspects.  

---

### **5 Linear Equation Solvers**
- **Isaacson Ch. 2** → Gaussian elimination, Cholesky, Jacobi, Gauss–Seidel, iterative methods (pp. 29–82).  
- **Isaacson Ch. 3** → Nonlinear solvers (Newton, chord, false position, Bairstow).  
- Still useful for classical iterative solvers.  
- Missing: Krylov methods, preconditioning, multigrid.  
  → Use **Saad – Iterative Methods for Sparse Linear Systems** for Krylov/preconditioning.  
  → Use **Hackbusch – Multigrid Methods** for multigrid.  

---

## Recommended Reading Strategy
- Use **Isaacson & Keller** for **theory-heavy sections (1 & 5.1)**.  
- Use **LeVeque** for **finite difference & finite volume (2–3)**.  
- Use **Johnson** for **finite element rigor (4)**.  
- Supplement with **Quarteroni & Valli** for **unified coverage and time discretization**.  
- Add **Saad & Hackbusch** for **modern iterative solvers**.  

---

## Lecture Notes
start with MIT 18.336 — it’s comprehensive and modern. Pair it with Cambridge FEM notes for the finite element part. Use Trefethen’s notes for dispersion/pollution effects.
