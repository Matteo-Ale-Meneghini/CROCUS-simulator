# CROCUS-simulator
Real-time simulator of the CROCUS nuclear reactor at EPFL. It is the work of the semester project conducted by Matteo Meneghini and Caterina Frau in the Spring semester of 2025. The code is based on that of the simulator developed at JSI for their TRIGA reactor.

# Download for Windows
- Download WSL (Ubuntu 22.04)

Open the WSL bash and copy & paste the following commands (for Ubuntu 22.04):
- sudo apt update && sudo apt install git
- git clone --recurse-submodules https://github.com/Matteo-Ale-Meneghini/CROCUS-simulator.git
- cd CROCUS-simulator
- cd build
- cmake ..

Update or install all necessary packages (errors and asking an AI will guide you)
- make
- ./SimulatorGUI

# Download for Linux (Ubuntu 22.04)
Follow the same steps as for Windows, without the need for WSL
