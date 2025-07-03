# 🩺 Medical Data Visualizer

Visualizing medical examination data to explore the relationship between various health metrics and cardiovascular disease.

---

## 📌 Project Overview

This project analyzes a dataset of patient medical records and visualizes relationships between health features and the presence of cardiovascular disease. The objective is to uncover patterns and trends that can be useful for public health insights and risk prediction.

Key tasks include:
- Data cleaning and normalization
- Feature engineering
- Creation of categorical plots and correlation heatmaps

---

## 📁 Files

- `medical_examination.csv` – The dataset used in the analysis
- `medical_data_visualizer.py` – The main script to clean data and generate plots
- `catplot.png` – Output categorical plot
- `heatmap.png` – Correlation heatmap of medical variables

---

## 📊 Tools & Libraries

- Python
- pandas
- matplotlib
- seaborn
- numpy

---

## 📸 Visualizations

### 📌 Categorical Plot (`catplot.png`)

Displays counts of patients grouped by features such as cholesterol, glucose, smoking, alcohol intake, and activity — separated by cardiovascular disease status.

![Categorical Plot](catplot.png)

---

### 🧪 Correlation Heatmap (`heatmap.png`)

Reveals correlation between variables like BMI, age, blood pressure, and disease outcome.

![Heatmap](heatmap.png)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AyushJ30/Medical-Data-Visualizer.git
   cd Medical-Data-Visualizer
