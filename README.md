# Task 2: Exploratory Data Analysis on Titanic Datase

---

## 🎯 Objective
- Perform detailed EDA on the Titanic Dataset.
- Analyze feature distributions and summary statistics.
- Handle missing data effectively.
- Visualize outliers and skewness.
- Explore correlations between features.
- Make basic feature-level inferences from visualizations.

---

## 📂 Dataset Details
- Dataset Name: `Titanic-Dataset.csv`
- Dataset Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- This dataset contains passenger information including survival status, class, gender, age, fare, and other travel details.

---

## 🛠️ Tools and Libraries Used
- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly

---

## ✅ Key Steps Performed
1. Loaded the dataset `Titanic-Dataset.csv` into Google Colab.
2. Displayed the dataset’s structure, types, and summary statistics.
3. Identified and handled missing values in the `Age` and `Embarked` columns.
4. Visualized data distributions using histograms.
5. Detected outliers using boxplots.
6. Created a correlation matrix using numeric features only.
7. Explored feature relationships using pairplots.
8. Visualized categorical variables using countplots.
9. Checked skewness for key numerical features.

---

## 🔍 Key Findings
- The dataset had missing values in the `Age` and `Embarked` columns, which were handled using median and mode imputation.
- Outliers were identified in the `Fare` and `Age` columns.
- The `Age` and `Fare` distributions were right-skewed.
- Female passengers and first-class passengers had higher survival rates.
- No significant multicollinearity was found between the numeric features.

---

## 📦 Files Included
- `Task2_EDA.ipynb` – Google Colab notebook with full EDA code and visualizations.
- `Titanic-Dataset.csv` – Dataset file used for the analysis.
- `README.md` – Detailed description of the project and steps followed.

---

## 💻 How to Run
1. Open the Google Colab notebook.
2. Upload `Titanic-Dataset.csv` to the Colab environment.
3. Run the code cells step-by-step to perform the complete EDA.

---

## ✨ Conclusion
This EDA provided valuable insights into the Titanic dataset and demonstrated the use of key data analysis techniques such as handling missing values, detecting outliers, analyzing correlations, and visualizing categorical and numerical data.


