# RC_High-Pass-Filter_Simulation-using-LTspice
RC High-Pass Filter simulation project using LTspice. Demonstrates high-frequency signal pass-through and -3dB cutoff response.
This project demonstrates an RC High-Pass Filter simulation using LTspice. The simulation shows how the circuit allows high-frequency signals to pass while attenuating low-frequency components. The expected -3dB cutoff point is clearly visualized in the Bode plot.

## 🔧 Circuit Configuration
- *Resistor (R)*: 1kΩ  
- *Capacitor (C)*: 0.1μF  
- *Voltage Source*: AC 1V  
- *Simulation Command*: .ac dec 100 10 1Meg

## 📈 Output
- Bode plot shows gain and phase shift.
- Cutoff frequency (fc) calculated using:  
  \[ fc = \frac{1}{2πRC} = \frac{1}{2π × 1kΩ × 0.1μF} ≈ 1.59kHz \]

## 📁 Files Included
- RC_HighPass_Filter.asc — LTspice schematic
- Circuit and waveform screenshots

## 🔍 Tools Used
- LTspice (Analog Devices)
- ## Author
- Vishal Singh
- http://linkedin.com/in/vishal-singh-542338161
