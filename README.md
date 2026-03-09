# TASD-Enhanced Q216D Tokamak Simulation v1.0

**Interactive 3D browser-based tokamak plasma simulation** demonstrating ultra-precise energy transition control using the TASD (Toroidal-Attractor Signal Dynamics) framework and the original **Ψ_universe attractor equation**.

The core of the simulation is the Ψ_universe equation, which projects plasma features (temperature 2.0–3.0 keV, density 1–2 × 10¹⁹ m⁻³) into high-dimensional space, applies dissipative oscillatory dynamics with controlled turbulence (Hurst exponent 0.8, variance 0.2), reduces via PCA to 3D, and modulates energy transitions in real time. This achieves exceptionally tight control within **2.10108–2.10288 keV** (span ~0.0018 keV) over simulated runs up to 3 hours.

### ✨ Key Features
- Real-time 3D toroidal plasma visualization (Three.js) with adaptive particle count for smooth 60 fps performance
- Live energy and PCA charts with annotated pellet injection and MGI events
- Full TASD attractor implementation running directly in-browser via Pyodide
- Interactive controls: temperature, density, zoom, speed, 10 representation modes, and field-line animation
- Dynamic performance optimization (frameSkip + variable particle count)
- CSV data export and complete simulation summary
- Zero-install: runs in any modern browser

### 🚀 How to Run
1. Download or clone the repository.
2. Open the file **`index.html`** in any web browser (Chrome, Firefox, Edge, Safari).
3. Click **Start** and interact with the sliders and dropdowns.

No Python, no installation, no server required.

### Patent Pending
This software demonstrates the Q108D-Tokamak-Model with Ψ_universe equation from **US Provisional Patent Application filed January 12, 2026** by Nicolas B. Quiroz, MD.

### License
Apache License 2.0 — see [LICENSE](LICENSE) file.

### Citation
Quiroz, N. B. (2026). TASD-Enhanced Q216D Tokamak Simulation v1.0 [Software]. Zenodo. https://doi.org/10.5281/zenodo.18926912
