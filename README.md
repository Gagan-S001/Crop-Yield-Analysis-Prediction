# 🌾 Crop Yield Analysis and Prediction

An end-to-end Data Analytics and Machine Learning project focused on analyzing agricultural data, identifying factors influencing crop yield, and predicting crop productivity using Python and statistical techniques.

## 🎯 Project Objectives

- Analyze agricultural data to identify crop yield patterns and trends.
- Perform Exploratory Data Analysis (EDA) to understand relationships between agricultural variables.
- Identify key factors influencing crop yield.
- Apply K-Means clustering to segment agricultural data.
- Perform statistical analysis to evaluate differences in crop yield.
- Develop and evaluate machine learning regression models for yield prediction.

## 📊 Dataset Overview

- **Total Records:** 2,000
- **Total Variables:** 14
- **Target Variable:** Yield (tons per hectare)

### Dataset Features

- Crop Type
- Region
- Soil Type
- Rainfall
- Temperature
- Humidity
- Soil pH Level
- Nitrogen
- Phosphorus
- Potassium
- Irrigation Days
- Fertilizer Usage
- Pesticide Usage
- Crop Yield

## 🛠️ Technologies & Libraries

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Statistical Analysis:** SciPy
- **Environment:** Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Cleaning and Preprocessing
- Checked missing values and duplicate records.
- Examined data types and data distributions.
- Identified potential outliers using the IQR method.
- Prepared categorical and numerical variables for analysis.

### 2. Exploratory Data Analysis (EDA)
- Analyzed crop yield distributions.
- Examined yield patterns across crop types, regions, and soil types.
- Performed correlation analysis to identify relationships between features and crop yield.
- Visualized key agricultural trends and patterns.

### 3. Statistical Analysis
- Applied Pearson correlation to evaluate relationships between numerical variables and crop yield.
- Used ANOVA to examine differences in average yield across clusters.

### 4. Clustering Analysis
- Applied K-Means clustering to segment agricultural observations into 4 clusters.
- Used PCA for dimensionality reduction and cluster visualization.
- Compared average crop yield across different clusters.

### 5. Machine Learning Models
Developed and evaluated the following regression models:

- Random Forest Regressor
- Gradient Boosting Regressor

Applied:
- GridSearchCV for hyperparameter tuning.
- 5-Fold Cross-Validation for model evaluation.
- Feature Importance Analysis to identify influential variables.

## 📈 Key Findings

- Dataset contained **2,000 records across 14 variables**.
- No missing values or duplicate records were identified.
- Irrigation Days showed the strongest observed correlation with crop yield (**0.4558**).
- Rainfall showed a positive correlation with crop yield (**0.3198**).
- K-Means identified **4 distinct clusters**.
- The highest-performing cluster achieved an average yield of **2.558 tons/hectare**.
- ANOVA indicated statistically significant differences in average yield across clusters (**p < 0.001**).
- The top influential features included Crop Type, Irrigation Days, Rainfall, Nitrogen, and Potassium.

## 🤖 Model Performance

The regression models were evaluated using R² and RMSE.

| Model | Test R² | Test RMSE |
|---|---:|---:|
| Random Forest Regressor | 81.49% | 0.5863 |
| Gradient Boosting Regressor | **89.58%** | **0.4400** |

**Best Performing Model:** Gradient Boosting Regressor

- Test R²: **89.58%**
- Test RMSE: **0.4400**
- Test MAE: **0.2945**

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
```

### Step 3: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Run the Notebook

Open the project notebook and execute the cells sequentially.

Ensure that `Crop_Data.csv` is available in the project directory.

## 📁 Project Structure

```text
Crop-Yield-Analysis/
│
├── Crop_Data.csv
├── Crop Field_Code_nb.ipynb
├── Crop_Yield_Report.docx
├── Crop_Yield_PPT.pptx
└── README.md
```

## 🔮 Future Improvements

- Incorporate additional historical agricultural datasets.
- Explore advanced feature selection techniques.
- Evaluate additional regression algorithms.
- Improve model generalization using external datasets.
- Develop an interactive dashboard for agricultural insights.

## 👨‍💻 Author

**Gagan**

Data Analyst | Python | SQL | Excel | Power BI | Machine Learning

