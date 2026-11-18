# Multi-Stage NPN BJT Amplifier Simulation (MATLAB / Simulink)

## Tools
- MATLAB R2024b
- Simscape Electrical (`ee_lib` / `fl_lib`)

## Main Components
- **NPN Transistors:** `Q1`, `Q2` (`NPN Bipolar Transistor`)
- **Bias and Load Resistors:** `R1`, `R2`, `RE`, `Rc`, `RL`, `R_R1`, `R_R2`, `R_RE`
- **Coupling and Bypass Capacitors:** `C1`-`C4`
- **AC Input Source:** `Vin`
- **DC Power Supplies:** `Vcc`, `Vcc2`
- **Voltage Sensors & Scopes:** `IN`, `OUT 1`, `OUT2` (simulation time: `0.01 s`)

## How to Run
1. Open `project_1.slx` in MATLAB R2024b or later.
2. Run the simulation.
3. Observe the signals on `IN`, `OUT 1`, and `OUT2`.
