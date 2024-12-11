# DCAPPSO: Dynamic Coefficient Adjustment in Parallel Particle Swarm Optimization for Asteroid Rotational Properties Inversion

This repository contains data and results from the paper "DCAPPSO: A Novel Approach for Inverting Asteroid Rotational Properties with Applications to DAMIT and Tianwen-2 Target Asteroid".

## Repository Structure

The repository is organized into five main folders:

1. **Performance_Analysis**: Contains data and results related to the performance analysis of the DCAPPSO algorithm.
2. **simulated_asteroid**: Includes data and results from the generation and inversion of synthetic lightcurves.
3. **real_asteroid**: Contains data and results for 23 real asteroids, including a case study of asteroid (44) Nysa.
4. **Asteroid (469219)Kamo'oalewa**: Holds data and results specific to the analysis of asteroid Kamo'oalewa, the target of the Tianwen-2 mission.
5. **Supplementary_experiments**: Includes additional inversion experiments for asteroids (15) Eunomia, (21) Lutetia, and (433) Eros, highlighting the effects of lightcurve quantity and diversity on inversion accuracy.

## Contents

### Performance Analysis

This folder demonstrates the computational efficiency of the DCAPPSO algorithm:
- Tests conducted on a high-performance computing platform with two 32-core CPUs
- Achieved a **48.617x speedup** with 100 worker processes
- Efficiency analysis performed with 1, 2, 4, 8, 16, 32, 64, and 100 workers

### Simulated Asteroid

Contains synthetic lightcurve data and inversion results:
- Generated from a known Cellinoid shape model
- Demonstrates algorithm accuracy even with added noise
- Showcases the **176° ambiguity** in rotational phase angle inversion

### Real Asteroid

Presents data and analysis results for 23 real asteroids:
- Detailed case study of asteroid (44) Nysa using data from **16 apparitions** over four decades
- Comparative analysis with DAMIT database values
- Uncertainty estimations for derived parameters (typically around **0.01°** for pole orientations and less than **0.001 hr** for rotational periods)

### Asteroid (469219) Kamo'oalewa

Analysis of the Tianwen-2 mission target:
- Derived rotational period: **0.460510 hr (27.63 minutes)**
- Pole orientation: **(134.67°, -11.39°)**
- Shape analysis: moderately elongated with axis ratios **b/a ≈ 0.67** and **c/a ≈ 0.56**
- Includes uncertainty analysis results

### Supplementary Experiments

This folder contains additional experiments highlighting the impact of lightcurve quantity and diversity on inversion accuracy. The folder includes data and results for the following asteroids:

- **(433) Eros**:
  - Using **20 lightcurves**: Pole orientation longitude = **200.94°**, latitude = **-41.21°**, rotational period = **5.271816 hr**
  - Using **40 lightcurves**: Pole orientation longitude = **201.75°**, latitude = **7.68°**, rotational period = **5.269156 hr**
  - Results demonstrate improved accuracy in pole orientation inversion as lightcurve quantity increases.

- **(15) Eunomia**:
  - Using **7 lightcurves**: Pole orientation = **(93.59°, -78.32°)**, rotational period = **6.082754 hr**
  - Highlights the importance of lightcurve quantity in accurate pole determination.

- **(21) Lutetia**:
  - Using **7 lightcurves**: Pole orientation = **(38.55°, -13.04°)**, rotational period = **8.169019 hr**
  - Results reveal decreased precision in pole orientation inversion with fewer lightcurves.

These experiments confirm that increasing the diversity and quantity of lightcurves significantly improves the reliability of pole orientation inversion, while rotational period estimations remain accurate even with fewer lightcurves.

## Key Findings

- The DCAPPSO algorithm shows excellent performance in determining the rotational periods and pole orientations of asteroids.
- Results demonstrate high consistency with known values from the DAMIT database.
- Supplementary experiments highlight the importance of lightcurve quantity and diversity in improving pole orientation accuracy.
- Provides new insights into the shape and rotational properties of Tianwen-2's target asteroid, Kamo'oalewa.
- Demonstrates potential in supporting planetary exploration missions like Tianwen-2.

## Contact

For questions regarding the data or the research, please contact:
[csyxzhang@qq.com]
