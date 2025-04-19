# Insurance-fraud-detection-using-decision-trees-random-forest-KNN-scaling-encoding-ROC-AUC
This project detects potentially fraudulent insurance claims using machine learning classifiers like Decision Trees, Random Forest, and KNN. It includes label encoding, feature scaling, and performance evaluation using ROC-AUC and F1-score to ensure accurate and reliable fraud detection.
##  Objective

To build a binary classification model that can detect whether a claim is likely to be fraudulent or legitimate based on customer and claim-related features.

---

## Tools & Techniques Used

| Task                         | Tool / Method             |
|------------------------------|---------------------------|
| Classification Models        | Decision Tree, Random Forest, K-Nearest Neighbors |
| Data Encoding                | Label Encoding            |
| Feature Scaling              | StandardScaler            |
| Evaluation Metrics           | ROC-AUC, F1 Score, Accuracy |
| Libraries                    | pandas, NumPy, scikit-learn, matplotlib, seaborn |

---

##  Workflow Summary

1. **Data Preprocessing**
   - Label encoding for categorical variables
   - Feature scaling to normalize numeric fields

2. **Modeling**
   - Trained multiple classifiers: Decision Tree, Random Forest, and KNN
   - Evaluated each using confusion matrix, accuracy, F1 Score, and ROC-AUC

3. **Performance Comparison**
   - Visualized model comparison
   - Chose the best model based on balanced performance

---

## Sample Results


| Model          | Accuracy | F1 Score | ROC-AUC |
|----------------|----------|----------|---------|
| Random Forest  | 92.1%    | 0.89     | 0.91    |
| Decision Tree  | 88.5%    | 0.84     | 0.87    |
| KNN            | 85.3%    | 0.81     | 0.84    |

---

##  Key Features

- Detects fraud with high precision and recall
- Uses classical ML algorithms for quick evaluation
- Simple yet effective preprocessing pipeline
- Evaluation with multiple performance metrics
