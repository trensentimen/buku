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


b)	Tujuan Instruksional Khusus (TIK)
Berikut adalah tujuan instruksional khusus (TIK) untuk tutorial tentang analisis sentimen pemilihan presiden 2024 menggunakan machine learning, dengan materi yang telah diganti:

Materi: Dasar-dasar Analisis Sentimen
Terminal Behavior	Conditional of Demonstration or Rest	Standard of Performance
Menjelaskan konsep sentimen, polaritas, dan skala sentimen	Peserta didik diberikan materi tentang konsep sentimen, polaritas, dan skala sentimen.	Peserta didik dapat menjelaskan konsep sentimen, polaritas, dan skala sentimen dengan benar.
Menjelaskan jenis-jenis analisis sentimen	Peserta didik diberikan materi tentang jenis-jenis analisis sentimen.	Peserta didik dapat menjelaskan jenis-jenis analisis sentimen dengan benar.
Menjelaskan kelebihan dan kekurangan analisis sentimen	Peserta didik diberikan materi tentang kelebihan dan kekurangan analisis sentimen.	Peserta didik dapat menjelaskan kelebihan dan kekurangan analisis sentimen dengan benar.

Materi: Pengumpulan Data Sentimen dan konsep crisp-dm
Terminal Behavior	Conditional of Demonstration or Rest	Standard of Performance
Menjelaskan konsep pengumpulan data sentimen	Peserta didik diberikan materi tentang konsep pengumpulan data sentimen.	Peserta didik dapat menjelaskan konsep pengumpulan data sentimen dengan benar.
Menjelaskan konsep CRISP-DM	Peserta didik diberikan materi tentang konsep CRISP-DM.	Peserta didik dapat menjelaskan konsep CRISP-DM dengan benar.
Menerapkan konsep CRISP-DM untuk mengumpulkan data sentimen	Peserta didik diberikan contoh penerapan konsep CRISP-DM untuk mengumpulkan data sentimen.	Peserta didik dapat menerapkan konsep CRISP-DM untuk mengumpulkan data sentimen dengan benar.

Materi: Naive Bayes untuk Analisis Sentimen
Terminal Behavior	Conditional of Demonstration or Rest	Standard of Performance
Menjelaskan konsep Naive Bayes	Peserta didik diberikan materi tentang konsep Naive Bayes.	Peserta didik dapat menjelaskan konsep Naive Bayes dengan benar.
Menjelaskan prinsip kerja Naive Bayes untuk analisis sentimen	Peserta didik diberikan materi tentang prinsip kerja Naive Bayes untuk analisis sentimen.	Peserta didik dapat menjelaskan prinsip kerja Naive Bayes untuk analisis sentimen dengan benar.
Membangun model Naive Bayes untuk analisis sentimen	Peserta didik diberikan contoh kode Python untuk membangun model Naive Bayes untuk analisis sentimen.	Peserta didik dapat membangun model Naive Bayes untuk analisis sentimen dengan akurasi yang tinggi.

Materi: Membangun Web Servis dengan Golang
Terminal Behavior	Conditional of Demonstration or Rest	Standard of Performance
Menjelaskan konsep web servis	Peserta didik diberikan materi tentang konsep web servis.	Peserta didik dapat menjelaskan konsep web servis dengan benar.
Menjelaskan cara membangun web servis dengan Golang	Peserta didik diberikan contoh kode Golang untuk membangun web servis.	Peserta didik dapat membangun web servis dengan Golang dengan benar.

Materi: Integrasi dengan Cloud Functions
Terminal Behavior	Conditional of Demonstration or Rest	Standard of Performance
Menjelaskan konsep Cloud Functions	Peserta didik diberikan materi tentang konsep Cloud Functions.	Peserta didik dapat menjelaskan konsep Cloud Functions dengan benar.
Menjelaskan cara mengintegrasikan web servis dengan Cloud Functions	Peserta didik diberikan contoh kode untuk mengintegrasikan web servis dengan Cloud Functions.	Peserta didik dapat mengintegrasikan web servis dengan Cloud Functions dengan benar.

Materi: Membangun Frontend dengan HTML, JAVASCRIPT dan CSS
Terminal Behavior	Conditional of Demonstration or Rest	Standard of Performance
Menjelaskan struktur HTML	Peserta didik diberikan materi tentang struktur HTML.	Peserta didik dapat menjelaskan struktur HTML dengan benar.
Menjelaskan elemen-elemen CSS	Peserta didik diberikan materi tentang elemen-elemen CSS.	Peserta didik dapat menjelaskan elemen-elemen CSS dengan benar.
Menjelaskan konsep JavaScript	Peserta didik diberikan materi tentang konsep JavaScript.	Peserta didik dapat menjelaskan konsep JavaScript dengan benar.
Membangun frontend untuk menampilkan hasil analisis sentimen	Peserta didik diberikan contoh kode HTML, CSS, dan JavaScript untuk menampilkan hasil analisis sentimen.	Peserta didik dapat membangun frontend untuk menampilkan hasil analisis sentimen dengan benar.

Materi: Mengunggah Javascript menjadi CDN
Terminal Behavior	Conditional of Demonstration or Rest	Standard of Performance
Menjelaskan konsep CDN	Peserta didik diberikan materi tentang konsep CDN.	Peserta didik dapat menjelaskan konsep CDN dengan benar.
Menjelaskan cara mengunggah Javascript ke CDN	Peserta didik diberikan materi tentang cara mengunggah Javascript ke CDN.	Peserta didik dapat mengunggah Javascript ke CDN dengan benar.
Menjelaskan manfaat mengunggah Javascript ke CDN	Peserta didik diberikan materi tentang manfaat mengunggah Javascript ke CDN.	Peserta didik dapat menjelaskan manfaat mengunggah Javascript ke CDN dengan benar.


# BAB 2
A.	PYTHON
Python merupakan bahasa pemrograman tingkat tinggi yang dibuat oleh Guido Van Rossum dan dirilis pada tahun 1991 Python juga merupakan bahasa yanng sangat populer belakangan ini. Selain itu python juga merupakan Bahasa pemrograman yang multi fungsi contohnya python dapat digunakan untuk Machine Learning dan Deep Larning. Python memiliki penulisan sintaksis yang mudah selain itu python juga memiliki library yang lengkap dan memiliki dukungan komunitas yang kuat karena python bersifat open source. Untuk menuliskan source code python anda dapat menggunakan IDE seperti vs code, sublime text, PyCharm atau anda juga dapat menggunakan IDE online seperti Jupyter notebook dan google colab.[1] Python dapat digunakan untuk berbagai keperluan, seperti pengembangan aplikasi web, aplikasi desktop, IoT, dan berbagai aplikasi lainnya.
Ada beberapa alasan mengapa Python menjadi pilihan utama, yaitu:
1.	Python dapat berjalan di berbagai platform seperti Windows, Linux, macOS, Android, Raspberry Pi, dan lain-lain.
2.	Python memiliki sintaks yang sederhana dan mirip dengan bahasa Inggris.
3.	Sintaks Python memungkinkan penulisan kode yang lebih ringkas dibandingkan dengan bahasa pemrograman lain.
4.	Python menggunakan interpreter, sehingga program dapat dieksekusi dengan cepat setelah selesai dibuat.
5.	Python mendukung paradigma pemrograman prosedural, berorientasi objek, dan fungsional.[2]
