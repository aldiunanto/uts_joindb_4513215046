# JAVA APPLICATION Tutorial (Indonesia)

## Pendahuluan

Aplikasi ini adalah aplikasi yang berdasarkan bahasa pemrograman java, dengan menggunakan java aplication,
atau bisa disebut juga java swing. Disini akan dijelaskan tutorial yang difungsikan untuk melakukan tracking
atau pengambilan data universitas yang telah dibikin di database dengan menggunakan JDBC MySql.

Kira-kira hasil dari tutorial ini akan seperti pada gambar dibawah ini.
![Figure 0.1](images/Gambar1.png)

Untuk penjelasan tutorial dari awal hingga akhir, dapat dilihat dibawah ini:

## Tutorial Aplikasi

Untuk tutorial kali ini akan dibagi menjadi beberapa part dari awal hingga akhir. Semoga dapat dimengerti dan juga aplikasi
dapat dijalankan dengan berhasil dan juga dapat berguna.

## Step 1 (Download Projek & Buat Database)

1. Masuk ke URL github https://github.com/naufaltrix/uts_joindb_4513215046 dan anda akan masuk ke dashboard seperti
gambar dibawah ini.
![Figure 0.1](images/Gambar2.png)

2. Setelah masuk menu dan melihat tampilan diatas, lalu selanjutnya adalah download zip folder pada github di menu kiri dan
bisa dilihat pada gambar dibawah ini.
![Figure 0.1](images/Gambar3.png)

3. Setelah download extract folder zip, lalu masukan dump universitas.sql ke database local phpmyadmin dengan buka terminal lalu
nyalakan xampp untuk localhost server dengan ketik di terminal /opt/lamp/lamp start.
![Figure 0.1](images/Gambar4.png) Dan kalau di windows nyalakan seperti biasa dengan mengkil xampp lalu nayalakan server local.

4. Buka browser lalu ketik pada url : localhost/phpmyadmin dan akan terlihat dashboard pada gambar dibawah ini.
![Figure 0.1](images/Gambar5.png)

5. Setelah buka, buat database baru dengan nama universitas dengan klik menu database seperti gambar dibawah ini.
![Figure 0.1](images/Gambar6.png)

6. Setelah selesai langsung klik tombol create, dan hasilnya akan seperti gambar dibawah ini.
![Figure 0.1](images/Gambar7.png)

7. Setelah semua tercreate, langkah selanjutnya adalah import file dump unversitas.sql didalam folder yang di ekstrak, seperti
pada gambar dibawah ini.
![Figure 0.1](images/Gambar8.png)

8. Setelah di klik untuk di buat database baru maka hasilnya akan seperti pada gambar dibawah ini.
![Figure 0.1](images/Gambar9.png) maka bisa dilihat strukturnya akan seperti pada gambar dibawah ini. ![Figure 0.1](images/Gambar10.png)


9. Selesai

Untuk step pertama telah selesai melakukan download dan juga melakukan ekstrak data serta membuat database pada local server
di Phpmyadmin dengan xampp.

## Step 2 (Menjalankan Program di Netbeans)

Disini akan dijelaskan untuk step 2 yaitu menjalankan projek yang telah didownload dari repository github, untuk kelengkapannya
dapat diikuti step dari awal hingga akhir, dan semoga user dapat mengerti dan juga paham untuk menjalankan aplikasi yang sudah dibuat.

1. Langkah yang pertama adalah buka aplikasi netbeans pada komputer / laptop yang telah disediakan, dan dashboardnya dapat dilihat seperti gambar dibawah ini.
![Figure 0.1](images/Gambar11.png)


2. Buka *File->Open Project* maka akan muncul seperti pada gambar dibawah ini
![Figure 0.1](images/Gambar12.png)

3. Setelah projeknya tampil maka langkah selanjutnya adalah dengan menekan tombol *F6* atau tekan tombol run pada netbeans untuk melakukan runing program, dan hasilnya akan terlihat seperti pada gambar dibawah ini.
![Figure 0.1](images/Gambar13.png)

## Step 3 (Cek Database di Server)

Data pada aplikasi sudah sesuai dengan data pada server dengan masuk ke url http://trina.hol.es/ dan akan terlihat hasilnya seperti pada gambar dibawah ini.
![Figure 0.1](images/Gambar14.png)


# Selesai !!



