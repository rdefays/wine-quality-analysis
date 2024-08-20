# Wine Quality Analysis

## Overview

This project focuses on exploring and analyzing a wine quality dataset to enhance data science skills. The dataset is sourced from Kaggle and contains various attributes related to wine quality. The key objectives of this project are:

- **Data Exploration**: Understand the dataset, perform data cleaning, and handle missing values or outliers.
- **Data Visualization**: Create visualizations to uncover patterns and insights within the data.
- **Dimensionality Reduction**: Apply Principal Component Analysis (PCA) to reduce the dimensionality of the dataset and visualize it in 2D.
- **Regression Models**: Develop and evaluate regression models to predict wine quality.
- **Classification Models**: Implement classification models to categorize wine quality into distinct classes.
- **Performance Evaluation**: Use metrics such as ROC curves and confusion matrices to assess model performance.

### Project Structure

- **Data Exploration and Cleaning**: Noteboos for initial data exploration and preprocessing.
- **Visualization**: Code for generating visualizations and insights.
- **Dimensionality Reduction**: PCA implementation and results.
- **Models**: Regression and classification models, including hyperparameter tuning and evaluation.
- **Reports**: Results and findings from the analysis, including visualizations and performance metrics.


## Overview

This project focuses on exploring a dataset to enhance data science skills. The dataset is obtained from Kaggle and includes various attributes related to wine quality. The goal of this project is to thoroughly analyze the dataset, apply various data science techniques, and showcase findings and capabilities.

**Data Source:** [Wine Quality Dataset](https://www.kaggle.com/datasets/abdelazizsami/wine-quality)

**DOI Citation:** 10.34740/kaggle/dsv/8948959

## Table of Contents

- [Wine Quality Analysis](#wine-quality-analysis)
  - [Overview](#overview)
    - [Project Structure](#project-structure)
  - [Overview](#overview-1)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Data](#data)
  - [Objectives](#objectives)
  - [Results](#results)
  - [Contributing](#contributing)
  - [License](#license)

## Introduction

This project is designed to improve data science skills by working with a real-world dataset. It involves data cleaning, exploration, visualization, and applying machine learning algorithms to uncover insights and trends in the data.

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/rdefays/wine-quality-analysis.git
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd wine-quality-analysis
    ```

3. **Install Dependencies:**
    Make sure you have Python and pip installed. Then, install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the project, follow these steps:

1. **Load the Dataset:**
    ```python
    import pandas as pd
    data = pd.read_csv('data/wine_quality.csv')
    ```

2. **Run Analysis:**
    Execute the Jupyter notebook or Python scripts to perform data analysis and modeling:
    ```bash
    jupyter notebook
    ```
    Or
    ```bash
    python analysis.py
    ```

## Data

The dataset used in this project is available from Kaggle and contains various attributes related to wine quality. You can download it using the following link:

- [Wine Quality Dataset](https://www.kaggle.com/datasets/abdelazizsami/wine-quality)

The dataset file is located in the `data/` directory:
- `data/wine_quality.csv`

## Objectives

The primary objective of this project is to:

- Explore and clean the dataset.
- Perform exploratory data analysis (EDA).
- Apply various data science techniques, including data visualization and machine learning.
- Showcase the findings through visualizations and performance metrics.

## Results

Results and findings from the project are included in the Jupyter notebook or Python script. You can view visualizations, summaries, and any conclusions drawn from the analysis.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


