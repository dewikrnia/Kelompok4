# Kelompok4

<html>
<body>

<p align="center">
<img src="https://github.com/dewikrnia/Kelompok4/blob/main/picture/cover.png" >
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
   
   Berikut ini fungsi user dalam bentuk grafik :
   - View Data Sekolah
   - View Data Guru

2.1   Perspektif produk
----------
Website Profil SMP Al Azhar Syifa Budi Pekanbaru II adalah sebuah informasi dari sekolah yang di aplikasiskan pada website. Pengolahan data di kelola oleh admin.

**2.1.1 Antarmuka sistem**

![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Antarmuka%20Sistem%20(2).png)

Website Profil SMP Al Azhar Syifa Budi Pekanbaru II memiliki 1 user yaitu admin. Admin bertugas untuk mengelola semua data yang ada di sistem ini, sehingga nantinya dapat dilihat oleh user.

**2.1.2 Antarmuka pengguna**

   - **Mockup Website**

|  |  |
|--|--|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-login.png) Pada halaman login admin diminta untuk mengisi username dan password.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-register.png) Pada halaman register admin diminta untuk mengisi email, username, padsword dan konfirmasi password.|
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-dashboard.png) Pada halaman dashboard berisi informasi mengenai jumlah data yang ada pada tiap tabel di halaman admin.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-dataguru.png) Pada halaman data guru digunakan admin untuk mengelola data guru.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-prestasi.png) Pada halaman prestasi digunakan admin unruk mengelola data prestasi.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-program%20sekolah.png) Pada halaman program sekolah digunakan admin untuk mengelola data program sekolah.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-informasi.png) Pada halaman informasi digunakan admin untuk mengelola data informasi.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-organisasi.png) Pada halaman organisasi digunakan admin untuk mengelola data organisasi.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-eskul.png) Pada halaman ekstrakulikuler digunakan admin untuk mengelola data ekstrakulikuler.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-sarana%20dan%20prasarana.png) Pada halaman sarana dan prasarana digunakan admin untuk mengelola data sarana dan prasarana.|
|![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-kontak.png) Pada halamana kontak digunakan admin untuk mengelola data kontak.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-visi%20misi.png) Pada halaman visi dan misi digunakan admim untuk mengelola data visi dan misi.|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-ucapankepsek.png) Pada halaman ucapan kepala sekolah digunakan admin untuk mengelola data ucapan kepala sekolah|| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-profil.png) Pada profil digunakan admin untuk mengelola data profil sekolah dulu.|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-kalender.png) Pada halaman kalender akademik digunakan admin untuk mengelola data kalender akademik.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-galeri.png) Pada halaman galeri digunakan admin untuk mengelola data galeri.|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-slider.png) Pada halaman silder digunakan admin untuk mengelola data slider.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin-datauser.png) Pada halaman data user digunakan admin untuk mengelola data user.|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-beranda.png) Pada halaman beranda digunakan untuk menampilkan beberapa informasi penting dari website profile SMP Al-Azhar Syifa Budi Pekanbaru II.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-ucapan%20kepala%20sekolah.png) Pada halaman ucapan kepala sekolah dapat digunakan untuk melihat ucapan kepala sekolah.|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-data%20guru.png) Pada halaman data guru dapat digunakan untuk melihat data guru.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-prestasi.png) Pada halaman prestasi dapat digunakan untuk melihat prestasi prestasi siswa.|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-sarana%20prasarana.png) Pada halaman sarana prasarana dapat digunakan untuk melihat seluruh sarana dan prasarana yang ada. | ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-galeri.png) Pada halaman galeri dapat digunakan untuk melihat galeri sekolah.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-visi.png) Pada halaman visi dan misi dapat digunakan untuk melihat visi.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-misi.png) Pada halaman visi dan misi dapat digunakan untuk melihat misi.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-informasi.png) Pada halaman dapat digunakan untuk melihat informasi yang ada.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-dalam%20informasi.png) Pada halaman dalam informasi dapat digunakan untuk melihat informasi secara lebih detail.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-program%20sekolah.png) Pada halaman program sekolah dapat digunakan untuk melihat program sekolah.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-dalam%20program%20sekolah.png) Pada halaman dalam program sekolah dapat digunakan untuk melihat program sekolah secara lebih detail.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-kalender%20akademik.png) Pada halaman kalender akademik digunakan untuk melihat kalender akademik.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-%20organisasi.png) Pada organisasi dapat digunakan untuk melihat organisasi.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-ekstrakulikuler.png) Pada halaman ekstrakulikuler dapat digunakan untuk melihat ekstrakulikuler.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-dalam%20ekstrakulikuler.png) Pada halaman dalam ekstrakulikuler dapat digunakan untuk melihat ekstrakulikuler lebih detail.| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/user-kontak.png) Pada halaman kontak digunakan untuk menampilkan beberapa kontak yang dapat dihubungi mengenai SMP Al-Azhar Syifa Budi Pekanbaru II.|
 
