# Capstone-Modul-3-Machine-Learning


## 🏙️ **Predicting Fair Apartment Prices in Daegu using Machine Learning**


### 📌 **Project Overview**

Properti hunian seperti apartemen merupakan kebutuhan yang semakin krusial di kota besar seperti Daegu, Korea Selatan. Namun, salah satu tantangan utama dalam penjualan unit apartemen adalah penentuan harga yang tepat dan kompetitif. Harga yang terlalu tinggi membuat unit sulit terjual, sementara harga terlalu rendah berisiko menimbulkan kerugian bagi pemilik. Dalam konteks ini, pendekatan berbasis machine learning dapat menjadi solusi objektif dalam memprediksi harga jual apartemen berdasarkan fitur internal dan eksternal yang dimilikinya.

### 🎯 **Business Problem**

Pemilik apartemen di Daegu kerap kesulitan menentukan harga jual yang wajar karena keterbatasan referensi dan analisis pasar. Penentuan harga secara subjektif berpotensi menyebabkan unit tidak laku terjual atau kehilangan nilai pasar. Oleh karena itu, dibutuhkan model prediktif yang mampu memperkirakan harga jual yang fair berdasarkan karakteristik unit dan lingkungannya.

### 💡 **Goals**

Membangun model machine learning regresi yang dapat memprediksi harga jual apartemen di kota Daegu dengan akurasi tinggi. Model ini diharapkan dapat membantu:

- Pemilik atau agen properti menentukan harga jual awal yang kompetitif.

- Menyediakan estimasi harga yang objektif berdasarkan fitur-fitur apartemen.

- Mengoptimalkan strategi penjualan properti di pasar sekunder.

### 📊 **Dataset Description**

Dataset yang digunakan merupakan data historis penjualan apartemen di Daegu dan mencakup berbagai fitur, seperti:

- Ukuran unit (luas dalam sqft)

- Tipe lorong dan stasiun subway terdekat

- Jarak ke transportasi publik

- Jumlah fasilitas internal dan eksternal

- Tahun pembangunan

- Jumlah parkir basement

- Target: Harga jual apartemen (SalePrice)

### 🧠 **Analytic Approach**
- Tahapan utama: Business Understanding → Data Understanding → Data Cleaning → Feature Engineering → Modeling → Evaluation → Conclusion & Recommendation.

- Algoritma utama: XGBoost Regressor sebagai model akhir.

- Algoritma baseline: Linear Regression dan Random Forest Regressor.

- Metode evaluasi: MAE, RMSE, MAPE, dan R-squared, dipilih berdasarkan keterkaitan dengan konteks bisnis.

### ⚙️ **Tools & Technologies**
- Python

- Jupyter Notebook

- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

- Model disimpan dalam format .pkl untuk deployment

### 📈 **Outcome**

Model akhir berhasil dibangun dan diuji menggunakan data validasi. Hasil evaluasi menunjukkan bahwa model mampu memprediksi harga jual dengan error yang cukup rendah, serta memiliki generalisasi yang baik terhadap data baru.

### ✅ **Conclusion & Recommendation**

Model prediksi ini direkomendasikan untuk digunakan oleh pemilik properti dan agen real estate di Daegu sebagai alat bantu dalam menentukan harga jual awal. Namun, model ini memiliki batasan pada variasi data, dan performanya mungkin menurun pada unit apartemen dengan karakteristik unik atau langka. Rekomendasi perbaikan mencakup penambahan data real-time dan fitur lokasi yang lebih kaya seperti peta zonasi atau nilai tanah.
