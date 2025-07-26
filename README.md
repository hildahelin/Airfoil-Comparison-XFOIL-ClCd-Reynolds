# 🛩️ Airfoil Performance Analysis: NACA 2412 vs 0012

This project compares the aerodynamic performance of two widely-used airfoils, **NACA 2412** and **NACA 0012**, under varying Reynolds numbers. Using **XFOIL simulations**, we investigate how **lift-to-drag ratio (Cl/Cd)** evolves with speed, and how stall characteristics differ between the symmetric and cambered airfoils.

---

## 🔍 Objectives

- Analyze Cl and Cd coefficients of NACA 2412 and 0012.
- Investigate stall behavior through Gaussian curve fitting.
- Compare aerodynamic efficiency (Cl/Cd) under Reynolds numbers ranging from 5M to 35M.
- Visualize the performance using Matplotlib graphs.
- Interpret anomalies caused by simulation instabilities.

---

## 📊 Results Preview

- Symmetric airfoil NACA 0012 has **lower maximum lift** but **more stable Cl/Cd** at high speeds.
- Cambered airfoil NACA 2412 shows **sharper stall resistance** but suffers from simulation breakdowns at high Reynolds (25M).
- Graphs include:
  - Cl vs AoA (Stall highlighted)
  - Cd vs AoA (Drag dip marked)
  - Cl/Cd vs Re (Simulation crash & uncertainties visualized)

---

## 🧠 Insights

> "While NACA 0012 offers stability at high speeds and symmetric control for aerobatics, NACA 2412 provides higher lift but is more sensitive to flow separation at extreme Reynolds conditions."

---

## 🛠️ Tools Used

- 🧪 XFOIL (v6.99)
- 📈 Python (Matplotlib, NumPy, Pandas)
- 📁 Raw `.txt` polar data from XFOIL outputs

---

## 📂 Folder Structure
