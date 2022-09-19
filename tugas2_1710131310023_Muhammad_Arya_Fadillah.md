# 1. KOMPONEN SISTEM OPERASI LINUX
---

Berikut adalah Struktur Sistem Operasi Linux :


1. Kernel

   Kernel adalah inti dari sistem linux, yang mengotrol hardware dan membentuk berbagai fungsi berasas rendah. Fungsi-fungsi yang dilakukan oleh kernel, antara lain: pelayanan tanggal (system call) dan jam sistem, manajemen file dan penanganan sekuriti, pelayanan operasi input/output, menejemen dan penjadwalan proses, menejemen memory, melakukan kegiatan akuntansi sistem, melakukan penanganan kesalahan dan interupsi (interupt).

2. Shell

   Shell adalah penterjemah (command line interpreter). Pada Linux disebut sebagai terminal. Perangkat lunak inilah yang menjadi jembatan antara user dengan sistem linux. User cukup memberikan perintah dan shell yang akan menanganinya. Perintah-perintah shell linux dapat berupa:
   - perintah built-in. Perintah yang merupakan bagian internal dari shell.
   - perintah eksternal. perintah yang bukan bagian internal dari shell (dapat berupa utilitas atau program aplikasi)
Shell, baik di linux maupun di UNIX digunakan untuk interaksi antara user dengan komputernya termasuk juga dalam mengontrol session UNIX dan pemrograman (scripting). UNIX shell menediakan sekumpulan instruksi khusus yang dapat digunakan untuk membuat program shell script. Ada beberapa jenis shell yang umum ditemukan dalam distro Linux, yakni : Bash dan tcsh.

3. Utilitas

   utilitas (utility) adalah program yang telah disediakan sistem linux untuk melakukan tugas tertentu. jumlahnya banyak denagn fungsi yang beraneka ragam. Beberapa kelompok utilitas dilihat dari fungsinya :
   a. utilitas manajemen file dan direktori, utilitas kelompok ini sangat bermanfaat untuk melakukan tugas yang berhubungan dengan file dan direktori seperti, untuk membuat direktori dan menghapus file. Utilitas penyunting file. Utilitas ini sering disebut editor, sangat bermanfaat untuk membuat program atau menyimpan informasi tertentu ke dalam file;
   b. Utilitas penunjang komunikasi dan jaringan. Utilitas ini bermanfaat untuk melakukan komunikasi antar user. Bahkan user dapat mentransfer data antar sistem;
   c. Utilitas administrasi sistem. Utilitas ini berguna bagi administrator sistem untuk mengelola sistem. Misalnya untuk menciptakan nama user baru dan mendaftarkan printer pada sistem;
   d. Utilitas pemrograman C. Utilitas ini berguna untuk membuat program aplikasi dengan bahasa C;
   e. Utilitas penganalisi unjuk kerja sistem. Utilitas ini dapat digunakan oleh administratos sistem untuk mengananlisis kerja sistem, sehingga dapat melakukan penyetingan guna meningkatkan unjuk kerja;
   f. Utilitas untuk keperluan backup dan restore. Utilitas ini bermanfaat untuk menyalin atau memindahkan data atau program ke media eksternal seperti magnetic tape,atau sebaliknya.

4. Program Aplikasi

   Program aplikasi (aplication software) adalah program-program yang dibuat oleh user, untuk memenuhi kebutuhuannya sendiri. Program-program ini dapat dibuat dengan menggunakan sejumlah utilitas, perintah built-in milik shell, atau dibangun dengan bahasa perograman seperti C, COBOL,atau Phyton dan berbagai development tool seperti oracle dan Informix. Bisa juga berupa program pake yang dibeli dari pemasok perangkat lunak.
---

- **Membuat Folder melalui Terminal Linux**

Ada berbagai cara untuk membuat folder pada sistem operasi Linux, salah satunya dengan menggunakan terminal yang telah disediakan oleh OS tersebut, yakni dengan cara :

