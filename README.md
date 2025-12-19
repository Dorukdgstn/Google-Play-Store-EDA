# Google Play Store Exploratory Data Analysis (EDA)

This project provides a comprehensive exploratory data analysis and data cleaning of the Google Play Store dataset. The main goal is to transform messy, real-world data into a clean format suitable for analysis and to uncover insights about app categories, ratings, and market trends.

## 🚀 Key Features and Data Cleaning Steps

- **Data Wrangling:** Processed columns like `Installs`, `Price`, and `Reviews` by removing special characters ($, +, ,) and converting them into numerical types.
- **Handling Inconsistencies:** Identified and removed non-numeric noise (e.g., the "3.0M" entry in the Reviews column).
- **Feature Engineering:** - Extracted **Day, Month, and Year** from the `Last Updated` column using `pd.to_datetime`.
  - Standardized the `Size` column by converting "M" (Megabytes) and "k" (Kilobytes) into a uniform numerical format.
- **Removing Duplicates:** Cleaned the dataset by dropping duplicate app entries to ensure analysis accuracy.
- **Visualizations:** Performed Univariate and Bivariate analysis using **Seaborn** and **Matplotlib**.

## 📊 Key Insights
- Identified top app categories by total installations.
- Visualized the distribution of ratings and content ratings across the store.
- Compared the top 5 most installed apps across major categories like Games and Communication.

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy)
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Google Colab / Jupyter Notebook
