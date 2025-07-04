# Customer Support Analytics – CSAT Prediction & Service Optimization

# Objective
The goal of this project is to improve customer service efficiency and predict satisfaction outcomes (CSAT)using structured support ticket data.
Through a combination of exploratory data analysis (EDA), NLP, and basic machine learning models, we identify patterns and build a deployable satisfaction predictor.

# Dataset Overview
The dataset includes historical support case records 

Project Workflow

# 1. 📊 EDA (Exploratory Data Analysis)
- Performed **UBM analysis**:
  - **Univariate**: Frequency of CSAT scores, sub-categories, agent shifts
  - **Bivariate**: CSAT vs shift, CSAT vs response time, CSAT vs tenure
  - **Multivariate**: Heatmap of CSAT by shift and tenure bucket
# 2. 🧹 Data Cleaning
- Removed duplicates, handled missing values
- Converted date columns, created new `response_time_min` field
- Encoded categorical features for modeling
# 3. 🧠 ML Modeling
- **Logistic Regression** for linear trend modeling
- **Random Forest Classifier** for improved accuracy
- **Model Evaluation**: Accuracy, confusion matrix, classification report
- **Feature Importance** plotted for interpretability
# 4. ✨ NLP Insights
- Generated a **Word Cloud** from open customer remarks
- Applied **sentiment analysis** using `TextBlob`
- Visualized **sentiment polarity** distribution
#  Key Insights
- Longer response times result in lower CSAT
- Specific complaint categories (e.g., Exchange, Return) have lower satisfaction
- Afternoon shifts perform better overall
- Negative sentiment in remarks often correlates with low CSAT
# Tools & Libraries Used
- **Python**, **Pandas**, **NumPy** – Data processing
- **Matplotlib**, **Seaborn** – Visualization
- **Scikit-learn** – Machine Learning
- **TextBlob**, **WordCloud** – NLP
- **Jupyter Notebook** / **Colab** – Development platform
# Future Enhancements
- Deploy as a live dashboard with Streamlit or Flask
- Integrate more advanced ML/NLP techniques
- Build a feedback alert system based on sentiment scores
# Author
- **Gayatri Shirish Khairnar** – Data Science Enthusiast | BTech Final Year  
- Minor Internship Project | July 2025 Submission
# License
This project is academic in nature and shared for learning purposes only.
