Projek ini untuk mendeteksi citra tangan gunting, batu, dan kertas menggunakan dataset rps

Metode yang digunakan untuk melatih model adalah EfficienNetB0. EfficientNetB0 adalah salah satu model arsitektur jaringan saraf tiruan (neural network) yang dirancang untuk tugas klasifikasi gambar. Model ini dikembangkan oleh tim Google Brain pada tahun 2019. Keunggulan utama dari EfficientNet adalah efisiensinya dalam menggunakan sumber daya komputasi, sehingga memberikan kinerja yang baik dengan ukuran model yang lebih kecil dibandingkan dengan arsitektur lainnya.EfficientNet memanfaatkan skala resolusi gambar, kedalaman jaringan (jumlah lapisan atau depth), dan lebar jaringan (jumlah filter atau width) secara optimal. Ini dicapai dengan menggunakan parameter skala (scale parameter) yang disesuaikan untuk menentukan ukuran model yang sesuai dengan tugas tertentu. Berikut adalah arsitektur dari EfficientNetB0 :
!(https://github.com/noviaadelia/Web-Deployment/blob/main/download.jpg)

Setelah model dilatih, kemudian model disimpan dengan ekstensi h5 dan deploy menggunakan Flask. 
Web deployment dengan Flask mengacu pada proses mempublikasikan atau mengekspor aplikasi web yang dikembangkan menggunakan framework Flask. Flask adalah salah satu framework web mikro untuk Python yang memungkinkan pengembang untuk membuat aplikasi web dengan mudah dan cepat.
