# Embedded Electronics

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Embedded%20Electronics-blue" />
  <img src="https://img.shields.io/badge/Tool-LTspice-orange" />
  <img src="https://img.shields.io/badge/Tool-PicoScope%202205A-informational" />
  <img src="https://img.shields.io/badge/MCU-ESP32--C6-success" />
  <img src="https://img.shields.io/badge/Platform-Arduino%20Uno-lightgrey" />
</p>

This repository is a **hands-on electronics portfolio** that documents practical work with analog and mixed-signal circuits commonly found in embedded systems.

Each topic includes:
- circuit design and calculations
- LTspice simulations
- breadboard implementation
- oscilloscope / multimeter measurements
- comparison between **theory ↔ simulation ↔ measurement**

---

## Structure

Each folder contains its own `README.md` (technical report) and supporting files:

- `figures/` — schematics, LTspice plots, PicoScope screenshots
- `ltspice/` — `.asc` circuits used for simulation (when applicable)

---

## Topics

- **DC circuits** — resistor networks, dividers, E12 selection, basic measurements  
  → [`Report`](01-dc-circuits/README.md)

- **AC circuits** — capacitors and inductors in AC, frequency response observations, practical measurements  
  → [`Report`](02-ac-circuits/README.md)

- **RC / RL transient response** — time constants, step response, comparison of measured vs simulated waveforms  
  → [`Report`](03-rc-rl-circuits/README.md)

- **Transistors** — BJT operation, NPN/PNP circuits, switching and simple driver stages, measurement vs simulation  
  → [`Report`](04-transistors/README.md)

- **Operational amplifiers** — LM741: slew rate, non-inverting/inverting amps, summing amps, bandwidth; includes signal conditioning for ESP32 ADC range  
  → [`Report`](05-op-amps/README.md)

- **I2C LCD hacking** — I²C bus analysis with oscilloscope, PCF8574 address decoding, reconstructing LCD data/commands (HD44780 over I²C expander)  
  → [`Report`](06-i2c-lcd-hacking/README.md)
  
---

## Tools

- **LTspice** (schematics + simulation)
- **PicoScope 2205A** (measurements / bus captures)
- **Arduino Uno** (I²C source)
- **ESP32-C6** (ADC / embedded interfacing use-case)
- breadboard + basic components (R/C/L, BJTs, LM741, PCF8574 LCD module)
