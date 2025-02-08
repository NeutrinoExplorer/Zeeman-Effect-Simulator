# Zeeman-Effect-Simulator
Simulates the normal Zeeman effect in a Fabry-Perot interferometer with customizable parameters.

# Zeeman Effect Simulator

This simulator models the Zeeman effect in a Fabry-Perot interferometer, allowing to visualize how a magnetic field affects the energy transitions of a selected element.

## Features
- **Element Selection:** You can choose between different elements from a library.
- **Parameter Configuration:** The interface allows to adjust the intensity of the magnetic field, the distance between the mirrors and the focal length.
- **Normal Zeeman Effect:** The code only considers the normal Zeeman effect.
- **Energy Transitions:** Simulates only transitions between adjacent azimuthal quantum numbers.
- **Light Source Database:** A `sources.json` file is included, where you can add or modify light source data for use in the simulator.

## Requirements
To run the simulator, you need to have Python and the following libraries installed:
```bash
pip install numpy matplotlib json

By Morris Eriksson, Pelle Nydahl, Hannes Karlsson, Oscar Wollman
