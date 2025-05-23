# 🏏 IPL-Match-Winner-Prediction-using-ML

This project leverages machine learning techniques to predict the outcome of Indian Premier League (IPL) matches. By analyzing historical match data, we aim to forecast the winning team based on various match-related factors such as teams, toss decision, venue, and more.

---

## 📊 Dataset Overview

The dataset includes detailed information about IPL matches and contains the following columns:

- **Season**: Year of the IPL season
- **City**: City where the match was played
- **Date**: Date of the match
- **Team1, Team2**: Competing teams
- **Toss_Winner, Toss_Decision**: Toss outcomes
- **Result**: Outcome of the match
- **DL_Applied**: Whether Duckworth-Lewis method was used
- **Winner**: Match winner
- **Win_By_Runs, Win_By_Wickets**: Margin of victory
- **Player_of_Match**: Best performing player
- **Venue**: Stadium
- **Umpires**: Match officials

---

## 🎯 Project Objective

To build machine learning models that can accurately predict the winner of a match using available pre-match data, and evaluate the best-performing model using multiple metrics.

---

## ✅ Tasks

### 1. 📥 Data Loading & Understanding
- Load dataset
- Preview records
- Identify column types and structure

### 2. 🧹 Data Cleaning
- Handle missing/null values
- Encode categorical variables
- Remove duplicates/outliers
- Document cleaning decisions

### 3. 📈 Exploratory Data Analysis (EDA)
- Visualize patterns and distributions
- Analyze team performances
- Investigate toss impacts and match outcomes

### 4. ⚙️ Data Preprocessing
- Train-test split (e.g., 80-20)
- Feature and target selection
- Normalize/scale numeric features

### 5. 🤖 Model Training
Train and compare:
- Logistic Regression
- SVM
- KNN
- Decision Trees
- Random Forest
- XGBoost

### 6. 📊 Model Evaluation
- Evaluate using Accuracy, Precision, Recall, F1-Score
- Use Confusion Matrix for interpretation

### 7. 🔍 Hyperparameter Tuning
- Grid Search or Random Search
- Tune the best model for optimal results

### 8. 🥇 Model Selection
- Compare all models
- Justify the best-performing model
- Save final model as `.pkl`

---

## 📌 Deliverables

- `📄 Documentation`: Detailed steps and insights
- `📁 Code`: Jupyter notebooks / Python scripts
- `📊 Presentation`: Summary of process and results (PowerPoint)
- `✅ Final Model`: Best-trained model in `.pkl` format

---

## 📎 PowerPoint Summary Structure

1. **Title Slide**: Project title, author, and date  
2. **Introduction**: Problem overview and objectives  
3. **Data Overview**: Dataset structure and sample  
4. **Data Cleaning**: Steps taken and techniques used  
5. **EDA**: Visualizations and key insights  
6. **Modeling**: List of models and training results  
7. **Model Comparison**: Evaluation of all models  
8. **Conclusion**: Improvements and future scope  
9. **Q&A**: Final interaction slide  

---

## 🚀 Future Improvements

- Include real-time match updates
- Integrate player-specific performance metrics
- Use ensemble stacking techniques
- Collect more recent seasons for updated insights

---

## 🧠 Technologies Used

- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Jupyter Notebook
- Matplotlib, Seaborn
- GridSearchCV
- Pickle

---

## 📫 Contact

For any questions or collaboration, feel free to reach out via GitHub or email.

