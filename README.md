# Task 2: Exploratory Data Analysis (EDA)

## 📌 Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand data using statistics and visualizations.

## 🛠️ Tools Used
- **Pandas** → Data manipulation and summary statistics
- **Matplotlib** → Basic plotting
- **Seaborn** → Advanced statistical visualizations
- **Plotly** → Interactive charts

## 📂 Dataset
- Source: Titanic dataset (CSV format)
- Used the **cleaned dataset from Task 1** to ensure accuracy and consistency.

## 🔎 Steps Performed
1. **Data Inspection**
   - Loaded dataset and checked structure (`head()`, `info()`).
   - Verified missing values and data types.

2. **Summary Statistics**
   - Generated descriptive statistics (`mean`, `median`, `std`, etc.).
   - Compared numeric vs categorical features.

3. **Visualizations**
   - Histograms for Age and Fare distributions.
   - Boxplots to detect outliers and compare spread.
   - Pairplot to explore feature relationships.
   - Correlation matrix (heatmap) to identify linear relationships.

4. **Patterns, Trends, and Anomalies**
   - Younger passengers had higher survival rates.
   - Higher fares correlated with survival (first-class advantage).
   - Fare distribution was skewed with extreme outliers.
   - Age distribution showed anomalies (missing values, very old passengers).

5. **Feature-Level Inferences**
   - **Age**: Younger passengers more likely to survive.
   - **Fare**: Wealthier passengers had better survival chances.
   - **Pclass**: Strong survival differences across classes.
   - **Correlation**: Fare and Pclass were strongly related.

