# Bank Customer Churn Prediction

This project aims to analyze customer churn in a banking dataset and identify key factors that influence a customer's decision to leave the bank. It includes data preprocessing, statistical analysis using Chi-squared tests, and data visualization to support business insights.

## Dataset

- **Source**: [Binary Classification with a Bank Churn Dataset | Kaggle](https://www.kaggle.com/competitions/playground-series-s4e1/data)
- **File**: `train.csv`
- **Total records**: 165034 customers - 14 columns
- **Target variable**: `Exited` (1 = customer has left, 0 = still active)

---

## Methods & Tools

- **Python**
- **Google Colab + Jupyter Notebook**
- **Libraries**:
  - `pandas`, `numpy` for data processing
  - `matplotlib`, `seaborn`, `plotly` for visualization
  - `scipy.stats` for Chi-squared test
  - `wordcloud` for name frequency visualization

---

## Statistical Analysis

We applied the **Chi-squared test of independence** to determine which categorical features are significantly related to customer churn.

### Hypotheses:
- **H0**: The feature is independent of churn
- **H1**: The feature is associated with churn

A p-value < 0.05 indicates statistical significance.

---

## Key Findings

- `NumOfProducts` and `IsActiveMember` are the most significant predictors of churn.
- `Geography` and `Gender` also show correlation.
- `HasCrCard` has a weak association with churn.
- `Surname` is not useful due to high cardinality.

---

## Visualization Highlights

- Violin plots show churn distribution by age and number of products.
- WordCloud reveals the most common surnames.
- Chi-squared test results are summarized in a ranked table.

---

## Future Work

- Build predictive models using Logistic Regression or Decision Trees.
- Perform feature engineering for numerical attributes.
- Implement customer retention strategies based on insights.

---

## 📬 Contact
For any inquiries or contributions, feel free to reach out:

- **Email:** nguyencaodien2003@gmail.com
- **GitHub:** [CaoDien2003](https://github.com/YourGitHubUsername)
- **LinkedIn:** [Điền Cao](https://www.linkedin.com/in/nguyencaodien/)

