# supersonic-double-wedge-aerofoil-analysis
Multi-method (Theory, CFD, Experiment) analysis of supersonic flow (M=1.8) on a double-wedge aerofoil. Investigated shock angles &amp; pressure distributions. ANSYS Fluent, TecQuipment AF300 Wind Tunnel.
# Supersonic Flow Analysis: Double Wedge Aerofoil (Multi-Method Approach)

## Project Overview
This repository documents my comprehensive investigation into the two-dimensional supersonic flow field (Mach 1.8, 5° Angle of Attack) around a 10° total angle double-wedge aerofoil. This project was undertaken as part of the "Advanced Aerodynamics" module at the University of Hertfordshire.

The primary goal was to analyze and compare the flow structure – specifically leading-edge shock wave angles and surface pressure coefficient (Cp) distributions – using three distinct methodologies:

1.  **Theoretical Analysis:**
    *   Application of Shock-Expansion theory.
    *   Use of Prandtl-Meyer functions for analytical predictions of wave patterns and pressure.

2.  **Computational Fluid Dynamics (CFD) Simulation:**
    *   Geometry and structured mesh generation using ANSYS DesignModeler and ANSYS Meshing.
    *   Steady-state RANS simulations performed in **ANSYS Fluent**, employing the **Spalart-Allmaras turbulence model**.
    *   Post-processing of results to visualize flow features (Mach number, Cp contours) and extract quantitative data.

3.  **Experimental Analysis:**
    *   Analysis of data acquired from the **TecQuipment AF300 intermittent supersonic wind tunnel**.
    *   **Schlieren flow visualization** for qualitative and quantitative analysis of shock wave structures.
    *   **Direct surface pressure measurements** from taps on the aerofoil model.

## Objectives
*   Characterize the supersonic flow field around the specified double-wedge airfoil.
*   Quantify key parameters (shock wave angles, pressure coefficients) using each method.
*   Evaluate the level of agreement and identify discrepancies between theoretical, numerical, and experimental results.
*   Discuss potential reasons for observed discrepancies, considering the inherent assumptions and limitations of each methodology.

## Key Findings & Learnings
This study provided valuable insights into the complexities of supersonic flow and the strengths/limitations of different analytical approaches. Discrepancies observed, particularly in pressure distributions and lower shock angles, highlighted the significant influence of viscous effects (not fully captured by theory) and the nuances of CFD modelling and experimental measurement in supersonic regimes.

## Repository Contents
*   `Advanced Aero.pdf`: The full technical report detailing methodology, results, and discussion.

## Technologies & Tools
*   **Software:** ANSYS Workbench 2025 R1 (DesignModeler, Meshing, Fluent), MATLAB.
*   **Experimental Rig:** TecQuipment AF300 Intermittent Supersonic Wind Tunnel.
