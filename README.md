# Kelompok4

<html>
<body>
<div align="center"><h1> Software Requirements Spesification</h1></div>

<p align="center"><b>Version 1.7 </b><br>
<p align="center">22 Oktober 2023</b>
<p align="center">
<img src="https://github.com/dewikrnia/Kelompok4/blob/main/picture/LOGO%20RESMI%20PCR.svg" width="400" height="400"/ >
</p>

<p align="center"><b>Sistem Profile SMP Al Azhar Syifa Budi Pekanbaru II<br>
</b>
<p align="center">Kelompok 4 <br>
 Dewi Kurnia Sari            (2257301033)<br>
 Dyva Herza Nabila    (2257301039)<br>
 Farra Rumaisyah       (2257301044)<br><br><br>

<p align="center"><b>Program Studi Sistem Informasi</b><br>
<p align="center"><b>Politeknik Caltex Riau</b>
<p align="center"><b>2023</b>
</p>
</body>
</html>
 

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Website Profil SMP Al Azhar Syifa Budi Pekanbaru II". Dokumen ini dibangun untuk membantu admin sekolah untuk mengelola dan menampilkan profil sekolah yang dapat di akses secara online sehingga akan memudahkan user yang ingin mengetahui profil sekolah. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "WEBSITE PROFILE SMP AL-AZHAR SYIFA BUDI PEKANBARU".

1.2   Lingkup
----------
Sistem Profile SMP Al Azhar Syifa Budi Pekanbaru II merupakan website yang digunakan untuk membantu admin sekolah dalam mengelola informasi terkait dengan profil sekolah dan memfasilitasi komunikasi yang lebih baik dengan berbagai pemangku kepentingan, seperti siswa, orang tua, guru, dan staf sekolah.

1.3    Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses aplikasi |
| Software Requirement Specification | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| Use Case | situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4   Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
- http://hasantarmizi.blogspot.co.id/2017/04/pengertian-sublime-text.html
- IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software  Requirements Specifications. IEEE Computer Society, 1998. 1.5  Overview 
- _SRSExample-webapp.pdf_

1.5   Overview
----------

Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Dalam era globalisasi dengan perkembangan teknologi yang pesat, lembaga pendidikan, seperti sekolah, perlu mengikuti perkembangan ini untuk meningkatkan efisiensi dan komunikasi dengan semua pemangku kepentingan, termasuk siswa, orang tua, guru, dan staf sekolah. Dalam studi kasus ini, kami akan merancang sebuah sistem website profil sekolah yang akan memungkinkan admin sekolah untuk mengelola dan menyediakan informasi yang relevan tentang sekolah. Software yang kami buat ini berbasis website dimana akan dirancang untuk memenuhi kebutuhan administrasi dan komunikasi sekolah dengan berbagai fitur yang disesuaikan dengan lingkungan pendidikan. Berikut akan kami jelaskan  sistem software kami,  admin fungsi utama yaitu :
   - Input Data Sekolah
   - Input Data Guru
   - Input Sistem Akademik
   
   Berikut ini fungsi user dalam bentuk grafik :
   - View Data Sekolah
   - View Data Guru
   - View Sistem Akademik

2.1   Perspektif produk
----------
Website Profil SMP Al Azhar Syifa Budi Pekanbaru II adalah sebuah informasi dari sekolah yang di aplikasiskan pada website. Pengolahan data di kelola oleh admin.

**2.1.1 Antarmuka sistem**

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/antarmuka%20sistem1.png)

Website Profil SMP Al Azhar Syifa Budi Pekanbaru II memiliki 1 user yaitu admin. Admin bertugas untuk mengelola semua data yang ada di sistem ini, sehingga nantinya dapat dilihat oleh user.

