# Belajar GitHub (All About GitHub)

## Apa itu Git?
Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.
Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

## Apa itu GitHub?
Github adalah aplikasi berbasis website yang memberikan layanan berupa penyimpanan repository secara gratis. Apa itu repository? repository adalah tempat dimana Anda dapat menyimpan file - file berupa source code. Kalau masih susah membayangkan, coba Anda ingat - ingat, pernah membuat folder di Google Drive lalu Anda isi dengan file - file kerjaan atau mungkin software ? Nah, repository pada Github itu semacam Anda menyimpan file - file di Google Drive tadi.

Github juga merupakan Version Control System (VCS) yang paling populer. Perusahaan - perusahaan besar seperti Facebook, Twitter dan Google saja menggunakan Github untuk berkaloborasi dengan ratusan programmernya untuk mengembangkan aplikasi mereka.

## Apa Fungsi GitHub
Github berfungsi untuk menyimpan repository yang tadi sudah saya jelaskan diatas dan juga sebagai alat kolaborasi dalam pengerjaan suatu project. Begini agar lebih jelas. Anda mendapat project berupa pembuatan website company profile. Untuk mengerjakan project itu, Anda mengajak 1 teman untuk mengerjakan bagian backend-nya (PHP, MySQL dsb). Agar pengerjaan dapat selesai dengan mudah, Anda memutuskan untuk menggunakan Github. Jadi meskipun tidak mengerjakan di tempat yang sama atau bertemu secara langsung, project Anda tetap dapat selesai dan dapat dikerjakan oleh Anda berdua. Itulah yang dimaksud sebagai alat kolaborasi.

Selain itu, kita bisa melakukan beberapa hal ini di Github :
1 Kita bisa memfollow programmer lain, jadi apa yang dilakukan oleh programmer yang Anda follow bisa Anda ketahui.
2 Star, fungsinya sama dengan Bookmark
3 Watch, mengawasi repository tertentu. Sehingga ketika ada perubahan, maka Anda akan mendapat notifikasi
4 Fork, ini mirip copy paste kok. Ketika Anda menemukan source code programmer lain, Anda bisa melakukan fork sehingga keesokan harinya tidak perlu lagi susah - susah mencari source code tersebut. Cukup buka di repository Anda saja.

## langkah-langkah menambahkan project ke GitHub
1. Menambahkan Git kedalam Project
```
git init 
```
 perintah tersebut berfungsi untuk membuat repository. Perintah ```git init``` akan membuat sebuah direktori bernama .git di dalam proyek kita. Direktori ini digunakan Git sebagai database untuk menyimpan perubahan yang kita lakukan.

 2. Menambahkan perubahan dalam direktory kerja kedalam Staging Area
 ```git add
```
fungsi 'git add' Untuk mengubah kondisi file dari modified ke staged. Gunakan "." untuk menambahkan seluruh perubahan yang ada pada direktori.
gunakan `git status` untuk memlihat status repositorynya.

3. menyimpan perubahan pada git (merubah status dari stagged ke commited)
```
git commit -m "Masukkah Komentar"
```
Argumen "-m" untuk menambahkan pesan setiap menyimpan revisi.
cek status git pastikan status telah berubah ke Commited.