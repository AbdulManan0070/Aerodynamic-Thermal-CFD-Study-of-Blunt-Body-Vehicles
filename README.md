# CFD Analysis of Blunt Vehicle Geometry

This repository contains a Fluid Mechanics II course project involving **computational fluid dynamics (CFD)** simulations on a **blunt boxy vehicle geometry** using **ANSYS Fluent**. The study investigates aerodynamic and thermal behavior under varying flow and geometric conditions, focusing on lift, drag, pressure fields, heat transfer, and vortex shedding patterns.

---

##  Project Overview

The objective of this project was to evaluate the aerodynamic characteristics of a vehicle-like blunt body with a drag coefficient of approximately **0.608**, using CFD simulations. Multiple iterations were conducted to study the influence of:

- Inlet velocity
- Angle of attack
- Body dimensions
- Edge curvature
- Temperature distributions

These parameters were analyzed under **steady-state**, **transient**, and **heat-transfer** conditions.

---

##  Software & Tools Used

- **ANSYS Workbench – Fluent (CFD)**
- **Mesh Generation Tools (ANSYS Mesher)**
- **Post-processing of Flow Fields & Graphs**

---

##  Geometry Details

The baseline body shape consisted of a **rectangular prism with rounded edges**, selected to match the desired drag coefficient value (≈ 0.608). Rounded geometry induces:

- High pressure drag
- Large wake region
- Flow separation at trailing edges

---

##  Simulation Study

Three main simulation iterations were performed:

### **Iteration 1**
- Geometry: 4 × 2 m with 0.3 m edge radius
- Velocity: 200 m/s
- Analyses: Steady, Transient, Heat Transfer

Key observations:
- Strong wake region → high drag
- Oscillatory vortex shedding in transient mode
- Temperature gradients concentrated at leading edges

---

### **Iteration 2**
- Velocity increased to 500 m/s
- Body rotated (90° angle of attack)
- Analyses: Steady, Transient, Heat Transfer

Key observations:
- Higher lift & drag forces
- Intensified flow instability
- Increased thermal gradients

---

### **Iteration 3**
- Geometry scaled to 5 × 3 m
- Edge radius: 0.7 m
- Temperature conditions applied
  - Body: 800 K
  - Inlet / Outlet: 500 K

Key observations:
- Increased frontal drag
- Higher vortex energy in transient flow
- Large temperature accumulation at leading region

---

##  Key Parameters Evaluated

- **Drag (Cd) & Lift (Cl)**
- **Velocity contours**
- **Pressure distribution**
- **Temperature gradients**
- **Vortex shedding patterns**
- **Wake behavior**

---

##  Conclusions

The study demonstrated that:

- Higher inlet velocities significantly increase drag, lift, and unsteady flow behavior.
- Larger body dimensions result in enhanced wake formation and pressure drag.
- Thermal loads accumulate near stagnation points, especially at high velocities.
- Edge rounding reduces but does not eliminate turbulent wake effects for blunt bodies.

These findings highlight the importance of shape optimization and thermal management in vehicle aerodynamics.

---



