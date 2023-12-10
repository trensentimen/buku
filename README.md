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

B.	JUPYTER NOTEBOOK
Jupyter Notebook adalah aplikasi berbasis web open source yang dapat digunakan untuk membuat dan membagikan dokumen. Dokumen ini berisi kode, persamaan matematika, visualisasi maupun text. Jupyter notebook ini dikelola oleh orang-orang yang tergabung pada Project Jupyter. [3]
jupyter Notebook adalah singkatan dari tiga bahasa pemrograman: Julia (Ju), Python (Py), dan R. Aplikasi web gratis yang paling umum digunakan oleh data scientist. Aplikasi ini digunakan untuk membuat dan berbagi dokumen yang berisi kode, hasil perhitungan, visualisasi, dan teks. Tiga bahasa pemrograman yang disertakan dalam Jupyter Notebook sendiri penting bagi data scientist.[4]
(https://algorit.ma/blog/cara-menggunakan-jupyter-notebook-2022/ )


C.	VS CODE
Visual Studio Code (disingkat VCode) adalah perangkat lunak penyunting kode-sumber buatan Microsoft untuk Linux, macOS, dan Windows.[5] (https://techcrunch.com/2015/04/29/microsoft-shocks-the-world-with-visual-studio-code-a-free-code-editor-for-os-x-linux-and-windows/, ) Visual Studio Code menyediakan fitur seperti penyorotan sintaksis, penyelesaian kode, kutipan kode, merefaktor kode, pengawakutuan, dan Git. Microsoft merilis sumber kode Visual Studio Code di repositori GitHub dengan lisensi MIT (Code - OSS), sedangkan biner yang dibangun oleh Microsoft tidak dirilis dengan lisensi MIT dan merupakan perangkat lunak berpemilik.[6] (https://id.wikipedia.org/wiki/Visual_Studio_Code )

D.	POSTMAN
Postman adalah alat pengembangan API yang komprehensif yang dapat digunakan untuk mengembangkan, menguji, dan mendokumentasikan API.

Fitur-fitur Postman meliputi:

1.	Pembuatan permintaan HTTP yang mudah: Postman memungkinkan pengembang untuk membuat permintaan HTTP menggunakan berbagai metode, seperti GET, POST, PUT, dan DELETE.
2.	Pengelolaan variabel yang fleksibel: Postman menyediakan fitur variabel yang memudahkan pengelolaan nilai yang dapat digunakan secara dinamis dalam permintaan API.
3.	Pengujian API yang komprehensif: Postman mendukung pengujian API manual dan otomatis, serta menyediakan berbagai fitur untuk membantu pengembang membuat skenario pengujian kompleks.
4.	Dokumentasi API yang otomatis: Postman dapat digunakan untuk membuat dokumentasi otomatis dari koleksi permintaan API, sehingga memudahkan berbagi informasi dengan tim atau komunitas.
5.	Kolaborasi yang mudah: Postman memungkinkan pengembang untuk berbagi koleksi dan lingkungan, sehingga memudahkan kolaborasi dalam pengembangan API.
6.	Keamanan yang terjamin: Postman menggunakan enkripsi HTTPS untuk memastikan keamanan data yang dikirimkan melalui API.
7.	Postman adalah alat yang berharga bagi pengembang API karena dapat membantu mereka mengembangkan, menguji, dan mendokumentasikan API dengan lebih mudah dan efisien.

Berikut adalah beberapa contoh bagaimana Postman dapat digunakan:

1.	Pengembang dapat menggunakan Postman untuk membuat permintaan HTTP ke API yang mereka buat untuk menguji fungsionalitas API.
2.	Pengembang dapat menggunakan Postman untuk membuat skenario pengujian otomatis untuk API mereka.
3.	Pengembang dapat menggunakan Postman untuk membuat dokumentasi API yang mudah dipahami oleh pengguna.
4.	Tim pengembang dapat menggunakan Postman untuk berbagi koleksi permintaan dan lingkungan, sehingga memudahkan kolaborasi dalam pengembangan API.
Postman adalah alat yang serbaguna yang dapat digunakan untuk berbagai keperluan pengembangan API. Dengan antarmuka yang ramah pengguna dan fitur-fitur yang komprehensif, Postman dapat membantu pengembang API meningkatkan produktivitas dan kualitas pekerjaan mereka.




E.	GITHUB
GitHub adalah layanan hos web bersama untuk proyek pengembangan perangkat lunak yang menggunakan sistem kendali versi Git dan layanan hosting internet. Hal ini banyak digunakan untuk kode komputer. Ini memberikan kontrol akses dan beberapa fitur kolaborasi seperti pelacakan bug, permintaan fitur, manajemen tugas, dan wiki untuk setiap proyek.[7]( https://techcrunch.com/2012/07/09/github-pours-energies-into-enterprise-raises-100-million-from-power-vc-andreesen-horowitz/)  Pengembangan platform GitHub dimulai pada tanggal 19 Oktober 2007. Situs ini diluncurkan pada April 2008 oleh Tom Preston-Werner, Chris Wanstrath, dan PJ Hyett. [8](https://id.wikipedia.org/wiki/GitHub )

F.	GOOGLE CLOUD PLATFORM
Google Cloud Platform, (atau GCP) adalah kumpulan layanan komputasi awan yang ditawarkan oleh Google. GCP berjalan di atas infrastruktur yang sama yang digunakan oleh Google untuk produk internalnya, seperti Google Search, YouTube dan Gmail. Bersamaan dengan seperangkat alat manajemen, GCP menyediakan serangkaian layanan cloud modular termasuk komputasi, penyimpanan data, Analisis data dan pembelajaran mesin. Registrasi membutuhkan detail kartu kredit atau rekening bank [9]
( https://id.wikipedia.org/wiki/Google_Cloud_Platform#cite_note-auto-2)
G.	MONGODB
MongoDBmerupakan  sebuah  sistem basis data yang berbasis dokumen (Document Oriented Database)dan termasuk sistem basis data yang menganut paham NoSQL. NoSQLsingkatan dari Not Only SQL, artinya sebuah sistem basis data tidak hanya harus menggunakan perintah SQLuntuk melakukan proses manipulasi data. MongoDBtidak memiliki tabel, kolom, dan baris. Pada MongoDByang ada hanyalah koleksi dan dokumen.  Dokumen yang terdapat dalam MongoDBdapat memiliki atribut yang berbeda dengan dokumen lain walaupun berada dalam satu koleksi.[10]

H.	GOLANG
Golang (Go Language) merupakan sebuah bahasa pemrograman yang mengkombinasikan  keamanan  dan performa untuk pengembangan sistem yang bersifat open  sourcedan  dikembangkan di Google  oleh  Rob Pike, Robert Griesemer, dan Ken Thompson beserta kontributor lainnya dalam komunitas pengembang open source.  Hingga saat ini, Golang mulai banyak digunakan pada Perusahaan-perusahaan besar maupun startup yang bergerak di bidang teknologi [11]

I.	JAVASCRIPT
JavaScript adalah bahasa pemrograman yang khusus untuk halaman web agar halaman web menjadi lebih hidup. Kalau dilihat dari suku katanya terdiri dari dua suku kata, yaitu Java dan Script. Java adalah Bahasa pemrograman berorientasi objek, sedangkan Script adalah serangkaian instruksi program.[12]
Java Script dijalankan pada sisi klien yang akan memberikan kemampuan fitur-fitur tambahan halaman web yang lebih baik dibandingkan fitur-fitur yang terdapat pada HTML [13].
 