**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Login.png) Pada halaman login admin diminta untuk mengisi username dan password.| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Dashboard.png) Pada Dashboard admin terdapat panel-panel seperti penduduk, pendidikan, agama, pekerjaan, laporan dan ucapan selamat datang.|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Dropdone%20Kependudukan.png) Pada halaman dashboard ada navigation bar kependudukan yang berisi dropdown angka kelahiran dan angka kematian| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Agama.png) Pada Halaman agama dapat menginputkan data agama penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Pekerjaan.png) Pada Halaman pekerjaan dapat menginputkan data pekerjaan penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Warga.png) Pada Halaman warga dapat menginputkan data warga|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Pendidikan.png) Pada Halaman pendidikan dapat menginputkan data pendidikan penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Angka%20Kelahiran.png) Pada Halaman kelahiran dapat menginputkan data kelahiran penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Input%20Angka%20Kematian.png) Pada Halaman kematian dapat menginputkan data kematian penduduk| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Grafik%20Angka%20kelahiran.png) Pada Halaman grafik kelahiran dapat melihat data angka kelahiran|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Grafik%20Angka%20kematian.png) Pada Halaman grafik kematian dapat melihat data angka kematian| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Laporan.png) Pada Halaman laporan dapat melihat dan mendownload laporan penduduk|
| ![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/Halaman%20Lupa%20Password.png) Pada halaman lupa password dapat mengganti password terlebih dahulu memasukkan username dan password sebelumnya| |
 
**2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Tampilan%20Antarmuka.png)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Website Profil SMP Al Azhar Syifa Budi Pekanbaru II antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka perangkat lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Website Profil SMP Al Azhar Syifa Budi Pekanbaru II antara lain :
1. Kabel Lan UTP RJ45
2. Modem
3. wifi

**2.1.6 Batasan memori**

Tidak ada

**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses aplikasi |
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |

**2.1.8 Kebutuhan adaptasi**

Tidak ada
   
2.2 Spesifikasi Kebutuhan fungsional
----------
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/USECASE%20WEBSITE%20PROFIL%20SMP%20AL-%20AZHAR%20PEKANBARU%20.png)
   
**2.2.1 Admin Login**

Use Case: Login

Diagram : 
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/login.png)

Deskripsi Singkat
Admin melukan login terlebih dahulu sebelum masuk ke tampilan home.
Deskripsi langkah-langkah
1. Admin melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Login Admin
   

**2.2.2 Admin Mengelola Tentang**

Use Case: Mengelola Tentang

Diagram: 
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MengelolaAboutUs.png)

Deskripsi Singkat
Admin melakukan kelola Tentang yang berisi ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri.
Deskripsi Langkah-langkah
1. Admin mengklik navbar Tentang.
2. Admin memilih menu yang ada pada Tentang.
3. Sistem akan menampilkan pilihan menu Tentang yang dipilih.
4. Admin melakukan kelola data pada pilihan menu yang dipilih.

Xref: Bagian 3.2.2, Admin Mengelola Tentang

**2.2.3 Admin Mengelola Profil Sekolah**

Use Case: Mengelola Profil Sekolah

Diagram :
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20login.png)

Deskripsi Singkat
Admin melakukan kelola Profil Sekolah yang berisi program sekolah, kalender akademik, dan fasilitas.
Deskripsi Langkah-langkah
1. Admin mengklik navbar Profil Sekolah.
2. Admin memilih menu yang ada pada Profil Sekolah.
3. Sistem akan menampilkan pilihan menu Profil Sekolah yang dipilih.
4. Admin melakukan kelola data pada pilihan menu yang dipilih.

Xref: Bagian 3.2.3, Mengelola Profil Sekolah
      
**2.2.4 Admin Mengelola Berita**

Use Case: Mengelola Berita

Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20admin%20kelola%20data2.png)
      
Deskripsi Singkat
Admin melakukan kelola Berita.
Deskripsi Langkah-langkah
1. Admin mengklik navbar Berita.
2. Sistem akan menampilkan menu Berita yang dipilih.
3. Admin melakukan kelola data pada menu Berita.

Xref: Bagian 3.2.4, Mengelola Berita

**2.2.5 Admin Mengelola Pengumuman**

Use Case: Mengelola Pengumuman
Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20lihat%20data%20kependudukan.png)

Deskripsi Singkat
Admin melakukan kelola Pengumuman.
Deskripsi Langkah-langkah
1. Admin mengklik navbar Pengumuman.
2. Sistem akan menampilkan menu Pengumuman yang dipilih.
3. Admin melakukan kelola data pada menu Pengumuman.

Xref: Bagian 3.2.5, Mengelola Pengumuman
   
