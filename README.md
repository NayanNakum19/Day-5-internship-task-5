# Day-5-internship-task-5
Trained Decision Tree & Random Forest models to predict heart disease, visualized the tree, analyzed overfitting, and evaluated with cross-validation.
# 💻 Task 5: Decision Tree & Random Forest - Heart Disease

## 🧾 Objective
Train Decision Tree and Random Forest classifiers on the Heart Disease dataset to:
- Visualize decision boundaries
- Interpret feature importance
- Evaluate models with cross-validation
- Understand overfitting

## 📊 Accuracy Summary
| Model                         | Accuracy       |
|------------------------------|----------------|
| Decision Tree                | 98.54%         |
| Limited Tree (max_depth=3)   | 78.05%         |
| Random Forest                | 98.54%         |
| Cross-Validation (RF avg)    | 99.71%         |

## 📁 Files Included
- `heart.csv` — Dataset
- `task5_decision_tree_rf.ipynb` — Code notebook
- `decision_tree_plot.png` — Decision Tree visualization
- `feature_importance.png` — Feature importance bar graph

## 🛠 Libraries Used
- pandas, scikit-learn, matplotlib, seaborn

## 📌 How to Run
```bash
pip install -r requirements.txt
jupyter notebook task5_decision_tree_rf.ipynb
``
