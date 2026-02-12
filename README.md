# Gaussian-Pulse-Propagation
# Broadening of Gaussian Pulses

## Objective
Compare the results predicted by the linear system model of an optical fiber with the results of simulation.

## Theory
An optical fiber can be represented approximately by a linear system with an impulse response \(h(t)\) or a transfer function \(H(j\omega)\).  

If the optical source has a spectral width much greater than the signal bandwidth (e.g., the source is a directly modulated laser diode) and the operating wavelength is far from the zero-dispersion wavelength, then \(H(j\omega)\) is approximately Gaussian:

<img width="1482" height="1120" alt="image" src="https://github.com/user-attachments/assets/83f63473-b1b3-4afc-ad17-9e9850041cae" />

### Output Pulse Broadening
If a Gaussian pulse is input to a linear system with a Gaussian impulse response, the output is also Gaussian with RMS width:

<img width="340" height="102" alt="image" src="https://github.com/user-attachments/assets/c60d35c1-8a0f-4c50-873d-1314ec59a29f" />

## Calculations
**System Parameters:**

| Component | Parameter | Value |
|-----------|-----------|-------|
| Transmitter – Gaussian Pulse Generator | Operating wavelength | 1550 nm |
| | Bit rate | 2.5 Gb/s |
| | FWHM pulse width | 0.5 bit period |
| | Chirp factor | -6 |
| Fiber | Type | Corning SMF-28 |
| | Length | 50 km |

**Required Calculations:**
- RMS width of transmitted pulse (\(T_{in}\))  
- RMS spectral width of transmitted pulse (\(\Delta \lambda\))  
- RMS width of fiber impulse response (\(T_F\))  
- RMS width of pulse at fiber far end (\(T_{out}\))  

## Layout
Place and connect the following components:
1. **User-defined bit sequence generator** – set to generate a single pulse of the specified width  
2. **Optical Gaussian pulse generator** – enter the chirp factor as a negative number  

## Simulation
- Set the parameters and run the simulation.  
- Use the visualizer displays to measure:  
  - FWHM width of input and output pulses  
 
## Analysis
Compare the simulation results with the theoretical calculations and discuss any observed differences.

 Results to Record
<img width="1448" height="1015" alt="Screenshot 2026-02-05 113211" src="https://github.com/user-attachments/assets/5a7b450e-e6d6-4efc-8c33-791775fdfa8c" />
## TABULATION
![WhatsApp Image 2026-02-12 at 7 02 17 PM](https://github.com/user-attachments/assets/037236db-ab18-407e-b780-8011a36c6467)


## GRAPH
<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/38e30b01-280e-417e-9666-542113a01f13" />

## RESULT
Hence we successfully obtained  and predicted by the linear system model of an optical fiber with the results of simulation.





