# Project-KMMI-

## PENERAPAN K-MEANS++ CLUSTERING UNTUK SEGMENTASI CUSTOMER E-COMMERCE INDIA MENGGUNAKAN METODE RFM (RECENCY FREQUENCY MONETARY) 

**Latar Belakang**

Teknologi data mining pada sebuah perusahaan pada dasarnya dapat membantu mempercepat proses pengambilan keputusan secara tepat, memungkinkan perusahaan untuk mengelola informasi yang terkandung di dalam data transaksi menjadi sebuah pengetahuan (knowledge) yang baru. Melalui pengetahuan yang didapat, perusahaan dapat meningkatkan pendapatannya dan mengurangi biaya, dan pada akhirnya dimasa yang akan datang perusahaan dapat lebih kompetitif. 

Dalam project kali ini, penulis akan menganalisis data penjualan yang diperoleh dari e-commerce India. E-commerce menurut Wong (2010) adalah proses jual beli dan memasarkan barang serta jasa melalui sistem elektronik, seperti radio, televisi dan jaringan komputer atau internet. Data-data yang diperoleh dari website e-commerce tersebut tentunya akan menghasilkan insight/informasi yang berharga yang kemudian kita dapat menyimpulkan informasi yang didapat serta merekomendasikan suatu keputusan bisnis sehingga pihak e-commerce dapat memaksimalkan penjualan mereka dengan baik. 

Strategi bisnis yang digunakan adalah Customer Relationship Management, yaitu  teori yang membahas tentang hubungan perusahaan dengan pelanggan, yang memiliki tujuan untuk meningkatkan hubungan dengan tiap pelanggan demi mencapai perkembangan perusahaan yang sehat. Sehingga untuk mengimplementasikan CRM, diperlukan analisis data berdasarkan RFM. Analisis Recency, Frequency, Monetary (RFM) merupakan proses analisis perilaku pelanggan. Dalam menentukan segmentasi pelanggan, digunakan model RFM berdasarkan tiga variabel yaitu recency terakhir melakukan transaksi, frequency dari transaksi, dan monetary dari jumlah transaksi setiap pelanggan. Menurut Tsiptsis dan Chorianopoulos (2009), analisis RFM terdiri Recency, Frequency, Monetary yang memiliki pengertian sebagai berikut :

Recency merupakan variabel untuk mengukur nilai pelanggan berdasarkan rentang waktu (tanggal, bulan, tahun) transaksi terakhir pelanggan sampai saat ini. Semakin kecil rentang waktu maka nilai recency semakin besar.

Frequency merupakan variabel untuk mengukur nilai pelanggan berdasarkan jumlah transaksi yang dilakukan pelanggan dalam satu periode. Semakin banyak jumlah transaksi yang dilakukan maka nilai semakin besar. 

Monetary merupakan variabel untuk mengukur nilai pelanggan berdasarkan jumlah besaran uang yang dikeluarkan pelanggan dalam satu periode. Semakin banyak jumlah besaran uang yang dikeluarkan pelanggan maka nilai semakin besar. 

**Tujuan**

Pada project kali ini, penulis akan mengkategorikan / klasterisasi pelanggan berdasarkan ciri-ciri  pelanggan dengan RFM (Recency, Frequency, dan Monetary). Hal ini bertujuan agar mengetahui recency (kebaruan pelanggan tersebut memesan barang), frequency (seberapa sering pelanggan tersebut memesan barang), monetary (besaran uang yang dikeluarkan pelanggan), sehingga terbentuk beberapa karakter pelanggan dan mendapat informasi jumlah penjualan barang yang disukai tiap klaster dan mengetahui asal klaster tersebut berasal sehingga target customer tepat sasaran. Kemudian kebijakan promosi nya akan disesuaikan berdasarkan klaster pelanggan tersebut.  

**Sumber Data**

Sumber data yang digunakan adalah data e-commerce yang berasal dari india. Dataset tersebut dapat diakses dengan bebas melalui platform kaggle melalui tautan berikut:
https://www.kaggle.com/benroshan/ecommerce-data?select=List+of+Orders.csv 

**Metode yang digunakan** 

Metode yang digunakan adalah menggunakan penerapan K-Means++ Clustering untuk pengelompokan / segmentasi pelanggan berdasarkan prinsip RFM (Recency, Frequency, Monetary). Penulis akan menggunakan tools google colab dengan bahasa pemrograman python.

**Kesimpulan**

Informasi yang didapat dari projek analisis data kali ini adalah:

Penjualan terbanyak terjadi pada produk pada kategori clothing. Berdasarkan sub-kategori barang yang terjual, penjualan terbanyak ada pada handkerchief, disusul stole, saree. Sangat dianjurkan untuk melakukan promo/diskon pada produk tersebut karena penjualannya keuntungannya yang tinggi. T-shirt cukup menghasilkan keuntungan yang baik walaupun jumlah penjualannya kurang dari stole. Sehingga T-shirt juga sangat direkomendasikan untuk di promosikan lebih intense lagi.
Ada beberapa kerugian pada table dan chairs sehingga saya tidak merekomendasikan bagi tim bisnis untuk memberi diskon pada produk-produk tersebut, begitu pula dengan produk trousers, skirt, legging, kurti, electronic games, phones untuk saat ini karena keuntungannya masih terlalu sedikit.
Keuntungan tertinggi yang didapat berasal dari negara bagian madhya pradesh, maharashtra, rajasthan, delhi, west bengal, dan gujarat. Sehingga saya merekomendasikan untuk meningkatkan performa pemasaran pada negara bagian tersebut serta mengevaluasi penjualan pada negara bagian yang lainnya terutama pada negara bagian Haryana dan goa karena keuntungan nya sangat kecil.
Setelah bulan april 2019, penjualan mengalami penurunan drastis, sehingga harus diadakannya evaluasi mengenai pemasaran pada bulan tersebut.

Rekomendasi segmentasi pelanggan:

Gold: Fokus untuk meningkatkan pembelian customer sehingga perlu membentuk cross/Up Selling Strategy. Cross selling adalah metode untuk menawarkan produk tambahan pada konsumen. Biasanya, yang ditawarkan adalah produk yang sifatnya pelengkap atau terkait dengan produk yang dibeli.
Silver: Fokus supaya customer melakukan pembelian kembali sehingga perlu membentuk Retention Strategy, Cross/Up Selling Strategy. Customer retention adalah upaya untuk mempertahankan pelanggan yang sudah pernah membeli produk agar terus melakukan transaksi. Dapat berupa pemberian diskon/promo.
Non-Profit: Customer pada segmen ini sudah churn, maka fokus campaign untuk mengaktifkan customer kembali dengan membentuk Reactivation strategy, dengan kata lain strategi pengaktifan kembali. Reactivation strategy ini sendiri bisa menggunakan reactivation e-mail untuk develop messaging untuk reactivation campaign.     
