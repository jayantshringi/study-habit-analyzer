# 🎓 Academic Performance & Study Habit Analyzer

Welcome to the **Academic Performance & Study Habit Analyzer**! This is an interactive, beginner-friendly data science project designed to explore how a student's daily inputs (such as weekly study hours, sleep, and attendance) relate to their academic outputs (subject grades).

This project uses Python, **Pandas** for data preparation, and **Matplotlib** for creating rich, modern visualizations.

---

## 🚀 Project Overview

In data science, visualization is one of the most powerful tools for finding patterns and correlation. This notebook guides you step-by-step through:
1. **Structuring Student Data** into a tabular format.
2. **Analyzing Metrics** across different courses.
3. **Visualizing Trends and Allocations** using four fundamental types of charts.

---

## 📊 Visualizations Included

The analyzer demonstrates how to use **Matplotlib** to build and customize four distinct chart types:

| Chart Type | Purpose | variables Visualized |
| :--- | :--- | :--- |
| 📊 **Bar Chart** | Side-by-side comparison of categories. | Subject vs. Average Grade (%) |
| 📈 **Line Chart** | Tracking progress and trajectories over time. | Semester Milestones vs. Grade Score (%) |
| 🍕 **Pie Chart** | Breakdown of how a single resource (time) is divided. | Activities vs. Weekly Hours Allocation |
| 🎯 **Scatter Plot** | Analyzing correlation/relationship between two variables. | Study Hours (per week) vs. Average Grade (%) |

---

## 📋 The Dataset

The notebook uses a simulated student dataset representing a typical academic week:

| Subject | Study Hours (per week) | Attendance Rate (%) | Average Grade (%) |
| :--- | :---: | :---: | :---: |
| **Math** | 8 | 95% | 85% |
| **Python Programming** | 12 | 98% | 92% |
| **Science** | 6 | 90% | 78% |
| **History** | 4 | 85% | 70% |
| **English** | 5 | 88% | 82% |

---

## ⚙️ Setup & Installation

To run this notebook locally, ensure you have Python installed along with the required libraries.

### 1. Install Dependencies
Run the following command in your terminal/command prompt to install the required libraries:
```bash
pip install pandas matplotlib notebook
```

### 2. Launching the Notebook
1. Open your terminal and navigate to the project directory.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the file [Academic Performance & Study Habit Analyzer.ipynb](file:///d:/bytXL/Data%20Science/Project/Academic%20Performance%20&%20Study%20Habit%20Analyzer.ipynb) and start running the cells!

---

## 🔍 Detailed Notebook Walkthrough

### 1. Library Imports & Dataset Creation
Loads `pandas` and `matplotlib.pyplot` and structures the dictionary of subject records into a `pandas.DataFrame`.

### 2. Bar Chart: Subject Grade Comparison
Uses a curated, modern hex color palette (`#4F46E5`, `#06B6D4`, etc.) to compare performance across courses. It configures titles, labels, y-axis limits (0–100%), and grid lines.

### 3. Line Chart: Grade Trajectory
Tracks progress across semester milestones (*Quiz 1*, *Quiz 2*, *Midterm*, *Project 1*, *Final Exam*) in Python Programming. Illustrates the learning curve.

### 4. Pie Chart: Weekly Time Breakdown
Explodes the *Self-Study* slice to emphasize focus. Displays percentages automatically of how the 168 hours of a week are distributed across Lectures, Self-Study, Extracurriculars, Sleep, and Leisure.

### 5. Scatter Plot: Correlation Analysis
Maps weekly study hours on the X-axis and average grades on the Y-axis. Labels each data point with the subject name using `plt.annotate()` to identify which subjects follow a strong positive correlation.

---

## 🧪 Try It Yourself! (Exercises)

To deepen your understanding, try making the following edits in the notebook:
* **Add New Subjects:** Add a row for `"Chemistry"` or `"Art"` to the dataset in Section 1 and rerun all cells to see the charts auto-update.
* **Modify Student Data:** Edit the study hours or grades to see how it affects the scatter plot correlation.
* **Customize Aesthetics:** Experiment with different colors by changing the hex color lists (e.g., `#4F46E5`, `#10B981`) to your own preferred themes.
