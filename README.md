# Project-Based: Business Intelligence Analyst

### Bank Muamalat Business Intelligence Analyst Project Based Internship Program

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun solusi **Business Intelligence (BI)** berbasis data transaksi penjualan PT Sejahtera Bersama. Data diolah dari beberapa sumber CSV, digabungkan menjadi satu tabel master menggunakan **Google BigQuery**, kemudian divisualisasikan menggunakan **Looker Studio** untuk menghasilkan insight bisnis yang mendukung pengambilan keputusan strategis.

## 🗂️ Dataset
Proyek ini menggunakan 4 file CSV:
- **Customers.csv** – Data pelanggan
- **Orders.csv** – Data transaksi penjualan
- **Products.csv** – Data produk
- **ProductCategory.csv** – Data kategori produk

## 🧩 Relationship
Hubungan antar tabel:
| From Table                | To Table          | Primary Key     | Foreign Key |
|---------------------------|-------------------------|-----------------|-------|
| Customers                 |  Orders           | CustomerID      | CustomerID  |
| Product                   |  Orders           |  ProdNumber     |  ProdNumber |
| Category                  |Product            |  CategoryID     |  Category   |

## 🛠️ Tools & Teknologi
- **Google BigQuery** – Data processing & query
- **Looker Studio** – Data visualization & dashboard

## 📈 Dashboard & Visualisasi
Link : [Dashboard](https://lookerstudio.google.com/reporting/aa341d19-6a58-455f-a40e-fb97013b07c6)

![alt text](https://github.com/mfatarsyah/Bank-Muamalat-Business-Intelligence-Analyst-Project-Based-Internship/blob/main/Dashboard.png)


## 💡 Insight & Rekomendasi Bisnis
Berdasarkan analisis data:

- Memprioritaskan kategori produk dengan penjualan tertinggi melalui optimalisasi stok dan strategi promosi.
- Meningkatkan nilai transaksi pada kategori dengan quantity tinggi melalui strategi up selling dan bundling produk.
- Memfokuskan aktivitas pemasaran dan distribusi pada kota dengan kontribusi penjualan terbesar.
- Menerapkan promosi khusus dan penyesuaian produk pada kota dengan performa penjualan rendah.

## 👤 Author
**M Fatarsyah Hardeva**  
Business Intelligence / Data Analyst  


