UAS PRAKTEK KOMUNIKASI DATA

DOSEN PENGAMPU :
 - Rian Rahmanda Putra, S.Kom., M.Kom

ANGGOTA :
 - RAFA ATSAAL RAMADHAN KAMAL
 - M. FARIZ ALFAHREZA
 - R. ISLAMI AL - BARIQ PASYAH
 - MUHAMMAD RIZKI IHWANI RIANTO

Repository ini berisi aplikasi chat client–server berbasis Python yang berjalan pada jaringan lokal menggunakan TCP socket dan antarmuka grafis Tkinter.

Program server berfungsi sebagai pusat komunikasi yang menerima banyak koneksi client secara bersamaan menggunakan mekanisme multithreading. Server mengelola client berdasarkan ID, menangani pesan broadcast ke seluruh client dan private message antar client, serta menampilkan log aktivitas komunikasi secara real time pada GUI server.

Program client menyediakan antarmuka grafis untuk mengirim dan menerima pesan. Client dapat mengirim pesan broadcast atau pesan privat ke client tertentu dengan format yang telah ditentukan. Setiap pesan yang dikirim dan diterima dicatat ke dalam file log client, lengkap dengan informasi waktu, kode ASCII pesan, dan perhitungan RTT saat pengiriman.

Aplikasi ini cocok digunakan sebagai media pembelajaran konsep client–server, socket programming TCP, multithreading, dan komunikasi jaringan lokal.
