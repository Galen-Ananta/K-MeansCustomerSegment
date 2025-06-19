## Segmentasi Konsumen dengan Clustering K-Means

### Deskripsi Proyek

Proyek ini bertujuan untuk mengelompokkan konsumen berdasarkan karakteristik pembeliannya menggunakan metode **K-Means Clustering**. Segmentasi ini membantu perusahaan memahami perilaku konsumen dan merancang strategi pemasaran yang lebih tepat sasaran.

Dataset yang digunakan mencakup informasi berikut:
* Nama Sales Person
* Negara (Country)
* Produk yang dibeli
* Tanggal pembelian
* Total amount pembelian
* Jumlah box yang dikirim

---

### Tujuan

* Mengidentifikasi **pola pembelian konsumen** berdasarkan volume dan nilai pembelian.
* Membentuk **segmentasi strategis** untuk mendukung keputusan bisnis dan pemasaran.
* Menyajikan hasil clustering dalam bentuk **visualisasi interaktif dan naratif**.

---

### Segmentasi Konsumen

| Cluster | Nama Segmentasi         | Interpretasi                                                | Tindak Lanjut Strategis                                 |
| ------- | ----------------------- | ----------------------------------------------------------- | ------------------------------------------------------- |
| **0**   | Low Volume Explorers    | Konsumen dengan jumlah pembelian rendah dan frekuensi kecil | Edukasi produk, dorong upselling dengan diskon awal     |
| **1**   | Mass Buyers             | Pembelian volume besar, harga per unit rendah               | Optimalkan logistik, tawarkan bundling ekonomis         |
| **2**   | Premium Loyalists       | Konsisten membeli produk dengan harga tinggi                | Tawarkan program loyalitas, early-access produk premium |
| **3**   | Price-Sensitive Testers | Volume kecil, tertarik mencoba produk baru                  | Promo first-time buyer, A/B test penawaran harga        |

---

### Visualisasi

* Distribusi Cluster per Country
  Menunjukkan persebaran segmentasi (Cluster 0–3) di masing-masing negara secara grup bar chart.

* Produk dengan Penjualan Di Bawah Rata-rata Selama 3 Bulan Berturut-turut
  Menampilkan produk-produk yang secara konsisten memiliki rata-rata penjualan di bawah rata-rata global pada bulan Juni–Agustus, sehingga dapat dijadikan prioritas untuk strategi evaluasi.

* Time Series Rata-rata Penjualan per Bulan
  Grafik interaktif yang memperlihatkan perkembangan rata-rata penjualan per bulan untuk masing-masing produk, membantu melihat tren naik/turun dari waktu ke waktu.

* Time Series Penjualan per Kota (Country)
  Visual interaktif berbasis dropdown untuk mengeksplorasi tren penjualan bulanan di tiap negara. Pengguna dapat memilih negara untuk melihat dinamika penjualannya secara detail dari waktu ke waktu.

---

### Tools & Library

* Python (Pandas, Plotly)
* Scikit-learn (KMeans)
* Jupyter Notebook / VS Code

---

### Cara Menjalankan

1. Jalankan notebook `KMeans (3D).ipynb`
2. Pastikan dependensi terinstal: `pip install pandas plotly scikit-learn`
3. Data clustering otomatis dilakukan → hasil dapat divisualisasikan interaktif

---
