# Microstrip Patch Antenna Design and Simulation

## Project Overview

This project focuses on the design and simulation of a **rectangular microstrip patch antenna** using **ANSYS HFSS 2024**.

The antenna was designed for operation in the **2.4 GHz frequency range** using an **FR4 substrate**. The final simulation showed resonance at approximately **2.382 GHz**.

The project includes antenna dimension calculations, HFSS modeling, S-parameter analysis, impedance matching analysis using a Smith chart, and radiation-pattern analysis.

---

## Objectives

* Design a rectangular microstrip patch antenna for the 2.4 GHz frequency range.
* Calculate the required patch dimensions.
* Select FR4 as the dielectric substrate.
* Model the antenna using ANSYS HFSS 2024.
* Analyze the antenna's return loss and impedance matching.
* Evaluate VSWR and radiation characteristics.
* Compare theoretical design calculations with simulation results.

---

## Tools Used

* **ANSYS HFSS 2024**
* Electromagnetic simulation
* Microstrip antenna design
* S-parameter analysis
* Smith chart analysis
* Radiation-pattern analysis

---

## Antenna Specifications

| Parameter                        | Value       |
| -------------------------------- | ----------- |
| Target frequency                 | 2.4 GHz     |
| Simulated resonant frequency     | 2.382 GHz   |
| Substrate                        | FR4         |
| Dielectric constant (εᵣ)         | 4.4         |
| Substrate thickness              | 1.6 mm      |
| Patch width                      | 38.02 mm    |
| Effective dielectric constant    | ≈ 4.0       |
| Effective length                 | 31.37 mm    |
| Fringing length extension        | ≈ 0.75 mm   |
| Final calculated physical length | ≈ 29.87 mm  |
| Return loss (S11)                | -20.6675 dB |
| VSWR                             | 1.20        |

The project report also lists the given/model patch dimensions as approximately **29.7 mm × 38 mm**.

---

## Antenna Structure

The HFSS model consists of:

* **Radiating Patch** – rectangular copper patch used for radiation.
* **Feedline** – used to excite the patch.
* **Ground Plane** – conductive layer below the substrate.
* **FR4 Substrate** – dielectric material with εᵣ = 4.4.
* **Radiation Box** – simulation region representing the surrounding open space.

---

## Design Methodology

### 1. Frequency Selection

The antenna was designed for the **2.4 GHz range**, with the simulation producing resonance at approximately **2.382 GHz**.

### 2. Substrate Selection

FR4 was selected with:

* Dielectric constant: **4.4**
* Thickness: **1.6 mm**

### 3. Antenna Calculations

Standard microstrip patch antenna calculations were used to determine the antenna dimensions.

The calculated effective dielectric constant was approximately **4.0**.

The effective length was calculated as **31.37 mm**, and after considering the fringing-field effect, the final calculated physical length was approximately **29.87 mm**.

### 4. HFSS Simulation

The antenna structure was modeled in **ANSYS HFSS 2024** and simulated to analyze its electromagnetic characteristics.

---

## Simulation Results

### Return Loss

The simulated S-parameter plot shows a resonance at approximately **2.382 GHz**.

The minimum return loss obtained was:

**S11 = -20.6675 dB**

This indicates good impedance matching and low reflected power at the resonant frequency.

### VSWR

The corresponding VSWR was:

**VSWR = 1.20**

This indicates good impedance matching between the antenna and transmission line.

### Smith Chart

The Smith chart was used to observe the impedance characteristics of the antenna over the frequency sweep.

The trace approaching the center represents good matching toward the **50-ohm reference impedance**.

### Radiation Pattern

The polar plot represents the variation of electric-field strength with direction at approximately **2.4 GHz** and provides the radiation characteristics of the designed antenna.

---

## Key Results

| Parameter           |          Result |
| ------------------- | --------------: |
| Resonant frequency  |   **2.382 GHz** |
| Return loss         | **-20.6675 dB** |
| VSWR                |        **1.20** |
| Substrate           |         **FR4** |
| Dielectric constant |         **4.4** |
| Substrate thickness |      **1.6 mm** |

---

## Applications

The designed microstrip patch antenna can be used for applications such as:

* Wireless LAN (Wi-Fi)
* Bluetooth systems
* Satellite communication
* Radar systems
* 5G and IoT-based devices

These applications are also listed in the project report.

---

## Repository Structure

```text
Antenna-Design-and-Simulation/
│
├── README.md
│
├── results/
│   ├── return-loss-s11.png
│   ├── smith-chart.png
│   └── radiation-pattern.png
│
└── diagrams/
    └── antenna-structure.png
```

---

## Project Team

**Apurva Bagadi**
**Anushka Goswami**
**Nisha Bagal**

**Guide:** Prof. Dr. Shital Pawar
**Vishwakarma Institute of Technology, Pune**

---

## Conclusion

A rectangular microstrip patch antenna was designed and simulated using **ANSYS HFSS 2024** with an FR4 substrate.

The antenna achieved a simulated resonant frequency of **2.382 GHz**, a return loss of **-20.6675 dB**, and a VSWR of **1.20**.

The simulation results demonstrated good impedance matching and stable resonant behavior, showing the effectiveness of HFSS-based electromagnetic simulation for microstrip antenna design.
