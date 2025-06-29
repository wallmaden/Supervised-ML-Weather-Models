# Supervised-ML-Weather-Models
Analyse European weather trends using machine learning (supervised and unsupervised) to predict environmental outcomes, compare algorithm performance, detect long-term climate patterns, and recommend models for climate forecasting.

![Python Logo](https://github.com/wallmaden/Supervised-ML-Weather-Models/raw/main/04%20Analysis%20and%20Visualisations/python-logo.png)

**Author:** Paul Maden  
**Date:** June 2025

---

## Project Overview

This project was developed in collaboration with **ClimateWins**, a European nonprofit focused on understanding and predicting the effects of climate change—especially extreme weather events across Europe.

The project was completed in two phases:

- **Achievement 1 (Part 1):** Focused on using **supervised machine learning** to predict favorable weather conditions and evaluate model performance.
- **Achievement 2 (Part 2):** Applied **unsupervised learning**, advanced ML models, and deep learning (e.g. CNNs) to explore long-term climate trends and generate insights for policy recommendations.

The work culminated in a final proposal presentation (see `/presentation/`) highlighting model comparisons, results, and strategic forecasts.

---

## Objectives

- Predict favorable vs. hazardous weather conditions using ML  
- Compare supervised models (e.g. KNN, Decision Trees, ANN)  
- Apply unsupervised learning to reveal climate trends and anomalies  
- Experiment with CNNs and advanced tuning to forecast future risks  
- Recommend safe zones for habitation over 25–50 years  
- Translate results into actionable proposals for ClimateWins  

---

## Data Source

- **European Climate Assessment & Dataset (ECAD)**
- Covers weather data from the **late 1800s to 2022**
- Includes data from **18 weather stations across Europe**
- Key features include: temperature, wind speed, snow, global radiation, and precipitation

---

## Methodology

### Part 1 – Supervised Learning

- Preprocessing: normalization, imputation, and feature selection  
- Models:
  - **K-Nearest Neighbors (KNN)** — Top short-term performer  
  - **Decision Tree** — Interpretable but less accurate  
  - **Artificial Neural Network (ANN)** — Strong but resource-intensive  

### Part 2 – Advanced & Unsupervised ML

- Clustering & pattern discovery (K-Means, PCA)  
- Advanced deep learning using **CNNs** to detect radar-like patterns  
- Hyperparameter tuning and optimization  
- Forecasting safest zones for habitation (next 25–50 years)  

---

## Thought Experiments (from Final Presentation)

1. **Discovering Patterns in Changing Weather**  
   Unsupervised models to reveal climate deviations  

2. **Better Forecasts Through Tuning**  
   CNN & model optimization comparisons (pre- vs. post-tuning)  

3. **Seeing Weather with ML**  
   Visual modeling of radar-like patterns via convolutional neural networks 

---

## Ethical Considerations

- **Bias:** Dataset coverage is uneven across regions, especially southern Europe
- **Transparency:** ANN models may be difficult to interpret in high-stakes decisions
- **Responsibility:** Machine learning results should be used in partnership with human expertise, especially when predicting extreme events

---

## Results & Recommendation

> **K-Nearest Neighbors (KNN)** remains the best choice for short-term forecasting  
> **CNNs** and deep models show promise for visual classification of climate extremes  
> **Unsupervised techniques** valuable for long-term strategic insight and risk mapping  

---

## Next Steps

- Deploy KNN for regional short-term forecasting  
- Extend CNN training with weather radar simulation datasets  
- Integrate climate risk zones into ClimateWins' planning dashboard  
- Further test ensemble and GAN models for future scenario generation 

---

## Contact

For more information or collaboration inquiries, feel free to reach out via GitHub or LinkedIn.

---

## Repository Structure

/data → Weather datasets (ECAD)
/notebooks → Jupyter notebooks for modeling & analysis
/scripts → Python scripts for ML, preprocessing, tuning
/presentation → Final PowerPoint report & visuals
README.md → This file

---

## Acknowledgments

CareerFountry provided the datasource and guidance for this case study.

