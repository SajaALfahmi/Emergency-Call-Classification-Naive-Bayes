# Emergency Call Classification using Naïve Bayes

This project implements a **Bernoulli Naïve Bayes classifier** to categorize emergency calls into two priority levels (High Priority vs. Low Priority). The project was developed as part of a Machine Learning assignment.

## Project Overview
The core objective is to understand the mathematical foundations of the Naïve Bayes algorithm by implementing it from scratch and comparing the results with professional machine learning libraries.

## Key Features
- **Manual Implementation:** Calculated prior and conditional probabilities from scratch.
- **Laplace Smoothing:** Applied `+1` smoothing to handle zero-frequency issues in the dataset.
- **Scikit-learn Comparison:** Validated manual calculations against the `BernoulliNB` model from `scikit-learn` to ensure accuracy.
- **Model Evaluation:** Used 10-fold cross-validation to assess model performance.
- **Data Visualization:** Analyzed feature impact using Matplotlib and Seaborn.

## Technologies Used
- **Language:** Python
- **Libraries:** - `pandas` & `numpy` (Data manipulation and calculations)
  - `scikit-learn` (Model verification and cross-validation)
  - `matplotlib` & `seaborn` (Visualization)

## Project Structure
- `Naive_Bayes.ipynb`: The main Jupyter Notebook containing the full implementation and analysis.
- `emergency_triage_nb_train.csv`: Training dataset.
- `emergency_triage_nb_queries.csv`: Query instances for testing.

## Results Summary
The manual implementation matched the `scikit-learn` results perfectly. The model achieved an accuracy of approximately **56%** using 10-fold cross-validation. Symptoms such as *severe_bleeding*, *unconscious*, and *chest_pain* were identified as the strongest predictors for high-priority calls.

---
*Created by Saja Alfahmi*
