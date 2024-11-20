# **Proyek Analisis Data Penjualan Menggunakan Excel**

### **Deskripsi Proyek**
Proyek ini bertujuan untuk menganalisis data penjualan guna mengidentifikasi pola dan tren yang mempengaruhi volume penjualan. 
Hasil analisis ini akan memberikan wawasan untuk merumuskan strategi pemasaran, pengelolaan stok, dan perencanaan promosi yang 
lebih efektif, sehingga dapat mendukung pengambilan keputusan. 

### **Langkah-langkah Analisis**

#### **1. Ask – Menentukan Pertanyaan Bisnis**
Pada tahap ini, fokus pada pemahaman masalah yang perlu diselesaikan dan tujuan yang ingin dicapai. Beberapa pertanyaan utama 
yang diajukan meliputi:
- Berapa total penjualan, laba, jumlah produk terjual, dan margin laba yang dihasilkan?
- Bagaimana tren penjualan setiap bulannya?
- Bagaimana komposisi penjualan berdasarkan segmen pasar?
- Produk apa saja yang memiliki penjualan tertinggi?

#### **2. Prepare – Mengumpulkan dan Menyusun Data**
Data yang digunakan dalam proyek ini merupakan data penjualan berbentuk excel yang disediakan oleh platform MySkill ketika 
mengikuti pelatihan Microsoft Excel. Beberapa informasi yang terkandung dalam data penjualan tersebut antara lain:
- Order ID: Merupakan nomor identifikasi unik yang diberikan untuk setiap pesanan yang dilakukan oleh pelanggan.
- Order Date: Tanggal ketika pelanggan memesan produk.
- Ship Date: Tanggal ketika pesanan dikirim kepada pelanggan.
- Ship Mode: Metode pengiriman yang digunakan, seperti pengiriman standar atau ekspres.
- Customer ID: Nomor identifikasi unik untuk pelanggan.
- Customer Name: Nama pelanggan yang melakukan pesanan.
- Segment: Segmen pasar yang melibatkan pelanggan, seperti "Consumer", "Corporate", atau "Home Office".
- Country: Negara tempat pelanggan berada.
- City: Kota tempat pelanggan berada.
- State: Negara bagian tempat pelanggan berada.
- Postal Code: Kode pos dari alamat pelanggan.
- Region: Wilayah geografis tempat pelanggan berada, misalnya "North", "South", "East", atau "West".
- Product ID: Nomor identifikasi unik untuk produk yang dibeli.
- Category: Kategori utama dari produk, misalnya "Furniture", "Office Supplies", atau "Technology".
- Sub-Category: Subkategori produk yang lebih spesifik, seperti "Chairs", "Tables", atau "Binders".
- Product Name: Nama produk yang dibeli.
- Sales: Nilai penjualan produk dalam dolar.
- Quantity: Jumlah unit produk yang terjual.
- Discount: Diskon yang diberikan pada produk.
- Profit: Laba yang diperoleh dari penjualan produk setelah memperhitungkan biaya.

#### **3. Process – Pembersihan dan Pemrosesan Data**
Pada tahap ini, dilakukan pembersihan data untuk memastikan bahwa data yang digunakan bebas dari kesalahan dan 
siap untuk dianalisis. Berikut adalah pembersihan dan pemrosesan data yang dilakukan:
- Menghapus baris data yang hilang atau tidak relevan.
- Menghapus duplikat data yang tercatat lebih dari satu kali.
- Mengonversi kolom tanggal menjadi format yang sesuai.
- Mengonversi kolom "Sales" dan "Profit" menjadi mata uang dolar US.
- Mengekstrak kolom "Order Date" menjadi kolom baru yaitu "Calender", "Month", dan "Year". 

