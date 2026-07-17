# Mobile Review ABSA

Aspect-Based Sentiment Analysis (ABSA) on a dataset of mobile-phone reviews. Unlike basic sentiment analysis, ABSA breaks each review down into aspects (e.g. `SCREEN$Quality`, `PROCESSOR$Performance`) and assigns a sentiment to each one.

**▶ View the notebook online:** [nbviewer](https://nbviewer.org/github/joystonmenezes/mobile-review-absa/blob/master/mobile-review-absa.ipynb) · [on GitHub](https://github.com/joystonmenezes/mobile-review-absa/blob/master/mobile-review-absa.ipynb)

## Approach

This is an *in-domain* use case with predefined aspect categories, so the model combines two parts:

1. **Aspect Category classifier** — maps aspect words (e.g. "retina screen") to a category
2. **Sentiment model** — computes the polarity (positive / negative / neutral) for each aspect

## Contents

- `mobile-review-absa.ipynb` — the notebook
- `Mobile_review_train_data.csv`, `Mobile_review_test_data.csv`, `Mobile_review_test_data2.csv` — datasets

## Tools

Python · pandas · scikit-learn / NLP (Jupyter Notebook)
