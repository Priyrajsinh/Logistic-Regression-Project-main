# 🚀 Logistic Regression Project

## 🔍 Predicting Ad Clicks Using Machine Learning

This project applies **Logistic Regression** to predict whether an internet user will click on an advertisement. By analyzing key user behavior metrics like daily time spent on a site, age, area income, and internet usage, we develop a predictive model that provides valuable insights for targeted advertising strategies.

---

## 📌 Table of Contents

- [📂 Project Overview](#-project-overview)
- [📊 Dataset Information](#-dataset-information)
- [📁 Project Structure](#-project-structure)
- [📈 Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [⚙️ Data Preprocessing](#-data-preprocessing)
- [🤖 Model Development](#-model-development)
- [📝 Model Evaluation](#-model-evaluation)
- [📌 Key Visualizations](#-key-visualizations)
- [🔚 Conclusion](#-conclusion)

---

## 📂 Project Overview

🔹 **Goal:** Predict whether a user will click on an advertisement based on their behavior and demographics.
🔹 **Algorithm Used:** Logistic Regression
🔹 **Dataset:** `advertising.csv`
🔹 **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Understanding user behavior in digital marketing is crucial for optimizing advertisements. This project builds a logistic regression model to classify users based on whether they clicked on an ad, helping businesses tailor their marketing efforts effectively.

🔗 **GitHub Repository:** [Project Link](https://github.com/27abhishek27/Logistic-Regression-Project)

---

## 📊 Dataset Information

The dataset consists of multiple features related to user activity and demographics:

| Feature                      | Description                                           |
| ---------------------------- | ----------------------------------------------------- |
| **Daily Time Spent on Site** | Time (in minutes) a user spends daily on the website. |
| **Age**                      | Age of the user.                                      |
| **Area Income**              | Average income of the user's geographical area.       |
| **Daily Internet Usage**     | Time (in minutes) spent online daily.                 |
| **Ad Topic Line**            | Headline of the advertisement.                        |
| **City**                     | User's city.                                          |
| **Male**                     | Gender indicator (1 = Male, 0 = Female).              |
| **Country**                  | User's country.                                       |
| **Timestamp**                | Time when the user was shown the ad.                  |
| **Clicked on Ad**            | Target variable (1 = Clicked, 0 = Did not click).     |

---

## 📈 Exploratory Data Analysis (EDA)

Before building the model, we analyze the data to uncover patterns and relationships:

✔ **Age Distribution**: Understanding the age demographics.
✔ **Daily Time Spent vs Clicks**: Checking if more time on the site leads to higher click rates.
✔ **Income Distribution**: Analyzing income levels of users.
✔ **Daily Internet Usage vs Clicks**: Exploring the impact of internet activity on ad clicks.
✔ **Correlation Heatmap**: Identifying relationships between numerical features.

📌 **Visualizations Used:**

- ![Histogram of the Age](https://github.com/27abhishek27/Logistic-Regression-Project/blob/main/Logistic%20Regression%20Project%20Png/histogram%20of%20the%20age.png)
- ![Jointplot showing Area Income versus Age](https://github.com/27abhishek27/Logistic-Regression-Project/blob/main/Logistic%20Regression%20Project%20Png/jointplot%20showing%20area%20income%20versus%20age.png)
- ![Jointplot showing the kde distributions of Daily Time spent on site vs. Age](https://github.com/27abhishek27/Logistic-Regression-Project/blob/main/Logistic%20Regression%20Project%20Png/jointplot%20showing%20the%20kde.png)
- ![Jointplot of 'Daily Time Spent on Site' vs. 'Daily Internet Usage'](https://github.com/27abhishek27/Logistic-Regression-Project/blob/main/Logistic%20Regression%20Project%20Png/jointplot%20of%20daily%20time%20spent%20on%20site%20vs%20daily%20internet%20usage.png)
- ![Pairplot with the hue defined by the 'Clicked on Ad' column feature](https://github.com/27abhishek27/Logistic-Regression-Project/blob/main/Logistic%20Regression%20Project%20Png/pairplot%20with%20the%20hue.png)

---

## ⚙️ Data Preprocessing

Before feeding the data into the model, we perform:

🔹 **Handling Missing Values**: Checking and imputing missing values.
🔹 **Encoding Categorical Features**: Converting categorical variables into numerical form.
🔹 **Feature Scaling**: Standardizing numerical features to improve model performance.

---

## 🤖 Model Development

We implement **Logistic Regression** using `sklearn`:

1️⃣ **Data Splitting**: Splitting the dataset into training and testing sets.
2️⃣ **Model Training**: Fitting the logistic regression model to the training data.
3️⃣ **Hyperparameter Tuning**: Adjusting the regularization parameter (`C`) for optimal performance.

---

## 📝 Model Evaluation

📌 **Performance Metrics Used:**

- **Accuracy Score**: Overall correctness of predictions.
- **Confusion Matrix**: Evaluates true positives, true negatives, false positives, and false negatives.
- **Classification Report**: Shows precision, recall, and F1-score.
- **ROC Curve & AUC Score**: Measures how well the model distinguishes between classes.

---

## 🔚 Conclusion

✅ **Insights Gained:**

- Users spending more time on the site tend to have a higher probability of clicking on ads.
- Age and income play significant roles in determining ad click behavior.
- Logistic Regression provides a solid baseline for ad click prediction, which can be improved with advanced models.



