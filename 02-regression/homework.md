# Homework 2

## Question 1: Column with missing values

Which of `engine_displacement`, `horsepower`, `vehicle_weight`, `model_year` has missing values.

> 💡 **Answer:** `horsepower`

## Question 2: Median horsepower

Median (50th percentile) of `horsepower`.

> 💡 **Answer:** `254`

## Question 3: Fill NA with 0 vs. mean

Split (seed 42, 60/20/20) → fill missing values with 0 vs. training-set mean → train linear regression (no regularization) on each → compare validation RMSE (round to 3 decimals).

> 💡 **Answer:** `TODO` (0 / mean / equally good)

## Question 4: Regularization strength

Fill NA with 0 → train regularized linear regression for each `r` in `[0, 0.01, 0.1, 1, 5, 10, 100]` → validation RMSE (round to 4 decimals) → best `r` (smallest on ties).

> 💡 **Answer:** `TODO`

## Question 5: Seed stability

Fill NA with 0, no regularization → repeat 60/20/20 split + train + validation RMSE for seeds `0`–`9` → `np.std` of the 10 scores (round to 3 decimals).

> 💡 **Answer:** `TODO`

## Question 6: Final test RMSE

Seed 9 split → combine train + val → fill NA with 0 → train with `r=0.001` → RMSE on test set.

> 💡 **Answer:** `TODO`