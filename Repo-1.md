<h1>Menginstall Git</h1>

Step-Step untuk menginstall Git :

<ol>
  <li>Download terlebih dahulu di https://git-scm.com/downloads</li>
  <li>Jika sudah ter-download, Jalankan aplikasi Git</li>
  <li>Akan dimunculkan lisensi. Klik <b>Next</b> saja untuk lanjut</li>
  <li>Setelah itu pilih lokasi instalasi, boleh selain data C. Jika sudah Klik <b>Next</b> lagi untuk lanjut</li>
  <li>Pilih Komponen. Jika sudah Klik <b>Next</b> lagi untuk lanjut</li>
  <li>Mengisi shortcut untuk menu Start. Gunakan default (Git). Jika sudah Klik <b>Next</b> lagi untuk lanjut</li>
  <li>Pilih editor yang akan digunakan bersama dengan Git.  Jika sudah Klik <b>Next</b> lagi untuk lanjut</li>
  <li>Selanjutnya Di bagian <b>Adjusting your PATH environment</b> Pilih <b>Use Git from the Windows Command Prompt</b>. Jika sudah Klik <b>Next</b> lagi untuk lanjut</li>
  <li>Selanjutnya Di bagian <b>Choosing HTTPS transport backend</b> Pilih <b>Use the OpenSSLLibrary</b>. Jika sudah Klik <b>Next</b> lagi untuk lanjut</li>
  <li>Selanjutnya Di bagian <b>Configuring the line ending conversions</b> Pilih <b>Checkout windows style, commit Unix-style line endings</b>. Jika sudah klik <b>Next</b> lagi untuk lanjut</li>
  <li>Selanjutnya Di bagian <b>Configuring the terminal emulator to use with git Bash</b> Pilih <b>Use MinTTY (the default terminal of MSYS2)</b>. Jika sudah Klik <b>Next</b> lagi untuk lanjut</li>
  <li>Selanjutnya Di bagian <b>Configuring extra options</b> Pilih <b>Enable file system catching</b> dan <b>Enable Git Credential Manager</b>. Jika sudah Klik <b>Next</b> lagi untuk lanjut</li>
  <li>Setelah itu proses instalasi akan dilakukan.</li>
  <li>Jika sudah selesai Klik <b>Finish.</b>
</ol>

<h1> Konfigurasi Git</h1>

Untuk melakukan konfigurasi di Git dapat menggunakan langkah berikut :

<ol>
  <li>Buka Command Prompt atau Git Bash</li>
  <li>Ketikkan <b>$ git config --global user.name "Nama Anda di GitHub"</b></li>
  <li>Ketikkan <b>$ git config --global user.email email@domain.tld</b></li>
  <li>Setelah mengetikkan dua langkah yang diatas, selanjutnya kita akan ketik <b> $ git config --list</b> untuk melihat hasilnya</li>
  <li> Jika sudah maka hasilnya akan seperti ini ![Konfigurasi Git Ku](https://user-images.githubusercontent.com/91443673/135025310-9e09ea02-4f7f-4059-ac21-3dd44029fd5a.png)</li>
</ol>

<h1>Membuat Repository</h1>

Untuk membuat Repository dapat menggunakan langkah berikut :

<ol>
  <li>Login ke halaman https://github.com/</li>
  <li>Setelah itu klik +. Pilih <b>New Repository</b></li>
  <li>Setelah itu masukan <b>Repository name</b>. Kita bisa menambahkan deskripsi, mengatur repository menjadi public atau private, dan lisensi</li>
  <li>Terakhir kita klik <b>Create repository</b></li>
</ol>

<h1>Clone Repository</h1>

Untuk melakukan Clone Repository dapat menggunakan langkah berikut :

<ol>
  <li>Kita buat dulu folder untuk menyimpan Hasil Clone Repository kita</li>
  <li>Setelah itu kita klik kanan pada folder yang kita buat, lalu klik <b>Git Bash Here</b></li>
  <li>Setelah itu kita masuk ke halaman https://github.com, di bagian repository kita pilih <b>Code</b> dan kita salin link HTTPS</li>
  <li> Setelah itu kita copykan link tersebut di <b>Git Bash Here</b> yang sudah kita buka tadi dengan mengetikkan,"git clone (Link HTTPS)"
</ol>

<br>$ git clone https://github.com/rasyidnugroho/01-mppl.git
<br>Cloning into '01-mppl'...
<br>remote: Enumerating objects: 9, done.
<br>remote: Counting objects: 100% (9/9), done.
<br>remote: Compressing objects: 100% (8/8), done.
<br>remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
<br>Receiving objects: 100% (9/9), done.
<br>Resolving deltas: 100% (1/1), done.
