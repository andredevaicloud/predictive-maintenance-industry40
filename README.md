# ⚙ Predictive Maintenance for Industry 4.0 (IoT Data Analysis)

[![Status](https://img.shields.io/badge/Status-Completed%20V1-brightgreen.svg)]()
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-Project-lightgrey.svg)]()

## Project Overview

This project is a foundational Machine Learning solution for *Predictive Maintenance* (PdM) in a simulated manufacturing environment. It demonstrates the ability to analyze simulated Internet of Things (IoT) sensor data (Temperature and Vibration) to anticipate equipment failures, a core principle of *Industry 4.0*.

The primary goal is to shift from reactive maintenance (fixing things after they break) to *proactive scheduling*, saving costs and minimizing unplanned downtime.

**[View the full analysis in the Jupyter Notebook: IndustriaI40.ipynb](./IndustriaI40.ipynb)**

---

## Key Features & Business Value

| Feature | Description | Business Impact (Industry 4.0) |
| :--- | :--- | :--- |
| *IoT Data Simulation* | Generated a synthetic time-series dataset with induced anomalies (pre-failure state). | *Data Readiness:* Demonstrated capacity to handle and structure industrial sensor data. |
| *ML Classification* | Trained a *Logistic Regression* model to classify equipment state (Normal vs. Risk of Failure). | *Operational Efficiency:* Provides a clear, actionable binary alert for maintenance teams. |
| *Zero False Alarms* | Achieved *1.00 Precision* for the "Risk of Failure" class. | *Cost Reduction:* Avoids unnecessary equipment shutdowns and wasted labor costs. |
| *High Recall* | Achieved *0.93 Recall* for the "Risk of Failure" class. | *Risk Mitigation:* Successfully captured 93% of all imminent failures, drastically reducing the risk of catastrophic unplanned downtime. |

## 🛠 Technology Stack

| Category | Tools / Libraries |
| :--- | :--- |
| *Language* | Python 3.x |
| *Environment* | Jupyter Notebook |
| *Data Handling* | Pandas, NumPy |
| *Machine Learning* | Scikit-learn (sklearn) |
| *Visualization* | Matplotlib, Seaborn |

## 📁 Repository Structure

