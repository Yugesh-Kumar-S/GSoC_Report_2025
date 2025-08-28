# Phase 2

In the second phase of the project, I focused on implementing **CSV data handling functionalities**, **external sensor integrations**, and a **reusable experiment framework** to expand the scope of the PSLab Flutter app.

---

## CSV features

To improve data logging, I implemented a complete CSV workflow:

- **Export**  
  Users can export recorded sensor readings into CSV files with timestamps and custom file names.  

- **Import**  
  Previously recorded sessions can be re-imported into the app for review and visualization.  

- **Visualization**  
  Both live and imported data can be visualized using **interactive charts**, enabling pattern recognition and insights.  

- **Sharing**  
  CSV files can be shared externally, making it easier for users to collaborate or analyze data in other scientific tools.  


---

## Sensor Integration

In addition to mobile built‑in sensors, I integrated the following **external sensors** into the PSLab Flutter app:

- **BMP180** – Atmospheric pressure & temperature measurements  
- **APDS9960** – Ambient light, proximity, and gesture detection  
- **ADS1115** – High-resolution analog-to-digital converter  
- **VL53L0X** – Time-of-flight sensor for accurate distance measurement  


| <img width="250" alt="BMP180" src="/images/bmp180.png" /> | <img width="250" alt="APDS9960" src="/images/apds9960.png" /> | <img width="250" alt="VL53L0X" src="/images/vl53l0x.png" /> |
| --- | --- | --- |
| | <img width="250" alt="ADS1115" src="/images/ads1115.png" /> | |

---

## Experiment Framework

To standardize experiment workflows, I implemented a **reusable experiment framework** that includes:

- A guided, step-by-step flow that presents clear instructions, visuals, and progress inside the instrument screen, helping users complete experiments from start to finish.
- A floating, movable on-screen guide shows the current step, overall progress, and completion feedback, with an option to end the experiment at any time and trigger follow-up actions afterward.  

This framework makes it easier to add new experiments in the future with minimal effort.  

---

## Experiments Implemented

Using the framework, I successfully built the following experiments:

- **Light Intensity vs Distance Experiment**  
  Demonstrates the inverse-square law of light using Lux Meter.  

- **Barometer Experiment**  
  Tracks atmospheric pressure variations with altitude using in-built sensors or the BMP180 module.  

[Experiment demo](images/experiment.mp4)
