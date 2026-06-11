# Medical Radiology Report Generation System

## Overview
This repository contains a Natural Language Generation (NLG) and data analysis project focused on automating medical documentation. Specifically, it demonstrates workflows for processing structured radiology data (such as imaging modalities and lung findings) and generating cohesive, standardized clinical reports.

## Project Architecture & Assets

### 📓 Jupyter Notebooks
* **`01_Medical_Report_Generation_Basics.ipynb`:** Explores the foundational concepts of medical text generation, data extraction, and basic reporting workflows.
* **`02_Medical_Report_Generation_System.ipynb`:** The complete, end-to-end system designed to take structured patient findings and output formatted clinical text.

### 📁 Dataset
* **`radiology_reports_summary.csv`:** The underlying dataset containing structured patient data. It includes variables such as imaging modality (e.g., CT, X-Ray), specific lung/pleural/bone findings, overall impression categories, and generated report word counts.

## Potential Use Cases
Automated report generation in healthcare helps to:
* Reduce physician burnout by drafting routine clinical notes.
* Standardize medical terminology across radiology departments.
* Ensure critical findings are consistently formatted and highlighted.

## How to Use
1. **Clone the Repository:** Download the project files to your local machine.
2. **Explore the Code:** Open the Jupyter Notebooks sequentially (01, then 02) to understand the progression from basic data handling to the full generation system. 
3. **Analyze the Data:** The CSV dataset can be loaded into Pandas to inspect the relationship between specific medical findings and the length/structure of the resulting reports.

> **Disclaimer:** All data and generated reports within this repository are synthetic and created strictly for educational demonstration purposes. This project does not contain any real patient health data or Protected Health Information (PHI).
