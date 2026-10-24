# 📊 Kaggle Data Science & Analysis Showcase

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-Interactive_App-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://multilingual-mobile-app-reviews.streamlit.app/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![SciPy](https://img.shields.io/badge/SciPy-Hypothesis_Testing-8CAAE6?style=flat-square&logo=scipy&logoColor=white)](https://scipy.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook_Published-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/code/sandeepmalviya/multilingual-app-review-analysis)
[![License: MIT](https://img.shields.io/badge/License-MIT-4F46E5.svg?style=flat-square)](LICENSE)

An end-to-end data science and machine learning showcase by [Sandeep Malviya](https://github.com/SandyCompetent). This repository demonstrates full-cycle data science workflows: taking raw, realistic Kaggle datasets from ingestion and data cleaning through exploratory data analysis (EDA), rigorous statistical hypothesis testing, and production deployment via interactive Streamlit web applications.

---

## 🚀 Featured Project: Multilingual Mobile App Review Analysis

An in-depth analysis and interactive dashboard exploring the [Multilingual Mobile App Reviews Dataset 2025 on Kaggle](https://www.kaggle.com/datasets/pratyushpuri/multilingual-mobile-app-reviews-dataset-2025/data).

* **🌐 Live Interactive App**: [**multilingual-mobile-app-reviews.streamlit.app**](https://multilingual-mobile-app-reviews.streamlit.app/)
* **📓 Kaggle Notebook**: [**View Analysis on Kaggle**](https://www.kaggle.com/code/sandeepmalviya/multilingual-app-review-analysis)
* **📁 Project Directory**: [`MultilingualMobileAppReviewDatasetAugust2025/`](./MultilingualMobileAppReviewDatasetAugust2025)

![Streamlit Interactive Dashboard](https://raw.githubusercontent.com/SandyCompetent/kaggle_analysis_showcase/main/MultilingualMobileAppReviewDatasetAugust2025/Output/streamlit_output_01.jpg)

### 📌 Problem Context & Dataset
The project analyzes a realistic dataset containing **over 2,500 mobile app reviews** across **40+ popular applications** in **24 different languages**. The dataset was curated with real-world data quality challenges (missing attributes, inconsistent data types, and multilingual string encoding), providing a rigorous testbed for production data cleaning pipelines.

### 🔑 Key Analytical Insights
1. **Rating Distribution**: Mean rating of **3.02**. Reviews heavily cluster around 'Average' and 'Poor', reflecting the behavioural tendency of users to voice feedback more actively when friction occurs.
2. **Review Length & Demographics**: Bivariate correlation showed no statistically significant relationship between reviewer age or review token length and the final rating score.
3. **ANOVA Hypothesis Testing**: A one-way Analysis of Variance (ANOVA) across 18 distinct app categories confirmed no statistically significant variance in mean ratings across functional categories ($p\text{-value} > 0.05$).

<div align="center">
  <img src="https://raw.githubusercontent.com/SandyCompetent/kaggle_analysis_showcase/main/MultilingualMobileAppReviewDatasetAugust2025/Output/output_01.png" width="48%" alt="Rating Distribution" />
  <img src="https://raw.githubusercontent.com/SandyCompetent/kaggle_analysis_showcase/main/MultilingualMobileAppReviewDatasetAugust2025/Output/output_02.png" width="48%" alt="Category Breakdown" />
</div>

---

## 🛠️ Tech Stack & Methodology

| Component | Library / Framework | Application |
|---|---|---|
| **Data Cleaning & Wrangling** | `pandas`, `numpy` | Handling missing values, type casting, multilingual string normalization |
| **Statistical Analysis** | `scipy.stats` | One-way ANOVA hypothesis testing, Pearson correlation matrix |
| **Exploratory Visualizations** | `matplotlib`, `seaborn`, `plotly` | Distribution plots, correlation heatmaps, interactive scatter |
| **Web Dashboard Deployment** | `streamlit` | Multi-filter dashboard deployed on Streamlit Community Cloud |

---

## 📂 Repository Layout

```
kaggle_analysis_showcase/
├── MultilingualMobileAppReviewDatasetAugust2025/
│   ├── Output/                       # Generated analysis plots and dashboard previews
│   ├── main_analysis.ipynb           # Comprehensive exploratory data analysis notebook
│   ├── streamlit_app.py              # Interactive web dashboard source
│   ├── requirements.txt              # Project-specific pinned dependencies
│   └── README.md                     # Deep-dive study documentation
├── requirements.txt                  # Root dependencies
├── LICENSE                           # MIT License
└── README.md                         # Main portfolio showcase overview
```

---

## ⚙️ Running Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SandyCompetent/kaggle_analysis_showcase.git
   cd kaggle_analysis_showcase/MultilingualMobileAppReviewDatasetAugust2025
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Streamlit dashboard**:
   ```bash
   streamlit run streamlit_app.py
   ```

---

## 📜 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.
