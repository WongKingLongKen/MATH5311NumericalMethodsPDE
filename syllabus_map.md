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

### **1 Stability analysis, truncation error, convergence**
- **Isaacson & Keller** → Ch. 2–3 (local truncation error, stability, convergence theory)  
- **LeVeque** → Ch. 2–4 (consistency, stability, Lax equivalence theorem)  

### **2 Finite Difference Method**
- **2.1 Heat equation (2D)** → LeVeque Ch. 6 (parabolic PDEs, diffusion schemes)  
- **2.2 Advection (1D)** → LeVeque Ch. 7 (hyperbolic PDEs, upwind schemes)  
- **2.3 Dispersion & modified equation** → LeVeque Ch. 8 (dispersion analysis, modified equations)  
- **2.4 Upwind extension** → LeVeque Ch. 7–8 (higher-order upwind, flux limiters)  

### **3 Basics of Finite Volume Method**
- **3.1 Finite volume basics** → LeVeque Ch. 12 (finite volume framework)  
- **3.2 Godunov & Riemann problem** → LeVeque Ch. 13; **Toro – Riemann Solvers**  
- **3.3 Wave equation & pollution effects** → LeVeque Ch. 9 (wave propagation, numerical dispersion)  
- **3.4 FD for elliptic & geometry** → Quarteroni & Valli Ch. 2–3 (elliptic PDEs, general geometries)  

### **4 Basics of Finite Element Method**
- **4.1 Variational form & FEM** → **Johnson** Ch. 1–3  
- **4.2 Boundary conditions & high-order FEM** → Johnson Ch. 4–5; Quarteroni & Valli Ch. 6  
- **4.3 FEM in 2D** → Johnson Ch. 6 (triangular elements, basis functions)  
- **4.4 Discontinuous Galerkin** → Quarteroni & Valli Ch. 7; MIT 18.336 notes  
- **4.5 Theoretical aspects** → Johnson Ch. 7–8 (error estimates, convergence)  
- **4.6 Time discretization** → Quarteroni & Valli Ch. 8 (implicit/explicit schemes in FEM)  

### **5 Linear Equation Solvers**
- **5.1 Iterative solvers** → Isaacson & Keller Ch. 7 (Jacobi, Gauss–Seidel)  
- **5.2 Krylov & preconditioning** → **Saad – Iterative Methods** Ch. 6–8  
- **5.3 Multigrid** → **Hackbusch – Multigrid Methods**  
- **5.4 Nonlinear solvers** → Quarteroni & Valli Ch. 9 (Newton, fixed-point methods)  

---

## 🎯 Recommended Reading Strategy
- Use **Isaacson & Keller** for **theory-heavy sections (1 & 5.1)**.  
- Use **LeVeque** for **finite difference & finite volume (2–3)**.  
- Use **Johnson** for **finite element rigor (4)**.  
- Supplement with **Quarteroni & Valli** for **unified coverage and time discretization**.  
- Add **Saad & Hackbusch** for **modern iterative solvers**.  
