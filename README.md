# Latar Belakang
Sebuah supermarket menjual berbagai produk antara lain wine, buah-buahan, daging, ikan, produk-manis, dan produk emas. Produk-produk tersebut dijual melalui berbagai channel penjualan antara lain melalui web, catalog, dan store. Pelanggan dari supermarket tersebut beragam usia, pendapatan, level pendidikan, dan jumlah anggota keluarganya.
# Pernyataan Masalah
Memberikan gambaran untuk strategi pemasaran serta pengembangan produk yang lebih baik sesuai dengan preferensi dan perilaku pelanggan
# Data Understanding & Data Cleaning
Untuk menjawab pertanyaan diatas, maka dilakukan analisa data Supermarket Customers, cleansing data, kategorisasi ulang beberapa kolom, dan lain-lain
# 1. Analisis Demografis Usia Pelanggan
Dilakukan analisis distribusi usia pelanggan dan hubungannya dengan jumlah item belanja pelanggan
Berdasarkan histogram, uji statistik kruskal wallis, dan statistik deskriptif usia pelanggan diatas, dapat disimpulkan:
* Rentang usia terbanyak adalah antara 30 hingga 50 tahun, dengan frekuensi tertinggi mencapai hampir sekitar 500 pelanggan
* Ada beberapa pelanggan yang berada di bawah usia 20 tahun dan beberapa di atas usia 70 tahun, namun jumlahnya sangat sedikit dibandingkan dengan rentang usia 30-60 tahun
* Terdapat perbedaan yang signifikan jumlah item belanja yang dibeli pelanggan antar kelompok umur
* Pelanggan yang berbelanja di supermarket mulai dari umur 16 hingga 73 tahun. Rata-rata pelanggan yang berbelanja di supermarket tersebut sekitar umur 44 tahun, jumlah pelanggan paling banyak berumur 41 tahun
# 2. Analisis Demografis Pendapatan Pelanggan
Dilakukan analisis distribusi pendapatan pelanggan dan hubungannya dengan jumlah item belanja pelanggan
Berdasarkan histogram, uji statistik kruskal wallis, dan statistik deskriptif pendapatan pelanggan diatas, dapat disimpulkan:
* Rentang pendapatan pelanggan yang berbelanja di supermarket adalah antara 20000 hingga 80000, dengan frekuensi tertinggi di angka 40000 mencapai hampir sekitar 600 pelanggan
* Ada beberapa pelanggan yang memilii pendapatan di bawah 20000 dan beberapa di atas 100000, namun jumlahnya sangat sedikit dibandingkan dengan rentang pendapatan 20000 hingga 80000
* Tidak terdapat perbedaan yang signifikan jumlah item belanja yang dibeli pelanggan antar kelompok pendapatan
* Pelanggan yang berbelanja di supermarket memiliki pendapatan mulai dari 1730 hingga 162397. Rata-rata pendapatan pelanggan yang berbelanja di supermarket tersebut sekitar 51959, jumlah pelanggan paling banyak memiliki pendapatan sebesar 7500
# 3. Analisis Demografis Level Pendidikan Pelanggan
Dilakukan analisis distribusi level pendidikan pelanggan dan hubungannya dengan jumlah item belanja pelanggan
Berdasarkan histogram, uji statistik kruskal wallis, dan statistik deskriptif level pendidikan pelanggan diatas, dapat disimpulkan:
* Level pendidikan pelanggan yang berbelanja di supermarket adalah basic education, undergraduate, graduate, dan postgraduate, dengan frekuensi tertinggi di level graduate mencapai sekitar 1480 pelanggan
* Level pendidikan pelanggan paling sedikit adalah basic graduate dengan frekuensi 54 pelanggan
* Terdapat perbedaan yang signifikan jumlah item belanja yang dibeli pelanggan antar kelompok level pendidikan pelanggan
# 4. Analisis Demografis Jumlah Anggota Keluarga Pelanggan
Dilakukan analisis distribusi jumlah anggota keluarga pelanggan dan hubungannya dengan jumlah item belanja pelanggan
Berdasarkan histogram, uji statistik kruskal wallis, dan statistik deskriptif jumlah anggota keluarga pelanggan diatas, dapat disimpulkan:
* Rentang jumlah anggota keluarga pelanggan yang berbelanja di supermarket adalah antara 1 hingga 5 orang, dengan frekuensi tertinggi adalah pelanggan yang memiliki jumlah anggota keluarga sebanyak 3 orang
* Terdapat perbedaan yang signifikan jumlah item belanja yang dibeli pelanggan antar kelompok jumlah anggota keluarga pelanggan
* Rata-rata jumlah belanja produk paling tinggi adalah pelanggan dengan jumlah anggota keluarga hanya 1 orang, dan paling rendah adalah 4 orang anggota keluarga
# 5. Analisis Produk Penjualan Supermarket
Dilakukan analisis tren atau preferensi pelanggan untuk produk-produk seperti wine, buah-buahan, daging, ikan, produk-manis, dan produk emas
Berdasarkan piechart penjualan produk diatas dapat diketahui bahwa produk yang memiliki penjualan tertinggi adalah produk wine, dan terendah adalah fruit
# 6. Tingkat Penerimaan Pelanggan terhadap Campaign Promo
Mengevaluasi seberapa efektif  campaign promo sebelumnya berdasarkan pada berapa banyak pelanggan yang menerima tawaran dalam setiap kampanye (AcceptedCmp1 hingga AcceptedCmp5) dan tanggapan terhadap kampanye terakhir (Response).
Berdasarkan hasil line chart diatas menunjukkan bahwa penerimaan pelanggan paling banyak adalah pada pada campaign terakhir, untuk campaign promosi ke 1, 3, 4, dan 5 cenderung stagnan, namun terdapat penuruan pada campaign promo ke 2
# 7. Analisis Frekuensi Pembelian Melalui Berbagai Channel Pembelian
Analisis Frekuensi pembelian melalui berbagai saluran (NumWebPurchases, NumCatalogPurchases, NumStorePurchases)
Berdasarkan hasil barchart channel penjualan produk diatas menunjukkan bahwa penjualan produk paling tinggi melalui store langsung, kemudian dilanjutkan melalui channel web dan kemudian catalog.
# 8. Analisis Korelasi Web Visit dan Pembelian Melalui Web
Mengevaluasi hubungan antara jumlah kunjungan ke situs web perusahaan (NumWebVisitsMonth) dan jumlah pembelian melalui situs web. Apakah pelanggan yang sering mengunjungi situs web juga cenderung lebih aktif dalam berbelanja secara online?
- Korelasi antara jumlah visit pelanggan ke web dan pembelian melalui web cenderung lemah dan negatif. Ini berarti terdapat kecenderungan bahwa ketika satu variabel meningkat, variabel lainnya cenderung menurun, meskipun tidak secara kuat
- Nilai P-Value yang sangat kecil menunjukkan bahwa hubungan ini tidak terjadi secara kebetulan dalam sampel yang di analisis, sehingga hasil korelasi antara visit pelanggan ke web dan pembelian melalui web signifikan secara statistik.
- #Kesimpulan dan Rekomendasi
- Dari analisis yang telah dilakukan, dapat disimpulkan bahwa:
- Mayoritas pelanggan supermarket berumur 30 hingga 50 tahun, dengan pendapatan antara 20000 hingga 80000, level pendidikan graduate, dan memiliki jumlah anggota keluarga 3
- Produk supermarket yang paling banyak diminati oleh pelanggan adalah wine, kemudian disusul oleh meat, gold, fish, sweet products, dan yang terakhir fruit
- Berdasarkan campaign promo yang diberikan supermarket beberapa kali, penerimaan pelanggan paling banyak adalah pada pada campaign terakhir, untuk campaign promosi ke 1, 3, 4, dan 5 cenderung stagnan, namun terdapat penuruan pada campaign promo ke 2
- Channel pembelian yang paling banyak digunakan pelanggan untuk berbelanja dengan mendatangi store secara langsung, kemudian disusul pembelanjaan melalui web, dan yang terakhir melalui catalog
- Hasil korelasi antara visit pelanggan ke web dan pembelian melalui web signifikan secara statistik
Sehingga rekomendasi yang dapat diberikan adalah:
- Supermarket dapat melakukan marketing yang terpusat pada profil pelanggan yang telah dianalisis sebelumnya
- Dengan melihat preferensi pelanggan terhadap produk supermarket, maka supermarket dapat mengantisipasi stock produk yang ada berdasarkan yang paling banyak diminati hingga kurang diminati, sehingga supermarket tidak akan kehabisan stock produk
- Untuk menambah kepuasan pelanggan dalam berbelanja di supermarket, maka channel pembelian paling banyak yaitu store dapat ditambah fasilitas dan kenyamanannya, sehingga dapat menarik pelanggan lebih banyak lagi
