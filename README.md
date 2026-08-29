# CMOS Inverter Design using Cadence Virtuoso

Design, simulation, and layout of a CMOS inverter implemented in Cadence Virtuoso, with DC and transient analysis across multiple transistor sizing configurations.

## Contents

### 1. Schematic Design
- `1. Inverter Schematic.png` — CMOS inverter schematic (PMOS-NMOS pair)
- `2. Test Schematic.png` — Test bench schematic used for simulation

### 2. Transient Analysis
- `3. Transient Analysis.png` — Transient response showing output switching behavior

### 3. DC Analysis — VTC Curves (Sizing Variations)
- `4. (a) DC Analysis_VTC Curve_Electrically symmetric inverter (Wp=4um; Wn=2um).png` — VTC curve for electrically symmetric sizing
- `4.(b) DC Analysis_VTC Curve_Inverter with stronger PMOS (Wp=8um; Wn=2um).png` — VTC curve with stronger PMOS
- `4.(c) DC Analysis_VTC Curve_Inverter with stronger NMOS (Wp=2um; Wn=2um).png` — VTC curve with stronger NMOS

### 4. NMOS/PMOS Swap Analysis
- `5.(a) Swap NMOS and PMOS Transient Analysis.png` — Transient analysis after swapping NMOS and PMOS positions
- `5.(b)Swap NMOS and PMOS_VTC.png` — VTC curve after swapping NMOS and PMOS positions

### 5. Layout
- `CMOS_inverter_Layout.jpeg` — Physical layout of the CMOS inverter

## Tools Used
- Cadence Virtuoso (Schematic Editor, Layout Editor)
- Cadence Spectre (Simulation)

## Key Observations
- Sizing PMOS and NMOS to balance carrier mobility differences shifts the switching threshold (Vm) of the VTC curve.
- A stronger PMOS shifts the switching threshold higher; a stronger NMOS shifts it lower.
- Swapping NMOS and PMOS positions was used to validate correct inverter operation and observe its effect on the transient and DC response.
