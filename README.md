### ACR Car Setup Pro - Engineering Edition

# ![ACR Car Setup Pro - Engineering Edition](https://github.com/user-attachments/assets/3eaa6ed7-30d5-459e-8205-25d03bb20eaa)

### 🏎️ Core Physics Engine
- **ACR Data Implementation:** Logic rewritten based on real telemetry extracted from the *Lancia Delta Integrale* setup file.
- **Asymmetric Suspension:** Implemented "Stiff Front / Soft Rear" spring rate logic (e.g., `70kN` front / `50kN` rear) to match specific ACR chassis behavior.
- **Damping Ratios:** Updated Damper logic to reflect the specific ACR standard where *Slow Rebound* is approx. **60% higher** than *Slow Bump*.

### ⚙️ Drivetrain & Braking
- **Differential Ramps:** Replaced generic angles with ACR-specific ramp logic (e.g., `60°` Accel / `75°` Coast) to optimize corner entry.
- **Braking Bias:** Shifted baseline bias forward to `~65%` to match the simulator's braking physics.

### 🔄 System & Scalability
- **Dynamic Weather Scaling:** Replaced static values with mathematical modifiers (e.g., `-50%` ARB stiffness for *Heavy Rain*), ensuring correct wet/snow setups for **all** car classes.
- **Universal Compatibility:** Scaled the *Group A* physics logic to correctly calculate setups for *WRC*, *R5*, and *Historic* classes.

### 🚀 Engineering Edition Updates
- **Complete Rally Class Coverage:** Added support for all major rally categories:
  - Group B (4WD & RWD) - Historic monsters
  - Modern RWD (Rally4) - Precision handling
  - Rally GT (Porsche/Mustang) - Power delivery control
  - Crosskart (AWD) - Unique chassis dynamics
  - Group S (Prototype) - Experimental setups
- **Advanced Weather Conditions:** Expanded to include:
  - Fog/Mist visibility adjustments
  - Cold weather (below 5°C) tire optimization
  - Hot weather (above 25°C) heat management
- **Enhanced Track Conditions:** Added specialized profiles for:
  - Deep Gravel/Ruts management
  - Wet Mud/Clay traction control
  - Ice (Packed Snow) optimization
- **Professional Engineering Profiles:** Each car class now has authentic engineering philosophy:
  - WRC: "Maximum Downforce Platform"
  - Group B RWD: "Power Oversteer Control"
  - FWD KitCar: "Front Traction Priority"
  - Rally GT: "Power Delivery Management"

### 🐛 Bug Fixes
- **Syntax Errors:** Removed invalid `` artifacts that were preventing the script from executing.
- **Calculation Precision:** Improved mathematical accuracy for suspension frequencies and damper ratios.

**Your Virtual Rally Engineering Team for Assetto Corsa.**

## 🏁 Overview

**ACR Car Setup Pro - Engineering Edition** is a professional standalone utility designed to generate authentic, competition-ready baseline setups for rally cars in *Assetto Corsa*.

Unlike standard calculators that provide generic values, this tool acts as a complete race engineering team. It uses a comprehensive database derived from **real telemetry data**, **WRC engineering principles**, and **Assetto Corsa physics engines** (using correct units like N/m, N, and Ramp Angles). The algorithms have been completely rebuilt based on extracted setup data from professional rally configurations.

## ⚙️ Key Features

* **Real Engineering Data:** Calculations based on actual extracted setups from *Lancia Delta Integrale* and professional rally engineering standards.
* **Complete Class Coverage:**
    * **Group A (4WD) - Lancia Delta:** Authentic asymmetric suspension setup
    * **WRC (2017+):** Aero-dependent, stiff platform with active differentials
    * **R5 / Rally2:** Modern balanced performance profiles
    * **Group B (4WD & RWD):** Historic power management setups
    * **Modern RWD (Rally4):** Precision handling for contemporary RWD
    * **FWD (KitCar/Rally4):** Aggressive rear rotation for FWD dynamics
    * **RWD Historic (Escort/BMW):** Mechanical grip optimization
    * **Rally GT (Porsche/Mustang):** Power delivery control for high-torque RWD
    * **Crosskart (AWD):** Unique lightweight chassis dynamics
    * **Group S (Prototype):** Experimental advanced setups

* **Professional Engineering Modifiers:** Advanced calculations adjust for:
    * **Surface Engineering:** Asphalt (stiff), Gravel (compliance), Snow (maximum traction)
    * **Track Conditions:** Bumpy absorption, Loose surface traction, Rut management, Ice optimization
    * **Weather Engineering:** Damp compliance, Wet aquaplaning prevention, Cold/Hot temperature tire optimization

* **Save & Load Engineering Data:** Save complete setup configurations to `.json` files to build your professional setup library.

* **Rally Engineering Guide:** Built-in professional tuning guide with WRC engineering principles and problem/solution workflows.

## 🚀 Installation & Usage

This application is released as a standalone **portable executable**. No installation is required.

1.  **Download:** Go to the **[Releases](../../releases)** page and download the latest `.zip` archive.
2.  **Extract:** Right-click the downloaded file and select **"Extract All"**. *Do not run the file directly from inside the zip.*
3.  **Run:** Open the extracted folder and double-click **`ACR Car Setup Pro - Engineering Edition.exe`**.

> **⚠️ Note on Windows Defender/SmartScreen:**
> Because this tool is a custom application created by an independent developer (unsigned), Windows might flag it as unrecognized. This is a common "false positive" for community tools. You can safely click **"More Info" -> "Run Anyway"**.

## 🛠️ How to Generate a Professional Setup

1.  **Surface:** Select the primary surface of the rally stage (Asphalt, Gravel, or Snow).
2.  **Car Class:** Select the specific vehicle category that matches your car's engineering profile.
3.  **Track Condition:** Define the stage characteristics (Smooth, Bumpy, Loose, Mixed, Ice, Deep Gravel, Wet Mud).
4.  **Weather:** Select weather conditions for precise grip and safety adjustments.
5.  Click **GET ENGINEERING BASELINE SETUP**.
6.  Input the resulting professional values into your Assetto Corsa setup menu.

## 💾 Saving Your Engineering Data

* Navigate to the **Save / Load & Notes** tab.
* Click **Save Current Setup** to store your complete engineering configuration as a `.json` file.
* Maintain detailed engineering notes in the dedicated area and save them as `.rtf` files for professional record-keeping.

## 🎯 Professional Tuning Principles

The Engineering Edition implements authentic rally engineering concepts:

* **Damper Ratios:** Professional 1.6:1 Rebound/Bump ratio standard
* **Spring Frequencies:** Surface-specific frequency tuning (Asphalt: 2.8-3.2Hz, Gravel: 1.8-2.2Hz, Snow: 1.4-1.8Hz)
* **Differential Logic:** Lower ramp angles = More lock (Aggressive), Higher angles = Less lock (Smooth)
* **Weight Transfer Management:** Advanced suspension tuning for optimal tire loading

## 🤝 Credits & Contact

* **Developer:** [ilborga70](https://github.com/ilborga70)
* **Website:** [scl-tools.blogspot.com](https://scl-tools.blogspot.com/)
* **Pro Sim FOV Utility:** [Check it out here](https://github.com/ilborga70/Pro-Sim-FOV-Utility)

**Engineering References:** Toyota Gazoo Racing, Hyundai Motorsport, M-Sport, Citroën Racing

---

*This tool is unofficial and is not affiliated with Kunos Simulazioni. Professional engineering principles applied for authentic rally simulation experience.*
