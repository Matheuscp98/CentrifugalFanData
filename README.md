# 🌀 Tabular Datasets for Analysis of Computational Fluid Dynamics Results from an Industrial Centrifugal Fan

## 📝 Description
This repository contains **tabular datasets** generated from **Computational Fluid Dynamics (CFD)** simulations of an **industrial centrifugal fan for ovens**. 

The data were obtained through a **Design of Experiments (DOE)** using a **Central Composite Design (CCD)** with **4 geometric input factors**.

A total of **504 simulations** were performed in **Ansys** (Workbench, SpaceClaim, Fluent Meshing, Fluent, CFD-Post), producing **35 output variables** including pressures, velocities, turbulence metrics, torque, mass flow rate, blade mass, material cost, and a performance index.  
 
The dataset is intended for **Statistical Analysis, Response Surface Modeling, Sensitivity Studies, Multiobjetive Optimization (MO), and Machine Learning (ML) applications**.  

**Note:** The main focus of this repository is on the **dataset**.

---

## 📚 Publications

This repository is part of the research study:

-  *Manuscript currently under peer review*

---

## 🛠️ How to Use
1. Clone or download this repository.  
2. Open '.csv' files with **Python (pandas)**, **R**, **Microsoft Excel**, **Google Sheets**, or other software .
3. Use [**Fan Abbreviation**](fan_abbreviation.csv) to interpret variable abbreviation.
4. Use [**Fan DOE**](fan_doe.csv) to understand the **Design of Experiments** with Central Composite Design, coded/decoded input variables.  
5. Use [**Fan Responses**](fan_responses.csv) as the **main dataset** with 480 runs, 4 input, and 35 output variables.  

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| [**README**](README.md) | Documentation of the dataset and repository usage. |
| [**Fan DOE**](fan_doe.csv) | Central Composite Design (CCD) with coded and decoded input variables. |
| [**Fan Responses**](fan_responses.csv) | Main dataset with 480 simulations, 4 input variables, and 35 output variables). |
| [**Fan Abbreviation**](fan_abbreviation.csv) | Mapping of abbreviations to full variable names and respective units. |

---

## 📊 Variables
**Inputs (Design of Experiments factors):**
- `NB`: Number of Blades (adm)
- `BEA`: Blade Entry Angle (°)  
- `BOA`: Blade Opening Angle (°)  
- `BL`: Blade Length (mm)  

**Outputs:**
- `BM`: Blade Mass (kg)  
- `MFR`: Mass Flow Rate (kg/s)  
- `T`: Torque (N·m)  
- `PI`: Performance Index (adm)  
- `MC`: Material Cost (USD)  

**Static Pressure:**  
- `SP_min`: Minimum Static Pressure (Pa)
- `SP_mean`: Mean Static Pressure (Pa)
- `SP_max`: Maximum Static Pressure (Pa)

**Dynamic Pressure:**  
- `DP_min`: Minimum Dynamic Pressure (Pa)
- `DP_mean`: Mean Dynamic Pressure (Pa)
- `DP_max`: Maximum Dynamic Pressure (Pa)

**Total Pressure:**  
- `TP_min`: Minimum Total Pressure (Pa)
- `TP_mean`: Mean Total Pressure (Pa)
- `TP_max`: Maximum Total Pressure (Pa)

**Velocity Magnitude:**  
- `VMAG_mean`: Mean Velocity Magnitude (m/s)
- `VMAG_max`: Maximum Velocity Magnitude (m/s)

**Axial Velocity:**  
- `AV_min`: Minimum Axial Velocity (m/s)
- `AV_mean`: Mean Axial Velocity (m/s)
- `AV_max`: Maximum Axial Velocity (m/s)

**Radial Velocity:**  
- `RV_min`: Minimum Radial Velocity (m/s)
- `RV_mean`: Mean Radial Velocity (m/s)
- `RV_max`: Maximum Radial Velocity (m/s)

**Tangential Velocity:**  
- `TV_min`: Minimum Tangential Velocity (m/s)
- `TV_mean`: Mean Tangential Velocity (m/s)
- `TV_max`: Maximum Tangential Velocity (m/s)

**Turbulent Kinetic Energy k:**  
- `k_min`: Minimum Turbulent Kinetic Energy (m²/s²)  

**Turbulent Dissipation Rate ε:**  
- `eps_min`: Minimum ε (m²/s³)
- `eps_mean`: Mean ε (m²/s³)
- `eps_max`: Maximum ε (m²/s³)

**Specific Dissipation Rate ω:**  
- `omega_min`: Minimum ω (1/s)
- `omega_max`: Maximum ω (1/s)

**Turbulent Reynolds Number:**  
- `Re_min`: Minimum Turbulent Reynolds Number (adm)
- `Re_mean`: Mean Turbulent Reynolds Number (adm)

**Large Eddy Simulation Resolution:**  
- `LES_mean`: Mean LES Resolution Estimate (adm)
- `LES_max`: Maximum LES Resolution Estimate (adm)

---

## 📬 Contact

<a href="mailto:matheusc_pereira@hotmail.com">
  <img src="https://i.ibb.co/k6Ddn36k/email.png" alt="E-mail" height="60"/>
</a>
<a href="https://www.linkedin.com/in/matheuscostapereira/">
  <img src="https://i.ibb.co/Kx4rZxdr/linkedin.png" alt="LinkedIn" height="60"/>
</a>
<a href="https://scholar.google.com.br/citations?user=1iDBIzYAAAAJ&hl=en-us">
  <img src="https://i.ibb.co/SwsRKK1t/scholar.png" alt="Google Scholar" height="60"/>
</a>
<a href="https://lattes.cnpq.br/7025666927284220">
  <img src="https://i.ibb.co/1fMjS38j/lattes.png" alt="Lattes" height="60"/>
</a>

---

> _Feel free to open issues or PRs, or reach out for collaboration or questions!_
