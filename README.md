<div align="center">

# ⚡ JV-MSA: Modular Stator Alternator ⚙️

**Honors Calculus Capstone Project**
*A fully 3D-printed, modular permanent magnet alternator designed to physicalize Faraday's Law, test electromagnetic induction, and generate electricity.*

![Project Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![Build](https://img.shields.io/badge/Build-3D_Printed-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-Custom_Copyright-orange?style=for-the-badge)

</div>

<br/>

## 📌 Abstract
> This study investigates the mathematical and physical relationship between coil density and induced electromotive force (EMF) using a custom-designed, 3D-printed permanent magnet alternator (the JV-MSA). Grounded in Faraday’s Law of Induction, the experiment aims to isolate the rate of change (dV/dN) by maintaining a constant angular velocity (50.27 rad/s) and a constant magnetic field (0.1317 T).
>
> Experimental data yielded a highly linear relationship (R^2 = 0.9951) with a constant induced EMF of 5.5 mV per coil turn. By setting the algebraic slope of the experimental data equal to the calculus-derived derivation of Faraday's Law, the effective cross-sectional area of the complex 3D-printed coils was successfully reverse-engineered (A_eff = 1,174 mm^2). The physical generator operated with an average error margin of 6.30% compared to the frictionless theoretical model, successfully proving that additive manufacturing can reliably replicate advanced calculus models while highlighting the real-world constraints of magnetic flux leakage and internal wire resistance.

*🎥 **Note:** A full physical build and demonstration video will be uploaded at a later date.*

---

## 🛠️ Hardware & Fabrication
I built this generator using 3D printing to show that you don't need an expensive industrial lab to test power systems—you can do high-level engineering with basic tools and some copper wire.

* **CAD Software:** Fusion 360 
* **Materials:** PLA and PETG Filaments
* **Conductor:** 26 AWG Copper Wire
* **Testing Instrumentation:** Fluke 87V Multimeter
* **Mechanics:** Custom 16:1 step-up gear ratio to maintain a constant angular velocity.

---

## 📐 Mathematical Model & Performance
The primary objective of the JV-MSA was to test the physical output against the theoretical calculus model for electromagnetic induction.

* **Target Equation:** Faraday's Law of Induction
* **Measured Variance:** The physical prototype achieved an average **6.30% error margin** when compared to the theoretical mathematical models, tightening to a **1.82% error margin** at 200 turns.
* **Derived Constants:** Experimental testing established a constant output of **5.5 mV per turn**, which was used to successfully reverse-engineer the coil's Effective Area (**1,174 mm^2**).

---

## 🚀 Future Development
The current iteration of the JV-MSA successfully generates measurable Alternating Current (AC). Future plans for this project include designing and integrating a custom Printed Circuit Board (PCB) equipped with a full-bridge rectifier to convert the AC output into stable Direct Current (DC). This will allow the generator to act as a functional, modular power supply for miscellaneous micro-electronics and future engineering projects.

---

## 📂 Repository Contents
This repository is organized into two primary directories:

* `📁 Cad_Files/` — Contains the raw STL files for 3D printing the stator, gears, and housing.
* `📁 Documents/` — Contains the full Honors Calculus Capstone Technical Report (PDF), data logs, and demonstration videos.

---

## ⚖️ License & Usage Rights
**© 2026 Jamal Victor Elbyad. All Rights Reserved.**

I’m sharing my capstone files because I want to be open about my process and show exactly how I built this. I hope other students or engineers find this helpful for whatever projects they are working on. By using this repository, you agree to these terms:

* **Modifications Allowed:** You are welcome to modify, remix, and improve the CAD files for personal or educational use.
* **GitHub Only:** You may share your modifications by "forking" this repository directly on GitHub.
* **No Re-uploading:** You may **NOT** re-upload these files, or any modified versions of them, to other websites, platforms, or 3D-printing repositories (e.g., Thingiverse, Printables, MakerWorld). 
* **Attribution:** Any forks or sharing within GitHub must clearly credit the original creator: Jamal Victor Elbyad.

*(The creator retains all exclusive rights to distribute this project on other platforms).*