**2.2.6 Admin Mengelola Kontak**

Use Case: Mengelola Kontak

Diagram:
![](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20admin%20generate%20laporan.png)

Deskripsi Singkat
Admin melakukan kelola Kontak.
Deskripsi Langkah-langkah
1. Admin mengklik navbar Kontak.
2. Sistem akan menampilkan menu Kontak yang dipilih.
3. Admin melakukan kelola data pada menu Kontak. 

Xref: Bagian 3.2.6, Mengelola Kontak

**2.2.7 Admin Mengelola Kemuridan**

Use Case: Mengelola Kemuridan

Diagram:
![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/use%20case%20kelola%20user.png)

Deskripsi Singkat
Admin melakukan kelola Kemuridan yang berisi Organisasi dan Ekstrakulikuler.
Deskripsi Langkah-langkah
1. Admin mengklik navbar Kemuridan.
2. Admin memilih menu yang ada pada Kemuridan.
3. Sistem akan menampilkan pilihan menu Kemuridan yang dipilih.
4. Admin melakukan kelola data pada pilihan menu yang dipilih.

Xref: Bagian 3.2.7, Mengelola Kemuridan



2.3   Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platofrm  OS ( Admin, sekdes dan kepala desa ) 
 
2.4   Karakteristik pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). 
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6   Asumsi-asumsi
----------
Maksimal penginputan id atau memasukkan kode pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan"Anda telah melebihi batas maksimum".

2.7   Kebutuhan Penyeimbang
----------
Tidak ada


BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakses aplikasi ini yaitu dengan hak akses yang di berikan oleh admmin, login melalui aplikasi ini dengan mencantumkan username kemudian sistem akan mencocokkan username sekdes dan kepala desa lohbener. Setelah login berhasil kepala desa dapat melihat grafik kependudukan dan laporan desa Lohbener di aplikasi tersebut.
      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1 Kepala desa Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Kepala desa |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman login |
| Basic Path | 1. Kepala desa mengisi form login dengan username dan password <br> 2.Kepala desa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Kepala desa dapat login dan mengakses aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbene |
| Exception Push | Username dan password salah |
      
**3.2.2 Kepala desa melihat laporan kependudukan**

|  |  |
|--|--|
| Nama Fungsi | View laporan kependudukan |
| Xref | Bagian 2.2.2, View laporan kependudukan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Membuka halaman grafik kependudukan |
| Basic Path | 1. Kepala desa mengklik navbar laporan <br> 2. Sitem akan menampilkan combobox pilihan bulan dan tahun <br>3. Kepala desa memilih combobox tersebut dan klik tombol lihat <br> 4. Sistem akan menampilkan hasil laporan. |
| Alternative | Tidak ada |
| Post Condition | Kepala desa melihat laporan kependudukan |
| Exception Push | Tidak ada koneksi |
   
**3.2.3 Admin login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.3, Login admin |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman login admin |
| Basic Path | 1. Admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin berhasil login dan mengakses aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Exception Push | Username dan password salah |
   
**3.2.4 Admin input data kependudukan**

|  |  |
|--|--|
| Nama Fungsi | Input data kependudukan |
| Xref | Bagian 2.2.4, Input data kependudukan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman utama admin |
| Basic Path | 1. Admin melakukan input data kependudukan, pekerjaan, agama, pendidikan dan lain-lain <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menyimpan data kependudukan <br> 4. Bila data sudah ada sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data kependudukan |
| Exception Push | Tidak ada koneksi |
   
**3.2.5 Admin melihat data kependudukan**

|  |  |
|--|--|
| Nama Fungsi | View data kependudukan |
| Xref | Bagian 2.2.5, View data kependudukan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | Halaman form input data |
| Basic Path | 1. Sistem akan menampilkan data kependudukan desa Lohbener. <br> 2. Admin melihat data dan dapat mengedit atau menghapusnya. <br> 3. Sistem menampilkan edit data kependudukan <br>4. Admin  mengedit data kependudukan yang baru atau yang sudah ada<br>5. Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan|
| Alternative | Tidak ada |
| Post Condition | Halaman data kependudukan |
| Exception Push | Tidak ada koneksi |
   
