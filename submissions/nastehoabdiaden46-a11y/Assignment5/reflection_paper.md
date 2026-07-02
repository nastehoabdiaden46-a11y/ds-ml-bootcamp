# Assignment Five – Part C: Reflection Paper

## What Did You Implement?

In this assignment, I reproduced the Lesson 5 preprocessing pipeline and implemented three classification models for loan approval prediction. I cleaned and prepared the loan dataset by removing currency symbols, correcting category inconsistencies, handling missing values, removing duplicate rows, capping outliers, encoding categorical values, and creating additional features.

After preprocessing, I trained three machine learning models:

- Logistic Regression
- Random Forest
- Decision Tree

Logistic Regression and Random Forest were implemented based on the lesson materials, while Decision Tree was selected as an additional classification algorithm through research.

---

## Comparison of Models

The predictions produced by the three models were slightly different during the sanity check because each algorithm uses different methods to learn patterns from the data.

Logistic Regression predicts outcomes using probabilities and linear relationships between variables.

Random Forest predicts by combining many decision trees and using majority voting.

Decision Tree predicts outcomes using branching structures and conditional rules.

Among the three models, Random Forest generated more realistic predictions because it combines multiple trees instead of relying on a single model.

---

## Understanding Random Forest

Random Forest is an ensemble classification algorithm that combines multiple decision trees to improve prediction performance.

Instead of using one decision tree, the algorithm creates several trees from random subsets of data. Each tree independently predicts a result.

The final prediction is selected through majority voting.

For example:

- Tree 1 → Approved
- Tree 2 → Approved
- Tree 3 → Rejected

Final prediction:

Approved

Random Forest improves prediction accuracy and reduces overfitting problems.

---

## Other Algorithm (Decision Tree)

The additional algorithm selected for this assignment was Decision Tree.

Decision Tree was chosen because it is easy to understand and suitable for loan approval prediction problems.

The model creates decisions based on features such as:

- Income
- Credit Score
- Loan Amount
- Employment Years

### Advantage

Easy to understand and visualize.

### Limitation

Can overfit training data.

Compared to Logistic Regression and Random Forest, Decision Tree performed reasonably well but Random Forest generally achieved stronger performance.

---

## Metrics Discussion

Random Forest achieved the strongest overall performance based on:

- Accuracy
- Precision
- Recall
- F1-Score

Higher Accuracy means the model correctly predicts more observations.

Higher Precision indicates fewer false positive predictions.

Higher Recall shows better identification of positive cases.

Higher F1-Score represents a balance between Precision and Recall.

These metrics indicate that Random Forest provides reliable prediction performance.

---

## Findings

Based on the results obtained from this assignment, I would select Random Forest for loan approval prediction.

Random Forest is effective because it reduces overfitting and captures complex relationships among variables better than individual models.

Loan approval decisions depend on multiple factors including income, credit score, loan amount, and employment history. Random Forest can learn these relationships more effectively.

Overall, this assignment improved my understanding of:

- Data preprocessing
- Classification algorithms
- Performance metrics
- Model comparison
- Machine learning prediction techniques