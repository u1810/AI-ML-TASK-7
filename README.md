# AI-ML-TASK-7
# AI & ML Internship Task 7: Support Vector Machines (SVM)

## Objective
Implement and evaluate Support Vector Machines (SVM) for both linear and non-linear (RBF kernel) classification using the Breast Cancer dataset. Visualize decision boundaries and tune hyperparameters for optimal performance.

---

##  Dataset
- **Dataset Used:** Breast Cancer Wisconsin Dataset
- **Target Variable:** `diagnosis` (Malignant = 1, Benign = 0)

---

##  Tools & Libraries
- Python (Google Colab)
- NumPy
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

##  Tasks Performed

1. Loaded and preprocessed the dataset.
2. Encoded diagnosis labels and scaled features.
3. Trained two SVM models:
   - Linear Kernel
   - RBF Kernel
4. Visualized decision boundaries (using 2D features).
5. Tuned `C` and `gamma` using GridSearchCV.
6. Evaluated models with accuracy, confusion matrix & classification report.
7. Performed cross-validation to check model robustness.

---

##  Results
- **Best Kernel:** RBF (non-linear)
- **Best Parameters:** Tuned using GridSearchCV
- **Accuracy:** ~97–99% (based on test and cross-validation)

---

##  Visualizations
- 2D decision boundaries for both Linear and RBF kernels.
- Confusion matrix and metrics printed in console.

---

## File Structure
├── breast-cancer.csv
├── aiml-task7.ipynb
└── README.md

---

##  Conclusion
SVMs proved to be highly effective for binary classification of breast cancer data. With proper feature scaling and parameter tuning, both linear and non-linear kernels showed high accuracy and generalization capability.


