# Dynamic Network Slicing for Enhanced Wi-Fi Performance

This project demonstrates dynamic network slicing for enhanced Wi-Fi performance in 5G networks. It explores techniques to improve resource allocation and network efficiency by simulating and analyzing network slicing in real-time.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Objectives](#Objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

---

## Project Overview

Network slicing is a key feature of 5G technology that allows the creation of multiple virtual networks on a shared infrastructure. This project focuses on implementing dynamic slicing to enhance Wi-Fi network performance by allocating resources efficiently based on demand and priority.

## Project Structure
```bash
Dynamic-Network-Slicing/
├── main.py        # Main script to run the project
├── Graph.py       # Handles visualization and graphing
└── ...            # Other project modules
│
├── example-input.yml  # Example configuration file
├── requirements.txt   # Dependencies required for the project
├── README.md          # Project documentation (this file)
```


## Objectives

- Analyze dynamic slicing in 5G networks.
- Optimize resource utilization for Wi-Fi networks.
- Improve overall network performance using open-source tools.

## Features

- Simulation of network slicing in 5G for Wi-Fi networks.
- Dynamic allocation of resources based on real-time inputs.
- Visual representation of network performance metrics.

---

## Technologies Used

- **Python**: Core language for scripting and simulation.
- **Matplotlib**: Visualization of performance metrics.
- **PyYAML**: Configuration management.
- **Open-source tools**: Built using free and open-source resources.

---

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Sachin63Kumar/Dynamic-Network-Slicing.git
    cd Dynamic-Network-Slicing
    ```

2. Install the necessary dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the main simulation script:

    ```bash
    cd ..
    python -m Dynamic-Network-Slicing.main example-input.yml
    ```

---

## Usage
1. Prepare your configuration file (e.g., example-input.yml) with the required parameters.

2. Run the simulation:
```bash
python -m Dynamic-Network-Slicing.main example-input.yml
```
3. View the generated visualizations for analysis.

