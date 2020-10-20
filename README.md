#LatihanVCS
Tugas pertemuan ke 4 Bahasa Pemrograman

Nama	: Bangkit Akbar Anggara
NIM 	: 312010148
Kelas 	: TI.20.B.1
Prodi 	: Teknik Informatika

#Cara Menggunakan Git:

1.Install git terlebih dahulu(www.git-scm.com)
2.Setelah menginstall Git, Silahkan cek untuk melihat versi Git yang anda install dengan mengetik
![Screenshot(1)](Screenshot/Screenshot(1).png)
	
	$ git version

3.Anda bisa melakukan login awal pada Git menggunakan Command Prompt (Windows)
![Screenshot(2)](Screenshot/Screenshot(2).png)

4.Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.
![Screenshot(3)](Screenshot/Screenshot(3).png)

	$ git config --global user.name "UsernameAnda"

5.Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.
![Screenshot(4)](Screenshot/Screenshot(4).png)

	$ git config --global user.email emailanda

6.Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.
![Screenshot(5)](Screenshot/Screenshot(5).png)

	$ git config --list
7.Login ke Github
![Screenshot(6)](Screenshot/Screenshot(6).png)

8.Buat akun terlebih dahulu jika anda baru pertama kali menggunakan Github
![Screenshot(7)](Screenshot/Screenshot(7).png)

9.Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.
![Screenshot(8)](Screenshot/Screenshot(8).png)

10.Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.
![Screenshot(9)](Screenshot/Screenshot(9).png)

11.Setelah berhasil membuat folder pada local disk komputer Anda, buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini.
![Screenshot(10)](Screenshot/Screenshot(10).png)

12.Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut
![Screenshot(11)](Screenshot/Screenshot(11).png)

	$ git init

13.Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini
![Screenshot(12)](Screenshot/Screenshot(12).png)

->Buat file di folder yang sudah dibuat (LatihanVCS). Contohnya, di sini kami membuat file README.md

14.Buka GitBash lalu masukkan perintah berikut
![Screenshot(13)](Screenshot/Screenshot(13).png)

	$ git add README.md

15.Lalu setelah itu ketik perintah berikut
![Screenshot(14)](Screenshot/Screenshot(14).png)

	$ git add .

16.Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit
![Screenshot(15)](Screenshot/Screenshot(15).png)

	$ git commit -m "first commit"

17.Setelah git commit, lalu anda masukan perintah git log
![Screenshot(16)](Screenshot/Screenshot(16).png)

	$ git log

18.Lakukan Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository
![Screenshot(17)](Screenshot/Screenshot(17).png)

	$ git remote add origin https://github.com/AkbarXelion/LatihanVCS.git

19.Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub
![Screenshot(18)](Screenshot/Screenshot(18).png)

	$ git push -u origin main

->Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub.

20.Selesai anda sudah berhasil menginstall git juga menggunakan git dan github
![Screenshot(19)](Screenshot/Screenshot(19).png)