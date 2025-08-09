# Sleep-pattern-analyzer-using-smart-watch-data-
Sleep Pattern Analyzer using smartwatch data to identify and cluster sleep behaviors with K-Means algorithm. Built in Python with visualizations using Matplotlib and Seaborn. Helps detect irregular patterns, track changes, and improve sleep quality through data-driven insights.

# Sleep Pattern Analyzer using Smartwatch Data 💤

## 📌 Overview
This project analyzes sleep patterns using **smartwatch data** and applies **K-Means Clustering** to group similar sleep behaviors.  
The goal is to identify different sleep quality clusters and provide insights for improving rest and recovery.

---

## 🎯 Objectives
- Collect and process smartwatch sleep tracking data.
- Perform exploratory data analysis (EDA) to understand patterns.
- Apply **K-Means Clustering** to group similar sleep patterns.
- Visualize clusters for better interpretation.
- Suggest possible lifestyle changes for better sleep quality.

---

## 🛠 Technologies Used
- **Python 3**
- **Pandas** – Data handling
- **NumPy** – Numerical operations
- **Matplotlib / Seaborn** – Data visualization
- **scikit-learn** – Machine Learning (K-Means)
- **Jupyter Notebook** – Development environment

---

## 📂 Project Structure
```

sleep-pattern-analyzer/
│
├── README.md                  # Project documentation
├── requirements.txt           # Python dependencies
├── data/
│   ├── smartwatch\_sleep\_data.csv
├── notebooks/
│   ├── sleep\_analysis.ipynb   # Main analysis notebook
├── src/
│   ├── data\_preprocessing.py  # Cleaning & preprocessing code
│   ├── clustering.py          # K-Means implementation
├── visuals/
│   ├── cluster\_plot.png
│   ├── sleep\_distribution.png
└── results/
├── cluster\_summary.csv

````

---

## 🚀 How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/sleep-pattern-analyzer.git
cd sleep-pattern-analyzer
````

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook

```bash
jupyter notebook notebooks/sleep_analysis.ipynb
```

---

## 📊 Dataset

The smartwatch dataset contains:

* **Date** – Recording date
* **Total Sleep Time (hours)**
* **Deep Sleep Duration (hours)**
* **REM Sleep Duration (hours)**
* **Light Sleep Duration (hours)**
* **Awake Time (minutes)**
* **Sleep Efficiency (%)**

---

## 🔍 Methodology

1. **Data Collection & Cleaning** – Remove duplicates, handle missing values.
2. **Feature Engineering** – Extract meaningful features from raw data.
3. **EDA** – Visualize sleep trends & correlations.
4. **Clustering** – Apply K-Means to group users into different sleep pattern clusters.
5. **Evaluation** – Interpret clusters and generate insights.

---

## 📸 Sample Visualizations

**Sleep Clusters:**
![Cluster Plot](visuals/cluster_plot.png)

**Sleep Distribution:**
![Sleep Distribution](visuals/sleep_distribution.png)

---

## 📜 Results & Insights

* Cluster 0: **Healthy Sleepers** – Consistent 7-8 hours sleep with high efficiency.
* Cluster 1: **Light Sleepers** – High light sleep time, low deep sleep.
* Cluster 2: **Irregular Sleepers** – Inconsistent sleep patterns, low efficiency.

---

