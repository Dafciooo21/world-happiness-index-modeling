<<<<<<< HEAD

## **World Happiness Index Modeling**

<img src="whr-cover-ico.png" alt="WHI" width="250"/>

This repository contains a Jupyter notebook that performs an analysis and modeling of the World Happiness Index (WHI). The WHI is a comprehensive indicator that measures the level of perceived happiness in various countries. It was developed by the Sustainable Development Solutions Network (SDSN), a network for sustainable development solutions operating under the aegis of the United Nations (UN). The data for the index is derived from extensive surveys where respondents rate their lives on a scale from 0 to 10, with 0 indicating the worst possible quality of life and 10 the best.

## Project Motivation & Goal

The motivation behind this project is to explore and understand the factors that influence the happiness of nations. By analyzing various socio-economic indicators, we aim to identify key determinants of happiness and develop models that can predict the World Happiness Index. This can help policymakers and researchers to design better strategies for improving the well-being of populations around the world.

The goal of this analysis is to understand the factors contributing to the World Happiness Index and to build predictive models to estimate the index based on various socio-economic indicators.

## ****Loading Data****

Data is loaded from a CSV file containing panel data on various happiness-related metrics for different countries over multiple years.

- [Agregated data in csv format](https://worldhappiness.report/data/)
- [Official WHI_2023 Report](https://worldhappiness.report/data/)

## Description

#### Data Preprocessing

- Selection of relevant variables,
- Handling missing values,
- Verifying data types.

#### Exploratory Data Analysis (EDA)

- Visualizing the distribution of variables,
- Identifying correlations between different variables,
- Detecting outliers and anomalies,
- Understanding trends over time.

#### Modeling

Several models are applied to the preprocessed data to predict the World Happiness Index:

**1.**	**Multiple Linear Regression**

**2.**	**Polynomial Regression**

**3.**	**Random Forest**

**4.**	**AdaBoost**

###### **Model Evaluation**

Each model is evaluated using Mean Squared Error (MSE) on training and test datasets. Learning curves are plotted to assess model performance.

#### **Conclusions**

The analysis compares the performance of multiple regression models, highlighting their strengths and weaknesses. The learning curves and evaluation metrics provide insights into which model best predicts the World Happiness Index.

## **How to Run**

**1.**	Clone the repository.

**2.**	Install the required libraries.

**3.**	Execute the Jupyter notebook.

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
jupyter notebook WHI.ipynb
```

## Licensing, Authors, Acknowledgements

This analysis is based on the World Happiness Report data. Feel free to use this code to add additional features.
=================================================================================================================

## **World Happiness Index Modeling**

<img src="whr-cover-ico.png" alt="WHI" width="250"/>

**World Happiness Index** is a comprehensive indicator that measures the level of perceived happiness in various countries. It was developed by the Sustainable Development Solutions Network (SDSN), a network for sustainable development solutions operating under the aegis of the United Nations (UN). The data for the index is derived from extensive surveys where respondents rate their lives on a scale from 0 to 10, with 0 indicating the worst possible quality of life and 10 the best.

The ranking is published annually, and the results are used not only to assess the progress of countries towards sustainable development goals but also serve as a tool for policymakers to develop and modify policies aimed at enhancing the overall level of happiness and quality of life.

This index serves as an important diagnostic tool that helps understand how different policies and socio-economic conditions affect the well-being of citizens, thereby contributing to promoting global initiatives aimed at building more harmonious and happier societies.

## Table of Contents

## Installation

## Project Motivation

## Description

## Licensing, Authors, Acknowledgements

The underlying data used for the analysis comes from the WorldHapiness website. Feel free to use this code to add additional features.

### **Links to data and the official report website:**

- [Agregated data in csv format](https://worldhappiness.report/data/)
- [Official WHI_2023 Report](https://worldhappiness.report/data/)
