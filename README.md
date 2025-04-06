# Computational Science Studies

This repository contains codes and reports for various projects in computational science focused on material science and complex systems.

---

## Newton

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <h3>Simulation of a Three-Mass Spring System</h3>
    <p>Compares the velocity Verlet algorithm with the time-evolution operator method to simulate a three-mass system connected by springs.</p>
  </div>
  <div style="flex: 1; text-align: right;">
    <img src="images/1.png" alt="Newton Plot" width="400">
  </div>
</div>

---

## Fourier

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <h3>Derivative Approximation Methods</h3>
    <p>Analyzes and compares derivative approximation using Finite-Difference methods, FFT-based methods, and the DFT matrix approach on smooth, periodic functions.</p>
  </div>
  <div style="flex: 1; text-align: right;">
    <img src="images/2.png" alt="Fourier Plot" width="400">
  </div>
</div>

---

## Schrödinger

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <h3>Tight-Binding Model for Graphene Nanoribbons</h3>
    <p>Implements a tight-binding model with modified edge hopping to calculate band structures of armchair graphene nanoribbons, highlighting the effect of edge corrections.</p>
  </div>
  <div style="flex: 1; text-align: right;">
    <img src="images/3.png" alt="Schrödinger Plot" width="400">
  </div>
</div>

---

## Prandtl

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <h3>Prandtl-Tomlinson Model for Atomic-Scale Friction</h3>
    <p>Studies the PT model to simulate friction at the atomic scale, reproducing friction loops and analyzing the impact of thermal fluctuations via Langevin dynamics.</p>
  </div>
  <div style="flex: 1; text-align: right;">
    <img src="images/4.png" alt="Prandtl Plot" width="400">
  </div>
</div>

---

## Mandelbrot

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <h3>Fractal Geometry via the Chaos Game</h3>
    <p>This project extends the chaos game approach to generate a pentagonal fractal (often termed the “Sierpinski pentagon”). By iteratively moving a fraction toward randomly chosen vertices of a regular pentagon, the fractal emerges. Two methods are used to quantify its complexity: the self-similarity dimension, yielding D<sub>self</sub> ≈ 1.6723, and the pointwise correlation dimension, with D<sub>corr</sub> ≈ 1.6750. These complementary approaches confirm the fractal’s scale-invariant nature.</p>
  </div>
  <div style="flex: 1; text-align: right;">
    <img src="images/5.png" alt="Mandelbrot Plot" width="400">
  </div>
</div>

---

## Metropolis

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <h3>Monte Carlo Simulation of the Ising Model</h3>
    <p>This work implements a Monte Carlo simulation of the 2D Ising model to explore magnetic phase transitions in both ferromagnetic (J = +1) and antiferromagnetic (J = −1) systems. The study examines the effects of temperature and external magnetic fields on order parameters, employing the Metropolis algorithm accelerated by numba for efficiency. Key observations include the behavior of magnetization and staggered magnetization, as well as the impact of non-ideal order parameters on the sharpness of phase transitions.</p>
  </div>
  <div style="flex: 1; text-align: right;">
    <img src="images/6.png" alt="Metropolis Plot" width="400">
  </div>
</div>

