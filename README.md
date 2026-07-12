**Membrane-based integrated photonics.**

**Multi-physics simulation-driven design-to-fab.**

I build active photonic devices on silicon. The materials that modulate and emit light don't grow on it, so I move them onto CMOS-compatible platforms as thin freestanding membranes, then design and fabricate the devices in-house. The most immediate application is optical interconnects, moving data on and between chips, but the same approach extends across active photonics.

What I work on:

- Complex oxides (lithium niobate, barium titanate) for electro-optic modulators
- III-V and III-N for on-chip lasers and resonant-cavity LEDs
- Heterogeneous integration onto CMOS via 2D-material-assisted epitaxy and transfer

From target to measured device, one loop:

- Scope: deep research sets the target and the benchmark to beat
- Design: coupled, cross-validated multi-physics simulation derives the device and its fabrication window, inside the CMOS design rules, with inverse design and AI/ML surrogates
- Build: fabrication realizes that window, with DFT-guided interface engineering and membrane transfer
- Prove: device and optical measurement, read out with coupled-mode theory, close the loop and calibrate the model

Across the design stage: TCAD (devices), DFT (materials), FEM (mechanics), FDTD / RCWA / mode solving / ray optics (photonics).

Each pass de-risks the next fabrication and sharpens the model. Everything is scripted in Python, with the heavy solves in the cloud.
