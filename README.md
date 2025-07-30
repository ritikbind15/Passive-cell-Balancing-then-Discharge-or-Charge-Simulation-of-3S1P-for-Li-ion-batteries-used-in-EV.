# Passive-cell-Balancing-then-Discharge or Charge-Simulation-of-3S1P-for-Li-ion-batteries-used-in-EV.
This project presents a MATLAB-based simulation of a passive cell balancing algorithm implemented on a 3S1P Li-ion battery configuration using min SoC discharge logic. The goal is to ensure uniform state-of-charge (SoC) across all cells, enhancing the performance, safety, and lifespan of battery packs used in electric Vehicles. 

🔋 Project Overview

Configuration: 3S1P (3 cells in series, 1 parallel string)

Battery Type: Lithium-ion

Focus:

Passive cell balancing based on minimum or average SOC strategy

Simulation of both charging and discharging cases post-balancing

Tools Used: MATLAB & Simulink

📌 Features

Implements passive balancing via resistor-based energy dissipation.

Supports balancing-before-discharge and balancing-before-charge scenarios.

Models voltage, SOC, and current behavior for each individual cell.

Provides real-time visualization of the balancing and energy flow process.

Analyzes imbalance correction impact on battery safety and efficiency.

⚙️ How It Works

Cell Initialization: Each of the three cells begins with different SOC levels.

Balancing Phase: Passive balancing is initiated to reduce the SOC difference using dissipative resistors.

Charging/Discharging: Once balanced, the pack undergoes a charge or discharge cycle.

Monitoring: Cell voltages, SOCs, balancing currents, and total pack behavior are monitored.

📊 Results & Observations

Passive balancing significantly reduces SOC mismatch.

Improves uniformity in cell behavior during subsequent charging/discharging.

Simulation shows minimized risk of overcharging or over-discharging.

📦 Applications

Battery management system (BMS) algorithm development

EV battery pack simulation and validation

Educational tool for battery balancing techniques

Benchmarking different balancing strategies

🧠 Future Scope

Include active balancing for efficiency comparison

Scale up to higher series/parallel configurations (e.g., 16S1P, 8S2P)

Introduce temperature-dependent behavior and aging models
Implement real-time balancing during charging/discharging

