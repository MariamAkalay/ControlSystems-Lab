# ControlSystems-Lab
MATLAB/Simulink lab projects: lag compensator design and system analysis
# Control Systems Lab Projects

This repository contains two MATLAB/Simulink lab projects exploring control systems, feedback design, and controller effects.

---

## 1. Lag Compensator Design

- **Objective:** Design a lag compensator to improve steady-state accuracy while maintaining a sufficient phase margin.
- **System:** Second-order system.
- **Approach:**  
  - Started by testing a proportional controller.  
  - Designed a lag compensator to boost low-frequency gain.  
  - Analyzed the system response under **three cases of gain (K)**:  
    - **K < 30** → system responds slowly, steady-state error is high.  
    - **K = 30** → system has a balanced response.  
    - **K > 30** → faster response but risk of overshoot increases.  
- **Outcome:** Using the lag compensator, the system achieved better steady-state performance without sacrificing stability.

---

## 2. System Behavior Analysis

- **Objective:** Analyze the behavior of a system with multiple configurations and feedback loops.
- **System:** Various transfer functions connected in feedback.  
- **Approach:**  
  - Tested different gain values and system parameters.  
  - Observed how the output response changes with each configuration.  
  - Designed an adequate compensator to improve performance.
- **Outcome:** The compensator significantly improved the **steady-state accuracy** while maintaining stability, demonstrating the impact of controller design on system dynamics.

---

## Files

- `.slx` file → Simulink model of the project

## Usage

Open the `.slx` file in MATLAB/Simulink to simulate the model and explore the results.
