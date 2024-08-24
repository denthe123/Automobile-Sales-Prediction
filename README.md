# Automobile-Sales-Prediction

## Overview

This project aims to predict automobile sales using linear regression. It focuses on optimizing the R² score by exploring different random states and employing various data preprocessing techniques.

## Features

- **Data Preprocessing:** Handles categorical features with one-hot encoding and applies column transformations.
- **Model Training:** Utilizes linear regression in a pipeline with a `ColumnTransformer` for encoding and preprocessing.
- **Optimization:** Searches for the best random state to achieve the highest R² score for the regression model.

## Dataset

The dataset used in this project includes various features related to car sales:
- `Name`: Car model name
- `Location`: Location of the sale
- `Fuel_Type`: Type of fuel used by the car
- `Transmission`: Transmission type (manual/automatic)
- `Owner_Type`: Type of car owner (first/second/third etc.)

## Getting Started

### Prerequisites

Ensure you have Python 3.7+ and the necessary packages installed. You can install the required packages.

