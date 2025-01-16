Linier Regresi untuk Menentukan Harga Penggunaan Rideshare Uber dan Lyft
About Dataset
Context
- Project ini menggunakan model Linier Regresi untuk menentukan harga yang harus dikeluarkan untuk menggunakan rideshare Uber ataupun Lyft. Data yang digunakan merupakan dataset Uber and Lyft Dataset Boston, MA yang mencatat pemesanan perjalanan taksi Uber dan Lyft di Kota Boston selama November-Desember 2018. Dataset ini terdiri dari 693071 baris dengan total kolom sebanyak 57 tentang data harga perjalanan menggunakan taksi Uber & Lyft berdasarkan waktu, penggandaan harga (surge multiplier), jarak, dan keadaan cuaca pada saat itu. Adapun variabel dependen dari data yang digunakan adalah variabel price.
- Model Linier Regression digunakan untuk mengetahui pengaruh waktu, penggandaan hargam jarak, dan keaadan cuaca terhadap variasi harga serta mendapatkan model prediksi untuk harga armada Uber/Lyft berdasarkan faktor-faktor yang diketahui.
- Link dataset: https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma/data
Objective
- Mampu memahami konsep regression dengan Linear Regression
- Mampu mempersiapkan data untuk digunakan dalam model Linear Regression 
- Mampu mengimplementasikan Linear Regression untuk membuat prediksi
Reporting
Dataset Uber and Lyft Dataset Boston, MA terdiri dari 693071 baris dan 57 kolom. Setelah dilakukan eksplorasi, didapatkan beberal informasi di antaranya:
1. Jumlah penggunaan layanan Uber lebih tinggi dibandingkan dengan layanan Lyft. Layanan Uber digunakan oleh 51% dari total pengguna, yaitu sebanyak 330.568 pengguna, sementara layanan Lyft digunakan oleh 48,2% dari total pengguna, yaitu 307.408 pengguna. Perbedaan jumlah pengguna antara Uber dan Lyft adalah 23.160.
2. Faktor yang menyebabkan jumlah pengguna layanan Uber lebih banyak adalah tarifnya yang lebih murah dibanding layanan Lyft. Rata-rata harga untuk Lyft adalah 17.35, sedangkan Uber memiliki rata-rata harga sebesar 15.80. Selisih harga rata-rata antara Uber dan Lyft adalah sebesar 1.55
3. Layanan Uber dan Lyft seringkali ramai digunakan pengguna pada jam 00.00 dan mulai sepi pada pukul 08.00. Penggunaan layanan mulai stabil pada pukul 10.00 hingga 18.00
4. Tarif penggunaan layanan Uber dan Lyft cenderung meningkat seiring dengan bertambahnya jarak tempuh perjalanan. Namun, terdapat beberapa faktor lain yang mungkin mempengaruhi tarif layanan, seperti diskon, promosi, tipe mobil, dan kondisi lainnya.
