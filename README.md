# Machine Learning 

## Current Topics Covered

### 1. Feature Encoding
Understanding when to use different encoding methods for categorical variables.

**Label Encoding** - Best for Ordinal categorical variables where data follows a logical order:
- Satisfaction rating: dislike, neutral, like
- Sizing: small, medium, large

**One-Hot Encoding** - Best for Nominal categorical variables where data does not follow a logical order:
- Gender: female, male
- Colors: red, blue, green

### 2. Logistic Regression
Classification algorithm for predicting categories (despite having "regression" in the name).

**Key Point:** Logistic regression is NOT a regression algorithm - it's a classification algorithm.

**Current Exercise:** Titanic survival prediction using passenger characteristics.

## Files
- `ExerciseLogisticRegression.ipynb` - Hands-on Titanic dataset exercise
- `Encoding Features` - Notes on when to use label vs one-hot encoding
- `titanic/` - Dataset folder with train.csv, test.csv, and sample submission

## Next Steps
This project will expand to cover additional machine learning algorithms and techniques.