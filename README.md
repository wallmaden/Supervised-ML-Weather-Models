# Supervised-ML-Weather-Models
Analyse European weather trends using supervised machine learning to predict environmental outcomes, compare algorithm performance, and recommend the most effective model for climate forecasting.

**Author:** Paul Maden  
**Date:** April 2025

---

## Project Overview

This project was developed in collaboration with **ClimateWins**, a European nonprofit focused on understanding and predicting the effects of climate change, especially extreme weather events across Europe.

The goal of this project is to evaluate the use of supervised machine learning models to analyze historical weather data and identify the most effective algorithms for forecasting climate-related conditions.

---

## Objectives

- Use machine learning to detect and forecast climate-related weather patterns.
- Compare the performance of different supervised ML models.
- Recommend an optimal model for short- and long-term climate forecasting.
- Provide actionable next steps for integration into ClimateWins' tools and strategies.

---

## Data Source

- **European Climate Assessment & Dataset (ECAD)**
- Covers weather data from the **late 1800s to 2022**
- Includes data from **18 weather stations across Europe**
- Key features include: temperature, wind speed, snow, global radiation, and precipitation

---

## Methodology

### 1. Feature Optimization
- Preprocessed features to normalize scales and handle missing values
- Identified high-impact variables influencing daily weather conditions

### 2. Supervised Machine Learning Models
The following models were trained and evaluated:

- **K-Nearest Neighbors (KNN)**  
  Best performer on short-term predictions with high accuracy

- **Decision Tree**  
  Easy to interpret but prone to overfitting, lowest accuracy in trials

- **Artificial Neural Network (ANN)**  
  Handles complex, nonlinear patterns; requires more tuning and computational power

---

## Ethical Considerations

- **Bias:** Dataset coverage is uneven across regions, especially southern Europe
- **Transparency:** ANN models may be difficult to interpret in high-stakes decisions
- **Responsibility:** Machine learning results should be used in partnership with human expertise, especially when predicting extreme events

---

## Results & Recommendation

After evaluating the models

> **K-Nearest Neighbors (KNN)** is recommended for initial deployment due to its superior accuracy and simplicity. It is ideal for short-term forecasts (e.g., 48–72 hours) and easy to maintain for a nonprofit with limited technical resources.

---

## Next Steps

- Deploy KNN with cross-validation across multiple European regions
- Train and tune ANN models on long-term datasets to detect broader climate trends
- Integrate prediction output into an interactive dashboard for ClimateWins stakeholders

---

## Contact

For more information or collaboration inquiries, feel free to reach out via GitHub or LinkedIn.

---

## Repository Structure

/data → Weather datasets (ECAD historical data) /notebooks → Jupyter notebooks for data prep, training, evaluation /scripts → Python scripts for model functions /presentation → PowerPoint presentation (final report) /README.md → This file

yaml
Copy
Edit

---

## 🙏 Acknowledgments

CareerFountry provided the datasource and guidance for this case study.

