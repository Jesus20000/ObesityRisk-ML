### Goal

The goal is to predict obesity risk in individuals based on various health indicators.

## Project Description

This project involves developing a machine learning model to predict obesity risk categories. The dataset includes features such as age, height, weight, and other health-related attributes. The aim is to create a model that accurately classifies individuals into different obesity risk categories.

## Project Structure

- `data/`
  - `train.csv` : Training dataset.
  - `test.csv` : Test dataset.
- `notebooks/`
  - `obesity_risk_prediction.ipynb` : Jupyter Notebook with code for data analysis, preprocessing, and modeling.
- `src/`
- `README.md` : Project overview and instructions.
- `requirements.txt` : List of required Python packages.

## Data Description

- `id` : Unique identifier for each individual.
- `Gender` : Gender of the individual.
- `Age` : Age of the individual.
- `Height` : Height of the individual (in cm).
- `Weight` : Weight of the individual (in kg).
- `family_history_with_overweight` : Indicates family history of overweight.
- `FAVC` : Frequency of high caloric food consumption.
- `FCVC` : Frequency of vegetable consumption.
- `NCP` : Number of main meals consumed per day.
- `CAEC` : Alcohol consumption.
- `SMOKE` : Smoking status.
- `CH2O` : Amount of water consumption.
- `SCC` : Snack consumption status.
- `FAF` : Frequency of physical activity.
- `TUE` : Time spent on physical activity.
- `CALC` : Caloric consumption.
- `MTRANS` : Transportation mode.
- `NObeyesdad` : Target variable indicating obesity risk category.

## Usage

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Multi-Class-Prediction-of-Obesity-Risk.git
   cd Multi-Class-Prediction-of-Obesity-Risk