**2.1.3 Antarmuka perangkat keras**

![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/TampilanAntarMuka.png)

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
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Usecase%20-%20SMP%20AL%20AZHAR.png)
   
**2.2.1 Admin Login**

Use Case: Login

Diagram : 
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Login.png)

Deskripsi Singkat
Admin melukan login terlebih dahulu sebelum masuk ke tampilan home.
Deskripsi langkah-langkah
1. Admin melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Login Admin
   

**2.2.2 Admin Mengelola Tentang Kami**

Use Case: Mengelola Tentang Kami

Diagram: 
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Admin%20-%20Mengelola%20Tentang%20Kami.png)

Deskripsi Singkat
Admin melakukan kelola Tentang Kami yang berisi ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri, saran dan prasarana, dan informasi.
Deskripsi Langkah-langkah
1. Admin memilih menu ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri, saran dan prasarana, dan informasi yang ingin dikelola.
2. Sistem akan menampilkan data dari menu yang dipilih.
3. Admin melakukan kelola data pada menu yang dipilih.
4. Sistem akan menampilkan perubahan pada menu yang dikelola.

Xref: Bagian 3.2.2, Admin Mengelola Tentang Kami

**2.2.3 Admin Mengelola Akademik**

Use Case: Mengelola Akademik

Diagram :
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Admin%20-%20Mengelola%20Akademik.png)

Deskripsi Singkat
Admin melakukan kelola Profil Sekolah yang berisi program sekolah dan kalender akademik.
Deskripsi Langkah-langkah
1. Admin memilih menu program sekolah dan kalender akademik yang ingin dikelola.
2. Sistem akan menampilkan data dari menu yang dipilih.
3. Admin melakukan kelola data pada menu yang dipilih.
4. Sistem akan menampilkan perubahan pada menu yang dikelola.

Xref: Bagian 3.2.3, Mengelola Akademik

**2.2.4 Admin Mengelola Kontak**

Use Case: Mengelola Kontak

Diagram:
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Admin%20-%20Mengelola%20Kontak.png)

Deskripsi Singkat
Admin melakukan kelola Kontak.
Deskripsi Langkah-langkah
1. Admin mengklik menu Kontak.
2. Sistem akan menampilkan data dari menu yang dipilih.
3. Admin melakukan kelola data pada menu yang dipilih.
4. Sistem akan menampilkan perubahan pada menu yang dikelola.

Xref: Bagian 3.2.4, Mengelola Kontak

**2.2.5 Admin Mengelola Kemuridan**

Use Case: Mengelola Kemuridan

Diagram:
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Admin%20-%20Mengelola%20Kemuridan.png)

Deskripsi Singkat
Admin melakukan kelola Kemuridan yang berisi Organisasi dan Ekstrakulikuler.
Deskripsi Langkah-langkah
1. Admin memilih menu organisasi dan ekstrakulikuler yang ingin dikelola.
2. Sistem akan menampilkan data dari menu yang dipilih.
3. Admin melakukan kelola data pada menu yang dipilih.
4. Sistem akan menampilkan perubahan pada menu yang dikelola.

Xref: Bagian 3.2.5, Mengelola Kemuridan

**2.2.6 Admin Mengelola Profil**

Use Case: Mengelola Profil

Diagram:
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Admin%20-%20Mengelola%20Profil.png)

Deskripsi Singkat
Admin melakukan kelola Profil.
Deskripsi Langkah-langkah
1. Admin mengklik menu Profil.
2. Sistem akan menampilkan data dari menu yang dipilih.
3. Admin melakukan kelola data pada menu yang dipilih.
4. Sistem akan menampilkan perubahan pada menu yang dikelola.

Xref: Bagian 3.2.6, Mengelola Profil

**2.2.7 Admin Mengelola Slider**

Use Case: Mengelola Slider

Diagram:
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Admin%20-%20Mengelola%20Slider.png)

Deskripsi Singkat
Admin melakukan kelola Slider.
Deskripsi Langkah-langkah
1. Admin mengklik menu Slider.
2. Sistem akan menampilkan data dari menu yang dipilih.
3. Admin melakukan kelola data pada menu yang dipilih.
4. Sistem akan menampilkan perubahan pada menu yang dikelola.

