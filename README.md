<h1 align="center">TUGAS ANALISIS PEMROGRAMAN ⁠BERBASIS OBJEK :electron:</h1>

<h3>Anggota Kelompok 1 :a: :parking: :b: :o2:</h3>

ico | Nama | NPM | Branch | Task
:---: | :---: | :---: | :---: | :---:
:trollface: | [Husein Zidan](https://github.com/ZIDANIDROS) | 4522210012 | `Master` | solving & pembuatan UML atau Class Diagram
:bowtie: | [Adi Pramono](https://github.com/GeneralFizi) | 4520210001 | `Adi-pramono` | material & Interview
:woman: | [Zahra Jane Arnecia](https://github.com/janerysn) | 4522210028 | `Zahra-Jane` | Membuat Materi Problem & UI/UX Design
:neckbeard:| [Dimas Satrio Parikesit](https://github.com/Dimsstr) | 4522210002 | `Dimas` | Analisis & ERD 
:shipit:| [Muhammad Sulthan Zharfan](https://github.com/SulthanZharfan) | 4522210016 | `SultanZharfan` | Membuat fitur-fitur, Flowchart, & Use case

<p align="center">
 <img width="100px" src="https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/LOGO/logonya-removebg-preview.png" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">SultanBarber.app :barber:</h2>
 <p align="center">Pengembangan UKM dari unit usaha Barbershop "Sultan Barber" semoga sukses sampai selesai, amin.</p>
</p>
  <p align="center">
    <a href="https://github.com/ZIDANIDROS/SultanBarber.App/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/ZIDANIDROS/SultanBarber.App" />
    </a>
    <a href="https://codecov.io/gh/ZIDANIDROS/SultanBarber.App">
      <img alt="Tests Coverage" src="https://codecov.io/gh/ZIDANIDROS/SultanBarber.App/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/ZIDANIDROS/SultanBarber.App/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/ZIDANIDROS/SultanBarber.App?color=0088ff" />
    </a>
    <a href="https://github.com/ZIDANIDROS/SultanBarber.App/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/ZIDANIDROS/SultanBarber.App?color=0088ff" />
    </a>
    <a href="https://securityscorecards.dev/viewer/?uri=github.com/ZIDANIDROS/SultanBarber.App">
      <img alt="OpenSSF Scorecard" src="https://api.securityscorecards.dev/projects/github.com/ZIDANIDROS/SultanBarber.App/badge" />
    </a>
    <br />
    <br />
  </p>

1. [Cerita Bisnisnya](#Cerita-Bisnisnya)
2. [Actor](#Actor)
3. [Problem](#Problem)
5. [Solving](#Solving)
6. [Fitur](#Fitur)
7. ⁠[⁠Use Case dan Flowchart](#Use-cases-dan-Flowchart)
8. ⁠[Dokumen](#Dokumentasi)
9. ⁠[ERD](#ERD)
10. ⁠[Class Diagram](#Class-Diagram)
11. ⁠[Design UI dan Wireframe](#Design-UI-dan-Wireframe)

# Cerita Bisnisnya

Alur sesi wawancara sudah tersedia di Youtube :movie_camera:
[klik disini](https://youtu.be/2IEAi9ZAAJE)

# Actor

<h4>:busts_in_silhouette: Customer : </h4>
1. Kondisi adanya kebutuhan untuk memesan jadwal potong rambut menunjukkan bahwa adanya kesulitan dalam mengatur waktu dan mendapatkan layanan potong rambut secara optimal <br>
2. Ketersediaan informasi mengenai antrian pelanggan penting untuk memberikan transparansi kepada pelanggan tentang kapan mereka dilayani <br>
3. Kondisi adanya menuntut akses cepat dan jelas mengenai tempat parkir yang tersedia pada barber <br>
4. Kebutuhan tersedianya informasi daftar model rambut yang ditawarkan akan membantu pelanggan dalam membuat keputusan yang tepat sesuai dengan keinginan mereka <br>
5. Kondisi pelanggan ingin mengetahui tren terbaru dalam model rambut serta model rambut yang sesuai dengan gaya dan preferensi mereka <br>
6. Kemudahan dalam melakukan pembayaran menjadi faktor penting bagi kenyamanan pelanggan <br>
7. Kondisi pelanggan tidak sempat untuk pergi ke barbershop untuk memotong rambut menunjukan bahwa adanya peluang bagi barber untuk pelayanan home service <br><br>

<h4>:busts_in_silhouette: Capster : </h4> 
1. Kondisi dimana pemotong dapat mengelola waktu mereka lebih baik dan meningkatkan kepuasaan pelanggan dengan mengurangi waktu tunggu <br>
2. Kondisi dimana pemotong dapat cepat mengakses informasi tentang preferensi pelanggan sehingga memungkinkan memberikan layanan yang lebih sesuai <br>
3. Kondisi dimana pemotong dapat memiliki transaksi dapat dilakukan dengan cepat dan aman, menghemat waktu pelanggan dan pemotong rambut <br>
4. Kondisi pemotong rambut dapat dengan mudah melacak dan mengelola antrian pelanggan yang menggunakan layanan home serving, memungkinkan pemotong untuk menyesuaikan jadwal secara efisien <br> <br>

<h4>:bust_in_silhouette: Manager : </h4> 
1. Kondisi adanya menuntut kemudahan dalam membuat, mengatur dan melacak berbagai promosi yang ditawarkan <br>
2. Kebutuhan untuk mengelola informasi keanggotaan pelanggan, termasuk status keanggotaan, reward, dan riwayat transaksi <br>
3. Kondisi melacak persediaan barang secara real time, mengelola pembelian dan pengeluaran, sera mengatur stok barang dengan tepat <br>
4. Kemudahan untuk melacak dan melaporkan masalah atau kerusakan peralatan, sehingga dapat segera mengambil tindakan perbaikan untuk meminimalkan dampak pada barbershop <br>
5. Kemudahan dalam melacak penjualan memberikan informasi yang berharga tentang kinerja penjualan barber, memungkinkan manajer untuk mengidentifikasi tren dan mengevaluasi promosi <br>
6. Pelacakan jumlah pelanggan per minggu memberikan wawasan tentang tingkat kunjungan salon dari waktu ke waktu <br>
7. Kemudahan untuk mengatur jadwal pemeliharaan peralatan dan fasilitas secara efisien, mencegah kerusakan yang tidak terduga, dan menjaga kualitas layanan <br>
8. Kondisi  menghitung gaji karyawan secara otomatis berdasarkan parameter yang ditentukan, mengurangi kesalahan dan adil dalam penggajian <br>
9. Kemudahan untuk melacak kinerja karyawan secara objektif, memberikan penghargaan kepada karyawan yang bekerja keras <br>
10. Kondisi manajer mencatat setiap transaksi pembayaran yang dilakukan oleh pelanggan, mencatat detail seperti jumlah yang dibayarkan, metode pembayaran, dan item atau layanan yang dibeli.<br>

# Problem

<h4>Customer : :interrobang:</h4>
1. Membutuhkan aplikasi untuk memesan jadwal potong rambut <br>
2. Membutuhkan informasi antrian pelanggan untuk mengetahui kapan giliran mereka akan tiba <br>
3. Membutuhkan informasi untuk mengetahui ketersediaan parkir <br>
4. Membutuhkan informasi daftar model rambut yang tersedia <br>
5. Membutuhkan informasi daftar model rambut yang sedang populer dan cocok dengan mereka <br>
6. Membutuhkan aplikasi untuk melakukan pembayaran melalui gateway yang tersedia <br>
7. Membutuhkan aplikasi dapat mengakses riwayat potongan rambut sebelumnya <br>
8. Membutuhkan akses yang mudah dalam pembelian produk pada barbershop <br>
9. Membutuhkan opsi untuk mendapatkan layanan salon di rumah mereka tanpa harus pergi ke barbershop<br><br>

<h4>Capster : :interrobang:</h4>
1. Membutuhkan informasi tentang antrian pelanggan untuk mengatur jadwal mereka dan memberikan layanan yang lebih efisien <br>
2. Membutuhkan akses cepat untuk melihat pesanan dan informasi pelanggan <br>
3. Membutuhkan proses pembayaran yang lebih variatif agar tidak merepotkan mencari cash dalam kembalian <br>
4. Membutuhkan cara untuk mengatur dan memprioritaskan antrian pelanggan di berbagai lokasi yang berbeda<br><br>
  
<h4>Manager : :interrobang:</h4>
1. Menghadapi kesulitan dalam merancang dan melacak efektivitas promosi untuk menarik pelanggan baru dan mempertahankan pelanggan yang sudah ada <br>
2. Membutuhkan mengelola keanggotaan pelanggan dengan efisien untuk meningkatkan loyalitas pelanggan dan memberikan layanan yang lebih baik <br>
3. Membutuhkan pengelolaan inventaris produk dan perlengkapan salon dengan efisien untuk memastikan ketersediaan barang yang memadai <br>
4. Membutuhkan pemantauan dan menangani kerusakan peralatan salon dengan cepat untuk menghindari gangguan dalam layanan <br>
5. Membutuhkan pemantauan kinerja penjualan untuk mengidentifikasi tren dan membuat keputusan strategis yang tepat <br>
6. Membutuhkan pemantauan jumlah pelanggan yang dilayani setiap minggu untuk mengukur kinerja salon <br>
7. Membutuhkan perlu mengatur jadwal pemeliharaan rutin peralatan dan fasilitas salon untuk memastikan operasi yang lancar <br>
8. Membutuhkan menghitung gaji karyawan dengan akurat berdasarkan kinerja dan jam kerja mereka <br>
9. membutuhkan cara untuk mencatat dan melacak pembayaran yang dilakukan oleh pelanggan untuk layanan atau produk yang mereka beli di salon<br>

# Solving 

<h4>Customer : :thinking:</h4>
Mengetahui adanya problem yang berkaitan dengan aktor customer maka solusi yang dilakukan adalah melakukan upaya dalam implementasi  pembuatan aplikasi atau sistem  yang bertujuan untuk mendukung dalam meningkatkan jalannya kinerja operasional toko, maka dari itu toko dapat melakukan pengenalan (promosi) dari sistem atau aplikasi yang dibuat kepada customer dengan harapan dapat memudahkan customer dalam mengetahui ketersediaan pelayanan toko melalui fitur-fitur yang tersedia. <br><br>

<h4>Capster : :thinking:</h4>
Mengetahui adanya problem yang berkaitan dengan aktor pemotong maka solusi yang dilakukan adalah melakukan upaya dalam implementasi pembuatan aplikasi atau sistem yang bertujuan untuk memudahkan pemotong dalam melakukan pekerjaan nya dalam melayani customer melalui fitur-fitur yang tersedia <br><br>

<h4>Manajer : :thinking:</h4>
Mengetahui adanya problem yang berkaitan dengan aktor Manajer, problem yang ada meliputi perancangan dan keberlangsungan operasional toko, maka solusi yang dilakukan adalah melakukan upaya dalam implementasi pembuatan aplikasi atau sistem  yang bertujuan untuk mendukung dan meningkatkan jalanya kinerja operasional toko. Aplikasi atau sistem yang dibuat bertujuan untuk memudahkan manajer dalam mengawasi, mengatur dan mengelola keberlangsungan operasional toko.<br>

# Fitur
<h4>Pelanggan : :receipt:</h4>
1. Pendaftaran: Mendaftar akun pelanggan baru.<br>
2. Masuk: Masuk ke akun pelanggan yang sudah terdaftar.<br> 
3. Detektor Antrian: Menampilkan informasi mengenai antrian pelanggan yang sedang menunggu. <br> 
4. Ketersediaan Tempat Parkir: Menampilkan informasi tentang ketersediaan tempat parkir jika tersedia. <br>
5. Reservasi: Mengatur dan melakukan reservasi untuk layanan yang diinginkan.<br>
6. Menu Gaya Rambut: Menampilkan menu pilihan potongan rambut yang tersedia.<br>
7. Gaya Populer: Menampilkan potongan rambut atau gaya yang sedang populer atau tren.<br>
8. Tampilan Nama Pemotong: Menampilkan nama-nama pemotong rambut yang tersedia.<br>
9. Tampilan Nomor Antrian: Menampilkan nomor antrian pelanggan yang sedang menunggu. <br>
10. Opsi Opsional: Menyediakan opsi tambahan atau fitur opsional untuk mempersonalisasi layanan. <br>
11. Pembelian: Membeli layanan atau produk yang ditawarkan.<br>
12. Pemrosesan Pembayaran: Mengelola proses pembayaran untuk layanan atau produk yang dibeli. <br>
13. Langganan: Menawarkan layanan berlangganan untuk pelanggan yang ingin mendapatkan manfaat secara berkala atau reguler.<br>
14. Home Serving: Menawarkan layanan dirumah untuk pelanggan yang tidak dapat ke tempat potong rambut.<br><br>

<h4>Capster : :receipt:</h4>
1. Pendaftaran: Mendaftar akun pemotong baru.<br>
2. Masuk: Masuk ke akun pemotong yang sudah terdaftar.<br>
3. Detektor Antrian Pelanggan: Mengidentifikasi dan mendeteksi antrian pelanggan yang sedang menunggu untuk mendapatkan layanan. <br>
4. Tampilan Pesanan dan Keterangan Pelanggan: Menampilkan pesanan yang telah dibuat oleh pelanggan beserta keterangan atau permintaan khusus mereka.<br>
5. Detektor Antrian Pelanggan Home Serving: Menawarkan layanan dirumah untuk pelanggan yang tidak dapat ke tempat potong rambut.<br><br>

<h4>Manager : :receipt:</h4>
1. Pendaftaran: Mendaftar akun manager baru.<br>
2. Masuk: Masuk ke akun manager yang sudah terdaftar.<br>
3. Manajemen Promo: Mengelola dan menetapkan promosi atau diskon untuk pelanggan.<br>
4. Manajemen Keanggotaan: Mengelola program keanggotaan dan manfaat yang ditawarkan kepada anggota.<br>
5. Manajemen Inventaris Barber: Mengelola inventaris barang-barang yang digunakan di salon cukur.<br>
6. Pelacakan Kerusakan: Melacak dan mencatat jumlah kerusakan atau barang yang rusak.<br>
7. Pelacakan Penjualan: Melacak dan mencatat jumlah produk yang terjual.<br>
8. Jumlah Pelanggan per Minggu: Memonitor jumlah pelanggan yang datang setiap minggu.<br>
9. Strategi Pemeliharaan Pelanggan: Mengembangkan strategi untuk meningkatkan loyalitas pelanggan dan memastikan pelanggan kembali lagi.<br>
10. Penentuan Gaji: Menentukan gaji karyawan berdasarkan seberapa banyak pelanggan yang dilayani atau berapa banyak penjualan yang berhasil mereka lakukan.<br>
11. Karyawan Terbaik: Menentukan siapa karyawan terbaik, dihitung dari berapa banyak pelanggan yang dia hadapi.<br>
12. Pencatatan Pembayaran: Manajer dapat mencatat setiap pembayaran yang diterima dari <br>
13. pelanggan dan melacaknya dalam sistem manajemen barbershop.<br> <br>

# Use cases dan Flowchart 
<h3>:hammer_and_wrench: by Lucid :</h3>
<p>Use case:</p>
<img width="700px" src="https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/Use%20Case/Use%20Case.png"/>


Flowchart: ![alt text](https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/Flowchart/Flowchart.png)

# Dokumen

<p>:page_with_curl: bentuk lembaran</p>
<img width="500px" src="https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/Resi%20penjualan/resi%20sulthan%20barber.jpg"/>
<img width="500px" src="https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/Kartu%20member%20fisik/kartu%20member%20fisiknya.jpg"/>

# ERD
:shield:
![alt text](https://github.com/ZIDANIDROS/SultanBarber.App/blob/Dimas/ERD/APBO%20-%20ERD.png)

# Class Diagram
<h3>by Lucid :</h3>

:link: Link : [klik disini](https://lucid.app/lucidchart/4dde6727-8048-4163-a0c7-6789dffc82c0/edit?invitationId=inv_53a062ca-b970-428d-9bf0-a52037a43409&page=0_0#)

![alt text](https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/UML/UML3.JPG)

# Design UI dan Wireframe 
<h3>by Figma : :calling:</h3>

:link: Link : [klik disini](https://www.figma.com/file/S1PQS5DUcDWCtzFdWmuR1c/mobile-apbo?type=design&node-id=331-1351&mode=design&t=Xre9iz46xr9cBASv-0)

- Mockup Konsumen
<img src="https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/Figma/MockUp/Mockup%20Konsumen.png" alt="Mockup Konsumen" align="bottom">
- Mockup Pegawai 
<img src="https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/Figma/MockUp/Mockup%20Pegawai.png" alt="diagram" align="bottom">
- Wireframe Konsumen 
<img src="https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/Figma/Wireframe/Wireframe%20Konsumen.png"alt="Wireframe Konsumen" align="bottom">
- Wireframe Pegawai
<img src="https://github.com/ZIDANIDROS/SultanBarber.App/blob/master/Figma/Wireframe/Wireframe%20Pegawai.png"alt="Wireframe Pegawai" align="bottom">


LINK YOUTUBE TUGAS UTS :link: Link : [klik disini](https://www.figma.com/file/S1PQS5DUcDWCtzFdWmuR1c/mobile-apbo?type=design&node-id=331-1351&mode=design&t=Xre9iz46xr9cBASv-0)
