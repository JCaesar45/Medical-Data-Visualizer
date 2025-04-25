```markdown
# Page View Time Series Visualizer

This project is part of the freeCodeCamp Data Analysis with Python Certification. It visualizes forum page view data from freeCodeCamp using line charts, bar charts, and box plots to highlight trends and seasonal patterns.

## 📊 Project Summary

The dataset contains daily page views from May 2016 to December 2019. The goal is to visualize:
- Long-term trends with a **line plot**
- Average monthly usage by year with a **bar plot**
- Distributions over time with **box plots**

## 🛠️ Technologies Used
- Python 3
- Pandas
- Matplotlib
- Seaborn

## 📁 Files
- `time_series_visualizer.py`: Contains the main code and all plot functions.
- `main.py`: Script to run and test visualizations.
- `test_module.py`: Unit tests to verify the functionality.
- `fcc-forum-pageviews.csv`: The dataset (daily forum page views).

## 📌 Instructions

### 1. Load and Clean the Data
- Import from `fcc-forum-pageviews.csv`
- Remove data below the 2.5th percentile and above the 97.5th percentile

### 2. Line Plot (`draw_line_plot`)
Shows page views over time.

### 3. Bar Plot (`draw_bar_plot`)
Displays average daily page views per month grouped by year.

### 4. Box Plots (`draw_box_plot`)
Two plots:
- **Year-wise Box Plot**: Displays yearly trend
- **Month-wise Box Plot**: Shows seasonality

## 🧪 Run Tests

```bash
pytest test_module.py
```

## 📸 Output Examples
- `line_plot.png`
- `bar_plot.png`
- `box_plot.png`

## ✅ Certification Project
Submit this on the [freeCodeCamp](https://www.freecodecamp.org/) platform to earn credit for the "Page View Time Series Visualizer" project.

---
```

---
