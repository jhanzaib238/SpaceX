# SpaceX
Saylani SMIT Hackathon
# SpaceX Launch Success Prediction 🚀

![Confusion Matrix](confusion_matrix.png)

Machine learning system to predict SpaceX launch outcomes with 92.7% accuracy using historical launch data and weather features.

## Features ✨

- **Temporal Analysis**: Launch year/month/hour, weekend detection
- **Hardware Metrics**: Booster reuse count, fairing recovery attempts
- **Environmental Factors**: Weather window, net precipitation
- **Advanced Preprocessing**:
  - Nested JSON handling (cores/fairings)
  - Time-based data splitting
  - Custom feature engineering pipeline

## Model Performance 🏆

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 92.7%    | 94%       | 95%    | 94%      |
| Random Forest       | 53.7%    | 54%       | 100%   | 70%      |

*Logistic Regression outperformed due to class imbalance handling*

## Installation ⚙️

```bash
git clone https://github.com/yourusername/spacex-launch-predictor.git
conda create -n spacex python=3.8
conda activate spacex
pip install -r requirements.txt
