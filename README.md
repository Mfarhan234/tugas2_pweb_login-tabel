# Tugas 2 - Login dan Tabel

Identitas
Nama: Muhammad Farhan
NRP: 5054241018
Jurusan: Rekayasa Kecerdasan Artifisial
Kelas: Pemrograman Web

Tentang Tugas Ini
Pada pertemuan ke-2, tugas yang diberikan adalah membuat halaman tabel dan form login menggunakan HTML dasar. Tujuannya untuk memahami struktur elemen, atribut, dan tag umum pada HTML.

Isi Website
1. Tabel Nilai
	File: index.html

	Bagian ini menampilkan tabel nilai siswa dengan header gabungan:
	- `rowspan` pada kolom Nama untuk menggabungkan dua baris header.
	- `colspan` pada kolom Nilai untuk membagi ke tiga mata pelajaran.
	- Baris data berisi contoh nilai Kimia, Fisika, dan Biologi.

2. Form Login
	File: index.html

	Bagian ini berisi form login sederhana:
	- Input username (`type="text"`).
	- Input password (`type="password"`).
	- Checkbox "Remember me".
	- Tombol submit untuk login.

Struktur File
Pertemuan_2/tugas2_pweb_login-tabel/
├── index.html
└── README.md

Penjelasan Kode HTML
index.html
- Menggunakan tag `<table>`, `<tr>`, `<th>`, dan `<td>` untuk membangun tabel.
- Atribut `rowspan` dan `colspan` dipakai untuk mengatur header tabel.
- Form login dibungkus dengan `<fieldset>` dan `<legend>` agar tampil jelas.
- Styling dasar menggunakan atribut `style` langsung pada elemen.

Catatan
Proyek ini bersifat statis dan hanya berfokus pada latihan struktur HTML dasar, tanpa JavaScript atau backend.


