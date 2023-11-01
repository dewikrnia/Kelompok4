# Kelompok4

<html>
<body>

<p align="center">
<img src="https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image/POLINDRA.png](https://github.com/dewikrnia/Kelompok4/blob/main/picture/cover.png)" >
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

![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Antarmuka%20Sistem2.png)

Website Profil SMP Al Azhar Syifa Budi Pekanbaru II memiliki 1 user yaitu admin. Admin bertugas untuk mengelola semua data yang ada di sistem ini, sehingga nantinya dapat dilihat oleh user.

**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-LOGIN%20ADMIN.png) Pada halaman login admin diminta untuk mengisi username dan password.| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-DASHBOARD%20ADMIN.png) Pada Dashboard admin terdapat panel-panel seperti program sekolah, data guru, prestasi, organisasi, ekstrakulikuler, kalender akademik, berita, user manajemen, pengumuman, dan galeri.|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-DATA%20GURU%20ADMIN.png) Pada halaman data guru dapat digunakan admin untuk mengelola data guru| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/admin_prestasi.png) Pada halaman prestasi dapat digunakan admin unruk mengelola data prestasi|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA%20-PROGRAM%20SEKOLAH%20ADMIN.png) Pada halaman program sekolah dapat digunakan admin untuk mengelola data program sekolah| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_KALANDER%20AKADEMIK.png) Pada halaman kalender akademik digunakan untuk mengupdate kalender akademik|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-%20BERITA%20ADMIN%20.png) Pada berita dapat digunakan admin untuk mengelola data berita| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-ORGANISASI%20ADMIN.png) Pada organisasi dapat digunakan admin untuk mengelola data organisasi|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-EKSTRAKULIKULER%20ADMIN.png) Pada ekstrakulikuler dapat digunakan admin untuk mengelola data ekstrakulikuler| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-%20PENGUMUMAN%20ADMIN%20.png) Pada halaman pengumuman dapat digunakan admin untuk mengelola data pengumuman|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-%20GALERI%20ADMIN%20.png) Pada halamana geleri dapat digunakan admin untuk mengelola data galeri| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA-%20USER%20MANAJEMEN%20ADMIN%20.png) Pada halaman user manajemen dapat digunakan admim untuk mengelola data user|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_DASHBOARD.png) Pada halaman dashboard dapat digunakan untuk melihat halaman utama yang berisi informasi informasi utama| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_BERITA.png) Pada halaman berita dapat digunakan untuk melihat berita|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_DATAGURU.png) Pada halaman data guru dapat digunakan untuk melihat data guru| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_PRESTASI.png) Pada halaman prestasi dapat digunakan untuk melihat prestasi|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_PROGRAMSEKOLAH.png) Pada halaman program sekolah dapat digunakan untuk melihat program sekolah| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_KALANDER%20AKADEMIK.png) Pada halaman kalender akademik digunakan untuk melihat kalender akademik|
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_ORGANISASI.png) Pada organisasi dapat digunakan untuk melihat organisasi| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_EKSTRAKULIKULER.png) Pada ekstrakulikuler dapat digunakan untuk melihat ekstrakulikuler| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_PENGUMUMAN.png) Pada halaman pengumuman dapat digunakan untuk melihat pengumuman| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_UCAPAN%20KEPALA%20SEKOLAH.png) Pada halaman ucapan kepala sekolah dapat digunakan untuk melihat ucapan kepala sekolah| 
| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/FIGMA_VISI%20MISI.png) Pada halaman visi dan misi dapat digunakan untuk melihat visi dan misi| ![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/image.png) Pada halaman galeri dapat digunakan untuk melihat galeri sekolah||
 
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
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/Usecasebaru.png)
   
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
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MengelolaTentangKami.png)

Deskripsi Singkat
Admin melakukan kelola Tentang yang berisi ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri.
Deskripsi Langkah-langkah
1. Admin mengklik navbar Tentang.
2. Admin memilih menu yang ada pada Tentang.
3. Sistem akan menampilkan pilihan menu Tentang yang dipilih.
4. Admin melakukan kelola data pada pilihan menu yang dipilih.

