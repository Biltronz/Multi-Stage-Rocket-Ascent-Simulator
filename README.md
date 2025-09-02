# Multi-Stage-Rocket-Ascent-Simulator

A Python simulation of a multi-stage rocket ascent under gravity and atmospheric drag. The simulation models:

- Multiple rocket stages with given mass, thrust, burn rate, and burn time.
- Gravity decreasing with altitude.
- Atmospheric density decreasing with altitude.
- Drag forces acting on the rocket a function of atmospheric density and velocity.
- Coast phase after final stage burnout.

## Features
- Produces time series data for **altitude, velocity, acceleration, mass, and drag**.
- Saves data as `multi_stage_rocket_simulation.csv` for further analysis.
- Generates **plots of all major parameters over time**.

## Installation
```bash
pip install numpy matplotlib pandas
