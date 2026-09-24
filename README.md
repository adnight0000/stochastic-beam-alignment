# Stochastic Beam Alignment for Sub-THz Communications

Monte Carlo evaluation of beam search strategies for initial beam alignment
in 2D and 3D sub-THz communication systems.

This work was completed as part of the **Mobile Networks Project – Sub-THz
Communications** at KTH Royal Institute of Technology.

## Overview

Highly directional antennas are important for sub-THz communication systems,
but narrow beams make initial beam alignment more challenging.

This project investigates different beam search strategies and evaluates
their alignment delay using Monte Carlo simulation.

The analysis considers both 2D and 3D search spaces and studies how
beamwidth and search strategy affect the time required to establish alignment.

## Beam-Search Strategies

Six beam-search strategies are evaluated:

1. Clockwise sequential scanning
2. Counter clockwise sequential scanning
3. Random probing with repetition
4. Random probing without repetition
5. Variable step structured scanning
6. Hybrid grid-based random scanning

## Methodology

The beam alignment process is modelled using ideal directional antenna
patterns.

For each beam-search strategy, repeated Monte Carlo trials are performed
to estimate alignment performance across different beamwidths.

The evaluation considers:

- Mean alignment time
- Alignment time probability distributions
- Effect of beamwidth
- Differences between 2D and 3D search spaces

## Implementation

The simulation is implemented in Python using:

- NumPy
- Matplotlib
- Jupyter Notebook

The complete implementation and experiments are available in
[`beam_alignment.ipynb`](beam_alignment.ipynb).

## Key Observations

The simulations demonstrate the trade-off between beamwidth and alignment
delay.

Randomized search strategies can reduce alignment delay compared with
sequential scanning, while structured and hybrid strategies become
particularly useful when searching the larger 3D directional space.

## My Contribution

This project was completed as a group project.

My primary contribution was **Part 3: Stochastic Beam Alignment**, including:

- Implementation of 2D and 3D beam-alignment simulations
- Implementation and comparison of multiple beam-search strategies
- Monte Carlo evaluation across different beamwidths
- Analysis and visualization of alignment-time performance

## Project Report

The complete project report is available here:

[View the project report](report/Sub_THz_Communications_Project_Report.pdf)

## Authors

- Georgios Telis
- Sunidhi Gopal Adhyapak
- Aditya Datta
- Pranathi Ashwath

Supervisor: Vitaly Petrov

KTH Royal Institute of Technology, 2026