Xref: Bagian 3.2.2, Admin Mengelola Tentang Kami

**2.2.3 Admin Mengelola Profil Sekolah**

Use Case: Mengelola Profil Sekolah

Diagram :
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MengelolaProfilSekolah.png)

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
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MengelolaBerita.png)
      
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
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MengelolaPengumuman.png)

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
![](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MengelolaKontak.png)

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
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MengelolaKegiatanKemuridan.png)

Deskripsi Singkat
Admin melakukan kelola Kemuridan yang berisi Organisasi dan Ekstrakulikuler.
Deskripsi Langkah-langkah
1. Admin mengklik navbar Kemuridan.
2. Admin memilih menu yang ada pada Kemuridan.
3. Sistem akan menampilkan pilihan menu Kemuridan yang dipilih.
4. Admin melakukan kelola data pada pilihan menu yang dipilih.

Xref: Bagian 3.2.7, Mengelola Kemuridan

**2.2.8 User Melihat Tentang Kami**

Use Case: Melihat Tentang Kami

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MelihatTentangKami.png)

Deskripsi Singkat
User melihat Tentang Kami yang berisi ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri.
Deskripsi Langkah-langkah
1. User mengklik navbar Tentang Kami.
2. User memilih menu yang ada pada Tentang Kami.
3. Sistem akan menampilkan pilihan menu Tentang Kami yang dipilih.

Xref: Bagian 3.2.8, Melihat Tentang Kami

**2.2.9 User Melihat Profil Sekolah**

Use Case: Melihat Profil Sekolah

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MelihatProfilSekolah.png)

Deskripsi Singkat
User melihat Profil Sekolah yang berisi program sekolah, kalender akademik, dan fasilitas.
Deskripsi Langkah-langkah
1. User mengklik navbar Profil Sekolah.
2. User memilih menu yang ada pada Profil Sekolah.
3. Sistem akan menampilkan pilihan menu Profil Sekolah yang dipilih.

Xref: Bagian 3.2.9, Melihat Profil Sekolah

**2.2.10 User Melihat Berita**

Use Case: Melihat Berita

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MelihatBerita.png)

Deskripsi Singkat
User melihat Berita.
Deskripsi Langkah-langkah
1. User mengklik navbar Berita.
2. Sistem akan menampilkan menu Berita yang dipilih.

Xref: Bagian 3.2.10, Melihat Pengumuman

**2.2.11 User Melihat Pengumuman**

Use Case: Melihat Pengumuman

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MelihatPengumuman.png)

Deskripsi Singkat
User melihat Pengumuman.
Deskripsi Langkah-langkah
1. User mengklik navbar Pengumuman.
2. Sistem akan menampilkan menu Pengumuman yang dipilih.

Xref: Bagian 3.2.11, Melihat Pengumuman

**2.2.12 User Melihat Kontak**

Use Case: Melihat Kontak

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MelihatKontak.png)

Deskripsi Singkat
User melihat Kontak.
Deskripsi Langkah-langkah
1. User mengklik navbar Kontak.
2. Sistem akan menampilkan menu Kontak yang dipilih. 

Xref: Bagian 3.2.13, Melihat Kontak

**2.2.13 User Melihat Kemuridan**

Use Case: Melihat Kemuridan

Diagram:
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/MelihatKegiatanKemuridan.png)

Deskripsi Singkat
User melihat Kemuridan yang berisi Organisasi dan Ekstrakulikuler.
Deskripsi Langkah-langkah
1. User mengklik navbar Kemuridan.
2. User memilih menu yang ada pada Kemuridan.
3. Sistem akan menampilkan pilihan menu Kemuridan yang dipilih. 

