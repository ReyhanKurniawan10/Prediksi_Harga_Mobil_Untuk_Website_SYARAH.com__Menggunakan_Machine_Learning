# 1. Project Overview
Proyek ini menganalisis pasar mobil bekas di Arab Saudi untuk mendapatkan insight, membantu pengambilan keputusan harga, dan mengidentifikasi faktor-faktor utama yang memengaruhi harga mobil. Fokus utama adalah membangun model prediksi berbasis machine learning untuk memperkirakan harga pasar yang adil berdasarkan atribut mobil, sehingga membantu penjual dan pembeli membuat keputusan yang lebih tepat.
Tujuan Utama:
Tujuan 1: Menganalisis tren dan pola pada pasar mobil bekas, termasuk pengaruh fitur mobil terhadap harga.
Tujuan 2: Membangun dan mengevaluasi model machine learning untuk memprediksi harga mobil secara akurat.
Tujuan 3: Memberikan rekomendasi berbasis data untuk strategi penentuan harga di platform jual beli mobil online.

# 2. Data Sources
- Dataset: Data listing mobil bekas dari syarah.com (platform jual beli mobil online di Arab Saudi).
- Fitur meliputi: Type, Region, Make, Gear_Type, Origin, Options, Year, Engine_Size, Mileage, Negotiable, dan Price.
- Total: 5.624 baris yang merepresentasikan setiap unit mobil yang dijual.

# Technologies Used
- **Programming Language:** Python (Pandas, NumPy)
- **Machine Learning:** Scikit-learn, XGBoost
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Version Control:** Git

# 4 Project Structure
```
├── README.md           <- Penjelasan utama proyek untuk developer.
│
├── data
│   ├── raw             <- Data asli yang belum diubah.
│   └── clean           <- Data yang sudah dibersihkan dan siap dipakai.
│
├── model               <- Model terlatih dan hasil prediksi.
│
└── notebook            <- Notebook Jupyter untuk eksplorasi data dan pemodelan.
```

# 5 Summary of Finding

## 5.1 Business Insight
- Tahun produksi, merek, dan jarak tempuh adalah faktor yang paling berpengaruh terhadap harga mobil.
- Mobil baru dan merek premium (misalnya Mercedes, BMW) memiliki harga lebih tinggi.
- Mobil dengan jarak tempuh tinggi lebih sering memiliki harga yang bisa dinegosiasikan.
- Terdapat variasi harga antar wilayah yang konsisten, kemungkinan dipengaruhi oleh permintaan lokal.

## 5.2 Actionable Recommendation
- Mengimplementasikan fitur rekomendasi harga otomatis untuk penjual berdasarkan model ML.
- Menargetkan kampanye iklan untuk merek premium dan wilayah dengan permintaan tinggi.
- Mendorong penjual menampilkan spesifikasi detail dan menonjolkan jarak tempuh rendah.
- Menawarkan promo atau opsi pembiayaan untuk mobil lama dengan jarak tempuh tinggi.
