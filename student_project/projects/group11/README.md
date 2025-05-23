# Data Science Projects
# Prediksi Harga Rumah dengan Regresi Linear

## 📌 Deskripsi
Project ini bertujuan untuk memprediksi volume penjualan menggunakan data historis penjualan toko ritel.

## 📁 Struktur Project
- `notebooks/model.ipynb` – Notebook utama berisi pemodelan
- `dataset/` – Berisi dataset yang digunakan

## 🧰 Tools
- Python (pandas, sklearn, matplotlib)
- Google Colab Notebook
- GitHub

## 📈 Hasil Model
Model regresi linier menghasilkan sebagai berikut:
* R² Score: 0.6161 → Artinya model bisa menjelaskan 61.6% variasi log(harga). Untuk data properti yang biasanya banyak faktor eksternal (lokasi detail, kondisi bangunan, dll).
* MAE 0.1676 di log scale setara dengan error sekitar: 0.1826 atau ±18% kesalahan relatif rata-rata dari harga.
* RMSE 0.218 di log scale juga berarti kesalahan prediksi kira-kira ±24% dari harga asli.