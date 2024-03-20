# LoS and Disease Prediction

## Overview

The LoS (Length of Stay) and Disease Prediction project utilizes machine learning techniques to predict the length of stay and disease outcomes for patients based on data from the MIMIC-IV dataset. The project consists of two separate Jupyter notebooks: one for predicting length of stay and another for disease prediction.

## MIMIC-IV

[MIMIC-IV](https://physionet.org/content/mimiciv/2.2/), the Medical Information Mart for Intensive Care IV, is a comprehensive dataset comprising health-related data for patients admitted to intensive care units (ICUs). It encompasses patient demographics, clinical measurements, laboratory results, medications, procedures, and outcomes, providing a rich resource for researchers and healthcare professionals. Widely utilized for clinical research, predictive modeling, decision support system development, and medical education, MIMIC-IV facilitates the study of critical care medicine, disease patterns, and the development of algorithms for patient monitoring and management.

## Requirements

To run the project, ensure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- xgboost

Additionally, the project requires access to the MIMIC-IV dataset.

## Jupyter Notebooks

The project is divided into two separate Jupyter notebooks:

1. **LoS Prediction.ipynb**: This notebook focuses on predicting the length of stay for patients using various machine learning algorithms. It includes data preprocessing, model training, evaluation, and visualization. *Refer to the pdf version for complete preview*

2. **Disease Prediction.ipynb**: This notebook is dedicated to predicting disease outcomes for patients based on the MIMIC-IV dataset. Similar to the LoS prediction notebook, it covers data preprocessing, model training, evaluation, and visualization.

## Usage

1. Clone the repository to your local machine:

    ```
    git clone https://github.com/your-username/los-and-disease-prediction.git
    ```

2. Install the required dependencies using pip:

    ```
    pip install pandas numpy matplotlib seaborn scikit-learn statsmodels xgboost
    ```

3. Access the [MIMIC-IV dataset](https://mimic.mit.edu/docs/gettingstarted/) and ensure it is properly loaded in the Jupyter notebooks.

4. Open and run the Jupyter notebooks (**LoS Prediction.ipynb** and **Disease Prediction.ipynb**) in your preferred environment.

## Dataset

The MIMIC-IV dataset is a comprehensive collection of health-related data for patients admitted to intensive care units (ICUs). It includes information such as patient demographics, vital signs, laboratory results, medications, procedures, and outcomes.

## Acknowledgments

Special thanks to the creators of the MIMIC-IV dataset for providing valuable data for healthcare research.

