# System Identification with MATLAB

## Project Overview
This project focuses on identifying dynamic systems using various modeling approaches, including ARX, FIR, and Output Error (OE) models. It explores parameter estimation techniques and evaluates model accuracy through simulation and error analysis. The work is based on two systems:
1. **System 1 (PT3):** \( G_1(s) = \frac{10}{s^3 + 5.8s^2 + 8s + 20} \)
2. **System 2 (PT2-Tt):** \( G_2(s) = \frac{0.25}{s^2 + 1.5s + 0.5} e^{-s} \)

---

## Key Features
- **Dynamic System Analysis:** Investigates impulse, step, and frequency responses for given systems.
- **Model Estimation:** Implements ARX, FIR, and OE models with various optimization techniques.
- **Noise Handling:** Studies the effect of measurement noise and explores methods to mitigate it.
- **Error Metrics:** Evaluates model accuracy using RMSE and frequency response comparisons.

---

## Objectives
1. Understand system identification principles and techniques.
2. Develop MATLAB functions for parameter estimation and model output simulation.
3. Compare and contrast modeling methods (ARX, FIR, OE) in the presence of noise.
4. Present results visually and quantitatively using RMSE and Bode plots.

---

## Skills Demonstrated
- **MATLAB Programming:** Developed reusable and parameterized functions for system identification.
- **System Modeling:** Implemented ARX, FIR, and OE models with varying complexities.
- **Optimization Techniques:** Applied least squares and nonlinear optimization methods.
- **Data Analysis:** Evaluated model performance using RMSE and frequency domain comparisons.

---

## Components and Implementation
### Tasks:
1. **Dynamic System Analysis:**
   - Analyze poles, step responses, impulse responses, and Bode diagrams of the systems.
2. **Data Generation:**
   - Create datasets using step, impulse, and Pseudo-Random Binary Signal (PRBS) inputs.
   - Add adjustable noise levels for realistic simulations.
3. **Model Estimation:**
   - ARX Model: Parameter estimation using least squares and recursive methods.
   - FIR Model: Regression matrix creation and parameter estimation.
   - OE Model: Nonlinear optimization using MATLAB's `fminunc`.
4. **Evaluation:**
   - Compare simulated outputs with actual noiseless system outputs.
   - Study noise effects on ARX estimation and validate improvements using 1/A filtering, IV method, and OE models.

### MATLAB Commands:
- System Analysis: `step`, `impulse`, `bode`, `pole`.
- Data Generation: `randn`, `filter`, `prbs`.
- Optimization: `inv`, `fminunc`.
- Plotting: `plot`, `figure`.

---

## Installation and Usage
### Requirements:
- MATLAB (latest version recommended)
- MATLAB Control System Toolbox (for system analysis functions)

### Steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/system-identification.git
