# AuraVisualiser 🌊🎶

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]()
[![Built with: Vanilla JS](https://img.shields.io/badge/Built_with-Vanilla_JS-f7df1e.svg)]()
[![Web Audio API](https://img.shields.io/badge/Web-Audio_API-ff69b4.svg)]()

A lightweight, single-page web application for generating, analyzing, and visualizing diverse audio signals in real-time. Built entirely with Vanilla JavaScript, the HTML5 Canvas API, and the Web Audio API—**zero external dependencies required.**

- Main - https://auravisualiser.pages.dev/
- v1 - https://7c8ba97d.auravisualiser.pages.dev/

## ✨ Features

*   **Integrated Audio Engine:** Generate 6 distinct types of audio scenarios directly within the browser (no external files needed).
*   **Dynamic Visualizer:** High-resolution FFT (Fast Fourier Transform) frequency analysis with smooth motion-trailing effects.
*   **Real-Time Parameter Control:** Every audio scenario features dual real-time dynamic sliders to manipulate frequencies, modulation, or timing on the fly.
*   **Custom Theming:** Full control over the visualizer's aesthetic. Adjust Background, Primary Bar, and Peak highlight colors, alongside the motion-trail fade duration.
*   **Built-in Presets:** Jumpstart your styling with 6 carefully crafted visual themes (e.g., *Cyberpunk City, Synthwave Sunset, Terminal Matrix*).
*   **Zero Setup:** It's a single HTML file. Just download and open.

## 🚀 Getting Started

Because AuraVisualiser is built as a single-page, dependency-free application, installation is instantaneous.

1. Clone the repository or download `index.html`.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Click **"Initialize Audio Engine"** to bypass browser autoplay restrictions and start visualizing!

## 🎛️ Audio Scenarios

AuraVisualiser includes several built-in generators designed to test different aspects of frequency response and visual rendering:

1.  **Sine Sweep (Sonar):** An exponential frequency sweep from 50Hz up to a user-defined maximum. Great for testing full-spectrum rendering.
2.  **Concurrent Harmonics:** Generates a fundamental frequency alongside multiple mathematically related harmonic overtones.
3.  **Dual Detuned (Beating):** Plays two closely matched frequencies to create auditory and visual "beating" (phase cancellation/reinforcement).
4.  **Rhythmic Noise Burst:** White noise pushed through a low-pass filter with an envelope, demonstrating transient visual response.
5.  **FM Synthesis (Bell):** A classic Frequency Modulation setup to create complex sidebands and metallic timbres.
6.  **Sub Bass Pulse:** A low-frequency oscillator mapped to an LFO for pulsing sub-bass testing.

## 🛠️ Technology Stack

*   **HTML5 / CSS3:** Responsive, dark-mode native user interface.
*   **Vanilla JavaScript:** Logic, state management, and UI binding.
*   [**Web Audio API**](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API): Real-time audio synthesis (`OscillatorNode`, `GainNode`, `BiquadFilterNode`) and analysis (`AnalyserNode`).
*   [**Canvas API**](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API): High-performance frame-by-frame visual rendering at 60fps.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
If you want to add a new audio scenario or a cool visual preset, feel free to fork the repository and submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for details.