Xref: Bagian 3.2.7, Mengelola Slider

**2.2.8 Admin Mengelola Data User**

Use Case: Mengelola Data User

Diagram:
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Admin%20-%20Mengelola%20Data%20User.png)

Deskripsi Singkat
Admin melakukan kelola Data User.
Deskripsi Langkah-langkah
1. Admin mengklik menu Data User.
2. Sistem akan menampilkan data dari menu yang dipilih.
3. Admin melakukan kelola data pada menu yang dipilih.
4. Sistem akan menampilkan perubahan pada menu yang dikelola.

Xref: Bagian 3.2.8, Mengelola Data User

**2.2.9 Admin Mengelola Data Beranda**

Use Case: Mengelola Beranda

Diagram:
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Admin%20-%20Mengelola%20Beranda.png)

Deskripsi Singkat
Admin melakukan kelola Beranda.
Deskripsi Langkah-langkah
1. Admin mengklik menu yang akan ditampilkan pada halaman Beranda.
2. Sistem akan menampilkan data dari menu yang dipilih.
3. Admin melakukan kelola data pada menu yang dipilih.
4. Sistem akan menampilkan perubahan pada menu yang dikelola.

Xref: Bagian 3.2.9, Mengelola Data User

**2.2.10 User Melihat Tentang Kami**

Use Case: Melihat Tentang Kami

Diagram:
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/User%20Melihat%20Tentang%20Kami.png)

Deskripsi Singkat
User melihat Tentang Kami yang berisi ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri, saran dan prasarana, dan informasi.
Deskripsi Langkah-langkah
1. User mengklik navbar Tentang Kami.
2. User memilih menu yang ada pada Tentang Kami.
3. Sistem akan menampilkan data pilihan menu Tentang Kami yang dipilih.

Xref: Bagian 3.2.10, Melihat Tentang Kami

**2.2.11 User Melihat Akademik**

Use Case: Melihat Akademik

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/User%20-%20Melihat%20Akademik.png)

Deskripsi Singkat
User melihat Akademik yang berisi program sekolah dan kalender akademik.
Deskripsi Langkah-langkah
1. User mengklik navbar Akademik.
2. User memilih menu yang ada pada Akademik.
3. Sistem akan menampilkan data pilihan menu Akademik yang dipilih.

Xref: Bagian 3.2.11, Melihat Akademik

**2.2.12 User Melihat Kontak**

Use Case: Melihat Kontak

Diagram:
![enter image description here]()

Deskripsi Singkat
User melihat Kontak.
Deskripsi Langkah-langkah
1. User mengklik navbar Kontak.
2. Sistem akan menampilkan data menu Kontak. 

Xref: Bagian 3.2.13, Melihat Kontak

**2.2.13 User Melihat Kemuridan**

Use Case: Melihat Kemuridan

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/User%20-%20Melihat%20Kemuridan.png)

Deskripsi Singkat
User melihat Kemuridan yang berisi Organisasi dan Ekstrakulikuler.
Deskripsi Langkah-langkah
1. User mengklik navbar Kemuridan.
2. User memilih menu yang ada pada Kemuridan.
3. Sistem akan menampilkan data pilihan menu Kemuridan yang dipilih. 

Xref: Bagian 3.2.13, Melihat Kemuridan

**2.2.14 User Melihat Beranda**

Use Case: Melihat Beranda

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/User%20-%20Melihat%20Beranda.png)

Deskripsi Singkat
User melihat Beranda.
Deskripsi Langkah-langkah
1. User mengklik navbar Beranda.
2. Sistem akan menampilkan data menu Beranda.

Xref: Bagian 3.2.14, Melihat Beranda


2.3   Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platofrm  OS ( Admin, user ) 
 
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
Tidak ada persyaratan khusus untuk mengakses website ini, sehingga siapapun dapat mengakses website ini tanpa perlu login terlebih dahulu.
      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1 Admin Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Admin |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Halaman login |
| Basic Path | 1. Admin mengisi form login dengan username dan password <br> 2.Admin mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin dapat login dan mengakses Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Exception Push | Username dan password salah |
      
