
# 🍷 Wine Quality Analysis (Red vs White Wine)

## 📌 Project Overview
Analisis dataset kualitas wine merah dan putih dari **UCI Machine Learning Repository**.  
Tujuan utama project ini adalah memahami faktor-faktor yang memengaruhi kualitas wine dan membandingkan perbedaan antara red wine dan white wine.  

---

## 🗂 Dataset
- **Source:** [Wine Quality Dataset (UCI ML Repo)](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)  
- **Files:**
  - `winequality-red.csv` → 1599 sampel red wine  
  - `winequality-white.csv` → 4898 sampel white wine  
- **Fitur:**  
  - 11 variabel kimia (alcohol, acidity, citric acid, sugar, sulfur dioxide, pH, dll)  
  - 1 variabel target: **quality** (skor 0–10)  

---

## 🔎 Methodology
1. **Data Preparation**
   - Load & merge red/white wine dataset
   - Data cleaning (cek missing values, duplikasi, tipe data)

2. **Exploratory Data Analysis (EDA)**
   - Distribusi kualitas wine (countplot red vs white)
   - Statistik deskriptif
   - Korelasi antar fitur (heatmap)
   - Boxplot (alcohol vs quality, acidity vs quality)

3. **Statistical Testing**
   - Independent T-test → membandingkan kadar alkohol red vs white wine

4. **Predictive Modeling**
   - Labeling kualitas → *low, medium, high*
   - Random Forest Classifier untuk prediksi kualitas
   - Analisis feature importance

---

## 📊 Key Insights
- White wine cenderung memiliki skor kualitas lebih tinggi dibanding red wine  
- Kadar **alcohol** berhubungan positif dengan kualitas wine  
- **Volatile acidity** berpengaruh negatif terhadap kualitas  
- Random Forest mengonfirmasi bahwa **alcohol adalah faktor dominan**  

---

## 🖼 Sample Visualizations
*(Tambahkan gambar hasil visualisasi di repo)*  

- Distribusi kualitas red vs white wine  
- Heatmap korelasi antar variabel  
- Boxplot kadar alcohol vs kualitas  
- Feature importance dari Random Forest  

---

## 🏆 Project Level
- **Intermediate → Advanced (entry-level)**  

---

## ⚙️ Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy  
- **Jupyter Notebook** untuk analisis & visualisasi  

---

## 🚀 Next Steps
- Mencoba model lain (Logistic Regression, XGBoost)  
- Hyperparameter tuning untuk meningkatkan akurasi  
- Membuat dashboard interaktif (Streamlit/Power BI)  

---

✨ Project ini merupakan bagian dari pengembangan **portfolio data analysis** saya.  
Silakan lihat notebook lengkap di repo ini, dan jangan ragu untuk berdiskusi!  
