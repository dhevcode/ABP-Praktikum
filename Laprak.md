<div align="center">
  <h3>LAPORAN PRAKTIKUM<br>APLIKASI BERBASIS PLATFORM</h3>
  <h>
  <br>
  <h3>MODUL 1<br>PENGENALAN GIT</h3>
  <br>
  <img src="assets/logotelu.png" alt="Logo Telkom" width="200">
  <br>
  <br>

**Disusun Oleh :**<br>
Dheva Dewa Septiantoni<br>
2311102324<br>
IF-11-01
<br>
<br>

**Dosen Pengampu :**<br>
Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom
<br>
<br>

**Assisten Praktikum :**<br>
Apri Pandu Wicaksono<br>
Rangga Pradarrell Fathi
<br>
<br>

PROGRAM STUDI S1 TEKNIK INFORMATIKA<br>
FAKULTAS INFORMATIKA<br>
UNIVERSITAS TELKOM PURWOKERTO<br>
2026

</div>

---

## 1. Dasar Teori

**Git** adalah sistem pengontrol versi (Version Control System) yang digunakan untuk mencatat dan merekam setiap jejak perubahan pada file proyek, baik saat dikerjakan secara mandiri maupun dalam kolaborasi tim. Karena bersifat terdistribusi, Git tidak hanya mengandalkan satu pusat penyimpanan saja, melainkan setiap pengguna memiliki salinan database riwayat proyek secara utuh di perangkat masing-masing.

**GitHub** adalah layanan platform berbasis web yang digunakan untuk menyimpan dan mengelola repositori Git secara online. Melalui GitHub, pengguna dapat mengunggah, menyimpan, dan membagikan proyek agar dapat diakses dari mana saja.

**Command Line Interface (CLI)** adalah antarmuka berbasis teks yang memungkinkan pengguna berinteraksi dengan komputer melalui perintah yang diketik di terminal atau command prompt. Dalam Git, CLI digunakan untuk menjalankan perintah seperti membuat repositori, menambahkan file, melakukan commit, dan mengunggah proyek ke GitHub.

## 2. Langkah Praktikum

Berikut adalah urutan langkah-langkah untuk melakukan inisialisasi dan setup repositori dari lokal ke GitHub melalui CLI:

### a. Langkah 1: Membuat Repositori Baru di GitHub

Langkah pertama yang harus dilakukan adalah membuat repositori atau wadah baru di platform GitHub. Repositori ini nantinya akan bertindak sebagai tempat penyimpanan online untuk kode proyek kita. Lebih jelasnya seperti pada gambar berikut:

![Gambar 1](assets/L1.png)

### b. Langkah 2: Panduan Perintah Git

Setelah repositori dibuat, GitHub otomatis akan menampilkan panduan daftar perintah ('command') yang diperlukan. Perintah-perintah dasar ini yang nantinya akan kita eksekusi di terminal untuk menyambungkan folder lokal komputer ke repositori online. Lebih jelasnya seperti pada gambar berikut:

![Gambar 2](assets/L2.png)

### c. Langkah 3: Membuat Folder dan File Proyek

Buat dan siapkan folder dan file proyek pada komputer untuk menyimpan file yang digunakan untuk diunggah ke GitHub. Di dalam folder tersebut dapat dibuat file sederhana, seperti file teks, README.md, file codingan, dll. Lebih jelasnya seperti pada gambar berikut:

![Gambar 3](assets/L3.png)


### e. Langkah 4: Menjalankan Perintah Git melalui Command Prompt

Pada tahap ini, kita menggunakan serangkaian perintah Git secara berurutan untuk proses sinkronisasi folder lokal ke GitHub melalui terminal dilakukan dengan urutan perintah berikut:
<br>- 'git init': Mengubah folder biasa menjadi repositori Git lokal dengan membuat database .git.
<br>- 'git add .': Memasukkan semua file (laporan, kodingan, dan folder assets) ke dalam antrean staging area.
<br>- 'git commit -m "pesan"': Mengunci dan menyimpan riwayat perubahan secara permanen di database lokal.
<br>- 'git branch -M main': Mengatur nama cabang utama menjadi main sesuai standar GitHub terbaru.
<br>- 'git remote add origin [URL]': Menghubungkan alamat repositori online di GitHub dengan folder di laptop.
<br>- 'git push -u origin main': Mengunggah seluruh data dari komputer ke server GitHub agar bisa diakses secara publik.

<br>Lebih jelasnya pada gambar berikut:

![Gambar 4](assets/L4.png)

<br>Pada gambar tersebut diketahui mendapatkan eror saat upload file ke repositori, saya coba ulang untuk menguploadnya dan ternyata berhasil

### e. Langkah 5: Memeriksa Repository di Github

Buka kembali halaman repository di Github untuk memastikan file yang telah diunggah munsul dalam repository. Jika file sudah terlihat, maka proses upload telah berhasil. Lebih jelasnya seperti pada gambar berikut:

![Gambar 5](assets/L5.png)

## 3. Kesimpulan dan Penutup

Berdasarkan hasil praktikum yang telah dilakukan, dapat disimpulkan bahwa penggunaan Git sangat penting dan berguna bagi mahasiswa Informatika untuk mencatat dan merekam setiap jejak perubahan pada file proyek, dengan GitHub sebagai wadahnya. Serta, penguasaan perintah CLI seperti 'git init' dan 'git push', mahasiswa dapat melakukan manajemen repositori dengan lebih efisien dan terkontrol.


## 4. Referensi

- [Materi Modul 1](https://drive.google.com/file/d/1v2HYQXoUcKedERxtmi9eJqeZ1MsQZ5T4/view)
