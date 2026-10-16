# Boiler Curve Inspector

> Interactive browser-based boiler curve inspector, thermodynamic saddle surface visualization, and EnergyPlus IDF object generator.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen.svg)](https://binghangli-opensource.github.io/BoilerCurveInspector/)

---

## 🌟 Overview

**Boiler Curve Inspector** is a standalone, browser-based thermodynamic performance visualization tool designed for HVAC engineers, building energy modelers, and researchers.

It visualizes how boiler thermal efficiency varies continuously across two critical dimensions:
1. **Water Temperature** (Inlet / Return Water Temperature $T_{in}$)
2. **Part-Load Ratio** (Useful heat output PLR)

---

## 🚀 Live Demo & Offline Usage

* **Offline Single-File**: Download [`index.html`](index.html) to your local machine. Double-click to open in any modern browser (Chrome, Edge, Firefox, Safari) — **no installation, no server, and no Python environment required**.

---

## ✨ Key Features

- **3D WebGL Saddle Surface**: Real-time rendering of thermodynamic efficiency surfaces with interactive orbit, pan, and zoom.
- **2D Real-Time Operating Slices**:
  - *Part-Load Response Curve* at any selected return water temperature.
  - *Water Temperature Response Curve* at any selected firing rate / load fraction.
- **Traceable Data Sources & Presets**:
  - **Illustrative Engineering Estimates**: A coherent progressive series of condensing boiler models (80%, 86%, 90%, 94%, 96%, 98% HHV) seeded by published empirical data.
  - **Published Equipment Benchmarks**: Digitized Lochinvar Crest family performance table (LBL Modelica Buildings), OpenStudio CT3-17 reference fit, NECB 2020/2025 compliance curves, and EnergyPlus baseline datasets.
- **EnergyPlus IDF Generator**:
  - One-click generation and copy/download of valid EnergyPlus objects (`Curve:Biquadratic`, `Curve:Cubic`, and `Boiler:HotWater`).
  - Supports both SI (°C) and IP (°F) engineering units.
- **Modern User Experience**:
  - Full Dark/Light theme switching.
  - Responsive layout with UI font scale stepper.
  - Built-in technical documentation, derivation theory, and third-party notices.

---

## 📜 License & Acknowledgments

- **Application Code**: Licensed under the [MIT License](LICENSE), Copyright (c) 2026 Binghang Li.
- **Upstream Data & Standards**:
  - OpenStudio(R) Standards (NatLabRockies)
  - LBL Modelica Buildings Library (Lawrence Berkeley National Laboratory)
  - EnergyPlus (U.S. Department of Energy / NREL)

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for full upstream attribution and license texts.
