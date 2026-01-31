

# Intelligent Travel Recommendation Engine

### **Predictive Intelligence | Vector Space Modeling | Relational Data Pipelines**

## 📌 Executive Summary

This system is an **End-to-End Decision-Support Tool** designed to predict and recommend optimal travel destinations by mapping unstructured user requirements into a high-dimensional vector space. Originally engineered in 2023, the project demonstrates a professional-grade application of **Mathematical Similarity Scoring** and **Pattern Recognition** to solve the "Cold Start" problem in personalized tourism.

## 🛠️ Core Technical Pillars

This project serves as proof of mastery in the following domains required for Data Science, AI, and Full-Stack roles:

### 1. Vector Space Modeling (NLP Pipeline)

* **Feature Extraction**: Utilized `TfidfVectorizer` to transform raw text inputs (e.g., "Heritage," "Wildlife") into a **Vector Space Model (VSM)**.
* **Dimensionality**: Successfully converted categorical and text data into numerical vectors, allowing for advanced statistical comparison.

### 2. Predictive Similarity Engine

* **Mathematical Optimization**: Implemented **Cosine Similarity** to calculate the angular distance between a user's intent vector and destination feature vectors.
* **Algorithm**: Utilized the formula: 

 to ensure recommendations are based on mathematical proximity rather than simple keyword matches.
* **K-Nearest Neighbors (KNN)**: Engineered a custom KNN logic to perform neighborhood-based ranking, ensuring a "Top-5" recommendation accuracy.

### 3. Data Engineering & Relational Architecture

* **Relational Mapping**: Designed a data workflow that bridges demographic user profiles (`User.csv`) with geographical metadata (`data_content.csv`).
* **ETL Processes**: Built a `Pandas` pipeline to handle real-world "dirty" data, including null-value imputation for missing Age/Sex attributes and duration normalization.
* **Spatial Logic**: Incorporated destination metadata such as **Distance (Kms)**, **Duration**, and **Nearby Places** to provide contextually aware suggestions.

## 📊 Dataset Insights & Feature Sets

The engine processes multi-dimensional data points to refine its predictive accuracy:

| Feature Category | Variables Tracked | Impact on Model |
| --- | --- | --- |
| **User Profile** | Age, Sex, Previous Interest | Personalized bias toward relevant clusters. |
| **Travel Intent** | Category (Heritage, Park, etc.) | Core vector direction for TF-IDF mapping. |
| **Logistical Meta** | Distance, Rating, Duration | Ranking weights for real-world usability. |

## 🚀 Deployment & Usage

1. **Clone the Repo**: `git clone https://github.com/shreyamalogi/Intelligent-Travel-Recommendation-Engine.git`
2. **Install Dependencies**: `pip install pandas scikit-learn matplotlib`
3. **Launch System**: `python main.py`

