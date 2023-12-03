# BAB 1
## A. PENDAHULUAN
Dalam era digital yang terus berkembang, akses mudah ke layanan internet telah meresapi kehidupan sehari-hari masyarakat Indonesia. Perkembangan ini tidak hanya menciptakan kemudahan akses, tetapi juga mengubah paradigma interaksi sosial melalui media sosial seperti Twitter, Instagram, dan Facebook. Dalam konteks ini, masyarakat tidak hanya konsumen informasi, tetapi juga aktor yang berpartisipasi aktif, menggambarkan pandangan dan perasaan mereka melalui unggahan gambar dan komentar.

Pentingnya akses mudah ke internet dan penggunaan media sosial dalam kehidupan sehari-hari telah mengilhami penelitian dan eksplorasi lebih lanjut mengenai pemahaman sentimen masyarakat. Data yang berasal dari komentar-komentar di media sosial dapat menjadi sumber daya yang berharga untuk penelitian berbasis sentimen, mencakup berbagai topik seperti sentiment Masyarakat terhadap isu yang sedang hangat saait ini yaitu pemilihan presiden 2024. Studi kasus ini akan membuka peluang untuk melihat bagaimana masyarakat merespons peristiwa politik yang krusial melalui media sosial.

Seiring dengan perkembangan teknologi, pendekatan yang melibatkan webservis dan cloud computing semakin mendapatkan perhatian. Studi kasus pemilihan presiden 2024 akan dianalisis dengan menggunakan machine learning dengan algoritma pemodelan Naïve Bayes Classifier yang dibangun dengan bahasa pemrograman Python. Python dipilih untuk pengembangan model machine learning karena python merupakan Bahasa yang popular digunakan dalam pengembangan model machine learning.

Untuk menampilkan hasil dari pemodelan, frontend dibangun menggunakan HTML dengan framwork css Bulma dan Javascript standar Es6. Untuk kebersihan kode Javascript akan diunggah menjadi CDN dengan Jsdelivr. Selain memberikan wawasan terhadap sentimen masyarakat, tutorial ini juga akan memberikan panduan praktis dalam mengimplementasikan teknologi-teknologi tersebut. 

Lalu untuk menghubungkan model yang dibangung menggunkan Python, dibangun juga Backend menggunakan Golang untuk mengola database dan memanggil model NBC yang akan menganalisis data. Untuk mempermudah penggunaan backend oleh frontend, dibangunlah webservis menggunakan Google Cloud Function yang akan memanggil package backend dan menjadikannya Api (application programming interface) sehingga mempermudah pemanggilan fungsi fungsi pada backend.

Dengan pendekatan yang berbasis pada kasus pemilihan presiden 2024, serta penggunaan teknologi webservis, cloud computing, dan front-end development, buku tutorial ini bertujuan memberikan pemahaman mendalam kepada pembaca tentang analisis sentimen yang dapat diterapkan pada berbagai konteks dalam era digital ini.

## B. TUJUAN INTRUKSIONAL DAN CAPAIAN PEMBELAJARAN
Dalam perancangan buku tutorial ini, tujuan instruksional menjadi fondasi utama untuk memandu proses pembelajaran. Terdapat dua jenis tujuan instruksional yang relevan, yaitu Tujuan Instruksional Umum (TIU) dan Tujuan Instruksional Khusus (TIK).
a)	Tujuan Instruksional Umum (TIU)
Setelah menyelesaikan tutorial ini, peserta didik diharapkan mampu:
•	Memahami konsep dan prinsip machine learning, khususnya algoritma pemodelan Naïve Bayes Classifier.
•	Membangun model machine learning dengan bahasa pemrograman Python.
•	Menampilkan hasil dari pemodelan menggunakan HTML, CSS, dan JavaScript.
•	Menghubungkan model machine learning dengan backend menggunakan Golang.
•	Membangun webservis menggunakan Google Cloud Function.

Tujuan instruksional umum ini dirumuskan dengan mengacu pada topik tutorial yang diberikan. Tujuan ini bersifat umum dan tidak spesifik pada materi-materi tertentu. Tujuan ini juga dirumuskan dengan menggunakan kata kerja operasional yang dapat diukur, sehingga dapat diamati apakah peserta didik telah mencapai tujuan tersebut atau belum.

Berikut adalah penjelasan dari masing-masing tujuan instruksional umum:
•	Memahami konsep dan prinsip machine learning, khususnya algoritma pemodelan Naïve Bayes Classifier. Tujuan ini mencakup pemahaman peserta didik tentang konsep-konsep dasar machine learning, seperti supervised learning, unsupervised learning, dan reinforcement learning. Selain itu, peserta didik juga diharapkan memahami prinsip kerja algoritma pemodelan Naïve Bayes Classifier.
•	Membangun model machine learning dengan bahasa pemrograman Python. Tujuan ini mencakup kemampuan peserta didik untuk menerapkan konsep-konsep machine learning dalam bahasa pemrograman Python. Peserta didik diharapkan dapat memahami sintaks dan fungsi-fungsi Python yang diperlukan untuk membangun model machine learning.
•	Menampilkan hasil dari pemodelan menggunakan HTML, CSS, dan JavaScript. Tujuan ini mencakup kemampuan peserta didik untuk menampilkan hasil dari pemodelan machine learning menggunakan bahasa pemrograman HTML, CSS, dan JavaScript. Peserta didik diharapkan dapat memahami struktur dan elemen-elemen HTML, CSS, dan JavaScript yang diperlukan untuk menampilkan data hasil pemodelan.
•	Menghubungkan model machine learning dengan backend menggunakan Golang. Tujuan ini mencakup kemampuan peserta didik untuk menghubungkan model machine learning dengan backend menggunakan bahasa pemrograman Golang. Peserta didik diharapkan dapat memahami sintaks dan fungsi-fungsi Golang yang diperlukan untuk menghubungkan model machine learning dengan backend.
•	Membangun webservis menggunakan Google Cloud Function. Tujuan ini mencakup kemampuan peserta didik untuk membangun webservis menggunakan Google Cloud Function. Peserta didik diharapkan dapat memahami konsep dan prinsip webservis, serta cara membangun webservis menggunakan Google Cloud Function.
•	Tujuan instruksional umum ini dapat digunakan sebagai acuan dalam mengembangkan tujuan instruksional khusus (TIK) untuk setiap materi yang akan dipelajari dalam tutorial.




# BAB 2