# Data Mining Project: Weather Condition Clustering and Rain Prediction

This repository contains the code and resources for a data mining project focused on clustering weather conditions and predicting whether it will rain. The project employs various classification techniques and evaluates the clustering performance using ARI (Adjusted Rand Index) and NMI (Normalized Mutual Information).

## Project Overview

This project aims to perform clustering on a weather condition dataset and evaluate the clustering performance using ARI and NMI metrics. Additionally, it includes a prediction task to determine whether it will rain based on the clustered weather conditions using classification algorithms such as K-Nearest Neighbors (KNN), Decision Tree Classifier, and Support Vector Machine (SVM).

## Contents

- `Project_2_datamining.ipynb`: Jupyter Notebook containing the entire project workflow.
- `data/`: Directory containing the weather condition dataset used in this project.


## Requirements

To run the code in this repository, you need the following packages:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

You can install the required packages using pip:

```bash
pip install numpy pandas scikit-learn matplotlib jupyter
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/maryamjbr/classification_weather_condition_dataset.git
cd classification_weather_condition_dataset
```

2. Download the weather condition dataset and place it in the `data/` directory.

3. Open the Jupyter Notebook:

```bash
jupyter notebook Project_2_datamining.ipynb
```

4. Follow the steps in the notebook to preprocess the data, apply KNN, Decision Tree, and SVM classifiers, evaluate the results using ARI and NMI, and predict whether it will rain.

## Project Steps

### 1. Data Preprocessing

- Load the weather condition dataset.
- Handle missing values and perform necessary data cleaning.
- Standardize or normalize the data if required.

### 2. Classification

- Apply KNN, Decision Tree Classifier, and SVM to the preprocessed data.
- Choose appropriate hyperparameters for each classifier using techniques like cross-validation.

### 3. Evaluation

- Evaluate the classification performance using ARI and NMI metrics.
- Visualize the classification results and evaluation metrics.

### 4. Rain Prediction

- Use the classified weather conditions to predict whether it will rain.
- Implement a classification model to make the rain prediction.
- Evaluate the prediction accuracy and other relevant metrics.

## Results

Detailed analysis and plots can be found in the Jupyter Notebook.

