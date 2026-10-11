# Homework 3

## Question 1: Mode of `industry`

Fill missing values (categorical → `'NA'`, numerical → `0.0`) → most frequent value of `industry`.
> 💡 **Answer:** `technology`

## Question 2: Biggest correlation

Correlation matrix of numerical features → pair with the biggest correlation among `interaction_count`/`lead_score`, `number_of_courses_viewed`/`lead_score`, `number_of_courses_viewed`/`interaction_count`, `annual_income`/`interaction_count`.
> 💡 **Answer:** `interaction_count`/`lead_score`

## Question 3: Mutual information

Split (seed 42, 60/20/20, drop `converted`) → mutual information between `converted` and each categorical variable on the training set (round to 2 decimals) → highest score.
> 💡 **Answer:** `lead_source`

## Question 4: Logistic regression accuracy

One-hot encode categoricals → train `LogisticRegression(solver='liblinear', C=1.0, max_iter=1000, random_state=42)` → validation accuracy (round to 2 decimals).
> 💡 **Answer:** `TODO` (0.55 / 0.65 / 0.75 / 0.85)

## Question 5: Feature elimination

Same features and params as Q4 (no rounding) → drop each feature in turn and retrain → difference between original and reduced accuracy → smallest difference (can be negative).
> 💡 **Answer:** `TODO` (`lead_source` / `number_of_courses_viewed` / `interaction_count`)

## Question 6: Regularization strength

All features as in Q4 → train for each `C` in `[0.000001, 0.00001, 0.0001, 0.001]` → validation accuracy (round to 3 decimals) → best `C` (smallest on ties).
> 💡 **Answer:** `TODO`