# Titanic Survival Prediction using Machine Learning

Mini project - predicts whether a Titanic passenger survived or not using **supervised learning (classification)**.

## Files
| File | Description |
|---|---|
| `titanic_raw.csv` | Original Titanic dataset (891 passengers) |
| `titanic_survival_prediction.ipynb` | Complete notebook: cleaning, graphs, model training, comparison |
| `titanic_analysis.csv` | Cleaned dataset used for training |
| `model_comparison.csv` | Accuracy, precision, recall and F1-score of all models |
| `survival_predictions.csv` | Actual vs predicted result for test passengers |

## Models used
Logistic Regression, Decision Tree, Random Forest, AdaBoost (weak learner = decision stump, `max_depth=1`, 50 estimators)

The notebook also shows how `n_estimators` (and the weak learner / `max_depth`) affects the accuracy of AdaBoost, Random Forest and Decision Tree.

## Result
Random Forest performed best with **82.7% accuracy** on the test data. Logistic Regression, AdaBoost and Decision Tree each reached 79.9%.

## How to run
```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook titanic_survival_prediction.ipynb
```

## Dataset
https://github.com/datasciencedojo/datasets (titanic.csv)
