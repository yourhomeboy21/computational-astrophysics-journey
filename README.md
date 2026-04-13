# Computational Astrophysics Journey 🚀

[![Open In Colab](https://colab.research.google.com/drive/1pTyPV0pgcyXKlXuMSvOg_IX_yTyewrxp?usp=sharing)](https://google.com)

I am a bscit student documenting my transition into computational astrophysics through numerical simulations. My goal is to build a foundation in high-performance computing and celestial mechanics.

---

## Project 1: Planetary Orbit Simulator
This project uses the **Euler-Cromer numerical integration method** to simulate stable planetary orbits. Instead of using pre-calculated paths, the satellite's position is updated step-by-step using Newton's Universal Law of Gravitation.

### 📊 Simulation Result: Mars Orbit
Below is a high-resolution simulation of a satellite at a 500km altitude around Mars. The code automatically calculates the required circular velocity (~2989 m/s) to maintain a stable trajectory.

![Mars Orbit Simulation](Mars_Scientific_Orbit.png)

### 🛠️ Technical Implementation
- **Language:** Python 3
- **Numerical Method:** Euler-Cromer Integration ($dt = 10s$)
- **Key Libraries:** NumPy (Vector Math), Matplotlib (Scientific Visualization)
-
