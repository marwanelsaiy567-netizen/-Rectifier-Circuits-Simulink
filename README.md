# Power Electronics Circuits Simulation using MATLAB/Simulink

A comprehensive collection of **single-phase** and **three-phase** power electronics simulations developed using **MATLAB/Simulink**.

This repository includes simulations of uncontrolled rectifiers, controlled rectifiers, semi-converters, full converters, and dual converters with different RL load conditions. The models were developed and tested as part of the **Power Electronics Laboratory** course.

---

##  Author

**Marwan Mostafa Ahmed Elsaey**  
Faculty of Engineering – Zagazig University  
Department of smart grid power Engineering

---

##  Software Requirements

- MATLAB R2022b 
- Simulink
- Simscape Electrical / Simscape Power Systems

---

##  Repository Structure

```
Rectifier-Circuits-Simulink/
├── models/
│   ├── Single-phase models (.slx)
│   └── Three-phase models (.slx)
├── report/
│   └── PE_lab_simulations_graphs.pdf
├── README.md
```

---

##  How to Run

1. Open MATLAB.
2. Navigate to the `models/` folder.
3. Open the required `.slx` model.
4. Click **Run** (or press **Ctrl + T**).
5. Open the **Scope** blocks to observe voltage and current waveforms.
6. Compare the obtained results with the report available in the `report/` folder.

---

##  List of Experiments

| Experiment | Load / Operating Mode |
|------------|-----------------------|
| Single-phase Half-wave Diode Rectifier | RL load (Low L – Discontinuous Current) |
| Single-phase Half-wave Diode Rectifier | RL load (High L – Continuous Current) |
| Single-phase Half-wave Diode Rectifier + Freewheeling Diode | RL load (Low L) |
| Single-phase Half-wave Diode Rectifier + Freewheeling Diode | RL load (High L) |
| Single-phase Full-wave Bridge Rectifier | RL load (Low L) |
| Single-phase Full-wave Bridge Rectifier | RL load (High L) |
| Single-phase Full-wave Center-Tapped Rectifier | RL load (Low L) |
| Single-phase Full-wave Center-Tapped Rectifier | RL load (High L) |
| Single-phase Half-wave Controlled Rectifier | RL load (Low L) |
| Single-phase Half-wave Controlled Rectifier | RL load (High L) |
| Single-phase Half-wave Controlled Rectifier + Freewheeling Diode | RL load (Low L) |
| Single-phase Half-wave Controlled Rectifier + Freewheeling Diode | RL load (High L) |
| Single-phase Semi Converter | RL load (Low L) |
| Single-phase Semi Converter | RL load (High L) |
| Single-phase Full Converter | RL load (Low L) |
| Single-phase Full Converter | RL load (High L) |
| Single-phase Dual Converter | RL load (High L – Four Quadrant Operation) |
| Three-phase Half-wave Diode Rectifier | RL load (Low L) |
| Three-phase Half-wave Diode Rectifier | RL load (High L) |
| Three-phase Full-wave Diode Rectifier | RL load (Low L) |
| Three-phase Full-wave Diode Rectifier | RL load (High L) |
| Three-phase Half-wave Controlled Rectifier | RL load (Low L) |
| Three-phase Half-wave Controlled Rectifier | RL load (High L) |
| Three-phase Semi Converter | RL load (Low L) |
| Three-phase Semi Converter | RL load (High L) |
| Three-phase Full Converter | RL load (Low L) |
| Three-phase Full Converter | RL load (High L) |

---

##  Simulation Outputs

Each model contains measurement blocks for observing:

- Source Voltage
- Load Voltage
- Load Current
- Supply Current
- Thyristor Voltage
- Output Voltage
- Output Current

The generated waveforms can be viewed directly using Simulink **Scope** blocks.

---

##  Report

The repository includes a complete laboratory report containing:

- Circuit diagrams
- MATLAB/Simulink models
- Simulation parameters
- Output waveforms
- Experimental observations
- Performance comparison between different converter topologies


```

##  Learning Outcomes

This project demonstrates practical implementation and simulation of:

- Uncontrolled Rectifiers
- Controlled Rectifiers
- Freewheeling Diodes
- Single-phase Converters
- Three-phase Converters
- Semi Converters
- Full Converters
- Dual Converters
- Continuous and Discontinuous Conduction Modes
- MATLAB/Simulink Power Electronics Modeling

---

##  License

This project is intended for educational and learning purposes.

Feel free to use the models for study and academic reference while giving appropriate credit.
