# Quick Return Mechanism Analysis

This project analyzes the **Quick Return Mechanism** using both **MATLAB (analytical approach)** and **ADAMS (simulation approach)**. The goal is to evaluate the **angular positions, velocities, accelerations**, and visualize the mechanism’s motion.

## 📌 Project Overview
The **Quick Return Mechanism (QRM)** is widely used in shaping, slotting, and pressing machines, where the **return stroke is faster than the forward stroke**. This improves efficiency in mechanical operations.

### 🔍 Key Objectives:
- Solve the **kinematic equations** of the mechanism analytically in MATLAB.
- Simulate and validate results using **ADAMS software**.
- Compare the **positions, velocities, and accelerations** from both methods.
- Generate an **animation** of the mechanism.

---

## 📂 Project Structure
- `main.m` → MATLAB script for **analytical calculations**.
- `main.mlx` → MATLAB **Live Script** with detailed step-by-step calculations.
- `main.bin` → Binary file (possibly simulation results or compiled data).
- `main.docx` → Project report explaining methodology and results.
- `main.pdf` → **Final project report** including equations, graphs, and analysis.
- `VID1.mp4` → **MATLAB animation** of the mechanism.
- `VID2.mp4` → **ADAMS software simulation** of the mechanism.

---

## 📊 Mathematical Formulation
The **position equations** governing the mechanism are:

\[
O_1O_2 + AO_2 \cdot \sin(\theta_2) = AO_1 \cdot \sin(\theta_1)
\]

\[
AO_2 \cdot \cos(\theta_2) = AO_1 \cdot \cos(\theta_1)
\]

\[
BO_1 \cdot \sin(\theta_1) + BC \cdot \sin(\theta_3) = BO_1y
\]

\[
BO_1 \cdot \cos(\theta_1) + BC \cdot \cos(\theta_3) - BO_1x = 0
\]

where **θ1, θ2, θ3** represent angular positions of different links.

### **Velocity & Acceleration:**
- **Angular velocities:** Derived using time differentiation.
- **Angular accelerations:** Computed by differentiating velocity equations.

---

## 🚀 How to Run
1. Open MATLAB.
2. Run `main.m` to execute the **analytical solution**.
3. View MATLAB’s **computed graphs and animations** (`VID1.mp4`).
4. Compare with **ADAMS simulation results** (`VID2.mp4`).

---

## 🎥 Simulation & Animation
- **MATLAB Animation (`VID1.mp4`)**:
  - Plots **real-time motion** of the mechanism.
  - Uses **link positions and angles** to illustrate the movement.
- **ADAMS Simulation (`VID2.mp4`)**:
  - Models the **same mechanism** using a professional **dynamics simulation tool**.
  - Confirms MATLAB results through **graphical verification**.

---

## 📜 Report Submission Guidelines
- The report (`main.pdf`) must be **typed** and include:
  - **Mathematical derivations**
  - **Graphs & plots**
  - **Comparative analysis between MATLAB & ADAMS**
- All MATLAB scripts must be included.
- **Final submission should be a compressed file (.zip or .rar)** named:

  ```
  StudentName_StudentID.rar
  ```

- **Plagiarism is strictly prohibited**.

---

## 🏗️ Future Improvements
- Extend the model to **include external forces**.
- Implement **higher-order numerical methods** for better accuracy.
- Develop an **interactive GUI for user-defined input parameters**.

---

## 📧 Contact
For any questions, feel free to reach out.

---

📌 **Created for the Dynamics Course, Spring 1403, Mechanical Engineering Department, University of Tehran**