# 💊 Drugs, Side Effects, and Medical Conditions Analysis

## 📘 Project Overview

This project focuses on the analysis of a comprehensive dataset containing information about **various drugs, their side effects, and the medical conditions** they are used to treat.
The aim is to uncover **patterns, correlations, and insights** that help better understand the pharmaceutical landscape — including how certain drugs are related to specific conditions and side effects.

---

## 📂 Dataset Information

* **Dataset Name:** Drugs, Side Effects, and Medical Conditions
* **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/jithinanievarghese/drugs-side-effects-and-medical-condition)
* **Number of Attributes:** 17
* **Number of Data Rows:** 2,931

This dataset includes key details such as:

* Drug names and types
* Medical conditions treated
* Reported side effects
* Usage attributes (e.g., prescription type, pregnancy category, and alcohol interactions)

---

## 🧹 Data Preprocessing

### 🔸 Selection

* Removed irrelevant attributes: `csa`, `drug_link`, `medical_condition_url`
* Filled missing values in binary attributes for consistency and ease of analysis

### 🔸 Cleaning

* **Text Processing:** Tokenized and cleaned the `medical_condition_description` column using **NLTK**
* **Side Effects:** Processed textual data in the `side_effects` column for meaningful analysis
* Standardized and transformed the dataset into a structured format suitable for further exploration

---

## 📊 Descriptive Statistics & Data Analysis

### Dataset Dimensions (After Preprocessing)

* **Rows:** 2,931
* **Columns:** 14

### 🔍 Key Insights

* Identified and counted unique drugs and medical conditions
* Explored attributes like `rx_otc`, `pregnancy_category`, and `alcohol`
* Visualized findings using:

  * **Bar graphs**
  * **Pie charts**
  * **Scatter plots**
  * **Line plots**
  * **Heatmaps** for correlation analysis
  * **Funnel chart**
  * **Radar chart**
  * **Count plot**
  * **Box plot**
  * **Pair plot**

### 🧠 Advanced Analysis

* **Correlation Matrices:** Explored interdependencies between drug properties
* **Association Rule Mining:** Applied the **Apriori algorithm** to find related drugs
* **Machine Learning:**

  * Implemented **Decision Tree Classification** for predictive analysis
  * Used **Clustering** techniques to group similar drugs and side effects

---

## 🧾 Conclusion

This project demonstrates a full data analysis pipeline — from **data cleaning and transformation** to **statistical exploration and machine learning applications**.
By leveraging both descriptive and predictive methods, it provides valuable insights into:

* The relationships between drugs and medical conditions
* Patterns in user ratings and reported side effects
* Associations among drugs used for similar treatments

These findings can contribute to **safer prescriptions**, **better healthcare decisions**, and **further pharmaceutical research**.

---

## 🧰 Python Libraries Used

* **Pandas** – Data manipulation and preprocessing
* **NLTK** – Text cleaning and tokenization
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical plotting
* **Plotly** - Interactive and dynamic visualization
* **Scikit-learn** – Machine learning and modeling

---

## 📈 Future Work

* Incorporate sentiment analysis on user reviews
* Integrate a recommendation system for safer drug alternatives
* Develop an interactive dashboard using Plotly or Streamlit

---
