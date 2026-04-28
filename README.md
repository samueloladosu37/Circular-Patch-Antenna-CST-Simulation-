# Circular-Patch-Antenna-CST-Simulation
Design and simulation of a circular microstrip patch antenna using CST Studio Suite.
The antenna shows a broadside radiation pattern with a maximum directivity of approximately 7.09 dBi at 2.92 GHz. Maximum gain approximately 6.76 dBi for the third mesh. The radiation is predominantly directed along the z-axis, with minimal back radiation. The high radiation efficiency -0.3289dB(93%) indicates low material losses, while the total efficiency result -0.7368 dB (84%) shows minor mismatch losses.

- Resonant frequency: **2.92 GHz**
- Peak gain: **6.76 dBi**
- Directivity: **7.09 dBi**
- Radiation efficiency: **93%**
- Bandwidth: **350 MHz (~12%)**

## Geometry
- Patch radius: 17 mm
- Substrate: εr = 2.62
- Feed: 50 Ω stripline
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/Model.jpg)
---

## Key Results

### Return Loss (S11)
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/S11.jpg)

- Resonance at 2.92 GHz
- S11 ≈ -10.48 dB
- Bandwidth: 2.75 – 3.10 GHz

---

### VSWR
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/VSWR.jpg)

- Minimum VSWR ≈ 1.85
- Good matching near resonance

---

### Radiation Pattern
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/farfield.jpg)

- Broadside radiation (+z direction)
- Low back radiation

---

### Gain & Directivity
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/Max%20Gain%20Vs%20Freq.jpg)

- Peak gain: 6.76 dBi
- Directivity: 7.09 dBi

---

### Surface Current
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/Surface%20I.jpg)

- TM11 mode confirmed
- Strong edge currents

---

### Efficiency
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/Efficiency.jpg)

- Radiation efficiency: 93%
- Total efficiency: 84%

---

## Simulation Setup
- Solver: CST Time Domain (FIT)
- Boundary: Open (add space)
- Mesh: Adaptive (3 passes)
- Convergence: ΔS < 0.005
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/Background%20conditons.jpg)
 ![Preview](https://github.com/samueloladosu37/Circular-Patch-Antenna-CST-Simulation-/blob/main/Background%20conditons.jpg)
  
  
