# Dipole Antenna Design and Simulation at 2.4 GHz

## Project Overview

This project focuses on the design, simulation, and analysis of a **half-wave dipole antenna** operating at 2.4 GHz — a frequency widely used in Wi-Fi, Bluetooth, and other wireless communication applications. The antenna was modeled and analyzed using **Ansys HFSS 2024 R2**, a powerful electromagnetic simulation software.

The main goals of the project are:
- To design an efficient dipole antenna optimized for 2.4 GHz.
- To evaluate key antenna parameters such as return loss, radiation pattern, gain, and electric field distribution.
- To understand the antenna’s performance in both frequency and spatial domains, ensuring reliable wireless communication performance.


## Geometrical Parameters

The dipole antenna is modeled using two metallic cylindrical arms with the following parameters:

| **Parameter**      | **Value**        | **Unit** | **Description**                                |
|-------------------|------------------|----------|------------------------------------------------|
| Center Position    | (0, 0, -60/2)    | mm       | Evaluated as (0 mm, 0 mm, -30 mm)              |
| Axis               | Z                | —        | Dipole arms aligned along Z-axis               |
| Radius             | 2.08183          | mm       | Radius of each dipole arm                      |
| Height             | 59.44            | mm       | Total dipole length ≈ λ/2 at 2.4 GHz           |
| Number of Segments | 0                | —        | Full cylinder without segmentation             |



## Design Description

The antenna is a **classic half-wave dipole**, consisting of two identical conductive cylindrical arms separated by a small feed gap. The length of each arm corresponds roughly to one-quarter wavelength at 2.4 GHz, giving a total dipole length close to half the wavelength.

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
- A deep return loss dip (~ -14.7 dB) at 2.0 GHz confirms minimal power reflection.  

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
- Validates consistent gain performance around 2.4 GHz.



Thank you for reviewing this project!  
Feel free to contact me for further information or collaboration.
