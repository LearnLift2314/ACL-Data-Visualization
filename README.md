# ACL-Data-Visualization

## Overview
This repository contains Python scripts for visualizing ACL (Anterior Cruciate Ligament) injury and recovery data. The project generates plots that show trends in injury rates and recovery times based on various factors such as age, height, weight, gender, training intensity, rest days, rehabilitation efficiency, and rehabilitation programs.

The project is implemented entirely in Python and is designed to run in a local Python environment, Jupyter Notebook, or Google Colab.

By visualizing ACL injury trends and recovery times, this project provides actionable insights for athletes, coaches, and clinicians. It highlights key risk factors, gender differences, and recovery patterns, helping inform training, rehabilitation, and injury prevention strategies. This work is inspired by real-world ACL challenges and aims to reduce injury risks while supporting faster, data-driven recovery decisions. 

---

## Project Structure
.
├── ACL_Data_Visualization.py
├── Python Plotting 1 - Injury Risk.xlsx
├── Python Plotting 2 - Recovery Time.xlsx
├── README.md
---

## Methods

### ACL Injury Data Visualization
This section generates plots analyzing ACL injury risk:

- Line plots compare **Female, Male, and Overall** injuries against age, height, weight, training intensity, and rest days.  
- Regression (trend) lines are added using Seaborn to highlight trends.  
- Gender-specific differences are visualized in a bar chart.

### ACL Recovery Time Visualization
This section generates plots analyzing post-injury recovery time:

- Line plots show **Average Recovery Time** versus age, height, weight, jump height, speed, and rehabilitation efficiency.  
- Trend lines are added to indicate relationships.  
- A pie chart shows the distribution of recovery times across different rehabilitation programs.

---

## Technologies & Libraries Used
- Python 3.8+  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- openpyxl  

---

## Output Files
The project generates the following figures as PDFs:

- Fig_1.pdf – ACL Injury Rates Vs. Age  
- Fig_2.pdf – ACL Injury Rates Vs. Height  
- Fig_3.pdf – ACL Injury Rates Vs. Weight  
- Fig_4.pdf – ACL Injury Rates Vs. Training Intensity  
- Fig_5.pdf – ACL Injury Rates Vs. Training Hours  
- Fig_6.pdf – ACL Injury Rates Vs. Rest Days  
- Fig_7.pdf – ACL Injury Rates Vs. Gender  
- Fig_8.pdf – ACL Recovery Time Vs. Age  
- Fig_9.pdf – ACL Recovery Time Vs. Height  
- Fig_10.pdf – ACL Recovery Time Vs. Weight  
- Fig_11.pdf – ACL Recovery Time Vs. Jump Height  
- Fig_12.pdf – ACL Recovery Time Vs. Speed  
- Fig_13.pdf – ACL Recovery Time Vs. Rehabilitation Efficiency  
- Fig_14.pdf – ACL Recovery Time Vs. Rehabilitation Program  

---

## How to Run Locally

### Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn openpyxl
Required Data Files

Ensure the following Excel files are located in the same directory as the Python script:

Python Plotting 1 - Injury Risk.xlsx

Python Plotting 2 - Recovery Time.xlsx
Run Instructions

Run the Python script to generate all plots:
python ACL_Data_Visualization.py
All plots will be saved as PDFs in the local directory (Fig_1.pdf to Fig_14.pdf).
Reproducibility

All plotting and regression steps are fully contained within the Python script. Random states are fixed where applicable to ensure reproducibility. No external APIs or pretrained models are used.
Author

Ben Zhang
