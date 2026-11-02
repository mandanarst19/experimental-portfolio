# Experimental Portfolio — Thin Films and Devices for Neuromorphic Hardware

Hands-on fabrication and characterization work by **Mandana Roosta**, carried out during my M.Sc. in Condensed Matter Physics at Shahid Beheshti University (2023–2026), group of Prof. Majid Mohseni.

I performed every process step myself, from deposition and annealing through patterning, contacting and electrical measurement. The NiO fiber-network concept is my own. This work complements my computational research on VO₂ neuristors and physical reservoir computing ([thesis code](https://github.com/mandanarst19/Multi-Task-Learning-on-Phase-Change-Material), [ThermoIsing-Net](https://github.com/mandanarst19/ThermoIsing-Net)).

📄 **Full summary:** [Experimental_Work_Report_Mandana_Roosta.pdf](Experimental_Work_Report_Mandana_Roosta.pdf)

| # | Project | Key result | Report |
|---|---|---|---|
| 1 | VO₂ thin films on sapphire | ~360× insulator–metal transition, T<sub>c</sub> ≈ 68 °C, threshold switching | [PDF](VO2_Thin_Films_Lab_Report.pdf) |
| 2 | NiO electrospun fiber networks *(own concept)* | Fiber morphology controlled by tip–collector distance; hysteretic, rectifying I–V | [PDF](NiO_Electrospun_Fiber_Networks_Lab_Report.pdf) |
| 3 | Cu photolithography (etching and lift-off) | Faithful line transfer; edge-defect analysis | [PDF](Cu_Photolithography_Lab_Report.pdf) |
| 4 | Cu electrodeposition on graphite | Conductive Cu coating; transport-limited growth | [PDF](Cu_Electrodeposition_on_Graphite_Lab_Report.pdf) |
| 5 | WS₂ by precursor-conversion CVD | Two-stage tube-furnace process with Ar/H₂ flow control | [PDF](WS2_CVD_Process_Report.pdf) |

---

## 1. VO₂ thin films for thermal neuristors

Metallic V was RF-sputtered onto c-plane sapphire in pure Ar on a six-target sputter system, then oxidised in a tube furnace. The films show a clear insulator–metal transition: resistance drops ~360× (42 kΩ → 118 Ω), with T<sub>c</sub> ≈ 68 °C on heating and 62 °C on cooling.

<p align="center"><img src="figures/vo2_plasma_RT.jpg" width="720" alt="Ar plasma in the sputter chamber and R–T curve of a VO₂ film"></p>
<p align="center"><em>(a) Ar plasma through the chamber viewport during deposition. (b) Resistance vs temperature of a VO₂ film on sapphire.</em></p>

- **Electrothermal behaviour:** negative-TCR self-heating (50 → 22 Ω at 0.25 W), then current-controlled NDR above ~2.4 V, measured on a Keithley 2400 probe station.
- **Open questions:** R–T and I–V come from different devices; room-temperature resistance varies strongly between devices. Next steps: same-device R–T/I–V, Raman/XRD, lithographic µm gaps with 4-wire contacts.

## 2. NiO electrospun fiber networks for lithography-free memristive junctions

**Idea:** build many-junction memristor arrays without high-resolution lithography by stacking a NiO fiber layer and an insulating PVP fiber layer, so that every crossing acts as one junction.

<p align="center"><img src="figures/nio_fibers_10cm_vs_15cm.jpg" width="720" alt="Electrospun fibers at 10 cm and 15 cm tip–collector distance"></p>
<p align="center"><em>Same voltage (15 kV), different distance (50×): (a) wet, coiled fibers at 10 cm; (b) straight, bead-free fibers at 15 cm.</em></p>

- **Parameter study:** six conditions (10–17 cm, 5–15 kV). With a water-based solution, distance mattered more than field, because flight time must exceed the slow water-evaporation time.
- **Device result:** hysteretic, rectifying I–V at the nA level (~5 nA at +10 V, I₊/I₋ ≈ 3).
- **Honest assessment:** addressable junctions were not yet achieved. The inert-gas anneal carbonized the PVP spacer and the dense mat percolated; Ag migration from the contacts is the most likely origin of the hysteresis. Redesign: co-solvent, aligned collection, air calcination and an oxide spacer.
- **Link to reservoir computing:** random memristive networks are studied as physical reservoirs; nonlinearity, hysteresis and many coupled nodes are the properties a reservoir needs.

## 3–5. Patterning, deposition and thermal processing

<p align="center"><img src="figures/cu_lines_micrograph.jpg" width="360" alt="Etched Cu lines on glass with an edge defect"></p>
<p align="center"><em>Etched Cu lines (light) on glass, with a residual-Cu defect bridging into the gap.</em></p>

- **Cu photolithography:** sputtered Cu on glass, then patterned it by two routes: S1813 positive resist with FeCl₃ wet etching, and AZ nLOF 2020 negative resist with lift-off (hot NaOH, since cross-linked nLOF resists acetone).
- **Cu electrodeposition:** within a postdoc-led device project, prepared a CuSO₄/SDS electrolyte, assembled a two-electrode cell and deposited Cu on graphite.
- **WS₂ precursor-conversion CVD:** dip-coated (NH₄)₂WS₄ on Si/SiO₂ and converted it in a tube furnace (vacuum, Ar purge, Ar/H₂ via mass-flow controllers, two-stage ramp-and-hold). The film phase has not yet been characterized.

## Skills

**Deposition:** RF magnetron sputtering, electrospinning, dip coating, electrodeposition · **Thermal processing:** tube-furnace oxidation, annealing and CVD with mass-flow gas control (Ar, H₂) · **Lithography:** positive/negative UV resists, spin coating, mask alignment, wet etching, lift-off · **Characterization:** I–V and R–T on a probe station (Keithley 2400), optical microscopy, Python data analysis

---

**Contact:** mandanaroosta.academia@gmail.com · [github.com/mandanarst19](https://github.com/mandanarst19)
