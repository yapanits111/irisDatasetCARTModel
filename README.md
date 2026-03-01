# Iris Dataset CART Model

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yapanits111/irisDatasetCARTModel/blob/main/irisCART.ipynb)

A Classification and Regression Tree (CART) model implementation for classifying Iris flower species using the classic Iris dataset.

## Overview

This project demonstrates the use of a Decision Tree Classifier (CART algorithm) to classify Iris flowers into three species: Setosa, Versicolor, and Virginica based on their sepal and petal measurements.

## Dataset

The project uses the **Iris.csv** dataset containing:
- **150 samples** of iris flowers
- **4 features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **3 target classes**: Iris-setosa, Iris-versicolor, Iris-virginica

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

Install dependencies:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Project Structure

```
irisDatasetCARTModel/
├── irisCART.ipynb    # Main Jupyter notebook with CART implementation
├── Iris.csv          # Dataset file
└── README.md         # Project documentation
```

## Methodology

1. **Data Loading & Exploration**: Load the Iris dataset and check for missing values
2. **Data Preprocessing**: Remove the Id column and prepare features (X) and target (y)
3. **Train-Test Split**: Split data into 80% training and 20% testing sets with stratification
4. **Model Training**: Train a Decision Tree Classifier using the Gini impurity criterion
5. **Evaluation**: Generate classification report, confusion matrix, and accuracy score
6. **Visualization**: Display confusion matrix heatmap and decision tree structure

## Usage

1. Clone the repository
2. Ensure `Iris.csv` is in the same directory as the notebook
3. Run the Jupyter notebook `irisCART.ipynb`

Or click the "Open in Colab" badge above to run directly in Google Colab.

## Output

The notebook produces:
- Dataset statistics and class distribution
- Classification report with precision, recall, and F1-score
- Confusion matrix (numeric and heatmap visualization)
- Accuracy score
- Visual representation of the trained decision tree

## License

This project is open source and available for educational purposes.
" 

