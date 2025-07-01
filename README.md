#  K-Nearest Neighbors (KNN) Classifier on Iris Dataset

This project demonstrates how to implement, evaluate, and visualize a **K-Nearest Neighbors (KNN)** classifier using the famous **Iris flower dataset**.

---

##  Project Overview

The Iris dataset contains measurements of 150 iris flowers from three different species (*Setosa*, *Versicolor*, *Virginica*).  
This project shows the full KNN workflow:
- Data loading & preprocessing
- Training & testing the model
- Finding the best **K** value
- Evaluating performance (accuracy, confusion matrix, classification report)
- Visualizing decision boundaries with a custom **purple & yellow color palette**

---

##  **Key Steps**

### 1️⃣ Load & Explore the Data
- Load `Iris.csv` using **Pandas**
- Inspect the dataset: `.head()`, `.tail()`, `.shape`, `.describe()`
- Drop the `Id` column

### 2️⃣ Feature & Target Setup
- `x` = all features except `Species`
- `y` = `Species` column

### 3️⃣ Train-Test Split
- 70% training, 30% testing split using `train_test_split`

### 4️⃣ Feature Scaling
- Standardize features with `StandardScaler` to make KNN distance-based learning effective

### 5️⃣ Train KNN Model
- Train **KNN** with `k=7` neighbors

### 6️⃣ Evaluate the Model
- Predict on test data
- Compute **confusion matrix**, **accuracy**, and **classification report**
- Experiment with `K` values from 1 to 20 to find the best value
- Plot `K` vs `Accuracy` to visualize performance

### 7️⃣ Visualize Decision Boundaries
- Use only **Petal Length** & **Petal Width** for 2D visualization
- Generate a mesh grid and predict regions
- Plot decision boundaries using a **purple & yellow** colormap with **Matplotlib**
- Overlay actual data points for comparison

---

##  **Example Output**

- **Accuracy scores** for multiple K values
- **Confusion matrix**
- **Classification report** with precision, recall, f1-score
- **Decision boundary plot** with beautiful **purple & yellow regions**

---

##  **Tech Stack**

- **Python 3.x**
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`



