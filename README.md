# **Analisis Data Penjualan E-Commerce**

## **Background**
Perusahaan menghadapi tantangan untuk meningkatkan penjualan dan memahami faktor-faktor yang memengaruhi hasil penjualan. Dengan banyaknya produk dan segmen pasar, perusahaan perlu mengidentifikasi tren penjualan, produk yang paling menguntungkan, serta area yang membutuhkan perhatian lebih. Oleh karena itu, analisis data penjualan yang lebih mendalam diperlukan untuk mengoptimalkan strategi pemasaran dan pengelolaan produk.

## **Objectives**
Tujuan dari proyek ini adalah untuk:
- Menganalisis tren penjualan bulanan untuk memahami pola musiman.
- Mengidentifikasi produk dengan penjualan tertinggi.
- Menghitung margin laba dan mengevaluasi produk serta segmen yang paling menguntungkan.
- Memberikan rekomendasi strategis untuk meningkatkan penjualan dan efisiensi operasional.

## **Data Overview**
Data yang digunakan dalam proyek ini adalah data penjualan e-commerce yang mencakup informasi berikut:
- **Order ID**: Nomor identifikasi pesanan
- **Order Date**: Tanggal pemesanan produk
- **Ship Date**: Tanggal pengiriman produk
- **Ship Mode**: Metode pengiriman
- **Customer ID**: Nomor identifikasi pelanggan
- **Customer Name**: Nama pelanggan
- **Segment**: Segmen pasar pelanggan (Consumer, Corporate, Home Office)
- **Country**: Negara pelanggan
- **City**: Kota pelanggan
- **State**: Negara bagian pelanggan
- **Region**: Wilayah geografis pelanggan
- **Product ID**: Nomor identifikasi produk
- **Category**: Kategori produk (Furniture, Office Supplies, Technology)
- **Sub-Category**: Subkategori produk (Chairs, Tables, Binders)
- **Sales**: Nilai penjualan produk dalam dolar
- **Quantity**: Jumlah unit yang terjual
- **Discount**: Diskon yang diberikan
- **Profit**: Laba yang diperoleh dari penjualan produk

## **Business Questions**
Beberapa pertanyaan bisnis yang ingin dijawab melalui analisis data ini:
1. Berapa total penjualan, laba, jumlah produk terjual, dan margin laba yang dihasilkan?
2. Bagaimana tren penjualan setiap bulannya?
3. Bagaimana komposisi penjualan berdasarkan segmen pasar?
4. Produk apa saja yang memiliki penjualan tertinggi?

## **Metodologi**

Tools: Microsoft Excel   
Proyek ini menggunakan metode berikut untuk analisis data penjualan:

### 1. **Collection (Pengumpulan Data)**
   - Pengumpulan data penjualan dilakukan dari platform MySkill dalam format Excel. Data yang dikumpulkan mencakup informasi mengenai transaksi penjualan, pelanggan, dan produk yang dijual.

### 2. **Cleaning (Pembersihan Data)**
   Proses pembersihan data dilakukan untuk memastikan kualitas dan konsistensi data. Langkah-langkah pembersihan meliputi:
   - Menghapus baris data yang hilang atau tidak relevan.
   - Menghapus duplikat data yang tercatat lebih dari satu kali.
   - Mengonversi kolom tanggal menjadi format yang sesuai untuk analisis.
   - Mengonversi kolom "Sales" dan "Profit" ke dalam mata uang dolar AS.
   - Mengekstrak kolom "Order Date" untuk membuat kolom baru seperti "Calendar", "Month", dan "Year" untuk analisis lebih lanjut.

