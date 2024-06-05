# Vehicle Routing Problem for Container Drayage Operations

This project models a special version of the vehicle routing problem (VRP) focused on container drayage operations. The goal is to match import and export containers while considering constraints such as truck working hours, port time windows, and customer time windows.

## Features

- Mathematical modeling of VRP using Mixed Integer Linear Programming (MILP)
- Simulation and validation using MATLAB
- Integration with Visual Basic for real-time decision-making

## Prerequisites

- MATLAB (with optimization toolbox)
- Visual Basic environment

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/vehicle-routing-problem.git
    ```
2. Navigate to the project directory:
    ```sh
    cd vehicle-routing-problem
    ```

## Usage

### MATLAB

1. Open `vehicle_routing_model.m` in MATLAB.
2. Run the script to see the optimized route and total distance.

### Visual Basic

1. Open `VehicleRouting.vb` in your Visual Basic environment.
2. Run the module to see the optimized route.

## Sample Output

### MATLAB
```matlab
Optimized Route:
     0     1     0     0     0     0     0     0     0     0
     0     0     0     0     1     0     0     0     0     0
     0     0     0     0     0     0     1     0     0     0
     1     0     0     0     0     0     0     0     0     0
     0     0     1     0     0     0     0     0     0     0
     0     1     0     0     0     0     0     0     0     0
     0     0     0     1     0     0     0     0     0     0
     0     0     0     0     0     1     0     0     0     0
     0     0     0     0     0     0     0     1     0     0
     0     0     0     0     0     0     0     0     1     0
Total Distance: 187
```

### Visual Basic
```
Optimized Route:
0 1 2 3 4 5 6 7 8 9
```

## Author

Vahid Keshmiri  
V.Keshmiry@Gmail.com
