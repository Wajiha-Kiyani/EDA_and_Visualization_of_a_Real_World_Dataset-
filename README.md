# **EDA and Visualization of the Titanic Dataset**
## **Project Overview**
This project performs **Exploratory Data Analysis (EDA) and Visualization** on the **Titanic Dataset**. The goal is to analyze the dataset, handle missing values and outliers, and visualize key patterns using **Pandas, Matplotlib and Seaborn**.
## **Contents**
1. **Dataset Loading** – Load the Titanic dataset using Pandas.
2. **Data Cleaning** – Handle missing values, remove duplicates, and detect outliers.
3. **Data Visualization** – Generate bar charts, histograms, and a correlation heatmap.
4. **Summary Insights** – Document key findings from the analysis.
## **Installation & Requirements**
Make sure you have **Python** installed along with the required libraries. You can install the dependencies using:
```bash
pip install pandas numpy matplotlib seaborn
```
## **How to Run the Script**
1. Clone this repository or download the script.
2. Place the **titanic_dataset.csv** file in the same directory as the script.
3. Run the script.

4. The script will output:
   - Basic dataset info and first few rows.
   - Processed dataset after cleaning.
   - Visualizations including bar charts, histograms, and a correlation heatmap.

## **Expected Output**
- **Bar charts** for categorical variables (`Sex`, `Pclass`, `Embarked`).
- **Histograms** showing distributions of numeric variables (`Age`, `Fare`, `SibSp`, `Parch`).
- **A correlation heatmap** for numeric features.
- **Summary insights** explaining key patterns in the data.

## **Summary Insights**
- **Females and first-class passengers had higher survival rates.**
- **The majority of passengers were from the lower class.**
- **Fare values had outliers, which were removed using the IQR method.**
- **There is a strong correlation between Pclass and Fare, indicating socio-economic differences.**


---
📌 **Note:** If you encounter any issues, ensure that the dataset is correctly placed and dependencies are installed.
