# Multi-Dimensional Generic Simulation Project

## Overview
This project, **MultiDGenericSim**, is a multi-dimensional generic simulation application focusing on object-oriented programming concepts and C++ design. It involves modeling different elements of a system and running simulations on them.

## Features
- Simulates various scenarios based on different parameters.
- Uses an object-oriented approach to manage different entities (e.g., Population, Elements).
- Data parsing from files for initialization.
- Modular code structure with several reusable components.

## Project Structure
The project is organized into multiple files, each serving a specific purpose:

- **main.cpp**: Entry point of the application.
- **Element.h**: Header file containing class definitions for elements used in the simulation.
- **Population.h / Population.cpp**: Represents a population of entities being simulated.
- **Simulation.h / Simulation.cpp**: Contains logic related to running the simulation.
- **FileParse.h / FileParse.cpp**: Handles parsing of input data from files.

## Build Instructions
1. **Prerequisites**:
   - Ensure CMake version 3.19 or later is installed.
   - A C++ compiler supporting C++98.

2. **Building the Project**:
   - Clone the repository: `git clone <repository-url>`
   - Navigate to the project directory: `cd MultiDGenericSim`
   - Create a build directory: `mkdir build && cd build`
   - Run CMake: `cmake ..`
   - Compile the project: `make`

3. **Running the Simulation**:
   - After building, you can run the executable: `./MultiDGenericSim`

## Usage
The simulation can be run using command-line arguments for configuration. The input data for the simulation must be provided in a specific format, and it is parsed by **FileParse**.

## Contributing
Contributions are welcome. Please submit a pull request with clear descriptions of your changes.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For any questions or suggestions, please feel free to contact maylindenberg@gmail.com.
