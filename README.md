# Traffic Light Controller in Verilog using Xilinx

## Overview
This project implements a traffic light controller in Verilog, designed to manage the flow of traffic at two intersections. It uses a state machine to control Red, Yellow, and Green lights for each road based on traffic signals.

## Features
- *State Machine Based Control:* Handles the timing and transitions of traffic lights with different states for each intersection.
- *Support for Two Intersections:* Controls two separate traffic lights, labeled as Light A and Light B.
- *Synchronous Clocking:* Operates using a clock signal to handle state transitions reliably.
- *Configurable Timing:* The design can be modified to adjust the duration of red, yellow, and green lights.
  
## Project Structure
- *src/*: Contains the Verilog source file for the traffic light controller (traffic_light.v).
- *tb/*: Testbench for simulating the traffic light controller's behavior.
- *docs/*: Documentation on the state machine design and simulation results.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/traffic-light-verilog-xilinx.git
   cd traffic-light-verilog-xilinx
2. Open the project in Xilinx Vivado or ISE.
3. Run synthesis and simulation using the provided testbench.
4. Analyze the waveform and check status signals for functionality.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests.
