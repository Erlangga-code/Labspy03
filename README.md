# Labspy03
Tugas Praktikum  Mata Kuliah Program Komputer dan Praktek
------------------------------------------------------------------------------------------------------------
**Algoritma Latihan1:**

Tampilkan Pesan:

    Menampilkan pesan ke pengguna untuk menginformasikan bahwa program akan menghasilkan bilangan acak yang kurang dari 0.5.

Input Jumlah:

    Meminta pengguna untuk memasukkan jumlah bilangan acak yang ingin dihasilkan. Nilai yang dimasukkan disimpan dalam variabel jumlah.

Inisialisasi Variabel Maksimum:

    Membuat variabel max dan menginisialisasinya dengan nilai 0. Meskipun variabel ini tidak digunakan dalam kode yang diberikan,
    kemungkinan besar ini adalah sisa dari kode sebelumnya yang bertujuan untuk mencari nilai maksimum. 
    Kita akan abaikan untuk saat ini.

Import Modul random:

    Mengimpor modul random yang menyediakan fungsi-fungsi untuk menghasilkan bilangan acak.

Perulangan:

    Melakukan perulangan sebanyak jumlah kali:

Mencetak nomor urut data (i+1).

    Menggunakan fungsi random.uniform(0, 0.5) untuk menghasilkan bilangan acak antara 0 (inklusif) dan 0.5 (eksklusif).

Mencetak bilangan acak yang dihasilkan.

**Hasil Program**


![Hasil 1](https://github.com/user-attachments/assets/513a9f67-9e0d-4c48-b160-255ceb85d937)

----------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------


Algoritma Latihan2 :
**
Inisialisasi Variabel:**

max diinisialisasi dengan nilai 0. Variabel ini akan digunakan untuk menyimpan bilangan terbesar yang ditemukan sejauh ini.
Perulangan Tak Terbatas:

**Input Bilangan:**
  
  
  Meminta pengguna untuk memasukkan sebuah bilangan. Bilangan ini akan disimpan dalam variabel a.
  Perbandingan: Membandingkan nilai a dengan nilai max yang sudah ada.
  Jika a lebih besar dari max: Nilai max diperbarui menjadi nilai a.
  Jika a sama dengan 0: Perulangan dihentikan (break).
**
Output:**
  
  Setelah perulangan selesai, nilai max (bilangan terbesar yang ditemukan) dicetak ke layar.


**Penjelasan Algoritma:**
  
  
  Algoritma ini bekerja dengan cara terus-menerus meminta pengguna untuk memasukkan bilangan. Setiap bilangan yang dimasukkan akan dibandingkan dengan bilangan terbesar yang sudah     
  ditemukan sejauh ini. 
  Jika bilangan yang baru dimasukkan lebih besar, maka bilangan terbesar akan diperbarui. Proses ini akan terus berulang sampai pengguna memasukkan angka 0 sebagai tanda berhenti.

**Contoh Pelaksanaan:**

Misalkan pengguna memasukkan bilangan-bilangan berikut: 5, 9, 3, 11, 0.

max awalnya bernilai 0.

Angka 5 dimasukkan, max menjadi 5.

Angka 9 dimasukkan, max menjadi 9.

Angka 3 dimasukkan, max tetap 9.

Angka 11 dimasukkan, max menjadi 11.

Angka 0 dimasukkan, perulangan berhenti.

Program mencetak "Bilangan terbesar adalah: 11".



**Hasil Program**

![Hasil 2](https://github.com/user-attachments/assets/94c3a096-d228-4c0c-ad6e-04744266b473)


**----------------------------------------------------------------------------------------------------------------------------------------**
**----------------------------------------------------------------------------------------------------------------------------------------**
**----------------------------------------------------------------------------------------------------------------------------------------**



Definisi Fungsi hitung_laba:

Fungsi ini menerima dua parameter: modal_awal (jumlah uang yang diinvestasikan) dan bunga (tingkat bunga dalam bentuk desimal).

Fungsi ini menghitung laba dengan mengalikan modal awal dengan suku bunga.

Fungsi ini mengembalikan nilai laba yang telah dihitung.


Input Data:

Meminta pengguna untuk memasukkan nilai modal awal dan suku bunga.

Nilai modal awal disimpan dalam variabel modal_awal sebagai bilangan bulat.

Nilai suku bunga disimpan dalam variabel bunga sebagai bilangan desimal.


Pemanggilan Fungsi:

Memanggil fungsi hitung_laba dengan argumen modal_awal dan bunga.

Hasil yang dikembalikan oleh fungsi disimpan dalam variabel laba.


Tampilkan Hasil:

Mencetak nilai laba ke layar.



**Hasil Program**


![Hasil 3](https://github.com/user-attachments/assets/15805062-02fe-465a-ac35-fd25322d5bb1)

