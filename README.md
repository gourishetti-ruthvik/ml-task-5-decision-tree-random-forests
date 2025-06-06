# 🧠 Task 5: Decision Trees & Random Forests – Heart Disease Prediction

## Objective(AIM)

This project focuses on learning tree-based models like **Decision Trees** and **Random Forests** for classification. The dataset used is the **Heart Disease Dataset**, and the key goals include training classifiers, preventing overfitting, model evaluation, and interpreting feature importances.

---

## Tools & Libraries Used

- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- `plot_tree`
- Jupyter Notebook

---

## Project Structure

decision-tree-random-forest/   
├── data/  
│ └── heart.csv    
├── decision_tree_random_forest.ipynb  
└── README.md     


---

## Steps Followed

### 1. Load the Dataset

- Used `heart.csv` dataset.
- Checked for missing values.
- Split data into features (X) and labels (y).

### 2. Train-Test Split

- Split dataset into training (80%) and testing (20%) using `train_test_split`.

### 3. Train a Decision Tree Classifier

- Trained a `DecisionTreeClassifier`.
- Evaluated training and testing accuracy.

### 4. Visualize the Decision Tree

- Used `plot_tree()` from `sklearn.tree` to visualize the decision tree structure.

### 5. Analyze Overfitting

- Observed overfitting on the full tree.
- Controlled tree depth using `max_depth`.

### 6. Train a Random Forest Classifier

- Trained a `RandomForestClassifier` with 100 trees.
- Compared performance with decision tree.

### 7. Feature Importance

- Extracted and plotted feature importances using `RandomForestClassifier.feature_importances_`.

### 8. Cross-Validation

- Used `cross_val_score` to evaluate model stability.

### 9. Evaluation Metrics

- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## Results Summary

- Random Forest performed best on unseen data.
- Pruning helped reduce overfitting in Decision Tree.
- Top features were identified using Random Forest.

---
