# Iris Flower Classification Project

## Project Description
This project implements a machine learning model to classify iris flowers into three species (setosa, versicolor, virginica) based on their sepal and petal measurements. The classic Iris dataset is used, containing 150 samples with four features each.

## Dataset Information
- **Source**: Built-in scikit-learn dataset
- **Features**:
  - sepal length (cm)
  - sepal width (cm)
  - petal length (cm)
  - petal width (cm)
- **Target**: Species classification (3 classes)
- **Samples**: 150 (50 per class)

## Requirements
- Python 3.6+
- Required packages:
pandas
numpy
scikit-learn
matplotlib
seaborn


## Installation
1. Clone the repository
git clone https://github.com/yourusername/iris-classification.git

2. Install dependencies
   pip install -r requirements.txt

## Usage
Run the main script:
python iris_classification.py


The script will:
1. Load and preprocess the Iris dataset
2. Train a Random Forest classifier
3. Evaluate model performance
4. Make sample predictions

## Results
The model achieves approximately 93-97% accuracy on test data. Sample output:

Accuracy: 0.95
Classification report:
precision recall f1-score support
setosa 1.00 1.00 1.00 10
versicolor 0.90 0.90 0.90 10
virginica 0.90 0.90 0.90 10


## License
MIT License - Free for academic and commercial use
