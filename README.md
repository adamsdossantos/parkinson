# SVM Machine Learning Project - Parkinson Desease Prediction

## 1. Project Overview

This project implements a Support Vector Machine (SVM) model for predict Parkinson Desease. SVM is a supervised learning algorithm used for classification and regression analysis. It aims to find the optimal hyperplane that maximizes the margin between different classes.


## 2. Dataset Source

https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set

## 3. Features
- **Data Preprocessing**:  cleaning, normalization, and splitting into training and testing sets.
- **Model Training**: Training an SVM model using scikit-learn.
- **Model Evaluation**: Evaluating the performance of the model using metrics such as accuracy, precision, recall, and F1-score.


## 4. Project Structure
    ├── parkinson_desease.csv       # Dataset file 
    ├── parkinson_detection.ipynb   # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/parkinson.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook parkinson_detection.ipynb
```
## 6. Usage

Open the parkinson.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the train.csv and perform necessary preprocessing.
- **Model Training**: Train an SVM model with adjustable hyperparameters.
- **Model Evaluation**: Evaluate the model using accuracy, precision, recall, and F1-score


## 7. Results in Test
| Metric    |  Value |
|-----------|--------|
| Accuracy  |  90%   |
| Precision |  94%   |
| Recall    |  71%   |
| F1 Score  |  77%   |

## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.







