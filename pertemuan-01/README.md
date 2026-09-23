# pertemuan-01
1. kesinambungan PWD–DPW–DPWL;
jawaban : Pemrograman Web Dasar (PWD): Fokus kepada fondasi front-end statis (HTML, CSS, JavaScript dasar) untuk dasar scripting back-end prosedural (PHP dasar).

Desain dan Pemrograman Web (DPW): Mengintegrasikan front-end dan back-end secare dinamis, mengenalkan pengelolaan basis data (MySQL/MariaDB), untuk penerapan arsitektur perangkat lunak seperti MVC (Model-View-Controller).

Desain dan Pemrograman Web Lanjutan (DPWL): Melanjutkan konsep DPW ke tingkat industri kek memanfaatkan framework modern (seperti Laravel atau CodeIgniter), pengamanan aplikasi (web security), pembuatan RESTful API, hingga arsitektur microservices

2. perbedaan PHP terstruktur dan MVC;
jawaban : PHP Terstruktur (Native): Kode logika, basis data, dan tampilan HTML yang digabung menjadi satu. Akibat nya, kode cepat berantakan, makin rumit dirawat saat proyek membesar, dan rawan bentur kalau dikerjakan tim.

PHP Berbasis MVC: Kodenya dipisah secara rapi menjadi tiga bagian terisolasi yaitu: Model (data/database), View (tampilan/HTML), dan Controller (logika penghubung). Aplikasi jauh lebih rapi, mudah diperbaiki, dan efisien untuk kerja tim.

3. fungsi Model, View, dan Controller;
jawaban : Model: Mengelola logika data, aturan bisnis, dan interaksi langsung ke basis data kayak kueri SELECT, INSERT, UPDATE, DELETE.

4. alur request–response MVC;
jawaban : Pengguna Browser : akses URL atau mengklik tombol.

Controller: Menerima request dari URL dan menentukan aksi yang harus dilakukan.

Model: Dipanggil oleh Controller untuk mengambil atau mengolah data dari database.

View: Menerima data dari Controller lalu merender tampilannya (HTML).

Response: Tampilan akhirnya dikirim kembali ke browser pengguna.

5. pemetaan satu atau beberapa bagian/fitur aplikasi DPW ke Model, Controller, dan View disertai alasan; dan
jawaban : 
Model : untuk tugas nya Menyimpan fungsi kueri SQL untuk mengambil seluruh data barang, menambahkan stok baru, atau menghapus barang dari basis data
alasan nya agar seluruh logika manipulasi data terpusat di satu tempat dan aman dari kebocoran ke lapisan antarmuka.

Controller : untuk tugas nya Menampung input form penambahan barang dari pengguna, memvalidasi apakah jumlah stok berupa angka, memanggil BarangModel untuk menyimpan ke database, lalu mengarahkan ke halaman
alasan nya agar berfungsi sebagai pengatur lalu lintas logika aplikasi agar data divalidasi sebelum masuk ke database

View: untuk tugas nya menampilkan tabel daftar barang beserta tombol "Tambah" atau "Hapus", serta form input data barang baru
alasan nya hanya bertugas menyajikan struktur halaman dan menerima input pengguna tanpa membawa fungsi pemrosesan data

6. kesimpulan P1.
jawaban : Penerapan arsitektur MVC pada pemrograman web merupakan standar industri yang menyelesaikan masalah acak-acakannya kode (spaghetti code) pada PHP terstruktur