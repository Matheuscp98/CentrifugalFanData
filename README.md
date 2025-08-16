# 🌪️ Tabular Datasets for Analysis of CFD Results from an Industrial Centrifugal Fan

## 📝 Description
This repository contains **tabular datasets** from **480 CFD simulations** of an **industrial centrifugal fan** used in oven air recirculation at **5,600 rpm**.  
A **Central Composite Design (CCD)** within a **Design of Experiments (DOE)** framework varied four blade parameters:  
- **NB** (Number of Blades)  
- **BEA** (Blade Entry Angle)  
- **BOA** (Blade Opening Angle)  
- **BL** (Blade Length)  

Simulations were carried out in **Ansys®** (SpaceClaim, Fluent Meshing, Fluent, CFD-Post).  
The dataset provides **35 output variables** (pressures, velocities, turbulence metrics, torque, mass flow rate, material cost, performance index).  
It serves as a **benchmark** for statistical analysis, design optimization, sensitivity studies, and Machine Learning applications.


## 🛠️ How to Use
1. Clone or download this repository.  
2. Open `.csv` files with **Python (pandas)**, **R**, or **Excel**.  Open '.csv' files with **Python (pandas)**, **R**, **Microsoft Excel**, **Google Sheets**, or other software .
3. Use `fan_abbreviation.csv` to interpret variable codes.
4. Use **`fan_doe.csv`** to understand the **Design of Experiments** (Central Composite Design, coded/decoded input variables).  
5. Use **`fan_responses.csv`** as the **main dataset** with 480 runs and all 4 input, and 35 output variables.  

---

## 📚 Publications

This repository is part of the research study:

-  *(The dataset is from this work. Manuscript currently under review)*

---

## 📂 Repository Structure

| File | Description |
|------|-------------|
| [**README.md**](README.md) | Documentation of the dataset and repository usage. |
| [**fan_doe.csv**](fan_doe.csv) | Central Composite Design (CCD) with coded and decoded input variables. |
| [**fan_responses.csv**](fan_responses.csv) | Main dataset with 480 simulations (4 input variables + 35 output variables). |
| [**fan_abbreviation.csv**](fan_abbreviation.csv) | Mapping of abbreviations to full variable names and respective units. |

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

<a href="mailto:matheusc_pereira@hotmail.com"><img src="https://img.shields.io/badge/E--mail-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="E-mail"/></a>
<a href="https://www.linkedin.com/in/matheuscostapereira/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://lattes.cnpq.br/7025666927284220"><img src="https://img.shields.io/badge/Lattes-4169E1?style=for-the-badge&logoColor=white" alt="Lattes"/></a>

---

> _Feel free to open issues or PRs, or reach out for collaboration or questions!_
