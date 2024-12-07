# 🛒 E-Commerce Sales Data Analysis

## 📄 Background
Perusahaan menghadapi tantangan untuk meningkatkan penjualan dan memahami faktor-faktor yang memengaruhi hasil penjualan. Dengan banyaknya produk dan segmen pasar, perusahaan perlu mengidentifikasi tren penjualan, produk yang paling menguntungkan, serta area yang membutuhkan perhatian lebih. Oleh karena itu, analisis data penjualan yang lebih mendalam diperlukan untuk mengoptimalkan strategi pemasaran dan pengelolaan produk.

## 🎯 Objectives
Tujuan dari proyek ini adalah untuk:
1. Menganalisis tren penjualan bulanan untuk memahami pola musiman.
2. Mengidentifikasi produk dengan penjualan tertinggi.
3. Menghitung margin laba dan mengevaluasi produk serta segmen yang paling menguntungkan.
4. Memberikan rekomendasi strategis untuk meningkatkan penjualan dan efisiensi operasional.

## 📊 Data Overview
Data yang digunakan dalam proyek ini adalah data penjualan e-commerce yang mencakup informasi berikut:

### Struktur Data

| **Kolom**              | **Deskripsi**                                        |
|------------------------|------------------------------------------------------|
| `Order ID`             | ID unik untuk setiap transaksi pesanan               |
| `Order Date`           | Tanggal pesanan dilakukan                           |
| `Ship Date`            | Tanggal pengiriman barang                           |
| `Ship Mode`            | Metode pengiriman produk (misal: Second Class)       |
| `Customer ID`          | ID unik untuk pelanggan                              |
| `Customer Name`        | Nama pelanggan                                       |
| `Segment`              | Segmen pelanggan (misal: Consumer, Corporate)        |
| `Country`              | Negara pelanggan                                    |
| `City`                 | Kota pelanggan                                       |
| `State`                | Provinsi pelanggan                                   |
| `Postal Code`          | Kode pos pelanggan                                  |
| `Region`               | Wilayah (misal: South, West)                         |
| `Product ID`           | ID unik untuk setiap produk                         |
| `Category`             | Kategori produk (misal: Furniture, Office Supplies)  |
| `Sub-Category`         | Sub-kategori produk (misal: Chairs, Bookcases)       |
| `Product Name`         | Nama produk                                          |
| `Sales`                | Penjualan produk dalam satuan mata uang              |
| `Quantity`             | Jumlah unit produk yang terjual                     |
| `Discount`             | Persentase diskon yang diberikan                    |
| `Profit`               | Keuntungan yang didapatkan dari penjualan produk    |
| `Calendar`             | Bulan transaksi dilakukan                           |
| `Month`                | Bulan transaksi dilakukan                           |
| `Year`                 | Tahun transaksi dilakukan                           |

### Contoh Data

| Order ID      | Order Date  | Ship Date   | Ship Mode     | Customer ID | Customer Name | Segment  | Country       | City        | State    | Postal Code | Region | Product ID    | Category        | Sub-Category | Product Name                             | Sales     | Quantity | Discount | Profit   | Calendar | Month | Year |
|---------------|-------------|-------------|---------------|-------------|---------------|----------|---------------|-------------|----------|-------------|--------|---------------|-----------------|--------------|-------------------------------------------|-----------|----------|----------|----------|----------|-------|------|
| CA-2016-152156| 08/11/2016  | 11/11/2016  | Second Class  | CG-12520    | Claire Gute   | Consumer | United States | Henderson   | Kentucky | 42420       | South  | FUR-BO-10001798| Furniture       | Bookcases    | Bush Somerset Collection Bookcase        | $261,96   | 2        | 0%       | $41,91   | 8        | Nov   | 2016 |
| CA-2016-152156| 08/11/2016  | 11/11/2016  | Second Class  | CG-12520    | Claire Gute   | Consumer | United States | Henderson   | Kentucky | 42420       | South  | FUR-CH-10000454| Furniture       | Chairs       | Hon Deluxe Fabric Upholstered Stacking Chairs | $731,94   | 3        | 0%       | $219,58  | 8        | Nov   | 2016 |
| CA-2016-138688| 12/06/2016  | 16/06/2016  | Second Class  | DV-13045    | Darrin Van Huff | Corporate | United States | Los Angeles | California | 90036       | West   | OFF-LA-10000240| Office Supplies | Labels       | Self-Adhesive Address Labels for Typewriters | $14,62    | 2        | 0%       | $6,87    | 12       | Jun   | 2016 |

## ❓ Business Questions
Beberapa pertanyaan bisnis yang ingin dijawab melalui analisis data ini:
1. Berapa total penjualan, laba, jumlah produk terjual, dan margin laba yang dihasilkan?
2. Bagaimana tren penjualan setiap bulannya?
3. Bagaimana komposisi penjualan berdasarkan segmen pasar?
4. Produk apa saja yang memiliki penjualan tertinggi?

## 🔬 Methodology

Tools: Microsoft Excel   
Proyek ini menggunakan metode berikut untuk analisis data penjualan:

### 1. Collection (Pengumpulan Data)
   - Pengumpulan data penjualan dilakukan dari platform MySkill dalam format Excel. Data yang dikumpulkan mencakup informasi mengenai transaksi penjualan, pelanggan, dan produk yang dijual.

