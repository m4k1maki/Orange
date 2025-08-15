# 🚢 Supervised Classification Methods with Orange – Titanic Dataset
<img width="1011" height="583" alt="image" src="https://github.com/user-attachments/assets/35632366-4903-4f83-8abc-086f658461ca" />

##  Introduction
This project explores and compares three **supervised classification algorithms** implemented using the **Orange Data Mining** tool, applied to the **Titanic dataset**.

**Dataset**: Titanic passenger data including attributes such as Passenger Class, Sex, Age, Fare, Embarkation Port, and Survival status.  
**Goal**: Predict passenger survival (binary classification) based on their attributes.

---

##  Methods & Models
We tested and evaluated three supervised learning algorithms:

1. **k-Nearest Neighbors (kNN)**
   - Non-parametric algorithm that classifies data based on the majority class among the k nearest neighbors.
   - Key parameter: *k* (number of neighbors).

2. **Decision Tree**
   - Tree-structured model using attribute-based splitting.
   - Easy to interpret, visualizes decision-making steps.

3. **Naive Bayes**
   - Probabilistic classifier based on Bayes’ theorem with strong independence assumptions.
   - Works well with categorical features.

---

##  Workflow in Orange
1. **Data Import**: Titanic dataset loaded into Orange.
2. **Preprocessing**:
   - Handle missing values.
   - Convert categorical features to numerical.
3. **Model Training**: Applied kNN, Decision Tree, and Naive Bayes.
4. **Evaluation**:
   - Used **Test & Score** widget.
   - Compared models using metrics: Accuracy, Precision, Recall, F1-score, AUC.
5. **Visualization**:
   - Decision Tree diagrams.
   - ROC curves for each model.
   - Confusion matrices.

---

**Observation**:
- Decision Tree is highly interpretable but may overfit if not pruned.
- kNN performance depends heavily on *k* and feature scaling.
- Naive Bayes performs well with categorical data but may be limited by its independence assumption.

---

##  Conclusion
- All three algorithms can predict Titanic survival with reasonable accuracy.
- Choice of algorithm depends on the trade-off between interpretability, performance, and dataset characteristics.
- **Orange** provides an intuitive visual workflow for model building, evaluation, and comparison.

---

##  Future Work
- Test with more algorithms (e.g., Random Forest, Logistic Regression, SVM).
- Apply feature engineering for better accuracy.
- Use hyperparameter tuning to optimize each model.

---

##  Tools & Environment
- **Orange Data Mining** (visual programming interface).
- Titanic dataset (CSV format).
- OS: Windows 10.
