# **Gender Bias in Professor Ratings**  

## 📌 Project Overview  
This project investigates potential gender bias in professor ratings using statistical analysis and machine learning models. Through hypothesis testing, regression modeling, and data visualization, we analyze student evaluations to determine if male professors receive systematically higher ratings than female professors.  

## 🔍 Key Analyses & Methodologies  
- **Statistical Testing:** Conducted **permutation tests, Mann-Whitney U tests, and Cohen’s d effect size calculations** to assess gender-based disparities.  
- **Machine Learning Models:** Developed **Linear Regression and Logistic Regression models**, optimizing features using **Variance Inflation Factor (VIF) analysis** and handling imbalanced data with **SMOTE**.  
- **Feature Engineering & Preprocessing:** Standardized numerical features with **StandardScaler**, removed multicollinearity, and extracted insights from text-based professor tags.  
- **Model Performance:** Achieved **73.48% R²** for predicting professor ratings and **AUC of 0.667** in classification tasks.  
- **Data Visualization:** Used **Matplotlib and Seaborn** to create correlation heatmaps, confidence intervals, and distribution plots for better interpretability.  

## 📂 Repository Structure  
```
│── gender_bias_report.pdf   # Detailed report documenting methodology, results, and insights  
│── gender_bias_analysis.py                 # Python script containing data processing, statistical tests, and ML models  
│── README.md                 # Project documentation  
```

## ⚙️ Installation & Setup  
Ensure you have Python 3.x and the required libraries installed:  
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## 🚀 Usage  
Run the **gender_bias_analysis.py** script to execute the statistical tests and machine learning models:  
```bash
python gender_bias_analysis.py
```

## 📊 Results & Findings  
- Male professors had a statistically significant but **small** advantage in ratings.  
- The **logistic regression model** performed best, achieving **AUC = 0.667** in predicting rating outcomes.  
- Feature importance analysis showed that **"Take Class Again"** was the strongest predictor of ratings.  

## 🏆 Key Skills Demonstrated  
✅ **Statistical Hypothesis Testing** (Permutation tests, Effect Size, Confidence Intervals)  
✅ **Machine Learning & Predictive Modeling** (Regression, Logistic Classification, SMOTE)  
✅ **Feature Engineering & Preprocessing** (VIF Analysis, StandardScaler, Handling Missing Data)  
✅ **Data Visualization** (Seaborn, Matplotlib, Correlation Heatmaps)  

## 👨‍💻 Contributors  
- Yueh-Han Chen  
- Pranav Thorat  
- Ahamed Foisal  

## 📜 License  
This project is open-source and available under the **MIT License**.  
