# Performance Scoring System – Summary
This project introduces a statistical performance scoring model for evaluating store and employee performance using dynamic and distribution-aware techniques.

Key Steps:
## 1. Distribution Detection: Each of the 5 performance metrics is tested via Chi-Square to classify as Beta or Normal.

## 2. Scoring Logic:
- Beta metrics → scored via CDF percentiles.
- Normal metrics → scored via z-scores.

## 3. Weighted Aggregation: Scores are combined using business-priority weights, aligned with expert rankings.

The model ensures objective, scalable, and insightful performance evaluation tailored to business needs.

**All project details are provided in the methodology.ipynb file, along with a dashboard draft designed to enhance the readability and interpretability of the insights generated from the model.**
