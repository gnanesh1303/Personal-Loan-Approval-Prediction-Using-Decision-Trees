
# Personal Loan Approval Prediction using Decision Trees

This project demonstrates how to use a Decision Tree Classifier to predict whether a customer will accept a personal loan based on their financial and demographic data.

---

## Project Overview

Loan approval is a critical process in banking, where accurate and transparent decision-making is essential. In this project, we use an interpretable machine learning model — a Decision Tree — to predict loan acceptance, with a focus on explainability, fairness, and performance.

---

## Dataset Information

- **Source**: Bank Personal Loan Dataset (UCI Repository format)
- **Records**: 5000 customers
- **Target Variable**: `Personal.Loan` (1 = accepted, 0 = not accepted)
- **Features**:
  - Demographic: Age, Education, Family
  - Financial: Income, CCAvg, Mortgage
  - Behavioral: CD Account, CreditCard, Online, Securities Account

---

## Technologies Used

- Python 3
- Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

---

## Key Steps

1. **Data Loading & Cleaning**
   - Removed ID and ZIP code
   - Checked for missing values

2. **EDA & Visualizations**
   - Class distribution pie chart
   - Correlation heatmap
   - Feature importance bar plot

3. **Model Building**
   - Used `DecisionTreeClassifier` from Scikit-learn
   - Tuned tree depth based on training and testing accuracy

4. **Evaluation Metrics**
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
   - ROC Curve (AUC)
   - Precision-Recall Curve

5. **Interpretability**
   - Visualized the decision tree structure
   - Analyzed feature importance

---

## Results

- **Best Model Depth**: 4
- **Accuracy**: 98%
- **AUC Score**: 0.98
- **Average Precision Score**: 0.94
- **Key Features**: Income, Education, CCAvg, CD Account

---

## Project Structure

```
├── bankloan.csv
├── decision_tree_loan_prediction.py
├── README.md
├── accuracy_vs_depth.png
├── confusion_matrix.png
├── decision_tree_plot.png
├── roc_curve.png
├── precision_recall_curve.png
├── class_distribution_pie.png
├── feature_importance_barh.png
├── correlation_heatmap.png
```

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/loan-prediction-decisiontree.git
   ```
2. Navigate to the folder:
   ```bash
   cd loan-prediction-decisiontree
   ```
3. Run the Python script:
   ```bash
   python decision_tree_loan_prediction.py
   ```

---

## References

- Pedregosa, F. et al. (2011). *Scikit-learn: Machine Learning in Python*. JMLR.
- Molnar, C. (2022). *Interpretable Machine Learning*. Leanpub.
- Lundberg, S., & Lee, S.-I. (2017). *A Unified Approach to Interpreting Model Predictions*. NeurIPS.
- UCI Machine Learning Repository

---

## Acknowledgements

This project was developed as part of a Data Science course to demonstrate interpretable machine learning in a real-world financial scenario.

---

## Contact

**Author**: Praneet Sivakumar  
**Student ID**: 23095964  
**Email**: praneet.datasci@domain.com  
**LinkedIn**: https://www.linkedin.com/in/praneet-ds  
**GitHub**: https://github.com/Prani8/loan-prediction-decisiontree