**3.2.2 Admin Mengelola Tentang Kami**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Tentang Kami |
| Xref | Bagian 2.2.2, Mengelola Tentang Kami |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin menu ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri, saran dan prasarana, dan informasi yang ingin dikelola <br> 2. Admin memilih menu tersebut dan klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan menu yang akan dipanggil pada halaman Tentang Kami |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
**3.2.3 Admin Mengelola Akademik**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Akademik |
| Xref | Bagian 2.2.3, Mengelola Akademik |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin memilih menu program sekolah dan kalender akademik yang ingin dikelola <br> 2. Admin memilih menu tersebut dan klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan menu yang akan dipanggil pada halaman Akademik |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.4 Admin Mengelola Kontak**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Kontak |
| Xref | Bagian 2.2.4, Mengelola Kontak |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik menu Kontak <br> 2. Admin klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Kontak |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.5  Admin Mengelola Kemuridan**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Kemuridan |
| Xref | Bagian 2.2.5, Mengelola Kemuridan |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin memilih menu organisasi dan ekstrakulikuler yang ingin dikelola <br> 2. Admin memilih menu tersebut dan klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan menu yang akan dipanggil pada halaman Kemuridan |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.6 Admin Mengelola Profil**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Profil |
| Xref | Bagian 2.2.6, Mengelola Profil |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik menu Kontak <br> 2. Admin klik tombol edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Profil |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.7 Admin Mengelola Slider**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Slider |
| Xref | Bagian 2.2.7, Mengelola Slider |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik menu Kontak <br> 2. Admin klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Slider |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.8 Admin Mengelola Data User**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Data User |
| Xref | Bagian 2.2.8, Mengelola Data User |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik menu Kontak <br> 2. Admin klik tombol hapus <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Data User |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.9 Admin Mengelola Beranda**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Beranda |
| Xref | Bagian 2.2.9, Mengelola Beranda |
| Trigger | Membuka Website Admin Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik menu yang akan ditampilkan pada halaman Beranda <br> 2. Admin klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Beranda |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.10 User Melihat Tentang Kami**

|  |  |
|--|--|
| Nama Fungsi | Melihat Tentang Kami |
| Xref | Bagian 2.2.10, Melihat Tentang Kami |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Tentang <br> 2. Sistem akan menampilkan combobox pilihan ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri, saran dan prasarana, dan informasi <br>3. Sistem akan menampilkan hasil combobox yang dipilih. |
| Alternative | Tidak ada |
| Post Condition | User melihat hasil combobox yang yang dipilih |
| Exception Push | Tidak ada koneksi |
   
**3.2.11 User Melihat Akademik**

|  |  |
|--|--|
| Nama Fungsi | Melihat Akademik |
| Xref | Bagian 2.2.11, Melihat Akademik |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Profil Sekolah <br> 2. Sistem akan menampilkan combobox pilihan program sekolah dan kalender akademik <br>3.  Sistem akan menampilkan hasil combobox yang dipilih. |
| Alternative | Tidak ada |
| Post Condition | User melihat hasil combobox yang dipilihh |
| Exception Push | Tidak ada koneksi |
   
**3.2.12 User Melihat Kontak**

|  |  |
|--|--|
| Nama Fungsi | Melihat Kontak |
| Xref | Bagian 2.2.12, Melihat Kontak |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Kontak <br> 2. Sistem akan menampilkan halaman Kontak. |
| Alternative | Tidak ada |
| Post Condition | User melihat Kontak |
| Exception Push | Tidak ada koneksi |

**3.2.13  User Melihat Kemuridan**

|  |  |
|--|--|
| Nama Fungsi | Melihat Kemuridan |
| Xref | Bagian 2.2.13, Melihat Kemuridan |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Kemuridan <br> 2. Sistem akan menampilkan combobox pilihan organisasi dan ekstrakulikuler <br>3. Sistem akan menampilkan hasil combobox yang dipilih. |
| Alternative | Tidak ada |
| Post Condition | User melihat hasil combobox yang dipilih |
| Exception Push | Tidak ada koneksi |

**3.2.14 User Melihat Beranda**

|  |  |
|--|--|
| Nama Fungsi | Melihat Beranda |
| Xref | Bagian 2.2.14, Melihat Beranda |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Beranda <br> 2. Sistem akan menampilkan halaman Beranda. |
| Alternative | Tidak ada |
| Post Condition | User melihat Beranda |
| Exception Push | Tidak ada koneksi |
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/ERD%20Website%20Profile%20Sekolah-Page-1.drawio.png)

**Tabel Admin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id| bigint | Nomer auto increment id |
| username | varchar | berisikan username untuk akses login admin |
| password | varchar | berisikan password untuk login admin |
| email | varchar | berisikan email dari admin |

**Tabel Guru**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_guru | varchar | Nomor auto increment id_guru |
| nama_guru | varchar | Nama guru |
| jabatan | varchar | Jabatan guru |
| mapel | varchar | Mata pelajaran yang di ajar |
| foto_guru | varchar | Foto guru |