### 3. **Exploratory Data Analysis (EDA)**
   Pada tahap ini, analisis eksplorasi dilakukan untuk mendapatkan wawasan awal mengenai distribusi dan pola data. Beberapa teknik yang digunakan adalah:
   
   - **Analisis Deskriptif**: Menganalisis distribusi penjualan berdasarkan kategori produk, segmen pasar, dan lokasi untuk memahami bagaimana produk terjual di berbagai dimensi.
   - **Trend Analysis (Analisis Tren)**: Menganalisis tren penjualan per bulan untuk memahami pola musiman atau fluktuasi penjualan sepanjang waktu.
   - **Pivot Tables (Tabel Pivot)**: Membuat tabel pivot untuk merangkum total penjualan, jumlah produk terjual, dan laba berdasarkan produk, bulan, dan segmen pasar.
   - **Top 10 Produk**: Mengidentifikasi 10 produk dengan penjualan tertinggi berdasarkan data yang ada, yang dapat memberikan wawasan mengenai produk yang paling diminati oleh pelanggan.
   - **Analisis Margin Laba**: Menghitung margin laba untuk setiap produk dan kategori untuk mengetahui produk mana yang paling menguntungkan bagi perusahaan.

### 4. **Visualization (Visualisasi Data)**
   Untuk memudahkan pemahaman hasil analisis, visualisasi data digunakan melalui berbagai cara:
   
   - **Dashboard Excel**: Membuat dashboard interaktif di Excel yang menunjukkan tren penjualan, produk terlaris, serta analisis berdasarkan bulan, kategori, dan segmen pasar. Ini memungkinkan pemangku kepentingan untuk melihat gambaran umum yang jelas dan mudah dipahami.
   - **Grafik dan Visualisasi**: Menggunakan grafik garis dan batang untuk menunjukkan tren penjualan per bulan dan menampilkan 10 produk terlaris berdasarkan penjualan. Grafik ini membantu untuk menampilkan data secara visual sehingga lebih mudah menganalisis perubahan dan pola penjualan.

   Berikut adalah hasil visualisasi dari data penjualan yang telah dianalisis.


  ![Sales Dashboard](https://github.com/listiangr/Ecommerce_Sales_Data_Analysis_Using_Excel/blob/main/Sales%20Dashboard.png?row=true)

  

## **Insight**
Beberapa wawasan yang ditemukan dari analisis data penjualan:
1. Penjualan lebih tinggi pada kategori **Technology**, dengan produk seperti **Canon imageCLASS 2200** memberikan margin keuntungan tinggi.
2. Bulan **September** mencatat penjualan dan profit margin tertinggi, menunjukkan potensi peningkatan penjualan pada bulan tersebut.
3. Produk dengan margin keuntungan tinggi cenderung memiliki volume penjualan yang lebih rendah.

## **Recommendation**
Berdasarkan hasil analisis, berikut adalah beberapa rekomendasi:
1. **Fokus pada Promo Segmen Home Office**: Memperkuat promosi pada produk **Canon imageCLASS 2200** dan produk serupa untuk meningkatkan penjualan di segmen **Home Office**.
2. **Tingkatkan Pemasaran di Bulan Februari**: Mengintensifkan pemasaran pada bulan **Februari** untuk memanfaatkan potensi peningkatan penjualan.
3. **Optimalkan Produk Unggulan**: Menjaga stok dan strategi pemasaran produk dengan margin keuntungan tinggi untuk memaksimalkan profit.
4. **Kampanye Diskon pada Produk dengan Penurunan Penjualan**: Menawarkan diskon untuk produk yang penjualannya menurun untuk merangsang pembelian.
5. **Evaluasi Stok Berdasarkan Tren Penjualan**: Menyesuaikan stok produk berdasarkan permintaan dan tren penjualan untuk menghindari overstock atau kekurangan stok.

## **Conclusion**
Proyek ini memberikan wawasan yang berharga mengenai faktor-faktor yang memengaruhi penjualan dan margin laba perusahaan. Dengan menganalisis tren penjualan, produk yang menguntungkan, serta segmen pasar, perusahaan dapat membuat keputusan yang lebih baik untuk meningkatkan strategi pemasaran dan pengelolaan stok. Berdasarkan temuan analisis, perusahaan dapat mengambil langkah-langkah strategis untuk memaksimalkan pertumbuhan penjualan dan margin laba.
