## AI Web Deployment

Projek ini untuk mendeteksi citra tangan gunting, batu, dan kertas menggunakan dataset rps.

Berikut adalah sample dari Dataset

![image](https://github.com/noviaadelia/Web-Deployment/assets/71584786/99293d8d-1830-459c-b307-2ed07e504424)

Metode yang digunakan untuk melatih model adalah EfficienNetB0. EfficientNetB0 adalah salah satu model arsitektur jaringan saraf tiruan (neural network) yang dirancang untuk tugas klasifikasi gambar. Model ini dikembangkan oleh tim Google Brain pada tahun 2019. Keunggulan utama dari EfficientNet adalah efisiensinya dalam menggunakan sumber daya komputasi, sehingga memberikan kinerja yang baik dengan ukuran model yang lebih kecil dibandingkan dengan arsitektur lainnya.EfficientNet memanfaatkan skala resolusi gambar, kedalaman jaringan (jumlah lapisan atau depth), dan lebar jaringan (jumlah filter atau width) secara optimal. Ini dicapai dengan menggunakan parameter skala (scale parameter) yang disesuaikan untuk menentukan ukuran model yang sesuai dengan tugas tertentu. Berikut adalah arsitektur dari EfficientNetB0 :

![image](https://github.com/noviaadelia/Web-Deployment/assets/71584786/c2fe7b7e-e71d-4f89-a404-9187fc519022)

Berikut adalah grafik Accuracy dan Loss Training dan Validation

![image](https://github.com/noviaadelia/Web-Deployment/assets/71584786/48ff61c3-0abd-44fe-9877-f34aeb9669e6)

![image](https://github.com/noviaadelia/Web-Deployment/assets/71584786/1b5173ed-7dfc-4851-977b-623458f58325)

Setelah model dilatih, kemudian model disimpan dengan ekstensi h5 dan deploy menggunakan Flask. 
Web deployment dengan Flask mengacu pada proses mempublikasikan atau mengekspor aplikasi web yang dikembangkan menggunakan framework Flask. Flask adalah salah satu framework web mikro untuk Python yang memungkinkan pengembang untuk membuat aplikasi web dengan mudah dan cepat.
