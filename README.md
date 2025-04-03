# Brownian Motion Simulations in Python

This repository contains a single Jupyter Notebook—`brownian motion.ipynb`—that demonstrates simulations of 1-D and 2-D Brownian motion using Python's `numpy`, `matplotlib`, and `random` libraries.

## Overview

The Notebook covers the following topics:

- **1-D Brownian Motion:**  
  - Simulates a 1-D random walk.
  - The process stops when it reaches the absorption point at **50**.
  - The resulting path is plotted to visualize the trajectory.

- **2-D Brownian Motion (Initial Domain [-50, 50]):**  
  - Simulates a 2-D random walk where both the domain and range are defined as **[-50, 50]**.
  - The process is designed to stop once it reaches the absorption point at **(50, 0)**.
  - A single run is plotted to show the path taken in 2-D space.

- **Multiple Runs for 2-D Simulation:**  
  - Performs **100 runs** and **1000 runs** of the 2-D Brownian motion.
  - Histograms of the endpoint distributions are plotted.
  - Key statistics—**mean, standard deviation, median, mode, and variance**—are calculated to assess the behavior of the system.

- **Modified Domain in 2-D Simulation:**  
  - The simulation domain is adjusted from **[-50, 50]** to **[-25, 25]**.
  - The Notebook includes plots to demonstrate how changing the domain affects the random walk behavior.

## Getting Started

### Prerequisites

Ensure you have the following:
- **Python 3.7+**
- **Jupyter Notebook** or JupyterLab

The Notebook requires the following Python libraries:
- `numpy`
- `matplotlib`
- `scipy`
- Python’s built-in `random` module

You can install the necessary libraries using pip:

```bash
pip install numpy matplotlib scipy
```

### Running the Notebook

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ian0671/Brownian-Motion.git
   cd brownian-motion-notebook
   ```

2. **Launch Jupyter Notebook or JupyterLab:**

   ```bash
   jupyter notebook
   ```
   or

   ```bash
   jupyter lab
   ```

3. **Open the Notebook:**
   Open the file `brownian motion.ipynb` to start exploring and running the simulations interactively.

## Notebook Structure

The Notebook is organized into the following sections:

1. **Introduction:**  
   Provides background on Brownian motion and outlines the objectives of the simulations.

2. **1-D Brownian Motion Simulation:**  
   - Code to simulate a 1-D random walk.
   - The simulation stops once the process reaches an absorption point at **50**.
   - A plot is generated to visualize the path.

3. **2-D Brownian Motion Simulation (Single Run):**  
   - Simulates the 2-D Brownian motion in a domain of **[-50, 50]**.
   - Stops when the process reaches the absorption point at **(50, 0)**.
   - A plot shows the resulting 2-D trajectory.

4. **Statistical Analysis with Multiple Runs:**  
   - The Notebook performs **100 runs** and **1000 runs** of the 2-D simulation.
   - Histograms of endpoints (or other designated metrics) are generated.
   - Statistical measures—mean, standard deviation, median, mode, and variance—are extracted from the simulation data, offering insights into the distribution.

5. **Modified Domain Analysis:**  
   - Adjusts the 2-D simulation domain from **[-50, 50]** to **[-25, 25]**.
   - Includes updated plots to compare the behavior under the new domain.

## Results

Upon running the Notebook, you will obtain:
- A visualization of the 1-D Brownian motion with an absorption point at 50.
- A detailed 2-D simulation where the process stops at (50, 0) for a single-run scenario.
- Histograms and computed statistics (mean, standard deviation, median, mode, variance) for 100 and 1000 runs of the 2-D simulations.
- Comparative visualizations showing the effect of reducing the simulation domain on the 2-D random walk.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

