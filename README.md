# Cybersecurity AI - Intrusion Detection System

This repository contains the implementation of an **AI-powered intrusion detection system (IDS)** designed to enhance cybersecurity by identifying and classifying malicious network activity. The project leverages the **KDD dataset** and utilizes **machine learning techniques** for intrusion detection.

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Dataset](#dataset)
---

## Overview
The **Cybersecurity AI project** is focused on developing an advanced intrusion detection system. By applying machine learning algorithms to the KDD dataset, the system detects and classifies network activity as normal or malicious, helping to prevent and mitigate cybersecurity threats.

### Key Objectives:
- Enhance the understanding of network security.
- Implement a robust machine learning pipeline to detect intrusions.
- Provide a reproducible and scalable solution for cybersecurity challenges.

---

## Features
- **Machine Learning-Based Intrusion Detection**: Employs various algorithms to classify network activity.
- **KDD Dataset Integration**: Utilizes the KDD dataset for training and evaluation.
- **Interactive Jupyter Notebook**: Provides analysis and implementation in an easy-to-follow format.
- **Customizable**: Allows users to experiment with different models and configurations.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/eyabesbes/cybersecurity-AI.git
   cd cybersecurity-AI
   ```

2. Set up a Python environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Usage
1. Open the Jupyter Notebook file provided in the repository.
2. Load the KDD dataset (instructions provided in the [Dataset](#dataset) section).
3. Execute the cells step-by-step to train and evaluate the intrusion detection system.
4. Customize the code to experiment with different algorithms or parameters.

---

## Dataset
The project utilizes the **KDD Cup 1999 dataset**, a benchmark dataset for evaluating intrusion detection systems. 

### Download the Dataset:
- You can download the dataset from [KDD Cup 1999 Dataset](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html).
- Place the dataset in the `data/` directory of the repository.