### 2. Cleaning (Pembersihan Data)
   Proses pembersihan data dilakukan untuk memastikan kualitas dan konsistensi data. Langkah-langkah pembersihan meliputi:
   - Menghapus baris data yang hilang atau tidak relevan.
   - Menghapus duplikat data yang tercatat lebih dari satu kali.
   - Mengonversi kolom tanggal menjadi format yang sesuai untuk analisis.
   - Mengonversi kolom "Sales" dan "Profit" ke dalam mata uang dolar AS.
   - Mengekstrak kolom "Order Date" untuk membuat kolom baru seperti "Calendar", "Month", dan "Year" untuk analisis lebih lanjut.

### 3. Exploratory Data Analysis (EDA)
   Pada tahap ini, analisis eksplorasi dilakukan untuk mendapatkan wawasan awal mengenai distribusi dan pola data. Beberapa teknik yang digunakan adalah:
   - **Analisis Deskriptif**: Menganalisis distribusi penjualan berdasarkan kategori produk, segmen pasar, dan lokasi untuk memahami bagaimana produk terjual di berbagai dimensi.
   - **Trend Analysis (Analisis Tren)**: Menganalisis tren penjualan per bulan untuk memahami pola musiman atau fluktuasi penjualan sepanjang waktu.
   - **Pivot Tables (Tabel Pivot)**: Membuat tabel pivot untuk merangkum total penjualan, jumlah produk terjual, dan laba berdasarkan produk, bulan, dan segmen pasar.
   - **Top 10 Produk**: Mengidentifikasi 10 produk dengan penjualan tertinggi berdasarkan data yang ada, yang dapat memberikan wawasan mengenai produk yang paling diminati oleh pelanggan.
   - **Analisis Margin Laba**: Menghitung margin laba untuk setiap produk dan kategori untuk mengetahui produk mana yang paling menguntungkan bagi perusahaan.

### 4. Visualization (Visualisasi Data)
   Untuk memudahkan pemahaman hasil analisis, visualisasi data digunakan melalui berbagai cara:
   - **Dashboard Excel**: Membuat dashboard interaktif di Excel yang menunjukkan tren penjualan, produk terlaris, serta analisis berdasarkan bulan, kategori, dan segmen pasar. Ini memungkinkan pemangku kepentingan untuk melihat gambaran umum yang jelas dan mudah dipahami.
   - **Grafik dan Visualisasi**: Menggunakan grafik garis dan batang untuk menunjukkan tren penjualan per bulan dan menampilkan 10 produk terlaris berdasarkan penjualan. Grafik ini membantu untuk menampilkan data secara visual sehingga lebih mudah menganalisis perubahan dan pola penjualan.

   Berikut adalah dashboard visualisasi dari data penjualan yang telah dianalisis.

  ![Sales Dashboard](https://github.com/listiangr/Ecommerce_Sales_Data_Analysis_Using_Excel/blob/main/Sales%20Dashboard.png?row=true)

  
## 📈 Insight
Beberapa wawasan yang ditemukan dari analisis data penjualan:
1. Penjualan mengalami fluktuasi sepanjang tahun. Bulan dengan penjualan tertinggi adalah November ($352,461), diikuti oleh Desember ($325,294), sedangkan bulan dengan penjualan terendah adalah Januari ($94,925).
2. Margin keuntungan (profit margin) cenderung berada di kisaran 10-17%, dengan margin tertinggi pada bulan Februari (17%).
3. Segmen Consumer menyumbang setengah dari total penjualan (50%, $1,161,401), diikuti oleh Corporate (31%, $706,146) dan Home Office (19%, $429,653).
4. Produk dengan kontribusi penjualan terbesar adalah Canon imageCLASS 2200 Advanced Copier ($61,600), jauh melebihi produk lainnya.
5. Produk-produk lain dalam daftar top 10 sebagian besar adalah alat kantor seperti mesin binding, printer, dan kursi kerja.

## 💡 Recommendation
Berdasarkan hasil analisis, berikut adalah beberapa rekomendasi:
1. Fokus pada strategi pemasaran intensif di bulan-bulan dengan penjualan rendah, seperti Januari dan Februari. Misalnya, melalui promosi awal tahun, diskon produk, atau bundling untuk meningkatkan daya tarik pelanggan.
2. Karena segmen Consumer mendominasi penjualan, perlu dilakukan upaya untuk meningkatkan penetrasi ke segmen Corporate dan Home Office melalui penawaran produk atau layanan yang sesuai, seperti paket volume tinggi atau layanan purna jual.
3. Mengkaji produk dengan profit margin rendah untuk mengidentifikasi peluang efisiensi biaya atau meningkatkan harga pada produk yang memiliki permintaan tinggi tetapi margin rendah.
4. Memprioritaskan stok dan promosi untuk produk terlaris seperti Canon imageCLASS 2200 Advanced Copier. Selain itu, dapat dipertimbangkan untuk memperkenalkan produk pelengkap untuk mendorong pembelian tambahan.
5. Mengingat puncak penjualan terjadi pada November dan Desember, perusahaan dapat memaksimalkan momen ini dengan promosi akhir tahun, penawaran diskon, atau kampanye liburan untuk meningkatkan penjualan lebih lanjut.

## 📌 Conclusion
Proyek ini memberikan wawasan yang berharga mengenai faktor-faktor yang memengaruhi penjualan dan margin laba perusahaan. Dengan menganalisis tren penjualan, produk yang menguntungkan, serta segmen pasar, perusahaan dapat membuat keputusan yang lebih baik untuk meningkatkan strategi pemasaran dan pengelolaan stok. Berdasarkan temuan analisis, perusahaan dapat mengambil langkah-langkah strategis untuk memaksimalkan pertumbuhan penjualan dan margin laba.

