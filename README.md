Assignment: Express.js & Modul Node.js

IIDENTITAS

Nama : Putra Heryan Gagah Perkasa

NIM : F1D022087

DESKRIPSI TUGAS

Tugas ini bertujuan untuk membuat sebuah server web sederhana menggunakan framework Express.js pada lingkungan Node.js.

Server utama (index.js) akan menangani beberapa route:

Route / yang menampilkan identitas mahasiswa.

Route /hitung yang memanfaatkan fungsi tambah() dari modul lokal utils/math.js untuk melakukan penjumlahan.

Route /profile yang di-handle oleh modul router terpisah (routes/profile.js) untuk menampilkan data profil dalam format JSON. Router ini juga menangani parameter dinamis untuk menampilkan detail profil berdasarkan NIM.

HASIL

Berikut adalah hasil eksekusi dari setiap endpoint yang telah dibuat, diakses melalui browser.

1. Halaman Utama (/)

Halaman ini adalah endpoint root dari server yang menampilkan nama lengkap dan NIM mahasiswa.

<img width="1919" height="1020" alt="file_2025-09-25_15 22 04" src="https://github.com/user-attachments/assets/28757d4a-c807-481c-9c4b-d414a61d3e46" />


2. Halaman Perhitungan (/hitung)

Endpoint ini memanggil fungsi tambah(15, 10) dari modul utils/math.js dan menampilkan hasilnya ke browser.

<img width="1919" height="1019" alt="file_2025-09-25_15 22 48" src="https://github.com/user-attachments/assets/05980340-625e-4c48-b1a7-480a9085d24a" />


3. Halaman Daftar Profile (/profile)

Endpoint ini menampilkan seluruh data profil yang tersimpan dalam bentuk array JSON pada file routes/profile.js.

<img width="1919" height="1018" alt="file_2025-09-25_15 23 50" src="https://github.com/user-attachments/assets/97c08792-309e-4647-b1ec-f6a821821fb4" />


4. Halaman Detail Profile (/profile/F1D022087)

Endpoint dinamis ini menampilkan detail dari satu profil spesifik berdasarkan nim yang diberikan sebagai parameter di URL.

<img width="1919" height="1016" alt="file_2025-09-25_15 24 26" src="https://github.com/user-attachments/assets/21cb2a14-0611-4e4c-b38a-46a304e700df" />

[GANTI BARIS INI DENGAN SCREENSHOT ANDA]

Contoh: ![Hasil Halaman Detail Profile](./screenshots/hasil-detail-profile.png)
