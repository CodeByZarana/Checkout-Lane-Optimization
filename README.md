# Checkout-Lane-Optimization

This project simulates and analyzes customer checkout times at self-checkout and manual cashier lanes using various probability distributions. The goal is to explore server utilization, customer waiting times, and overall lane performance to optimize the efficiency of checkout processes.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Efficient management of checkout lanes in retail environments is crucial for minimizing customer wait times and maximizing throughput. This project simulates customer behavior in self-checkout and manual cashier lanes by modeling interarrival and service times with different statistical distributions. The simulation evaluates server utilization and customer waiting times to provide insights for optimizing lane performance.

## Project Structure

- `Modelling_Project.ipynb`: The main Jupyter notebook containing the code for data analysis, simulations, and visualizations.
- `interarrival_times.csv`: Dataset containing the interarrival times of customers.
- `service_times_self_checkout.csv`: Dataset containing the service times for self-checkout lanes.
- `service_times_manual_cashier.csv`: Dataset containing the service times for manual cashier lanes.
- `README.md`: Documentation for the project.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/CodeByZarana/Checkout-Lane-Optimization.git
    cd Checkout-Lane-Optimization
    ```

2. Install the required Python packages:
    ```bash
    pip install pandas numpy matplotlib scipy
    ```

3. Ensure the datasets (`interarrival_times.csv`, `service_times_self_checkout.csv`, and `service_times_manual_cashier.csv`) are available in the project directory.

## Usage

1. Open the `Modelling_Project.ipynb` file in Jupyter Notebook or Jupyter Lab.
2. Run the cells in the notebook to load the data, perform statistical analysis, and run simulations.
3. Review the visualizations and outputs to understand the performance of the checkout lanes under different conditions.

## Results

The project provides insights into:
- The distribution of interarrival times and service times at both self-checkout and manual cashier lanes.
- Server utilization rates and customer waiting times for both types of lanes.
- Recommendations for optimizing the number of lanes and managing customer flow based on the simulation results.

## Contributing

Contributions are welcome! If you have any ideas to improve this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
