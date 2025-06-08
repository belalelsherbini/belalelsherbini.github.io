<div style = "display: flex; gap: 10px; justify-content: center;">
  <img src = "/projects/graphicequalizer/ge5.png" width="400" height="250">
  <img src = "/projects/spectrumanalyzer/sa2.png" width="400" height="250">
</div>
<br>

### What I Did
- Designed, programmed, and debugged a **GUI based real time spectrum analyzer** that takes input from an RTL-SDR.
- Implemented user customizability options such as **adjustable center frequency** and **critical frequencies** for optional **filter visualizations.**

### How I Did It
- Acquired and processed signal data in chunks from an RTL-SDR using the pyrtlsdr library, enabling flexible SDR input handling.
- Built a Python GUI with Tkinter, utilizing Numpy for FFT-based spectrum analysis and Matplotlib for real-time signal visualization.
- Designed and implemented optional Butterworth filter visualizations (Low Pass, High Pass, Band Pass) using SciPy for enhanced frequency domain insights.

### Outcomes
- Developed advanced proficiency in Python-based signal processing by integrating RTL-SDR hardware for real-time RF data acquisition and analysis.
- Engineered a robust pipeline to process, filter, and visualize SDR data in the frequency domain, achieving seamless real-time spectrum display and interaction.
- Gained in-depth expertise in Butterworth filter design, implementation, and visualization, enhancing practical DSP skills for RF applications.
