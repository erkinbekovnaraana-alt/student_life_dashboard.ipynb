# Student Performance Analysis — Behavioral Factors Study

## Overview

This project explores the relationship between student behavior and academic performance through data analysis and visualization.

The study focuses on three key factors:

* study time
* sleep duration
* phone usage

The objective is to identify patterns and understand how these variables influence exam outcomes.

---

## Problem Statement

Student performance is influenced by multiple lifestyle factors. This project aims to answer:

* How does study time affect exam scores?
* Does sleep contribute to better academic performance?
* What is the impact of phone usage on student success?

---

## Data

A structured dataset was created with the following variables:

* `study_hours`: number of hours spent studying
* `phone_hours`: daily phone usage
* `sleep_hours`: hours of sleep
* `exam_score`: exam performance

The dataset contains 8 observations representing different behavioral patterns.

---

## Methodology

### Data Preparation

* Data was organized using a Pandas DataFrame
* Variables were selected to represent key behavioral factors

---

### Visualization

Three scatter plots were created using Plotly:

1. Study Hours vs Exam Score
2. Sleep Hours vs Exam Score
3. Phone Usage vs Exam Score

These visualizations help identify relationships between variables and performance.

---

## Results

### Study Time

A positive relationship is observed between study hours and exam scores:

* Increased study time is associated with higher performance

---

### Sleep

Sleep also shows a positive correlation:

* Students with more sleep tend to achieve better results

---

### Phone Usage

A negative relationship is observed:

* Higher phone usage is associated with lower exam scores

---

## Key Insights

* Academic performance improves with increased study time
* Adequate sleep is an important factor in learning efficiency
* Excessive phone usage may negatively impact concentration and results

---

## Limitations

* Small dataset size
* Synthetic data does not capture real-world complexity
* No statistical tests or modeling applied

---

## Future Improvements

* Use real-world student datasets
* Apply statistical analysis (correlation coefficients, regression)
* Conduct hypothesis testing
* Expand features (e.g., stress, attendance, study methods)
* Build predictive models

---

## Tech Stack

* Python
* Pandas
* Plotly

---

## Repository Structure

```id="q7w8e9"
student-performance-analysis/
│
├── notebook.ipynb
├── README.md
```

---

## Conclusion

The analysis suggests that student performance is influenced by behavioral factors. Increased study time and sufficient sleep contribute positively, while excessive phone usage has a negative effect.

---

## Author

Independent project focused on data analysis and behavioral insights in education.
