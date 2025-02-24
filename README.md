# **Exploratory Data Analysis (EDA) on Red Wine Quality 🍷**  

## **Project Overview**  
This project performs **Exploratory Data Analysis (EDA)** on the **Red Wine Quality** dataset using **Pandas, Seaborn, and Matplotlib**. The dataset contains **physicochemical properties** of different red wine samples and their corresponding **quality scores** (rated between 0-10).  

By analyzing this dataset, we aim to uncover key patterns, correlations, and insights that influence wine quality.  

## **Dataset Information**  
- **Dataset Name**: `winequality-red.csv`  
- **Number of Features**: 12  
- **Target Variable**: `quality` (Wine quality score)  
- **Features**:
  - `fixed acidity`, `volatile acidity`, `citric acid`
  - `residual sugar`, `chlorides`, `free sulfur dioxide`, `total sulfur dioxide`
  - `density`, `pH`, `sulphates`, `alcohol`

## **Key Questions Explored in EDA**  
1. **What factors influence red wine quality the most?**  
2. **Which features are highly correlated with wine quality?**  
3. **Are there any outliers or missing values in the dataset?**  
4. **How are different chemical properties distributed?**  
5. **How does alcohol content relate to wine quality?**  

## **EDA Process & Insights**  
### **Data Cleaning & Preprocessing**  
  Checked for missing values and data types.  
  Standardized column names.  
  Identified potential outliers in the dataset.  

### **Univariate Analysis**  
  Plotted histograms and boxplots for feature distributions.  
  Found that **alcohol and volatile acidity** show distinct patterns in quality levels.  

### **Bivariate & Correlation Analysis**  
  Used a **heatmap** to visualize correlations:  
  - **Alcohol has a strong positive correlation** with quality.  
  - **Volatile acidity negatively impacts wine quality**.  
  Identified multicollinearity among certain features.  

### **Data Visualization**  
  **Scatter plots & pair plots** to explore feature interactions.  
  **Boxplots** to analyze quality distribution.  
  **Correlation heatmap** for feature relationships.  

## **Key Findings**  
  **Alcohol** has the **strongest positive impact** on wine quality.  
  **High volatile acidity** negatively affects wine quality.  
  **Total sulfur dioxide** has a moderate correlation with wine quality.  
  **Most wines have a quality rating between 5 and 7.**  

**Dataset Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)  