#### **4. Analyze – Melakukan Analisis Data**
Setelah data dibersihkan, analisis dilakukan untuk menemukan pola dan wawasan yang berguna. Beberapa metode analisis yang diterapkan meliputi:
- **Analisis Deskriptif**: Menganalisis distribusi penjualan berdasarkan kategori produk, segmen pasar, dan lokasi untuk memahami bagaimana produk terjual.
- **Trend Analysis**: Melihat tren penjualan per bulan untuk memahami pola musiman atau fluktuasi.
- **Pivot Tables**: Membuat tabel pivot untuk merangkum total penjualan, jumlah produk terjual, dan profit berdasarkan produk, bulan, dan segmen pasar.
- **Top 10 Produk**: Mengidentifikasi 10 produk dengan penjualan tertinggi berdasarkan data yang ada.
- **Analisis Margin Laba**: Menghitung margin laba untuk setiap produk dan kategori untuk melihat produk mana yang paling menguntungkan.

#### **5. Share – Menyajikan Hasil Visualisasi**
Hasil analisis disajikan dalam format yang mudah dipahami oleh stakeholder. Berikut adalah cara yang digunakan untuk menyajikan hasil analisis.
- **Dashboard Excel**: Membuat dashboard interaktif di Excel yang menunjukkan tren penjualan, produk terlaris, serta analisis berdasarkan bulan, kategori, dan segmen pasar.
- **Grafik dan Visualisasi**: Menggunakan grafik garis dan batang untuk menunjukkan tren penjualan per bulan dan top 10 produk berdasarkan penjualan.


  Berikut adalah hasil visualisasi dari data penjualan yang telah dianalisis.


  ![Sales Dashboard](https://github.com/user-attachments/assets/81282a89-f32e-4c73-b044-ddf5c5f508a2)

#### **6. Act – Mengambil Tindakan Berdasarkan Hasil Analisis**
Berdasarkan temuan analisis yang telah dilakukan, berikut adalah beberapa langkah strategis yang dapat diambil untuk meningkatkan penjualan:
1. **Fokus pada Promo Segmen Home Office:**
   - Mengingat kontribusi besar dari produk di segmen **Consumer**, khususnya produk **Canon imageCLASS 2200 Advanced Copier**, disarankan untuk lebih memfokuskan promosi pada produk serupa di segmen **Home Office**. Hal ini akan membantu meningkatkan penjualan di segmen dengan potensi pasar tinggi ini.
2. **Tingkatkan Pemasaran di Bulan Februari:**
   - Berdasarkan temuan bahwa bulan **September** mencatat penjualan dan profit margin tertinggi, strategi pemasaran yang lebih intensif pada bulan **Februari** bisa jadi langkah yang efektif untuk mendorong penjualan, dengan penekanan pada produk yang memiliki permintaan tinggi pada periode tersebut.
3. **Optimalkan Produk Unggulan:**
   - Mengingat adanya produk-produk dengan margin keuntungan yang tinggi, seperti **Canon imageCLASS 2200**, penting untuk mengoptimalkan strategi pemasaran dan stok produk ini. Dengan memfokuskan sumber daya pada produk-produk unggulan, perusahaan dapat memaksimalkan pertumbuhan penjualan serta margin keuntungan.
4. **Kampanye Diskon atau Promo pada Produk dengan Penurunan Penjualan:**
   - Untuk produk yang menunjukkan penurunan penjualan, bisa dipertimbangkan untuk mengadakan diskon atau promosi khusus guna merangsang pembelian. Hal ini juga dapat meningkatkan volume penjualan dan mencegah produk dari terjebak dalam stok yang tidak terjual.
5. **Evaluasi dan Penyesuaian Stok Berdasarkan Tren Penjualan:**
   - Mengingat tren penjualan yang tinggi pada produk tertentu di segmen tertentu, perusahaan bisa menyesuaikan stok produk secara lebih cermat dan berdasarkan permintaan yang terus berubah. Langkah ini akan menghindari overstock atau kekurangan barang yang dapat mempengaruhi performa penjualan.



