# Emergency Call Classification using Naïve Bayes

A machine learning project that classifies emergency calls into **High Priority** and **Low Priority** using the Bernoulli Naïve Bayes algorithm.

This project focuses on understanding the mathematical foundations of Naïve Bayes by implementing the algorithm from scratch and validating the results using the scikit-learn implementation.

---

## Project Overview

Emergency call prioritization is essential for allocating emergency resources efficiently. This project predicts the priority level of emergency calls based on reported symptoms using a Bernoulli Naïve Bayes classifier.

The implementation includes manual probability calculations, Laplace smoothing, model evaluation, and comparison with the scikit-learn implementation.

---

## Key Features

- Implemented Bernoulli Naïve Bayes from scratch.
- Computed prior and conditional probabilities manually.
- Applied Laplace smoothing to handle zero-frequency problems.
- Validated results using scikit-learn's BernoulliNB.
- Evaluated the model using 10-fold Cross Validation.
- Visualized conditional probabilities using charts.

---

## Results

The manually implemented classifier produced predictions consistent with the scikit-learn implementation.

The model achieved an average accuracy of approximately **56%** using **10-fold Cross Validation**.

---

## Visualization

### Conditional Probability Bar Chart

![Probability Bar Chart](probability bar chart.png)

---

### Conditional Probability Line Plot

![Conditional Probability Line Plot](conditional probability line plot.png)

---

## Documentation

A detailed assignment report is included in this repository covering:

- Manual probability calculations
- Laplace smoothing
- Mathematical derivation
- Model evaluation
- Discussion and conclusions

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Repository Structure

```text
.
├── README.md
├── emergency_triage_analysis.ipynb
├── Emergency_Call_Classification_Assignment.pdf
├── probability_bar_chart.png
├── conditional_probability_line_plot.png
```

---
*Created by Saja Alfahmi*
