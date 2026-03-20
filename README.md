# MNIST Classification with Decision Trees

Classical machine learning approach for handwritten digit classification on MNIST, centered on decision trees with tuning and model comparison.

## Overview
This project flattens MNIST image tensors into feature vectors and applies tree-based models to classify digits from `0` to `9`. The notebook includes a baseline decision tree, hyperparameter tuning with `GridSearchCV`, and a stronger random forest comparison.

## Tech Stack
- Python
- Scikit-learn
- TensorFlow / Keras datasets
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Workflow
1. Load the MNIST dataset
2. Reshape `28x28` grayscale images into flat feature vectors
3. Train a baseline `DecisionTreeClassifier`
4. Evaluate using accuracy, classification report, and confusion matrix
5. Tune tree parameters with `GridSearchCV`
6. Compare performance with a `RandomForestClassifier`

## Models Used
- Decision Tree Classifier
- Tuned Decision Tree
- Random Forest Classifier

## Results
- Baseline decision tree accuracy: about `87.3%`
- Tuned decision tree accuracy: about `87.9%`
- Random forest accuracy: about `96.3%`

## Files
```text
MNIST_DataSet_Classification_Using_Decision_Tree/
├── MNIST Dataset Classification using Decision Trees 2.ipynb
├── requirements.txt
└── README.md
```

## Run Locally
```bash
pip install -r requirements.txt
jupyter notebook "MNIST Dataset Classification using Decision Trees 2.ipynb"
```

## Learning Focus
- Applying classical ML to image data
- Feature flattening for non-neural models
- Hyperparameter tuning with grid search
- Comparing interpretability and performance of tree-based classifiers
