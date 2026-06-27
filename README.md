# Skybreaker Rocket: 6-DOF Flight Dynamics & Trajectory Optimization

## Overview
This repository contains a Python-based 6-Degrees of Freedom (6-DOF) flight simulation for the "Skybreaker" rocket, developed as part of Faraday Rocketry UPV. The primary objective of this project is to validate the vehicle's performance envelope and determine the optimal launch heading to maximize apogee under specific environmental conditions at the INTA launch site.

## Key Features included
* **6-DOF Simulation:** Utilization of the RocketPy library to model complex flight dynamics, factoring in variable mass inertia, thrust curves, static margins, and Mach-dependent drag coefficients.
* **Wind Compensation & Optimization:** Analysis weathercocking tendencies against specific wind vectors (Y: -5.76 m/s, X: 4.39 m/s) to mathematically optimize the launch rail heading.
* **Data Visualization:** Employment RocketPy's native plotting methods (`FlightPlots`) to generate comprehensive 2D and 3D plots of the rocket's trajectory, stability margins, angle of attack, and acceleration. 

## Project Outcomes
By running the simulation across multiple iterations, the model successfully demonstrated that adjusting the launch heading to 145° optimally compensated for wind drift, maximizing the apogee at 2,837.5 meters while maintaining safe stability parameters.

## Files Included
* `Aitor_Pérez_Grau_skybreaker_analysis.ipynb` - The main Python script in Jupiter notebook selected for convenience in the execution, containing the environment setup, motor/rocket instantiation, and optimization logic.
* `Analisis_vuelo_Skybreaker.pdf` - The detailed 14-page technical report containing the mathematical reasoning and exported visual data.

## Skills Demonstrated
Python (OOP, NumPy), RocketPy (6-DOF, FlightPlots), Flight Dynamics, Data Visualization, and Technical Reporting.
