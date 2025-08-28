
##  Project Overview
This project uses the **[AI Assistant Usage in Student Life (Synthetic) dataset](https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic)** to practice **Python data science and machine learning skills**.  
It covers **Exploratory Data Analysis (EDA)**, **visualizations**, **feature engineering**, and multiple **machine learning models**.  

The dataset simulates **10,000+ student sessions** with AI assistants, tracking usage, outcomes, and engagement patterns.  

---

##  Contents
The project is structured into six main parts:

### Part A – Basic EDA
1. Load and preview the dataset  
2. Dataset shape, column names, and datatypes  
3. Missing values check  
4. Summary statistics (`SessionLengthMin`, `TotalPrompts`)  
5. Unique value counts for categorical features  
6. Common task types and student activity analysis  

### Part B – Visualization
- Histogram of `SessionLengthMin`  
- Bar chart of sessions by `StudentLevel`  
- Countplot of `TaskType` (Seaborn)  
- Boxplot of `SessionLengthMin` by `StudentLevel`  
- Pie chart of `FinalOutcome`  
- Scatterplot (`SessionLengthMin` vs `TotalPrompts`)  
- Line chart of average `AI_AssistanceLevel` over `SessionDate`  
- Correlation heatmap (numeric features)  

### Part C – GroupBy & Aggregations
- Average session length per `TaskType`  
- Most active `Discipline`  
- AI Assistance comparison across `StudentLevel`  
- Most common outcome for graduate students  
- Median session length by outcome  

### Part D – Feature Engineering
- Extract `Year`, `Month`, `Day` from `SessionDate`  
- Label encode `StudentLevel`  
- One-hot encode `TaskType`  
- Create `PromptsPerMinute` feature  
- Bin `SessionLengthMin` into `Short`, `Medium`, `Long`  

### Part E – Machine Learning Models
- **Classification tasks:** predict `FinalOutcome`, `UsedAgain`  
- Models covered:
  - Decision Tree  
  - Logistic Regression  
  - Random Forest  
  - K-Nearest Neighbors (KNN)  
  - Naive Bayes  
  - Gradient Boosting  
  - XGBoost  

- Train-test split (80/20)  
- Evaluation: Accuracy, Confusion Matrix, Classification Report  

### Part F – Model Evaluation & Hyperparameter Tuning
- Cross-validation (Logistic Regression)  
- Hyperparameter tuning with **GridSearchCV** (Decision Tree, Random Forest)  
- Model comparisons across classifiers  

---

##  Tech Stack
- **Python** 3.x  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Visualization  
- **Scikit-learn** – ML models & evaluation  
- **XGBoost** – Gradient boosting classifier  


---

##  Acknowledgements
Dataset: [AI Assistant Usage in Student Life (Synthetic) – Kaggle](https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic)  
