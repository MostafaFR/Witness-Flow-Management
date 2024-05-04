# Cinema Customer Flow Optimization Project

## Overview

This project involves the simulation of customer flow at a Cinema using the Witness software. Aimed at optimizing the customer experience during peak times, this simulation addresses the challenges posed by a single ticketing counter by proposing and evaluating the addition of automated kiosks.

## Project Features

### Detailed Simulation
- **Customer Arrival**: Modeled using a triangular distribution to simulate the arrival of customers with assigned attributes like gender, film choice, and purchase method.
- **Purchase and Activity Flow**: Tracks customer choices across different purchase points (online, kiosk, counter) and additional activities like snacks or restroom visits.
- **Dynamic Environment Handling**: Manages real-time updates to customer information and cinema logistics to optimize flow and minimize wait times.

### Technical Implementation
- **Witness Software**: Utilizes the power of Witness to simulate complex customer interactions and operational scenarios.
- **Parametric Adjustments**: Offers flexibility to adjust parameters such as the number of counters and kiosks based on simulated efficiency and customer satisfaction metrics.

## Repository Structure

- **/simulation_models**: Contains the Witness models and setup files.
- **/data**: Includes data on customer attributes, film schedules, and seating capacities.
- **/scripts**: Scripts for setting up and running simulations, as well as for analyzing the results.
- **/documentation**: Detailed documentation and project report files.

## Getting Started

To run this simulation:
1. Ensure you have Witness simulation software installed.
2. Clone this repository: git clone https://github.com/yourusername/cinema-flow-optimization.git
3. Navigate to the `/simulation_models` directory and open the simulation files with Witness.
4. Adjust the parameters as required and run the simulations to evaluate different scenarios.