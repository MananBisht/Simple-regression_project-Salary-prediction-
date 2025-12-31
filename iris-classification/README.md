#  Iris Flower Classification using KNN

This project is my first hands-on Machine Learning classification project.  
The goal is to classify Iris flowers into different species based on their physical measurements.

---

##  Problem Statement

Given the measurements of an Iris flower:
- Sepal length
- Sepal width
- Petal length
- Petal width  

Predict the **species of the flower**:
- Setosa
- Versicolor
- Virginica

This is a **supervised classification problem**.

---

##  Machine Learning Concepts Used

- Supervised Learning
- Classification
- Train / Test Split
- K-Nearest Neighbors (KNN)
- Model Evaluation using Accuracy
- Overfitting vs Underfitting
- Hyperparameter tuning (`n_neighbors`)
- Mapping model outputs to human-readable labels

---

##  Tools & Libraries

- Python
- Scikit-learn
- VS Code
- Git & GitHub

---

##  Dataset

The project uses the **Iris dataset**, which is a built-in dataset provided by Scikit-learn.

- Total samples: 150
- Features: 4 numerical features
- Classes: 3 flower species

The dataset is clean and requires no missing value handling, making it ideal for learning ML fundamentals.

---

##  Project Workflow

1. Load the Iris dataset
2. Separate features (X) and labels (y)
3. Split data into training and testing sets
4. Train a KNN classifier
5. Make predictions on unseen test data
6. Evaluate model performance using accuracy
7. Experiment with different values of `k` to observe overfitting and underfitting
8. Convert model predictions into flower names

---

##  Results

- The model achieves **high accuracy** on the test set.
- Changing the number of neighbors (`k`) demonstrates:
  - Small `k` → risk of overfitting
  - Large `k` → risk of underfitting
  - Moderate `k` → better generalization

This project helped me understand how model complexity affects performance.

---

##  Key Learnings

- Machine Learning models learn patterns from training data and must be evaluated on unseen data
- Accuracy alone can be misleading on simple datasets
- Hyperparameters play a crucial role in model behavior
- Clean workflow matters more than complex algorithms

---

##📎 Future Improvements

- Add confusion matrix and classification report
- Try other classifiers (Logistic Regression, Decision Tree)
- Visualize decision boundaries

---

##  Author

**Manan**  
Machine Learning learner building projects step by step.
