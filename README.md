# 🩺 Prediksi Penyakit Diabetes Menggunakan KNN dan Naive Bayes

## 📌 Deskripsi Proyek
Proyek ini merupakan implementasi **Data Mining dan Machine Learning** untuk memprediksi risiko **penyakit diabetes** berdasarkan berbagai faktor kesehatan dan perilaku.  
Dua algoritma klasifikasi yang digunakan adalah **K-Nearest Neighbors (KNN)** dan **Naive Bayes**, kemudian dibandingkan kinerjanya menggunakan metrik evaluasi standar.

Proyek ini dibuat sebagai **Final Project / Laporan Akhir** tahun 2024.

---

## 🎯 Tujuan Penelitian
1. Mengidentifikasi faktor-faktor risiko yang memengaruhi diabetes.
2. Membangun model prediksi diabetes menggunakan algoritma **KNN** dan **Naive Bayes**.
3. Mengevaluasi performa model menggunakan:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix
4. Membandingkan kinerja kedua metode untuk menentukan model terbaik.
5. Memberikan wawasan untuk **deteksi dini dan pencegahan diabetes**.

---

## 📊 Dataset
Dataset berisi data kesehatan individu dengan beberapa variabel utama, antara lain:
- Gender
- Age
- Smoking History
- Hypertension
- Heart Disease
- BMI
- HbA1c Level
- Glucose Level  
- **Target**: `diabetes` (0 = Tidak Diabetes, 1 = Diabetes)

Dataset diproses dan dianalisis menggunakan **Google Colab**.

---

## ⚙️ Tahapan Penelitian

### 1. Data Preprocessing
- Encoding variabel kategori menggunakan `LabelEncoder`
- Menangani missing values dengan **median**
- Standarisasi fitur menggunakan `StandardScaler`

### 2. Pembagian Data
- Training set: 80%
- Testing set: 20%

### 3. Model yang Digunakan
- **K-Nearest Neighbors (KNN)** dengan `k = 5`
- **Naive Bayes (GaussianNB)**

### 4. Evaluasi Model
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

---

## 📈 Hasil Evaluasi

### 🔹 KNN
- **Accuracy: ±96.14%**
- Jumlah kesalahan prediksi relatif kecil
- Performa sangat baik dalam mendeteksi kasus diabetes

### 🔹 Naive Bayes
- Accuracy lebih rendah dibanding KNN
- Lebih cepat dan efisien
- Sensitif terhadap asumsi independensi fitur

📌 **Kesimpulan**:  
Model **KNN memberikan performa klasifikasi yang lebih baik** dibandingkan Naive Bayes pada dataset ini.

---

## 🧠 Insight Penting
- Faktor seperti **glucose level, BMI, dan HbA1c** sangat berpengaruh terhadap prediksi diabetes
- KNN cocok untuk data dengan pola non-linear
- Naive Bayes unggul dari sisi kecepatan, namun kurang fleksibel terhadap data kompleks

---

## 🛠️ Teknologi yang Digunakan
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 👨‍🎓 Penulis
**Mohammad Daffa My Honest Anugerah**  
NIM: 06022006  
Universitas Tanri Abeng  
Jakarta, 2024

---

## 📄 Catatan
Proyek ini dibuat untuk keperluan akademik dan pembelajaran.  
Pen
