<div align="center">

<img src="https://raw.githubusercontent.com/YOUR-USERNAME/TRSYP-RERO-ENICarthage/main/docs/assets/trsyp_banner.png" alt="IEEE TRSYP 2025" width="100%"/>

# TRSYP-RERO-ENICarthage

[![Docs](https://github.com/YOUR-USERNAME/TRSYP-RERO-ENICarthage/actions/workflows/docs.yml/badge.svg)](https://github.com/YOUR-USERNAME/TRSYP-RERO-ENICarthage/actions)  
[![MkDocs](https://img.shields.io/badge/Documentation-MkDocs-4B8BBE?logo=mkdocs)](https://YOUR-USERNAME.github.io/TRSYP-RERO-ENICarthage/)  
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python)](requirements.txt)  
[![YOLOv8](https://img.shields.io/badge/YOLO-v8-00D4AA?logo=ultralytics)](src/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**IEEE Tunisian RAS Student and Young Professional (TRSYP) – 2nd Edition**  
**Theme**: *AutoEmbodAI* – Smart Autonomous Vehicle Challenge (ADAS Level 3+)

</div>

---

## Overview

A **fully autonomous miniature vehicle** that demonstrates **next-generation ADAS** with:

- **Autonomous Navigation** using onboard vision  
- **AI-Powered Risk Prediction** via real-time object & sign detection  
- **Emergency Response System** for immediate threat mitigation  
- **Sensor Health Diagnostics** with onboard display alerts  

**Compliant with IEEE TRSYP 2025 Specification Book**

---

## Quick Start (Simulation Demo)

```bash
git clone https://github.com/YOUR-USERNAME/TRSYP-RERO-ENICarthage.git
cd TRSYP-RERO-ENICarthage
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt

# Run full ADAS pipeline
python src/main.py --input data/test_drive.mp4 --output result.mp4

Demo Output: Lane following, object detection, risk alerts, emergency stop simulation


Repository Structure
textTRSYP-RERO-ENICarthage/
│
├── src/                  # Full codebase (AI, navigation, diagnostics)
├── models/               # YOLOv8 weights (.pt)
├── cad/schematics/       # KiCad project files
├── docs/                 # Full documentation (MkDocs)
├── data/                 # Test videos & images
├── .github/workflows/    # CI/CD for docs
├── requirements.txt
├── mkdocs.yml
└── README.md

Deliverables (Per Specification Book)






























RequiredStatusLocationCodebase with full documentationDonesrc/ + Live DocsSchematics/CAD (if applicable)Readycad/schematics/ (upload .kicad_*)Clear READMEDoneThis fileTechnical Report (PDF)Uploaddocs/technical_report.pdf

Key Functionalities (Level 3+ ADAS)

























FeatureImplementationAutonomous NavigationOpenCV Canny + Hough Transform → lane centeringAI Risk PredictionYOLOv8 detects STOP, SPEED, pedestrians, vehiclesEmergency ResponseImmediate motor halt on high-risk detectionSensor Health DiagnosticsReal-time anomaly check → OLED alert display

Hardware (Compliant)





























ComponentSpecificationSBCRaspberry Pi 4CameraPi Camera v2 (1080p)UltrasonicHC-SR04 ×2 (obstacle avoidance)Motor DriverL298N (PWM control)Display0.96" OLED (I2C) – diagnostics & alerts

Schematics: cad/schematics/autonomous_vehicle.kicad_pro


Evaluation Criteria Mapping (100 pts)

































Criteria (20 pts each)How We ScoreTechnical InnovationYOLOv8 + OpenCV fusion, real-time diagnosticsPrototype Functionality & NavigationFull lane following + obstacle avoidanceAI-Based Risk PredictionDynamic object & sign detection with confidenceSensor Health DiagnosticsAnomaly detection + OLED feedbackFinal Presentation & DocumentationLive MkDocs site + PDF reportSystem OptimizationLightweight models, efficient pipeline

Documentation
Live Site: https://YOUR-USERNAME.github.io/TRSYP-RERO-ENICarthage/
Built with MkDocs + Material Theme – auto-deployed via GitHub Actions
