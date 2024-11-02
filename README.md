# Control Systems Design Project

This project is part of the **Control Systems** module and focuses on designing and simulating different types of controllers (P, PI, PD, and PID) for a second-order system using **LTspice**. Each controller’s effect on the system’s stability, response time, and overall performance is analyzed.

## Project Overview
Control systems are fundamental in engineering, enabling precise control over dynamic systems. This project investigates how different controllers impact a second-order system’s response, allowing for a deeper understanding of system behavior and performance.

## Table of Contents
- [Introduction](#introduction)
- [Objectives](#objectives)
- [Project Structure](#project-structure)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction
In this project, various control techniques are applied to a second-order system to analyze the influence of each controller on the system's response. The controllers include:
- **Proportional (P)**: Adjusts control action proportional to the error.
- **Proportional-Integral (PI)**: Reduces steady-state error by integrating the error over time.
- **Proportional-Derivative (PD)**: Uses the derivative of the error to anticipate future error trends.
- **Proportional-Integral-Derivative (PID)**: Combines all three actions to optimize system response.

## Objectives
The main goals of this project are:
1. **Design and Implement** P, PI, PD, and PID controllers for a second-order system.
2. **Analyze System Response** to determine:
   - Maximum Peak Overshoot
   - Rise Time
   - Settling Time
   - Steady-State Error

## Project Structure
The repository includes the following files:
- **Report PDF**: Documentation of the design process and analysis results.
  - `EC5030_DesignProject_2020e050.pdf`: Detailed report on the control system designs.
- **LTspice Simulation Files**: `.asc` files for LTspice simulations of each controller.
  - `p_controller.asc`: LTspice simulation file for the P controller.
  - `pi_controller.asc`: LTspice simulation file for the PI controller.
  - `pd_controller.asc`: LTspice simulation file for the PD controller.
  - `pid_controller.asc`: LTspice simulation file for the PID controller.

## Installation and Setup
1. **Install LTspice**: 
   - Download LTspice from [Analog Devices’ LTspice page](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html).
2. **Clone the Repository**:
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/yourusername/Control_Systems_Project.git
     ```

## Usage
### Running Simulations in LTspice
1. Open LTspice on your computer.
2. Open the desired `.asc` file:
   - `p_controller.asc` for P controller simulation.
   - `pi_controller.asc` for PI controller simulation.
   - `pd_controller.asc` for PD controller simulation.
   - `pid_controller.asc` for PID controller simulation.
3. **Run the Simulation**:
   - In LTspice, click the **Run** button (or press F9) to start the simulation.
   - Observe and analyze the output waveforms, focusing on rise time, overshoot, and settling time for each controller.

## Results
The following results were obtained for each controller type:
- **P Controller**: High peak overshoot, simple implementation, limited error correction.
- **PI Controller**: Eliminates steady-state error but can increase settling time.
- **PD Controller**: Reduces overshoot and settling time but sensitive to noise.
- **PID Controller**: Combines all effects for optimal control, balancing stability, response time, and error correction.

Each controller type’s influence on the system’s behavior is discussed in detail in the [project report](./EC5030_DesignProject_2020e050.pdf).

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
