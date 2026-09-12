# Essay Score Prediction with Supervised Machine Learning

Ranked **4th place out of 253 participants** in the [HWU F78DS January Semester 2025 Kaggle Competition](https://www.kaggle.com/competitions/hwu-f78ds-january-semester-2025).

A Year 2 data science project applying supervised machine learning techniques to predict essay scores from extracted textual features.

| Detail | Information |
|---|---|
| Program | Bachelor of Science (Hons) in Statistical Data Science |
| Course | F78DS Data Science Life Cycle |
| Year and Semester | Year 2, Semester 2 |
| Date | March 2025 - April 2025 |
| Competition | [HWU F78DS January Semester 2025](https://www.kaggle.com/competitions/hwu-f78ds-january-semester-2025) |
| Language | Python |
| Tool | Jupyter Notebook |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| Competition Result | 4th / 253 Participants |
| Marks Obtained | 28.33/30 |

## About the Project

Participated in the HWU F78DS January Semester 2025 in-course machine learning competition, where the objective was to predict essay scores using extracted textual features.

The task was formulated as a multi-class classification problem, where numerical features extracted from essays were used to predict scores ranging from 1 to 6.

The project followed the data science lifecycle, including exploratory data analysis, feature engineering, preprocessing, supervised learning and model evaluation using the Quadratic Weighted Kappa (QWK) metric.

## What I Did

- Explored essay feature data using descriptive statistics and visualisations.
- Analysed relationships between essay characteristics and essay scores.
- Performed feature engineering to improve model inputs.
- Applied feature scaling using Quantile Transformer.
- Built supervised classification models using Gaussian Naive Bayes and Random Forest.
- Evaluated model performance using accuracy, F1-score, confusion matrices and Quadratic Weighted Kappa.
- Generated prediction outputs for Kaggle competition submission.

## Results

### Feature Distribution Analysis

![Feature distributions](plots/feature-distributions.png)

Exploratory data analysis was performed to understand the distribution and variation of extracted essay features. Different features showed different scales and distributions, highlighting the importance of preprocessing before applying machine learning models.

### Feature Correlation Analysis

![Feature correlation heatmap](plots/feature-correlation-heatmap.png)

Correlation analysis was used to investigate relationships between essay features and scores. Features related to essay length, vocabulary usage and writing characteristics showed stronger relationships with essay scores.

### Model Performance Comparison

![Model comparison](plots/model-comparison.png)

Two supervised classification models were evaluated:

- Gaussian Naive Bayes achieved a QWK score of **0.7208**.
- Random Forest achieved a higher QWK score of **0.7448**.

Random Forest demonstrated better overall performance and was selected as the stronger-performing model.

### Gaussian Naive Bayes Confusion Matrix

![Naive Bayes confusion matrix](plots/naive-bayes-confusion-matrix.png)

The confusion matrix shows the classification performance of Gaussian Naive Bayes across the six essay score categories.

### Random Forest Confusion Matrix

![Random Forest confusion matrix](plots/random-forest-confusion-matrix.png)

The Random Forest model demonstrated improved classification performance compared with Gaussian Naive Bayes across the essay score categories.

## Competition Outcome

The final model achieved:

**4th Place / 253 Participants**

in the [HWU F78DS January Semester 2025 Kaggle Competition](https://www.kaggle.com/competitions/hwu-f78ds-january-semester-2025).

The competition used **Quadratic Weighted Kappa (QWK)** as the evaluation metric. QWK measures agreement between predicted and actual essay scores while considering the difference between incorrect predictions.

## Skills Demonstrated

- Exploratory data analysis.
- Feature engineering and preprocessing.
- Multi-class classification.
- Supervised machine learning.
- Model evaluation and comparison.
- Python programming with Scikit-learn.
- Data visualisation using Matplotlib and Seaborn.
- Kaggle competition workflow.

## Dataset

The dataset was provided through the HWU F78DS January Semester 2025 Kaggle competition.

The essay dataset contains extracted numerical features including:

- Essay length features (characters, words and sentences).
- Punctuation usage.
- Average word length.
- Part-of-speech features.
- Prompt-related word features.
- Synonym and vocabulary-related features.
- Essay score labels ranging from 1 to 6.

Included files:

- `Essay-Features.csv`
- `Essay-Features-Submission.csv`
- `Kaggle Submission File.csv`

## Availability

The repository contains the datasets, selected visualisations and an analysis summary.

The full coursework notebook and submission files are kept private but can be requested by contacting me at: 29natasha.sj@gmail.com

---

[Back to Degree Projects](../README.md)
