# project-UAS-pemrograman
Kelas Data




![uas1](https://github.com/user-attachments/assets/7b3a76da-6602-4f37-84dc-a5718972ad10)

Kelas Data digunakan untuk menyimpan dan mengelola daftar buku.

Inisialisasi: __init__ menginisialisasi atribut books sebagai daftar kosong.

Menambahkan Buku: add_book menambahkan judul buku ke dalam daftar books.

Menghapus Buku: remove_book menghapus judul buku dari daftar jika ada dalam books.

Mendapatkan Daftar Buku: get_books mengembalikan daftar buku yang ada.

Kelas View





![uas2](https://github.com/user-attachments/assets/8cc4521e-db2b-4429-a405-2a6fdbc49ab6)

Kelas View digunakan untuk interaksi dengan pengguna.

Menampilkan Buku: display_books menampilkan daftar buku yang ada.

Mendapatkan Input Pengguna: get_user_input meminta pengguna untuk memasukkan judul buku.

Menampilkan Pesan: show_message menampilkan pesan kepada pengguna.


class Process



![uas3](https://github.com/user-attachments/assets/9190f1aa-4952-44ad-a709-c2191518bc39)
Kelas Process mengelola logika aplikasi dengan menggunakan Data dan View.

Inisialisasi: __init__ menginisialisasi objek Data dan View.

Menambahkan Buku: add_book meminta pengguna memasukkan judul buku, menambahkannya ke daftar, dan menampilkan pesan konfirmasi. Pengguna dapat terus menambahkan buku sampai memilih untuk berhenti.

Menghapus Buku: remove_book meminta pengguna memasukkan judul buku dan menghapusnya dari daftar, lalu menampilkan pesan konfirmasi.

Menampilkan Daftar Buku: show_books mengambil daftar buku dari objek Data dan menampilkannya melalui View.

Menjalankan Aplikasi: run menjalankan loop utama yang menampilkan menu, menerima pilihan pengguna, dan memanggil metode sesuai dengan pilihan tersebut. Pengguna dapat menambah buku, menghapus buku, menampilkan daftar buku, atau keluar dari aplikasi.


class main




![uas4](https://github.com/user-attachments/assets/3b8e4843-0a2a-491e-9734-bc5ee68e6963)


Kode berikut menggabungkan kelas Data, View, dan Process dan menjalankan aplikasi saat file dijalankan sebagai program utama.

Jika file dijalankan sebagai program utama, instance Process dibuat dan metode run dipanggil untuk memulai aplikasi.


hasil kode di atas

![uas hasil](https://github.com/user-attachments/assets/6a885bd4-24fe-4d27-98f3-49e2781683ef)


Link youtube
https://youtu.be/_k93VZJdZD0?si=fxDOG6TdV3zJMI56

