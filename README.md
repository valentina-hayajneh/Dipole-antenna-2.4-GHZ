## Project Overview 

The **half-wave dipole** is one of the simplest and most widely used antennas in wireless communications, valued for both its ease of design and strong performance. This project focuses on designing and simulating a half-wave dipole antenna at 2.4 GHz with specific performance requirements. To validate the results, the simulated design is benchmarked against a commercially available half-wave dipole antenna,URL: https://southwestantennas.com/products/omni-antennas/omni-antenna-22-25-ghz-215-dbi-internal-bandpass-filter
<img width="1407" height="591" alt="image" src="https://github.com/user-attachments/assets/bc469aa2-dc58-466c-a9ae-8d8b6772233b" />

## Geometrical Parameters 

The dipole antenna consists of two cylindrical metallic arms, separated by a 1.2 mm gap. The total length of the dipole (including both arms and the gap) is approximately 54.26 mm, which corresponds to 85% of a half-wavelength at 2.35 GHz (to account for practical effects like end loading and arm thickness). The arms are not equal in length: the upper arm measures approximately 23.68 mm and the lower arm 29.38 mm. The dipole is centered approximately near the origin, with a slight asymmetry due to the unequal arms 
<img width="368" height="571" alt="image" src="https://github.com/user-attachments/assets/6f5b8378-95ef-4ef2-bc49-bf69232863d3" />

## Optimization Process
An optimization process was carried out to determine the best length reduction factor that would yield performance closely matching that of the commercial dipole antenna used as a benchmark. After several simulation iterations and parameter sweeps, the optimal factor was found to be 0.85 of the half-wavelength at the center frequency of 2.35 GHz. This choice led to improved impedance matching and reduced reflection (return loss).
<img width="1030" height="577" alt="image" src="https://github.com/user-attachments/assets/eba0720b-b8ff-4343-b236-2639f505b6e8" />

## Importance of Each Simulation Result

**Return Loss (S11):**  
  Indicates how much power is reflected back from the antenna input. A value below -10 dB typically suggests good matching, and values below -15 dB are excellent.
<img width="892" height="570" alt="image" src="https://github.com/user-attachments/assets/966e43ee-49d2-4bcb-9012-0f9dc72fba55" />

**VSWR (Voltage Standing Wave Ratio):**  

  Describes the efficiency of power transfer from the source to the antenna. A VSWR value of 1.0 is ideal. Values below 2.0 are generally acceptable.
<img width="827" height="555" alt="image" src="https://github.com/user-attachments/assets/e29b4eac-ec9e-4e82-bee4-2d5dbca9620b" />

### Realized Gain

The realized gain represents the antenna gain including losses due to mismatch and efficiency factors, providing a realistic measure of the antenna's ability to direct energy in space. The 3D gain plot below shows a maximum realized gain of approximately **2.15 dBi**, which is consistent with typical half-wave dipole performance.
<img width="752" height="537" alt="image" src="https://github.com/user-attachments/assets/048e7c54-e7ce-42e2-8690-a4014e3726a3" />

## Radiation Pattern Analysis

The radiation characteristics of the designed half-wave dipole antenna were analyzed in detail, including its gain distribution, radiation patterns in azimuth and elevation planes, and polarization behavior.

### Radiation Pattern - Azimuth

The azimuth radiation pattern demonstrates how the antenna radiates power around the horizontal plane. The plot indicates a nearly omnidirectional pattern in the azimuth plane, with uniform gain close to 2 dBi across all angles.
<img width="739" height="581" alt="image" src="https://github.com/user-attachments/assets/9b617e69-ebb2-4f0f-8bba-dbce6b73bbf1" />

### Radiation Pattern - Elevation

The elevation pattern shows the radiation distribution vertically. It clearly exhibits the expected dipole shape with two main lobes and nulls at 0° and 180°, confirming the characteristic figure-eight pattern.
<img width="737" height="542" alt="image" src="https://github.com/user-attachments/assets/e4617f03-f75c-4f0f-88bc-30f636afe80a" />

### Polarization

The polarization plot shows the antenna radiation is **linearly polarized**, as one electric field component dominates strongly over the others. The main component is along the Z-axis (approximately 9.7 V), while other components are negligible (< 0.02 V), confirming **vertical linear polarization** of the antenna.
<img width="1403" height="399" alt="image" src="https://github.com/user-attachments/assets/d0d280d9-3cdb-492d-8a51-acaa7604a728" />






