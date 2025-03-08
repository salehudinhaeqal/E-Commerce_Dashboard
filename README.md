# 📊 Streamlit E-Commerce Dashboard

Dashboard ini dibuat menggunakan **Streamlit** untuk menganalisis data e-commerce berdasarkan dataset transaksi yang tersedia.

## 📥 Instalasi
### 1. Persyaratan
Pastikan Anda telah menginstal **Python** dan pustaka yang diperlukan. Semua pustaka yang digunakan dapat ditemukan dalam berkas `requirements.txt`.

### 2. Instalasi Dependensi
Jalankan perintah berikut untuk menginstal semua dependensi:
```sh
pip install -r requirements.txt
```

### 3. Menjalankan Dashboard
Setelah semua dependensi terinstal, jalankan aplikasi dengan perintah berikut:
```sh
streamlit run dashboard.py
```

## 📄 Dataset
Dataset yang digunakan dalam analisis ini adalah **all_data.csv**. Pastikan file tersebut berada di dalam direktori yang sama dengan `dashboard.py` agar aplikasi berjalan dengan benar.

## 📊 Fitur
- Menampilkan **ringkasan data** pesanan, produk, dan pendapatan.
- Visualisasi **produk dan kategori terlaris**.
- Analisis **pola pembelian berdasarkan waktu**.
- Filter data berdasarkan **rentang tanggal transaksi**.

## 📂 Struktur Direktori
```
submission
├───dashboard
| ├───main_data.csv
| └───dashboard.py
├───data
| ├───data_1.csv
| └───data_2.csv
├───notebook.ipynb
├───README.md
└───requirements.txt
└───url.txt

## 📝 Lisensi
Proyek ini dibuat untuk keperluan edukasi dan tidak untuk penggunaan komersial.

---
**© 2025 Haeqal Salehudin**