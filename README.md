# ANSYS Fluent Portfolio

This repository compiles selected **ANSYS Fluent** projects on Numerical Thermo-Fluid Mechanics. All project PDFs are located in the [`Cases/`](./Cases) folder.

> **What you’ll find**
> - End‑to‑end Fluent workflows: **geometry → meshing → physics & numerics → convergence → post‑processing**
> - Cases across **laminar & turbulent**, **steady & transient**, with **Energy** equation and **UDF** inlets
> - Clear **figures & metrics**: Cp/Cf, XY profiles, streamlines, velocity/temperature fields, TKE/ε

---

## 📂 Fluent Projects (PDFs)

| # | Project | Physics / Models | What I Did | PDF |
|---|---|---|---|---|
| 1 | **Natural Convection in an Equilateral Triangle** | Laminar • Gravity + **Energy** • Ra = 1e4, 1e5 | Built triangular geometry; created ~1k and ~8k‑cell meshes; steady‑state where possible; compared residuals/contours and Ra/mesh sensitivity | [`Natural_Convection.pdf`](./Cases/Natural_Convection.pdf) |
| 2 | **Backward‑Facing Step (Laminar)** | Steady • Re = 50, 100 • **UDF** parabolic inlet | Structured mesh & named selections; SIMPLE; XY velocity profiles at multiple stations; separation/reattachment trends | [`Backward-Facing_Step.pdf`](./Cases/Backward-Facing_Step.pdf) |
| 3 | **Cylinder Wake (Transient)** | Unsteady • Re = 20, 80 • 2nd‑order **implicit** | BL‑refined tri mesh; Δt = 0.01; residuals + time‑stamped u/v/contours; lift/drag evolution | [`Cylinder_Wake.pdf`](./Cases/Cylinder_Wake.pdf) |
| 4 | **Backward‑Facing Step (Turbulent)** | **k‑ε** turbulence • Re ≈ 1×10⁴ | Residual target 1e‑6; monitored **Cp** & **Cf**; produced Cp(x), Cf(x), streamlines, turbulence fields | [`Backward-Facing_Step_Turbulent.pdf`](./Cases/Backward-Facing_Step_Turbulent.pdf) |
| 5 | **Hot–Cold Water Mixing** | **Energy + k‑ε** | 2D junction geometry; face sizing ~5 mm; streamlines; **TKE/ε**; temperature & velocity contours | [`Water_Mixing.pdf`](./Cases/Water_Mixing.pdf) |

---
