# Kepler's Laws from Data

Rediscovering Kepler's three laws of planetary motion from NASA JPL Horizons data, using Python, linear regression and Fourier regression. Mars is the main example.

## Contents

| File | What it is |
| --- | --- |
| `kepler_presentation.pdf` | Slides from the talk (27 slides). |
| `notebooks/kepler_laws.ipynb` | The analysis. Runs from top to bottom with the data in this folder. |
| `notebooks/get_planet_data.ipynb` | Downloads the planet data from the JPL Horizons API. Only needed to refresh the data. |
| `planet_data/` | Daily positions and velocities of the eight planets, 2020-2024 (AU and AU/day, heliocentric, J2000). |
| `notebooks/plots/` | Figures used in the slides. |

## Results

| Law | Check | Result |
| --- | --- | --- |
| 1. Ellipse | eccentricity of Mars, from distances and from regression | 0.0934 and 0.0934 |
| 2. Equal areas | variation of the area swept per day | about 0.002% |
| 3. Harmonic law | slope of log T against log a, four inner planets | 1.5003 (expected 1.5) |

## Running it

Install `pandas numpy matplotlib seaborn scikit-learn sympy jupyter`, open `notebooks/kepler_laws.ipynb` and run all cells. The data source is the NASA JPL Horizons system.
