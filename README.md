# Hacker Statistics – Random Walk Simulation

This project simulates a random walk process inspired by the
Hacker Statistics case study from DataCamp.

## Problem
A player starts at step 0 and rolls a die 100 times:
- 1–2: step down (minimum 0)
- 3–5: step up
- 6: roll again and move up by the second result
- With 0.5% probability, the player falls back to step 0

## Goal
Estimate the probability of reaching step 60 by repeating the simulation.

## Tools
- Python
- NumPy
- Matplotlib

## Result
With 500 simulations and a fixed random seed:
- Estimated probability: ~60.8%