1. Buka terminal dengan tekan ctrl+alt+t bersamaan

Akan keluar tampilan terminal linux

![Screenshot from 2022-09-18 13-09-50](https://user-images.githubusercontent.com/112482818/190918276-d12f1221-de04-4517-b13a-aa80db0213d3.png)


2. Ketikkan ~$ ls -l , untuk menampilkan directory

![Screenshot from 2022-09-18 13-10-22](https://user-images.githubusercontent.com/112482818/190918365-f3b5f9fb-e9e9-418a-b526-210986ca37e3.png)


3. Selanjutnya, ketikkan ~$ cd Downloads

Untuk directory seperti ( Dekstop, Document, Downloads, dll. Kita dapat memilih sendiri dimana akan menyimpan folder yang ingin dibuat, disini saya menggunakan directory Downloads )

![Screenshot from 2022-09-18 13-11-42](https://user-images.githubusercontent.com/112482818/190918606-cd9d3859-5c3c-439f-9e72-cf879650ca45.png)


4. Ketikkan ~$ mkdir ebook 

ebook adalah nama folder yang saya buat, disini kita dapat membuat nama folder sendiri dengan mengetikkan nama folder setelah mkdir

![Screenshot from 2022-09-18 13-12-59](https://user-images.githubusercontent.com/112482818/190918858-17efdd14-7cfa-4be6-aacb-1c8f3ae01511.png)


5. Setelah itu lakukan pengecekkan apakah folder telah berhasil dibuat dengan cara mengetikkan ~$ ls ebook

apabila berhasil, maka akan tampil seperti dibawah ini

![Screenshot from 2022-09-18 13-13-11](https://user-images.githubusercontent.com/112482818/190918965-276f4bab-7040-47c0-bef6-c2c4b646e14d.png)


6. Folder telah berhasil dibuat

![Screenshot from 2022-09-19 06-56-23](https://user-images.githubusercontent.com/112482818/190919051-7f8072da-f7a6-406f-9370-09be17b7ad5e.png)


---

- **Membuat Document Text**

1. Klik kanan pada dekstop linux, pilih Create New Document, pilih Empty Document, maka akan tampil seperti dibawah ini

Silahkan isikan nama file sesuai keinginan sendiri

![Screenshot from 2022-09-19 06-51-36](https://user-images.githubusercontent.com/112482818/190919217-4621b0df-0e94-4c11-9dd3-2f38acb5229e.png)


2. Setelah itu, buka file text document tersebut

![Screenshot from 2022-09-19 06-52-29](https://user-images.githubusercontent.com/112482818/190919306-896eac67-5b1a-4578-8cd4-364e4482519c.png)


3. Lalu, isikan file text document tersebut seusai keinginan

Disana saya mengisi document tersebut dengan text FILETEXT "Hello World", simpan file dengan klik save.

![Screenshot from 2022-09-19 06-53-13](https://user-images.githubusercontent.com/112482818/190919354-1ab298b9-ddf7-4e80-9931-4f054a5fa0be.png)


---

- **Cara PING jaringan melalui Terminal Linux**

1. Buka Terminal

![Screenshot from 2022-09-19 07-00-18](https://user-images.githubusercontent.com/112482818/190919574-d2e18717-4737-4838-82de-133fb5b01cc4.png)


2. Ketikkan ~$ ping www.google.com

Untuk www.google.com dapat ganti dengan IP Adress/Website

![Screenshot from 2022-09-19 07-00-35](https://user-images.githubusercontent.com/112482818/190919744-284989aa-d0ea-4350-80e4-01cfd6d24b12.png)


3. Maka akan tampil data PING dari tujuan kita

![Screenshot from 2022-09-19 07-01-07](https://user-images.githubusercontent.com/112482818/190919792-cd71666c-b2df-48c2-a947-df5d691dbd17.png)


---




