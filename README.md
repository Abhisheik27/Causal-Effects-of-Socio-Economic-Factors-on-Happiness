# Causal Analysis of Socio-Economic Factors on Happiness

This project explores the causal impact of socio-economic factors like GDP per capita, social support, health, and freedom on national happiness using advanced causal inference techniques.

## Objective

To identify and quantify the causal effects of key socio-economic variables on a country’s Happiness Score using:

- **LiNGAM** (Linear Non-Gaussian Acyclic Model)
- **DoWhy** framework
- **Propensity Score Matching**

## Dataset

World Happiness Report data (2015–2019)  
Source: [Kaggle - Economics of Happiness](https://www.kaggle.com/datasets/nikbearbrown/the-economics-of-happiness-simple-data-20152019/data)

## Methods Used

- **LiNGAM**: Identified the causal structure and direction of influence between variables.
- **DoWhy**: Estimated Average Treatment Effects (ATE) under formal assumptions.
- **Propensity Score Matching**: Controlled for confounding and validated causal claims.

## Key Results

| Factor           | ATE (DoWhy) | ATE (Propensity) |
|------------------|-------------|------------------|
| GDP per capita   | 1.959       | 1.274            |
| Social support   | 0.586       | 0.561            |
| Healthy life     | 1.026       | 1.253            |
| Freedom          | 1.987       | 1.751            |

## Conclusions

- **Freedom** and **GDP per capita** show the strongest causal effects on happiness.
- All factors studied had positive causal influence, supporting their role in well-being policy decisions.
- Results were consistent across methods, reinforcing reliability.

##  Tech Used

Python, pandas, DoWhy, LiNGAM, matplotlib, sklearn
