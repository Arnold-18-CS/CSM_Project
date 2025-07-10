# CSM Simulation Groupwork Project

## Project Overview

This project simulates a single-server queue system for a bank using Python. Customers arrive randomly and are served on a first-come, first-served basis. The simulation models the arrival, waiting, and service process for 500 customers and analyzes key performance metrics.

## Assumptions

- Inter-arrival times of customers are uniformly distributed between 1 and 8 minutes.
- Service times are uniformly distributed between 1 and 6 minutes.
- There is only one server (single-server queue).
- The queuing discipline is FIFO (First-In, First-Out).

## Features

- Discrete-event simulation using SimPy
- Generation of inter-arrival and service times for 500 customers
- Calculation of performance metrics (wait times, queue lengths, idle times, etc.)
- Export of simulation results to CSV
- Visualizations: histograms, scatter plots, and line charts

## Setup Instructions

1. **Clone the repository** (if applicable) and navigate to the project directory.
2. **Create and activate a virtual environment:**

   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   # or
   source venv/bin/activate  # On macOS/Linux
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Running the Simulation

- Open `simulation.ipynb` in Jupyter Notebook or VSCode.
- Run all cells to execute the simulation.
- The simulation will generate a CSV file (`Simulation_Results.csv`) with detailed results.

## Output & Visualizations

The notebook produces the following outputs:

- **Simulation Table:** A table of all customers with their arrival, wait, service, and departure times.
- **Visualizations:**
  - Histogram of Customer Wait Times
  - Histogram of Time in System
  - Scatter Plot: Arrival Time vs. Wait Time
  - Queue Length Over Time
  - Idle Time Before Service for Each Customer
  - Cumulative Number of Customers Served Over Time

## Dependencies

All required packages are listed in `requirements.txt`. Key packages include:

- simpy
- pandas
- matplotlib
- numpy

## Authors

- Group members of CSM Simulation Project

## License

This project is for educational purposes.
