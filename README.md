# Keamanan-data
Project: Alat GUI untuk Enkripsi dan Steganografi
Gambaran Umum
Proyek ini berisi tiga alat GUI Python untuk kriptografi dan steganografi, yang dikembangkan menggunakan Tkinter untuk antarmuka grafis. Setiap alat memiliki fungsi spesifik:

chipergui.py: Alat untuk melakukan enkripsi dan dekripsi menggunakan Caesar cipher.
desgui.py: Alat untuk melakukan enkripsi dan dekripsi menggunakan Data Encryption Standard (DES).
steganogui.py: Alat untuk menyembunyikan dan mengekstrak pesan teks dalam gambar menggunakan steganografi.
Alat-alat ini menyediakan antarmuka pengguna yang ramah untuk melakukan tugas-tugas umum dalam kriptografi dan penyembunyian data.

File-File
chipergui.py:
Antarmuka grafis (GUI) untuk enkripsi dan dekripsi Caesar Cipher.

Fitur:
Mengenkripsi pesan dengan Caesar cipher dengan pergeseran karakter.
Mendekripsi pesan yang dienkripsi dengan membalikkan pergeseran.
Kunci pergeseran yang dapat disesuaikan.
desgui.py:
GUI untuk enkripsi dan dekripsi menggunakan Data Encryption Standard (DES).

Fitur:
Mengenkripsi teks biasa menggunakan enkripsi DES.
Mendekripsi teks terenkripsi menggunakan dekripsi DES.
Memungkinkan pengguna untuk memasukkan kunci dan teks.
steganogui.py:
GUI untuk melakukan steganografi, yaitu menyembunyikan teks dalam gambar dan mengekstraknya.

Fitur:
Menyembunyikan pesan rahasia dalam file gambar (format JPEG).
Mengekstrak pesan tersembunyi dari file gambar.
Persyaratan
Pastikan Anda telah menginstal dependensi berikut:

Python 3.x
Tkinter (pip install tk untuk Python 3)
PyCryptodome (untuk DES) (pip install pycryptodome)
Pillow (untuk pengolahan gambar pada steganografi) (pip install pillow)
Penggunaan
1. chipergui.py (Caesar Cipher):
Untuk menggunakan alat enkripsi Caesar cipher:

Jalankan chipergui.py.
Masukkan pesan yang ingin dienkripsi di kotak input.
Tentukan nilai pergeseran (angka) untuk cipher.
Klik "Encrypt" untuk mengenkripsi pesan atau "Decrypt" untuk mendekripsinya.
Hasilnya akan ditampilkan di kotak hasil.
2. desgui.py (Enkripsi DES):
Untuk menggunakan alat enkripsi DES:

Jalankan desgui.py.
Masukkan teks biasa dan kunci (panjang 8 karakter).
Klik "Encrypt" untuk mengenkripsi pesan atau "Decrypt" untuk mendekripsinya.
Hasilnya akan ditampilkan di kotak output.
3. steganogui.py (Steganografi):
Untuk menggunakan alat steganografi:

Jalankan steganogui.py.
Untuk menyembunyikan pesan, pilih gambar dan masukkan pesan yang ingin disembunyikan. Kemudian klik "Hide Message".
Untuk mengekstrak pesan tersembunyi, pilih gambar yang berisi pesan tersembunyi dan klik "Extract Message".
Contoh Alur Kerja
Caesar Cipher:

Enkripsi pesan sederhana seperti "HELLO" dengan kunci pergeseran 3 → "KHOOR".
Dekripsi "KHOOR" kembali menjadi "HELLO" menggunakan kunci pergeseran yang sama.
Enkripsi DES:

Enkripsi pesan "HELLO WORLD" dengan kunci "12345678".
Dekripsi ciphertext kembali menjadi "HELLO WORLD" menggunakan kunci yang sama.
Steganografi:

Menyembunyikan teks "SECRET MESSAGE" dalam sebuah gambar.
Mengekstrak teks tersembunyi dari gambar.
