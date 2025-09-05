# Air Pollution Predictor Competition
**BitGrit Global Air Pollution Prediction Competition:** Predicting air pollution levels using spatial and temporal features.
**Final Model Accuracy Score:** 87.67%, within 3% of 1st place (90.59%)

**Problem & Data**
Dataset: 7,649 training samples, 2,739 test samples
(*Data will not be shown per competition guidelines)

**Feature Engineering**
Cyclical encodings for temporal patterns
Geographic transformations and interactions
Rush hour and seasonal indicators
60+ engineered features total

**Tech Stack**
Python, scikit-learn, pandas, numpy, Gradient boosting, feature engineering, cross-validation

## Results
| Model | CV Score | Leaderboard |
|-------|----------|-------------|
| V1    | 96.97%   | 87.67%     |
| V2    | 98.09%   | 87.26%     |
| V3    | 98.18%   | 86.54%     |
| V4    | 98.74%   | 85.93%     |

**Key Learning:** Higher model complexity led to worse generalization. Simpler models performed better on unseen data. Demonstrated the importance of validation strategies that account for temporal and spatial data distribution shifts.

