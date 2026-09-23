# Homework 1

## Question 1: Pandas version

`pd.__version__`

> 💡 **Answer:** `3.0.6`

## Question 2: Records count

Rows in `car_fuel_efficiency_2026.csv`.

> 💡 **Answer:** `10000`

## Question 3: Fuel types

Unique values in the fuel type column.

> 💡 **Answer:** `3`

## Question 4: Missing values

Columns with at least one null.

> 💡 **Answer:** `2`

## Question 5: Max fuel efficiency (Asia)

Max fuel efficiency, filtered to Asia.

> 💡 **Answer:** `41.2`

## Question 6: Median horsepower before/after fillna

Median → mode → `fillna(mode)` → median again.

> 💡 **Answer:** `Yes, it decreased`

## Question 7: Sum of `w`

Asia subset → `vehicle_weight`, `model_year` → first 7 rows → `X` → `XTX = X.T @ X` → invert → `w = XTX_inv @ X.T @ y`.

> 💡 **Answer:** `0.369`
