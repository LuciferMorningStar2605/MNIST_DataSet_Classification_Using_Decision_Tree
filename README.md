# 🔢 MNIST Handwritten Digit Classification using Decision Trees

This project implements a **Decision Tree Classifier** to recognize handwritten digits from the **MNIST dataset**.  
The MNIST dataset is one of the most widely used benchmarks in machine learning, containing grayscale images of digits (0–9).  
This project demonstrates how classical machine learning models, such as decision trees, can be applied to image classification tasks.  

---

## 📌 Project Overview

- Dataset: **MNIST Handwritten Digits** (70,000 images: 60,000 training, 10,000 testing)  
- Model: **Decision Tree Classifier (Scikit-Learn)**  
- Goal: Classify digits (0–9) with interpretable ML models  
- Key Features:
  - Data loading and preprocessing  
  - Training and evaluating a Decision Tree model  
  - Visualization of decision boundaries, classification reports, and confusion matrix  

---

## 📂 Dataset

- **Source**: [MNIST Dataset](http://yann.lecun.com/exdb/mnist/) (also available via `keras.datasets` and `sklearn.datasets`)  
- **Images**: 28 × 28 grayscale handwritten digits  
- **Preprocessing**:
  - Flattened images into 784-dimensional vectors (28×28)  
  - Normalized pixel values (0–255 range scaled to 0–1)  

---

## ⚙️ Methodology & Workflow

1. **Data Loading**
   - Imported MNIST dataset  
   - Split into training and test sets  

2. **Preprocessing**
   - Flattened 28×28 images into 1D arrays  
   - Scaled values to improve performance  

3. **Model Training**
   - Used `DecisionTreeClassifier` from Scikit-Learn  
   - Tuned hyperparameters like `max_depth`, `criterion` (`gini`/`entropy`)  

4. **Evaluation**
   - Calculated model accuracy on test set  
   - Generated confusion matrix & classification report  
   - Visualized sample predictions  

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries:**
  - `numpy`, `pandas` – Data handling  
  - `matplotlib`, `seaborn` – Visualization  
  - `scikit-learn` – Decision Tree, metrics, preprocessing  

---

## 🚀 Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/mnist-decision-tree.git
cd mnist-decision-tree
