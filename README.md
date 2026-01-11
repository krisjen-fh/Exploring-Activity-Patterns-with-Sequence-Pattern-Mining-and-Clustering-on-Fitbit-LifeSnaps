# 📊 Eksplorasi Pola Aktivitas & Tidur Pengguna Fitbit
### Sequence Pattern Mining & Clustering pada Dataset Fitbit LifeSnaps

## 🧠 Deskripsi Proyek
Proyek ini merupakan **proyek akhir mata kuliah Data Mining** yang berfokus pada analisis **pola aktivitas dan tidur pengguna perangkat Fitbit**.  
Tujuan utama proyek ini adalah untuk **menggali pola perilaku aktivitas fisik**, mengelompokkan pengguna berdasarkan karakteristik kesehatannya, serta memahami hubungan antara **gaya hidup, kondisi emosional, dan profil psikologis**.

Dataset yang digunakan adalah **Fitbit LifeSnaps**, yang mencakup:
- Data aktivitas harian dan per jam  
- Data fisiologis pengguna  
- Data survei psikologis  

---

## 🎯 Tujuan Proyek
- Mengidentifikasi **pola aktivitas harian** pengguna menggunakan *Sequence Pattern Mining*
- Mengelompokkan pengguna berdasarkan **karakteristik aktivitas dan risiko kesehatan**
- Menganalisis hubungan antara **aktivitas fisik, tingkat stres, motivasi olahraga, dan kepribadian**
- Memberikan **wawasan berbasis data** untuk mendukung intervensi gaya hidup sehat

---

## 🗂️ Dataset
Dataset Fitbit LifeSnaps terdiri dari:
- **Activity Data**: langkah harian, waktu sedentari, aktivitas per jam  
- **Physiological Data**: detak jantung istirahat, BMI  
- **Psychological Survey Data**:
  - STAI (Anxiety)
  - BREQ (Exercise Motivation)
  - TTM
  - PANAS
  - Personality Traits  

---

## 🔎 Metodologi

### 1️⃣ Exploratory Data Analysis & Pre-processing
Tahap awal analisis meliputi:
- Exploratory Data Analysis (EDA)
- Penanganan **missing values**
- Deteksi dan penanganan **outlier**
- Transformasi dan seleksi fitur

---

### 2️⃣ Sequence Pattern Mining
- Menggunakan algoritma **PrefixSpan**
- Mengidentifikasi **pola aktivitas paling sering muncul**
- Pola yang dihasilkan digunakan untuk **segmentasi pengguna** ke dalam tiga kelompok:
  - 🟢 **Aktif & Sehat**
  - 🟡 **Kurang Gerak**
  - 🔴 **Stres / Kurang Istirahat**

---

### 3️⃣ Clustering Analysis
Analisis clustering dilakukan menggunakan fitur:
- Jumlah langkah
- Detak jantung istirahat
- BMI
- Waktu sedentari  

Tujuan clustering adalah untuk:
- Mengidentifikasi **kelompok risiko kesehatan**
- Membandingkan hasil clustering dengan segmentasi berbasis pola aktivitas

---

### 4️⃣ Integrasi Data Psikologis
Data survei psikologis digabungkan dengan data aktivitas untuk:
- Menganalisis hubungan antara **gaya hidup dan tingkat stres**
- Mengkaji **motivasi olahraga (intrinsik vs ekstrinsik)**
- Melihat pengaruh **kepribadian terhadap pola aktivitas**

---

## 📈 Hasil & Insight Utama
- Pengguna dengan **pola aktivitas aktif** cenderung memiliki:
  - Tingkat stres lebih rendah
  - Motivasi olahraga yang lebih **intrinsik**
- Pola hidup sedentari berkorelasi dengan:
  - Tingkat stres lebih tinggi
  - Risiko kesehatan yang lebih besar
- Integrasi data aktivitas dan psikologis memberikan **pemahaman holistik** terhadap perilaku pengguna

---

## 💡 Kesimpulan
Proyek ini menunjukkan bahwa pendekatan **data mining berbasis pola dan clustering** mampu memberikan wawasan mendalam mengenai hubungan antara:
**aktivitas fisik, kondisi emosional, dan profil psikologis**.

Hasil analisis ini memiliki potensi untuk digunakan sebagai dasar **intervensi berbasis data** guna mendorong gaya hidup yang lebih sehat.

---

## 🛠️ Tools & Techniques
- Python  
- Pandas, NumPy  
- Data Visualization  
- PrefixSpan  
- Clustering Algorithms  

---

## 👩‍💻 Author
**Krisjen Fraulein Hutagalung (me)**  
**Alisha Deana Tabita**  
**Putri Manika Rukmamaya**  
Undergraduate Data Science Student – UNESA
