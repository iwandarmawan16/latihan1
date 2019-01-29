latihan1

Apa Itu GIT ?
![git1](https://user-images.githubusercontent.com/46879070/51877395-9dc13280-239e-11e9-8b7b-103d165e8e9b.jpg)



GIT adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. GIT dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database GIT tidak hanya berada dalam satu tempat saja.
Cara Install GIT di Windows
Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:
1.Buka https://gitforwindows.org/ dan download installer GIT untuk Windows.
2.Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.
Beberapa Perintah Pada GIT
git init, perintah untuk membuat repository local.
git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
git commit, perintah untuk menyimpan perubahan kedalam database git.
git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).
Langkah-Langkah Menggunakan GIT

1.Klik kanan pada Desktop, Klik “Git Bash Here”
![1](https://user-images.githubusercontent.com/46879070/51877403-a6b20400-239e-11e9-8578-df221eea8541.jpg)


2.Akan tampil command prompt seperti ini :
![2](https://user-images.githubusercontent.com/46879070/51877431-c517ff80-239e-11e9-9866-f544eca74a24.jpg)

3.Buka Drive yang ingin di pakai “cd /d”
![2 1](https://user-images.githubusercontent.com/46879070/51877404-a74a9a80-239e-11e9-86e6-f5996979116f.jpg)


4.Buat directory “mkdir pemrograman1”
![3](https://user-images.githubusercontent.com/46879070/51877451-cf39fe00-239e-11e9-9881-6af9fd481adb.jpg)


5.Buka directory Pemrograman1 dengan perintah cd pemrograman1
![4](https://user-images.githubusercontent.com/46879070/51877443-ccd7a400-239e-11e9-822f-fdade41ffa57.jpg)


6.Buat directory latihan1 dan buka directory latihan1 “mkdir latihan1”
![5](https://user-images.githubusercontent.com/46879070/51877444-cd703a80-239e-11e9-8a01-ce044ef115df.jpg)


7.Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md
![6](https://user-images.githubusercontent.com/46879070/51877445-ce08d100-239e-11e9-9c56-ec7817b6798f.jpg)


8.Jalankan perintah git init untuk menjalankan repository local
![7](https://user-images.githubusercontent.com/46879070/51877446-cea16780-239e-11e9-9d30-0dc20221acc7.jpg)


9.Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md
![8](https://user-images.githubusercontent.com/46879070/51877447-cea16780-239e-11e9-814a-b6e92ecab755.jpg)


10.Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"
![9](https://user-images.githubusercontent.com/46879070/51877464-e4169180-239e-11e9-8ee9-a66b8f22c61e.jpg)


11.Buat repository server, isi nama repositorynya semisal : latihan1 ,kemudian klik tombol Creat repository
![9 1](https://user-images.githubusercontent.com/46879070/51877450-cf39fe00-239e-11e9-9d90-c7d092e1dec2.jpg)



12.Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak user.
![11](https://user-images.githubusercontent.com/46879070/51877477-ebd63600-239e-11e9-822e-2ad489f512e7.jpg)


13.Mengirim perubahan ke server dengan perintah git push -u origin master
![20](https://user-images.githubusercontent.com/46879070/51877495-fc86ac00-239e-11e9-8c19-bd5bf4485000.jpg)


14.Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut
![18](https://user-images.githubusercontent.com/46879070/51877497-001a3300-239f-11e9-92d9-7cd8babb1634.jpg)




15.Buka drive D kemudian klik Pemograman1
![15](https://user-images.githubusercontent.com/46879070/51877508-0ad4c800-239f-11e9-8a84-76527d8c8e24.jpg)





16.Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad
![16](https://user-images.githubusercontent.com/46879070/51877512-0f997c00-239f-11e9-9aec-c47e32547296.jpg)





17.Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihan1"
  ![20](https://user-images.githubusercontent.com/46879070/51877522-1b853e00-239f-11e9-9880-14d6adb9b3e8.jpg)
  ![22](https://user-images.githubusercontent.com/46879070/51877538-2c35b400-239f-11e9-8024-625f8febdc66.jpg)
  ![21](https://user-images.githubusercontent.com/46879070/51877541-2e980e00-239f-11e9-91cc-f118464a5f07.jpg)
  
  
  
18.Kemuidan lihat perubahannya pada laman github.com
![terakhir](https://user-images.githubusercontent.com/46879070/51877553-3b1c6680-239f-11e9-92c6-881b5fb2db40.jpg)





R Iwan Darmawan
311720879
TI 18 B.1  
