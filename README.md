# ITEC6180 - Process Mining with PM4Py

## Assignment Overview
This repository contains the submission for **ITEC6180 Homework 3 - Process Mining Analysis** using PM4Py on Emergency Department (ED) hospital data.

## Dataset
- **EDHospital.csv**: Event log data from an Emergency Department containing patient case activities and timestamps
- Contains 55,079 cases with various medical activities including:
  - Reception, Nurse admission, Doctor admission
  - Diagnostic tests (blood tests, imaging)
  - Consultations and discharge processes

## Repository Structure

### Main Files:
- **`Part II Finalized.ipynb`** - **MAIN SUBMISSION FILE**
  - Complete analysis with all assignment answers
  - Process mining algorithms and visualizations
  - **Run this file to get the main assignment results**

- **`Tester_2.0.ipynb`** - Testing and Development Notebook
  - Detailed code exploration and testing
  - Additional analysis and algorithm variations
  - Execution timing and performance metrics

### Supporting Files:
- **`ITEC6180_Part_II.ipynb`** - Initial analysis notebook
- **`ITEC6180 EDHospital Group A Part1.pdf`** - BPMN diagram documentation
- **`EDHospital.csv`** - Primary dataset

## 🎯 Assignment Requirements Completed

### Part I: Log Exploration
- Load ED event log into PM4Py
- Identify main activities and paths
- Find most common activity and variant
- Analyze process structure

### Part II: Time Perspective
- Calculate average durations and delays
- Identify shortest and longest activities
- Analyze longest paths and bottlenecks
- Performance analysis

### Part III: Variant Analysis
- Filter infrequent variants
- Compare duration patterns
- Comment on findings

### Part IV: Process Discovery
- Apply Alpha Miner variations
- Apply Heuristic Miner
- Apply Inductive Miner
- Generate BPMN models
- Compare algorithm results

## 🚀 Quick Start

### Prerequisites
```bash
pip install pm4py pandas numpy matplotlib seaborn
