# STRUKTUR SISTEM OPERASI
## **Pendahuluan**

Sebuah sistem yang besar dan kompleks seperti sistem operasi modern harus diatur dengan cara membagi task ke dalam komponen-komponen kecil agar dapat berfungsi dengan baik dan mudah dimodifikasi.

Menurut Silberschatz, et al, ada tiga cara
yaitu:
- Struktur Sederhana.
- Pendekatan Berlapis.
- Kernel Mikro.

1. Struktur Sederhana

> - Banyak sistem yang dimulai dengan sistem
yang lebih kecil, sederhana, dan terbatas.
>
> - Contoh sistem seperti ini adalah MS-DOS,
yang disusun untuk mendukung fungsi yang
banyak pada ruang yang sedikit karena
keterbatasan perangkat keras untuk
menjalankannya.
>
> - Contoh sistem lainnya adalah UNIX, yang terdiri
dari dua bagian yang terpisah, yaitu kernel dan
program sistem. 
>
> - Kernel selanjutnya dibagi dua bagian, yaitu
antarmuka (interface) dan device drivers. 
>
> - Kernel mendukung sistem berkas, penjadwalan
CPU, manajemen memori, dan fungsi sistem
operasi lainnya melalui system calls.

2. Pendekatan Berlapis 

> - Sistem operasi dibagi menjadi sejumlah
lapisan yang masing-masing dibangun di
atas lapisan yang lebih rendah. 
>
> - Lapisan yang lebih rendah menyediakan
layanan untuk lapisan yang lebih tinggi.
>
> - Lapisan yang paling bawah adalah perangkat
keras, dan yang paling tinggi adalah userinterface.
>
> - Sebuah lapisan adalah implementasi dari obyek
abstrak yang merupakan enkapsulasi dari data dan
operasi yang bisa memanipulasi data tersebut.
>
> - Keuntungan utama dengan sistem ini adalah
modularitas. Pendekatan ini mempermudah debug
dan verifikasi sistem. 
>
> - Lapisan pertama bisa di debug tanpa mengganggu
sistem yang lain karena hanya menggunakan
perangkat keras dasar untuk implementasi
fungsinya. 

**Lapisan Sistem Operasi**

> - Perangkat keras
Lebih berhubungan kepada perancang sistem.
>
> - Sistem operasi
Lebih berhubungan kepada programmer.
>
> - Kelengkapan
Lebih berhubungan kepada programer.
>
> - Program aplikasi
Lebih berhubungan kepada pengguna aplikasi
komputer.
---

Gambar Lapisan Sistem Operasi
![](img/Screenshot%202022-09-26%20184453.png)

---
3. Kernel Mikro

> - Fungsi
utama mikrokernel adalah
mendukung fasilitas komunikasi antara program klien dan bermacam-macam layanan yang juga berjalan di user space.
>
> - Komunikasi yang dilakukan secara tidak langsung, didukung oleh sistem message passing, dengan bertukar pesan melalui mikrokernel.
>
> - Metode ini
menyusun
sistem
operasi dengan
mengeluarkan semua komponen yang
kurang essensial dari kernel, dan
mengimplementasikannya sebagai program
sistem dan level pengguna. 
>
> - Hasilnya kernel yang lebih
kecil
>
> - Salah satu
keuntungan mikrokernel adalah ketika
layanan
baru
akan
ditambahkan
k
e user space,
kernel tidak perlu
dimodifikasi. Kalau
pun harus,
perubahan
akan lebih
sedikit. 
>
> - Hasil
sistem
operasinya lebih mudah
untuk
ditempatkan
pada
suatu desain
perangkat keras
k
e
desain lainnya.
>
> - Mikrokernel
juga mendukung
keamanan
reliabilitas
yang lebih, karena kebanyakan layanan
berjalan
sebagai
pengguna
proses. Jika layanan
gagal,
sistem lainnya
tetap terjaga.