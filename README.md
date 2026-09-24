

#### `NumPy-Data-Imputation / README.md`


# NumPy Data Imputation & Analytics Pipeline

A Python pipeline built with NumPy to handle missing matrix data (NaNs) through mean imputation and extract variance metrics without explicit loops.

## Key Features
* **Vectorized Imputation**: Replaces missing values dynamically using `np.nanmean` and boolean index mapping.
* **Matrix Slicing & Filtering**: Isolates project anomalies (budget vs. spend) using array masks.
* **Reproducible Pipeline**: Uses explicit random seeds for reproducible synthetic data generation.

## How to Run
```bash
python numpy_imputation.py
```
```Sample Output
Plaintext

=== NUMPY IMPUTATION PIPELINE OUTPUT ===
Calculated Column Means (Budget, Spend): [534.12 512.89]
Budget Variance:                        68412.30
Spend Variance:                         71045.12
Total Over-budget Projects Identified:  88
```
