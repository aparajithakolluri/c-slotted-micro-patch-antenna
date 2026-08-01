

# 📡 C-Slotted Microstrip Patch Antenna

## Overview

The **C-Slotted Microstrip Patch Antenna** is designed and simulated using **ANSYS HFSS** to enhance antenna bandwidth and impedance matching through the incorporation of C-shaped slots on the radiating patch. The slot structure alters the surface current distribution, enabling improved return loss and multi-resonant characteristics suitable for modern wireless communication applications.

---

## Antenna Design

The antenna consists of a microstrip patch fabricated on an  jean substrate and excited using a microstrip line feed. Multiple C-shaped slots are etched on the radiating patch to improve impedance matching and bandwidth while maintaining a compact design.


## Simulation Results

The antenna was analyzed using **ANSYS HFSS**. The simulated **S11 (Return Loss)** response demonstrates multiple resonant frequencies with good impedance matching over the operating band.

### S11 Parameter Plot

<p align="center">
  <img src="images/s11_plot.png" width="650">
</p>

### Key Performance

| Parameter            | Value                                                                               |
| -------------------- | ----------------------------------------------------------------------------------- |
| Simulation Software  | ANSYS HFSS                                                                          |
| Antenna Type         | C-Slotted Microstrip Patch                                                          |
| Feeding Method       | Microstrip Line Feed                                                                |
| Substrate            | FR-4 Epoxy                                                                          |
| Return Loss          | Better than -10 dB at multiple resonant frequencies                                 |
| Resonant Frequencies | 4.18 GHz, 6.60 GHz, 7.20 GHz, 10.19 GHz, 10.84 GHz, 11.57 GHz, 12.53 GHz, 12.70 GHz |

---

## Features

* Compact microstrip antenna design
* C-shaped slot implementation
* Improved impedance matching
* Multi-band operation
* Enhanced return loss characteristics
* Designed and optimized using ANSYS HFSS

---

## Working Principle

The C-shaped slots increase the effective current path on the patch, resulting in multiple resonant modes. This enhances bandwidth and improves impedance matching by reducing the reflection coefficient (S11). The optimized geometry enables efficient radiation over multiple operating frequencies while maintaining a compact antenna size.

---

## Applications

* Ultra-Wideband (UWB) Communication
* Wireless Communication Systems
* WLAN
* Wi-Fi Applications
* ISM Band Devices
* RF and Microwave Systems
* IoT Applications

---

## Software Used

* ANSYS HFSS
* MATLAB (for calculations, optional)

---

## Future Improvements

* Gain enhancement using parasitic elements
* Bandwidth optimization
* MIMO antenna implementation
* Circular polarization
* Experimental fabrication and measurement

---

