# 🌊 Computational Fluid Dynamics 🌊

<div align="center">
 <img src="https://github.com/user-attachments/assets/da846a8f-fb33-44c2-a37d-b3c912fa832a" alt="Computational Fluid Dynamics Banner" width="900"/>
</div>

> Explore the elegance of fluid behavior through rigorous theory and computational precision!

This repository is a deep dive into **Computational Fluid Dynamics (CFD)**, where partial differential equations (PDEs) reveal the secrets of fluid flow, and numerical methods bring them to life. Created with passion by Kiara Gholizad for the CFD course at Sharif University of Technology, taught by Dr. Hossein Pakzad, this repo is a tribute to the theoretical foundations of fluid dynamics. Each PDF file contains problems meticulously solved in a detailed manner to comprehensively cover every aspect of CFD. If you love derivations, stability analysis, and the beauty of mathematical physics, you're in the right place!

---

## 🌍 Why CFD Rocks

CFD is more than math—it’s the key to unlocking nature’s fluid mysteries! From shockwaves in supersonic jets to heat diffusion in engines, CFD drives innovations in aerospace, energy, and beyond. This repo equips you with the theoretical tools to master fluid dynamics. Ready to dive in?

> 🎯 **Challenge**: Run a notebook and tweak a parameter—can you spot a theoretical principle at work? Share your findings in the repo’s Discussions!

---

## 🗺️ Your Theoretical Journey

<div align="center">