**3.2.6 Cetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.6, Cetak Laporan |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener |
| Precondition | halaman utama admin |
| Basic Path | 1. Admin mengklik tombol laporan <br> 2. Sistem menampilkan laporan kependudukan <br> 3. Admin memilih combobox tersebut dan klik tombol lihat <br>4. Sistem akan menampilkan hasil laporan. <br>5. Admin mencetak laporan  |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.7  Admin mengelola user**

|  |  |
|--|--|
| Nama Fungsi | Mengelola user |
| Xref | Bagian 2.2.7, Mengelola user |
| Trigger | Membuka aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbener | 
| Precondition | halaman utama admin |
| Basic Path | 1. Sistem menampilkan form.<br>2. Admin mengisi form user dengan jabatan, tanggal mulai, tanggal berakhir, dll kemudian klik tombol simpan.<br>3. Sistem akan menyimpan data user ke database.  |
| Post Condition | Halaman user |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/erd_proyek2.png)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| int | Nomer auto increment Id_user|
| Username | varchar | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |
| level | varchar | untuk membedakan level saat login antara admin dan user

**Tabel Warga**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| NIK | varchar | nomer kependudukan|
| Nama | varchar | nomer kependudukan|
| jns_kelamin | varchar | Identifikasi jenis kelamin|
| Tgl_lahir | date | tanggal lahir peserta |
| Agama | varchar | Identifikasi agama |

**Tabel Pegawai**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pegawai| int | Nomer auto increment Id_bioadmin|
| Id_user| int | untuk mengambil username dan password admin pada tabel user|
| nik| varchar | nik admin|
| jabatan | varchar | mendefinisikan level user |
| tgl_masuk | date | awal jabatan|
| tgl_keluar | date | akhir jabatan|

**Tabel Kelahiran**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kelahiran| int | Nomer auto increment Id_kelahiran|
| Id_warga| int | foreignt key tabel warga |
| tgl_lahir| date | tanggal lahir anak |
| jns_kelamin| varchar | jenis kelamin anak|
| ayah | varchar | nama ayah|
| ibu | varchar | nama ibu|
| tmp_lahir| varchar | tempat lahir anak |
| rt | int | nomor rt|
| rw | int | nomor rw|

**Tabel Kematian**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kematian| int | Nomer auto increment Id_kematian|
| Id_warga| int | foreignt key tabel warga |
| tmp_kematian| varchar | tempat lahir anak |
| tgl_kematian| date | tanggal lahir anak |
| rt | int | nomor rt|
| rw | int | nomor rw|

**Tabel Pekerjaan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pekerjaan| int | Nomer auto increment Id_pekerjaan|
| Id_warga| int | foreignt key tabel warga |
| pekerjaan| varchar | pekerjaan masyarakat  |
| tgl_input | date | tanggal input pekerjaan |

**Tabel Pendidikan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pendidikan| int | Nomer auto increment Id_pendidikan|
| Id_warga| int | foreignt key tabel warga |
| pendidikan| varchar | pendidikan masyarakat  |
| tgl_masuk | date | tanggal masuk pendidikan |

**Tabel ktp**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_ktp| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_ktp| varchar | Identifikasi memiliki atau belum memiliki ktp |
| masa_berlaku | date | tanggal berlaku ktp |

**Tabel kk**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kk| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| kepala_keluarga| varchar | nama kepala keluarga |
| no_kk | varchar | nomor kk |

**Tabel pindah**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pindah| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| tgl_pindah | date | tanggal akan pindah |
| ket | varchar | alamat pindah |

**Tabel datang**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_datang| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| tgl_datang | date | tanggal kedatangan |
| ket | varchar | alamat sebelum datang |

**Tabel pilih**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_pilih| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_pilih | varchar | hak pilih |

**Tabel kawin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_kawin| varchar | Nomer auto increment Id_angdes|
| Id_warga| int | foreignt key tabel warga |
| status_kawin | varchar | status warga |

**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| int | Nomer auto increment Id_laporan|
| Id_warga| int | foreignt key tabel warga |
| laporan | varchar | berisi laporan kependudukan |

**Tabel Agama**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_agama| int | Nomer auto increment Id_laporan|
| Id_warga| int | foreignt key tabel warga |
| agama| varchar | berisi agama penduduk |
