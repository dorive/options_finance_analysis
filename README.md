# Delta-Hedging Simulation for European Options

## Overview

This Python project is a simulation of delta-hedging for European options. It aims to analyze the impact of hedging frequency on the distribution of the Profit and Loss (PnL). Delta-hedging is a risk management strategy used by options traders to minimize the exposure to changes in the underlying asset's price.

In this simulation, thousands of Brownian motion paths for the underlying stock price are generated, and a delta-hedge is performed for each path. The resulting PnL is then analyzed to understand how varying the hedging frequency affects its distribution.

## Requirements

- Python 3
- Jupyter Notebook

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/dorive/ options_finance_analysis.git

2. Navigate to the project directory:

   ```bash
   cd  options_finance_analysis

3. Open the Jupyter Notebook:

   ```bash
    jupyter notebook delta_hedging_jupyter.ipynb

## Simulation Details

- The delta_hedging_simulation.ipynb Jupyter Notebook contains the Python code for the simulation.
- The simulation generates a large number of stock price paths using Brownian motion.
- Delta-hedging is performed for each path, and the PnL is calculated.
- The PnL distribution is analyzed to observe how hedging frequency impacts its variance.

## Results

The main observation from this simulation is that as the hedging frequency increases, the variance of the PnL decreases, converging toward zero. This behavior follows an inverse square root relationship, where increasing the frequency of delta-hedging results in diminishing variance.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to contact me:

    Name: David Orive-Miguel
    LinkedIn: www.linkedin.com/in/david-orive-miguel-42262890
