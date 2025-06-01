# 🔊 Ultrasonic Diffraction Pattern Simulator

A Python GUI app that simulates ultrasonic diffraction patterns, calculates key wave properties, and visualizes concentric ring formations for educational physics experiments.

## 🚀 Features

- GUI-based input using Tkinter
- Calculates:
  - Angle of diffraction (θ)
  - Wavelength of ultrasonic wave (λᵤ)
  - Velocity of ultrasonic wave (Vᵤ)
- Real-time visualization of concentric diffraction rings using Matplotlib
- Educationally aligned with ultrasonic diffractometer experiments in physics labs

## 🧪 How It Works

Users input:
- Frequency of ultrasonic wave (Hz)
- Distance from diffractometer to screen (L in cm)
- Distance from central to nth-order diffraction spot (D in cm)
- Diffraction order (n)

The app then:
- Computes the angle of diffraction: `θ = tan⁻¹(D / L)`
- Calculates ultrasonic wavelength: `λᵤ = n * λ / sin(θ)` (with red light λ ≈ 650 nm)
- Computes ultrasonic wave velocity: `Vᵤ = λᵤ * ν`
- Plots concentric diffraction rings based on `n` and `D`

## 🖼️ GUI Preview

TODO

## 📦 Requirements

- Python 3.x
- `tkinter` (usually included by default)
- `matplotlib`
- `numpy`

Install dependencies using pip:
```bash
pip install matplotlib numpy
