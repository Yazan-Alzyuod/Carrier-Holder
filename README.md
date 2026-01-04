# Carrier-Holder
# Static Structural Analysis of Mechanical Part (Steel 37) 🛡️


## 📌 Project Overview
This project performs a high-fidelity Finite Element Analysis (FEA) on a mechanical component (`exPart2|Cut-Extrude1`) using **Ansys Mechanical**. The primary objective was to validate the structural integrity of the part under specified static loads and ensure compliance with industry safety standards by calculating the **Factor of Safety (FoS)** relative to the material's yield strength.

## ⚙️ Simulation Setup and Methodology

### 1. Geometry and Mesh
* **Component Analyzed:** A custom-designed part (`exPart2|Cut-Extrude1`).
* **Meshing:** The geometry was discretized using an optimized mesh to accurately capture stress concentrations, particularly around geometric features and load application points.

### 2. Material Properties: Steel 37
The component is modeled using **Steel 37**, a common structural steel, with its mechanical properties defined in the Ansys library.
* **Stress Limit Type:** Tensile Yield Per Material
* **Key Property:** Tensile Yield Strength (used as the safety limit).

### 3. Boundary Conditions & Loads
* **Loads:** Static loads (forces and/or pressures) were applied, simulating real-world operational stresses. (Specific load values inferred from the analysis, but the resulting stress is the focus).
* **Constraints:** Defined fixed supports or appropriate displacement constraints to ground the model.

## 📊 Results & Structural Validation

### 🔍 Key Findings
The simulation successfully converged, demonstrating the robust structural design of the component.

1.  **Safety Factor (FoS):**
    * **Minimum Safety Factor:** **9.8291**
    * This high value indicates that the maximum equivalent (von Mises) stress experienced by the component is significantly lower than the yield strength of Steel 37, confirming a high degree of confidence in the design's structural reliability and minimal risk of plastic deformation under the design load.

2.  **Governing Stress:**
    * The safety factor was calculated based on the maximum equivalent (von Mises) stress criterion.


## 🚀 Repository Contents
* `Project.wbpj`: The Ansys Workbench project file.
* `alagah report.pdf`: The detailed simulation report.

---
## 👨‍💻 Author
**Yazan Alzyuod**
* **Mechanical Engineer**
* 📧 [yqlasem@gmail.com](mailto:yqlasem@gmail.com)
* 🔗 [LinkedIn Profile](https://www.linkedin.com/in/yazan-alzyuod)
* 💻 [GitHub Profile](https://github.com/Yazan-Alzyuod)
* 📞 00962775327776
