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

### 🧩 Segmentasi Konsumen

| Cluster | Nama Segmentasi         | Interpretasi                                                | Tindak Lanjut Strategis                                 |
| ------- | ----------------------- | ----------------------------------------------------------- | ------------------------------------------------------- |
| **0**   | Low Volume Explorers    | Konsumen dengan jumlah pembelian rendah dan frekuensi kecil | Edukasi produk, dorong upselling dengan diskon awal     |
| **1**   | Mass Buyers             | Pembelian volume besar, harga per unit rendah               | Optimalkan logistik, tawarkan bundling ekonomis         |
| **2**   | Premium Loyalists       | Konsisten membeli produk dengan harga tinggi                | Tawarkan program loyalitas, early-access produk premium |
| **3**   | Price-Sensitive Testers | Volume kecil, tertarik mencoba produk baru                  | Promo first-time buyer, A/B test penawaran harga        |

---

### 📈 Visualisasi


* **Distribusi Cluster per Country**: Menunjukkan persebaran segmentasi di tiap negara.

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
