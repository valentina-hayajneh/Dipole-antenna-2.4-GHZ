# Dipole Antenna Design and Simulation at 2.4 GHz
<img width="1169" height="736" alt="Screenshot 2025-08-03 155738" src="https://github.com/user-attachments/assets/1631f0bd-feba-4cf2-b15b-e07a772f7f14" />

## Project Overview

This repository presents my personal work on the design, simulation, and analysis of a **half-wave dipole antenna** operating at 2.4 GHz, suitable for wireless applications such as Wi‑Fi and Bluetooth. The model and simulations were performed entirely using **Ansys HFSS 2024 R2**. The project’s objectives include:

- Designing an efficient dipole antenna tuned for 2.4 GHz.
- Evaluating key performance metrics: return loss (S₁₁), radiation pattern, gain, and electric field distribution.
- Demonstrating consistent performance both in the frequency domain and spatial domain.


## Geometrical Parameters

The dipole antenna is composed of two identical metallic cylindrical arms, each approximately 59.44 mm long (about a quarter-wavelength at 2.4 GHz), with a radius of 2.08183 mm. The dipole is centered at coordinates (0, 0, –30 mm), effectively placing the midpoint of the antenna at the origin. The arms extend symmetrically along the Z‑axis. There is no segmentation applied (i.e. one continuous cylinder per arm). This layout ensures the total dipole length is very close to λ/2.


## Design Description

The antenna is a **classic half-wave dipole**, consisting of two identical conductive cylindrical arms separated by a small feed gap. The length of each arm corresponds roughly to one-quarter wavelength at 2.4 GHz, giving a total dipole length close to half the wavelength.

The simplicity of the dipole design makes it an ideal benchmark antenna with:
- **Omnidirectional radiation** in the azimuthal plane.
- Predictable and stable gain characteristics.
- Good impedance matching when properly designed and fed.

The dipole is oriented along the **Y-axis** in the simulation environment, which aligns with conventional practice for analyzing radiation characteristics.



## Importance of Each Simulation Result

### 1️ Dipole Antenna Geometry (3D Model)  
- Visualizes the antenna’s physical structure and dimensions.  
- Ensures geometry matches design specifications, impacting resonance and radiation.

### 2️ Radiation Pattern Visualization (3D)  
- Shows how the antenna radiates energy spatially.  
- Confirms the classic toroidal radiation shape with nulls along the dipole axis.

### 3️ S-Parameter (Return Loss) Plot  
- Indicates antenna impedance matching efficiency.  
- A deep return loss dip (~ –14.7 dB) at 2.0 GHz confirms minimal power reflection.  

### 4️ Gain Polar Plot vs Phi  
- Displays antenna gain stability across azimuth angles.  
- Confirms nearly omnidirectional radiation in the horizontal plane.

### 5️ 3D Gain Plot (Gain Distribution)  
- Spatially visualizes antenna gain and main radiation lobes.  
- Helps identify the strongest radiation directions.

### 6️ Electric Field Distribution Plot (rE Components)  
- Shows the distribution and magnitude of electric field components.  
- Dominant components reveal antenna polarization characteristics.

### 7️ Gain Plot 4 (Polar Gain at Theta=90°)  
- Detailed gain variation at a fixed elevation angle.  
- Validates consistent gain performance around 2.4 GHz.

---

Thank you for reviewing my work. Feel free to reach out if you'd like more information or contextual details.
