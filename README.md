# 📈 BBRI Stock Forecasting with Box-Jenkins

![Time Series Forecasting](https://cdn.discordapp.com/attachments/430679114912104448/1336390861998784664/Pz2uFUAAGICq9kDAAAAABBjqMwDAAAAABBjCPMAAAAAAMQYwjwAAAAAADGGMA8AAAAAQIwhzAMAAAAAEGMI8wAAAAAAxBjCPAAAAAAAMYYwDwAAAABAjCHMAwAAAAAQYwjzAAAAAADEGMI8AAAAAAAx5v8DdqAUqX7DS9AAAAAASUVORK5CYII.png?ex=67a3a27a&is=67a250fa&hm=f769c19d0efcff078c41f19029d02f17264d778290e6af60936d00ef769166eb&)

## 🔍 Overview
Proyek ini menganalisis dan memprediksi pergerakan harga saham **BBRI** menggunakan metode **Box-Jenkins (ARIMA)**. Dengan pendekatan **time series analysis**, proyek ini menguji kestasioneran data, mengidentifikasi model terbaik, dan mengevaluasi performa prediksi menggunakan metrik RMSE.

## 📊 Dataset
- **Sumber:** [Yahoo Finance](https://finance.yahoo.com/quote/BBRI.JK/)  
- **Periode:** 2020 - 2025  
- **Variabel utama:** **Close Price** (Harga Penutupan)  

## 🛠️ Metode & Tools
- **Metode:**  
  - Augmented Dickey-Fuller (ADF) untuk uji kestasioneran  
  - Box-Cox Transformation untuk menstabilkan variansi  
  - Differencing untuk mengatasi tren  
  - ACF/PACF Plot untuk identifikasi model  
  - Maximum Likelihood Estimation (MLE) untuk estimasi parameter  
  - Akaike Information Criterion (AIC) untuk pemilihan model terbaik  
  - Ljung-Box Test untuk uji kelayakan model  
  - RMSE untuk evaluasi akurasi prediksi  

- **Tools & Libraries:**
  - 🐍 Python (Google Colab)
  - 📦 Pandas, NumPy, Matplotlib, Seaborn
  - 📊 Statsmodels (ARIMA), SciPy

## 🔬 Hasil Analisis
- Model terbaik berdasarkan **AIC**: **ARIMA(37,1,0)**  
- **RMSE** dari prediksi: **152.259**  
- Residual model tidak berdistribusi normal, sehingga model ini masih bisa ditingkatkan.

## 📜 Referensi
1. Prasetya, B. D., Pamungkas, F. S., & Kharisudin, I. (2019). Pemodelan dan Peramalan Data Saham dengan Analisis Time Series menggunakan Python.
2. Rezaldi, D. A., & Sugiman. (2021). Peramalan Metode ARIMA Data Saham PT. Telekomunikasi Indonesia.
