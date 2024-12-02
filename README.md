<p align="center"><img src="readmeImages/header.png" width="100%"></p>

# TCM Hob Inspector

## Overview

The **TCM Hob Inspector** is an advanced, multifunctional system designed for the automatic inspection of gear hobbing tools. It employs advanced ML technologies to enhance efficiency, precision, and cost-effectiveness in tool maintenance processes.

<p align="center"><img src="readmeImages/hob_system_overview.png" width=75%></p>

### Key Features:

- **Hybrid classic and ML-driven image processing**:
  - Segmentation of tooth rake faces and surface anomalies using ML models.
  - Segmentation of flank wear with classic machine vision methods.
- **Cost optimization module**:
  - Analyses tool state and suggests optimal grinding method to maximize lifecycle profitability.
- **Interactive Dash application**:
  - Enables result visualization, selection of machining parameters, and generation of detailed tool scan reports.
- **SQL database**:
  - Secure storage for scan results and analysis data.

---

## Machine Learning Solutions

- Dual inference using **YOLOv8 instance segmentation model** and classic machine vision methods
- Supervised learning with **custom datasets**
- Annotations with artifacts saved in `.json` format, compatible with **LabelMe software**
- **Semi-automatic dataset creation** system
- Data collection during the production cycle for model development
- Custom Python scripts for training and evaluating ML models

---

## Visualization and Reporting
The project includes a powerful visualization application to analyze and interpret inspection results effectively:

### Examples:

**Hob Wear Map**
<p align="center"><img src="readmeImages/ScanningExample.png" width="75%"></p>

**Automatic Report Generation**
<p align="center"><img src="readmeImages/RaportExample.png"></p>

---

## Video Demonstration

Learn more about the **Hob Inspector** by watching our demonstration video on YouTube.

<p align="center">
  <a href="https://youtu.be/zdKuHlUXVqI" target="_blank">
    <img src="ReadmeImages/youtube-thumbnail.png" alt="TCM Hob Inspector Video" width="50%">
  </a>
</p>

---

<p align="center"><img src="readmeImages/scanner.png"></p>

---

## Collaborators

<div align="center">
  <table style="background-color:white">
    <tr>
      <th><a href="https://pwr.edu.pl/">Wrocław University of Science and Technology</a></th>
      <th><a href="https://mvlab.pl/">Machine Vision Laboratory</a></th>
      <th><a href="https://www.tcm-international.com/">TCM International</a></th>
    </tr>
    <tr>
      <td width="33%"><p align="center"><img src="readmeImages/pwr-logo.png" height="100"></p></td>
      <td width="33%"><p align="center"><img src="readmeImages/mv-logo.png" height="100"></p></td>
      <td width="33%"><p align="center"><img src="readmeImages/TCM-logo-text.png" height="75"></p></td>
    </tr>
  </table>
</div>
