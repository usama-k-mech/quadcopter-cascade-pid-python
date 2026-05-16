# Quadcopter Cascade PID Controller - Python

Nonlinear 6-DOF simulation of a quadcopter tracking a figure-8 trajectory using a 3-loop cascade PID controller.

---

## 🔗 Official Recognition
This implementation was accepted as an official example in the c4dynamics framework:**:
- [c4dynamics/pid_cascade](https://c4dynamics.github.io/c4dynamics/programs/pid_cascade/quadcopter_pid.html)

---

## Results

| Metric | Value |
|--------|-------|
| RMSE X | 0.199 m (5.0% of X amplitude) |
| RMSE Y | 0.383 m (19.2% of Y amplitude) |
| RMSE Z | 0.002 m (0.14% of altitude) |
| Max altitude deviation | 2.53 cm |

---

## Visualizations

### Vehicle Model & Reference Frame
![Quadcopter Body Frame](src/figures/quad_frame.png)

### Control Architecture
![Cascade PID Architecture](src/figures/Cascade_PID.png)

### Figure-8 Reference Trajectory
![Figure-8 Trajectory](src/figures/Fig_8_Marked.png)

### Simulation Results
![Simulation Results](src/figures/simulation_results.png)

---

## Quick Start
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/usama-k-mech/quadcopter-cascade-pid-python/blob/main/src/quadcopter_pid.ipynb)

---

## 📁 Files
- `src/quad_pid_utils.py` - Dynamics, controllers, plotting, metrics
- `src/quadcopter_pid.ipynb` - Main simulation notebook
- `src/figures/` - Architecture and trajectory diagrams
