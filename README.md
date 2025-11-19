# ACR Car Setup Pro - Performance Tuned

**Your Virtual Race Engineer for Assetto Corsa Rally.**

*![ACR Car Setup Pro - Performance Tuned](https://github.com/user-attachments/assets/aff9f788-ec5e-4a0c-a49e-ac4e7f49163a)*

## 🏁 Overview

**ACR Performance Tuning** is a standalone utility designed to generate professional, competition-ready baseline setups for rally cars in *Assetto Corsa*.

Unlike standard calculators that provide generic values, this tool acts as a race engineer. It uses a database derived from **real telemetry data** and **Assetto Corsa physics engines** (using correct units like N/m, N, and Ramp Angles). The algorithms have been "Performance Tuned" to eliminate understeer and maximize traction for specific car classes and surfaces.

## ⚙️ Key Features

* **Physics-Based Calculation:** Generates values using the specific physics units required by Assetto Corsa (Springs in N/m, Dampers in N/m/s, Diffs in Ramp Angles/Nm).
* **Class-Specific Engineering:**
    * **R5 / Rally2:** High traction, compliant suspension.
    * **WRC (2017+):** Aero-dependent, stiff platform.
    * **Group A (4WD):** Optimized to reduce native understeer.
    * **FWD (Kit Car):** Aggressive rear rotation (lift-off oversteer).
    * **RWD (Historic):** Progressive setups for controlled sliding.
* **Dynamic Modifiers:** Calculations adjust automatically for:
    * **Surface:** Asphalt, Gravel, Snow.
    * **Track Condition:** Smooth, Bumpy, Loose, Mixed, Ice.
    * **Weather:** Dry, Damp, Wet/Heavy Rain (Anti-Aquaplaning logic).
* **Save & Load System:** Save your full setup configuration (dropdowns + results) to `.json` files to build your own setup library.
* **Integrated Tuning Guide:** A built-in "Problem/Solution" tab to help you fine-tune the car based on driving feedback.

## 🚀 Installation & Usage

This application is released as a standalone **portable executable**. No installation is required.

1.  **Download:** Go to the **[Releases](../../releases)** page and download the latest `.zip` archive.
2.  **Extract:** Right-click the downloaded file and select **"Extract All"**. *Do not run the file directly from inside the zip.*
3.  **Run:** Open the extracted folder and double-click **`ACR Performance Tuning.exe`**.

> **⚠️ Note on Windows Defender/SmartScreen:**
> Because this tool is a custom application created by an independent developer (unsigned), Windows might flag it as unrecognized. This is a common "false positive" for community tools. You can safely click **"More Info" -> "Run Anyway"**.

## 🛠️ How to Generate a Setup

1.  **Surface:** Select the primary surface of the rally stage (Asphalt, Gravel, or Snow).
2.  **Car Class:** Select the category that matches your vehicle (e.g., *Group A (4WD)*).
3.  **Track Condition:** Define the roughness of the stage (e.g., *Bumpy / Damaged*).
4.  **Weather:** Select the weather conditions to apply safety margins or grip adjustments.
5.  Click **GET PROFESSIONAL BASELINE SETUP**.
6.  Input the resulting values into your Assetto Corsa setup menu.

## 💾 Saving Your Data

* Navigate to the **Save / Load & Notes** tab.
* Click **Save Current Setup** to store your current configuration and results as a `.json` file.
* You can also keep personal driving notes in the text area and save them separately as `.rtf` files.

## 🤝 Credits & Contact

* **Developer:** [ilborga70](https://github.com/ilborga70)
* **Website:** [scl-tools.blogspot.com](https://scl-tools.blogspot.com/)
* **Pro Sim FOV Utility:** [Check it out here](https://github.com/ilborga70/Pro-Sim-FOV-Utility)

---

*This tool is unofficial and is not affiliated with Kunos Simulazioni.*