| # | Study | Theory | Implementation | Key Theorems & Methods |
|:-:|:------|:-------|:---------------|:------------|
| 1 | [PDE Classification & Characteristics](#-pde-classification--characteristics) | CFD_Numerical_Methods_Part1.pdf | - | PDE Classification, Characteristic Curves, Transport Equations, Incompressible Flow, Energy Equations |
| 2 | [Finite Difference Methods I](#-finite-difference-methods-i) | CFD_Numerical_Methods_Part2.pdf | CFD_Numerical_Methods_Part2.ipynb | Backward Difference Approximations, Von Neumann Stability, Artificial Viscosity, FTCS Schemes |
| 3 | [Finite Difference Methods II](#-finite-difference-methods-ii) | CFD_Numerical_Methods_Part3.pdf | CFD_Numerical_Methods_Part3.ipynb | Taylor Series, Three-Level Schemes, Implicit Laasonen, Explicit DuFort-Frankel, Boundary Conditions |

</div>

> 💡 **Fun Fact**: The PDEs here govern everything from ocean currents to rocket aerodynamics. You’re practically a fluid dynamics detective!

---

## 🧬 PDE Classification & Characteristics

<div align="center">
 <img src="https://github.com/user-attachments/assets/7474f978-8573-4449-be18-34cf35ed10f8" alt="PDE Classification Visualization" width="1000"/>
</div>

### 📜 The Theoretical Core

Step into the heart of CFD with **Partial Differential Equations (PDEs)**, the mathematical backbone of fluid dynamics. This study explores:

- **Classification**: Sorting PDEs into hyperbolic, parabolic, and elliptic types using discriminant analysis—like decoding the language of fluids.
- **Characteristics**: Mapping the paths of information flow to understand wave propagation and diffusion.
- **Transport Equations**: Deriving concentration flow equations rooted in conservation principles.
- **Incompressible Flow**: Unraveling the elegant constraints that simplify fluid behavior.
- **Energy Equations**: Connecting temperature and flow to reveal thermodynamic insights.

This section is a theoretical feast, packed with derivations, characteristic curve analyses, and the physics of fluid motion.

### 🔑 Theoretical Highlights

- Hyperbolic PDEs: Waves racing with finite speed.
- Parabolic PDEs: Diffusion spreading energy smoothly.
- Elliptic PDEs: Equilibrium as nature’s steady state.
- Characteristic curves: The tracks of solution propagation.
- Conservation laws: The universal rules of fluid physics.

> 🧪 **Theory Tidbit**: Hyperbolic PDEs carry information like ripples on a pond. Try deriving characteristic curves for a wave equation to see the magic!

---

## 📊 Finite Difference Methods I


<div align="center">
 <img src="https://github.com/user-attachments/assets/bfe272bf-16b5-4013-84e7-e2daefb15f1b" alt="Numerical Methods Visualization" width="900"/>
</div>

### 📜 The Theoretical Core

Enter the world of **finite difference methods**, where PDEs meet computational precision. This study delves into:

- **Backward Difference Approximations**: Building third-derivative formulas via Taylor series, polynomial interpolation, and backward differences—three rigorous approaches.
- **Stability Analysis**: Applying the von Neumann method to keep the heat equation stable.
- **Artificial Viscosity**: Exploring numerical diffusion in FTCS schemes for advection equations.
- **Instability Insights**: Proving why purely advective problems can unravel computationally.

This is a theoretical masterclass in balancing accuracy and stability. Run `CFD_Numerical_Methods_Part2.ipynb` to see equations transform into vivid plots!

### 🔑 Theoretical Highlights

- Truncation errors: The mathematical price of discretization.
- Numerical stability: Where physics meets computational limits.
- Artificial viscosity: A numerical side-effect with physical meaning.
- Von Neumann analysis: A Fourier lens on stability.
- Advection challenges: The theoretical roots of instability.

> 💡 **Theory Tidbit**: Artificial viscosity acts like a damper on numerical waves. Can you derive its impact on the advection equation?

---

## 🧮 Finite Difference Methods II

<div align="center">
 <img src="https://github.com/user-attachments/assets/9961c978-def2-4fd3-994e-b63f4eadeddd" alt="Advanced Numerical Methods" width="900"/>
</div>

### 📜 The Theoretical Core

Advance your skills with sophisticated **finite difference methods** for the heat equation, blending theory and application:

- **Truncation Error Analysis**: Dissecting three-level schemes for the 1D heat equation with parameter *d*.
- **Numerical Methods**:
  - **Implicit Laasonen**: An unconditionally stable method using tridiagonal matrices.
  - **Explicit DuFort-Frankel**: A fast scheme initialized with FTCS.
- **Physical Application**: Modeling heat conduction in a marble slab with mixed boundary conditions, calculating temperature profiles and heat flux.
- **Method Comparison**: Analyzing the theoretical strengths of implicit vs. explicit approaches.

Execute `CFD_Numerical_Methods_Part3.ipynb` to analyze and visualize heat conduction, supported by rigorous mathematical formulations.

### 🔑 Theoretical Highlights

- Multi-level schemes: A theoretical puzzle in time discretization.
- Implicit stability: The power of tridiagonal systems.
- Explicit trade-offs: Balancing speed and stability.
- Boundary conditions: Bridging physics and math.
- Heat flux: Linking gradients to physical reality.

> 🎯 **Theory Challenge**: Derive the truncation error for the DuFort-Frankel method. Hint: Taylor expansions are your friend!

---

## 🚀 Future Theoretical Horizons

The journey continues! Look forward to:

- **Finite Volume Methods**: Discretizing conservation laws with precision.
- **Turbulence Modeling**: Capturing the chaotic elegance of fluids.
- **Complex Flows**: Tackling shockwaves, multiphase flows, and more.

Stay tuned for deeper derivations and computational insights!

---

## 🎬 Behind the Scenes

Crafting this repo felt like solving a PDE with infinite dimensions! My aha moment was realizing implicit methods are the theoretical bedrock of CFD—stable and elegant. Debugging the DuFort-Frankel method was like taming a numerical storm, but seeing a converging solution was pure joy.

---

## 🔧 Requirements and Setup

To explore this theoretical landscape, you’ll need:

```python
numpy               # For matrix computations
matplotlib          # To visualize theoretical results
scipy               # For tridiagonal solvers
jupyter             # For interactive exploration
sympy               # For symbolic derivations
tabulate            # For clean data display
```

---

## 🚀 Jump Right In
```bash
# Clone this repository
git clone https://github.com/kiaraGholizad/Computational-Fluid-Dynamics.git

# Equip yourself with the right tools
pip install numpy scipy matplotlib sympy tabulate

# Start your fluid dynamics adventure!
```
