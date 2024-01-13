# Cascade-Controller-for-Multirotor-Drone

Quadcopter Control System Design in MATLAB
This project involves the design and analysis of a control system for the lateral dynamics of a quadcopter based on cascade architecture using MATLAB. The model used is a linearized and decoupled at low speed, the derivation of which is not covered in this work. Feel free to use any model and adjusting the requirements/inputs.

# Tools used
Matlab, Control System Toolbox, Cascade Control, Hinfinity, Monte Carlo.

# Contents
Model Construction: A quadcopter model is defined using state-space representation, considering uncertain parameters. Dynamic blocks and internal inputs/outputs are established for further analysis.

Attitude Control: One-degree-of-freedom controller for roll angle and a two-degree-of-freedom controller for roll rate are designed. The script uses the Hinfstruct optimization method for tuning the controllers to meet specified requirements.

Position Control : Similar to attitude control, one-degree-of-freedom and two-degree-of-freedom controllers are designed for lateral position and velocity. The Hinfstruct optimization method is applied for tuning to meet specified requirements.

Robust Stability Analysis : Robust stability analysis is conducted for both attitude and position control. Weighted systems are defined, and Bode diagrams are plotted to assess robust stability and performance.

Monte Carlo Study (N = 500): A Monte Carlo study is performed to evaluate system performance under parameter uncertainties. Stability, settling time, overshoot, phase margin, and gain margin are analyzed over multiple simulations.

# Requirements
MATLAB R20XX or later
Control System Toolbox
# Usage
Open the MATLAB and run the script section by section or as a whole.
View the generated plots and results to analyze the performance of the control system.
