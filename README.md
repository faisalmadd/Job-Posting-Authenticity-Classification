# Real or Fake Job Posting Classification
A project for 6006CEM Machine Learning and Related Applications coursework.


Dataset employed for this project:

Real / Fake Job Posting Prediction by Shivam Bansal (Kaggle)

Link: https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction/data

# Methodology
- Firstly the Exploratory Data Analysis (EDA) was carried out to discover the patterns available in the dataset.
- Then the data cleaning process was carried out to remove unrelated columns and join the text from the columns.
- Third step was using WordCloud and SpaCY to find out which keywords are the most common in the real/fraudulent job postings.
- Then the feature extraction was carried out using the TfidfVectorizer.
- Last but not least the Logistic Regression, Random Forest, and XGBoost models were trained and evaluated.
