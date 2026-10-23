Simple Expert System (Sistem Pakar) Diagnosis Penyakit Tanaman
======================================================================
1.Introduction:


Aplikasi ini adalah program Sistem Pakar berbasis Command Line Interface (CLI)
yang dibangun menggunakan bahasa pemrograman Python. 

Program ini menerapkan metode pencarian Forward Chaining (Pelacakan Maju)
untuk mencocokkan fakta berupa gejala-gejala tanaman yang diinputkan oleh 
pengguna ke dalam basis pengetahuan (rules). Hasil akhirnya berupa identifikasi 
jenis penyakit serta saran solusi penanganan yang tepat.

Metode: Forward Chaining
Bahasa: Python 3.x


2. Requirements (Kebutuhan Sistem)


Sebelum menjalankan program sistem pakar ini, pastikan perangkat komputer atau laptop telah memenuhi prasyarat berikut:

Perangkat Lunak Utama: Python (Versi 3.x direkomendasikan).

Modul / Library: Tidak memerlukan instalasi library tambahan eksternal (murni menggunakan built-in library bawaan Python).

Environment: Terminal, Command Prompt (Windows), atau PowerShell / Bash untuk menjalankan skrip berbasis CLI (Command Line Interface).



3. How to Use (Cara Penggunaan)


Ikuti langkah-langkah berikut untuk mengoperasikan program di laptop masing-masing:

1.Simpan File Program
Buat sebuah file baru bernama expert_system.py di dalam folder project, lalu masukkan kode Python sistem pakar yang sudah dibuat sebelumnya.

2.Buka Terminal / Command Prompt
Arahkan direktori terminal ke folder tempat file expert_system.py berada menggunakan perintah:

Bash


cd path/ke/folder-project
3.Jalankan Program
Eksekusi program menggunakan perintah Python:

Bash


python expert_system.py
4.Masukkan Input Gejala

Program akan menampilkan daftar pilihan gejala (angka 1 sampai 4).

Ketik nomor gejala yang ingin didiagnosis. Jika memilih lebih dari satu gejala, pisahkan menggunakan tanda koma (contoh: 1,2).

Tekan Enter untuk memproses.

3. Result (Hasil Output Program)
Program sistem pakar ini memproses input pengguna menggunakan logika Forward Chaining untuk memberikan hasil diagnosis. 

