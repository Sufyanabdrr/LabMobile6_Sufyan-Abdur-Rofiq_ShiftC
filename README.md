# Tugas 6 Praktikum Pemrograman Mobile

Nama  : Sufyan Abdur Rofiq

NIM  : H1D022004

Shift Awal  : B

Shift Baru  : C

# A. Screenshot Halaman Utama :

![sufyanss1](https://github.com/user-attachments/assets/506b6035-0af9-4fdf-ae6e-33f3a6b19062)


![sufyanss2](https://github.com/user-attachments/assets/d5ac6ef9-a8e9-4713-845b-aa1e772c3bca)


# B. Cara untuk menambahkan Komponen di halaman Ionic :

1). Untuk menambahkan komponen di halaman Ionic, langkah pertama adalah memastikan bahwa perangkat sudah terinstall Node.js dan Ionic CLI, karena kedua alat ini diperlukan untuk menjalankan proyek Ionic. Node.js berfungsi sebagai lingkungan runtime untuk menjalankan JavaScript di server, sementara Ionic CLI adalah alat manajemen proyek Ionic. Jika Node.js belum terpasang, unduh dari situs resminya, install, dan verifikasi instalasinya dengan mengetik node -v di terminal. Ini akan menunjukkan versi Node.js yang terpasang. Setelah itu, instal Ionic CLI dengan menjalankan perintah npm install -g @ionic/cli di terminal. Ionic CLI akan memungkinkan pengelolaan proyek Ionic di perangkat. Untuk memastikan Ionic CLI terpasang dengan benar, ketik ionic -v di terminal untuk melihat versinya.

2). Setelah persiapan selesai, buat proyek baru dengan mengetik ionic start di terminal. Nantinya, akan ada pilihan untuk menentukan nama proyek dan template. Template ini menentukan struktur dasar aplikasi, seperti blank untuk halaman kosong, tabs untuk navigasi tab, atau sidemenu untuk aplikasi dengan menu samping. Setelah memilih template, Ionic akan mengunduh dan menyiapkan file-file dasar proyek, dan proses ini mungkin membutuhkan waktu beberapa menit. Setelah proyek selesai dibuat, masuk ke dalam direktori proyek dengan mengetik cd nama-proyek, sesuai nama proyek yang telah dipilih.

3). Di dalam direktori proyek, terdapat folder src, yang berisi seluruh kode sumber aplikasi. Semua halaman dan komponen berada di dalam subfolder app. Misalnya, halaman utama proyek (home) terletak di folder src/app/home. Buka folder home dan cari file home.page.html, yang merupakan file utama halaman beranda aplikasi. File ini adalah tempat untuk menambahkan komponen Ionic.

4). Untuk menambahkan komponen ke halaman, kunjungi situs Ionic Components, yang menyediakan berbagai macam komponen seperti tombol, daftar, kartu, dan form input. Setiap komponen memiliki contoh kode HTML yang dapat langsung digunakan dalam proyek. Misalnya, untuk menambahkan tombol, cari komponen ion-button di situs tersebut dan salin kode HTML-nya. Contoh kode tombol adalah <ion-button color="primary">Klik Saya</ion-button>, yang membuat tombol berwarna biru bertuliskan "Klik Saya".

5). Buka file home.page.html di editor teks, lalu tempelkan kode komponen tersebut di lokasi yang diinginkan dalam struktur halaman, misalnya di dalam tag <ion-content> untuk menampilkannya di tengah halaman. Penyesuaian tampilan tombol juga dapat dilakukan dengan mengubah atribut seperti warna (color), ukuran (size), atau jenis (expand). Misalnya, untuk membuat tombol berwarna merah dan berukuran besar, kode dapat diubah menjadi <ion-button color="danger" size="large">Klik Saya</ion-button>.

6). Setelah selesai menambahkan komponen, lakukan pengujian tampilan di aplikasi dengan menjalankan perintah ionic serve di terminal. Perintah ini akan menjalankan server lokal dan membuka aplikasi di browser, sehingga komponen yang telah ditambahkan dapat langsung dilihat. Server ini juga otomatis memperbarui tampilan di browser setiap kali perubahan di file disimpan, memudahkan untuk melihat hasilnya secara langsung. Dengan langkah-langkah ini, komponen Ionic akan muncul di halaman utama aplikasi sesuai dengan penyesuaian yang telah dibuat.
