# ❤️ Heart Disease Analysis (EDA Project)

This project explores the heart disease dataset to uncover patterns, trends, and potential risk factors related to cardiovascular health. The focus is on exploratory data analysis (EDA) using statistical summaries and visualizations.

---

## 📊 Dataset

- **Source**: [heart.csv from The Data Analysis Workshop](https://github.com/PacktWorkshops/The-Data-Analysis-Workshop/blob/master/Chapter07/Dataset/heart.csv)
- **Rows**: 303 patients  
- **Columns**: 14 features (age, sex, cp, trestbps, chol, thalach, etc.)  
- **Target variable**: `target` (1 = heart disease, 0 = no heart disease)

---

## 🧠 Techniques Used
- Descriptive statistics  
- Visual exploration: histograms, boxplots, heatmaps, countplots  
- Correlation analysis  
- Group-wise comparison by target class

---

## 🎯 Goal

- Understand how patient attributes relate to heart disease  
- Visualize differences between patients with and without heart disease  
- Identify patterns across age, sex, cholesterol, blood pressure, and more

---

## ✅ Key Insights

- Males represent the majority of patients with heart disease in this dataset  
- Chest pain type (`cp`) and max heart rate (`thalach`) show clear variation across target classes  
- No strong linear correlation between cholesterol and heart disease, but combined features reveal insights  
- Age group 50–60 appears most affected

---

## 🛠️ Tools & Libraries

Python, Pandas, NumPy  
Matplotlib, Seaborn  
Jupyter Notebook / Google Colab

---

# 😃 Emotion Detection with Rule-based NLP (Vietnamese)

This project focuses on detecting emotional sentiment in Vietnamese text using a rule-based approach. It involves building a custom emotion lexicon and applying logical rules to classify input sentences into emotion categories such as positive or negative.

---

## 📄 Dataset

- **Source**: Manually created dataset of Vietnamese sentences  
- **Format**: `.txt` and `.csv` files for sample text and emotion word dictionary  
- **Categories**: Positive (1), Negative (-1)

---

## 🧠 Techniques Used

- Vietnamese text preprocessing: lowercasing, punctuation removal, tokenization  
- Dictionary-based sentiment scoring using positive/negative word lists  
- Rule-based classification logic (count-based comparison)  
- Accuracy evaluation by comparing predicted vs. labeled sentiments  
- Batch sentiment prediction from tokenized CSV files

---

## 🎯 Goal

- Build a transparent, interpretable rule-based emotion detection system for Vietnamese  
- Perform basic sentiment classification without using machine learning  
- Provide a lightweight prototype for future improvement or extension

---

## ✅ Results

- The predicted labels (`pre_Sentiment`) matched ground-truth labels (`Sentiment`) on **~84.7%** of test samples  
- Results are saved to CSV for easy inspection, validation, or dashboard integration

---

## 🛠️ Tools & Libraries

- Python, Pandas, re (Regex)  
- Text preprocessing techniques: lowercasing, punctuation removal, tokenization  

---

⭐ This is an educational project built during my learning process, and I’m actively improving it as I grow.
