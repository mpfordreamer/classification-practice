# Klasifikasi - Diabetes Prediction

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi apakah seorang pasien menderita diabetes berdasarkan beberapa pengukuran diagnostik klinis. Model ini menggunakan algoritma klasifikasi untuk membedakan antara pasien diabetes dan non-diabetes.

---

## 📂 Struktur Proyek
```text
Klasifikasi/
├── datasets/
│   └── diabetes.csv          # Dataset Diabetes
└── classification-practice.ipynb  # Notebook Latihan Klasifikasi
```

---

## 🛠️ Ringkasan & Library
Model ini mengevaluasi berbagai algoritma klasifikasi dan menangani ketidakseimbangan kelas (*class imbalance*).

**Library Utama:**
*   `pandas` & `numpy`: Analisis dan struktur data.
*   `seaborn` & `matplotlib`: Visualisasi grafik dan persebaran data.
*   `sklearn`: Algoritma klasifikasi (Decision Tree, Random Forest, dll).
*   `LazyPredict`: Evaluasi cepat berbagai model klasifikasi.
*   `imblearn` (SMOTE): Penanganan data tidak seimbang.

---

## 🚀 Cara Menjalankan
Untuk menjalankan notebook ini secara interaktif di **Google Colab**, ikuti langkah berikut:

1.  **Buka Google Colab**: Masuk ke [Google Colab](https://colab.research.google.com/).
2.  **Upload Notebook**: Pilih tab `Upload` dan pilih file `classification-practice.ipynb`.
3.  **Upload Dataset**:
    *   Pastikan path dataset di notebook sesuai (misal: `datasets/diabetes.csv`).
    *   Upload file `diabetes.csv` ke session storage Colab.
4.  **Jalankan Sel**: Klik `Runtime` -> `Run all` atau jalankan sel satu per satu dari atas ke bawah.

---

## 📊 Informasi Dataset
Dataset ini berisi data medis pasien wanita keturunan Suku Pima:
*   `Pregnancies`: Jumlah kehamilan.
*   `Glucose`: Kadar glukosa plasma.
*   `BloodPressure`: Tekanan darah diastolik (mm Hg).
*   `SkinThickness`: Ketebalan lipatan kulit trisep (mm).
*   `Insulin`: Kadar insulin serum 2 jam (mu U/ml).
*   `BMI`: Indeks Massa Tubuh (massa kg / tinggi m²).
*   `DiabetesPedigreeFunction`: Fungsi riwayat keturunan diabetes.
*   `Age`: Umur pasien.
*   **`Outcome`** (Target): Status diabetes (0 = Tidak, 1 = Ya).