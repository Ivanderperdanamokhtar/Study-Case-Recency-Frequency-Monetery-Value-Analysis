# RFM Analysis

**RFM Analysis** adalah proyek analisis perilaku pelanggan menggunakan metode **RFM** (Recency, Frequency, Monetary) untuk memahami segmentasi pelanggan dan memberikan wawasan yang relevan dalam meningkatkan loyalitas serta retensi pelanggan.

## Apa itu RFM?

RFM adalah metode analisis pelanggan berbasis data yang mengukur:
1. **Recency (Kedekatan Waktu):** Seberapa baru pelanggan terakhir kali melakukan pembelian.
2. **Frequency (Frekuensi):** Seberapa sering pelanggan melakukan pembelian.
3. **Monetary Value (Nilai Transaksi):** Total nilai pembelian pelanggan dalam satu periode tertentu.

### Tujuan Analisis RFM:
- Mengidentifikasi **pelanggan bernilai tinggi**.
- Mengenali **pelanggan berisiko churn**.
- Merancang strategi promosi yang lebih personal dan relevan untuk **meningkatkan loyalitas dan pendapatan**.

---

## Studi Kasus: CozyMart

CozyMart adalah toko daring yang menjual kebutuhan rumah tangga dan gaya hidup. Meskipun jumlah pelanggan meningkat, perusahaan menghadapi beberapa tantangan seperti stagnasi pendapatan, tingkat respons rendah terhadap promosi, dan ketergantungan pada diskon besar. 

### Masalah Bisnis:
1. **Stagnasi Pendapatan:** Banyak pelanggan baru hanya melakukan satu pembelian, sementara pelanggan lama mulai tidak aktif.
2. **Tingkat Respons Rendah:** Promosi email memiliki tingkat pembukaan hanya 12%, dengan konversi pembelian sebesar 2%.
3. **Ketergantungan pada Diskon:** Penjualan hanya meningkat saat diskon besar, tetapi margin laba tertekan.
4. **Kurangnya Pemahaman Pelanggan:** Promosi seragam membuat kampanye pemasaran kurang efektif.

### Tujuan Analisis:
- Mengidentifikasi pelanggan terbaik dan pelanggan berisiko churn.
- Mengoptimalkan promosi berdasarkan perilaku pelanggan.
- Meningkatkan efisiensi pemasaran dan loyalitas pelanggan.

---

## Metodologi

### 1. Data yang Digunakan:
Dataset pelanggan CozyMart mencakup:
- **Tanggal pembelian terakhir** (Last Purchase Date).
- **Total pembelian** (Total Purchases).
- **Nilai transaksi seumur hidup** (Lifetime Value).

### 2. Skor RFM:
Setiap pelanggan diberi skor dari 1 hingga 5 untuk masing-masing dimensi RFM:
- **Recency:** Pelanggan dengan pembelian terbaru diberi skor lebih tinggi.
- **Frequency:** Pelanggan dengan pembelian lebih sering diberi skor lebih tinggi.
- **Monetary:** Pelanggan dengan nilai pembelian lebih besar diberi skor lebih tinggi.

### 3. Segmentasi Pelanggan:
Berdasarkan skor RFM, pelanggan dikelompokkan ke dalam segmen berikut:
- **Champions:** Pelanggan terbaik dengan skor tinggi di semua dimensi.
- **Loyal Customers:** Pelanggan setia dengan frekuensi pembelian tinggi.
- **At Risk:** Pelanggan bernilai tinggi tetapi jarang bertransaksi akhir-akhir ini.
- **Hibernating:** Pelanggan yang tidak aktif dan jarang berbelanja.
- **Promising:** Pelanggan potensial untuk ditingkatkan menjadi pelanggan bernilai tinggi.

---

## Temuan Utama

### 1. Pelanggan Bernilai Tinggi:
Pelanggan dengan skor **RFM = 555** adalah segmen terbaik yang menunjukkan:
- **Aktivitas terkini:** Baru-baru ini melakukan pembelian.
- **Frekuensi tinggi:** Sering berbelanja.
- **Nilai tinggi:** Memberikan kontribusi besar terhadap pendapatan.

### 2. Pelanggan Berisiko Churn:
Pelanggan dengan skor **R = 1 atau 2 dan F = 1 atau 2** memerlukan perhatian khusus untuk mencegah churn.

### 3. Responsivitas Terhadap Promosi:
Pelanggan dengan **Recency dan Frequency tinggi (R = 4 atau 5, F = 4 atau 5)** lebih mungkin merespons promosi yang relevan.

---

## Rekomendasi Bisnis

### 1. Tingkatkan Loyalitas Pelanggan:
- Buat program loyalitas eksklusif untuk segmen **Champions**.
- Kirim pesan penghargaan kepada pelanggan dengan nilai transaksi besar.

### 2. Retensi Pelanggan Berisiko:
- Luncurkan kampanye "We Miss You" untuk pelanggan yang sudah lama tidak aktif.
- Berikan insentif seperti diskon bersyarat atau rekomendasi produk yang relevan.

### 3. Kurangi Ketergantungan pada Diskon:
- Gunakan strategi bundling produk untuk meningkatkan nilai tanpa mengurangi margin.
- Berikan promosi non-diskon seperti pengiriman gratis atau hadiah kecil.

### 4. Optimalkan Promosi Berdasarkan Segmentasi:
- Tawarkan akses eksklusif ke produk baru untuk **Champions**.
- Kirimkan penawaran waktu terbatas kepada **Promising** untuk meningkatkan keterlibatan.

---
## Teknologi yang Digunakan
- **Python:** Pandas, Matplotlib, Seaborn
- **Jupyter Notebook**
- **Library Visualisasi:** Matplotlib, Seaborn

---

Dengan analisis ini, CozyMart dapat meningkatkan loyalitas pelanggan, mengoptimalkan kampanye pemasaran, dan mendorong pertumbuhan pendapatan secara berkelanjutan.
