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
Logistic Regression, AdaBoost

## Result
Both models reached **79.9% accuracy** on the test data. Logistic Regression was selected as the final model because of its slightly higher F1-score (0.75 vs 0.74).

## How to run
```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook titanic_survival_prediction.ipynb
```

## Dataset
https://github.com/datasciencedojo/datasets (titanic.csv)