**Tabel Prestasi**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_prestasi | varchar | Nomor auto increment id_prestasi|
| nama_prestasi | varchar | Nama prestasi |
| tanggal_prestasi | date | Tanggal prestasi |
| keterangan_prestasi | text | Keterangan prestasi |
| foto_prestasi | varchar | Foto prestasi |

**Tabel Berita**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_berita| varchar | Nomor auto increment id_berita|
| nama_berita | varchar | Nama berita |
| tanggal_berita | date | Tanggal berita |
| keterangan_berita| text | Keterangan berita |
| foto_berita | varchar | Foto berita |


**Tabel Galeri**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_galeri | varchar | Nomor auto increment id_galeri|
| nama_galeri | varchar | Nama galeri |
| tanggal_galeri | date | Tanggal galeri |
| keterangan_galeri| text | Keterangan galeri |
| file_galeri | varchar | File galeri |

**Tabel Fasilitas**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_fasilitas | varchar | Nomor auto increment id_fasilitas|
| nama_fasilitas| varchar | Nama fasilitas |
| keterangan_fasilitas| text | Keterangan fasilitas |
| foto_fasilitas | varchar | Foto fasilitas |
| tanggal_fasilitas | date | Tanggal fasilitas |

**Tabel Ekstrakulikuler**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_eskul | varchar | Nomor auto increment id_ekstrakulikuler|
| nama_eskul | varchar | Nama ekstrakulikuler |
| keterangan_eskul | text | Keterangan ekstrakulikuler |
| foto_eskul | varchar | Foto ekstrakulikuler |
| tanggal_eskul | date | Tanggal ekstrakulikuler |

**Tabel Organisasi**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_organisasi | varchar | Nomor auto increment id_organisasi|
| nama_organisasi | varchar | Nama organisasi |
| keterangan_organisasi| text | Keterangan organisasi |
| foto_organisasi | varchar | Foto organisasi |
| tanggal_organisasi | date | Tanggal organisasi |

**Tabel Program Sekolah**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_program | varchar | Nomor auto increment id_program|
| nama_program | varchar | Nama program |
| tanggal_program | date | Tanggal program |
| keterangan_program| text | Keterangan program |
| foto_program | varchar | Foto program |

**Tabel Kalender Akademik**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_kalender | varchar | Nomor auto increment id_kalender |
| tanggal | date | Tanggal kalender |
| keterangan| text | Keterangan kalender |
| file_1 | varchar | File kalender 1 |
| file_2 | varchar | File kalender 2 |

**Tabel Sejarah**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_sejarah | varchar | Nomor auto increment id_sejarah |
| keterangan| text | Keterangan sejarah |
| file | varchar | File sejarah |

**Tabel Slider**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_slider | varchar | Nomor auto increment id_slider |
| keterangan| text | Keterangan slider |
| file | varchar | File slider |

**Tabel Ucapan Kepala Sekolah**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_ucapan | varchar | Nomor auto increment id_ucapan |
| nama | varchar | Nama kepala sekolah |
| keterangan| text | Keterangan kepala sekolah |
| foto | varchar | Foto kepala sekolah |

**Tabel Visi dan Misi**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_visimisi | varchar | Nomor auto increment id_visimisi |
| visi | varchar | Visi sekolah |
| misi | varchar | Misi sekolah |

**Tabel Tentang**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_tentang | varchar | Nomor auto increment id_tentang |
| telepon | varchar | Telepon sekolah |
| instagram | varchar | Instagram sekolah |
| email | varchar | Email sekolah |
| alamat | varchar | Alamat sekolah |
| facebook | varchar | Facebook sekolah |

Validasi Data Wawancara
----------
Validasi data wawancara dengan pihak SMP Al Azhar Syifa Budi Pekanbaru II.
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/SURAT%20VAIDASI%20SEKOLAH_KEL%206_FRAMEWORK_page-0001.jpg)
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/SURAT%20VAIDASI%20SEKOLAH_KEL%206_FRAMEWORK_page-0002.jpg)

Dokumentasi
----------
Dokumentasi dengan pihak SMP Al Azhar Syifa Budi Pekanbaru II.
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/dokumentasi2.jpeg)
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/DOKUMENTASI.jpeg)

Job Desc
----------
| Nama | Tugas | 
| ------ | ------ | 
| Dewi Kurnia Sari | SRS, Desain Website, Membuat Website |
| Dyva Herza Nabila | SRS, Desain Website, Membuat Website | 
| Farra Rumaisyah | SRS, Desain Website, Membuat Website | 