Xref: Bagian 3.2.13, Melihat Kegiatan Kemuridan



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
Tidak ada persyaratan khusus untuk mengakses website ini, sehingga siapapun dapat mengakses website ini tanpa perlu login terlwbih dahulu.
      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1 Admin Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Admin |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
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
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik navbar Tentang <br> 2. Sistem akan menampilkan combobox pilihan ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri <br>3. Admin memilih combobox tersebut dan klik tombol tambah, hapus, atau edit <br> 4. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Tentang |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
**3.2.3 Admin Mengelola Profil Sekolah**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Profil Sekolah |
| Xref | Bagian 2.2.3, Mengelola Profil Sekolah |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik navbar Profil Sekolah <br> 2. Sistem akan menampilkan combobox pilihan program sekolah, kalender akademik, dan fasilitas <br>3. Admin memilih combobox tersebut dan klik tombol tambah, hapus, atau edit <br> 4. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Profil Sekolah |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
**3.2.4 Admin Mengelola Berita**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Berita |
| Xref | Bagian 2.2.4, Mengelola Berita |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik navbar Berita <br> 2. Admin klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Berita |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
**3.2.5 Admin Mengelola Pengumuman**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Pengumuman |
| Xref | Bagian 2.2.5, Mengelola Pengumuman |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik navbar Pengumuman <br> 2. Admin klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Pengumuman |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
**3.2.6 Admin Mengelola Kontak**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Kontak |
| Xref | Bagian 2.2.6, Mengelola Kontak |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik navbar Kontak <br> 2. Admin klik tombol tambah, hapus, atau edit <br> 3. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Kontak |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.7  Admin Mengelola Kemuridan**

|  |  |
|--|--|
| Nama Fungsi | Mengelola Kemuridan |
| Xref | Bagian 2.2.7, Mengelola Kemuridan |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. Admin mengklik navbar Kemuridan <br> 2. Sistem akan menampilkan combobox pilihan organisasi dan ekstrakulikuler <br>3. Admin memilih combobox tersebut dan klik tombol tambah, hapus, atau edit <br> 4. Sistem akan menampilkan hasil perubahan. |
| Alternative | Tidak ada |
| Post Condition | Admin melihat hasil perubahan Kemuridan |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.8 User Melihat Tentang Kami**

|  |  |
|--|--|
| Nama Fungsi | Melihat Tentang Kami |
| Xref | Bagian 2.2.8, Melihat Tentang Kami |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Tentang <br> 2. Sistem akan menampilkan combobox pilihan ucapan kepala sekolah, visi dan misi, data guru, prestasi, dan galeri <br>3. Sistem akan menampilkan hasil combobox yang dipilih. |
| Alternative | Tidak ada |
| Post Condition | User melihat hasil combobox yang yang dipilih |
| Exception Push | Tidak ada koneksi |
   
**3.2.9 User Melihat Profil Sekolah**

|  |  |
|--|--|
| Nama Fungsi | Melihat Profil Sekolah |
| Xref | Bagian 2.2.9, Melihat Profil Sekolah |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Profil Sekolah <br> 2. Sistem akan menampilkan combobox pilihan program sekolah, kalender akademik, dan fasilitas <br>3.  Sistem akan menampilkan hasil combobox yang dipilih. |
| Alternative | Tidak ada |
| Post Condition | User melihat hasil combobox yang dipilihh |
| Exception Push | Tidak ada koneksi |
   
**3.2.10 User Melihat Berita**

|  |  |
|--|--|
| Nama Fungsi | Melihat Berita |
| Xref | Bagian 2.2.10, Melihat Berita |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Berita <br> 2. Sistem akan menampilkan menu Berita. |
| Alternative | Tidak ada |
| Post Condition | User melihat menu Berita |
| Exception Push | Tidak ada koneksi |
   
**3.2.11 User Melihat Pengumuman**

|  |  |
|--|--|
| Nama Fungsi | Melihat Pengumuman |
| Xref | Bagian 2.2.11, Melihat Pengumuman |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Pengumuman <br> 2. Sistem akan menampilkan menu Pengumuman. |
| Alternative | Tidak ada |
| Post Condition | User meelihat menu Pengumuman |
| Exception Push | Tidak ada koneksi |
   
