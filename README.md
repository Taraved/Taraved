### Svyatoslav Nikulin

2nd-year B.Sc. student in Control Engineering, Ural Federal University, Yekaterinburg.
Interested in feedback control systems: mathematical plant modelling, digital controller design,
and embedded implementation on microcontrollers.

**Projects**

- [**esp32-maglev**](https://github.com/Taraved/esp32-maglev) — magnetic levitation project on ESP32
  for evaluating how much closed-loop control quality a neural controller loses when quantized from
  float32 to int8. Theoretical calculations, RL-actuator pre-analysis plots, closed-loop simulations,
  and hardware schematics completed (physical testbed assembly pending).
- [**mk_emul**](https://github.com/Taraved/mk_emul) — STM32F407 (ARM Cortex-M4) desktop emulator,
  course project at UrFU (merged upstream: [#1](https://github.com/LifeStyle28/mk_emul/pull/1),
  [#2](https://github.com/LifeStyle28/mk_emul/pull/2)). My part: Cortex-M4 CPU core with exact
  interrupt timing and FPU context, timers and PWM, HAL/FreeRTOS builds, source-level debugger
  over GDB, and 127 automated tests.
- [**Q-Control-Optimization**](https://github.com/Taraved/Q-Control-Optimization) — practical
  quantum computing applied to emergency reconfiguration of a power-grid substation: formulated as
  a QUBO problem, programmed on gate-based quantum circuits using the Quantum Approximate
  Optimization Algorithm (QAOA), and benchmarked against the classical optimum.

**Current Research**

- Effect of Quality Factor on RLC Filter Behaviour (UrFU, supervised by Duong Ngoc Anh) —
  co-authored paper in preparation. Modelling low-pass, high-pass, band-pass and band-stop RLC filters
  in  MATLAB/Engee; linking Q to frequency-domain (bandwidth, peaking) and time-domain (overshoot,
  settling time) behaviour, and analysing sensitivity of resonant frequency and Q to inductor losses
  and component tolerances. Early stage.

**Tools:** Python, C/C++, STM32, ESP32, FreeRTOS, Qt, Quantum Computing (QAOA/QUBO), Git, Linux
