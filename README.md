latihan1
Apa Itu GIT ?

GIT adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. GIT dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database GIT tidak hanya berada dalam satu tempat saja.
Cara Install GIT di Windows
Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:
Buka https://gitforwindows.org/ dan download installer GIT untuk Windows.
Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.
Beberapa Perintah Pada GIT
git init, perintah untuk membuat repository local.
git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
git commit, perintah untuk menyimpan perubahan kedalam database git.
git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).
Langkah-Langkah Menggunakan GIT
Klik kanan pada Desktop, Klik “Git Bash Here”

Akan tampil command prompt seperti ini :

Buka Drive yang ingin di pakai “cd /d”

Buat directory “mkdir pemrograman1”

Buka directory Pemrograman1 dengan perintah cd pemrograman1

Buat directory latihan1 dan buka directory latihan1 “mkdir latihan1”

Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md

Jalankan perintah git init untuk menjalankan repository local

Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md

Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"

Buat repository server, isi nama repositorynya semisal : latihan1 ,kemudian klik tombol Creat repository

Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak user.

Mengirim perubahan ke server dengan perintah git push -u origin master

Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut

Buka drive D kemudian klik Pemograman1

Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad

Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihan1"
  
Kemuidan lihat perubahannya pada laman github.com


R Iwan Darmawan
311720879
TI 18 B.1  