**3.2.12 User Melihat Kontak**

|  |  |
|--|--|
| Nama Fungsi | Melihat Kontak |
| Xref | Bagian 2.2.12, Melihat Kontak |
| Trigger | Membuka Website Profil SMP Al Azhar Syifa Budi Pekanbaru II |
| Precondition | Membuka halaman utama |
| Basic Path | 1. User mengklik navbar Kontak <br> 2. Sistem akan melihat Kontak. |
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
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/ERD%20Website%20Profile%20Sekolah-Page-1.drawio.png)

**Tabel Admin**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_user| varchar | Nomer auto increment id_admin |
| username | varchar | berisikan username untuk akses login admin |
| password | varchar | berisikan password untuk login admin |
| email | varchar | berisikan email dari admin |

**Tabel Guru**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_guru | varchar | Nomor auto increment id_prestasi|
| nip | int | NIP guru|
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

**Tabel Pengumuman**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_pengumuman | varchar | Nomor auto increment id_pengumuman|
| nama_pengumuman | varchar | Nama pengumuman |
| tanggal_pengumuman | date | Tanggal pengumuman |
| keterangan_pengumuman| text | Keterangan pengumuman |
| foto_pengumuman | varchar | Foto pengumuman |

**Tabel Galeri**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_galeri | varchar | Nomor auto increment id_galeri|
| nama_galeri | varchar | Nama galeri |
| tanggal_galeri | date | Tanggal galeri |
| keterangan_galeri| text | Keterangan galeri |
| foto_galeri | varchar | Foto galeri |
| video_galeri | varchar | Video galeri |

**Tabel Fasilitas**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_fasilitas | varchar | Nomor auto increment id_fasilitas|
| nama_fasilitas| varchar | Nama fasilitas |
| keterangan_fasilitas| text | Keterangan fasilitas |
| foto_fasilitas | varchar | Foto fasilitas |

**Tabel Ekstrakulikuler**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_ekstrakulikuler | varchar | Nomor auto increment id_ekstrakulikuler|
| nama_ekstrakulikuler| varchar | Nama ekstrakulikuler |
| keterangan_ekstrakulikuler| text | Keterangan ekstrakulikuler |
| foto_ekstrakulikuler | varchar | Foto ekstrakulikuler |

**Tabel Berita**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_berita| varchar | Nomor auto increment id_berita|
| nama_berita | varchar | Nama berita |
| tanggal_berita | date | Tanggal berita |
| keterangan_berita| text | Keterangan berita |
| foto_berita | varchar | Foto berita |

**Tabel Organisasi**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_organisasi | varchar | Nomor auto increment id_organisasi|
| nama_organisasi | varchar | Nama organisasi |
| keterangan_organisasi| text | Keterangan organisasi |
| foto_organisasi | varchar | Foto organisasi |

**Tabel Program Sekolah**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id_program| varchar | Nomor auto increment id_program|
| nama_program | varchar | Nama program |
| tanggal_program | date | Tanggal program |
| keterangan_program| text | Keterangan program |
| foto_program | varchar | Foto program |

3.4 Validasi Data Wawancara
----------
Validasi data wawancara dengan pihak SMP Al Azhar Syifa Budi Pekanbaru II.
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/SURAT%20VAIDASI%20SEKOLAH_KEL%206_FRAMEWORK_page-0001.jpg)
![enter image description here](https://github.com/dewikrnia/Kelompok4/blob/main/picture/SURAT%20VAIDASI%20SEKOLAH_KEL%206_FRAMEWORK_page-0002.jpg)

Job Desc
| Nama | Tugas | 
| ------ | ------ | 
| Dewi Kurnia Sari | SRS, Desain Website |
| Dyva Herza Nabila | SRS, Desain Website | 
| Farra Rumaisyah | SRS, Desain Website | 
