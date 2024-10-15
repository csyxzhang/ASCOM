# DCAPPSO: Dynamic Coefficient Adjustment in Parallel Particle Swarm Optimization for Asteroid Rotational Properties Inversion

This repository contains data and results from the paper "DCAPPSO: A Novel Approach for Inverting Asteroid Rotational Properties with Applications to DAMIT and Tianwen-2 Target Asteroid".

## Repository Structure

The repository is organized into four main folders:

1. **Performance_Analysis**: Contains data and results related to the performance analysis of the DCAPPSO algorithm.
2. **simulated_asteroid**: Includes data and results from the generation and inversion of synthetic lightcurves.
3. **real_asteroid**: Contains data and results for 23 real asteroids, including a case study of asteroid (44)Nysa.
4. **Asteroid(469219)Kamo'oalewa**: Holds data and results specific to the analysis of asteroid Kamo'oalewa, the target of the Tianwen-2 mission.

## Contents

### Performance Analysis

This folder demonstrates the computational efficiency of the DCAPPSO algorithm:
- Tests conducted on a high-performance computing platform with two 32-core CPUs
- Achieved a 46.030x speedup with 64 worker processes
- Efficiency analysis from 1 to 64 workers

### Simulated Asteroid

Contains synthetic lightcurve data and inversion results:
- Generated from a known Cellinoid shape model
- Demonstrates algorithm accuracy with added noise
- Showcases the 176° ambiguity in rotational phase angle inversion

### Real Asteroid

Presents data and analysis results for 23 real asteroids:
- Detailed case study of asteroid (44)Nysa using data from 16 apparitions over four decades
- Comparative analysis with DAMIT database values
- Uncertainty estimations for derived parameters (typically around 0.01° for pole orientations and less than 0.001 hr for rotational periods)

### Asteroid (469219) Kamo'oalewa

Analysis of the Tianwen-2 mission target:
- Derived rotational period: 0.460510 hr (27.63 minutes)
- Pole orientation: (134.67°, -11.39°)
- Shape analysis: moderately elongated with axis ratios b/a ≈ 0.67 and c/a ≈ 0.56
- Uncertainty analysis results

## Key Findings

- DCAPPSO algorithm shows excellent performance in determining rotational periods of asteroids
- High consistency with known values from the DAMIT database
- Provides new insights into the shape and rotational properties of Kamo'oalewa
- Demonstrates potential in supporting planetary exploration missions like Tianwen-2

## Contact

For questions regarding the data or the research, please contact:
[csyxzhang@qq.com]
